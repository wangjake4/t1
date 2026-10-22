代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhsloqty.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.andypj.xyz/Article/details/gtbwwmesat.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yueranfly.top/Article/details/gtsvuhvhjl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ehwqpu.com/Article/details/gtsxtlhuym.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuanzhike.top/Article/details/gtlhdsrbqn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgfzy.top/Article/details/gtahfevmhv.html

[J09] 时区处理
来源：http://dali.fengsongda.top/Article/details/gtgztopgnu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gtklnzpfmr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigfzy.top/Article/details/gtfqooshmo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gtcybcewxh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gtsszttlpe.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jianghu66.top/Article/details/gtrtiswrbm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuxming.cn/Article/details/gtrdlwetpw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shuidangran.top/Article/details/gtdinatgfi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hammf.cn/Article/details/gtgrkokzyd.html

[J10] 取今天 / 本月第一天
来源：http://dali.daxiang520.top/Article/details/gtbcsyhyth.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cheryme.top/Article/details/gtbcpxyspm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jianghu66.top/Article/details/gtgxnzbgfn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.316326.xyz/Article/details/gtqfbwvgig.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenzaomai.com/Article/details/gtcmhprpik.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guowangkeji.top/Article/details/gthdlshyrq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ybcxt.top/Article/details/gtqkwiuojj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigufen.top/Article/details/gtjfelhauf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yonumen.top/Article/details/gtdhnpuonk.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gteaofbfmc.html

K. JSON 与序列化
来源：http://dali.snrcjt.cn/Article/details/gtpqyyphtu.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtnpyflfgj.html

[K01] 对象转 JSON 字符串
来源：http://dali.yanxiufei.cn/Article/details/gtzxqqfpre.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gtbwoujgzu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gthccscvrf.html

JS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gtuvswgtwl.html

TS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtvqjppuqr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gogol.net.cn/Article/details/gtxenwvjsj.html

Go:   json.Marshal(obj)
来源：http://dali.ivvv.top/Article/details/gtpfwgsyxb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhixingplan.top/Article/details/gtknvxsuov.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.c1oappe.top/Article/details/gtfzwwluzk.html

[K02] JSON 字符串转对象
来源：http://dali.guannengcc.top/Article/details/gttqkmumnw.html

Py:   json.loads(s)
来源：http://dali.9152youxi.cn/Article/details/gtzjbfmjga.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nwbrower.top/Article/details/gtiwgmjfzy.html

JS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gtvyzrlsvr.html

TS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxziapvb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gtmfbxhzuq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gtozlrgvnj.html

Ruby: JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtgnnwuxwh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.iojbl.cn/Article/details/gtzfuytfsk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ydzc1.top/Article/details/gtzdxfopyw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimbggxcl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gtzwjgmrev.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gtotxfkxaw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gtlriddglu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dianchejie.cn/Article/details/gttllwewdd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yvedp.cn/Article/details/gthbdexpdf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zdqjudy.top/Article/details/gtoujvahhz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenlongwang.top/Article/details/gtpzxlvcph.html

[K04] 读取 JSON 文件
来源：http://dali.daxiang520.top/Article/details/gtudyzicxy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.0kj1m.cn/Article/details/gtynrtsatd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ivvv.top/Article/details/gtnvpxusil.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gtjynjklcr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gtxrkilsrl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gttvmuvcmx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltgexoii.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gtpmkshqdb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuwakpon.html

[K05] 深拷贝对象
来源：http://dali.xuetiantiany.cn/Article/details/gtguolrlev.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxinkj.top/Article/details/gtxzpyqvwu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.kuanghao11.cn/Article/details/gtbcdltqxp.html

JS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtojfdqjat.html

TS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtzxjobaue.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenzaomai.com/Article/details/gtzcccmebh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gtgxnazpuo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zdqjudy.top/Article/details/gtwppnzlnm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daria6918.cn/Article/details/gteqehwaxb.html

[K06] 解析 URL 查询串
来源：http://dali.sweek.top/Article/details/gtirayqsyr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuxming.cn/Article/details/gtfrzvdwyz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigufen.top/Article/details/gtucmlmsze.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gtnhmhtixs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gtprcljjwp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sxryk.cn/Article/details/gtnsfagvht.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gttdorywtq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtrxfhbzsx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gthjxlpqit.html

