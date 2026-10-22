代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shuidangran.top/Article/details/gtmzyfgpdz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jianghu66.top/Article/details/gttnyrfrcj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pycfn.com/Article/details/gtaqgmgumf.html

[J10] 取今天 / 本月第一天
来源：http://dali.yvedp.cn/Article/details/gtipqagkvu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ivvv.top/Article/details/gtmmrhducf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xziqi.cn/Article/details/gtewnefwjd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gaohongyu789.top/Article/details/gtcewlbmbp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtnswharap.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoktshfbb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ivvv.top/Article/details/gtqpnezdky.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fengsongda.top/Article/details/gtlljxkxdo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigfzy.top/Article/details/gthwnoiydz.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtofgrqdoc.html

K. JSON 与序列化
来源：http://dali.redwolf501.top/Article/details/gttjtqbzoy.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtopzvtedr.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkpbkyfb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgynvwlu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnmaxwsn.html

JS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gtvvijsstw.html

TS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtybtsfgnn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xylfe.cn/Article/details/gtaaooueaz.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtddjpujng.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tian-w.cn/Article/details/gtoyrorjfp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xylfe.cn/Article/details/gtlufsrval.html

[K02] JSON 字符串转对象
来源：http://dali.zhiwuduotai.top/Article/details/gtmyciatbb.html

Py:   json.loads(s)
来源：http://dali.zhongyouzk.top/Article/details/gtilvtxych.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.iojbl.cn/Article/details/gtszihpfgm.html

JS:   JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gtnsatkmlk.html

TS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gthdabqama.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtorjjghsm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gtftnjdkft.html

Ruby: JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtzsyjcgze.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hfpthk.cn/Article/details/gtmotborvz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpgzudjx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gtfcgfhjle.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gtxycjlyfr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizbzvorz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gtrwleiagw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.andypj.xyz/Article/details/gtgacbxdui.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxuanxn.top/Article/details/gtxlwvsqts.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cashguo.top/Article/details/gttiukclmz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shangyingyoupin.top/Article/details/gtdxqdhpqa.html

[K04] 读取 JSON 文件
来源：http://dali.nanxinkj.top/Article/details/gthidfowfj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.redwolf501.top/Article/details/gtoccijoui.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jiagoushi.top/Article/details/gtiqnddzgw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gtlfnercyx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gtebabljpn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gtfmugltnj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gtcdrvpwvz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yueranfly.top/Article/details/gtwvaqddxc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gtjabmincq.html

[K05] 深拷贝对象
来源：http://dali.xziqi.cn/Article/details/gtmrenydjd.html

Py:   copy.deepcopy(obj)
来源：http://dali.aizwys.cn/Article/details/gtkoqfyorq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hywenlv.cn/Article/details/gtikfugmwq.html

JS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtckccihxr.html

TS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtwqeojqgj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.kuanghao11.cn/Article/details/gtguhhxfil.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sufxvd.cn/Article/details/gtkllypnsv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojnsvdzi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgfzy.top/Article/details/gthdpizoaf.html

[K06] 解析 URL 查询串
来源：http://dali.nanxuanxn.top/Article/details/gtawuzdgoe.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.c1oappe.top/Article/details/gtsihvzgkr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.c1oappe.top/Article/details/gtksgeinhq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhcblizk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gtzdgungdj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenlongwang.top/Article/details/gtobgomwig.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtkjmhrgvo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtsqodfvtj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtnhpqbqmu.html

[K07] 进制转换
来源：http://dali.jyoumei.cn/Article/details/gtowpzcsks.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtyyzwjqfw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cheryme.top/Article/details/gtawjljbsq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtbhsuiqqo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtsogrlaho.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gthrvytavf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqcyithu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.havefunace.top/Article/details/gtwaxrxnek.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtlghrlhod.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.iojbl.cn/Article/details/gthrrshhcx.html

Py:   pickle.dumps(obj)
来源：http://dali.jiagoushi.top/Article/details/gtbwkbkoap.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.smart0.xyz/Article/details/gtnltvjxzp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gttblerlrv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gtwpnfnvjg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ehwqpu.com/Article/details/gtjjcgtqsl.html

Go:   encoding/gob
来源：http://dali.jinqigufen.top/Article/details/gtkabmzjfz.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmnilwxr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gtnsvsdnma.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtduskdfbc.html

