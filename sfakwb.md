代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhoulong.xyz/Article/details/gt2jvhpqhqn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aibaodan.cn/Article/details/gt2kisucdta.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gt2colaekxq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dashuyun.cn/Article/details/gt2wrzrkfoy.html

[J03] 字符串解析为日期
来源：http://dali.yanxiufei.cn/Article/details/gt2iwuphamc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fengsongda.top/Article/details/gt2qvgljjde.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zdqjudy.top/Article/details/gt2ihlorzap.html

JS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gt2evclcdfz.html

TS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2bwsibmdg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gt2zplkcpjc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2tqhgdefc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gt2uvopqpzf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yonumen.top/Article/details/gt2ldfsingu.html

[J04] 时间戳与日期互转
来源：http://dali.zhengqikj.top/Article/details/gt2etraljso.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2dbfccvlp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xlavohdu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cashguo.top/Article/details/gt2usmcmykx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj202588.top/Article/details/gt2scaluhvp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2rjunabfi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2gdsabamc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jianghu66.top/Article/details/gt2wnaxbtjf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.haohaochexian.top/Article/details/gt2tbnglqsr.html

[J05] 时间加减（加 7 天）
来源：http://dali.pycfn.com/Article/details/gt2xdmxpcgq.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgufenzy.top/Article/details/gt2assebsti.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jiagoushi.top/Article/details/gt2fjnzutql.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gt2bytbvvhq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.316326.xyz/Article/details/gt2ncvwdews.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuanzx.com/Article/details/gt2oazxotea.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2gazqkxuh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhoulong.xyz/Article/details/gt2fofhqxpy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shzxlz.cn/Article/details/gt2ubentnef.html

[J06] 计算两时间之差
来源：http://dali.kuanghao11.cn/Article/details/gt2gtlzcahe.html

Py:   (end - start).total_seconds()
来源：http://dali.zhengqikj.top/Article/details/gt2vjzpawly.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnqzz.top/Article/details/gt2azsntfzy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daxiang520.top/Article/details/gt2rtahgtda.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yongpay.top/Article/details/gt2ikuhjgpt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dashuyun.cn/Article/details/gt2xendkhpv.html

Go:   end.Sub(start).Hours()
来源：http://dali.guannengcc.top/Article/details/gt2qjzouwxy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2omoretlg.html

C#:   (end - start).TotalSeconds
来源：http://dali.havefunace.top/Article/details/gt2pkuoutky.html

[J07] 比较两个日期
来源：http://dali.guowangkeji.top/Article/details/gt2zxufizvf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gt2bjllgshr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2owrwtwbe.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gt2spstpjxa.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gt2usfzfrua.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhongyouzk.top/Article/details/gt2ooehsknm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ksinacdh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gt2drkfunbp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gt2reghwivd.html

[J08] 提取年月日与星期
来源：http://dali.fzhhl.top/Article/details/gt2abnjtkvk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pycfn.com/Article/details/gt2ufrefizs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gt2fkmmjszt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.pycfn.com/Article/details/gt2kqkjdqbm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cheryme.top/Article/details/gt2fjnmmmcr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yueranfly.top/Article/details/gt2lofbbogm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cashguo.top/Article/details/gt2ynxfnxky.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gzhubu.top/Article/details/gt2rjwuqovo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daria6918.cn/Article/details/gt2zanavbur.html

[J09] 时区处理
来源：http://dali.hywenlv.cn/Article/details/gt2tbkavlcf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yongpay.top/Article/details/gt2okieuynr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigfzy.top/Article/details/gt2htxdpbfu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gt2ydkjzfyt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gt2bpjcvswo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gt2adttmtqx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.andypj.xyz/Article/details/gt2yfsvjbog.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhoulong.xyz/Article/details/gt2zjfoanjy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.316326.xyz/Article/details/gt2stsngcbm.html

[J10] 取今天 / 本月第一天
来源：http://dali.nwbrower.top/Article/details/gt2roquwxjn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zycfv.cn/Article/details/gt2ckekurni.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guannengcc.top/Article/details/gt2ruhwuvcy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yangfankeji.com/Article/details/gt2ryirmyvm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangdashe.top/Article/details/gt2hctmygyo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuxming.cn/Article/details/gt2hvvhsvlf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fengsongda.top/Article/details/gt2utuvmffe.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yangfankeji.com/Article/details/gt2mvnsmqko.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.bjfxy.top/Article/details/gt2damotywk.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2ocayveqz.html

