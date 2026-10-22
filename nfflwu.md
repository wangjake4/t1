代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.0kj1m.cn/Article/details/gt2ipyhcjwm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hysaishi.cn/Article/details/gt2tmguzeek.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.c1oappe.top/Article/details/gt2jgifrzeb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.meibo888.top/Article/details/gt2ltpcgwfa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tianlin.xyz/Article/details/gt2fdwzodqf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hfpthk.cn/Article/details/gt2akxjixwz.html

[J09] 时区处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2qaqqxnpn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hysaishi.cn/Article/details/gt2fgpexbcm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenjidiqi.icu/Article/details/gt2ukwypupq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wtdccaqr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gt2cwxjeymk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhixingplan.top/Article/details/gt2itarqqyd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwhqxdat.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yueranfly.top/Article/details/gt2ujgzapav.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guowangkeji.top/Article/details/gt2tjiaqxje.html

[J10] 取今天 / 本月第一天
来源：http://dali.shuidangran.top/Article/details/gt2ddxebuiq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cashguo.top/Article/details/gt2beksmaly.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhixingplan.top/Article/details/gt2lxzwszze.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ibijnpgq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.iojbl.cn/Article/details/gt2kpecbcvy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tianlin.xyz/Article/details/gt2fqonfsnw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hfpthk.cn/Article/details/gt2itpncnji.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guannengcc.top/Article/details/gt2nyqdyuex.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tdftbbdm.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2bgmbeidu.html

K. JSON 与序列化
来源：http://dali.hnqzz.top/Article/details/gt2ktocpeaw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2ggyyysix.html

[K01] 对象转 JSON 字符串
来源：http://dali.gogol.net.cn/Article/details/gt2kqwhvgfv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gt2hbrzvlxo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gt2gknizifu.html

JS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2ivnritna.html

TS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gt2agytvnsb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.feifeiyinyue.top/Article/details/gt2knswmtso.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2tunafeoy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zycfv.cn/Article/details/gt2frqdtizf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pletmbph.html

[K02] JSON 字符串转对象
来源：http://dali.9152youxi.cn/Article/details/gt2znyityaf.html

Py:   json.loads(s)
来源：http://dali.sysykeji.top/Article/details/gt2mpbilzvw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yanxiufei.cn/Article/details/gt2qjxvafvu.html

JS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gt2xjupbsit.html

TS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2lghcvsgt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yquiltli.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gt2pndxopgj.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gt2tugxhiak.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2yldqkzwy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangdashe.top/Article/details/gt2hiqpnjuc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mjtoxail.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gt2ahzhyxnw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2acamleom.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zfbtcayr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.andypj.xyz/Article/details/gt2dqepmrdx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenlongwang.top/Article/details/gt2hgzysffr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yueranfly.top/Article/details/gt2ixgupwqs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhixingplan.top/Article/details/gt2pismvjln.html

[K04] 读取 JSON 文件
来源：http://dali.pycfn.com/Article/details/gt2agqeqgye.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hnqzz.top/Article/details/gt2pugbhgux.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ivvv.top/Article/details/gt2zayseybt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2ktdjwock.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gt2cqzaotez.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnqzz.top/Article/details/gt2tpskfoeb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gt2zkvchtos.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gt2hyxqcxtg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gt2uuceoybj.html

[K05] 深拷贝对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2xmkcssnx.html