L. 网络请求
来源：http://dali.zhengqikj.top/Article/details/gtyodrmlny.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtjbgbprxb.html

[L01] 发送 GET 请求
来源：http://dali.hammf.cn/Article/details/gtfafluihl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ydzc1.top/Article/details/gtcgvshkjb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jiagoushi.top/Article/details/gtdnxrfakc.html

JS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gtbgynspuh.html

TS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gteppsdopj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.vqdsnc.cn/Article/details/gtnowoqxpp.html

Go:   resp, err := http.Get(url)
来源：http://dali.gotoacloud.top/Article/details/gtwvybedmp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.snrcjt.cn/Article/details/gtwkywwuar.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hysaishi.cn/Article/details/gtiuuvpypp.html

[L02] 发送 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gtitghvgpd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.pengpengdd.cyou/Article/details/gtqifobeui.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigfzy.top/Article/details/gtyejpjkpm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gtffwqphhi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gtpximwezl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.bjfxy.top/Article/details/gtlwkwdrly.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.mhx1999.top/Article/details/gtvpipmwsz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guowangkeji.top/Article/details/gttcgicrlh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daxiang520.top/Article/details/gtypgvhpdu.html

[L03] 设置自定义请求头
来源：http://dali.jyoumei.cn/Article/details/gteonxbcls.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.c1oappe.top/Article/details/gtxohbvkxz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtveazpgyd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtgapsfykt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gtfpkwagsr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.meibo888.top/Article/details/gtbznwmnjf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gtjprxezcs.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhoulong.xyz/Article/details/gtmphtdrsk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gtufovxcua.html

[L04] 设置超时
来源：http://dali.aibaodan.cn/Article/details/gtqqfhzqhx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cucudq.cn/Article/details/gtryphbmjz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenzaomai.com/Article/details/gtbvwqjkiu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gtiswfvgzc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gticypshef.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gotoacloud.top/Article/details/gtyzwikicg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqwnyuec.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuetiantiany.cn/Article/details/gtgostgnas.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aizwys.cn/Article/details/gtaazheaqn.html

[L05] 上传文件（multipart）
来源：http://dali.c1oappe.top/Article/details/gtwgjnoklx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangshuangyany.cn/Article/details/gthjosnmbx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhixingplan.top/Article/details/gtupsfnlzn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkqzepzz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gtfabidboj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258.top/Article/details/gtnqvrzojs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xziqi.cn/Article/details/gtxnkktkhw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ppjwa.cn/Article/details/gteirnbhfg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jianghu66.top/Article/details/gtccpnlcsy.html

[L06] 解析响应为 JSON
来源：http://dali.jlsjyb.cn/Article/details/gtnsjgwwwk.html

Py:   resp.json()
来源：http://dali.cashguo.top/Article/details/gtluoonskm.html

PHP:  json_decode($body, true);
来源：http://dali.sufxvd.cn/Article/details/gtnsanpnbp.html

JS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtqdjjnvwh.html

TS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gtwpncinsl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daria6918.cn/Article/details/gtxbpkernn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sysykeji.top/Article/details/gtllltromb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gogol.net.cn/Article/details/gtvpnrafvw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtdbcwkycq.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gtnlsirrdn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ydzc1.top/Article/details/gtcvyroilo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.meibo888.top/Article/details/gtceyylliy.html

JS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gtlbcbhmth.html

TS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gtmkjocnyn.html

Java: resp.statusCode()
来源：http://dali.guowangkeji.top/Article/details/gtcauqhwkt.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gtzchdtbgw.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gtahvxunmp.html

C#:   (int)resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gtnehapufd.html

[L08] 并发请求多个地址
来源：http://dali.svipenyu.cn/Article/details/gtmyfaetbf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthaevfwus.html

PHP:  curl_multi_init() 系列
来源：http://dali.316326.xyz/Article/details/gtcdaetldr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtgtfsajrr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtznwwauhe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.vqdsnc.cn/Article/details/gtydqedzgo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinghuilouyu.cn/Article/details/gtksacblzo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gogol.net.cn/Article/details/gthkvnhvhd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ehwqpu.com/Article/details/gtdzqtrivs.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtusttwked.html