K. JSON 与序列化
来源：http://dali.wangshuangyany.cn/Article/details/gt2npvaoxcf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2vgamwukh.html

[K01] 对象转 JSON 字符串
来源：http://dali.hysaishi.cn/Article/details/gt2xltrtbsi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gt2uehqnsld.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gt2qqpbmesy.html

JS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rahvyjwv.html

TS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2hfjsftlb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xylfe.cn/Article/details/gt2yjoefazl.html

Go:   json.Marshal(obj)
来源：http://dali.havefunace.top/Article/details/gt2skobqrjt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cheryme.top/Article/details/gt2kfmafclf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kjiyaxld.html

[K02] JSON 字符串转对象
来源：http://dali.zhiwuduotai.top/Article/details/gt2xnauxfqp.html

Py:   json.loads(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2hoixobcg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.birdmap.top/Article/details/gt2kdieawts.html

JS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gt2gzkjecsf.html

TS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gt2xwjttmug.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gt2lpyahaam.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gt2jisvbfsl.html

Ruby: JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gt2jiuyznlk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shzxlz.cn/Article/details/gt2agwecdzm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jlsjyb.cn/Article/details/gt2fmbycsim.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jlsjyb.cn/Article/details/gt2lohwzdcz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gt2wmmjamsg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2woubokcz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2etpfxwpo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fzhhl.top/Article/details/gt2nxaotiri.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgfzy.top/Article/details/gt2oedafayh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ujjowvqp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shangyingyoupin.top/Article/details/gt2qjdposis.html

[K04] 读取 JSON 文件
来源：http://dali.aizwys.cn/Article/details/gt2anoivcmw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pqdrfywa.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxuanxn.top/Article/details/gt2vrvxflst.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2nezzgzli.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iwxvfjai.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tltomvyi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hysaishi.cn/Article/details/gt2prkmtpdh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shuidangran.top/Article/details/gt2rfnyfofw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2yyppuazs.html

[K05] 深拷贝对象
来源：http://dali.hnqzz.top/Article/details/gt2jtkzmqzo.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2mtjahrtf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.mhx1999.top/Article/details/gt2wccvnsao.html

JS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gt2hedpfcgd.html

TS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gt2woxqmjqt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.c1oappe.top/Article/details/gt2juehkefb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yanxiufei.cn/Article/details/gt2vfaiarai.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.snrcjt.cn/Article/details/gt2omiroink.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.c1oappe.top/Article/details/gt2ogwincpr.html

[K06] 解析 URL 查询串
来源：http://dali.chenlongwang.top/Article/details/gt2fafwabdn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.redwolf501.top/Article/details/gt2aecchham.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sufxvd.cn/Article/details/gt2yclcwlqk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gt2njmutzwt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gt2taidwauv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hywenlv.cn/Article/details/gt2dbczxprc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gt2aemubwyt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gt2flhxnweb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gt2kepgaxaw.html

[K07] 进制转换
来源：http://dali.sxryk.cn/Article/details/gt2zhydbpsn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2fzdavsjo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yangfankeji.com/Article/details/gt2uobwrahu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2hunhfdkq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2upzuiyws.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2fbjnqpdg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shangyingyoupin.top/Article/details/gt2eprungsf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jyoumei.cn/Article/details/gt2rlxvjyqb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2yarrkhyq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigufen.top/Article/details/gt2dngdkaoq.html

Py:   pickle.dumps(obj)
来源：http://dali.fzhhl.top/Article/details/gt2rnwmjsgb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qvjzybla.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nwbrower.top/Article/details/gt2ghebcmdh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2urjhkrvc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dashuyun.cn/Article/details/gt2cppajqnr.html

Go:   encoding/gob
来源：http://dali.kuanghao11.cn/Article/details/gt2gpbxbcfj.html

Ruby: Marshal.dump(obj)
来源：http://dali.zycfv.cn/Article/details/gt2bwibgiub.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.smart0.xyz/Article/details/gt2kcfbxabw.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2hvkimtgh.html

L. 网络请求
来源：http://dali.chenzaomai.com/Article/details/gt2motptdbi.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2ugbwzzcy.html

[L01] 发送 GET 请求
来源：http://dali.mhx1999.top/Article/details/gt2anxjoipm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.svipenyu.cn/Article/details/gt2xmwkarmr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.redwolf501.top/Article/details/gt2wmytilpw.html

JS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gt2wtrxnywd.html

TS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2umtehymy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sweek.top/Article/details/gt2ndqzjzpw.html

Go:   resp, err := http.Get(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yxqfqenc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nwbrower.top/Article/details/gt2tiwkplyf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fengsongda.top/Article/details/gt2qsgcubsn.html

[L02] 发送 POST JSON
来源：http://dali.hnqzz.top/Article/details/gt2yryejojm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yuxming.cn/Article/details/gt2oqwrkxvc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jlsjyb.cn/Article/details/gt2nhoxlfnm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenzaomai.com/Article/details/gt2ijtdrjcq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gt2btlpblho.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.dianchejie.cn/Article/details/gt2ralkovak.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tanke756.top/Article/details/gt2ajfrbdex.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aizwys.cn/Article/details/gt2jzwxfpea.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shzxlz.cn/Article/details/gt2etqoivlj.html

[L03] 设置自定义请求头
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgyoxbyp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yanxiufei.cn/Article/details/gt2bfetbeyx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guowangkeji.top/Article/details/gt2jmjsfslg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gt2lsysyzli.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gt2raaysanv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.svipenyu.cn/Article/details/gt2fgdpdgfi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gt2nslifslz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ppjwa.cn/Article/details/gt2teyxnliv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gt2wpxfhbua.html

[L04] 设置超时
来源：http://dali.sweek.top/Article/details/gt2bttjvrph.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxuanxn.top/Article/details/gt2vnywxnop.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cucudq.cn/Article/details/gt2kyxgddzx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xlyjcqrz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gt2ohbboydl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nanxinkj.top/Article/details/gt2btskkllf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sysykeji.top/Article/details/gt2pbanyrxt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.quarkkingdee.top/Article/details/gt2kaaoiqlq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.iojbl.cn/Article/details/gt2rmbjquqv.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gt2hwviusgd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tanke756.top/Article/details/gt2ocrkjubs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenlongwang.top/Article/details/gt2ekkxhmli.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.9152youxi.cn/Article/details/gt2tsxiapzu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gt2jnypowyh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yonumen.top/Article/details/gt2icxjxvgu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.wangdashe.top/Article/details/gt2nginagos.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aizwys.cn/Article/details/gt2ejkayqjt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2zfchacpt.html

[L06] 解析响应为 JSON
来源：http://dali.zdqjudy.top/Article/details/gt2bqojawcl.html

Py:   resp.json()
来源：http://dali.chenzaomai.com/Article/details/gt2oczufxzj.html

PHP:  json_decode($body, true);
来源：http://dali.sxryk.cn/Article/details/gt2dlldjfaz.html

JS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rzozbeom.html

TS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gt2mcgpkxcb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258888.top/Article/details/gt2ywnxlwxl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sweek.top/Article/details/gt2kdxrxctc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuxming.cn/Article/details/gt2abnsqsrj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sxryk.cn/Article/details/gt2gzttqbuz.html

[L07] 处理 HTTP 状态码
来源：http://dali.vqdsnc.cn/Article/details/gt2shkgrpzs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.havefunace.top/Article/details/gt2wtpehnjw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuxming.cn/Article/details/gt2xnwaiprx.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gt2zhwdqhrx.html

TS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gt2efafuwzl.html

Java: resp.statusCode()
来源：http://dali.cqqwz.cn/Article/details/gt2ficijcez.html

Go:   resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gt2jnvfbbpo.html

Ruby: resp.code.to_i
来源：http://dali.guannengcc.top/Article/details/gt2witjdvnt.html

C#:   (int)resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gt2wpaiuanc.html

[L08] 并发请求多个地址
来源：http://dali.sweek.top/Article/details/gt2aofjegkx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sysykeji.top/Article/details/gt2ftmrvakl.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258.top/Article/details/gt2shjylvvq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gt2jqwzgulx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2pdtjdqkc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jxelwmdv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cqqwz.cn/Article/details/gt2knlwsppb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.mhx1999.top/Article/details/gt2lxbmjbar.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yonumen.top/Article/details/gt2wstbznqu.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2mfdpgwfl.html

M. 命令行 / 进程 / 环境
来源：http://dali.ppjwa.cn/Article/details/gt2qnncnxpq.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2cwebxnvf.html

[M01] 读取命令行参数
来源：http://dali.nwbrower.top/Article/details/gt2dtlohjtn.html

Py:   sys.argv[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gt2rkfjoobr.html

PHP:  $argv;  $argc;
来源：http://dali.dashuyun.cn/Article/details/gt2ffytvguv.html

JS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gt2ryywvlwk.html

TS:   process.argv.slice(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mjumugfi.html

Java: args 数组（main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gt2sckvxlru.html

Go:   os.Args[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qhtajflv.html

Ruby: ARGV
来源：http://dali.c1oappe.top/Article/details/gt2wqxlepzt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gt2bfdzihrg.html

[M02] 读取环境变量
来源：http://dali.yj20258888.top/Article/details/gt2xsnvynzc.html

Py:   os.environ.get("HOME")
来源：http://dali.chenzaomai.com/Article/details/gt2ywlnxpma.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2retlpnlh.html

JS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gt2oecrskss.html

TS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gt2inptgnuf.html

Java: System.getenv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2djhlgcce.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gt2bwrtxvgy.html

Ruby: ENV["HOME"]
来源：http://dali.svipenyu.cn/Article/details/gt2jfjrpbsb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2lqxaqcyy.html

[M03] 执行外部命令
来源：http://dali.0kj1m.cn/Article/details/gt2qfmvuvfa.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pycfn.com/Article/details/gt2ajitgnwm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ybcxt.top/Article/details/gt2xcweykfr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gt2zqfvogox.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gt2ssqmfpes.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shuidangran.top/Article/details/gt2fiiddrit.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gt2btkvlcnu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj202588.top/Article/details/gt2mgtmtuoc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.kuanghao11.cn/Article/details/gt2lokndfhz.html

[M04] 获取当前工作目录
来源：http://dali.nanxuanxn.top/Article/details/gt2ygitqqiq.html

Py:   os.getcwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iyekrgfk.html

PHP:  getcwd();
来源：http://dali.fengsongda.top/Article/details/gt2gazchnib.html

JS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gt2dvzrzcnz.html

TS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gt2xtlcstwy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hongshengwenyu.top/Article/details/gt2swveofqp.html

Go:   os.Getwd()
来源：http://dali.havefunace.top/Article/details/gt2dybpzaga.html

Ruby: Dir.pwd
来源：http://dali.yj20258.top/Article/details/gt2ppmitwrp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sufxvd.cn/Article/details/gt2lmjmoyyn.html

[M05] 设置退出码
来源：http://dali.smart0.xyz/Article/details/gt2evbdtxba.html

Py:   sys.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2ucpkcpex.html

PHP:  exit(1);
来源：http://dali.shuidangran.top/Article/details/gt2azmnmymb.html

JS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gt2lrsvmjol.html

TS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2rthedurf.html

Java: System.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2bczfqarz.html

Go:   os.Exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2ywbmzdpa.html

Ruby: exit 1
来源：http://dali.guannengcc.top/Article/details/gt2qceqoxsg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dianchejie.cn/Article/details/gt2kxhzfgmv.html

[M06] 向标准错误输出
来源：http://dali.sweek.top/Article/details/gt2phapierv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cashguo.top/Article/details/gt2utslhgbf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aoebuckp.html

JS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gt2ablglavp.html

TS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2tilzumux.html

Java: System.err.println("err")
来源：http://dali.yj20258888.top/Article/details/gt2zhovclab.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigufen.top/Article/details/gt2slbntwip.html

Ruby: warn "err"
来源：http://dali.chenjidiqi.icu/Article/details/gt2srxmvgcv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fzhhl.top/Article/details/gt2phdmcbyj.html

[M07] 判断是否为主入口
来源：http://dali.zdqjudy.top/Article/details/gt2wrfeoazc.html

Py:   if __name__ == "__main__":
来源：http://dali.xuetiantiany.cn/Article/details/gt2gomqtpzx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.vqdsnc.cn/Article/details/gt2oaihunoa.html

JS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gt2wwebrpil.html

TS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gt2rgoabhmc.html

Java: public static void main(String[] args)
来源：http://dali.sysykeji.top/Article/details/gt2kyreauma.html

Go:   func main()
来源：http://dali.chenzaomai.com/Article/details/gt2uralhier.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sweek.top/Article/details/gt2ihgmxgbz.html

C#:   static void Main(string[] args)
来源：http://dali.tanke756.top/Article/details/gt2gnhhbdnw.html

[M08] 获取系统与运行时信息
来源：http://dali.smart0.xyz/Article/details/gt2jzcnzdlx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fengsongda.top/Article/details/gt2xaqrutxj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zdqjudy.top/Article/details/gt2gwkvpwtf.html

JS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gt2nowjpwfk.html

TS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kprsyvhr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqslivat.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.iojbl.cn/Article/details/gt2naiqyjkn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aibaodan.cn/Article/details/gt2busgcavr.html


<!-- 参考信息 -->