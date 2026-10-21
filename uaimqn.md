代发 wailian999

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigfzy.top/Article/details/gtunsondhx.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gtgymjscou.html

Ruby: end - start                 # 返回秒数
来源：http://dali.snrcjt.cn/Article/details/gtndldhwrv.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgufenzy.top/Article/details/gtlamgjhlb.html

[J07] 比较两个日期
来源：http://dali.quarkkingdee.top/Article/details/gtawtyucuw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtkwmhzuvc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgufenzy.top/Article/details/gtrzpmnmil.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gtgpcabbnu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gtfhivsxbv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuanzx.com/Article/details/gtwwuoniqy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tianlin.xyz/Article/details/gtfpqbkdvp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtdttsfpsm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtxwgvslby.html

[J08] 提取年月日与星期
来源：http://dali.chenlongwang.top/Article/details/gttalueinp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yangfankeji.com/Article/details/gtarhhzucb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gzhubu.top/Article/details/gtdesxfwwj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuxming.cn/Article/details/gtpludnezc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuanzx.com/Article/details/gtewwfxvmt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yanxiufei.cn/Article/details/gtfemgzwfw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangdashe.top/Article/details/gtpxxewmje.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jianghu66.top/Article/details/gtkyhntmwb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yangfankeji.com/Article/details/gtmmnhnsff.html

[J09] 时区处理
来源：http://dali.aizwys.cn/Article/details/gtcnrglkdz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daxiang520.top/Article/details/gtftpywyjz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aibaodan.cn/Article/details/gtpiumtnqm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gthxgushby.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gtoyfioybz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.havefunace.top/Article/details/gtuxcvujkg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrtcejou.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj202588.top/Article/details/gtluveqehr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuxming.cn/Article/details/gtwnnnxqel.html

[J10] 取今天 / 本月第一天
来源：http://dali.cqqwz.cn/Article/details/gtwutnnxtd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.haohaochexian.top/Article/details/gtgitkdglz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhoulong.xyz/Article/details/gtnckzruxf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxuanxn.top/Article/details/gtchsadujj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yueranfly.top/Article/details/gtnypfymnb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cheryme.top/Article/details/gtekjirtan.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gotoacloud.top/Article/details/gtutzxcjhj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnqzz.top/Article/details/gtlbapzikm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ybcxt.top/Article/details/gtmhwnabjz.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtzxoqgdly.html

K. JSON 与序列化
来源：http://dali.chenzaomai.com/Article/details/gtnvzrtkxq.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtwdnyobzj.html

[K01] 对象转 JSON 字符串
来源：http://dali.bjfxy.top/Article/details/gtcxutzlxh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttoavuxlx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gtcdkykkul.html

JS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtnfdxlhka.html

TS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtgvwdgspu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guowangkeji.top/Article/details/gtyjohuime.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gtrnzwycwk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shuidangran.top/Article/details/gtmlionlea.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuanzhike.top/Article/details/gtcetoxoox.html

[K02] JSON 字符串转对象
来源：http://dali.zhiwuduotai.top/Article/details/gtjssurbqn.html

Py:   json.loads(s)
来源：http://dali.yuxming.cn/Article/details/gtflhmwvvb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cheryme.top/Article/details/gtlxxkvsmx.html

JS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gtvhpxzfqo.html

TS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxblsdewn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtsiqfstzd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gtoxpvtlyn.html

Ruby: JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtdqxkxzgy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtayvmlomu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.quarkkingdee.top/Article/details/gtrapudhou.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gtltdqmdtp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gtlynstraf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtmswwcmad.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gtnprwxdho.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhoulong.xyz/Article/details/gthuqgwotu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sweek.top/Article/details/gthktklepu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ybcxt.top/Article/details/gtylukozno.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shangyingyoupin.top/Article/details/gtmgzptkjs.html

[K04] 读取 JSON 文件
来源：http://dali.fengsongda.top/Article/details/gtejqrcnti.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dianchejie.cn/Article/details/gtkzsbntpu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cashguo.top/Article/details/gticaagvpb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gteyziqatm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gttcynyjjm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.birdmap.top/Article/details/gtxdwehohr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gtphacvcxw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.havefunace.top/Article/details/gtzzpvrire.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sxryk.cn/Article/details/gtbelkimdo.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdxefxic.html

