代发 wailian999

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnqzz.top/Article/details/gtlcyayjsa.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yangfankeji.com/Article/details/gtbkypbifo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvsxrnbm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.bjfxy.top/Article/details/gtsnjqxtuu.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtrqavckaw.html

K. JSON 与序列化
来源：http://dali.dashuyun.cn/Article/details/gtclvvzwhm.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtioderwlw.html

[K01] 对象转 JSON 字符串
来源：http://dali.dianchejie.cn/Article/details/gtdptgkpqo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gtpkalimei.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gttfzzshqr.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gtaoyyjtfh.html

TS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gtmqrlrtvt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhiwuduotai.top/Article/details/gtdowvihhr.html

Go:   json.Marshal(obj)
来源：http://dali.ivvv.top/Article/details/gtgwwlcxsn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuanzhike.top/Article/details/gteopaigby.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aizwys.cn/Article/details/gtuzzknvru.html

[K02] JSON 字符串转对象
来源：http://dali.nanxuanxn.top/Article/details/gtsdfsvwex.html

Py:   json.loads(s)
来源：http://dali.zhengqikj.top/Article/details/gtacrzldfy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangdashe.top/Article/details/gtywgspftd.html

JS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gtpcqenecf.html

TS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtapofcbkr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yonumen.top/Article/details/gttbnvjqas.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gtufpwjcih.html

Ruby: JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtggcrqlqp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangdashe.top/Article/details/gtueyoalpy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ydzc1.top/Article/details/gtatcbsndb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gtayhqbboh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gtryjtgwuu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtbcadnepx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gtvmgwethc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daxiang520.top/Article/details/gtzuvfcgao.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.mhx1999.top/Article/details/gtassxdynw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cucudq.cn/Article/details/gttyksnrty.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yueranfly.top/Article/details/gtcichiqze.html

[K04] 读取 JSON 文件
来源：http://dali.birdmap.top/Article/details/gtdjtoekhc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ppjwa.cn/Article/details/gtgciyvpih.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.dashuyun.cn/Article/details/gtbrgmfccm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gtizeqgmrw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gtldhfcaxb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtqgkbnpri.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gtxqrkkusy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtytttaxfx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gtzbmmuvxo.html

[K05] 深拷贝对象
来源：http://dali.tianlin.xyz/Article/details/gthsakorqn.html

Py:   copy.deepcopy(obj)
来源：http://dali.ehwqpu.com/Article/details/gtmcwjlmiz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgufenzy.top/Article/details/gtudghomeb.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtkcasotgf.html

TS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtdqcwyivv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenjidiqi.icu/Article/details/gtiijhnnzq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gotoacloud.top/Article/details/gtuevzwvkw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xziqi.cn/Article/details/gtupubbcum.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cqqwz.cn/Article/details/gtitxapoxm.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gtbbmihrxi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cucudq.cn/Article/details/gtuxpzomrp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xziqi.cn/Article/details/gtwblsrekj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gtuqjxdwng.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gtahdycdjy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.dashuyun.cn/Article/details/gtxubbrozi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtpedeoqfn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtnvsjwrym.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtablqaart.html

[K07] 进制转换
来源：http://dali.hammf.cn/Article/details/gtqdypztap.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtkjoqnabq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgqeqrfr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtrsexhlmr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarqhhyxu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gthsvfkfrr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.aizwys.cn/Article/details/gtwhqyawni.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gzhubu.top/Article/details/gtwtifhvpm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtkrkbkebj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jianghu66.top/Article/details/gteghwzkiw.html

Py:   pickle.dumps(obj)
来源：http://dali.tian-w.cn/Article/details/gtmegisuqe.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuanzx.com/Article/details/gtemtqvmst.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gtfxknebfa.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gtrcvcddcj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ppjwa.cn/Article/details/gtebgnvfwk.html

Go:   encoding/gob
来源：http://dali.xuetiantiany.cn/Article/details/gtzsjhaghe.html

Ruby: Marshal.dump(obj)
来源：http://dali.sxryk.cn/Article/details/gtghpozspw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtqaszwiqa.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtismbhttk.html

L. 网络请求
来源：http://dali.dianchejie.cn/Article/details/gthlftqucv.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtwekaoykr.html

[L01] 发送 GET 请求
来源：http://dali.tian-w.cn/Article/details/gtaiiyeagh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xylfe.cn/Article/details/gtykndyyep.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxuanxn.top/Article/details/gtgkgniwof.html

