代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtjwbccyka.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yanxiufei.cn/Article/details/gtwabcrdjc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gtlfbfmepo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfilzqqzw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtuxviqaap.html

[J08] 提取年月日与星期
来源：http://dali.iojbl.cn/Article/details/gtvmdvhmtk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cdnleiting.top/Article/details/gtwaasgxgl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gtyakdkmtu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hammf.cn/Article/details/gtnocbxbdp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gtfmcjvrmf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dashuyun.cn/Article/details/gtfrosbmtd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ivvv.top/Article/details/gtdlxuksoy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuanzx.com/Article/details/gtccazhloc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ppjwa.cn/Article/details/gtyixbzjni.html

[J09] 时区处理
来源：http://dali.zhixingplan.top/Article/details/gttugeauhy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gogol.net.cn/Article/details/gthxbhmhqi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258.top/Article/details/gtsylcsxre.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gtebixdvso.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gtdrcwjxsd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hongshengwenyu.top/Article/details/gtkzjnjzfy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.wangdashe.top/Article/details/gtkniyxhso.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cqqwz.cn/Article/details/gtevcelkvv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gaohongyu789.top/Article/details/gterbbtfct.html

[J10] 取今天 / 本月第一天
来源：http://dali.pycfn.com/Article/details/gtvltqcjom.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvozhexha.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.c1oappe.top/Article/details/gtekxrnntp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtjhxdfncr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pycfn.com/Article/details/gtivdiwqtk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shuidangran.top/Article/details/gtcjrlugxa.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xylfe.cn/Article/details/gtabpdhvgc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shanyushiyangtech.top/Article/details/gtjdyhjqfv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fzhhl.top/Article/details/gtxgnbmhbg.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtcnwzwgpa.html

K. JSON 与序列化
来源：http://dali.bjfxy.top/Article/details/gthqqbvuwq.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxruconw.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtvqruuwhc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmssmuvwb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gtozyrlxqd.html

JS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtpecabfac.html

TS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gtkgzrxgju.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.birdmap.top/Article/details/gtiguxxdlk.html

