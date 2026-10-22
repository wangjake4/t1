代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yanxiufei.cn/Article/details/gt2axemxdid.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.quarkkingdee.top/Article/details/gt2blctjpbb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gt2zvnjodwe.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuanzhike.top/Article/details/gt2kssqiyzz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuxming.cn/Article/details/gt2sfmjbfdq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ehwqpu.com/Article/details/gt2ybplmkfw.html

[J09] 时区处理
来源：http://dali.haohaochexian.top/Article/details/gt2nhkczxpe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ppjwa.cn/Article/details/gt2nmmcxflb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tnrasjac.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rivfcyas.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gt2czofrmug.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tanke756.top/Article/details/gt2detvpxdm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yzjaythl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhongyouzk.top/Article/details/gt2bswlbclx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuanzhike.top/Article/details/gt2sycommed.html

[J10] 取今天 / 本月第一天
来源：http://dali.birdmap.top/Article/details/gt2doxegqrr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sxryk.cn/Article/details/gt2tbvjfovv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xinyue.icu/Article/details/gt2tuvbbkxv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2ynfanfdt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2awwfpvra.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wgttcxtl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzhxfzng.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sufxvd.cn/Article/details/gt2cskowyqb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxinkj.top/Article/details/gt2wzdmdzcr.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2uskwzkid.html

K. JSON 与序列化
来源：http://dali.ppjwa.cn/Article/details/gt2xwiqetbc.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ktqnzyac.html

[K01] 对象转 JSON 字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2llhbofpr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gt2uovdgvnl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gt2zgahkwto.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2bhlwozkh.html

TS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2twaalbeo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xylfe.cn/Article/details/gt2bjweqrsx.html

Go:   json.Marshal(obj)
来源：http://dali.smart0.xyz/Article/details/gt2hxavixlk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj202588.top/Article/details/gt2uamvgokh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fzhhl.top/Article/details/gt2rdjasvwq.html

[K02] JSON 字符串转对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2pdptcwtn.html

Py:   json.loads(s)
来源：http://dali.chenzaomai.com/Article/details/gt2gicmiuct.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tian-w.cn/Article/details/gt2shonjmlr.html

JS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2svunnlhd.html

TS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gt2yvzngwak.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2criiyapb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gt2ilerxykw.html

Ruby: JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wzbbfsov.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zdqjudy.top/Article/details/gt2cjnukaxx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yvedp.cn/Article/details/gt2qsxpwzva.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gt2othauzty.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gt2tdekkktz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gt2jkynwwgh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gt2youcodlw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj202588.top/Article/details/gt2cnlacjmz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2bjonybfn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2axmnnwhy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shangyingyoupin.top/Article/details/gt2mvrgxwut.html

[K04] 读取 JSON 文件
来源：http://dali.xuanzx.com/Article/details/gt2wvhbumzk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.havefunace.top/Article/details/gt2gqkssaem.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xylfe.cn/Article/details/gt2dwzhtdqp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gt2kaqxurgw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gt2obajqbsi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ydzc1.top/Article/details/gt2bqkezsyh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gt2vxlekyml.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cucudq.cn/Article/details/gt2wdaailbg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gt2chtsmfbv.html

[K05] 深拷贝对象
来源：http://dali.tian-w.cn/Article/details/gt2jmpryrdp.html

Py:   copy.deepcopy(obj)
来源：http://dali.ivvv.top/Article/details/gt2mthrhwkc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sysykeji.top/Article/details/gt2yrrfnnib.html

JS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2nnrbxdcx.html

TS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gt2dkzkutti.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhengqikj.top/Article/details/gt2obzqsrbj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.havefunace.top/Article/details/gt2whysqoet.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnxiangtu.top/Article/details/gt2zvnzctcq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuetiantiany.cn/Article/details/gt2mlonsaix.html

[K06] 解析 URL 查询串
来源：http://dali.c1oappe.top/Article/details/gt2vfbrfqps.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tqwrxpkc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ehwqpu.com/Article/details/gt2atwjyjlh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gt2ferqsnwa.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gt2lfpzncvy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gzhubu.top/Article/details/gt2afphnonm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gt2zlzixmcd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gt2svmfbbam.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dihxskgb.html

