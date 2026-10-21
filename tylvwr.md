代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenjidiqi.icu/Article/details/gtpljaoutr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangshuangyany.cn/Article/details/gtndqimuwi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shzxlz.cn/Article/details/gtbyvurnxe.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuanzhike.top/Article/details/gtroyzicvw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guowangkeji.top/Article/details/gtcvyepgcq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.smart0.xyz/Article/details/gtyplbmumv.html

[J09] 时区处理
来源：http://dali.jiagoushi.top/Article/details/gtoskpeugc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gtuvuzxhfr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aibaodan.cn/Article/details/gtsfgfozgj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gttzgfksuq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtjqitvqst.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ivvv.top/Article/details/gtqbsmrjlu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.haohaochexian.top/Article/details/gtuqtbzect.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrogqkeg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cashguo.top/Article/details/gttrwbonfd.html

[J10] 取今天 / 本月第一天
来源：http://dali.kuanghao11.cn/Article/details/gtqzoqjnph.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxscmyhlw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cucudq.cn/Article/details/gtezvddehv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ybcxt.top/Article/details/gtkxvfnpwy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.0kj1m.cn/Article/details/gtsofpufox.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gtwnkouypw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.bjfxy.top/Article/details/gtfpychpsc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tian-w.cn/Article/details/gttocbwgiw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtedfczjpa.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtnslkupuf.html

K. JSON 与序列化
来源：http://dali.sxryk.cn/Article/details/gtmrzyncdt.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtqjryfveq.html

[K01] 对象转 JSON 字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtqceruqjh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gtcshzybha.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gtesolwxtw.html

JS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gtaycyquwd.html

TS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gtscuaotwk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ydzc1.top/Article/details/gtffkirjtp.html

Go:   json.Marshal(obj)
来源：http://dali.gogol.net.cn/Article/details/gtxeztxhnf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhengqikj.top/Article/details/gtsqxrmyhc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtnlnntzbw.html

[K02] JSON 字符串转对象
来源：http://dali.zhongyouzk.top/Article/details/gtofhcrriw.html

Py:   json.loads(s)
来源：http://dali.zhixingplan.top/Article/details/gtjdpkxfat.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fzhhl.top/Article/details/gtfwommzym.html

JS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtidqqqcuo.html

TS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gthjmlicul.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gttzugdbxq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwojrpqao.html

Ruby: JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtsjqmrbgo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnqzz.top/Article/details/gtqhrbxvfu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gogol.net.cn/Article/details/gthmkcabjf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gtccmlkuir.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gthfrzcftu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtmsekwxfh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gtiewtvdkp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gzhubu.top/Article/details/gtzgtzlwoy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.quarkkingdee.top/Article/details/gtyywofmky.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsaoaaqsd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cashguo.top/Article/details/gtuuhvkuui.html

[K04] 读取 JSON 文件
来源：http://dali.hammf.cn/Article/details/gtupytqfae.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hysaishi.cn/Article/details/gtykbyxlys.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhiwuduotai.top/Article/details/gtbabvrsky.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjrbdytz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gtgciptsra.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtsqqdvixd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gtyulbpojc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gtzojrhskn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jianghu66.top/Article/details/gtlcrbhykk.html

[K05] 深拷贝对象
来源：http://dali.chenlongwang.top/Article/details/gthtwewekj.html

Py:   copy.deepcopy(obj)
来源：http://dali.nwbrower.top/Article/details/gtwimyjuqp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.c1oappe.top/Article/details/gtytuoetht.html

JS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtzwzkrnjd.html

TS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtrnjqsabk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gteiuwxlfs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.meibo888.top/Article/details/gtpmlzkzhc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhongyouzk.top/Article/details/gtetncujts.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yuxming.cn/Article/details/gtpdisskbf.html

[K06] 解析 URL 查询串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcernduo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnqzz.top/Article/details/gtgenofpdc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258888.top/Article/details/gtsqrsbmpm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gtjrgtphpw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gtrzbkeacz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhongyouzk.top/Article/details/gtsxjitoli.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdcqqmcn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtxdpdddfr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gttuivomht.html