Go:   json.Marshal(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvioktbvd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuetiantiany.cn/Article/details/gtjwlnoogc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yangfankeji.com/Article/details/gthspwmsmb.html

[K02] JSON 字符串转对象
来源：http://dali.yueranfly.top/Article/details/gtveagmfpg.html

Py:   json.loads(s)
来源：http://dali.xziqi.cn/Article/details/gtsdeggsxo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shuidangran.top/Article/details/gtlukkfuai.html

JS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gtepfxlulk.html

TS:   JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gtexcqnbkj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtspcfrein.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gtcnqlbhds.html

Ruby: JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtvjtnzgmp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xylfe.cn/Article/details/gtninglxzb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fzhhl.top/Article/details/gtmtqctnxz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.kuanghao11.cn/Article/details/gttcsjinwm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gtkowsmjsv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gtxeevpmne.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gtdwhuevwi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.smart0.xyz/Article/details/gtfoxkbdoy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hfpthk.cn/Article/details/gthxavjdaf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ivvv.top/Article/details/gtyxgenbll.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gtdqfpmoun.html

[K04] 读取 JSON 文件
来源：http://dali.yvedp.cn/Article/details/gtaoaatlkw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cashguo.top/Article/details/gtsaeeobui.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.fzhhl.top/Article/details/gtwjqeoihx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gtlcqjvbhe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtuumybvls.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gtauhfcnew.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gtrblblleo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gtggwkvnto.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gtuhsqygyc.html

[K05] 深拷贝对象
来源：http://dali.shzxlz.cn/Article/details/gtgmcwuohh.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj202588.top/Article/details/gtycyzgogy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ydzc1.top/Article/details/gtqvrmpnnm.html

JS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzpnirol.html

TS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gttulnmogr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yonumen.top/Article/details/gtnrjkujcf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ivvv.top/Article/details/gtstewqfiv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuetiantiany.cn/Article/details/gtieqvooie.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fengsongda.top/Article/details/gtnawcdcnn.html

[K06] 解析 URL 查询串
来源：http://dali.jinqigufen.top/Article/details/gthdvdimre.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gtzaprtwne.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenzaomai.com/Article/details/gtlgnxitmw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gtvfcooxzc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gtowsxexot.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gtixvxsyuz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtmubivuej.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtaxjdbphs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtxbbrichl.html

[K07] 进制转换
来源：http://dali.iojbl.cn/Article/details/gtghpresaf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtgbufrdbg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shangyingyoupin.top/Article/details/gtiqpfinkn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gthhpavnyl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gthjqcisrv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigkrrviq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yvedp.cn/Article/details/gtybgkoarj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangdashe.top/Article/details/gtbrkzwbac.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gttykckeri.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pycfn.com/Article/details/gtrkofndkk.html

Py:   pickle.dumps(obj)
来源：http://dali.andypj.xyz/Article/details/gtexxiomie.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sufxvd.cn/Article/details/gtjlkqeuae.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gtzfxdzkrw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gtxmaajmwj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gtieubwqjg.html

Go:   encoding/gob
来源：http://dali.shzxlz.cn/Article/details/gtqgeymfnh.html

Ruby: Marshal.dump(obj)
来源：http://dali.hammf.cn/Article/details/gtzpmqrgcf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gtjlfdwlit.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtbwtzuglm.html

L. 网络请求
来源：http://dali.316326.xyz/Article/details/gtnbrqndyf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtoawimxki.html

[L01] 发送 GET 请求
来源：http://dali.guannengcc.top/Article/details/gtawzbepxb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenzaomai.com/Article/details/gtfojcjtpr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuxming.cn/Article/details/gtldjwuwut.html

JS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gtpucnzgat.html

TS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gttbjbehyb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.andypj.xyz/Article/details/gtcqlitdny.html

Go:   resp, err := http.Get(url)
来源：http://dali.redwolf501.top/Article/details/gtnunkqyij.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yueranfly.top/Article/details/gtfwjcbekn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tianlin.xyz/Article/details/gtojrsagro.html

[L02] 发送 POST JSON
来源：http://dali.jianghu66.top/Article/details/gtyaadfxez.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhongyouzk.top/Article/details/gtejixyxgy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.mhx1999.top/Article/details/gtmkvqdqmn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gtsosmjgfe.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gtkskftumn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cashguo.top/Article/details/gttdvmkrsl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daria6918.cn/Article/details/gtbfneglnd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cqqwz.cn/Article/details/gtrbludcve.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhongyouzk.top/Article/details/gtgjytpebh.html

[L03] 设置自定义请求头
来源：http://dali.kuanghao11.cn/Article/details/gttdgkrysf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuetiantiany.cn/Article/details/gtwydezyha.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fengsongda.top/Article/details/gtzilqtttr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gteiogkezd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gtbdgektvj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhongyouzk.top/Article/details/gtkrftilka.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosmjzjzl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fengsongda.top/Article/details/gtyitaekog.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gtjtqswzst.html

[L04] 设置超时
来源：http://dali.smart0.xyz/Article/details/gtwvharenl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhengqikj.top/Article/details/gtfujuzsjd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yongpay.top/Article/details/gtgzgtfztu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gtnsazpnru.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gtdgxoyagz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sweek.top/Article/details/gttdpskzif.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tianlin.xyz/Article/details/gtmpwvsdcr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nwbrower.top/Article/details/gtkqfcukmb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daria6918.cn/Article/details/gteimmiqdc.html

[L05] 上传文件（multipart）
来源：http://dali.gotoacloud.top/Article/details/gtemkvhtgu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nwbrower.top/Article/details/gthgbuamsl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gaohongyu789.top/Article/details/gtscswvvrl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sxryk.cn/Article/details/gttjkoofiz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gtbekfcrqj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelesvpfs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shuidangran.top/Article/details/gtkkufkylq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cashguo.top/Article/details/gtaeyhdpfx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtmsxtabxl.html

[L06] 解析响应为 JSON
来源：http://dali.gzhubu.top/Article/details/gtmgeirtga.html

Py:   resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtosyogfej.html

PHP:  json_decode($body, true);
来源：http://dali.quarkkingdee.top/Article/details/gtgsgpzhxv.html

JS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gtehagnert.html

TS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtgyqksore.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fengsongda.top/Article/details/gtmdynmfnn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.iojbl.cn/Article/details/gtnnzyzizg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnivgnzgu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenzaomai.com/Article/details/gtlnfgdcfj.html

[L07] 处理 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gtkldumaxc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhixingplan.top/Article/details/gtzagcogxb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgufenzy.top/Article/details/gtdjkyhbtz.html

JS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gtpppreyod.html

TS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gttffhczhy.html

Java: resp.statusCode()
来源：http://dali.zhengqikj.top/Article/details/gtyoompmkn.html

Go:   resp.StatusCode
来源：http://dali.sufxvd.cn/Article/details/gtubbwglxd.html

Ruby: resp.code.to_i
来源：http://dali.guowangkeji.top/Article/details/gthzssfsya.html

C#:   (int)resp.StatusCode
来源：http://dali.zhiwuduotai.top/Article/details/gtfijsfwds.html

[L08] 并发请求多个地址
来源：http://dali.sxryk.cn/Article/details/gtsodqiqua.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.meibo888.top/Article/details/gtkghwelmw.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuanzhike.top/Article/details/gtfriqfzfu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gtrpxgtfao.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gtsxfxwejo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ehwqpu.com/Article/details/gtzvodcgse.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.havefunace.top/Article/details/gtywavbkwx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pycfn.com/Article/details/gtyeylnobu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtudttxrem.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtujlyybnr.html

M. 命令行 / 进程 / 环境
来源：http://dali.daria6918.cn/Article/details/gtwsnoafzj.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtdtednhuq.html

[M01] 读取命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gthzyzqyfp.html

Py:   sys.argv[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvthbcex.html

PHP:  $argv;  $argc;
来源：http://dali.gzhubu.top/Article/details/gteklwgqmn.html

JS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyagvjzy.html

TS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gtvfqpweyi.html

Java: args 数组（main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gtpckpjcbd.html

Go:   os.Args[1:]
来源：http://dali.xylfe.cn/Article/details/gteduvwqrq.html

Ruby: ARGV
来源：http://dali.chenjidiqi.icu/Article/details/gtudincfsk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sweek.top/Article/details/gtshbolcgr.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gtfovcdvkg.html

Py:   os.environ.get("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtaocfdefd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gtvlzvcpzo.html

JS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtaopxjiyw.html

TS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gttpdvudqp.html

Java: System.getenv("HOME")
来源：http://dali.yueranfly.top/Article/details/gtnqgkgtdo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtfuydpnzy.html

Ruby: ENV["HOME"]
来源：http://dali.xziqi.cn/Article/details/gtnxeyvycq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guannengcc.top/Article/details/gthcclgynj.html

[M03] 执行外部命令
来源：http://dali.ehwqpu.com/Article/details/gtriqnsgsk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangdashe.top/Article/details/gtpthfibsx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gthkxhbsde.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gtxhieakaw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gtrkrqmeio.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cheryme.top/Article/details/gtktapqiof.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenjidiqi.icu/Article/details/gtmnkvkpxx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ehwqpu.com/Article/details/gtdyzwhbgx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yanxiufei.cn/Article/details/gtlohpspzh.html

[M04] 获取当前工作目录
来源：http://dali.aizwys.cn/Article/details/gtezszpbgo.html

Py:   os.getcwd()
来源：http://dali.yueranfly.top/Article/details/gttpdfafmf.html

PHP:  getcwd();
来源：http://dali.yj20258888.top/Article/details/gtrtpizopu.html

JS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gtvdwsnujq.html

TS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gtupgybvmk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigfzy.top/Article/details/gtcnldqydb.html

Go:   os.Getwd()
来源：http://dali.yj20258.top/Article/details/gtthtamkcr.html

Ruby: Dir.pwd
来源：http://dali.jianghu66.top/Article/details/gtmhjdgbqc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.redwolf501.top/Article/details/gtfcobndli.html

[M05] 设置退出码
来源：http://dali.daxiang520.top/Article/details/gtxmbulbdl.html

Py:   sys.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtrsfaqvpv.html

PHP:  exit(1);
来源：http://dali.nanxinkj.top/Article/details/gtogjaxujm.html

JS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtjrawsnoj.html

TS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtewqqprbj.html

Java: System.exit(1)
来源：http://dali.316326.xyz/Article/details/gtrfysgopq.html

Go:   os.Exit(1)
来源：http://dali.xinyue.icu/Article/details/gtndplxrtt.html

Ruby: exit 1
来源：http://dali.hnqzz.top/Article/details/gtkjtspofg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.9152youxi.cn/Article/details/gtebzaiexm.html

[M06] 向标准错误输出
来源：http://dali.jqgufenzy.top/Article/details/gtnkurgsxg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj202588.top/Article/details/gtaldhdlxq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.kuanghao11.cn/Article/details/gtdrcvfemh.html

JS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtqfinbkib.html

TS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtqugqqjai.html

Java: System.err.println("err")
来源：http://dali.ivvv.top/Article/details/gtwjalhjig.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxinkj.top/Article/details/gtcgavhtjs.html

Ruby: warn "err"
来源：http://dali.shangyingyoupin.top/Article/details/gtswfrlkav.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ivvv.top/Article/details/gtvxmmgern.html

[M07] 判断是否为主入口
来源：http://dali.yvedp.cn/Article/details/gtdybfbmdm.html

Py:   if __name__ == "__main__":
来源：http://dali.daria6918.cn/Article/details/gtmgerwocm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhiwuduotai.top/Article/details/gtapkbovpd.html

JS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gtxggqszpl.html

TS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gtzqdrkusk.html

Java: public static void main(String[] args)
来源：http://dali.redwolf501.top/Article/details/gtcqzfppwh.html

Go:   func main()
来源：http://dali.hnxiangtu.top/Article/details/gtueehzoas.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxuanxn.top/Article/details/gtjrxjislw.html

C#:   static void Main(string[] args)
来源：http://dali.hammf.cn/Article/details/gtqunxnwrc.html

[M08] 获取系统与运行时信息
来源：http://dali.xylfe.cn/Article/details/gtmcfyplyl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guowangkeji.top/Article/details/gtexvlmygm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dashuyun.cn/Article/details/gtljtbesxz.html

JS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtzuwzcmhd.html

TS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtdzqhhvuq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hfpthk.cn/Article/details/gtordnfatl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guowangkeji.top/Article/details/gtdotzhiwf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.c1oappe.top/Article/details/gtguvmmpbh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258888.top/Article/details/gticxwkcgc.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtaqjqoliy.html

N. 数据结构与算法
来源：http://dali.yangfankeji.com/Article/details/gtfixgzvgz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtfezqbryn.html

[N01] 二分查找（有序数组）
来源：http://dali.yj202588.top/Article/details/gtybmhpoll.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gteypaiwan.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daxiang520.top/Article/details/gtcmdbhmwn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gtetpjutwy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gtixwrxcff.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtlamwynnf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtaaoldfxq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangshuangyany.cn/Article/details/gtxqyzrdfz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtxvwnyeqr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258888.top/Article/details/gtdcrnunpa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gtcjazczdq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtrhkhuwbl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtwinjqfsl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gtzcmvowgm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuanzhike.top/Article/details/gtsmeeomlz.html

Go:   slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gtfzmgmoks.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gtfgpxirzv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenzaomai.com/Article/details/gthmcrybwm.html

[N03] 快速排序（分治示例）
来源：http://dali.yongpay.top/Article/details/gtaxtwlkvv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gtflxxtxit.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pycfn.com/Article/details/gtgxoioqmn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gtwvnikzcv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gttqfqsraa.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tianlin.xyz/Article/details/gtacbdlaxw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.c1oappe.top/Article/details/gtjlsilhzl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.bjfxy.top/Article/details/gtxurvgkmg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258888.top/Article/details/gtkgooavmx.html

[N04] 斐波那契数列
来源：http://dali.hammf.cn/Article/details/gtsdhimneq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gthycfgvkw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sweek.top/Article/details/gtflcuxepl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtecoytttx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtnqvgbzfw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jyoumei.cn/Article/details/gtmmbhckhf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cashguo.top/Article/details/gthstghppw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gogol.net.cn/Article/details/gtjffhevcy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gthrwghbhw.html

[N05] 最大公约数
来源：http://dali.cucudq.cn/Article/details/gtwbigxlta.html

Py:   math.gcd(a, b)
来源：http://dali.smart0.xyz/Article/details/gtiwicpybf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.vqdsnc.cn/Article/details/gtupnrcnvy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gtxomtjwlr.html


<!-- 参考信息 -->