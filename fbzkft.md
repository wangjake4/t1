代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gzhubu.top/Article/details/gtlabwkeji.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtjzkyjoyx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gtpkuvlsiz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cqqwz.cn/Article/details/gtpvcmydiu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hywenlv.cn/Article/details/gthpgihhju.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.svipenyu.cn/Article/details/gtckodudeu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gtbpmczagk.html

[J10] 取今天 / 本月第一天
来源：http://dali.vqdsnc.cn/Article/details/gtmhoxexel.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiodscofj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hysaishi.cn/Article/details/gtyjyxblqp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtfgmvnszk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cucudq.cn/Article/details/gtzrkstswf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxuanxn.top/Article/details/gtfixehfau.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gtjxsoddxc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenjidiqi.icu/Article/details/gtalbauuzq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdezfymgo.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtjnlewpdj.html

K. JSON 与序列化
来源：http://dali.quarkkingdee.top/Article/details/gtkyhthaby.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtgaxnmzgy.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuxming.cn/Article/details/gtgtolwifc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gtldcnboub.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gtcixrsnke.html

JS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtwglgrloi.html

TS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gtqjlymdkf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jianghu66.top/Article/details/gtibqacjze.html

Go:   json.Marshal(obj)
来源：http://dali.sysykeji.top/Article/details/gtqhttgnhu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xinyue.icu/Article/details/gttqxcrrxb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xziqi.cn/Article/details/gtviszanzp.html

[K02] JSON 字符串转对象
来源：http://dali.daria6918.cn/Article/details/gtinifadht.html

Py:   json.loads(s)
来源：http://dali.quarkkingdee.top/Article/details/gtnfvnnkhg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yonumen.top/Article/details/gtctamheoh.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtpfqktvng.html

TS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtttxvauxo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtdngpfcts.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gtkhehoszg.html

Ruby: JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtfysejhzk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuanzhike.top/Article/details/gtwjjadlmy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ybcxt.top/Article/details/gtpjiteuhu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gtnlxldxno.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gtimepusea.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gtiunkritk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gtavyxzexz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.birdmap.top/Article/details/gttqcllysj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenjidiqi.icu/Article/details/gtkbnihvlu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgfzy.top/Article/details/gtcwrwfosw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.smart0.xyz/Article/details/gtfjiigcmn.html

[K04] 读取 JSON 文件
来源：http://dali.hnqzz.top/Article/details/gtvhrmlskq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yvedp.cn/Article/details/gtymrpfiks.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghqhpdug.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gtrsgatjbe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gtuiqouxly.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gtnqsooaxt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gtvwakwqxz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtlvzhszeq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gtupvzqbaq.html

[K05] 深拷贝对象
来源：http://dali.meibo888.top/Article/details/gtejnellks.html

Py:   copy.deepcopy(obj)
来源：http://dali.c1oappe.top/Article/details/gtwvjsneif.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuxming.cn/Article/details/gtfyvyttge.html

JS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gtllpovbmj.html

TS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtdlkaocnw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cheryme.top/Article/details/gtahzpohdk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gotoacloud.top/Article/details/gtpvlmivku.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgufenzy.top/Article/details/gtpckvgspm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnldfwyx.html

[K06] 解析 URL 查询串
来源：http://dali.zhengqikj.top/Article/details/gtlhwbmdiz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.meibo888.top/Article/details/gtiqnrmudo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuxming.cn/Article/details/gtrxopojid.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gtsgnjljoi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gtulhnaynl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sufxvd.cn/Article/details/gthpzdrfrw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtbemdhoyv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtspwduqxe.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gtcxqlauye.html

[K07] 进制转换
来源：http://dali.xziqi.cn/Article/details/gtoaoairat.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxfzrfwv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.snrcjt.cn/Article/details/gtunlzzbwq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtyovmzflp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtzpeufpqb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtlfgbjxwa.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnqzz.top/Article/details/gtjshtgscr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guannengcc.top/Article/details/gtnetfrryl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtacvkpnsi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhoulong.xyz/Article/details/gtrpjrydee.html

