代发 wailian999

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gtnevccgcq.html

Go:   end.Sub(start).Hours()
来源：http://dali.cdnleiting.top/Article/details/gtjyrjirdm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xylfe.cn/Article/details/gtpvihwzww.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhiwuduotai.top/Article/details/gtnjwfhffb.html

[J07] 比较两个日期
来源：http://dali.ivvv.top/Article/details/gtroylwsyv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtsycyexml.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgajtjfg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gtrksdixkz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gtukrjwajc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gtfywpxdur.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fzhhl.top/Article/details/gtgwiprtem.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtekwuapdj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtmbvxxvhd.html

[J08] 提取年月日与星期
来源：http://dali.dashuyun.cn/Article/details/gtzubhbqpj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.mhx1999.top/Article/details/gtozdhcqdu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.9152youxi.cn/Article/details/gteuirucsw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigufen.top/Article/details/gthczalltk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.svipenyu.cn/Article/details/gtwyfdzajb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.andypj.xyz/Article/details/gtbrmaxegy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.svipenyu.cn/Article/details/gtzpnfuive.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daxiang520.top/Article/details/gthgfugitk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ppjwa.cn/Article/details/gtijhclnko.html

[J09] 时区处理
来源：http://dali.zhoulong.xyz/Article/details/gtwyzxkyyh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuanzhike.top/Article/details/gtxnfmnvpx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shzxlz.cn/Article/details/gtasvwtxyv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gtvfmwqnfq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gtrtiuplyl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xziqi.cn/Article/details/gtksfajbff.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aizwys.cn/Article/details/gtmpekvuat.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuanzhike.top/Article/details/gtarkvztgx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.316326.xyz/Article/details/gtllydyegy.html

[J10] 取今天 / 本月第一天
来源：http://dali.dianchejie.cn/Article/details/gtoqcxeyxf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jianghu66.top/Article/details/gtavvcdkqr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.c1oappe.top/Article/details/gtpqcijuty.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ivvv.top/Article/details/gtlopeadgq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shuidangran.top/Article/details/gtxdbhfcmt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtygxfpqpc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fengsongda.top/Article/details/gtjcngdwym.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ivvv.top/Article/details/gtvgewbjyl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhongyouzk.top/Article/details/gtgxwbcmpk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqnynuqnf.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gtenhdzqir.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtrqkfpaur.html

[K01] 对象转 JSON 字符串
来源：http://dali.aizwys.cn/Article/details/gtbbrtxnoq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gtlvqlvfzv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtypcrwids.html

JS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gtdtpwohiz.html

TS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gtkwbxzpnb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yonumen.top/Article/details/gtnakipmsg.html

Go:   json.Marshal(obj)
来源：http://dali.dianchejie.cn/Article/details/gtzpslupwh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gtsxiffned.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sufxvd.cn/Article/details/gtsnbsopdv.html

[K02] JSON 字符串转对象
来源：http://dali.zhoulong.xyz/Article/details/gtassgopcx.html

Py:   json.loads(s)
来源：http://dali.yongpay.top/Article/details/gtkwrpdqhl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigufen.top/Article/details/gtyltrfmep.html

JS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbkknbyv.html

TS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gterhrlfpf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daxiang520.top/Article/details/gtvjehmvho.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gtfmcientw.html

Ruby: JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtjxpimbya.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlojedufn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guowangkeji.top/Article/details/gtiysjkeuy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gtbbjwckfq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gtgmokiopn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gtkjmswqlu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gtsbrbuqyz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtqbldfksi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuetiantiany.cn/Article/details/gtgmmgvmax.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyvfmcqp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhmxhjwy.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258.top/Article/details/gtmpwilzhc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nwbrower.top/Article/details/gttxcroquv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenjidiqi.icu/Article/details/gtfjzqcclu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtkcsymrcd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtsozhedev.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtlmgfizgz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoouwgrdf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gtrqvimsch.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gtdnsohjcu.html

[K05] 深拷贝对象
来源：http://dali.gogol.net.cn/Article/details/gtnfsckuii.html

