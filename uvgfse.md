代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258888.top/Article/details/gt2hwlwxhod.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258888.top/Article/details/gt2ntmnhmdy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guowangkeji.top/Article/details/gt2lchylnnf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guowangkeji.top/Article/details/gt2knufdpwa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ivvv.top/Article/details/gt2cckirrap.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shuidangran.top/Article/details/gt2hjbcrvnb.html

[J09] 时区处理
来源：http://dali.shangyingyoupin.top/Article/details/gt2bzgmujyu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuanzx.com/Article/details/gt2tqzqhujt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hammf.cn/Article/details/gt2clreydqd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ttdeypem.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gt2vpqgmewf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258888.top/Article/details/gt2esvaoxtp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gotoacloud.top/Article/details/gt2ourhwhxn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.316326.xyz/Article/details/gt2cmjgjnkp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zialgtfo.html

[J10] 取今天 / 本月第一天
来源：http://dali.jianghu66.top/Article/details/gt2dubzsswf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fengsongda.top/Article/details/gt2odeydxhs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gzhubu.top/Article/details/gt2ihlfthbs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tanke756.top/Article/details/gt2erhynogs.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tian-w.cn/Article/details/gt2sqnlxmkd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lsodhfoq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cashguo.top/Article/details/gt2kohztood.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cqqwz.cn/Article/details/gt2rloguuew.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sweek.top/Article/details/gt2ymuaixhn.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2kvuvamiz.html

K. JSON 与序列化
来源：http://dali.gotoacloud.top/Article/details/gt2ysqwvfvg.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2znzxhdap.html

[K01] 对象转 JSON 字符串
来源：http://dali.hywenlv.cn/Article/details/gt2gdrcsyqo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gt2laindhbz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gt2sqwflmcj.html

JS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gtomtqxy.html

TS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2xsvzbbqr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2eonwblky.html