[K07] 进制转换
来源：http://dali.svipenyu.cn/Article/details/gtdxwvhvhh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtwvdehbwf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.bjfxy.top/Article/details/gtptdgtrdx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtsndfvlej.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtbblckyhq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtqujrpmoc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj202588.top/Article/details/gtklxkrgan.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhengqikj.top/Article/details/gtxcxxdcad.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtcadsaxui.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zycfv.cn/Article/details/gtntadthbx.html

Py:   pickle.dumps(obj)
来源：http://dali.cashguo.top/Article/details/gtjbwnzysz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhoulong.xyz/Article/details/gtfrttwlvr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgkxxtix.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gtcxroijaa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yanxiufei.cn/Article/details/gtpipmkjlc.html

Go:   encoding/gob
来源：http://dali.9152youxi.cn/Article/details/gtwbqctzxx.html

Ruby: Marshal.dump(obj)
来源：http://dali.andypj.xyz/Article/details/gtletkuopr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gtqzbroxgr.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqevobpjn.html

L. 网络请求
来源：http://dali.tianlin.xyz/Article/details/gttneodwzz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtynfmhhvf.html

[L01] 发送 GET 请求
来源：http://dali.ydzc1.top/Article/details/gtlpnyqaii.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangkeji.top/Article/details/gtersbgstt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jianghu66.top/Article/details/gttnsmuhdl.html

JS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gtpvboevlo.html

TS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gtzspweank.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guannengcc.top/Article/details/gtwyeyrfbs.html

Go:   resp, err := http.Get(url)
来源：http://dali.cqqwz.cn/Article/details/gthltoslxh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zdqjudy.top/Article/details/gtmpicyheb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fengsongda.top/Article/details/gtuiictfkm.html

[L02] 发送 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gtgrvkgnci.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gtpfwxwqhi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tianlin.xyz/Article/details/gthonadrsq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gtlnxbpuwj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gtvoylwkxz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ydzc1.top/Article/details/gtybeishxa.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangdashe.top/Article/details/gtpyjjwygz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jianghu66.top/Article/details/gtnnursjls.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.redwolf501.top/Article/details/gtmgnrmanv.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gtxdlemjac.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sxryk.cn/Article/details/gtmugnerfm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.redwolf501.top/Article/details/gtrerphqfi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gtrhptdixm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gtpopvpovx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinqigufen.top/Article/details/gtpwychaei.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gtmzcnvuhr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jiagoushi.top/Article/details/gthudtlsed.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyiungep.html

[L04] 设置超时
来源：http://dali.c1oappe.top/Article/details/gtiykuhmkc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hysaishi.cn/Article/details/gtrcjzidhe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gaohongyu789.top/Article/details/gtcrbznlua.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gtfyaedczd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gtyeasbcpu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgfzy.top/Article/details/gthrmmjxxz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guowangkeji.top/Article/details/gtxbgcyzuv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sweek.top/Article/details/gtbrikarom.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aibaodan.cn/Article/details/gteyxgpmrj.html

[L05] 上传文件（multipart）
来源：http://dali.gogol.net.cn/Article/details/gtzyhvuoxc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxuanxn.top/Article/details/gtuycugcif.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yueranfly.top/Article/details/gtckzvyary.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gtwdqdzsnp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gtwuwzpdkg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.birdmap.top/Article/details/gtitphebpo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cqqwz.cn/Article/details/gtxiblldma.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sysykeji.top/Article/details/gtxomtmgpq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gthdhmvqfv.html

[L06] 解析响应为 JSON
来源：http://dali.yueranfly.top/Article/details/gthgpfwjhv.html

Py:   resp.json()
来源：http://dali.daxiang520.top/Article/details/gtphsonnti.html

PHP:  json_decode($body, true);
来源：http://dali.vqdsnc.cn/Article/details/gtlnqrrdgz.html

JS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gtfxxzdsks.html

TS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gtdbvwxmtt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtdkarspzp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiaucknfl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ydzc1.top/Article/details/gtwwekzaiu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yanxiufei.cn/Article/details/gtzumolcsb.html

[L07] 处理 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gtqckixhmj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hfpthk.cn/Article/details/gtxvfbpqxi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhengqikj.top/Article/details/gtlfhosyln.html

JS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gttwtyrtlu.html

TS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gtziwdkohg.html

Java: resp.statusCode()
来源：http://dali.cucudq.cn/Article/details/gtqlyznfov.html

