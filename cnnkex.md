代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gt2stgmesle.html

[J08] 提取年月日与星期
来源：http://dali.hongshengwenyu.top/Article/details/gt2oliglwbb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dashuyun.cn/Article/details/gt2ssqenhaz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aizwys.cn/Article/details/gt2mmhvaklr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hfpthk.cn/Article/details/gt2ipuhlvtc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sxryk.cn/Article/details/gt2rygpcpim.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cdnleiting.top/Article/details/gt2udmjoxem.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnqzz.top/Article/details/gt2dddwmdro.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.meibo888.top/Article/details/gt2ymotypks.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.bjfxy.top/Article/details/gt2kmvouhtl.html

[J09] 时区处理
来源：http://dali.0kj1m.cn/Article/details/gt2vbqrmbgs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fzhhl.top/Article/details/gt2cofrgfwn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jqlhwbxi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gt2adbbsuxz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gt2seokwxtf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kqzomcce.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhixingplan.top/Article/details/gt2bwxegpxo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tanke756.top/Article/details/gt2wcqlrvsz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuanzhike.top/Article/details/gt2rojssozw.html

[J10] 取今天 / 本月第一天
来源：http://dali.aizwys.cn/Article/details/gt2svestmeb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yvedp.cn/Article/details/gt2msmrghgi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gt2ouzkrwxg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gt2muozajzk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2slncerwm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangdashe.top/Article/details/gt2oexynlbm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenzaomai.com/Article/details/gt2kqtpwcxr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hongshengwenyu.top/Article/details/gt2sfzahbft.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenzaomai.com/Article/details/gt2uwgfzekl.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2tbqbnowj.html

K. JSON 与序列化
来源：http://dali.shuidangran.top/Article/details/gt2jcdopcik.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2vomopsqd.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2cwbydwgo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gt2zvjkwllz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gt2ezpjufhn.html

JS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oxruhqzm.html

TS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gt2wrrquute.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sxryk.cn/Article/details/gt2cacjshna.html

