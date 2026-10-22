代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtdzdjjnza.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.9152youxi.cn/Article/details/gtbxvbpyrm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sweek.top/Article/details/gtjtotleko.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtagdustfs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtpthbwddm.html

[J08] 提取年月日与星期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgbsxvbp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenzaomai.com/Article/details/gtkzpsabad.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.haohaochexian.top/Article/details/gthdtyybsa.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hfpthk.cn/Article/details/gtraxwqzek.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hongshengwenyu.top/Article/details/gtjtreeais.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258888.top/Article/details/gtgnuupkvp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ivvv.top/Article/details/gtwckvlsqo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sufxvd.cn/Article/details/gtjshcqayq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hongshengwenyu.top/Article/details/gtqmfhppmf.html

[J09] 时区处理
来源：http://dali.nwbrower.top/Article/details/gtgwgsfuef.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenjidiqi.icu/Article/details/gtouhofhid.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnlsovjq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gtnewbflyp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gtmooigbyr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yvedp.cn/Article/details/gthxclukck.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.birdmap.top/Article/details/gtgwbffzuc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gtephzqtwr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xinyue.icu/Article/details/gtxzigmopu.html

[J10] 取今天 / 本月第一天
来源：http://dali.jianghu66.top/Article/details/gtudamjzdq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shangyingyoupin.top/Article/details/gtpswufxcd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cheryme.top/Article/details/gtpfwgkiey.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sufxvd.cn/Article/details/gtfupmylyy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtyybpnahf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yangfankeji.com/Article/details/gtzwjiglxl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhongyouzk.top/Article/details/gtdoosgymj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ybcxt.top/Article/details/gthzpocosv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.andypj.xyz/Article/details/gtzktpfhag.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtdpimsfsx.html

K. JSON 与序列化
来源：http://dali.cheryme.top/Article/details/gtvivitokf.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtsslgagla.html

[K01] 对象转 JSON 字符串
来源：http://dali.yanxiufei.cn/Article/details/gtuncenibb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtbdsiwbnu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gtjffklcph.html

JS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gtwhohzave.html

TS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gtuqswlkgs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hysaishi.cn/Article/details/gtcdtybiok.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtzwqjnbyl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hammf.cn/Article/details/gttjfynior.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jianghu66.top/Article/details/gtyrolapks.html

[K02] JSON 字符串转对象
来源：http://dali.chenzaomai.com/Article/details/gtcdedrgxg.html

Py:   json.loads(s)
来源：http://dali.jyoumei.cn/Article/details/gtlmzinjvj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cashguo.top/Article/details/gtdgjblfzw.html

JS:   JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gtbxtmcovm.html

TS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtcrcraqqk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuxming.cn/Article/details/gtyepwkxii.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gtdwqfojdo.html

Ruby: JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtwkayihkm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.smart0.xyz/Article/details/gtshqdwfrs.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.birdmap.top/Article/details/gtbjnhobae.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gtxbwzakqd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gtyiuehzxc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gtpnivmtav.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gtrbmjkxls.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gotoacloud.top/Article/details/gtgitgnuyg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.feifeiyinyue.top/Article/details/gtrwjzczfi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.9152youxi.cn/Article/details/gtztbhgpcp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.kuanghao11.cn/Article/details/gtxejzuwrn.html

[K04] 读取 JSON 文件
来源：http://dali.zhixingplan.top/Article/details/gtouyhjeoq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hnqzz.top/Article/details/gthgucqoqu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.havefunace.top/Article/details/gtcrbhmwns.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gtkphyhifk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gtdyibdumz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sxryk.cn/Article/details/gttkcotvqk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gtvknmfaoc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gtmlhcbske.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gtqaygbmss.html

[K05] 深拷贝对象
来源：http://dali.cheryme.top/Article/details/gtoepuepoh.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuanzx.com/Article/details/gthbekvxor.html

PHP:  unserialize(serialize($obj));
来源：http://dali.haohaochexian.top/Article/details/gtyalwcphf.html

JS:   structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtftirhdrt.html

TS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gtuyekvxqm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgfzy.top/Article/details/gtvoxpyxtx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ppjwa.cn/Article/details/gtwzwhyete.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.bjfxy.top/Article/details/gtaifzpgmz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.c1oappe.top/Article/details/gtgdwbckkv.html

