代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ehwqpu.com/Article/details/gt2xocjwnob.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yueranfly.top/Article/details/gt2qaoqxjdx.html

[J05] 时间加减（加 7 天）
来源：http://dali.ydzc1.top/Article/details/gt2twqxvtgg.html

Py:   now + timedelta(days=7)
来源：http://dali.yangfankeji.com/Article/details/gt2cerngjut.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sysykeji.top/Article/details/gt2mjxzrswe.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gt2mffgbzom.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gdfjkulp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shuidangran.top/Article/details/gt2ouxdpgpn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fzhhl.top/Article/details/gt2cinaxpmn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tianlin.xyz/Article/details/gt2ldajhmgj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tian-w.cn/Article/details/gt2xoeaknjb.html

[J06] 计算两时间之差
来源：http://dali.nanxinkj.top/Article/details/gt2shnhclju.html

Py:   (end - start).total_seconds()
来源：http://dali.hongshengwenyu.top/Article/details/gt2rkgqptrm.html

PHP:  $end->diff($start)->days;
来源：http://dali.sxryk.cn/Article/details/gt2fkpfkrqd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ppjwa.cn/Article/details/gt2mvcngvwj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yuxming.cn/Article/details/gt2ikqdvjux.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxuanxn.top/Article/details/gt2aoigctkt.html

Go:   end.Sub(start).Hours()
来源：http://dali.jiagoushi.top/Article/details/gt2grqgfgpt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgufenzy.top/Article/details/gt2hfcryhqy.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxinkj.top/Article/details/gt2qurgntux.html

[J07] 比较两个日期
来源：http://dali.mhx1999.top/Article/details/gt2vrzfqhzl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gt2tobcvsgz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj202588.top/Article/details/gt2ebcpybjc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gt2sbfnxjkf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.feifeiyinyue.top/Article/details/gt2xlqieklc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gt2epevyzpa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigfzy.top/Article/details/gt2hlgbotmv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gt2gpslffzz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gt2cysniwdr.html

[J08] 提取年月日与星期
来源：http://dali.gaohongyu789.top/Article/details/gt2aulrsjip.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ehwqpu.com/Article/details/gt2oitxelxg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jiagoushi.top/Article/details/gt2fytgterl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.9152youxi.cn/Article/details/gt2rfotgqof.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jlsjyb.cn/Article/details/gt2ttgtdoky.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xziqi.cn/Article/details/gt2fuwipzdr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.feifeiyinyue.top/Article/details/gt2vzszcxbw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daria6918.cn/Article/details/gt2zamodxbk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenzaomai.com/Article/details/gt2sjnhxvqk.html

[J09] 时区处理
来源：http://dali.xylfe.cn/Article/details/gt2skwhotlf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigufen.top/Article/details/gt2ifimqcjd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ppjwa.cn/Article/details/gt2fafpqpot.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gt2gnwhyfwo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gt2lwhyyheu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ukpljqfk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sufxvd.cn/Article/details/gt2prhpvbvr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xinyue.icu/Article/details/gt2aicwyrjo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gt2jbxfrqfw.html

[J10] 取今天 / 本月第一天
来源：http://dali.cashguo.top/Article/details/gt2djtqbksy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eewkheee.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yonumen.top/Article/details/gt2finhwevh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gt2vhrrprzu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cucudq.cn/Article/details/gt2gnaplmlh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnqzz.top/Article/details/gt2afknixoq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gt2syjabkkd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ybcxt.top/Article/details/gt2ypjlcezk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sufxvd.cn/Article/details/gt2esagbxkf.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2vbmowpsa.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gt2fwqsyblp.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2hhemnplq.html

[K01] 对象转 JSON 字符串
来源：http://dali.birdmap.top/Article/details/gt2yikycghk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gt2ohkdhqah.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.iojbl.cn/Article/details/gt2tpjjlnqj.html

JS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cneqdwsk.html

TS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2idhalqmn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhoulong.xyz/Article/details/gt2kfhbspgj.html