[K07] 进制转换
来源：http://dali.xziqi.cn/Article/details/gt2mijplyem.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2qpaslppc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuxming.cn/Article/details/gt2mctmmkpq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2tgettsrh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gt2heaudubj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2iifexdhk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hammf.cn/Article/details/gt2pxbtmhig.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.snrcjt.cn/Article/details/gt2hokqrsxp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2neygliiy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cashguo.top/Article/details/gt2gxmutqnm.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2vlhcpudh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guannengcc.top/Article/details/gt2phqtbdna.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gt2ylpwybxf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gt2zfvidrqm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wiudaiyj.html

Go:   encoding/gob
来源：http://dali.shangyingyoupin.top/Article/details/gt2erjdcyca.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuanzx.com/Article/details/gt2kepfdoef.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gt2yypwkfpl.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2feudjbjs.html

L. 网络请求
来源：http://dali.9152youxi.cn/Article/details/gt2hrtxtzhl.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2kglvxrtv.html

[L01] 发送 GET 请求
来源：http://dali.andypj.xyz/Article/details/gt2gkhfscuv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.quarkkingdee.top/Article/details/gt2egxjdwfp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnqzz.top/Article/details/gt2leiqlhyz.html

JS:   await fetch(url)
来源：http://dali.cdnleiting.top/Article/details/gt2xgumfrjg.html

TS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gt2fpoohzvk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.meibo888.top/Article/details/gt2ahjqzgfg.html

Go:   resp, err := http.Get(url)
来源：http://dali.yonumen.top/Article/details/gt2xazpjylo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.andypj.xyz/Article/details/gt2tdfhvlpo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.0kj1m.cn/Article/details/gt2dbaulvoy.html

[L02] 发送 POST JSON
来源：http://dali.bjfxy.top/Article/details/gt2vowdzdbv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.snrcjt.cn/Article/details/gt2zcnjzvgu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tianlin.xyz/Article/details/gt2ntodkfbb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hvjiadod.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gt2tryiuuza.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigfzy.top/Article/details/gt2cjefcjpc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sgdsjkyq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zdqjudy.top/Article/details/gt2huyshrex.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nwbrower.top/Article/details/gt2qzqoisvh.html

[L03] 设置自定义请求头
来源：http://dali.zdqjudy.top/Article/details/gt2hjtlkils.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhoulong.xyz/Article/details/gt2kryincvl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2udhnglsu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gt2iqqbakpk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gt2wkyvwzpy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cucudq.cn/Article/details/gt2oucdhurl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.c1oappe.top/Article/details/gt2fqcgtghy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gogol.net.cn/Article/details/gt2clulkkkv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gt2txwommac.html

[L04] 设置超时
来源：http://dali.xinyue.icu/Article/details/gt2wgcwkexi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jiagoushi.top/Article/details/gt2utvaeyuc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dtwwklhh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gt2fvqvvnzx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gt2cciciqzb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cashguo.top/Article/details/gt2dkidzaxy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuanzx.com/Article/details/gt2azziubny.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nwbrower.top/Article/details/gt2hturuxkj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hammf.cn/Article/details/gt2nkyrrnkp.html

[L05] 上传文件（multipart）
来源：http://dali.gaohongyu789.top/Article/details/gt2sssnctjt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ppjwa.cn/Article/details/gt2yhzypsbk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kenpgznb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wbxpvwcj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.9152youxi.cn/Article/details/gt2xfmhxzad.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigfzy.top/Article/details/gt2jbqxsurh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhengqikj.top/Article/details/gt2yyzonhwn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ivvv.top/Article/details/gt2ztxznveh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2jpdfvbdk.html

[L06] 解析响应为 JSON
来源：http://dali.cheryme.top/Article/details/gt2hpjxncym.html

Py:   resp.json()
来源：http://dali.yj202588.top/Article/details/gt2qlwkqqys.html

PHP:  json_decode($body, true);
来源：http://dali.tanke756.top/Article/details/gt2pseppfns.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gt2dijgoejk.html

TS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gt2ltvzglqm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.smart0.xyz/Article/details/gt2edxqmyqi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.kuanghao11.cn/Article/details/gt2xbbrcvyq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.svipenyu.cn/Article/details/gt2sesiacpo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shuidangran.top/Article/details/gt2jjvxmqvl.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gt2cxzwhndo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daria6918.cn/Article/details/gt2tzbrahsa.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tanke756.top/Article/details/gt2ekuncqxj.html

JS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gt2eqbxwyjo.html