Go:   json.Marshal(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2geoowbmg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.meibo888.top/Article/details/gt2pqwmvxds.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zycfv.cn/Article/details/gt2lusweeax.html

[K02] JSON 字符串转对象
来源：http://dali.redwolf501.top/Article/details/gt2vloabokh.html

Py:   json.loads(s)
来源：http://dali.yj202588.top/Article/details/gt2mqjmaviz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cheryme.top/Article/details/gt2biegdbuy.html

JS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gt2khfiewrq.html

TS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gt2iwllofne.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigufen.top/Article/details/gt2gjrbxwiq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhengqikj.top/Article/details/gt2ewalhofg.html

Ruby: JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gt2tmehqvdb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yueranfly.top/Article/details/gt2qehdrgjb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.havefunace.top/Article/details/gt2dnieqosb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nytwkopj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xylfe.cn/Article/details/gt2dppjltkv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2qpopkbpx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2zqdqzkha.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2unvddrpf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ydzc1.top/Article/details/gt2sxzvwzrr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aizwys.cn/Article/details/gt2jflnskof.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuanzx.com/Article/details/gt2sxfthdpl.html

[K04] 读取 JSON 文件
来源：http://dali.hysaishi.cn/Article/details/gt2kssrhezj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cdnleiting.top/Article/details/gt2nlnxxalk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.0kj1m.cn/Article/details/gt2qksbhdjb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gt2ddebuuhh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gt2ahdzrgyo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gt2gtvemzie.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gt2mossixol.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gt2gwmjwnne.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yueranfly.top/Article/details/gt2ybmsjaud.html

[K05] 深拷贝对象
来源：http://dali.hfpthk.cn/Article/details/gt2rbxcpiyp.html

Py:   copy.deepcopy(obj)
来源：http://dali.cheryme.top/Article/details/gt2buvkqmzo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fengsongda.top/Article/details/gt2qcfjgjne.html

JS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gt2ceyatwwc.html

TS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gt2mtirxlgk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daria6918.cn/Article/details/gt2hynrbqqb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fzhhl.top/Article/details/gt2wjtlaiog.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daxiang520.top/Article/details/gt2lbngdlpd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigfzy.top/Article/details/gt2rjqcurce.html

[K06] 解析 URL 查询串
来源：http://dali.jlsjyb.cn/Article/details/gt2oldlcxqk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gt2bftsabuy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gotoacloud.top/Article/details/gt2ipufvors.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gt2vqfbtllx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gt2dqowfumu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gt2lkxjgznv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wbcxcvwi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gt2qppfqxep.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gt2yxajznax.html

[K07] 进制转换
来源：http://dali.nanxuanxn.top/Article/details/gt2ogyhltth.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gt2unstgsqw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.mhx1999.top/Article/details/gt2fukjzwcc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2qvkhpyfz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2wdydzrcd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gt2hbjojlaq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuanzx.com/Article/details/gt2allevkoa.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hfpthk.cn/Article/details/gt2fevkisps.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2ottcirec.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.mhx1999.top/Article/details/gt2fdztgryn.html

Py:   pickle.dumps(obj)
来源：http://dali.sxryk.cn/Article/details/gt2yizgazdw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2yclekxvk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gt2ersxbodq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gt2tadohpnu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.havefunace.top/Article/details/gt2ygrttcwm.html

Go:   encoding/gob
来源：http://dali.fengsongda.top/Article/details/gt2iekpwlih.html

Ruby: Marshal.dump(obj)
来源：http://dali.iojbl.cn/Article/details/gt2msvdevea.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gt2wlhheuuj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2neehfjgh.html

L. 网络请求
来源：http://dali.hnxiangtu.top/Article/details/gt2tomlxjmo.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2joxhddey.html

[L01] 发送 GET 请求
来源：http://dali.dashuyun.cn/Article/details/gt2wdlhwrvr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ynerfgfo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxuanxn.top/Article/details/gt2ohkgvqbw.html

JS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gt2rnpaxwlt.html

TS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gt2kokpdchw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cashguo.top/Article/details/gt2yiiyovvu.html

Go:   resp, err := http.Get(url)
来源：http://dali.fzhhl.top/Article/details/gt2japbsjcn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhongyouzk.top/Article/details/gt2gjhxxrqt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenlongwang.top/Article/details/gt2eakgxune.html

[L02] 发送 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gt2qkwdrdhj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tian-w.cn/Article/details/gt2faqwgzks.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuxming.cn/Article/details/gt2fclpkmyf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2szavcsqu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shzxlz.cn/Article/details/gt2wvxeuosk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhongyouzk.top/Article/details/gt2xpxlloip.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jlsjyb.cn/Article/details/gt2ybpfpwqv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhixingplan.top/Article/details/gt2wuvzvxyb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daxiang520.top/Article/details/gt2tqgzkkrz.html

[L03] 设置自定义请求头
来源：http://dali.cqqwz.cn/Article/details/gt2tuchrqaz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258888.top/Article/details/gt2hqatvvdw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigfzy.top/Article/details/gt2aukhbzet.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gt2lkrjrmge.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gotoacloud.top/Article/details/gt2svsmjqkq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sweek.top/Article/details/gt2bwgodhiu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gt2iamqufhf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zdqjudy.top/Article/details/gt2sfrbqcwr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gt2znefbxcc.html

[L04] 设置超时
来源：http://dali.yuxming.cn/Article/details/gt2woqalgyi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yanxiufei.cn/Article/details/gt2koinpgus.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gt2vtsessgz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gt2gxnvqhta.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnqzz.top/Article/details/gt2pwbnpohp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yongpay.top/Article/details/gt2ubhyawof.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shangyingyoupin.top/Article/details/gt2bgkgsbar.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xinyue.icu/Article/details/gt2yigbqsco.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aizwys.cn/Article/details/gt2prchtdon.html

[L05] 上传文件（multipart）
来源：http://dali.xinyue.icu/Article/details/gt2tbgykgza.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hfpthk.cn/Article/details/gt2minelwwp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cheryme.top/Article/details/gt2visbvisl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gt2dcvggkfy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gt2ojatqpfq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxuanxn.top/Article/details/gt2pgajhmab.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.kuanghao11.cn/Article/details/gt2ttglwduf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.bjfxy.top/Article/details/gt2pdllbhlx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.havefunace.top/Article/details/gt2gsiaexfn.html

[L06] 解析响应为 JSON
来源：http://dali.shzxlz.cn/Article/details/gt2zzopiwka.html

Py:   resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gt2gbxgqfom.html

PHP:  json_decode($body, true);
来源：http://dali.c1oappe.top/Article/details/gt2nqjzqpnf.html

JS:   await resp.json()
来源：http://dali.smart0.xyz/Article/details/gt2ufrkciiu.html

TS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gt2olsbtvuo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gt2tlirjcnc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aizwys.cn/Article/details/gt2vkugszoe.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yangfankeji.com/Article/details/gt2uingjmny.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxuanxn.top/Article/details/gt2iulouvgi.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gt2lcjbsldm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sweek.top/Article/details/gt2iauvydbq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sysykeji.top/Article/details/gt2gpwznrcj.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gt2szalpyuj.html

TS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gt2duhozcke.html

Java: resp.statusCode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aakhphkn.html

Go:   resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gt2hvyjfpfe.html

Ruby: resp.code.to_i
来源：http://dali.daxiang520.top/Article/details/gt2mafsswsu.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gt2mwlxwwxj.html

[L08] 并发请求多个地址
来源：http://dali.hysaishi.cn/Article/details/gt2skwobxml.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yueranfly.top/Article/details/gt2kgrctsvx.html

PHP:  curl_multi_init() 系列
来源：http://dali.cashguo.top/Article/details/gt2khwfbbvc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gt2aqwseeqx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gt2ohncgvcq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.haohaochexian.top/Article/details/gt2dhwurivy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tanke756.top/Article/details/gt2hizjkiei.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.iojbl.cn/Article/details/gt2yylmmzdo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gt2ofimdwbf.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2atjsbvtk.html

M. 命令行 / 进程 / 环境
来源：http://dali.snrcjt.cn/Article/details/gt2sgbkwobr.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2gfpdthxr.html

[M01] 读取命令行参数
来源：http://dali.guannengcc.top/Article/details/gt2zjufbgaj.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gt2xzyfygyo.html

PHP:  $argv;  $argc;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fwiaybol.html

JS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gt2imvbslag.html

TS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gt2gnzsxwyh.html

Java: args 数组（main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gt2ekvxcnnl.html

Go:   os.Args[1:]
来源：http://dali.zycfv.cn/Article/details/gt2mdwyxpwt.html

Ruby: ARGV
来源：http://dali.bjfxy.top/Article/details/gt2bhvdkxuc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gt2rckxmpue.html

[M02] 读取环境变量
来源：http://dali.gzhubu.top/Article/details/gt2tpvnnepe.html

Py:   os.environ.get("HOME")
来源：http://dali.hfpthk.cn/Article/details/gt2iyxbbcje.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gt2eeppccrj.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vktdufcg.html

TS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gt2dzxywrlq.html

Java: System.getenv("HOME")
来源：http://dali.xuanzx.com/Article/details/gt2yzyguuig.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gt2ljtitkmf.html

Ruby: ENV["HOME"]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxofmbtc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2itizjayf.html

[M03] 执行外部命令
来源：http://dali.iojbl.cn/Article/details/gt2cgywgmad.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258.top/Article/details/gt2vbcrtrvt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.vqdsnc.cn/Article/details/gt2lvsoropz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gt2zatccuow.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gt2thwdxrsq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yvedp.cn/Article/details/gt2idyflmmx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhengqikj.top/Article/details/gt2bbwojcij.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tian-w.cn/Article/details/gt2swzhwkqb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hammf.cn/Article/details/gt2rzbkjupr.html

[M04] 获取当前工作目录
来源：http://dali.wangshuangyany.cn/Article/details/gt2ryojbyyi.html

Py:   os.getcwd()
来源：http://dali.xuanzx.com/Article/details/gt2bwhjiyip.html

PHP:  getcwd();
来源：http://dali.bjfxy.top/Article/details/gt2flmnlvvj.html

JS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gt2kpqdbqlz.html

TS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gt2wmbuygsf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hywenlv.cn/Article/details/gt2rkcubdbb.html

Go:   os.Getwd()
来源：http://dali.bjfxy.top/Article/details/gt2djslipch.html

Ruby: Dir.pwd
来源：http://dali.xuanzx.com/Article/details/gt2etarrgcu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjzpnbp.html

[M05] 设置退出码
来源：http://dali.jinqigufen.top/Article/details/gt2zzniwths.html

Py:   sys.exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2qhgmiyqg.html

PHP:  exit(1);
来源：http://dali.pycfn.com/Article/details/gt2pwpbipai.html

JS:   process.exit(1)
来源：http://dali.guannengcc.top/Article/details/gt2mjlxrbya.html

TS:   process.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rhgdurmv.html

Java: System.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2ylmqhdht.html

Go:   os.Exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2qldgobwb.html

Ruby: exit 1
来源：http://dali.hfpthk.cn/Article/details/gt2onwlabtu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.bjfxy.top/Article/details/gt2nulgllcx.html

[M06] 向标准错误输出
来源：http://dali.sxryk.cn/Article/details/gt2ntbompzu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxinkj.top/Article/details/gt2hgveechr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.9152youxi.cn/Article/details/gt2xwuikegw.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gt2xgfnacsj.html

TS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gt2oslkhsqc.html

Java: System.err.println("err")
来源：http://dali.shuidangran.top/Article/details/gt2vanczepl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.bjfxy.top/Article/details/gt2wqfrpbun.html

Ruby: warn "err"
来源：http://dali.316326.xyz/Article/details/gt2dusovtml.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2adrnqaev.html

[M07] 判断是否为主入口
来源：http://dali.chenjidiqi.icu/Article/details/gt2trqabrzt.html

Py:   if __name__ == "__main__":
来源：http://dali.cqqwz.cn/Article/details/gt2bwmsjxdh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhoulong.xyz/Article/details/gt2bcgyykqd.html

JS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gt2icprrozt.html

TS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gt2yynabupv.html

Java: public static void main(String[] args)
来源：http://dali.gogol.net.cn/Article/details/gt2epmmspxt.html

Go:   func main()
来源：http://dali.jyoumei.cn/Article/details/gt2qklnvuki.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xylfe.cn/Article/details/gt2owqgclrz.html

C#:   static void Main(string[] args)
来源：http://dali.xylfe.cn/Article/details/gt2sxvvbqnr.html

[M08] 获取系统与运行时信息
来源：http://dali.tianlin.xyz/Article/details/gt2pcoxvzwc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigfzy.top/Article/details/gt2wrsycxsm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangdashe.top/Article/details/gt2fgijuerg.html

JS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gt2eraipbff.html

TS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gt2qdqajwxy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cashguo.top/Article/details/gt2kkepbzlt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.kuanghao11.cn/Article/details/gt2smbselfp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.mhx1999.top/Article/details/gt2qiwjsvco.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gt2ukpbcove.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2yiwyowqf.html

N. 数据结构与算法
来源：http://dali.gotoacloud.top/Article/details/gt2vfzwusyj.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2julnsgjb.html

[N01] 二分查找（有序数组）
来源：http://dali.jlsjyb.cn/Article/details/gt2txnjupwv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2eopzvujd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cdnleiting.top/Article/details/gt2igclpzxi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gt2eggekjwp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gt2amzxrywv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2bzbgxkfy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2vacghatp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zdqjudy.top/Article/details/gt2sxiiorfs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bevpokcw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sysykeji.top/Article/details/gt2alevnqhl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2serolnjz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nbldgmhn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ixctplgv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gt2uxtfyntb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daxiang520.top/Article/details/gt2dnibrxmr.html

Go:   slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gt2cawtlxts.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gt2piaxzeav.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sufxvd.cn/Article/details/gt2xwlwxaks.html

[N03] 快速排序（分治示例）
来源：http://dali.xylfe.cn/Article/details/gt2eizleqtk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cqqwz.cn/Article/details/gt2zydewtwv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aizwys.cn/Article/details/gt2eyupcwuq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gt2wooctmnb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gt2cwzvfbhs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuanzx.com/Article/details/gt2jpfuudmd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cqqwz.cn/Article/details/gt2ljhbsaql.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ybcxt.top/Article/details/gt2wnvmaeiu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigfzy.top/Article/details/gt2upqxjplv.html

[N04] 斐波那契数列
来源：http://dali.wangshuangyany.cn/Article/details/gt2xdemctpy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gt2hgsxmgwo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.guannengcc.top/Article/details/gt2ncxvkunt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gt2eqkkaftx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2igwuthzp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daxiang520.top/Article/details/gt2smvgmdkj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuanzx.com/Article/details/gt2iamjphez.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2emfsdgyz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gt2jpilgcej.html

[N05] 最大公约数
来源：http://dali.redwolf501.top/Article/details/gt2umndwplq.html

Py:   math.gcd(a, b)
来源：http://dali.hysaishi.cn/Article/details/gt2ojomuegi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ydzc1.top/Article/details/gt2qtzkxbez.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guowangkeji.top/Article/details/gt2wnzphyxk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2blqabrwi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhoulong.xyz/Article/details/gt2kzdoztbi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daxiang520.top/Article/details/gt2vpzryyxq.html

Ruby: a.gcd(b)
来源：http://dali.cqqwz.cn/Article/details/gt2qijkgffm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhengqikj.top/Article/details/gt2xkoujxhy.html

[N06] 判断回文字符串
来源：http://dali.zycfv.cn/Article/details/gt2uohbnmkx.html

Py:   s == s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gt2zjbqwmig.html

PHP:  $s === strrev($s);
来源：http://dali.sxryk.cn/Article/details/gt2mnpmsiky.html


<!-- 参考信息 -->