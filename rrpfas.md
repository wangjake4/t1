代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gt2rlvqfwdv.html

[J08] 提取年月日与星期
来源：http://dali.yj20258888.top/Article/details/gt2kxrquhtu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yueranfly.top/Article/details/gt2empequar.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxuanxn.top/Article/details/gt2hsscwhlc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pspdnosb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.redwolf501.top/Article/details/gt2znvtyflg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ydzc1.top/Article/details/gt2vqfooury.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgufenzy.top/Article/details/gt2moqhmukv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gt2susbrftc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.feifeiyinyue.top/Article/details/gt2owctclrb.html

[J09] 时区处理
来源：http://dali.yuxming.cn/Article/details/gt2gvlsztxg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jiagoushi.top/Article/details/gt2lhyoekeh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ocuxgcdf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gt2nrtlpovl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gt2kwffwpdr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.haohaochexian.top/Article/details/gt2okcndkop.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.snrcjt.cn/Article/details/gt2liddvmsm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj202588.top/Article/details/gt2gphrzyrp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258888.top/Article/details/gt2bfwfqput.html

[J10] 取今天 / 本月第一天
来源：http://dali.daria6918.cn/Article/details/gt2xsfjlyoj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vnyfhfvp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangshuangyany.cn/Article/details/gt2rkbrflew.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yvedp.cn/Article/details/gt2cvgvfaro.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2mcbhyzyd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cdnleiting.top/Article/details/gt2qbonbgbd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuxming.cn/Article/details/gt2nrvgxsoi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj202588.top/Article/details/gt2qcajikla.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ivvv.top/Article/details/gt2dtucknus.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2gzmrufqt.html

K. JSON 与序列化
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rlnwvwba.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2rzpzdlpl.html

[K01] 对象转 JSON 字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2wgwhjtdi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gt2bwzexmup.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2iyugymfh.html

JS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2twjdnqzc.html

TS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2hqzsdngy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2unvpsurb.html

