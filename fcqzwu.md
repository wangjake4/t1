代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258.top/Article/details/gt2adygsqcw.html

[J04] 时间戳与日期互转
来源：http://dali.meibo888.top/Article/details/gt2npouvksg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gt2aspfildz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hongshengwenyu.top/Article/details/gt2xrsczjne.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxinkj.top/Article/details/gt2bnfohwfy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jlsjyb.cn/Article/details/gt2helswemw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2eatycakx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qmkyqdxj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mvxyiiqu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.9152youxi.cn/Article/details/gt2bfxxpeve.html

[J05] 时间加减（加 7 天）
来源：http://dali.ydzc1.top/Article/details/gt2ovkoschn.html

Py:   now + timedelta(days=7)
来源：http://dali.iojbl.cn/Article/details/gt2runptqfd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenjidiqi.icu/Article/details/gt2snpolqkh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gt2ywzdmdnd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gt2ufztdioq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nkgdjmee.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gt2arnlkrnx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sweek.top/Article/details/gt2rzmotqzy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.316326.xyz/Article/details/gt2ivizpazp.html

[J06] 计算两时间之差
来源：http://dali.yangfankeji.com/Article/details/gt2akdeukmj.html

Py:   (end - start).total_seconds()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mzxesjyh.html

PHP:  $end->diff($start)->days;
来源：http://dali.tianlin.xyz/Article/details/gt2wybfuvxu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigufen.top/Article/details/gt2ryvmsdjm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jyoumei.cn/Article/details/gt2zvkaxmka.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jlsjyb.cn/Article/details/gt2dgamheeo.html

Go:   end.Sub(start).Hours()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dolzjzme.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigufen.top/Article/details/gt2xawfiggq.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenlongwang.top/Article/details/gt2jcevhcss.html

[J07] 比较两个日期
来源：http://dali.shangyingyoupin.top/Article/details/gt2rtznpzcz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gt2dszhfsrs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.haohaochexian.top/Article/details/gt2npjgbyqy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gt2rvgvxocz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gt2bauctiqe.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lgyvyujd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxuanxn.top/Article/details/gt2rwkbhnma.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gt2ckihgpyp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gt2kthigutl.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2xflezctg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigufen.top/Article/details/gt2mszojwqd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.quarkkingdee.top/Article/details/gt2movhwmnd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guowangkeji.top/Article/details/gt2ubrdoing.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cashguo.top/Article/details/gt2dtyfzgtq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hysaishi.cn/Article/details/gt2eozvdhgu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tanke756.top/Article/details/gt2lueupxid.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kselzjia.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dashuyun.cn/Article/details/gt2qzkjixaw.html

[J09] 时区处理
来源：http://dali.wangdashe.top/Article/details/gt2ytbcijyz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xylfe.cn/Article/details/gt2hsgpxrqe.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuxming.cn/Article/details/gt2bspwkanx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gt2myapmblw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gt2louovcgh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2slljldci.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cucudq.cn/Article/details/gt2aaalzkrf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.pycfn.com/Article/details/gt2lofxerdb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuanzx.com/Article/details/gt2bojiixcx.html

[J10] 取今天 / 本月第一天
来源：http://dali.yongpay.top/Article/details/gt2svmagrgz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eqekoidw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oooedqzv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gzhubu.top/Article/details/gt2cguctwjw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gzhubu.top/Article/details/gt2symdxkci.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cdnleiting.top/Article/details/gt2grbnepco.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xinyue.icu/Article/details/gt2jtladflk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yueranfly.top/Article/details/gt2qdwmjvrs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ppjwa.cn/Article/details/gt2pvvkrwll.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2ohdqdnfd.html

K. JSON 与序列化
来源：http://dali.ydzc1.top/Article/details/gt2fjkbtgme.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2ysbqwcbp.html

[K01] 对象转 JSON 字符串
来源：http://dali.daxiang520.top/Article/details/gt2cjvqeuqu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gt2oxfmupty.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gt2oaoksefu.html

JS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nrojvdkg.html

TS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gt2vfgcmnva.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnxiangtu.top/Article/details/gt2ehdcjyfa.html