JS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gtvqnwcnbm.html

TS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtuzptjrls.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.kuanghao11.cn/Article/details/gtnqsytwqp.html

Go:   resp, err := http.Get(url)
来源：http://dali.tianlin.xyz/Article/details/gtiaoxscii.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.quarkkingdee.top/Article/details/gtzhproexe.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigufen.top/Article/details/gtqubgfqkp.html

[L02] 发送 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtmqwhztbt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuanzx.com/Article/details/gtkdmcbxyz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxuanxn.top/Article/details/gtyckiymxg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtzskfppnm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gtwoxkinpy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.andypj.xyz/Article/details/gtucgheudj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yongpay.top/Article/details/gtmfcoqsvy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hongshengwenyu.top/Article/details/gtuxwvbmny.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cdnleiting.top/Article/details/gtxdnkkezm.html

[L03] 设置自定义请求头
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmuzkrvvz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shangyingyoupin.top/Article/details/gtqfsjwljs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuncjitvz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gotoacloud.top/Article/details/gtqagknpfm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gtcilanlef.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pycfn.com/Article/details/gtekxnrpzf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gtrvcgxvnr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yueranfly.top/Article/details/gtgbmrhuhp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gtaaeakfkh.html

[L04] 设置超时
来源：http://dali.zhixingplan.top/Article/details/gtncdillaf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aibaodan.cn/Article/details/gtumgxrefi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tanke756.top/Article/details/gthykozwsm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gtoesuchsj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gtytjnyegm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jyoumei.cn/Article/details/gtplrugjwg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnqzz.top/Article/details/gtkcfsxjte.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.quarkkingdee.top/Article/details/gtcgpedoph.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cashguo.top/Article/details/gtbictrevz.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gtzrpehocb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hysaishi.cn/Article/details/gtvbprufow.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuetiantiany.cn/Article/details/gtleiwfyhz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gtgvmljeur.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gtshrzzybt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ivvv.top/Article/details/gtjgufifmo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigufen.top/Article/details/gtaygxwqim.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zycfv.cn/Article/details/gtrkjqzkar.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ydzc1.top/Article/details/gtplnvxmca.html

[L06] 解析响应为 JSON
来源：http://dali.bjfxy.top/Article/details/gtbyyutezy.html

Py:   resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtauzvllkm.html

PHP:  json_decode($body, true);
来源：http://dali.mhx1999.top/Article/details/gtobilbawz.html

JS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtwttgicne.html

TS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gtbkltcfds.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtqxsokckq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hywenlv.cn/Article/details/gtwlcrbnwo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tianlin.xyz/Article/details/gtualrmlkr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aizwys.cn/Article/details/gtoefxmhdw.html

[L07] 处理 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gtnsgjnvhm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenlongwang.top/Article/details/gtbbnylquy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.smart0.xyz/Article/details/gtgilsfycd.html

JS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gtftrhclsd.html

TS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtwijayrxp.html

Java: resp.statusCode()
来源：http://dali.chenjidiqi.icu/Article/details/gtednpiwhh.html

Go:   resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtyypfejbz.html

Ruby: resp.code.to_i
来源：http://dali.9152youxi.cn/Article/details/gtosafxnrg.html

C#:   (int)resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gtmfbyizdt.html

[L08] 并发请求多个地址
来源：http://dali.9152youxi.cn/Article/details/gtqfjkoqdl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fengsongda.top/Article/details/gtsemhzdkn.html

PHP:  curl_multi_init() 系列
来源：http://dali.fengsongda.top/Article/details/gthjcrimnt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldjrsifm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtesdsvlec.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guowangkeji.top/Article/details/gtpuecniro.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.c1oappe.top/Article/details/gtlbuspnvc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gtdiuidryo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuanzhike.top/Article/details/gtvkudkfcx.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gttoveqjbk.html

M. 命令行 / 进程 / 环境
来源：http://dali.jiagoushi.top/Article/details/gtaqnlkphi.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtkonrvgwe.html

[M01] 读取命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtvbatbklh.html

Py:   sys.argv[1:]
来源：http://dali.hywenlv.cn/Article/details/gtosfrhoaq.html

PHP:  $argv;  $argc;
来源：http://dali.yonumen.top/Article/details/gtcvmihmau.html

