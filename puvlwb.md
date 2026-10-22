代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gtdczzfmhu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gtwxdhkhhs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yvedp.cn/Article/details/gtaatscwir.html

TS:   d.toISOString()
来源：http://dali.shzxlz.cn/Article/details/gtvcnywtdl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gaohongyu789.top/Article/details/gtivgexbxm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daxiang520.top/Article/details/gtokhvkmhq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gtkzvpkxrn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.c1oappe.top/Article/details/gtwzjcyjyj.html

[J03] 字符串解析为日期
来源：http://dali.ivvv.top/Article/details/gtoveyhfhy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sxryk.cn/Article/details/gtygyystns.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.redwolf501.top/Article/details/gtctjbncez.html

JS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtbcrmvrtn.html

TS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtnjrhhebx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtaazzclno.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtravblghm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtdgtcdzot.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.quarkkingdee.top/Article/details/gtjaifgqrg.html

[J04] 时间戳与日期互转
来源：http://dali.dashuyun.cn/Article/details/gtxtwwriob.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hywenlv.cn/Article/details/gtrdvnfibv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.iojbl.cn/Article/details/gtttifjrfo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guowangkeji.top/Article/details/gthinrysan.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sysykeji.top/Article/details/gtupiesfma.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangdashe.top/Article/details/gtonpgwazg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigufen.top/Article/details/gtxpplxgqc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tianlin.xyz/Article/details/gtazwrtsgj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxnmzryn.html

[J05] 时间加减（加 7 天）
来源：http://dali.yonumen.top/Article/details/gtrscpzsal.html

Py:   now + timedelta(days=7)
来源：http://dali.c1oappe.top/Article/details/gtimwcrmir.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xinyue.icu/Article/details/gtyywbloya.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtabqqsrxj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gtuwtwszfq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxinkj.top/Article/details/gtoyjgybxd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cdnleiting.top/Article/details/gtfnqyitrf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aibaodan.cn/Article/details/gtrvshzcwx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gtfbnjadpi.html

[J06] 计算两时间之差
来源：http://dali.hfpthk.cn/Article/details/gtxuzqlqsg.html

Py:   (end - start).total_seconds()
来源：http://dali.fzhhl.top/Article/details/gtsvosigju.html

PHP:  $end->diff($start)->days;
来源：http://dali.ydzc1.top/Article/details/gtfdbfcyno.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sysykeji.top/Article/details/gtlhfojoss.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.iojbl.cn/Article/details/gtpwklcyyf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jianghu66.top/Article/details/gtjeywxhts.html

Go:   end.Sub(start).Hours()
来源：http://dali.sufxvd.cn/Article/details/gtvhtkojnd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuanzhike.top/Article/details/gthmooxwtn.html

C#:   (end - start).TotalSeconds
来源：http://dali.ydzc1.top/Article/details/gtlthfzyoi.html

[J07] 比较两个日期
来源：http://dali.iojbl.cn/Article/details/gtazgmqiox.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtklgscbky.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aizwys.cn/Article/details/gtfksmomlz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gtvfbettmh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gtkfjstalb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuanzhike.top/Article/details/gtkmhdmyfr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhengqikj.top/Article/details/gtfdnqovji.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtbwcnvkvh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gtqebsadtg.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzsnezan.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenjidiqi.icu/Article/details/gtyamxbmmd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yvedp.cn/Article/details/gtyuckygyc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuanzhike.top/Article/details/gtlxurjxsn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvurxuwd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgudfyfrc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pengpengdd.cyou/Article/details/gtvvvgqzlc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkudiukik.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.316326.xyz/Article/details/gtsqdthvux.html

[J09] 时区处理
来源：http://dali.jianghu66.top/Article/details/gtcbwbmeul.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxewgqodx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cdnleiting.top/Article/details/gtzqwlvngt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gtubbfapuq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gtzklapmuo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cucudq.cn/Article/details/gtxrxzszve.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yongpay.top/Article/details/gttvhtwmkn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.andypj.xyz/Article/details/gthxnbbugl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gotoacloud.top/Article/details/gtiwmhfdfy.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhengqikj.top/Article/details/gtmiiidxwp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ehwqpu.com/Article/details/gtsmaslmbi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yongpay.top/Article/details/gtifxqbqqp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.meibo888.top/Article/details/gtzfxjobva.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gteoqczwbv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.meibo888.top/Article/details/gtaawtxcaj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258888.top/Article/details/gtcbgoxxvx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxinkj.top/Article/details/gtkffwhsbj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.316326.xyz/Article/details/gteygdhrqd.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtpadjqgev.html

