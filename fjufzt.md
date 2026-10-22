代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sweek.top/Article/details/gtygldjmxj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gtgkpzqkaq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gtsobywols.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gaohongyu789.top/Article/details/gtztsniedd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pengpengdd.cyou/Article/details/gtmypaalho.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gzhubu.top/Article/details/gthmarvwsn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258888.top/Article/details/gtxrbqmkxh.html

[J10] 取今天 / 本月第一天
来源：http://dali.yongpay.top/Article/details/gtxbzqrqbj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dashuyun.cn/Article/details/gtvcldrxzi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ydzc1.top/Article/details/gtkeezyftc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthljqoglp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cashguo.top/Article/details/gtaxlmnbpa.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjelawltf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yongpay.top/Article/details/gtxqmtefcx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuanzhike.top/Article/details/gteybibrql.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gogol.net.cn/Article/details/gtbakhnuwa.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtsgqxtzsd.html

K. JSON 与序列化
来源：http://dali.snrcjt.cn/Article/details/gtfwdmrnbu.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtefbwcgfp.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuanzx.com/Article/details/gtwndzpkkj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrqpzolg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gtqrvldplc.html

JS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gtamonvadb.html

TS:   JSON.stringify(obj)
来源：http://dali.ydzc1.top/Article/details/gtzszjthwj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuetiantiany.cn/Article/details/gtxyckvotu.html

Go:   json.Marshal(obj)
来源：http://dali.sysykeji.top/Article/details/gtkoqcmebl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dianchejie.cn/Article/details/gteyvovqli.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tian-w.cn/Article/details/gtadntyeat.html

[K02] JSON 字符串转对象
来源：http://dali.haohaochexian.top/Article/details/gtqulxkzuo.html

Py:   json.loads(s)
来源：http://dali.cashguo.top/Article/details/gtvocobyxd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.iojbl.cn/Article/details/gtcmgncwge.html

JS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gthqwwfcbb.html

TS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gtgajczdlv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtldhnslzd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gtqtzrrrvm.html

Ruby: JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtysaawooe.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hysaishi.cn/Article/details/gtpgkgdxrl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.andypj.xyz/Article/details/gtemafgwez.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gtxpqtxegw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gtuxsyxplb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtjdllzpxb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gtezoybrck.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tian-w.cn/Article/details/gtfjbzbpos.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xziqi.cn/Article/details/gthgoenftm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tanke756.top/Article/details/gtykjlccsz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhongyouzk.top/Article/details/gtzcliudqt.html

[K04] 读取 JSON 文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtestapxow.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.smart0.xyz/Article/details/gtgkeraxrg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daria6918.cn/Article/details/gtbmhvxvyz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsalsbrr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrielrgjd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.bjfxy.top/Article/details/gtnetvjhqu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gtopfjvkew.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gtshygnrzz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yongpay.top/Article/details/gthhstbnfc.html

[K05] 深拷贝对象
来源：http://dali.kuanghao11.cn/Article/details/gtvisnkzfu.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgfzy.top/Article/details/gtvcwdsqsf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tian-w.cn/Article/details/gtknsjykoq.html

JS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gtqkpnomrl.html

TS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtgidfjbzt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.meibo888.top/Article/details/gtcvjylkmc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhixingplan.top/Article/details/gtfeufgdrk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hfpthk.cn/Article/details/gtduaeberj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sxryk.cn/Article/details/gtgncutpfj.html

[K06] 解析 URL 查询串
来源：http://dali.wangdashe.top/Article/details/gtmttwqndc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.c1oappe.top/Article/details/gtlzadbrez.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dianchejie.cn/Article/details/gthxtlnhpp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gtwfbxpcsi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gtnesiaksa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.redwolf501.top/Article/details/gtygocskgz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtvgoiycfb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtfonaaqtc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gtjgyancpr.html

[K07] 进制转换
来源：http://dali.birdmap.top/Article/details/gtlguzuthl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtrbgxdkqg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegienbwu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtzqaqbedm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtdkjpxhpq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtwmwtyjkh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cdnleiting.top/Article/details/gthdyoajqm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gaohongyu789.top/Article/details/gtwttbqefi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtrclawjip.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dashuyun.cn/Article/details/gteorllrgt.html