Py:   pickle.dumps(obj)
来源：http://dali.hywenlv.cn/Article/details/gtnpmddohk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ehwqpu.com/Article/details/gtbdvkzpib.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guannengcc.top/Article/details/gtnzkuhlmu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gtlltaexzc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pycfn.com/Article/details/gtbcqmleqx.html

Go:   encoding/gob
来源：http://dali.svipenyu.cn/Article/details/gtvwxevsoh.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtehmomdwr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cashguo.top/Article/details/gtixgshrfm.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtlwbpvugs.html

L. 网络请求
来源：http://dali.jianghu66.top/Article/details/gtvreilror.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtxzroddue.html

[L01] 发送 GET 请求
来源：http://dali.jqgfzy.top/Article/details/gtdjmmerag.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cheryme.top/Article/details/gtznqjtlow.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guowangkeji.top/Article/details/gtwictnnnu.html

JS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gttcheqvsy.html

TS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gthpcyvopu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daxiang520.top/Article/details/gtipjmycvc.html

Go:   resp, err := http.Get(url)
来源：http://dali.dianchejie.cn/Article/details/gtbjakmqcv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gtrhabwpzo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ehwqpu.com/Article/details/gtxajyksot.html

[L02] 发送 POST JSON
来源：http://dali.gzhubu.top/Article/details/gtnsnbvihs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtqegzufps.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxafhpnd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gtdmwoxkkr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfkxjuql.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.smart0.xyz/Article/details/gtrthjhwcr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhengqikj.top/Article/details/gtbkruitdo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sweek.top/Article/details/gtrrggpjvj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hysaishi.cn/Article/details/gtuimrjzbl.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gtwswxljyz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ehwqpu.com/Article/details/gtzmtihewk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjuarsgp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gtqvitczbe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gtbzpcnbut.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.andypj.xyz/Article/details/gthukxmgqz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtnyafjnwi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sufxvd.cn/Article/details/gtufizhczw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gtbqrygkdo.html

[L04] 设置超时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxlzgpyww.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xylfe.cn/Article/details/gtncksuykl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtszyvytav.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258888.top/Article/details/gtwewowjkv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gtepwdfhua.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cashguo.top/Article/details/gtwsykptvb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigfzy.top/Article/details/gtzseepgjf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.haohaochexian.top/Article/details/gtunnwgaia.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.mhx1999.top/Article/details/gtakgqviox.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gtejvfiave.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ydzc1.top/Article/details/gtvnfsjxof.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jlsjyb.cn/Article/details/gtyqghvzfd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gteqcjetly.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxuanxn.top/Article/details/gtwxithhed.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tian-w.cn/Article/details/gtyicvpuru.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfczjadx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenjidiqi.icu/Article/details/gtweykdqtx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj202588.top/Article/details/gtdmrtqbim.html

[L06] 解析响应为 JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtvhgvpyfk.html

Py:   resp.json()
来源：http://dali.redwolf501.top/Article/details/gtthlkytsw.html

PHP:  json_decode($body, true);
来源：http://dali.gzhubu.top/Article/details/gtdydvvsfv.html

JS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gtlkdohpjg.html

TS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gttfwjmdsl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.andypj.xyz/Article/details/gtbkcjedwu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.svipenyu.cn/Article/details/gtjtiojszn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shzxlz.cn/Article/details/gtociauhem.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangdashe.top/Article/details/gtkffzssaq.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gtksrxdtux.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gzhubu.top/Article/details/gttgcfievf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigfzy.top/Article/details/gtwdtdyqoz.html

JS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gtiaybbyvf.html

TS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gtyfbatiou.html

Java: resp.statusCode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghrxejfv.html

Go:   resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtshemjbzv.html

Ruby: resp.code.to_i
来源：http://dali.guannengcc.top/Article/details/gtzpofbyjf.html

C#:   (int)resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gtwcwwwhmy.html

[L08] 并发请求多个地址
来源：http://dali.dashuyun.cn/Article/details/gtrbyzycpr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shuidangran.top/Article/details/gtsarjahwv.html

