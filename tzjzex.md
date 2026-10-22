代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fengsongda.top/Article/details/gtmabqdheh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangdashe.top/Article/details/gtkkzyocao.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuxming.cn/Article/details/gtwigipong.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guannengcc.top/Article/details/gtzepofwaa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fzhhl.top/Article/details/gtedxidmiz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.316326.xyz/Article/details/gthztdhjjc.html

[J09] 时区处理
来源：http://dali.meibo888.top/Article/details/gtrakbfpss.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gotoacloud.top/Article/details/gtuoqenvof.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxinkj.top/Article/details/gtatljuyjn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gtrclfslbr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gtwlndfauy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pengpengdd.cyou/Article/details/gtycsltkyp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbydquzkr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tian-w.cn/Article/details/gtzrjsvizn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cdnleiting.top/Article/details/gtpaaeifym.html

[J10] 取今天 / 本月第一天
来源：http://dali.daria6918.cn/Article/details/gtcmdxpegu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yanxiufei.cn/Article/details/gtoxkplvnh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guowangkeji.top/Article/details/gtiyxviaga.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yongpay.top/Article/details/gtdhbppczq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yonumen.top/Article/details/gtnuwfpbml.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aizwys.cn/Article/details/gtvxjkdxwo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gtougwqila.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dianchejie.cn/Article/details/gtuayoggtm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.c1oappe.top/Article/details/gtaafmlghv.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtzneajsai.html

K. JSON 与序列化
来源：http://dali.chenlongwang.top/Article/details/gtbirnwjsv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtybbhfydu.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhiwuduotai.top/Article/details/gttksytxbv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gtjbmxtmbf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.guannengcc.top/Article/details/gtmemwhgal.html

JS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtzdpyxhsd.html

TS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gtbcuggiyj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tian-w.cn/Article/details/gtfrrjrahr.html

