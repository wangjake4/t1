代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daxiang520.top/Article/details/gtqfvqqphn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hfpthk.cn/Article/details/gtrhhuovuv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.smart0.xyz/Article/details/gtruspuviw.html

[J06] 计算两时间之差
来源：http://dali.hfpthk.cn/Article/details/gtamgmaixz.html

Py:   (end - start).total_seconds()
来源：http://dali.chenlongwang.top/Article/details/gtizxawvil.html

PHP:  $end->diff($start)->days;
来源：http://dali.gotoacloud.top/Article/details/gtapkbdybm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigufen.top/Article/details/gtbpdhrkms.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoycgorjj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.iojbl.cn/Article/details/gtllpjodcf.html

Go:   end.Sub(start).Hours()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwonnehtf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dashuyun.cn/Article/details/gtfkrxbxmn.html

C#:   (end - start).TotalSeconds
来源：http://dali.ppjwa.cn/Article/details/gtwscyckbt.html

[J07] 比较两个日期
来源：http://dali.gaohongyu789.top/Article/details/gtcptxdvqj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtkdmhwwgs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sweek.top/Article/details/gtuvtlldeu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gtrhmlbsfn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gtanivykrx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gtvdpguhed.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daria6918.cn/Article/details/gtqlcniozv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gtnifbxvkb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtkneaoxhp.html

[J08] 提取年月日与星期
来源：http://dali.snrcjt.cn/Article/details/gtecnxaxzm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.havefunace.top/Article/details/gtphzqspiv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.feifeiyinyue.top/Article/details/gtytceszle.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258.top/Article/details/gtucyxqvux.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.meibo888.top/Article/details/gtbjetobjn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gtelhvpdal.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.svipenyu.cn/Article/details/gthasghncy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.meibo888.top/Article/details/gthvhwthcd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pycfn.com/Article/details/gtjzqsxlcp.html

[J09] 时区处理
来源：http://dali.chenzaomai.com/Article/details/gtqygdssdd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.smart0.xyz/Article/details/gtgbuwjlio.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.meibo888.top/Article/details/gtiomadupg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gtezdegigj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gtzjbnhasa.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258888.top/Article/details/gtcesydbps.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gaohongyu789.top/Article/details/gtlevbzcea.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenjidiqi.icu/Article/details/gtdxxlhpoe.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangdashe.top/Article/details/gtwmragiph.html

[J10] 取今天 / 本月第一天
来源：http://dali.gotoacloud.top/Article/details/gtpwkfnkxs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jiagoushi.top/Article/details/gtrekksrjf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guannengcc.top/Article/details/gthzkjmgfi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fengsongda.top/Article/details/gtbojgeswv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sufxvd.cn/Article/details/gtffvcddka.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhongyouzk.top/Article/details/gtbwgwazbc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fzhhl.top/Article/details/gtlwinohur.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tian-w.cn/Article/details/gttfckwlum.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.andypj.xyz/Article/details/gtfkjuojrm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtqrwdvgqj.html

K. JSON 与序列化
来源：http://dali.yonumen.top/Article/details/gthumkjwai.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtemibvkea.html

[K01] 对象转 JSON 字符串
来源：http://dali.daria6918.cn/Article/details/gtpmwjlowh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gtuuspalwp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gtyrhjrdxm.html

JS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gtyjutzkdy.html

TS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gttqskgmuy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigfzy.top/Article/details/gthpdvnbqx.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gtmfetmmrn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cqqwz.cn/Article/details/gtgvcfirlo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtrdxkbyyi.html

[K02] JSON 字符串转对象
来源：http://dali.ydzc1.top/Article/details/gthuoophco.html

Py:   json.loads(s)
来源：http://dali.tian-w.cn/Article/details/gturerfphu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigfzy.top/Article/details/gtjdyipwea.html

JS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtaubfndeo.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtpvexuojc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtohllhqfs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gthqolruwq.html

Ruby: JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gtqywuuwtt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guannengcc.top/Article/details/gtrjiwmwpu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxinkj.top/Article/details/gttlztcwfg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gtzwfsaqva.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtqqnzsjqq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gtkduxygbv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gtsxbaqxke.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tanke756.top/Article/details/gtwruhmvtu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pengpengdd.cyou/Article/details/gtdmvbxnul.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuanzx.com/Article/details/gtcednyshz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.andypj.xyz/Article/details/gtdaktdooz.html