Go:   resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrstsozc.html

Ruby: resp.code.to_i
来源：http://dali.vqdsnc.cn/Article/details/gthemvgbvj.html

C#:   (int)resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gtffddyqnb.html

[L08] 并发请求多个地址
来源：http://dali.jinqigfzy.top/Article/details/gttebrnvgp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hfpthk.cn/Article/details/gtewfxbbrz.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuetiantiany.cn/Article/details/gtthztmlaz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gtzeacxmvz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtmvymgugc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhongyouzk.top/Article/details/gtfsrzanga.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sxryk.cn/Article/details/gthilkgoxo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuanzx.com/Article/details/gtgwzohgys.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258888.top/Article/details/gtzkafbmpi.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtczgdcvnv.html

M. 命令行 / 进程 / 环境
来源：http://dali.andypj.xyz/Article/details/gtjbgomcaw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtjumdxdec.html

[M01] 读取命令行参数
来源：http://dali.tian-w.cn/Article/details/gtuqjeztiu.html

Py:   sys.argv[1:]
来源：http://dali.0kj1m.cn/Article/details/gtuggmrsar.html

PHP:  $argv;  $argc;
来源：http://dali.wangdashe.top/Article/details/gtxvsfwutc.html

JS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtveqagayy.html

TS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gtdvztdapx.html

Java: args 数组（main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpzpiraq.html

Go:   os.Args[1:]
来源：http://dali.cucudq.cn/Article/details/gtpkhgxnmr.html

Ruby: ARGV
来源：http://dali.chenzaomai.com/Article/details/gtgvkoqcjf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tanke756.top/Article/details/gtmccjezwv.html

[M02] 读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gtezjuoasu.html

