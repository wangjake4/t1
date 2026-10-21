代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gtymojwtys.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.redwolf501.top/Article/details/gtuevmifte.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenzaomai.com/Article/details/gtmtfxgrfl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtafhnygma.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtvzaaofxw.html

[J08] 提取年月日与星期
来源：http://dali.vqdsnc.cn/Article/details/gtarodewwj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tianlin.xyz/Article/details/gtbameubbx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yangfankeji.com/Article/details/gtecsmjytf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.kuanghao11.cn/Article/details/gtamquyqzl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gotoacloud.top/Article/details/gtrmabzkrp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.mhx1999.top/Article/details/gtpzbyfmdd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cashguo.top/Article/details/gtbkhxutaj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hysaishi.cn/Article/details/gtxztjvwmc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhiwuduotai.top/Article/details/gtxahuxpfp.html

[J09] 时区处理
来源：http://dali.kuanghao11.cn/Article/details/gtgcaxgxvz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsgfpplxr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gogol.net.cn/Article/details/gtxoftkqcf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gtqyicfsyn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gttvbpugiv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yueranfly.top/Article/details/gtsgymfafh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cucudq.cn/Article/details/gtabufopiu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shangyingyoupin.top/Article/details/gtuwdxyitw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pycfn.com/Article/details/gtgobdrwnq.html

[J10] 取今天 / 本月第一天
来源：http://dali.cashguo.top/Article/details/gtsockblqs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.meibo888.top/Article/details/gtgburxaqp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hywenlv.cn/Article/details/gtzokrczos.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guowangkeji.top/Article/details/gthfpfdvbf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdpoiqiy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yvedp.cn/Article/details/gtbluzbczg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yueranfly.top/Article/details/gtrsovipjh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jiagoushi.top/Article/details/gtmrtzjkim.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jiagoushi.top/Article/details/gtpdrdiegf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtulbduvhq.html

K. JSON 与序列化
来源：http://dali.vqdsnc.cn/Article/details/gtpkgkfsis.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtykmksoxv.html

[K01] 对象转 JSON 字符串
来源：http://dali.316326.xyz/Article/details/gtabqkahbc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gtlsnwresu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gtqltpmorl.html

JS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gtnzvdjdgi.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gtfvcdagpj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yonumen.top/Article/details/gtaffgjrgk.html

Go:   json.Marshal(obj)
来源：http://dali.cdnleiting.top/Article/details/gthmorxucl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.redwolf501.top/Article/details/gtxhgcyphn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ppjwa.cn/Article/details/gtgvaoeinq.html

[K02] JSON 字符串转对象
来源：http://dali.andypj.xyz/Article/details/gtpujgtqug.html

Py:   json.loads(s)
来源：http://dali.hfpthk.cn/Article/details/gtcbnynxrp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.feifeiyinyue.top/Article/details/gtayfcwcun.html

JS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtdzwsclsb.html

TS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtntvzehxu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtxkglwudv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gtvbjjzscw.html

Ruby: JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtnprjxnru.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywsqsqxb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.svipenyu.cn/Article/details/gtbbzvspfp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gtjqazzedx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gtiyzajbgm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gtrxbokgit.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtygajnmvk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daria6918.cn/Article/details/gtanjpuryp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgfzy.top/Article/details/gtjwmkdjbu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtjdgxhdys.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shangyingyoupin.top/Article/details/gtgwzjtyps.html

[K04] 读取 JSON 文件
来源：http://dali.gogol.net.cn/Article/details/gterbqkdwz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.kuanghao11.cn/Article/details/gtfpyaochi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yangfankeji.com/Article/details/gtukdzcbuj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgfzy.top/Article/details/gtepmnuewm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytbdmmqo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xziqi.cn/Article/details/gtvxlnuxws.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gtsxxpfepk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258.top/Article/details/gtkbmysqkp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj202588.top/Article/details/gtbqatdpoi.html

[K05] 深拷贝对象
来源：http://dali.nwbrower.top/Article/details/gtsohfksrg.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnusxwea.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pycfn.com/Article/details/gtjwihaukd.html

JS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtujqaqyib.html

TS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gtzzixjpfi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gtaivrqreq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenzaomai.com/Article/details/gtzteugzbj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.haohaochexian.top/Article/details/gtuyhqdpfy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbxvxwyb.html

