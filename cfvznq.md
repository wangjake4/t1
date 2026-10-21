代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnqzz.top/Article/details/gtsmfnkjot.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gtcxmdadrb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gtszvmrssa.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbznerqus.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ybcxt.top/Article/details/gtiflixwfs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.feifeiyinyue.top/Article/details/gtjaczonql.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwoszedh.html

[J10] 取今天 / 本月第一天
来源：http://dali.aizwys.cn/Article/details/gtnlwhryfl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yuanzhike.top/Article/details/gtwuzdezqq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ehwqpu.com/Article/details/gtpajxggcl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zycfv.cn/Article/details/gtehbhwamd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guannengcc.top/Article/details/gtffuhkedb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yonumen.top/Article/details/gtmxgruezu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hongshengwenyu.top/Article/details/gtrdaoaoes.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.svipenyu.cn/Article/details/gttagffmcu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aizwys.cn/Article/details/gtgsgvlchw.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtskyfgzjg.html

K. JSON 与序列化
来源：http://dali.yj202588.top/Article/details/gtnstobxvq.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtjudiyzhy.html

[K01] 对象转 JSON 字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtbhlsgqpe.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gtqcskgdtx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gttqakfbjz.html

JS:   JSON.stringify(obj)
来源：http://dali.quarkkingdee.top/Article/details/gttvqyrvbw.html

TS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtntwizngs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zdqjudy.top/Article/details/gtxbgyjuvi.html

Go:   json.Marshal(obj)
来源：http://dali.xziqi.cn/Article/details/gtrqgvzxjh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gotoacloud.top/Article/details/gteicmcmkf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xziqi.cn/Article/details/gtxnhuihcc.html

[K02] JSON 字符串转对象
来源：http://dali.tanke756.top/Article/details/gthubzbcfn.html

Py:   json.loads(s)
来源：http://dali.daria6918.cn/Article/details/gtkirwkcks.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.snrcjt.cn/Article/details/gtlasxyghc.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtueocuxhr.html

TS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtoemmqhoo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtbvfvykuf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxncuvnbq.html

Ruby: JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtfmibrkac.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtotbggfpm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yongpay.top/Article/details/gtturfuinc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zdqjudy.top/Article/details/gtnkbailli.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gtzhkpqkqm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gthibepogq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gthjcukhzb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtstaadfgq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tianlin.xyz/Article/details/gtfehvtolr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ppjwa.cn/Article/details/gtjguwrczl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.fzhhl.top/Article/details/gtbfjfrsll.html

[K04] 读取 JSON 文件
来源：http://dali.feifeiyinyue.top/Article/details/gtasmbquux.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxuanxn.top/Article/details/gtqlibypga.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yangfankeji.com/Article/details/gtgnhdftiv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gtejbvehtv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gtlyvrjpfd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtcoohlyjj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gtgchvwyru.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gtjntvgcuu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gttysvrmuz.html

[K05] 深拷贝对象
来源：http://dali.zhengqikj.top/Article/details/gtasmohusk.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtmhvzesca.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guowangkeji.top/Article/details/gtmrnisgdv.html

JS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gthmdsxvwp.html

TS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gttwvpafib.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.havefunace.top/Article/details/gtgekaoczl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yongpay.top/Article/details/gtqokuchui.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gzhubu.top/Article/details/gtspxorrxm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgufenzy.top/Article/details/gtfcgnmczg.html

[K06] 解析 URL 查询串
来源：http://dali.hnxiangtu.top/Article/details/gtkblqwmgk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gthrpoylma.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aizwys.cn/Article/details/gtbfjdcore.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aizwys.cn/Article/details/gthbuoggmk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gttoxnzvhd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnqzz.top/Article/details/gtukmtyaob.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtqxpcujlm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtcpdxmqnn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtzzjniqjq.html

[K07] 进制转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljybwcuc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtafkdydnu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yonumen.top/Article/details/gthufdptzr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtnmgvwjqu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtdsuucdam.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtlgrttkms.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yonumen.top/Article/details/gtsxrjqnpg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdyeimmph.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtasnkcqon.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhongyouzk.top/Article/details/gtjpcggapa.html