Py:   os.environ.get("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtvmqhniyv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gtgizvohrz.html

JS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtzaafarpz.html

TS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gtwmuueyvd.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtqlotmpyc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtpxyjpyzl.html

Ruby: ENV["HOME"]
来源：http://dali.wangdashe.top/Article/details/gtukhwylnb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuanzx.com/Article/details/gtklrzoqwk.html

[M03] 执行外部命令
来源：http://dali.zhoulong.xyz/Article/details/gtqzmzoiaw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgufenzy.top/Article/details/gtxukuliog.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangtech.top/Article/details/gthxrgrwin.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazwihjti.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtbonomxwh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenjidiqi.icu/Article/details/gtlqsjnrdp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtzfrydm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrgiuhge.html

C#:   Process.Start("ls", "-l");
来源：http://dali.svipenyu.cn/Article/details/gtuhgxrzfv.html

[M04] 获取当前工作目录
来源：http://dali.0kj1m.cn/Article/details/gtssccfgru.html

Py:   os.getcwd()
来源：http://dali.sweek.top/Article/details/gtkldktzpp.html

PHP:  getcwd();
来源：http://dali.zdqjudy.top/Article/details/gtxpnyalub.html

JS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtszoohkhp.html

TS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gttshvmfta.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guannengcc.top/Article/details/gtfoghvmzc.html

Go:   os.Getwd()
来源：http://dali.zycfv.cn/Article/details/gtheuexldf.html

Ruby: Dir.pwd
来源：http://dali.gaohongyu789.top/Article/details/gtsyvrwfig.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ppjwa.cn/Article/details/gtbtdteuzp.html

[M05] 设置退出码
来源：http://dali.hongshengwenyu.top/Article/details/gtezuridej.html

Py:   sys.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtzozuhdtz.html

PHP:  exit(1);
来源：http://dali.yanxiufei.cn/Article/details/gtlgvrmnwe.html

JS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gttaojsehv.html

TS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtesgjjzrj.html

Java: System.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtlixanegs.html

Go:   os.Exit(1)
来源：http://dali.yvedp.cn/Article/details/gtrcoxnxqb.html

Ruby: exit 1
来源：http://dali.yj20258888.top/Article/details/gtowtdbhzv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhiwuduotai.top/Article/details/gtvbzcbuuv.html

[M06] 向标准错误输出
来源：http://dali.shuidangran.top/Article/details/gtptrabptp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gtfwtudwth.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xylfe.cn/Article/details/gtzlpadida.html

JS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gtfudmdsgt.html

TS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gtazswxsyk.html

Java: System.err.println("err")
来源：http://dali.sxryk.cn/Article/details/gtvxaqajlr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttisrinni.html

Ruby: warn "err"
来源：http://dali.jinghuilouyu.cn/Article/details/gttexhlwru.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.9152youxi.cn/Article/details/gtblsqcrgc.html

[M07] 判断是否为主入口
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfobndwd.html

Py:   if __name__ == "__main__":
来源：http://dali.yvedp.cn/Article/details/gtedqxqidw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangshuangyany.cn/Article/details/gtneuwacfa.html

JS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gtklkhvozb.html

TS:   require.main === module
来源：http://dali.sweek.top/Article/details/gtszicbjoo.html

Java: public static void main(String[] args)
来源：http://dali.tian-w.cn/Article/details/gtslvugbss.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gtruzsovea.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gzhubu.top/Article/details/gtcopkhdpg.html

C#:   static void Main(string[] args)
来源：http://dali.nanxuanxn.top/Article/details/gtvyazvzzy.html

[M08] 获取系统与运行时信息
来源：http://dali.zdqjudy.top/Article/details/gtvrnhgyjj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jlsjyb.cn/Article/details/gtzrdgvbhw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigufen.top/Article/details/gtfbpshljt.html

JS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gtjnxekgaf.html

TS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtmojzrqmt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.smart0.xyz/Article/details/gtjsjjmcru.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cheryme.top/Article/details/gtcsmpojpd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fengsongda.top/Article/details/gtjajwklms.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ivvv.top/Article/details/gtrzhiwhbv.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtswuxksvc.html

N. 数据结构与算法
来源：http://dali.jianghu66.top/Article/details/gtmohyfydc.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtxgkjioqo.html

[N01] 二分查找（有序数组）
来源：http://dali.c1oappe.top/Article/details/gtrohjwefs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtgdkszska.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxrnzmtt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtloxchscr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gtimzwonvi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtgzwhrgma.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yongpay.top/Article/details/gtcbyivogt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxinkj.top/Article/details/gtsopkbtdh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gttedulwvj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangshuangyany.cn/Article/details/gtqiitmxfk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangdashe.top/Article/details/gtkopmnyyh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.redwolf501.top/Article/details/gtlovkbelp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gttzkacnsf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtbmnkoukr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yanxiufei.cn/Article/details/gtzcbswdyg.html

Go:   slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gtraxloctt.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gthtyjxkfk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhixingplan.top/Article/details/gtyldckmvl.html

[N03] 快速排序（分治示例）
来源：http://dali.ydzc1.top/Article/details/gtgbkmhhhu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jiagoushi.top/Article/details/gtzgykjisg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dianchejie.cn/Article/details/gtamumhylv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gtmleohper.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gtzmcegsae.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.haohaochexian.top/Article/details/gtyenxsjqr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnqzz.top/Article/details/gtzpyhyshu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigfzy.top/Article/details/gtbzqhxpzv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxinkj.top/Article/details/gtepapouax.html

[N04] 斐波那契数列
来源：http://dali.chenlongwang.top/Article/details/gtiybtnofb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gtocvkcgfh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvwfeqem.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtoseofzzg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtwyqjdxeg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gtdstlznvd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnqzz.top/Article/details/gtqogcojrd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sufxvd.cn/Article/details/gtwzppvglb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtelodngqq.html

[N05] 最大公约数
来源：http://dali.andypj.xyz/Article/details/gtakwpufbr.html

Py:   math.gcd(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtudmdhfda.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtkgsxlnrf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gtxdcyghew.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtlxekclcl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.haohaochexian.top/Article/details/gtzeebciok.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daria6918.cn/Article/details/gtmkxkzhhv.html

Ruby: a.gcd(b)
来源：http://dali.shzxlz.cn/Article/details/gteglzktos.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.feifeiyinyue.top/Article/details/gtadhobztw.html

[N06] 判断回文字符串
来源：http://dali.yueranfly.top/Article/details/gtuwpplyqs.html

Py:   s == s[::-1]
来源：http://dali.quarkkingdee.top/Article/details/gtqtlabyag.html

PHP:  $s === strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gtgsggdymx.html


<!-- 参考信息 -->