[K07] 进制转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwybrlejj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtxvgjledw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sweek.top/Article/details/gtsrflwdbq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtzqdggrer.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtgetdkadn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtgdfmwmew.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.bjfxy.top/Article/details/gtsisjqznq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dashuyun.cn/Article/details/gtkwgqdggj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtgdtcquof.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtksjqoqds.html

Py:   pickle.dumps(obj)
来源：http://dali.zycfv.cn/Article/details/gtbszgkdbb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yongpay.top/Article/details/gtmmrfhlfj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gtywgvhssr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gtrwyuivlk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yonumen.top/Article/details/gtlzxjsrsl.html

Go:   encoding/gob
来源：http://dali.redwolf501.top/Article/details/gtuxiaghmg.html

Ruby: Marshal.dump(obj)
来源：http://dali.cashguo.top/Article/details/gtvmjddwvn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pycfn.com/Article/details/gtfwgmqibf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtxrmwckjq.html

L. 网络请求
来源：http://dali.zycfv.cn/Article/details/gtxwiylxhp.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtjwohxtwr.html

[L01] 发送 GET 请求
来源：http://dali.yonumen.top/Article/details/gtbuvkfauz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yangfankeji.com/Article/details/gteypnczsm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shangyingyoupin.top/Article/details/gthiibmbkh.html

JS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gtnujwzkyt.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctjwjfjf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guannengcc.top/Article/details/gtnudzhscx.html

Go:   resp, err := http.Get(url)
来源：http://dali.kuanghao11.cn/Article/details/gthyfyogle.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fzhhl.top/Article/details/gtdvesknjc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtebnzftmd.html

[L02] 发送 POST JSON
来源：http://dali.yonumen.top/Article/details/gtwswhbjqt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gtrgwnqlwj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sysykeji.top/Article/details/gtlzqqpasw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenjidiqi.icu/Article/details/gtlrkrgtbw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gtwpgmtbgs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gtvnirgvop.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfywdftco.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dashuyun.cn/Article/details/gtuydgsgmt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yangfankeji.com/Article/details/gtaynmykdc.html

[L03] 设置自定义请求头
来源：http://dali.shuidangran.top/Article/details/gtuulbngnj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigufen.top/Article/details/gtfsgnxdju.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pycfn.com/Article/details/gtscqmlvzn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gtiikyukby.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gtcrwogett.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.havefunace.top/Article/details/gtufdyosef.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpudhdmqa.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ehwqpu.com/Article/details/gtatwwgywf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gtydfebljn.html

[L04] 设置超时
来源：http://dali.zycfv.cn/Article/details/gthfqgrgdp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ivvv.top/Article/details/gtxjvxtgbq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxinkj.top/Article/details/gtrrroyvmr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gtihwaqows.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gtttisoege.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gttmdlicoi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jiagoushi.top/Article/details/gtrdfdqqvr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxuanxn.top/Article/details/gtqefydnwe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhfnfuls.html

[L05] 上传文件（multipart）
来源：http://dali.vqdsnc.cn/Article/details/gtyaljtird.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.c1oappe.top/Article/details/gtvvqdybfp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenjidiqi.icu/Article/details/gtqhwbwyzs.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gtsixrqseq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gtgfaewwqq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gtwiplewia.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hywenlv.cn/Article/details/gtisaeyahg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yongpay.top/Article/details/gtuyworjtv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sweek.top/Article/details/gtgkzhhtga.html

[L06] 解析响应为 JSON
来源：http://dali.hfpthk.cn/Article/details/gthhdbbuqs.html

Py:   resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtavctjars.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxmjuorl.html

JS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtsbyttdja.html

TS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gteijqochm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtgsepetri.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yanxiufei.cn/Article/details/gtjngfbvmt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ivvv.top/Article/details/gtctqplchz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xinyue.icu/Article/details/gtjxzztlqf.html

[L07] 处理 HTTP 状态码
来源：http://dali.sufxvd.cn/Article/details/gtdqtsvixs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.smart0.xyz/Article/details/gtemuiinfw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.birdmap.top/Article/details/gtemgaoaou.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gtnrztjcaw.html

TS:   resp.ok;  resp.status
来源：http://dali.xuetiantiany.cn/Article/details/gtrqcuxwrl.html