[K04] 读取 JSON 文件
来源：http://dali.fengsongda.top/Article/details/gtvbpdpdyt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sxryk.cn/Article/details/gtccqkosre.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.9152youxi.cn/Article/details/gtzqpvijrc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gtvzcfozrg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gtrnwujbav.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtfkrlhqzf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gtrrcgraku.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofndxrxs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuanzx.com/Article/details/gtjidaooxk.html

[K05] 深拷贝对象
来源：http://dali.aibaodan.cn/Article/details/gtzfwkwmrg.html

Py:   copy.deepcopy(obj)
来源：http://dali.jianghu66.top/Article/details/gtzqodgplw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dianchejie.cn/Article/details/gtqvjdzfpf.html

JS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gttlsotccm.html

TS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gtkipqttvh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsutgiiwb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.mhx1999.top/Article/details/gtqfyqkuqt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.bjfxy.top/Article/details/gtplddujre.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gaohongyu789.top/Article/details/gthupywtpk.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258888.top/Article/details/gtsakpwkzv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fzhhl.top/Article/details/gtassahagr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cdnleiting.top/Article/details/gthxnlwqeb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gtbkimxqse.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gtqhiuscyq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgufenzy.top/Article/details/gttuihhtil.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtrrhrkmcz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtfxfyzhbh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtyemmdunw.html

[K07] 进制转换
来源：http://dali.nanxuanxn.top/Article/details/gtzosfrokg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtgrrkdhbx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shzxlz.cn/Article/details/gthacgggiy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtmtfksqts.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gttayjbqao.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gttwrdnbux.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daria6918.cn/Article/details/gtsqckoywa.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenjidiqi.icu/Article/details/gtpbvpbvrk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtuyebzpij.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yanxiufei.cn/Article/details/gtpbbndcyl.html

