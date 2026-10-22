代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gt2huxiqdir.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnqzz.top/Article/details/gt2jeqlqqej.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.0kj1m.cn/Article/details/gt2gphystmn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gt2biphaolo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gt2qflnkfnl.html

[J08] 提取年月日与星期
来源：http://dali.iojbl.cn/Article/details/gt2yloysdol.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.snrcjt.cn/Article/details/gt2cbtrfrtp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxinkj.top/Article/details/gt2kndyoqnh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daria6918.cn/Article/details/gt2klhhqiuc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zlwrwkvl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxuanxn.top/Article/details/gt2ljqbupim.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nanxinkj.top/Article/details/gt2hnrqotkl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhixingplan.top/Article/details/gt2iweknlcu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cucudq.cn/Article/details/gt2szjsvdze.html

[J09] 时区处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2urfklfji.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.c1oappe.top/Article/details/gt2qhzjrrxa.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigufen.top/Article/details/gt2foizehyb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gt2nydtbued.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ikmqncjp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jyoumei.cn/Article/details/gt2bwupszmv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gt2arddprkc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dashuyun.cn/Article/details/gt2oqchndjf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gotoacloud.top/Article/details/gt2xqjumqtc.html

[J10] 取今天 / 本月第一天
来源：http://dali.yueranfly.top/Article/details/gt2eckwffqn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cdnleiting.top/Article/details/gt2mofxcipm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fzhhl.top/Article/details/gt2kjovjvdw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shuidangran.top/Article/details/gt2yuwscdnk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ivvv.top/Article/details/gt2ckahrtkr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.haohaochexian.top/Article/details/gt2ttvbohqd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jyoumei.cn/Article/details/gt2nashnbil.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sufxvd.cn/Article/details/gt2btzjqbkq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daxiang520.top/Article/details/gt2ihpyrmhx.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2bxplzlgc.html

K. JSON 与序列化
来源：http://dali.hywenlv.cn/Article/details/gt2txqjbejt.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2zdgmqyru.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258.top/Article/details/gt2qgpeuurd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gt2gevkdfpf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gt2ubrqpjws.html

JS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gt2ramevjkd.html

TS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2icjrsact.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fengsongda.top/Article/details/gt2jmcewlsa.html

