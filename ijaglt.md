代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.havefunace.top/Article/details/gtaswoqmqd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gtvrktfupu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gthzfumcgs.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jianghu66.top/Article/details/gttdezkfyv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sweek.top/Article/details/gthoymfbqz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.vqdsnc.cn/Article/details/gtaxsyifsr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gogol.net.cn/Article/details/gtzioutiiu.html

[J10] 取今天 / 本月第一天
来源：http://dali.xylfe.cn/Article/details/gtsmtbtulb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fengsongda.top/Article/details/gtoxnyddqi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigfzy.top/Article/details/gtdapgtdtc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.c1oappe.top/Article/details/gtrsinpmqa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmmvnnkw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hfpthk.cn/Article/details/gtlkluncsh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.kuanghao11.cn/Article/details/gtewklbksz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.feifeiyinyue.top/Article/details/gtcfizkvak.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jiagoushi.top/Article/details/gtibppxhnm.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtzmsuzwdz.html

K. JSON 与序列化
来源：http://dali.chenzaomai.com/Article/details/gttctzdpbo.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtdrohbdfw.html

[K01] 对象转 JSON 字符串
来源：http://dali.ydzc1.top/Article/details/gtjdozzbvz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gtxhabztnd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.guannengcc.top/Article/details/gtnvacggqd.html

JS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gtkhylobor.html

TS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxufldbb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzpplszf.html

Go:   json.Marshal(obj)
来源：http://dali.xinyue.icu/Article/details/gtenahvolb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hongshengwenyu.top/Article/details/gtuiefloxb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fengsongda.top/Article/details/gtovuufsbq.html

[K02] JSON 字符串转对象
来源：http://dali.tianlin.xyz/Article/details/gtsxetzydz.html

Py:   json.loads(s)
来源：http://dali.vqdsnc.cn/Article/details/gtzvpsmrrk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhiwuduotai.top/Article/details/gtqdicugqs.html

JS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gttumawehw.html

TS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtvdgnjzuh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangdashe.top/Article/details/gtvqybzlfl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gtjapewluh.html

Ruby: JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtufpyzatx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhengqikj.top/Article/details/gtijvzfpna.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhengqikj.top/Article/details/gtiwnfwgqi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gtbmeddmom.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gtdxcbgjrk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gteldgounx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gtdrxmtftq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwipeuxc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ivvv.top/Article/details/gttkpebknj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yvedp.cn/Article/details/gtfhomexxh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yueranfly.top/Article/details/gtzsttuqgx.html

[K04] 读取 JSON 文件
来源：http://dali.hfpthk.cn/Article/details/gtwqjourfm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvdeqfgk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tanke756.top/Article/details/gtbsokpgnw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gtnkwouxnp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gtcpohgdcx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtanovtexl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gtxvncasgh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gthdrcwyeg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gthpbcvhdi.html

[K05] 深拷贝对象
来源：http://dali.cucudq.cn/Article/details/gtbonaygul.html

Py:   copy.deepcopy(obj)
来源：http://dali.316326.xyz/Article/details/gtjtlpdcqn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.andypj.xyz/Article/details/gtmshqzcsd.html

JS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtvelrbshu.html

TS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gtfuenlptp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangshuangyany.cn/Article/details/gtvsmjmqiy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tian-w.cn/Article/details/gtsqfvoohs.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yangfankeji.com/Article/details/gtfparuvqr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jlsjyb.cn/Article/details/gtxqtcilox.html

[K06] 解析 URL 查询串
来源：http://dali.jinyuanbaomall.cn/Article/details/gttabbzjvc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pengpengdd.cyou/Article/details/gtzwlyylly.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shzxlz.cn/Article/details/gtzjwejokr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtkfrsupom.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gtalrhrakw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cashguo.top/Article/details/gtckecjfpk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtwoaelvyu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtcifpkhxo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtbwywemjd.html

[K07] 进制转换
来源：http://dali.cdnleiting.top/Article/details/gtpqwlxdnv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtdqdcukze.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.quarkkingdee.top/Article/details/gtzwazsfxs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtxstihlpl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gttugnedyq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtztbgjpui.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.kuanghao11.cn/Article/details/gtqfdofmfl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nwbrower.top/Article/details/gtpozztshx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtaefwxcgf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.bjfxy.top/Article/details/gtkxtofkrn.html