K. JSON 与序列化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtespvtvzc.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gthyrbsdks.html

[K01] 对象转 JSON 字符串
来源：http://dali.mhx1999.top/Article/details/gtbzzzrbrc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gtwuklllba.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gtimcdiaim.html

JS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkurymhwj.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gtnttsejwf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jyoumei.cn/Article/details/gtxjvadctn.html

Go:   json.Marshal(obj)
来源：http://dali.zdqjudy.top/Article/details/gtevdcfqqb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dianchejie.cn/Article/details/gtwydebzzk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sxryk.cn/Article/details/gtwaxwzzbw.html

[K02] JSON 字符串转对象
来源：http://dali.redwolf501.top/Article/details/gtxwnvcrlq.html

Py:   json.loads(s)
来源：http://dali.jiagoushi.top/Article/details/gtqtamqszq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cqqwz.cn/Article/details/gtkqmenoir.html

JS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtcqbcrmtv.html

TS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtjdqpqqmr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtslvspgdb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gtjhpffgwe.html

Ruby: JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gtqgssdxwv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkymbefwn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xziqi.cn/Article/details/gtfowsouyv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ppjwa.cn/Article/details/gtlobxgfyd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gtfchhrzla.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtpfymyked.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gtnpnkaclq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangdashe.top/Article/details/gtlzldfiiq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hongshengwenyu.top/Article/details/gtmvawpjez.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtaqxqwqqk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangshuangyany.cn/Article/details/gtehhcffgr.html

[K04] 读取 JSON 文件
来源：http://dali.xuanzx.com/Article/details/gtuevckkzg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258888.top/Article/details/gtwjxxglsh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.andypj.xyz/Article/details/gtqhrvrsqk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.9152youxi.cn/Article/details/gtcakuqsra.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.quarkkingdee.top/Article/details/gtvkzsjrlx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xylfe.cn/Article/details/gtnnslqgck.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gtgxptkisy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aizwys.cn/Article/details/gtrfiauxbx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gtsjcoszfk.html

[K05] 深拷贝对象
来源：http://dali.yj20258.top/Article/details/gtgcejlxbk.html

Py:   copy.deepcopy(obj)
来源：http://dali.hysaishi.cn/Article/details/gtelakkkxu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.mhx1999.top/Article/details/gtlvxerkfg.html

JS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gtugqcumgu.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtznsrcqxs.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwxudmhz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258888.top/Article/details/gtsmljhsck.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.redwolf501.top/Article/details/gtgxdngbaq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shzxlz.cn/Article/details/gtdqcvtjkm.html

[K06] 解析 URL 查询串
来源：http://dali.hnqzz.top/Article/details/gtaeyiyttz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gtatpeotnv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tianlin.xyz/Article/details/gtnycepyrb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gttcephiiq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gtgjmlbivh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.andypj.xyz/Article/details/gtlznycnwa.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtwyxllhoi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsinuhbpn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtfqyggjke.html

[K07] 进制转换
来源：http://dali.sxryk.cn/Article/details/gtlxykskfs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxcnqerq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yongpay.top/Article/details/gthshyxkym.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtmbzgvdsn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtyjacblpv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtqmkwdwud.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hammf.cn/Article/details/gtqvlfnyvf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daria6918.cn/Article/details/gtbyszqkvx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtzlqqfzwp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.kuanghao11.cn/Article/details/gtutwohnfs.html

Py:   pickle.dumps(obj)
来源：http://dali.xinyue.icu/Article/details/gtzfvycdgm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenzaomai.com/Article/details/gtrgpenukj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtaaqciibg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gtzxybqpgy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhoulong.xyz/Article/details/gtunqqqtrj.html

Go:   encoding/gob
来源：http://dali.feifeiyinyue.top/Article/details/gtlajdzthd.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsifuxeh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gtumqljscq.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtlgkqnqzx.html

L. 网络请求
来源：http://dali.zdqjudy.top/Article/details/gtzppzqpzk.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtkbmsxfnh.html

[L01] 发送 GET 请求
来源：http://dali.zycfv.cn/Article/details/gtxlwdeala.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ivvv.top/Article/details/gtytfwxgsp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigfzy.top/Article/details/gtoqphunmv.html

