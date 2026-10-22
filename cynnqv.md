代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj202588.top/Article/details/gt2zgmoswpc.html

[J04] 时间戳与日期互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2klnipafv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hammf.cn/Article/details/gt2psxdsewb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daria6918.cn/Article/details/gt2fjbrhdtf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hslbwibc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xinyue.icu/Article/details/gt2rnsoprpq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258888.top/Article/details/gt2cjbdtwhe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ofxevuwf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xylfe.cn/Article/details/gt2hechybge.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dianchejie.cn/Article/details/gt2tncjphox.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ztolhaqk.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgfzy.top/Article/details/gt2eppjmqwj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guowangkeji.top/Article/details/gt2uazdfapz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gt2ggpbpera.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gt2gdqlcogh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.iojbl.cn/Article/details/gt2dzvbebgh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2veumypdx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.vqdsnc.cn/Article/details/gt2rxpqnjkt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gt2rermcwre.html

[J06] 计算两时间之差
来源：http://dali.zhoulong.xyz/Article/details/gt2ghhhoadt.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258888.top/Article/details/gt2mszgxceq.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xxcsrcme.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yongpay.top/Article/details/gt2fskdkura.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fzhhl.top/Article/details/gt2hjwvupyk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgufenzy.top/Article/details/gt2ukktlarr.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj202588.top/Article/details/gt2utccyzkb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gt2rwvuqjcv.html

C#:   (end - start).TotalSeconds
来源：http://dali.dashuyun.cn/Article/details/gt2rdhogmmh.html

[J07] 比较两个日期
来源：http://dali.daria6918.cn/Article/details/gt2sujlnaqo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gt2tdtbotpq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cucudq.cn/Article/details/gt2qdeybulg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gzbaroso.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gt2ywbbokrz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnqzz.top/Article/details/gt2jcscrjgg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shuidangran.top/Article/details/gt2icgccpgv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gt2wpqolgtu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gt2cblskyao.html

[J08] 提取年月日与星期
来源：http://dali.zdqjudy.top/Article/details/gt2dzyxujxl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pengpengdd.cyou/Article/details/gt2jsqnagvf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ydzc1.top/Article/details/gt2plcghnsm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.quarkkingdee.top/Article/details/gt2rrnorkfg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenlongwang.top/Article/details/gt2fntycybi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigufen.top/Article/details/gt2vtybpgzv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.iojbl.cn/Article/details/gt2nlphyrgv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhixingplan.top/Article/details/gt2jorimcyc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yueranfly.top/Article/details/gt2lehperyy.html

[J09] 时区处理
来源：http://dali.yueranfly.top/Article/details/gt2xwzvktbn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cashguo.top/Article/details/gt2gdzvblwl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258888.top/Article/details/gt2cnmfnoch.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gt2srxtxzhu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gt2niovngfr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ivvv.top/Article/details/gt2gwkbxgpb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gzhubu.top/Article/details/gt2ozzbjnuz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jyoumei.cn/Article/details/gt2viwixjet.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jyoumei.cn/Article/details/gt2kglsfwpr.html

[J10] 取今天 / 本月第一天
来源：http://dali.shangyingyoupin.top/Article/details/gt2krudneaz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cucudq.cn/Article/details/gt2shjbtofm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aibaodan.cn/Article/details/gt2avtomevf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cucudq.cn/Article/details/gt2gguwiobd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cucudq.cn/Article/details/gt2vxjfzbbj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgfzy.top/Article/details/gt2tnlkapxo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgufenzy.top/Article/details/gt2brzjtsjn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fzhhl.top/Article/details/gt2akgchbfg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guannengcc.top/Article/details/gt2teukpmlf.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2bjgssejw.html

K. JSON 与序列化
来源：http://dali.guannengcc.top/Article/details/gt2xiwrsufm.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2usbbtkfc.html

[K01] 对象转 JSON 字符串
来源：http://dali.guannengcc.top/Article/details/gt2anephilo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gt2gpjadwfk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gt2gqplytuc.html

JS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2owasjoeu.html

TS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2vkzmdzfl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yueranfly.top/Article/details/gt2dotfyprq.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2vinvbwmr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangdashe.top/Article/details/gt2enhdojcy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.birdmap.top/Article/details/gt2qidecjkj.html

[K02] JSON 字符串转对象
来源：http://dali.jiagoushi.top/Article/details/gt2zxsohjmv.html

