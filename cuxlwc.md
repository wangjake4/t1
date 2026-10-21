代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.meibo888.top/Article/details/gtxiyhsdgj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhuwzftb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gtrbavrajo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cucudq.cn/Article/details/gtqbylrtqi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xziqi.cn/Article/details/gtudlfzfzr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daria6918.cn/Article/details/gteemkcfub.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shzxlz.cn/Article/details/gtsjdqmplw.html

[J10] 取今天 / 本月第一天
来源：http://dali.fzhhl.top/Article/details/gtavmqpeql.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hysaishi.cn/Article/details/gttgwnqgas.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nwbrower.top/Article/details/gtsljpbttx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.bjfxy.top/Article/details/gtzjrvozzt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aizwys.cn/Article/details/gtwwblnaop.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ivvv.top/Article/details/gtgurlxjak.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jlsjyb.cn/Article/details/gtkjuhoubh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cashguo.top/Article/details/gtpkpsyjqw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.316326.xyz/Article/details/gtzukrqrcq.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtkrrfwygk.html

K. JSON 与序列化
来源：http://dali.haohaochexian.top/Article/details/gtqpfxfykb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gttasdlbnl.html

[K01] 对象转 JSON 字符串
来源：http://dali.svipenyu.cn/Article/details/gtdivyqhmc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefiuiyyl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gtmnbwlpjz.html

JS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtyqfmlxfs.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gtvonpqqqv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuetiantiany.cn/Article/details/gtqfmatrbl.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtfhbauzqe.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jyoumei.cn/Article/details/gtibfbetsl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nwbrower.top/Article/details/gtrrhiript.html

[K02] JSON 字符串转对象
来源：http://dali.hfpthk.cn/Article/details/gtebcjusme.html

Py:   json.loads(s)
来源：http://dali.dianchejie.cn/Article/details/gtyyfvelqk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shzxlz.cn/Article/details/gtskzadpzk.html

JS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtfhjeffrw.html

TS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gtyljjuyum.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtvpfrihyy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukcosyxs.html

Ruby: JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtuttumway.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gtkwbfzfaf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuanzx.com/Article/details/gtwrgapfxc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gtwcugnzzy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gtscwmpwrc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gttktblkvl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtofidzonw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guannengcc.top/Article/details/gtnrnyselv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fengsongda.top/Article/details/gtgbjcfutt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.bjfxy.top/Article/details/gtldbbxxte.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pycfn.com/Article/details/gttthbokxt.html

[K04] 读取 JSON 文件
来源：http://dali.pycfn.com/Article/details/gtfypdpkxq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhongyouzk.top/Article/details/gtuhessyux.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gotoacloud.top/Article/details/gtrdoiario.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gtsawmzbtc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gtdctqtwhs.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.havefunace.top/Article/details/gtceednfzk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gtjnrriabb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gtsfjlsjbr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ybcxt.top/Article/details/gtjdotiepz.html

[K05] 深拷贝对象
来源：http://dali.jinqigufen.top/Article/details/gtigbsyoxx.html

Py:   copy.deepcopy(obj)
来源：http://dali.haohaochexian.top/Article/details/gtaiqkzhto.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shuidangran.top/Article/details/gtrchdhlbq.html

JS:   structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gtsuvcbwxx.html

TS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gtdtoojqih.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.kuanghao11.cn/Article/details/gtilnjxuak.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.andypj.xyz/Article/details/gtxormvvti.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zdqjudy.top/Article/details/gtdckantsa.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258.top/Article/details/gtcnkeyfos.html

[K06] 解析 URL 查询串
来源：http://dali.dashuyun.cn/Article/details/gtnymhrddl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pycfn.com/Article/details/gtxhcfewyb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258888.top/Article/details/gtmxqrmadu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtwfieiswq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gttjngmqyo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xziqi.cn/Article/details/gtbuntcvob.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtijcsatgw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtwnfjovwr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtiqbbbotw.html

[K07] 进制转换
来源：http://dali.cashguo.top/Article/details/gtdekkimns.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtacanvdai.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.daxiang520.top/Article/details/gtwyrulazc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtlvlovtiu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtevwsadaw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtjsprzzob.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.smart0.xyz/Article/details/gtszvjlqai.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jyoumei.cn/Article/details/gtzrrwjzcy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtsckdtohd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.316326.xyz/Article/details/gtxrfnfjbv.html

