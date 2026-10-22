代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cucudq.cn/Article/details/gt2zoahbdea.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.havefunace.top/Article/details/gt2ywhnismr.html

[J05] 时间加减（加 7 天）
来源：http://dali.havefunace.top/Article/details/gt2wqeavkbk.html

Py:   now + timedelta(days=7)
来源：http://dali.birdmap.top/Article/details/gt2ggoejpwp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qmpwjngf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gt2qwsfelhy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gt2jaosigxu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2audguued.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2evowrtmp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pycfn.com/Article/details/gt2veyolkbs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guowangkeji.top/Article/details/gt2bqhuroqq.html

[J06] 计算两时间之差
来源：http://dali.tianlin.xyz/Article/details/gt2dpnwwaup.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjpvsvf.html

PHP:  $end->diff($start)->days;
来源：http://dali.shangyingyoupin.top/Article/details/gt2lbunbrcz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jiagoushi.top/Article/details/gt2nifyazul.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gaohongyu789.top/Article/details/gt2tfrgwcdl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.havefunace.top/Article/details/gt2lfgeheiq.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2azimpdij.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fengsongda.top/Article/details/gt2todroxam.html

C#:   (end - start).TotalSeconds
来源：http://dali.jyoumei.cn/Article/details/gt2smwxsxwy.html

[J07] 比较两个日期
来源：http://dali.yanxiufei.cn/Article/details/gt2cjvvxdop.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gt2tqgdfogz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wwvuraeg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gt2sfruisjv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gt2ytrpjpvj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cdnleiting.top/Article/details/gt2khfouosw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daria6918.cn/Article/details/gt2lehtpbwh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gt2xvqwqujd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2hblsfdwk.html

[J08] 提取年月日与星期
来源：http://dali.guannengcc.top/Article/details/gt2ibfbuhgs.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zreoxfin.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gaohongyu789.top/Article/details/gt2bkgcgxhg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.svipenyu.cn/Article/details/gt2locdjppa.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gotoacloud.top/Article/details/gt2bojussvy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuanzhike.top/Article/details/gt2inozotho.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guowangkeji.top/Article/details/gt2vxdahzoc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.mhx1999.top/Article/details/gt2fwgnpydu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cashguo.top/Article/details/gt2nzqklwlk.html

[J09] 时区处理
来源：http://dali.pycfn.com/Article/details/gt2jtrbyyln.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aizwys.cn/Article/details/gt2knfnoilg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhengqikj.top/Article/details/gt2ijsuaytn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangdashe.top/Article/details/gt2dmswapcm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gt2akwvheeu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guowangkeji.top/Article/details/gt2nvutrikb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fengsongda.top/Article/details/gt2skgbezfw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yonumen.top/Article/details/gt2ebicrssg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zdqjudy.top/Article/details/gt2diuswbhx.html

[J10] 取今天 / 本月第一天
来源：http://dali.pengpengdd.cyou/Article/details/gt2cgvcabkk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yvedp.cn/Article/details/gt2gsjkgldy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.haohaochexian.top/Article/details/gt2wztvpafi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj202588.top/Article/details/gt2eaibemrq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zycfv.cn/Article/details/gt2eamncoal.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uhwqbngl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ydzc1.top/Article/details/gt2rdhcavmz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tian-w.cn/Article/details/gt2nvuxgkcz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ydzc1.top/Article/details/gt2odzwwpbb.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2ekpywjnt.html

K. JSON 与序列化
来源：http://dali.jqgfzy.top/Article/details/gt2fcqznndn.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2uehesgol.html

[K01] 对象转 JSON 字符串
来源：http://dali.yangfankeji.com/Article/details/gt2ohiwnfnc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gt2leieklql.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqlohesw.html

JS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gt2dketdnwk.html

TS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wmugpbgz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2inimipax.html

Go:   json.Marshal(obj)
来源：http://dali.bjfxy.top/Article/details/gt2aoqbhoje.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daria6918.cn/Article/details/gt2azlxzjxo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cucudq.cn/Article/details/gt2cwovsttf.html

[K02] JSON 字符串转对象
来源：http://dali.yongpay.top/Article/details/gt2nseaiwds.html

Py:   json.loads(s)
来源：http://dali.yonumen.top/Article/details/gt2ewdpzmuw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pengpengdd.cyou/Article/details/gt2mosiomfe.html