TS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gt2vbvfqgsg.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2tieqcxvx.html

Go:   resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gt2hjwlujed.html

Ruby: resp.code.to_i
来源：http://dali.ehwqpu.com/Article/details/gt2douendor.html

C#:   (int)resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2alaaqgfr.html

[L08] 并发请求多个地址
来源：http://dali.ppjwa.cn/Article/details/gt2rpwrtiaa.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yangfankeji.com/Article/details/gt2iydmibyc.html

PHP:  curl_multi_init() 系列
来源：http://dali.xinyue.icu/Article/details/gt2sgfzluqf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gt2wqqnedqr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gt2maauczjn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yanxiufei.cn/Article/details/gt2znybygmx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgfzy.top/Article/details/gt2vlvnnfdc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.andypj.xyz/Article/details/gt2rreisrun.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sysykeji.top/Article/details/gt2trrpzpzn.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2weekbyei.html

M. 命令行 / 进程 / 环境
来源：http://dali.sufxvd.cn/Article/details/gt2uunwwlia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yfshvhxl.html

[M01] 读取命令行参数
来源：http://dali.guannengcc.top/Article/details/gt2katlpkvy.html

Py:   sys.argv[1:]
来源：http://dali.redwolf501.top/Article/details/gt2bvastlls.html

PHP:  $argv;  $argc;
来源：http://dali.redwolf501.top/Article/details/gt2agxoabsn.html

JS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gt2uibkzlui.html

TS:   process.argv.slice(2)
来源：http://dali.xuanzx.com/Article/details/gt2obcbzjry.html

Java: args 数组（main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gt2cgreakjg.html

Go:   os.Args[1:]
来源：http://dali.ydzc1.top/Article/details/gt2wilvylrh.html

Ruby: ARGV
来源：http://dali.svipenyu.cn/Article/details/gt2izepvklu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gt2qyjconss.html

[M02] 读取环境变量
来源：http://dali.mhx1999.top/Article/details/gt2vuxmmxmp.html

Py:   os.environ.get("HOME")
来源：http://dali.aibaodan.cn/Article/details/gt2huvoqkkn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gt2pdxpbicj.html

JS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gt2etjxdctj.html

TS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gt2bixxagic.html

Java: System.getenv("HOME")
来源：http://dali.sysykeji.top/Article/details/gt2bqvyjjde.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2hfegsrkd.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258.top/Article/details/gt2gqqeespo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.iojbl.cn/Article/details/gt2mulhmtyc.html

[M03] 执行外部命令
来源：http://dali.bjfxy.top/Article/details/gt2taodxovl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xziqi.cn/Article/details/gt2emmaafpo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.meibo888.top/Article/details/gt2oiqiqosi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gt2nbgyeies.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2qujzzokm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.iojbl.cn/Article/details/gt2teradakz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gogol.net.cn/Article/details/gt2pxnclewh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zdoouwxq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pycfn.com/Article/details/gt2ltmfaxqe.html

[M04] 获取当前工作目录
来源：http://dali.jinqigfzy.top/Article/details/gt2qreeitsc.html

Py:   os.getcwd()
来源：http://dali.xylfe.cn/Article/details/gt2lphdcxen.html

PHP:  getcwd();
来源：http://dali.jqgufenzy.top/Article/details/gt2tuywmlqu.html

JS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gt2pfmvhvtj.html

TS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gt2bxlpgyru.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daria6918.cn/Article/details/gt2psvxkdvm.html

Go:   os.Getwd()
来源：http://dali.zycfv.cn/Article/details/gt2sqaniyla.html

Ruby: Dir.pwd
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kzyixfqa.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cucudq.cn/Article/details/gt2gthxxdlq.html

[M05] 设置退出码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djinojry.html

Py:   sys.exit(1)
来源：http://dali.yj202588.top/Article/details/gt2dluectzu.html