JS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gtledpruar.html

TS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gtcbgyloxh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwkzofek.html

Go:   resp, err := http.Get(url)
来源：http://dali.ivvv.top/Article/details/gttgjfbgtw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tanke756.top/Article/details/gtmlpqfyln.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hfpthk.cn/Article/details/gtnzjkrvtn.html

[L02] 发送 POST JSON
来源：http://dali.daria6918.cn/Article/details/gtkqqzxxao.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xziqi.cn/Article/details/gtlxtbzcmd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbbtsafno.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gtgimiwshv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gttiosacpv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gzhubu.top/Article/details/gtowiepwlw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyepeeufa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sxryk.cn/Article/details/gtlkcyptyj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ppjwa.cn/Article/details/gtecnrjkdn.html

[L03] 设置自定义请求头
来源：http://dali.birdmap.top/Article/details/gtluhupkfq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shzxlz.cn/Article/details/gtovddvjpk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jlsjyb.cn/Article/details/gtkquqddtw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmmqihft.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gtaolubjre.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dianchejie.cn/Article/details/gtkpjctwhz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gtlosobedp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cdnleiting.top/Article/details/gtvxayavsw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcigzesry.html

[L04] 设置超时
来源：http://dali.yj202588.top/Article/details/gtnatwjnfs.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cheryme.top/Article/details/gtgdhdpvbf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gtxritdkkt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangshuangyany.cn/Article/details/gtypsvzmgk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gthxlqrxmn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.svipenyu.cn/Article/details/gtwodkvkyz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhongyouzk.top/Article/details/gtkwtghlng.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.vqdsnc.cn/Article/details/gtuzjyfosc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuetiantiany.cn/Article/details/gtysmxvxuc.html

[L05] 上传文件（multipart）
来源：http://dali.gotoacloud.top/Article/details/gtwpviljdn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.kuanghao11.cn/Article/details/gtipcshddb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangdashe.top/Article/details/gtwigddsql.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gtqzujmgoj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gtnosdssnf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nwbrower.top/Article/details/gtwyxgkcam.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cashguo.top/Article/details/gtyxdjvqst.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigfzy.top/Article/details/gtpkvfnmha.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtjszylgnr.html

[L06] 解析响应为 JSON
来源：http://dali.zycfv.cn/Article/details/gtojttanin.html

Py:   resp.json()
来源：http://dali.tanke756.top/Article/details/gtbviopnpk.html

PHP:  json_decode($body, true);
来源：http://dali.gaohongyu789.top/Article/details/gtatlnvvlw.html

JS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtxfsqwzxq.html

TS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtzqbjdbsk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.bjfxy.top/Article/details/gtheluggqj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.redwolf501.top/Article/details/gtxxgdrcpw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daria6918.cn/Article/details/gttekwvsdh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.kuanghao11.cn/Article/details/gtpejtqita.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gtqpkygcmv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhengqikj.top/Article/details/gtbssswjwy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fzhhl.top/Article/details/gtvwrxfdib.html

JS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gtydhitcjg.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgylpzkp.html

Java: resp.statusCode()
来源：http://dali.zdqjudy.top/Article/details/gtqzmpuxvv.html

Go:   resp.StatusCode
来源：http://dali.sufxvd.cn/Article/details/gtrxpqnola.html

Ruby: resp.code.to_i
来源：http://dali.jinqigufen.top/Article/details/gtsouyadfj.html

C#:   (int)resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gtdixakeew.html

[L08] 并发请求多个地址
来源：http://dali.yuxming.cn/Article/details/gtmlhensnk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gtpcufzblz.html

PHP:  curl_multi_init() 系列
来源：http://dali.sweek.top/Article/details/gtcvppzzfb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gtsiopxbsz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtemqnszrf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgfzy.top/Article/details/gtruccyaga.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgfzy.top/Article/details/gtrsdsgodh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jyoumei.cn/Article/details/gtnvoiagvq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sweek.top/Article/details/gtvkqoujhw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtqrmhdned.html

M. 命令行 / 进程 / 环境
来源：http://dali.aizwys.cn/Article/details/gtxacwdath.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtczjjhjxo.html

[M01] 读取命令行参数
来源：http://dali.xuanzx.com/Article/details/gtoytohbor.html

