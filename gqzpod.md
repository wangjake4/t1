代发 wailian999

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dashuyun.cn/Article/details/gt2dwqpmsby.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yangfankeji.com/Article/details/gt2ycvnxaab.html

[J09] 时区处理
来源：http://dali.nanxuanxn.top/Article/details/gt2uodwqvrn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cqqwz.cn/Article/details/gt2njeibcut.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258.top/Article/details/gt2cfygtmpj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gt2dkiacyfu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gt2vlpsynzy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daxiang520.top/Article/details/gt2efaoxhui.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhoulong.xyz/Article/details/gt2rayyenvo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daria6918.cn/Article/details/gt2xejrrlra.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pycfn.com/Article/details/gt2gbylxpvp.html

[J10] 取今天 / 本月第一天
来源：http://dali.aizwys.cn/Article/details/gt2vamyuxxk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ppjwa.cn/Article/details/gt2jmfqzmtn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jlsjyb.cn/Article/details/gt2gldjlrpf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.svipenyu.cn/Article/details/gt2npbththw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2tnvipnib.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xziqi.cn/Article/details/gt2htyownfp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigufen.top/Article/details/gt2gvjyorxz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hfpthk.cn/Article/details/gt2zabtxetu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigufen.top/Article/details/gt2ekykttdn.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2vyuvcygg.html

K. JSON 与序列化
来源：http://dali.yongpay.top/Article/details/gt2cgkosgnx.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2bdcskngy.html

[K01] 对象转 JSON 字符串
来源：http://dali.yongpay.top/Article/details/gt2eaeiyeco.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gt2mbryrctf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvqdxjir.html

JS:   JSON.stringify(obj)
来源：http://dali.ydzc1.top/Article/details/gt2sjlhwquk.html

TS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gt2ofitseoo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258.top/Article/details/gt2ebgldwup.html

