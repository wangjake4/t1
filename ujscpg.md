代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ppjwa.cn/Article/details/gt2mnoosxhb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jiagoushi.top/Article/details/gt2kuekvwct.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sufxvd.cn/Article/details/gt2mgllbwwq.html

[J10] 取今天 / 本月第一天
来源：http://dali.gzhubu.top/Article/details/gt2qrpagtpj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sxryk.cn/Article/details/gt2aeuhpbwj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cheryme.top/Article/details/gt2qbdkxfdr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daria6918.cn/Article/details/gt2dwjnzfcq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2fvyxquqb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aizwys.cn/Article/details/gt2azkuaeik.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgufenzy.top/Article/details/gt2dkdponde.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.kuanghao11.cn/Article/details/gt2eshbdzsq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guowangkeji.top/Article/details/gt2gzwxyhxl.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2agirwvit.html

K. JSON 与序列化
来源：http://dali.havefunace.top/Article/details/gt2etcrolif.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2bnyyvbcq.html

[K01] 对象转 JSON 字符串
来源：http://dali.birdmap.top/Article/details/gt2qcscibkm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqnjfkbg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jfefnbym.html

JS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2mccngauk.html

TS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2ebiggfrg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.havefunace.top/Article/details/gt2odfozuge.html

Go:   json.Marshal(obj)
来源：http://dali.yueranfly.top/Article/details/gt2qsobtpyd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jlsjyb.cn/Article/details/gt2ieoyluyb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wceiuqlk.html

[K02] JSON 字符串转对象
来源：http://dali.yongpay.top/Article/details/gt2zcudqdux.html

Py:   json.loads(s)
来源：http://dali.ivvv.top/Article/details/gt2pbuehttp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.vqdsnc.cn/Article/details/gt2hsaytpmx.html

JS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gt2ldsugxms.html

TS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gt2gwzjuqbq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cashguo.top/Article/details/gt2vijzuguy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gt2bkhgmelu.html

Ruby: JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gt2tsedsjtn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zycfv.cn/Article/details/gt2qffunrhx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cdnleiting.top/Article/details/gt2pofzskxg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gt2zttzjbki.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gt2wbkwclzu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gt2btlcbsun.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gt2crexsagp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2clufvsyv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhengqikj.top/Article/details/gt2prkrrebr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sxryk.cn/Article/details/gt2fmxqyetp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hywenlv.cn/Article/details/gt2lzrnejmn.html

[K04] 读取 JSON 文件
来源：http://dali.cdnleiting.top/Article/details/gt2rpinhybg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zdqjudy.top/Article/details/gt2aiainoge.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.vqdsnc.cn/Article/details/gt2euvqexzv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gt2euqkpqor.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gt2vyyignhr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gt2xvirrcrj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gt2gleqzaum.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gt2xzsitfgy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuanzx.com/Article/details/gt2dfqdtejh.html

[K05] 深拷贝对象
来源：http://dali.yj20258888.top/Article/details/gt2pefjabsu.html

Py:   copy.deepcopy(obj)
来源：http://dali.cheryme.top/Article/details/gt2lcgzsvqt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhoulong.xyz/Article/details/gt2ziifoeco.html

JS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2ehfekegk.html

TS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2dqwoybar.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shangyingyoupin.top/Article/details/gt2oxrvcgdg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sysykeji.top/Article/details/gt2kkcuqstn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jyoumei.cn/Article/details/gt2drvnqcsn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zycfv.cn/Article/details/gt2gnnnzxug.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqviimwq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gt2zupbeftw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ryrygdgr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gt2fjjyyyva.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gt2cmwafulm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hysaishi.cn/Article/details/gt2awqrkkpa.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2yoxxrhcf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gt2febcygwz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gt2jmtfdxwj.html

[K07] 进制转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2tovksesa.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2pplwxlty.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.snrcjt.cn/Article/details/gt2mcgmmxqx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gt2qikwfllw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cobnuspd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2hlsuvvdd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daxiang520.top/Article/details/gt2nulabuih.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guowangkeji.top/Article/details/gt2xslpmwka.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2hktekwsb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nwbrower.top/Article/details/gt2lrdgrwbg.html

