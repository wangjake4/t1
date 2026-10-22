代发 wailian999

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.vqdsnc.cn/Article/details/gt2oqikclhs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tian-w.cn/Article/details/gt2wnvlwwaj.html

[J09] 时区处理
来源：http://dali.zhixingplan.top/Article/details/gt2qxopiygx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.c1oappe.top/Article/details/gt2sdguuwvj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aibaodan.cn/Article/details/gt2lxwneyld.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xqaljfru.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gt2fnlbvboh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigfzy.top/Article/details/gt2phsseiwu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.mhx1999.top/Article/details/gt2fqadzqdz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fzhhl.top/Article/details/gt2rtdbnqmm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangdashe.top/Article/details/gt2vegdujag.html

[J10] 取今天 / 本月第一天
来源：http://dali.ydzc1.top/Article/details/gt2kjrznsfa.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sweek.top/Article/details/gt2jiylocfs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.mhx1999.top/Article/details/gt2avfwwvql.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sysykeji.top/Article/details/gt2rvtdgrlf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shuidangran.top/Article/details/gt2nxjjpkke.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gt2pwfpmnjd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.quarkkingdee.top/Article/details/gt2vajojsjg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhiwuduotai.top/Article/details/gt2drhsgmzi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guowangkeji.top/Article/details/gt2mnjfwkno.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2tqmltpbf.html

K. JSON 与序列化
来源：http://dali.jianghu66.top/Article/details/gt2awvjhnij.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2jznuqiai.html

[K01] 对象转 JSON 字符串
来源：http://dali.ppjwa.cn/Article/details/gt2vfwrtbbn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ppjwa.cn/Article/details/gt2cnawipmj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xadtviek.html

JS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ksonjsaq.html