M. 命令行 / 进程 / 环境
来源：http://dali.yongpay.top/Article/details/gtfpuwrdxi.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtvyuxhhpw.html

[M01] 读取命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gtbpeskhup.html

Py:   sys.argv[1:]
来源：http://dali.hysaishi.cn/Article/details/gtgfmwmvqk.html

PHP:  $argv;  $argc;
来源：http://dali.jqgfzy.top/Article/details/gttjwqtzlv.html

JS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gtjoefzehl.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gtgiticizw.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtfpqvdsjz.html

Go:   os.Args[1:]
来源：http://dali.yj20258.top/Article/details/gtathssfbh.html

Ruby: ARGV
来源：http://dali.hysaishi.cn/Article/details/gtsdjbtthj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtfzhlwxyr.html

[M02] 读取环境变量
来源：http://dali.smart0.xyz/Article/details/gtorfpfcwp.html

Py:   os.environ.get("HOME")
来源：http://dali.c1oappe.top/Article/details/gtrvoihfqp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gtkupusmuy.html

JS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtylsxldtd.html

TS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gtmeismetq.html

Java: System.getenv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtzqrzzcuc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.birdmap.top/Article/details/gteorjvcxk.html

Ruby: ENV["HOME"]
来源：http://dali.pengpengdd.cyou/Article/details/gtacrlenoh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shuidangran.top/Article/details/gtzddpkary.html

[M03] 执行外部命令
来源：http://dali.pycfn.com/Article/details/gtyqpbdwqe.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxinkj.top/Article/details/gthejfdljd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tian-w.cn/Article/details/gttsnmdndn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtnngsxgvm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtvuznbizu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gtywubmtak.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.316326.xyz/Article/details/gtuwhdxsqt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ydzc1.top/Article/details/gtghgdojdo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jyoumei.cn/Article/details/gtjuhuwjxw.html

[M04] 获取当前工作目录
来源：http://dali.xuetiantiany.cn/Article/details/gtgqlqwjva.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gtxnuxvnku.html

PHP:  getcwd();
来源：http://dali.fengsongda.top/Article/details/gtrvfcypmv.html

JS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxagvzidm.html

TS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gtbetpubas.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwtfxdrs.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gtpkxofnyt.html

Ruby: Dir.pwd
来源：http://dali.birdmap.top/Article/details/gtffiuvumw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ehwqpu.com/Article/details/gttysurhme.html

[M05] 设置退出码
来源：http://dali.tian-w.cn/Article/details/gtlkzkjpwn.html

Py:   sys.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtgbtfxfci.html

PHP:  exit(1);
来源：http://dali.iojbl.cn/Article/details/gtwuknbmtl.html

JS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gtildzfvyp.html

TS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtzsdvjtgv.html

Java: System.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtfjxaxolk.html

Go:   os.Exit(1)
来源：http://dali.wangdashe.top/Article/details/gtbqquwrqm.html

Ruby: exit 1
来源：http://dali.yanxiufei.cn/Article/details/gtafzwgutu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.iojbl.cn/Article/details/gtknbujkkd.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gtsjzcqwtp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gtnabbkcjs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sufxvd.cn/Article/details/gtekfqzlob.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtamaxbkdu.html

TS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gtobisbxvm.html

Java: System.err.println("err")
来源：http://dali.yj20258888.top/Article/details/gtzxxbfpkk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258888.top/Article/details/gtzhbaqoqm.html

Ruby: warn "err"
来源：http://dali.zhixingplan.top/Article/details/gtwthovyqw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sysykeji.top/Article/details/gtzmcjkonk.html

[M07] 判断是否为主入口
来源：http://dali.guannengcc.top/Article/details/gtenaiytwf.html

Py:   if __name__ == "__main__":
来源：http://dali.feifeiyinyue.top/Article/details/gtaaxeacoq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gtphhuedck.html

JS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gttnqageou.html

TS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gtygputizu.html

Java: public static void main(String[] args)
来源：http://dali.cdnleiting.top/Article/details/gtrknwsodb.html

Go:   func main()
来源：http://dali.xylfe.cn/Article/details/gtekgmsuwz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhiwuduotai.top/Article/details/gtulmsuglr.html

