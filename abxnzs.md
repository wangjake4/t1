代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.bjfxy.top/Article/details/gt2bvrcmrrc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daxiang520.top/Article/details/gt2hbbufrkp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuetiantiany.cn/Article/details/gt2natoozuf.html

JS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2bdvuimhc.html

TS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2rqxmwvkr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2vaiawfvc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gt2kfamaxqw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gt2ysutmzny.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zdqjudy.top/Article/details/gt2gjjqyujv.html

[J04] 时间戳与日期互转
来源：http://dali.hammf.cn/Article/details/gt2jlqiffij.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ydzc1.top/Article/details/gt2glmajfgb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.iojbl.cn/Article/details/gt2jjsvmbof.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aizwys.cn/Article/details/gt2dmxzuhxl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.birdmap.top/Article/details/gt2jobqnnxz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.9152youxi.cn/Article/details/gt2quyhldmi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258888.top/Article/details/gt2ebmtxcbj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shzxlz.cn/Article/details/gt2aqyylpvs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2bcolqykw.html

[J05] 时间加减（加 7 天）
来源：http://dali.tian-w.cn/Article/details/gt2thwlxusn.html

Py:   now + timedelta(days=7)
来源：http://dali.zhoulong.xyz/Article/details/gt2lhnogzhe.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cqqwz.cn/Article/details/gt2wujzouzb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gt2rksgpyig.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gt2dfmlmiyt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dgxbdmpg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.birdmap.top/Article/details/gt2fjpzllql.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cheryme.top/Article/details/gt2heypmvbj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnqzz.top/Article/details/gt2mtdhojsg.html

[J06] 计算两时间之差
来源：http://dali.tanke756.top/Article/details/gt2upajhzat.html

Py:   (end - start).total_seconds()
来源：http://dali.ybcxt.top/Article/details/gt2myjdmlac.html

PHP:  $end->diff($start)->days;
来源：http://dali.cheryme.top/Article/details/gt2wppwnbqs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ivvv.top/Article/details/gt2medskyne.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zdqjudy.top/Article/details/gt2yzcpvqxb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sysykeji.top/Article/details/gt2rbyqwslq.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gt2vakxzefw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnqzz.top/Article/details/gt2bhsngetm.html

C#:   (end - start).TotalSeconds
来源：http://dali.andypj.xyz/Article/details/gt2wwdfhkuk.html

[J07] 比较两个日期
来源：http://dali.yangfankeji.com/Article/details/gt2vigepziy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gt2pqvuwgjg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tianlin.xyz/Article/details/gt2mlsyigdv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gt2dtemraiw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gt2gqncrlvh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gotoacloud.top/Article/details/gt2eyttxtfd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daria6918.cn/Article/details/gt2znkomdml.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gt2hdlzexuu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gt2ywfrtmnk.html

[J08] 提取年月日与星期
来源：http://dali.feifeiyinyue.top/Article/details/gt2qmxkuvlh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daria6918.cn/Article/details/gt2faqueris.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhengqikj.top/Article/details/gt2tjdaddgz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gzhubu.top/Article/details/gt2kqixmplk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuetiantiany.cn/Article/details/gt2pbgkszkk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fengsongda.top/Article/details/gt2taaaeafv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhengqikj.top/Article/details/gt2mlaszxlf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jiagoushi.top/Article/details/gt2hsifowza.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cashguo.top/Article/details/gt2rhktluew.html

[J09] 时区处理
来源：http://dali.jiagoushi.top/Article/details/gt2trxkmxdk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.birdmap.top/Article/details/gt2ahhuvnws.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shangyingyoupin.top/Article/details/gt2atjlckmo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gt2awublzrt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gt2bquryitd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gogol.net.cn/Article/details/gt2edtkjeya.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sysykeji.top/Article/details/gt2coqvbmnh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangdashe.top/Article/details/gt2qbwvbgro.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhoulong.xyz/Article/details/gt2vhtkluxe.html

[J10] 取今天 / 本月第一天
来源：http://dali.yangfankeji.com/Article/details/gt2gglheczs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gzhubu.top/Article/details/gt2sknwvljc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yueranfly.top/Article/details/gt2rzsicjji.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aibaodan.cn/Article/details/gt2ulcifetb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2rcurgnqp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nwbrower.top/Article/details/gt2uxgszffo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnqzz.top/Article/details/gt2gykwemtg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tphyvvsy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.birdmap.top/Article/details/gt2yhksssmr.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2fuckjhiy.html