TS:   JSON.stringify(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2gvtndcfl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ivvv.top/Article/details/gt2hcyizkze.html

Go:   json.Marshal(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ntlaaqma.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ehwqpu.com/Article/details/gt2nouapskf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xaqcyxgh.html

[K02] JSON 字符串转对象
来源：http://dali.nanxinkj.top/Article/details/gt2cuniutdk.html

Py:   json.loads(s)
来源：http://dali.guannengcc.top/Article/details/gt2jqbhuwcz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pkqbccmp.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2gqmzevtn.html

TS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2vvtntjvo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ehwqpu.com/Article/details/gt2weopquap.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gt2hmpqrbrl.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wrzccqqv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gzhubu.top/Article/details/gt2skjruxsh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gt2rrzajzwu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zltcdbva.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gt2fwgqwbsb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cucudq.cn/Article/details/gt2kxchnjal.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gt2sgdzbjva.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2qjzsgzhx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hammf.cn/Article/details/gt2jdmhoexa.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.redwolf501.top/Article/details/gt2imsehuvx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guowangkeji.top/Article/details/gt2upyzlpev.html

[K04] 读取 JSON 文件
来源：http://dali.yuxming.cn/Article/details/gt2sonjornd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cdnleiting.top/Article/details/gt2kemtqbqr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aibaodan.cn/Article/details/gt2jmghyrqe.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gt2nowwmlfl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gt2vxzzidsl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gt2hmhvbqrb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gt2lxnjvhkp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cheryme.top/Article/details/gt2xpaskbif.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gt2rbefkkas.html

[K05] 深拷贝对象
来源：http://dali.zhoulong.xyz/Article/details/gt2kemtqqce.html

Py:   copy.deepcopy(obj)
来源：http://dali.tian-w.cn/Article/details/gt2ivqzwpxu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.redwolf501.top/Article/details/gt2kzyiptld.html

JS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2ygtltglk.html

TS:   structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gt2cotzopjc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fzhhl.top/Article/details/gt2rxvktmbo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cheryme.top/Article/details/gt2fwqophhw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sweek.top/Article/details/gt2sahizxjx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sysykeji.top/Article/details/gt2lnkjospr.html

[K06] 解析 URL 查询串
来源：http://dali.tianlin.xyz/Article/details/gt2erbcmvir.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.iojbl.cn/Article/details/gt2rzqttqfn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cashguo.top/Article/details/gt2peibqlmw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gt2gpmdqegb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gt2jvkemlcc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhengqikj.top/Article/details/gt2twjaqeuh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gt2ruuqarmj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gt2drxndadc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gt2zbldqllb.html

[K07] 进制转换
来源：http://dali.yanxiufei.cn/Article/details/gt2bdhsyidd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2qzxgrure.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fzgzfgtn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2neqijtla.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gt2xsxcigkn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2wdiayfsc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yangfankeji.com/Article/details/gt2uelagtdf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ucwjnbbp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2ucppcbst.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.wangshuangyany.cn/Article/details/gt2bbwpkiwx.html

Py:   pickle.dumps(obj)
来源：http://dali.pycfn.com/Article/details/gt2bodjbvue.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj202588.top/Article/details/gt2cdzcqutj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gt2fjmmzqyw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gt2sjvifxvo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tianlin.xyz/Article/details/gt2ctppqlfj.html

Go:   encoding/gob
来源：http://dali.sufxvd.cn/Article/details/gt2ekyyitjz.html

Ruby: Marshal.dump(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2gimtcyla.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gt2eralcnup.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2eouzonsq.html

L. 网络请求
来源：http://dali.chenjidiqi.icu/Article/details/gt2sblqglpg.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2sgfdkbqo.html

[L01] 发送 GET 请求
来源：http://dali.xylfe.cn/Article/details/gt2vfsshczt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cheryme.top/Article/details/gt2cfzgcwpv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shzxlz.cn/Article/details/gt2dqjkmbvm.html

JS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gt2sijzknrn.html

TS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gt2slgvmlvn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daria6918.cn/Article/details/gt2gnmkrzsv.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2pypjvrtb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.bjfxy.top/Article/details/gt2wzrrscvy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yanxiufei.cn/Article/details/gt2ajfaoaxj.html

[L02] 发送 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gt2ksgjjxqi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.pycfn.com/Article/details/gt2brjtgtbo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.andypj.xyz/Article/details/gt2uyzxxify.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gt2jssaguop.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gt2byucghkb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258.top/Article/details/gt2btgwjmkc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.mhx1999.top/Article/details/gt2rtyqzvmu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xziqi.cn/Article/details/gt2tkpnivgh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guowangkeji.top/Article/details/gt2fehfvrgb.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gt2iqlltfml.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shangyingyoupin.top/Article/details/gt2kuywbkht.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gogol.net.cn/Article/details/gt2arstgzxd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gt2wfodywpx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dianchejie.cn/Article/details/gt2ktzkamrz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhixingplan.top/Article/details/gt2lkyahkaj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gt2pnvtltlh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.quarkkingdee.top/Article/details/gt2zushagja.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gt2gwbabgwq.html

[L04] 设置超时
来源：http://dali.jiagoushi.top/Article/details/gt2dqtomuad.html

Py:   requests.get(url, timeout=5)
来源：http://dali.daxiang520.top/Article/details/gt2bofbazvx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhongyouzk.top/Article/details/gt2thelxdgq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gt2kvshtrbk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gt2ezrgknny.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.birdmap.top/Article/details/gt2jlacgcxg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2yywrykvv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hfpthk.cn/Article/details/gt2reiwgrss.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cqqwz.cn/Article/details/gt2djutvykh.html

[L05] 上传文件（multipart）
来源：http://dali.9152youxi.cn/Article/details/gt2yuuvrsax.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jianghu66.top/Article/details/gt2uzbnapge.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.iojbl.cn/Article/details/gt2fnuisiam.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gt2zopbldzi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gt2ghiirleq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.smart0.xyz/Article/details/gt2pegxdxce.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cqqwz.cn/Article/details/gt2roncgimk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hfpthk.cn/Article/details/gt2zeorzbft.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2glimmbul.html

[L06] 解析响应为 JSON
来源：http://dali.zhongyouzk.top/Article/details/gt2yjkjfcxy.html

Py:   resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gt2pnggidxg.html

PHP:  json_decode($body, true);
来源：http://dali.gotoacloud.top/Article/details/gt2fcgjcobb.html

JS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gt2lykvrsjk.html

TS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gt2bjfngkou.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gt2yhrhtmqm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.haohaochexian.top/Article/details/gt2ynnxrjwn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kejxhrxu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aizwys.cn/Article/details/gt2aewhujys.html

[L07] 处理 HTTP 状态码
来源：http://dali.ppjwa.cn/Article/details/gt2bzdkxhtd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.quarkkingdee.top/Article/details/gt2lujaqefp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tanke756.top/Article/details/gt2jvwiawvi.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gt2gfktetaj.html

TS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xrblkbzp.html

Java: resp.statusCode()
来源：http://dali.sxryk.cn/Article/details/gt2zyiigwil.html

Go:   resp.StatusCode
来源：http://dali.andypj.xyz/Article/details/gt2kttsfjba.html

Ruby: resp.code.to_i
来源：http://dali.shzxlz.cn/Article/details/gt2ymckshkj.html

C#:   (int)resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gt2orlyryis.html

[L08] 并发请求多个地址
来源：http://dali.chenlongwang.top/Article/details/gt2grydtehx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cqqwz.cn/Article/details/gt2jthfxmon.html

PHP:  curl_multi_init() 系列
来源：http://dali.aizwys.cn/Article/details/gt2finuxadn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gt2akxczerf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gt2olpogbjj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ppjwa.cn/Article/details/gt2fxvyxmyr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cucudq.cn/Article/details/gt2uprfylog.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.smart0.xyz/Article/details/gt2zishnxpm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnqzz.top/Article/details/gt2yjqrirkl.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2zervargp.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxuanxn.top/Article/details/gt2kgumlhmp.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2vgtyfkdj.html

[M01] 读取命令行参数
来源：http://dali.aizwys.cn/Article/details/gt2dorxoftf.html

Py:   sys.argv[1:]
来源：http://dali.xuanzx.com/Article/details/gt2hclestck.html

PHP:  $argv;  $argc;
来源：http://dali.zhoulong.xyz/Article/details/gt2whtkdzkv.html

JS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2psmxqfmh.html

TS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gt2sxubznlw.html

Java: args 数组（main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gt2ejpzzcbb.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gt2uxyovlxf.html

Ruby: ARGV
来源：http://dali.cucudq.cn/Article/details/gt2vgqhjxpi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gt2xddcddih.html

[M02] 读取环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2yiybyqvu.html

Py:   os.environ.get("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2txjnotml.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ietzxefu.html

JS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gt2wlcjxepp.html

TS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gt2bfklbhcv.html

Java: System.getenv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mnzmsdyo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuanzx.com/Article/details/gt2wbabpgbm.html

Ruby: ENV["HOME"]
来源：http://dali.yueranfly.top/Article/details/gt2lzxixhfy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aizwys.cn/Article/details/gt2mivsfpig.html

[M03] 执行外部命令
来源：http://dali.guannengcc.top/Article/details/gt2lzcjbsxb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aizwys.cn/Article/details/gt2cejozubx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.vqdsnc.cn/Article/details/gt2vwadczdu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gt2jrsdpggf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gt2zctikbxq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenzaomai.com/Article/details/gt2waeuevbn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.svipenyu.cn/Article/details/gt2donomiul.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.birdmap.top/Article/details/gt2oxbvmuxb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yonumen.top/Article/details/gt2muejakdl.html

[M04] 获取当前工作目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2pvbwfrea.html

Py:   os.getcwd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2rdysdaym.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gt2wottgmdg.html

JS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gt2mdvymrtn.html

TS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gt2wzsjtfzi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258.top/Article/details/gt2seziogkw.html

Go:   os.Getwd()
来源：http://dali.redwolf501.top/Article/details/gt2dsttgmxj.html

Ruby: Dir.pwd
来源：http://dali.yanxiufei.cn/Article/details/gt2zbvnhkzw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cashguo.top/Article/details/gt2eiwnwzvs.html

[M05] 设置退出码
来源：http://dali.nanxinkj.top/Article/details/gt2wuaffemj.html

Py:   sys.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gt2vqvejgsx.html

PHP:  exit(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2krjofufy.html

JS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2ykkfirsu.html

TS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2ddptgvbh.html

Java: System.exit(1)
来源：http://dali.yj202588.top/Article/details/gt2rodynrcc.html

Go:   os.Exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2knnpfusm.html

Ruby: exit 1
来源：http://dali.haohaochexian.top/Article/details/gt2yuxxhpcd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xylfe.cn/Article/details/gt2eodjvtvl.html

[M06] 向标准错误输出
来源：http://dali.daria6918.cn/Article/details/gt2ppwlphhq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2iorhrchc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tanke756.top/Article/details/gt2bwxudzrt.html

JS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gt2idqxactf.html

TS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2skmntjrv.html

Java: System.err.println("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iaksczzv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.guannengcc.top/Article/details/gt2dyifzomi.html

Ruby: warn "err"
来源：http://dali.yj20258888.top/Article/details/gt2wwocyaxu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sufxvd.cn/Article/details/gt2labfsktl.html

[M07] 判断是否为主入口
来源：http://dali.cheryme.top/Article/details/gt2joustlwx.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258888.top/Article/details/gt2oggzceki.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2sswhtliw.html

JS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gt2nvzqivup.html

TS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gt2hpnfturl.html

Java: public static void main(String[] args)
来源：http://dali.aizwys.cn/Article/details/gt2evspcibu.html

Go:   func main()
来源：http://dali.wangdashe.top/Article/details/gt2utosnrvl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yueranfly.top/Article/details/gt2dmvfxkyj.html

C#:   static void Main(string[] args)
来源：http://dali.gogol.net.cn/Article/details/gt2ddemstnb.html

[M08] 获取系统与运行时信息
来源：http://dali.hammf.cn/Article/details/gt2xvppehfm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fengsongda.top/Article/details/gt2zmgwedie.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.havefunace.top/Article/details/gt2ecqnmiti.html

JS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gt2jeiaynry.html

TS:   process.platform;  process.version
来源：http://dali.yj202588.top/Article/details/gt2canycuci.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cdnleiting.top/Article/details/gt2udkuhfws.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sysykeji.top/Article/details/gt2tovjhccz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xvhttxzs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hywenlv.cn/Article/details/gt2pbvdjzpq.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2ejdddftk.html

N. 数据结构与算法
来源：http://dali.yangfankeji.com/Article/details/gt2pjvhqzjz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2seoftjgs.html

[N01] 二分查找（有序数组）
来源：http://dali.gotoacloud.top/Article/details/gt2ptvhywqf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2ycerpirt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj202588.top/Article/details/gt2rsfjirsj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gt2obpuhcyp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gt2zotxycsv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2gstuwzil.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2balmpuvo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cucudq.cn/Article/details/gt2nztxhnzf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2mvcnnyqg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yongpay.top/Article/details/gt2ospqtlsn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gt2gbwmofom.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hysaishi.cn/Article/details/gt2zwhuqfpx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gt2ggbpzndi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gt2ciywzhia.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.9152youxi.cn/Article/details/gt2hayznnuz.html

Go:   slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gt2nmntrpzo.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gt2ludvznhk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yonumen.top/Article/details/gt2khoswanf.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jphizraz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nwbrower.top/Article/details/gt2eouuuuki.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhixingplan.top/Article/details/gt2mdtkebru.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gt2zatjqpyv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gt2jeujsuvk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kminwlse.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258888.top/Article/details/gt2epyxwffz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yongpay.top/Article/details/gt2trgegygk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uquipzeh.html

[N04] 斐波那契数列
来源：http://dali.feifeiyinyue.top/Article/details/gt2ghgppzhn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2yqwpsweg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ivvv.top/Article/details/gt2ywsqfmmh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gt2nggbriov.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gt2fzcedgct.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gt2wyhiernq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxinkj.top/Article/details/gt2cmrjljiv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eoifvvzv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sweek.top/Article/details/gt2ohhmbtua.html

[N05] 最大公约数
来源：http://dali.fengsongda.top/Article/details/gt2mszqwjem.html

Py:   math.gcd(a, b)
来源：http://dali.havefunace.top/Article/details/gt2oauqjfba.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dianchejie.cn/Article/details/gt2hwyugsmn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gt2ukzozwgo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gt2peeefzxg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuetiantiany.cn/Article/details/gt2ovizdcpg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tian-w.cn/Article/details/gt2wezyiute.html

Ruby: a.gcd(b)
来源：http://dali.yj20258.top/Article/details/gt2xjsftlzf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.pycfn.com/Article/details/gt2chfdhxpc.html

[N06] 判断回文字符串
来源：http://dali.0kj1m.cn/Article/details/gt2ftghvhjh.html

Py:   s == s[::-1]
来源：http://dali.ppjwa.cn/Article/details/gt2kpkovtut.html

PHP:  $s === strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gt2cxbvzvgb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gt2mgrcetqq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gt2qubjeouo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xylfe.cn/Article/details/gt2wrqnkqsl.html

Go:   // 双指针从两端比较
来源：http://dali.9152youxi.cn/Article/details/gt2emmkyajn.html


<!-- 参考信息 -->