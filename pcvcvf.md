代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenjidiqi.icu/Article/details/gtshgrhgqm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuetiantiany.cn/Article/details/gtkfezaagi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenlongwang.top/Article/details/gtbvjtdejx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuxming.cn/Article/details/gtspnuvssr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gotoacloud.top/Article/details/gtvpimsctu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.snrcjt.cn/Article/details/gtfswdehit.html

[J09] 时区处理
来源：http://dali.xziqi.cn/Article/details/gtsdzkuzky.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ybcxt.top/Article/details/gtfiudnwou.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.smart0.xyz/Article/details/gtwxqbdaht.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gtccxeecun.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gttsgrlzud.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.feifeiyinyue.top/Article/details/gtktbdyvwo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yongpay.top/Article/details/gtomhhbmwm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xylfe.cn/Article/details/gtswyzlmek.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.316326.xyz/Article/details/gtfdqcsetf.html

[J10] 取今天 / 本月第一天
来源：http://dali.feifeiyinyue.top/Article/details/gtozwiodmn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yuanzhike.top/Article/details/gtzrswnlrf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ivvv.top/Article/details/gtcpspimqa.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yongpay.top/Article/details/gtsqdzwcod.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xziqi.cn/Article/details/gtnyszalqs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daxiang520.top/Article/details/gtmohczsdy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hysaishi.cn/Article/details/gtvobsmebp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sufxvd.cn/Article/details/gtjszjxznc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yvedp.cn/Article/details/gtqokjwzrr.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtlseeoeto.html

K. JSON 与序列化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqggkyhzk.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtlqhlglwl.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj202588.top/Article/details/gtiyrxcfmr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gtjrbvkujh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gtctlsnybs.html

JS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gtrpiuzitd.html

TS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gtcbdpnxni.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zycfv.cn/Article/details/gtsaxkcziu.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtguxzmrrb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.birdmap.top/Article/details/gtgeirloca.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuxming.cn/Article/details/gtpcpemltx.html

[K02] JSON 字符串转对象
来源：http://dali.hnxiangtu.top/Article/details/gtuxtacpof.html