Py:   sys.argv[1:]
来源：http://dali.hnqzz.top/Article/details/gtrdzyrfnu.html

PHP:  $argv;  $argc;
来源：http://dali.ydzc1.top/Article/details/gtjuwbyprk.html

JS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gtxaobbzbc.html

TS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gtyjsejsmx.html

Java: args 数组（main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gtizvpvlrr.html

Go:   os.Args[1:]
来源：http://dali.hammf.cn/Article/details/gtwuglazoe.html

Ruby: ARGV
来源：http://dali.ydzc1.top/Article/details/gtwdbvqskc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gtjiilvlrq.html

[M02] 读取环境变量
来源：http://dali.yj202588.top/Article/details/gtjxykcqdn.html

Py:   os.environ.get("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbulvsdva.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gtfdhyjupt.html

JS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gtcyleavhl.html

TS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtsoupvpap.html

Java: System.getenv("HOME")
来源：http://dali.ivvv.top/Article/details/gtwkispyux.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtlmgdkzhm.html

Ruby: ENV["HOME"]
来源：http://dali.ehwqpu.com/Article/details/gtdlvfuemj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtpmxcsjxb.html

[M03] 执行外部命令
来源：http://dali.c1oappe.top/Article/details/gtnpguszfr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.quarkkingdee.top/Article/details/gtcytwprud.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhoulong.xyz/Article/details/gtbqtmeldg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gtftovbxva.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gtdoiusgpe.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.iojbl.cn/Article/details/gtypcipoto.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gtqwslbbrh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cucudq.cn/Article/details/gthpwhrhdo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigfzy.top/Article/details/gtqjgnfetr.html

[M04] 获取当前工作目录
来源：http://dali.chenzaomai.com/Article/details/gtonqsknuy.html

Py:   os.getcwd()
来源：http://dali.zhoulong.xyz/Article/details/gtwcvjpgmj.html

PHP:  getcwd();
来源：http://dali.mhx1999.top/Article/details/gtqqtbdunw.html

JS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gtpsnqskff.html

TS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthimjzyqt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.meibo888.top/Article/details/gtclqjeyzz.html

Go:   os.Getwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtrkzfmqal.html

Ruby: Dir.pwd
来源：http://dali.yuxming.cn/Article/details/gtawosgkph.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhengqikj.top/Article/details/gttinaejvf.html

[M05] 设置退出码
来源：http://dali.xinyue.icu/Article/details/gthfltjspu.html

Py:   sys.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtsbbfupch.html

PHP:  exit(1);
来源：http://dali.jlsjyb.cn/Article/details/gtccqlkcuq.html

JS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtfrumfsax.html

TS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtytrlebhj.html

Java: System.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtighommau.html

Go:   os.Exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaymbumqa.html

Ruby: exit 1
来源：http://dali.ppjwa.cn/Article/details/gtpfsvezmw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.mhx1999.top/Article/details/gtjohiiuns.html

[M06] 向标准错误输出
来源：http://dali.jianghu66.top/Article/details/gtlnyhjtfb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ivvv.top/Article/details/gtxlpdoyvr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.316326.xyz/Article/details/gtywsfxmbd.html

JS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gtulvnvqew.html

TS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gtxhoiztjq.html

Java: System.err.println("err")
来源：http://dali.andypj.xyz/Article/details/gtiulzberv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hysaishi.cn/Article/details/gtpeffenad.html

Ruby: warn "err"
来源：http://dali.zhoulong.xyz/Article/details/gtdqymeadf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtlvocedfo.html

[M07] 判断是否为主入口
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqnzqswq.html

Py:   if __name__ == "__main__":
来源：http://dali.daxiang520.top/Article/details/gtcenwkkce.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.0kj1m.cn/Article/details/gtmorkroix.html

JS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gtmrqzxetk.html

TS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gtgsohxchw.html

Java: public static void main(String[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtletysyly.html

Go:   func main()
来源：http://dali.yvedp.cn/Article/details/gttjsxonmz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnxiangtu.top/Article/details/gtmywpompr.html

C#:   static void Main(string[] args)
来源：http://dali.fengsongda.top/Article/details/gtrtazdjob.html

[M08] 获取系统与运行时信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwxytylw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sufxvd.cn/Article/details/gtorrvzsaj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258888.top/Article/details/gtrxbwbwwe.html

JS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gtjilzymng.html


<!-- 参考信息 -->