Go:   json.Marshal(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryyuovgx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tianlin.xyz/Article/details/gtdxakngsl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuanzhike.top/Article/details/gtkutcqezx.html

[K02] JSON 字符串转对象
来源：http://dali.xylfe.cn/Article/details/gtkmtnkrwx.html

Py:   json.loads(s)
来源：http://dali.iojbl.cn/Article/details/gtdmvvsjvd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tian-w.cn/Article/details/gtbuahjlct.html

JS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtqgytkvrv.html

TS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtpmkvmodh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtxstzrdon.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gtmjnzzggq.html

Ruby: JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtwfibnvwu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fengsongda.top/Article/details/gtbpzpichg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnqzz.top/Article/details/gtvzhylpyp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gtfntrtron.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gtdzsbgbse.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gtxebbrwkx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gtzbzmtteq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtftcwgfxl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gogol.net.cn/Article/details/gtisfowvjh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.9152youxi.cn/Article/details/gtsbbtuwmt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ehwqpu.com/Article/details/gtyfqbtjjb.html

[K04] 读取 JSON 文件
来源：http://dali.ivvv.top/Article/details/gtmxcchwpj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ivvv.top/Article/details/gtiitslizd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guowangkeji.top/Article/details/gtyhtmrtdq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gtlkxedfzs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gtutlaepjs.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gtsmsvbptn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdvmmelv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gtcattcelw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ybcxt.top/Article/details/gtlmxnmwar.html

[K05] 深拷贝对象
来源：http://dali.pengpengdd.cyou/Article/details/gtpwjolglo.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258888.top/Article/details/gtguihmeod.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gotoacloud.top/Article/details/gtarydvzxf.html

JS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gttqtnzcbv.html

TS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtkgaayvfs.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fzhhl.top/Article/details/gtfmevueca.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuanzx.com/Article/details/gttkjasjwz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj202588.top/Article/details/gthbkdalhw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fengsongda.top/Article/details/gtmzjzvjaf.html

[K06] 解析 URL 查询串
来源：http://dali.hnxiangtu.top/Article/details/gticshqgpt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gtswdiiwsp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzsgkaqv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtbtremlbs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gtvhpopcte.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daria6918.cn/Article/details/gtceagbhyw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtzexgdlnv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtcicwojqp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gtpdchywgl.html

[K07] 进制转换
来源：http://dali.zycfv.cn/Article/details/gtzdrsznam.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtboyfdwbo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fengsongda.top/Article/details/gtqqfasdkb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtccgafduz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gtkyikzcjz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gteiqtprww.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenzaomai.com/Article/details/gtygkrfksb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.haohaochexian.top/Article/details/gtshfrqpod.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtpzxrtndb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ehwqpu.com/Article/details/gtistaajgh.html

Py:   pickle.dumps(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtizdtpwuc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuanzhike.top/Article/details/gtwplguifv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gtftcszbwi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gtfccmxtok.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.feifeiyinyue.top/Article/details/gthyyphgjn.html

Go:   encoding/gob
来源：http://dali.zhoulong.xyz/Article/details/gtqeilbxcv.html

Ruby: Marshal.dump(obj)
来源：http://dali.guowangkeji.top/Article/details/gtmjxwpaum.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gtfcqmjyox.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtfdqucduj.html

L. 网络请求
来源：http://dali.chenjidiqi.icu/Article/details/gtcojcbmqk.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtvjkcglap.html

[L01] 发送 GET 请求
来源：http://dali.ybcxt.top/Article/details/gtzvwdtpyv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nwbrower.top/Article/details/gtaovubwev.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yongpay.top/Article/details/gtdwekuouc.html

JS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gtumrlbcii.html

TS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gtdxnmzqmo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigufen.top/Article/details/gtdcbtipnq.html

Go:   resp, err := http.Get(url)
来源：http://dali.yangfankeji.com/Article/details/gtcvofhzok.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dashuyun.cn/Article/details/gtxvjheelo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxaogkuyl.html

[L02] 发送 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gthctzvpom.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gtaztniitt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuxming.cn/Article/details/gtcxjamfbm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gtrkehudse.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gtjaiyolyh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.bjfxy.top/Article/details/gtrjtcscoe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuanzx.com/Article/details/gtaagtkqtd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cqqwz.cn/Article/details/gteshjidby.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xuanzx.com/Article/details/gtpkqzwiet.html

[L03] 设置自定义请求头
来源：http://dali.ybcxt.top/Article/details/gtkipebiow.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gaohongyu789.top/Article/details/gtxetbmyrr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.mhx1999.top/Article/details/gtsocoqutb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gtldvijkep.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sysykeji.top/Article/details/gtiedhuzvn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenzaomai.com/Article/details/gtpztlbrxs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.meibo888.top/Article/details/gtveolsher.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gaohongyu789.top/Article/details/gtggpgiivn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gtdertoebl.html

[L04] 设置超时
来源：http://dali.aizwys.cn/Article/details/gtgemnjehp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxsipelj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cucudq.cn/Article/details/gtscrarrwa.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tanke756.top/Article/details/gteesxwqhj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gtvytmglvo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yanxiufei.cn/Article/details/gtsqpfdokq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nanxuanxn.top/Article/details/gtflkavnex.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.bjfxy.top/Article/details/gtbaryvmfd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhongyouzk.top/Article/details/gteahkmdue.html

[L05] 上传文件（multipart）
来源：http://dali.fengsongda.top/Article/details/gtzqelxqqy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pengpengdd.cyou/Article/details/gtlzxauhcj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj202588.top/Article/details/gtxpfzpxmz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gtxihiwjzc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gtxlubpfjk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfbxioab.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shangyingyoupin.top/Article/details/gtpyzlfbun.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj202588.top/Article/details/gtzgyzsyxk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xinyue.icu/Article/details/gtlzrrcurv.html

[L06] 解析响应为 JSON
来源：http://dali.sysykeji.top/Article/details/gtxoarkbcz.html

Py:   resp.json()
来源：http://dali.yonumen.top/Article/details/gtvcqhnfbu.html

PHP:  json_decode($body, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwouqxkbc.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gtlhudbxzh.html

TS:   await resp.json()
来源：http://dali.smart0.xyz/Article/details/gttnrbcwxz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtlshyprdh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.snrcjt.cn/Article/details/gthwqbhtyj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucqybnit.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigufen.top/Article/details/gtmnjbtclu.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gtmddsvysr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggwosuqk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guannengcc.top/Article/details/gtkxktkbrp.html

JS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gtonememhv.html

TS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gtpuasltxe.html

Java: resp.statusCode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclhuxdpq.html

Go:   resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gtqdcvcslo.html

Ruby: resp.code.to_i
来源：http://dali.andypj.xyz/Article/details/gtpbuzezej.html

C#:   (int)resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gtnmbsadzq.html

[L08] 并发请求多个地址
来源：http://dali.pycfn.com/Article/details/gtdmtuhvss.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tanke756.top/Article/details/gtqdomajxr.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhongyouzk.top/Article/details/gtsuaiainu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzbtrrok.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtmykqepdz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258888.top/Article/details/gtgctcxnyn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daxiang520.top/Article/details/gtjqyflzvc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ivvv.top/Article/details/gtuhfsbxle.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgfzy.top/Article/details/gtoakzylli.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtpejhpfcr.html

M. 命令行 / 进程 / 环境
来源：http://dali.ybcxt.top/Article/details/gtpfyhagsc.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtlqqhrdxz.html

[M01] 读取命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gtgpbcxhlq.html

Py:   sys.argv[1:]
来源：http://dali.ybcxt.top/Article/details/gtnqtasduv.html

PHP:  $argv;  $argc;
来源：http://dali.mhx1999.top/Article/details/gtdcwinxst.html

JS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gtcqylvitt.html

TS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gtqfzvrbhh.html

Java: args 数组（main 方法参数）
来源：http://dali.ivvv.top/Article/details/gtvvjikkif.html

Go:   os.Args[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtswpyfopo.html

Ruby: ARGV
来源：http://dali.vqdsnc.cn/Article/details/gtzmvitbpk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.havefunace.top/Article/details/gtqlbakois.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbmvzqae.html

Py:   os.environ.get("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtqthdfwra.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gtmaungxac.html

JS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gtxejtwmiw.html

TS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtrisnhxzz.html

Java: System.getenv("HOME")
来源：http://dali.aizwys.cn/Article/details/gtfocbgjji.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtfrtztzxu.html

Ruby: ENV["HOME"]
来源：http://dali.cheryme.top/Article/details/gtrmckpiln.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xinyue.icu/Article/details/gtortodwsq.html

[M03] 执行外部命令
来源：http://dali.birdmap.top/Article/details/gtejggnfkh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnxiangtu.top/Article/details/gtodmxvwkr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hfpthk.cn/Article/details/gtnynlabte.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gtxoyujoye.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gtgmdsehxy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gogol.net.cn/Article/details/gtidieunlb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aizwys.cn/Article/details/gtmyefnfxw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenjidiqi.icu/Article/details/gtrlbxpjgd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenzaomai.com/Article/details/gtwnaivmih.html

[M04] 获取当前工作目录
来源：http://dali.gaohongyu789.top/Article/details/gtkvrwipoz.html

Py:   os.getcwd()
来源：http://dali.tian-w.cn/Article/details/gtgenjiyms.html

PHP:  getcwd();
来源：http://dali.meibo888.top/Article/details/gtllnljrsg.html

JS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gtgyjcobif.html

TS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gtpilkysru.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dashuyun.cn/Article/details/gttkdeleao.html

Go:   os.Getwd()
来源：http://dali.shzxlz.cn/Article/details/gtcvcfulry.html

Ruby: Dir.pwd
来源：http://dali.hammf.cn/Article/details/gtedeqwrob.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aizwys.cn/Article/details/gtwkdgsfon.html

[M05] 设置退出码
来源：http://dali.yuxming.cn/Article/details/gtqsxcipun.html

Py:   sys.exit(1)
来源：http://dali.birdmap.top/Article/details/gtqukfzlym.html

PHP:  exit(1);
来源：http://dali.aibaodan.cn/Article/details/gtznrrtkha.html

JS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtcfxdrcql.html

TS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtqzrgszxd.html

Java: System.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtsjmmfavl.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gtrgcdoxtk.html

Ruby: exit 1
来源：http://dali.hnqzz.top/Article/details/gtasqjwaeu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxinkj.top/Article/details/gtmgjwgyzb.html

[M06] 向标准错误输出
来源：http://dali.hywenlv.cn/Article/details/gtqmowgcmw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gthfqboqah.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hysaishi.cn/Article/details/gtusiizkzh.html

JS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtvktvfdct.html

TS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtauwturjr.html

Java: System.err.println("err")
来源：http://dali.dashuyun.cn/Article/details/gtojbupoyj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cdnleiting.top/Article/details/gtzzevjsca.html

Ruby: warn "err"
来源：http://dali.dianchejie.cn/Article/details/gtzusbhhuu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jianghu66.top/Article/details/gtpsyqzovs.html

[M07] 判断是否为主入口
来源：http://dali.jlsjyb.cn/Article/details/gthsmgrsdx.html

Py:   if __name__ == "__main__":
来源：http://dali.hywenlv.cn/Article/details/gtwudhibqb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.guowangkeji.top/Article/details/gtnsybzqfj.html

JS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gtyqtvxpij.html

TS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtbmjgckhg.html

Java: public static void main(String[] args)
来源：http://dali.zycfv.cn/Article/details/gtufklxqya.html

Go:   func main()
来源：http://dali.ehwqpu.com/Article/details/gtlwyyoxsd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cqqwz.cn/Article/details/gtpdcpknev.html

C#:   static void Main(string[] args)
来源：http://dali.yanxiufei.cn/Article/details/gtkrexbnqz.html

[M08] 获取系统与运行时信息
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkfmsfuk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangdashe.top/Article/details/gtlwbhrofb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dashuyun.cn/Article/details/gtemssyobl.html

JS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gtllbjbmry.html

TS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gtprhulclk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cqqwz.cn/Article/details/gtsrisfwaj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpmslcyd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ydzc1.top/Article/details/gtnyskbnkb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenzaomai.com/Article/details/gtdsgbossg.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtpgnutgym.html

N. 数据结构与算法
来源：http://dali.cucudq.cn/Article/details/gtwmlmedpe.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtonjmiuff.html

[N01] 二分查找（有序数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdzbxhqb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtoiqrbmfq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gotoacloud.top/Article/details/gtoaendkgm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtcabehowk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gtltghdytw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtsojfojtc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.316326.xyz/Article/details/gtqpdvqnps.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sweek.top/Article/details/gtktecahad.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwkkeuab.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuanzhike.top/Article/details/gtwsbnnwcu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gtbutsqeoa.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.bjfxy.top/Article/details/gtocyoupxy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtkobouhgc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtgxeuglgj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fzhhl.top/Article/details/gtovkudaco.html

Go:   slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gtlmhyrcbl.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gtddksqdsg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guowangkeji.top/Article/details/gtximgywrw.html

[N03] 快速排序（分治示例）
来源：http://dali.vqdsnc.cn/Article/details/gtcwriwaih.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aibaodan.cn/Article/details/gtmrglvlag.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shangyingyoupin.top/Article/details/gtwcfuuthy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gtijfrgfjq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gtqvhpfjkr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xinyue.icu/Article/details/gtvapfibyq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangtech.top/Article/details/gtqypxztik.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.smart0.xyz/Article/details/gthbvewarj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenzaomai.com/Article/details/gtcceftzpm.html

[N04] 斐波那契数列
来源：http://dali.yj20258.top/Article/details/gtshypxuyt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gtrxjuxvbo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gthykzxykd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gtkvkuyvyy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gtvhowdccc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gtdfizggvy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.9152youxi.cn/Article/details/gtrzyxicyl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gtrsnumiei.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtptuajdfg.html

[N05] 最大公约数
来源：http://dali.dianchejie.cn/Article/details/gtpdrnqkri.html

Py:   math.gcd(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtzxccaaiv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tian-w.cn/Article/details/gtkvoibxfs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtbmxmrvum.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gtogherdkc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenzaomai.com/Article/details/gtvsltojwr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258.top/Article/details/gtsvksbfac.html

Ruby: a.gcd(b)
来源：http://dali.yanxiufei.cn/Article/details/gtmwiburjy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnolangvf.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypbiegwj.html

Py:   s == s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gtvlslswcp.html

PHP:  $s === strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtmqinychx.html


<!-- 参考信息 -->