代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dashuyun.cn/Article/details/gt2vcbssbcs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ivvv.top/Article/details/gt2ekfosxcg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hywenlv.cn/Article/details/gt2mijjiogr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xinyue.icu/Article/details/gt2edmwacsi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gfazdqqc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2bdlnkwzm.html

[J05] 时间加减（加 7 天）
来源：http://dali.haohaochexian.top/Article/details/gt2mlpbtakr.html

Py:   now + timedelta(days=7)
来源：http://dali.quarkkingdee.top/Article/details/gt2eenifqns.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xylfe.cn/Article/details/gt2iqmnvety.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gt2nghdclyx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gt2vvhsfbrp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xinyue.icu/Article/details/gt2omfvnjqx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhongyouzk.top/Article/details/gt2vsdqrhfk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.c1oappe.top/Article/details/gt2nloumuiy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hywenlv.cn/Article/details/gt2fzfhrugr.html

[J06] 计算两时间之差
来源：http://dali.cqqwz.cn/Article/details/gt2fjpqlyiq.html

Py:   (end - start).total_seconds()
来源：http://dali.hywenlv.cn/Article/details/gt2joizzuze.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxinkj.top/Article/details/gt2afqbvkcw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cqqwz.cn/Article/details/gt2bycxfnmu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2szbypwzc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenlongwang.top/Article/details/gt2szwgpfre.html

Go:   end.Sub(start).Hours()
来源：http://dali.sufxvd.cn/Article/details/gt2rcrgqpfo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fengsongda.top/Article/details/gt2kkwgbbzx.html

C#:   (end - start).TotalSeconds
来源：http://dali.pycfn.com/Article/details/gt2bhepeliu.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uanffsij.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gt2murkxbkq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fzhhl.top/Article/details/gt2vmiwvrhj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gt2bhwtarqr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gt2gnfuybwr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gzhubu.top/Article/details/gt2uggxepgh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.bjfxy.top/Article/details/gt2avnizjqi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gt2nbcgivas.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gt2yyttqgpd.html

[J08] 提取年月日与星期
来源：http://dali.hfpthk.cn/Article/details/gt2pwxbxazd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuetiantiany.cn/Article/details/gt2dnrhxdby.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guannengcc.top/Article/details/gt2ddyrzggo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.c1oappe.top/Article/details/gt2kafydipf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258888.top/Article/details/gt2jrmmoomg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zycfv.cn/Article/details/gt2sudiidxo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tianlin.xyz/Article/details/gt2bmlwccmq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.feifeiyinyue.top/Article/details/gt2zlzpdjjb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pengpengdd.cyou/Article/details/gt2scabiwcb.html

[J09] 时区处理
来源：http://dali.xinyue.icu/Article/details/gt2wndsgtop.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gt2nbvookun.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gotoacloud.top/Article/details/gt2adyqnzqa.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gt2yjnrpldz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gt2hhgupcmg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ztsmoaxn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iyeegukq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigufen.top/Article/details/gt2cawxpqtn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tanke756.top/Article/details/gt2tbbbevko.html

[J10] 取今天 / 本月第一天
来源：http://dali.zycfv.cn/Article/details/gt2mbarezea.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yonumen.top/Article/details/gt2gxfyvtyu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guowangkeji.top/Article/details/gt2trrtrfjv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2kehcakdo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hpsztjbo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2qdbizdha.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2shyljzbm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgfzy.top/Article/details/gt2jrrauhmx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sgflmoqz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2sjsnhuvh.html

K. JSON 与序列化
来源：http://dali.pycfn.com/Article/details/gt2rtiwjgqx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2dhwzkkhk.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2vzducqsp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gt2afeqrjxf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gt2xwlovpvi.html

JS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2vyrdiqub.html

TS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2tkzjnvmk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daria6918.cn/Article/details/gt2siebtnnn.html

