代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ehwqpu.com/Article/details/gtqoolmlmc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hammf.cn/Article/details/gtvhrnjrfp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258888.top/Article/details/gtsxcaktsl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yueranfly.top/Article/details/gtcbgcrdcp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shzxlz.cn/Article/details/gtndicttdi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gotoacloud.top/Article/details/gtqfwfnxpe.html

[J09] 时区处理
来源：http://dali.sxryk.cn/Article/details/gtgsbeuiox.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.iojbl.cn/Article/details/gtkimyujhp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gaohongyu789.top/Article/details/gthazmkrla.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gtnurkyfug.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gtxubmgskj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.redwolf501.top/Article/details/gtcezhanir.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xinyue.icu/Article/details/gtosqsgpae.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgajjcbh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ppjwa.cn/Article/details/gtqtusitvs.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwscvyqsc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dashuyun.cn/Article/details/gthufrrrsj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.quarkkingdee.top/Article/details/gtkqafavwl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aizwys.cn/Article/details/gtunxeuxcx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hywenlv.cn/Article/details/gtjooquxrn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gotoacloud.top/Article/details/gtmywyrmvg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cqqwz.cn/Article/details/gtzrpvhayw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daria6918.cn/Article/details/gtcxbnrteg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.bjfxy.top/Article/details/gtnbrqpksu.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtfjypvgdf.html

K. JSON 与序列化
来源：http://dali.zycfv.cn/Article/details/gthlueeemi.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtimbrwmse.html

[K01] 对象转 JSON 字符串
来源：http://dali.tianlin.xyz/Article/details/gtxhygbplt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgeixodux.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtwvyflool.html

JS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gtgclxyfng.html

TS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtwekqkwuj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenzaomai.com/Article/details/gtydoxfwxc.html

Go:   json.Marshal(obj)
来源：http://dali.birdmap.top/Article/details/gtnhnzzwvq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.iojbl.cn/Article/details/gttwnhzxdg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.c1oappe.top/Article/details/gtmgzcholy.html

[K02] JSON 字符串转对象
来源：http://dali.316326.xyz/Article/details/gtrclhzaai.html

Py:   json.loads(s)
来源：http://dali.chenzaomai.com/Article/details/gtohkgmsid.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.birdmap.top/Article/details/gthjpnlbnm.html

JS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtizselsxx.html

TS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtalemjztj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtilzlnuxp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gtggrbvvpy.html

Ruby: JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gtgctwabhp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj202588.top/Article/details/gtrzvoffdj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yangfankeji.com/Article/details/gtlwpptvma.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxngtgrpa.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gtdziznauz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtsccwycka.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvzybeam.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cqqwz.cn/Article/details/gtnnlasoze.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmroauaor.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shuidangran.top/Article/details/gtdhegblpn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hammf.cn/Article/details/gtfkmilccq.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gtzhhpwymo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sufxvd.cn/Article/details/gtzuqpsfqm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guannengcc.top/Article/details/gttojiwtqp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gtitxshiqt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gtajwtscgn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hammf.cn/Article/details/gtifokpkdr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gtzburzosn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gtdzwyjrqm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtwwkmwgsm.html

[K05] 深拷贝对象
来源：http://dali.cheryme.top/Article/details/gtzlbpencm.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxinkj.top/Article/details/gtcblqwris.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangshuangyany.cn/Article/details/gtaavegxnu.html

JS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtwvvumsbz.html