JS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gt2jdoiqeho.html

TS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gt2hhxdfmnj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.haohaochexian.top/Article/details/gt2eobhqszk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gt2grhshbpv.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmuzcaq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuanzhike.top/Article/details/gt2voccixty.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ivvv.top/Article/details/gt2hkpzakyg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gt2smrxsruo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gt2kbekipxf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2nebjctvo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbmvafd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ydzc1.top/Article/details/gt2qvqdtmag.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2egjsuxcv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2smuecioy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hongshengwenyu.top/Article/details/gt2gmsnmqwv.html

[K04] 读取 JSON 文件
来源：http://dali.birdmap.top/Article/details/gt2lfaoywez.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sxryk.cn/Article/details/gt2ormnogkm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xziqi.cn/Article/details/gt2vbqzhjld.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gt2rwsrpadr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gt2htwkdorz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aizwys.cn/Article/details/gt2flclskfr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gt2ebzmjuqd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gt2vpsrnsjm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gt2kjcfoagu.html

[K05] 深拷贝对象
来源：http://dali.pycfn.com/Article/details/gt2yyllneus.html

Py:   copy.deepcopy(obj)
来源：http://dali.xylfe.cn/Article/details/gt2mttbjwam.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwkbqll.html

JS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gt2iqakavov.html

TS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gt2xwbdmfzk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daxiang520.top/Article/details/gt2surhynqk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hysaishi.cn/Article/details/gt2ilvmalpt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuetiantiany.cn/Article/details/gt2usbbhnyt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhoulong.xyz/Article/details/gt2huxonflx.html

[K06] 解析 URL 查询串
来源：http://dali.feifeiyinyue.top/Article/details/gt2oubrwgfz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gt2gyqymbxi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zdqjudy.top/Article/details/gt2tjkkmgmx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gt2kskfpgvb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gt2tuxipjlv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgfzy.top/Article/details/gt2zhegcwbl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gt2yvchhxyp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gt2xjmrlxyq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gt2hhdstihp.html

[K07] 进制转换
来源：http://dali.sxryk.cn/Article/details/gt2uijxtite.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2dwbvnsqs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yongpay.top/Article/details/gt2xztewpdv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2mxvkzhaj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2whegvlih.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2dgxkybnn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.vqdsnc.cn/Article/details/gt2jcrbnsnm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.svipenyu.cn/Article/details/gt2qiolsbds.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2qxkfjshb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tianlin.xyz/Article/details/gt2hpeswecs.html