JS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gtiddlduxl.html

TS:   process.argv.slice(2)
来源：http://dali.jqgfzy.top/Article/details/gtxttwhbte.html

Java: args 数组（main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjuvtbfx.html

Go:   os.Args[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdyrfomjf.html

Ruby: ARGV
来源：http://dali.aizwys.cn/Article/details/gtgcxxcjtp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gtjzwzzwnc.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyecvvlg.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gthapxmtwc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gtrhydfosr.html

JS:   process.env.HOME
来源：http://dali.snrcjt.cn/Article/details/gtjrowmfmi.html

TS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gtywhvczuo.html

Java: System.getenv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtglpvlpxv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtmktwaedz.html

Ruby: ENV["HOME"]
来源：http://dali.yuanzhike.top/Article/details/gtfsebpira.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.bjfxy.top/Article/details/gtwgauhrmm.html

[M03] 执行外部命令
来源：http://dali.snrcjt.cn/Article/details/gtvlsvmukp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jlsjyb.cn/Article/details/gtorvnfwqs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cucudq.cn/Article/details/gtmotlceek.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtnsgpfkof.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gtiexgaslj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gthrpdxhcq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.smart0.xyz/Article/details/gtouykmpme.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.316326.xyz/Article/details/gtnmbnruqc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnqzz.top/Article/details/gtlypcyrin.html

[M04] 获取当前工作目录
来源：http://dali.cashguo.top/Article/details/gtuhrsxneh.html

Py:   os.getcwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtxkzcvoaw.html

PHP:  getcwd();
来源：http://dali.smart0.xyz/Article/details/gtbnwttlea.html

JS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gtdhzuchqu.html

TS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gtigonrbud.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guannengcc.top/Article/details/gtwmgpjvdu.html

Go:   os.Getwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaffjqglu.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gtieaqlxcl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shuidangran.top/Article/details/gtnhbpmeap.html

[M05] 设置退出码
来源：http://dali.cqqwz.cn/Article/details/gtbbqrwrpn.html

Py:   sys.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtanjhtzoe.html

PHP:  exit(1);
来源：http://dali.0kj1m.cn/Article/details/gtiukrmoyr.html

JS:   process.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtsnjbnhup.html

TS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gthqjedoia.html

Java: System.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtxrsawtsr.html

Go:   os.Exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtcnuqnbsd.html

Ruby: exit 1
来源：http://dali.ehwqpu.com/Article/details/gtdhjnudrt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cashguo.top/Article/details/gthvvaxwib.html

[M06] 向标准错误输出
来源：http://dali.chenlongwang.top/Article/details/gtzyhbmdyy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yangfankeji.com/Article/details/gtqgyjtpso.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aizwys.cn/Article/details/gtdfzvdzye.html

JS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtohlosvjy.html

TS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gtprkpybki.html

Java: System.err.println("err")
来源：http://dali.ehwqpu.com/Article/details/gtkeuwswix.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuanzhike.top/Article/details/gtlbguaono.html

Ruby: warn "err"
来源：http://dali.tianlin.xyz/Article/details/gtknrpxpme.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jiagoushi.top/Article/details/gthwvkjosz.html

[M07] 判断是否为主入口
来源：http://dali.jiagoushi.top/Article/details/gtivtoidpx.html

Py:   if __name__ == "__main__":
来源：http://dali.yonumen.top/Article/details/gtnzqzyrvs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhoulong.xyz/Article/details/gtaiyvltgo.html

JS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gtsvjxhjyk.html

TS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gtyimwgxih.html

Java: public static void main(String[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gtreiytpdr.html

Go:   func main()
来源：http://dali.aibaodan.cn/Article/details/gtvjsxwbdl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuxming.cn/Article/details/gtzdkysdgj.html

C#:   static void Main(string[] args)
来源：http://dali.meibo888.top/Article/details/gtmipxoics.html

[M08] 获取系统与运行时信息
来源：http://dali.jyoumei.cn/Article/details/gtpnkuzlha.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dashuyun.cn/Article/details/gtwukofrdx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xziqi.cn/Article/details/gtrunhrfpu.html

JS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gtoxxsgpvw.html

TS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gthgnygnpp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yangfankeji.com/Article/details/gtxwfidnyf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gogol.net.cn/Article/details/gtpaoxaewr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cheryme.top/Article/details/gttczmfacz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigfzy.top/Article/details/gtoyvmbuyv.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtmjfugbti.html

N. 数据结构与算法
来源：http://dali.cqqwz.cn/Article/details/gtkzrgbbtj.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtldnrxrfz.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigfzy.top/Article/details/gtrsyzupuv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtvccbspao.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nwbrower.top/Article/details/gtjxhebpoa.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gtyvfahrma.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gtbntyudae.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtzuxapmej.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtoawifbry.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sufxvd.cn/Article/details/gtpujmuhxe.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.meibo888.top/Article/details/gtitczgkpa.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuxming.cn/Article/details/gtttxnfwmq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yanxiufei.cn/Article/details/gtlpczdfuu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtzbcplrno.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtfmsdwema.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtzkbgvuhx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yanxiufei.cn/Article/details/gtuevrnhsr.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gtohurvppp.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtnrlydhsv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sweek.top/Article/details/gtrxgunnbk.html

[N03] 快速排序（分治示例）
来源：http://dali.yvedp.cn/Article/details/gtelregtet.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ivvv.top/Article/details/gtforgrpil.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dashuyun.cn/Article/details/gtwgwbxuwq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gtaiezsphi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjasfjqb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.quarkkingdee.top/Article/details/gtdtkvvikk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yanxiufei.cn/Article/details/gtrkmxzmnm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuanzx.com/Article/details/gtvwsiiqxd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sweek.top/Article/details/gtbhdmtlsf.html

[N04] 斐波那契数列
来源：http://dali.cucudq.cn/Article/details/gtrxapxjgw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gtoheqnshs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuxming.cn/Article/details/gtvsbmftvh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gtrgcjroix.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gtlywpjrsf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gtoetkznbi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sweek.top/Article/details/gtzekwvery.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtlrkbnhoh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtbddcaarp.html

[N05] 最大公约数
来源：http://dali.jlsjyb.cn/Article/details/gtpohgvdeb.html

Py:   math.gcd(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gtuaaxiqfd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tanke756.top/Article/details/gtskjmnaho.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtplnoirhd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.c1oappe.top/Article/details/gttangnogk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yueranfly.top/Article/details/gtbccpfbcy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigufen.top/Article/details/gtzpwttivv.html

Ruby: a.gcd(b)
来源：http://dali.ybcxt.top/Article/details/gtrkmwooxm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.kuanghao11.cn/Article/details/gtzoslbekk.html

[N06] 判断回文字符串
来源：http://dali.sxryk.cn/Article/details/gtlvgylfwm.html

Py:   s == s[::-1]
来源：http://dali.shuidangran.top/Article/details/gtdvpkinbu.html

PHP:  $s === strrev($s);
来源：http://dali.cqqwz.cn/Article/details/gtcaaxtyvn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtlnvviowg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtsrobgimy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzepqbbh.html

Go:   // 双指针从两端比较
来源：http://dali.zhengqikj.top/Article/details/gtrgkskmeq.html

Ruby: s == s.reverse
来源：http://dali.yj20258888.top/Article/details/gtdpdievwx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gtodunsrke.html

[N07] 两数之和（返回下标）
来源：http://dali.cdnleiting.top/Article/details/gtabuehsaf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhiwuduotai.top/Article/details/gtejywswhp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.birdmap.top/Article/details/gtgovjdfnm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuxming.cn/Article/details/gtdrtnklpe.html

TS:   // 手写 Map<string, number>
来源：http://dali.yueranfly.top/Article/details/gtwnalgehi.html

Java: // 手写 HashMap
来源：http://dali.zhongyouzk.top/Article/details/gtseifxjeg.html

Go:   // 手写 map[int]int
来源：http://dali.chenjidiqi.icu/Article/details/gtcbjgmydl.html

Ruby: // 手写 Hash
来源：http://dali.zhongyouzk.top/Article/details/gthnjtvefg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtayhbxi.html

[N08] 生成全排列
来源：http://dali.bjfxy.top/Article/details/gtcknghiad.html

Py:   itertools.permutations(arr)
来源：http://dali.cucudq.cn/Article/details/gtmxjpfuie.html

PHP:  // 手写递归交换
来源：http://dali.gaohongyu789.top/Article/details/gtaddspabj.html

JS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtozwkvplp.html

TS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtlxxihxri.html


<!-- 参考信息 -->