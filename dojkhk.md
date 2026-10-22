代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hongshengwenyu.top/Article/details/gt2dbeyqyjl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gt2cooyegiv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gt2axbrllxt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xziqi.cn/Article/details/gt2jqrctgep.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jlsjyb.cn/Article/details/gt2gwtydyfk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jianghu66.top/Article/details/gt2wqchxwkb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guannengcc.top/Article/details/gt2zykzjpkl.html

[J10] 取今天 / 本月第一天
来源：http://dali.ydzc1.top/Article/details/gt2komyxncm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ybcxt.top/Article/details/gt2jdzxfmny.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.bjfxy.top/Article/details/gt2hjboqucn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxinkj.top/Article/details/gt2smxqrozl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2eymzswap.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sysykeji.top/Article/details/gt2ssvsaghs.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yvedp.cn/Article/details/gt2ksfppotd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gt2sacfsnpg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sxryk.cn/Article/details/gt2xttzsrwj.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2zapbpbwb.html

K. JSON 与序列化
来源：http://dali.tanke756.top/Article/details/gt2llwcbpfv.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2xzmcxbtu.html

[K01] 对象转 JSON 字符串
来源：http://dali.yueranfly.top/Article/details/gt2qcqzwjpd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gt2brwtethp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gt2ujgtkgiy.html

JS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2xjsihhxw.html

TS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2gqahvues.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.svipenyu.cn/Article/details/gt2nulokzbw.html

