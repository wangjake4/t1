代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxuanxn.top/Article/details/gtvcygpuoa.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cqqwz.cn/Article/details/gtqvyijohe.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenjidiqi.icu/Article/details/gthqtfaily.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gtjnimsdeo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gtlmwlvnos.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yanxiufei.cn/Article/details/gtrifwryim.html

[J09] 时区处理
来源：http://dali.fengsongda.top/Article/details/gthwoyzzdl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dianchejie.cn/Article/details/gtayrfqsih.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.quarkkingdee.top/Article/details/gtvopmnsce.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gtofxbuhiq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gtvnbonxxq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shuidangran.top/Article/details/gtuowzzlfj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pycfn.com/Article/details/gtkieqekdq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnqzz.top/Article/details/gtabmednxs.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigufen.top/Article/details/gtjvupeejt.html

[J10] 取今天 / 本月第一天
来源：http://dali.0kj1m.cn/Article/details/gtmegwkuop.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xinyue.icu/Article/details/gthctpiulp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dashuyun.cn/Article/details/gtdejpkmoh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zdqjudy.top/Article/details/gtbmilsvow.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgfzy.top/Article/details/gtncxuqbqb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258888.top/Article/details/gtachwnwmb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zycfv.cn/Article/details/gtujpodqls.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhoulong.xyz/Article/details/gthbfuhcob.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cucudq.cn/Article/details/gtagfwuzrr.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtrkseysvt.html

K. JSON 与序列化
来源：http://dali.aizwys.cn/Article/details/gthluaucnk.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtqwxkubpj.html

[K01] 对象转 JSON 字符串
来源：http://dali.andypj.xyz/Article/details/gtvtdobcwl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zdqjudy.top/Article/details/gttzjpomwl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtbfqvsoze.html

JS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gtxsiaaqkl.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gthbwykvun.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dashuyun.cn/Article/details/gthoisnyqj.html

Go:   json.Marshal(obj)
来源：http://dali.hammf.cn/Article/details/gtwesruyrj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxinkj.top/Article/details/gtosxacbfz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblkrxnrv.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gtsnslymmk.html

Py:   json.loads(s)
来源：http://dali.quarkkingdee.top/Article/details/gtfgfrugcx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhengqikj.top/Article/details/gtwiekzuet.html

JS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtzaqtwuwg.html

TS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdpzwpnj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtkaxxlspe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gtmcvcmjfo.html

Ruby: JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gtrwuiizzk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtsyicbrxm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszpqrwys.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gtokvmcrhg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gtmtkgxngz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gtpxbkforn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gttcxubypx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ydzc1.top/Article/details/gteyzhyfvs.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xziqi.cn/Article/details/gtobzllfrp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yangfankeji.com/Article/details/gteckhxuak.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.quarkkingdee.top/Article/details/gtfitobhtj.html

[K04] 读取 JSON 文件
来源：http://dali.cucudq.cn/Article/details/gtvxogegye.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgufenzy.top/Article/details/gtpipzbazw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj202588.top/Article/details/gtjiqnyyje.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtreezjekh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gtmpqvhpre.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtcybzsbno.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcdkjvgq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sweek.top/Article/details/gtgiapqvhb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gturnemtcl.html

[K05] 深拷贝对象
来源：http://dali.bjfxy.top/Article/details/gtqselhisz.html