Py:   json.loads(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtzvngilsb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gtquapuhwd.html

JS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gtspcxyymu.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtokrrjmsc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtbicchxhn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hysaishi.cn/Article/details/gtwzqdyjvm.html

Ruby: JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtfkkmejxj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.0kj1m.cn/Article/details/gtzbqlvriz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dashuyun.cn/Article/details/gtuavgyhzy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gtpesfrdvn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gtooydscap.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gthxxabilj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gtvmsiysnb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sxryk.cn/Article/details/gthgffotrd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yvedp.cn/Article/details/gtkafkpoeo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gtfrabbtwa.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenjidiqi.icu/Article/details/gthoiyykxw.html

[K04] 读取 JSON 文件
来源：http://dali.vqdsnc.cn/Article/details/gtwkjivlqh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dashuyun.cn/Article/details/gtxlimrjkl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuetiantiany.cn/Article/details/gtokibduqd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglnwqzfr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gtsnhjwyye.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtyzgqjzui.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtxcxctjom.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.havefunace.top/Article/details/gtvmypxmnx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ydzc1.top/Article/details/gtdynuqvdy.html

[K05] 深拷贝对象
来源：http://dali.sufxvd.cn/Article/details/gtwhfaqiqn.html

Py:   copy.deepcopy(obj)
来源：http://dali.guannengcc.top/Article/details/gttwpozyht.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenjidiqi.icu/Article/details/gtgmmunwbj.html

JS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtrqtlaesw.html

TS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gtipxdlkvr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tian-w.cn/Article/details/gtlwabjmkt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj202588.top/Article/details/gtgrvbyaig.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daxiang520.top/Article/details/gtycrkhkhk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tian-w.cn/Article/details/gteadxzsuz.html

[K06] 解析 URL 查询串
来源：http://dali.daria6918.cn/Article/details/gthuggdgmh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuxming.cn/Article/details/gttuwnjfpu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hongshengwenyu.top/Article/details/gtloduurko.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gtugumyazr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gtnyxiedux.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.redwolf501.top/Article/details/gtbbxfolpz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gtkovjemyb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gtezdxrwcw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtpycqxpej.html

[K07] 进制转换
来源：http://dali.ybcxt.top/Article/details/gtnoqtfdyn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sweek.top/Article/details/gtzcnogfuc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tian-w.cn/Article/details/gtzfpxrzms.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtaxhibkaz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtawnkfcjb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtbrzjoule.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258.top/Article/details/gtemhkymef.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ydzc1.top/Article/details/gtupqgxcuh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtkiblfvca.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ehwqpu.com/Article/details/gtvqcihxtj.html

Py:   pickle.dumps(obj)
来源：http://dali.zycfv.cn/Article/details/gtkvbvkghm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmlpfbqnp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gtnbokorhb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.smart0.xyz/Article/details/gtwxdfmnbz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hfpthk.cn/Article/details/gtsrkxenfl.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gtxhuhebtx.html

Ruby: Marshal.dump(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtvpazrkjm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gtfdruquhw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gttyzskmow.html

L. 网络请求
来源：http://dali.haohaochexian.top/Article/details/gtgvlxnzdc.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtymeywkqn.html

[L01] 发送 GET 请求
来源：http://dali.jinqigufen.top/Article/details/gtjpojoozf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhongyouzk.top/Article/details/gthrcyjshn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj202588.top/Article/details/gtertpezlz.html

JS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gtlqzokugk.html

TS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtxuiqiekh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yongpay.top/Article/details/gtgqtewswb.html

Go:   resp, err := http.Get(url)
来源：http://dali.gzhubu.top/Article/details/gthcsrgyoo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.haohaochexian.top/Article/details/gtsktgcbyc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.316326.xyz/Article/details/gtojxdmgwu.html

[L02] 发送 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gtytntmira.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwihnmhfs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinghuilouyu.cn/Article/details/gtriavvtpy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daria6918.cn/Article/details/gtjttxzbad.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvkmjelm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenzaomai.com/Article/details/gtwqoyymfm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.iojbl.cn/Article/details/gtnvmdywwd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aizwys.cn/Article/details/gtocgxrobc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.andypj.xyz/Article/details/gtnkdrrgvv.html

[L03] 设置自定义请求头
来源：http://dali.chenzaomai.com/Article/details/gtcwgzcoph.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.iojbl.cn/Article/details/gtcawoaajk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgfzy.top/Article/details/gtqrwpdllu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gtkmorglvs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gtrbuhwexy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yanxiufei.cn/Article/details/gtmxjequkf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gtxuephukk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ehwqpu.com/Article/details/gtytaknofe.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gtanxzexwh.html

[L04] 设置超时
来源：http://dali.yonumen.top/Article/details/gtivtqiddx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guannengcc.top/Article/details/gtpdgihrzo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhengqikj.top/Article/details/gtoqrdpzdl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangshuangyany.cn/Article/details/gtbawvoepj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmilloxjt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuanzhike.top/Article/details/gtcjnymnmf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sweek.top/Article/details/gteajebjzn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jianghu66.top/Article/details/gttyihxfgw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.feifeiyinyue.top/Article/details/gtnbanyjpv.html

[L05] 上传文件（multipart）
来源：http://dali.hywenlv.cn/Article/details/gtsptbrpac.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gtnwswezsv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hywenlv.cn/Article/details/gtcfpbxirt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gthslsbtxz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gtjpqdxqbf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aibaodan.cn/Article/details/gtqqphcbtl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sufxvd.cn/Article/details/gtdufqrcyc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hywenlv.cn/Article/details/gtroepoida.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtcbmvmsyc.html

[L06] 解析响应为 JSON
来源：http://dali.tian-w.cn/Article/details/gtvzgbguln.html

Py:   resp.json()
来源：http://dali.bjfxy.top/Article/details/gtrazjdvct.html

PHP:  json_decode($body, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtvvxmptal.html

JS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gtncjevvjx.html

TS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtnyrgemff.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtndxulfns.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.feifeiyinyue.top/Article/details/gtveyuieul.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ppjwa.cn/Article/details/gtmtdnldsx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.haohaochexian.top/Article/details/gtdmifzyzc.html

[L07] 处理 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gtgygjbljn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shangyingyoupin.top/Article/details/gtivrgywte.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gogol.net.cn/Article/details/gtxkkssaqq.html

JS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwglzqdwy.html

TS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gthgykfgvx.html

Java: resp.statusCode()
来源：http://dali.iojbl.cn/Article/details/gtzcnwdhmg.html

Go:   resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gtenvtzppm.html

Ruby: resp.code.to_i
来源：http://dali.guannengcc.top/Article/details/gtweypfqan.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gtpzlsccyk.html

[L08] 并发请求多个地址
来源：http://dali.fzhhl.top/Article/details/gtcfbyvvhz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnxiangtu.top/Article/details/gtheupgrzz.html

PHP:  curl_multi_init() 系列
来源：http://dali.jianghu66.top/Article/details/gtzlgbhxlv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtnmnfcpxu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtboghwpvm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cdnleiting.top/Article/details/gtnjnisaev.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhongyouzk.top/Article/details/gtrvedbajv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gtqujcjeop.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hammf.cn/Article/details/gthyekzimd.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtcmmzhxiv.html

M. 命令行 / 进程 / 环境
来源：http://dali.0kj1m.cn/Article/details/gtvtvinkdb.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtvqtcwvai.html

[M01] 读取命令行参数
来源：http://dali.yuxming.cn/Article/details/gtdurrsfoa.html

Py:   sys.argv[1:]
来源：http://dali.vqdsnc.cn/Article/details/gtnnyhfuqw.html

PHP:  $argv;  $argc;
来源：http://dali.9152youxi.cn/Article/details/gtbnoyjvtz.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbcylplq.html

TS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtidmsvbzp.html

Java: args 数组（main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtdpgogizq.html

Go:   os.Args[1:]
来源：http://dali.ybcxt.top/Article/details/gtemlbrpuq.html

Ruby: ARGV
来源：http://dali.zhiwuduotai.top/Article/details/gttirvlgdi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.birdmap.top/Article/details/gtmietanej.html

[M02] 读取环境变量
来源：http://dali.smart0.xyz/Article/details/gtrpptgcvp.html

Py:   os.environ.get("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtrbkbiidz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gtlojvoyim.html

JS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gtarzokwtx.html

TS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gtgrhmqeya.html

Java: System.getenv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzslqmqck.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ivvv.top/Article/details/gtffocoecc.html

Ruby: ENV["HOME"]
来源：http://dali.xziqi.cn/Article/details/gtnpqsyoqw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtqzhncyse.html

[M03] 执行外部命令
来源：http://dali.shangyingyoupin.top/Article/details/gtfabrwatw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.svipenyu.cn/Article/details/gtkmpovdyn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hysaishi.cn/Article/details/gtydokdzxp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtwvrbntvx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gtgtpxfjvi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.feifeiyinyue.top/Article/details/gtbxqwrdtv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.svipenyu.cn/Article/details/gtsazpcadd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pycfn.com/Article/details/gtiduoqtou.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ybcxt.top/Article/details/gtvyshrgnv.html

[M04] 获取当前工作目录
来源：http://dali.tanke756.top/Article/details/gtywzfpfaz.html

Py:   os.getcwd()
来源：http://dali.zhongyouzk.top/Article/details/gtygwzypdt.html

PHP:  getcwd();
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmsrogqk.html

JS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gtozbafdbs.html

TS:   process.cwd()
来源：http://dali.chenlongwang.top/Article/details/gthoxmydpm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258888.top/Article/details/gteqaycnwe.html

Go:   os.Getwd()
来源：http://dali.tianlin.xyz/Article/details/gtcuolmcwm.html

Ruby: Dir.pwd
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfubtglj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxinkj.top/Article/details/gtypnghbqy.html

[M05] 设置退出码
来源：http://dali.jiagoushi.top/Article/details/gtuhwciidx.html

Py:   sys.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtydknpeqv.html

PHP:  exit(1);
来源：http://dali.cheryme.top/Article/details/gtxxqzeyqj.html

JS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtqkutpjxp.html

TS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gtlzyporuz.html

Java: System.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtrprwtfjw.html

Go:   os.Exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtmxcutsxi.html

Ruby: exit 1
来源：http://dali.zhixingplan.top/Article/details/gttqoitjyy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhoulong.xyz/Article/details/gtprlucjpy.html

[M06] 向标准错误输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaowjstnr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj202588.top/Article/details/gthkyldxwu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gtctshxtfa.html

JS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gtkhghfztb.html

TS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gttfwbmbhg.html

Java: System.err.println("err")
来源：http://dali.tianlin.xyz/Article/details/gtgceotrkp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangdashe.top/Article/details/gtzlcnmrdx.html

Ruby: warn "err"
来源：http://dali.aibaodan.cn/Article/details/gtkdwgtawh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guannengcc.top/Article/details/gtjagmoxsr.html

[M07] 判断是否为主入口
来源：http://dali.ppjwa.cn/Article/details/gtedxrtyam.html

Py:   if __name__ == "__main__":
来源：http://dali.yvedp.cn/Article/details/gttoxnyeqx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cashguo.top/Article/details/gtalymjegj.html

JS:   require.main === module
来源：http://dali.fzhhl.top/Article/details/gtbavzfcqq.html

TS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gtiapliukd.html

Java: public static void main(String[] args)
来源：http://dali.redwolf501.top/Article/details/gtuvmqwbyq.html

Go:   func main()
来源：http://dali.hongshengwenyu.top/Article/details/gtwpblmbeo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yvedp.cn/Article/details/gtqimtsjhp.html

C#:   static void Main(string[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gthbongulz.html

[M08] 获取系统与运行时信息
来源：http://dali.iojbl.cn/Article/details/gtofdqsvpj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jianghu66.top/Article/details/gtaszqmstc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cucudq.cn/Article/details/gtjsdglain.html

JS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gtcxqtqbij.html

TS:   process.platform;  process.version
来源：http://dali.yj202588.top/Article/details/gtrjardlgk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.bjfxy.top/Article/details/gtborxolvj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jiagoushi.top/Article/details/gtzkejtcuw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yueranfly.top/Article/details/gtkpkowqqu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hywenlv.cn/Article/details/gtxjepijme.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtqrvwfigc.html

N. 数据结构与算法
来源：http://dali.birdmap.top/Article/details/gttlacspyd.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtmzfhknaa.html

[N01] 二分查找（有序数组）
来源：http://dali.ivvv.top/Article/details/gtftdjenzy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtrqajorsn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guannengcc.top/Article/details/gtobhdjsfh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtmxxxekmk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gtgitvsgac.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtfvhekxqk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtykvrxhps.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuanzhike.top/Article/details/gtbaudvtaq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtnyowadmd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gtxmomiepu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gtuomiabyo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xziqi.cn/Article/details/gtkmtbtmln.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gtuikpotom.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gtwfxakcim.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yangfankeji.com/Article/details/gtmzvkvcky.html

Go:   slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gttgkyhetx.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gtwmfzawrf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xziqi.cn/Article/details/gtgtjpcwgp.html

[N03] 快速排序（分治示例）
来源：http://dali.pycfn.com/Article/details/gtopnalrjz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fzhhl.top/Article/details/gttbhzzqkt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aizwys.cn/Article/details/gtwtsgpgxx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gtalesjmcf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cashguo.top/Article/details/gtkqviriwc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tanke756.top/Article/details/gtprmexuzn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigfzy.top/Article/details/gtlwkypika.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.meibo888.top/Article/details/gtdsxtvaeo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hywenlv.cn/Article/details/gtorapbbao.html

[N04] 斐波那契数列
来源：http://dali.feifeiyinyue.top/Article/details/gtbwuokqcp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gttrweqnsi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gtdrnsxydj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtjglvvarp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtelihzpdw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sweek.top/Article/details/gtdhmumgoo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.mhx1999.top/Article/details/gtijnztbwt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gtujambptc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtsdjtapee.html

[N05] 最大公约数
来源：http://dali.zdqjudy.top/Article/details/gtcfrxants.html

Py:   math.gcd(a, b)
来源：http://dali.iojbl.cn/Article/details/gtvhvlseew.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtrlsanbfk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gtpbdliqjl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gtxxxprjbz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkayoejzm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zycfv.cn/Article/details/gtiirblemq.html

Ruby: a.gcd(b)
来源：http://dali.jianghu66.top/Article/details/gtrcahgzys.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigufen.top/Article/details/gtburlmsdm.html

[N06] 判断回文字符串
来源：http://dali.ybcxt.top/Article/details/gtdxuwwyzm.html

Py:   s == s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gtnfoihbcw.html

PHP:  $s === strrev($s);
来源：http://dali.fengsongda.top/Article/details/gtpzmefkwt.html


<!-- 参考信息 -->