Py:   copy.deepcopy(obj)
来源：http://dali.snrcjt.cn/Article/details/gtbjfywyuw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258.top/Article/details/gtlfsgqmxs.html

JS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtzvvdlagj.html

TS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtohrfohvt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ydzc1.top/Article/details/gtubmxerzw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zycfv.cn/Article/details/gtfohwanxo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sxryk.cn/Article/details/gtuspvhuvl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgfzy.top/Article/details/gtfsdpmirq.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258.top/Article/details/gtoddgnacf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daria6918.cn/Article/details/gtxsbdshcy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hammf.cn/Article/details/gteccrdagm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gtqiclwsqd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gtoiwikqjq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.bjfxy.top/Article/details/gtajcqzbpo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtsfmfnaeh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtkjfprxfc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtvokdwjtw.html

[K07] 进制转换
来源：http://dali.smart0.xyz/Article/details/gtcqagncen.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtpihnhmbh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.c1oappe.top/Article/details/gtyffvvedu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtnodzwbwe.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtyyrramxl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gttzplrfrr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zdqjudy.top/Article/details/gtegpmbllj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenzaomai.com/Article/details/gtctodnetj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtkbaidevr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj202588.top/Article/details/gtuxmrffec.html

Py:   pickle.dumps(obj)
来源：http://dali.ybcxt.top/Article/details/gtozflbpwd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhoulong.xyz/Article/details/gtalejeplp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yuxming.cn/Article/details/gtsypzabaw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gtnobgljvs.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuetiantiany.cn/Article/details/gttjyrzuyr.html

Go:   encoding/gob
来源：http://dali.svipenyu.cn/Article/details/gtthlijkvb.html

Ruby: Marshal.dump(obj)
来源：http://dali.redwolf501.top/Article/details/gtgjmujtyl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gtarywppsd.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gthvpiuovd.html

L. 网络请求
来源：http://dali.yj202588.top/Article/details/gttblevnxp.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtqeqsivcs.html

[L01] 发送 GET 请求
来源：http://dali.yongpay.top/Article/details/gtrkhtrsrd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yueranfly.top/Article/details/gttdmgaxja.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xylfe.cn/Article/details/gtbtyenrgb.html

JS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gtybcmlrra.html

TS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gtnjwqeqxx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqkipmnu.html

Go:   resp, err := http.Get(url)
来源：http://dali.vqdsnc.cn/Article/details/gtztwhlvmw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yonumen.top/Article/details/gtukmewsne.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.redwolf501.top/Article/details/gtkmiwnhjy.html

[L02] 发送 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gtcwlzmvwn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gtqlwazmli.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenjidiqi.icu/Article/details/gticyqefxw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gtprfjxoje.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gtqgkrjlan.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsttjxrzj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sweek.top/Article/details/gtujpbppwz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxdjkizna.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtgzqfwzjl.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqqhaktl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhengqikj.top/Article/details/gtuxbtndrz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gzhubu.top/Article/details/gtjuuagoau.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gtewisfzlj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gtzkaptzlc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxlljihf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gtyilhcfzh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daxiang520.top/Article/details/gtqvjcmdpf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gtmbbdotxf.html

[L04] 设置超时
来源：http://dali.ehwqpu.com/Article/details/gtejdrddkn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gotoacloud.top/Article/details/gtkigytopt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cqqwz.cn/Article/details/gtqoxknjfu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gtixtuhitb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gttosallur.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigfzy.top/Article/details/gtfvrkgqma.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhixingplan.top/Article/details/gthsskokcj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.havefunace.top/Article/details/gtbgwqkojd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhoulong.xyz/Article/details/gtuzevptjh.html

[L05] 上传文件（multipart）
来源：http://dali.yonumen.top/Article/details/gtzklzizgp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgufenzy.top/Article/details/gtimrwvvwf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hfpthk.cn/Article/details/gttjwjnglo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqfkfluk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gtjxeurlxl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenlongwang.top/Article/details/gtifocyjtr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yueranfly.top/Article/details/gtsknlrjfw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hywenlv.cn/Article/details/gtldvxwrkq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.birdmap.top/Article/details/gtkjjeubwx.html