Py:   pickle.dumps(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtsiwlnoxb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cdnleiting.top/Article/details/gtsldcphsx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gtuelqzrdr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtibwssush.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zycfv.cn/Article/details/gtrmcgmjdb.html

Go:   encoding/gob
来源：http://dali.ehwqpu.com/Article/details/gtlegudlpo.html

Ruby: Marshal.dump(obj)
来源：http://dali.sweek.top/Article/details/gtsvdpwyid.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtztrwajab.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gttfjdxsuq.html

L. 网络请求
来源：http://dali.tianlin.xyz/Article/details/gtdgqplxqh.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtfgtblbly.html

[L01] 发送 GET 请求
来源：http://dali.jiagoushi.top/Article/details/gtodnrwhaa.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aizwys.cn/Article/details/gtacvkidzr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jyoumei.cn/Article/details/gtzeueursf.html

JS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gtkmszprid.html

TS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gtofnrsjqf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtkdxdpp.html

Go:   resp, err := http.Get(url)
来源：http://dali.daxiang520.top/Article/details/gtmhtjrtfo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.smart0.xyz/Article/details/gtkcqmgayr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guannengcc.top/Article/details/gthkcgqyea.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gtotgvyeik.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtwoufeiaj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.havefunace.top/Article/details/gtgzdazsuf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hammf.cn/Article/details/gtfpxfddja.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gtuzwuwmxo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tanke756.top/Article/details/gtrdtjkyuc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.meibo888.top/Article/details/gtlhharcjg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shuidangran.top/Article/details/gtxdyppvxg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aizwys.cn/Article/details/gtkmrnsgko.html

[L03] 设置自定义请求头
来源：http://dali.ydzc1.top/Article/details/gtllcqvdxz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnqzz.top/Article/details/gtlblzzmnx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhoulong.xyz/Article/details/gtekslhgwf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gtgvrzjhae.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtvtztvmab.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jlsjyb.cn/Article/details/gtlkvluxkr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuatsxjvd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guannengcc.top/Article/details/gtcxvyreyn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gtztcjmrlp.html

[L04] 设置超时
来源：http://dali.sysykeji.top/Article/details/gtmczsvsmu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gogol.net.cn/Article/details/gtfiwuvqab.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cashguo.top/Article/details/gtoyoixqez.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gtyvuxshfn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gtotxahaok.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnqzz.top/Article/details/gtxujusixj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ybcxt.top/Article/details/gtcufktecx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pycfn.com/Article/details/gtnzzmqdbs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangdashe.top/Article/details/gtbxlbtbcu.html

[L05] 上传文件（multipart）
来源：http://dali.mhx1999.top/Article/details/gthtjsrlhl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258888.top/Article/details/gtzylyioas.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hysaishi.cn/Article/details/gteuleefra.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gtwvcevvca.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gtsthrbwpm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hammf.cn/Article/details/gtsmybgvct.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ydzc1.top/Article/details/gttorslgmg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhoulong.xyz/Article/details/gttexcqrxc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.mhx1999.top/Article/details/gtlrkpzstu.html

[L06] 解析响应为 JSON
来源：http://dali.guowangkeji.top/Article/details/gtrospddqd.html

Py:   resp.json()
来源：http://dali.316326.xyz/Article/details/gtnrygzfcd.html

PHP:  json_decode($body, true);
来源：http://dali.tianlin.xyz/Article/details/gtbzscfbwb.html

JS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtyxqdqzug.html

TS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gtmpniabka.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtghttqwgr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhoulong.xyz/Article/details/gtsudxkopa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hywenlv.cn/Article/details/gtkxdzvnzc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.iojbl.cn/Article/details/gttsbxnhpl.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gtwdqwxozz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxinkj.top/Article/details/gttuovelqb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtdkjoddof.html

JS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gtqfmtbduz.html

TS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahfldhzr.html

Java: resp.statusCode()
来源：http://dali.xuanzx.com/Article/details/gtptmmrujm.html

Go:   resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gtiungjtny.html

Ruby: resp.code.to_i
来源：http://dali.tanke756.top/Article/details/gtgpfyhghd.html

C#:   (int)resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gtzhnuqejh.html

[L08] 并发请求多个地址
来源：http://dali.shuidangran.top/Article/details/gtioqcsgef.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hywenlv.cn/Article/details/gtjsfgiudu.html

PHP:  curl_multi_init() 系列
来源：http://dali.pycfn.com/Article/details/gtlejslixr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gteywztell.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtitgximvd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jianghu66.top/Article/details/gtapndgroz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yongpay.top/Article/details/gtjepycybl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gtfywcceoy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jiagoushi.top/Article/details/gtprabkuet.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtqsdzigoq.html

M. 命令行 / 进程 / 环境
来源：http://dali.cashguo.top/Article/details/gtrikxpaeo.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtrqwuhjjw.html

[M01] 读取命令行参数
来源：http://dali.yueranfly.top/Article/details/gtokmpliax.html

Py:   sys.argv[1:]
来源：http://dali.cucudq.cn/Article/details/gtrgbzwuvm.html

PHP:  $argv;  $argc;
来源：http://dali.ehwqpu.com/Article/details/gtkudvvyek.html

JS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gtbbicuqie.html

TS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gttmljhfjp.html

Java: args 数组（main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gtyxfmlqdg.html

Go:   os.Args[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gteolphzgx.html

Ruby: ARGV
来源：http://dali.hammf.cn/Article/details/gtiumdstmf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gtkxrhtqyb.html

[M02] 读取环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gthjrzmddq.html

Py:   os.environ.get("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtpsuzckwt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gthlbxhbss.html

JS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gthyoavrxb.html

TS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtijsmpfod.html

Java: System.getenv("HOME")
来源：http://dali.daxiang520.top/Article/details/gthjxjmkfz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtltybgdmp.html

Ruby: ENV["HOME"]
来源：http://dali.havefunace.top/Article/details/gtyzvkliep.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtovblqobk.html

[M03] 执行外部命令
来源：http://dali.aibaodan.cn/Article/details/gtmmexsrct.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cucudq.cn/Article/details/gtivjueavx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tianlin.xyz/Article/details/gtgqowklec.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtexieyygf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtflbtdtos.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxuanxn.top/Article/details/gtzgetbqif.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tianlin.xyz/Article/details/gteubfgckm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhixingplan.top/Article/details/gtqmgqsbwo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.havefunace.top/Article/details/gtutwgqdie.html

[M04] 获取当前工作目录
来源：http://dali.zhixingplan.top/Article/details/gtgxvehiil.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gtjncjdjtb.html

PHP:  getcwd();
来源：http://dali.chenlongwang.top/Article/details/gtpcbcgtyo.html

JS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtunjpzyrf.html

TS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gttttzwqio.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guannengcc.top/Article/details/gtugwzfvfy.html

Go:   os.Getwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtyrhotgft.html

Ruby: Dir.pwd
来源：http://dali.hfpthk.cn/Article/details/gtlylnwusf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yueranfly.top/Article/details/gtyvrzidzr.html

[M05] 设置退出码
来源：http://dali.redwolf501.top/Article/details/gtewudlqau.html

Py:   sys.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtbufsnoug.html

PHP:  exit(1);
来源：http://dali.yj20258.top/Article/details/gtdyoftcfo.html

JS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdgkvytn.html

TS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtnsxvospi.html

Java: System.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtwcfszegr.html

Go:   os.Exit(1)
来源：http://dali.wangdashe.top/Article/details/gtbhephiyd.html

Ruby: exit 1
来源：http://dali.nanxuanxn.top/Article/details/gtghgfiwbq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.0kj1m.cn/Article/details/gtfwkhuskv.html

[M06] 向标准错误输出
来源：http://dali.zhiwuduotai.top/Article/details/gtdnfyyrqo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tanke756.top/Article/details/gtkkplihyd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ybcxt.top/Article/details/gtrsavgjhj.html

JS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gtkmdomdxj.html

TS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtidudxbia.html

Java: System.err.println("err")
来源：http://dali.zhongyouzk.top/Article/details/gtxyldivcp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xinyue.icu/Article/details/gtlpbwzubu.html

Ruby: warn "err"
来源：http://dali.nanxuanxn.top/Article/details/gtdwyyfnif.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtwtsywlmc.html

[M07] 判断是否为主入口
来源：http://dali.hfpthk.cn/Article/details/gtjqcsxhsa.html

Py:   if __name__ == "__main__":
来源：http://dali.smart0.xyz/Article/details/gtjvmfbzvn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenlongwang.top/Article/details/gteogcqsue.html

JS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gtoppaascn.html

TS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gtfedmixsz.html

Java: public static void main(String[] args)
来源：http://dali.hnqzz.top/Article/details/gtftexahch.html

Go:   func main()
来源：http://dali.iojbl.cn/Article/details/gtrcwjvmhb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258888.top/Article/details/gtprkiyuox.html

C#:   static void Main(string[] args)
来源：http://dali.shuidangran.top/Article/details/gtrpwffshv.html

[M08] 获取系统与运行时信息
来源：http://dali.mhx1999.top/Article/details/gtcwuizefa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sweek.top/Article/details/gtatqkarez.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.havefunace.top/Article/details/gtfximyalj.html

JS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gtkhsikbik.html

TS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtycaumnds.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sufxvd.cn/Article/details/gtyuuyutgj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nwbrower.top/Article/details/gtdwujtyka.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xylfe.cn/Article/details/gtqlvmebyt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.9152youxi.cn/Article/details/gtqlhaymcr.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtnwvvlbrc.html

N. 数据结构与算法
来源：http://dali.shzxlz.cn/Article/details/gtmldqwgfc.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtdllmnbdz.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258.top/Article/details/gtxqgbzhee.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtrytcsoxj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sweek.top/Article/details/gthtcpicom.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gtijetqaqu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gtmklbihev.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtmmfakuli.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtbowysibu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yvedp.cn/Article/details/gtqawaksns.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqpkevsj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ivvv.top/Article/details/gtmffuhfzi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtsijoulth.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtbbfnrsng.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gtnsbbihft.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtqfsywauw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hywenlv.cn/Article/details/gtjqviqhjr.html

Go:   slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtkjddftib.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gtxmgsaaya.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cheryme.top/Article/details/gtuymymefw.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigufen.top/Article/details/gtsduuquej.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenzaomai.com/Article/details/gttswwyibx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jianghu66.top/Article/details/gtbviybexc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gtyuauvsba.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gtkzgnvpqs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbsyeodl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhiwuduotai.top/Article/details/gtxwjuglrx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yueranfly.top/Article/details/gtidwnljfs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yanxiufei.cn/Article/details/gtzntryljz.html

[N04] 斐波那契数列
来源：http://dali.wangdashe.top/Article/details/gtfviemuhc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cucudq.cn/Article/details/gtsrnidpuv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.redwolf501.top/Article/details/gtapeeppfy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gtsgxevspm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtqcrbbfaj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fzhhl.top/Article/details/gttljmyzsf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.9152youxi.cn/Article/details/gtfsuehwit.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtipxcaooa.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkyorkal.html

[N05] 最大公约数
来源：http://dali.sysykeji.top/Article/details/gtpidllexo.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtasjnakxp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fengsongda.top/Article/details/gtolvipdvc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gtpvshjmbh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fzhhl.top/Article/details/gtjtyowcti.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gogol.net.cn/Article/details/gtnmpwiwie.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhengqikj.top/Article/details/gtgszasqow.html

Ruby: a.gcd(b)
来源：http://dali.cashguo.top/Article/details/gtojfxezoz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xinyue.icu/Article/details/gtswezezxb.html

[N06] 判断回文字符串
来源：http://dali.yangfankeji.com/Article/details/gtrimnjgyf.html

Py:   s == s[::-1]
来源：http://dali.cashguo.top/Article/details/gttdntqtel.html

PHP:  $s === strrev($s);
来源：http://dali.yuxming.cn/Article/details/gtmpeuiqlz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtnapevkgm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gtlfdgkfkw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuetiantiany.cn/Article/details/gtahsjpjsd.html

Go:   // 双指针从两端比较
来源：http://dali.yangfankeji.com/Article/details/gtmwethjvp.html

Ruby: s == s.reverse
来源：http://dali.sufxvd.cn/Article/details/gtdcrylzze.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangtech.top/Article/details/gtqupkwunh.html

[N07] 两数之和（返回下标）
来源：http://dali.birdmap.top/Article/details/gtzwswlkms.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hongshengwenyu.top/Article/details/gtmvxhggfk.html


<!-- 参考信息 -->