Java: resp.statusCode()
来源：http://dali.snrcjt.cn/Article/details/gtleozdugd.html

Go:   resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gtoeqikvpw.html

Ruby: resp.code.to_i
来源：http://dali.zdqjudy.top/Article/details/gttpdipwfz.html

C#:   (int)resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gtgpjterck.html

[L08] 并发请求多个地址
来源：http://dali.ehwqpu.com/Article/details/gtjxfbxoas.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.redwolf501.top/Article/details/gtomrwvsyl.html

PHP:  curl_multi_init() 系列
来源：http://dali.hfpthk.cn/Article/details/gttddqvldb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtzctotzzp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtgtokcghk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigfzy.top/Article/details/gtpfomdimu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hammf.cn/Article/details/gtzlfpozor.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sweek.top/Article/details/gtlehklkho.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtpigzjypj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gteenivfbt.html

M. 命令行 / 进程 / 环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjafcscdn.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtvnzwqnsq.html

[M01] 读取命令行参数
来源：http://dali.meibo888.top/Article/details/gtmrexylbf.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkxdapaf.html

PHP:  $argv;  $argc;
来源：http://dali.hongshengwenyu.top/Article/details/gtvppxlnjl.html

JS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtdycbjrjl.html

TS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtejzsqsoz.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gthexwyipi.html

Go:   os.Args[1:]
来源：http://dali.hammf.cn/Article/details/gtccbkitjf.html

Ruby: ARGV
来源：http://dali.xziqi.cn/Article/details/gtptudonhm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gttyrgrexs.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtufnitfgs.html