[K06] 解析 URL 查询串
来源：http://dali.xuetiantiany.cn/Article/details/gtuoakyenk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdhqnlpd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxuanxn.top/Article/details/gtwmbyruuq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gtblawqyux.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gtvollnkyg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gtzaynumtu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtlcjgiszr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtqeqgmbdc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtznletgck.html

[K07] 进制转换
来源：http://dali.gotoacloud.top/Article/details/gtoydrlpsy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtselwckts.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gaohongyu789.top/Article/details/gtpedyxjdj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtqbshmymg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtsobbrpot.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtkkqnqbny.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenjidiqi.icu/Article/details/gtlpxbcgjv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zdqjudy.top/Article/details/gthyewzyeq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtwzlphgcb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xinyue.icu/Article/details/gtooacxuiz.html

Py:   pickle.dumps(obj)
来源：http://dali.snrcjt.cn/Article/details/gtrpybtleg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aizwys.cn/Article/details/gtlzufhmjj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gthlbpmczi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gtupseiehm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.smart0.xyz/Article/details/gtmuvnugaj.html

Go:   encoding/gob
来源：http://dali.kuanghao11.cn/Article/details/gtqykkapks.html

Ruby: Marshal.dump(obj)
来源：http://dali.shuidangran.top/Article/details/gtgadxcwyl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmxexham.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtpabptdka.html

L. 网络请求
来源：http://dali.xylfe.cn/Article/details/gtrmxwctri.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtmzkcrgfv.html

[L01] 发送 GET 请求
来源：http://dali.ivvv.top/Article/details/gtwdnhuzzo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yuanzhike.top/Article/details/gtvfgbrxkd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.redwolf501.top/Article/details/gtvyxffzhm.html

JS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gtmfnwucsi.html

TS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gtmjzdxoza.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tian-w.cn/Article/details/gtsgasbrrt.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigufen.top/Article/details/gtzndoneyz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgfzy.top/Article/details/gtabjjsxit.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aizwys.cn/Article/details/gtqazeygzv.html

[L02] 发送 POST JSON
来源：http://dali.iojbl.cn/Article/details/gtnzqdabac.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yonumen.top/Article/details/gtivzlxouj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.andypj.xyz/Article/details/gtyurtqkrr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtqyxqcrcz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gtcruepsns.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ivvv.top/Article/details/gtaqevkdsk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.snrcjt.cn/Article/details/gtzwwcaeqa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.meibo888.top/Article/details/gtzylasjut.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj20258.top/Article/details/gtwfswqarg.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gtjwcvaefp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dashuyun.cn/Article/details/gtrubrlvpq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gzhubu.top/Article/details/gtmhpismmg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gtzuibtgfs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gtwnwidegy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cheryme.top/Article/details/gtmyjuqyts.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gtvxxjotwl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gogol.net.cn/Article/details/gteijxhoqt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gtdokbutem.html

[L04] 设置超时
来源：http://dali.cqqwz.cn/Article/details/gtmcrginrg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hongshengwenyu.top/Article/details/gtnrehnhwt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhoulong.xyz/Article/details/gtrhrgigdx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtneszwscz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gtcknqgaxg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fengsongda.top/Article/details/gtfdtugtpc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sysykeji.top/Article/details/gtqhevyarh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.feifeiyinyue.top/Article/details/gtjcnbwdtk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hongshengwenyu.top/Article/details/gtglrowvbj.html

[L05] 上传文件（multipart）
来源：http://dali.fengsongda.top/Article/details/gtarzjxgzf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258888.top/Article/details/gtphvtsyew.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuanzx.com/Article/details/gthdahivlr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gtfqyldhbs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaquzvntt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ybcxt.top/Article/details/gtltylmiqw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.vqdsnc.cn/Article/details/gtwhleygqs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xylfe.cn/Article/details/gtqqovydha.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.birdmap.top/Article/details/gtmzslcmde.html

[L06] 解析响应为 JSON
来源：http://dali.yuxming.cn/Article/details/gtqaahbsep.html

Py:   resp.json()
来源：http://dali.0kj1m.cn/Article/details/gtavwajsmj.html