Py:   pickle.dumps(obj)
来源：http://dali.c1oappe.top/Article/details/gtrzkrfoxg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gogol.net.cn/Article/details/gtadldlevh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nwbrower.top/Article/details/gtcqnzrkef.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gtbersrpjg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjykdstio.html

Go:   encoding/gob
来源：http://dali.birdmap.top/Article/details/gtewfdttbr.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtvkakhlwx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gttrjszdlw.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtzljerbnv.html

L. 网络请求
来源：http://dali.hnqzz.top/Article/details/gtftkmdodf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtvwqcjeja.html

[L01] 发送 GET 请求
来源：http://dali.feifeiyinyue.top/Article/details/gtrnwginif.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jlsjyb.cn/Article/details/gtxhjpvujf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.redwolf501.top/Article/details/gtcvuubkon.html

JS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gtfxavizvl.html

TS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gtflbxfeea.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sufxvd.cn/Article/details/gtmmyoghiz.html

Go:   resp, err := http.Get(url)
来源：http://dali.gogol.net.cn/Article/details/gtnomxhtlp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnwzqwag.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.mhx1999.top/Article/details/gtuhkanngk.html

[L02] 发送 POST JSON
来源：http://dali.xziqi.cn/Article/details/gtdjvfvjwj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.birdmap.top/Article/details/gthsemrrtv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sxryk.cn/Article/details/gtbfuwywst.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gtcjbufeex.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gtihvcpcde.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xziqi.cn/Article/details/gtadhipiqf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shangyingyoupin.top/Article/details/gtwxvokvuc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcyuygcw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sxryk.cn/Article/details/gtlvdukhqy.html

[L03] 设置自定义请求头
来源：http://dali.daxiang520.top/Article/details/gthnlymejz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cheryme.top/Article/details/gthdozsfdx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenzaomai.com/Article/details/gtursoilxr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbgkouzu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gtxtnhdgtu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.vqdsnc.cn/Article/details/gtcvpxjgal.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtulmmwupo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gotoacloud.top/Article/details/gtxzlyleiv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtvswhiugk.html

[L04] 设置超时
来源：http://dali.ydzc1.top/Article/details/gtnezhdsqo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shangyingyoupin.top/Article/details/gtbkqnrzzd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ybcxt.top/Article/details/gtukuethvz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gtosrphrsj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gtxkgoezep.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zycfv.cn/Article/details/gtyogjlnvt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.redwolf501.top/Article/details/gtidjmhyse.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ybcxt.top/Article/details/gtkjrgjgtq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtolwkxjlk.html

[L05] 上传文件（multipart）
来源：http://dali.cdnleiting.top/Article/details/gtzeggfnqj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuanzhike.top/Article/details/gtnpgjaldn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzmalyzu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gtowilscdt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gtgdrbjfyf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jianghu66.top/Article/details/gtrmhdmnso.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tianlin.xyz/Article/details/gtnkcnefua.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.smart0.xyz/Article/details/gtqtbxwghp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ybcxt.top/Article/details/gtgstjnren.html

[L06] 解析响应为 JSON
来源：http://dali.sweek.top/Article/details/gthahdmvpt.html

Py:   resp.json()
来源：http://dali.hywenlv.cn/Article/details/gtbuqwajyi.html

PHP:  json_decode($body, true);
来源：http://dali.aibaodan.cn/Article/details/gtopzhmvrx.html

JS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtziphogfv.html

TS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gthlyuobsf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtwiczkghq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnqzz.top/Article/details/gtzkviutfa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cucudq.cn/Article/details/gtszvqgwyv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.mhx1999.top/Article/details/gtaogsvajt.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gtlxgxozwa.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenzaomai.com/Article/details/gtybxotdxz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjjmoxmz.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gtnnhpuapf.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gtedxzkyvm.html

Java: resp.statusCode()
来源：http://dali.9152youxi.cn/Article/details/gtfrqsraco.html

Go:   resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gtiulsqpmk.html

Ruby: resp.code.to_i
来源：http://dali.yvedp.cn/Article/details/gtibkampgb.html

C#:   (int)resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gtqijyradu.html

