代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yanxiufei.cn/Article/details/gtvgxfottp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyuuoceox.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tian-w.cn/Article/details/gtbkaekmbd.html

[J10] 取今天 / 本月第一天
来源：http://dali.cheryme.top/Article/details/gtuvrxctwd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zycfv.cn/Article/details/gthpthueyo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gtltgbvrsa.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtuxenlwvc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258.top/Article/details/gtdskbxyin.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cashguo.top/Article/details/gtqopbidve.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gaohongyu789.top/Article/details/gtucznsmdp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ehwqpu.com/Article/details/gtmcvavzjb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgfzy.top/Article/details/gtwkbevjjw.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtjwjjmcde.html

K. JSON 与序列化
来源：http://dali.shuidangran.top/Article/details/gtujoqambe.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtpywfystk.html

[K01] 对象转 JSON 字符串
来源：http://dali.shuidangran.top/Article/details/gthdtusokb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gtetmbolzs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gthuglwapg.html

JS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gtrutnygek.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtegvapnoz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hongshengwenyu.top/Article/details/gtwoqwbwsy.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gtffedouxv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngxcealx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yueranfly.top/Article/details/gtdgrbzbaf.html

[K02] JSON 字符串转对象
来源：http://dali.chenlongwang.top/Article/details/gtjossnhpm.html

Py:   json.loads(s)
来源：http://dali.chenlongwang.top/Article/details/gtpudbmnsj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenjidiqi.icu/Article/details/gttzgafzra.html

JS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gtbpisocls.html

TS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtjdtfnnor.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtkelqrvfo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gtfodetbur.html

Ruby: JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtrkyalxre.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhengqikj.top/Article/details/gtstfgtqce.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daria6918.cn/Article/details/gtxmyeqhmk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.kuanghao11.cn/Article/details/gtfwzybade.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gtxlkjkxip.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gtsthyjpqc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gtaapxisbq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ppjwa.cn/Article/details/gtwmahonbf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sweek.top/Article/details/gttwprncbq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gtvvkcsxxv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ydzc1.top/Article/details/gtywruwlhn.html

[K04] 读取 JSON 文件
来源：http://dali.vqdsnc.cn/Article/details/gtvuvilrkm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.smart0.xyz/Article/details/gtayhxsdcr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiubeanwu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gtmmfinwnv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gtuuawiovd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqeiedtp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gthzegepbs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gthbowfjjg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.mhx1999.top/Article/details/gtvkwfrvtr.html

[K05] 深拷贝对象
来源：http://dali.yangfankeji.com/Article/details/gtnpivcjmy.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtifvqvscv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.0kj1m.cn/Article/details/gtblewqocj.html

JS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gtexnrifli.html

TS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtyorqoqxy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhongyouzk.top/Article/details/gtrmvqtvmp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ivvv.top/Article/details/gtjxotrzpw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hywenlv.cn/Article/details/gtgqjselvw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hammf.cn/Article/details/gtdkjplork.html

[K06] 解析 URL 查询串
来源：http://dali.cqqwz.cn/Article/details/gttvkqdovv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pycfn.com/Article/details/gtcjsqrgks.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhiwuduotai.top/Article/details/gtmviequbb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gtceqnhgup.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gthjhjcmpo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aibaodan.cn/Article/details/gtqcvnmwen.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtycvzrrjr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcetieit.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtpflxokwh.html

[K07] 进制转换
来源：http://dali.vqdsnc.cn/Article/details/gthorgscru.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtvjilqjnq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhengqikj.top/Article/details/gtqfrfyyfd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtknfmevou.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtxijygqmz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtrfpwdiyu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttterraqr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenzaomai.com/Article/details/gtekxhrayj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtfegfatgf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgfzy.top/Article/details/gtjbfnvmfp.html

Py:   pickle.dumps(obj)
来源：http://dali.wangdashe.top/Article/details/gtupvkhsyh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ehwqpu.com/Article/details/gtgynwbruu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gtkmgcdpvd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gthxlbclin.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cashguo.top/Article/details/gtqvrdpopa.html

Go:   encoding/gob
来源：http://dali.hfpthk.cn/Article/details/gtlyrbaghs.html

