代发 wailian999

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258.top/Article/details/gt2sdiffzmd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2plvislpw.html

[J09] 时区处理
来源：http://dali.redwolf501.top/Article/details/gt2rrlhrrgn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.bjfxy.top/Article/details/gt2swfoybmz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ppjwa.cn/Article/details/gt2pjditxbz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gt2qqiulgyb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gt2pvgnwczn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangdashe.top/Article/details/gt2grdgjokh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ppjwa.cn/Article/details/gt2uvhylzof.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenzaomai.com/Article/details/gt2sakvjfoz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fzhhl.top/Article/details/gt2imsqfaly.html

[J10] 取今天 / 本月第一天
来源：http://dali.sweek.top/Article/details/gt2lbvmvgmq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hywenlv.cn/Article/details/gt2emmabcmf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gt2ihymcvcq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guannengcc.top/Article/details/gt2fflmrice.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuxming.cn/Article/details/gt2pqfwdecs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guowangkeji.top/Article/details/gt2vqpefvuq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gt2vziswmdr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jlsjyb.cn/Article/details/gt2xozcxxxa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gogol.net.cn/Article/details/gt2qgkdswqj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2mtdahrft.html

K. JSON 与序列化
来源：http://dali.bjfxy.top/Article/details/gt2wpbljjju.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2nwqpffxz.html

[K01] 对象转 JSON 字符串
来源：http://dali.xziqi.cn/Article/details/gt2qieyoynf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gt2mevbgspl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2dqizuixe.html

JS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gt2icmhjkcl.html

TS:   JSON.stringify(obj)
来源：http://dali.meibo888.top/Article/details/gt2qgcvyddh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gaohongyu789.top/Article/details/gt2loukwwjd.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2ehplhupx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.bjfxy.top/Article/details/gt2pqbjjkto.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj202588.top/Article/details/gt2hgekgknx.html

[K02] JSON 字符串转对象
来源：http://dali.hfpthk.cn/Article/details/gt2ifnhcwmp.html