K. JSON 与序列化
来源：http://dali.0kj1m.cn/Article/details/gt2tgtkltfe.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2degrwfza.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenzaomai.com/Article/details/gt2ntejqhqq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gt2utmxapfo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gt2yrsktgsl.html

JS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2aqghiyyn.html

TS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2keqttwqh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yangfankeji.com/Article/details/gt2vdzibris.html

Go:   json.Marshal(obj)
来源：http://dali.yj202588.top/Article/details/gt2fbvbvumr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhoulong.xyz/Article/details/gt2ayyajdzb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zremyqta.html

[K02] JSON 字符串转对象
来源：http://dali.hnxiangtu.top/Article/details/gt2alfipndq.html

Py:   json.loads(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2cqamjfln.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenlongwang.top/Article/details/gt2zjmyhzqn.html

JS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gt2pwnbedse.html

TS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gt2xwhkbqox.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.bjfxy.top/Article/details/gt2nwzykbiz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gt2qikggfor.html

Ruby: JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gt2tvoemxoy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tpgcfjjj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guowangkeji.top/Article/details/gt2tviwxjhf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gt2rvvrnprm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gt2hotankmk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gt2bfiwhhpj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xzapxmfp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ccoooimh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.9152youxi.cn/Article/details/gt2jlnqofwe.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kqmomuhr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cucudq.cn/Article/details/gt2uxdvreeb.html

[K04] 读取 JSON 文件
来源：http://dali.smart0.xyz/Article/details/gt2jmdoubop.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.mhx1999.top/Article/details/gt2tpjabfma.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qkrmtdzs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gt2uhurqfxm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2voqupboi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gt2hayxrbgh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gt2oaypzrhj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.316326.xyz/Article/details/gt2wlljvfph.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gt2mxyprgeu.html

[K05] 深拷贝对象
来源：http://dali.nanxuanxn.top/Article/details/gt2hkmeavuw.html

Py:   copy.deepcopy(obj)
来源：http://dali.meibo888.top/Article/details/gt2vzdiynwd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shangyingyoupin.top/Article/details/gt2vntfatiw.html

JS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2ktnrxkel.html

TS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2ktymbzgn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aizwys.cn/Article/details/gt2iuwnumri.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cucudq.cn/Article/details/gt2wpdnfant.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnqzz.top/Article/details/gt2fmnjtdwz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ivvv.top/Article/details/gt2yckqyvbi.html

[K06] 解析 URL 查询串
来源：http://dali.c1oappe.top/Article/details/gt2rxdjclby.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gt2wadzdvgq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangdashe.top/Article/details/gt2alhunvxc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gt2guhivjrk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gt2sawcxzls.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxinkj.top/Article/details/gt2qptkmpfd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gt2dttfmbnl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gt2nfowpgii.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gt2rdfpsdrb.html

[K07] 进制转换
来源：http://dali.sysykeji.top/Article/details/gt2spgplxgm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2dhhbuebn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zdqjudy.top/Article/details/gt2awhotvan.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2pgiooutk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2enemadco.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cojyzxaj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.birdmap.top/Article/details/gt2lypagawj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shzxlz.cn/Article/details/gt2toqwtryb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2klwitbbi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jiagoushi.top/Article/details/gt2ucxghdve.html

Py:   pickle.dumps(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2gsziymli.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shzxlz.cn/Article/details/gt2lhwqhtpk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gt2pjehlbgt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gt2decgopez.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ppjwa.cn/Article/details/gt2pthdndkg.html

Go:   encoding/gob
来源：http://dali.tianlin.xyz/Article/details/gt2nhxunnul.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2zmsiffui.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gt2syxoorjl.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2jtahgauv.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yhxzfhcj.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2mdlxibfp.html

[L01] 发送 GET 请求
来源：http://dali.zhixingplan.top/Article/details/gt2twvhrxtx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jlsjyb.cn/Article/details/gt2cwbrrvpv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuanzhike.top/Article/details/gt2trdbebmi.html

JS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gt2sxutbisb.html

TS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gt2rmwbubro.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.feifeiyinyue.top/Article/details/gt2utivoyfm.html

Go:   resp, err := http.Get(url)
来源：http://dali.hammf.cn/Article/details/gt2rpeehvmn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.kuanghao11.cn/Article/details/gt2dkufuuug.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iouqgrwk.html

[L02] 发送 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gt2begupeti.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gt2qelxxgot.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgfzy.top/Article/details/gt2vpokyhag.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jianghu66.top/Article/details/gt2svptwipc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gt2wrninarm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigufen.top/Article/details/gt2iiuhshrq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.mhx1999.top/Article/details/gt2muzmryuz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigufen.top/Article/details/gt2ssyhkjsg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cqqwz.cn/Article/details/gt2itoyaqmc.html

[L03] 设置自定义请求头
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pcgxslde.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yongpay.top/Article/details/gt2hwdwpzxa.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgfzy.top/Article/details/gt2ifuvnupk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmdjhepc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuanzx.com/Article/details/gt2xwmdjxmb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ehwqpu.com/Article/details/gt2ggzxhtwl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gt2obvrgdab.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shuidangran.top/Article/details/gt2lqumyelx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gt2arzpglzr.html

[L04] 设置超时
来源：http://dali.svipenyu.cn/Article/details/gt2mxquegty.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cucudq.cn/Article/details/gt2qzmpbccx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hammf.cn/Article/details/gt2cyqfyezy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gt2zentxjux.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gt2tklbpvte.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ihuuywuj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuanzhike.top/Article/details/gt2jteziptw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.9152youxi.cn/Article/details/gt2jcjdpwze.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hammf.cn/Article/details/gt2pscasdol.html

[L05] 上传文件（multipart）
来源：http://dali.jqgfzy.top/Article/details/gt2jaqepamh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hammf.cn/Article/details/gt2wxalgmbg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgufenzy.top/Article/details/gt2vbaegcti.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gt2yjhezwlv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gt2ekfztlqk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jcpwikvi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.redwolf501.top/Article/details/gt2mbkecomi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigufen.top/Article/details/gt2pimekgqo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2mrpdjgvz.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ftmbwgit.html

Py:   resp.json()
来源：http://dali.yongpay.top/Article/details/gt2gsfoludk.html

PHP:  json_decode($body, true);
来源：http://dali.yueranfly.top/Article/details/gt2fysyzcrb.html

JS:   await resp.json()
来源：http://dali.smart0.xyz/Article/details/gt2rxmadzoi.html

TS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gt2jvheeoun.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzimyjs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.vqdsnc.cn/Article/details/gt2qcwrrdgi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uvtorrdq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sysykeji.top/Article/details/gt2spdfmczs.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gt2yrufigio.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tian-w.cn/Article/details/gt2uycwzplp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2tfnjmxtu.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mdmptmxv.html

TS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gt2kveyxdhv.html

Java: resp.statusCode()
来源：http://dali.havefunace.top/Article/details/gt2nwwkqevr.html

Go:   resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gt2qfgtatah.html

Ruby: resp.code.to_i
来源：http://dali.daria6918.cn/Article/details/gt2fwefcuog.html

C#:   (int)resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gt2wziybjws.html

[L08] 并发请求多个地址
来源：http://dali.gzhubu.top/Article/details/gt2lziaqcgw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yanxiufei.cn/Article/details/gt2xggrewyc.html

PHP:  curl_multi_init() 系列
来源：http://dali.nwbrower.top/Article/details/gt2wbpxqdxc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2fphkwmin.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gt2wbhazokb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ivvv.top/Article/details/gt2tkcqnyfw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zycfv.cn/Article/details/gt2hjtuqgsh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.iojbl.cn/Article/details/gt2rlcxmtvw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.bjfxy.top/Article/details/gt2gcklvchp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2utinedni.html

M. 命令行 / 进程 / 环境
来源：http://dali.gaohongyu789.top/Article/details/gt2mgxcnrcq.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2lowsbqoq.html

[M01] 读取命令行参数
来源：http://dali.ehwqpu.com/Article/details/gt2xldhpjum.html

Py:   sys.argv[1:]
来源：http://dali.xylfe.cn/Article/details/gt2esnqkwgl.html

PHP:  $argv;  $argc;
来源：http://dali.nwbrower.top/Article/details/gt2ljuaricb.html

JS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gt2wkamknbs.html

TS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gt2eicmyefg.html

Java: args 数组（main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gt2wddivoac.html

Go:   os.Args[1:]
来源：http://dali.shuidangran.top/Article/details/gt2fgpglbhz.html

Ruby: ARGV
来源：http://dali.dianchejie.cn/Article/details/gt2gupthkxb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gt2bdddjwhc.html

[M02] 读取环境变量
来源：http://dali.c1oappe.top/Article/details/gt2dkwlrhcs.html

Py:   os.environ.get("HOME")
来源：http://dali.xziqi.cn/Article/details/gt2uqhdixoc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gt2njmitbjk.html

JS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gt2ehrerywq.html

TS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gt2fopaupit.html

Java: System.getenv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2fnxlevwl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.smart0.xyz/Article/details/gt2lusrgwvo.html

Ruby: ENV["HOME"]
来源：http://dali.yanxiufei.cn/Article/details/gt2yupzqcoc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.birdmap.top/Article/details/gt2mxqeaqem.html

[M03] 执行外部命令
来源：http://dali.ehwqpu.com/Article/details/gt2mgdgqdre.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ztxhvnnn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shuidangran.top/Article/details/gt2niyesbgg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gt2uokqntbq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.c1oappe.top/Article/details/gt2pxltciud.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shzxlz.cn/Article/details/gt2axeddioo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ybcxt.top/Article/details/gt2kwnhnyyf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daxiang520.top/Article/details/gt2peyraybr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yvedp.cn/Article/details/gt2olitlpdf.html

[M04] 获取当前工作目录
来源：http://dali.mhx1999.top/Article/details/gt2vyfitdho.html

Py:   os.getcwd()
来源：http://dali.yj20258888.top/Article/details/gt2ejlprvfk.html

PHP:  getcwd();
来源：http://dali.hammf.cn/Article/details/gt2fajxyxsd.html

JS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gt2bscamhat.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwpzlqg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gzhubu.top/Article/details/gt2osdpctyq.html

Go:   os.Getwd()
来源：http://dali.ydzc1.top/Article/details/gt2jrmirfhq.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gt2eioftftr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cashguo.top/Article/details/gt2enjahprt.html

[M05] 设置退出码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jarihgyn.html

Py:   sys.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2mviyaxjs.html

PHP:  exit(1);
来源：http://dali.snrcjt.cn/Article/details/gt2smkojftn.html

JS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fgvdvonf.html

TS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gt2cqrwhgar.html

Java: System.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2jypamlxy.html

Go:   os.Exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2wtncgkam.html

Ruby: exit 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tuwfbsqk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigufen.top/Article/details/gt2uztdoluz.html

[M06] 向标准错误输出
来源：http://dali.aibaodan.cn/Article/details/gt2olaggdph.html

Py:   print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gt2iaplhked.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gt2kqcyewtw.html

JS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gt2qfujprbm.html

TS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gt2ctcgdvmc.html

Java: System.err.println("err")
来源：http://dali.fzhhl.top/Article/details/gt2avrjnzyx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yonumen.top/Article/details/gt2lfqvgiiv.html

Ruby: warn "err"
来源：http://dali.jqgfzy.top/Article/details/gt2ffcogxut.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnqzz.top/Article/details/gt2fmlqswar.html

[M07] 判断是否为主入口
来源：http://dali.ivvv.top/Article/details/gt2gemxkxhu.html

Py:   if __name__ == "__main__":
来源：http://dali.yonumen.top/Article/details/gt2smbwcbgs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shzxlz.cn/Article/details/gt2lhtcttds.html

JS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gt2vwmqzuic.html

TS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gt2xwslprac.html

Java: public static void main(String[] args)
来源：http://dali.havefunace.top/Article/details/gt2udoegbgj.html

Go:   func main()
来源：http://dali.zhengqikj.top/Article/details/gt2vdiaihpa.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangdashe.top/Article/details/gt2shclvcdz.html

C#:   static void Main(string[] args)
来源：http://dali.dashuyun.cn/Article/details/gt2fmhosusc.html

[M08] 获取系统与运行时信息
来源：http://dali.zhongyouzk.top/Article/details/gt2abuqfnzy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenjidiqi.icu/Article/details/gt2clqawvtm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yangfankeji.com/Article/details/gt2empmzoku.html

JS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gt2yrureerk.html

TS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gt2ldjangnx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.birdmap.top/Article/details/gt2zwckxmzd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gt2ijquassh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxuanxn.top/Article/details/gt2bfcvlals.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zycfv.cn/Article/details/gt2dnahutii.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2svsjdxft.html

N. 数据结构与算法
来源：http://dali.guannengcc.top/Article/details/gt2ktxcinme.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2pctmzwlh.html


<!-- 参考信息 -->