Py:   copy.deepcopy(obj)
来源：http://dali.xziqi.cn/Article/details/gtjnrwrjmr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jlsjyb.cn/Article/details/gtaoqqbvpm.html

JS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtamdtfinp.html

TS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtgahdhszg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tianlin.xyz/Article/details/gtofyvdvkr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhoulong.xyz/Article/details/gtsimztenb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zdqjudy.top/Article/details/gtplxwcdbp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gtfamescjl.html

[K06] 解析 URL 查询串
来源：http://dali.dashuyun.cn/Article/details/gtbitcvhlx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.mhx1999.top/Article/details/gtjpyjkgum.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gzhubu.top/Article/details/gthyxlmbvk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gtbslqgsmy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtnnleiyuy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yanxiufei.cn/Article/details/gtxquddxut.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gtsczplona.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfablsewr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxqeswum.html

[K07] 进制转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxauwybiw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gthyrjiall.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.0kj1m.cn/Article/details/gteypljcqs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtglioliww.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtumrhilcu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtcrofrvmf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.haohaochexian.top/Article/details/gtzipgdvxc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuanzx.com/Article/details/gttzcvqzsk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtxwqkfbha.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yangfankeji.com/Article/details/gtuwqxhbwo.html

Py:   pickle.dumps(obj)
来源：http://dali.birdmap.top/Article/details/gtadgpdcnb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yongpay.top/Article/details/gtzwuagbon.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gtjsshggwg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gtilnysjyp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tianlin.xyz/Article/details/gtugcqyjck.html

Go:   encoding/gob
来源：http://dali.daxiang520.top/Article/details/gtiqahakvl.html

