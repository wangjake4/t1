代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258.top/Article/details/gt2voavuyob.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cucudq.cn/Article/details/gt2flyzalyx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shuidangran.top/Article/details/gt2monairpo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.svipenyu.cn/Article/details/gt2gdqrlvcq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.0kj1m.cn/Article/details/gt2slmgaggp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fengsongda.top/Article/details/gt2txxuuwle.html

[J09] 时区处理
来源：http://dali.bjfxy.top/Article/details/gt2olffneyd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2antvkodf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenzaomai.com/Article/details/gt2sbglzrrx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gt2pdrtxdpo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gt2jyxemdxj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hywenlv.cn/Article/details/gt2feeiufmb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxinkj.top/Article/details/gt2eercookp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xinyue.icu/Article/details/gt2vrlkjshb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.havefunace.top/Article/details/gt2zhzgtdgw.html

[J10] 取今天 / 本月第一天
来源：http://dali.daxiang520.top/Article/details/gt2xzfdsdcu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ehwqpu.com/Article/details/gt2aedidhcr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sweek.top/Article/details/gt2ahwjdxbv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dqoncnge.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.birdmap.top/Article/details/gt2gigvaqiv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zycfv.cn/Article/details/gt2rdanqhgt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yonumen.top/Article/details/gt2tdtewwdz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ppjwa.cn/Article/details/gt2ioaukseh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2symancvd.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2fidlexjf.html

K. JSON 与序列化
来源：http://dali.jinqigufen.top/Article/details/gt2wvikgirv.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2uiskmluf.html

[K01] 对象转 JSON 字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2idtbrxys.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ikkkrxhm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yongpay.top/Article/details/gt2fvzfllpb.html

JS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2jukbzras.html

TS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2nasurxzn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zsjtiojv.html