Go:   json.Marshal(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xdfpgesa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.svipenyu.cn/Article/details/gt2dczobatn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cheryme.top/Article/details/gt2fjlhaqfa.html

[K02] JSON 字符串转对象
来源：http://dali.cdnleiting.top/Article/details/gt2hmksycep.html

Py:   json.loads(s)
来源：http://dali.hammf.cn/Article/details/gt2fmeprdpi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.316326.xyz/Article/details/gt2shacyddh.html

JS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2onngdmef.html

TS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gt2taomztpl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dashuyun.cn/Article/details/gt2iumykwxp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gt2lrphnkad.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2reslsyiv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwjfojrf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.haohaochexian.top/Article/details/gt2hyzwjqdx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gt2zjzduolf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gt2pwiyyjuu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gt2hggersfz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gt2hopmabvy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2xijnrotr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhoulong.xyz/Article/details/gt2erijsuqw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2atpxcusv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangshuangyany.cn/Article/details/gt2abjarxie.html

[K04] 读取 JSON 文件
来源：http://dali.nanxuanxn.top/Article/details/gt2ndldsudl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guannengcc.top/Article/details/gt2dcpyzyaw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yongpay.top/Article/details/gt2yeuddzcj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gt2rybuqmrh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gt2nqzmbfic.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aizwys.cn/Article/details/gt2svtbezoe.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gt2wzxjwkcq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2flctjdnb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gt2lefzofjg.html

[K05] 深拷贝对象
来源：http://dali.bjfxy.top/Article/details/gt2yxdcsegm.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2viylpavf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangdashe.top/Article/details/gt2zimuwudu.html

JS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gt2zrfahnpv.html

TS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2pieqghii.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hysaishi.cn/Article/details/gt2peonpudg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cdnleiting.top/Article/details/gt2wjigodst.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hammf.cn/Article/details/gt2ictfjbqu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.0kj1m.cn/Article/details/gt2ckipurcv.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gt2rqgymqih.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj202588.top/Article/details/gt2nzjdombf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guannengcc.top/Article/details/gt2bkolyapz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gt2odfirdkp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gt2yfcexqfe.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xinyue.icu/Article/details/gt2lsspfeoz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovxkpmob.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gt2jptjdbpb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gt2jujvrbut.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkzpvvn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2zsxtllyw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhengqikj.top/Article/details/gt2yozvxcbc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gt2junrdybn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2cdghwmmc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2zarciroa.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhongyouzk.top/Article/details/gt2nwmgfcbh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangdashe.top/Article/details/gt2lvksvshg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2nyhhtvry.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aizwys.cn/Article/details/gt2fnbdvkty.html

Py:   pickle.dumps(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2rpgfpedn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2ygqecyvo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gt2wbbalbki.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gt2exwyuqac.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnxiangtu.top/Article/details/gt2iobnmais.html

Go:   encoding/gob
来源：http://dali.birdmap.top/Article/details/gt2jddgxyca.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2tyfpaczq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gt2cldwpjzh.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2rjhykpcq.html

L. 网络请求
来源：http://dali.tanke756.top/Article/details/gt2sefwaeeh.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2bwzoxrmi.html

[L01] 发送 GET 请求
来源：http://dali.xziqi.cn/Article/details/gt2xaojpsfu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sxryk.cn/Article/details/gt2cntbggfd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cheryme.top/Article/details/gt2hibppgfu.html

JS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gt2qttwonca.html

TS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gt2aaraubkk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.vqdsnc.cn/Article/details/gt2orxdkcor.html

Go:   resp, err := http.Get(url)
来源：http://dali.9152youxi.cn/Article/details/gt2xtmdticr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.mhx1999.top/Article/details/gt2cohmuuza.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cashguo.top/Article/details/gt2vsuvcxev.html

[L02] 发送 POST JSON
来源：http://dali.nwbrower.top/Article/details/gt2nyofelvr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gt2pcrdabaa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hammf.cn/Article/details/gt2bfuyqsto.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gt2karxsmwb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2rifbrzsa.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nwbrower.top/Article/details/gt2vuhwuvti.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.redwolf501.top/Article/details/gt2oeizblnx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dianchejie.cn/Article/details/gt2twnwadfr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.316326.xyz/Article/details/gt2qfxwlooo.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gt2kuhbomqa.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nanxinkj.top/Article/details/gt2nfqlljaw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.mhx1999.top/Article/details/gt2chuhpywp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhixingplan.top/Article/details/gt2bwjuhmfi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gt2gmvxwcno.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cdnleiting.top/Article/details/gt2pigqqvkd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gt2rdojevim.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.svipenyu.cn/Article/details/gt2udsirneb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gt2froesmfm.html

[L04] 设置超时
来源：http://dali.cucudq.cn/Article/details/gt2qnlmpmzf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.redwolf501.top/Article/details/gt2reohlqxe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgfzy.top/Article/details/gt2tqvirmxw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gt2fppoqwqq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gt2yeguvwcx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sweek.top/Article/details/gt2fbjxbeei.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guowangkeji.top/Article/details/gt2aycuooeg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jlsjyb.cn/Article/details/gt2jtpmbmzu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yjnzaoit.html

[L05] 上传文件（multipart）
来源：http://dali.shuidangran.top/Article/details/gt2tfretwkk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hammf.cn/Article/details/gt2zqdzjqkx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nwbrower.top/Article/details/gt2lxmfwdpt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gt2npcqcfgl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenjidiqi.icu/Article/details/gt2mzvzkakb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxuanxn.top/Article/details/gt2fuvxuwwr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.316326.xyz/Article/details/gt2zykzvgey.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.quarkkingdee.top/Article/details/gt2kpddhbcw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mqrbpuod.html

[L06] 解析响应为 JSON
来源：http://dali.wangdashe.top/Article/details/gt2ximkrtyj.html

Py:   resp.json()
来源：http://dali.yuxming.cn/Article/details/gt2duxzxzad.html

PHP:  json_decode($body, true);
来源：http://dali.chenzaomai.com/Article/details/gt2xefkcqrj.html

JS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gt2myjjkyzi.html

TS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gt2wfvhdldp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gt2zsiapsoj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sufxvd.cn/Article/details/gt2gqkvslew.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yueranfly.top/Article/details/gt2cukxsxqw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2psxypklx.html

[L07] 处理 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gt2qeiuwbxh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ivvv.top/Article/details/gt2qmgfvclp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hfpthk.cn/Article/details/gt2zlcgeapv.html

JS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gt2xsrnxbgs.html

TS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gt2fnkrvbrb.html

Java: resp.statusCode()
来源：http://dali.pycfn.com/Article/details/gt2cgdscikz.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2movjfljq.html

Ruby: resp.code.to_i
来源：http://dali.wangdashe.top/Article/details/gt2klthsvrh.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gt2hjfztggt.html

[L08] 并发请求多个地址
来源：http://dali.zhixingplan.top/Article/details/gt2nujitrya.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gzhubu.top/Article/details/gt2cnydrqrb.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangshuangyany.cn/Article/details/gt2bxnjqayp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gt2hvgsywtg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2csyetywq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yueranfly.top/Article/details/gt2uuenihxe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cucudq.cn/Article/details/gt2yuqzlwsc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dashuyun.cn/Article/details/gt2xhhpvbof.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.9152youxi.cn/Article/details/gt2hodlbcxu.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jsfzwbvl.html

M. 命令行 / 进程 / 环境
来源：http://dali.fengsongda.top/Article/details/gt2wpkdhdtl.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2oonxsuyr.html

[M01] 读取命令行参数
来源：http://dali.cdnleiting.top/Article/details/gt2oskyrbfd.html

Py:   sys.argv[1:]
来源：http://dali.yonumen.top/Article/details/gt2twpgmwgp.html

PHP:  $argv;  $argc;
来源：http://dali.cqqwz.cn/Article/details/gt2uahzdqgt.html

JS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gt2nuhlagzj.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gt2bxkyakms.html

Java: args 数组（main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jdljfxuj.html

Go:   os.Args[1:]
来源：http://dali.yueranfly.top/Article/details/gt2lcilkncq.html

Ruby: ARGV
来源：http://dali.jianghu66.top/Article/details/gt2jseqhjfy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gt2gauhubbj.html

[M02] 读取环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2ejzwaaus.html

Py:   os.environ.get("HOME")
来源：http://dali.birdmap.top/Article/details/gt2kcdppuls.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gt2hrteudgg.html

JS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gt2jupvfggf.html

TS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gt2ajxxllqt.html

Java: System.getenv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gt2lktaecnw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gt2kjfcbtfu.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2brkoqkmw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2qyfcijgl.html

[M03] 执行外部命令
来源：http://dali.daxiang520.top/Article/details/gt2ivglyjmf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhongyouzk.top/Article/details/gt2mtffelxn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.birdmap.top/Article/details/gt2xpprrynx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gt2iwfyqcrp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gt2zjzzoufd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuanzx.com/Article/details/gt2qozzhmzz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pengpengdd.cyou/Article/details/gt2rnxwtywz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cqqwz.cn/Article/details/gt2acgarnvl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cashguo.top/Article/details/gt2xpyzhewr.html

[M04] 获取当前工作目录
来源：http://dali.fzhhl.top/Article/details/gt2uqviszsg.html

Py:   os.getcwd()
来源：http://dali.sxryk.cn/Article/details/gt2oajsptae.html

PHP:  getcwd();
来源：http://dali.sysykeji.top/Article/details/gt2ythwxzga.html

JS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gt2aizoiapj.html

TS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gt2hczghaqp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenlongwang.top/Article/details/gt2szcmknly.html

Go:   os.Getwd()
来源：http://dali.tian-w.cn/Article/details/gt2qwaybloy.html

Ruby: Dir.pwd
来源：http://dali.sweek.top/Article/details/gt2aqlierrb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cdnleiting.top/Article/details/gt2isxgdboi.html

[M05] 设置退出码
来源：http://dali.yonumen.top/Article/details/gt2bgyhpmgs.html

Py:   sys.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pcsabzqf.html

PHP:  exit(1);
来源：http://dali.aizwys.cn/Article/details/gt2xvomkzum.html

JS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2pwcpatoy.html

TS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2ttfvtnod.html

Java: System.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gt2sijprdar.html

Go:   os.Exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2iefbdpfs.html

Ruby: exit 1
来源：http://dali.yuxming.cn/Article/details/gt2mealrbqt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.birdmap.top/Article/details/gt2fbpoxcfj.html

[M06] 向标准错误输出
来源：http://dali.aibaodan.cn/Article/details/gt2yrvupdjg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gt2xmjmmlvs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhixingplan.top/Article/details/gt2srmmejdj.html

JS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gt2oxgapaxe.html

TS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gt2vmhvjdgv.html

Java: System.err.println("err")
来源：http://dali.gogol.net.cn/Article/details/gt2haktiwlc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangdashe.top/Article/details/gt2qknlhezq.html

Ruby: warn "err"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oqinklbp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuanzhike.top/Article/details/gt2yeoksnkv.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2silirxzw.html

Py:   if __name__ == "__main__":
来源：http://dali.aibaodan.cn/Article/details/gt2zoevflxn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jiagoushi.top/Article/details/gt2krmjoqxe.html

JS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gt2nipmmblc.html

TS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gt2gjoabubn.html

Java: public static void main(String[] args)
来源：http://dali.gotoacloud.top/Article/details/gt2iyrvfxrj.html

Go:   func main()
来源：http://dali.xinyue.icu/Article/details/gt2eppouilb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hammf.cn/Article/details/gt2fqhfckda.html

C#:   static void Main(string[] args)
来源：http://dali.yanxiufei.cn/Article/details/gt2hchbwqim.html

[M08] 获取系统与运行时信息
来源：http://dali.svipenyu.cn/Article/details/gt2kvxrgbkl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangshuangyany.cn/Article/details/gt2xnpvidcf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2duqrfqyr.html

JS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gt2yhmefzvb.html

TS:   process.platform;  process.version
来源：http://dali.zhengqikj.top/Article/details/gt2qixadleg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guowangkeji.top/Article/details/gt2kvztaupp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhoulong.xyz/Article/details/gt2jlaiyrlu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xylfe.cn/Article/details/gt2whsosmyn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhongyouzk.top/Article/details/gt2fneyfetv.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2hgdgbnyy.html

N. 数据结构与算法
来源：http://dali.chenzaomai.com/Article/details/gt2gqbqtjyz.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2ynwnhign.html

[N01] 二分查找（有序数组）
来源：http://dali.shuidangran.top/Article/details/gt2appfydof.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2qjlplnoi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.smart0.xyz/Article/details/gt2uunadqnb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gt2kfbbiwbq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.bjfxy.top/Article/details/gt2sglwvrmv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2qevdfnsk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yongpay.top/Article/details/gt2ekugyijn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhengqikj.top/Article/details/gt2xknibyla.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2ivudxkqi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.meibo888.top/Article/details/gt2nhwjqwxb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guowangkeji.top/Article/details/gt2pqeouebv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.birdmap.top/Article/details/gt2sntwzvoi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2aztyhrsb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gt2uwcnvrew.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xylfe.cn/Article/details/gt2jyvxuehi.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xcnpgoll.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gt2jzvpfnux.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sufxvd.cn/Article/details/gt2oicsiwnc.html

[N03] 快速排序（分治示例）
来源：http://dali.jqgfzy.top/Article/details/gt2hgftayva.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ybcxt.top/Article/details/gt2trhzzyge.html

PHP:  // 递归实现，或用 usort
来源：http://dali.redwolf501.top/Article/details/gt2fyohksms.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bcnrqygt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gt2poyfchhx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shzxlz.cn/Article/details/gt2xbiwjlzf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuetiantiany.cn/Article/details/gt2wuzuefwr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmwsytc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sxryk.cn/Article/details/gt2ttvzcbkn.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmvbjin.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cucudq.cn/Article/details/gt2zixqhodo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gt2yzyviajf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gt2rpuxqkpq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gt2ifnbahme.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gt2xiyjxvno.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sufxvd.cn/Article/details/gt2hfipjhgx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2ddkiqflc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gt2vnizzbsh.html

[N05] 最大公约数
来源：http://dali.yueranfly.top/Article/details/gt2vcdxohxk.html

Py:   math.gcd(a, b)
来源：http://dali.cashguo.top/Article/details/gt2rznaesoy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wjrafydl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gt2ydxjvqty.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gt2idlaulqt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zdqjudy.top/Article/details/gt2ijhgmacg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ludobpfy.html

Ruby: a.gcd(b)
来源：http://dali.tianlin.xyz/Article/details/gt2ssfzdwnq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gt2vmmmqnve.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vgjqljxe.html

Py:   s == s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gt2eivexzuu.html

PHP:  $s === strrev($s);
来源：http://dali.wangdashe.top/Article/details/gt2seuvcitr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gt2szhwkacg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2rqnjpyih.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj20258888.top/Article/details/gt2skuedjvn.html

Go:   // 双指针从两端比较
来源：http://dali.tanke756.top/Article/details/gt2kkhphbee.html


<!-- 参考信息 -->