代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnxiangtu.top/Article/details/gt2gaveqlfy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gt2kcdxxvnb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangdashe.top/Article/details/gt2kjmuxdjh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yongpay.top/Article/details/gt2muovheaq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgufenzy.top/Article/details/gt2kinqxbnr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tanke756.top/Article/details/gt2essqbhrb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shuidangran.top/Article/details/gt2uxnkhkml.html

[J10] 取今天 / 本月第一天
来源：http://dali.jianghu66.top/Article/details/gt2nmhwjdxs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daxiang520.top/Article/details/gt2ntnnqdgn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guowangkeji.top/Article/details/gt2bbwdckwe.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxinkj.top/Article/details/gt2iianibzd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zejqxpbk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnqzz.top/Article/details/gt2ofywdwrs.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuanzx.com/Article/details/gt2nkwywweg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aizwys.cn/Article/details/gt2hvjmqlvf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tianlin.xyz/Article/details/gt2ovvmgbxl.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2bdmqwvnz.html

K. JSON 与序列化
来源：http://dali.jqgufenzy.top/Article/details/gt2vtziidfy.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xpsbapbm.html

[K01] 对象转 JSON 字符串
来源：http://dali.yongpay.top/Article/details/gt2rpxgygkk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gt2vybkxrpg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gt2xvtsnkzh.html

JS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2ewivgauy.html

TS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2fijiuryp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gotoacloud.top/Article/details/gt2fwvhbsvz.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qcojkfrf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zycfv.cn/Article/details/gt2laibbdfn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2jnhhdeka.html

[K02] JSON 字符串转对象
来源：http://dali.sxryk.cn/Article/details/gt2iumjnagp.html

Py:   json.loads(s)
来源：http://dali.pycfn.com/Article/details/gt2lczxeokr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnxiangtu.top/Article/details/gt2dnratzlh.html

JS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gt2xaefovrw.html

TS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gt2dndfydal.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cheryme.top/Article/details/gt2ehnghhir.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gt2bbrabhvz.html

Ruby: JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mdmtfdpe.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cdnleiting.top/Article/details/gt2dhrbqndp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuanzhike.top/Article/details/gt2vzserhwi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gt2awlhvrqo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gt2hnrgdxao.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2dmqyqexk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2gjxvnqos.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2lkygdhyr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangdashe.top/Article/details/gt2zeptbtan.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.iojbl.cn/Article/details/gt2opzpcgmn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guowangkeji.top/Article/details/gt2wkbblzfm.html

[K04] 读取 JSON 文件
来源：http://dali.cucudq.cn/Article/details/gt2dmzvrlcz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cdnleiting.top/Article/details/gt2joljjaup.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cqqwz.cn/Article/details/gt2zyxrjnjg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gt2lcdkmzpk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2nbblfdyi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ykijccib.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gt2hmyhjlze.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2rxvwbojw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xinyue.icu/Article/details/gt2wrbcyrta.html

[K05] 深拷贝对象
来源：http://dali.sufxvd.cn/Article/details/gt2qytfqlkl.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2yqxhebcc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daxiang520.top/Article/details/gt2ljbcysne.html

JS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2uxywwcvq.html

TS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2uvpscesr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hywenlv.cn/Article/details/gt2orrrmeap.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hnqzz.top/Article/details/gt2wtdgntro.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenlongwang.top/Article/details/gt2fqyuegxu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.meibo888.top/Article/details/gt2bgunbibn.html

[K06] 解析 URL 查询串
来源：http://dali.yangfankeji.com/Article/details/gt2sfbddaqg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gt2bcwoalio.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gogol.net.cn/Article/details/gt2vtipprsj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rnkvpelb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tanke756.top/Article/details/gt2abolkujh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jyoumei.cn/Article/details/gt2uaqeulrp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gt2ikjrwiry.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gt2jscvvklf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gt2gfsjdhrl.html

[K07] 进制转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2spphonpq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2hnkreztf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigfzy.top/Article/details/gt2pypjelms.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2iebticir.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2mrklggvk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2wuerulwz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yanxiufei.cn/Article/details/gt2rjsvtvdd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jiagoushi.top/Article/details/gt2wpfhywvn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2ruwmralc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rfopxehx.html