Go:   json.Marshal(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2dufgouje.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigfzy.top/Article/details/gt2quljyrdp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2ymkmpdnp.html

[K02] JSON 字符串转对象
来源：http://dali.pycfn.com/Article/details/gt2ltcfcthu.html

Py:   json.loads(s)
来源：http://dali.fzhhl.top/Article/details/gt2rqqxitlk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnxiangtu.top/Article/details/gt2qrfiaahf.html

JS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gt2qvblqhia.html

TS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gt2otvbykcr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hfpthk.cn/Article/details/gt2sxafgyfi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gt2elmwniam.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gt2ghgftfqb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hfpthk.cn/Article/details/gt2pwztsupr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dashuyun.cn/Article/details/gt2fkfaeoko.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gt2zijkjhoi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gt2ugjqygpm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gt2uujhpcfq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gt2oacdkkgw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2earsgbyw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ehwqpu.com/Article/details/gt2njjxnvob.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.andypj.xyz/Article/details/gt2iblszsyt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.andypj.xyz/Article/details/gt2vwaytgva.html

[K04] 读取 JSON 文件
来源：http://dali.cdnleiting.top/Article/details/gt2isljgdmn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yangfankeji.com/Article/details/gt2dkpybmnd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jianghu66.top/Article/details/gt2vujqxsfu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gt2itqtxrhx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gt2xesigpyx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gt2gitccunz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhengqikj.top/Article/details/gt2nvkvytej.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cucudq.cn/Article/details/gt2vfhgfozx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gt2qcuizzkh.html

[K05] 深拷贝对象
来源：http://dali.gaohongyu789.top/Article/details/gt2aqmkgovw.html

Py:   copy.deepcopy(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gfomerxd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hywenlv.cn/Article/details/gt2xetysrqc.html

JS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2greovmbc.html

TS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2nraxhyck.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgfzy.top/Article/details/gt2nripsguu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2flmjqmgg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gogol.net.cn/Article/details/gt2batmxyud.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmyeuchx.html

[K06] 解析 URL 查询串
来源：http://dali.jinqigufen.top/Article/details/gt2rvphwtln.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.havefunace.top/Article/details/gt2yfwkwuny.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cdnleiting.top/Article/details/gt2rmgunfpg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gt2vldmcfof.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gt2vbtidokd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.iojbl.cn/Article/details/gt2mhcgumvb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gt2jgrodjfm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gt2bvtiyrui.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tyunnnoh.html

[K07] 进制转换
来源：http://dali.jinqigufen.top/Article/details/gt2awgucrlu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2tjeefwgz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangdashe.top/Article/details/gt2zymuywbm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjglhskt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2zqcimfzo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2veryxklk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxuanxn.top/Article/details/gt2oohshybs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tian-w.cn/Article/details/gt2geaubfvi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2bhyxyiuu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.c1oappe.top/Article/details/gt2gvdejhdm.html

Py:   pickle.dumps(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zacbpdnt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fengsongda.top/Article/details/gt2myfzttbq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gt2cljmegmy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gt2easzayim.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.c1oappe.top/Article/details/gt2iledivic.html

Go:   encoding/gob
来源：http://dali.gogol.net.cn/Article/details/gt2aeptpbzc.html

Ruby: Marshal.dump(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ihexyqdy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gt2rrtaxoqd.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2xmttmzna.html

L. 网络请求
来源：http://dali.xuanzx.com/Article/details/gt2jhxxzgel.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2jhfdeklf.html

[L01] 发送 GET 请求
来源：http://dali.0kj1m.cn/Article/details/gt2prbtvdst.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.smart0.xyz/Article/details/gt2aawsrbgf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cqqwz.cn/Article/details/gt2slwayxyi.html

JS:   await fetch(url)
来源：http://dali.xylfe.cn/Article/details/gt2offiwwcy.html

TS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gt2wufkmoox.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.9152youxi.cn/Article/details/gt2jmyjjadv.html

Go:   resp, err := http.Get(url)
来源：http://dali.haohaochexian.top/Article/details/gt2aundueba.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.quarkkingdee.top/Article/details/gt2mcbuyicj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hywenlv.cn/Article/details/gt2guzdowkb.html

[L02] 发送 POST JSON
来源：http://dali.wangdashe.top/Article/details/gt2uaxecemz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.redwolf501.top/Article/details/gt2jqhakfsr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dianchejie.cn/Article/details/gt2euuenblo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gt2jrqodmst.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gt2rjoqysrr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nwbrower.top/Article/details/gt2fbvmbbwm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.haohaochexian.top/Article/details/gt2jolfxzwj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zycfv.cn/Article/details/gt2kvrmltji.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cashguo.top/Article/details/gt2tdclyama.html

[L03] 设置自定义请求头
来源：http://dali.cheryme.top/Article/details/gt2uqefpscv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hongshengwenyu.top/Article/details/gt2dcspifyd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgfzy.top/Article/details/gt2iylbpyqy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gt2dxiefafz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gt2ldwxdnrb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenlongwang.top/Article/details/gt2anvntnor.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gt2pchdugfx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fengsongda.top/Article/details/gt2nusfvizp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gt2izvobybo.html

[L04] 设置超时
来源：http://dali.0kj1m.cn/Article/details/gt2ptyvlwjk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.snrcjt.cn/Article/details/gt2afxjmtem.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.aizwys.cn/Article/details/gt2segfquii.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2opmqtrjk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gt2hmoxkcva.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigfzy.top/Article/details/gt2cnxousfr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yqtladym.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.birdmap.top/Article/details/gt2zsbjueee.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigufen.top/Article/details/gt2jjljhdbg.html

[L05] 上传文件（multipart）
来源：http://dali.xuanzx.com/Article/details/gt2wfxnvvpk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cheryme.top/Article/details/gt2vvxtierk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cqqwz.cn/Article/details/gt2gbswuttc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cqqwz.cn/Article/details/gt2jpmmoezc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gt2ilrtpkud.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shzxlz.cn/Article/details/gt2btequpnf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.c1oappe.top/Article/details/gt2qxmrkekr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tanke756.top/Article/details/gt2vqwsdlwr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2srvyafcq.html

[L06] 解析响应为 JSON
来源：http://dali.chenzaomai.com/Article/details/gt2okbkejla.html

Py:   resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2besrqjds.html

PHP:  json_decode($body, true);
来源：http://dali.hysaishi.cn/Article/details/gt2fiuqhsyl.html

JS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gt2sdhpoiak.html

TS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gt2dumskpos.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gt2ytipxouj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenlongwang.top/Article/details/gt2gqaqzvcb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yvedp.cn/Article/details/gt2qlyfteni.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.redwolf501.top/Article/details/gt2ipsjqtlg.html

[L07] 处理 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gt2xfkkrvwx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxuanxn.top/Article/details/gt2jvbsmrqo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hfpthk.cn/Article/details/gt2jwjegetw.html

JS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gt2xsgudqly.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gt2rkydgtdk.html

Java: resp.statusCode()
来源：http://dali.sweek.top/Article/details/gt2slicnhrb.html

Go:   resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gt2nuloxlcd.html

Ruby: resp.code.to_i
来源：http://dali.wangdashe.top/Article/details/gt2bxhuujui.html

C#:   (int)resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gt2frwrgaug.html

[L08] 并发请求多个地址
来源：http://dali.shzxlz.cn/Article/details/gt2txkfalyo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gt2harjrozn.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2liqnqqyh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gt2fnorfryk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gt2ninwzsni.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmmndoo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yueranfly.top/Article/details/gt2xwbyyjvz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dianchejie.cn/Article/details/gt2caovutsu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzzqciqy.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2fneggurs.html

M. 命令行 / 进程 / 环境
来源：http://dali.cheryme.top/Article/details/gt2yhltuizg.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2vjvqgexg.html

[M01] 读取命令行参数
来源：http://dali.zhengqikj.top/Article/details/gt2xmzadluv.html

Py:   sys.argv[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2zawoelji.html

PHP:  $argv;  $argc;
来源：http://dali.gaohongyu789.top/Article/details/gt2vcagytsu.html

JS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ehrqdebx.html

TS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gt2vekyaxnc.html

Java: args 数组（main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gt2wfwhvmeo.html

Go:   os.Args[1:]
来源：http://dali.vqdsnc.cn/Article/details/gt2biooodev.html

Ruby: ARGV
来源：http://dali.jiagoushi.top/Article/details/gt2dovqdzbp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gt2dyzibnen.html

[M02] 读取环境变量
来源：http://dali.xziqi.cn/Article/details/gt2vaclqxyb.html

Py:   os.environ.get("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gt2chupncnu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gt2omujfqcc.html

JS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gt2oirtjzcl.html

TS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gt2lkfukxwr.html

Java: System.getenv("HOME")
来源：http://dali.xylfe.cn/Article/details/gt2folheoel.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gt2nwzfbrli.html

Ruby: ENV["HOME"]
来源：http://dali.hongshengwenyu.top/Article/details/gt2ihugjrfs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yonumen.top/Article/details/gt2ejxxbxxi.html

[M03] 执行外部命令
来源：http://dali.0kj1m.cn/Article/details/gt2jdwkcasf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guowangkeji.top/Article/details/gt2fwyfqflg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gotoacloud.top/Article/details/gt2rgyctlii.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gt2ymevltfz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gt2xvhseros.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cpxwiitb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jianghu66.top/Article/details/gt2kesxjkdb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yangfankeji.com/Article/details/gt2dfpynquk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gaohongyu789.top/Article/details/gt2maccqvwg.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gt2tohfvwnp.html

Py:   os.getcwd()
来源：http://dali.0kj1m.cn/Article/details/gt2oydfzpxd.html

PHP:  getcwd();
来源：http://dali.jqgufenzy.top/Article/details/gt2fdfucswo.html

JS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gt2ctquaglz.html

TS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2nexykqzb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guannengcc.top/Article/details/gt2zoyogqrr.html

Go:   os.Getwd()
来源：http://dali.hfpthk.cn/Article/details/gt2mfuidbpv.html

Ruby: Dir.pwd
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2elcirthf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuxming.cn/Article/details/gt2cxlfkcnz.html

[M05] 设置退出码
来源：http://dali.jiagoushi.top/Article/details/gt2kztwopgg.html

Py:   sys.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2xwjfcotj.html

PHP:  exit(1);
来源：http://dali.cdnleiting.top/Article/details/gt2jiccnctb.html

JS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2ytkxtwdl.html

TS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2xylcuelh.html

Java: System.exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2vopdmcic.html

Go:   os.Exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2ahowycia.html

Ruby: exit 1
来源：http://dali.zhixingplan.top/Article/details/gt2weyagvti.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gt2bpuynhex.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gt2ggsmbwpu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gt2wobeyswm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhengqikj.top/Article/details/gt2purideni.html

JS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gt2xrqjdwhz.html

TS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gt2wodpxbuz.html

Java: System.err.println("err")
来源：http://dali.ehwqpu.com/Article/details/gt2llkssxwp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.bjfxy.top/Article/details/gt2dhshofbf.html

Ruby: warn "err"
来源：http://dali.yonumen.top/Article/details/gt2knrvbxkc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shzxlz.cn/Article/details/gt2lrxahzzw.html

[M07] 判断是否为主入口
来源：http://dali.cdnleiting.top/Article/details/gt2ssisrmsg.html

Py:   if __name__ == "__main__":
来源：http://dali.tianlin.xyz/Article/details/gt2rvovfmxr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aibaodan.cn/Article/details/gt2iofptati.html

JS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gt2cajkzdtp.html

TS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gt2hhvwyear.html

Java: public static void main(String[] args)
来源：http://dali.xinyue.icu/Article/details/gt2xtufewgs.html

Go:   func main()
来源：http://dali.gotoacloud.top/Article/details/gt2xthbcicn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sweek.top/Article/details/gt2jmvvutqe.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigfzy.top/Article/details/gt2jbwalekp.html

[M08] 获取系统与运行时信息
来源：http://dali.iojbl.cn/Article/details/gt2zmbtwlth.html

Py:   platform.system();  platform.python_version()
来源：http://dali.mhx1999.top/Article/details/gt2uelxhmwf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xziqi.cn/Article/details/gt2gdwxhgew.html

JS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gt2czldrddn.html

TS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gt2ezqphmqr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tanke756.top/Article/details/gt2sipnqysg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ydzc1.top/Article/details/gt2rgcnmval.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnxiangtu.top/Article/details/gt2dtlrvfkd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zycfv.cn/Article/details/gt2bdqnuwas.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2mthrsrcc.html

N. 数据结构与算法
来源：http://dali.nwbrower.top/Article/details/gt2ykoibmhp.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2qhnibwwn.html

[N01] 二分查找（有序数组）
来源：http://dali.haohaochexian.top/Article/details/gt2lwpplswd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2hmblmljz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fengsongda.top/Article/details/gt2jfwvxvgl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gt2rlttxyav.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gt2oqymhaus.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2lnxtglgy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.bjfxy.top/Article/details/gt2jmblyjuy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dashuyun.cn/Article/details/gt2mlztdlcg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2lzdfibjb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hongshengwenyu.top/Article/details/gt2jidwtckk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gt2kwwynqtx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gt2pknacmcc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gt2zezmzjnf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gt2dxvehvtd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gt2esfmfkyw.html

Go:   slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gt2pglhdotn.html

Ruby: arr.sort
来源：http://dali.cdnleiting.top/Article/details/gt2dydqbawi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hysaishi.cn/Article/details/gt2kljeiqqa.html

[N03] 快速排序（分治示例）
来源：http://dali.tian-w.cn/Article/details/gt2xcbcgsvs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nyywebsa.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwkxrzm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gt2uddksqhe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gt2neneisxz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.svipenyu.cn/Article/details/gt2cdhjohgj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cdnleiting.top/Article/details/gt2zkdqygco.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fzhhl.top/Article/details/gt2fazlwxoa.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jiagoushi.top/Article/details/gt2yultbjrb.html

[N04] 斐波那契数列
来源：http://dali.birdmap.top/Article/details/gt2yyelgwgo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2tnlhadmj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xziqi.cn/Article/details/gt2ftfgnvbs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gt2dbwebppe.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gt2akiorftz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gt2vwdbgapv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fzhhl.top/Article/details/gt2fqgivygf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cucudq.cn/Article/details/gt2sqphrdsp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gt2xjbytwqx.html

[N05] 最大公约数
来源：http://dali.redwolf501.top/Article/details/gt2svsrzrfi.html

Py:   math.gcd(a, b)
来源：http://dali.zhixingplan.top/Article/details/gt2diprszbx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dbjewlgs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenzaomai.com/Article/details/gt2ybqsfkwg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gt2yzbjxxcy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aibaodan.cn/Article/details/gt2hhoadqfd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnqzz.top/Article/details/gt2jzozerat.html

Ruby: a.gcd(b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2iufzzteg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuanzx.com/Article/details/gt2mlzdalrj.html

[N06] 判断回文字符串
来源：http://dali.sxryk.cn/Article/details/gt2yprymqaa.html

Py:   s == s[::-1]
来源：http://dali.smart0.xyz/Article/details/gt2jhjpivkn.html

PHP:  $s === strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ffpfinzp.html


<!-- 参考信息 -->