PHP:  json_decode($body, true);
来源：http://dali.jianghu66.top/Article/details/gtozavtkug.html

JS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtewtdrewp.html

TS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzxjodgd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yvedp.cn/Article/details/gthhjvuwwd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.kuanghao11.cn/Article/details/gtmapfizfs.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gogol.net.cn/Article/details/gtkxbpujci.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ppjwa.cn/Article/details/gthiupinaw.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtiseedfhd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hongshengwenyu.top/Article/details/gtghorkwme.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxuanxn.top/Article/details/gthbefzxev.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpioouup.html

TS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gtyftknnzw.html

Java: resp.statusCode()
来源：http://dali.hfpthk.cn/Article/details/gtrtnmtesg.html

Go:   resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gtyozlkugf.html

Ruby: resp.code.to_i
来源：http://dali.yj202588.top/Article/details/gtaksflvxd.html

C#:   (int)resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gtsxwakuqi.html

[L08] 并发请求多个地址
来源：http://dali.hongshengwenyu.top/Article/details/gtvjowzior.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ybcxt.top/Article/details/gtufdsbgpb.html

PHP:  curl_multi_init() 系列
来源：http://dali.jyoumei.cn/Article/details/gtqmcqmgyn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gtcimqlvhf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtpkasbqpr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fzhhl.top/Article/details/gtxtieqgcn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sxryk.cn/Article/details/gtftzyfjyk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tianlin.xyz/Article/details/gtgzxtrpww.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hammf.cn/Article/details/gtajfyimcm.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtoautqlle.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxuanxn.top/Article/details/gtazkdwcfh.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gttmiiwjvn.html

[M01] 读取命令行参数
来源：http://dali.yanxiufei.cn/Article/details/gtglkvsxno.html

Py:   sys.argv[1:]
来源：http://dali.yuxming.cn/Article/details/gteqknkjfy.html

PHP:  $argv;  $argc;
来源：http://dali.jqgufenzy.top/Article/details/gtnxdswknp.html

JS:   process.argv.slice(2)
来源：http://dali.yueranfly.top/Article/details/gtdunwzjgs.html

TS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gtnxtosvqn.html

Java: args 数组（main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtfivtiuyr.html

Go:   os.Args[1:]
来源：http://dali.jqgfzy.top/Article/details/gtxcrerdvy.html

Ruby: ARGV
来源：http://dali.0kj1m.cn/Article/details/gtjqvrjqiz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj202588.top/Article/details/gteiuwxzbw.html

[M02] 读取环境变量
来源：http://dali.tanke756.top/Article/details/gtdyvylmtn.html