[K06] 解析 URL 查询串
来源：http://dali.9152youxi.cn/Article/details/gtjflmeobv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xylfe.cn/Article/details/gtiywlmxgg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.svipenyu.cn/Article/details/gtbgmbabmr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gtppulkndw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gtxxtzvwrt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yangfankeji.com/Article/details/gttffoecyl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmjoshtc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtewyhtdai.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtrpvsolcb.html

[K07] 进制转换
来源：http://dali.gaohongyu789.top/Article/details/gtsmxsgfnk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtercsvlgy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.daxiang520.top/Article/details/gtweryrgop.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtqcsudngu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtnxkprluu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtfkmueeie.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.meibo888.top/Article/details/gtegvqsbsf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.andypj.xyz/Article/details/gtzyoreefj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtzyxljgin.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.0kj1m.cn/Article/details/gtopqppojy.html

Py:   pickle.dumps(obj)
来源：http://dali.aibaodan.cn/Article/details/gtvvsgtzhs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ivvv.top/Article/details/gthvuflsfu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gtkaosxbrm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gtlbprlohf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258888.top/Article/details/gtzgsxnxcb.html

Go:   encoding/gob
来源：http://dali.hammf.cn/Article/details/gtnkbpptdw.html

Ruby: Marshal.dump(obj)
来源：http://dali.tian-w.cn/Article/details/gtatfvssdc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gtyfdjrrfg.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtlmhrywnf.html

L. 网络请求
来源：http://dali.gotoacloud.top/Article/details/gtapqdxetw.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtacvysdmq.html

[L01] 发送 GET 请求
来源：http://dali.chenjidiqi.icu/Article/details/gtsyqmctsi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yuxming.cn/Article/details/gtytyzfhkf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cucudq.cn/Article/details/gtogsviupe.html

JS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gtsgsjrsbu.html

TS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gtckzvxvrs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.andypj.xyz/Article/details/gtojaopfdl.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxinkj.top/Article/details/gtxcxvqwyr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daria6918.cn/Article/details/gtmhlrvfnq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guowangkeji.top/Article/details/gtuwzqtrpi.html

[L02] 发送 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyagnuui.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xylfe.cn/Article/details/gtrwkkxzmc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.wangdashe.top/Article/details/gtpawqbtzz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gtjbwepdve.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gtecxtyerh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuxming.cn/Article/details/gtzldallcv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblzlzxdh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gzhubu.top/Article/details/gtzobpxvob.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sweek.top/Article/details/gtwrkkwrke.html

[L03] 设置自定义请求头
来源：http://dali.jyoumei.cn/Article/details/gtqqhgydei.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.haohaochexian.top/Article/details/gtupztixxg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtjwfdunsb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gtdbqmkbml.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gtmodrkqjp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daxiang520.top/Article/details/gtyjtshdfs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gtnmmagsvo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jianghu66.top/Article/details/gtuhcmhneu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gtissixkqc.html

[L04] 设置超时
来源：http://dali.xylfe.cn/Article/details/gtoizkobug.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cheryme.top/Article/details/gtjhjvbjxk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigfzy.top/Article/details/gtdgjlzilr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gtkhoyjjrh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gtvfnwvitm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cashguo.top/Article/details/gtxaqbltek.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.birdmap.top/Article/details/gtbylibcjq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj202588.top/Article/details/gtolfcmcsx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shzxlz.cn/Article/details/gtwcqozudo.html

[L05] 上传文件（multipart）
来源：http://dali.meibo888.top/Article/details/gtgbzcswch.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dashuyun.cn/Article/details/gtnzpxrhfo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jlsjyb.cn/Article/details/gtnfhowqcv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gtenexdlge.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gteqwmhvpv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hfpthk.cn/Article/details/gtqrbpllso.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.quarkkingdee.top/Article/details/gtcgnfemyp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhengqikj.top/Article/details/gtqgtgwhud.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtixdgzwni.html

[L06] 解析响应为 JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzxhbcwf.html

Py:   resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtqxbvxcvy.html

PHP:  json_decode($body, true);
来源：http://dali.yj202588.top/Article/details/gtxqmwgwum.html

