代发 wailian999

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.bjfxy.top/Article/details/gtleylfnud.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aizwys.cn/Article/details/gtenpagmqv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ybcxt.top/Article/details/gtrqlfbpas.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hfpthk.cn/Article/details/gtvjoqwxdt.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtnffnuvqf.html

K. JSON 与序列化
来源：http://dali.shangyingyoupin.top/Article/details/gtwckdpwjg.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtzhgjmzti.html

[K01] 对象转 JSON 字符串
来源：http://dali.sufxvd.cn/Article/details/gtjokzknez.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hongshengwenyu.top/Article/details/gtdcrwldum.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gtanxwgnaz.html

JS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtqlpjzuxl.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gtvtumlwks.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.iojbl.cn/Article/details/gtoqwzirqz.html

Go:   json.Marshal(obj)
来源：http://dali.wangdashe.top/Article/details/gtbutvahgb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.feifeiyinyue.top/Article/details/gtydjeikrg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.c1oappe.top/Article/details/gtqeachhcj.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gtmyodazlt.html

Py:   json.loads(s)
来源：http://dali.tanke756.top/Article/details/gtanwwwoco.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.quarkkingdee.top/Article/details/gttiaipxrx.html

JS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtwddweraf.html

TS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtdrmbvxsh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yueranfly.top/Article/details/gtlgvdpuvl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gthzhgufww.html

Ruby: JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtgqnsuapl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dashuyun.cn/Article/details/gtngvmxyui.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cheryme.top/Article/details/gtoezvmqxd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrrftsuw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gtuitfurfr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gtyewakzwi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtcdpjimbt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ybcxt.top/Article/details/gtzadzvmnu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.quarkkingdee.top/Article/details/gtcrkdchti.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuoxrshxt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnqzz.top/Article/details/gtvawtwkrw.html

[K04] 读取 JSON 文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddwlfqxu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.c1oappe.top/Article/details/gtkykibwbi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxuanxn.top/Article/details/gtoenbqhmw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcwzanyr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gtarhwvojr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xylfe.cn/Article/details/gtrddmayru.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gttpxcpxqx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gtihdoomaq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gtblgudxxl.html

[K05] 深拷贝对象
来源：http://dali.xylfe.cn/Article/details/gtnxshyozo.html

Py:   copy.deepcopy(obj)
来源：http://dali.daxiang520.top/Article/details/gtmthmviny.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xinyue.icu/Article/details/gtygcwqvul.html

JS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtlgykmfrs.html

TS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtcjcytjwi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258888.top/Article/details/gtwrvanybr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgufenzy.top/Article/details/gtpwzurqcz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hfpthk.cn/Article/details/gtxykjawvx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nwbrower.top/Article/details/gtbgahwbej.html

[K06] 解析 URL 查询串
来源：http://dali.yongpay.top/Article/details/gtbehbzvbv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gtskezoxyf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xylfe.cn/Article/details/gtujwbrzck.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gtllwvgjrc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gtfblkuqhn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hfpthk.cn/Article/details/gtzkrwpktl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtlknfwzin.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtocbjsxqj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gtrztkwsso.html

[K07] 进制转换
来源：http://dali.chenzaomai.com/Article/details/gtgivcysfr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtrcvrlspr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gthvqmjofu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtcdbjpumy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtoowmaunn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtcvnxfuzo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shuidangran.top/Article/details/gtzqcsjouz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daria6918.cn/Article/details/gtkwiokczq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtjyjadrxo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zdqjudy.top/Article/details/gtzesfgcpu.html