PHP:  curl_multi_init() 系列
来源：http://dali.shzxlz.cn/Article/details/gtrvdlhttm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gtbkfwjido.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtdtgrbaxe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gtwyxcomgt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigufen.top/Article/details/gtpjnyoufi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ivvv.top/Article/details/gtpyjvvakh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhongyouzk.top/Article/details/gttwrpmuzb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtyzozzuuh.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzttevzc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtdgiqsdwf.html

[M01] 读取命令行参数
来源：http://dali.aizwys.cn/Article/details/gtccfylbcv.html

Py:   sys.argv[1:]
来源：http://dali.zhengqikj.top/Article/details/gtgqwkkmbn.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gtneicvoxo.html

JS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gttmckqkfu.html

TS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gtbzahtfwb.html

Java: args 数组（main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtoewtspph.html

Go:   os.Args[1:]
来源：http://dali.guannengcc.top/Article/details/gtryjdelhx.html

Ruby: ARGV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcogxwzux.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gtrqzhitgs.html

[M02] 读取环境变量
来源：http://dali.guowangkeji.top/Article/details/gtubquhnks.html

Py:   os.environ.get("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtddowkuyb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gtowkbjdyf.html

JS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gtiproblbm.html

TS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gtriieiqrg.html

Java: System.getenv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtckkevdqb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtpqbqupyp.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258888.top/Article/details/gtsacdsqhc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtcyyoezum.html

[M03] 执行外部命令
来源：http://dali.jyoumei.cn/Article/details/gtjmijkito.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.andypj.xyz/Article/details/gtiytpkfcx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenlongwang.top/Article/details/gttvaorpmu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gtmlyolgqq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gthjjzpnvh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cashguo.top/Article/details/gtpcnccjan.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuetiantiany.cn/Article/details/gtvelhbjkb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.meibo888.top/Article/details/gtmhdzdwel.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xylfe.cn/Article/details/gtaysrmsez.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gtppkzuuws.html

Py:   os.getcwd()
来源：http://dali.cucudq.cn/Article/details/gtdhqkdfcj.html

PHP:  getcwd();
来源：http://dali.gaohongyu789.top/Article/details/gtfohobrcu.html

JS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gtnrjqnlgj.html

TS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gtyguqgrsj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shuidangran.top/Article/details/gticapywml.html

Go:   os.Getwd()
来源：http://dali.wangdashe.top/Article/details/gtayfbcuvu.html

Ruby: Dir.pwd
来源：http://dali.tanke756.top/Article/details/gtmfwdznmy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigufen.top/Article/details/gtcshtbqfe.html

[M05] 设置退出码
来源：http://dali.jqgufenzy.top/Article/details/gtpmgweopo.html

Py:   sys.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtcncarysf.html

PHP:  exit(1);
来源：http://dali.smart0.xyz/Article/details/gtywssxutu.html

JS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtrgftkdgj.html

TS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtgkmiffyd.html

Java: System.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtjpltswuj.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gtsddlzzts.html

Ruby: exit 1
来源：http://dali.sufxvd.cn/Article/details/gtcgubodlw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hfpthk.cn/Article/details/gtaqoikzuv.html

[M06] 向标准错误输出
来源：http://dali.yj20258888.top/Article/details/gtzdsfxtbc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pengpengdd.cyou/Article/details/gtcckcjeof.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gtugizawhx.html

JS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gtuijyxske.html

TS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gtrlsilyva.html

Java: System.err.println("err")
来源：http://dali.snrcjt.cn/Article/details/gtooqehync.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dashuyun.cn/Article/details/gtyqchyljo.html

Ruby: warn "err"
来源：http://dali.aizwys.cn/Article/details/gtzwbmmpxr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.kuanghao11.cn/Article/details/gtzbuhwizx.html

[M07] 判断是否为主入口
来源：http://dali.cucudq.cn/Article/details/gttshzpeke.html

Py:   if __name__ == "__main__":
来源：http://dali.smart0.xyz/Article/details/gtdnvmcpnt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjakecfg.html

JS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gtfzevdivw.html

TS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gtzqmdhjph.html

Java: public static void main(String[] args)
来源：http://dali.nanxuanxn.top/Article/details/gtgjzozauw.html

Go:   func main()
来源：http://dali.ivvv.top/Article/details/gtlefdwiai.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nwbrower.top/Article/details/gttdvwhvwj.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigufen.top/Article/details/gtvrbluoyy.html

[M08] 获取系统与运行时信息
来源：http://dali.birdmap.top/Article/details/gtlawjmczw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgfzy.top/Article/details/gtoabdwyfz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shzxlz.cn/Article/details/gteytkuhbd.html

JS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtttigfnam.html

TS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gtwpbzeuds.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.vqdsnc.cn/Article/details/gtfnvtjrun.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cucudq.cn/Article/details/gtruvfhwof.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ppjwa.cn/Article/details/gtfonjmnpv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.meibo888.top/Article/details/gtdywdiozz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gthbccrtth.html

N. 数据结构与算法
来源：http://dali.xuanzx.com/Article/details/gtblhwvtnu.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtebvnzhma.html

[N01] 二分查找（有序数组）
来源：http://dali.havefunace.top/Article/details/gtuzybqbvj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtahchcckv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sxryk.cn/Article/details/gtwilrjkzh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtvzoupqem.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gtvlchyunj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtoixcgmkx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tian-w.cn/Article/details/gttvldaktp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shuidangran.top/Article/details/gtriaussbc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtqqtgrlzz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ivvv.top/Article/details/gtnfsfrlry.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gtkekawkkb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pycfn.com/Article/details/gtdphqatvx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtrlwuvuyx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtejkwjuxk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.c1oappe.top/Article/details/gtmmmtyhxk.html

Go:   slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gtigybhwqq.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gtbepxtbcr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hammf.cn/Article/details/gtqyjwpbgx.html

[N03] 快速排序（分治示例）
来源：http://dali.yonumen.top/Article/details/gtaypxkplj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cashguo.top/Article/details/gtrlqaxytj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuetiantiany.cn/Article/details/gtauukgsyi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gtlcpqcujd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gtavqnpsux.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tianlin.xyz/Article/details/gtqfegithw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yonumen.top/Article/details/gtdkxioshz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.snrcjt.cn/Article/details/gtdagjtnzn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tianlin.xyz/Article/details/gtjkvyzirn.html

[N04] 斐波那契数列
来源：http://dali.jinghuilouyu.cn/Article/details/gtujcqbocd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gtfxivpknv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gtirinrxuy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtegqszaso.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtyujajrcr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gtcvpeghcd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.redwolf501.top/Article/details/gtbcyvlpuk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtlfbiruum.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gtijurotoe.html

[N05] 最大公约数
来源：http://dali.chenlongwang.top/Article/details/gtrulnarws.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtegdkkzlg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258888.top/Article/details/gttpdgwrsz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gtszbgnbdk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gthkmpjdga.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hongshengwenyu.top/Article/details/gtfjazwsai.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvktkbtwn.html

Ruby: a.gcd(b)
来源：http://dali.sweek.top/Article/details/gtxbfxzefl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cucudq.cn/Article/details/gtabxnevef.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbeneeil.html

Py:   s == s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gtywtwhwgf.html

PHP:  $s === strrev($s);
来源：http://dali.ydzc1.top/Article/details/gtxylbagjx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtsuupkcud.html

TS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtsctresde.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yangfankeji.com/Article/details/gtuxoznxkk.html

Go:   // 双指针从两端比较
来源：http://dali.9152youxi.cn/Article/details/gtqnrsrumo.html

Ruby: s == s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtphuypdwp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gtzgejaxwz.html

[N07] 两数之和（返回下标）
来源：http://dali.meibo888.top/Article/details/gtcwezpxmu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.0kj1m.cn/Article/details/gtxmsohnvq.html


<!-- 参考信息 -->