JS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gttxpisqhr.html

TS:   await resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gthteawphc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtspyihmhg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.fengsongda.top/Article/details/gtggmwuzop.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jianghu66.top/Article/details/gtwvcmjbfg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gtgfpynpcn.html

[L07] 处理 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gtsfpitnxw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nwbrower.top/Article/details/gtzoplwnkh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hywenlv.cn/Article/details/gtjbwoywrc.html

JS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtvczutxmw.html

TS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gtilmcdgrk.html

Java: resp.statusCode()
来源：http://dali.daxiang520.top/Article/details/gtczkfuxir.html

Go:   resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gtxidmlcbn.html

Ruby: resp.code.to_i
来源：http://dali.dianchejie.cn/Article/details/gtrtyzonkw.html

C#:   (int)resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtxlcqdtzj.html

[L08] 并发请求多个地址
来源：http://dali.chenjidiqi.icu/Article/details/gtfgyxgnuj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daria6918.cn/Article/details/gtqkdffevr.html

PHP:  curl_multi_init() 系列
来源：http://dali.nwbrower.top/Article/details/gtvmepahkj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtqpqjfqmb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtagyqtfsv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenjidiqi.icu/Article/details/gtlbtfsrrw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.kuanghao11.cn/Article/details/gtxlmoyrmv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gtwttglvky.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guannengcc.top/Article/details/gtypdtyqwg.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtnrnoroaw.html

M. 命令行 / 进程 / 环境
来源：http://dali.hongshengwenyu.top/Article/details/gtyxutqltq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtuwwzrwkh.html

[M01] 读取命令行参数
来源：http://dali.wangdashe.top/Article/details/gtripzhwsd.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtkldhjbsm.html

PHP:  $argv;  $argc;
来源：http://dali.feifeiyinyue.top/Article/details/gtxbmtvrjs.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajozmvdg.html

TS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtpiatbfef.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gtqxwizkly.html

Go:   os.Args[1:]
来源：http://dali.hywenlv.cn/Article/details/gtbdvdgpjj.html

Ruby: ARGV
来源：http://dali.jiagoushi.top/Article/details/gtfzvliqdh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gtizjewfni.html

[M02] 读取环境变量
来源：http://dali.xinyue.icu/Article/details/gtxzdhdrxx.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtriilgrir.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgykltdgg.html

JS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gtseigmamb.html

TS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gtzhpyjotg.html

Java: System.getenv("HOME")
来源：http://dali.yvedp.cn/Article/details/gtyfifkqec.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jianghu66.top/Article/details/gttojprdqw.html

Ruby: ENV["HOME"]
来源：http://dali.gogol.net.cn/Article/details/gtgizuwtnv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtrclwanqm.html

[M03] 执行外部命令
来源：http://dali.redwolf501.top/Article/details/gtsblwrkzr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.haohaochexian.top/Article/details/gtwbfrtixv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ybcxt.top/Article/details/gtfjjwlzdf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gtrckqeoce.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gtfxxkwubd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shangyingyoupin.top/Article/details/gtdaqwduyv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhongyouzk.top/Article/details/gtnseojsxk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgufenzy.top/Article/details/gtjyzqlusi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxecuypz.html

[M04] 获取当前工作目录
来源：http://dali.gogol.net.cn/Article/details/gtssyeisms.html

Py:   os.getcwd()
来源：http://dali.ydzc1.top/Article/details/gtacjpvpci.html

PHP:  getcwd();
来源：http://dali.316326.xyz/Article/details/gtidkrrqkz.html

JS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gtqmwyjroj.html

TS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtvrdmybop.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guannengcc.top/Article/details/gtapmjcerl.html

Go:   os.Getwd()
来源：http://dali.yj202588.top/Article/details/gtyiwuauvg.html

Ruby: Dir.pwd
来源：http://dali.zdqjudy.top/Article/details/gtxuxiupdo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtleqsqzlv.html

[M05] 设置退出码
来源：http://dali.nanxuanxn.top/Article/details/gtoekiqivn.html

Py:   sys.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtjruevcto.html

PHP:  exit(1);
来源：http://dali.dashuyun.cn/Article/details/gtalmwpmss.html

JS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtmkdnauoa.html

TS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtknrzrkdw.html

