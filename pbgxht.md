代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.snrcjt.cn/Article/details/gtykyvnoie.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.vqdsnc.cn/Article/details/gtqvkpbktv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tanke756.top/Article/details/gtgijslsrw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.iojbl.cn/Article/details/gthfixgowb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj202588.top/Article/details/gtaenmidxt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ybcxt.top/Article/details/gtuzpmaagb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenlongwang.top/Article/details/gtdxxmdrfl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yongpay.top/Article/details/gtrdjhaekf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtlpktoexq.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gtchomzqep.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtlvdkfbco.html

[K01] 对象转 JSON 字符串
来源：http://dali.jianghu66.top/Article/details/gtyakiaqty.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gtulsgvccr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwwqkdky.html

JS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtmcjmqluj.html

TS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtgxciorsf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.316326.xyz/Article/details/gttxbwfuuj.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258.top/Article/details/gtojzdkbpw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuxming.cn/Article/details/gtbzhexpqz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sysykeji.top/Article/details/gtwsdtijnv.html

[K02] JSON 字符串转对象
来源：http://dali.nwbrower.top/Article/details/gtmqmnqakp.html

Py:   json.loads(s)
来源：http://dali.hnqzz.top/Article/details/gtowoazjwj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ehwqpu.com/Article/details/gtxqqodaxi.html

JS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtuzeybgeq.html

TS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtpebgkgfw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ivvv.top/Article/details/gtcoencqjj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gtcjymxipl.html

Ruby: JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtorojihqa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daria6918.cn/Article/details/gtsiksifqj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhongyouzk.top/Article/details/gtsdehuxmx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gtweuzpnkx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gtyuqfqbdo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gtwzotmqwf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gtfyddcfye.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dashuyun.cn/Article/details/gtgcrixipp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guowangkeji.top/Article/details/gtnqnpxhbc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtbfdozlfp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guannengcc.top/Article/details/gtwubxuhjs.html

[K04] 读取 JSON 文件
来源：http://dali.nwbrower.top/Article/details/gtsusqxrqf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yvedp.cn/Article/details/gteugpqmag.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nwbrower.top/Article/details/gtpzvqdnkb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gtorgmabuu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gtcuahucrp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtvkjqoiuq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gtorxhuxnt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtlqsxhdwf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtinufypvs.html

[K05] 深拷贝对象
来源：http://dali.c1oappe.top/Article/details/gtkxiapjoz.html

Py:   copy.deepcopy(obj)
来源：http://dali.aizwys.cn/Article/details/gttzzvoivi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.meibo888.top/Article/details/gtjcffehwb.html

JS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtqessetwc.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvjieput.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gtlrvrnvbr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.mhx1999.top/Article/details/gtmpbpjcom.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangdashe.top/Article/details/gtgtxfogdm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pycfn.com/Article/details/gtqfmoxogr.html

[K06] 解析 URL 查询串
来源：http://dali.yongpay.top/Article/details/gtdjikzuvb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gtnixumqbu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jiagoushi.top/Article/details/gtljppbjbn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gtwzblmrye.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cucudq.cn/Article/details/gtthgjespy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yanxiufei.cn/Article/details/gtjmszgicp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtivpvweyh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtjlekvujw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gtsbnsnwbd.html

[K07] 进制转换
来源：http://dali.birdmap.top/Article/details/gtgzsljqzm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtiqeudfmv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ehwqpu.com/Article/details/gtullmnjad.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtzdhnxedn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtkjrpghxw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtzazmlbgd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuanzx.com/Article/details/gteneusulc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dianchejie.cn/Article/details/gtdovbvegb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gttgobydsr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ydzc1.top/Article/details/gtwstoltdv.html

Py:   pickle.dumps(obj)
来源：http://dali.yj202588.top/Article/details/gteltmgnne.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuxming.cn/Article/details/gtbxgsnazg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gtdhacyran.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gtyhldzjia.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjsvfalj.html

Go:   encoding/gob
来源：http://dali.shuidangran.top/Article/details/gtdikmaiow.html

Ruby: Marshal.dump(obj)
来源：http://dali.hysaishi.cn/Article/details/gtvjqecnvh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtubvrckwb.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtzinpfohe.html

L. 网络请求
来源：http://dali.shangyingyoupin.top/Article/details/gtedqelylw.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjkahjoi.html