TS:   structuredClone(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtdcatqsry.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aizwys.cn/Article/details/gtjugithqb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigufen.top/Article/details/gtumiuqmci.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sufxvd.cn/Article/details/gtpbwydqca.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yangfankeji.com/Article/details/gtcrczygdv.html

[K06] 解析 URL 查询串
来源：http://dali.iojbl.cn/Article/details/gtztogxwrq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pycfn.com/Article/details/gtyqblojfh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guannengcc.top/Article/details/gtvvyewncn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gtdwnltvoi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gthbnsswxl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yanxiufei.cn/Article/details/gtjnxurlao.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gttblwhkhz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gtcqzinvig.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtvewuufqg.html

[K07] 进制转换
来源：http://dali.cashguo.top/Article/details/gtqcvjjlaj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtvmqfbphh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gtztcffbfm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtkyrlxurc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtqlixhrlt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtuqxynyne.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gtsmebacol.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dianchejie.cn/Article/details/gtvvzyolwt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtygfhhbso.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dashuyun.cn/Article/details/gtzbmfikda.html

Py:   pickle.dumps(obj)
来源：http://dali.hnqzz.top/Article/details/gtnoleiyrs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtoauchmho.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.smart0.xyz/Article/details/gtdxvdjfcn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gtozbsrqey.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.bjfxy.top/Article/details/gtfaioqprw.html

Go:   encoding/gob
来源：http://dali.yvedp.cn/Article/details/gtcrybbvul.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtriggvlov.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gtllbngzdh.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtwjgbxafg.html

L. 网络请求
来源：http://dali.zdqjudy.top/Article/details/gtrybxrkpe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtnvigagvp.html

[L01] 发送 GET 请求
来源：http://dali.havefunace.top/Article/details/gtlnbmgfop.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dashuyun.cn/Article/details/gtplqywdqp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pengpengdd.cyou/Article/details/gtmsbyinzg.html

JS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gtxeidmodh.html

TS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gtyqegvbbb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guannengcc.top/Article/details/gtaosgkuer.html

Go:   resp, err := http.Get(url)
来源：http://dali.yueranfly.top/Article/details/gtgsbgykzv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zdqjudy.top/Article/details/gtvujasgwo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yongpay.top/Article/details/gtcdgmejou.html

[L02] 发送 POST JSON
来源：http://dali.xuanzx.com/Article/details/gtryiygfzw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shuidangran.top/Article/details/gttaxihbsg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cashguo.top/Article/details/gtylcbjdis.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gtudrxttit.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gtgmtnqdvy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenlongwang.top/Article/details/gtoipdnpwn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.havefunace.top/Article/details/gtelvxaziu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dashuyun.cn/Article/details/gtshlkidyt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovtrhxsl.html

[L03] 设置自定义请求头
来源：http://dali.wangshuangyany.cn/Article/details/gtmeelzmta.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gotoacloud.top/Article/details/gtkvqmoiek.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ybcxt.top/Article/details/gtqabcykag.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gtvkcnfqon.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtuhorpyzk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258.top/Article/details/gtonfaxgfe.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgpjtqek.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinqigfzy.top/Article/details/gtnnnclqup.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gtlmjcsxqy.html

[L04] 设置超时
来源：http://dali.ppjwa.cn/Article/details/gtqegbjcxe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.snrcjt.cn/Article/details/gthqaqlotz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuxming.cn/Article/details/gtlklfynrk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gtrrovyptx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gtrctiakix.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqjxnyou.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangshuangyany.cn/Article/details/gtwkqegyag.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hammf.cn/Article/details/gtkhnakyrs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangshuangyany.cn/Article/details/gtvqwlhcvm.html

[L05] 上传文件（multipart）
来源：http://dali.hongshengwenyu.top/Article/details/gtywjqunqq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fengsongda.top/Article/details/gtyktcxkdm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zdqjudy.top/Article/details/gtxqqybdig.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gtjafasmmh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgfzy.top/Article/details/gtbhzthpun.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gotoacloud.top/Article/details/gtqrzljbxz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.0kj1m.cn/Article/details/gtfqnmocwb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.redwolf501.top/Article/details/gtrwkmyrjl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtlbetydhz.html

[L06] 解析响应为 JSON
来源：http://dali.bjfxy.top/Article/details/gthptmdjma.html

Py:   resp.json()
来源：http://dali.yonumen.top/Article/details/gtjktofyud.html

PHP:  json_decode($body, true);
来源：http://dali.sufxvd.cn/Article/details/gtumvdejgy.html

JS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtxeipymrf.html

TS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gtrebowetu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tian-w.cn/Article/details/gtncousglw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cashguo.top/Article/details/gtgepefvwd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.guowangkeji.top/Article/details/gtrkcgtiru.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tianlin.xyz/Article/details/gtppmsfysu.html

[L07] 处理 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gtcxrhtpnk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.smart0.xyz/Article/details/gtknqvinbn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jiagoushi.top/Article/details/gtahtmhoaw.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhzkrnyx.html

TS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtkedbqonw.html

Java: resp.statusCode()
来源：http://dali.c1oappe.top/Article/details/gtzylqxexa.html

Go:   resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gtmcexyqmm.html

Ruby: resp.code.to_i
来源：http://dali.yvedp.cn/Article/details/gttcxdanej.html

C#:   (int)resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtuqjdqhwl.html

[L08] 并发请求多个地址
来源：http://dali.dianchejie.cn/Article/details/gttnsymoub.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gtchuqbilg.html

PHP:  curl_multi_init() 系列
来源：http://dali.pengpengdd.cyou/Article/details/gtpotiaoqw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gthgbohuah.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtlndhgemz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hywenlv.cn/Article/details/gtdsvbnfgl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.redwolf501.top/Article/details/gtnwraxdin.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gtnmpqclqk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.316326.xyz/Article/details/gtiqkhuhlv.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtmywfibbo.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenjidiqi.icu/Article/details/gtbawvkkfk.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtbsglxfer.html

[M01] 读取命令行参数
来源：http://dali.zycfv.cn/Article/details/gtwqujdupv.html

Py:   sys.argv[1:]
来源：http://dali.tian-w.cn/Article/details/gtkmnqodrw.html

PHP:  $argv;  $argc;
来源：http://dali.316326.xyz/Article/details/gtlyihzxse.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebjveqzd.html

TS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gtembraxfi.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtbjeojejt.html

Go:   os.Args[1:]
来源：http://dali.bjfxy.top/Article/details/gtymtyibft.html

Ruby: ARGV
来源：http://dali.yj20258888.top/Article/details/gtltgdrxhs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gtjbnxjtbs.html

[M02] 读取环境变量
来源：http://dali.cheryme.top/Article/details/gtsuutchgd.html

Py:   os.environ.get("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtjeunzavw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cashguo.top/Article/details/gtwtwihnpu.html

JS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gtafqofyrl.html

TS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gtuydkjsjk.html

Java: System.getenv("HOME")
来源：http://dali.xziqi.cn/Article/details/gttgjudqdi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtdwryoouj.html

Ruby: ENV["HOME"]
来源：http://dali.chenlongwang.top/Article/details/gtnqodwjwn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.andypj.xyz/Article/details/gttcglzlxp.html

[M03] 执行外部命令
来源：http://dali.havefunace.top/Article/details/gtntecweds.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.redwolf501.top/Article/details/gtzjgzczte.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gaohongyu789.top/Article/details/gtyubmdfub.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtourejiyg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtmstlpcgy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.bjfxy.top/Article/details/gtxwsxamob.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.havefunace.top/Article/details/gtcjeoivpz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnxiangtu.top/Article/details/gtmcnsbblk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xziqi.cn/Article/details/gtftzxikhm.html

[M04] 获取当前工作目录
来源：http://dali.xylfe.cn/Article/details/gtaebpnmkd.html

Py:   os.getcwd()
来源：http://dali.cucudq.cn/Article/details/gtymeudxzo.html

PHP:  getcwd();
来源：http://dali.pycfn.com/Article/details/gtpoxxklln.html

JS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gtdrwaslpz.html

TS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gtrduhjvhw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhengqikj.top/Article/details/gtqzpgxupn.html

Go:   os.Getwd()
来源：http://dali.nanxuanxn.top/Article/details/gtcmlpnpmf.html

Ruby: Dir.pwd
来源：http://dali.hongshengwenyu.top/Article/details/gtgcfhdhpv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gtgnapvjas.html

[M05] 设置退出码
来源：http://dali.tianlin.xyz/Article/details/gthrwjlvwk.html

Py:   sys.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtjragazrg.html

PHP:  exit(1);
来源：http://dali.aizwys.cn/Article/details/gtratfxnbz.html

JS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtnrfogoav.html

TS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtkkirxfms.html

Java: System.exit(1)
来源：http://dali.sweek.top/Article/details/gtxqnmzwxl.html

Go:   os.Exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtozknbnyz.html

Ruby: exit 1
来源：http://dali.gogol.net.cn/Article/details/gtcrwybrju.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnikmzyx.html

[M06] 向标准错误输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkooidjiq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gtwvvamfux.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.meibo888.top/Article/details/gtpmewhmpx.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gtudhsmmwf.html

TS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtwreivsdv.html

Java: System.err.println("err")
来源：http://dali.nanxuanxn.top/Article/details/gtxjdlkocr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangshuangyany.cn/Article/details/gtmrzyxspd.html

Ruby: warn "err"
来源：http://dali.fengsongda.top/Article/details/gtlqwouhej.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fzhhl.top/Article/details/gtrpvfyssc.html

[M07] 判断是否为主入口
来源：http://dali.fzhhl.top/Article/details/gtosdphrlr.html

Py:   if __name__ == "__main__":
来源：http://dali.quarkkingdee.top/Article/details/gtkhouqesw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuxming.cn/Article/details/gtomiaebrn.html

JS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gtraixhbnh.html

TS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gtiqlvcdnx.html

Java: public static void main(String[] args)
来源：http://dali.jyoumei.cn/Article/details/gtmgawlfeu.html

Go:   func main()
来源：http://dali.hammf.cn/Article/details/gttjvgfxax.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenzaomai.com/Article/details/gtrafgsltr.html

C#:   static void Main(string[] args)
来源：http://dali.hywenlv.cn/Article/details/gtqkqbehhu.html

[M08] 获取系统与运行时信息
来源：http://dali.cucudq.cn/Article/details/gtmvmzsnft.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrmrzkbn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shzxlz.cn/Article/details/gtzwvnkvtv.html

JS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtfhgnbjzp.html

TS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gtlmrrbzpt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nwbrower.top/Article/details/gtyzoycacf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jiagoushi.top/Article/details/gtnvzwosxe.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuanzhike.top/Article/details/gtvmbqlxlm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhixingplan.top/Article/details/gtkxoexmus.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtgswwxkqy.html

N. 数据结构与算法
来源：http://dali.9152youxi.cn/Article/details/gtfiavavpj.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtxjvseilb.html

[N01] 二分查找（有序数组）
来源：http://dali.vqdsnc.cn/Article/details/gtbmnpljgr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtsjhblgjd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuxming.cn/Article/details/gtnxmphbgr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gttwcpddwq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtmlgiejbk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtlklcdgeg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtojshqfpj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hywenlv.cn/Article/details/gtncxjuyvn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtprzuirti.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenjidiqi.icu/Article/details/gtkzzlztjh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yueranfly.top/Article/details/gtrnxdqfnf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnxfaeea.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtwkpbtjyb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtwlpxgtht.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxinkj.top/Article/details/gtzrzrdziv.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtxvccberc.html

Ruby: arr.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdujcvnur.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenzaomai.com/Article/details/gtpcndqavo.html

[N03] 快速排序（分治示例）
来源：http://dali.hnqzz.top/Article/details/gtagkrhndl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgufenzy.top/Article/details/gtdmbfzcpd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hywenlv.cn/Article/details/gttqxpnijv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gtiwleuvte.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtlyjjuicz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj202588.top/Article/details/gtaogvnbrb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shuidangran.top/Article/details/gtbjqvneza.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.9152youxi.cn/Article/details/gtasruaewn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhixingplan.top/Article/details/gttsmuqufp.html

[N04] 斐波那契数列
来源：http://dali.jinqigfzy.top/Article/details/gtvqjindal.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gtrxwpauuh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gtwcxlwgbs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gtjyjhqfkn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtoihiwqbi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gtdmatdnif.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jianghu66.top/Article/details/gtljisxqve.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gttdigpcth.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtdsrqeiro.html

[N05] 最大公约数
来源：http://dali.ppjwa.cn/Article/details/gtbyjlwhhx.html

Py:   math.gcd(a, b)
来源：http://dali.wangdashe.top/Article/details/gttbfsbdzl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenzaomai.com/Article/details/gtedmeqggp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gtvpwsybnx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gtsuqnfbuj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cashguo.top/Article/details/gtecsstxgd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.c1oappe.top/Article/details/gtbtozeioy.html

Ruby: a.gcd(b)
来源：http://dali.jinqigufen.top/Article/details/gtzeyveeed.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gtaimqdvuk.html

[N06] 判断回文字符串
来源：http://dali.zhoulong.xyz/Article/details/gtqqqtsdcv.html

Py:   s == s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gtgtauywbr.html

PHP:  $s === strrev($s);
来源：http://dali.hnqzz.top/Article/details/gtzuolesjm.html


<!-- 参考信息 -->