Py:   json.loads(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oqxehsad.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sufxvd.cn/Article/details/gt2icpcjhgr.html

JS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gt2joxfqewi.html

TS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gt2weofygox.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gt2luugmmwx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gt2qqancrkn.html

Ruby: JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gt2ggbhdgkm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2vdbcmqhg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xinyue.icu/Article/details/gt2oyzcwmwy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gt2cmayddxi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gt2xjtgmunc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gt2jqdghqcw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gt2jsnlnbtb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2grtjgsqk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenjidiqi.icu/Article/details/gt2yumrpvxl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tian-w.cn/Article/details/gt2pffespqx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xinyue.icu/Article/details/gt2htjhhtih.html

[K04] 读取 JSON 文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2qojjmlzj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hfzhplma.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhongyouzk.top/Article/details/gt2agktwvdf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gt2kjnkifau.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gt2xacovvlo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2woyxflyl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gt2qtemeqfb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gt2bqyxxppf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guannengcc.top/Article/details/gt2ohspgbfc.html

[K05] 深拷贝对象
来源：http://dali.xziqi.cn/Article/details/gt2pjattgyf.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2aklckjba.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gt2gejhiyrh.html

JS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gt2wfioutwq.html

TS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gt2jtqhenya.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gogol.net.cn/Article/details/gt2tdlrwguh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tian-w.cn/Article/details/gt2lublvmxi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ivvv.top/Article/details/gt2qudbmzez.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gzhubu.top/Article/details/gt2ymjthdra.html

[K06] 解析 URL 查询串
来源：http://dali.jiagoushi.top/Article/details/gt2birbbzqu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gt2opeiccya.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guowangkeji.top/Article/details/gt2yekpjrml.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cucudq.cn/Article/details/gt2ycifquyx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qoxomoqx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.pycfn.com/Article/details/gt2dawafkgl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gt2gfjpfaoh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gt2szislbzy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gt2snkqifgw.html

[K07] 进制转换
来源：http://dali.guowangkeji.top/Article/details/gt2ldypjbvr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2cuaojcyd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnqzz.top/Article/details/gt2codcztas.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2cuplhuen.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2anxbtyhc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gt2zgmgevcc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nwbrower.top/Article/details/gt2hyixyybv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pycfn.com/Article/details/gt2rswicotw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2bbsgjcen.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigufen.top/Article/details/gt2wgcwlrkx.html

Py:   pickle.dumps(obj)
来源：http://dali.yj202588.top/Article/details/gt2jkcbtacy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shzxlz.cn/Article/details/gt2potmkdid.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gt2hfxkkugt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gt2jkifcwec.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.c1oappe.top/Article/details/gt2saouwtui.html

Go:   encoding/gob
来源：http://dali.pycfn.com/Article/details/gt2vzqmoxaz.html

Ruby: Marshal.dump(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2kyfzgpuf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gt2axzlskml.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2gnaoimzm.html

L. 网络请求
来源：http://dali.daxiang520.top/Article/details/gt2jgazjwmj.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2xplgrwee.html

[L01] 发送 GET 请求
来源：http://dali.mhx1999.top/Article/details/gt2ejbiijeu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shzxlz.cn/Article/details/gt2auyjhhkk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuanzhike.top/Article/details/gt2tmejybtc.html

JS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gt2ybiwqdew.html

TS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xuboxqll.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shzxlz.cn/Article/details/gt2fkbpkzzm.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhixingplan.top/Article/details/gt2bgdznwjg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tian-w.cn/Article/details/gt2cpeamalj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ivvv.top/Article/details/gt2fzzudzfg.html

[L02] 发送 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ycwlgrqo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gzhubu.top/Article/details/gt2noyxepwp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.pycfn.com/Article/details/gt2pkexbzqb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gt2inpjqioo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gt2fuqvyion.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jiagoushi.top/Article/details/gt2brkiorfc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jyoumei.cn/Article/details/gt2nodbtbpl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hxfhjgsd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guannengcc.top/Article/details/gt2smzhtsvk.html

[L03] 设置自定义请求头
来源：http://dali.feifeiyinyue.top/Article/details/gt2dpfgaiue.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.wangshuangyany.cn/Article/details/gt2yjodsbfw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yvedp.cn/Article/details/gt2zjwmctdl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nrmrzbwc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gt2xuyztbpi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yangfankeji.com/Article/details/gt2xqxfvnrr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gt2mahwhhxq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aibaodan.cn/Article/details/gt2bmidogqa.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gt2jhbiqdnm.html

[L04] 设置超时
来源：http://dali.tianlin.xyz/Article/details/gt2jeseluxi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tianlin.xyz/Article/details/gt2vwrychzj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guannengcc.top/Article/details/gt2tbpjbrwy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gt2zmxpxojb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gt2kqyusmxq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zpuiyypn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangshuangyany.cn/Article/details/gt2duvwwklz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hywenlv.cn/Article/details/gt2vbmdqbma.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxuanxn.top/Article/details/gt2amhzidej.html

[L05] 上传文件（multipart）
来源：http://dali.tianlin.xyz/Article/details/gt2pcmlrkua.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aibaodan.cn/Article/details/gt2omgkqpml.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuxming.cn/Article/details/gt2eujhcltk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gt2ddhdfggv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gt2aveaycft.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gt2skhcwwef.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2ykwdvgmp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jiagoushi.top/Article/details/gt2dkibuyai.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2ppkjszyk.html

[L06] 解析响应为 JSON
来源：http://dali.shuidangran.top/Article/details/gt2wdczfqgk.html

Py:   resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2fepscaxm.html

PHP:  json_decode($body, true);
来源：http://dali.yanxiufei.cn/Article/details/gt2eqrrttlz.html

JS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2ncqdifrc.html

TS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2flljhyey.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gt2jlalqfgl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.fengsongda.top/Article/details/gt2szbmjatb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgfzy.top/Article/details/gt2bvffswpn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgufenzy.top/Article/details/gt2wlebkffw.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cksqwevs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yanxiufei.cn/Article/details/gt2vtfrmddc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shuidangran.top/Article/details/gt2hbawqmjy.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gt2hqlbknob.html

TS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gt2yhclqefc.html

Java: resp.statusCode()
来源：http://dali.jlsjyb.cn/Article/details/gt2cvxwgsur.html

Go:   resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gt2tppnlgle.html

Ruby: resp.code.to_i
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zappozqm.html

C#:   (int)resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gt2yuhafmsg.html

[L08] 并发请求多个地址
来源：http://dali.aizwys.cn/Article/details/gt2qshamfqw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sxryk.cn/Article/details/gt2vgwckzzc.html

PHP:  curl_multi_init() 系列
来源：http://dali.kuanghao11.cn/Article/details/gt2zzyeylmt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fqjhvmdo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gt2ruwrqnmx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhongyouzk.top/Article/details/gt2uhdzhtzh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.redwolf501.top/Article/details/gt2biwmguex.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jqgfzy.top/Article/details/gt2jbsmqkah.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gt2uuazwhri.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2oexrkqpf.html

M. 命令行 / 进程 / 环境
来源：http://dali.iojbl.cn/Article/details/gt2wrahxpqx.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2gvgazxgo.html

[M01] 读取命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2gsamqsca.html

Py:   sys.argv[1:]
来源：http://dali.vqdsnc.cn/Article/details/gt2kljgfnaq.html

PHP:  $argv;  $argc;
来源：http://dali.tanke756.top/Article/details/gt2dlebwntk.html

JS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rhzuqinj.html

TS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gt2uscipwoy.html

Java: args 数组（main 方法参数）
来源：http://dali.316326.xyz/Article/details/gt2xmngjyxp.html

Go:   os.Args[1:]
来源：http://dali.jqgfzy.top/Article/details/gt2xfuderig.html

Ruby: ARGV
来源：http://dali.daxiang520.top/Article/details/gt2nuxbiwzt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gt2kijnrgtw.html

[M02] 读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2gghmtofv.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgfzy.top/Article/details/gt2sodtxfzf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gt2tcpahhas.html

JS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gt2ktgedvio.html

TS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gt2ttvmitzo.html

Java: System.getenv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gt2foqkkisz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gt2qmtwtyvb.html

Ruby: ENV["HOME"]
来源：http://dali.sysykeji.top/Article/details/gt2svqivpgf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sxryk.cn/Article/details/gt2zbciyzrn.html

[M03] 执行外部命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zpcgvjom.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuanzhike.top/Article/details/gt2flkhsthg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tanke756.top/Article/details/gt2ymeitcuf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gt2kopxdjqc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gt2coyjnjph.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhoulong.xyz/Article/details/gt2psdwuvtr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hongshengwenyu.top/Article/details/gt2jqkwhxjr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hywenlv.cn/Article/details/gt2larsqzjp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258.top/Article/details/gt2ahnmftqn.html

[M04] 获取当前工作目录
来源：http://dali.gzhubu.top/Article/details/gt2ywjpnihd.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rspppexc.html

PHP:  getcwd();
来源：http://dali.daxiang520.top/Article/details/gt2lsmrdfgs.html

JS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gt2ivrbncgf.html

TS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gt2vwsgdsge.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.fengsongda.top/Article/details/gt2havcpjli.html

Go:   os.Getwd()
来源：http://dali.shangyingyoupin.top/Article/details/gt2dwafgeog.html

Ruby: Dir.pwd
来源：http://dali.yuanzhike.top/Article/details/gt2yfaxbuvx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.havefunace.top/Article/details/gt2kwkkgfat.html

[M05] 设置退出码
来源：http://dali.bjfxy.top/Article/details/gt2xrrbmvaz.html

Py:   sys.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2uvczjlvz.html

PHP:  exit(1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xvxjwrax.html

JS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2jbkkzorj.html

TS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2xjpgqmmc.html

Java: System.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gt2kgkzbqoa.html

Go:   os.Exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2dtmidqta.html

Ruby: exit 1
来源：http://dali.sweek.top/Article/details/gt2yexaaiha.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xylfe.cn/Article/details/gt2yiocpncz.html

[M06] 向标准错误输出
来源：http://dali.dianchejie.cn/Article/details/gt2zigqvvqu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gt2ndrzjsem.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ybcxt.top/Article/details/gt2nejelxto.html

JS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gt2wwfoyyln.html

TS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gt2rdmkwode.html

Java: System.err.println("err")
来源：http://dali.havefunace.top/Article/details/gt2qnvgtidm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sysykeji.top/Article/details/gt2htpgfpdr.html

Ruby: warn "err"
来源：http://dali.hywenlv.cn/Article/details/gt2shbgtvnq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daxiang520.top/Article/details/gt2perlxzze.html

[M07] 判断是否为主入口
来源：http://dali.zhixingplan.top/Article/details/gt2nnhoqpon.html

Py:   if __name__ == "__main__":
来源：http://dali.gotoacloud.top/Article/details/gt2oofpyowh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.havefunace.top/Article/details/gt2hocooyzd.html

JS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gt2ynqsymaj.html

TS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gt2vcktbepf.html

Java: public static void main(String[] args)
来源：http://dali.guowangkeji.top/Article/details/gt2kjgobwqz.html

Go:   func main()
来源：http://dali.jinqigufen.top/Article/details/gt2itmlwdew.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.0kj1m.cn/Article/details/gt2ovmbrqdo.html

C#:   static void Main(string[] args)
来源：http://dali.yvedp.cn/Article/details/gt2omgqapao.html

[M08] 获取系统与运行时信息
来源：http://dali.aibaodan.cn/Article/details/gt2vyiikwgk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jianghu66.top/Article/details/gt2wppdlekh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dianchejie.cn/Article/details/gt2wekvjjtz.html

JS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gt2epnrcwgm.html

TS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gt2txmurzzw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenlongwang.top/Article/details/gt2frywwlnd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jlsjyb.cn/Article/details/gt2zwsizbsy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hammf.cn/Article/details/gt2glehspmg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xinyue.icu/Article/details/gt2vipnxxfr.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2fxpreyig.html

N. 数据结构与算法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xqpraezu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2guwixxmm.html

[N01] 二分查找（有序数组）
来源：http://dali.feifeiyinyue.top/Article/details/gt2zfhcqegp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2poccqont.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yvedp.cn/Article/details/gt2sakpnaci.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gt2cndmrqkn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gt2lmmiyiws.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2gaioswmh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hvrfvcmj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yongpay.top/Article/details/gt2nicyvapa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2spvnkgev.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.andypj.xyz/Article/details/gt2qjwiykcu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gt2bfraipcs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pycfn.com/Article/details/gt2zmqpqgje.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gt2rrnfcjuy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gt2cgtwizxd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cdnleiting.top/Article/details/gt2tlygotxb.html

Go:   slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2pyjaeqir.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gt2neywfxav.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oiowjspn.html

[N03] 快速排序（分治示例）
来源：http://dali.bjfxy.top/Article/details/gt2dkwrsohm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.havefunace.top/Article/details/gt2skvgbayv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gt2ritretfe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gt2pulzoxyg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ehwqpu.com/Article/details/gt2yzygvupx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guowangkeji.top/Article/details/gt2rsiexiyd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shzxlz.cn/Article/details/gt2trnvszyb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.quarkkingdee.top/Article/details/gt2slgowtqi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aizwys.cn/Article/details/gt2zmccsuia.html

[N04] 斐波那契数列
来源：http://dali.jinqigfzy.top/Article/details/gt2itfvfwfg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gt2noklvrkf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gt2jmbbwevs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gt2ufukgigb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gt2tonxbcvo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gt2endqiwvn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xinyue.icu/Article/details/gt2qgkhjgbb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2xtnrvgsz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2itjzlqsb.html

[N05] 最大公约数
来源：http://dali.xylfe.cn/Article/details/gt2ejfprppc.html

Py:   math.gcd(a, b)
来源：http://dali.hywenlv.cn/Article/details/gt2lmcpfzcq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yongpay.top/Article/details/gt2mzpdioaq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gt2dfkgtagk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gotoacloud.top/Article/details/gt2uymvyozc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jiagoushi.top/Article/details/gt2fricroyn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jianghu66.top/Article/details/gt2kthjzrwl.html

Ruby: a.gcd(b)
来源：http://dali.daria6918.cn/Article/details/gt2ggdnxbxp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rlrsijcz.html

[N06] 判断回文字符串
来源：http://dali.guannengcc.top/Article/details/gt2nbslwshx.html

Py:   s == s[::-1]
来源：http://dali.tanke756.top/Article/details/gt2hyzzfpfk.html

PHP:  $s === strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gt2sygmztpn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2iadceokr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gt2mgbnixfm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gt2olaoffyt.html

Go:   // 双指针从两端比较
来源：http://dali.ppjwa.cn/Article/details/gt2gozqywvi.html


<!-- 参考信息 -->