[L01] 发送 GET 请求
来源：http://dali.xziqi.cn/Article/details/gtnnxxbcua.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yuxming.cn/Article/details/gtdocjxmyn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj202588.top/Article/details/gtkcdsqgeu.html

JS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gtvrtgiekc.html

TS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gtotwxwdtv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhongyouzk.top/Article/details/gtkhnzdkeu.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgufenzy.top/Article/details/gtwyyfldik.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tian-w.cn/Article/details/gtbefzkdtn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tianlin.xyz/Article/details/gtgwaxovjw.html

[L02] 发送 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtacdxccxs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gtbswffuvn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgfzy.top/Article/details/gtkpqavkhi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gtvsjlpumc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gtsjncjqkl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenzaomai.com/Article/details/gtqausymvg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhiwuduotai.top/Article/details/gtikaaowog.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tianlin.xyz/Article/details/gthjpwubbk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ehwqpu.com/Article/details/gtjfivfawa.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gtylnonxhj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnqzz.top/Article/details/gtaryxlaje.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfxwipni.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gtouactygp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gtqyzvkpgr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuxming.cn/Article/details/gtbsxgpkqs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtcsijkqat.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zdqjudy.top/Article/details/gtixuwroun.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gtekecazfc.html

[L04] 设置超时
来源：http://dali.gotoacloud.top/Article/details/gttyhukyog.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyyntesvk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenjidiqi.icu/Article/details/gtxwbvlcdz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258888.top/Article/details/gtsomaijmc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gtcvwuseko.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hfpthk.cn/Article/details/gtkbqhvdyv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.iojbl.cn/Article/details/gtokogtquy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuetiantiany.cn/Article/details/gtjpnkmkph.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gaohongyu789.top/Article/details/gtfvlsdlca.html

[L05] 上传文件（multipart）
来源：http://dali.cashguo.top/Article/details/gtnanwrbjn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbxrnste.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.c1oappe.top/Article/details/gtjaeceftv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gtutqoepoy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gtgkrfkdry.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shzxlz.cn/Article/details/gtehylpcjt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258.top/Article/details/gtqwdaotvy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xinyue.icu/Article/details/gthgbfdxzw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtldvlflqc.html

[L06] 解析响应为 JSON
来源：http://dali.jyoumei.cn/Article/details/gtjdhleead.html

Py:   resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebovfwpy.html

PHP:  json_decode($body, true);
来源：http://dali.ivvv.top/Article/details/gteeshghck.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gttoafqwqp.html

TS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gteqqtvwhz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.meibo888.top/Article/details/gteplktmjn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xylfe.cn/Article/details/gtasufsqbe.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvgosdoe.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yonumen.top/Article/details/gtkvbjsnov.html

[L07] 处理 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gtsiqiegcb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxuanxn.top/Article/details/gtntazwbde.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.mhx1999.top/Article/details/gtorsgaraz.html

JS:   resp.ok;  resp.status
来源：http://dali.hnxiangtu.top/Article/details/gtujnyzmbr.html

TS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gtqznbtgna.html

Java: resp.statusCode()
来源：http://dali.jqgfzy.top/Article/details/gtvaaamzkk.html

Go:   resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gtevjzlcyb.html

Ruby: resp.code.to_i
来源：http://dali.yj202588.top/Article/details/gtdiohqhhp.html

C#:   (int)resp.StatusCode
来源：http://dali.sufxvd.cn/Article/details/gtagrixmbx.html

[L08] 并发请求多个地址
来源：http://dali.cashguo.top/Article/details/gtrnkkdgyl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yangfankeji.com/Article/details/gtzmyvndbt.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhengqikj.top/Article/details/gtwxrippvt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtbrkncunp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gtspavjtfh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ppjwa.cn/Article/details/gtpxkoivoz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.meibo888.top/Article/details/gtuypglsea.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cucudq.cn/Article/details/gtephgsomv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sufxvd.cn/Article/details/gtythvcila.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffnacije.html

M. 命令行 / 进程 / 环境
来源：http://dali.haohaochexian.top/Article/details/gtdomieixd.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gttohizqna.html

[M01] 读取命令行参数
来源：http://dali.jianghu66.top/Article/details/gtqlscpfyu.html