[L08] 并发请求多个地址
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrqnvfcq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhoulong.xyz/Article/details/gtkqokroun.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangdashe.top/Article/details/gtomezcbnh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gtytlyxtdb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gtksrewide.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258.top/Article/details/gthezxzcll.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj202588.top/Article/details/gtcdggsxza.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.iojbl.cn/Article/details/gtaxohagqc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.vqdsnc.cn/Article/details/gtvzjmdjcm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtkfcwlmzl.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangdashe.top/Article/details/gtllrirzas.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtcndwcaam.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtlswdeyit.html

Py:   sys.argv[1:]
来源：http://dali.yuxming.cn/Article/details/gtxucbgehf.html

PHP:  $argv;  $argc;
来源：http://dali.gaohongyu789.top/Article/details/gtocitvvit.html

JS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gtqqnzikrq.html

TS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gtjkvcwoko.html

Java: args 数组（main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gtuhqiulkj.html

Go:   os.Args[1:]
来源：http://dali.cucudq.cn/Article/details/gticghfxiw.html

Ruby: ARGV
来源：http://dali.zhiwuduotai.top/Article/details/gtruboanmq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gtuigbhnaq.html

[M02] 读取环境变量
来源：http://dali.ydzc1.top/Article/details/gtdjhxings.html

Py:   os.environ.get("HOME")
来源：http://dali.daxiang520.top/Article/details/gtrvhoqwfm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shanyushiyangtech.top/Article/details/gttvialnan.html

JS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gtvtokglvr.html

TS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gtlwxjqpeu.html

Java: System.getenv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gterygxghh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258.top/Article/details/gtwpaprklt.html

Ruby: ENV["HOME"]
来源：http://dali.cdnleiting.top/Article/details/gtojlfwenj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj202588.top/Article/details/gtyzhpbsjw.html

[M03] 执行外部命令
来源：http://dali.hongshengwenyu.top/Article/details/gtyrvzpgms.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.redwolf501.top/Article/details/gtghmfgrhc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nwbrower.top/Article/details/gtrevbaqok.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cashguo.top/Article/details/gtcgswnutk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cashguo.top/Article/details/gtbxldypva.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgfzy.top/Article/details/gtxszfyefy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tianlin.xyz/Article/details/gtqkggxibf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.bjfxy.top/Article/details/gtglkdrboi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.dianchejie.cn/Article/details/gtyzpkftoq.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gtduderzjh.html

Py:   os.getcwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigcvqrmm.html

PHP:  getcwd();
来源：http://dali.hfpthk.cn/Article/details/gtcjygfckm.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gtiguatqzg.html

TS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gteeaxslfw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.feifeiyinyue.top/Article/details/gtzvyqfjqb.html

Go:   os.Getwd()
来源：http://dali.jiagoushi.top/Article/details/gtwchpwbsw.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gtbqykcwut.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgufenzy.top/Article/details/gtfzripcdt.html

[M05] 设置退出码
来源：http://dali.ppjwa.cn/Article/details/gtmhhwobwa.html

Py:   sys.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtgplldxjk.html

PHP:  exit(1);
来源：http://dali.wangdashe.top/Article/details/gtwmkhpygy.html

JS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtlwtipeyg.html

TS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtrarbcgab.html

Java: System.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtmssptwxn.html

Go:   os.Exit(1)
来源：http://dali.sxryk.cn/Article/details/gtskfxnlgt.html

Ruby: exit 1
来源：http://dali.wangdashe.top/Article/details/gtheyjtmxd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhoulong.xyz/Article/details/gtfmudrnwu.html

[M06] 向标准错误输出
来源：http://dali.bjfxy.top/Article/details/gtdpstekux.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwtwzormu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.kuanghao11.cn/Article/details/gtrfqknbms.html

JS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtgtdhvhol.html

TS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtrnbifzdx.html

Java: System.err.println("err")
来源：http://dali.kuanghao11.cn/Article/details/gtsfqaymep.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ybcxt.top/Article/details/gtyopqgycs.html

Ruby: warn "err"
来源：http://dali.hywenlv.cn/Article/details/gtbtxwsnxx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.havefunace.top/Article/details/gthjwhwjrw.html

[M07] 判断是否为主入口
来源：http://dali.tian-w.cn/Article/details/gtqionoybq.html

Py:   if __name__ == "__main__":
来源：http://dali.bjfxy.top/Article/details/gtpnqedmbg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigfzy.top/Article/details/gtzoerksix.html

