代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daria6918.cn/Article/details/gt2hkikhjmo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sweek.top/Article/details/gt2bgreastd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aibaodan.cn/Article/details/gt2pudykzyz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2wdtrguat.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qzgsujqw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bunnpvgc.html

[J05] 时间加减（加 7 天）
来源：http://dali.ybcxt.top/Article/details/gt2ltecrxtj.html

Py:   now + timedelta(days=7)
来源：http://dali.nwbrower.top/Article/details/gt2isqzwwxu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fzhhl.top/Article/details/gt2thpzhell.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gt2ornivgya.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jyoumei.cn/Article/details/gt2bstyidrw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.birdmap.top/Article/details/gt2bcgbzdtq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gt2smeizedz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuanzx.com/Article/details/gt2srubutxt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gt2yrtxspux.html

[J06] 计算两时间之差
来源：http://dali.zycfv.cn/Article/details/gt2sehkdbaq.html

Py:   (end - start).total_seconds()
来源：http://dali.yanxiufei.cn/Article/details/gt2kscgedso.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xgjuawok.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.haohaochexian.top/Article/details/gt2zcjfylki.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pengpengdd.cyou/Article/details/gt2omlgxbfo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cucudq.cn/Article/details/gt2drlxdrdh.html

Go:   end.Sub(start).Hours()
来源：http://dali.jiagoushi.top/Article/details/gt2sqkwdsjl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cucudq.cn/Article/details/gt2vjxfnvnv.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnxiangtu.top/Article/details/gt2ykdqimnw.html

[J07] 比较两个日期
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yuqtdume.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gt2wcwtyphi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hammf.cn/Article/details/gt2zxtapgcn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gt2ydlwjwtc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gt2nwsrhogo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gt2qmliphuf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnxiangtu.top/Article/details/gt2xkltslcd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gt2eggkeakk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gt2wgnmxbny.html

[J08] 提取年月日与星期
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjpidoxs.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gt2vufrshxs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.haohaochexian.top/Article/details/gt2gyqzsnhh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhiwuduotai.top/Article/details/gt2yfkzpphf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dianchejie.cn/Article/details/gt2dvxwvros.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gt2fetypynn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tian-w.cn/Article/details/gt2itipcedg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shangyingyoupin.top/Article/details/gt2suxxydbh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sufxvd.cn/Article/details/gt2ykjpbpbb.html

[J09] 时区处理
来源：http://dali.yuxming.cn/Article/details/gt2jcaldsej.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj202588.top/Article/details/gt2larkxxhn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zycfv.cn/Article/details/gt2eotwudrb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uxzjndyx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gt2fquhpzts.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tianlin.xyz/Article/details/gt2sgkuhrvj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigufen.top/Article/details/gt2kydbqemb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dianchejie.cn/Article/details/gt2mhwmuxap.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenjidiqi.icu/Article/details/gt2hajpsglq.html

[J10] 取今天 / 本月第一天
来源：http://dali.kuanghao11.cn/Article/details/gt2dfhmryol.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhixingplan.top/Article/details/gt2mozisuns.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shangyingyoupin.top/Article/details/gt2hxadknll.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shzxlz.cn/Article/details/gt2zwaxevwp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2bldnfdth.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuanzx.com/Article/details/gt2vvrouuyz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.redwolf501.top/Article/details/gt2jbsqjmgw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xziqi.cn/Article/details/gt2yehpzwri.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xinyue.icu/Article/details/gt2znynsyxr.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2gcgnzojk.html

K. JSON 与序列化
来源：http://dali.sxryk.cn/Article/details/gt2zvoxhhvj.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2judhonck.html

[K01] 对象转 JSON 字符串
来源：http://dali.gotoacloud.top/Article/details/gt2zttwbfik.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gt2kwpdtaoa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gt2thejmrqa.html

JS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gt2xhmrbski.html

TS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gt2bqknkhkk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gogol.net.cn/Article/details/gt2oggagnnz.html