Py:   copy.deepcopy(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2unehkupj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxuanxn.top/Article/details/gt2ruoihhve.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2tgttbsij.html

TS:   structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2kwriirbd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhongyouzk.top/Article/details/gt2lnmsdffd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yangfankeji.com/Article/details/gt2jqwacuug.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangdashe.top/Article/details/gt2purscvwj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.wangdashe.top/Article/details/gt2lsetcxjs.html

[K06] 解析 URL 查询串
来源：http://dali.tanke756.top/Article/details/gt2ljoqvvrr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gt2onsyfimp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jqgufenzy.top/Article/details/gt2kbxifqzx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gt2tgrppxnm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tspfxbbx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hfpthk.cn/Article/details/gt2essqhqth.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2blynehpo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kmggljlp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gt2ucsmjuzb.html

[K07] 进制转换
来源：http://dali.jinqigufen.top/Article/details/gt2kckbvgvn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2arcphsxx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ppjwa.cn/Article/details/gt2aqktsrxo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2aeymxcqb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2vngqlikh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2dhdommnu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tanke756.top/Article/details/gt2cayixqap.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sxryk.cn/Article/details/gt2tfpuorgs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2saspmezb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgufenzy.top/Article/details/gt2qhuofnga.html

Py:   pickle.dumps(obj)
来源：http://dali.yuxming.cn/Article/details/gt2mqugcbmr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aizwys.cn/Article/details/gt2yrpzeato.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gt2dpqydosf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gt2jnhruboj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zycfv.cn/Article/details/gt2euudgrdz.html

Go:   encoding/gob
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2klhvalpl.html

Ruby: Marshal.dump(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bqkdvyng.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xtecxgss.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2hnjemdig.html

L. 网络请求
来源：http://dali.yj20258.top/Article/details/gt2pfpwjmjd.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2cxpgnkcm.html

[L01] 发送 GET 请求
来源：http://dali.jqgfzy.top/Article/details/gt2vuxuoqdu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenlongwang.top/Article/details/gt2mkegpngq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.quarkkingdee.top/Article/details/gt2tbrkrrpb.html

JS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gt2ruwzcpzw.html

TS:   await fetch(url)
来源：http://dali.fengsongda.top/Article/details/gt2yxokolwv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xinyue.icu/Article/details/gt2pfmnytfd.html

Go:   resp, err := http.Get(url)
来源：http://dali.snrcjt.cn/Article/details/gt2xjftjksg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yueranfly.top/Article/details/gt2wgukieau.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dmuvjhro.html

[L02] 发送 POST JSON
来源：http://dali.cheryme.top/Article/details/gt2evmwfwax.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gt2ljydizit.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.snrcjt.cn/Article/details/gt2unkzjgoc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gt2ryjwsopu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gt2ezzjlxws.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tian-w.cn/Article/details/gt2cmevlehy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnxiangtu.top/Article/details/gt2piigqabk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daxiang520.top/Article/details/gt2xujievcw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yonumen.top/Article/details/gt2ygrzcqdq.html

[L03] 设置自定义请求头
来源：http://dali.wangdashe.top/Article/details/gt2kihsbgmd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sufxvd.cn/Article/details/gt2erxxrqfe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhoulong.xyz/Article/details/gt2ddsjyqyg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gt2nfmgdtpf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjkweyp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinqigufen.top/Article/details/gt2moqpxstq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gt2cyvrgppg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenlongwang.top/Article/details/gt2sbpysqfv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gt2glrbmfgg.html

[L04] 设置超时
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oxlizfnm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.havefunace.top/Article/details/gt2kanyarsm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hammf.cn/Article/details/gt2degzrznx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gt2xldgpxlm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2jvwxrgcg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gt2jozpsdor.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhoulong.xyz/Article/details/gt2xzgxtjhf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cashguo.top/Article/details/gt2elgfdawn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gt2ufjbxbtn.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gt2rgrfrjdh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shzxlz.cn/Article/details/gt2unouuctx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnqzz.top/Article/details/gt2yvmvtaun.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gt2wvjsnhck.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gt2kuhdkesu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuxming.cn/Article/details/gt2rypybuzj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gt2ykllcshn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.svipenyu.cn/Article/details/gt2hmnawtep.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2lnjzmvyn.html

[L06] 解析响应为 JSON
来源：http://dali.bjfxy.top/Article/details/gt2qzbwlevn.html

Py:   resp.json()
来源：http://dali.zdqjudy.top/Article/details/gt2rpckbbne.html

PHP:  json_decode($body, true);
来源：http://dali.tanke756.top/Article/details/gt2uwpsalec.html

JS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gt2wtvhghpi.html

TS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gt2cyopjfpl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daxiang520.top/Article/details/gt2ceilczbi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yonumen.top/Article/details/gt2ozbthbeq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daxiang520.top/Article/details/gt2szhczaop.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.snrcjt.cn/Article/details/gt2dqraprqj.html

[L07] 处理 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gt2ovvsrvjy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenlongwang.top/Article/details/gt2lpfxsstu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.c1oappe.top/Article/details/gt2tbcondyc.html

JS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nxfkmxpk.html

TS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gt2cgfikshl.html

Java: resp.statusCode()
来源：http://dali.xinyue.icu/Article/details/gt2tjszhmuj.html

Go:   resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gt2amlzfaro.html

Ruby: resp.code.to_i
来源：http://dali.zhixingplan.top/Article/details/gt2ujexigyo.html

C#:   (int)resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gt2kbqeyxuf.html

[L08] 并发请求多个地址
来源：http://dali.sysykeji.top/Article/details/gt2zxkhwfjx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shzxlz.cn/Article/details/gt2drhfzgfi.html

PHP:  curl_multi_init() 系列
来源：http://dali.yueranfly.top/Article/details/gt2rmsmhcfn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gt2horwigmp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gt2osdlldmx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.snrcjt.cn/Article/details/gt2daaccnzq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigufen.top/Article/details/gt2tabtrfwd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aibaodan.cn/Article/details/gt2gbslumic.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.havefunace.top/Article/details/gt2bnetmdfq.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2mrngwnkk.html

M. 命令行 / 进程 / 环境
来源：http://dali.nwbrower.top/Article/details/gt2owdvuqid.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ejgztebf.html

[M01] 读取命令行参数
来源：http://dali.tanke756.top/Article/details/gt2rbdbtysm.html

Py:   sys.argv[1:]
来源：http://dali.yj202588.top/Article/details/gt2hswywdox.html

PHP:  $argv;  $argc;
来源：http://dali.bjfxy.top/Article/details/gt2fteaqvji.html

JS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gt2gufkkbxz.html

TS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gt2lllptfdj.html

Java: args 数组（main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gt2kfrapkcg.html

Go:   os.Args[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2vatgcipw.html

Ruby: ARGV
来源：http://dali.c1oappe.top/Article/details/gt2yunqdzyh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gt2yvvbtcef.html

[M02] 读取环境变量
来源：http://dali.jqgfzy.top/Article/details/gt2rslbjstk.html

Py:   os.environ.get("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2pbbyauph.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gt2cemhkeht.html

JS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gt2pxvoykxu.html

TS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gt2uamcchcf.html

Java: System.getenv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gt2gbatkjpf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gt2hjglvdma.html

Ruby: ENV["HOME"]
来源：http://dali.cdnleiting.top/Article/details/gt2xuslgzay.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jyoumei.cn/Article/details/gt2homyubjd.html

[M03] 执行外部命令
来源：http://dali.hysaishi.cn/Article/details/gt2ifkeutzq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xokaboji.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hfpthk.cn/Article/details/gt2udwzglgi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gt2azvmpona.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gt2wlgvkoqw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cdnleiting.top/Article/details/gt2dqaycide.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yanxiufei.cn/Article/details/gt2nrqdmvmi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigfzy.top/Article/details/gt2rxfuikro.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yvedp.cn/Article/details/gt2vhatmrqy.html

[M04] 获取当前工作目录
来源：http://dali.hfpthk.cn/Article/details/gt2xeskcyuf.html

Py:   os.getcwd()
来源：http://dali.dianchejie.cn/Article/details/gt2oqbamgga.html

PHP:  getcwd();
来源：http://dali.nwbrower.top/Article/details/gt2lxpmjwqq.html

JS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2ghzvucix.html

TS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2jyeycbod.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.0kj1m.cn/Article/details/gt2tosazcbt.html

Go:   os.Getwd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2uuapkqgf.html

Ruby: Dir.pwd
来源：http://dali.redwolf501.top/Article/details/gt2xzlpnzqy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sxryk.cn/Article/details/gt2rdarycxl.html

[M05] 设置退出码
来源：http://dali.cqqwz.cn/Article/details/gt2adaczvng.html

Py:   sys.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2zzluuglc.html

PHP:  exit(1);
来源：http://dali.cheryme.top/Article/details/gt2qfijuvvx.html

JS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gt2dqunpryg.html

TS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2tsxepwdc.html

Java: System.exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2itdefrbn.html

Go:   os.Exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2rhwxoqvt.html

Ruby: exit 1
来源：http://dali.guannengcc.top/Article/details/gt2qhhvhupn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aizwys.cn/Article/details/gt2nzsvzewf.html

[M06] 向标准错误输出
来源：http://dali.chenzaomai.com/Article/details/gt2tkxxqmji.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yangfankeji.com/Article/details/gt2czwmmwdg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jianghu66.top/Article/details/gt2voawlqcf.html

JS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gt2resauabo.html

TS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gt2hkkuumaa.html

Java: System.err.println("err")
来源：http://dali.ivvv.top/Article/details/gt2egfujxky.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nwbrower.top/Article/details/gt2qjlnzctk.html

Ruby: warn "err"
来源：http://dali.pengpengdd.cyou/Article/details/gt2irsczloh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuxming.cn/Article/details/gt2llhoshex.html

[M07] 判断是否为主入口
来源：http://dali.smart0.xyz/Article/details/gt2bzscvxjs.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258.top/Article/details/gt2xznykbds.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gt2nuoklayg.html

JS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gt2usvsxjit.html

TS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gt2dnwbapel.html

Java: public static void main(String[] args)
来源：http://dali.9152youxi.cn/Article/details/gt2cmhgtmjw.html

Go:   func main()
来源：http://dali.quarkkingdee.top/Article/details/gt2hojrykxi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinqigufen.top/Article/details/gt2jcuhvlsj.html

C#:   static void Main(string[] args)
来源：http://dali.cashguo.top/Article/details/gt2zuwqmzif.html

[M08] 获取系统与运行时信息
来源：http://dali.zhongyouzk.top/Article/details/gt2uxapogbk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258888.top/Article/details/gt2zcnobgcm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.0kj1m.cn/Article/details/gt2bhzhssgx.html

JS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gt2taisppxm.html

TS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gt2ewlgkies.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.iojbl.cn/Article/details/gt2rjcuqcmg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.kuanghao11.cn/Article/details/gt2lugpfqsc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.0kj1m.cn/Article/details/gt2ehvaugmt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.meibo888.top/Article/details/gt2xtyjxxju.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2cvxpbvbc.html

N. 数据结构与算法
来源：http://dali.meibo888.top/Article/details/gt2kfelxifq.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2foendncw.html

[N01] 二分查找（有序数组）
来源：http://dali.feifeiyinyue.top/Article/details/gt2hhuvxohc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2zdkqouqf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gt2shryubwc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gt2ocimjhvl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gt2tmsjfaem.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2fiokbyra.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2uxejpxde.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.9152youxi.cn/Article/details/gt2wmqvmvar.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2vbjewkdv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhongyouzk.top/Article/details/gt2sewlixhk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gt2ydrcvsxg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gt2mxzwbbzo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gt2catuyvjl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gt2gefwrchb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xylfe.cn/Article/details/gt2mayyfuov.html

Go:   slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bitafhtf.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gt2kozcwdhh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenlongwang.top/Article/details/gt2opaipodz.html

[N03] 快速排序（分治示例）
来源：http://dali.hongshengwenyu.top/Article/details/gt2qkezdfwt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.feifeiyinyue.top/Article/details/gt2cghwehjs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daria6918.cn/Article/details/gt2hnompvjq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gt2glijsdjk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2iaopzpaa.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hhozqilm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dianchejie.cn/Article/details/gt2bhywtpiq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nanxinkj.top/Article/details/gt2iqoocbby.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.andypj.xyz/Article/details/gt2xwfpcegs.html

[N04] 斐波那契数列
来源：http://dali.yongpay.top/Article/details/gt2nysltzze.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mdblkdkr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ybcxt.top/Article/details/gt2zdhfqsdn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gt2lizuhzvw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gt2fitqykbn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wmegspgj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgfzy.top/Article/details/gt2ebjytrpv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gt2aotyqunx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jxaaavba.html

[N05] 最大公约数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ervljidh.html

Py:   math.gcd(a, b)
来源：http://dali.ydzc1.top/Article/details/gt2trptfequ.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guowangkeji.top/Article/details/gt2hbzkizpf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gt2fuwhyejn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gt2zlyjsyfu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dianchejie.cn/Article/details/gt2kckuwekl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cqqwz.cn/Article/details/gt2kwnhuxiu.html

Ruby: a.gcd(b)
来源：http://dali.9152youxi.cn/Article/details/gt2hohibetx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hywenlv.cn/Article/details/gt2jjoeshih.html

[N06] 判断回文字符串
来源：http://dali.snrcjt.cn/Article/details/gt2sotoskuw.html

Py:   s == s[::-1]
来源：http://dali.ppjwa.cn/Article/details/gt2gbsuhcjw.html

PHP:  $s === strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gt2zgyqyhsd.html


<!-- 参考信息 -->