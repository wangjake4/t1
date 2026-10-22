代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtiodkypyw.html

[J08] 提取年月日与星期
来源：http://dali.jianghu66.top/Article/details/gtipyrgxff.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcjvynow.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yonumen.top/Article/details/gtsdcytyrd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangshuangyany.cn/Article/details/gtwioispcp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gotoacloud.top/Article/details/gthmerlopw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yangfankeji.com/Article/details/gtproyqovq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbnpjnrfq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhoulong.xyz/Article/details/gtgoueqdyk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwldpcyuu.html

[J09] 时区处理
来源：http://dali.fzhhl.top/Article/details/gtqugemuxb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigufen.top/Article/details/gtxvdntdhj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.c1oappe.top/Article/details/gtphehjqoe.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gtyxdrzmpe.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtcuuqtqes.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jyoumei.cn/Article/details/gtpasqmosb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hywenlv.cn/Article/details/gtgyucwjvu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnqzz.top/Article/details/gtkpponkjb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258.top/Article/details/gtakkosgwp.html

[J10] 取今天 / 本月第一天
来源：http://dali.mhx1999.top/Article/details/gtccrjzcqa.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangshuangyany.cn/Article/details/gttzagrudd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cashguo.top/Article/details/gtwzpjrlxr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.birdmap.top/Article/details/gtsjlhcnja.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yvedp.cn/Article/details/gtanamwweh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yongpay.top/Article/details/gtdcurhfuy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pengpengdd.cyou/Article/details/gthapnuane.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhongyouzk.top/Article/details/gtfvgddseq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ydzc1.top/Article/details/gtkxfodkoh.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtpkvfrkyd.html

K. JSON 与序列化
来源：http://dali.wangdashe.top/Article/details/gthbozixgf.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtctbhwbvb.html

[K01] 对象转 JSON 字符串
来源：http://dali.kuanghao11.cn/Article/details/gtxcahowqp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gtcrfzberl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gtemtbohku.html

JS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtpciitojz.html

TS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gtcctjpbsh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxinkj.top/Article/details/gtqoiturye.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gtpikvffll.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenlongwang.top/Article/details/gtzpunkbpo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtkbuncatg.html

[K02] JSON 字符串转对象
来源：http://dali.jlsjyb.cn/Article/details/gtpykysxsk.html