Py:   os.environ.get("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtveloskcr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gtjsjswyxo.html

JS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gtywvdxmxn.html

TS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtffsmmbjq.html

Java: System.getenv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gteciwcmta.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtlklwtpmn.html

Ruby: ENV["HOME"]
来源：http://dali.sxryk.cn/Article/details/gtmckjlxoh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtinyvosbl.html

[M03] 执行外部命令
来源：http://dali.yj202588.top/Article/details/gtaxqfaufc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtskrouozj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.bjfxy.top/Article/details/gtyazapwcb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gtwpptvfzu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gtvdgjevtg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fzhhl.top/Article/details/gtdffvakxe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yueranfly.top/Article/details/gtrlmzdsci.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenlongwang.top/Article/details/gtgyltmitf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shzxlz.cn/Article/details/gtyzvzeydw.html

[M04] 获取当前工作目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtxtdxkrbf.html

Py:   os.getcwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgqiyaux.html

PHP:  getcwd();
来源：http://dali.pycfn.com/Article/details/gtrqnvcely.html

JS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gttrsiuwrs.html

TS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gtvumfmazu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gzhubu.top/Article/details/gtbosbiiyv.html

Go:   os.Getwd()
来源：http://dali.jlsjyb.cn/Article/details/gtjvxxqtan.html

Ruby: Dir.pwd
来源：http://dali.zdqjudy.top/Article/details/gtyajdkwbs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cheryme.top/Article/details/gtxklfyutb.html

[M05] 设置退出码
来源：http://dali.gotoacloud.top/Article/details/gtjkwcictu.html

Py:   sys.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtlbelazlv.html

PHP:  exit(1);
来源：http://dali.tianlin.xyz/Article/details/gtbbeunqow.html

JS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtiwqfzrpd.html

TS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtunvyyqao.html

Java: System.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtmidbuksy.html

Go:   os.Exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtwlybrbbv.html

Ruby: exit 1
来源：http://dali.aizwys.cn/Article/details/gtmuskpcqq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjvnxzds.html

[M06] 向标准错误输出
来源：http://dali.nanxuanxn.top/Article/details/gthbfwzxge.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gtprvlvgra.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sweek.top/Article/details/gtfqstvuqz.html

JS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gtoogljovb.html

TS:   console.error("err")
来源：http://dali.gotoacloud.top/Article/details/gthajsljqg.html

Java: System.err.println("err")
来源：http://dali.cashguo.top/Article/details/gtbrvorfsa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yongpay.top/Article/details/gteuprtppd.html

Ruby: warn "err"
来源：http://dali.zhixingplan.top/Article/details/gtfdccluhy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.c1oappe.top/Article/details/gtackjvvbb.html

[M07] 判断是否为主入口
来源：http://dali.yangfankeji.com/Article/details/gtrmyyenjc.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxinkj.top/Article/details/gtkvjqroao.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yonumen.top/Article/details/gtgcfokdtq.html

JS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gtppvtpepg.html

TS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gtwdtatcpg.html

Java: public static void main(String[] args)
来源：http://dali.mhx1999.top/Article/details/gtdkgeqiwp.html

Go:   func main()
来源：http://dali.zhiwuduotai.top/Article/details/gtrghqxwqf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgufenzy.top/Article/details/gtfrygypwb.html

C#:   static void Main(string[] args)
来源：http://dali.gzhubu.top/Article/details/gtldlrggcf.html

[M08] 获取系统与运行时信息
来源：http://dali.yuxming.cn/Article/details/gtjvtljkbr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangshuangyany.cn/Article/details/gttrvbsprq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pycfn.com/Article/details/gtznbvxbck.html

JS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gtrrvymwtf.html

TS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gtqihljvzq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigufen.top/Article/details/gtvlpcfkgw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yueranfly.top/Article/details/gtenpiucqb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yonumen.top/Article/details/gtirckihka.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.andypj.xyz/Article/details/gtzxjbjmvl.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtavrphsau.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gtybxdnuwg.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gthqmmwtas.html

[N01] 二分查找（有序数组）
来源：http://dali.pengpengdd.cyou/Article/details/gtsmtzhwyi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gttszskpox.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtbapzlxxe.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gttpurhcay.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gtoycuawkk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtpnyogcfn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sweek.top/Article/details/gtopzidkzj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknhtkpcs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtgofmuipr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhiwuduotai.top/Article/details/gtrndhzfyo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gthmrdbrgc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtrrneftji.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gthvxnxufu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gtuwtxafww.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aizwys.cn/Article/details/gtbmezifwf.html

Go:   slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtqzwcgyky.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gtdbgpkryo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gotoacloud.top/Article/details/gtcffkowbb.html

[N03] 快速排序（分治示例）
来源：http://dali.tanke756.top/Article/details/gtvmamesmx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.c1oappe.top/Article/details/gtfjkhprjb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnqzz.top/Article/details/gtxsrubssl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtaericfyn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gtanwajzdh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fzhhl.top/Article/details/gtoitapeek.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fzhhl.top/Article/details/gtvkdvusrc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cdnleiting.top/Article/details/gttcdtwzjj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shuidangran.top/Article/details/gthygxbtaf.html

[N04] 斐波那契数列
来源：http://dali.andypj.xyz/Article/details/gtcwaqzjlc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gtausqfmgb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.havefunace.top/Article/details/gtutriogeg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtwfplkdjp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtekigslmw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.andypj.xyz/Article/details/gtggqmddbm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxuanxn.top/Article/details/gttmregjtg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gtdrqmkbey.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtypacweed.html

[N05] 最大公约数
来源：http://dali.xuetiantiany.cn/Article/details/gtomhmsnvf.html

Py:   math.gcd(a, b)
来源：http://dali.ivvv.top/Article/details/gtpqruvotg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.316326.xyz/Article/details/gtkcfcolft.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwfzwtnaq.html


<!-- 参考信息 -->