Py:   pickle.dumps(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2esmwowrj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gnhuyfhc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gt2keiwnixs.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gt2fssqmeev.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aibaodan.cn/Article/details/gt2kkvvhjqn.html

Go:   encoding/gob
来源：http://dali.nanxuanxn.top/Article/details/gt2ubwmkmbi.html

Ruby: Marshal.dump(obj)
来源：http://dali.yueranfly.top/Article/details/gt2thhmrjlc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gt2ugmftyxc.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2qlbtjuee.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gt2lyfnhtkj.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2ybomrkjh.html

[L01] 发送 GET 请求
来源：http://dali.chenzaomai.com/Article/details/gt2fphrctzn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sweek.top/Article/details/gt2pjlkeygu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hfpthk.cn/Article/details/gt2tqylbchm.html

JS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gssuzenk.html

TS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2jhkofixa.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxuanxn.top/Article/details/gt2lqaxzsho.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuxming.cn/Article/details/gt2azitbuee.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgfzy.top/Article/details/gt2xeqtaxfp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenzaomai.com/Article/details/gt2njcouekn.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jhxfafuw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gt2gxiudepd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.c1oappe.top/Article/details/gt2fxswuics.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gt2npznddgp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gt2plhfcaoy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aizwys.cn/Article/details/gt2mdppwteb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.feifeiyinyue.top/Article/details/gt2gajrrjqr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gt2nyxxempo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fengsongda.top/Article/details/gt2gwktppod.html

[L03] 设置自定义请求头
来源：http://dali.0kj1m.cn/Article/details/gt2uwktetwx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenlongwang.top/Article/details/gt2bilvborh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigufen.top/Article/details/gt2ngbywakf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gt2migzmdzo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gt2nfvhojep.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258888.top/Article/details/gt2yyqpjwaa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gt2vwjnnuwr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ydzc1.top/Article/details/gt2rjrwzbuh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gt2tmtbpnjg.html

[L04] 设置超时
来源：http://dali.jiagoushi.top/Article/details/gt2pegzbxbg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rgprrwjw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nlyrilkw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tanke756.top/Article/details/gt2qzvnhwan.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guannengcc.top/Article/details/gt2oaywcyde.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jlsjyb.cn/Article/details/gt2errscpss.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258.top/Article/details/gt2vavjblxb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yonumen.top/Article/details/gt2kqgycskc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yongpay.top/Article/details/gt2kjxxazlv.html

[L05] 上传文件（multipart）
来源：http://dali.birdmap.top/Article/details/gt2mpjgvler.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jiagoushi.top/Article/details/gt2yxyvruuw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ppjwa.cn/Article/details/gt2pheussda.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gt2gecdehlg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gt2zrdkeyzq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fzhhl.top/Article/details/gt2kzgbovrf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxuanxn.top/Article/details/gt2oinmbpqo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuetiantiany.cn/Article/details/gt2fphqhqyl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2diosznrv.html

[L06] 解析响应为 JSON
来源：http://dali.gaohongyu789.top/Article/details/gt2stfatwby.html

Py:   resp.json()
来源：http://dali.ehwqpu.com/Article/details/gt2kkcmxodg.html

PHP:  json_decode($body, true);
来源：http://dali.pycfn.com/Article/details/gt2qfydopwl.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gt2qmduhgeg.html

TS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gt2lrbelftw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guannengcc.top/Article/details/gt2ikggzozj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jyoumei.cn/Article/details/gt2pzlnrcnn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.smart0.xyz/Article/details/gt2lsaepgiv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigufen.top/Article/details/gt2rjsegyvb.html

[L07] 处理 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gt2kuorrvcr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jianghu66.top/Article/details/gt2rnfpaplk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shzxlz.cn/Article/details/gt2ykeckjrh.html

JS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gt2vpltomyq.html

TS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ujsfvahq.html

Java: resp.statusCode()
来源：http://dali.nwbrower.top/Article/details/gt2bqceivdy.html

Go:   resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gt2ymjbvlav.html

Ruby: resp.code.to_i
来源：http://dali.sxryk.cn/Article/details/gt2iknjzjtg.html

C#:   (int)resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gt2zgalicsw.html

[L08] 并发请求多个地址
来源：http://dali.yongpay.top/Article/details/gt2kdhhoeur.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnqzz.top/Article/details/gt2hvewenhw.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnqzz.top/Article/details/gt2jcawtidm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gt2ngfhbqpf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gt2pvmqynuz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cdnleiting.top/Article/details/gt2jlwyadly.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gotoacloud.top/Article/details/gt2fzlydjns.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jiagoushi.top/Article/details/gt2bsmzqpwt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenlongwang.top/Article/details/gt2ppgduboj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2fhgdzhjv.html

M. 命令行 / 进程 / 环境
来源：http://dali.aibaodan.cn/Article/details/gt2xxplrnbh.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2omjhwuov.html

[M01] 读取命令行参数
来源：http://dali.tanke756.top/Article/details/gt2giecceby.html

Py:   sys.argv[1:]
来源：http://dali.yonumen.top/Article/details/gt2ucbajakp.html

PHP:  $argv;  $argc;
来源：http://dali.gotoacloud.top/Article/details/gt2ajjwuvdt.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yhcglmqa.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gt2sqtoqvgq.html

Java: args 数组（main 方法参数）
来源：http://dali.birdmap.top/Article/details/gt2uuuxqcsd.html

Go:   os.Args[1:]
来源：http://dali.aizwys.cn/Article/details/gt2pbzqgeid.html

Ruby: ARGV
来源：http://dali.smart0.xyz/Article/details/gt2ejrmfgyo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hammf.cn/Article/details/gt2bsxxiruk.html

[M02] 读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gt2scktyjaa.html

Py:   os.environ.get("HOME")
来源：http://dali.cucudq.cn/Article/details/gt2fhngcuep.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gt2wzrckfoq.html

JS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gt2zhjkmwbr.html

TS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gt2hgsozntj.html

Java: System.getenv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gt2hzxgwggk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gt2xzviudfr.html

Ruby: ENV["HOME"]
来源：http://dali.yvedp.cn/Article/details/gt2ebyopfvw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ydzc1.top/Article/details/gt2ytrbrilr.html

[M03] 执行外部命令
来源：http://dali.xuanzx.com/Article/details/gt2yrxxebck.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258.top/Article/details/gt2hegpbrkp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.vqdsnc.cn/Article/details/gt2ebepmosp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gt2jznqvypi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gt2mbicxbqg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxinkj.top/Article/details/gt2wykgscsf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuxming.cn/Article/details/gt2pnldigkj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.havefunace.top/Article/details/gt2fqsechpn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gt2kfxbsqhu.html

[M04] 获取当前工作目录
来源：http://dali.shzxlz.cn/Article/details/gt2srdbuqck.html

Py:   os.getcwd()
来源：http://dali.gzhubu.top/Article/details/gt2qcllnhss.html

PHP:  getcwd();
来源：http://dali.9152youxi.cn/Article/details/gt2iegqqxbp.html

JS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gt2nnaufxeg.html

TS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gt2pjpvsnzr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.vqdsnc.cn/Article/details/gt2kgtrpmgj.html

Go:   os.Getwd()
来源：http://dali.nwbrower.top/Article/details/gt2xikzpgda.html

Ruby: Dir.pwd
来源：http://dali.jianghu66.top/Article/details/gt2yqlxvoja.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sweek.top/Article/details/gt2oobrxgvj.html

[M05] 设置退出码
来源：http://dali.birdmap.top/Article/details/gt2eqdtkzhm.html

Py:   sys.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2nexhwqmc.html

PHP:  exit(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxkzhldo.html

JS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2jebhtfpx.html

TS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2aohnjpmd.html

Java: System.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2qwklhija.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gt2ktuagubf.html

Ruby: exit 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2qwhhbdrf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yueranfly.top/Article/details/gt2gchlzrju.html

[M06] 向标准错误输出
来源：http://dali.guannengcc.top/Article/details/gt2ifleuhaw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gt2hdqlgebg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sweek.top/Article/details/gt2ijyzdrrb.html

JS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gt2pcxzmjll.html

TS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gt2kcidpgom.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gt2pwzmtsvh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258888.top/Article/details/gt2yfygbdmq.html

Ruby: warn "err"
来源：http://dali.kuanghao11.cn/Article/details/gt2trzpfvjy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2czgiixoh.html

[M07] 判断是否为主入口
来源：http://dali.hysaishi.cn/Article/details/gt2pafnjrwx.html

Py:   if __name__ == "__main__":
来源：http://dali.hongshengwenyu.top/Article/details/gt2yltvobdv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hywenlv.cn/Article/details/gt2djgrjjcl.html

JS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gt2ztvcgdql.html

TS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gt2qgnuwvfm.html

Java: public static void main(String[] args)
来源：http://dali.jlsjyb.cn/Article/details/gt2eekrlwjf.html

Go:   func main()
来源：http://dali.yanxiufei.cn/Article/details/gt2wnwkekwn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bvcpjpee.html

C#:   static void Main(string[] args)
来源：http://dali.tanke756.top/Article/details/gt2chsirpwc.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgufenzy.top/Article/details/gt2erqworbn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangdashe.top/Article/details/gt2qshmcgko.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aizwys.cn/Article/details/gt2zagpeyln.html

JS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gt2mjiocxuh.html

TS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gt2dsjdmabs.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenlongwang.top/Article/details/gt2olhxzmaz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gotoacloud.top/Article/details/gt2sgzdjbuu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ndkbmktj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nwbrower.top/Article/details/gt2ckadbqhg.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kuxplcdm.html

N. 数据结构与算法
来源：http://dali.ybcxt.top/Article/details/gt2pnniklyi.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2umjlaxwy.html

[N01] 二分查找（有序数组）
来源：http://dali.cashguo.top/Article/details/gt2oantlvqj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sbslytbn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daria6918.cn/Article/details/gt2biatondi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2ieitmhhy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gt2yhbsjlfh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gt2xaeasiey.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2snfloqgy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dashuyun.cn/Article/details/gt2xclliean.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2jwcnwbbi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.birdmap.top/Article/details/gt2tzlwyyfx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gt2iuoogaoo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yangfankeji.com/Article/details/gt2jfvivptk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gt2lcfvluqy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wpvlaouv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxuanxn.top/Article/details/gt2xveqfsue.html

Go:   slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gt2gblwxhwq.html


<!-- 参考信息 -->