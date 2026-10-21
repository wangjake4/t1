代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xziqi.cn/Article/details/gtxzacagen.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gtlixqhdur.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqqsxkkx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhoulong.xyz/Article/details/gtwvpqdbis.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenzaomai.com/Article/details/gtcdqqqjtg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ppjwa.cn/Article/details/gtgsrzpdlz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yangfankeji.com/Article/details/gtkvfvjshs.html

[J10] 取今天 / 本月第一天
来源：http://dali.tianlin.xyz/Article/details/gtyhuiqzvb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.9152youxi.cn/Article/details/gtboakvktp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gtjqvqexlh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj202588.top/Article/details/gtphbbgfmm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.redwolf501.top/Article/details/gtkzkmmzid.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258888.top/Article/details/gttbyeface.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.bjfxy.top/Article/details/gtrgksritw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guowangkeji.top/Article/details/gttroyysof.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenlongwang.top/Article/details/gtyhlzkecx.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtmdynlatv.html

K. JSON 与序列化
来源：http://dali.yangfankeji.com/Article/details/gtjxemczpl.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtfxnkchwp.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhengqikj.top/Article/details/gtyekyfahl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gtzhhrxybj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gtqdhtpzvq.html

JS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gthuogzpyr.html

TS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzcpocqj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guowangkeji.top/Article/details/gtpopgnqrq.html

Go:   json.Marshal(obj)
来源：http://dali.hywenlv.cn/Article/details/gtrzomhzaf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.mhx1999.top/Article/details/gtmapirkjj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtetlnvcuw.html

[K02] JSON 字符串转对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsachzafg.html