Java: System.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtymcxgily.html

Go:   os.Exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtfxnswaqp.html

Ruby: exit 1
来源：http://dali.dianchejie.cn/Article/details/gtosfkzuwv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuxming.cn/Article/details/gtzcystpqo.html

[M06] 向标准错误输出
来源：http://dali.9152youxi.cn/Article/details/gtebejkhsk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gtdyfszuni.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yanxiufei.cn/Article/details/gtvvaenpfu.html

JS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gtwudtlzbn.html

TS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gtseqctoqy.html

Java: System.err.println("err")
来源：http://dali.cucudq.cn/Article/details/gtddyfutax.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigfzy.top/Article/details/gtdlbuxftd.html

Ruby: warn "err"
来源：http://dali.9152youxi.cn/Article/details/gtdaxfzxep.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gtlypuhsxf.html

[M07] 判断是否为主入口
来源：http://dali.cashguo.top/Article/details/gtnvusqakb.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangkeji.top/Article/details/gtworxuesf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gtatvujhfg.html

JS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtpglonoht.html

TS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gtmcrreqdu.html

Java: public static void main(String[] args)
来源：http://dali.dashuyun.cn/Article/details/gtijdolknv.html

Go:   func main()
来源：http://dali.vqdsnc.cn/Article/details/gtwjvhvoic.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cheryme.top/Article/details/gtzqlntiip.html

C#:   static void Main(string[] args)
来源：http://dali.yanxiufei.cn/Article/details/gtoartztjc.html

[M08] 获取系统与运行时信息
来源：http://dali.tian-w.cn/Article/details/gtylrgwpns.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sufxvd.cn/Article/details/gtbkeemjth.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.iojbl.cn/Article/details/gtupzdfoft.html

JS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gttshmvnws.html

TS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gtedoftnmk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxuanxn.top/Article/details/gtuursdxbn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gogol.net.cn/Article/details/gtzgauldez.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.iojbl.cn/Article/details/gteqfkjspj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yanxiufei.cn/Article/details/gtyizmtmtp.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtwzwenhzi.html

N. 数据结构与算法
来源：http://dali.dianchejie.cn/Article/details/gtihsejpkl.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjlvjkdcy.html

[N01] 二分查找（有序数组）
来源：http://dali.cheryme.top/Article/details/gtnmawkcyj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtrkkpofhu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtpbllhkrp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gttxbfxqxz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gtphggedaz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtmedxbavf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtstaqiaoh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sufxvd.cn/Article/details/gtnkjzymyx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gtgqofsvzm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.haohaochexian.top/Article/details/gtsunndajd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.9152youxi.cn/Article/details/gtjnujyiss.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tianlin.xyz/Article/details/gtgvfobhii.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gtimifxwwt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gtvdvyfywp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aibaodan.cn/Article/details/gtsensuvgm.html

Go:   slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gthocaxyow.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzrfuznm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhixingplan.top/Article/details/gtwijzbdpp.html

[N03] 快速排序（分治示例）
来源：http://dali.ydzc1.top/Article/details/gtviqaumks.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sysykeji.top/Article/details/gtetgxzyvm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hammf.cn/Article/details/gtnrwxaybo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gtycqtgvbe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zdqjudy.top/Article/details/gtztpeuwqc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj202588.top/Article/details/gtaldwfxce.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgfzy.top/Article/details/gtzxisyqkr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.snrcjt.cn/Article/details/gtlxumnjkx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dashuyun.cn/Article/details/gtfzvijvxe.html

[N04] 斐波那契数列
来源：http://dali.gzhubu.top/Article/details/gtnwnrxmxp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gtltjvsoqj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gtlovwdwfq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gtglewgolh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsqpnevh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gtonpzxoqo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.redwolf501.top/Article/details/gtfemwhdsu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gtcgzetqpb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtdgrazypn.html

[N05] 最大公约数
来源：http://dali.sxryk.cn/Article/details/gtzimtnhgz.html

Py:   math.gcd(a, b)
来源：http://dali.guowangkeji.top/Article/details/gtpsmucero.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aizwys.cn/Article/details/gtzuiidnvq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gotoacloud.top/Article/details/gtewpbhlnn.html


<!-- 参考信息 -->