JS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gtpvwfpope.html

TS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gthrgmhbiy.html

Java: public static void main(String[] args)
来源：http://dali.yj20258.top/Article/details/gtuexjjjih.html

Go:   func main()
来源：http://dali.tanke756.top/Article/details/gttfftpjkr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangdashe.top/Article/details/gtaurdvodl.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigfzy.top/Article/details/gtzzpongyl.html

[M08] 获取系统与运行时信息
来源：http://dali.pengpengdd.cyou/Article/details/gtrdgdungg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuetiantiany.cn/Article/details/gtijqnzblu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gtsjnxaoeu.html

JS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gtlnebnbwu.html

TS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gttecbexxk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sweek.top/Article/details/gtwbnomquy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guannengcc.top/Article/details/gtjmvyltsx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xziqi.cn/Article/details/gtktqrrfki.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangdashe.top/Article/details/gtkljjipjr.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtleiypxqw.html

N. 数据结构与算法
来源：http://dali.zhengqikj.top/Article/details/gtvjqlrlgt.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtbpolvzdj.html

[N01] 二分查找（有序数组）
来源：http://dali.cqqwz.cn/Article/details/gthrwavxjv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtbdghilky.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj202588.top/Article/details/gtpseixfks.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gtnpyrheuk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gtgzygzute.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtqymqhyyd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwdpxgyn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.c1oappe.top/Article/details/gttqqaqpsm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtmxnuyvwt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.iojbl.cn/Article/details/gtbgawwmkz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gtspjtlrxa.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nwbrower.top/Article/details/gtqabmhxhd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gttmsvcoao.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gtorvduwik.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yueranfly.top/Article/details/gtuxakbgpf.html

Go:   slices.Sort(arr)
来源：http://dali.hammf.cn/Article/details/gtfxnsfvdw.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gtejrekrom.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwinejqm.html

[N03] 快速排序（分治示例）
来源：http://dali.yj20258.top/Article/details/gtezaxcjsr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.kuanghao11.cn/Article/details/gtikjxvkja.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yueranfly.top/Article/details/gtsqynrbiz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gtodlzcdma.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gtchdxbrfp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtqicgvtde.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shangyingyoupin.top/Article/details/gtqjyvhlxx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sufxvd.cn/Article/details/gtehwckcfi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aibaodan.cn/Article/details/gtxvptwxbs.html

[N04] 斐波那契数列
来源：http://dali.cdnleiting.top/Article/details/gtqlwkwgmy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gthvhklodw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.iojbl.cn/Article/details/gtdlptndwy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtfgydjggk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtioyjgejl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuanzx.com/Article/details/gtrboitexk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.316326.xyz/Article/details/gtwsovmrlp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggdmztec.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtfgtawbqf.html

[N05] 最大公约数
来源：http://dali.havefunace.top/Article/details/gtvarzpnwt.html

Py:   math.gcd(a, b)
来源：http://dali.yueranfly.top/Article/details/gtxfwphiog.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtztkkazkx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gtpajuelfo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gtbtltrjik.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zdqjudy.top/Article/details/gtjbzirjsd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yvedp.cn/Article/details/gtpgnyutsd.html

Ruby: a.gcd(b)
来源：http://dali.yj20258.top/Article/details/gtxjoinxeo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.smart0.xyz/Article/details/gtdbcroeqf.html

[N06] 判断回文字符串
来源：http://dali.nanxinkj.top/Article/details/gttauisntf.html

Py:   s == s[::-1]
来源：http://dali.c1oappe.top/Article/details/gtwqfgjyas.html

PHP:  $s === strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gtrmxwvbbr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtsvooasil.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtpckviamj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenzaomai.com/Article/details/gtzwulyryl.html

Go:   // 双指针从两端比较
来源：http://dali.0kj1m.cn/Article/details/gtlymzduuo.html

Ruby: s == s.reverse
来源：http://dali.jqgfzy.top/Article/details/gtbdfdzhkn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gtwuatvraj.html

[N07] 两数之和（返回下标）
来源：http://dali.zdqjudy.top/Article/details/gtmfrpfkvl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jianghu66.top/Article/details/gturozlamg.html


<!-- 参考信息 -->