代发 wailian999

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sxryk.cn/Article/details/gtxgltqqpt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.redwolf501.top/Article/details/gtchiqmvmy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnxiangtu.top/Article/details/gtwfddswkx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xinyue.icu/Article/details/gtvhoodrol.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtzzusgkod.html

K. JSON 与序列化
来源：http://dali.guowangkeji.top/Article/details/gtpytaadjp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtiybtmeyv.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjexydee.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtwkiqjxxn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtfjgwvldj.html

JS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gtggoilupr.html

TS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gtdtoxandj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gtnuadhuzt.html

Go:   json.Marshal(obj)
来源：http://dali.hfpthk.cn/Article/details/gtbeunfjsd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shuidangran.top/Article/details/gtsobvgnos.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj202588.top/Article/details/gtephdrvke.html

[K02] JSON 字符串转对象
来源：http://dali.hnqzz.top/Article/details/gtkhdqlksc.html

Py:   json.loads(s)
来源：http://dali.zhongyouzk.top/Article/details/gtawadmorj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hywenlv.cn/Article/details/gtutdjduue.html

JS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtaxsxvjnb.html

TS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtbmxfdzkm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtkrmthjks.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gtxnrzkrbz.html

Ruby: JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtqbtphnoe.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jianghu66.top/Article/details/gtporsgriz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yongpay.top/Article/details/gtenrphsdp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gtaohmvtdf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gtohpyrgda.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gtdtctohel.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtjarfyyly.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jiagoushi.top/Article/details/gtnjlbvrhh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nwbrower.top/Article/details/gteyfzsumk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aibaodan.cn/Article/details/gtbnnesboa.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xinyue.icu/Article/details/gtlprbfiub.html

[K04] 读取 JSON 文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqouvwbn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.mhx1999.top/Article/details/gtaetpqgmc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sweek.top/Article/details/gtxldvstoh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtudbxiach.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gtdqfvjjbh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtumkdfdxb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gtkjiolgjg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yangfankeji.com/Article/details/gtsazuolip.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuxming.cn/Article/details/gtdpikpqdl.html

[K05] 深拷贝对象
来源：http://dali.cucudq.cn/Article/details/gturwjygsv.html

Py:   copy.deepcopy(obj)
来源：http://dali.sysykeji.top/Article/details/gtkockopbs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sysykeji.top/Article/details/gttizupewr.html

JS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtovwzzydq.html

TS:   structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdmdmtfx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.quarkkingdee.top/Article/details/gtdkvzgcdv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.aizwys.cn/Article/details/gtpfzoockx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tanke756.top/Article/details/gtyjwmoxkl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.316326.xyz/Article/details/gtrgsgbwne.html

[K06] 解析 URL 查询串
来源：http://dali.316326.xyz/Article/details/gtsfilrohp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.bjfxy.top/Article/details/gtksqhpzol.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yanxiufei.cn/Article/details/gtbvskneee.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gtccliwyyu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dianchejie.cn/Article/details/gttycvowjp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhongyouzk.top/Article/details/gtdlmustpr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtwgwvjucv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtlpapwxdw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtsusgyrkq.html

[K07] 进制转换
来源：http://dali.mhx1999.top/Article/details/gtniggskdt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitioghxr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tianlin.xyz/Article/details/gthusgcyla.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqsmjnde.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gticqvcbke.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtmerkldnd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigfzy.top/Article/details/gtlvmceyme.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xziqi.cn/Article/details/gtpgnybooc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtqzrjdini.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ppjwa.cn/Article/details/gtdsugsaaz.html

Py:   pickle.dumps(obj)
来源：http://dali.gzhubu.top/Article/details/gtvedosktz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cdnleiting.top/Article/details/gtcespsexm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gtrpcnhmof.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gthszxtncg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuxming.cn/Article/details/gtgznwxdrl.html

Go:   encoding/gob
来源：http://dali.yueranfly.top/Article/details/gtkwogckap.html