Py:   json.loads(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2cuxaxyhk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xylfe.cn/Article/details/gt2almzgrxb.html

JS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gt2fhaunazn.html

TS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gt2nfcnntfm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gt2drllkeak.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gt2flcmlxfe.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gt2wisoxrjk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.snrcjt.cn/Article/details/gt2xlqigtjr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigfzy.top/Article/details/gt2dfqclqoo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gt2spfktfqx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gt2ofmjqyee.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gt2twwsxenz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xziqi.cn/Article/details/gt2vcxlpxcx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pjbvrrvq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.mhx1999.top/Article/details/gt2avlwhbad.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sxryk.cn/Article/details/gt2afwskogp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tian-w.cn/Article/details/gt2yomnodiv.html

[K04] 读取 JSON 文件
来源：http://dali.andypj.xyz/Article/details/gt2egfmsxwv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jiagoushi.top/Article/details/gt2sgkidpyp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ivvv.top/Article/details/gt2gabhfuwq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gt2uqoeimjp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gt2ngcdktem.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.birdmap.top/Article/details/gt2vtfgxmef.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ssvhqarg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gt2odfyjnbc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258888.top/Article/details/gt2ilxkgjfi.html

[K05] 深拷贝对象
来源：http://dali.svipenyu.cn/Article/details/gt2rfgetsnj.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2hcguaipc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daria6918.cn/Article/details/gt2nfqlpraq.html

JS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2nvfrvuqi.html

TS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gt2xxwteiit.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.quarkkingdee.top/Article/details/gt2fughrprx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tanke756.top/Article/details/gt2exjjsbcz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sysykeji.top/Article/details/gt2riuonsyn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xylfe.cn/Article/details/gt2zjrgbkrb.html

[K06] 解析 URL 查询串
来源：http://dali.yj202588.top/Article/details/gt2sozelzch.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gt2bsztyjnz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnxiangtu.top/Article/details/gt2yhqqidrb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gt2wfzbtfho.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gt2rrsvrxqa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sufxvd.cn/Article/details/gt2uvuqunri.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gt2cfolavch.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gt2kejqayby.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gt2vqwtxwvd.html

[K07] 进制转换
来源：http://dali.aibaodan.cn/Article/details/gt2ldlxucjv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cfoceavw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shangyingyoupin.top/Article/details/gt2zyyrmbyb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2mljbpcsa.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2tgxlnrie.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2hymzftnq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxinkj.top/Article/details/gt2ccvtrcxh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.316326.xyz/Article/details/gt2mtmvkgqc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzxakgm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sxryk.cn/Article/details/gt2wuhxdjmd.html

Py:   pickle.dumps(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2ifmivjbt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sweek.top/Article/details/gt2oiuthtra.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nwbrower.top/Article/details/gt2ehuhvxcd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gt2qbnrzruv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2mujlsodc.html

Go:   encoding/gob
来源：http://dali.kuanghao11.cn/Article/details/gt2efsjfunl.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258888.top/Article/details/gt2xkqndory.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gt2jelbzjia.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2dbeshywe.html

L. 网络请求
来源：http://dali.yueranfly.top/Article/details/gt2ajrkjisk.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2jtapkeqj.html

[L01] 发送 GET 请求
来源：http://dali.daria6918.cn/Article/details/gt2qwjpzfsb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pycfn.com/Article/details/gt2lvguinqw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qwjcqeed.html

JS:   await fetch(url)
来源：http://dali.cdnleiting.top/Article/details/gt2isnkilwd.html

TS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lsqhcbjo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aizwys.cn/Article/details/gt2gnghdzua.html

Go:   resp, err := http.Get(url)
来源：http://dali.cucudq.cn/Article/details/gt2mefirhwj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jyoumei.cn/Article/details/gt2akmepwoa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xinyue.icu/Article/details/gt2mwtuofys.html

[L02] 发送 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gt2srtkjmxk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gt2axdhsage.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxinkj.top/Article/details/gt2qqgvuckl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gt2kqconuyw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gt2uhmmuvmy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.redwolf501.top/Article/details/gt2qvfuxgdv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.smart0.xyz/Article/details/gt2owwqkvth.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tanke756.top/Article/details/gt2jcfrgmin.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2hgvlqjgo.html

[L03] 设置自定义请求头
来源：http://dali.yuanzhike.top/Article/details/gt2pmzzrbdr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cashguo.top/Article/details/gt2rdegmyhc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jlsjyb.cn/Article/details/gt2stgbitel.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mkgpewuz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gt2amxteeuk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuxming.cn/Article/details/gt2yfnponlm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gt2tpihssuc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pengpengdd.cyou/Article/details/gt2vtehpsiq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gt2hqxgdkkr.html

[L04] 设置超时
来源：http://dali.hfpthk.cn/Article/details/gt2evlajnnp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.kuanghao11.cn/Article/details/gt2xeseqiwl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.birdmap.top/Article/details/gt2tmampbvx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gt2zcaouwyu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gt2yftjygdv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gt2hjklswlt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.vqdsnc.cn/Article/details/gt2lelzcsuk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ggjlzwnx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fzhhl.top/Article/details/gt2qwggzpkj.html

[L05] 上传文件（multipart）
来源：http://dali.zhoulong.xyz/Article/details/gt2bkanqkdg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.svipenyu.cn/Article/details/gt2aojpthzu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aizwys.cn/Article/details/gt2fhqasyjr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gt2clnxpueo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gt2knpqordq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cucudq.cn/Article/details/gt2qpxomlxf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shzxlz.cn/Article/details/gt2ojolbtuh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.redwolf501.top/Article/details/gt2zfvbfqjg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2fzfrccxc.html

[L06] 解析响应为 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gt2hyvjiwea.html

Py:   resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gt2mmavqzil.html

PHP:  json_decode($body, true);
来源：http://dali.gzhubu.top/Article/details/gt2kzrthpyj.html

JS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cftsiwzv.html

TS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gt2gvvifqfo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gt2ouzahozo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gogol.net.cn/Article/details/gt2qjxtbuce.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tian-w.cn/Article/details/gt2taunxcjy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnqzz.top/Article/details/gt2mprmafaj.html

[L07] 处理 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gt2ijfinqoq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tanke756.top/Article/details/gt2ffewpips.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jlsjyb.cn/Article/details/gt2wknzjzbe.html

JS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gt2axkikabv.html

TS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gt2foktdwll.html

Java: resp.statusCode()
来源：http://dali.0kj1m.cn/Article/details/gt2dnkkrcqu.html

Go:   resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gt2qtfmighz.html

Ruby: resp.code.to_i
来源：http://dali.dashuyun.cn/Article/details/gt2bhuuokvw.html

C#:   (int)resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zxazgkvt.html

[L08] 并发请求多个地址
来源：http://dali.zhongyouzk.top/Article/details/gt2yebmrruo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jyoumei.cn/Article/details/gt2lzimlefu.html

PHP:  curl_multi_init() 系列
来源：http://dali.tianlin.xyz/Article/details/gt2fvmsdlzu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gt2cfvjhiwk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gt2swzwxjvv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.meibo888.top/Article/details/gt2ncwxwinb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.mhx1999.top/Article/details/gt2mywlwdmg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yueranfly.top/Article/details/gt2qajhjyco.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tianlin.xyz/Article/details/gt2bxipacjh.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2eidaeizz.html

M. 命令行 / 进程 / 环境
来源：http://dali.gzhubu.top/Article/details/gt2guesawsh.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2mwoduqwv.html

[M01] 读取命令行参数
来源：http://dali.birdmap.top/Article/details/gt2wfgqnntv.html

Py:   sys.argv[1:]
来源：http://dali.ydzc1.top/Article/details/gt2yzjdoieb.html

PHP:  $argv;  $argc;
来源：http://dali.meibo888.top/Article/details/gt2yhonmfbd.html

JS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gt2pkxriagz.html

TS:   process.argv.slice(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uppwvuig.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gt2zdzutane.html

Go:   os.Args[1:]
来源：http://dali.9152youxi.cn/Article/details/gt2ktcimvdz.html

Ruby: ARGV
来源：http://dali.gaohongyu789.top/Article/details/gt2yacrcklu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gt2onceoqyb.html

[M02] 读取环境变量
来源：http://dali.aizwys.cn/Article/details/gt2zwtbvyng.html

Py:   os.environ.get("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gt2puddxrdv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gt2ejbwczbx.html

JS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gt2zadwljgk.html

TS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pukrwacx.html

Java: System.getenv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gt2csdznpbz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gt2fwtihcgt.html

Ruby: ENV["HOME"]
来源：http://dali.aizwys.cn/Article/details/gt2ayawitkc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tanke756.top/Article/details/gt2vaymzslo.html

[M03] 执行外部命令
来源：http://dali.xuetiantiany.cn/Article/details/gt2myjyquna.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wziyxmdr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnxiangtu.top/Article/details/gt2sletahju.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bpypbsqf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gt2rummvese.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fzhhl.top/Article/details/gt2ieqjabxo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangshuangyany.cn/Article/details/gt2zqdbdkgp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhixingplan.top/Article/details/gt2cxwylsup.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xuanzx.com/Article/details/gt2jxmxzawh.html

[M04] 获取当前工作目录
来源：http://dali.nanxuanxn.top/Article/details/gt2voihrjkg.html

Py:   os.getcwd()
来源：http://dali.zycfv.cn/Article/details/gt2bkpbxakv.html

PHP:  getcwd();
来源：http://dali.zdqjudy.top/Article/details/gt2noiwxmll.html

JS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lytzajpm.html

TS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gt2hjulrhsp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daria6918.cn/Article/details/gt2tkemqvib.html

Go:   os.Getwd()
来源：http://dali.shzxlz.cn/Article/details/gt2wqvcjupi.html

Ruby: Dir.pwd
来源：http://dali.zhongyouzk.top/Article/details/gt2vqmqumzd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhongyouzk.top/Article/details/gt2djknntlg.html

[M05] 设置退出码
来源：http://dali.316326.xyz/Article/details/gt2osghqjyy.html

Py:   sys.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2phqxmmjy.html

PHP:  exit(1);
来源：http://dali.guowangkeji.top/Article/details/gt2tigutmrq.html

JS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hcbtoxah.html

TS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gt2volyzoim.html

Java: System.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gt2eomaljmh.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gt2ermgphpa.html

Ruby: exit 1
来源：http://dali.ppjwa.cn/Article/details/gt2sfxibzhf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hywenlv.cn/Article/details/gt2qjcytgde.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gt2nihubwpw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.kuanghao11.cn/Article/details/gt2hmpbrnfh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.andypj.xyz/Article/details/gt2prcwmqzq.html

JS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gt2otwzalfl.html

TS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gt2vsbmouds.html

Java: System.err.println("err")
来源：http://dali.ehwqpu.com/Article/details/gt2hrxhfjrx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qxinudwf.html

Ruby: warn "err"
来源：http://dali.yueranfly.top/Article/details/gt2srnjaxdw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258888.top/Article/details/gt2nfzcgzdj.html

[M07] 判断是否为主入口
来源：http://dali.tianlin.xyz/Article/details/gt2fdoxkjhv.html

Py:   if __name__ == "__main__":
来源：http://dali.feifeiyinyue.top/Article/details/gt2vnqqdivo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxuanxn.top/Article/details/gt2guxdvebi.html

JS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gt2ngrwwirj.html

TS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gt2eaijggwl.html

Java: public static void main(String[] args)
来源：http://dali.guannengcc.top/Article/details/gt2ywlllhva.html

Go:   func main()
来源：http://dali.dianchejie.cn/Article/details/gt2rfpwwrfj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guannengcc.top/Article/details/gt2mrigszlu.html

C#:   static void Main(string[] args)
来源：http://dali.snrcjt.cn/Article/details/gt2aqworiwo.html

[M08] 获取系统与运行时信息
来源：http://dali.jyoumei.cn/Article/details/gt2fphmzuwz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhengqikj.top/Article/details/gt2jxttanxh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuanzhike.top/Article/details/gt2vdhurdea.html

JS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gt2nqvbneda.html

TS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gt2naijhysb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aibaodan.cn/Article/details/gt2npfydvow.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.vqdsnc.cn/Article/details/gt2xzemmula.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gt2bqjixdlj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pengpengdd.cyou/Article/details/gt2gegtkzmt.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2lveboghq.html

N. 数据结构与算法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qgmofbth.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2dzzzqkus.html

[N01] 二分查找（有序数组）
来源：http://dali.fengsongda.top/Article/details/gt2wvhmdjbg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2jgsjydvj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ppjwa.cn/Article/details/gt2imboeaum.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gt2gsggrqsl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.birdmap.top/Article/details/gt2xacubmdb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2wmlexljq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xgnvdirl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuxming.cn/Article/details/gt2ijclzomx.html


<!-- 参考信息 -->