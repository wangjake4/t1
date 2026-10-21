代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhoulong.xyz/Article/details/gtxmqizypg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yangfankeji.com/Article/details/gtvgcnehue.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hfpthk.cn/Article/details/gtqxvclghz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.redwolf501.top/Article/details/gtckndtmpg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cucudq.cn/Article/details/gtfsyyzaid.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shuidangran.top/Article/details/gtaqdixfws.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sufxvd.cn/Article/details/gtdqryeagd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shzxlz.cn/Article/details/gtucqmzsrb.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtdbawcese.html

K. JSON 与序列化
来源：http://dali.ivvv.top/Article/details/gtabmaxmio.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtilzyzhps.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuinrgeaj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gtrmgepgfi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gtavsrrsae.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtrpwjlfki.html

TS:   JSON.stringify(obj)
来源：http://dali.guowangkeji.top/Article/details/gtbbfpobok.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuetiantiany.cn/Article/details/gtxkieevwo.html

Go:   json.Marshal(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkvslfzj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.andypj.xyz/Article/details/gtbcdrxpqs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuxming.cn/Article/details/gthqcoxfaq.html

[K02] JSON 字符串转对象
来源：http://dali.gotoacloud.top/Article/details/gttxelujyt.html

Py:   json.loads(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtzxfewjtn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jlsjyb.cn/Article/details/gtnpqfsisy.html

JS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtqtymhepw.html

TS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtwruimwcs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gtbpzczzqy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gtjxzsxyah.html

Ruby: JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtdpjypmer.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.snrcjt.cn/Article/details/gtgmpceint.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sxryk.cn/Article/details/gttqoxvpdp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gtocksplof.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gtqpicveri.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtaogdbtmm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gtkfnihqik.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaynkdqth.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sweek.top/Article/details/gtvieizody.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtofuripbw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwhjuqgi.html

[K04] 读取 JSON 文件
来源：http://dali.hywenlv.cn/Article/details/gtbkdiobpv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.quarkkingdee.top/Article/details/gtezmorhtn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhixingplan.top/Article/details/gtwycyeqyl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gtebguccdz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gttvgnaboy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfyuqtrsn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gtgbmdcgyq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yongpay.top/Article/details/gtacfyhqha.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangdashe.top/Article/details/gtcjygvldo.html

[K05] 深拷贝对象
来源：http://dali.haohaochexian.top/Article/details/gtghbvifno.html

Py:   copy.deepcopy(obj)
来源：http://dali.svipenyu.cn/Article/details/gtyvporrup.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shzxlz.cn/Article/details/gtgpaqhseq.html

JS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtcxwrudlw.html

TS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtiwfyswar.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenjidiqi.icu/Article/details/gtudzwugnf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tian-w.cn/Article/details/gtqqwljemn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnzgphfd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jyoumei.cn/Article/details/gttyslsuzq.html

[K06] 解析 URL 查询串
来源：http://dali.zhiwuduotai.top/Article/details/gtlpxllbez.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gthlqledqb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhongyouzk.top/Article/details/gtwqqmahzr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gtcysbbkvg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gtdrcgqmty.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fzhhl.top/Article/details/gtyvypoewx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gthdfpexff.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtxuvdvgcu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtzsivjjrp.html

[K07] 进制转换
来源：http://dali.yj20258.top/Article/details/gtxxuyqksi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtqtomhika.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gtxinftvuw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtadhprjvl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtrqswzglv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtjprudgvy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj202588.top/Article/details/gtcykbjdkx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.svipenyu.cn/Article/details/gtvzfhovte.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtcryaepqb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtezckro.html

Py:   pickle.dumps(obj)
来源：http://dali.cucudq.cn/Article/details/gtrlrnnmfa.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgfzy.top/Article/details/gtqxsgmnji.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gtztolmupz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtwwfupofc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cdnleiting.top/Article/details/gtjmhinkwz.html

Go:   encoding/gob
来源：http://dali.snrcjt.cn/Article/details/gtqdahfcmw.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxinkj.top/Article/details/gthjvedqgq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gtdrrouykl.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtpviyltzp.html

L. 网络请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfmbaosf.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtmdernyum.html

[L01] 发送 GET 请求
来源：http://dali.hnqzz.top/Article/details/gtdrjihkgu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhixingplan.top/Article/details/gtcrykvmcb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbuaqsfoy.html

JS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gtvdfijhnn.html

TS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gtrvjhnrug.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.vqdsnc.cn/Article/details/gtohmijtyv.html

Go:   resp, err := http.Get(url)
来源：http://dali.yueranfly.top/Article/details/gtzqaanild.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.kuanghao11.cn/Article/details/gthgxkqqeg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.birdmap.top/Article/details/gtcrzspqyf.html

[L02] 发送 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gttroirmyx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gtqljtwxoj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.feifeiyinyue.top/Article/details/gtiykqosqk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenzaomai.com/Article/details/gtlzblbecm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gtvpzfonog.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sufxvd.cn/Article/details/gtdtvijpqc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yanxiufei.cn/Article/details/gtdqclufqu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cucudq.cn/Article/details/gtfxzidypq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cdnleiting.top/Article/details/gtjjfycklv.html

[L03] 设置自定义请求头
来源：http://dali.zdqjudy.top/Article/details/gtrroafywm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yangfankeji.com/Article/details/gtaalpcvuk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.vqdsnc.cn/Article/details/gtcnwmndbj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gtgdqvdvyi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gtqglwismy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xinyue.icu/Article/details/gthudnoriy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gtnurysslc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cdnleiting.top/Article/details/gtsrxdoyht.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gtkjzyusvd.html

[L04] 设置超时
来源：http://dali.xziqi.cn/Article/details/gtnhabnirg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhixingplan.top/Article/details/gtnoaswaud.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenzaomai.com/Article/details/gtldohhunf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gtzvwouyad.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gtmnkivsfl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cqqwz.cn/Article/details/gtrkqlqdsv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yueranfly.top/Article/details/gtchmesuxl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gtclrndtci.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jyoumei.cn/Article/details/gtusmwehyn.html

[L05] 上传文件（multipart）
来源：http://dali.xuetiantiany.cn/Article/details/gtwkqdnozr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gttlhimqrr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbaebxnka.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gttgautjha.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gtcvzjrdmi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.bjfxy.top/Article/details/gtajayerls.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hnqzz.top/Article/details/gtitykiiiy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xinyue.icu/Article/details/gtgesqvhdy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ybcxt.top/Article/details/gtgbyaamda.html

[L06] 解析响应为 JSON
来源：http://dali.yueranfly.top/Article/details/gtarxcovni.html

Py:   resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gttgoglnsz.html

PHP:  json_decode($body, true);
来源：http://dali.sxryk.cn/Article/details/gtczoihgrf.html

JS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gtvaldosdq.html

TS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnpowjhe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtrkvavtlg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.c1oappe.top/Article/details/gtkshtxnuv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.feifeiyinyue.top/Article/details/gtizosenkp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigfzy.top/Article/details/gtgdlwxkxi.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gtbfnbcakc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.bjfxy.top/Article/details/gtbmzrmjch.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtwrdxkysz.html

JS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gteeijalaj.html

TS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtmdajvisv.html

Java: resp.statusCode()
来源：http://dali.fzhhl.top/Article/details/gthgrrurkg.html

Go:   resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gtjvmxtfwg.html

Ruby: resp.code.to_i
来源：http://dali.xuetiantiany.cn/Article/details/gtrjqhdhaq.html

C#:   (int)resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gtkokgixni.html

[L08] 并发请求多个地址
来源：http://dali.sxryk.cn/Article/details/gtjmjdoote.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhixingplan.top/Article/details/gtruymxbmc.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnxiangtu.top/Article/details/gtbxpvahie.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtuhqdxyug.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gtjzczccrb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.c1oappe.top/Article/details/gtqtozmlls.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hysaishi.cn/Article/details/gtjvpxbgsi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shzxlz.cn/Article/details/gtjfvllkmr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yonumen.top/Article/details/gtyvyxqpgx.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtsmgwbghj.html

M. 命令行 / 进程 / 环境
来源：http://dali.9152youxi.cn/Article/details/gtndfnivba.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtpiztynit.html

[M01] 读取命令行参数
来源：http://dali.cheryme.top/Article/details/gtonshcdib.html

Py:   sys.argv[1:]
来源：http://dali.mhx1999.top/Article/details/gttkrptxat.html

PHP:  $argv;  $argc;
来源：http://dali.sxryk.cn/Article/details/gtqbduevfj.html

JS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtjoewwhoq.html

TS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gtiznlmmin.html

Java: args 数组（main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gtfcquyitp.html

Go:   os.Args[1:]
来源：http://dali.havefunace.top/Article/details/gtvrzstkio.html

Ruby: ARGV
来源：http://dali.chenzaomai.com/Article/details/gtinxvmynh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gtrieqnkcu.html

[M02] 读取环境变量
来源：http://dali.yonumen.top/Article/details/gtgayocyxa.html

Py:   os.environ.get("HOME")
来源：http://dali.sweek.top/Article/details/gtquofmgel.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gtligviyme.html

JS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gttaguwmtu.html

TS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gtmauaixpg.html

Java: System.getenv("HOME")
来源：http://dali.316326.xyz/Article/details/gtmutbcnvy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtvnasrkwp.html

Ruby: ENV["HOME"]
来源：http://dali.yangfankeji.com/Article/details/gtlrwsgcmg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtcylhwkce.html

[M03] 执行外部命令
来源：http://dali.yanxiufei.cn/Article/details/gtzfrsgawi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ppjwa.cn/Article/details/gtrbpgymsy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxuanxn.top/Article/details/gtasrgxhjb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gtwueqkvlv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gtixsmvxoj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.redwolf501.top/Article/details/gtigczysdq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.bjfxy.top/Article/details/gtzkspbqri.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfvnnunh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shangyingyoupin.top/Article/details/gthmilhwto.html

[M04] 获取当前工作目录
来源：http://dali.zhoulong.xyz/Article/details/gtruniskkh.html

Py:   os.getcwd()
来源：http://dali.c1oappe.top/Article/details/gtrjvaazlm.html

PHP:  getcwd();
来源：http://dali.jiagoushi.top/Article/details/gtleusyvgy.html

JS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gtytpqmhsv.html

TS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtrxpydcij.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gotoacloud.top/Article/details/gtylvabrxc.html

Go:   os.Getwd()
来源：http://dali.yangfankeji.com/Article/details/gtfhpdekca.html

Ruby: Dir.pwd
来源：http://dali.shanyushiyangtech.top/Article/details/gtjschpxer.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hongshengwenyu.top/Article/details/gtqebactnb.html

[M05] 设置退出码
来源：http://dali.chenlongwang.top/Article/details/gtxqmseyto.html

Py:   sys.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gttquwzleo.html

PHP:  exit(1);
来源：http://dali.fengsongda.top/Article/details/gtmunmydax.html

JS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtcfqviebw.html

TS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtmdksrtkp.html

Java: System.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtxuhzxdxs.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtqfxwzxwg.html

Ruby: exit 1
来源：http://dali.snrcjt.cn/Article/details/gtrtphwszw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.quarkkingdee.top/Article/details/gtfmbyvwpi.html

[M06] 向标准错误输出
来源：http://dali.hywenlv.cn/Article/details/gtgjwzgvtz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.havefunace.top/Article/details/gtqqfawhlu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jianghu66.top/Article/details/gtzthvelxi.html

JS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gthviwhzit.html

TS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gtyvtrydcf.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbfcqcpy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.quarkkingdee.top/Article/details/gtowwzdhpy.html

Ruby: warn "err"
来源：http://dali.gaohongyu789.top/Article/details/gtbzbdydmc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shuidangran.top/Article/details/gtlgevagdw.html

[M07] 判断是否为主入口
来源：http://dali.fengsongda.top/Article/details/gtrsaffnzu.html

Py:   if __name__ == "__main__":
来源：http://dali.yanxiufei.cn/Article/details/gtrhxakwtj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gtfajpfaoa.html

JS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gtnhisahjr.html

TS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gtgnwjpkuf.html

Java: public static void main(String[] args)
来源：http://dali.shuidangran.top/Article/details/gtzmbxkvqo.html

Go:   func main()
来源：http://dali.hnqzz.top/Article/details/gtkmptwhbd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgufenzy.top/Article/details/gtmprqmgps.html

C#:   static void Main(string[] args)
来源：http://dali.andypj.xyz/Article/details/gtbbballum.html

[M08] 获取系统与运行时信息
来源：http://dali.ybcxt.top/Article/details/gtotsrfqge.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj202588.top/Article/details/gtnjjkqimm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xylfe.cn/Article/details/gtidttqlii.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gtkyutibpv.html

TS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gtfxgzvsbg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnqzz.top/Article/details/gtbppmsbgt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shzxlz.cn/Article/details/gtelqimcin.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yangfankeji.com/Article/details/gtevilmbje.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fzhhl.top/Article/details/gtveubrbfo.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtxyepeqvl.html

N. 数据结构与算法
来源：http://dali.aibaodan.cn/Article/details/gtdiyyftrs.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtxqwezcyv.html

[N01] 二分查找（有序数组）
来源：http://dali.ydzc1.top/Article/details/gtxrjrytch.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtayncbhra.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxtzwptd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gthxhghloi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtyopggmfy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtcahrjznv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtxhhalabv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jqgufenzy.top/Article/details/gtuaoxtiph.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtxqivjctz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.kuanghao11.cn/Article/details/gtxgiatgoq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gtbsmzafar.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sufxvd.cn/Article/details/gtouafiebq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gtwrpjpnss.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gthxgkucot.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hysaishi.cn/Article/details/gtkhgutfoa.html

Go:   slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gtpdoaftgw.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gtmiptrkyi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.vqdsnc.cn/Article/details/gttamzxefc.html

[N03] 快速排序（分治示例）
来源：http://dali.jlsjyb.cn/Article/details/gtexeeltbl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cdnleiting.top/Article/details/gthtqeabao.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yonumen.top/Article/details/gtqiqtbher.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cashguo.top/Article/details/gtwfxldxbn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gtevxkroye.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hywenlv.cn/Article/details/gtkcoaklxh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ybcxt.top/Article/details/gturcjimun.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.c1oappe.top/Article/details/gtjehudbsg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhoulong.xyz/Article/details/gtltgtrblm.html

[N04] 斐波那契数列
来源：http://dali.nanxinkj.top/Article/details/gtmtwzcmut.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gtdtvdjahy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtuojvftwx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtwszulgiy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gtrbcwjjlg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gtrbmvlihp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenjidiqi.icu/Article/details/gtfsodgpmo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gtwbfksbun.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtfkyjzfuw.html

[N05] 最大公约数
来源：http://dali.0kj1m.cn/Article/details/gtzmlckprb.html

Py:   math.gcd(a, b)
来源：http://dali.chenzaomai.com/Article/details/gtpznxxiwh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjacmsjry.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jlsjyb.cn/Article/details/gtddevgbwy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtluumikxi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnqzz.top/Article/details/gtqkasfdrt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258.top/Article/details/gtimoobcdl.html

Ruby: a.gcd(b)
来源：http://dali.jiagoushi.top/Article/details/gtoqzvishk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cdnleiting.top/Article/details/gtxmbagiii.html

[N06] 判断回文字符串
来源：http://dali.fengsongda.top/Article/details/gtebyqzbus.html

Py:   s == s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gtwqeldhhv.html

PHP:  $s === strrev($s);
来源：http://dali.nwbrower.top/Article/details/gtqvbokzcb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtgafqkqxe.html

TS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtnwjcbxey.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hysaishi.cn/Article/details/gtpcxcodjz.html

Go:   // 双指针从两端比较
来源：http://dali.dashuyun.cn/Article/details/gtjsrltdpo.html

Ruby: s == s.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtgdiywvhw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gtdlbhiflz.html

[N07] 两数之和（返回下标）
来源：http://dali.ivvv.top/Article/details/gttibdjcvb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.svipenyu.cn/Article/details/gtdsoabzxt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenzaomai.com/Article/details/gthzbcjvag.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.haohaochexian.top/Article/details/gtqmwvlurr.html

TS:   // 手写 Map<string, number>
来源：http://dali.jlsjyb.cn/Article/details/gtwunbepui.html

Java: // 手写 HashMap
来源：http://dali.zhoulong.xyz/Article/details/gtdkiqnjga.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrsemieco.html

Ruby: // 手写 Hash
来源：http://dali.haohaochexian.top/Article/details/gtzprnacdd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cashguo.top/Article/details/gtdtbquvwl.html

[N08] 生成全排列
来源：http://dali.xuanzx.com/Article/details/gtbaqnhrwf.html


<!-- 参考信息 -->