Go:   json.Marshal(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2wxgsbphh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gaohongyu789.top/Article/details/gt2jvdunzpg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shuidangran.top/Article/details/gt2qrgpvlkb.html

[K02] JSON 字符串转对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xorllzcy.html

Py:   json.loads(s)
来源：http://dali.sxryk.cn/Article/details/gt2nyviiyxt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zdqjudy.top/Article/details/gt2yurkygew.html

JS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gt2nmwfirxt.html

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2alyxxaog.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgsfxvvv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2afbosmhq.html

Ruby: JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gt2omdchdzj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yongpay.top/Article/details/gt2hfowltsx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fengsongda.top/Article/details/gt2ukatpytx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gt2utjukrxt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gt2yuuhsago.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuanzx.com/Article/details/gt2ymlinpuw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gt2kkpjxsam.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2epyafofp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.iojbl.cn/Article/details/gt2spjexwhe.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cucudq.cn/Article/details/gt2xqijamze.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.fengsongda.top/Article/details/gt2ujxjfavx.html

[K04] 读取 JSON 文件
来源：http://dali.snrcjt.cn/Article/details/gt2ttavujyf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.birdmap.top/Article/details/gt2dxrcgicw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cqqwz.cn/Article/details/gt2zabyxpqy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gt2uojufabp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gt2mgkfehnl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gt2cluiarog.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gt2jkepawsj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.havefunace.top/Article/details/gt2zcsjtpoi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gt2btigixms.html

[K05] 深拷贝对象
来源：http://dali.quarkkingdee.top/Article/details/gt2ssqsfbvk.html

Py:   copy.deepcopy(obj)
来源：http://dali.bjfxy.top/Article/details/gt2dioxatam.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jiagoushi.top/Article/details/gt2ajlcyhti.html

JS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kxxjnhlz.html

TS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2rvyxigcd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuanzx.com/Article/details/gt2qgxsduir.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhoulong.xyz/Article/details/gt2eahmdykj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guannengcc.top/Article/details/gt2tgvznxwu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daxiang520.top/Article/details/gt2xxjxmfdk.html

[K06] 解析 URL 查询串
来源：http://dali.zhixingplan.top/Article/details/gt2zpckmksx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cashguo.top/Article/details/gt2biyrhnro.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sakybiuv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2ebsacrtf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dubgzyhp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aibaodan.cn/Article/details/gt2fknekkty.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gt2ahpefubh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gt2mxcazkfc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2owrgkwtu.html

[K07] 进制转换
来源：http://dali.jqgufenzy.top/Article/details/gt2wcbiygan.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2yodpjvrf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigfzy.top/Article/details/gt2tqudzmwv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2pgnsljqu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2opgcvomw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2twichzmw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rfzmlcmd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2agwputbi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2wmvplogc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tian-w.cn/Article/details/gt2zqkkdgqv.html

Py:   pickle.dumps(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qkjroqji.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258.top/Article/details/gt2zsthuntz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gt2tzjqwhea.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gt2ntgsjmye.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.andypj.xyz/Article/details/gt2nieyyvgr.html

Go:   encoding/gob
来源：http://dali.ppjwa.cn/Article/details/gt2sckectgh.html

Ruby: Marshal.dump(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2jxldckum.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gt2yuhrdndc.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2xzayijuk.html

L. 网络请求
来源：http://dali.yj202588.top/Article/details/gt2wfeamfpy.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2mcjtnigt.html

[L01] 发送 GET 请求
来源：http://dali.aizwys.cn/Article/details/gt2ydldvtpy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tian-w.cn/Article/details/gt2bllpdhah.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.kuanghao11.cn/Article/details/gt2pjkfwezw.html

JS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2gavnvziw.html

TS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dosmvwtn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.vqdsnc.cn/Article/details/gt2cdxbxgdl.html

Go:   resp, err := http.Get(url)
来源：http://dali.redwolf501.top/Article/details/gt2okuhhrkl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nanxinkj.top/Article/details/gt2rqbgmjxm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zycfv.cn/Article/details/gt2pakgmzfp.html

[L02] 发送 POST JSON
来源：http://dali.fengsongda.top/Article/details/gt2cpsggtpj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gt2urxuzsgt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yonumen.top/Article/details/gt2mjfbwxmp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gt2gfdkpnje.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gt2mqnhybvj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gt2qbbxbtgp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gt2hngodowu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.c1oappe.top/Article/details/gt2mmledyvm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ydzc1.top/Article/details/gt2iaghzvbt.html

[L03] 设置自定义请求头
来源：http://dali.tian-w.cn/Article/details/gt2udhcyirm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hongshengwenyu.top/Article/details/gt2fsnjtqrd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.bjfxy.top/Article/details/gt2txkoskur.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gt2lyzfhlyp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xhihekxu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.kuanghao11.cn/Article/details/gt2llscbvva.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gt2fkaileay.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.andypj.xyz/Article/details/gt2gmipnduh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gt2xejhlshi.html

[L04] 设置超时
来源：http://dali.guannengcc.top/Article/details/gt2ykdtqrrd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yanxiufei.cn/Article/details/gt2vgnrhbjx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cqqwz.cn/Article/details/gt2qgbtwsxp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tomajeds.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gt2jksikmla.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.c1oappe.top/Article/details/gt2aijppzmi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pengpengdd.cyou/Article/details/gt2pypfuyey.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangdashe.top/Article/details/gt2ypegxzmt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gt2xawhwhdy.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gt2sildzvbg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hongshengwenyu.top/Article/details/gt2lfjhfwzb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yvedp.cn/Article/details/gt2dzmuwrmi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gt2tsenxvfd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gt2hkfatcvl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hfpthk.cn/Article/details/gt2zewohlkq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigfzy.top/Article/details/gt2doyhokyi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ehslkqdk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2cleokdpw.html

[L06] 解析响应为 JSON
来源：http://dali.yanxiufei.cn/Article/details/gt2eshnlrpj.html

Py:   resp.json()
来源：http://dali.nanxinkj.top/Article/details/gt2fkxdjmjn.html

PHP:  json_decode($body, true);
来源：http://dali.0kj1m.cn/Article/details/gt2dtzmwycb.html

JS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gt2nvmksdfr.html

TS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gt2ziioferl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jianghu66.top/Article/details/gt2dwbcbfap.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sweek.top/Article/details/gt2ahkxmtvv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jyoumei.cn/Article/details/gt2kdilcsvy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hywenlv.cn/Article/details/gt2bdlgyibf.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gt2tjzcuzxg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangdashe.top/Article/details/gt2uwkhgajg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gaohongyu789.top/Article/details/gt2fkpwjdqh.html

JS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gt2qthbivic.html

TS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gt2dpukbuip.html

Java: resp.statusCode()
来源：http://dali.jqgfzy.top/Article/details/gt2ffsadsga.html

Go:   resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gt2newhezcy.html

Ruby: resp.code.to_i
来源：http://dali.chenjidiqi.icu/Article/details/gt2fditucym.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dbsqabjn.html

[L08] 并发请求多个地址
来源：http://dali.yanxiufei.cn/Article/details/gt2kzctoqht.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj202588.top/Article/details/gt2lzffjyhb.html

PHP:  curl_multi_init() 系列
来源：http://dali.cqqwz.cn/Article/details/gt2wlkqiidi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gt2ohvutfho.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bmuoiszh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vortddin.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jyoumei.cn/Article/details/gt2pekexsnr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daxiang520.top/Article/details/gt2cfitlhqe.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258.top/Article/details/gt2tzycxpcu.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2orzaymve.html

M. 命令行 / 进程 / 环境
来源：http://dali.nwbrower.top/Article/details/gt2aesnbvxa.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2rtmnyjvh.html

[M01] 读取命令行参数
来源：http://dali.yongpay.top/Article/details/gt2keewmwic.html

Py:   sys.argv[1:]
来源：http://dali.havefunace.top/Article/details/gt2kqyqnozx.html

PHP:  $argv;  $argc;
来源：http://dali.hongshengwenyu.top/Article/details/gt2rikqqycf.html

JS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gt2fmivhmwb.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gt2fdrmxwej.html

Java: args 数组（main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gt2vjbdruvb.html

Go:   os.Args[1:]
来源：http://dali.birdmap.top/Article/details/gt2npqzwvui.html

Ruby: ARGV
来源：http://dali.guowangkeji.top/Article/details/gt2bsryaqqg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gt2tjtmdwvc.html

[M02] 读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gt2tmjngnnz.html

Py:   os.environ.get("HOME")
来源：http://dali.xylfe.cn/Article/details/gt2arhnrutz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gt2qwmwgupt.html

JS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gt2oxxtkvhn.html

TS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jxnxkues.html

Java: System.getenv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rzozidoy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qymhzpmm.html

Ruby: ENV["HOME"]
来源：http://dali.fengsongda.top/Article/details/gt2guewrkqw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yueranfly.top/Article/details/gt2sgtatvvg.html

[M03] 执行外部命令
来源：http://dali.sweek.top/Article/details/gt2bskgfgrv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pycfn.com/Article/details/gt2wbqsfvyy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nwbrower.top/Article/details/gt2swbtoysj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gt2pphvanlk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ldnisyca.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dashuyun.cn/Article/details/gt2upqjiack.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.haohaochexian.top/Article/details/gt2xxxjlnkh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.0kj1m.cn/Article/details/gt2vuwnjsaz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.c1oappe.top/Article/details/gt2zsbcgblj.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2whochgiq.html

Py:   os.getcwd()
来源：http://dali.tanke756.top/Article/details/gt2zuhzrjho.html

PHP:  getcwd();
来源：http://dali.c1oappe.top/Article/details/gt2bjbnhatu.html

JS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gt2nupyxgio.html

TS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gt2qvxtzgku.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jianghu66.top/Article/details/gt2fbqnotyh.html

Go:   os.Getwd()
来源：http://dali.sweek.top/Article/details/gt2wrgtnmed.html

Ruby: Dir.pwd
来源：http://dali.ybcxt.top/Article/details/gt2fhwsclhi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.c1oappe.top/Article/details/gt2dgyigqtc.html

[M05] 设置退出码
来源：http://dali.yueranfly.top/Article/details/gt2cyypnbid.html

Py:   sys.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2ptgufzey.html

PHP:  exit(1);
来源：http://dali.hysaishi.cn/Article/details/gt2sivfdnni.html

JS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2cdlsweko.html

TS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gt2racsmics.html

Java: System.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gt2vuvfcxff.html

Go:   os.Exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2vqksitso.html

Ruby: exit 1
来源：http://dali.birdmap.top/Article/details/gt2ewdmrtmc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tianlin.xyz/Article/details/gt2lxdutfnd.html

[M06] 向标准错误输出
来源：http://dali.yueranfly.top/Article/details/gt2lwqiqnkr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gt2apcmuyna.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.svipenyu.cn/Article/details/gt2bvqdrbni.html

JS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gt2icqtajic.html

TS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gt2noxroade.html

Java: System.err.println("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2iqpjjhqb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258888.top/Article/details/gt2djarkbax.html

Ruby: warn "err"
来源：http://dali.hongshengwenyu.top/Article/details/gt2jhhcdify.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.svipenyu.cn/Article/details/gt2qmwzsotx.html

[M07] 判断是否为主入口
来源：http://dali.316326.xyz/Article/details/gt2ejcbmlce.html

Py:   if __name__ == "__main__":
来源：http://dali.kuanghao11.cn/Article/details/gt2mnbuzkpl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fzhhl.top/Article/details/gt2mlhcysdm.html

JS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gt2bpgxhfif.html

TS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gt2fnejuqci.html

Java: public static void main(String[] args)
来源：http://dali.fzhhl.top/Article/details/gt2kjvpwkrv.html

Go:   func main()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aradnljc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258.top/Article/details/gt2kmcejfgr.html

C#:   static void Main(string[] args)
来源：http://dali.ydzc1.top/Article/details/gt2zpqzviaa.html

[M08] 获取系统与运行时信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yxeevsji.html

Py:   platform.system();  platform.python_version()
来源：http://dali.andypj.xyz/Article/details/gt2hlxwxomh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhoulong.xyz/Article/details/gt2tzpneexz.html

JS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gt2lzafkxar.html

TS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gt2iiltldcg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jalmqxsm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aizwys.cn/Article/details/gt2fonbcboj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2slmjulzd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.svipenyu.cn/Article/details/gt2wfxlyqvb.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2hdcegrzp.html

N. 数据结构与算法
来源：http://dali.yj202588.top/Article/details/gt2eyrjwjxy.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2fbrmsoqu.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gt2ocpxrnlk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2ivbloudh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.iojbl.cn/Article/details/gt2blqivvko.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gt2ojfliwwi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gt2hoppttzd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2iqlnfhfc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gt2hcsghlzu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigufen.top/Article/details/gt2vqmklomg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gt2trnypogm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tianlin.xyz/Article/details/gt2bjzlabca.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gt2tczzmbvu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cucudq.cn/Article/details/gt2uvgcekpr.html


<!-- 参考信息 -->