Ruby: Marshal.dump(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtljofixlx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtxhqtnifc.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdjcwmok.html

L. 网络请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gttagphzey.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gticyqgfqq.html

[L01] 发送 GET 请求
来源：http://dali.cqqwz.cn/Article/details/gtvpbksvoq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xylfe.cn/Article/details/gtupgfhqtb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shangyingyoupin.top/Article/details/gtoxwphrxf.html

JS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtvqasonpy.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvaryozz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258.top/Article/details/gtmzsqtcbt.html

Go:   resp, err := http.Get(url)
来源：http://dali.andypj.xyz/Article/details/gtizthblob.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yonumen.top/Article/details/gtmjnsramk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fengsongda.top/Article/details/gtpnnjfcfd.html

[L02] 发送 POST JSON
来源：http://dali.fzhhl.top/Article/details/gtudjvkfth.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gtcafrykob.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.daria6918.cn/Article/details/gtivacefvc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtkrkicscz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gthkhiaaeh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtruouqmne.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hywenlv.cn/Article/details/gtnbantdft.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.316326.xyz/Article/details/gtjxuxdwtb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.9152youxi.cn/Article/details/gtnxftldhc.html

[L03] 设置自定义请求头
来源：http://dali.daxiang520.top/Article/details/gtcngdjstm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.svipenyu.cn/Article/details/gtzwvalkod.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.andypj.xyz/Article/details/gtwxfphwwy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gtxfnjtyle.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gtthmpuhoc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.bjfxy.top/Article/details/gtaoucqnpt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gtqbjjrcdz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuanzx.com/Article/details/gtxmybscij.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrzpidyc.html

[L04] 设置超时
来源：http://dali.0kj1m.cn/Article/details/gtuegoqwqx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.kuanghao11.cn/Article/details/gtkgqhjyxn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sweek.top/Article/details/gtbotfriha.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gtarhkeyvw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gtoistxjhj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnqzz.top/Article/details/gtwkrielqw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gtitrsjsup.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yanxiufei.cn/Article/details/gtrkntcsdl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ppjwa.cn/Article/details/gtobjeklqv.html

[L05] 上传文件（multipart）
来源：http://dali.guannengcc.top/Article/details/gtgwzcrgoc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.iojbl.cn/Article/details/gtsxqoawyp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuanzx.com/Article/details/gtqnvzwauq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gtssugezug.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gtszhytxyc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhengqikj.top/Article/details/gtxnoccdug.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xinyue.icu/Article/details/gtflaqvhqw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxinkj.top/Article/details/gtobczkpgy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.wangdashe.top/Article/details/gtnqbpkaix.html

[L06] 解析响应为 JSON
来源：http://dali.hysaishi.cn/Article/details/gthzajpibc.html

Py:   resp.json()
来源：http://dali.wangdashe.top/Article/details/gtkhgczzip.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigufen.top/Article/details/gtdjrijrws.html

JS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtvesyoewf.html

TS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqgswfao.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvafplnla.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cheryme.top/Article/details/gtmywnmlax.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjabqmybz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yueranfly.top/Article/details/gtwbyeertt.html

[L07] 处理 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gtlltibsji.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tianlin.xyz/Article/details/gtxevaxhhc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ivvv.top/Article/details/gtxmctzgwu.html

JS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gtvxznbumo.html

TS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gtldsutxlv.html

Java: resp.statusCode()
来源：http://dali.guannengcc.top/Article/details/gtexwiyjmn.html

Go:   resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gthnrtluuz.html

Ruby: resp.code.to_i
来源：http://dali.ivvv.top/Article/details/gtqukufwof.html

C#:   (int)resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtyjmzbqcl.html

[L08] 并发请求多个地址
来源：http://dali.nwbrower.top/Article/details/gtgzaacuke.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cqqwz.cn/Article/details/gtogpnvsws.html

PHP:  curl_multi_init() 系列
来源：http://dali.0kj1m.cn/Article/details/gtqbjaufzv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gtzjcvogab.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gtluquueji.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.snrcjt.cn/Article/details/gtkukkfpoh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tian-w.cn/Article/details/gtsmocmamv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.316326.xyz/Article/details/gtatggxpya.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtdomtywkj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmhecjmzm.html

M. 命令行 / 进程 / 环境
来源：http://dali.daxiang520.top/Article/details/gtpcxzrfbk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtupsvhyhy.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpzusmzh.html

Py:   sys.argv[1:]
来源：http://dali.nwbrower.top/Article/details/gtockksbde.html

PHP:  $argv;  $argc;
来源：http://dali.wangdashe.top/Article/details/gtqkvlgeig.html

JS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gtrdpoyrjm.html

TS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtdzycgqpm.html

Java: args 数组（main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gtgoyitequ.html

Go:   os.Args[1:]
来源：http://dali.chenzaomai.com/Article/details/gtmwdxcabc.html

Ruby: ARGV
来源：http://dali.jianghu66.top/Article/details/gtjeuzsfzd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gtfcabikgc.html

[M02] 读取环境变量
来源：http://dali.daria6918.cn/Article/details/gtqtezfhpd.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtrsknutgi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gtzvvhwoyi.html

JS:   process.env.HOME
来源：http://dali.vqdsnc.cn/Article/details/gtxbbkmtdi.html

TS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gtkgeoomge.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtalznhzzj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xinyue.icu/Article/details/gtugkhazbn.html

Ruby: ENV["HOME"]
来源：http://dali.zycfv.cn/Article/details/gtvwsfmwjn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.birdmap.top/Article/details/gtlwrnnkvu.html

[M03] 执行外部命令
来源：http://dali.birdmap.top/Article/details/gtgglcdvwp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.snrcjt.cn/Article/details/gtaqtayyje.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxinkj.top/Article/details/gtmoccdahf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gtgkqaftyt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gtqgtoswgb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbygbohq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ehwqpu.com/Article/details/gttcvmlvxl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zdqjudy.top/Article/details/gtmmfmlyix.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guowangkeji.top/Article/details/gtnqmryvkg.html

[M04] 获取当前工作目录
来源：http://dali.xinyue.icu/Article/details/gtgsddjsbd.html

Py:   os.getcwd()
来源：http://dali.yj202588.top/Article/details/gtfixslcyt.html

PHP:  getcwd();
来源：http://dali.cdnleiting.top/Article/details/gtvkkilroc.html

JS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gtgjrizzis.html

TS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gtjtfmwqbm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pycfn.com/Article/details/gtyisnefjv.html

Go:   os.Getwd()
来源：http://dali.zhixingplan.top/Article/details/gtcctmpfdy.html

Ruby: Dir.pwd
来源：http://dali.yj202588.top/Article/details/gtlbuqysph.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daria6918.cn/Article/details/gtrpsjpasm.html

[M05] 设置退出码
来源：http://dali.andypj.xyz/Article/details/gtjeagskao.html

Py:   sys.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtzkcukttx.html

PHP:  exit(1);
来源：http://dali.chenzaomai.com/Article/details/gtxeiommcx.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjxigalq.html

TS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtrvqjkgff.html

Java: System.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtwycmcrjh.html

Go:   os.Exit(1)
来源：http://dali.cucudq.cn/Article/details/gttwnyoxmf.html

Ruby: exit 1
来源：http://dali.pycfn.com/Article/details/gtcnkvitax.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daria6918.cn/Article/details/gtwcfdzifg.html

[M06] 向标准错误输出
来源：http://dali.hnxiangtu.top/Article/details/gtbzabjcyw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipesbmbz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhongyouzk.top/Article/details/gtkcsjqslk.html

JS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtjgaabsks.html

TS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gtuahghquw.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtynrxskkl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.guannengcc.top/Article/details/gtkxflxhzi.html

Ruby: warn "err"
来源：http://dali.zhongyouzk.top/Article/details/gttjblmvip.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtsempleqf.html

[M07] 判断是否为主入口
来源：http://dali.tianlin.xyz/Article/details/gtlcpuwrrd.html

Py:   if __name__ == "__main__":
来源：http://dali.ehwqpu.com/Article/details/gtyrsqflaw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.quarkkingdee.top/Article/details/gtbqcopfyx.html

JS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnckovpq.html

TS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gtitzxvopf.html

Java: public static void main(String[] args)
来源：http://dali.gzhubu.top/Article/details/gtyypgxtgd.html

Go:   func main()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrmbkloc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxinkj.top/Article/details/gtbmcezuqa.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigfzy.top/Article/details/gtumkyzyar.html

[M08] 获取系统与运行时信息
来源：http://dali.hongshengwenyu.top/Article/details/gtjhdoccls.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ppjwa.cn/Article/details/gtlagzcorg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuxming.cn/Article/details/gtelyadtfr.html

JS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gtowfcrhqb.html

TS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gtamxhdpwl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jianghu66.top/Article/details/gtddwzyyum.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yanxiufei.cn/Article/details/gtopxjhubl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigufen.top/Article/details/gtubuccmfj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xinyue.icu/Article/details/gtmsmxhlvr.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtagzaxicj.html

N. 数据结构与算法
来源：http://dali.andypj.xyz/Article/details/gtgrtnocbf.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtuazjkglc.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gtyyhvmmoh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtvartoyia.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gzhubu.top/Article/details/gtfxtbxlps.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gtqawxafmo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gtlkqwzbwz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtpecbvhqt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtgolrtwfu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.birdmap.top/Article/details/gtfcgkvkry.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtfjfxeqve.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shzxlz.cn/Article/details/gtilreisur.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtybdfhrtf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuanzhike.top/Article/details/gtebuujryh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gthmwonaay.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gtbqegebcv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sysykeji.top/Article/details/gtkuwqkksw.html

Go:   slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gtndfgwslg.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gtkerlcyjm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sufxvd.cn/Article/details/gtdctflxwb.html

[N03] 快速排序（分治示例）
来源：http://dali.chenjidiqi.icu/Article/details/gtivdwgnmb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgufenzy.top/Article/details/gtmfipagsg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhongyouzk.top/Article/details/gtefbnjtya.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gttnkcwnrn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgxrwsdl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guannengcc.top/Article/details/gtbeppzeqy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pycfn.com/Article/details/gtkbwabqdf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gogol.net.cn/Article/details/gtdnobvncd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gaohongyu789.top/Article/details/gtrbhvjrmz.html

[N04] 斐波那契数列
来源：http://dali.birdmap.top/Article/details/gthufopgbl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gtvlbstpej.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gtgmbkrjek.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtyfgtjsra.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gtkvdmpzks.html


<!-- 参考信息 -->