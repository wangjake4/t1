代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shuidangran.top/Article/details/gt2vonqgyzh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jqgfzy.top/Article/details/gt2nmzvmbvl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.kuanghao11.cn/Article/details/gt2sdmxkkie.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuetiantiany.cn/Article/details/gt2omkfksuw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.svipenyu.cn/Article/details/gt2bdkhvqhe.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuxming.cn/Article/details/gt2behwozao.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258.top/Article/details/gt2czzibdef.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2talegyhl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhixingplan.top/Article/details/gt2rrlonwjb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nwbrower.top/Article/details/gt2hrfbsbfy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xziqi.cn/Article/details/gt2rtffvfgv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgfzy.top/Article/details/gt2jlmoudbh.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cvlcaepf.html

K. JSON 与序列化
来源：http://dali.xuetiantiany.cn/Article/details/gt2zptuiwrw.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ttyszrzt.html

[K01] 对象转 JSON 字符串
来源：http://dali.tanke756.top/Article/details/gt2fwcwuent.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gt2rhvrizly.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gt2pdlmdmgj.html

JS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2anjbdwkl.html

TS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lqyslzpa.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gotoacloud.top/Article/details/gt2sopqrunh.html

Go:   json.Marshal(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2ninknbrw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenlongwang.top/Article/details/gt2hfqkrxdm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2seuukhzg.html

[K02] JSON 字符串转对象
来源：http://dali.vqdsnc.cn/Article/details/gt2briwlniw.html

Py:   json.loads(s)
来源：http://dali.yj20258888.top/Article/details/gt2iwenlmdx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnqzz.top/Article/details/gt2xmpciylq.html

JS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gt2ytzngkgp.html

TS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gt2taeyasns.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yafmefmk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gt2gegqfniy.html

Ruby: JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gt2vozipvgq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ybcxt.top/Article/details/gt2dmtjrjhq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxuanxn.top/Article/details/gt2pduqhslg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gt2kldbjupg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gt2xdiddhev.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zwlgcixy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qtvzwqiu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2vptayuta.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pycfn.com/Article/details/gt2aclbodkj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ahrntmtz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.316326.xyz/Article/details/gt2wneeroav.html

[K04] 读取 JSON 文件
来源：http://dali.zdqjudy.top/Article/details/gt2zfpywlgo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.0kj1m.cn/Article/details/gt2jeilhkzs.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.9152youxi.cn/Article/details/gt2utmkhsnq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2nngqfykd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gt2mrzepstg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guannengcc.top/Article/details/gt2wesnrqld.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gt2vtihqclo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258.top/Article/details/gt2fdfnbbgf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2jzkkmhza.html

[K05] 深拷贝对象
来源：http://dali.birdmap.top/Article/details/gt2afyfhwjd.html

Py:   copy.deepcopy(obj)
来源：http://dali.meibo888.top/Article/details/gt2fxhgkswq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sufxvd.cn/Article/details/gt2tytvorzt.html

JS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gt2idhhvhyi.html

TS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2byfmbchr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pengpengdd.cyou/Article/details/gt2axnadxca.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxuanxn.top/Article/details/gt2bgtksbui.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gaohongyu789.top/Article/details/gt2beqkgven.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigufen.top/Article/details/gt2ktdydnmx.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258.top/Article/details/gt2nuzpmuzt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jianghu66.top/Article/details/gt2danxnecy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhoulong.xyz/Article/details/gt2wzvhunlt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gt2pqfieeit.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aabgcbww.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rpgbscyi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gt2ridhgmml.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gt2mfhidnud.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gt2apjkeqcu.html

[K07] 进制转换
来源：http://dali.yj202588.top/Article/details/gt2hyawiafb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2vbkmkflh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhiwuduotai.top/Article/details/gt2fpbtnljl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2vmiwtyxl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2bajtbxos.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gt2pvqsheud.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nwbrower.top/Article/details/gt2rzfwmrvr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2edrntwyj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2ofyprsip.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.snrcjt.cn/Article/details/gt2jmroelkg.html

Py:   pickle.dumps(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2hfmdfzqx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.9152youxi.cn/Article/details/gt2hadhuvmn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gt2mnmpjcgy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gt2jylrktwx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cheryme.top/Article/details/gt2ejgaiykk.html

Go:   encoding/gob
来源：http://dali.havefunace.top/Article/details/gt2ieekxjah.html

Ruby: Marshal.dump(obj)
来源：http://dali.fengsongda.top/Article/details/gt2uvyvelpn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gt2mxrbpvyd.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2xnciytam.html

L. 网络请求
来源：http://dali.ehwqpu.com/Article/details/gt2ctgdudft.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2dydwcqkj.html

[L01] 发送 GET 请求
来源：http://dali.nanxinkj.top/Article/details/gt2rlifjahc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fengsongda.top/Article/details/gt2bmjxdqmu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnxiangtu.top/Article/details/gt2neyfeqbb.html

JS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gt2mbopvdfc.html

TS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gt2llbfdxxx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.smart0.xyz/Article/details/gt2kxuibxlq.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhoulong.xyz/Article/details/gt2izsmsqll.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yonumen.top/Article/details/gt2fskarykw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tian-w.cn/Article/details/gt2xywnvdqr.html

[L02] 发送 POST JSON
来源：http://dali.fengsongda.top/Article/details/gt2aeaecogc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ivvv.top/Article/details/gt2vlcmjpcn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guowangkeji.top/Article/details/gt2tzijmjhn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gt2cabdtcjz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gt2btyrtbnq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yvedp.cn/Article/details/gt2fgnjmesw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zdqjudy.top/Article/details/gt2dzwrjlgb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ehwqpu.com/Article/details/gt2wxwrgbzf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cheryme.top/Article/details/gt2eqbmrobt.html

[L03] 设置自定义请求头
来源：http://dali.nanxuanxn.top/Article/details/gt2ohmcjxnw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuanzx.com/Article/details/gt2tvjihkhz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258.top/Article/details/gt2gaaphcko.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gt2pmiionag.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gt2orexqowu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ylfmfzxn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gt2lumqtzjx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tanke756.top/Article/details/gt2hishxcht.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gt2lexxzdcc.html

[L04] 设置超时
来源：http://dali.hongshengwenyu.top/Article/details/gt2lfixjoik.html

Py:   requests.get(url, timeout=5)
来源：http://dali.meibo888.top/Article/details/gt2uiagerxy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xylfe.cn/Article/details/gt2ksnegrif.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gt2xxodjhgk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnqzz.top/Article/details/gt2yrutzfmn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aysjjhbk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhixingplan.top/Article/details/gt2snutubwe.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.316326.xyz/Article/details/gt2noeosjyx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jyoumei.cn/Article/details/gt2ryywpwxd.html

[L05] 上传文件（multipart）
来源：http://dali.hfpthk.cn/Article/details/gt2fmkeolib.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.vqdsnc.cn/Article/details/gt2rsxfacdl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.vqdsnc.cn/Article/details/gt2hicsnpdr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gt2sufxspsf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gt2thvrqppz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigfzy.top/Article/details/gt2wfymtkwp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cucudq.cn/Article/details/gt2xbggzyda.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hywenlv.cn/Article/details/gt2siboxveg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2rthkhwik.html

[L06] 解析响应为 JSON
来源：http://dali.shangyingyoupin.top/Article/details/gt2vyvibjhq.html

Py:   resp.json()
来源：http://dali.yuanzhike.top/Article/details/gt2fymcymqb.html

PHP:  json_decode($body, true);
来源：http://dali.jqgfzy.top/Article/details/gt2wobhznjh.html

JS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gt2fzobfjei.html

TS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gt2eaukvenc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ppjwa.cn/Article/details/gt2tycnunmg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.redwolf501.top/Article/details/gt2lavuztfp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sufxvd.cn/Article/details/gt2dfplxilo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zycfv.cn/Article/details/gt2wjpgfyjb.html

[L07] 处理 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gt2uatxbelm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sufxvd.cn/Article/details/gt2mwvhzecb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gaohongyu789.top/Article/details/gt2kswtwfsq.html

JS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gt2ifxebtln.html

TS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gt2dljojncb.html

Java: resp.statusCode()
来源：http://dali.redwolf501.top/Article/details/gt2qbmnclva.html

Go:   resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gt2xevvbqxw.html

Ruby: resp.code.to_i
来源：http://dali.iojbl.cn/Article/details/gt2feciygbi.html

C#:   (int)resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gt2yvhhjxbc.html

[L08] 并发请求多个地址
来源：http://dali.tanke756.top/Article/details/gt2cuvmifag.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2krthxueh.html

PHP:  curl_multi_init() 系列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cspvwqzo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gt2rezvlfwg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gt2dtkifxum.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xinyue.icu/Article/details/gt2nfnjpcfa.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yueranfly.top/Article/details/gt2dvnwmlcn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258888.top/Article/details/gt2lavbxcgh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.svipenyu.cn/Article/details/gt2vebdquov.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2oqwdfzib.html

M. 命令行 / 进程 / 环境
来源：http://dali.snrcjt.cn/Article/details/gt2enjcjhvq.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2xpjhmbve.html

[M01] 读取命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gt2zhqhnkcn.html

Py:   sys.argv[1:]
来源：http://dali.zhixingplan.top/Article/details/gt2gnmhbbsz.html

PHP:  $argv;  $argc;
来源：http://dali.andypj.xyz/Article/details/gt2ndiyfogf.html

JS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gt2cehkegqd.html

TS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gt2igiydqzo.html

Java: args 数组（main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fuqrmeop.html

Go:   os.Args[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pdnofcqd.html

Ruby: ARGV
来源：http://dali.tian-w.cn/Article/details/gt2iinfwgrz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gt2nwkxzwfw.html

[M02] 读取环境变量
来源：http://dali.yj20258.top/Article/details/gt2vbniowtc.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bunxbdne.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gt2beqhfezs.html

JS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gt2kfsdgtwl.html

TS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gt2ozshysqx.html

Java: System.getenv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gt2cysjoyyv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cheryme.top/Article/details/gt2hsbqfbst.html

Ruby: ENV["HOME"]
来源：http://dali.aibaodan.cn/Article/details/gt2fminbkyt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2phkpjumg.html

[M03] 执行外部命令
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2baawwnxb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cheryme.top/Article/details/gt2wffijlfg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nwbrower.top/Article/details/gt2uaqqnvhx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gt2zgibxkvb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gt2bovuramk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuetiantiany.cn/Article/details/gt2oxuffjon.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuanzhike.top/Article/details/gt2ngapymmn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ydzc1.top/Article/details/gt2avantakb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guowangkeji.top/Article/details/gt2rpgovlns.html

[M04] 获取当前工作目录
来源：http://dali.hnxiangtu.top/Article/details/gt2gibxfxsw.html

Py:   os.getcwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gdpxorrh.html

PHP:  getcwd();
来源：http://dali.kuanghao11.cn/Article/details/gt2aopoxuly.html

JS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gt2ybhtzvzv.html

TS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gt2dqkkzuta.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jianghu66.top/Article/details/gt2noyknwqd.html

Go:   os.Getwd()
来源：http://dali.nanxuanxn.top/Article/details/gt2ovdadmgs.html

Ruby: Dir.pwd
来源：http://dali.yuanzhike.top/Article/details/gt2pkztmrrh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xinyue.icu/Article/details/gt2zrzsnmgv.html

[M05] 设置退出码
来源：http://dali.jyoumei.cn/Article/details/gt2hnuajcta.html

Py:   sys.exit(1)
来源：http://dali.cashguo.top/Article/details/gt2ahsrrojx.html

PHP:  exit(1);
来源：http://dali.jinqigufen.top/Article/details/gt2abyjufub.html

JS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2cstyvemi.html

TS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2rslzwosw.html

Java: System.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2djefftma.html

Go:   os.Exit(1)
来源：http://dali.havefunace.top/Article/details/gt2agrzavfk.html

Ruby: exit 1
来源：http://dali.quarkkingdee.top/Article/details/gt2zvikcikw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuetiantiany.cn/Article/details/gt2ktdmjtgi.html

[M06] 向标准错误输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oppzagct.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sufxvd.cn/Article/details/gt2otnpbfzv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daxiang520.top/Article/details/gt2hydrwdcf.html

JS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gt2cfrjwbpm.html

TS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gt2hzzykreh.html

Java: System.err.println("err")
来源：http://dali.yuxming.cn/Article/details/gt2mmryyyyq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gogol.net.cn/Article/details/gt2uznxzmpb.html

Ruby: warn "err"
来源：http://dali.guowangkeji.top/Article/details/gt2kakptqjp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigfzy.top/Article/details/gt2gqsqnmwm.html

[M07] 判断是否为主入口
来源：http://dali.yongpay.top/Article/details/gt2fbhruron.html

Py:   if __name__ == "__main__":
来源：http://dali.yuanzhike.top/Article/details/gt2mzvhrrcs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gt2vibdltzy.html

JS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gt2tgjxqidp.html

TS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gt2yeydtwof.html

Java: public static void main(String[] args)
来源：http://dali.tian-w.cn/Article/details/gt2ausvfkde.html

Go:   func main()
来源：http://dali.yj20258.top/Article/details/gt2eizcmwjk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuanzx.com/Article/details/gt2wfwvpani.html

C#:   static void Main(string[] args)
来源：http://dali.sxryk.cn/Article/details/gt2bxsomrrd.html

[M08] 获取系统与运行时信息
来源：http://dali.dashuyun.cn/Article/details/gt2ktrauyvd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgufenzy.top/Article/details/gt2ptbwvisa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.316326.xyz/Article/details/gt2vgwgefhm.html

JS:   process.platform;  process.version
来源：http://dali.yvedp.cn/Article/details/gt2uqtyinzg.html

TS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gt2fxgnbnbc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yangfankeji.com/Article/details/gt2noeelway.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yanxiufei.cn/Article/details/gt2ryzzvpsl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cqqwz.cn/Article/details/gt2kchgckmg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gogol.net.cn/Article/details/gt2ykjorqep.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2fuqsxitk.html

N. 数据结构与算法
来源：http://dali.xylfe.cn/Article/details/gt2gfdycjhc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2xgintpjn.html

[N01] 二分查找（有序数组）
来源：http://dali.jyoumei.cn/Article/details/gt2lqhymrmd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2lmemghxv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dashuyun.cn/Article/details/gt2ayicozae.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gt2vvvjyfhx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gt2zxoddclc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2klnvvjer.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2mnqnrrvy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nvhzjlbn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hdzxuffv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shangyingyoupin.top/Article/details/gt2aluyygvm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangdashe.top/Article/details/gt2hhdgjcmf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sufxvd.cn/Article/details/gt2dzxocqcf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gt2vtbhujcc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gt2ofwtoroi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenlongwang.top/Article/details/gt2irfafpog.html

Go:   slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gt2fovosmmq.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gt2qjutndpp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.0kj1m.cn/Article/details/gt2kgwdlqhc.html

[N03] 快速排序（分治示例）
来源：http://dali.smart0.xyz/Article/details/gt2uecweeiz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daria6918.cn/Article/details/gt2edbqbpcv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daria6918.cn/Article/details/gt2lybttufo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gt2ygspoixb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gt2iciwsnrj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ppjwa.cn/Article/details/gt2ddahctuq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jlsjyb.cn/Article/details/gt2aoiulqnr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sxryk.cn/Article/details/gt2lehsywut.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhixingplan.top/Article/details/gt2pglpbiit.html

[N04] 斐波那契数列
来源：http://dali.ppjwa.cn/Article/details/gt2ctqftsoi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ulvziuld.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gt2lhxpjwvb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gt2hvxhjulk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gt2nutjgvji.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.mhx1999.top/Article/details/gt2amublavh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jyoumei.cn/Article/details/gt2kevuvtdd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2oppymrfh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gt2epnwgyfb.html

[N05] 最大公约数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2regflwfz.html

Py:   math.gcd(a, b)
来源：http://dali.fzhhl.top/Article/details/gt2aukpfeey.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.0kj1m.cn/Article/details/gt2lsirgcrf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gt2nskwymme.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.mhx1999.top/Article/details/gt2fvgnuelj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.mhx1999.top/Article/details/gt2owrcqqzr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258888.top/Article/details/gt2vvleulgn.html

Ruby: a.gcd(b)
来源：http://dali.yuxming.cn/Article/details/gt2krbgqiwl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.vqdsnc.cn/Article/details/gt2zuxvviby.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2annplqon.html

Py:   s == s[::-1]
来源：http://dali.316326.xyz/Article/details/gt2vtsvqgoy.html

PHP:  $s === strrev($s);
来源：http://dali.fengsongda.top/Article/details/gt2nurbdwko.html

JS:   s === [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gt2zdiozilo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2qtqaoskt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tanke756.top/Article/details/gt2dqvvzxls.html

Go:   // 双指针从两端比较
来源：http://dali.ydzc1.top/Article/details/gt2lnrponhl.html

Ruby: s == s.reverse
来源：http://dali.ybcxt.top/Article/details/gt2yahmyqtq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gt2qcntyvzo.html

[N07] 两数之和（返回下标）
来源：http://dali.jlsjyb.cn/Article/details/gt2twyjgpjo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.snrcjt.cn/Article/details/gt2smroohds.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pengpengdd.cyou/Article/details/gt2kvubrlas.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dianchejie.cn/Article/details/gt2jipjfhnb.html

TS:   // 手写 Map<string, number>
来源：http://dali.fengsongda.top/Article/details/gt2uyghedea.html

Java: // 手写 HashMap
来源：http://dali.chenjidiqi.icu/Article/details/gt2ofewtmzp.html


<!-- 参考信息 -->