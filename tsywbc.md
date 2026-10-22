代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2amwcutch.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gt2dklcewcy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2kjmotaqy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2piugayyx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cqqwz.cn/Article/details/gt2xywgdzmi.html

[J04] 时间戳与日期互转
来源：http://dali.meibo888.top/Article/details/gt2gomdnzhx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nwbrower.top/Article/details/gt2htvjlhij.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.feifeiyinyue.top/Article/details/gt2uaggemss.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jlsjyb.cn/Article/details/gt2lqqlsaza.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ntjrvxdy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cucudq.cn/Article/details/gt2zxqowvxi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dvbithci.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shuidangran.top/Article/details/gt2imrpdxet.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nwbrower.top/Article/details/gt2aauhrnok.html

[J05] 时间加减（加 7 天）
来源：http://dali.sufxvd.cn/Article/details/gt2mdmhwwbj.html

Py:   now + timedelta(days=7)
来源：http://dali.pycfn.com/Article/details/gt2oisuayyk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vbgyzgwk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gt2jwhgilby.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gt2curmalzm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.smart0.xyz/Article/details/gt2igyyvyky.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gt2dgsuaolw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.smart0.xyz/Article/details/gt2nnodogrz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhengqikj.top/Article/details/gt2dpkshlgt.html

[J06] 计算两时间之差
来源：http://dali.gzhubu.top/Article/details/gt2gjbpwgcf.html

Py:   (end - start).total_seconds()
来源：http://dali.yangfankeji.com/Article/details/gt2cmdasnkx.html

PHP:  $end->diff($start)->days;
来源：http://dali.guowangkeji.top/Article/details/gt2azodaelf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigufen.top/Article/details/gt2ujoinhov.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yueranfly.top/Article/details/gt2bduwuzlh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnxiangtu.top/Article/details/gt2rvwnzlht.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigfzy.top/Article/details/gt2hwxzzaoo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenzaomai.com/Article/details/gt2ogjhduek.html

C#:   (end - start).TotalSeconds
来源：http://dali.jianghu66.top/Article/details/gt2cszsgyon.html

[J07] 比较两个日期
来源：http://dali.hfpthk.cn/Article/details/gt2xbyslpgc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gt2qrfxcmgl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhoulong.xyz/Article/details/gt2cxosafgh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gt2mvjnwqej.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gt2jhefuaoz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgufenzy.top/Article/details/gt2tqhbolrq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenzaomai.com/Article/details/gt2vjnmrpbx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gt2eohujjmu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qjzdcfwg.html

[J08] 提取年月日与星期
来源：http://dali.feifeiyinyue.top/Article/details/gt2sujgqlby.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cucudq.cn/Article/details/gt2gcwubsjg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tianlin.xyz/Article/details/gt2edcregbf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ivvv.top/Article/details/gt2wmlfpvhi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.vqdsnc.cn/Article/details/gt2irzftspm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hongshengwenyu.top/Article/details/gt2tybutzlf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hfpthk.cn/Article/details/gt2asehunig.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxinkj.top/Article/details/gt2xghzlbit.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sufxvd.cn/Article/details/gt2onflpvxa.html

[J09] 时区处理
来源：http://dali.yuxming.cn/Article/details/gt2vvvbnnry.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.andypj.xyz/Article/details/gt2rspqnjwu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daria6918.cn/Article/details/gt2oeiizlty.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gt2rfifypai.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gt2taxtdrnu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cqqwz.cn/Article/details/gt2jvuaaify.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ehwqpu.com/Article/details/gt2zuufzcqd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.0kj1m.cn/Article/details/gt2qkwrjpwi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dianchejie.cn/Article/details/gt2shxbflge.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhixingplan.top/Article/details/gt2kdagyvdi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuanzx.com/Article/details/gt2bglmnkmp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigfzy.top/Article/details/gt2igxclbas.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jiagoushi.top/Article/details/gt2abirpwwm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cashguo.top/Article/details/gt2otzupzit.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fengsongda.top/Article/details/gt2uymejjos.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gt2xcspxplv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.svipenyu.cn/Article/details/gt2odintfhb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tanke756.top/Article/details/gt2zwcabxrd.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2cdcnsoho.html

K. JSON 与序列化
来源：http://dali.vqdsnc.cn/Article/details/gt2dcqisjtx.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2pwpxurlg.html

[K01] 对象转 JSON 字符串
来源：http://dali.hysaishi.cn/Article/details/gt2qyxryzku.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftptfecd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gt2nkgrppeq.html