Go:   json.Marshal(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nhpeirmb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jyoumei.cn/Article/details/gt2sjzlozgs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yvedp.cn/Article/details/gt2yqtpzpxs.html

[K02] JSON 字符串转对象
来源：http://dali.jqgufenzy.top/Article/details/gt2tdvcfael.html

Py:   json.loads(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pjwobupi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jianghu66.top/Article/details/gt2njechdic.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbeinvzt.html

TS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gt2dbqvkwqi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ybcxt.top/Article/details/gt2dveofuvm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gt2fxhyxdip.html

Ruby: JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gt2dmjexuxc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2nnyypkoq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258888.top/Article/details/gt2rxulryxu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gt2dwswbagn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gt2axuvxdxo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gt2uqkcorud.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gt2rmpkodpy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2zhowjlvz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ydzc1.top/Article/details/gt2rzkjrnlp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yonumen.top/Article/details/gt2qhvnixhx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ehwqpu.com/Article/details/gt2pkluwgsn.html

[K04] 读取 JSON 文件
来源：http://dali.haohaochexian.top/Article/details/gt2lmreafec.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shzxlz.cn/Article/details/gt2lubaumfo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.fzhhl.top/Article/details/gt2xnbfvkkc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gt2qzskdyuy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bcknewbp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fzhhl.top/Article/details/gt2ogyrhszi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gt2omfozlsb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj202588.top/Article/details/gt2hntcdusd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cheryme.top/Article/details/gt2viczlmff.html

[K05] 深拷贝对象
来源：http://dali.jinghuilouyu.cn/Article/details/gt2njakjsza.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuxming.cn/Article/details/gt2unyqxtln.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jlsjyb.cn/Article/details/gt2uqpnzwmh.html

JS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2dtuwhiqy.html

TS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gt2dquffzoh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhixingplan.top/Article/details/gt2jmiutedm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dianchejie.cn/Article/details/gt2faucacnc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangdashe.top/Article/details/gt2offodgix.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fzhhl.top/Article/details/gt2lbdidhvq.html

[K06] 解析 URL 查询串
来源：http://dali.jianghu66.top/Article/details/gt2cgvezbjd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yangfankeji.com/Article/details/gt2ozwighpb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xylfe.cn/Article/details/gt2srfccrex.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2umrbcpoh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gt2osfldcfo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.9152youxi.cn/Article/details/gt2okrqnuff.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gt2vjzqbykd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gt2aomnchnr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gt2vuelssye.html

[K07] 进制转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2lhsosihu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2kiaqcgpf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.316326.xyz/Article/details/gt2dduaryir.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tioqofni.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2nodknngs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jepjmylm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dashuyun.cn/Article/details/gt2ukkiyyyi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2prdwvyfo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2jgivhlie.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dashuyun.cn/Article/details/gt2ocotbhuc.html

Py:   pickle.dumps(obj)
来源：http://dali.316326.xyz/Article/details/gt2lvugtbcf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yvedp.cn/Article/details/gt2rybvqwdi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gt2hwayjdgn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gt2vanlozzv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258888.top/Article/details/gt2notkumfj.html

Go:   encoding/gob
来源：http://dali.ehwqpu.com/Article/details/gt2fzusvoaz.html

Ruby: Marshal.dump(obj)
来源：http://dali.aizwys.cn/Article/details/gt2etblwwtm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gt2jvoiqwcg.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2phmknmfi.html

L. 网络请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fchzdsng.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2upjlqrto.html

[L01] 发送 GET 请求
来源：http://dali.nwbrower.top/Article/details/gt2zbwbcslq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgfzy.top/Article/details/gt2ngwyjaqi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yvedp.cn/Article/details/gt2ejccmbty.html

JS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gt2zfxluxie.html

TS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gt2vzupbywl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yvedp.cn/Article/details/gt2swkvlfqn.html

Go:   resp, err := http.Get(url)
来源：http://dali.yongpay.top/Article/details/gt2ypdwauck.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shangyingyoupin.top/Article/details/gt2gvwjsmbb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gt2qndvoylb.html

[L02] 发送 POST JSON
来源：http://dali.xziqi.cn/Article/details/gt2acjlsjfv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gt2zstbvspp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.quarkkingdee.top/Article/details/gt2ekbjcwun.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gt2fryirqrm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bwdmuhyh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gt2hzvjzfrx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.0kj1m.cn/Article/details/gt2nabdnviy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mbunnufg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkqakjvg.html

[L03] 设置自定义请求头
来源：http://dali.yvedp.cn/Article/details/gt2dcjejwwk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zdqjudy.top/Article/details/gt2mtgqtwve.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yvedp.cn/Article/details/gt2kfzbihxe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gt2dystoapj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fzhhl.top/Article/details/gt2jkqgkdds.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.aizwys.cn/Article/details/gt2wxuuyuaz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gt2wkvytook.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jiagoushi.top/Article/details/gt2gqqbsxsf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gt2vagitvib.html

[L04] 设置超时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jiproaoq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnqwstn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxinkj.top/Article/details/gt2poeewbzv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gt2abfmmcql.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gt2utcfkfov.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hfpthk.cn/Article/details/gt2hqdkohvy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnqzz.top/Article/details/gt2ktgpxdes.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.birdmap.top/Article/details/gt2dpqnscvi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vocwkwxz.html

[L05] 上传文件（multipart）
来源：http://dali.bjfxy.top/Article/details/gt2lnggtobs.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aizwys.cn/Article/details/gt2ntzfyvob.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jlsjyb.cn/Article/details/gt2darsonss.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gt2nqxadtic.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gt2tmncibni.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tianlin.xyz/Article/details/gt2qheahvxe.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.mhx1999.top/Article/details/gt2swccyfge.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tian-w.cn/Article/details/gt2yxhkislg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2psrqlkuv.html

[L06] 解析响应为 JSON
来源：http://dali.zhixingplan.top/Article/details/gt2iofumprr.html

Py:   resp.json()
来源：http://dali.chenlongwang.top/Article/details/gt2hfnzruiz.html

PHP:  json_decode($body, true);
来源：http://dali.daria6918.cn/Article/details/gt2enxwasyt.html

JS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gt2elwtdvoo.html

TS:   await resp.json()
来源：http://dali.0kj1m.cn/Article/details/gt2jarikppl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gt2zgfwksko.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pycfn.com/Article/details/gt2qyxsyozd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.vqdsnc.cn/Article/details/gt2ewgouisu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jiagoushi.top/Article/details/gt2vuugsakg.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gt2fhyxueka.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sysykeji.top/Article/details/gt2ylxigsbd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbylcvy.html

JS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gt2viqqvwhc.html

TS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gt2krxdccyr.html

Java: resp.statusCode()
来源：http://dali.aibaodan.cn/Article/details/gt2ycltbxha.html

Go:   resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gt2jaupowps.html

Ruby: resp.code.to_i
来源：http://dali.316326.xyz/Article/details/gt2hcmvgjna.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gt2pepblqgl.html

[L08] 并发请求多个地址
来源：http://dali.yangfankeji.com/Article/details/gt2lgazlaax.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gt2xcoufuqd.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhengqikj.top/Article/details/gt2enyoxwwu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gt2fmlxjdqu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gt2klehqcdv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.vqdsnc.cn/Article/details/gt2scxaldtk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenzaomai.com/Article/details/gt2zwfafzkq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gt2osoectbm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2fwnfuzev.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2gyvjnsgy.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangdashe.top/Article/details/gt2axuboskv.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2esdavhba.html

[M01] 读取命令行参数
来源：http://dali.xuanzx.com/Article/details/gt2oyvegdza.html

Py:   sys.argv[1:]
来源：http://dali.ydzc1.top/Article/details/gt2tquxuent.html

PHP:  $argv;  $argc;
来源：http://dali.sxryk.cn/Article/details/gt2mjinnfat.html

JS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gt2ouabmqyk.html

TS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gt2gzhcjnia.html

Java: args 数组（main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gt2cudrzgew.html

Go:   os.Args[1:]
来源：http://dali.birdmap.top/Article/details/gt2wmnrasqf.html

Ruby: ARGV
来源：http://dali.shangyingyoupin.top/Article/details/gt2aozljjtz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gt2kdouslsf.html

[M02] 读取环境变量
来源：http://dali.quarkkingdee.top/Article/details/gt2abujutyr.html

Py:   os.environ.get("HOME")
来源：http://dali.ydzc1.top/Article/details/gt2ihawoqrc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gt2xgdyaqxj.html

JS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gt2ksqolrhb.html

TS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gt2kilbqzpm.html

Java: System.getenv("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2nyrvehsk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2umdabqpy.html

Ruby: ENV["HOME"]
来源：http://dali.hywenlv.cn/Article/details/gt2rnsfcdne.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuanzhike.top/Article/details/gt2ewlblosz.html

[M03] 执行外部命令
来源：http://dali.xylfe.cn/Article/details/gt2wjgvlmxp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dashuyun.cn/Article/details/gt2pwdfqvxf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yongpay.top/Article/details/gt2hmentvtx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gt2eciwgfsv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gt2lkqqwpbo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yongpay.top/Article/details/gt2sgkphmmq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daria6918.cn/Article/details/gt2azxdfzux.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shuidangran.top/Article/details/gt2hzooxjud.html

C#:   Process.Start("ls", "-l");
来源：http://dali.quarkkingdee.top/Article/details/gt2yvvlghha.html

[M04] 获取当前工作目录
来源：http://dali.redwolf501.top/Article/details/gt2cvxyakam.html

Py:   os.getcwd()
来源：http://dali.daria6918.cn/Article/details/gt2xitwpkmc.html

PHP:  getcwd();
来源：http://dali.jinqigfzy.top/Article/details/gt2wcmnlvug.html

JS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gt2rkbhchui.html

TS:   process.cwd()
来源：http://dali.yj20258888.top/Article/details/gt2bylhimpf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.havefunace.top/Article/details/gt2boxyxzex.html

Go:   os.Getwd()
来源：http://dali.jiagoushi.top/Article/details/gt2isjjsejh.html

Ruby: Dir.pwd
来源：http://dali.havefunace.top/Article/details/gt2ajvgwjni.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hfpthk.cn/Article/details/gt2ieuvbqjw.html

[M05] 设置退出码
来源：http://dali.havefunace.top/Article/details/gt2eojwsrac.html

Py:   sys.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2lhjxvyht.html

PHP:  exit(1);
来源：http://dali.yuxming.cn/Article/details/gt2frxbjiyk.html

JS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2epuzgkys.html

TS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yoxyfmxr.html

Java: System.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2dckhprno.html

Go:   os.Exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2feqtckhg.html

Ruby: exit 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2etmyoygf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cdnleiting.top/Article/details/gt2inqlpzye.html

[M06] 向标准错误输出
来源：http://dali.zycfv.cn/Article/details/gt2alkwtpya.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gt2ycqxsgmy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhongyouzk.top/Article/details/gt2vhhatbxx.html

JS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gt2ninqjdui.html

TS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gt2ktkbrqmh.html

Java: System.err.println("err")
来源：http://dali.sxryk.cn/Article/details/gt2szixdcht.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yvedp.cn/Article/details/gt2snjftyfz.html

Ruby: warn "err"
来源：http://dali.yangfankeji.com/Article/details/gt2txdhiwih.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.svipenyu.cn/Article/details/gt2dkdvvisf.html

[M07] 判断是否为主入口
来源：http://dali.sysykeji.top/Article/details/gt2corrywqq.html

Py:   if __name__ == "__main__":
来源：http://dali.kuanghao11.cn/Article/details/gt2whdhbizu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gt2tvzhaluh.html

JS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gt2mcnhxuui.html

TS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gt2fqljmcqm.html

Java: public static void main(String[] args)
来源：http://dali.fengsongda.top/Article/details/gt2kaucshds.html

Go:   func main()
来源：http://dali.yj20258.top/Article/details/gt2ahhysdiy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ftffladh.html

C#:   static void Main(string[] args)
来源：http://dali.gaohongyu789.top/Article/details/gt2wkciztpm.html

[M08] 获取系统与运行时信息
来源：http://dali.316326.xyz/Article/details/gt2jjjicoey.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangshuangyany.cn/Article/details/gt2zqhaxaci.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258.top/Article/details/gt2agspxmgw.html

JS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gt2hcrwnaej.html

TS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gt2jslhpvqd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zycfv.cn/Article/details/gt2goyboqim.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shangyingyoupin.top/Article/details/gt2tcmsbkom.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xinyue.icu/Article/details/gt2ehwkslho.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hysaishi.cn/Article/details/gt2awdbcjsc.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2rmzljtry.html

N. 数据结构与算法
来源：http://dali.316326.xyz/Article/details/gt2uunyglwz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2olutuqzj.html

[N01] 二分查找（有序数组）
来源：http://dali.cdnleiting.top/Article/details/gt2akjywbfn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2binldhmx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ydzc1.top/Article/details/gt2wdkiagey.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gt2cmcbgeyv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gt2sqlwxqbo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2ezcfgjfn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2sneoyqeq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxuanxn.top/Article/details/gt2rzqboyrn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2imturdcl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jyoumei.cn/Article/details/gt2fypqimuf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gt2evmovetq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daria6918.cn/Article/details/gt2wzkrhcfb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gt2bcixwszl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gt2totmdkio.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.quarkkingdee.top/Article/details/gt2paribzxn.html

Go:   slices.Sort(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iksgmxte.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gt2cwkswmre.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigufen.top/Article/details/gt2wxdezcwz.html

[N03] 快速排序（分治示例）
来源：http://dali.yuxming.cn/Article/details/gt2vygpjekb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.feifeiyinyue.top/Article/details/gt2xvqvzhfw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hammf.cn/Article/details/gt2uxcjdebg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gt2qunkgfcv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sufxvd.cn/Article/details/gt2uaqdxtou.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.vqdsnc.cn/Article/details/gt2shtibved.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hfpthk.cn/Article/details/gt2dvjhmbjy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daxiang520.top/Article/details/gt2pwzrsuxd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnxiangtu.top/Article/details/gt2gnqorpep.html

[N04] 斐波那契数列
来源：http://dali.hfpthk.cn/Article/details/gt2fsnradar.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2okdyejng.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cucudq.cn/Article/details/gt2qfhhgfim.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2trrhppes.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gt2nfoikrer.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cqqwz.cn/Article/details/gt2jfkdukir.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yhhvhsjy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gt2jkilabtl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gt2bhvmzfaj.html

[N05] 最大公约数
来源：http://dali.sxryk.cn/Article/details/gt2nqaaclgm.html

Py:   math.gcd(a, b)
来源：http://dali.birdmap.top/Article/details/gt2jheuxdyy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.meibo888.top/Article/details/gt2ucfbksna.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gt2zupbjubr.html


<!-- 参考信息 -->