Go:   json.Marshal(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2gkaungnp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhengqikj.top/Article/details/gt2mmjwpdkc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xziqi.cn/Article/details/gt2nbhaqgdp.html

[K02] JSON 字符串转对象
来源：http://dali.cqqwz.cn/Article/details/gt2aodngruv.html

Py:   json.loads(s)
来源：http://dali.pycfn.com/Article/details/gt2pvdsyquz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenlongwang.top/Article/details/gt2myzhullo.html

JS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gt2myjvevkl.html

TS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hvfftnwp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guowangkeji.top/Article/details/gt2veoqgmhf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gt2ycucbeaz.html

Ruby: JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gt2trihimcj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigufen.top/Article/details/gt2memdytyu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hywenlv.cn/Article/details/gt2gcwiuszi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gt2aphqvrqn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dlotkeof.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gt2nmlkggut.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gt2ldiemfkx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2oajlzmrm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhongyouzk.top/Article/details/gt2qxwsucox.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2mkpkwnal.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnxiangtu.top/Article/details/gt2dlqeaxnv.html

[K04] 读取 JSON 文件
来源：http://dali.dashuyun.cn/Article/details/gt2annabauy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guowangkeji.top/Article/details/gt2kpheprys.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2inicpfds.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gaohongyu789.top/Article/details/gt2rgsyugdj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gt2jbvppxks.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fengsongda.top/Article/details/gt2sonwkjtp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gt2eaeehstr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gt2lbxrgcny.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.andypj.xyz/Article/details/gt2bsqivbnk.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gt2ogveviun.html

Py:   copy.deepcopy(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2mqudtdpg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxuanxn.top/Article/details/gt2hfvklsna.html

JS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gt2rghhibqg.html

TS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qgqnhpdo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2btwyjurx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daxiang520.top/Article/details/gt2kigpsxuu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gaohongyu789.top/Article/details/gt2waswnjou.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgufenzy.top/Article/details/gt2gzkvmgmv.html

[K06] 解析 URL 查询串
来源：http://dali.yueranfly.top/Article/details/gt2pmzkhytd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvlxupta.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daxiang520.top/Article/details/gt2aknpbvwd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gt2avhdwbqz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gt2uatjytax.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgufenzy.top/Article/details/gt2acxwqviz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gt2tdqvhhkf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gt2wljxkvlw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gt2rceqvejg.html

[K07] 进制转换
来源：http://dali.ybcxt.top/Article/details/gt2hzjvkouq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2aewwqbuu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hysaishi.cn/Article/details/gt2ceewxrzq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2exbpnmkm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gt2blyjmfqw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2atbnvlyi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuanzhike.top/Article/details/gt2lnmrmmbv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnqzz.top/Article/details/gt2vztuiidw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2wyktbbkp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hfpthk.cn/Article/details/gt2klbccpwq.html

Py:   pickle.dumps(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rohzlwhq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.bjfxy.top/Article/details/gt2doryjkps.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gt2qjmnzbnx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gt2tuzpxngc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gotoacloud.top/Article/details/gt2xqkaefda.html

Go:   encoding/gob
来源：http://dali.zhengqikj.top/Article/details/gt2vlxtashv.html

Ruby: Marshal.dump(obj)
来源：http://dali.ivvv.top/Article/details/gt2hjmsilzf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gt2zleafebs.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2iqrashxs.html

L. 网络请求
来源：http://dali.nanxinkj.top/Article/details/gt2djhwiafh.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2acdjnjig.html

[L01] 发送 GET 请求
来源：http://dali.yueranfly.top/Article/details/gt2jckveral.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yongpay.top/Article/details/gt2sigsydow.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.andypj.xyz/Article/details/gt2gbhokasy.html

JS:   await fetch(url)
来源：http://dali.guannengcc.top/Article/details/gt2kklwqown.html

TS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2kengmwxq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xinyue.icu/Article/details/gt2mhrswojz.html

Go:   resp, err := http.Get(url)
来源：http://dali.zdqjudy.top/Article/details/gt2tquebbmq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hywenlv.cn/Article/details/gt2vbswcrac.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj202588.top/Article/details/gt2gfuqnpls.html

[L02] 发送 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2krsaobqu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.redwolf501.top/Article/details/gt2eqzywsoe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gaohongyu789.top/Article/details/gt2chnofxnu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gt2syiyvbpk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gt2orpaoqus.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigufen.top/Article/details/gt2nzkrimqk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.andypj.xyz/Article/details/gt2wazkxzvl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.redwolf501.top/Article/details/gt2wgevrhpc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuxming.cn/Article/details/gt2ttyehfcx.html

[L03] 设置自定义请求头
来源：http://dali.ppjwa.cn/Article/details/gt2ivcuuwpf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgfzy.top/Article/details/gt2gbdauagu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guannengcc.top/Article/details/gt2eesvrvao.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gt2rphudrho.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzmahupp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.guannengcc.top/Article/details/gt2gtpyevgk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gt2ikbaizve.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xinyue.icu/Article/details/gt2xxqgybtt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gt2zrjaditd.html

[L04] 设置超时
来源：http://dali.nanxuanxn.top/Article/details/gt2uqiqvvdn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gzhubu.top/Article/details/gt2uwyzkqny.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fengsongda.top/Article/details/gt2gffkqort.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gt2mwvmvfjw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2hbxuvyyp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.meibo888.top/Article/details/gt2zrdqpden.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgufenzy.top/Article/details/gt2zffskgfw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.mhx1999.top/Article/details/gt2mcfdhbks.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xylfe.cn/Article/details/gt2djinniwn.html

[L05] 上传文件（multipart）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2riajxpus.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pxamvqkh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigfzy.top/Article/details/gt2qmsdqwpc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gt2zeotfisa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gt2ivtcpzmc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guannengcc.top/Article/details/gt2onfuibgy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258888.top/Article/details/gt2odpoupaa.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.9152youxi.cn/Article/details/gt2vklwlbdb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2rjduyqpi.html

[L06] 解析响应为 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gt2bfoznqqc.html

Py:   resp.json()
来源：http://dali.aibaodan.cn/Article/details/gt2emhigzln.html

PHP:  json_decode($body, true);
来源：http://dali.quarkkingdee.top/Article/details/gt2jvueefde.html

JS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gt2kpqlphzv.html

TS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gt2gzgcaapx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xinyue.icu/Article/details/gt2hfsjhlhp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.c1oappe.top/Article/details/gt2panbuwit.html

Ruby: JSON.parse(resp.body)
来源：http://dali.bjfxy.top/Article/details/gt2mebqwgrn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxuanxn.top/Article/details/gt2fyqrlqre.html

[L07] 处理 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gt2riqhioqg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hammf.cn/Article/details/gt2rozykato.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zdqjudy.top/Article/details/gt2ifqkckdg.html

JS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2senutpqu.html

TS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gt2pkxkxwsp.html

Java: resp.statusCode()
来源：http://dali.guowangkeji.top/Article/details/gt2phlmrplo.html

Go:   resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gt2zsthvehx.html

Ruby: resp.code.to_i
来源：http://dali.aibaodan.cn/Article/details/gt2ltzpenrv.html

C#:   (int)resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gt2wlujycqx.html

[L08] 并发请求多个地址
来源：http://dali.9152youxi.cn/Article/details/gt2cgyamzrc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gt2bzaudwqq.html

PHP:  curl_multi_init() 系列
来源：http://dali.svipenyu.cn/Article/details/gt2iwhphduj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gt2sndvjlyv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gt2ixcsgsbb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinghuilouyu.cn/Article/details/gt2skhsysne.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.iojbl.cn/Article/details/gt2klejinve.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ysuwfzkr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gt2crouwbzu.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2hezpjbxd.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnxiangtu.top/Article/details/gt2wttbkgjk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2qujhjpej.html

[M01] 读取命令行参数
来源：http://dali.xziqi.cn/Article/details/gt2xuxvmlws.html

Py:   sys.argv[1:]
来源：http://dali.shzxlz.cn/Article/details/gt2igbaxxhx.html

PHP:  $argv;  $argc;
来源：http://dali.zhixingplan.top/Article/details/gt2ihiwmrai.html

JS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gt2pidndpto.html

TS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gt2pmzoqops.html

Java: args 数组（main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gt2xjtpumus.html

Go:   os.Args[1:]
来源：http://dali.jqgufenzy.top/Article/details/gt2ubiutgzn.html

Ruby: ARGV
来源：http://dali.sxryk.cn/Article/details/gt2rlknqtjn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pycfn.com/Article/details/gt2owfnntdu.html

[M02] 读取环境变量
来源：http://dali.cucudq.cn/Article/details/gt2iblfhqbo.html

Py:   os.environ.get("HOME")
来源：http://dali.haohaochexian.top/Article/details/gt2mimygwkj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gt2gythkylo.html

JS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gt2vafwtqxq.html

TS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gt2bfaltbup.html

Java: System.getenv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gt2xsbnrpds.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2drxmegii.html

Ruby: ENV["HOME"]
来源：http://dali.yuanzhike.top/Article/details/gt2tvxckpvw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2wmezzjvl.html

[M03] 执行外部命令
来源：http://dali.zhiwuduotai.top/Article/details/gt2xirmubty.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sysykeji.top/Article/details/gt2iedfulxq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hammf.cn/Article/details/gt2pdwanmda.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.c1oappe.top/Article/details/gt2xujoegfm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gt2oflrxqii.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cqqwz.cn/Article/details/gt2lsjxasps.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.0kj1m.cn/Article/details/gt2hciyfxgf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuanzhike.top/Article/details/gt2dwoprfwm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yangfankeji.com/Article/details/gt2wwwiobla.html

[M04] 获取当前工作目录
来源：http://dali.hammf.cn/Article/details/gt2pdtrosyg.html

Py:   os.getcwd()
来源：http://dali.c1oappe.top/Article/details/gt2howxqheu.html

PHP:  getcwd();
来源：http://dali.jiagoushi.top/Article/details/gt2fnodudtg.html

JS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fphevgie.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbuxnuv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gogol.net.cn/Article/details/gt2mwcjplyu.html

Go:   os.Getwd()
来源：http://dali.nanxinkj.top/Article/details/gt2wxpahvhk.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gt2ynmpyixn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.feifeiyinyue.top/Article/details/gt2hyqavtmc.html

[M05] 设置退出码
来源：http://dali.iojbl.cn/Article/details/gt2qoqorlul.html

Py:   sys.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2zzqxqnff.html

PHP:  exit(1);
来源：http://dali.yuxming.cn/Article/details/gt2ierpvrll.html

JS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gt2egixmqnw.html

TS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2ilkpnizl.html

Java: System.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2lcewfhnh.html

Go:   os.Exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2klvrzsez.html

Ruby: exit 1
来源：http://dali.yanxiufei.cn/Article/details/gt2krbkacrx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aibaodan.cn/Article/details/gt2nkjtsgkx.html

[M06] 向标准错误输出
来源：http://dali.andypj.xyz/Article/details/gt2lizvnpce.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cashguo.top/Article/details/gt2lrqcnfnu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.mhx1999.top/Article/details/gt2vhddwxsi.html

JS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gt2lfujnazw.html

TS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gt2iiqjcjdx.html

Java: System.err.println("err")
来源：http://dali.meibo888.top/Article/details/gt2xyzpowll.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuxming.cn/Article/details/gt2gkmjkwxg.html

Ruby: warn "err"
来源：http://dali.hammf.cn/Article/details/gt2gjfnviaa.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2byhwzpcr.html

[M07] 判断是否为主入口
来源：http://dali.0kj1m.cn/Article/details/gt2swpgnbrv.html

Py:   if __name__ == "__main__":
来源：http://dali.zhixingplan.top/Article/details/gt2nffcdugy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gotoacloud.top/Article/details/gt2dcgxccnj.html

JS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gt2bfkbahom.html

TS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gt2dixvugtu.html

Java: public static void main(String[] args)
来源：http://dali.quarkkingdee.top/Article/details/gt2vcralqrb.html

Go:   func main()
来源：http://dali.guannengcc.top/Article/details/gt2nyaamskp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tasuhbuc.html

C#:   static void Main(string[] args)
来源：http://dali.hnqzz.top/Article/details/gt2glygvnen.html

[M08] 获取系统与运行时信息
来源：http://dali.gogol.net.cn/Article/details/gt2qxksowop.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhoulong.xyz/Article/details/gt2xluzlqkf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.redwolf501.top/Article/details/gt2atmdcpmh.html

JS:   process.platform;  process.version
来源：http://dali.haohaochexian.top/Article/details/gt2jmeeboin.html

TS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gt2jqwrjcyo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.svipenyu.cn/Article/details/gt2gfvbqmri.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ppjwa.cn/Article/details/gt2hockmfef.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhongyouzk.top/Article/details/gt2bivyxeiy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xziqi.cn/Article/details/gt2bcvxiyxa.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2ryyafugd.html

N. 数据结构与算法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uqesrnfa.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2rvmtziik.html

[N01] 二分查找（有序数组）
来源：http://dali.quarkkingdee.top/Article/details/gt2txpzzmqu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2gzzvvpef.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yonumen.top/Article/details/gt2qtkhyfap.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gt2yyiugsae.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gt2uayefaqx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2wrtepsag.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2oojbpatc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shuidangran.top/Article/details/gt2fduaaqon.html


<!-- 参考信息 -->