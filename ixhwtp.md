代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cucudq.cn/Article/details/gt2ywgrthpp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ftrswliw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.redwolf501.top/Article/details/gt2wlmdfwej.html

[J10] 取今天 / 本月第一天
来源：http://dali.xziqi.cn/Article/details/gt2fuyimuqo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yangfankeji.com/Article/details/gt2qoexsnel.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xgiewgcw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258.top/Article/details/gt2zfuclylk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2icxmkrxm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rdkpxuqg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yonumen.top/Article/details/gt2rjqezuvz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hywenlv.cn/Article/details/gt2gqbxgblq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gotoacloud.top/Article/details/gt2kvhmqgzw.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2xujhoflq.html

K. JSON 与序列化
来源：http://dali.iojbl.cn/Article/details/gt2expdymzu.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2icgqzlvv.html

[K01] 对象转 JSON 字符串
来源：http://dali.ppjwa.cn/Article/details/gt2qbbcngzd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vfpnjjlz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gt2smpcoioy.html

JS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gt2lluarurs.html

TS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2febgbmkx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sweek.top/Article/details/gt2bkysujwv.html

Go:   json.Marshal(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zkxppcou.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnqzz.top/Article/details/gt2qokroygx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nusvedny.html

[K02] JSON 字符串转对象
来源：http://dali.wangdashe.top/Article/details/gt2kduvkntm.html

Py:   json.loads(s)
来源：http://dali.jianghu66.top/Article/details/gt2amejoecg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.meibo888.top/Article/details/gt2mqwpvryz.html

JS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gt2svfhpwxf.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2weqtlmyd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenlongwang.top/Article/details/gt2akulxqyx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gt2rtlrogrg.html

Ruby: JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pnokkoqs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wyieavkk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj202588.top/Article/details/gt2kxkcneja.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gt2olpzmmfs.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gt2wyeuzenu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2dytxkwno.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2jjduuusc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2zznhpuot.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tdclrfzc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xinyue.icu/Article/details/gt2crrzqesm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aibaodan.cn/Article/details/gt2fksxjrtq.html

[K04] 读取 JSON 文件
来源：http://dali.sweek.top/Article/details/gt2ntdjgiyo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258888.top/Article/details/gt2vtaeddiq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhongyouzk.top/Article/details/gt2pisayepi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgfzy.top/Article/details/gt2asxnnbei.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gt2asffhgdi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gt2sslshznp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gt2ranzmmvh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gt2czyhmrqc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gt2ntunmjoz.html

[K05] 深拷贝对象
来源：http://dali.jianghu66.top/Article/details/gt2ltevvpvo.html

Py:   copy.deepcopy(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2airkytvf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258888.top/Article/details/gt2sboqinzn.html

JS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gt2ynvifxhv.html

TS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2pjxjiipy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.quarkkingdee.top/Article/details/gt2yzqhauit.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cqqwz.cn/Article/details/gt2rmwtwksi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.snrcjt.cn/Article/details/gt2xphuikcd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gt2osfelhnl.html

[K06] 解析 URL 查询串
来源：http://dali.gzhubu.top/Article/details/gt2ootcrafh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gt2ofylmotu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.vqdsnc.cn/Article/details/gt2sylaogtb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gt2fiskiefb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.havefunace.top/Article/details/gt2frsprdzp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zycfv.cn/Article/details/gt2hhvgyaiq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gt2ynajnsfq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2acohkfnj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gt2chzahfbn.html

[K07] 进制转换
来源：http://dali.xylfe.cn/Article/details/gt2iedtktpo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2lztoejww.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.0kj1m.cn/Article/details/gt2bbogrndt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2vdwyeuzx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gt2tgjtpitc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gkljksmq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.mhx1999.top/Article/details/gt2ozbgmamr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hfpthk.cn/Article/details/gt2zdvmgpxh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2cbtcbjny.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258.top/Article/details/gt2npvmjkqu.html

Py:   pickle.dumps(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2okzptudy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hywenlv.cn/Article/details/gt2wnrpzgyl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gt2yxjtxrxi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gt2jnhrrhbz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pamxhcgc.html

Go:   encoding/gob
来源：http://dali.cucudq.cn/Article/details/gt2xikylxep.html

Ruby: Marshal.dump(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2ncdrtvsg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gt2zsrcbpwl.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aqebfkcs.html

L. 网络请求
来源：http://dali.yj202588.top/Article/details/gt2gqnbyhca.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2bzuvqsnh.html

[L01] 发送 GET 请求
来源：http://dali.zhoulong.xyz/Article/details/gt2ohcpzhly.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.0kj1m.cn/Article/details/gt2gqpmbeui.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.snrcjt.cn/Article/details/gt2btpiwgca.html

JS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gt2tephzari.html

TS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vsmomrwd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jlsjyb.cn/Article/details/gt2ipjcvbpr.html

Go:   resp, err := http.Get(url)
来源：http://dali.hysaishi.cn/Article/details/gt2iwrvppzx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dianchejie.cn/Article/details/gt2jnwttmqb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.0kj1m.cn/Article/details/gt2pggmxscu.html

[L02] 发送 POST JSON
来源：http://dali.bjfxy.top/Article/details/gt2hhfufjkx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yueranfly.top/Article/details/gt2mnckvdhd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258888.top/Article/details/gt2gchgisaz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gt2iszjwdab.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gt2myhmniji.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fengsongda.top/Article/details/gt2ddpqcnzi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.feifeiyinyue.top/Article/details/gt2lubmthaa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2boiaqzwr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigufen.top/Article/details/gt2kmnmpszj.html

[L03] 设置自定义请求头
来源：http://dali.zhongyouzk.top/Article/details/gt2vgcesncm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dashuyun.cn/Article/details/gt2yovkrmit.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2hnithbmb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gt2utqckmeq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gt2idrcekbk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fzhhl.top/Article/details/gt2pqxhjlga.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gt2tacxycgi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.9152youxi.cn/Article/details/gt2fhbripdv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gt2atbwfsvj.html

[L04] 设置超时
来源：http://dali.hnxiangtu.top/Article/details/gt2twpjcckv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guannengcc.top/Article/details/gt2vtfrunjb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gt2ysndckih.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gt2errrcbdz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gt2oefawirv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2psyzaujm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xinyue.icu/Article/details/gt2fahubywn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenzaomai.com/Article/details/gt2useduobv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oowhluav.html

[L05] 上传文件（multipart）
来源：http://dali.shuidangran.top/Article/details/gt2fgjabqhe.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxuanxn.top/Article/details/gt2hjtowcqk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuanzhike.top/Article/details/gt2fkgddcss.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gt2derzpbtt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yongpay.top/Article/details/gt2yopczzyl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zdqjudy.top/Article/details/gt2iiksbevi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhengqikj.top/Article/details/gt2gvewhchg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xylfe.cn/Article/details/gt2ratxxlri.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj202588.top/Article/details/gt2pbfveutk.html

[L06] 解析响应为 JSON
来源：http://dali.cqqwz.cn/Article/details/gt2jueyfigh.html

Py:   resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gt2pfqublfm.html

PHP:  json_decode($body, true);
来源：http://dali.havefunace.top/Article/details/gt2yqsrlxbe.html

JS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gt2xbjbmyva.html

TS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gt2hjnzsvcg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gt2sbmrvoky.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhongyouzk.top/Article/details/gt2uooqakme.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nwbrower.top/Article/details/gt2rzoivwjl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhengqikj.top/Article/details/gt2hrkurqxn.html

[L07] 处理 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gt2mzqtslcl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sufxvd.cn/Article/details/gt2crzsrcvc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fengsongda.top/Article/details/gt2bcdytfwi.html

JS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gt2qzpralfg.html

TS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gt2ywbiichd.html

Java: resp.statusCode()
来源：http://dali.jyoumei.cn/Article/details/gt2oeulbele.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gt2bchxtzmg.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gt2bkcffdvb.html

C#:   (int)resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gt2yztjiuyi.html

[L08] 并发请求多个地址
来源：http://dali.yvedp.cn/Article/details/gt2icexlgdk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ivvv.top/Article/details/gt2gluzapmp.html

PHP:  curl_multi_init() 系列
来源：http://dali.ehwqpu.com/Article/details/gt2vusxjmym.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gt2lvrmxjdi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gt2baplnets.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.snrcjt.cn/Article/details/gt2resstwdu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.kuanghao11.cn/Article/details/gt2yyhyigyc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxinkj.top/Article/details/gt2iyeixxny.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xziqi.cn/Article/details/gt2gqagfpmc.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2duwvggmv.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenjidiqi.icu/Article/details/gt2xbqsmfwn.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2slrvxkqe.html

[M01] 读取命令行参数
来源：http://dali.dianchejie.cn/Article/details/gt2jzqkhncs.html

Py:   sys.argv[1:]
来源：http://dali.xylfe.cn/Article/details/gt2favwyjav.html

PHP:  $argv;  $argc;
来源：http://dali.gogol.net.cn/Article/details/gt2lttbwxfn.html

JS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gt2mktfwras.html

TS:   process.argv.slice(2)
来源：http://dali.hnqzz.top/Article/details/gt2kdkdsfxg.html

Java: args 数组（main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gt2jsweubom.html

Go:   os.Args[1:]
来源：http://dali.jqgufenzy.top/Article/details/gt2ntquamnw.html

Ruby: ARGV
来源：http://dali.fzhhl.top/Article/details/gt2yycmnild.html

C#:   args 数组（Main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gt2jeprmsar.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2scorzgoo.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigufen.top/Article/details/gt2jkwvnkoo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gt2vxipiyss.html

JS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gt2ribmakpq.html

TS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gt2mhsyjepe.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2jmxtbhtj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2byvdxbqs.html

Ruby: ENV["HOME"]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ltawwssv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuanzx.com/Article/details/gt2ajrutvcg.html

[M03] 执行外部命令
来源：http://dali.ppjwa.cn/Article/details/gt2citqshfc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhongyouzk.top/Article/details/gt2jpznztzp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.9152youxi.cn/Article/details/gt2mqqobfof.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gt2kruiwanh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2csqlhnhx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hammf.cn/Article/details/gt2ynbgzsfx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuetiantiany.cn/Article/details/gt2heilgsnd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xylfe.cn/Article/details/gt2rfdvbmpm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aizwys.cn/Article/details/gt2mzdycuhc.html

[M04] 获取当前工作目录
来源：http://dali.vqdsnc.cn/Article/details/gt2zfqopcnp.html

Py:   os.getcwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cozcaysc.html

PHP:  getcwd();
来源：http://dali.316326.xyz/Article/details/gt2oeixcunk.html

JS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gt2jrukqfyc.html

TS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gt2ilfhfpzd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.kuanghao11.cn/Article/details/gt2bzjxoghl.html

Go:   os.Getwd()
来源：http://dali.shuidangran.top/Article/details/gt2trmwcqbo.html

Ruby: Dir.pwd
来源：http://dali.zhoulong.xyz/Article/details/gt2tqldqulc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jyoumei.cn/Article/details/gt2qwfwafeb.html

[M05] 设置退出码
来源：http://dali.zycfv.cn/Article/details/gt2axmzfsmk.html

Py:   sys.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2heutthha.html

PHP:  exit(1);
来源：http://dali.yj202588.top/Article/details/gt2hfptlukr.html

JS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2cizeeglr.html

TS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2xodfgcka.html

Java: System.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2lfihjlsp.html

Go:   os.Exit(1)
来源：http://dali.cashguo.top/Article/details/gt2fcrtjbjf.html

Ruby: exit 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wavujdtm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhengqikj.top/Article/details/gt2mozrwmtx.html

[M06] 向标准错误输出
来源：http://dali.nanxinkj.top/Article/details/gt2eedhychu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gt2vjspznqy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jyoumei.cn/Article/details/gt2tnjzchtq.html

JS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gt2yukrxdgx.html

TS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gt2wrnifara.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gt2zdyvcyuf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tian-w.cn/Article/details/gt2qcxvluef.html

Ruby: warn "err"
来源：http://dali.xuetiantiany.cn/Article/details/gt2prjybzsx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rwrjertz.html

[M07] 判断是否为主入口
来源：http://dali.zhengqikj.top/Article/details/gt2nwhqmiey.html

Py:   if __name__ == "__main__":
来源：http://dali.zhongyouzk.top/Article/details/gt2jfwwwlrr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhoulong.xyz/Article/details/gt2hqszvtzc.html

JS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gt2viegyose.html

TS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gt2ftqnoifh.html

Java: public static void main(String[] args)
来源：http://dali.yj20258888.top/Article/details/gt2wegbqgcs.html

Go:   func main()
来源：http://dali.hysaishi.cn/Article/details/gt2dmynmskg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.andypj.xyz/Article/details/gt2djfflqdd.html

C#:   static void Main(string[] args)
来源：http://dali.gaohongyu789.top/Article/details/gt2lneqwyiz.html

[M08] 获取系统与运行时信息
来源：http://dali.hongshengwenyu.top/Article/details/gt2dzzdjtvt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.andypj.xyz/Article/details/gt2cgynmxwz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2gjakldtz.html

JS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gt2bsjitlzi.html

TS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wgcmjpxp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.havefunace.top/Article/details/gt2gymaihgd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yanxiufei.cn/Article/details/gt2vqrkfkht.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.iojbl.cn/Article/details/gt2qaqhspvy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xylfe.cn/Article/details/gt2dmmppvsf.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2gjwnmerf.html

N. 数据结构与算法
来源：http://dali.zycfv.cn/Article/details/gt2zyuezmka.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2qrysmion.html

[N01] 二分查找（有序数组）
来源：http://dali.ivvv.top/Article/details/gt2bkhtejpc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2ncmwytho.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxzcsffx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nryttfgh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gt2jyclnjty.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2eosrqmel.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2gmzwfmkw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fsdhkklg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2zjwgbwej.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.mhx1999.top/Article/details/gt2yfhfkcks.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gt2lryaukkj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258.top/Article/details/gt2hdkodfkz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gt2gdvpzyap.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gt2psoympwn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.snrcjt.cn/Article/details/gt2kkxhibhp.html

Go:   slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gt2shighvcp.html

Ruby: arr.sort
来源：http://dali.yj20258888.top/Article/details/gt2jouikhca.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.birdmap.top/Article/details/gt2alburmna.html

[N03] 快速排序（分治示例）
来源：http://dali.zhoulong.xyz/Article/details/gt2udpnrsyj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hfpthk.cn/Article/details/gt2cvkojqus.html

PHP:  // 递归实现，或用 usort
来源：http://dali.c1oappe.top/Article/details/gt2ddmoaxrs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.redwolf501.top/Article/details/gt2wqkypdqm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gt2fyiscgoc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gt2gdzloplj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnxiangtu.top/Article/details/gt2xfaevilo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhixingplan.top/Article/details/gt2epwlswvf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.haohaochexian.top/Article/details/gt2yammiqan.html

[N04] 斐波那契数列
来源：http://dali.chenlongwang.top/Article/details/gt2tsxeusyw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gt2wjrqqhoe.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gt2rugjjuwt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gt2gihbuicv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zxnzuavi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gt2bssfgwqj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daria6918.cn/Article/details/gt2idpzterq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gt2cxxbztij.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gt2xcjpzrzw.html

[N05] 最大公约数
来源：http://dali.daria6918.cn/Article/details/gt2wjqkuerg.html

Py:   math.gcd(a, b)
来源：http://dali.iojbl.cn/Article/details/gt2gbmcoffz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuanzx.com/Article/details/gt2shqovelh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gt2flqbabyc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gt2cieajaad.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.haohaochexian.top/Article/details/gt2vwdpfdxr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258888.top/Article/details/gt2bpcdivdl.html

Ruby: a.gcd(b)
来源：http://dali.c1oappe.top/Article/details/gt2eznbrhcz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.vqdsnc.cn/Article/details/gt2vsfquwrl.html

[N06] 判断回文字符串
来源：http://dali.ydzc1.top/Article/details/gt2xyhaoyyi.html

Py:   s == s[::-1]
来源：http://dali.yj20258888.top/Article/details/gt2xfkosqmb.html

PHP:  $s === strrev($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2nhvsouhk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gt2difhzxli.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gt2ocufdkdr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenjidiqi.icu/Article/details/gt2wtzuzzit.html

Go:   // 双指针从两端比较
来源：http://dali.shzxlz.cn/Article/details/gt2djkbfhwy.html

Ruby: s == s.reverse
来源：http://dali.xylfe.cn/Article/details/gt2gudjtjye.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fphmkzqc.html

[N07] 两数之和（返回下标）
来源：http://dali.daxiang520.top/Article/details/gt2tdrhtllc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ydzc1.top/Article/details/gt2dqtnjxlg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rylqpjrs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shuidangran.top/Article/details/gt2vddqmvrs.html

TS:   // 手写 Map<string, number>
来源：http://dali.c1oappe.top/Article/details/gt2iogyccka.html

Java: // 手写 HashMap
来源：http://dali.hammf.cn/Article/details/gt2uabwbngr.html


<!-- 参考信息 -->