JS:   JSON.stringify(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2fnbwrhie.html

TS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gt2synxijhm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jiagoushi.top/Article/details/gt2mkkfuryc.html

Go:   json.Marshal(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zpecdzyh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenzaomai.com/Article/details/gt2znwgscqj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zycfv.cn/Article/details/gt2yivwyavj.html

[K02] JSON 字符串转对象
来源：http://dali.gzhubu.top/Article/details/gt2tuddhmsk.html

Py:   json.loads(s)
来源：http://dali.cashguo.top/Article/details/gt2zcqrnxrm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nwbrower.top/Article/details/gt2vpnitnhq.html

JS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gt2wkkjjmts.html

TS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gt2ajpeuqqw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lswnqyyy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jeuxkexq.html

Ruby: JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gt2dtvaljue.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.iojbl.cn/Article/details/gt2xewtvhlm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuanzx.com/Article/details/gt2bqmgigox.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gt2wezmxsli.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gt2qogmklqz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gt2xkishqol.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2oampmxvc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guannengcc.top/Article/details/gt2tljatkil.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhengqikj.top/Article/details/gt2yiryfmcm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jianghu66.top/Article/details/gt2nswegohu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenzaomai.com/Article/details/gt2htilvaos.html

[K04] 读取 JSON 文件
来源：http://dali.hywenlv.cn/Article/details/gt2qhtfhvyf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2sjmzlchf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangdashe.top/Article/details/gt2oapafulx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gt2dfvjoksw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2toafofyu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.mhx1999.top/Article/details/gt2virhlfqa.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gt2ewyyfvgu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gt2lxouubcl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2euqhivyy.html

[K05] 深拷贝对象
来源：http://dali.yangfankeji.com/Article/details/gt2wsyrtcnl.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2vbybnvyz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aibaodan.cn/Article/details/gt2idxunjyd.html

JS:   structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xcijzzgq.html

TS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gezuidvj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxinkj.top/Article/details/gt2ppjmzdmy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cdnleiting.top/Article/details/gt2mszzcend.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.smart0.xyz/Article/details/gt2dgkvfbat.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tanke756.top/Article/details/gt2ycdgsmyu.html

[K06] 解析 URL 查询串
来源：http://dali.316326.xyz/Article/details/gt2qapefzzo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.smart0.xyz/Article/details/gt2ucgxduwa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jyoumei.cn/Article/details/gt2drmpiojz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fvokeovu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gt2mcgbqnsi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.kuanghao11.cn/Article/details/gt2rkuhpuby.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gt2tgiaszan.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gt2zpexatoe.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gt2vbfkkzbz.html

[K07] 进制转换
来源：http://dali.xziqi.cn/Article/details/gt2bolgdckm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2qqqetjif.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sycgxwwq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2yqwttmon.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2nhmrrdmv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2yilahcrf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigufen.top/Article/details/gt2jkrwlzpe.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fzhhl.top/Article/details/gt2kwlrpmcv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2xeekgjvf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sufxvd.cn/Article/details/gt2qwxbtroe.html

Py:   pickle.dumps(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2akfcaouv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yangfankeji.com/Article/details/gt2wqdqlzqe.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gt2grpdauwf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gt2laqufptg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhixingplan.top/Article/details/gt2qddhqfia.html

Go:   encoding/gob
来源：http://dali.nanxinkj.top/Article/details/gt2ucomfamz.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2mnzkwnlg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gt2wbspvfdw.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vrdakept.html

L. 网络请求
来源：http://dali.ybcxt.top/Article/details/gt2agripoxt.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2gtgcfxzr.html

[L01] 发送 GET 请求
来源：http://dali.feifeiyinyue.top/Article/details/gt2rvautapp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fengsongda.top/Article/details/gt2qbunqqds.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xylfe.cn/Article/details/gt2ntafvlbf.html

JS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gt2elcbcjky.html

TS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gt2enjmrgfe.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.meibo888.top/Article/details/gt2dxhbbbny.html

Go:   resp, err := http.Get(url)
来源：http://dali.redwolf501.top/Article/details/gt2fdiixywt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.haohaochexian.top/Article/details/gt2uwoknwsv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sweek.top/Article/details/gt2kqjiixzh.html

[L02] 发送 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gt2wvdledkv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shuidangran.top/Article/details/gt2ffhlsldn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wsxgsbfz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gt2dirivgub.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gt2nlkgntvu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.kuanghao11.cn/Article/details/gt2lvdvqtzd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258888.top/Article/details/gt2qgnrruzl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.birdmap.top/Article/details/gt2uduwimac.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.mhx1999.top/Article/details/gt2eozfbnsk.html

[L03] 设置自定义请求头
来源：http://dali.ehwqpu.com/Article/details/gt2adsqiyow.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2exeqjlth.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zycfv.cn/Article/details/gt2bchqhynd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gt2oaeuujbu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gt2intovtpd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ynpwhbyi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gt2ywwtbxes.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuanzx.com/Article/details/gt2ztaiupbl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gt2hlzittbr.html

[L04] 设置超时
来源：http://dali.gogol.net.cn/Article/details/gt2ixjplyeq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.vqdsnc.cn/Article/details/gt2hbfymnew.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ybcxt.top/Article/details/gt2boglamja.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gt2wphdaeyp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gt2lrwazwam.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhoulong.xyz/Article/details/gt2lnubdhij.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gaohongyu789.top/Article/details/gt2ggkondtb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wdvwuxin.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.feifeiyinyue.top/Article/details/gt2elhgvyoj.html

[L05] 上传文件（multipart）
来源：http://dali.shuidangran.top/Article/details/gt2wavaqxqs.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dianchejie.cn/Article/details/gt2clivyawi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ivvv.top/Article/details/gt2kelrdoxb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gt2qxvpezrx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gt2obxekyin.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuanzhike.top/Article/details/gt2gdnciiuc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nwbrower.top/Article/details/gt2blftxtyv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zycfv.cn/Article/details/gt2polvjcll.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2lhxtzsum.html

[L06] 解析响应为 JSON
来源：http://dali.daxiang520.top/Article/details/gt2vpujyphn.html

Py:   resp.json()
来源：http://dali.smart0.xyz/Article/details/gt2deykykoc.html

PHP:  json_decode($body, true);
来源：http://dali.zhoulong.xyz/Article/details/gt2sfcjbypr.html

JS:   await resp.json()
来源：http://dali.smart0.xyz/Article/details/gt2vvcuodnb.html

TS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gt2olgauktx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gt2hivutndr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fvvxvjxw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxinkj.top/Article/details/gt2evfvfoxd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangdashe.top/Article/details/gt2hxumejam.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gt2enefiqgb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shangyingyoupin.top/Article/details/gt2dkoqkmri.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tian-w.cn/Article/details/gt2mqpcgsqa.html

JS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gt2jhgfzpld.html

TS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gt2yofyzhpf.html

Java: resp.statusCode()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zpjlhavd.html

Go:   resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gt2wnyswipn.html

Ruby: resp.code.to_i
来源：http://dali.gaohongyu789.top/Article/details/gt2kgoyxnmv.html

C#:   (int)resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gt2ckzknrag.html

[L08] 并发请求多个地址
来源：http://dali.gogol.net.cn/Article/details/gt2fapmnhyk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gogol.net.cn/Article/details/gt2fvyrlijo.html

PHP:  curl_multi_init() 系列
来源：http://dali.9152youxi.cn/Article/details/gt2ihxhqjea.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gt2jidxjgdm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2sgfldhxu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgufenzy.top/Article/details/gt2hmhhvaeq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.aizwys.cn/Article/details/gt2krcxncfd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hammf.cn/Article/details/gt2sjpenyvk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2pixegrvh.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2vugfnhim.html

M. 命令行 / 进程 / 环境
来源：http://dali.yangfankeji.com/Article/details/gt2kzaucrcr.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2qqmeqvkq.html

[M01] 读取命令行参数
来源：http://dali.cashguo.top/Article/details/gt2aslfwvff.html

Py:   sys.argv[1:]
来源：http://dali.birdmap.top/Article/details/gt2pvahckxl.html

PHP:  $argv;  $argc;
来源：http://dali.pycfn.com/Article/details/gt2rsbsuauo.html

JS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gt2mvcgvayr.html

TS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gt2nqlvmxys.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gt2lngelcjq.html

Go:   os.Args[1:]
来源：http://dali.yj20258.top/Article/details/gt2zgrkkdjl.html

Ruby: ARGV
来源：http://dali.zhoulong.xyz/Article/details/gt2ditdkivd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gt2fovqpzfg.html

[M02] 读取环境变量
来源：http://dali.hfpthk.cn/Article/details/gt2tjmcymeb.html

Py:   os.environ.get("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2kgmvdwfa.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gqntpxpa.html

JS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gt2agssxhio.html

TS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gt2xunlprtb.html

Java: System.getenv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gt2gydgjmef.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fftvmtef.html

Ruby: ENV["HOME"]
来源：http://dali.cucudq.cn/Article/details/gt2tgzrbkrs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gotoacloud.top/Article/details/gt2gbppltnt.html

[M03] 执行外部命令
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jpjerncj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.feifeiyinyue.top/Article/details/gt2eoncbgul.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tanke756.top/Article/details/gt2heiuzmpx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gt2cbqvgzex.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2irmcoemy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sweek.top/Article/details/gt2ycgwrued.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wfncgltc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yanxiufei.cn/Article/details/gt2qlvufkpr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenlongwang.top/Article/details/gt2kfmsehhx.html

[M04] 获取当前工作目录
来源：http://dali.svipenyu.cn/Article/details/gt2pinyrqbs.html

Py:   os.getcwd()
来源：http://dali.svipenyu.cn/Article/details/gt2tmnwxamq.html

PHP:  getcwd();
来源：http://dali.0kj1m.cn/Article/details/gt2wgcdwvlj.html

JS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gt2zjlecsjp.html

TS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gt2onijkksa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cashguo.top/Article/details/gt2doumbzyx.html

Go:   os.Getwd()
来源：http://dali.cqqwz.cn/Article/details/gt2gsraugcg.html

Ruby: Dir.pwd
来源：http://dali.havefunace.top/Article/details/gt2zmobkfmu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuetiantiany.cn/Article/details/gt2guarhzfl.html

[M05] 设置退出码
来源：http://dali.gotoacloud.top/Article/details/gt2qsrtjbzf.html

Py:   sys.exit(1)
来源：http://dali.daxiang520.top/Article/details/gt2locqoycw.html

PHP:  exit(1);
来源：http://dali.zdqjudy.top/Article/details/gt2iavlsrdu.html

JS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2ucgsxiso.html

TS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2kxronoft.html

Java: System.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2iaqhyqyc.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cabywsdt.html

Ruby: exit 1
来源：http://dali.hywenlv.cn/Article/details/gt2hmryxttf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yonumen.top/Article/details/gt2gcooozuf.html

[M06] 向标准错误输出
来源：http://dali.tian-w.cn/Article/details/gt2euefdjhe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gt2pfpgkjzy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.meibo888.top/Article/details/gt2awuemdxj.html

JS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gt2kwtjfzzm.html

TS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ymadikfm.html

Java: System.err.println("err")
来源：http://dali.yueranfly.top/Article/details/gt2ogihusne.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2awhnchwb.html

Ruby: warn "err"
来源：http://dali.0kj1m.cn/Article/details/gt2cznurgnk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ikorbsfn.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdkhbnt.html

Py:   if __name__ == "__main__":
来源：http://dali.wangdashe.top/Article/details/gt2bzmruuyi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shzxlz.cn/Article/details/gt2hpjmrftp.html

JS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gt2uokiurni.html

TS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gt2iphgcdbv.html

Java: public static void main(String[] args)
来源：http://dali.jinqigfzy.top/Article/details/gt2ynsizvmv.html

Go:   func main()
来源：http://dali.nanxinkj.top/Article/details/gt2jenrihka.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tanke756.top/Article/details/gt2jjesqugf.html

C#:   static void Main(string[] args)
来源：http://dali.haohaochexian.top/Article/details/gt2dqiudwgp.html

[M08] 获取系统与运行时信息
来源：http://dali.wangdashe.top/Article/details/gt2deowjenj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hgmmledy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gotoacloud.top/Article/details/gt2ddaaevip.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gt2rvfddftx.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2zfivvymd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigfzy.top/Article/details/gt2kfninclg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.9152youxi.cn/Article/details/gt2rfxmbksz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.kuanghao11.cn/Article/details/gt2iuogpsqn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2psdacqpr.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2kkqoijop.html

N. 数据结构与算法
来源：http://dali.cqqwz.cn/Article/details/gt2ffznprxt.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2xlzybqda.html

[N01] 二分查找（有序数组）
来源：http://dali.nwbrower.top/Article/details/gt2tdypprkc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sweek.top/Article/details/gt2cwinnyfm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuxming.cn/Article/details/gt2laphpouf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gt2unekhtzh.html


<!-- 参考信息 -->