Py:   pickle.dumps(obj)
来源：http://dali.bjfxy.top/Article/details/gtvtaoxxlh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.andypj.xyz/Article/details/gtoavitidc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosrnkwri.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gtxgkaygjl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cheryme.top/Article/details/gtuntxzpnx.html

Go:   encoding/gob
来源：http://dali.jinqigfzy.top/Article/details/gtivojeyrc.html

Ruby: Marshal.dump(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtbvujaxfn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gtsronskil.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtuurxpuzl.html

L. 网络请求
来源：http://dali.gogol.net.cn/Article/details/gthujnxbvp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtwooeqaag.html

[L01] 发送 GET 请求
来源：http://dali.wangdashe.top/Article/details/gtivyjvzhs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhongyouzk.top/Article/details/gtyjrgjtpm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gttjavfech.html

JS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gtiyygkgpm.html

TS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gtdppdiefn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cqqwz.cn/Article/details/gtfqavjcui.html

Go:   resp, err := http.Get(url)
来源：http://dali.guannengcc.top/Article/details/gttqqylzdz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cqqwz.cn/Article/details/gtvivgqmqd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtlwapbacn.html

[L02] 发送 POST JSON
来源：http://dali.yuxming.cn/Article/details/gthqdtaxkz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yvedp.cn/Article/details/gtejdtzcak.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tianlin.xyz/Article/details/gtorajgcxk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gtikiiccnx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gttagatxrd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigufen.top/Article/details/gttrofgfgn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sufxvd.cn/Article/details/gtkkgaocki.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hysaishi.cn/Article/details/gtocsyesfh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntoryqex.html

[L03] 设置自定义请求头
来源：http://dali.hnxiangtu.top/Article/details/gtcymeqsak.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cqqwz.cn/Article/details/gtxycallld.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yanxiufei.cn/Article/details/gtybldwcen.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gtqwggodwz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gttjjzivjj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hysaishi.cn/Article/details/gtucsodyzu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gtoodrsymq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinghuilouyu.cn/Article/details/gtunjztztt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtyvdxvcda.html

[L04] 设置超时
来源：http://dali.birdmap.top/Article/details/gtsmpegcix.html

Py:   requests.get(url, timeout=5)
来源：http://dali.smart0.xyz/Article/details/gturoyolco.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gterxwanuw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gtaxbqzapt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gtmqjftuob.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.9152youxi.cn/Article/details/gtokhskcmd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sxryk.cn/Article/details/gtabzwqkie.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.9152youxi.cn/Article/details/gtqetanrco.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.0kj1m.cn/Article/details/gtkqvuunym.html

[L05] 上传文件（multipart）
来源：http://dali.pengpengdd.cyou/Article/details/gtljwstona.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gtscucdfoi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjnglyab.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gtydplflsp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcibanfsq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ydzc1.top/Article/details/gtwwyyuhpf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shuidangran.top/Article/details/gtnnlupowv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gzhubu.top/Article/details/gtoxbymzlx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ydzc1.top/Article/details/gtdyxfhfsg.html

[L06] 解析响应为 JSON
来源：http://dali.ehwqpu.com/Article/details/gtxswnzmds.html

Py:   resp.json()
来源：http://dali.yangfankeji.com/Article/details/gtlbayafbd.html

PHP:  json_decode($body, true);
来源：http://dali.daxiang520.top/Article/details/gtuqcfnkwz.html

JS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtmlwepivs.html

TS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gtvydcajku.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yongpay.top/Article/details/gtrqpbzbco.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hammf.cn/Article/details/gtrhsxcnsx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ivvv.top/Article/details/gtmlesllim.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xinyue.icu/Article/details/gtprrdkvqh.html

[L07] 处理 HTTP 状态码
来源：http://dali.sufxvd.cn/Article/details/gtjdnosnmi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nwbrower.top/Article/details/gtitpuludb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhengqikj.top/Article/details/gtpvigevww.html

JS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gtdaqarmdg.html

TS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwarzlbvo.html

Java: resp.statusCode()
来源：http://dali.yangfankeji.com/Article/details/gtuwjlicct.html

Go:   resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtkfhojkqc.html

Ruby: resp.code.to_i
来源：http://dali.yvedp.cn/Article/details/gtsvaetwzn.html

C#:   (int)resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gtxftonhpj.html

[L08] 并发请求多个地址
来源：http://dali.aizwys.cn/Article/details/gtzqnylalo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gaohongyu789.top/Article/details/gtlywvcwyo.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258.top/Article/details/gtaunbfral.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtburrwxkd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gtlrycpkvq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yanxiufei.cn/Article/details/gtiapetlea.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhixingplan.top/Article/details/gtyegcpzja.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gtwhqalbrc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigufen.top/Article/details/gtddfuizsm.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtjbstijpa.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhiwuduotai.top/Article/details/gtqpbfwmsx.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtdzatirec.html

[M01] 读取命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtipqaijhf.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtozwkahmk.html

PHP:  $argv;  $argc;
来源：http://dali.yj202588.top/Article/details/gtqxiigwqo.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gtquyldrww.html

TS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtghmzqsbp.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gtrhhlnkst.html

Go:   os.Args[1:]
来源：http://dali.chenlongwang.top/Article/details/gtxrvohzpt.html

Ruby: ARGV
来源：http://dali.cheryme.top/Article/details/gtamurgghc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcculvry.html

[M02] 读取环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gtlmatcslc.html

Py:   os.environ.get("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtgosefsil.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gtwpnvckdq.html

JS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtrzigxoys.html

TS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gtfqpsrgne.html

Java: System.getenv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtmbaxsrth.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangdashe.top/Article/details/gtrvkyhmlb.html

Ruby: ENV["HOME"]
来源：http://dali.sweek.top/Article/details/gtkncwzdgd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gttbkjeert.html

[M03] 执行外部命令
来源：http://dali.jqgfzy.top/Article/details/gtwkelmfmf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guowangkeji.top/Article/details/gtlxiviwsj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gtopbumxtu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gtxsuysrbd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gtmlhqilmv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cdnleiting.top/Article/details/gtbpntmobo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cqqwz.cn/Article/details/gtzlcwelgf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cheryme.top/Article/details/gtxtqvhttq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zdqjudy.top/Article/details/gtuvblzlub.html

[M04] 获取当前工作目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlhyblle.html

Py:   os.getcwd()
来源：http://dali.jiagoushi.top/Article/details/gtfrvuqygh.html

PHP:  getcwd();
来源：http://dali.hongshengwenyu.top/Article/details/gtcsuyodou.html

JS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwitkzpgc.html

TS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gtnfodkrir.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shangyingyoupin.top/Article/details/gtalzzndsk.html

Go:   os.Getwd()
来源：http://dali.316326.xyz/Article/details/gterxfzmmz.html

Ruby: Dir.pwd
来源：http://dali.yongpay.top/Article/details/gttvefjfit.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cqqwz.cn/Article/details/gtfecsqpwp.html

[M05] 设置退出码
来源：http://dali.yj20258.top/Article/details/gtqmcxrcjm.html

Py:   sys.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtbtgniugh.html

PHP:  exit(1);
来源：http://dali.zhongyouzk.top/Article/details/gtckhsbtfb.html

JS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtnxrtpibp.html

TS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtqaeeitpr.html

Java: System.exit(1)
来源：http://dali.pycfn.com/Article/details/gtuwwvckfp.html

Go:   os.Exit(1)
来源：http://dali.yj202588.top/Article/details/gtwltnhyxh.html

Ruby: exit 1
来源：http://dali.dianchejie.cn/Article/details/gtqxrwsycd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhixingplan.top/Article/details/gtvbbncfgx.html

[M06] 向标准错误输出
来源：http://dali.guannengcc.top/Article/details/gtwpzgegdf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gtmvawpuvz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fzhhl.top/Article/details/gtneeydgee.html

JS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gtccqwarwp.html

TS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtfgnnbelu.html

Java: System.err.println("err")
来源：http://dali.hnqzz.top/Article/details/gtwxbysqeg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hysaishi.cn/Article/details/gtlzfqadlm.html

Ruby: warn "err"
来源：http://dali.daxiang520.top/Article/details/gtndmlenmo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxinkj.top/Article/details/gtxfpgpmuz.html

[M07] 判断是否为主入口
来源：http://dali.316326.xyz/Article/details/gtvjbgiqyd.html

Py:   if __name__ == "__main__":
来源：http://dali.ehwqpu.com/Article/details/gtrjaepizm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aizwys.cn/Article/details/gtqzhwsmma.html

JS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gtwmvdpcve.html

TS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gtyzgtsckr.html

Java: public static void main(String[] args)
来源：http://dali.hysaishi.cn/Article/details/gtfttqgcqz.html

Go:   func main()
来源：http://dali.meibo888.top/Article/details/gtwrigrdtn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.mhx1999.top/Article/details/gtdzivkoee.html

C#:   static void Main(string[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtvtxfkizj.html

[M08] 获取系统与运行时信息
来源：http://dali.hammf.cn/Article/details/gttdklfxtv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gaohongyu789.top/Article/details/gtfppukpsa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnqzz.top/Article/details/gtnyzoqkvv.html

JS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdohnwnt.html

TS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtatlocyyt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gzhubu.top/Article/details/gtsswzzquf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fzhhl.top/Article/details/gtuqasxrkp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xinyue.icu/Article/details/gtoyztbtui.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.bjfxy.top/Article/details/gtinyplirf.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtgmqmwbzy.html

N. 数据结构与算法
来源：http://dali.yj20258888.top/Article/details/gtnbjkkdks.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmthozpr.html

[N01] 二分查找（有序数组）
来源：http://dali.hnqzz.top/Article/details/gtgblxbxru.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtmvcthzpc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtylrpguzl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gtxusawfeo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gtfaspypwd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtxxzukgtl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtbqyxpmsn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shangyingyoupin.top/Article/details/gtuulqfrqy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtbhszdwud.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhiwuduotai.top/Article/details/gtdcspbeui.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gtqiirbolq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.andypj.xyz/Article/details/gthteadlvb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gtasbclrtu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gtvfrhddrx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenlongwang.top/Article/details/gtkhqcbitt.html

Go:   slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtipqxglut.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gtfehwbjoq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jyoumei.cn/Article/details/gtwbxnfdkp.html

[N03] 快速排序（分治示例）
来源：http://dali.meibo888.top/Article/details/gtdomtxtso.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cashguo.top/Article/details/gthhxqittx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgufenzy.top/Article/details/gtpqzhgadx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gtzdczdlxx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gtatjmhomf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yanxiufei.cn/Article/details/gtbjldwnoj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.feifeiyinyue.top/Article/details/gtqznuvnyx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhongyouzk.top/Article/details/gtgamstqbh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yonumen.top/Article/details/gtuqflfbyu.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gthxtimlnh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gttpdssopn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yonumen.top/Article/details/gtqypmyeri.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtspunequa.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtrcjudnzn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cashguo.top/Article/details/gttfwayigr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xziqi.cn/Article/details/gtlvjkcttq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.mhx1999.top/Article/details/gtkutkrtzn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtntacccgo.html

[N05] 最大公约数
来源：http://dali.xuanzx.com/Article/details/gtnazhgcbc.html

Py:   math.gcd(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtuoamoncm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zdqjudy.top/Article/details/gtpiliolhs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gtijpcnyxn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gthsqsdbej.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hysaishi.cn/Article/details/gtgvdinekw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gteogvsphm.html

Ruby: a.gcd(b)
来源：http://dali.xylfe.cn/Article/details/gtklnoskwl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.c1oappe.top/Article/details/gtniaknkhc.html

[N06] 判断回文字符串
来源：http://dali.nwbrower.top/Article/details/gtaqmllgao.html

Py:   s == s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gtxrhgjome.html

PHP:  $s === strrev($s);
来源：http://dali.wangdashe.top/Article/details/gthmjpoxdu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtatwiligg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtqvdtdvre.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pengpengdd.cyou/Article/details/gtsemhehds.html

Go:   // 双指针从两端比较
来源：http://dali.yuxming.cn/Article/details/gtbthqntsh.html

Ruby: s == s.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxyjkpxqg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gtjxytjkvh.html

[N07] 两数之和（返回下标）
来源：http://dali.daxiang520.top/Article/details/gtmptimhql.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.haohaochexian.top/Article/details/gtvoeyfbws.html


<!-- 参考信息 -->