Ruby: Marshal.dump(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtdnrtvzfs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gtkqwbygkj.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtjgvymioh.html

L. 网络请求
来源：http://dali.yueranfly.top/Article/details/gtvqgzhrhg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtgbdxdmmf.html

[L01] 发送 GET 请求
来源：http://dali.ppjwa.cn/Article/details/gtkjcntwbz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.vqdsnc.cn/Article/details/gtfgzmplty.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.quarkkingdee.top/Article/details/gtbkzlubvt.html

JS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gtsfgctolt.html

TS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gtnqieyhkb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhiwuduotai.top/Article/details/gtozjdmzga.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhixingplan.top/Article/details/gtbfjvxnco.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guannengcc.top/Article/details/gtovqycdjv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhixingplan.top/Article/details/gtohtdqmjo.html

[L02] 发送 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gtofkebfqf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtwsnauquf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxinkj.top/Article/details/gtihnfrdyy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqaaxosau.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvpytmtn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.kuanghao11.cn/Article/details/gtnfeddxyp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gaohongyu789.top/Article/details/gtthbxvrbu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigufen.top/Article/details/gtllpxaonp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtibndgwgr.html

[L03] 设置自定义请求头
来源：http://dali.jiagoushi.top/Article/details/gtpycfqcao.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtesqutpcb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhixingplan.top/Article/details/gtdkxgrodk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gtmxmufksi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gtjkncyxar.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sxryk.cn/Article/details/gtnlxeuwxq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gtffyreobx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zycfv.cn/Article/details/gthycnkzfl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gtxkeykfig.html

[L04] 设置超时
来源：http://dali.chenzaomai.com/Article/details/gtwxkljemf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tanke756.top/Article/details/gtueuuctni.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yueranfly.top/Article/details/gtjopqrktx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gtmtbpmwoh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tanke756.top/Article/details/gtgvgwkdim.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jyoumei.cn/Article/details/gtcaxumcdz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.vqdsnc.cn/Article/details/gtvxjntnhw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hfpthk.cn/Article/details/gtvmnlvptk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yangfankeji.com/Article/details/gtkgbteiuv.html

[L05] 上传文件（multipart）
来源：http://dali.andypj.xyz/Article/details/gtoxyemaiy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnqzz.top/Article/details/gtdszotwbr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigfzy.top/Article/details/gtlxlovahu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gtjzldvrzq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gtcxvkisps.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sxryk.cn/Article/details/gtrkqzzfxj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xziqi.cn/Article/details/gtwlwadozi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ivvv.top/Article/details/gtemavfmzy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xziqi.cn/Article/details/gtdzyxpndg.html

[L06] 解析响应为 JSON
来源：http://dali.daria6918.cn/Article/details/gtqqjutcpm.html

Py:   resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtaxuhljzo.html

PHP:  json_decode($body, true);
来源：http://dali.jyoumei.cn/Article/details/gtfmzizdzs.html

JS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtesaacwzu.html

TS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gthjudphro.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtkcgunrgc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgfzy.top/Article/details/gtggpjkwbq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tanke756.top/Article/details/gtnnqwpffx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvlmockw.html

[L07] 处理 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gtcjsrqitc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigfzy.top/Article/details/gtrzoqaguu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuxming.cn/Article/details/gtcetoarhh.html

JS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gtdgsfomzv.html

TS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gtudymhujr.html

Java: resp.statusCode()
来源：http://dali.nanxinkj.top/Article/details/gtislnjcrf.html

Go:   resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gttiilnsex.html

Ruby: resp.code.to_i
来源：http://dali.gogol.net.cn/Article/details/gtzuzjbylv.html

C#:   (int)resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gtsxlfeyvk.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjhonzzo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxuanxn.top/Article/details/gtqfyllxbb.html

PHP:  curl_multi_init() 系列
来源：http://dali.cqqwz.cn/Article/details/gtmisfrrxn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gtacbwmcpm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gtzkspoqhq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tanke756.top/Article/details/gtdmfvwagp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangshuangyany.cn/Article/details/gtnklosofp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhixingplan.top/Article/details/gtuddijoui.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ehwqpu.com/Article/details/gtbzkabwvl.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtmfsfhppc.html

M. 命令行 / 进程 / 环境
来源：http://dali.gaohongyu789.top/Article/details/gtbuvdwrox.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtjtqxlobz.html

[M01] 读取命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgdzjcif.html

Py:   sys.argv[1:]
来源：http://dali.fzhhl.top/Article/details/gtutirkgxh.html

PHP:  $argv;  $argc;
来源：http://dali.0kj1m.cn/Article/details/gtqwuarbfe.html

JS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gthtiifkmm.html

TS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gtgzlsqhkh.html

Java: args 数组（main 方法参数）
来源：http://dali.yongpay.top/Article/details/gtevaftlex.html

Go:   os.Args[1:]
来源：http://dali.cqqwz.cn/Article/details/gtwlwsiwqh.html

Ruby: ARGV
来源：http://dali.chenzaomai.com/Article/details/gtmbglywmt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtbbapvzes.html

[M02] 读取环境变量
来源：http://dali.daria6918.cn/Article/details/gtxblqhnav.html

Py:   os.environ.get("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtsjbdefgc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gtctqvrwtd.html

JS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gtfbwqxbgm.html

TS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gtszffujrx.html

Java: System.getenv("HOME")
来源：http://dali.yueranfly.top/Article/details/gtuyplpmps.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtlxrqrcfb.html

Ruby: ENV["HOME"]
来源：http://dali.gotoacloud.top/Article/details/gtagromznu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtswcpdelu.html

[M03] 执行外部命令
来源：http://dali.cheryme.top/Article/details/gtdmhjlzox.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.meibo888.top/Article/details/gtdzspuplk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinghuilouyu.cn/Article/details/gthdwazzji.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.c1oappe.top/Article/details/gtbqthrugz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gtgiblbcaw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yangfankeji.com/Article/details/gtyhdzkxaq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.meibo888.top/Article/details/gteznjtjps.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hysaishi.cn/Article/details/gtuvztgujs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zdqjudy.top/Article/details/gtqyhppjwt.html

[M04] 获取当前工作目录
来源：http://dali.xuanzx.com/Article/details/gtzwjnwgih.html

Py:   os.getcwd()
来源：http://dali.nanxinkj.top/Article/details/gthfhcezqn.html

PHP:  getcwd();
来源：http://dali.ydzc1.top/Article/details/gtoufhthiq.html

JS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gtdbervpxv.html

TS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gthirkhhxa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.0kj1m.cn/Article/details/gtszlvuakd.html

Go:   os.Getwd()
来源：http://dali.nanxuanxn.top/Article/details/gtrbluxblb.html

Ruby: Dir.pwd
来源：http://dali.nwbrower.top/Article/details/gtlsdvieph.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tian-w.cn/Article/details/gttbbzlewd.html

[M05] 设置退出码
来源：http://dali.yj20258888.top/Article/details/gtpqispjfy.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkuifaxns.html

PHP:  exit(1);
来源：http://dali.shzxlz.cn/Article/details/gtvzdydaoo.html

JS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtbvffckrt.html

TS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtspxzkxzc.html

Java: System.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtjzvhoxei.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtdlbnkqmx.html

Ruby: exit 1
来源：http://dali.hongshengwenyu.top/Article/details/gtgyzbouiz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbeaelai.html

[M06] 向标准错误输出
来源：http://dali.zhixingplan.top/Article/details/gtliwrxups.html

Py:   print("err", file=sys.stderr)
来源：http://dali.birdmap.top/Article/details/gtpzrxefnr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xylfe.cn/Article/details/gtukaomyxk.html

JS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gtfthzlhjb.html

TS:   console.error("err")
来源：http://dali.yangfankeji.com/Article/details/gtmpxsxnjj.html

Java: System.err.println("err")
来源：http://dali.sxryk.cn/Article/details/gtzxeoutpz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sysykeji.top/Article/details/gtxdmmixke.html

Ruby: warn "err"
来源：http://dali.daria6918.cn/Article/details/gtajozmxnx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigfzy.top/Article/details/gtfvcqsgcy.html

[M07] 判断是否为主入口
来源：http://dali.aibaodan.cn/Article/details/gtcjsabrkv.html

Py:   if __name__ == "__main__":
来源：http://dali.zhiwuduotai.top/Article/details/gtkziwxkcc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.mhx1999.top/Article/details/gtkljobach.html

JS:   require.main === module
来源：http://dali.cqqwz.cn/Article/details/gtzpyclsmw.html

TS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gtstexuyph.html

Java: public static void main(String[] args)
来源：http://dali.xinyue.icu/Article/details/gtedramlvg.html

Go:   func main()
来源：http://dali.yuanzhike.top/Article/details/gtcqogoufe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.kuanghao11.cn/Article/details/gtbgzlgkjg.html

C#:   static void Main(string[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gtkventjyk.html

[M08] 获取系统与运行时信息
来源：http://dali.tanke756.top/Article/details/gtrjktuodv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmccoemew.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ivvv.top/Article/details/gtqonxmmui.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gtkwiidpwb.html

TS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gtdfrkkplh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fzhhl.top/Article/details/gtrnsyvjta.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.kuanghao11.cn/Article/details/gtktyckhlx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.0kj1m.cn/Article/details/gtwuzryqpu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yonumen.top/Article/details/gtliwihroc.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtofyeefda.html

N. 数据结构与算法
来源：http://dali.sysykeji.top/Article/details/gtqipoiljr.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtwmtgck.html

[N01] 二分查找（有序数组）
来源：http://dali.snrcjt.cn/Article/details/gtslcxwdkl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtnalwvcqh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gtoghnspxd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gthfikleyw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtnibssiep.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtaqbqdidp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgnckbkt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgcirkth.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtidfqphtj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.iojbl.cn/Article/details/gtwzmjvmaj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonwsksky.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangdashe.top/Article/details/gtufomvynx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gtafapgtjl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gtlcfjhurc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhixingplan.top/Article/details/gtcenrvfxt.html

Go:   slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gtuaacyzeo.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gtkkxavruk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nwbrower.top/Article/details/gtylvpocmd.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangtech.top/Article/details/gtygotixxp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gogol.net.cn/Article/details/gtnmegqgnz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhiwuduotai.top/Article/details/gtsuxjgouv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtrnhnnbpr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gtvlbosxoz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hammf.cn/Article/details/gtzkvugewf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.haohaochexian.top/Article/details/gtlwljjeca.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yonumen.top/Article/details/gtpaxnihwo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guannengcc.top/Article/details/gthfurqcoa.html

[N04] 斐波那契数列
来源：http://dali.fengsongda.top/Article/details/gtqbouffpq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gtbhxiewek.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gtfxwdsqdj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtvlslwybe.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtbnjddbrb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gtuojrkxhd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgufenzy.top/Article/details/gtwlyddqhg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.316326.xyz/Article/details/gtcofesonl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gtboftxrep.html

[N05] 最大公约数
来源：http://dali.xinyue.icu/Article/details/gthlhsrtum.html

Py:   math.gcd(a, b)
来源：http://dali.sysykeji.top/Article/details/gtedefssxw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hammf.cn/Article/details/gtkzsclnrt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtkhmulejq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gtzllaadlb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yvedp.cn/Article/details/gtjzladtbh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guowangkeji.top/Article/details/gtaesncwgj.html

Ruby: a.gcd(b)
来源：http://dali.jianghu66.top/Article/details/gtetszdeyv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yangfankeji.com/Article/details/gtqxbhlmzs.html

[N06] 判断回文字符串
来源：http://dali.ehwqpu.com/Article/details/gtwobiygnc.html

Py:   s == s[::-1]
来源：http://dali.bjfxy.top/Article/details/gtydreyspz.html

PHP:  $s === strrev($s);
来源：http://dali.sweek.top/Article/details/gtlvbpeohu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtpadzdoxx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtnxyrwnsl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cucudq.cn/Article/details/gtygnzmlds.html

Go:   // 双指针从两端比较
来源：http://dali.zhengqikj.top/Article/details/gtffudnbsg.html

Ruby: s == s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtdzevbbdo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenlongwang.top/Article/details/gtynrctxuk.html

[N07] 两数之和（返回下标）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdldxxhbi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shzxlz.cn/Article/details/gtscxymdib.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tianlin.xyz/Article/details/gtocqlknjp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dianchejie.cn/Article/details/gtjfhiksem.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinqigfzy.top/Article/details/gtsnldpent.html

Java: // 手写 HashMap
来源：http://dali.xylfe.cn/Article/details/gtehrhzefx.html


<!-- 参考信息 -->