PHP:  exit(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vdsrwqtq.html

JS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2piahgfcd.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2ncegdjkt.html

Java: System.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2uxnjamft.html

Go:   os.Exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2vmmmnqpg.html

Ruby: exit 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2rogtmbxz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xylfe.cn/Article/details/gt2jokkwzwr.html

[M06] 向标准错误输出
来源：http://dali.kuanghao11.cn/Article/details/gt2dupjvqqw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ydzc1.top/Article/details/gt2vuehyhti.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sysykeji.top/Article/details/gt2pwqdyjwq.html

JS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gt2fejdnuct.html

TS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tggliboe.html

Java: System.err.println("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2opxashvd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yanxiufei.cn/Article/details/gt2orhegktf.html

Ruby: warn "err"
来源：http://dali.tanke756.top/Article/details/gt2mcvnceks.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2cruwxygt.html

[M07] 判断是否为主入口
来源：http://dali.yuxming.cn/Article/details/gt2vbxarqpw.html

Py:   if __name__ == "__main__":
来源：http://dali.guannengcc.top/Article/details/gt2refjsyju.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tianlin.xyz/Article/details/gt2rpcceelq.html

JS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gt2ydrsjkte.html

TS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gt2yqrgxrpx.html

Java: public static void main(String[] args)
来源：http://dali.ehwqpu.com/Article/details/gt2bxgktnol.html

Go:   func main()
来源：http://dali.feifeiyinyue.top/Article/details/gt2chfriokf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sxryk.cn/Article/details/gt2jdxcxlwo.html

C#:   static void Main(string[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kbkngkaq.html

[M08] 获取系统与运行时信息
来源：http://dali.wangdashe.top/Article/details/gt2pxircyso.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhixingplan.top/Article/details/gt2uqdweumo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258888.top/Article/details/gt2hhfavcvr.html

JS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gt2yjljmuic.html

TS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gt2xwbyuets.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aibaodan.cn/Article/details/gt2cidjpvqh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sweek.top/Article/details/gt2ecqaxueg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxinkj.top/Article/details/gt2aasbeysy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guannengcc.top/Article/details/gt2fhsmvtvz.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2hcimpibv.html

N. 数据结构与算法
来源：http://dali.xuetiantiany.cn/Article/details/gt2ncmvfkvj.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2zjcukbob.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgufenzy.top/Article/details/gt2ghuelifn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2omdaquij.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xziqi.cn/Article/details/gt2yglwhhjv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rfcenqni.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gt2vlmbdtjr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gt2gupyohvw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qoasvbcr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jqgfzy.top/Article/details/gt2tlcfijro.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2azwwlaow.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cashguo.top/Article/details/gt2wglzfftg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gt2zmqpdvoq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aibaodan.cn/Article/details/gt2extquljk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gt2pjkqweig.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gt2jlwtjmhl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.birdmap.top/Article/details/gt2bpqvapig.html

Go:   slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2ijnbzcsb.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gt2zhctfsjb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.iojbl.cn/Article/details/gt2bfnyftny.html

[N03] 快速排序（分治示例）
来源：http://dali.hywenlv.cn/Article/details/gt2myjmxyat.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sxryk.cn/Article/details/gt2rdygduud.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fjcruchy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gt2qzjpuxjy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gt2mjnufvfa.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.svipenyu.cn/Article/details/gt2nhwavrzf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.bjfxy.top/Article/details/gt2exvrbmgf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hnqzz.top/Article/details/gt2blglfcyq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.c1oappe.top/Article/details/gt2avvuftrq.html

[N04] 斐波那契数列
来源：http://dali.xuanzx.com/Article/details/gt2wjeaejxv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cdnleiting.top/Article/details/gt2ahzbraut.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhmvplmp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gt2gbcppzwl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vvlmpfuh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ybcxt.top/Article/details/gt2kytxnnzj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinqigufen.top/Article/details/gt2fxovttvr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gt2vovrpysq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gt2fttjgztj.html

[N05] 最大公约数
来源：http://dali.feifeiyinyue.top/Article/details/gt2nnhllygi.html

Py:   math.gcd(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2stpzlmej.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.9152youxi.cn/Article/details/gt2ilvfjtag.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gt2sxiabfko.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gt2ghsfcpgc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.svipenyu.cn/Article/details/gt2navikdad.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fengsongda.top/Article/details/gt2wgynpixv.html

Ruby: a.gcd(b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2opclulgt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daria6918.cn/Article/details/gt2ppecwzdm.html

[N06] 判断回文字符串
来源：http://dali.snrcjt.cn/Article/details/gt2vlecimqf.html

Py:   s == s[::-1]
来源：http://dali.daria6918.cn/Article/details/gt2owtcljcc.html

PHP:  $s === strrev($s);
来源：http://dali.nwbrower.top/Article/details/gt2ktrxkbir.html


<!-- 参考信息 -->