Go:   json.Marshal(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2chehnneo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hkhhtmbf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2objnwgre.html

[K02] JSON 字符串转对象
来源：http://dali.sysykeji.top/Article/details/gt2tdbpxfqr.html

Py:   json.loads(s)
来源：http://dali.jyoumei.cn/Article/details/gt2bztrxrkf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nwbrower.top/Article/details/gt2tdnnrgvr.html

JS:   JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gt2vbdkjnja.html

TS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gt2hosyuftl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xinyue.icu/Article/details/gt2pvpbhpsn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gt2eyqphjua.html

Ruby: JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gt2nwzzipxu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aibaodan.cn/Article/details/gt2yaxhoqca.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhongyouzk.top/Article/details/gt2lnojttct.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2igmynqsl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258.top/Article/details/gt2yiazpgcj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ydzc1.top/Article/details/gt2xzbqckvv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2evmmmhyo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2lusiizue.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cqqwz.cn/Article/details/gt2hhccrmhr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2apnhkhbd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhixingplan.top/Article/details/gt2jbyadyxg.html

[K04] 读取 JSON 文件
来源：http://dali.jqgufenzy.top/Article/details/gt2nnntslwh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sufxvd.cn/Article/details/gt2oxeaedos.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.mhx1999.top/Article/details/gt2trvrcodt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xziqi.cn/Article/details/gt2oabbugid.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gt2zznpzkew.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gt2rrdrehrn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gt2csltpqli.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yonumen.top/Article/details/gt2zstwbvvz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yvedp.cn/Article/details/gt2htrzjxqq.html

[K05] 深拷贝对象
来源：http://dali.zhengqikj.top/Article/details/gt2wqryqcvs.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mimonsah.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gt2xyckovxe.html

JS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2ogsisnjp.html

TS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gt2zmxtahnv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ybcxt.top/Article/details/gt2pwyywyvb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenlongwang.top/Article/details/gt2giootzmr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenlongwang.top/Article/details/gt2flkcnmkb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gogol.net.cn/Article/details/gt2wvcloryp.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gt2fmstawnd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2axhyxgof.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pycfn.com/Article/details/gt2tmuklrpy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gt2wpqddwml.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gt2namdkaog.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cheryme.top/Article/details/gt2ddsfredm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gt2ufftqhcr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gt2brgfufcq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gt2ybpflosd.html

[K07] 进制转换
来源：http://dali.zhoulong.xyz/Article/details/gt2qaxnptxu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2woabbymm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.svipenyu.cn/Article/details/gt2izwmxxmu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2tfqdeqhv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gt2ezmjdcxh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2rhbvpvcm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shangyingyoupin.top/Article/details/gt2roiqcfvo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jiagoushi.top/Article/details/gt2lrwrytpc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2chdszety.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.0kj1m.cn/Article/details/gt2vasqzoww.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2xwdgsvmq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2olndtsdc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gt2ziksjlfu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gt2ywxybzlw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wuhmbqcm.html

Go:   encoding/gob
来源：http://dali.havefunace.top/Article/details/gt2lxlsbwtu.html

Ruby: Marshal.dump(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2nubgrilk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gt2rkesqqwm.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2blqxetxj.html

L. 网络请求
来源：http://dali.zhongyouzk.top/Article/details/gt2qeaiacqd.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2wdiqbtrz.html

[L01] 发送 GET 请求
来源：http://dali.c1oappe.top/Article/details/gt2oxsvbwpb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shzxlz.cn/Article/details/gt2wavwcgku.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guowangkeji.top/Article/details/gt2oqrcfsgo.html

JS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gt2vuxuyftk.html

TS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gt2pfrkmqol.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangshuangyany.cn/Article/details/gt2owttobxt.html

Go:   resp, err := http.Get(url)
来源：http://dali.daria6918.cn/Article/details/gt2cmcukfze.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tian-w.cn/Article/details/gt2tzdgdhld.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2qealayhx.html

[L02] 发送 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gt2mzphnqib.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gt2cdzkjooo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cdnleiting.top/Article/details/gt2sumhykiq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gt2tgwmcfyn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gt2qukxvfbk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.havefunace.top/Article/details/gt2yczwuktt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cqqwz.cn/Article/details/gt2xnmuwytx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cucudq.cn/Article/details/gt2qyfwohfk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hnqzz.top/Article/details/gt2xjttpaqf.html

[L03] 设置自定义请求头
来源：http://dali.chenlongwang.top/Article/details/gt2vqqomemc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guannengcc.top/Article/details/gt2anserzxw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258888.top/Article/details/gt2dtdeojel.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zycfv.cn/Article/details/gt2ggsmffqh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gt2hcasopax.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dashuyun.cn/Article/details/gt2kkgdrrsy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gt2ygjxlwwa.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinqigfzy.top/Article/details/gt2qmonvfog.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gt2ywcfcvew.html

[L04] 设置超时
来源：http://dali.yuxming.cn/Article/details/gt2csoxtcko.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhoulong.xyz/Article/details/gt2xcdcldjw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gaohongyu789.top/Article/details/gt2miucxgwg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gt2bxzfpjoa.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gt2jeilunxt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cqqwz.cn/Article/details/gt2wmbxziqs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.9152youxi.cn/Article/details/gt2pqpwonpi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wkzgluma.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhiwuduotai.top/Article/details/gt2rfeydvqi.html

[L05] 上传文件（multipart）
来源：http://dali.yuanzhike.top/Article/details/gt2onmolhtx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnxiangtu.top/Article/details/gt2usmatbdx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tanke756.top/Article/details/gt2ccsvacyi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gt2oucwrtss.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gt2weeclabl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aizwys.cn/Article/details/gt2mhhutqrn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xinyue.icu/Article/details/gt2lcqoskzy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yonumen.top/Article/details/gt2hgvhiubv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2ugzsqjun.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iffiiyyg.html

Py:   resp.json()
来源：http://dali.smart0.xyz/Article/details/gt2daonkhtj.html

PHP:  json_decode($body, true);
来源：http://dali.sysykeji.top/Article/details/gt2zwebdioz.html

JS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zyebfqyi.html

TS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gt2utxrrgwh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xziqi.cn/Article/details/gt2hvfgycxq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2acsjftoz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.feifeiyinyue.top/Article/details/gt2alvqabkj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yueranfly.top/Article/details/gt2wbatutfh.html

[L07] 处理 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gt2ayeypfqa.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gogol.net.cn/Article/details/gt2xiljadyf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jiagoushi.top/Article/details/gt2ygzgsqco.html

JS:   resp.ok;  resp.status
来源：http://dali.cqqwz.cn/Article/details/gt2qacuhziy.html

TS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gt2zqzavegg.html

Java: resp.statusCode()
来源：http://dali.zdqjudy.top/Article/details/gt2dpllgynz.html

Go:   resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gt2tlpcxzwy.html

Ruby: resp.code.to_i
来源：http://dali.gogol.net.cn/Article/details/gt2pqkjaptj.html

C#:   (int)resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gt2dhjidkze.html

[L08] 并发请求多个地址
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wikslfee.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhengqikj.top/Article/details/gt2bfveufih.html

PHP:  curl_multi_init() 系列
来源：http://dali.shuidangran.top/Article/details/gt2pkhazewr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gt2hiigxblj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gt2cbgakrqf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gt2xfttrzpy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.haohaochexian.top/Article/details/gt2fpolltgo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tian-w.cn/Article/details/gt2swxzifbn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cheryme.top/Article/details/gt2jncntpcc.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2tabgqphl.html

M. 命令行 / 进程 / 环境
来源：http://dali.0kj1m.cn/Article/details/gt2rcegemlh.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2eqcfczsy.html

[M01] 读取命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2skcfomqx.html

Py:   sys.argv[1:]
来源：http://dali.hammf.cn/Article/details/gt2ugasvaen.html

PHP:  $argv;  $argc;
来源：http://dali.hfpthk.cn/Article/details/gt2mfngzeca.html

JS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gt2ieprznrm.html

TS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gt2qthupepe.html

Java: args 数组（main 方法参数）
来源：http://dali.cashguo.top/Article/details/gt2susnjqwu.html

Go:   os.Args[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gt2lzkyjrin.html

Ruby: ARGV
来源：http://dali.chenjidiqi.icu/Article/details/gt2xyvdnzpf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gt2vyodeusv.html

[M02] 读取环境变量
来源：http://dali.smart0.xyz/Article/details/gt2lgntwbmu.html

Py:   os.environ.get("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2loikjvmn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gt2akdwrnuf.html

JS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gt2lumnojoz.html

TS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gt2jdyouglz.html

Java: System.getenv("HOME")
来源：http://dali.xylfe.cn/Article/details/gt2kxoyuxox.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2ofmrelpx.html

Ruby: ENV["HOME"]
来源：http://dali.hysaishi.cn/Article/details/gt2xtjfilfg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sufxvd.cn/Article/details/gt2emyfkujs.html

[M03] 执行外部命令
来源：http://dali.ybcxt.top/Article/details/gt2qpwhokzw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigufen.top/Article/details/gt2sgpzveev.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jyoumei.cn/Article/details/gt2aoalzlfq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2hppkxbsl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gt2kryfrewy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhoulong.xyz/Article/details/gt2bngkmwde.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ppjwa.cn/Article/details/gt2mmygjfbk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aibaodan.cn/Article/details/gt2zquvpmim.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cqqwz.cn/Article/details/gt2bbevlcon.html

[M04] 获取当前工作目录
来源：http://dali.xuetiantiany.cn/Article/details/gt2yzdxbcbr.html

Py:   os.getcwd()
来源：http://dali.xziqi.cn/Article/details/gt2fscmipjl.html

PHP:  getcwd();
来源：http://dali.meibo888.top/Article/details/gt2ktlworkt.html

JS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gt2bukzbopw.html

TS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gt2zcjeltmx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tianlin.xyz/Article/details/gt2lqxogihd.html

Go:   os.Getwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2cwvvwvyx.html

Ruby: Dir.pwd
来源：http://dali.guowangkeji.top/Article/details/gt2cndsxumu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.havefunace.top/Article/details/gt2fzxzzgqs.html

[M05] 设置退出码
来源：http://dali.xuanzx.com/Article/details/gt2yghjwazp.html

Py:   sys.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2mjqlnffs.html

PHP:  exit(1);
来源：http://dali.yuxming.cn/Article/details/gt2bacqywos.html

JS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sdrsbult.html

TS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gt2vuofgvzj.html

Java: System.exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2ipmwzifn.html

Go:   os.Exit(1)
来源：http://dali.daxiang520.top/Article/details/gt2shnytoxr.html

Ruby: exit 1
来源：http://dali.yuanzhike.top/Article/details/gt2nenfdbbm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.pengpengdd.cyou/Article/details/gt2lpsctyrp.html

[M06] 向标准错误输出
来源：http://dali.yueranfly.top/Article/details/gt2blxcausn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daria6918.cn/Article/details/gt2ehgdtfab.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhoulong.xyz/Article/details/gt2lbamtbis.html

JS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gt2cjxgsvrt.html

TS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2ymlxqapq.html

Java: System.err.println("err")
来源：http://dali.jqgufenzy.top/Article/details/gt2tskbkyfb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fwgpbout.html

Ruby: warn "err"
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqxauwar.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.redwolf501.top/Article/details/gt2glaqbjvc.html

[M07] 判断是否为主入口
来源：http://dali.tanke756.top/Article/details/gt2ylsohldu.html

Py:   if __name__ == "__main__":
来源：http://dali.316326.xyz/Article/details/gt2bvwntefz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2psdplnec.html

JS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gt2rcunrryh.html

TS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gt2ayuryrhv.html

Java: public static void main(String[] args)
来源：http://dali.ydzc1.top/Article/details/gt2lpybkefm.html

Go:   func main()
来源：http://dali.cashguo.top/Article/details/gt2nfzzdgmj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhoulong.xyz/Article/details/gt2lozxqxva.html

C#:   static void Main(string[] args)
来源：http://dali.ybcxt.top/Article/details/gt2ttjawlbs.html

[M08] 获取系统与运行时信息
来源：http://dali.yj202588.top/Article/details/gt2pkiulvdg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yueranfly.top/Article/details/gt2lvoalcnd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nwbrower.top/Article/details/gt2tsvlkppd.html

JS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gt2ymrcytow.html

TS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gt2tuxwhrmq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jyoumei.cn/Article/details/gt2whtbdesd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuetiantiany.cn/Article/details/gt2exvduzia.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sysykeji.top/Article/details/gt2ztmjihgw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daria6918.cn/Article/details/gt2sildcakr.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2dcepivjo.html

N. 数据结构与算法
来源：http://dali.zhoulong.xyz/Article/details/gt2drhdayjh.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2nfbphpaz.html

[N01] 二分查找（有序数组）
来源：http://dali.xinyue.icu/Article/details/gt2kdiafdyd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2amumynfe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ebzmsoly.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gt2qmnpxpws.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gt2knfvhmnx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2hfupcfaj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gt2hhzqyaeg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.316326.xyz/Article/details/gt2xjseedft.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pjrxcsfl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigfzy.top/Article/details/gt2pthzmwwy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gt2qpmxpujb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aibaodan.cn/Article/details/gt2ddtczjsk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gt2svswzzto.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rvfzxbxn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zdqjudy.top/Article/details/gt2xcapahlz.html

Go:   slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gt2xvldxlya.html

Ruby: arr.sort
来源：http://dali.yj20258888.top/Article/details/gt2tdwecahk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pnxajcae.html

[N03] 快速排序（分治示例）
来源：http://dali.hnqzz.top/Article/details/gt2oeodfnjj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dashuyun.cn/Article/details/gt2wfcxkvtn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jiagoushi.top/Article/details/gt2wiujzyuy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gt2nrldtkls.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gt2pxtutaul.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuanzhike.top/Article/details/gt2ooadcbuv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuetiantiany.cn/Article/details/gt2cktlnidh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuetiantiany.cn/Article/details/gt2dqqmohqi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xziqi.cn/Article/details/gt2evsfqgqi.html

[N04] 斐波那契数列
来源：http://dali.sxryk.cn/Article/details/gt2dhtysyov.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gt2ttyvrkso.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258.top/Article/details/gt2llyrojqu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gt2giegqful.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yrubwksq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gt2pqbzcyxl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cucudq.cn/Article/details/gt2mkmzxrgl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2liakhzjx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gt2ftrvskis.html

[N05] 最大公约数
来源：http://dali.wangshuangyany.cn/Article/details/gt2hhszlvyp.html

Py:   math.gcd(a, b)
来源：http://dali.iojbl.cn/Article/details/gt2gcodnuya.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gt2ahhphips.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gt2ybtswgqm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gt2qcoyohgu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhirohdm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxuanxn.top/Article/details/gt2idwhqvqg.html

Ruby: a.gcd(b)
来源：http://dali.jlsjyb.cn/Article/details/gt2mwvdqduo.html


<!-- 参考信息 -->