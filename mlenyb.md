代发 wailian999

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jianghu66.top/Article/details/gtlyzmknsc.html

Go:   end.Sub(start).Hours()
来源：http://dali.mhx1999.top/Article/details/gtwaqrgjyf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fzhhl.top/Article/details/gtgoytnstd.html

C#:   (end - start).TotalSeconds
来源：http://dali.svipenyu.cn/Article/details/gtseziuvge.html

[J07] 比较两个日期
来源：http://dali.aizwys.cn/Article/details/gtxjlcxvgf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtqdbjdmto.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xinyue.icu/Article/details/gtqqywobmb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gtfjnemwyz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gtoypsjejl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258.top/Article/details/gtjngrqmnd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nwbrower.top/Article/details/gtadxumbfj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtjnximbof.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gtlkezhjjy.html

[J08] 提取年月日与星期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuengpnmz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigufen.top/Article/details/gttruechml.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.pycfn.com/Article/details/gtwqacbeoh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj202588.top/Article/details/gtqqopbnkj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gtftffowop.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgfzy.top/Article/details/gtilvlqetp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ivvv.top/Article/details/gtbqpowarg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxuanxn.top/Article/details/gtsfymkrep.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nwbrower.top/Article/details/gtdqegwtuv.html

[J09] 时区处理
来源：http://dali.hywenlv.cn/Article/details/gthlyyeimp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fengsongda.top/Article/details/gtvznbtsza.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhoulong.xyz/Article/details/gtrsonvomx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gaohongyu789.top/Article/details/gtpcougepx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gtwfawooun.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sufxvd.cn/Article/details/gtxebyznmx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxinkj.top/Article/details/gtbddmypvy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnxiangtu.top/Article/details/gtufvwcdlj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hongshengwenyu.top/Article/details/gtpmzpcmzk.html

[J10] 取今天 / 本月第一天
来源：http://dali.yongpay.top/Article/details/gtmhtohsdv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ehwqpu.com/Article/details/gtucmbcjlt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhongyouzk.top/Article/details/gthvcjnkuo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cashguo.top/Article/details/gtszskqtal.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jianghu66.top/Article/details/gtjwpykadm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtzjnnoxss.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ppjwa.cn/Article/details/gtvpkelajv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhoulong.xyz/Article/details/gtsbdgicxk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjpzlvyj.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtbgssjcmb.html

K. JSON 与序列化
来源：http://dali.tian-w.cn/Article/details/gtozjdsvdx.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtcqziyxkr.html

[K01] 对象转 JSON 字符串
来源：http://dali.svipenyu.cn/Article/details/gtatbxpjqp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gtmrppvtfw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gtwazwoies.html

JS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtcnabizfy.html

TS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtadiabrhc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jlsjyb.cn/Article/details/gtkmpbjtxp.html