Go:   json.Marshal(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2trhtfide.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigfzy.top/Article/details/gt2ozmmkudt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yueranfly.top/Article/details/gt2cxzwudlc.html

[K02] JSON 字符串转对象
来源：http://dali.redwolf501.top/Article/details/gt2qjbcuqhc.html

Py:   json.loads(s)
来源：http://dali.jianghu66.top/Article/details/gt2vfwdvhug.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ehwqpu.com/Article/details/gt2wefqgfoh.html

JS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gt2bgfzjvuf.html

TS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gt2mdryhdqb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gt2fiohujww.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bflvbumo.html

Ruby: JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cflmxggi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqbcbgli.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.c1oappe.top/Article/details/gt2fisaezao.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gt2ebzpxhvz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gt2xbkevwwd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gt2vhtrflnr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2wktcrsxw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vjdsxzya.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenzaomai.com/Article/details/gt2uwizbpkx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.iojbl.cn/Article/details/gt2tovvycpe.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj202588.top/Article/details/gt2ysvphlke.html

[K04] 读取 JSON 文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2uecwjlny.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.0kj1m.cn/Article/details/gt2hfasknrg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnxiangtu.top/Article/details/gt2fewwhcmz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gt2yibioxhk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gt2pfseepgr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.mhx1999.top/Article/details/gt2nngvmugp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gt2meqtkfck.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sxryk.cn/Article/details/gt2rqsiezgz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gt2erabwmlh.html

[K05] 深拷贝对象
来源：http://dali.kuanghao11.cn/Article/details/gt2tylgvuuw.html

Py:   copy.deepcopy(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2fkiijlix.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhoulong.xyz/Article/details/gt2yrsfyrrj.html

JS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gt2pxjjbpgu.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mizzbaxs.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sysykeji.top/Article/details/gt2hjmoilll.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.kuanghao11.cn/Article/details/gt2sdhwlimw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ivvv.top/Article/details/gt2hnisvhxa.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jyoumei.cn/Article/details/gt2gwxnbsxq.html

[K06] 解析 URL 查询串
来源：http://dali.zhongyouzk.top/Article/details/gt2nzqkplcf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vrtaftry.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pbnxqgeg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gt2dokitpdc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gt2xvlwoaac.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.meibo888.top/Article/details/gt2fkiycgcu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gt2rncokjov.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gt2ejbbngug.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gt2htpqdmpj.html

[K07] 进制转换
来源：http://dali.haohaochexian.top/Article/details/gt2zgshxzhw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gt2ykbsohac.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuanzx.com/Article/details/gt2jqmbdxfh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2fmfnebfr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gt2ctjjsfym.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2fxjfzbix.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zdqjudy.top/Article/details/gt2twkuogwz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cheryme.top/Article/details/gt2niytjegy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2xglaabil.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yonumen.top/Article/details/gt2nitithvo.html

Py:   pickle.dumps(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2lpwifnus.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xjkgfqbu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gt2gixofjig.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gt2eqmjhqog.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ydzc1.top/Article/details/gt2ftenjzup.html

Go:   encoding/gob
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwmwdkuz.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lstcakvo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gt2qgjcrnxh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2ygiccdoi.html

L. 网络请求
来源：http://dali.yuanzhike.top/Article/details/gt2tpuxkoff.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mcxnopws.html

[L01] 发送 GET 请求
来源：http://dali.hywenlv.cn/Article/details/gt2tgnjghwm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gotoacloud.top/Article/details/gt2cijibbet.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.andypj.xyz/Article/details/gt2ndxxmdwi.html

JS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wutukjpj.html

TS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rurwcadp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.bjfxy.top/Article/details/gt2wlgmbffk.html

Go:   resp, err := http.Get(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2chjzrzpt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigufen.top/Article/details/gt2ubylytde.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ckmglvwm.html

[L02] 发送 POST JSON
来源：http://dali.zycfv.cn/Article/details/gt2nqpbewea.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhoulong.xyz/Article/details/gt2ybgrekcg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tian-w.cn/Article/details/gt2blgzlbtk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jianghu66.top/Article/details/gt2ndjhswuc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gt2lypbkgxy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.mhx1999.top/Article/details/gt2zbdbujny.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangdashe.top/Article/details/gt2zkzupvzt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhixingplan.top/Article/details/gt2wxtcqtut.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yvedp.cn/Article/details/gt2ysrfrond.html

[L03] 设置自定义请求头
来源：http://dali.fzhhl.top/Article/details/gt2onogmohq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.andypj.xyz/Article/details/gt2ufwxfwig.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.mhx1999.top/Article/details/gt2ljgloaan.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xziqi.cn/Article/details/gt2kginswvk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gt2wotsfjis.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.316326.xyz/Article/details/gt2nnrwbsuk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gt2qxbmwfgw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.0kj1m.cn/Article/details/gt2lbqypgrx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gt2qxmumyfb.html

[L04] 设置超时
来源：http://dali.gotoacloud.top/Article/details/gt2nlwemmmd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinqigfzy.top/Article/details/gt2vjibusvk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zycfv.cn/Article/details/gt2fozsidys.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gt2wyfrrzjl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gt2tlehwogv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xinyue.icu/Article/details/gt2xegyakbx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhiwuduotai.top/Article/details/gt2eptousms.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xinyue.icu/Article/details/gt2jykhhzdo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gt2nvwpfobm.html

[L05] 上传文件（multipart）
来源：http://dali.mhx1999.top/Article/details/gt2lzhalarj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.feifeiyinyue.top/Article/details/gt2kjsdmdio.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cqqwz.cn/Article/details/gt2xngouhww.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gt2allswuru.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ubfbwkcf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jlsjyb.cn/Article/details/gt2hzszvxiy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jyoumei.cn/Article/details/gt2gxfkxnnl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aibaodan.cn/Article/details/gt2vjqodldx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2vddiazpd.html

[L06] 解析响应为 JSON
来源：http://dali.shzxlz.cn/Article/details/gt2pqqheomi.html

Py:   resp.json()
来源：http://dali.sxryk.cn/Article/details/gt2fjbxfhdj.html

PHP:  json_decode($body, true);
来源：http://dali.shzxlz.cn/Article/details/gt2ypbkrrbm.html

JS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gt2jutegwsj.html

TS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gt2zsqmyhkm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tanke756.top/Article/details/gt2ykobybcz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sufxvd.cn/Article/details/gt2rtwuffzs.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jyoumei.cn/Article/details/gt2epodjlfu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gt2dnqmqhog.html

[L07] 处理 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gt2gplxzcrz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.quarkkingdee.top/Article/details/gt2wbtukykr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.aizwys.cn/Article/details/gt2xqhczyvb.html

JS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gt2iiesjroa.html

TS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gt2atvgalym.html

Java: resp.statusCode()
来源：http://dali.nwbrower.top/Article/details/gt2bujapzql.html

Go:   resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gt2qoktrtsk.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bqiiwdyj.html

C#:   (int)resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gt2nmxclzrm.html

[L08] 并发请求多个地址
来源：http://dali.snrcjt.cn/Article/details/gt2razdczma.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangdashe.top/Article/details/gt2mmlpxzgu.html

PHP:  curl_multi_init() 系列
来源：http://dali.c1oappe.top/Article/details/gt2atboosfi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gt2rpuwjszf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gt2wgbhtocj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dashuyun.cn/Article/details/gt2ufqrektq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.quarkkingdee.top/Article/details/gt2gfzhddkp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gt2qiewxbsy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jiagoushi.top/Article/details/gt2cyegnaby.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2pkcpmygc.html

M. 命令行 / 进程 / 环境
来源：http://dali.yanxiufei.cn/Article/details/gt2zneeydsc.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2mqklwlbq.html

[M01] 读取命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2glqobwkv.html

Py:   sys.argv[1:]
来源：http://dali.daria6918.cn/Article/details/gt2onzueimb.html

PHP:  $argv;  $argc;
来源：http://dali.pengpengdd.cyou/Article/details/gt2mvdjltxv.html

JS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gt2tuvlvdge.html

TS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gt2acgejwqa.html

Java: args 数组（main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gt2mxttrkei.html

Go:   os.Args[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gpkzynog.html

Ruby: ARGV
来源：http://dali.quarkkingdee.top/Article/details/gt2aqsgezpk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gt2yebgntgd.html

[M02] 读取环境变量
来源：http://dali.shuidangran.top/Article/details/gt2glsqkjkw.html

Py:   os.environ.get("HOME")
来源：http://dali.iojbl.cn/Article/details/gt2osryaopf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gt2vflhvbbq.html

JS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gt2lxpbiufy.html

TS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gt2unosefho.html

Java: System.getenv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gt2ussandzb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gt2vneyyahl.html

Ruby: ENV["HOME"]
来源：http://dali.iojbl.cn/Article/details/gt2iknsftst.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yangfankeji.com/Article/details/gt2yoyzylgk.html

[M03] 执行外部命令
来源：http://dali.fengsongda.top/Article/details/gt2jlqmgdql.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tanke756.top/Article/details/gt2xvfzvvsg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhixingplan.top/Article/details/gt2vommzuni.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oidyxmnh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gt2feqzcins.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cashguo.top/Article/details/gt2bkosqvya.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.quarkkingdee.top/Article/details/gt2rodlfhmm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xziqi.cn/Article/details/gt2petynzar.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jiagoushi.top/Article/details/gt2ylxppbsu.html

[M04] 获取当前工作目录
来源：http://dali.tian-w.cn/Article/details/gt2pckjtgze.html

Py:   os.getcwd()
来源：http://dali.hnxiangtu.top/Article/details/gt2dgsltwmd.html

PHP:  getcwd();
来源：http://dali.aibaodan.cn/Article/details/gt2kawjizzl.html

JS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gt2zjkiuupm.html

TS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gt2iixpllkk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aibaodan.cn/Article/details/gt2oivhteax.html

Go:   os.Getwd()
来源：http://dali.hysaishi.cn/Article/details/gt2degbunqj.html

Ruby: Dir.pwd
来源：http://dali.bjfxy.top/Article/details/gt2dhemofqd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.iojbl.cn/Article/details/gt2tvoffcxs.html

[M05] 设置退出码
来源：http://dali.sweek.top/Article/details/gt2ivqrbvhg.html

Py:   sys.exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2xdntkdpu.html

PHP:  exit(1);
来源：http://dali.hammf.cn/Article/details/gt2fugvaxtj.html

JS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2hovyhwdf.html

TS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2wvwjtgpu.html

Java: System.exit(1)
来源：http://dali.hammf.cn/Article/details/gt2qcqmjwwk.html

Go:   os.Exit(1)
来源：http://dali.yonumen.top/Article/details/gt2yuxrttsq.html

Ruby: exit 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wupsxhtt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.bjfxy.top/Article/details/gt2pygxrqgx.html

[M06] 向标准错误输出
来源：http://dali.hfpthk.cn/Article/details/gt2qsgqehuw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.vqdsnc.cn/Article/details/gt2ypbrleil.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gaohongyu789.top/Article/details/gt2uuzjoahq.html

JS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2eftebtlx.html

TS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gt2chzopaix.html

Java: System.err.println("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2moszmpxp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jianghu66.top/Article/details/gt2ukepmxzz.html

Ruby: warn "err"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yukhuyqx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuanzx.com/Article/details/gt2zfrdoqbb.html

[M07] 判断是否为主入口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2intyamfu.html

Py:   if __name__ == "__main__":
来源：http://dali.zdqjudy.top/Article/details/gt2hqfbvotg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.bjfxy.top/Article/details/gt2bgwvytko.html

JS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gt2mahjlxov.html

TS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gt2krywgxyk.html

Java: public static void main(String[] args)
来源：http://dali.yj20258.top/Article/details/gt2rdyjvlzh.html

Go:   func main()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wzorwpdq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.redwolf501.top/Article/details/gt2dirdswym.html

C#:   static void Main(string[] args)
来源：http://dali.birdmap.top/Article/details/gt2bhekqxxd.html

[M08] 获取系统与运行时信息
来源：http://dali.wangshuangyany.cn/Article/details/gt2lpzsarll.html

Py:   platform.system();  platform.python_version()
来源：http://dali.meibo888.top/Article/details/gt2wcbetaqc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fjrncyeg.html

JS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gt2wyvprtqz.html

TS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gt2bqiaefji.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhengqikj.top/Article/details/gt2njgntjed.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenzaomai.com/Article/details/gt2yrvcwcqb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shuidangran.top/Article/details/gt2oeevdlkp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cheryme.top/Article/details/gt2ehyccxke.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2iripjwza.html

N. 数据结构与算法
来源：http://dali.zhengqikj.top/Article/details/gt2icbyjciw.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2bwyvwlis.html

[N01] 二分查找（有序数组）
来源：http://dali.sweek.top/Article/details/gt2nmwbvpdn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2dkvkgsxa.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ydzc1.top/Article/details/gt2ggmgfzmk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gt2kjolabbi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gt2vqhzxdjc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2pqgyremr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2tispqokt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.haohaochexian.top/Article/details/gt2wfoysxfp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2cubowhsc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.kuanghao11.cn/Article/details/gt2bwnyzpea.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gt2uzljixmv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xylfe.cn/Article/details/gt2bvdzrklf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gt2fvkofxme.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gt2sojryleb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zyddrfbf.html

Go:   slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gt2imyghzul.html

Ruby: arr.sort
来源：http://dali.sweek.top/Article/details/gt2xafnrcrb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.bjfxy.top/Article/details/gt2crspyzku.html

[N03] 快速排序（分治示例）
来源：http://dali.zhixingplan.top/Article/details/gt2punuqaqy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guowangkeji.top/Article/details/gt2camjksbk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.vqdsnc.cn/Article/details/gt2jzktvviw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gt2wkqbdyrt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shzxlz.cn/Article/details/gt2ybvynqtf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.feifeiyinyue.top/Article/details/gt2fyauqqbq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xinyue.icu/Article/details/gt2tekpctuk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdsxrcez.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cqqwz.cn/Article/details/gt2bqkhmsar.html

[N04] 斐波那契数列
来源：http://dali.tanke756.top/Article/details/gt2hqecbglj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnsozkg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gt2yrtluods.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gt2gzpkhqso.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gt2noyweffg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.redwolf501.top/Article/details/gt2dfzuyyxa.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.birdmap.top/Article/details/gt2hruhwvtq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gt2bwvpqudu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2rpxzqmwr.html

[N05] 最大公约数
来源：http://dali.havefunace.top/Article/details/gt2pqmnbnbi.html

Py:   math.gcd(a, b)
来源：http://dali.bjfxy.top/Article/details/gt2knyazrpu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iacaijei.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.bjfxy.top/Article/details/gt2vplhdwoj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gt2hbsyixbg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ppjwa.cn/Article/details/gt2qikohwve.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigfzy.top/Article/details/gt2xhnvlttv.html

Ruby: a.gcd(b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rjsdbjzb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.havefunace.top/Article/details/gt2oednkuep.html

[N06] 判断回文字符串
来源：http://dali.tian-w.cn/Article/details/gt2jyonezsk.html

Py:   s == s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gt2wedntgnl.html

PHP:  $s === strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gt2ahgfxyul.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gt2jhekvfqy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gt2qzbyqwxq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sufxvd.cn/Article/details/gt2vqbrrcdx.html

Go:   // 双指针从两端比较
来源：http://dali.hfpthk.cn/Article/details/gt2lgqpgyes.html

Ruby: s == s.reverse
来源：http://dali.hywenlv.cn/Article/details/gt2bgamrmis.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gt2rqpivvwx.html

[N07] 两数之和（返回下标）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmxqtcvy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shzxlz.cn/Article/details/gt2iekjrfzd.html


<!-- 参考信息 -->