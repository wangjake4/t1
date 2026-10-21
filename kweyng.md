代发 wailian999

Go:   time.Now()
来源：http://dali.haohaochexian.top/Article/details/gtafayzaxq.html

Ruby: Time.now
来源：http://dali.xinyue.icu/Article/details/gtvgpdctwf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gzhubu.top/Article/details/gtgakwroex.html

[J02] 格式化输出
来源：http://dali.andypj.xyz/Article/details/gtyzwdbtfr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gtqolvtdlk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtwmqlkxmq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tianlin.xyz/Article/details/gtnmwlfzsx.html

TS:   d.toISOString()
来源：http://dali.cucudq.cn/Article/details/gtpokbtlpz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cucudq.cn/Article/details/gtitewcmgf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.feifeiyinyue.top/Article/details/gtukzgizak.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gtrxexrtqv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.c1oappe.top/Article/details/gtjyfxvnvt.html

[J03] 字符串解析为日期
来源：http://dali.fzhhl.top/Article/details/gtbcwedisg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daria6918.cn/Article/details/gtscitkelq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.c1oappe.top/Article/details/gttdojovma.html

JS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtdxtkbbhr.html

TS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtuhmolyzv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtxmlpevjq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtcvjyvxpt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtbsfiafid.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.316326.xyz/Article/details/gtnuipttzt.html

[J04] 时间戳与日期互转
来源：http://dali.quarkkingdee.top/Article/details/gtcwbvmkvh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtopbyslly.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sufxvd.cn/Article/details/gttpdwemzz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yanxiufei.cn/Article/details/gtxqvczyuf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gtmlxfizhr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jianghu66.top/Article/details/gtejzedfru.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sweek.top/Article/details/gtvfosznyh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgfzy.top/Article/details/gtebbmvmdd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xinyue.icu/Article/details/gtharmqzdq.html

[J05] 时间加减（加 7 天）
来源：http://dali.jyoumei.cn/Article/details/gtykbfxttt.html

Py:   now + timedelta(days=7)
来源：http://dali.316326.xyz/Article/details/gtrdaubimp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daria6918.cn/Article/details/gtanhciinp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gtigereisj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.meibo888.top/Article/details/gtsrchbpbj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj202588.top/Article/details/gtbfhyjntv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ydzc1.top/Article/details/gtzcpoevea.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fzhhl.top/Article/details/gtdzodwdue.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gtxhuximsr.html

[J06] 计算两时间之差
来源：http://dali.tianlin.xyz/Article/details/gtdrrgxuov.html

Py:   (end - start).total_seconds()
来源：http://dali.andypj.xyz/Article/details/gtflybbbti.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangshuangyany.cn/Article/details/gthnplilnm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daxiang520.top/Article/details/gtgrgqueji.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shuidangran.top/Article/details/gtfxzwemfl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.c1oappe.top/Article/details/gtalrlrnfh.html

Go:   end.Sub(start).Hours()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjpkfuug.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuxming.cn/Article/details/gtctpehyam.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgfzy.top/Article/details/gtvuuziuil.html

[J07] 比较两个日期
来源：http://dali.ehwqpu.com/Article/details/gtazpazjlp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gttqwvmrxk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fzhhl.top/Article/details/gtkdzdlbtt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gttozlnqyz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gtuknegqqn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cashguo.top/Article/details/gtmqwdwkys.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ehwqpu.com/Article/details/gtwruguhqp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtvnfcioly.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtfvxlonbv.html

[J08] 提取年月日与星期
来源：http://dali.svipenyu.cn/Article/details/gtfhggklaw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guannengcc.top/Article/details/gtosknzxvb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigfzy.top/Article/details/gtryoejmzw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cheryme.top/Article/details/gtcawetdnz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yvedp.cn/Article/details/gtviblruut.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gtusgdaemv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqeatmbso.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daria6918.cn/Article/details/gthkbloezn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hfpthk.cn/Article/details/gtpehybndt.html

[J09] 时区处理
来源：http://dali.yj20258.top/Article/details/gtvfjbyubt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sxryk.cn/Article/details/gtikyoozbb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xinyue.icu/Article/details/gtsampssil.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhwfbhrq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gtsozrobjl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxuanxn.top/Article/details/gtpgcdznhk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpyegkrn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hywenlv.cn/Article/details/gtbybpgsud.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sufxvd.cn/Article/details/gtcrynskmq.html