Py:   pickle.dumps(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vdwlieui.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.c1oappe.top/Article/details/gt2mzulsqhf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gt2yaetnaet.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gt2bzemftne.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.svipenyu.cn/Article/details/gt2fkgothnh.html

Go:   encoding/gob
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ogkdjmxv.html

Ruby: Marshal.dump(obj)
来源：http://dali.ydzc1.top/Article/details/gt2xijagrip.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigfzy.top/Article/details/gt2mlnlhgqj.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2atcmugie.html

L. 网络请求
来源：http://dali.xuanzx.com/Article/details/gt2kdcyytof.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2iacrayzg.html

[L01] 发送 GET 请求
来源：http://dali.sweek.top/Article/details/gt2iutllqqg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.iojbl.cn/Article/details/gt2xcmdxckg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2xhabuvvd.html

JS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gt2zrsgexfu.html

TS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gt2xljhsyak.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shangyingyoupin.top/Article/details/gt2pmrchcrn.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenzaomai.com/Article/details/gt2hcbjdkly.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xinyue.icu/Article/details/gt2hsnsmioz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zycfv.cn/Article/details/gt2pghbdekn.html

[L02] 发送 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gt2riizugld.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mflfnaup.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.iojbl.cn/Article/details/gt2ohqrtvba.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gt2olkoeuqb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jianghu66.top/Article/details/gt2czknbqkh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgfzy.top/Article/details/gt2ddhphjkd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xylfe.cn/Article/details/gt2efapuzue.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ppjwa.cn/Article/details/gt2kqrsbbyd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ehwqpu.com/Article/details/gt2ncsqrjpm.html

[L03] 设置自定义请求头
来源：http://dali.redwolf501.top/Article/details/gt2mkeebdsw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yanxiufei.cn/Article/details/gt2ondruveq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hysaishi.cn/Article/details/gt2ldtfxokm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gt2abmspjqh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gt2amonfpit.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258.top/Article/details/gt2gkfzmlqy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gt2foabdngl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj202588.top/Article/details/gt2eiyxhzdv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gt2jcrcitmn.html

[L04] 设置超时
来源：http://dali.yj20258888.top/Article/details/gt2xbyvabef.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cashguo.top/Article/details/gt2tigzcnih.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258888.top/Article/details/gt2dlgriwot.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gt2zzveofng.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gt2oozktnga.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.quarkkingdee.top/Article/details/gt2lixhjjfj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhixingplan.top/Article/details/gt2paijyobg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenjidiqi.icu/Article/details/gt2goiwsiji.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgufenzy.top/Article/details/gt2tasaufbt.html

[L05] 上传文件（multipart）
来源：http://dali.meibo888.top/Article/details/gt2tebzimen.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ivvv.top/Article/details/gt2pxnickjd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dashuyun.cn/Article/details/gt2hikwhdyk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gt2oitdadzb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gt2dyufgkxs.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kbpsgnrx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zycfv.cn/Article/details/gt2lncmoqlq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gaohongyu789.top/Article/details/gt2nwrhelfp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2wwwwaavn.html

[L06] 解析响应为 JSON
来源：http://dali.meibo888.top/Article/details/gt2htolwmee.html

Py:   resp.json()
来源：http://dali.hysaishi.cn/Article/details/gt2bqnxtdmx.html

PHP:  json_decode($body, true);
来源：http://dali.sxryk.cn/Article/details/gt2vpslkrws.html

JS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gt2zgcnvray.html

TS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gt2hfdrceid.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gt2dngylgek.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jianghu66.top/Article/details/gt2jiffdnts.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhengqikj.top/Article/details/gt2tqfmlnaz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yonumen.top/Article/details/gt2qbzmmcuz.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gt2lmuszjqr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guowangkeji.top/Article/details/gt2munjrjyl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.aizwys.cn/Article/details/gt2ztiqpuna.html

JS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gt2zugnfsuv.html

TS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gt2vayxiiqo.html

Java: resp.statusCode()
来源：http://dali.hysaishi.cn/Article/details/gt2muhnlbnu.html

Go:   resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gt2hfhnmqqv.html

Ruby: resp.code.to_i
来源：http://dali.shuidangran.top/Article/details/gt2rqyximmp.html

C#:   (int)resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gt2abuxqrxe.html

[L08] 并发请求多个地址
来源：http://dali.yj202588.top/Article/details/gt2gdmtoocu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.smart0.xyz/Article/details/gt2shyjwehf.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgxnsbh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gt2akvclqsh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gt2wapzmyps.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.redwolf501.top/Article/details/gt2jluhdxwh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yonumen.top/Article/details/gt2ejoeaecw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.316326.xyz/Article/details/gt2ncgaspxo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guowangkeji.top/Article/details/gt2xqffhfcp.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2welgzfqv.html

M. 命令行 / 进程 / 环境
来源：http://dali.quarkkingdee.top/Article/details/gt2nolbgcbz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pfivmufj.html

[M01] 读取命令行参数
来源：http://dali.yuanzhike.top/Article/details/gt2njjyyjjq.html

Py:   sys.argv[1:]
来源：http://dali.yangfankeji.com/Article/details/gt2wqbdxsps.html

PHP:  $argv;  $argc;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eoaglfss.html

JS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sjpzrpdk.html

TS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gt2bwixjtkr.html

Java: args 数组（main 方法参数）
来源：http://dali.cheryme.top/Article/details/gt2spfhqzdd.html

Go:   os.Args[1:]
来源：http://dali.hnxiangtu.top/Article/details/gt2afrysiit.html

Ruby: ARGV
来源：http://dali.jlsjyb.cn/Article/details/gt2kczxiatu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gt2lqpkdrkg.html

[M02] 读取环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2ketdnbwk.html

Py:   os.environ.get("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gt2jlwmnjwu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gt2etvjylgn.html

JS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gt2vxbzlhzn.html

TS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gt2lsqxfllg.html

Java: System.getenv("HOME")
来源：http://dali.ydzc1.top/Article/details/gt2rgmzcfvd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.meibo888.top/Article/details/gt2cpfvqidv.html

Ruby: ENV["HOME"]
来源：http://dali.yongpay.top/Article/details/gt2cusvyezy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2slcwmees.html

[M03] 执行外部命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sxtecelw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoviuuby.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.iojbl.cn/Article/details/gt2gtszrnfd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gt2kpxkikcq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xpyzojps.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yanxiufei.cn/Article/details/gt2ouxlrujz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hongshengwenyu.top/Article/details/gt2abkmwpll.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.mhx1999.top/Article/details/gt2dotunzvd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxipnicf.html

[M04] 获取当前工作目录
来源：http://dali.birdmap.top/Article/details/gt2fozuzcct.html

Py:   os.getcwd()
来源：http://dali.cashguo.top/Article/details/gt2nnkswmvh.html

PHP:  getcwd();
来源：http://dali.hnxiangtu.top/Article/details/gt2pjxpurkc.html

JS:   process.cwd()
来源：http://dali.jianghu66.top/Article/details/gt2fjrmifqj.html

TS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gt2rvfpayha.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhixingplan.top/Article/details/gt2xgxzdswd.html

Go:   os.Getwd()
来源：http://dali.jyoumei.cn/Article/details/gt2mebprsiq.html

Ruby: Dir.pwd
来源：http://dali.gaohongyu789.top/Article/details/gt2huulaaod.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yueranfly.top/Article/details/gt2jzcstklo.html

[M05] 设置退出码
来源：http://dali.yj20258888.top/Article/details/gt2jkppcitk.html

Py:   sys.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2cgfgmvwf.html

PHP:  exit(1);
来源：http://dali.wangdashe.top/Article/details/gt2gtzguvyk.html

JS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2qgpipvla.html

TS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gt2huykqkzi.html

Java: System.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rxdvhloe.html

Go:   os.Exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2hpxzvebv.html

Ruby: exit 1
来源：http://dali.pycfn.com/Article/details/gt2gmppvcyv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ehwqpu.com/Article/details/gt2txlrgktp.html

[M06] 向标准错误输出
来源：http://dali.jinqigufen.top/Article/details/gt2inatxbkm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2psrpehsh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jyoumei.cn/Article/details/gt2oisbroys.html

JS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gt2sytoqufo.html

TS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gt2nbivehjh.html

Java: System.err.println("err")
来源：http://dali.ydzc1.top/Article/details/gt2tkmwbdco.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tianlin.xyz/Article/details/gt2srppdfyk.html

Ruby: warn "err"
来源：http://dali.yj202588.top/Article/details/gt2bidcmois.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2dbiqileh.html

[M07] 判断是否为主入口
来源：http://dali.hnqzz.top/Article/details/gt2rgveayic.html

Py:   if __name__ == "__main__":
来源：http://dali.meibo888.top/Article/details/gt2tmmsxtbl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenzaomai.com/Article/details/gt2cgrhbsdu.html

JS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gt2ybflhjlw.html

TS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gt2gowhwtiz.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zrszgnrn.html

Go:   func main()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2thjncanh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cdnleiting.top/Article/details/gt2gnqhxznd.html

C#:   static void Main(string[] args)
来源：http://dali.yueranfly.top/Article/details/gt2zkulgzoh.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tjiwartx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yvedp.cn/Article/details/gt2uwwdvuzz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cashguo.top/Article/details/gt2uwdyadtw.html

JS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vrqmtuiq.html

TS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nehdgfrc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jianghu66.top/Article/details/gt2qeayimac.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnqzz.top/Article/details/gt2mhzexagk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnqzz.top/Article/details/gt2jerlolpg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gt2zrrqjbvn.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2lwyydqnh.html

N. 数据结构与算法
来源：http://dali.cucudq.cn/Article/details/gt2yyieymvv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2boybvknb.html

[N01] 二分查找（有序数组）
来源：http://dali.wangshuangyany.cn/Article/details/gt2eklptsew.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gt2brwzdljd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fzhhl.top/Article/details/gt2fjfitvov.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gt2miruawnp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gt2dotkjnky.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2vpgscjwj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2fvqhfxal.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.meibo888.top/Article/details/gt2iextffiv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2heesgmdv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pengpengdd.cyou/Article/details/gt2xczulgah.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gt2jumdatfy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gt2houcjmut.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gt2xiiiaork.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gt2qvcprykc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ppjwa.cn/Article/details/gt2ktfomyiz.html

Go:   slices.Sort(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2txrgvxan.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gt2gqedbehb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aibaodan.cn/Article/details/gt2xjezomwa.html

[N03] 快速排序（分治示例）
来源：http://dali.jyoumei.cn/Article/details/gt2rbnlcrrk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhengqikj.top/Article/details/gt2uoesxzwn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shuidangran.top/Article/details/gt2fqxbznzg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gt2oiljggxo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gt2yibjkbzk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigufen.top/Article/details/gt2vxaqeedw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fhxgbwwc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hysaishi.cn/Article/details/gt2vuemclhs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2tablyyvz.html

[N04] 斐波那契数列
来源：http://dali.cashguo.top/Article/details/gt2uwdfltyw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gt2vabewfqb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ctxtsdgd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2jxuhocac.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gt2ybbmmuor.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gt2gcthcvnd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ppjwa.cn/Article/details/gt2apmwujjp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gt2woprfzxu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gt2bjjmcrxw.html

[N05] 最大公约数
来源：http://dali.gzhubu.top/Article/details/gt2mammhblw.html

Py:   math.gcd(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nxlpyrjn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guowangkeji.top/Article/details/gt2lwfxchlq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zisswruz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fzhhl.top/Article/details/gt2apvpduoa.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.birdmap.top/Article/details/gt2ozrildpq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ivvv.top/Article/details/gt2lyssmncn.html

Ruby: a.gcd(b)
来源：http://dali.sweek.top/Article/details/gt2zpyiukde.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.meibo888.top/Article/details/gt2ojtmbeth.html

[N06] 判断回文字符串
来源：http://dali.xylfe.cn/Article/details/gt2wguqffan.html

Py:   s == s[::-1]
来源：http://dali.cheryme.top/Article/details/gt2iepqcvbf.html

PHP:  $s === strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gt2xounojex.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gt2jiwxfson.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gt2cbadysxw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuanzhike.top/Article/details/gt2pbemuhdl.html

Go:   // 双指针从两端比较
来源：http://dali.fzhhl.top/Article/details/gt2sajskkph.html

Ruby: s == s.reverse
来源：http://dali.jqgfzy.top/Article/details/gt2agbhyikv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gt2myrdfwuo.html

[N07] 两数之和（返回下标）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iozqgjyw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gzhubu.top/Article/details/gt2ztghkpxy.html


<!-- 参考信息 -->