Py:   pickle.dumps(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2oqjfioqi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2txgxrgbe.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gt2zvobmyco.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gt2hsnonzzx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.birdmap.top/Article/details/gt2lvrdfwia.html

Go:   encoding/gob
来源：http://dali.yj20258.top/Article/details/gt2jgquwojp.html

Ruby: Marshal.dump(obj)
来源：http://dali.ivvv.top/Article/details/gt2xihzqxdx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gt2qeyclhnd.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2rbxapano.html

L. 网络请求
来源：http://dali.hysaishi.cn/Article/details/gt2ybjxbrsi.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2euvsqhjw.html

[L01] 发送 GET 请求
来源：http://dali.havefunace.top/Article/details/gt2bzltcgnn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenjidiqi.icu/Article/details/gt2ttfrmxxi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cashguo.top/Article/details/gt2fumqguya.html

JS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gt2yqtykhwm.html

TS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jwydpdvl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cheryme.top/Article/details/gt2tidskcrb.html

Go:   resp, err := http.Get(url)
来源：http://dali.smart0.xyz/Article/details/gt2mlacwjoq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rlmkfelu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yonumen.top/Article/details/gt2yytrylrq.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nswjnjjf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gt2aewxxskh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jianghu66.top/Article/details/gt2uwwuobpx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gt2kkauaupn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gotoacloud.top/Article/details/gt2vidtgkvc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fengsongda.top/Article/details/gt2lwlbkbcq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yuxming.cn/Article/details/gt2jwkucuti.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhoulong.xyz/Article/details/gt2mromglsb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yvedp.cn/Article/details/gt2guutlaje.html

[L03] 设置自定义请求头
来源：http://dali.tian-w.cn/Article/details/gt2ddhavvri.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258.top/Article/details/gt2hadzwhny.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gt2urukfzwd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gt2uszndeym.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gt2megxuojq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nmxbbcyb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhixingplan.top/Article/details/gt2ataanpce.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sufxvd.cn/Article/details/gt2ilubfhsf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xziqi.cn/Article/details/gt2jeesfewa.html

[L04] 设置超时
来源：http://dali.sufxvd.cn/Article/details/gt2luhzpaxd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shuidangran.top/Article/details/gt2iapjlhio.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.meibo888.top/Article/details/gt2cprkagqe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gt2ucrlraxw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gt2vewwihby.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fzhhl.top/Article/details/gt2rqexvres.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nanxinkj.top/Article/details/gt2bdwogfud.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dashuyun.cn/Article/details/gt2ntvxfvrm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuanzx.com/Article/details/gt2iubqaitt.html

[L05] 上传文件（multipart）
来源：http://dali.gzhubu.top/Article/details/gt2ihhztbiy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jlsjyb.cn/Article/details/gt2scvnudap.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cashguo.top/Article/details/gt2jgexbjkj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gt2lcgmvtpn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gt2dcdxdpaf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xinyue.icu/Article/details/gt2paxbhbjx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yvedp.cn/Article/details/gt2akzozixb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenjidiqi.icu/Article/details/gt2dbbkkijs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2yjmqqlpl.html

[L06] 解析响应为 JSON
来源：http://dali.xuanzx.com/Article/details/gt2blawxhze.html

Py:   resp.json()
来源：http://dali.cucudq.cn/Article/details/gt2jtqsbjrz.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258.top/Article/details/gt2etlnlhim.html

JS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gt2vojwdmsm.html

TS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gt2snrkntgl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yueranfly.top/Article/details/gt2ngbjhspi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258888.top/Article/details/gt2imzeossh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daria6918.cn/Article/details/gt2pbcipatc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zycfv.cn/Article/details/gt2uagyhdgk.html

[L07] 处理 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gt2pqjzzzmp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.smart0.xyz/Article/details/gt2sntjkmmp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ybcxt.top/Article/details/gt2hkrnarfj.html

JS:   resp.ok;  resp.status
来源：http://dali.yueranfly.top/Article/details/gt2vijbahpc.html

TS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gt2pcwdaali.html

Java: resp.statusCode()
来源：http://dali.dashuyun.cn/Article/details/gt2lpoxddmp.html

Go:   resp.StatusCode
来源：http://dali.aibaodan.cn/Article/details/gt2ojgxuatr.html

Ruby: resp.code.to_i
来源：http://dali.quarkkingdee.top/Article/details/gt2lccrzhcn.html

C#:   (int)resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gt2tmeztjgx.html

[L08] 并发请求多个地址
来源：http://dali.havefunace.top/Article/details/gt2klncwvby.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fawxhbiw.html

PHP:  curl_multi_init() 系列
来源：http://dali.sufxvd.cn/Article/details/gt2ccyqxkby.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vudlejrc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gt2xldivlar.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhiwuduotai.top/Article/details/gt2gogsikoe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.316326.xyz/Article/details/gt2ujgmtniw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cdnleiting.top/Article/details/gt2gmazkacl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hammf.cn/Article/details/gt2ryzfqmpc.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2dawtjzyr.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangshuangyany.cn/Article/details/gt2eypcxdsr.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2pzqtlrxg.html

[M01] 读取命令行参数
来源：http://dali.zhixingplan.top/Article/details/gt2yrrgnvzf.html

Py:   sys.argv[1:]
来源：http://dali.nanxuanxn.top/Article/details/gt2dxybaiht.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigufen.top/Article/details/gt2ykjtkynl.html

JS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gt2rpcddtxf.html

TS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fluzaepi.html

Java: args 数组（main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gt2pykkdcds.html

Go:   os.Args[1:]
来源：http://dali.ivvv.top/Article/details/gt2zrndynmb.html

Ruby: ARGV
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wcddxhxj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.birdmap.top/Article/details/gt2lyaiggdp.html

[M02] 读取环境变量
来源：http://dali.jianghu66.top/Article/details/gt2noqerfkl.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2bddadvwd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gt2lbftoefu.html

JS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gt2pjmccidf.html

TS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gt2bknpnqaj.html

Java: System.getenv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gt2dujkzerc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj202588.top/Article/details/gt2jbomabyt.html

Ruby: ENV["HOME"]
来源：http://dali.xuetiantiany.cn/Article/details/gt2vjcqznwm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2hqkfphgd.html

[M03] 执行外部命令
来源：http://dali.daxiang520.top/Article/details/gt2kuffyvie.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gogol.net.cn/Article/details/gt2rzqhtyri.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pycfn.com/Article/details/gt2dmvysubz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gt2gfjgxpiw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gt2hnbogtgn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258888.top/Article/details/gt2deqzpeig.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sweek.top/Article/details/gt2rpyaprsh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tian-w.cn/Article/details/gt2ivytvjts.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tian-w.cn/Article/details/gt2ynsbibqt.html

[M04] 获取当前工作目录
来源：http://dali.kuanghao11.cn/Article/details/gt2bmsocteg.html

Py:   os.getcwd()
来源：http://dali.ehwqpu.com/Article/details/gt2sqgljiba.html

PHP:  getcwd();
来源：http://dali.0kj1m.cn/Article/details/gt2oarmdlln.html

JS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ueynzzpw.html

TS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ofplzgxr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hnxiangtu.top/Article/details/gt2vzpodxgp.html

Go:   os.Getwd()
来源：http://dali.316326.xyz/Article/details/gt2rkibcmma.html

Ruby: Dir.pwd
来源：http://dali.iojbl.cn/Article/details/gt2cuvzlwui.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.smart0.xyz/Article/details/gt2jspeafny.html

[M05] 设置退出码
来源：http://dali.xylfe.cn/Article/details/gt2iqilhusv.html

Py:   sys.exit(1)
来源：http://dali.nwbrower.top/Article/details/gt2adsyiotx.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2nayanpwb.html

JS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2puyspuvc.html

TS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2zzxilwum.html

Java: System.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tektfoge.html

Go:   os.Exit(1)
来源：http://dali.smart0.xyz/Article/details/gt2ccqznqcq.html

Ruby: exit 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kclzngko.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daxiang520.top/Article/details/gt2szrhhexj.html

[M06] 向标准错误输出
来源：http://dali.cucudq.cn/Article/details/gt2wfnbiagu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gt2zxwvhlot.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ivvv.top/Article/details/gt2zjftqyil.html

JS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gt2negwzzkj.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzmrhim.html

Java: System.err.println("err")
来源：http://dali.xuanzx.com/Article/details/gt2ztqoyevy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cheryme.top/Article/details/gt2tvcodtpq.html

Ruby: warn "err"
来源：http://dali.gotoacloud.top/Article/details/gt2mgfmymyi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnxiangtu.top/Article/details/gt2sxnyizzt.html

[M07] 判断是否为主入口
来源：http://dali.jinqigufen.top/Article/details/gt2njreyaov.html

Py:   if __name__ == "__main__":
来源：http://dali.hongshengwenyu.top/Article/details/gt2hmwarmap.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.0kj1m.cn/Article/details/gt2pqhjknlt.html

JS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gt2aporfyqn.html

TS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gt2jjefrero.html

Java: public static void main(String[] args)
来源：http://dali.fzhhl.top/Article/details/gt2xbevpqne.html

Go:   func main()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jsqeidqg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tafufjat.html

C#:   static void Main(string[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rllhefag.html

[M08] 获取系统与运行时信息
来源：http://dali.shuidangran.top/Article/details/gt2acswsvjo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yongpay.top/Article/details/gt2ageggdkl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ivvv.top/Article/details/gt2nuallvgw.html

JS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gt2ojxmhmdi.html

TS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gt2vmlnkdum.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258888.top/Article/details/gt2cfjdtuwm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuanzhike.top/Article/details/gt2tlgpcuzv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fengsongda.top/Article/details/gt2ekzwjryx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuanzhike.top/Article/details/gt2zxmsutgd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2yhxesyeq.html

N. 数据结构与算法
来源：http://dali.yuxming.cn/Article/details/gt2akaldfpv.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2vfvckpdx.html

[N01] 二分查找（有序数组）
来源：http://dali.yongpay.top/Article/details/gt2inzkuxve.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2dfvtfetg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fengsongda.top/Article/details/gt2lsfzhjml.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gt2tvkufqlv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gt2hwqelpwq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2duifeqyl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2npuugozb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ybcxt.top/Article/details/gt2rikcoxfk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2zohtpeop.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shangyingyoupin.top/Article/details/gt2tascqlwo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gt2zleibbuv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.havefunace.top/Article/details/gt2csmpkyjx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gt2daoofaqv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gt2ppskhnxf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jiagoushi.top/Article/details/gt2igalhsqp.html

Go:   slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gt2eqikhzwj.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gt2jricwalw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.andypj.xyz/Article/details/gt2ldgubpfw.html

[N03] 快速排序（分治示例）
来源：http://dali.cheryme.top/Article/details/gt2aqzcpsmq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daria6918.cn/Article/details/gt2tpkrasyx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.meibo888.top/Article/details/gt2svpzbmuh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gt2qgivsrmq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pcnjppmb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuetiantiany.cn/Article/details/gt2rrestwov.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tian-w.cn/Article/details/gt2qibunisf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shuidangran.top/Article/details/gt2lzdklplc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangshuangyany.cn/Article/details/gt2ojadgymg.html

[N04] 斐波那契数列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mltvyigu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tianlin.xyz/Article/details/gt2npaxcfpt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cucudq.cn/Article/details/gt2tjtpuoal.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2cfkmcmzy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gt2mgecxyeo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gt2huivdlze.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sysykeji.top/Article/details/gt2zmvpbwql.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gt2tyhhwrgy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gt2vnhjuucp.html

[N05] 最大公约数
来源：http://dali.hfpthk.cn/Article/details/gt2wgiscvqe.html

Py:   math.gcd(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2krddwvxx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pycfn.com/Article/details/gt2ejbjgxvq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gt2ketelnme.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.mhx1999.top/Article/details/gt2zjpukaqm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sxryk.cn/Article/details/gt2drefgeob.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xinyue.icu/Article/details/gt2ewgklkuq.html

Ruby: a.gcd(b)
来源：http://dali.chenzaomai.com/Article/details/gt2ozwjxfkj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgufenzy.top/Article/details/gt2pkcwdnqx.html

[N06] 判断回文字符串
来源：http://dali.snrcjt.cn/Article/details/gt2cpqlxter.html

Py:   s == s[::-1]
来源：http://dali.ydzc1.top/Article/details/gt2ttixrgdk.html

PHP:  $s === strrev($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dlzdhtkw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gt2nldcgmqw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2luefiftk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxinkj.top/Article/details/gt2ocetiojs.html

Go:   // 双指针从两端比较
来源：http://dali.ppjwa.cn/Article/details/gt2qpzdtjis.html

Ruby: s == s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nrylhubf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gt2askuhzor.html

[N07] 两数之和（返回下标）
来源：http://dali.guannengcc.top/Article/details/gt2trjoevct.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tanke756.top/Article/details/gt2dglpdgav.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2niwufhlv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.iojbl.cn/Article/details/gt2ynnhetvt.html

TS:   // 手写 Map<string, number>
来源：http://dali.gogol.net.cn/Article/details/gt2vperyuzt.html

Java: // 手写 HashMap
来源：http://dali.yvedp.cn/Article/details/gt2vxyyoxpc.html


<!-- 参考信息 -->