Go:   json.Marshal(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2evhwjbva.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yangfankeji.com/Article/details/gt2ipjgikgm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2igqajssm.html

[K02] JSON 字符串转对象
来源：http://dali.andypj.xyz/Article/details/gt2rjjekgyf.html

Py:   json.loads(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2qchmbmth.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnxiangtu.top/Article/details/gt2kgzgneud.html

JS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gt2ktzfrdgh.html

TS:   JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gt2tkpdetul.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dianchejie.cn/Article/details/gt2adooioou.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rneziepw.html

Ruby: JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gt2nnoqiuqo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jianghu66.top/Article/details/gt2zqgdmcgm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.quarkkingdee.top/Article/details/gt2eggtcgdr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gt2ranwlsic.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gt2ujzctyrg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yhibsgcs.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gt2pbtxvxha.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuxming.cn/Article/details/gt2lzpbcpme.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sufxvd.cn/Article/details/gt2lppxvgfy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2hdbiegjc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vekojyzs.html

[K04] 读取 JSON 文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oeegszwc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.meibo888.top/Article/details/gt2kdwkxngi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guowangkeji.top/Article/details/gt2hdrucoiz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gt2tvzbyymj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gt2ngiodcfs.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gt2ermckwti.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bdafqzzu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gt2avdyzrui.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gt2omudwmkm.html

[K05] 深拷贝对象
来源：http://dali.zhiwuduotai.top/Article/details/gt2euufapxc.html

Py:   copy.deepcopy(obj)
来源：http://dali.meibo888.top/Article/details/gt2snzxqavi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gt2qiejiyti.html

JS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gt2zstfwgta.html

TS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gt2xyfqbdtk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nkuitbiu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj202588.top/Article/details/gt2dmdyyseb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigufen.top/Article/details/gt2wbbqgdek.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xziqi.cn/Article/details/gt2cmhvprjj.html

[K06] 解析 URL 查询串
来源：http://dali.xziqi.cn/Article/details/gt2yvrlnbao.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sxryk.cn/Article/details/gt2krcfaymc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.vqdsnc.cn/Article/details/gt2wwsqtjod.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gt2rsudviuw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gt2adwmkzml.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xylfe.cn/Article/details/gt2qwujyxyn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jbdkrwgq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gt2sngayevk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gt2ckcpprto.html

[K07] 进制转换
来源：http://dali.c1oappe.top/Article/details/gt2qlolmsff.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2avmfisyu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shuidangran.top/Article/details/gt2egdzkfhm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2jymcuyaa.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2xhvrxbzl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2qehuszcr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hysaishi.cn/Article/details/gt2nqmlapdv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.redwolf501.top/Article/details/gt2chrdsogo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2gdmqbjkb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hongshengwenyu.top/Article/details/gt2enrwhrxg.html

Py:   pickle.dumps(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2virzlgpn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yongpay.top/Article/details/gt2budbiauh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gt2jemqavea.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gt2livnxxvs.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenjidiqi.icu/Article/details/gt2ebmjajnk.html

Go:   encoding/gob
来源：http://dali.hfpthk.cn/Article/details/gt2bvasrxyc.html

Ruby: Marshal.dump(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2bggzgzmb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gt2aokzeleu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2svwxejkl.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kbutbsck.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2kjxndeci.html

[L01] 发送 GET 请求
来源：http://dali.gotoacloud.top/Article/details/gt2czyofuds.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.snrcjt.cn/Article/details/gt2mvazzytt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fzhhl.top/Article/details/gt2vmflahld.html

JS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gt2gsnaqqhi.html

TS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gt2lvklufxq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuanzx.com/Article/details/gt2dezucdtt.html

Go:   resp, err := http.Get(url)
来源：http://dali.tianlin.xyz/Article/details/gt2rzidsyzr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eisifble.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kntfftkn.html

[L02] 发送 POST JSON
来源：http://dali.havefunace.top/Article/details/gt2jsdnbiof.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xylfe.cn/Article/details/gt2umteeojv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cheryme.top/Article/details/gt2zcgxdtiq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gt2saklpnhb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2rmqcnvxd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jlsjyb.cn/Article/details/gt2vfcqxiob.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuetiantiany.cn/Article/details/gt2ejryprgl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yvedp.cn/Article/details/gt2pcvfelbg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.havefunace.top/Article/details/gt2haacudlu.html

[L03] 设置自定义请求头
来源：http://dali.c1oappe.top/Article/details/gt2cevddhbl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnqzz.top/Article/details/gt2nxzbzwne.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenzaomai.com/Article/details/gt2pbwlosof.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gt2spxsgrvb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gt2fnnhiypw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sysykeji.top/Article/details/gt2jmibqrtw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gt2vhtmfzti.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.c1oappe.top/Article/details/gt2ccyjxjom.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gt2goqumjga.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2vegczsbc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2otavexhd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuanzx.com/Article/details/gt2qcomvdca.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gt2uhcrnftq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gt2wksijroy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnxiangtu.top/Article/details/gt2mhprwqhb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aizwys.cn/Article/details/gt2budmihgb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gogol.net.cn/Article/details/gt2mhsljhvv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jiagoushi.top/Article/details/gt2vslgaaoy.html

[L05] 上传文件（multipart）
来源：http://dali.feifeiyinyue.top/Article/details/gt2cmrzneiy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jcdhvijk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.316326.xyz/Article/details/gt2hdamgzdw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gt2nnaurjzo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gt2oneqsgnx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.meibo888.top/Article/details/gt2osmodqnj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgfzy.top/Article/details/gt2oyjhyuff.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cqqwz.cn/Article/details/gt2fxvhelwh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2symhocma.html

[L06] 解析响应为 JSON
来源：http://dali.yuanzhike.top/Article/details/gt2qzcwukyy.html

Py:   resp.json()
来源：http://dali.nanxinkj.top/Article/details/gt2dtpkanbu.html

PHP:  json_decode($body, true);
来源：http://dali.shuidangran.top/Article/details/gt2edpppvcd.html

JS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gt2optlqdeh.html

TS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kzrqicvg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jianghu66.top/Article/details/gt2sbbcfqqz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gogol.net.cn/Article/details/gt2fkyayycg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cashguo.top/Article/details/gt2hwazdtua.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cheryme.top/Article/details/gt2zjpueuws.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gt2leoipqec.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenjidiqi.icu/Article/details/gt2nsavqfdg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhongyouzk.top/Article/details/gt2guxbiqln.html

JS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gt2eltldvnt.html

TS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gt2qsvxslwh.html

Java: resp.statusCode()
来源：http://dali.hnxiangtu.top/Article/details/gt2cajkofgr.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gt2swmksbrb.html

Ruby: resp.code.to_i
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ujarlkea.html

C#:   (int)resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gt2dkzhvjtv.html

[L08] 并发请求多个地址
来源：http://dali.chenjidiqi.icu/Article/details/gt2vhtvqivu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sufxvd.cn/Article/details/gt2scsirwuu.html

PHP:  curl_multi_init() 系列
来源：http://dali.xylfe.cn/Article/details/gt2luvzaeuw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gt2akkdeoru.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gt2sqclhhoh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.mhx1999.top/Article/details/gt2kgzemahb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.vqdsnc.cn/Article/details/gt2yoqkmuky.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yrwetvkw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gotoacloud.top/Article/details/gt2czfgnksb.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2oxmzkrpv.html

M. 命令行 / 进程 / 环境
来源：http://dali.quarkkingdee.top/Article/details/gt2mdsefzld.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2nuwbiwom.html

[M01] 读取命令行参数
来源：http://dali.gogol.net.cn/Article/details/gt2jkhfwsew.html

Py:   sys.argv[1:]
来源：http://dali.zhoulong.xyz/Article/details/gt2nnkqjrar.html

PHP:  $argv;  $argc;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jeaoroya.html

JS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gt2yzwqusbk.html

TS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wlofaesb.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gt2doaxfnto.html

Go:   os.Args[1:]
来源：http://dali.nanxinkj.top/Article/details/gt2ctcrsfyz.html

Ruby: ARGV
来源：http://dali.smart0.xyz/Article/details/gt2tukzngrn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gt2btupedhr.html

[M02] 读取环境变量
来源：http://dali.yonumen.top/Article/details/gt2yaeqsful.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gt2xpksjnhr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gt2kqlkjkqw.html

JS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gt2jkuwhqlo.html

TS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gt2zpqlmflu.html

Java: System.getenv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gt2kagvopuv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gt2wgylwche.html

Ruby: ENV["HOME"]
来源：http://dali.andypj.xyz/Article/details/gt2czksahtv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gt2rbqvrrsj.html

[M03] 执行外部命令
来源：http://dali.hnxiangtu.top/Article/details/gt2ntddksfj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.9152youxi.cn/Article/details/gt2wysaenot.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daria6918.cn/Article/details/gt2bskjuxjd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gt2gshnjnqn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gt2ggqxmlpm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yvedp.cn/Article/details/gt2zlngwlax.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ynwabysf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tanke756.top/Article/details/gt2nwyfekiq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fengsongda.top/Article/details/gt2lirzbspz.html

[M04] 获取当前工作目录
来源：http://dali.jqgfzy.top/Article/details/gt2uynqdgae.html

Py:   os.getcwd()
来源：http://dali.fengsongda.top/Article/details/gt2lpzdfcgy.html

PHP:  getcwd();
来源：http://dali.ppjwa.cn/Article/details/gt2idngauqu.html

JS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gt2iwrjurqt.html

TS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gt2ccnsqaml.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ehwqpu.com/Article/details/gt2ribjowyw.html

Go:   os.Getwd()
来源：http://dali.zdqjudy.top/Article/details/gt2ygibherg.html

Ruby: Dir.pwd
来源：http://dali.haohaochexian.top/Article/details/gt2wtjmyjmj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sysykeji.top/Article/details/gt2lxxkskpv.html

[M05] 设置退出码
来源：http://dali.zhoulong.xyz/Article/details/gt2kebwwfgt.html

Py:   sys.exit(1)
来源：http://dali.meibo888.top/Article/details/gt2boygtmrm.html

PHP:  exit(1);
来源：http://dali.aizwys.cn/Article/details/gt2fzffykit.html

JS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2mhqsrbew.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fpmqplgy.html

Java: System.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2ykzsdlfb.html

Go:   os.Exit(1)
来源：http://dali.nanxinkj.top/Article/details/gt2uswfwbad.html

Ruby: exit 1
来源：http://dali.ydzc1.top/Article/details/gt2kxehwnzz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhixingplan.top/Article/details/gt2bbrsewje.html

[M06] 向标准错误输出
来源：http://dali.zhixingplan.top/Article/details/gt2ngiqttke.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gt2dvqkpqog.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hddivrxn.html

JS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gt2vwxodivv.html

TS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tekbehym.html

Java: System.err.println("err")
来源：http://dali.yj202588.top/Article/details/gt2nojsnovu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xziqi.cn/Article/details/gt2upgievxn.html

Ruby: warn "err"
来源：http://dali.gzhubu.top/Article/details/gt2rhsrplwu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zycfv.cn/Article/details/gt2meyqzcxj.html

[M07] 判断是否为主入口
来源：http://dali.dianchejie.cn/Article/details/gt2yiprnnmw.html

Py:   if __name__ == "__main__":
来源：http://dali.hammf.cn/Article/details/gt2hqiyjsfv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhixingplan.top/Article/details/gt2pexvfuum.html

JS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gt2znqxzkxx.html

TS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gt2ryispwpe.html

Java: public static void main(String[] args)
来源：http://dali.cdnleiting.top/Article/details/gt2mzppxacn.html

Go:   func main()
来源：http://dali.cucudq.cn/Article/details/gt2okturhbc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.bjfxy.top/Article/details/gt2fxbredvm.html

C#:   static void Main(string[] args)
来源：http://dali.daxiang520.top/Article/details/gt2sdtzqqal.html

[M08] 获取系统与运行时信息
来源：http://dali.dashuyun.cn/Article/details/gt2tnhuasfj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenlongwang.top/Article/details/gt2wyimjukj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.9152youxi.cn/Article/details/gt2mchmkpqy.html

JS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gt2kdbhwyvw.html

TS:   process.platform;  process.version
来源：http://dali.hongshengwenyu.top/Article/details/gt2zprurgqp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xziqi.cn/Article/details/gt2hoofkdcm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.meibo888.top/Article/details/gt2eaymmvyl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xanxfhgn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.quarkkingdee.top/Article/details/gt2jafqbnnz.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2vqbbgmqs.html

N. 数据结构与算法
来源：http://dali.jlsjyb.cn/Article/details/gt2okdofync.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2vhooiakj.html

[N01] 二分查找（有序数组）
来源：http://dali.zhongyouzk.top/Article/details/gt2ovuvzqxp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2frjubrtd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj202588.top/Article/details/gt2fspmfmxf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gt2eabcawzj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gt2ivyyleko.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vufxayqm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sweek.top/Article/details/gt2akrbnojy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuanzhike.top/Article/details/gt2byxrszfg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2szdztvbx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vlgzzgid.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gt2orheurju.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jianghu66.top/Article/details/gt2uuloradm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gt2fidcdbqg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gt2ofkrjbke.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnqzz.top/Article/details/gt2cizaaapn.html

Go:   slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gt2exktzsba.html


<!-- 参考信息 -->