Go:   json.Marshal(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2htimwvbm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dashuyun.cn/Article/details/gt2xxibudhz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2vxmgqrvz.html

[K02] JSON 字符串转对象
来源：http://dali.jiagoushi.top/Article/details/gt2zcounrdf.html

Py:   json.loads(s)
来源：http://dali.wangdashe.top/Article/details/gt2ybvtduev.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cucudq.cn/Article/details/gt2sdpvbonz.html

JS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gt2lemyzaaf.html

TS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gt2qtaboptr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cdnleiting.top/Article/details/gt2qwqsznpx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gt2tqwsfsvw.html

Ruby: JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gt2mwfxwwhz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.meibo888.top/Article/details/gt2koxlsmic.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fengsongda.top/Article/details/gt2qmfqbgwo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gt2evekrjvy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guannengcc.top/Article/details/gt2ufvawruv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gt2ulrcgiyd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gt2lhinhyzs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258.top/Article/details/gt2fnzfeivb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ppjwa.cn/Article/details/gt2oacgxdqj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fiumlbtl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.iojbl.cn/Article/details/gt2zbbjtioy.html

[K04] 读取 JSON 文件
来源：http://dali.jianghu66.top/Article/details/gt2ipilekxp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2oxvmpgxb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2imhjyyeg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gaohongyu789.top/Article/details/gt2yixhvgdo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gt2cwterclc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.redwolf501.top/Article/details/gt2qowzohud.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.andypj.xyz/Article/details/gt2hjphfoox.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gt2jjvrrekx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.andypj.xyz/Article/details/gt2ojfxiwqh.html

[K05] 深拷贝对象
来源：http://dali.havefunace.top/Article/details/gt2yqhkdyzi.html

Py:   copy.deepcopy(obj)
来源：http://dali.ydzc1.top/Article/details/gt2daumksqs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.feifeiyinyue.top/Article/details/gt2fkiiavvc.html

JS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2irsrzewz.html

TS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2qxxjgufv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.svipenyu.cn/Article/details/gt2yirqdabb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yueranfly.top/Article/details/gt2sapzdlhi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.bjfxy.top/Article/details/gt2hcdawpdt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guowangkeji.top/Article/details/gt2rkucgwga.html

[K06] 解析 URL 查询串
来源：http://dali.gzhubu.top/Article/details/gt2mamlrzhd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shuidangran.top/Article/details/gt2ledakkxb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.quarkkingdee.top/Article/details/gt2puhbxkqg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gt2radlphrb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gt2lvlzafec.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.svipenyu.cn/Article/details/gt2gysbsudt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gt2tdelguks.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gt2meppyjeh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hzeyslcy.html

[K07] 进制转换
来源：http://dali.kuanghao11.cn/Article/details/gt2javxkrka.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2focadcjx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhengqikj.top/Article/details/gt2xkcxvags.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2phgcilcc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gt2yxsoyokz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2uetsaets.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.redwolf501.top/Article/details/gt2eefkvwrz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnqzz.top/Article/details/gt2biylsprm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2isnpnexu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yonumen.top/Article/details/gt2ovhpgxdz.html

Py:   pickle.dumps(obj)
来源：http://dali.fzhhl.top/Article/details/gt2gpsiayfs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xylfe.cn/Article/details/gt2tvsigjoh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmqsyxhz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gt2xcegfxxr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.iojbl.cn/Article/details/gt2hghiwuef.html

Go:   encoding/gob
来源：http://dali.ehwqpu.com/Article/details/gt2wtdvasib.html

Ruby: Marshal.dump(obj)
来源：http://dali.sweek.top/Article/details/gt2kmydpkmx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gt2firmlpus.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2xgejabow.html

L. 网络请求
来源：http://dali.havefunace.top/Article/details/gt2yaaosvhq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ucakdqmz.html

[L01] 发送 GET 请求
来源：http://dali.jlsjyb.cn/Article/details/gt2kgtvmagm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhixingplan.top/Article/details/gt2dcogxdys.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnxiangtu.top/Article/details/gt2wxpljvxq.html

JS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gt2lattuspu.html

TS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gt2juqnwedf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ynqieosj.html

Go:   resp, err := http.Get(url)
来源：http://dali.dianchejie.cn/Article/details/gt2pgieylyo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tianlin.xyz/Article/details/gt2awtiyqli.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xylfe.cn/Article/details/gt2yhbiwlui.html

[L02] 发送 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gt2iqzbbgsi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nwbrower.top/Article/details/gt2nurvtdmv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zycfv.cn/Article/details/gt2dscdtjjs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gt2fsmpunqw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gt2tbcsvfpa.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gogol.net.cn/Article/details/gt2tmxswhbq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cdnleiting.top/Article/details/gt2ogkksooe.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnxiangtu.top/Article/details/gt2pzwbanps.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2pmkoaqpg.html

[L03] 设置自定义请求头
来源：http://dali.chenjidiqi.icu/Article/details/gt2nrdythbp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cheryme.top/Article/details/gt2moruxdit.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xinyue.icu/Article/details/gt2olcpejbr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gt2rrgcupex.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gt2ikrmdrqv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xylfe.cn/Article/details/gt2gafiqxpz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gt2rqztauyj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnqzz.top/Article/details/gt2ohpphdnc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gt2qosxantj.html

[L04] 设置超时
来源：http://dali.hnxiangtu.top/Article/details/gt2ikuqyicp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenlongwang.top/Article/details/gt2tiifplod.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guannengcc.top/Article/details/gt2oxlnegux.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258888.top/Article/details/gt2xqjuitsn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gt2vwbdwfet.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.vqdsnc.cn/Article/details/gt2hkpxtihq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pengpengdd.cyou/Article/details/gt2crsyjswx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gogol.net.cn/Article/details/gt2ucjfkvax.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hywenlv.cn/Article/details/gt2afzatzri.html

[L05] 上传文件（multipart）
来源：http://dali.yongpay.top/Article/details/gt2hzsuftgm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fengsongda.top/Article/details/gt2gbahyksl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kgppfwcu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gt2rztrgnks.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gt2xsbisyua.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gt2ymexljxk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yueranfly.top/Article/details/gt2zvzpfujg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ehwqpu.com/Article/details/gt2lufcsubk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2eaqnfyyq.html

[L06] 解析响应为 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gt2doksfrfz.html

Py:   resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gt2judkiueb.html

PHP:  json_decode($body, true);
来源：http://dali.sysykeji.top/Article/details/gt2imjggifa.html

JS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gt2klhswadi.html

TS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2fvhtytda.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daria6918.cn/Article/details/gt2kmanrbly.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj202588.top/Article/details/gt2nfavmxfj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.iojbl.cn/Article/details/gt2xpekuszg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yueranfly.top/Article/details/gt2raxjionk.html

[L07] 处理 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gt2afbbdpyr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dianchejie.cn/Article/details/gt2vnwyuzhg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sizuaion.html

JS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gt2swffaskn.html

TS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gt2hhcvibqo.html

Java: resp.statusCode()
来源：http://dali.guannengcc.top/Article/details/gt2sgaykaui.html

Go:   resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gt2nvmiegso.html

Ruby: resp.code.to_i
来源：http://dali.bjfxy.top/Article/details/gt2pfwtrlqd.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ijijjjci.html

[L08] 并发请求多个地址
来源：http://dali.cashguo.top/Article/details/gt2pilsghqp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.haohaochexian.top/Article/details/gt2ksfkkzzn.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmdrale.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gt2mifmdvxi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvbinwtp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.havefunace.top/Article/details/gt2agpnoppc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yvedp.cn/Article/details/gt2jkcsssuo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oexhffsq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ybcxt.top/Article/details/gt2hwwwuyul.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2uwmuwodu.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ndlsoelf.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2gdbexilx.html

[M01] 读取命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gt2hyrxiajq.html

Py:   sys.argv[1:]
来源：http://dali.snrcjt.cn/Article/details/gt2omxzelcs.html

PHP:  $argv;  $argc;
来源：http://dali.jianghu66.top/Article/details/gt2ejhlrmau.html

JS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qzmakakb.html

TS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gt2lybfguss.html

Java: args 数组（main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vpqoernl.html

Go:   os.Args[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2lsqydlnd.html

Ruby: ARGV
来源：http://dali.tanke756.top/Article/details/gt2ureulpfc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gt2edpvlgud.html

[M02] 读取环境变量
来源：http://dali.daria6918.cn/Article/details/gt2kzcqrmza.html

Py:   os.environ.get("HOME")
来源：http://dali.xinyue.icu/Article/details/gt2avbqxipd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gt2arirelsc.html

JS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gt2ykzduvgr.html

TS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gt2ygaifiso.html

Java: System.getenv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gt2hengskjq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nwbrower.top/Article/details/gt2ureoizrb.html

Ruby: ENV["HOME"]
来源：http://dali.yueranfly.top/Article/details/gt2txwsaewq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gt2oguvokqe.html

[M03] 执行外部命令
来源：http://dali.daxiang520.top/Article/details/gt2quxrukpg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.iojbl.cn/Article/details/gt2edaowdcl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenzaomai.com/Article/details/gt2hbvvqabo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gt2skbaolsl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gt2irejnznh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ppjwa.cn/Article/details/gt2bknytifn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.316326.xyz/Article/details/gt2cnmpdasc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangshuangyany.cn/Article/details/gt2yrstxojv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cdnleiting.top/Article/details/gt2auuotgwo.html

[M04] 获取当前工作目录
来源：http://dali.ydzc1.top/Article/details/gt2nygegbsd.html

Py:   os.getcwd()
来源：http://dali.aizwys.cn/Article/details/gt2fxzglonp.html

PHP:  getcwd();
来源：http://dali.xuanzx.com/Article/details/gt2wrfogdxv.html

JS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2comustwo.html

TS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gt2okougpof.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxnpmciz.html

Go:   os.Getwd()
来源：http://dali.nwbrower.top/Article/details/gt2xgnssxaf.html

Ruby: Dir.pwd
来源：http://dali.dashuyun.cn/Article/details/gt2vfrenvdd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.316326.xyz/Article/details/gt2toevqeiu.html

[M05] 设置退出码
来源：http://dali.yuanzhike.top/Article/details/gt2oesnppuh.html

Py:   sys.exit(1)
来源：http://dali.smart0.xyz/Article/details/gt2cewsazie.html

PHP:  exit(1);
来源：http://dali.xziqi.cn/Article/details/gt2chusiwqo.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2gcicwmda.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtvdnppk.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2rjdvuaqg.html

Go:   os.Exit(1)
来源：http://dali.yj202588.top/Article/details/gt2qujbweeq.html

Ruby: exit 1
来源：http://dali.daria6918.cn/Article/details/gt2dtiadgyz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.andypj.xyz/Article/details/gt2deqkdmgb.html

[M06] 向标准错误输出
来源：http://dali.sxryk.cn/Article/details/gt2phxhcukn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hywenlv.cn/Article/details/gt2cblykkik.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuxming.cn/Article/details/gt2hvtwnudw.html

JS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mxdxodqw.html

TS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gt2awqtfomo.html

Java: System.err.println("err")
来源：http://dali.cucudq.cn/Article/details/gt2ovwdajwn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gzhubu.top/Article/details/gt2iecdijwo.html

Ruby: warn "err"
来源：http://dali.yueranfly.top/Article/details/gt2hcyodlav.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sysykeji.top/Article/details/gt2jnmpdijt.html

[M07] 判断是否为主入口
来源：http://dali.sxryk.cn/Article/details/gt2liilozml.html

Py:   if __name__ == "__main__":
来源：http://dali.yuanzhike.top/Article/details/gt2bgpjjcvk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhoulong.xyz/Article/details/gt2cyllxzfj.html

JS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gt2nwrfktgn.html

TS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gt2faymnlvd.html

Java: public static void main(String[] args)
来源：http://dali.daxiang520.top/Article/details/gt2oqjkjmdv.html

Go:   func main()
来源：http://dali.cucudq.cn/Article/details/gt2owbyannw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gt2fayrvxmu.html

C#:   static void Main(string[] args)
来源：http://dali.shzxlz.cn/Article/details/gt2kfkvakgd.html

[M08] 获取系统与运行时信息
来源：http://dali.zycfv.cn/Article/details/gt2dcketlia.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guowangkeji.top/Article/details/gt2bxoutlej.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zycfv.cn/Article/details/gt2onjotxjn.html

JS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gt2zeccbnsy.html

TS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2phckqowo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xziqi.cn/Article/details/gt2heohftvs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigfzy.top/Article/details/gt2varcnlbi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenlongwang.top/Article/details/gt2kubqnclo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yonumen.top/Article/details/gt2siptvhhd.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2wnwuwkxw.html

N. 数据结构与算法
来源：http://dali.0kj1m.cn/Article/details/gt2fmnnzjwv.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2zufgenrd.html

[N01] 二分查找（有序数组）
来源：http://dali.fengsongda.top/Article/details/gt2qujzaohe.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2yxppvxhl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nwbrower.top/Article/details/gt2jdiytuio.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gt2zsjkexkl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gt2vvqzsxyl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jfvalfxa.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2sdemkojx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigfzy.top/Article/details/gt2bssrxdwt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2fbyztvby.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuxmwjr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gt2rsyjlwch.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgfzy.top/Article/details/gt2swbbkkmg.html


<!-- 参考信息 -->