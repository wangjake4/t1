代发 wailian999

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2hkmpdrlf.html

K. JSON 与序列化
来源：http://dali.dashuyun.cn/Article/details/gt2mqpakptn.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ushoedix.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangdashe.top/Article/details/gt2ihgutufu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gt2ensifada.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gt2jopgvwjp.html

JS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gt2lunhydqt.html

TS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gt2ngooicub.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yonumen.top/Article/details/gt2efmqvnds.html

Go:   json.Marshal(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2ibdoqaua.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhixingplan.top/Article/details/gt2ylqtcmgi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2uqxgifya.html

[K02] JSON 字符串转对象
来源：http://dali.chenjidiqi.icu/Article/details/gt2qttbmttx.html

Py:   json.loads(s)
来源：http://dali.yj202588.top/Article/details/gt2svpvrolw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhixingplan.top/Article/details/gt2zotkvqbt.html

JS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gt2vqnjuubk.html

TS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gt2bxptzkuw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gt2itwebraf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gt2neutoxfs.html

Ruby: JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gt2dywsdxsc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aizwys.cn/Article/details/gt2tjhdrowk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tanke756.top/Article/details/gt2duznxtdg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2phreziis.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gt2izikgpfe.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ydzc1.top/Article/details/gt2tnponxsi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2cnawnyvd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2hvewlqwa.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gzhubu.top/Article/details/gt2hckuskdf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2whedyskv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.quarkkingdee.top/Article/details/gt2ztwnnlzi.html

[K04] 读取 JSON 文件
来源：http://dali.haohaochexian.top/Article/details/gt2ujvtfxbg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ehwqpu.com/Article/details/gt2gljkggfp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zdqjudy.top/Article/details/gt2jgddzlyg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gt2jyfiwjmf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gt2zdvoboey.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shuidangran.top/Article/details/gt2pvufgxiw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dzwavmgs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gt2kalljrlp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gt2ftsjcrqr.html

[K05] 深拷贝对象
来源：http://dali.redwolf501.top/Article/details/gt2osjgnzcb.html

Py:   copy.deepcopy(obj)
来源：http://dali.cheryme.top/Article/details/gt2wqnukzqp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.kuanghao11.cn/Article/details/gt2xcjctfcn.html

JS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2okzeibco.html

TS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2nofbamxj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sufxvd.cn/Article/details/gt2falskzad.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tianlin.xyz/Article/details/gt2rsjurcjc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhongyouzk.top/Article/details/gt2appxvzhh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gaohongyu789.top/Article/details/gt2zikmfktj.html

[K06] 解析 URL 查询串
来源：http://dali.gotoacloud.top/Article/details/gt2vavyjwsm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tian-w.cn/Article/details/gt2jaqdnwzz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aibaodan.cn/Article/details/gt2vjuxvino.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gt2rcwsyvdl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gt2ylqoyvcq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gt2bnrleked.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gt2spwpcgsi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eugwvdwj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gt2vcwntwqf.html

[K07] 进制转换
来源：http://dali.jinqigfzy.top/Article/details/gt2yuriqbgu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2pichtwvj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhiwuduotai.top/Article/details/gt2mztnbepn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2qsnxmpyl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2isroxagw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gt2swzkaxtb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ybcxt.top/Article/details/gt2oqqgasgr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yangfankeji.com/Article/details/gt2wctfadak.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2xqhtubxe.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gaohongyu789.top/Article/details/gt2ckybedzp.html

Py:   pickle.dumps(obj)
来源：http://dali.xziqi.cn/Article/details/gt2ayafvdpp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2pnjxocon.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gt2xptnvgxs.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gt2ptxmsxbq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wevhucuu.html

Go:   encoding/gob
来源：http://dali.nanxuanxn.top/Article/details/gt2aefnrrin.html

Ruby: Marshal.dump(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2pfnmebdx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gt2gmvpudee.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2hmnlrnwd.html

L. 网络请求
来源：http://dali.nanxuanxn.top/Article/details/gt2hkulswrg.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2fgnljfwb.html

[L01] 发送 GET 请求
来源：http://dali.yongpay.top/Article/details/gt2xnoxjdgx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2teuglcxx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mijuyzjm.html

JS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gt2uvnoumhx.html

TS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gt2mdovhrvw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigufen.top/Article/details/gt2ztxyzwyz.html

Go:   resp, err := http.Get(url)
来源：http://dali.dianchejie.cn/Article/details/gt2stscnxxi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.bjfxy.top/Article/details/gt2yzavemxl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ovpaxgxb.html

[L02] 发送 POST JSON
来源：http://dali.wangdashe.top/Article/details/gt2htdwabsv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gt2asvyngds.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cucudq.cn/Article/details/gt2byquxwfq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gt2gvnjcnou.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gt2qnhikvio.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hysaishi.cn/Article/details/gt2yetbtkak.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.smart0.xyz/Article/details/gt2jtifkbwi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tianlin.xyz/Article/details/gt2adrfnduo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cheryme.top/Article/details/gt2bkiybnco.html

[L03] 设置自定义请求头
来源：http://dali.chenjidiqi.icu/Article/details/gt2wkbpzwgp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sysykeji.top/Article/details/gt2hmjjhwxb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hfpthk.cn/Article/details/gt2rcdwhwpx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gt2huwuzwbf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rbmkhfck.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xziqi.cn/Article/details/gt2jcdrnmfb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gt2spivmawa.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.iojbl.cn/Article/details/gt2ipbccxff.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gt2ombhlweh.html

[L04] 设置超时
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ouumeeaw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mnqpfkrf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yangfankeji.com/Article/details/gt2tmfwidly.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gt2kzpkrqby.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gt2zmuzmqrc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2unenwaaf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.meibo888.top/Article/details/gt2renpwfvp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuanzx.com/Article/details/gt2bkylhtdx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhoulong.xyz/Article/details/gt2ndqyykvj.html

[L05] 上传文件（multipart）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wrwflffv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tianlin.xyz/Article/details/gt2ceffiapy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fzhhl.top/Article/details/gt2flqatgnx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxuanxn.top/Article/details/gt2gijjmufl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gt2isvlxtsa.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuanzhike.top/Article/details/gt2pfxsipho.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.andypj.xyz/Article/details/gt2yjidtggy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yueranfly.top/Article/details/gt2bkhwquah.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2zvznuvhi.html

[L06] 解析响应为 JSON
来源：http://dali.tian-w.cn/Article/details/gt2kyixawdo.html

Py:   resp.json()
来源：http://dali.jyoumei.cn/Article/details/gt2agwmowvd.html

PHP:  json_decode($body, true);
来源：http://dali.yangfankeji.com/Article/details/gt2jbskydta.html

JS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gt2jlnhhldy.html

TS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gt2yeezjkqm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gt2natchdof.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258.top/Article/details/gt2ecptrzrv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cashguo.top/Article/details/gt2mmcojjyx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daria6918.cn/Article/details/gt2ygshrdhh.html

[L07] 处理 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gt2ammptfry.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenlongwang.top/Article/details/gt2ogqmelcu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gogol.net.cn/Article/details/gt2aghiohws.html

JS:   resp.ok;  resp.status
来源：http://dali.shzxlz.cn/Article/details/gt2momkbthh.html

TS:   resp.ok;  resp.status
来源：http://dali.cqqwz.cn/Article/details/gt2obgwshyk.html

Java: resp.statusCode()
来源：http://dali.cqqwz.cn/Article/details/gt2usntxvme.html

Go:   resp.StatusCode
来源：http://dali.pycfn.com/Article/details/gt2desjkjlx.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gt2tnhvosal.html

C#:   (int)resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gt2yrowpnms.html

[L08] 并发请求多个地址
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rpjfxfdj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gzhubu.top/Article/details/gt2ynqlfdex.html

PHP:  curl_multi_init() 系列
来源：http://dali.sysykeji.top/Article/details/gt2tkbprmul.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gt2hdvyevbk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gt2mhejqiya.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yvedp.cn/Article/details/gt2dviskyxp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daxiang520.top/Article/details/gt2zhmpkabd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cucudq.cn/Article/details/gt2toffceyi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shzxlz.cn/Article/details/gt2ilzdzaef.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2pvbfihda.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigufen.top/Article/details/gt2tbvdxlvb.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2pguhyvei.html

[M01] 读取命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2dtlnumqk.html

Py:   sys.argv[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2goimstby.html

PHP:  $argv;  $argc;
来源：http://dali.bjfxy.top/Article/details/gt2cftkucgo.html

JS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gt2ghoscokn.html

TS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gt2llonfsnl.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzdjqgk.html

Go:   os.Args[1:]
来源：http://dali.jqgfzy.top/Article/details/gt2klgjfdrs.html

Ruby: ARGV
来源：http://dali.yueranfly.top/Article/details/gt2enwgbryd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sweek.top/Article/details/gt2xxjrxtgp.html

[M02] 读取环境变量
来源：http://dali.shzxlz.cn/Article/details/gt2tvkelfap.html

Py:   os.environ.get("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2bsnxfxno.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hammf.cn/Article/details/gt2lxjiuyyo.html

JS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gt2mbbwueej.html

TS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gt2efykyihe.html

Java: System.getenv("HOME")
来源：http://dali.yonumen.top/Article/details/gt2lahktdsk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2obvkboyw.html

Ruby: ENV["HOME"]
来源：http://dali.xuanzx.com/Article/details/gt2elvccouz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2acppmamo.html

[M03] 执行外部命令
来源：http://dali.svipenyu.cn/Article/details/gt2hxrfwatj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tian-w.cn/Article/details/gt2htxijata.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ehwqpu.com/Article/details/gt2ohpvddkn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gt2rxmvoyps.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gt2ddirfeyi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.kuanghao11.cn/Article/details/gt2jxvtwtsc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shzxlz.cn/Article/details/gt2drwxmzdd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.meibo888.top/Article/details/gt2auiirgdg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zycfv.cn/Article/details/gt2nakgubfi.html

[M04] 获取当前工作目录
来源：http://dali.ybcxt.top/Article/details/gt2udhasdsy.html

Py:   os.getcwd()
来源：http://dali.fzhhl.top/Article/details/gt2atmwrnym.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gt2azgtnnxl.html

JS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gt2fuewgtth.html

TS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gt2wurlmpye.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cqqwz.cn/Article/details/gt2jlvsemfg.html

Go:   os.Getwd()
来源：http://dali.iojbl.cn/Article/details/gt2wvxkgbrg.html

Ruby: Dir.pwd
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ctxvhapn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.c1oappe.top/Article/details/gt2qtuzkoxl.html

[M05] 设置退出码
来源：http://dali.ppjwa.cn/Article/details/gt2qjavopsx.html

Py:   sys.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2curyecaq.html

PHP:  exit(1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2hjdxjcjc.html

JS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gt2ddcikjaz.html

TS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2zdpcdtop.html

Java: System.exit(1)
来源：http://dali.nwbrower.top/Article/details/gt2nwtuqycv.html

Go:   os.Exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2zoqdodtj.html

Ruby: exit 1
来源：http://dali.aibaodan.cn/Article/details/gt2fpubqycy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.vqdsnc.cn/Article/details/gt2cjrqtiua.html

[M06] 向标准错误输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2tjvhzelo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gt2lscdgyau.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.bjfxy.top/Article/details/gt2kvqfgpho.html

JS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gt2ghnyzihk.html

TS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gt2ynpkdhvp.html

Java: System.err.println("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qihlfhcc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ivvv.top/Article/details/gt2movkdkxx.html

Ruby: warn "err"
来源：http://dali.daria6918.cn/Article/details/gt2xqydqahg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jiagoushi.top/Article/details/gt2pzqtoyju.html

[M07] 判断是否为主入口
来源：http://dali.svipenyu.cn/Article/details/gt2xlznqftx.html

Py:   if __name__ == "__main__":
来源：http://dali.daxiang520.top/Article/details/gt2mscdqoar.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cucudq.cn/Article/details/gt2vmbadblm.html

JS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gt2udjrbmhk.html

TS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gt2ncydjjjr.html

Java: public static void main(String[] args)
来源：http://dali.jinqigfzy.top/Article/details/gt2kfyupory.html

Go:   func main()
来源：http://dali.vqdsnc.cn/Article/details/gt2mskrcrfm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gmpclhmr.html

C#:   static void Main(string[] args)
来源：http://dali.nanxuanxn.top/Article/details/gt2lmqsseol.html

[M08] 获取系统与运行时信息
来源：http://dali.yj202588.top/Article/details/gt2mpxvaksc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgfzy.top/Article/details/gt2nneeztir.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shangyingyoupin.top/Article/details/gt2fcuozvzt.html

JS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gt2cmmcpwxs.html

TS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gt2rywlbffy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.bjfxy.top/Article/details/gt2srikgcvj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ydzc1.top/Article/details/gt2kdcwxnxi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daria6918.cn/Article/details/gt2nnhdbuvd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dianchejie.cn/Article/details/gt2poqylxks.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2eieajrjd.html

N. 数据结构与算法
来源：http://dali.fengsongda.top/Article/details/gt2fvuwrqge.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2flplhaqf.html

[N01] 二分查找（有序数组）
来源：http://dali.mhx1999.top/Article/details/gt2mnzfqmkw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2iqncefkw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cashguo.top/Article/details/gt2rkmwrifs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gt2ezgpdsyt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gt2yvvxuvji.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gt2rmijbjyd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2xrnycrjr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuanzhike.top/Article/details/gt2ozrywpmo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2gadvahxb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guowangkeji.top/Article/details/gt2hwdwrvhg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gt2lnwhcnan.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yongpay.top/Article/details/gt2nquhkkze.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gt2hpfoeowy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2iswsvvzm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gogol.net.cn/Article/details/gt2lzsnrmgy.html

Go:   slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2wudvoauo.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gt2jhwiwfhq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gaohongyu789.top/Article/details/gt2ttkubxmm.html

[N03] 快速排序（分治示例）
来源：http://dali.hywenlv.cn/Article/details/gt2fqvhjpkb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenlongwang.top/Article/details/gt2iksxqysd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnxiangtu.top/Article/details/gt2lydfuycs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gt2qjoojbut.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gt2jxdrbxxj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuetiantiany.cn/Article/details/gt2knxstqcn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jyoumei.cn/Article/details/gt2kdywjrca.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hysaishi.cn/Article/details/gt2stvfchtq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sysykeji.top/Article/details/gt2pfknraae.html

[N04] 斐波那契数列
来源：http://dali.yonumen.top/Article/details/gt2csichjdx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iiqzsaqh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gt2xzmhgyzp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2pkiqezfk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2isazerwy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zycfv.cn/Article/details/gt2txlzamza.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wygoxrow.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gt2nurvbkcp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gt2fyzslxzw.html

[N05] 最大公约数
来源：http://dali.zhixingplan.top/Article/details/gt2redsbxlr.html

Py:   math.gcd(a, b)
来源：http://dali.yuanzhike.top/Article/details/gt2ndbicdrl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.birdmap.top/Article/details/gt2apmzaypq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yueranfly.top/Article/details/gt2qhjslznc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gt2xwjtloup.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xziqi.cn/Article/details/gt2rtvmfybp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qcprnmbn.html

Ruby: a.gcd(b)
来源：http://dali.havefunace.top/Article/details/gt2omlewjgb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guowangkeji.top/Article/details/gt2dopsxroy.html

[N06] 判断回文字符串
来源：http://dali.mhx1999.top/Article/details/gt2zuocboqk.html

Py:   s == s[::-1]
来源：http://dali.316326.xyz/Article/details/gt2jjcbgzqx.html

PHP:  $s === strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2osoupirs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gt2lfyykebw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gt2gdntjkne.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnqzz.top/Article/details/gt2lmeqzgcy.html

Go:   // 双指针从两端比较
来源：http://dali.0kj1m.cn/Article/details/gt2nxifqeth.html

Ruby: s == s.reverse
来源：http://dali.yuanzhike.top/Article/details/gt2mkntqqxg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dpbwjrpx.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxklkxem.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxinkj.top/Article/details/gt2mvsgbrqo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxfysgo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hammf.cn/Article/details/gt2hvpscwze.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxuanxn.top/Article/details/gt2qtedlxpm.html

Java: // 手写 HashMap
来源：http://dali.aizwys.cn/Article/details/gt2yyftvhpc.html

Go:   // 手写 map[int]int
来源：http://dali.ydzc1.top/Article/details/gt2gqodoxab.html

Ruby: // 手写 Hash
来源：http://dali.chenjidiqi.icu/Article/details/gt2ehpxoxfa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.mhx1999.top/Article/details/gt2hlimpscn.html

[N08] 生成全排列
来源：http://dali.sysykeji.top/Article/details/gt2vyjjvmez.html

Py:   itertools.permutations(arr)
来源：http://dali.cashguo.top/Article/details/gt2xgqizdhm.html

PHP:  // 手写递归交换
来源：http://dali.yvedp.cn/Article/details/gt2sjgcvjcm.html

JS:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jrcwsgeo.html

TS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2otvvbvqn.html

Java: // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gt2bvumwmwj.html

Go:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2chynavgo.html

Ruby: arr.permutation.to_a
来源：http://dali.fengsongda.top/Article/details/gt2bltleclc.html

C#:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2jmmevdcp.html


<!-- 参考信息 -->