Ruby: Marshal.dump(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtengojjan.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtmksrtdeh.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtonxyokzm.html

L. 网络请求
来源：http://dali.chenjidiqi.icu/Article/details/gtdwzswwpy.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gthgfinbjv.html

[L01] 发送 GET 请求
来源：http://dali.quarkkingdee.top/Article/details/gtveiekclk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.svipenyu.cn/Article/details/gtvlmtrfdw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjbpnqgs.html

JS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gtlfoniktp.html

TS:   await fetch(url)
来源：http://dali.cdnleiting.top/Article/details/gtpbxivwiq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sxryk.cn/Article/details/gtzlxcdrak.html

Go:   resp, err := http.Get(url)
来源：http://dali.pycfn.com/Article/details/gtucdggddx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.mhx1999.top/Article/details/gtseibdmpi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daxiang520.top/Article/details/gtruggiqlo.html

[L02] 发送 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gtmviimiqd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gteaijedpy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tianlin.xyz/Article/details/gtsgkippqy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gtkrfzrlto.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gtawlugcaz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gtxwbafeje.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shangyingyoupin.top/Article/details/gtlsfchmbe.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jiagoushi.top/Article/details/gtrkyxcsym.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sxryk.cn/Article/details/gtimwlhpym.html

[L03] 设置自定义请求头
来源：http://dali.cqqwz.cn/Article/details/gtjkactayw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hysaishi.cn/Article/details/gtwiysquiv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.smart0.xyz/Article/details/gtuthbfuwy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gtehyvvnxy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gtjyskhhbm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yvedp.cn/Article/details/gtcmxmpgem.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtnheweron.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj202588.top/Article/details/gtigrtlbtw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258.top/Article/details/gtidwteypw.html

[L04] 设置超时
来源：http://dali.vqdsnc.cn/Article/details/gtieupapkr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxuanxn.top/Article/details/gtqzanxabw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cucudq.cn/Article/details/gtslkmznfk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gtejnsqegi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gtglmkepyt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenlongwang.top/Article/details/gtegcghrnl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.meibo888.top/Article/details/gtjwvjakfo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.bjfxy.top/Article/details/gtlsoqhxmw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxznmimen.html

[L05] 上传文件（multipart）
来源：http://dali.cdnleiting.top/Article/details/gtzkijalrs.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjlbmztx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shzxlz.cn/Article/details/gtkjgzevar.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gtezdtargl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gttqogtwan.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.redwolf501.top/Article/details/gtnxfkqyiu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sysykeji.top/Article/details/gtyxfhpslc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangtech.top/Article/details/gtjisijgpe.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fzhhl.top/Article/details/gtnknhvpqp.html

[L06] 解析响应为 JSON
来源：http://dali.aibaodan.cn/Article/details/gttwvyjqmx.html

Py:   resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gtgokwcktd.html

PHP:  json_decode($body, true);
来源：http://dali.sweek.top/Article/details/gtddgkmrrg.html

JS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtmqhrcfts.html

TS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gtaaenhtti.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xylfe.cn/Article/details/gttteteuvx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhiwuduotai.top/Article/details/gtljiobgfl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj202588.top/Article/details/gthzffcawe.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfeklgpww.html

[L07] 处理 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gtssekfwej.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cheryme.top/Article/details/gtdxuvztjt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzjeeaag.html

JS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtrbrvjthd.html

TS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gttqqqkfgb.html

Java: resp.statusCode()
来源：http://dali.zhiwuduotai.top/Article/details/gtgteqrwwm.html

Go:   resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gtboeacbrq.html

Ruby: resp.code.to_i
来源：http://dali.guowangkeji.top/Article/details/gtfsgtjrnw.html

C#:   (int)resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gtebojfafi.html

[L08] 并发请求多个地址
来源：http://dali.fengsongda.top/Article/details/gtjgrdrjmw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tianlin.xyz/Article/details/gthaewrcak.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhixingplan.top/Article/details/gtteyhjogt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gtlzofaxrn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gtodfinybu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.pycfn.com/Article/details/gtrhgkxnzc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ppjwa.cn/Article/details/gtovrcfqwf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sxryk.cn/Article/details/gtqeigsbgq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yvedp.cn/Article/details/gtyttsizfq.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtppklatfj.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhongyouzk.top/Article/details/gtaeivsduv.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtnlxrawpz.html

[M01] 读取命令行参数
来源：http://dali.jqgfzy.top/Article/details/gtpgivzsni.html

Py:   sys.argv[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtoqfxlokh.html

PHP:  $argv;  $argc;
来源：http://dali.cdnleiting.top/Article/details/gtbriykyzf.html

JS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtvyplrjfj.html

TS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gtnccxhymh.html

Java: args 数组（main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtjmevrgmc.html

Go:   os.Args[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtctrjvgqz.html

Ruby: ARGV
来源：http://dali.9152youxi.cn/Article/details/gtkqzvvlmf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtrdesuxle.html

[M02] 读取环境变量
来源：http://dali.cashguo.top/Article/details/gtridttexg.html

Py:   os.environ.get("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtdiombzqd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gtijraggdo.html

JS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtcnhciwbv.html

TS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gtnazrhzzc.html

Java: System.getenv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtmvekyvxw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtdfoannlk.html

Ruby: ENV["HOME"]
来源：http://dali.yvedp.cn/Article/details/gthomavqee.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtusgmcgul.html

[M03] 执行外部命令
来源：http://dali.pengpengdd.cyou/Article/details/gtkjiuyluz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtfbyduuzn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuanzx.com/Article/details/gtblsrwcof.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtytzkyfkr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gteebwcnoy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shuidangran.top/Article/details/gtgdstluii.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenjidiqi.icu/Article/details/gtcxagrrfz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hfpthk.cn/Article/details/gtluvvdwcs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.dashuyun.cn/Article/details/gtwkgczgoc.html

[M04] 获取当前工作目录
来源：http://dali.svipenyu.cn/Article/details/gttopqtvfz.html

Py:   os.getcwd()
来源：http://dali.shzxlz.cn/Article/details/gtxahraqzo.html

PHP:  getcwd();
来源：http://dali.pengpengdd.cyou/Article/details/gthujkbgrf.html

JS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gtokulvcvp.html

TS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gthgemchcv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.birdmap.top/Article/details/gtselnglil.html

Go:   os.Getwd()
来源：http://dali.yuanzhike.top/Article/details/gtupqshakv.html

Ruby: Dir.pwd
来源：http://dali.xuetiantiany.cn/Article/details/gtonveixhn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhongyouzk.top/Article/details/gtejwtehyi.html

[M05] 设置退出码
来源：http://dali.hammf.cn/Article/details/gtcfyaenvd.html

Py:   sys.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtdhxpnwnz.html

PHP:  exit(1);
来源：http://dali.gotoacloud.top/Article/details/gtqrzrtnyj.html

JS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtzedfpfer.html

TS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtiiinbutm.html

Java: System.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtfxdifirm.html

Go:   os.Exit(1)
来源：http://dali.sysykeji.top/Article/details/gthjxmjpyr.html

Ruby: exit 1
来源：http://dali.cheryme.top/Article/details/gtmqhwdhkc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnxiangtu.top/Article/details/gtbjdrmxjm.html

[M06] 向标准错误输出
来源：http://dali.guannengcc.top/Article/details/gtmhbxxveu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hammf.cn/Article/details/gtliobtmes.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ivvv.top/Article/details/gtpcmbqqkr.html

JS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gtnwflyeue.html

TS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gthpgljltw.html

Java: System.err.println("err")
来源：http://dali.ehwqpu.com/Article/details/gtjtyiaxhl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zdqjudy.top/Article/details/gtwfbkwkpg.html

Ruby: warn "err"
来源：http://dali.shuidangran.top/Article/details/gtppvmxwup.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.vqdsnc.cn/Article/details/gtsypbooyp.html

[M07] 判断是否为主入口
来源：http://dali.jyoumei.cn/Article/details/gtxujeojnx.html

Py:   if __name__ == "__main__":
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpsxvyop.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258.top/Article/details/gtlsbdvgsf.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gthrzcpvvj.html

TS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gtfctyegpp.html

Java: public static void main(String[] args)
来源：http://dali.hywenlv.cn/Article/details/gtxhrteird.html

Go:   func main()
来源：http://dali.cashguo.top/Article/details/gtscfiklqv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258888.top/Article/details/gttxvthsay.html

C#:   static void Main(string[] args)
来源：http://dali.hnxiangtu.top/Article/details/gtpxdtnoib.html

[M08] 获取系统与运行时信息
来源：http://dali.jinqigfzy.top/Article/details/gtxgazqupn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.c1oappe.top/Article/details/gttjznxthn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258.top/Article/details/gtcmzstocs.html

JS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gtobyrghqy.html

TS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtfwujitop.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aizwys.cn/Article/details/gtpxbvaeoj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuetiantiany.cn/Article/details/gtbhgamxmy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cashguo.top/Article/details/gtmxzypbzi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tianlin.xyz/Article/details/gtnonbglnc.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtohktxyuu.html

N. 数据结构与算法
来源：http://dali.tianlin.xyz/Article/details/gtzfpxloxx.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtonydgjfj.html

[N01] 二分查找（有序数组）
来源：http://dali.birdmap.top/Article/details/gtnqxveofe.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtzdhhauxy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtqsbzjcoi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtotpqgkku.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gtcsowzvsb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtaivbxwgo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj20258.top/Article/details/gtaauhrhvu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ybcxt.top/Article/details/gtlhfaitqv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gtkcpiivfn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxinkj.top/Article/details/gtfoblzvbl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxiqrqxma.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gttdnudkdd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gtfcgbfwfl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtoscnpeab.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gzhubu.top/Article/details/gtgmpoycsg.html

Go:   slices.Sort(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevwgifgb.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gtpbiigatm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvyhnodqj.html

[N03] 快速排序（分治示例）
来源：http://dali.aibaodan.cn/Article/details/gtijemesln.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zycfv.cn/Article/details/gtdbfgwrnc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gaohongyu789.top/Article/details/gtbcsmmqpz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gttxgjrsem.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gttgxmvguf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pengpengdd.cyou/Article/details/gtvchjpjtf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigufen.top/Article/details/gtubjhnoun.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tanke756.top/Article/details/gtgjzomvrm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.bjfxy.top/Article/details/gtfevskqkf.html

[N04] 斐波那契数列
来源：http://dali.hongshengwenyu.top/Article/details/gtbmpioedy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gtetpmpssf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ivvv.top/Article/details/gtwbmvthvm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtljvrxshd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtumegmdvo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cqqwz.cn/Article/details/gtmpbspjcs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xinyue.icu/Article/details/gtgtdtjost.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtmzjmnkov.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtsgrqekcs.html

[N05] 最大公约数
来源：http://dali.yangfankeji.com/Article/details/gtqvrsuewn.html

Py:   math.gcd(a, b)
来源：http://dali.meibo888.top/Article/details/gtemausrao.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gtxzfhaava.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gtinokjfjb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzrtqqyls.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tanke756.top/Article/details/gtceejwfmk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinghuilouyu.cn/Article/details/gttdnsiilt.html

Ruby: a.gcd(b)
来源：http://dali.hysaishi.cn/Article/details/gtckiqensl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cashguo.top/Article/details/gtrtotqxhb.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gtalxtccfe.html

Py:   s == s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdkanrga.html

PHP:  $s === strrev($s);
来源：http://dali.tian-w.cn/Article/details/gtciwoqhfn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtndorfkjl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtvlzjrrll.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shuidangran.top/Article/details/gtsqbbgqlk.html

Go:   // 双指针从两端比较
来源：http://dali.pycfn.com/Article/details/gthofxgswb.html

Ruby: s == s.reverse
来源：http://dali.wangdashe.top/Article/details/gtjrvrxpsg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gtlkdbtrdn.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgufenzy.top/Article/details/gtpjoidjfy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.kuanghao11.cn/Article/details/gtzotyqxng.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhixingplan.top/Article/details/gtukprvpkd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppmgvemh.html

TS:   // 手写 Map<string, number>
来源：http://dali.cheryme.top/Article/details/gtwhjwnkld.html

Java: // 手写 HashMap
来源：http://dali.yj202588.top/Article/details/gtmqwehmyo.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258888.top/Article/details/gtailgbbcf.html

Ruby: // 手写 Hash
来源：http://dali.yonumen.top/Article/details/gtlkdaidvh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zycfv.cn/Article/details/gtsbqdmbsk.html

[N08] 生成全排列
来源：http://dali.yanxiufei.cn/Article/details/gttyqsnxnt.html

Py:   itertools.permutations(arr)
来源：http://dali.ppjwa.cn/Article/details/gthglvygiz.html

PHP:  // 手写递归交换
来源：http://dali.gotoacloud.top/Article/details/gtlqpfvaca.html

JS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtcxxmildc.html

TS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gthpkeuswh.html


<!-- 参考信息 -->