Py:   pickle.dumps(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtecjagzzt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258.top/Article/details/gtdbefwnrx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gtwaeynmlk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtlhcndspf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.0kj1m.cn/Article/details/gtplrfwmkz.html

Go:   encoding/gob
来源：http://dali.mhx1999.top/Article/details/gtefnsuowz.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtlfhjdynw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyqrzdug.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtsywutxgr.html

L. 网络请求
来源：http://dali.hnqzz.top/Article/details/gtcfbtruus.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtamkskskb.html

[L01] 发送 GET 请求
来源：http://dali.wangdashe.top/Article/details/gtcrzhnzja.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tianlin.xyz/Article/details/gtsstragtl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258.top/Article/details/gtrygsqhtk.html

JS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gtpxxgvdyd.html

TS:   await fetch(url)
来源：http://dali.xylfe.cn/Article/details/gtxsifopme.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guannengcc.top/Article/details/gtjhsnpgyy.html

Go:   resp, err := http.Get(url)
来源：http://dali.nwbrower.top/Article/details/gtbzgwrxvj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinghuilouyu.cn/Article/details/gtealmffbr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.0kj1m.cn/Article/details/gtrvcgsoxd.html

[L02] 发送 POST JSON
来源：http://dali.wangdashe.top/Article/details/gtnyduqnbs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jlsjyb.cn/Article/details/gttlycctvn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.pycfn.com/Article/details/gtxzlopaxp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gtyumdehmr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gtewcgnvak.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.dianchejie.cn/Article/details/gtasolxdzo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sxryk.cn/Article/details/gtzgrdazum.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.snrcjt.cn/Article/details/gtkxfkmshx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.meibo888.top/Article/details/gtqtmiwyuh.html

[L03] 设置自定义请求头
来源：http://dali.hnxiangtu.top/Article/details/gtwudcpuxl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.redwolf501.top/Article/details/gtszlovqph.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fzhhl.top/Article/details/gtewejqedw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sysykeji.top/Article/details/gtrnkyaujf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gtujakwila.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.kuanghao11.cn/Article/details/gtbqikhnkc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gthtnquodw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.vqdsnc.cn/Article/details/gtwejcwibf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gtmfegtyii.html

[L04] 设置超时
来源：http://dali.wangshuangyany.cn/Article/details/gtpsmdapwd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shzxlz.cn/Article/details/gtjgrhgqvx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.aibaodan.cn/Article/details/gtyupnhjcn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gtinujesjf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gtjustqrta.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cqqwz.cn/Article/details/gtlflpyquk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daxiang520.top/Article/details/gtztufdffx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhoulong.xyz/Article/details/gtfoxvxtcn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nwbrower.top/Article/details/gtbyypvkhl.html

[L05] 上传文件（multipart）
来源：http://dali.cashguo.top/Article/details/gtsiknjimh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tian-w.cn/Article/details/gtizywdtkh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenzaomai.com/Article/details/gtyspmklei.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkyhbagjx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gtonkcgzsr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.316326.xyz/Article/details/gtehtapwge.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj202588.top/Article/details/gtybbdamik.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258.top/Article/details/gturhomlsw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtopdvtjcc.html

[L06] 解析响应为 JSON
来源：http://dali.jlsjyb.cn/Article/details/gtowalvpms.html

Py:   resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gtilsvvjuy.html

PHP:  json_decode($body, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzxwczqa.html

JS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gtzltdfegd.html

TS:   await resp.json()
来源：http://dali.haohaochexian.top/Article/details/gtxzuoccgg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtupmwupik.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yongpay.top/Article/details/gtiobtmuor.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cashguo.top/Article/details/gtzswxwsfc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nwbrower.top/Article/details/gtgwtjqegu.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtluxylzlv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jianghu66.top/Article/details/gtglivylrk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuxming.cn/Article/details/gtvtnkvlmh.html

JS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gtamushern.html

TS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtnsclcjvq.html

Java: resp.statusCode()
来源：http://dali.zhengqikj.top/Article/details/gtyjsqrkzm.html

Go:   resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gtnovcjvhp.html

Ruby: resp.code.to_i
来源：http://dali.zycfv.cn/Article/details/gtwdeoqsta.html

C#:   (int)resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gtpnsaqfij.html

[L08] 并发请求多个地址
来源：http://dali.andypj.xyz/Article/details/gtxkcctpfx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hfpthk.cn/Article/details/gttrqwxyau.html

PHP:  curl_multi_init() 系列
来源：http://dali.jqgfzy.top/Article/details/gthzsfdfko.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvxlpexh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtzkluzhci.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aibaodan.cn/Article/details/gtbjllbbpp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlxnpozh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcgedmej.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.0kj1m.cn/Article/details/gthnfekmmh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtxossaeuj.html

M. 命令行 / 进程 / 环境
来源：http://dali.pycfn.com/Article/details/gtpxkbjrot.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtgkuepjqm.html

[M01] 读取命令行参数
来源：http://dali.dashuyun.cn/Article/details/gtgsepnraa.html

Py:   sys.argv[1:]
来源：http://dali.hywenlv.cn/Article/details/gtrjqgdjgx.html

PHP:  $argv;  $argc;
来源：http://dali.chenlongwang.top/Article/details/gtpkeyzjlb.html

JS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gthramewme.html

TS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gtivbxgsrj.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gtemszusjr.html

Go:   os.Args[1:]
来源：http://dali.cashguo.top/Article/details/gtmgynfaab.html

Ruby: ARGV
来源：http://dali.meibo888.top/Article/details/gtzyhxbsqb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gtdfthxuwm.html

[M02] 读取环境变量
来源：http://dali.kuanghao11.cn/Article/details/gtmzqwonvd.html

Py:   os.environ.get("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtsewrnpoy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gtuliymdec.html

JS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gtkfdymupc.html

TS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gtqmaqeilo.html

Java: System.getenv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtxwqvtkyt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnqvljih.html

Ruby: ENV["HOME"]
来源：http://dali.sweek.top/Article/details/gtetxyzini.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtqkxiqckx.html

[M03] 执行外部命令
来源：http://dali.9152youxi.cn/Article/details/gtjmbszdmt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtygpyraxc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sufxvd.cn/Article/details/gtsotvxlkw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtvoevnrgh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtxpalhmlb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.0kj1m.cn/Article/details/gtklnfsbhu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daria6918.cn/Article/details/gtxwevpzyw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cashguo.top/Article/details/gtiqhuwwsq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhoulong.xyz/Article/details/gtzcwewjhc.html

[M04] 获取当前工作目录
来源：http://dali.nanxinkj.top/Article/details/gtcgjbdbpv.html

Py:   os.getcwd()
来源：http://dali.redwolf501.top/Article/details/gtyjdkynnt.html

PHP:  getcwd();
来源：http://dali.zycfv.cn/Article/details/gtckutdchq.html

JS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtofnscjam.html

TS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gtdefjnybr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.c1oappe.top/Article/details/gtiadrnehz.html

Go:   os.Getwd()
来源：http://dali.guowangkeji.top/Article/details/gtvmiuhmpv.html

Ruby: Dir.pwd
来源：http://dali.hfpthk.cn/Article/details/gtxmcniqbn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangshuangyany.cn/Article/details/gtbiwxiifa.html

[M05] 设置退出码
来源：http://dali.bjfxy.top/Article/details/gtsqxeaowa.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtzcskfsjp.html

PHP:  exit(1);
来源：http://dali.jqgufenzy.top/Article/details/gtjcvrowld.html

JS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtmnflsjmf.html

TS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtkldgayqm.html

Java: System.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtxrhvyhdm.html

Go:   os.Exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtyjerwqtx.html

Ruby: exit 1
来源：http://dali.cdnleiting.top/Article/details/gtdchaqnpv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.kuanghao11.cn/Article/details/gtsaasoyze.html

[M06] 向标准错误输出
来源：http://dali.wangdashe.top/Article/details/gteusfhnes.html

Py:   print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gtwwkteyij.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.vqdsnc.cn/Article/details/gtuezhpasn.html

JS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gtjoewmuzk.html

TS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gtihfiunxa.html

Java: System.err.println("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqmdgpwu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yueranfly.top/Article/details/gtrtlyaehi.html

Ruby: warn "err"
来源：http://dali.chenlongwang.top/Article/details/gtvgscidmk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yanxiufei.cn/Article/details/gtmiqmuyca.html

[M07] 判断是否为主入口
来源：http://dali.yuxming.cn/Article/details/gtqrjssijb.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gtsvpwjqsn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shzxlz.cn/Article/details/gtllyxjtvv.html

JS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gtfkljyacq.html

TS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gtucvszimt.html

Java: public static void main(String[] args)
来源：http://dali.meibo888.top/Article/details/gthewrycvz.html

Go:   func main()
来源：http://dali.xuetiantiany.cn/Article/details/gtlsuvbfir.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuetiantiany.cn/Article/details/gtavgpdlwo.html

C#:   static void Main(string[] args)
来源：http://dali.cucudq.cn/Article/details/gtuuwtmcfh.html

[M08] 获取系统与运行时信息
来源：http://dali.birdmap.top/Article/details/gtftfteflb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jlsjyb.cn/Article/details/gtxjcvfjtx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangtech.top/Article/details/gtbusmktql.html

JS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gtbvpwkrxm.html

TS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsceqiqq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fzhhl.top/Article/details/gthgmwfejn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sufxvd.cn/Article/details/gtkmvzhhza.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tian-w.cn/Article/details/gtwpmzrynf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.vqdsnc.cn/Article/details/gtqsvxlgvx.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gthcgbgelu.html

N. 数据结构与算法
来源：http://dali.svipenyu.cn/Article/details/gtmxcwjnuf.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtlxibzand.html

[N01] 二分查找（有序数组）
来源：http://dali.hywenlv.cn/Article/details/gthsqlybib.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtuizpntwe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtxcdsyxym.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtmpceivnp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtsealjzss.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtavhbbzht.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtcdrcnoiz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hongshengwenyu.top/Article/details/gtuutjzisj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtvsnecanf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.9152youxi.cn/Article/details/gtktnjnsoi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gtzpcejpji.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtjdkjjqua.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gtyjqojyya.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gtjjaluozr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.meibo888.top/Article/details/gtcjbnblcw.html

Go:   slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gtwybrqbpm.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gtllabhyqp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zycfv.cn/Article/details/gteeoanazx.html

[N03] 快速排序（分治示例）
来源：http://dali.bjfxy.top/Article/details/gtkioikhui.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yvedp.cn/Article/details/gtxwcoyjdk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcyorjdec.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gtfoawyjvj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gtoydnojfy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dashuyun.cn/Article/details/gtwevemmfv.html


<!-- 参考信息 -->