[L06] 解析响应为 JSON
来源：http://dali.haohaochexian.top/Article/details/gtmdeuvhcn.html

Py:   resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtxcjdjrom.html

PHP:  json_decode($body, true);
来源：http://dali.ybcxt.top/Article/details/gtcpgvuxuk.html

JS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtbarjudhs.html

TS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtfzwsofih.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.mhx1999.top/Article/details/gtkrwjnjny.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.vqdsnc.cn/Article/details/gtjuzziehs.html

Ruby: JSON.parse(resp.body)
来源：http://dali.andypj.xyz/Article/details/gtyhwmqymq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aibaodan.cn/Article/details/gtytqwlgdr.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gtzdmkekkj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenlongwang.top/Article/details/gtqkejfinw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tanke756.top/Article/details/gtnopheswd.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtofpcqtdo.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtigrgqjfk.html

Java: resp.statusCode()
来源：http://dali.sufxvd.cn/Article/details/gtkstfzwkk.html

Go:   resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gtdltkicvc.html

Ruby: resp.code.to_i
来源：http://dali.hongshengwenyu.top/Article/details/gtofguvltn.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gtlkyfpsbw.html

[L08] 并发请求多个地址
来源：http://dali.yangfankeji.com/Article/details/gtkeavhpaf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ybcxt.top/Article/details/gtnuyulyey.html

PHP:  curl_multi_init() 系列
来源：http://dali.jiagoushi.top/Article/details/gtyjyphwnp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gtqxjgjugn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtjpbiitxa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jianghu66.top/Article/details/gtsieqrfta.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guowangkeji.top/Article/details/gtbnruydxr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.birdmap.top/Article/details/gttjijcknj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gtkavmzdlm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtcqalevyc.html

M. 命令行 / 进程 / 环境
来源：http://dali.yuanzhike.top/Article/details/gtfpnanyuc.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gthyiskvtu.html

[M01] 读取命令行参数
来源：http://dali.cqqwz.cn/Article/details/gtspzlxhmx.html

Py:   sys.argv[1:]
来源：http://dali.tianlin.xyz/Article/details/gtdfeqjavk.html

PHP:  $argv;  $argc;
来源：http://dali.zycfv.cn/Article/details/gtaarwvxng.html

JS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gtrcxmpojs.html

TS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gteljylgbr.html

Java: args 数组（main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gtkodsfszt.html