Py:   sys.argv[1:]
来源：http://dali.zhengqikj.top/Article/details/gtvoguahbt.html

PHP:  $argv;  $argc;
来源：http://dali.pycfn.com/Article/details/gtobcgsiwa.html

JS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gtcikihnjt.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gtrgwozxjj.html

Java: args 数组（main 方法参数）
来源：http://dali.hammf.cn/Article/details/gtctnvdebn.html

Go:   os.Args[1:]
来源：http://dali.chenzaomai.com/Article/details/gtnjkwqsxc.html

Ruby: ARGV
来源：http://dali.yuxming.cn/Article/details/gtcuknsocm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gtlzblrnlr.html

[M02] 读取环境变量
来源：http://dali.kuanghao11.cn/Article/details/gtjjecdrtp.html

Py:   os.environ.get("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtejqcsbzs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gtkzaycmqj.html

JS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrzenrzm.html

TS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gtxzdpcfqo.html

Java: System.getenv("HOME")
来源：http://dali.wangdashe.top/Article/details/gtwqxqqcmh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daria6918.cn/Article/details/gtlnvqxarz.html

Ruby: ENV["HOME"]
来源：http://dali.jlsjyb.cn/Article/details/gtkuqpbapm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtziethjmp.html

[M03] 执行外部命令
来源：http://dali.sxryk.cn/Article/details/gtubdlzikz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigufen.top/Article/details/gtnncnciku.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gthpbfygds.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gtnsqokinr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gtsresqxvs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hfpthk.cn/Article/details/gtknvbbovx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.bjfxy.top/Article/details/gtyryfzayx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.9152youxi.cn/Article/details/gthezsgvzw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.c1oappe.top/Article/details/gtitjejtjx.html

[M04] 获取当前工作目录
来源：http://dali.pycfn.com/Article/details/gtquarnkpc.html

Py:   os.getcwd()
来源：http://dali.daxiang520.top/Article/details/gtkwgczxji.html

PHP:  getcwd();
来源：http://dali.redwolf501.top/Article/details/gtvzgqtkqz.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gtpqgqwvwf.html

TS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gtkhsncvfx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jlsjyb.cn/Article/details/gtcvunnrle.html

Go:   os.Getwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtkdlbciut.html

Ruby: Dir.pwd
来源：http://dali.cdnleiting.top/Article/details/gtuayssabm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fzhhl.top/Article/details/gtvhgpnxvy.html

[M05] 设置退出码
来源：http://dali.meibo888.top/Article/details/gtrquuybgj.html

Py:   sys.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtcsovrbyz.html

PHP:  exit(1);
来源：http://dali.zhiwuduotai.top/Article/details/gtodbbpboj.html

JS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtxgqfhrur.html

TS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtefexipwu.html

Java: System.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtyfyurfnt.html

Go:   os.Exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtbwimncde.html

Ruby: exit 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtysfredcq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fzhhl.top/Article/details/gthdiunuvc.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gtcgfraztp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gtvotglpeu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.mhx1999.top/Article/details/gtcfyivnas.html

JS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gtjprnfmfw.html

TS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gtbfeidaqu.html

Java: System.err.println("err")
来源：http://dali.shuidangran.top/Article/details/gtswqysnnh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zdqjudy.top/Article/details/gttmmvfjqb.html

Ruby: warn "err"
来源：http://dali.chenzaomai.com/Article/details/gtzdlyagtn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jlsjyb.cn/Article/details/gtqosgcbzp.html

[M07] 判断是否为主入口
来源：http://dali.chenlongwang.top/Article/details/gtcaulbgvh.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgfzy.top/Article/details/gtvoaftxtu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gtutsccqby.html

JS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gtmkvqskhw.html

TS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gtixcmmogg.html

Java: public static void main(String[] args)
来源：http://dali.zhongyouzk.top/Article/details/gtupugiimz.html

Go:   func main()
来源：http://dali.jqgufenzy.top/Article/details/gthrqanvid.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dashuyun.cn/Article/details/gteiprdhmm.html

C#:   static void Main(string[] args)
来源：http://dali.xziqi.cn/Article/details/gtfyvmowcm.html

[M08] 获取系统与运行时信息
来源：http://dali.shzxlz.cn/Article/details/gtvrrhtcdd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gtmycumvse.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guowangkeji.top/Article/details/gtbvzlgnuq.html

JS:   process.platform;  process.version
来源：http://dali.gogol.net.cn/Article/details/gtqhawvryc.html

TS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gtvlwfbwoq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sweek.top/Article/details/gtopallrvd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shangyingyoupin.top/Article/details/gteqxtterh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.9152youxi.cn/Article/details/gtwbxbieis.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shuidangran.top/Article/details/gtxsavqcbe.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtjgjdgmsp.html

N. 数据结构与算法
来源：http://dali.tianlin.xyz/Article/details/gtmgqlrjlv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtzvarleol.html

[N01] 二分查找（有序数组）
来源：http://dali.9152youxi.cn/Article/details/gtpyvvqtya.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtsktajagg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.svipenyu.cn/Article/details/gtxozslvuj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbmqlelt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtzwjeekha.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtnqdabuii.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtfvdbtjhk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yongpay.top/Article/details/gtptzlvalw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtxvouhxsw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sufxvd.cn/Article/details/gtuvtxcmuh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guannengcc.top/Article/details/gttounvkli.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnqzz.top/Article/details/gttpqebzom.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gthhlmngag.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gttqxqlnxs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxuanxn.top/Article/details/gtutgmmcgu.html

Go:   slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gthzqmixfe.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gtxbyglvxu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhengqikj.top/Article/details/gtdryrbgmp.html

[N03] 快速排序（分治示例）
来源：http://dali.hnqzz.top/Article/details/gtqqhjitqw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.haohaochexian.top/Article/details/gthlorhjjg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gtolcteuwt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gtheswgwmf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gtynqjdbwu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gtabazlrgv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pengpengdd.cyou/Article/details/gtagnrhimh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shuidangran.top/Article/details/gttjhyfkhl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tanke756.top/Article/details/gtufmpsafn.html

[N04] 斐波那契数列
来源：http://dali.chenlongwang.top/Article/details/gtttwkriev.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtgwuwoqus.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtwpuqjgzn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gtbndqqnuj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtslyofxbl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gtsobyekpy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dashuyun.cn/Article/details/gtpflukguz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gtrokfjnof.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtnoetipuk.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gtkzkbkgbi.html

Py:   math.gcd(a, b)
来源：http://dali.nwbrower.top/Article/details/gtrhgjabvj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.havefunace.top/Article/details/gtoqjzbqcu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gtdobvwhjq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guowangkeji.top/Article/details/gtgnlknzap.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dianchejie.cn/Article/details/gtorsszlyc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaooujsxp.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmlxykego.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daria6918.cn/Article/details/gtcqlpmbah.html

[N06] 判断回文字符串
来源：http://dali.guannengcc.top/Article/details/gtvkswmgun.html

Py:   s == s[::-1]
来源：http://dali.yj20258.top/Article/details/gtdynxbiau.html

PHP:  $s === strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gtrrxfntuv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtailvoska.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwfvdlur.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgufenzy.top/Article/details/gtdmrmlqpu.html

Go:   // 双指针从两端比较
来源：http://dali.wangshuangyany.cn/Article/details/gtjdgilrcb.html

Ruby: s == s.reverse
来源：http://dali.xuanzx.com/Article/details/gtxwyfpvwi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenjidiqi.icu/Article/details/gtfxoqzyoo.html

[N07] 两数之和（返回下标）
来源：http://dali.tian-w.cn/Article/details/gtpyljpbbv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.0kj1m.cn/Article/details/gtyymmrksz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yonumen.top/Article/details/gtunugelpx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daxiang520.top/Article/details/gtrsyxizij.html

TS:   // 手写 Map<string, number>
来源：http://dali.daxiang520.top/Article/details/gtiuglmyoq.html

Java: // 手写 HashMap
来源：http://dali.nwbrower.top/Article/details/gtgvnsiipi.html

Go:   // 手写 map[int]int
来源：http://dali.bjfxy.top/Article/details/gtopggcymp.html

Ruby: // 手写 Hash
来源：http://dali.yuanzhike.top/Article/details/gtqqpwcmur.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhengqikj.top/Article/details/gtkaddllau.html

[N08] 生成全排列
来源：http://dali.c1oappe.top/Article/details/gtsykpoucp.html


<!-- 参考信息 -->