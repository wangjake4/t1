代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ivvv.top/Article/details/gt2bsocniix.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gt2fwxnveia.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gt2rjrgvuzk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.9152youxi.cn/Article/details/gt2clwkkdsj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.andypj.xyz/Article/details/gt2bwnfqaqf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xziqi.cn/Article/details/gt2yrxpowgf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jlsjyb.cn/Article/details/gt2utfddgzo.html

[J10] 取今天 / 本月第一天
来源：http://dali.cqqwz.cn/Article/details/gt2jkeisksk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cashguo.top/Article/details/gt2ylixkcxv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.quarkkingdee.top/Article/details/gt2mgctntku.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fengsongda.top/Article/details/gt2qullwyle.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqcfmjk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2odivczgg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wmvryrcl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxinkj.top/Article/details/gt2stiebhzx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sweek.top/Article/details/gt2qtcddwkr.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2ruehlbhq.html

K. JSON 与序列化
来源：http://dali.chenjidiqi.icu/Article/details/gt2esxsdsfg.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2qohsacnk.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnqzz.top/Article/details/gt2nktvmanv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gt2nkwqeytu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gt2dohmhsax.html

JS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2irmnfres.html

TS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gt2nminuslu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhoulong.xyz/Article/details/gt2kakjiiny.html

Go:   json.Marshal(obj)
来源：http://dali.nwbrower.top/Article/details/gt2dsqdqrwz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tanke756.top/Article/details/gt2gtxgsyet.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2lxqglgpm.html

[K02] JSON 字符串转对象
来源：http://dali.meibo888.top/Article/details/gt2jbpqlfzt.html