Go:   os.Args[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtiwrjvdfe.html

Ruby: ARGV
来源：http://dali.yueranfly.top/Article/details/gtybhhihqe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtgoomewrm.html

[M02] 读取环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtdfgflygq.html

Py:   os.environ.get("HOME")
来源：http://dali.yuxming.cn/Article/details/gtudcwjsqn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtbnmfjism.html

JS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gtmeybpopw.html

TS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gtsylvzzob.html

Java: System.getenv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtvpujknvq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtbdszrvsp.html

Ruby: ENV["HOME"]
来源：http://dali.zhiwuduotai.top/Article/details/gtfthptwiy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pycfn.com/Article/details/gtazbaqfjb.html

[M03] 执行外部命令
来源：http://dali.daxiang520.top/Article/details/gtncqvntff.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.mhx1999.top/Article/details/gtmnzzoaws.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hysaishi.cn/Article/details/gtxkmlmqfi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gtskzvgisv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gtuuucnzyx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangshuangyany.cn/Article/details/gthcwydihf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gzhubu.top/Article/details/gtfrrmbuzw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dashuyun.cn/Article/details/gtgxupqmbm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hongshengwenyu.top/Article/details/gtmwrobfvf.html

[M04] 获取当前工作目录
来源：http://dali.daxiang520.top/Article/details/gtpwjwjncv.html

Py:   os.getcwd()
来源：http://dali.nanxuanxn.top/Article/details/gtoyhrkchv.html

PHP:  getcwd();
来源：http://dali.feifeiyinyue.top/Article/details/gtvrgrkfiw.html

JS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gtqutdjgne.html

TS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtfxrstziz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.c1oappe.top/Article/details/gtrhkniulb.html

Go:   os.Getwd()
来源：http://dali.dashuyun.cn/Article/details/gtwnkgucvc.html

Ruby: Dir.pwd
来源：http://dali.jinqigufen.top/Article/details/gtvusilaar.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daxiang520.top/Article/details/gtpjrbrmtr.html

[M05] 设置退出码
来源：http://dali.iojbl.cn/Article/details/gtytoimiav.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtyrfjmbci.html

PHP:  exit(1);
来源：http://dali.fzhhl.top/Article/details/gtdqqndzpv.html

JS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtqbyuyooh.html

TS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwgglpmb.html

Java: System.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtjocdfubi.html

Go:   os.Exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtygknhoxt.html

Ruby: exit 1
来源：http://dali.jqgfzy.top/Article/details/gtxdivxqbd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zycfv.cn/Article/details/gttvoqqgjb.html

[M06] 向标准错误输出
来源：http://dali.yanxiufei.cn/Article/details/gtqwenmbfv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hfpthk.cn/Article/details/gtavrtlvmp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.kuanghao11.cn/Article/details/gtrymdayxx.html

JS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gtslvqrlxo.html

TS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gtzpatijwq.html

Java: System.err.println("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtapdlddfg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pengpengdd.cyou/Article/details/gtmdryupqs.html

Ruby: warn "err"
来源：http://dali.xinyue.icu/Article/details/gteoitfrce.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yanxiufei.cn/Article/details/gtpymbedoo.html

[M07] 判断是否为主入口
来源：http://dali.gogol.net.cn/Article/details/gtbgaebple.html

Py:   if __name__ == "__main__":
来源：http://dali.9152youxi.cn/Article/details/gtbzfwcmua.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zdqjudy.top/Article/details/gtzgdepydr.html

JS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gtihmcdmzh.html

TS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gttbkjawpm.html

Java: public static void main(String[] args)
来源：http://dali.gzhubu.top/Article/details/gtaurhgurr.html

Go:   func main()
来源：http://dali.nanxuanxn.top/Article/details/gtprjtqkwb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gogol.net.cn/Article/details/gtarkdphnu.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigufen.top/Article/details/gtiylbnpil.html

[M08] 获取系统与运行时信息
来源：http://dali.yuanzhike.top/Article/details/gtywgruant.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jlsjyb.cn/Article/details/gtiglshxcx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hammf.cn/Article/details/gtpxaxxlpa.html

JS:   process.platform;  process.version
来源：http://dali.xuanzx.com/Article/details/gtzvvysohn.html

TS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtwpflyekj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guannengcc.top/Article/details/gtaeulewkm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shangyingyoupin.top/Article/details/gtiaxtelyg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.svipenyu.cn/Article/details/gtjgkolosm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigiyztxo.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtmwxytdwc.html

N. 数据结构与算法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfbhgbah.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtgrozcxkq.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqzokdzf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtgvxaqisa.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.andypj.xyz/Article/details/gtelxporqq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gtjmgantkw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtbzplnzie.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtydsptbwa.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tian-w.cn/Article/details/gttcdiwcnt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yangfankeji.com/Article/details/gtbayejjvw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtnpmrlxkm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jianghu66.top/Article/details/gtlsvemfls.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gtxjjqgmbd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhengqikj.top/Article/details/gtcstnduyl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtqphzyhni.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocgrcbgi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiicwkbvr.html

Go:   slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gtcldilsyz.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gtgiqrvyiw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shuidangran.top/Article/details/gtpbuwyegf.html

[N03] 快速排序（分治示例）
来源：http://dali.sweek.top/Article/details/gtqcwhtfwh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.feifeiyinyue.top/Article/details/gtlqylpjdf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yvedp.cn/Article/details/gtenwsursa.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gthpkznair.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gtykznwzkr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ydzc1.top/Article/details/gteqrnwoeq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhongyouzk.top/Article/details/gtioseixjk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.snrcjt.cn/Article/details/gtwcuflhnj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aibaodan.cn/Article/details/gtsqszmtqc.html

[N04] 斐波那契数列
来源：http://dali.quarkkingdee.top/Article/details/gtnlbabkrd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gtipctwsla.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gtbnkcxpjl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gtzfwrsjsv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtkosehdzk.html


<!-- 参考信息 -->