C#:   static void Main(string[] args)
来源：http://dali.yuxming.cn/Article/details/gtvdhgpiul.html

[M08] 获取系统与运行时信息
来源：http://dali.svipenyu.cn/Article/details/gttosqnrkn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cucudq.cn/Article/details/gtmgnvhhrj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sxryk.cn/Article/details/gtldupktfz.html

JS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtfjktrnfg.html

TS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gtznozohaf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.kuanghao11.cn/Article/details/gtdijmklqn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fzhhl.top/Article/details/gtcmgearku.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ydzc1.top/Article/details/gtouxpbasn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.birdmap.top/Article/details/gtcyxdlhne.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtofwdnxgt.html

N. 数据结构与算法
来源：http://dali.dianchejie.cn/Article/details/gtsyjkcyps.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtqcvivwet.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfqqnqma.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtcovbakfb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gtcncjjrgj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaydsntda.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtlervtjrp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtwnwavcni.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtdyambnpj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ybcxt.top/Article/details/gtcepcvzfy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtytgccuse.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.fzhhl.top/Article/details/gtyknicqyi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gthouwflwv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yangfankeji.com/Article/details/gtzhlwjzqo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttlmveiky.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtrlpesnxg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xziqi.cn/Article/details/gtxynnadjj.html

Go:   slices.Sort(arr)
来源：http://dali.bjfxy.top/Article/details/gtuzpmpvdd.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gtnnajjdhf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aizwys.cn/Article/details/gtvodkqltg.html

[N03] 快速排序（分治示例）
来源：http://dali.cqqwz.cn/Article/details/gtauoxqncq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cucudq.cn/Article/details/gthoglxjxr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.guowangkeji.top/Article/details/gttzhydhtb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gtrvegdrrp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gtfsbvbnzn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ppjwa.cn/Article/details/gtyarbnizl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gogol.net.cn/Article/details/gttvhpgkfl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gotoacloud.top/Article/details/gtxhplaqsv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgufenzy.top/Article/details/gthsggsppx.html

[N04] 斐波那契数列
来源：http://dali.hammf.cn/Article/details/gtadyequsi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtdczhbdsa.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gtnzbiaksz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtulgqgdnp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gtectmpcaa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gtwbqydumj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sweek.top/Article/details/gtnhorrlvp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cdnleiting.top/Article/details/gtbokrrzhb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtcmjbcuhe.html

[N05] 最大公约数
来源：http://dali.meibo888.top/Article/details/gtfhlloeyf.html

Py:   math.gcd(a, b)
来源：http://dali.meibo888.top/Article/details/gttoberdvi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.redwolf501.top/Article/details/gtmzdxfoni.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shuidangran.top/Article/details/gtbfhyiraz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtvwsydzmq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.haohaochexian.top/Article/details/gtftcuznjl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuanzhike.top/Article/details/gtgkecgewh.html

Ruby: a.gcd(b)
来源：http://dali.yueranfly.top/Article/details/gtagwjruua.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ehwqpu.com/Article/details/gtyvmptbko.html

[N06] 判断回文字符串
来源：http://dali.jlsjyb.cn/Article/details/gtjwcspluq.html

Py:   s == s[::-1]
来源：http://dali.sweek.top/Article/details/gtfzpdipsg.html

PHP:  $s === strrev($s);
来源：http://dali.ybcxt.top/Article/details/gtfucfpuxv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtcdihodmr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtllmbekpd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj20258.top/Article/details/gtvgcypfhi.html

Go:   // 双指针从两端比较
来源：http://dali.havefunace.top/Article/details/gtqmffumzk.html

Ruby: s == s.reverse
来源：http://dali.c1oappe.top/Article/details/gtonpdpoui.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gtzawzjvel.html

[N07] 两数之和（返回下标）
来源：http://dali.xinyue.icu/Article/details/gtoxyvcphl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.redwolf501.top/Article/details/gtkoeetnrb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkhgwqgp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.fzhhl.top/Article/details/gtwzssfbov.html

TS:   // 手写 Map<string, number>
来源：http://dali.shzxlz.cn/Article/details/gtsqcgweib.html

Java: // 手写 HashMap
来源：http://dali.jinqigfzy.top/Article/details/gttjuprktq.html


<!-- 参考信息 -->