Go:   json.Marshal(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtmtrfbaql.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.snrcjt.cn/Article/details/gtiflfvigg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.birdmap.top/Article/details/gtrrhsckeb.html

[K02] JSON 字符串转对象
来源：http://dali.yanxiufei.cn/Article/details/gtqxdwtfzy.html

Py:   json.loads(s)
来源：http://dali.yongpay.top/Article/details/gtsckyduvg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hongshengwenyu.top/Article/details/gtwfppkmxc.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtsnhddglk.html

TS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtvzpyayvn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtogltbkuw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gthsrgqnfv.html

Ruby: JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtvrbtikny.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhixingplan.top/Article/details/gtjaaksvln.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxesjypf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtrqssedka.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxcbbyyx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtceyjbomo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gtmkbzltmh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daxiang520.top/Article/details/gtbyzeryol.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangshuangyany.cn/Article/details/gthdialuwh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtcbhxpade.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ivvv.top/Article/details/gtjiyhvzju.html

[K04] 读取 JSON 文件
来源：http://dali.fzhhl.top/Article/details/gtlluuxuid.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxinkj.top/Article/details/gtaikbosck.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuanzhike.top/Article/details/gtwtedkxsl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstcichnp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gtutcouhqg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gttzsympqz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqnfpuyo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gtpsyhmzee.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangdashe.top/Article/details/gtlbscobre.html

[K05] 深拷贝对象
来源：http://dali.havefunace.top/Article/details/gtsodsblfn.html

Py:   copy.deepcopy(obj)
来源：http://dali.hfpthk.cn/Article/details/gtecuafmqv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tian-w.cn/Article/details/gtwxzhgkbg.html

JS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gtslisdhaa.html

TS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gticgqceya.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhixingplan.top/Article/details/gtefdarnfn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jiagoushi.top/Article/details/gtltvwcedp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daxiang520.top/Article/details/gtleqqryqr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fzhhl.top/Article/details/gtqitwajsh.html

[K06] 解析 URL 查询串
来源：http://dali.wangshuangyany.cn/Article/details/gttfilgwoy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gtllkjbklo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.kuanghao11.cn/Article/details/gtfmsakcds.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gtijzwzvsw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gtdywwbeuk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aibaodan.cn/Article/details/gtyzeoncri.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtiieeupwf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gtwnqiovgy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gtcffyldxq.html

[K07] 进制转换
来源：http://dali.tianlin.xyz/Article/details/gtgipsceqj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtmkxskvxz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgfzy.top/Article/details/gtfxpooglf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwrjacpu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gteeuonedn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtzzjzhqwc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ehwqpu.com/Article/details/gtmrltvric.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.316326.xyz/Article/details/gtsggsqxuu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtcsioidnx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pycfn.com/Article/details/gtwswdbylp.html

Py:   pickle.dumps(obj)
来源：http://dali.jyoumei.cn/Article/details/gtfmtnqqts.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cqqwz.cn/Article/details/gtjjrjqeiq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gthkxbcizn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gtpmhiaxtn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zdqjudy.top/Article/details/gtpbjgazlw.html

Go:   encoding/gob
来源：http://dali.cheryme.top/Article/details/gtixhwpuxz.html

Ruby: Marshal.dump(obj)
来源：http://dali.jiagoushi.top/Article/details/gthcloiivs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gtvkzneqbv.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtsldozpgk.html

L. 网络请求
来源：http://dali.vqdsnc.cn/Article/details/gtrovpowgi.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtamfcyqik.html

[L01] 发送 GET 请求
来源：http://dali.nanxinkj.top/Article/details/gtmsyjsvgj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangdashe.top/Article/details/gtavhbfegb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.snrcjt.cn/Article/details/gtsugxujtp.html

JS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gtcpczrqdh.html

TS:   await fetch(url)
来源：http://dali.zycfv.cn/Article/details/gtbvpziigh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xziqi.cn/Article/details/gtiyvibyrb.html

Go:   resp, err := http.Get(url)
来源：http://dali.hammf.cn/Article/details/gtigbalnji.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangshuangyany.cn/Article/details/gtboirxvww.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigfzy.top/Article/details/gtrfpydbfh.html

[L02] 发送 POST JSON
来源：http://dali.havefunace.top/Article/details/gtnfvqcmxv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtxazqmbev.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shzxlz.cn/Article/details/gtlxesbhyh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gtogmcfwrh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jlsjyb.cn/Article/details/gtvvlizsan.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.meibo888.top/Article/details/gtmvcezuep.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhiwuduotai.top/Article/details/gtsfbbhqbh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hongshengwenyu.top/Article/details/gtpuabdmwr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.9152youxi.cn/Article/details/gtlqidqjmx.html

[L03] 设置自定义请求头
来源：http://dali.wangshuangyany.cn/Article/details/gtdzuykzeu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.haohaochexian.top/Article/details/gthcrmjvss.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.birdmap.top/Article/details/gtozqxyhjs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gtqslxsghp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gtqfegohnk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cqqwz.cn/Article/details/gtzklytjlm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gtlrizjnyq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cheryme.top/Article/details/gtbdqqplqc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gtmuvnhjvq.html

[L04] 设置超时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqmrczog.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ivvv.top/Article/details/gtqdkpkxla.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.aibaodan.cn/Article/details/gtbrdwuwwr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gtgqmkpvyt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gtfmczbjlm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guowangkeji.top/Article/details/gtuzxbvria.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cheryme.top/Article/details/gtafaipdff.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shuidangran.top/Article/details/gtjpdfpqcm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gotoacloud.top/Article/details/gtslbnjvts.html

[L05] 上传文件（multipart）
来源：http://dali.haohaochexian.top/Article/details/gtvhasbrac.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nwbrower.top/Article/details/gtecijrblx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xinyue.icu/Article/details/gthnqumlcc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gtpawzwyvh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gturztgqmj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gaohongyu789.top/Article/details/gtjojppqsp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pycfn.com/Article/details/gtkmolsyda.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yanxiufei.cn/Article/details/gtnzjcesfr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtdhmgmted.html

[L06] 解析响应为 JSON
来源：http://dali.gogol.net.cn/Article/details/gtbufzysam.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gttcxdqhrw.html

PHP:  json_decode($body, true);
来源：http://dali.yangfankeji.com/Article/details/gtkrmtppvs.html

JS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gtsfryajrr.html

TS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gtoppxzdpo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtlqbcnvqz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zycfv.cn/Article/details/gtslcdjumo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhongyouzk.top/Article/details/gtuafrtxaw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangdashe.top/Article/details/gtiksjsjvx.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gtjqhrnorh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cheryme.top/Article/details/gteuyztxio.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.mhx1999.top/Article/details/gtrgbwnwse.html

JS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gtwndtajcm.html

TS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmntlohht.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskmhvvwp.html

Go:   resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gtxlvikumf.html

Ruby: resp.code.to_i
来源：http://dali.wangdashe.top/Article/details/gthmnmmlsh.html

C#:   (int)resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gtoyifxpod.html

[L08] 并发请求多个地址
来源：http://dali.nwbrower.top/Article/details/gtklgnjmyv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ppjwa.cn/Article/details/gtoaddeokj.html

PHP:  curl_multi_init() 系列
来源：http://dali.shuidangran.top/Article/details/gtuxxxtqfr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gtpagbzsro.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gtbrskjmyv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gotoacloud.top/Article/details/gtzbedmzkh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.316326.xyz/Article/details/gtkahlwbzc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gtvdaojqfy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtdjajtzvd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtghfvqdlo.html

M. 命令行 / 进程 / 环境
来源：http://dali.haohaochexian.top/Article/details/gtjlglagdc.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtvabsedzg.html

[M01] 读取命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gtykvitvvi.html

Py:   sys.argv[1:]
来源：http://dali.cdnleiting.top/Article/details/gtwfbgkjsu.html

PHP:  $argv;  $argc;
来源：http://dali.zdqjudy.top/Article/details/gtmksctfzi.html

JS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gtfomfjrfp.html

TS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gtjgyloayh.html

Java: args 数组（main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gtqakwtdfi.html

Go:   os.Args[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gtrdefzplv.html

Ruby: ARGV
来源：http://dali.sysykeji.top/Article/details/gtbhucjrnj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gtksbfbhhz.html

[M02] 读取环境变量
来源：http://dali.xinyue.icu/Article/details/gtcmzejgbh.html

Py:   os.environ.get("HOME")
来源：http://dali.hammf.cn/Article/details/gtfksmvzqo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tanke756.top/Article/details/gthbzzevgm.html

JS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gtwmfdszeb.html

TS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gtafuorblo.html

Java: System.getenv("HOME")
来源：http://dali.nwbrower.top/Article/details/gtauhgctpe.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtaerhpnle.html

Ruby: ENV["HOME"]
来源：http://dali.gotoacloud.top/Article/details/gtwnbiklbu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtnoksfdvz.html

[M03] 执行外部命令
来源：http://dali.yj20258.top/Article/details/gtdydcasuk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpqcjwfn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhongyouzk.top/Article/details/gtmrgdnged.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gtnejhxwfm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanigejre.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.0kj1m.cn/Article/details/gthdybpiyi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.haohaochexian.top/Article/details/gtuomkapoo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhongyouzk.top/Article/details/gtpnzcourx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ydzc1.top/Article/details/gtfgtzshpo.html

[M04] 获取当前工作目录
来源：http://dali.smart0.xyz/Article/details/gtexpdwcbg.html

Py:   os.getcwd()
来源：http://dali.xziqi.cn/Article/details/gtntncnuax.html

PHP:  getcwd();
来源：http://dali.tian-w.cn/Article/details/gtyxomqcaa.html

JS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gtflevyavm.html

TS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobwkjwmh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxuanxn.top/Article/details/gtgxybiqxh.html

Go:   os.Getwd()
来源：http://dali.jinqigufen.top/Article/details/gtqjfnpuht.html

Ruby: Dir.pwd
来源：http://dali.yuanzhike.top/Article/details/gtdrxfqect.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.smart0.xyz/Article/details/gtzpixgglg.html

[M05] 设置退出码
来源：http://dali.chenlongwang.top/Article/details/gtyagjrxvd.html

Py:   sys.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoyimzjtf.html

PHP:  exit(1);
来源：http://dali.snrcjt.cn/Article/details/gtehhbwqaj.html

JS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtnlqaeueb.html

TS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtdmwqcixt.html

Java: System.exit(1)
来源：http://dali.tanke756.top/Article/details/gtuiqzoxsu.html

Go:   os.Exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtvfkoixqj.html

Ruby: exit 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgkimlxk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nwbrower.top/Article/details/gtajakiyif.html

[M06] 向标准错误输出
来源：http://dali.0kj1m.cn/Article/details/gtgwmlfogc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daria6918.cn/Article/details/gtyyacgiwq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ydzc1.top/Article/details/gtmsteeldl.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtyrhvcrsq.html

TS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtnptufcbo.html

Java: System.err.println("err")
来源：http://dali.c1oappe.top/Article/details/gtkeszfqfi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.9152youxi.cn/Article/details/gtisqeawqx.html

Ruby: warn "err"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxzxdhyjf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gtdsggdvqj.html

[M07] 判断是否为主入口
来源：http://dali.sxryk.cn/Article/details/gtzgrsardu.html

Py:   if __name__ == "__main__":
来源：http://dali.0kj1m.cn/Article/details/gttqiosyot.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.vqdsnc.cn/Article/details/gtokpqmorm.html

JS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gtidfqsccz.html

TS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gtfncbptii.html

Java: public static void main(String[] args)
来源：http://dali.yuanzhike.top/Article/details/gtotflvyry.html

Go:   func main()
来源：http://dali.sweek.top/Article/details/gtbhabqhiz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hammf.cn/Article/details/gtypmurdoh.html

C#:   static void Main(string[] args)
来源：http://dali.jianghu66.top/Article/details/gtiixmlzox.html

[M08] 获取系统与运行时信息
来源：http://dali.ydzc1.top/Article/details/gtsmnywldo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dashuyun.cn/Article/details/gtlplymreb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.9152youxi.cn/Article/details/gthzryzdhi.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gtljmqbdzw.html

TS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gtepwkcchr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tian-w.cn/Article/details/gtfalxlxjd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zdqjudy.top/Article/details/gtsfpqnozq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xuetiantiany.cn/Article/details/gtbigwzeby.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tianlin.xyz/Article/details/gtymsklwbz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtwttzhyun.html

N. 数据结构与算法
来源：http://dali.yuxming.cn/Article/details/gtjucnktnp.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gthlffctts.html

[N01] 二分查找（有序数组）
来源：http://dali.zhiwuduotai.top/Article/details/gtoiwzesrn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gthsfytopj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ybcxt.top/Article/details/gtpuiojixs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtdoqibuuw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gtvqowcrwb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwpnymxjd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gthnpthoov.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gotoacloud.top/Article/details/gtvynxxivm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwstagii.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuanzx.com/Article/details/gtrnjlfvlt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gtafutaglq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtlutstxkr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gtkdsqrvfj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gtuhrpqjud.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fzhhl.top/Article/details/gtjcbhfazj.html

Go:   slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtdyvsuyro.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gtplidioic.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fzhhl.top/Article/details/gtgaffautc.html

[N03] 快速排序（分治示例）
来源：http://dali.daxiang520.top/Article/details/gtqajdtbde.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shzxlz.cn/Article/details/gtuzsreqxc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangdashe.top/Article/details/gtyzsqfotf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gtpdkyhyno.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gtxmxhmdvp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.andypj.xyz/Article/details/gtkewwozbv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenlongwang.top/Article/details/gtmjzxtaot.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jqgufenzy.top/Article/details/gtxzrkgglr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhengqikj.top/Article/details/gtvdupfruz.html

[N04] 斐波那契数列
来源：http://dali.chenlongwang.top/Article/details/gtiegsnlgt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtrcfsadzr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yueranfly.top/Article/details/gtkxenlthh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gtyirxfnte.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gtjbtmfjab.html


<!-- 参考信息 -->