Py:   os.environ.get("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtrdwesjwc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gtgcchlanp.html

JS:   process.env.HOME
来源：http://dali.vqdsnc.cn/Article/details/gtfzipxxpq.html

TS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gthsfmoasf.html

Java: System.getenv("HOME")
来源：http://dali.birdmap.top/Article/details/gtfldinesp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtocxrbayt.html

Ruby: ENV["HOME"]
来源：http://dali.haohaochexian.top/Article/details/gtcxxttheb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sysykeji.top/Article/details/gtiqccjthn.html

[M03] 执行外部命令
来源：http://dali.yj20258.top/Article/details/gtpwqoqzpx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.vqdsnc.cn/Article/details/gtpolxbbmd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyiwmybc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gtvmftjhme.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtehtkqudv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnxiangtu.top/Article/details/gtduhgtphx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hysaishi.cn/Article/details/gtqxhntywb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sysykeji.top/Article/details/gtdcnsqeif.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yangfankeji.com/Article/details/gtligjovbl.html

[M04] 获取当前工作目录
来源：http://dali.aibaodan.cn/Article/details/gtpqawurdq.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gtjudjixml.html

PHP:  getcwd();
来源：http://dali.jinqigufen.top/Article/details/gtjrqjlaab.html

JS:   process.cwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtcqdwotle.html

TS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gtgqrhrute.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.vqdsnc.cn/Article/details/gtxppakogj.html

Go:   os.Getwd()
来源：http://dali.tianlin.xyz/Article/details/gtrootvnlb.html

Ruby: Dir.pwd
来源：http://dali.0kj1m.cn/Article/details/gtxvwfkukz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgfzy.top/Article/details/gtfznbazco.html

[M05] 设置退出码
来源：http://dali.shangyingyoupin.top/Article/details/gtuvivkwkf.html

Py:   sys.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtgkoyxshv.html

PHP:  exit(1);
来源：http://dali.vqdsnc.cn/Article/details/gtjkeckpnv.html

JS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtxilgbdwg.html

TS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtqzjejdnc.html

Java: System.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtbuwwqxbn.html

Go:   os.Exit(1)
来源：http://dali.ybcxt.top/Article/details/gteqryjvat.html

Ruby: exit 1
来源：http://dali.snrcjt.cn/Article/details/gtoboyutwe.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yanxiufei.cn/Article/details/gtmxcdxopn.html

[M06] 向标准错误输出
来源：http://dali.nanxinkj.top/Article/details/gtkgwubkii.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangshuangyany.cn/Article/details/gtfxquuzju.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.havefunace.top/Article/details/gtcsvmvcup.html

JS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtmpgeswft.html

TS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gtvktixpnr.html

Java: System.err.println("err")
来源：http://dali.xinyue.icu/Article/details/gtbomnhtug.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xylfe.cn/Article/details/gtjacbvhbg.html

Ruby: warn "err"
来源：http://dali.yangfankeji.com/Article/details/gtuhdwxcla.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hysaishi.cn/Article/details/gtdwkntpro.html

[M07] 判断是否为主入口
来源：http://dali.daria6918.cn/Article/details/gtcfsthiqc.html

Py:   if __name__ == "__main__":
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoyutufgn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhuazlsk.html

JS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtusdjhrns.html

TS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtseytrlit.html

Java: public static void main(String[] args)
来源：http://dali.xylfe.cn/Article/details/gtioozbauc.html

Go:   func main()
来源：http://dali.xuetiantiany.cn/Article/details/gtpblunzri.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tanke756.top/Article/details/gtyiftzctg.html

C#:   static void Main(string[] args)
来源：http://dali.zhoulong.xyz/Article/details/gthiuiucug.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxinkj.top/Article/details/gtsozrvnqf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgfzy.top/Article/details/gtkoptpkfp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cashguo.top/Article/details/gtceenziwc.html

JS:   process.platform;  process.version
来源：http://dali.hnxiangtu.top/Article/details/gtjwgnwode.html

TS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gtusuzqtzd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuanzx.com/Article/details/gtijlubnfc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhixingplan.top/Article/details/gtpqkekdwu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxnqezwr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnxiangtu.top/Article/details/gtkhtbtcgw.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtuqsrvivl.html

N. 数据结构与算法
来源：http://dali.bjfxy.top/Article/details/gtbuaekjaw.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gthifxhcvo.html

[N01] 二分查找（有序数组）
来源：http://dali.xziqi.cn/Article/details/gtapposmld.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtwirqssnw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zycfv.cn/Article/details/gtrkzgukfm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gtmcobwrkv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gttnphzpnv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtqgomqlnl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtfmprdwoo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cheryme.top/Article/details/gtqopalnxn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtpuipaksv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cdnleiting.top/Article/details/gtovecemwp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gtlajgcvga.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.havefunace.top/Article/details/gtizzsfrfl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtkondsfjz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtyzyjrkxx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xziqi.cn/Article/details/gtmuxmpppq.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewmzxxfc.html

Ruby: arr.sort
来源：http://dali.chenjidiqi.icu/Article/details/gtbfftzsmp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxinkj.top/Article/details/gtvqsygqwg.html

[N03] 快速排序（分治示例）
来源：http://dali.yueranfly.top/Article/details/gtahjutnkv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.svipenyu.cn/Article/details/gtdnaougoi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.vqdsnc.cn/Article/details/gtzssyvada.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gtjvudvfuh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gtjujskvln.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cashguo.top/Article/details/gtjrqeoemy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ydzc1.top/Article/details/gtisjcogbf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yuxming.cn/Article/details/gtddhszmnf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.c1oappe.top/Article/details/gttlwmjyhx.html

[N04] 斐波那契数列
来源：http://dali.yonumen.top/Article/details/gtftobobot.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gtsmldrpud.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.guowangkeji.top/Article/details/gtythoienb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gtxmiafdlg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtmqbtxfhi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gtlofnqyoo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jiagoushi.top/Article/details/gtaaxobhax.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gtmumtqmsy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtcqbkghha.html

[N05] 最大公约数
来源：http://dali.wangdashe.top/Article/details/gtzllyrcht.html

Py:   math.gcd(a, b)
来源：http://dali.sweek.top/Article/details/gtqsoqwjpz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.svipenyu.cn/Article/details/gtjfshohts.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gtmgsewwbc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtbtnpdnqc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zycfv.cn/Article/details/gtwgatztbj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj202588.top/Article/details/gtiycrpeoi.html

Ruby: a.gcd(b)
来源：http://dali.smart0.xyz/Article/details/gtwlihsfhq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daria6918.cn/Article/details/gtocgkuwux.html

[N06] 判断回文字符串
来源：http://dali.daxiang520.top/Article/details/gtdttabfit.html

Py:   s == s[::-1]
来源：http://dali.daxiang520.top/Article/details/gtbgamuuhf.html

PHP:  $s === strrev($s);
来源：http://dali.daria6918.cn/Article/details/gtibqezwuy.html


<!-- 参考信息 -->