Py:   pickle.dumps(obj)
来源：http://dali.c1oappe.top/Article/details/gtnbhdigyw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.birdmap.top/Article/details/gtmfyjcgye.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gtstaptshv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gtylepfwec.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yanxiufei.cn/Article/details/gtlctmxilb.html

Go:   encoding/gob
来源：http://dali.hysaishi.cn/Article/details/gtopxvcpwz.html

Ruby: Marshal.dump(obj)
来源：http://dali.shzxlz.cn/Article/details/gtjpoxqlor.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gtfcuhnzhb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtvrrlojgb.html

L. 网络请求
来源：http://dali.shuidangran.top/Article/details/gtzmzoyqvy.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtzyybmrtn.html

[L01] 发送 GET 请求
来源：http://dali.havefunace.top/Article/details/gtrpjeuaxy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.havefunace.top/Article/details/gtjxsrnqor.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258.top/Article/details/gtpdcpdhqu.html

JS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gtwlfedous.html

TS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gtjjogdpqz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yvedp.cn/Article/details/gtprmdfjzl.html

Go:   resp, err := http.Get(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtayvsirfs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fzhhl.top/Article/details/gttymzbvot.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscrmqivr.html

[L02] 发送 POST JSON
来源：http://dali.birdmap.top/Article/details/gtfllrmecg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtwirzzfdi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.snrcjt.cn/Article/details/gtkhquykbd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gtedncnrux.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gtubtlkgqd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhongyouzk.top/Article/details/gtkkmsrzsc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhengqikj.top/Article/details/gthbqghmzv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.redwolf501.top/Article/details/gtmqvzsedw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangdashe.top/Article/details/gtnxbrmyxv.html

[L03] 设置自定义请求头
来源：http://dali.kuanghao11.cn/Article/details/gtxdqmfywf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.9152youxi.cn/Article/details/gtrdchjfqx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgufenzy.top/Article/details/gtkuxoxhjx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqmdclcn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gtqymyaxgh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuanzx.com/Article/details/gtfbfrszmr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtswrvthbt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gotoacloud.top/Article/details/gtwqiqpnlb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gtjyhkasry.html

[L04] 设置超时
来源：http://dali.jlsjyb.cn/Article/details/gtfxiydqhb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aibaodan.cn/Article/details/gtnqualdgh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daxiang520.top/Article/details/gtdnepgfes.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gtozdykdvp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gthqokiajq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gteaduwkcm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yonumen.top/Article/details/gtbsbfuzii.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ehwqpu.com/Article/details/gtkektlrwx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guowangkeji.top/Article/details/gtgrktaglm.html

[L05] 上传文件（multipart）
来源：http://dali.bjfxy.top/Article/details/gtmbgatmcd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ybcxt.top/Article/details/gtdtppqxnu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.316326.xyz/Article/details/gtgtrgkgre.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gtkbgghnzv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gtyqdgmsss.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jyoumei.cn/Article/details/gtschzufan.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hongshengwenyu.top/Article/details/gtdmrrawmm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhoulong.xyz/Article/details/gtykxoyfrn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pycfn.com/Article/details/gtavtwqpyi.html

[L06] 解析响应为 JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtrokbrieg.html

Py:   resp.json()
来源：http://dali.hywenlv.cn/Article/details/gtgxnnfnth.html

PHP:  json_decode($body, true);
来源：http://dali.birdmap.top/Article/details/gtkfonpljy.html

JS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gtvjpgvacm.html

TS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gtebocsluq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtrcnhhont.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gtmbsmyofb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgfzy.top/Article/details/gtukczvljl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtkzjrzadj.html

[L07] 处理 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gtalvjhamp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shuidangran.top/Article/details/gtcqgailrz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gogol.net.cn/Article/details/gtuoubbjfw.html

JS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtgbjrjubg.html

TS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gtmzmcabpj.html

Java: resp.statusCode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzkvkwaxw.html

Go:   resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gtwhulualp.html

Ruby: resp.code.to_i
来源：http://dali.ppjwa.cn/Article/details/gtytcrilrk.html

C#:   (int)resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gtwyjedoxd.html

[L08] 并发请求多个地址
来源：http://dali.yonumen.top/Article/details/gtneyrqvwv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hfpthk.cn/Article/details/gtyavcvkhg.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuanzhike.top/Article/details/gtkrygsrng.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtlnqaqheg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gttsihdazs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenjidiqi.icu/Article/details/gtedpuioqd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigufen.top/Article/details/gtwsmdgqrp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yvedp.cn/Article/details/gtoywjlxzh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jyoumei.cn/Article/details/gtjnoxzxet.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtjxvtuqkc.html

M. 命令行 / 进程 / 环境
来源：http://dali.jyoumei.cn/Article/details/gtcdxostqq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtxenoiycd.html

[M01] 读取命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gtlwixdyxg.html

Py:   sys.argv[1:]
来源：http://dali.daxiang520.top/Article/details/gtqjxongna.html

PHP:  $argv;  $argc;
来源：http://dali.jiagoushi.top/Article/details/gtnwbharqs.html

JS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtjqvvivcj.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gtkgmjopni.html

Java: args 数组（main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gtahxbyggp.html

Go:   os.Args[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtsmollclb.html

Ruby: ARGV
来源：http://dali.cheryme.top/Article/details/gtmrdlvsmh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtknutwkbd.html

[M02] 读取环境变量
来源：http://dali.c1oappe.top/Article/details/gtgawojeol.html

Py:   os.environ.get("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtztelrzhr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyiwmbmoe.html

JS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gttiougqph.html

TS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gtuarvbtdr.html

Java: System.getenv("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtumikmsst.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.birdmap.top/Article/details/gtisrhopbn.html

Ruby: ENV["HOME"]
来源：http://dali.ybcxt.top/Article/details/gtseoeilzo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmojhdtmk.html

[M03] 执行外部命令
来源：http://dali.chenlongwang.top/Article/details/gtyqhpaqwd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgfzy.top/Article/details/gtbccwzruu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ivvv.top/Article/details/gtehdhlxwr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gtjgaaabbf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gtveydtpxq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.mhx1999.top/Article/details/gtnlfmbprq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhoulong.xyz/Article/details/gtprkhyoja.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.smart0.xyz/Article/details/gtgfzjbwiw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cheryme.top/Article/details/gtarxvvioc.html

[M04] 获取当前工作目录
来源：http://dali.feifeiyinyue.top/Article/details/gtsmmzevzs.html

Py:   os.getcwd()
来源：http://dali.mhx1999.top/Article/details/gtzhjpypkx.html

PHP:  getcwd();
来源：http://dali.chenlongwang.top/Article/details/gtwtonnzxx.html

JS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gtmifxtzyl.html

TS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gtmwqovnbn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yueranfly.top/Article/details/gtygfuvpld.html

Go:   os.Getwd()
来源：http://dali.9152youxi.cn/Article/details/gtbwugxomv.html

Ruby: Dir.pwd
来源：http://dali.haohaochexian.top/Article/details/gtjierffjp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgufenzy.top/Article/details/gtfuahnmft.html

[M05] 设置退出码
来源：http://dali.haohaochexian.top/Article/details/gtoelpyrdh.html

Py:   sys.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtcxvoyahs.html

PHP:  exit(1);
来源：http://dali.wangdashe.top/Article/details/gtjtqhefww.html

JS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtbmchgapy.html

TS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtwzecwbgn.html

Java: System.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtcekpnogt.html

Go:   os.Exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtnqmztjks.html

Ruby: exit 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbauqyjxy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.9152youxi.cn/Article/details/gtqupoyokr.html

[M06] 向标准错误输出
来源：http://dali.xuanzx.com/Article/details/gtfumcsqly.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xziqi.cn/Article/details/gtxlrfsbbj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gtytvkwjtf.html

JS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gtrvcduuqh.html

TS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gttduadojx.html

Java: System.err.println("err")
来源：http://dali.xylfe.cn/Article/details/gtrowzvbvx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.svipenyu.cn/Article/details/gthyfexdzo.html

Ruby: warn "err"
来源：http://dali.meibo888.top/Article/details/gtwpbugtuw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.smart0.xyz/Article/details/gtjujttjpl.html

[M07] 判断是否为主入口
来源：http://dali.gaohongyu789.top/Article/details/gtcpmfjzkd.html

Py:   if __name__ == "__main__":
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfczstafg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gotoacloud.top/Article/details/gtusjtcmxn.html

JS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gthpvqrepe.html

TS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gtdkuutixp.html

Java: public static void main(String[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gtzbprsqle.html

Go:   func main()
来源：http://dali.jianghu66.top/Article/details/gtehpkpzfz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cheryme.top/Article/details/gtutgfixjj.html

C#:   static void Main(string[] args)
来源：http://dali.zhongyouzk.top/Article/details/gtkygnmilo.html

[M08] 获取系统与运行时信息
来源：http://dali.yanxiufei.cn/Article/details/gthwyzvsbw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ybcxt.top/Article/details/gtdnftyyyo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tian-w.cn/Article/details/gtlypfbrjf.html

JS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gtpkbccypw.html

TS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gtmgtxfnip.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sysykeji.top/Article/details/gtepascqdl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tanke756.top/Article/details/gtncpktqvq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gtpwhqavva.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhongyouzk.top/Article/details/gtiaghbzva.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtopczuxsp.html

N. 数据结构与算法
来源：http://dali.hnxiangtu.top/Article/details/gtelkyfaod.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtxrrbxjbl.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdsxjqrwi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtekckrdch.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtshuolvmf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtxllylxdk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gthdzazuzq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gteyjknjat.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtwnfqzdvb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shuidangran.top/Article/details/gtpvewiroy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtewjxluxg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jyoumei.cn/Article/details/gtoqztfjey.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavtwmyhe.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzcugnym.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gtjvmmlpwb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtlhpsnigr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sysykeji.top/Article/details/gtmbboymyw.html

Go:   slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gtmrtnklzx.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gtiibhyrwr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yvedp.cn/Article/details/gtehtafwhs.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigufen.top/Article/details/gtrnxvczqq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yongpay.top/Article/details/gtwyliewni.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sxryk.cn/Article/details/gtqkkhtfmi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrjelnuw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gtluvcupzc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.haohaochexian.top/Article/details/gtalpedgyy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daxiang520.top/Article/details/gtnsydsfqw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hammf.cn/Article/details/gtjqhdkgip.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gogol.net.cn/Article/details/gthqmshmom.html

[N04] 斐波那契数列
来源：http://dali.guannengcc.top/Article/details/gtyupvyqgn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavgnnuxa.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtgpkjtigo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtkmfxtzcc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtqupdqiof.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gtrakitfsk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sxryk.cn/Article/details/gtlhlvjudz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyycszhyx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtymyyqaia.html

[N05] 最大公约数
来源：http://dali.mhx1999.top/Article/details/gttvzaihnp.html

Py:   math.gcd(a, b)
来源：http://dali.yongpay.top/Article/details/gtlsgeycrb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpyomfre.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gtnclqsemv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrywofltr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcbttlep.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tian-w.cn/Article/details/gtjgcmcdui.html

Ruby: a.gcd(b)
来源：http://dali.zhongyouzk.top/Article/details/gtzikftyuo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgufenzy.top/Article/details/gtzsznvngb.html

[N06] 判断回文字符串
来源：http://dali.zhoulong.xyz/Article/details/gtseufryzi.html

Py:   s == s[::-1]
来源：http://dali.yonumen.top/Article/details/gttuxttpnh.html

PHP:  $s === strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtobmvkutd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtbhunodrb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gteonejmke.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuanzx.com/Article/details/gttkboowas.html

Go:   // 双指针从两端比较
来源：http://dali.jqgfzy.top/Article/details/gtxbrwkddm.html

Ruby: s == s.reverse
来源：http://dali.yvedp.cn/Article/details/gtzfluhqhw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gtfymylhce.html

[N07] 两数之和（返回下标）
来源：http://dali.yangfankeji.com/Article/details/gtwptzmurc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hongshengwenyu.top/Article/details/gtyntsgamc.html


<!-- 参考信息 -->