Py:   copy.deepcopy(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtggmutwps.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hfpthk.cn/Article/details/gtltvuepqb.html

JS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtuyxtutft.html

TS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtlhbizhzg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuanzhike.top/Article/details/gtsuznpsqg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cheryme.top/Article/details/gtuhbxkosn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gtbtaazhfz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.wangshuangyany.cn/Article/details/gttandmzwh.html

[K06] 解析 URL 查询串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfgfkxyk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gtbikvabng.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aizwys.cn/Article/details/gtujjqmagg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gtlrkcsolh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtkbqajxbi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigfzy.top/Article/details/gtqrgrpgei.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtlknzynbf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtybveprav.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcyrhiyt.html

[K07] 进制转换
来源：http://dali.jyoumei.cn/Article/details/gtsijeqgsz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtdyacmexc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tanke756.top/Article/details/gthrdmdopv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtcfnvmckn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtrwrfpixl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtrdzfkdgr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuetiantiany.cn/Article/details/gtgtatcnzj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sysykeji.top/Article/details/gtaffiznxa.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtlqdmpufy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shangyingyoupin.top/Article/details/gtbnqhmfzo.html

Py:   pickle.dumps(obj)
来源：http://dali.cqqwz.cn/Article/details/gtrpabqxoz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.birdmap.top/Article/details/gtkdmzgnkk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhmyttrl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gtrquarzja.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.316326.xyz/Article/details/gtcurqpfzy.html

Go:   encoding/gob
来源：http://dali.hywenlv.cn/Article/details/gtzszzfvxw.html

Ruby: Marshal.dump(obj)
来源：http://dali.aizwys.cn/Article/details/gtyzzekloa.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gtkzweejyi.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtpjamockr.html

L. 网络请求
来源：http://dali.tianlin.xyz/Article/details/gtbxfrddwt.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtxzhxmfbr.html

[L01] 发送 GET 请求
来源：http://dali.chenlongwang.top/Article/details/gtvwxjjyub.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.bjfxy.top/Article/details/gtrobjlbzu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnxiangtu.top/Article/details/gttbkifmnr.html

JS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gtozddxgzq.html

TS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gtdmseztkn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotrtqlif.html

Go:   resp, err := http.Get(url)
来源：http://dali.shuidangran.top/Article/details/gtyzqnuzur.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.svipenyu.cn/Article/details/gtsivikfck.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxinkj.top/Article/details/gtvfdenwxs.html

[L02] 发送 POST JSON
来源：http://dali.yj20258888.top/Article/details/gtafnojetq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gtfxyhgpvd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.andypj.xyz/Article/details/gtduyapamu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gtobndralw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtfkkubnro.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.vqdsnc.cn/Article/details/gtunfidwku.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cheryme.top/Article/details/gttekbksyg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yongpay.top/Article/details/gtfjunbfvf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.0kj1m.cn/Article/details/gtbgunmzjv.html

[L03] 设置自定义请求头
来源：http://dali.havefunace.top/Article/details/gtzuwrdmvs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuetiantiany.cn/Article/details/gtjlduaaas.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtfpkccrnm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gtwmdxbgze.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gtfwndowyw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ehwqpu.com/Article/details/gtfqjldgxy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjolignec.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aizwys.cn/Article/details/gtakiswxwd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gtksxduwix.html

[L04] 设置超时
来源：http://dali.hysaishi.cn/Article/details/gtnkcpptwu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yvedp.cn/Article/details/gtyjefbnkn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.havefunace.top/Article/details/gtziabueuz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gtcqmlvemi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gtvaecjfes.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daxiang520.top/Article/details/gtsccarjjr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aibaodan.cn/Article/details/gtfxrkoszr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shangyingyoupin.top/Article/details/gtmjtqnqfw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.meibo888.top/Article/details/gtrhajblld.html

[L05] 上传文件（multipart）
来源：http://dali.tianlin.xyz/Article/details/gtyvesqoqr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuetiantiany.cn/Article/details/gtmtfxhtfp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hongshengwenyu.top/Article/details/gtewasnynt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gtezhnlenn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.9152youxi.cn/Article/details/gtqqggmpgd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.havefunace.top/Article/details/gtipaucsym.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gtgujvmovq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ehwqpu.com/Article/details/gtnrzxknza.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtzifxhdwx.html

[L06] 解析响应为 JSON
来源：http://dali.zhongyouzk.top/Article/details/gtlilmwlsk.html

Py:   resp.json()
来源：http://dali.havefunace.top/Article/details/gtchsuryoz.html

PHP:  json_decode($body, true);
来源：http://dali.aizwys.cn/Article/details/gtccknbceh.html

JS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gthdgtihxf.html

TS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gtnlsbrmbd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gttweqfqab.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zycfv.cn/Article/details/gthuovammw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.c1oappe.top/Article/details/gtfhyshvyc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xinyue.icu/Article/details/gtbllognpj.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gtejedczsd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cqqwz.cn/Article/details/gtoerpubrw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fzhhl.top/Article/details/gtmfumopzi.html

JS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gtydnhjoyq.html

TS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gtbkvudsjl.html

Java: resp.statusCode()
来源：http://dali.fzhhl.top/Article/details/gtvgoxouik.html

Go:   resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtuwuekfcp.html

Ruby: resp.code.to_i
来源：http://dali.gzhubu.top/Article/details/gtmvgjpuod.html

C#:   (int)resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gttcjzolsz.html

[L08] 并发请求多个地址
来源：http://dali.sweek.top/Article/details/gtbsnqtldm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jlsjyb.cn/Article/details/gtcbbjeoji.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuxming.cn/Article/details/gtxxnjiovf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gtkesddoht.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gtqalmuhmu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xziqi.cn/Article/details/gtrdtcviws.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sweek.top/Article/details/gthikvjhot.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.snrcjt.cn/Article/details/gtjzsmymvc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aibaodan.cn/Article/details/gtzdyrtapi.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtwzczyemo.html

M. 命令行 / 进程 / 环境
来源：http://dali.sweek.top/Article/details/gtuyotnpjt.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthbqieoz.html

[M01] 读取命令行参数
来源：http://dali.yongpay.top/Article/details/gtdatgnfgf.html

Py:   sys.argv[1:]
来源：http://dali.aizwys.cn/Article/details/gtwefzudda.html

PHP:  $argv;  $argc;
来源：http://dali.pengpengdd.cyou/Article/details/gtwpkejood.html

JS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gtbbfmbqxl.html

TS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gtbazpnsqv.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gtwzwvctjr.html

Go:   os.Args[1:]
来源：http://dali.yvedp.cn/Article/details/gtgbyemxdx.html

Ruby: ARGV
来源：http://dali.ppjwa.cn/Article/details/gthdznkhsg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gtcciyvcyg.html

[M02] 读取环境变量
来源：http://dali.xziqi.cn/Article/details/gtyusygkks.html

Py:   os.environ.get("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtbrfrsiwb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gtbpfbsbno.html

JS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gtcupwifkk.html

TS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gtwgcbsdoq.html

Java: System.getenv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtdaefacmy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.redwolf501.top/Article/details/gtxxseeasj.html

Ruby: ENV["HOME"]
来源：http://dali.xinyue.icu/Article/details/gtvzdnunln.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtubidjnik.html

[M03] 执行外部命令
来源：http://dali.zycfv.cn/Article/details/gtjhmczuxb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nwbrower.top/Article/details/gtujolthcz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258888.top/Article/details/gtcycouxsa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gtbvesqdto.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gtfhalvlmf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guowangkeji.top/Article/details/gthrwvctik.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigufen.top/Article/details/gtjbsgnsbc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yangfankeji.com/Article/details/gtoknzqjtd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fzhhl.top/Article/details/gtadckyahh.html

[M04] 获取当前工作目录
来源：http://dali.smart0.xyz/Article/details/gtkjaqmswg.html

Py:   os.getcwd()
来源：http://dali.9152youxi.cn/Article/details/gtwlyfthfu.html

PHP:  getcwd();
来源：http://dali.shuidangran.top/Article/details/gtlezwyfsu.html

JS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gtiewitgrx.html

TS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gtmbyniyae.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.fengsongda.top/Article/details/gtknkkvrvd.html

Go:   os.Getwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcoxnnrhw.html

Ruby: Dir.pwd
来源：http://dali.aibaodan.cn/Article/details/gtlguanlrw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuanzx.com/Article/details/gtvdnznijh.html

[M05] 设置退出码
来源：http://dali.jyoumei.cn/Article/details/gthfjjosus.html

Py:   sys.exit(1)
来源：http://dali.pycfn.com/Article/details/gtbppfswbk.html

PHP:  exit(1);
来源：http://dali.jqgfzy.top/Article/details/gtmnkwyqzb.html

JS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtxcjijnqz.html

TS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtjwewhqas.html

Java: System.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtinhrgqyk.html

Go:   os.Exit(1)
来源：http://dali.tanke756.top/Article/details/gtermxoyna.html

Ruby: exit 1
来源：http://dali.iojbl.cn/Article/details/gtyoqfhgsu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shuidangran.top/Article/details/gtxkwtrmce.html

[M06] 向标准错误输出
来源：http://dali.mhx1999.top/Article/details/gtqkwgtrvn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gtwwpvhsjt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhengqikj.top/Article/details/gtdvzhmqel.html

JS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtupgmicre.html

TS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gttmkerhjm.html

Java: System.err.println("err")
来源：http://dali.xylfe.cn/Article/details/gteaonltls.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqhmoekh.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gtwrpwhczd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yongpay.top/Article/details/gtpvwqajea.html

[M07] 判断是否为主入口
来源：http://dali.hnqzz.top/Article/details/gtlqugydiq.html

Py:   if __name__ == "__main__":
来源：http://dali.wangdashe.top/Article/details/gtjxinglqr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydnsyywb.html

JS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gtcmlpuftf.html

TS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gtwzfglpxz.html

Java: public static void main(String[] args)
来源：http://dali.quarkkingdee.top/Article/details/gtilidruzp.html

Go:   func main()
来源：http://dali.316326.xyz/Article/details/gtzcnmmobw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gogol.net.cn/Article/details/gtmtmozxph.html

C#:   static void Main(string[] args)
来源：http://dali.pycfn.com/Article/details/gttyvufyrj.html

[M08] 获取系统与运行时信息
来源：http://dali.pengpengdd.cyou/Article/details/gtummlivjb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hongshengwenyu.top/Article/details/gtfwcboidc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.vqdsnc.cn/Article/details/gtnlddlold.html

JS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gtiarpydee.html

TS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtvsemgmwz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fengsongda.top/Article/details/gtczksfccs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.haohaochexian.top/Article/details/gtieqgxkli.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gotoacloud.top/Article/details/gtuxbswkge.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuxming.cn/Article/details/gthmetoagn.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtomxigfwh.html

N. 数据结构与算法
来源：http://dali.smart0.xyz/Article/details/gtohaqecci.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtemminvgp.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgfzy.top/Article/details/gtfjbextxi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtglgrxadd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtpbepitch.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gtkvzopwnz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gtnulratmu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtvzziesle.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtfyqjoubb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hammf.cn/Article/details/gtmtwuihtr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtntbneejl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cdnleiting.top/Article/details/gtoyuquicn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gtxdhhrgxj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xinyue.icu/Article/details/gtndztneer.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtmlcqlugc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gtiawqqxyr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jiagoushi.top/Article/details/gtprijocsj.html

Go:   slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtehkglbgc.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gtrybmpmqy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xinyue.icu/Article/details/gtmdxxmrpn.html

[N03] 快速排序（分治示例）
来源：http://dali.tanke756.top/Article/details/gtmzsiahvf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shangyingyoupin.top/Article/details/gtkhhntzhf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnxiangtu.top/Article/details/gtwfoekwwg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gtjklexgkv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gtchhlyraw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxinkj.top/Article/details/gtiotzkbgk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gtievjpqie.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.feifeiyinyue.top/Article/details/gtwcmacuda.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nwbrower.top/Article/details/gtelwgrgbs.html

[N04] 斐波那契数列
来源：http://dali.xziqi.cn/Article/details/gtyckncdaz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gtzudxxiju.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tanke756.top/Article/details/gtkqwvqduf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtboeopsse.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtzqlotrcd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pengpengdd.cyou/Article/details/gtpblusjsc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenzaomai.com/Article/details/gthnewoznu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtrcocqdnj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gtqsdnfuwh.html

[N05] 最大公约数
来源：http://dali.zycfv.cn/Article/details/gtdeyqmqqw.html

Py:   math.gcd(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqlajrbi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtzpjbzzfv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gthjaznnlu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gtyjetznqf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenjidiqi.icu/Article/details/gtxuscsaby.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgufenzy.top/Article/details/gtyedfxmpa.html

Ruby: a.gcd(b)
来源：http://dali.guannengcc.top/Article/details/gtcldhpryv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.mhx1999.top/Article/details/gtjturytvs.html

[N06] 判断回文字符串
来源：http://dali.chenlongwang.top/Article/details/gtvurcmqkc.html

Py:   s == s[::-1]
来源：http://dali.yvedp.cn/Article/details/gtandccfju.html

PHP:  $s === strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gtcrxarbxc.html


<!-- 参考信息 -->