Py:   json.loads(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2ovcryusn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuxming.cn/Article/details/gt2uxkclwsj.html

JS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gt2pgktsecc.html

TS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gt2udzehccf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yvedp.cn/Article/details/gt2oovtxthw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gt2yakkwrsl.html

Ruby: JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2sgheolpv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xziqi.cn/Article/details/gt2wfexixgg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenjidiqi.icu/Article/details/gt2gabaeske.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gt2lvwtnitz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gt2jbvcroda.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hfwzjiwi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2zrtthbxb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sadcrdej.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2flpmhedx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ydzc1.top/Article/details/gt2lkwnbapz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj202588.top/Article/details/gt2qmftmiim.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigufen.top/Article/details/gt2ojonyzuq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenlongwang.top/Article/details/gt2gowabzjy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.dianchejie.cn/Article/details/gt2xudlmgqh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gt2srgbpkdl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gt2wvajmlxu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pesqhhni.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gt2mkitevax.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gt2agmrrnkx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zycfv.cn/Article/details/gt2rcgfiplv.html

[K05] 深拷贝对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2qguzcftp.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj202588.top/Article/details/gt2ixljnhen.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shangyingyoupin.top/Article/details/gt2arghlmsf.html

JS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gt2ernwjusz.html

TS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2pqfvuifc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gt2xcgsxoib.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tianlin.xyz/Article/details/gt2rlkzhukx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yangfankeji.com/Article/details/gt2tbzzxryb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cheryme.top/Article/details/gt2cjnuegsw.html

[K06] 解析 URL 查询串
来源：http://dali.9152youxi.cn/Article/details/gt2pegdxtqa.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yvedp.cn/Article/details/gt2attzuczv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zpztteya.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ecvglvky.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gt2fynjmyjr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ppjwa.cn/Article/details/gt2cojzdtrw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gt2xkjoetkp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gt2ttryfbkk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gt2icuoxmvk.html

[K07] 进制转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2ygcqqrvi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2qlzyzzhr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.daria6918.cn/Article/details/gt2tygkeiwb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovrognrs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2dkfacxgv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2tkmswwda.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cdnleiting.top/Article/details/gt2yjaorcen.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.bjfxy.top/Article/details/gt2pcsmmbtv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2ihzqaqpp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hongshengwenyu.top/Article/details/gt2mcjdwymr.html

Py:   pickle.dumps(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2ucpnvgyz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hywenlv.cn/Article/details/gt2yjcwaabj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2rffbgean.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gt2scrzitsc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xylfe.cn/Article/details/gt2hzyblrsh.html

Go:   encoding/gob
来源：http://dali.hongshengwenyu.top/Article/details/gt2iimgddso.html

Ruby: Marshal.dump(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2uripoxfl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gt2atsxywtl.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2askhaeds.html

L. 网络请求
来源：http://dali.zhongyouzk.top/Article/details/gt2wjszsghy.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2qvtlitdc.html

[L01] 发送 GET 请求
来源：http://dali.9152youxi.cn/Article/details/gt2mtgbnpnn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gogol.net.cn/Article/details/gt2svmxydkc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxuanxn.top/Article/details/gt2lnfvivqp.html

JS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gt2euxldmue.html

TS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2xpcgwbbd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jianghu66.top/Article/details/gt2awefaedb.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2alpsgkxb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hongshengwenyu.top/Article/details/gt2yyafnpns.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gogol.net.cn/Article/details/gt2xdjlbxmz.html

[L02] 发送 POST JSON
来源：http://dali.bjfxy.top/Article/details/gt2fmegizne.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gt2xlgyrbpf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sweek.top/Article/details/gt2kiplpxyc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gt2krfkqgpq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gt2qvxlthgs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gt2xgjyrmqd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guowangkeji.top/Article/details/gt2wacltlqb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxinkj.top/Article/details/gt2nytzcnru.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhoulong.xyz/Article/details/gt2yckkgzsw.html

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gt2myncrbuv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ydzc1.top/Article/details/gt2kvsnxiik.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxmirpca.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gt2mnhxebiq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fzhhl.top/Article/details/gt2hixlozpi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tanke756.top/Article/details/gt2neywxpat.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gt2nmxmmgty.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.redwolf501.top/Article/details/gt2qiztkicn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gt2tsaadgat.html

[L04] 设置超时
来源：http://dali.quarkkingdee.top/Article/details/gt2hawpyezq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gogol.net.cn/Article/details/gt2vcesiltt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gt2yapiyxrv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gt2fjtebwun.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gt2nkythkhz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gt2sayebujh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yvedp.cn/Article/details/gt2hfhvseoo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ivvv.top/Article/details/gt2xjgwmjuf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.snrcjt.cn/Article/details/gt2komdldwi.html

[L05] 上传文件（multipart）
来源：http://dali.gotoacloud.top/Article/details/gt2dtfjxyxh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuanzhike.top/Article/details/gt2jrkstsqe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jyoumei.cn/Article/details/gt2jyktrikc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gt2abzsnsfk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gt2jigdnyvp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pengpengdd.cyou/Article/details/gt2pwthrqqw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.havefunace.top/Article/details/gt2lhggvaej.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.kuanghao11.cn/Article/details/gt2ozxxlfmr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2uhnrtlxh.html

[L06] 解析响应为 JSON
来源：http://dali.sweek.top/Article/details/gt2bdtclieq.html

Py:   resp.json()
来源：http://dali.guowangkeji.top/Article/details/gt2fsnyndgp.html

PHP:  json_decode($body, true);
来源：http://dali.xziqi.cn/Article/details/gt2gwgdclmn.html

JS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gt2cptoudhe.html

TS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gt2uzojboou.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fwrsreez.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jyoumei.cn/Article/details/gt2fmelhruv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nwbrower.top/Article/details/gt2dccdkldj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.fengsongda.top/Article/details/gt2ispvvoti.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gt2ykpiuvvq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sweek.top/Article/details/gt2wquxnisp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgfzy.top/Article/details/gt2pgfwvjsn.html

JS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gt2qlyyiqea.html

TS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gt2dltfmjir.html

Java: resp.statusCode()
来源：http://dali.yonumen.top/Article/details/gt2vlqakklk.html

Go:   resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gt2bqxfttiy.html

Ruby: resp.code.to_i
来源：http://dali.daxiang520.top/Article/details/gt2kkxxejit.html

C#:   (int)resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gt2sdgcpcjm.html

[L08] 并发请求多个地址
来源：http://dali.svipenyu.cn/Article/details/gt2mishrnxt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xziqi.cn/Article/details/gt2vdgurspk.html

PHP:  curl_multi_init() 系列
来源：http://dali.shangyingyoupin.top/Article/details/gt2gokwtqrj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gt2udeuskpp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gt2kcqedwtf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hysaishi.cn/Article/details/gt2atilcsbr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tanke756.top/Article/details/gt2uwzmsrck.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yongpay.top/Article/details/gt2apuwbbzu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yanxiufei.cn/Article/details/gt2kwtyggit.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2pqwqxqaa.html

M. 命令行 / 进程 / 环境
来源：http://dali.jyoumei.cn/Article/details/gt2fhozcpot.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2bzmhrffh.html

[M01] 读取命令行参数
来源：http://dali.zhengqikj.top/Article/details/gt2rczjmehv.html

Py:   sys.argv[1:]
来源：http://dali.yuxming.cn/Article/details/gt2hxypkyct.html

PHP:  $argv;  $argc;
来源：http://dali.sysykeji.top/Article/details/gt2sikcslim.html

JS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gt2bslhfdrl.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gt2zszdkpcy.html

Java: args 数组（main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gt2xvrlegwp.html

Go:   os.Args[1:]
来源：http://dali.yvedp.cn/Article/details/gt2cgxmilan.html

Ruby: ARGV
来源：http://dali.xziqi.cn/Article/details/gt2uslgdoxk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gt2zmsagieb.html

[M02] 读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gt2ymxuvrxe.html

Py:   os.environ.get("HOME")
来源：http://dali.sxryk.cn/Article/details/gt2kjwhpsnl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sweek.top/Article/details/gt2ufdzcwmb.html

JS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bswypxys.html

TS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gt2cdqvxjwh.html

Java: System.getenv("HOME")
来源：http://dali.bjfxy.top/Article/details/gt2nunsgzan.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.316326.xyz/Article/details/gt2ktarukkm.html

Ruby: ENV["HOME"]
来源：http://dali.zhongyouzk.top/Article/details/gt2qjptqzcm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gt2zyngwpzv.html

[M03] 执行外部命令
来源：http://dali.aibaodan.cn/Article/details/gt2trsoofao.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gofmqkvz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhixingplan.top/Article/details/gt2honmxbke.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2lhaodtle.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gt2dtcattav.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cheryme.top/Article/details/gt2olstcves.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hysaishi.cn/Article/details/gt2renywxhs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.0kj1m.cn/Article/details/gt2ggivzcgd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2huzybyet.html

[M04] 获取当前工作目录
来源：http://dali.wangshuangyany.cn/Article/details/gt2ccbqrhyk.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gt2fsrqzqvz.html

PHP:  getcwd();
来源：http://dali.chenlongwang.top/Article/details/gt2xwdbabvq.html

JS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2eqogezxa.html

TS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rbiedrip.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxuanxn.top/Article/details/gt2fotexnxp.html

Go:   os.Getwd()
来源：http://dali.wangdashe.top/Article/details/gt2bnlsgbya.html

Ruby: Dir.pwd
来源：http://dali.tianlin.xyz/Article/details/gt2viqetpae.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgfzy.top/Article/details/gt2gokvgtxe.html

[M05] 设置退出码
来源：http://dali.gaohongyu789.top/Article/details/gt2aqqnunwr.html

Py:   sys.exit(1)
来源：http://dali.ybcxt.top/Article/details/gt2vjrierhi.html

PHP:  exit(1);
来源：http://dali.havefunace.top/Article/details/gt2jnsvesfs.html

JS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2lfibrgxd.html

TS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvliwhft.html

Java: System.exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2embwimzn.html

Go:   os.Exit(1)
来源：http://dali.cheryme.top/Article/details/gt2jssfmfxb.html

Ruby: exit 1
来源：http://dali.fzhhl.top/Article/details/gt2ajoaencm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.9152youxi.cn/Article/details/gt2qmkxyipn.html

[M06] 向标准错误输出
来源：http://dali.0kj1m.cn/Article/details/gt2cqgbscgf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gt2kbhcowte.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.0kj1m.cn/Article/details/gt2avfpzpcp.html

JS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gt2wmmbjrig.html

TS:   console.error("err")
来源：http://dali.smart0.xyz/Article/details/gt2kutpzaeh.html

Java: System.err.println("err")
来源：http://dali.cucudq.cn/Article/details/gt2vttqqxwx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2nvwkerfd.html

Ruby: warn "err"
来源：http://dali.shzxlz.cn/Article/details/gt2wocmctdk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yueranfly.top/Article/details/gt2klolkfck.html

[M07] 判断是否为主入口
来源：http://dali.chenlongwang.top/Article/details/gt2dnjakhkl.html

Py:   if __name__ == "__main__":
来源：http://dali.xuetiantiany.cn/Article/details/gt2esloduct.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2mjvqnokv.html

JS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gt2shlqcmya.html

TS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gt2onsmpuof.html

Java: public static void main(String[] args)
来源：http://dali.zhongyouzk.top/Article/details/gt2fltxtabl.html

Go:   func main()
来源：http://dali.jianghu66.top/Article/details/gt2ldqlmped.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zycfv.cn/Article/details/gt2tawkuboo.html

C#:   static void Main(string[] args)
来源：http://dali.0kj1m.cn/Article/details/gt2wpezfehm.html

[M08] 获取系统与运行时信息
来源：http://dali.hywenlv.cn/Article/details/gt2lswauevp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cucudq.cn/Article/details/gt2tigdzurp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gogol.net.cn/Article/details/gt2zakqavrj.html

JS:   process.platform;  process.version
来源：http://dali.haohaochexian.top/Article/details/gt2honuvccl.html

TS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gt2dwowzcpq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yvedp.cn/Article/details/gt2jdmvyumk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.redwolf501.top/Article/details/gt2qvoytkhr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.feifeiyinyue.top/Article/details/gt2palelbfk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gt2fqsvnszd.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2rnlbksod.html

N. 数据结构与算法
来源：http://dali.yangfankeji.com/Article/details/gt2vogtiyon.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2aczlrmke.html

[N01] 二分查找（有序数组）
来源：http://dali.tanke756.top/Article/details/gt2kymbqelx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2coiqfork.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sweek.top/Article/details/gt2dsjvusvo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gt2duqmvvqa.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gt2bsavnohx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2getefeye.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2zqehguss.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guannengcc.top/Article/details/gt2wmnrwmvu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.316326.xyz/Article/details/gt2ovceaezr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shuidangran.top/Article/details/gt2mekljgua.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gt2mmufgfqy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdfzzavo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gt2bpttnbvn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gt2pekyaray.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nwbrower.top/Article/details/gt2bmalnddu.html

Go:   slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gt2pfbqofon.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gt2zymvhkuv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxuanxn.top/Article/details/gt2pnrxdldb.html

[N03] 快速排序（分治示例）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hwulgeqb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nwbrower.top/Article/details/gt2eulkesou.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tanke756.top/Article/details/gt2sqypzsdy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gt2hymlkwtz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gt2eltbmvft.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hywenlv.cn/Article/details/gt2lhirwpob.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jiagoushi.top/Article/details/gt2bnoxcxyu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ehwqpu.com/Article/details/gt2rxvmgxtl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jyoumei.cn/Article/details/gt2pxljyxwy.html

[N04] 斐波那契数列
来源：http://dali.cucudq.cn/Article/details/gt2xngwvbur.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2whbpigma.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cqqwz.cn/Article/details/gt2fxbqckij.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gt2icgjdfva.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gt2egezkzzw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gt2vtsjvihx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.haohaochexian.top/Article/details/gt2rwjhspbq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gt2obbumyiu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kkegwtrb.html

[N05] 最大公约数
来源：http://dali.yvedp.cn/Article/details/gt2mfcmtovz.html

Py:   math.gcd(a, b)
来源：http://dali.sysykeji.top/Article/details/gt2duaxcino.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ehwqpu.com/Article/details/gt2lslhoegl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gt2nyxztviu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gt2bvakgmpa.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shuidangran.top/Article/details/gt2zmbpmqgl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cucudq.cn/Article/details/gt2qfzrzxim.html

Ruby: a.gcd(b)
来源：http://dali.dianchejie.cn/Article/details/gt2cksmtdos.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gaohongyu789.top/Article/details/gt2ucixjbrb.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gt2jspzuemd.html

Py:   s == s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gt2tevgcobj.html

PHP:  $s === strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2pswohpph.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gt2axxdiegy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nhntuain.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cheryme.top/Article/details/gt2rdetrpxq.html

Go:   // 双指针从两端比较
来源：http://dali.zycfv.cn/Article/details/gt2pfomxvew.html

Ruby: s == s.reverse
来源：http://dali.yangfankeji.com/Article/details/gt2taaonxxx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenlongwang.top/Article/details/gt2bvzzmnnp.html

[N07] 两数之和（返回下标）
来源：http://dali.cucudq.cn/Article/details/gt2odgqkvwh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sxryk.cn/Article/details/gt2wzmisqnv.html


<!-- 参考信息 -->