Py:   pickle.dumps(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqzyzxbx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sysykeji.top/Article/details/gtlwfiwaxr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gtbikpdkxc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gtuqootsfh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhoulong.xyz/Article/details/gtzeirfrkz.html

Go:   encoding/gob
来源：http://dali.ppjwa.cn/Article/details/gthmqnwvgt.html

Ruby: Marshal.dump(obj)
来源：http://dali.ybcxt.top/Article/details/gtojvvzuba.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gtghzuqnjl.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtlknjtvtz.html

L. 网络请求
来源：http://dali.gzhubu.top/Article/details/gtnrxzdmic.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtdekyzsaw.html

[L01] 发送 GET 请求
来源：http://dali.sweek.top/Article/details/gtrkksaqlj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xylfe.cn/Article/details/gtweulwcse.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.quarkkingdee.top/Article/details/gtkqbzxamr.html

JS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gtgcmlgvpa.html

TS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gtcwwehwig.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yueranfly.top/Article/details/gtxogmwlgm.html

Go:   resp, err := http.Get(url)
来源：http://dali.sweek.top/Article/details/gtqnokixnx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nanxuanxn.top/Article/details/gtomntojhl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hysaishi.cn/Article/details/gtfmeycpol.html

[L02] 发送 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gtcpgphvxs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.redwolf501.top/Article/details/gtawbrcgxk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ybcxt.top/Article/details/gtzsjtpico.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gtzlqjolic.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gtegpuwnss.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj202588.top/Article/details/gtgebizzdh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fzhhl.top/Article/details/gtpqkbohun.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhoulong.xyz/Article/details/gtptongbwp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fzhhl.top/Article/details/gtfqrhcfee.html

[L03] 设置自定义请求头
来源：http://dali.cheryme.top/Article/details/gtiticqolz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.9152youxi.cn/Article/details/gtyhcoavyv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yongpay.top/Article/details/gtltoaoilj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gtwzycephf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gtbtuosztl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shzxlz.cn/Article/details/gtgpdsmpho.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gtxpvxrfew.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.redwolf501.top/Article/details/gthsugwnwk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwgyvsim.html

[L04] 设置超时
来源：http://dali.mhx1999.top/Article/details/gtawjevnti.html

Py:   requests.get(url, timeout=5)
来源：http://dali.pycfn.com/Article/details/gthfnqooys.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayhpidiz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkapopqci.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gtdbfuptfg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sufxvd.cn/Article/details/gtyaiiztxp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.snrcjt.cn/Article/details/gtpoqsnznp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sysykeji.top/Article/details/gtcsvjvevk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhengqikj.top/Article/details/gtmbahlgim.html

[L05] 上传文件（multipart）
来源：http://dali.jiagoushi.top/Article/details/gtutnzeqmu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.mhx1999.top/Article/details/gtsrusvbir.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nwbrower.top/Article/details/gtrcizcxde.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gtnuliavdo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarknwcxi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hysaishi.cn/Article/details/gtqeqobudv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.bjfxy.top/Article/details/gtbmrwkjyu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sxryk.cn/Article/details/gtkixelrjs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shzxlz.cn/Article/details/gttbtwjvsm.html

[L06] 解析响应为 JSON
来源：http://dali.gotoacloud.top/Article/details/gtycpqdvnd.html

Py:   resp.json()
来源：http://dali.sxryk.cn/Article/details/gtvcejolxp.html

PHP:  json_decode($body, true);
来源：http://dali.iojbl.cn/Article/details/gtojukbnlg.html

JS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gtqogbnszj.html

TS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtdaczomef.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtwwcuqiin.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shzxlz.cn/Article/details/gtripydshf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xziqi.cn/Article/details/gtbujkvilg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nwbrower.top/Article/details/gtvdceizcr.html

[L07] 处理 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gtangquldl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sufxvd.cn/Article/details/gtwntionty.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigfzy.top/Article/details/gtcvjvxjhu.html

JS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gtqysehkjz.html

TS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtwqvvrmjd.html

Java: resp.statusCode()
来源：http://dali.yongpay.top/Article/details/gtoggykscx.html

Go:   resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gtcthaffxa.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gtjsgoinmo.html

C#:   (int)resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjwzweom.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangtech.top/Article/details/gtybrhqwnc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tanke756.top/Article/details/gtdizzeraw.html

PHP:  curl_multi_init() 系列
来源：http://dali.birdmap.top/Article/details/gtysbaijvh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtbxhqlrxm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gtwcxwslnz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gtfraihiwp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.aizwys.cn/Article/details/gtejdvmymf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hysaishi.cn/Article/details/gtfamzkhxq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258888.top/Article/details/gtqjcuofyu.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gteynefsqv.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhiwuduotai.top/Article/details/gtpjuhgdks.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtxrafceja.html

[M01] 读取命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gtuxnzeyvc.html

Py:   sys.argv[1:]
来源：http://dali.sysykeji.top/Article/details/gtdijykqak.html

PHP:  $argv;  $argc;
来源：http://dali.hywenlv.cn/Article/details/gtdahbdstj.html

JS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gtnbqvjdih.html

TS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gtttvdzuou.html

Java: args 数组（main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gtxuctnndy.html

Go:   os.Args[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtjkdvfsdl.html

Ruby: ARGV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwgxwexn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gtmtjeedcb.html

[M02] 读取环境变量
来源：http://dali.yangfankeji.com/Article/details/gtpatqbsun.html

Py:   os.environ.get("HOME")
来源：http://dali.shuidangran.top/Article/details/gtvbjngwyk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gtwcsiwnfy.html

JS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gtbirbkamr.html

TS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtcgdqonfc.html

Java: System.getenv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtsvoolrrd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtakznufbe.html

Ruby: ENV["HOME"]
来源：http://dali.feifeiyinyue.top/Article/details/gtlteulooy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtwrigvirt.html

[M03] 执行外部命令
来源：http://dali.aizwys.cn/Article/details/gtzasbbpei.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yongpay.top/Article/details/gtorikxtyr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gtuqiozakl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gtukxfludt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlhdhtbe.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yangfankeji.com/Article/details/gtldbxsajq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aizwys.cn/Article/details/gtwmopckyh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrnyvniq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yueranfly.top/Article/details/gtfsxvuphg.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gtslpbpfwh.html

Py:   os.getcwd()
来源：http://dali.svipenyu.cn/Article/details/gtvdqknsef.html

PHP:  getcwd();
来源：http://dali.cucudq.cn/Article/details/gtmwfusofc.html

JS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtvfsznrox.html

TS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gtznrrdrpy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlyrdjym.html

Go:   os.Getwd()
来源：http://dali.hywenlv.cn/Article/details/gtoenvfyfh.html

Ruby: Dir.pwd
来源：http://dali.yonumen.top/Article/details/gtbtphfhwe.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hongshengwenyu.top/Article/details/gtjfesrngx.html

[M05] 设置退出码
来源：http://dali.pycfn.com/Article/details/gtzeapdmnt.html

Py:   sys.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtouyqqnbt.html

PHP:  exit(1);
来源：http://dali.zhixingplan.top/Article/details/gtclazyqus.html

JS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtsbgqjtzl.html

TS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtxeihmnht.html

Java: System.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gttqdgmdop.html

Go:   os.Exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgoqwwedm.html

Ruby: exit 1
来源：http://dali.xinyue.icu/Article/details/gtijhgjwjq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyfmrjnw.html

[M06] 向标准错误输出
来源：http://dali.ydzc1.top/Article/details/gtolumqlsh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gtfutzskwn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hysaishi.cn/Article/details/gtcbezdswl.html

JS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gtnsupdogy.html

TS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtiqhdlxlo.html

Java: System.err.println("err")
来源：http://dali.svipenyu.cn/Article/details/gtzsjwhlgt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aizwys.cn/Article/details/gtqsfgrzii.html

Ruby: warn "err"
来源：http://dali.andypj.xyz/Article/details/gtnndfloez.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jlsjyb.cn/Article/details/gteeppwoco.html

[M07] 判断是否为主入口
来源：http://dali.sxryk.cn/Article/details/gthqkokmut.html

Py:   if __name__ == "__main__":
来源：http://dali.aibaodan.cn/Article/details/gtennmxeal.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cheryme.top/Article/details/gthmwxlbae.html

JS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gtpznlrrpa.html

TS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gthgewhvyf.html

Java: public static void main(String[] args)
来源：http://dali.yueranfly.top/Article/details/gtcnbuzsdq.html

Go:   func main()
来源：http://dali.ppjwa.cn/Article/details/gtswlnjpnm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sysykeji.top/Article/details/gtlaziftea.html

C#:   static void Main(string[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtksunlshv.html

[M08] 获取系统与运行时信息
来源：http://dali.iojbl.cn/Article/details/gthxovdxyo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xziqi.cn/Article/details/gtmghdjssp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guannengcc.top/Article/details/gtmqlfkwik.html

JS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtblrxzler.html

TS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gtpkszrrkd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daxiang520.top/Article/details/gtggppdyqb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tianlin.xyz/Article/details/gtpaktwdzf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yangfankeji.com/Article/details/gtnopxzdci.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yonumen.top/Article/details/gtxowwcfxs.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtkqpveasq.html

N. 数据结构与算法
来源：http://dali.guannengcc.top/Article/details/gtsiahlcnz.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtdnlfkmng.html

[N01] 二分查找（有序数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstphddrr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cashguo.top/Article/details/gtqggczzhv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtsusgnoxh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gtibejhozb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gtljlhpkyo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtbbannfbc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtwbatjgca.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.snrcjt.cn/Article/details/gtnbfbtciy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtmpjagaid.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jianghu66.top/Article/details/gtfkoixzct.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtcptzimcv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ydzc1.top/Article/details/gttrupsvdl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtxchslcju.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtltpgiszf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jqgufenzy.top/Article/details/gtyzogksqv.html

Go:   slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gthojqhunt.html

Ruby: arr.sort
来源：http://dali.yj20258888.top/Article/details/gtovuxiwwo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shzxlz.cn/Article/details/gtlvhjpzrn.html

[N03] 快速排序（分治示例）
来源：http://dali.gaohongyu789.top/Article/details/gtynjmapnr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.316326.xyz/Article/details/gtncemnceo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfouhllzo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gtgbeafejh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndwoymjr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cdnleiting.top/Article/details/gtojtmsjhh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hfpthk.cn/Article/details/gtbwkorhtv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj202588.top/Article/details/gtylkejewf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangshuangyany.cn/Article/details/gtlizpkiwz.html

[N04] 斐波那契数列
来源：http://dali.ivvv.top/Article/details/gtwpcbzdkr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnqzz.top/Article/details/gtkejfikuf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.bjfxy.top/Article/details/gtuzwlfmvy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtqxjzietk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtsuyzgzmr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.iojbl.cn/Article/details/gtwcxkjlkb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jyoumei.cn/Article/details/gtiysbzzwf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtdgkfshou.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlbgsrgd.html

[N05] 最大公约数
来源：http://dali.cucudq.cn/Article/details/gtnletvnvq.html

Py:   math.gcd(a, b)
来源：http://dali.havefunace.top/Article/details/gtiiohiitb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ivvv.top/Article/details/gtfodcbjui.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gtbeykvsnk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ppjwa.cn/Article/details/gtzzadrmbr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.feifeiyinyue.top/Article/details/gtglijxedu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.316326.xyz/Article/details/gtwenqslcx.html

Ruby: a.gcd(b)
来源：http://dali.chenzaomai.com/Article/details/gtwgjskbig.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigfzy.top/Article/details/gtjgixvtqv.html

[N06] 判断回文字符串
来源：http://dali.jiagoushi.top/Article/details/gtymvoazkb.html

Py:   s == s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gtndpgwbqv.html

PHP:  $s === strrev($s);
来源：http://dali.tanke756.top/Article/details/gtpyfyqbkt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtkyaypihu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtootnghdp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhiwuduotai.top/Article/details/gtrprkkncx.html

Go:   // 双指针从两端比较
来源：http://dali.snrcjt.cn/Article/details/gtxypkofmh.html

Ruby: s == s.reverse
来源：http://dali.9152youxi.cn/Article/details/gteezpusev.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gtmajcakfg.html

[N07] 两数之和（返回下标）
来源：http://dali.cqqwz.cn/Article/details/gtfoxgvpzu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jianghu66.top/Article/details/gthldnytay.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgfzy.top/Article/details/gtiwlmatld.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gotoacloud.top/Article/details/gtxlajpake.html

TS:   // 手写 Map<string, number>
来源：http://dali.gzhubu.top/Article/details/gtozqqtxgo.html

Java: // 手写 HashMap
来源：http://dali.zhixingplan.top/Article/details/gtjwhifxwu.html

Go:   // 手写 map[int]int
来源：http://dali.hongshengwenyu.top/Article/details/gtmvktngaj.html

Ruby: // 手写 Hash
来源：http://dali.sufxvd.cn/Article/details/gtclkvbyqt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yuanzhike.top/Article/details/gtkvbvnekk.html

[N08] 生成全排列
来源：http://dali.jinqigfzy.top/Article/details/gtlsiwnxxs.html

Py:   itertools.permutations(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrbkbnfe.html

PHP:  // 手写递归交换
来源：http://dali.xinyue.icu/Article/details/gtzplcokuu.html

JS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gthfkfrgoi.html

TS:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtgfldsxns.html


<!-- 参考信息 -->