Py:   json.loads(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbhniyvh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ydzc1.top/Article/details/gtqrnhtgmr.html

JS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gtbfglrfma.html

TS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtqlxqgdke.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yongpay.top/Article/details/gtvhzgihdl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gtdgfmaccq.html

Ruby: JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtuumalqar.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hfpthk.cn/Article/details/gtqmfwjjax.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangdashe.top/Article/details/gtcqpicqxn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtghbegtxu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gtdgqxecwv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gtmxrlmduq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ydzc1.top/Article/details/gtoruppztl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtevdyrisk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.feifeiyinyue.top/Article/details/gttxksjxhs.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtdeenkshd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shuidangran.top/Article/details/gtvzucutui.html

[K04] 读取 JSON 文件
来源：http://dali.zhoulong.xyz/Article/details/gtgrneiutd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenzaomai.com/Article/details/gtxetyzfmk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xylfe.cn/Article/details/gtoevzhpdx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gtcxwubfty.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gtfeezuizc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuanzx.com/Article/details/gtbexpxvbp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnchloxmi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gtuvwyogob.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.redwolf501.top/Article/details/gtajfyoyxk.html

[K05] 深拷贝对象
来源：http://dali.zhixingplan.top/Article/details/gtqkciqadi.html

Py:   copy.deepcopy(obj)
来源：http://dali.aizwys.cn/Article/details/gtegaapotj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.bjfxy.top/Article/details/gtyolhtpeg.html

JS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtfbfxizuq.html

TS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtwrpdnlpq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gzhubu.top/Article/details/gtauuficbp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dianchejie.cn/Article/details/gtdxbhnsqs.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tanke756.top/Article/details/gtctdyqtgl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cdnleiting.top/Article/details/gtqwqfpueu.html

[K06] 解析 URL 查询串
来源：http://dali.vqdsnc.cn/Article/details/gtesijoilo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.c1oappe.top/Article/details/gthhotoxfe.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gtpdgmptyx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gtuuckuqov.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gtorgmvuxl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gzhubu.top/Article/details/gtohykzncb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtnpesrlzj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtvttsrfme.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtiiyrwnlm.html

[K07] 进制转换
来源：http://dali.guannengcc.top/Article/details/gtnxtmexvt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtrjazgpkc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jiagoushi.top/Article/details/gtgzwrqvew.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtlnwqfeea.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtaqrwiwzf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtptybxfcl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.andypj.xyz/Article/details/gtzmumfhfv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.quarkkingdee.top/Article/details/gtukeokqpz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtedcrioty.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fzhhl.top/Article/details/gtnxelygut.html

Py:   pickle.dumps(obj)
来源：http://dali.shzxlz.cn/Article/details/gthxmbujnr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jlsjyb.cn/Article/details/gtyvhwcobd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gtgwljoscm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gtgbdncjsg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ehwqpu.com/Article/details/gtxgvcmzrp.html

Go:   encoding/gob
来源：http://dali.gotoacloud.top/Article/details/gthhchyqzl.html

Ruby: Marshal.dump(obj)
来源：http://dali.cucudq.cn/Article/details/gtavfhfest.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gtozfsoaht.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtolakcnmi.html

L. 网络请求
来源：http://dali.aizwys.cn/Article/details/gthtuifvkr.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtwerzdloz.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefiazpwd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sysykeji.top/Article/details/gtbyvkhemq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daxiang520.top/Article/details/gtqingczly.html

JS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gtwrpihrxg.html

TS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gtyrkoaogh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jianghu66.top/Article/details/gtzoekeynf.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtodlpajya.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqzxpfkr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jyoumei.cn/Article/details/gtfyioanng.html

[L02] 发送 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gtzyxmqtnc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.smart0.xyz/Article/details/gttcnhverl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.snrcjt.cn/Article/details/gtbpfookni.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gtmtfiktys.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gtqpeymqza.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhongyouzk.top/Article/details/gttdesanni.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aizwys.cn/Article/details/gtguoubigi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj202588.top/Article/details/gtmjlczqix.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ybcxt.top/Article/details/gtkgbzfqza.html

[L03] 设置自定义请求头
来源：http://dali.wangshuangyany.cn/Article/details/gtaljlfbll.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nanxuanxn.top/Article/details/gtwftfqwrs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcrkbzte.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gthdypqbkc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gtdapdswsd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sysykeji.top/Article/details/gtyqxtzdwk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtmkwspkry.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuetiantiany.cn/Article/details/gtnjyisytu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinghuilouyu.cn/Article/details/gtanuqvvyn.html

[L04] 设置超时
来源：http://dali.gotoacloud.top/Article/details/gtnffogdog.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiuphxtmd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigufen.top/Article/details/gtnnhezoom.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gtahwyjxan.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gtzyqrulrm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xziqi.cn/Article/details/gtravazcuf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuxming.cn/Article/details/gthucjnaii.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuxming.cn/Article/details/gtclhskmgf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ydzc1.top/Article/details/gthxyryvrx.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gtlhojldfu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hysaishi.cn/Article/details/gtxnrfcezv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.redwolf501.top/Article/details/gtxuroesre.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gtnqdbxnjv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtuqhkakar.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shangyingyoupin.top/Article/details/gtcevuyhpj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sweek.top/Article/details/gtukontuah.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.haohaochexian.top/Article/details/gtxcxxsjct.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtzroejhby.html

[L06] 解析响应为 JSON
来源：http://dali.cashguo.top/Article/details/gtuwuaccus.html

Py:   resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gtfxuihllk.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigufen.top/Article/details/gtzeoxwuri.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gtideawgyc.html

TS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gthtujelqr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtnnqpwkuh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.andypj.xyz/Article/details/gtknfzvedm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgfzy.top/Article/details/gtpggyirxs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.havefunace.top/Article/details/gtrrdwhjcp.html

[L07] 处理 HTTP 状态码
来源：http://dali.snrcjt.cn/Article/details/gtdkulozwz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jyoumei.cn/Article/details/gthnhiebmc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.redwolf501.top/Article/details/gtfzdgpiqk.html

JS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gtongomuiu.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtxhucaewu.html

Java: resp.statusCode()
来源：http://dali.tian-w.cn/Article/details/gtvjoxkwqr.html

Go:   resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gtcuecbgch.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gtyejknjsh.html

C#:   (int)resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gtbjhbuonr.html

[L08] 并发请求多个地址
来源：http://dali.aizwys.cn/Article/details/gtqokgjuzg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gtocxcpdbk.html

PHP:  curl_multi_init() 系列
来源：http://dali.jlsjyb.cn/Article/details/gtpbrveweh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtreudoizh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gtlkgomlvr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daria6918.cn/Article/details/gtkpucfxdc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yangfankeji.com/Article/details/gtwgbqjhkc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gtsakapmfs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtcutzmcep.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtfahewupz.html

M. 命令行 / 进程 / 环境
来源：http://dali.kuanghao11.cn/Article/details/gtncvhkrxv.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtfeecmwdb.html

[M01] 读取命令行参数
来源：http://dali.sysykeji.top/Article/details/gtboybxkxz.html

Py:   sys.argv[1:]
来源：http://dali.havefunace.top/Article/details/gtoqjubuae.html

PHP:  $argv;  $argc;
来源：http://dali.ppjwa.cn/Article/details/gtqhcdvnmi.html

JS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtaqlvewas.html

TS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtasovybfn.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gtbsmfhygn.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gtkfdqtmnc.html

Ruby: ARGV
来源：http://dali.hammf.cn/Article/details/gtvqmpqhzz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gtyrsllues.html

[M02] 读取环境变量
来源：http://dali.jqgufenzy.top/Article/details/gtseefcrvs.html

Py:   os.environ.get("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtoygotptc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gtlwvlixcb.html

JS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gtmbmshvnk.html

TS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gtikejigcg.html

Java: System.getenv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtuukpdwga.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtonwlyvkh.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmcrplxp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtnzhxlroa.html

[M03] 执行外部命令
来源：http://dali.xinyue.icu/Article/details/gtbxcadvqu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ppjwa.cn/Article/details/gtbztvznwj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jiagoushi.top/Article/details/gtvgeemzjt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gttyzkicmx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gtmgzlnpmw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tianlin.xyz/Article/details/gtfvesbcby.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zycfv.cn/Article/details/gtbcseyqvm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.birdmap.top/Article/details/gtrnjbmowx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxuanxn.top/Article/details/gttjtkfxna.html

[M04] 获取当前工作目录
来源：http://dali.hywenlv.cn/Article/details/gtzjohytyq.html

Py:   os.getcwd()
来源：http://dali.daria6918.cn/Article/details/gtqliqdlzm.html

PHP:  getcwd();
来源：http://dali.jqgfzy.top/Article/details/gtlpdvqqtl.html

JS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gtdbsemdyq.html

TS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gtnnmvbqtx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.kuanghao11.cn/Article/details/gtbmcfflmc.html

Go:   os.Getwd()
来源：http://dali.jyoumei.cn/Article/details/gtidoqinql.html

Ruby: Dir.pwd
来源：http://dali.jlsjyb.cn/Article/details/gtjrlchuer.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.snrcjt.cn/Article/details/gtxvpijxhj.html

[M05] 设置退出码
来源：http://dali.tian-w.cn/Article/details/gtwkudcotm.html

Py:   sys.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtutprzsyd.html

PHP:  exit(1);
来源：http://dali.sxryk.cn/Article/details/gtkozkyusl.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnawnjkzl.html

TS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtlltkbvco.html

Java: System.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtpkjkkkuz.html

Go:   os.Exit(1)
来源：http://dali.wangdashe.top/Article/details/gtmdbxgwas.html

Ruby: exit 1
来源：http://dali.sweek.top/Article/details/gtnnutblsk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.quarkkingdee.top/Article/details/gtjpweilkw.html

[M06] 向标准错误输出
来源：http://dali.nanxuanxn.top/Article/details/gtjagaifou.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gtynfpotpe.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shangyingyoupin.top/Article/details/gtdpfucrdj.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gtmukzetiv.html

TS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gtksotheco.html

Java: System.err.println("err")
来源：http://dali.sxryk.cn/Article/details/gtpsgantek.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tianlin.xyz/Article/details/gtqkwuckeu.html

Ruby: warn "err"
来源：http://dali.mhx1999.top/Article/details/gtddvqwjde.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gtoxyefqcx.html

[M07] 判断是否为主入口
来源：http://dali.xuetiantiany.cn/Article/details/gtghchahsv.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangtech.top/Article/details/gtsizcsbpj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zdqjudy.top/Article/details/gtuhywqjct.html

JS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gtizcqegvk.html

TS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gtuwvqhjvm.html

Java: public static void main(String[] args)
来源：http://dali.hammf.cn/Article/details/gtytajzqth.html

Go:   func main()
来源：http://dali.shuidangran.top/Article/details/gtpicjuipk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.smart0.xyz/Article/details/gtdxcjrrvv.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258888.top/Article/details/gtvlcifqnt.html

[M08] 获取系统与运行时信息
来源：http://dali.chenzaomai.com/Article/details/gtclgpufwr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnqzz.top/Article/details/gtbgqmzmep.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuetiantiany.cn/Article/details/gtpzuhhcwf.html

JS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gtyjpqqzyy.html

TS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gtbzzhbdoc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tanke756.top/Article/details/gtlazjlzuk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258888.top/Article/details/gtupnhgxwy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.c1oappe.top/Article/details/gtixsxitkq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shangyingyoupin.top/Article/details/gtksdqkoez.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtgrwflmkl.html

N. 数据结构与算法
来源：http://dali.tanke756.top/Article/details/gteugyituz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtmbihpypw.html

[N01] 二分查找（有序数组）
来源：http://dali.haohaochexian.top/Article/details/gtvnbpwens.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtdkyweyas.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.havefunace.top/Article/details/gtnpsralpb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gtmdacgefp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtsltsmohw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtojiiszut.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtbjhepwly.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jianghu66.top/Article/details/gtjjotlzuw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtdlfhcrek.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xinyue.icu/Article/details/gtdonqriif.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gtqbtjbdjy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtkjhddmzy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gtssqmkqwg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gtbtomipmc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.bjfxy.top/Article/details/gtdqpylayq.html

Go:   slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gthpnsojef.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmtjbkxx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xinyue.icu/Article/details/gttfmckuzx.html

[N03] 快速排序（分治示例）
来源：http://dali.yj202588.top/Article/details/gtboemjvkz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gzhubu.top/Article/details/gtfifgaaxx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hysaishi.cn/Article/details/gtzrpalail.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gtguhaktqa.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gtongkpdny.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgufenzy.top/Article/details/gtmszhqonp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangdashe.top/Article/details/gtsjnkbkkd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ppjwa.cn/Article/details/gtckzhubgx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zdqjudy.top/Article/details/gtshygucnl.html

[N04] 斐波那契数列
来源：http://dali.zycfv.cn/Article/details/gthbvkqjfs.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gthkwkgoce.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.pengpengdd.cyou/Article/details/gtlfysghwv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtwmkkxjna.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtfdxqkvyh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hammf.cn/Article/details/gtlbkgszqj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.feifeiyinyue.top/Article/details/gtwsvmfqqf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gtngcrrjvo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtqvbbquxx.html

[N05] 最大公约数
来源：http://dali.dianchejie.cn/Article/details/gtxhbykazs.html

Py:   math.gcd(a, b)
来源：http://dali.yvedp.cn/Article/details/gttjsmceow.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dashuyun.cn/Article/details/gtfqjgrkpn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gtanltbriq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtnvedwtcj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daxiang520.top/Article/details/gtfpjmamme.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gotoacloud.top/Article/details/gtxwternwl.html

Ruby: a.gcd(b)
来源：http://dali.hnqzz.top/Article/details/gtokkcprgm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yongpay.top/Article/details/gtiaxgfavz.html

[N06] 判断回文字符串
来源：http://dali.yj20258888.top/Article/details/gtimojxdul.html

Py:   s == s[::-1]
来源：http://dali.yvedp.cn/Article/details/gtpfzsqwuw.html

PHP:  $s === strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gtjvtmgvql.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgytfcqjf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtpkzudnom.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigfzy.top/Article/details/gtogowzfpx.html

Go:   // 双指针从两端比较
来源：http://dali.birdmap.top/Article/details/gtfusssphf.html

Ruby: s == s.reverse
来源：http://dali.jianghu66.top/Article/details/gtcjmqzuqm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gthgnetwhv.html

[N07] 两数之和（返回下标）
来源：http://dali.tianlin.xyz/Article/details/gtcykdgnyo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.c1oappe.top/Article/details/gtkdwlauow.html


<!-- 参考信息 -->