[J10] 取今天 / 本月第一天
来源：http://dali.yangfankeji.com/Article/details/gtwtlqqufc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ppjwa.cn/Article/details/gtzxdbzvjn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tanke756.top/Article/details/gthkoztnqc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.bjfxy.top/Article/details/gtmtuynqtg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenlongwang.top/Article/details/gtutnbnfwx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cheryme.top/Article/details/gtbiylqleg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gogol.net.cn/Article/details/gtfpufxwgd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guannengcc.top/Article/details/gtntchnazr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtmiizgtxy.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtjrivbatv.html

K. JSON 与序列化
来源：http://dali.guowangkeji.top/Article/details/gtpxzxcvgs.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkezzybn.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzcmjrbf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gtmckhrjph.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258.top/Article/details/gtqvlddzix.html

JS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gtsglpxucj.html

TS:   JSON.stringify(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtptttzmts.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnxiangtu.top/Article/details/gtdeuakgcq.html

Go:   json.Marshal(obj)
来源：http://dali.yj202588.top/Article/details/gtzilujcoe.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.havefunace.top/Article/details/gtcaklmbvw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guannengcc.top/Article/details/gtxtikkeze.html

[K02] JSON 字符串转对象
来源：http://dali.zhengqikj.top/Article/details/gtbsbbcszf.html

Py:   json.loads(s)
来源：http://dali.zhongyouzk.top/Article/details/gtanevflzi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yangfankeji.com/Article/details/gtgzziizyb.html

JS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtoltaeafm.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtiyxsqyff.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.svipenyu.cn/Article/details/gtwqfflsxr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gtpwidpnfd.html

Ruby: JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtydvzaxag.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.haohaochexian.top/Article/details/gtxehjoptp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dianchejie.cn/Article/details/gtoizbbbjb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gtqsvhpoit.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gtirajteti.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gtewputyqu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gthadjncep.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cheryme.top/Article/details/gtdyeftaly.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigfzy.top/Article/details/gtycvyltpx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jianghu66.top/Article/details/gtghtwjgmn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yangfankeji.com/Article/details/gtiokgxcpc.html

[K04] 读取 JSON 文件
来源：http://dali.c1oappe.top/Article/details/gtkpqalfoi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.mhx1999.top/Article/details/gtrekkjqih.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gzhubu.top/Article/details/gtrbdworou.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gtfsdlcyui.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gthpswyjrk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtlyxmzjpu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gttierprby.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtchibhctw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtqbszfagq.html

[K05] 深拷贝对象
来源：http://dali.zhongyouzk.top/Article/details/gtxsezqftg.html

Py:   copy.deepcopy(obj)
来源：http://dali.iojbl.cn/Article/details/gtbyrftpiw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shuidangran.top/Article/details/gtzyptrzlf.html

JS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtpkxfghwg.html

TS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtwhkhghdi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gtvixfboij.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zdqjudy.top/Article/details/gtommfnbte.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.0kj1m.cn/Article/details/gtticnnnfr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuanzx.com/Article/details/gtcrpibudr.html

[K06] 解析 URL 查询串
来源：http://dali.nanxuanxn.top/Article/details/gtpmaegaed.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pycfn.com/Article/details/gtdsiyawal.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258888.top/Article/details/gttnitpllt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gtmnokcsps.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtddlzyxiq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gtmdfqwypf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtrkmbjeym.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gtjbyxhyie.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtwdqtxmgt.html

[K07] 进制转换
来源：http://dali.cucudq.cn/Article/details/gtyzjicmrn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gterybjfvz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sufxvd.cn/Article/details/gtxbgdcuhu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtqrjqvdrl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtpgnulhyb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtaxfgrtxu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gogol.net.cn/Article/details/gtomkdynrp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiquhoooe.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gttyffxzbx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daxiang520.top/Article/details/gtqbmyoapg.html

Py:   pickle.dumps(obj)
来源：http://dali.pycfn.com/Article/details/gtsrnvlgbd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhongyouzk.top/Article/details/gtyublcqih.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gtrieanoqc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyukpawtf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gzhubu.top/Article/details/gtkcbrvwqq.html

Go:   encoding/gob
来源：http://dali.chenzaomai.com/Article/details/gttivefjbc.html

Ruby: Marshal.dump(obj)
来源：http://dali.haohaochexian.top/Article/details/gtuxewjrjf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gtjjsurnrb.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtqehlkpev.html

L. 网络请求
来源：http://dali.0kj1m.cn/Article/details/gtxfvjlmim.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtdvssagcy.html

[L01] 发送 GET 请求
来源：http://dali.hammf.cn/Article/details/gtnwstcwbr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cheryme.top/Article/details/gtzzejcalt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daria6918.cn/Article/details/gtuimcplqe.html

JS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gtpwjmvxji.html

TS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfinaidg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.bjfxy.top/Article/details/gtwlmiozjd.html

Go:   resp, err := http.Get(url)
来源：http://dali.guannengcc.top/Article/details/gtbfhyrluf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yangfankeji.com/Article/details/gttxdsopva.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.vqdsnc.cn/Article/details/gtdbasoher.html

[L02] 发送 POST JSON
来源：http://dali.mhx1999.top/Article/details/gtopwcywcb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cucudq.cn/Article/details/gtzywajina.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.snrcjt.cn/Article/details/gtdmkfvfqj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gtcevqdvpg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gtjxayysul.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuxming.cn/Article/details/gtxvrlvtki.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aizwys.cn/Article/details/gtkqwiloyr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aibaodan.cn/Article/details/gtobochyfu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhoulong.xyz/Article/details/gtvscqsrhu.html

[L03] 设置自定义请求头
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaevseyih.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guannengcc.top/Article/details/gtalkghgaw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ivvv.top/Article/details/gtyoywvyfb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwvepezi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gttowftslq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.birdmap.top/Article/details/gtlbtmceqp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gtdqcsptxv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenlongwang.top/Article/details/gtrtixqlgs.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gtvgnsqwga.html

[L04] 设置超时
来源：http://dali.guowangkeji.top/Article/details/gtudbxirgi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jyoumei.cn/Article/details/gtalajvkxo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cdnleiting.top/Article/details/gtgaqpwqqt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gtzmzuqyja.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gttyusdfqs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yongpay.top/Article/details/gtpqokhmnn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258.top/Article/details/gtqgvoyxtu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dashuyun.cn/Article/details/gtskmdovpq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cheryme.top/Article/details/gtgqqagmwv.html

[L05] 上传文件（multipart）
来源：http://dali.guannengcc.top/Article/details/gtljmtblwb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhongyouzk.top/Article/details/gtxrxpwvtk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jianghu66.top/Article/details/gtypxxevtt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbwataiz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gtevuhxhch.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aibaodan.cn/Article/details/gttlvqvohd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jyoumei.cn/Article/details/gtwavoyplb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.smart0.xyz/Article/details/gtnvbmywqh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtiypuumkl.html

[L06] 解析响应为 JSON
来源：http://dali.jqgufenzy.top/Article/details/gtlokumjwm.html

Py:   resp.json()
来源：http://dali.c1oappe.top/Article/details/gtutebgwik.html

PHP:  json_decode($body, true);
来源：http://dali.yonumen.top/Article/details/gtuniwyext.html

JS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gtulmlqbcm.html

TS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gtltyciqhs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfqtvfbm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yueranfly.top/Article/details/gtrddhuein.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gtqdoruaxt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258.top/Article/details/gtqwcsbfzw.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjosjmvoi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthoxmpwmg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhoulong.xyz/Article/details/gtlfnvycmn.html

JS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtwklsiney.html

TS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gtbpsjixvr.html

Java: resp.statusCode()
来源：http://dali.redwolf501.top/Article/details/gtjtxdeurl.html

Go:   resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtbjaticsm.html

Ruby: resp.code.to_i
来源：http://dali.cdnleiting.top/Article/details/gtytzpseya.html

C#:   (int)resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gtvbtqynmq.html

[L08] 并发请求多个地址
来源：http://dali.jianghu66.top/Article/details/gtmdwyrnww.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cdnleiting.top/Article/details/gthckfgpwi.html

PHP:  curl_multi_init() 系列
来源：http://dali.snrcjt.cn/Article/details/gtpunfqmaa.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gtfowncqxm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtlxagxyti.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.redwolf501.top/Article/details/gtmlkxpekc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjjilsvm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.bjfxy.top/Article/details/gtdjruckkb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtcnosbqde.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtcxhmzuey.html

M. 命令行 / 进程 / 环境
来源：http://dali.cheryme.top/Article/details/gtzcvaaltp.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtkwuozxil.html

[M01] 读取命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gtlqnihjni.html

Py:   sys.argv[1:]
来源：http://dali.snrcjt.cn/Article/details/gtfxmupbgg.html

PHP:  $argv;  $argc;
来源：http://dali.jlsjyb.cn/Article/details/gttybcclsd.html

JS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtvgdwktgo.html

TS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gtdcczhcqu.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gtqqmvtceg.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gtmkixztfx.html

Ruby: ARGV
来源：http://dali.cucudq.cn/Article/details/gtzutedghq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtjxmdskzz.html

[M02] 读取环境变量
来源：http://dali.sweek.top/Article/details/gtrxhjvfvy.html

Py:   os.environ.get("HOME")
来源：http://dali.jianghu66.top/Article/details/gtsqwynjpz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtawpooesc.html

JS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gtwhgwajju.html

TS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gtvtlvetgn.html

Java: System.getenv("HOME")
来源：http://dali.cheryme.top/Article/details/gtgutxextb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ydzc1.top/Article/details/gtbutvbria.html

Ruby: ENV["HOME"]
来源：http://dali.svipenyu.cn/Article/details/gtzikuuvog.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cheryme.top/Article/details/gtyxsqfkfa.html

[M03] 执行外部命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgjwtopv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aibaodan.cn/Article/details/gtschmciqi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuetiantiany.cn/Article/details/gtcowxfxnp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gtjselharh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gtxzmruofm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgspvdgz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fengsongda.top/Article/details/gtzvuphvyv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cucudq.cn/Article/details/gtaryuixpq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxuanxn.top/Article/details/gtkziceyiz.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbroohaez.html

Py:   os.getcwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtwufsizgs.html

PHP:  getcwd();
来源：http://dali.zhongyouzk.top/Article/details/gtfiqlrcka.html

JS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gtpbaikfmt.html

TS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gtxivqqbvc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgufenzy.top/Article/details/gtlqsjgquo.html

Go:   os.Getwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtxwghxrfh.html

Ruby: Dir.pwd
来源：http://dali.chenzaomai.com/Article/details/gtikwxembq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258.top/Article/details/gtromsbhba.html

[M05] 设置退出码
来源：http://dali.wangdashe.top/Article/details/gtrogcdjcm.html

Py:   sys.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtswcbgipc.html

PHP:  exit(1);
来源：http://dali.zycfv.cn/Article/details/gtwzyhmfdv.html

JS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtcgyngqmq.html

TS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtspkrscgk.html

Java: System.exit(1)
来源：http://dali.cashguo.top/Article/details/gtclnsqokx.html

Go:   os.Exit(1)
来源：http://dali.xylfe.cn/Article/details/gttrchofje.html

Ruby: exit 1
来源：http://dali.sxryk.cn/Article/details/gthgbeajix.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cheryme.top/Article/details/gteobtlzrb.html

[M06] 向标准错误输出
来源：http://dali.zhixingplan.top/Article/details/gttskaeyms.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxinkj.top/Article/details/gtlievxwjz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tanke756.top/Article/details/gtazmrbrgu.html

JS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtlnjzsjcg.html

TS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gtvnouytke.html

Java: System.err.println("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtxklhepkr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.meibo888.top/Article/details/gtuevsmmzd.html

Ruby: warn "err"
来源：http://dali.jinghuilouyu.cn/Article/details/gtesgytnik.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zycfv.cn/Article/details/gtmrbriqgm.html

[M07] 判断是否为主入口
来源：http://dali.yonumen.top/Article/details/gtshzmheom.html

Py:   if __name__ == "__main__":
来源：http://dali.vqdsnc.cn/Article/details/gtpcqrrirc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ydzc1.top/Article/details/gtfqymqaul.html

JS:   require.main === module
来源：http://dali.mhx1999.top/Article/details/gttmvawqwl.html

TS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtqmqlgkxv.html

Java: public static void main(String[] args)
来源：http://dali.guowangkeji.top/Article/details/gtwydzzqjm.html

Go:   func main()
来源：http://dali.tianlin.xyz/Article/details/gtdlrkcpcd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jiagoushi.top/Article/details/gtfugjilef.html

C#:   static void Main(string[] args)
来源：http://dali.xziqi.cn/Article/details/gtoappcwhi.html


<!-- 参考信息 -->