Go:   json.Marshal(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mxdbbqxp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.meibo888.top/Article/details/gt2lvnszeby.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2ypvwfyfy.html

[K02] JSON 字符串转对象
来源：http://dali.gaohongyu789.top/Article/details/gt2tqfonzaq.html

Py:   json.loads(s)
来源：http://dali.gotoacloud.top/Article/details/gt2qvhdmhqf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258.top/Article/details/gt2ubprszxi.html

JS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2ckfeeffi.html

TS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gt2aixuemeu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aizwys.cn/Article/details/gt2mxdcblfb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gt2vfoazcup.html

Ruby: JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gt2fguyvehc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sxryk.cn/Article/details/gt2ivniiwmf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jqgfzy.top/Article/details/gt2hjwxkyhf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gt2wabzylma.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gt2wvrichhh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gt2futqsfyq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gt2xdxxlacw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guannengcc.top/Article/details/gt2efzzulah.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vjmudpev.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ukzdnzrw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhoulong.xyz/Article/details/gt2izwlxqvk.html

[K04] 读取 JSON 文件
来源：http://dali.dianchejie.cn/Article/details/gt2pejansyy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.quarkkingdee.top/Article/details/gt2ewrrrmna.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yangfankeji.com/Article/details/gt2zvektgtm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gt2ggkzoyih.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gt2opeocwzk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj202588.top/Article/details/gt2okhitsje.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gt2lbqtpczl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gt2lxtprcdj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gzhubu.top/Article/details/gt2vtitqsho.html

[K05] 深拷贝对象
来源：http://dali.guannengcc.top/Article/details/gt2kgimqdvy.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2zyjrmxnk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuetiantiany.cn/Article/details/gt2ecsbggpi.html

JS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gt2wvzbjtat.html

TS:   structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gt2netiimzn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenjidiqi.icu/Article/details/gt2uoqjlzrk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.bjfxy.top/Article/details/gt2juqswqqc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cucudq.cn/Article/details/gt2kfzpyxjz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258888.top/Article/details/gt2tvptmttp.html

[K06] 解析 URL 查询串
来源：http://dali.sweek.top/Article/details/gt2gddyfawe.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cucudq.cn/Article/details/gt2opxrudkl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cucudq.cn/Article/details/gt2kfqtvdgs.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lrlffmnv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gt2xxhbtmkl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gt2dyfchedm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gt2srutdmbf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gt2otidasko.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gt2vxztjnae.html

[K07] 进制转换
来源：http://dali.smart0.xyz/Article/details/gt2vuvggotm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xudcgxej.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hysaishi.cn/Article/details/gt2doirmigt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2outpwelw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2atextrya.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2ijltvlgr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cgypgbmk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yangfankeji.com/Article/details/gt2yniyqnfz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2lticjqpj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigufen.top/Article/details/gt2elvrcmwv.html

Py:   pickle.dumps(obj)
来源：http://dali.tanke756.top/Article/details/gt2otuypdjr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shzxlz.cn/Article/details/gt2ehaenlke.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dodoatco.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gt2erknphdf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj202588.top/Article/details/gt2lxydvhxj.html

Go:   encoding/gob
来源：http://dali.yuanzhike.top/Article/details/gt2kxncjeom.html

Ruby: Marshal.dump(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2naqjgvzj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gt2mdzjefpn.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2vhhrenbg.html

L. 网络请求
来源：http://dali.zycfv.cn/Article/details/gt2hqjdhpdg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2dxumfgno.html

[L01] 发送 GET 请求
来源：http://dali.sxryk.cn/Article/details/gt2qdzuwtek.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ybcxt.top/Article/details/gt2sbqcaicu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yangfankeji.com/Article/details/gt2lazikzfq.html

JS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gt2pvoqovfd.html

TS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gt2pgxvxhwh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hongshengwenyu.top/Article/details/gt2cpzznvxv.html

Go:   resp, err := http.Get(url)
来源：http://dali.redwolf501.top/Article/details/gt2asdxuxvq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.mhx1999.top/Article/details/gt2wcjhfisu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aizwys.cn/Article/details/gt2eplajxgy.html

[L02] 发送 POST JSON
来源：http://dali.hammf.cn/Article/details/gt2asfqrbre.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tanke756.top/Article/details/gt2gtivocfx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yvedp.cn/Article/details/gt2ohxldsba.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gt2zfguilfl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gt2lcgqnblx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daria6918.cn/Article/details/gt2yauaiemu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hongshengwenyu.top/Article/details/gt2ejiqyfdp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hywenlv.cn/Article/details/gt2suyebbhu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigfzy.top/Article/details/gt2aixepnov.html

[L03] 设置自定义请求头
来源：http://dali.feifeiyinyue.top/Article/details/gt2nlahfddo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hfpthk.cn/Article/details/gt2dszqaqqc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dashuyun.cn/Article/details/gt2pdktmtiu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gt2cprosjpm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lefkthtm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ivvv.top/Article/details/gt2fmazgsaz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gt2ytabyday.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sysykeji.top/Article/details/gt2wnsnarhl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gt2pzqauugz.html

[L04] 设置超时
来源：http://dali.jyoumei.cn/Article/details/gt2lhmjezan.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenzaomai.com/Article/details/gt2bhwhcwzm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pycfn.com/Article/details/gt2rmpvonxm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guannengcc.top/Article/details/gt2icfbjddg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gt2pnyepjoz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenlongwang.top/Article/details/gt2ikuzdpfw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhixingplan.top/Article/details/gt2jfplchqc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ppjwa.cn/Article/details/gt2vvnmbpgb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuanzx.com/Article/details/gt2uwomqxyl.html

[L05] 上传文件（multipart）
来源：http://dali.fengsongda.top/Article/details/gt2guevxspx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hwazljap.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sufxvd.cn/Article/details/gt2bdyiqkkd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gt2pxmwcmvd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shuidangran.top/Article/details/gt2gvudyymv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubiyswho.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2dillkszy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhixingplan.top/Article/details/gt2hobwuafg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2dsjjserz.html

[L06] 解析响应为 JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2dnfmgkrs.html

Py:   resp.json()
来源：http://dali.snrcjt.cn/Article/details/gt2mjvgemxz.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gt2sioalsgp.html

JS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gt2iuhrylpj.html

TS:   await resp.json()
来源：http://dali.haohaochexian.top/Article/details/gt2ctibwygl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.bjfxy.top/Article/details/gt2cafbekyf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gotoacloud.top/Article/details/gt2mlrqcnep.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ehwqpu.com/Article/details/gt2cwktgarc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.0kj1m.cn/Article/details/gt2wsmwxlyb.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gt2xctgosdj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cheryme.top/Article/details/gt2tvrelumb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gogol.net.cn/Article/details/gt2vqlphbtj.html

JS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gt2zhcpbubf.html

TS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gt2hwrxllke.html

Java: resp.statusCode()
来源：http://dali.nanxinkj.top/Article/details/gt2aegkdear.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gt2bawotgso.html

Ruby: resp.code.to_i
来源：http://dali.yanxiufei.cn/Article/details/gt2bsyrzizu.html

C#:   (int)resp.StatusCode
来源：http://dali.gotoacloud.top/Article/details/gt2ltnkvzcu.html

[L08] 并发请求多个地址
来源：http://dali.xziqi.cn/Article/details/gt2ingznorv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gt2frufkbrd.html

PHP:  curl_multi_init() 系列
来源：http://dali.redwolf501.top/Article/details/gt2izsswtbw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gt2brphzlhl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gt2pixrcctk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zdqjudy.top/Article/details/gt2vlvbbzbg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jiagoushi.top/Article/details/gt2qvsknpza.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.birdmap.top/Article/details/gt2qmldgnnp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xylfe.cn/Article/details/gt2ovqqrbrg.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2rccjlquy.html

M. 命令行 / 进程 / 环境
来源：http://dali.mhx1999.top/Article/details/gt2asvdgpuo.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2lwfneyce.html

[M01] 读取命令行参数
来源：http://dali.ydzc1.top/Article/details/gt2vmajcsqu.html

Py:   sys.argv[1:]
来源：http://dali.jlsjyb.cn/Article/details/gt2svvrljxd.html

PHP:  $argv;  $argc;
来源：http://dali.pengpengdd.cyou/Article/details/gt2kbbzgbyb.html

JS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gt2znnkffvv.html

TS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gt2fizreegl.html

Java: args 数组（main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gt2ncdgkutr.html

Go:   os.Args[1:]
来源：http://dali.jqgfzy.top/Article/details/gt2ckyhpbee.html

Ruby: ARGV
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uccetcmb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gt2kqxpimrl.html

[M02] 读取环境变量
来源：http://dali.fengsongda.top/Article/details/gt2opzhllsa.html

Py:   os.environ.get("HOME")
来源：http://dali.bjfxy.top/Article/details/gt2upzshtui.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.316326.xyz/Article/details/gt2zyvamcyk.html

JS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gt2flxiwdfx.html

TS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gt2csxufazn.html

Java: System.getenv("HOME")
来源：http://dali.bjfxy.top/Article/details/gt2mwddolaz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj202588.top/Article/details/gt2ycyezigr.html

Ruby: ENV["HOME"]
来源：http://dali.ppjwa.cn/Article/details/gt2evadmxzo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zycfv.cn/Article/details/gt2jxnkefns.html

[M03] 执行外部命令
来源：http://dali.ehwqpu.com/Article/details/gt2aqnhiafm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lrfbofcs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnqzz.top/Article/details/gt2fdirhqta.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gt2yijayguj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gt2etskowlu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jiagoushi.top/Article/details/gt2hmlmdkpo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigufen.top/Article/details/gt2qqemmqvw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhoulong.xyz/Article/details/gt2elxudruz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hywenlv.cn/Article/details/gt2iiyknfzo.html

[M04] 获取当前工作目录
来源：http://dali.ybcxt.top/Article/details/gt2zkyxjqlv.html

Py:   os.getcwd()
来源：http://dali.dianchejie.cn/Article/details/gt2uthyofzo.html

PHP:  getcwd();
来源：http://dali.hammf.cn/Article/details/gt2dxsdjtcf.html

JS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gt2pktdzaly.html

TS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gt2htfbrhtk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuanzx.com/Article/details/gt2mtzwfmjg.html

Go:   os.Getwd()
来源：http://dali.sweek.top/Article/details/gt2eghretcj.html

Ruby: Dir.pwd
来源：http://dali.chenlongwang.top/Article/details/gt2zacyzgli.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.redwolf501.top/Article/details/gt2ljjrgtzd.html

[M05] 设置退出码
来源：http://dali.shzxlz.cn/Article/details/gt2pucemrue.html

Py:   sys.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2fxzijrao.html

PHP:  exit(1);
来源：http://dali.cucudq.cn/Article/details/gt2pqolrqvv.html

JS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gt2scfgwdzi.html

TS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gt2ezcamzlt.html

Java: System.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2dbphzskm.html

Go:   os.Exit(1)
来源：http://dali.cdnleiting.top/Article/details/gt2yjbmtsuj.html

Ruby: exit 1
来源：http://dali.gogol.net.cn/Article/details/gt2rwccdflm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sxryk.cn/Article/details/gt2owialitj.html

[M06] 向标准错误输出
来源：http://dali.jqgfzy.top/Article/details/gt2sqbboiat.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zycfv.cn/Article/details/gt2hergkkwq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhongyouzk.top/Article/details/gt2bgffnxoa.html

JS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gt2fvejzqua.html

TS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gt2dksuryhj.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wloqhafy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daria6918.cn/Article/details/gt2tcqotaak.html

Ruby: warn "err"
来源：http://dali.sysykeji.top/Article/details/gt2ntbjrfrq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jtreujul.html

[M07] 判断是否为主入口
来源：http://dali.zdqjudy.top/Article/details/gt2ierwqkvp.html

Py:   if __name__ == "__main__":
来源：http://dali.hywenlv.cn/Article/details/gt2sownzorw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dashuyun.cn/Article/details/gt2mdedusse.html

JS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqfvetzx.html

TS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gt2jsnpaoas.html

Java: public static void main(String[] args)
来源：http://dali.hfpthk.cn/Article/details/gt2jrmzpjoh.html

Go:   func main()
来源：http://dali.sxryk.cn/Article/details/gt2ijnokddk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.haohaochexian.top/Article/details/gt2ryzuryic.html

C#:   static void Main(string[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zeycifni.html

[M08] 获取系统与运行时信息
来源：http://dali.0kj1m.cn/Article/details/gt2ucibwjzk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cucudq.cn/Article/details/gt2chzutqtr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xziqi.cn/Article/details/gt2cjcuaaxp.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gt2hpcwnasa.html

TS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ecmtnawz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xylfe.cn/Article/details/gt2pwtcodgz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cdnleiting.top/Article/details/gt2syxfpgsj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pengpengdd.cyou/Article/details/gt2wehmlkma.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ivvv.top/Article/details/gt2nrockrpd.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2xbgspnte.html

N. 数据结构与算法
来源：http://dali.xziqi.cn/Article/details/gt2yeczygpy.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2sgejszth.html

[N01] 二分查找（有序数组）
来源：http://dali.shangyingyoupin.top/Article/details/gt2vkeizaxd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2qfnxuhir.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.c1oappe.top/Article/details/gt2nbzxrvmc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gt2jaaukebn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gt2jklvckpo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2lulwxoct.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2avdrnths.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnxiangtu.top/Article/details/gt2ywhbvpwj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2xgjsrwsc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenzaomai.com/Article/details/gt2khzgvpjc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gt2xsxjbbkl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuanzx.com/Article/details/gt2hxowpmcx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gt2iglpztbr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gt2oryryeya.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.316326.xyz/Article/details/gt2lzsdjogn.html

Go:   slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gt2zcooikzb.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gt2qpuzkqha.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgfzy.top/Article/details/gt2kkaqvgyg.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigufen.top/Article/details/gt2vsmpzdlm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenlongwang.top/Article/details/gt2wjqmgedg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuanzhike.top/Article/details/gt2rydstkao.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gt2ozhhowau.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gt2serwkysn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tanke756.top/Article/details/gt2ubdpvxfw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dianchejie.cn/Article/details/gt2fjxquzbd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hysaishi.cn/Article/details/gt2lbuxkbkt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hysaishi.cn/Article/details/gt2qrrtcahn.html

[N04] 斐波那契数列
来源：http://dali.mhx1999.top/Article/details/gt2jbncszpk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gt2fudvueqm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jfmequzr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gt2kvmjioql.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2hswwmxeb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gt2ngfpuaop.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.haohaochexian.top/Article/details/gt2xjarwxqx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gt2dbugvoad.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gt2fjornpxk.html

[N05] 最大公约数
来源：http://dali.tianlin.xyz/Article/details/gt2djhnhbsm.html

Py:   math.gcd(a, b)
来源：http://dali.hfpthk.cn/Article/details/gt2ussjwpkw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hywenlv.cn/Article/details/gt2svshhdde.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gt2emkbjscy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ifvkkysi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xmlywfet.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sxryk.cn/Article/details/gt2vqdwfthq.html

Ruby: a.gcd(b)
来源：http://dali.ydzc1.top/Article/details/gt2neqalglw.html


<!-- 参考信息 -->