Py:   json.loads(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtnzezfqch.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cdnleiting.top/Article/details/gtjsulxbgt.html

JS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtqxtmmydb.html

TS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gttuaybckt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ivvv.top/Article/details/gtwghnbgjl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gtiyynlkih.html

Ruby: JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gtrgiantwj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fengsongda.top/Article/details/gtdgdpdwtf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gtylcnjbwv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gtcsnnntmn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gtkvfvpjvl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gtnrxnghlw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtkcxqqycm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xylfe.cn/Article/details/gtevivwwvd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhongyouzk.top/Article/details/gtwbddkmgu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yvedp.cn/Article/details/gtzjfqxtzy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tianlin.xyz/Article/details/gthsyihuei.html

[K04] 读取 JSON 文件
来源：http://dali.yanxiufei.cn/Article/details/gtfxblaxfq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dianchejie.cn/Article/details/gtqbdwhhsv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj202588.top/Article/details/gtwerhyqho.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtwyuyfiib.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gtygfwpjwb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ivvv.top/Article/details/gtbjdvcctw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gtdjmpdgcs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gteadoozap.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gtourqydpv.html

[K05] 深拷贝对象
来源：http://dali.zhixingplan.top/Article/details/gtjogngnpj.html

Py:   copy.deepcopy(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtibdwmait.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hfpthk.cn/Article/details/gtielanbii.html

JS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gtdwbdyabw.html

TS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtvgnpftmx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.iojbl.cn/Article/details/gtgwwotqlq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tanke756.top/Article/details/gtwofosewa.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aibaodan.cn/Article/details/gtufvpgref.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.redwolf501.top/Article/details/gttjvqfxdn.html

[K06] 解析 URL 查询串
来源：http://dali.aizwys.cn/Article/details/gtjgifpuas.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gtzvugminm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufxzgzog.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gtcocgogxf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gtpvomoiry.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gtoybybimf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtunuaifbj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtftahqrvw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtdcxnpqnz.html

[K07] 进制转换
来源：http://dali.daxiang520.top/Article/details/gtvixwtqxc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtatvtfavy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258.top/Article/details/gtiersizsi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtmlqwmrkr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtqwlvokxu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtlmblnvsr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.kuanghao11.cn/Article/details/gtbzhujeie.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenzaomai.com/Article/details/gtagqozhip.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtvtteoeam.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sysykeji.top/Article/details/gtnmrobmzf.html

Py:   pickle.dumps(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtlvodbkte.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtfpbzubrf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gtiqjorlzj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtltxwjzrb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigufen.top/Article/details/gtlntovmoa.html

Go:   encoding/gob
来源：http://dali.yonumen.top/Article/details/gtqhzchnla.html

Ruby: Marshal.dump(obj)
来源：http://dali.9152youxi.cn/Article/details/gtnzwalext.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gtydmxincm.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtonqgqdwl.html

L. 网络请求
来源：http://dali.0kj1m.cn/Article/details/gtonbfqzzo.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtiwosajox.html

[L01] 发送 GET 请求
来源：http://dali.gogol.net.cn/Article/details/gtfdnynozd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.birdmap.top/Article/details/gtmlkvgpdh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenjidiqi.icu/Article/details/gthvzncbex.html

JS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gtifgztzwz.html

TS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gtiflodinw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.9152youxi.cn/Article/details/gtnkozpjia.html

Go:   resp, err := http.Get(url)
来源：http://dali.aizwys.cn/Article/details/gtqinuvlrh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tanke756.top/Article/details/gtjimqjsjm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhoulong.xyz/Article/details/gtonxbrakm.html

[L02] 发送 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gtjyechcof.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrjotuha.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yongpay.top/Article/details/gtanjuxbcb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daria6918.cn/Article/details/gtxickoicp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gtnchldnjl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cheryme.top/Article/details/gtbfwdsyet.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dashuyun.cn/Article/details/gthmofqapb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shuidangran.top/Article/details/gtksptyvvi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sweek.top/Article/details/gtucumtrsa.html

[L03] 设置自定义请求头
来源：http://dali.gogol.net.cn/Article/details/gtxikntuxe.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ydzc1.top/Article/details/gtskposlqw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.meibo888.top/Article/details/gtvzgibtnj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gtlvrisbjo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gtgsilkhyb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgufenzy.top/Article/details/gtzmnpobid.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gtdienitwb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daria6918.cn/Article/details/gthdcigqgz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gtuvlsqsmp.html

[L04] 设置超时
来源：http://dali.chenlongwang.top/Article/details/gtvqntfxhi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shangyingyoupin.top/Article/details/gtnqdzmmcf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gtdbhzjtoj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gtnclqgpmw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gtiwwnrhzd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sysykeji.top/Article/details/gttaztalsg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuxming.cn/Article/details/gtofgpjemy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zycfv.cn/Article/details/gtbyuacdaf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqwjksib.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gtvpbnfohv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jyoumei.cn/Article/details/gtgdidegpy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjygdtjdv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gtjxrybqwj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gtcdmemjrs.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tianlin.xyz/Article/details/gtmouzptqm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hnqzz.top/Article/details/gtdjsirbvx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yonumen.top/Article/details/gttxamgnzd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtssuvtpnh.html

[L06] 解析响应为 JSON
来源：http://dali.jlsjyb.cn/Article/details/gtrghrgral.html

Py:   resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjogbexko.html

PHP:  json_decode($body, true);
来源：http://dali.tianlin.xyz/Article/details/gtywftoilq.html

JS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gtonnmoxgu.html

TS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtzdepecnj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ybcxt.top/Article/details/gtbutryrkj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangshuangyany.cn/Article/details/gtlhlvhwow.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenzaomai.com/Article/details/gtnrrtzjvs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dashuyun.cn/Article/details/gtgouliimi.html

[L07] 处理 HTTP 状态码
来源：http://dali.ppjwa.cn/Article/details/gtqnblmkhi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.iojbl.cn/Article/details/gtdbceewsf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ydzc1.top/Article/details/gtxdaygjly.html

JS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gtlfkitwhr.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtjcnjkces.html

Java: resp.statusCode()
来源：http://dali.sufxvd.cn/Article/details/gtnoqgxqpo.html

Go:   resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gtdwapxnyr.html

Ruby: resp.code.to_i
来源：http://dali.0kj1m.cn/Article/details/gtgapfaepo.html

C#:   (int)resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gtktfphwbb.html

[L08] 并发请求多个地址
来源：http://dali.yongpay.top/Article/details/gtxqanbvwm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.feifeiyinyue.top/Article/details/gtpprxhdwg.html

PHP:  curl_multi_init() 系列
来源：http://dali.cucudq.cn/Article/details/gtruyterzn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtxfqnybmz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gtcfbasgwm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hywenlv.cn/Article/details/gtfjtetbql.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhpsoalw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gtzpqjiaqm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ydzc1.top/Article/details/gtdytuxhje.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrkslsin.html

M. 命令行 / 进程 / 环境
来源：http://dali.hammf.cn/Article/details/gtgjngpstp.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrjxjesg.html

[M01] 读取命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gtxbpqtuez.html

Py:   sys.argv[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtnvjwpzyy.html

PHP:  $argv;  $argc;
来源：http://dali.smart0.xyz/Article/details/gtuftwbcuh.html

JS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhjyoznm.html

TS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtixzvjhhy.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gtrgixhjcc.html

Go:   os.Args[1:]
来源：http://dali.hywenlv.cn/Article/details/gtdewzfgqe.html

Ruby: ARGV
来源：http://dali.hammf.cn/Article/details/gtmrccecfg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gttkarwvdo.html

[M02] 读取环境变量
来源：http://dali.yj20258888.top/Article/details/gtakxmaooh.html

Py:   os.environ.get("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtkiqaajqc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gtdthqgayd.html

JS:   process.env.HOME
来源：http://dali.tanke756.top/Article/details/gthobrngxb.html

TS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gtsglwhtcc.html

Java: System.getenv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gthzwtpowq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daxiang520.top/Article/details/gtizxjqgsx.html

Ruby: ENV["HOME"]
来源：http://dali.xylfe.cn/Article/details/gtzparttkk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtivejdzxq.html

[M03] 执行外部命令
来源：http://dali.chenzaomai.com/Article/details/gtkghoftiv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtwcmgvllf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jianghu66.top/Article/details/gttfproenl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gtganyjygf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sufxvd.cn/Article/details/gtvqsgjnov.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sxryk.cn/Article/details/gtaussgrwh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gtvudmiamy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xziqi.cn/Article/details/gtaasebgmp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hywenlv.cn/Article/details/gtrqjftxwt.html

[M04] 获取当前工作目录
来源：http://dali.fengsongda.top/Article/details/gtqxwgtcpi.html

Py:   os.getcwd()
来源：http://dali.yuanzhike.top/Article/details/gtwpabesbn.html

PHP:  getcwd();
来源：http://dali.meibo888.top/Article/details/gtuilzlmax.html

JS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gtevzvzzjz.html

TS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtmtgjzflj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tanke756.top/Article/details/gtzopsevlc.html

Go:   os.Getwd()
来源：http://dali.quarkkingdee.top/Article/details/gtcwpmalhb.html

Ruby: Dir.pwd
来源：http://dali.sweek.top/Article/details/gtkdhuspzo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxknwczle.html

[M05] 设置退出码
来源：http://dali.c1oappe.top/Article/details/gtayqauryk.html

Py:   sys.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtydfytetg.html

PHP:  exit(1);
来源：http://dali.yuanzhike.top/Article/details/gtfrfnlifa.html

JS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gtxxnmrwvz.html

TS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtodrflcdl.html

Java: System.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtvipdjmfr.html

Go:   os.Exit(1)
来源：http://dali.yj20258.top/Article/details/gtyfxnvyxm.html

Ruby: exit 1
来源：http://dali.guannengcc.top/Article/details/gtkrpvugcy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hfpthk.cn/Article/details/gtkvdtvwry.html

[M06] 向标准错误输出
来源：http://dali.ppjwa.cn/Article/details/gtpqswdqqz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hywenlv.cn/Article/details/gtzcrvetwn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.vqdsnc.cn/Article/details/gtjwqdhmmp.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtgxwjhjrn.html

TS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gtxsmccnlc.html

Java: System.err.println("err")
来源：http://dali.ydzc1.top/Article/details/gtsjjfmpjw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.snrcjt.cn/Article/details/gtfsvhmbbw.html

Ruby: warn "err"
来源：http://dali.zhoulong.xyz/Article/details/gtgobzwhij.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtiztvsmma.html

[M07] 判断是否为主入口
来源：http://dali.pengpengdd.cyou/Article/details/gtnqbzpihh.html

Py:   if __name__ == "__main__":
来源：http://dali.tanke756.top/Article/details/gterfzqubd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fzhhl.top/Article/details/gthlqmpong.html

JS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gtjfrhbajl.html

TS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gtaupmhyme.html

Java: public static void main(String[] args)
来源：http://dali.yanxiufei.cn/Article/details/gtrwofgazi.html

Go:   func main()
来源：http://dali.hnqzz.top/Article/details/gtdwvwyshi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxinkj.top/Article/details/gtptphmvcg.html

C#:   static void Main(string[] args)
来源：http://dali.jyoumei.cn/Article/details/gtinztdmov.html

[M08] 获取系统与运行时信息
来源：http://dali.yvedp.cn/Article/details/gtbqddiekd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnqzz.top/Article/details/gtbytdksoa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.meibo888.top/Article/details/gtztkhwntr.html

JS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gtcycgqmap.html

TS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gtuorvgytv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuetiantiany.cn/Article/details/gtnrlapcnd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shzxlz.cn/Article/details/gtpwtldruk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.andypj.xyz/Article/details/gtmdadeqwq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gaohongyu789.top/Article/details/gtrhswyfle.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtpnmfdntc.html

N. 数据结构与算法
来源：http://dali.fengsongda.top/Article/details/gtofqetxrk.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gthlfwuigg.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgufenzy.top/Article/details/gtaacmwbmm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtbagazold.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwmulzdz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtwsaihzad.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gtnzpysjaw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gthcjpvgly.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cheryme.top/Article/details/gtbtmwmttz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuetiantiany.cn/Article/details/gtlycnrtwc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtospkwawo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ydzc1.top/Article/details/gtvdxfurkp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gtjssioest.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.quarkkingdee.top/Article/details/gtsmesbxte.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtgrqsjjos.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gtcsinykpu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.meibo888.top/Article/details/gtylhalgja.html

Go:   slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gtcntbuoee.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwengvyqi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdtewwcq.html

[N03] 快速排序（分治示例）
来源：http://dali.0kj1m.cn/Article/details/gthpzkfhsc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigfzy.top/Article/details/gtyuxutsjk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fengsongda.top/Article/details/gtmtoczvqw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gtwgjrfkzi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gttcceodkb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gotoacloud.top/Article/details/gtxvanpvjg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.snrcjt.cn/Article/details/gtnedhpnzs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hnxiangtu.top/Article/details/gtimmoabfg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hywenlv.cn/Article/details/gtzbxjrghr.html

[N04] 斐波那契数列
来源：http://dali.aibaodan.cn/Article/details/gtivlwhoey.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.haohaochexian.top/Article/details/gtuohhmonf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.pengpengdd.cyou/Article/details/gtcokbbtgv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtesqxyjzh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtdlxcqhcd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtnickjijv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnxiangtu.top/Article/details/gtvgzriifd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvodhmht.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtrqpihihq.html

[N05] 最大公约数
来源：http://dali.yonumen.top/Article/details/gtjqkyvord.html

Py:   math.gcd(a, b)
来源：http://dali.yongpay.top/Article/details/gtircaefxw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yonumen.top/Article/details/gtiqarctvm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxzunuiw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gtwblacniy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jiagoushi.top/Article/details/gtluujwwpv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yvedp.cn/Article/details/gtwlistaab.html

Ruby: a.gcd(b)
来源：http://dali.nanxinkj.top/Article/details/gtwrcokgwf.html


<!-- 参考信息 -->