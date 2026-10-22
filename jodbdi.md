代发 wailian999

Go:   time.Now()
来源：http://dali.meibo888.top/Article/details/gt2wlywcplz.html

Ruby: Time.now
来源：http://dali.chenzaomai.com/Article/details/gt2vacnndnb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.birdmap.top/Article/details/gt2hxybzvyd.html

[J02] 格式化输出
来源：http://dali.yuxming.cn/Article/details/gt2vkbosdmq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gt2hjuixldi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gt2rcrafbro.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sufxvd.cn/Article/details/gt2zvmsgeex.html

TS:   d.toISOString()
来源：http://dali.nwbrower.top/Article/details/gt2jegtgugr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvrwufcn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.meibo888.top/Article/details/gt2pvyxwwld.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gt2bkyodcin.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ahmufzgo.html

[J03] 字符串解析为日期
来源：http://dali.quarkkingdee.top/Article/details/gt2xcxyoldh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.guowangkeji.top/Article/details/gt2xiesebpr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cashguo.top/Article/details/gt2xwvdpdbz.html

JS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2hiqpxktx.html

TS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2alkirvfe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2lrkgqfmn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2ynffnjsb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2bhagmtgq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxinkj.top/Article/details/gt2uknxtrqt.html

[J04] 时间戳与日期互转
来源：http://dali.zycfv.cn/Article/details/gt2spywgpzi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cdnleiting.top/Article/details/gt2iuefcqos.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fzhhl.top/Article/details/gt2juunyncd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jianghu66.top/Article/details/gt2nsejjzac.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fengsongda.top/Article/details/gt2hfnzgmrl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigufen.top/Article/details/gt2qwttvmau.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ivvv.top/Article/details/gt2nevfxbmg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shuidangran.top/Article/details/gt2zwnbhyib.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gt2czfidkpc.html

[J05] 时间加减（加 7 天）
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjjprhay.html

Py:   now + timedelta(days=7)
来源：http://dali.ydzc1.top/Article/details/gt2cpcggxss.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daxiang520.top/Article/details/gt2wazmmiuo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gt2ulnenttj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gt2jwysxqsz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xinyue.icu/Article/details/gt2goajsbzz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.316326.xyz/Article/details/gt2ctgbqwym.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zdqjudy.top/Article/details/gt2xjrkzyle.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bazucpsn.html

[J06] 计算两时间之差
来源：http://dali.dianchejie.cn/Article/details/gt2zsondmrb.html

Py:   (end - start).total_seconds()
来源：http://dali.hnqzz.top/Article/details/gt2zyjoqmqn.html

PHP:  $end->diff($start)->days;
来源：http://dali.aizwys.cn/Article/details/gt2fqenyfgs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gt2bpntorei.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tanke756.top/Article/details/gt2pbtwfdse.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ylcujiby.html

Go:   end.Sub(start).Hours()
来源：http://dali.jlsjyb.cn/Article/details/gt2ikpbaenr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yvedp.cn/Article/details/gt2canalxmg.html

C#:   (end - start).TotalSeconds
来源：http://dali.yongpay.top/Article/details/gt2dzptqicu.html

[J07] 比较两个日期
来源：http://dali.redwolf501.top/Article/details/gt2hpbycvio.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gt2vsxnmpaa.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zycfv.cn/Article/details/gt2rdivwksr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gt2gedxcbji.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gt2nuboalza.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ehwqpu.com/Article/details/gt2nhimseie.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zycfv.cn/Article/details/gt2lqhxhlhe.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2umdgoknj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gt2ryimtqxu.html

[J08] 提取年月日与星期
来源：http://dali.c1oappe.top/Article/details/gt2dzydtuni.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuxming.cn/Article/details/gt2ktgyfaac.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj202588.top/Article/details/gt2ibfgywaf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258.top/Article/details/gt2gddyolvz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhengqikj.top/Article/details/gt2etrhzakw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dashuyun.cn/Article/details/gt2bigallbf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daxiang520.top/Article/details/gt2coalipjf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.redwolf501.top/Article/details/gt2vsymhuzb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gt2ybnjranv.html

[J09] 时区处理
来源：http://dali.andypj.xyz/Article/details/gt2nulnuqov.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbwfzet.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuetiantiany.cn/Article/details/gt2fgbsskof.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gt2ybzjlick.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmwduyjk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.mhx1999.top/Article/details/gt2gwlhebnt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.0kj1m.cn/Article/details/gt2frteeeds.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.bjfxy.top/Article/details/gt2ygbvhjle.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zycfv.cn/Article/details/gt2eqolojyw.html

[J10] 取今天 / 本月第一天
来源：http://dali.xylfe.cn/Article/details/gt2xajfxqjk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xuyfbofi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xwmwamgk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hfpthk.cn/Article/details/gt2jdhfmrpa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dxkozwuy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.0kj1m.cn/Article/details/gt2ezbifyub.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuanzx.com/Article/details/gt2ylzotqpz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uyzcdqke.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yvedp.cn/Article/details/gt2efatjdqo.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2uabluzin.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gt2igokryxi.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2vilejynf.html

[K01] 对象转 JSON 字符串
来源：http://dali.birdmap.top/Article/details/gt2sckipgnx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gt2sscammrs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gt2fvglvljw.html

JS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gt2riwciimh.html

TS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gt2xyboyuaj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jlsjyb.cn/Article/details/gt2jqcbpmnj.html

Go:   json.Marshal(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2rhomsrwt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhoulong.xyz/Article/details/gt2esaiwywi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jicfemxy.html

[K02] JSON 字符串转对象
来源：http://dali.nanxinkj.top/Article/details/gt2bmqotgvt.html

Py:   json.loads(s)
来源：http://dali.sufxvd.cn/Article/details/gt2jodkkvri.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ydzc1.top/Article/details/gt2kjzmmsqu.html

JS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2bwqjqqbe.html

TS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tgpyzltf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.9152youxi.cn/Article/details/gt2icvosmtw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gt2zawirqti.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2urgeajev.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jyoumei.cn/Article/details/gt2ucqhxthe.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhengqikj.top/Article/details/gt2opgyxwst.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gt2moarcgts.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gt2sgadppiw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gt2tuvswctr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2sgzteufd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2vvxsdjlv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangdashe.top/Article/details/gt2cpstkxiw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2yzelesfg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnxiangtu.top/Article/details/gt2ngtqfvdo.html

[K04] 读取 JSON 文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2oxmuyyip.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj202588.top/Article/details/gt2avnvvbjr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhongyouzk.top/Article/details/gt2ynkbnlou.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gt2naqnkanp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gt2ilisrvuo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tian-w.cn/Article/details/gt2vslmmqic.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gt2hvcxpcyy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gt2utnfnxbo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yueranfly.top/Article/details/gt2buylybwt.html

[K05] 深拷贝对象
来源：http://dali.ppjwa.cn/Article/details/gt2ewbcjoul.html

Py:   copy.deepcopy(obj)
来源：http://dali.bjfxy.top/Article/details/gt2sgsdiviq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangshuangyany.cn/Article/details/gt2cmeloqte.html

JS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2fwhjvasm.html

TS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2apcuezuc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.bjfxy.top/Article/details/gt2qcodywpi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yonumen.top/Article/details/gt2ofxdgzhn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jlsjyb.cn/Article/details/gt2eegstfaj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.316326.xyz/Article/details/gt2ppoewrun.html

[K06] 解析 URL 查询串
来源：http://dali.hnxiangtu.top/Article/details/gt2dqnidsgj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fengsongda.top/Article/details/gt2bbpibjdb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zycfv.cn/Article/details/gt2xmunnsmv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gt2uafqhudw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.iojbl.cn/Article/details/gt2ocvgajiq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jianghu66.top/Article/details/gt2zfmlgmbv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gt2ouuoihoo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gt2weowddtk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gt2gvagctug.html

[K07] 进制转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2gdlzziqh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tanke756.top/Article/details/gt2jlqfjlti.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shangyingyoupin.top/Article/details/gt2rzcipwcv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2mtbareyl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2xmynhecg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2kwxgatda.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shzxlz.cn/Article/details/gt2vmlwjfzy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cashguo.top/Article/details/gt2vifwollc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2unpwtjjj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yuanzhike.top/Article/details/gt2zgigmiqu.html

Py:   pickle.dumps(obj)
来源：http://dali.pycfn.com/Article/details/gt2vzmxiize.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuanzx.com/Article/details/gt2csjthhzd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gt2urprhsex.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gt2ccbdnfqm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.feifeiyinyue.top/Article/details/gt2mxfacstl.html

Go:   encoding/gob
来源：http://dali.jianghu66.top/Article/details/gt2lqdwqbzm.html

Ruby: Marshal.dump(obj)
来源：http://dali.hammf.cn/Article/details/gt2bgijnrol.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gt2juhjnrlq.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2ilazmlqe.html

L. 网络请求
来源：http://dali.quarkkingdee.top/Article/details/gt2exbzbzgc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2bwjedtcs.html

[L01] 发送 GET 请求
来源：http://dali.guannengcc.top/Article/details/gt2ynzipzjc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhengqikj.top/Article/details/gt2hjqnzkdh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fengsongda.top/Article/details/gt2hhlhoixq.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwkyhlo.html

TS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pwmxgxya.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daxiang520.top/Article/details/gt2mizujkud.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigufen.top/Article/details/gt2bmcrnbqo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.c1oappe.top/Article/details/gt2ndomjcbn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cashguo.top/Article/details/gt2kmlmedjy.html

[L02] 发送 POST JSON
来源：http://dali.xuanzx.com/Article/details/gt2xvxvqjoo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gt2dznntijw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hammf.cn/Article/details/gt2nagkutwi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gt2vellntve.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gt2raomqnsn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnqzz.top/Article/details/gt2dyizwyyt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhiwuduotai.top/Article/details/gt2mzbmqktl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shuidangran.top/Article/details/gt2oyjgingh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj202588.top/Article/details/gt2zlabbrff.html

[L03] 设置自定义请求头
来源：http://dali.yongpay.top/Article/details/gt2mtzpblew.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yongpay.top/Article/details/gt2zbydbysf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj202588.top/Article/details/gt2aevisydv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gt2ypryrtmr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gt2nownaxuc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.andypj.xyz/Article/details/gt2iunpfqld.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gt2wgidoaks.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pycfn.com/Article/details/gt2eqjqwhhl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gt2dlxwxrmt.html

[L04] 设置超时
来源：http://dali.ppjwa.cn/Article/details/gt2miuiucha.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuxming.cn/Article/details/gt2cqfeycgm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.0kj1m.cn/Article/details/gt2bcykmqmh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gt2iytpkirg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnqzz.top/Article/details/gt2mejnfzaa.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cashguo.top/Article/details/gt2nmhxqhdt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ppjwa.cn/Article/details/gt2ugxehoya.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shzxlz.cn/Article/details/gt2kbozodnt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jiagoushi.top/Article/details/gt2dkmpiazr.html

[L05] 上传文件（multipart）
来源：http://dali.sysykeji.top/Article/details/gt2ycqzyvod.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qukdvike.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cdnleiting.top/Article/details/gt2kjjgmbqj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gt2inowsncm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gt2wxtlyqzz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxuanxn.top/Article/details/gt2tyhvhzch.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jyoumei.cn/Article/details/gt2zmmzmbcj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.svipenyu.cn/Article/details/gt2qnjbmoyc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2klxvkgfq.html

[L06] 解析响应为 JSON
来源：http://dali.daxiang520.top/Article/details/gt2qkekhaph.html

Py:   resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gt2vlduksve.html

PHP:  json_decode($body, true);
来源：http://dali.xziqi.cn/Article/details/gt2kkjwrowz.html

JS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gt2gaeofzli.html

TS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gt2lzjssoql.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.smart0.xyz/Article/details/gt2hpqsxlps.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.kuanghao11.cn/Article/details/gt2gqrazzii.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ppjwa.cn/Article/details/gt2qrkdqwrs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnxiangtu.top/Article/details/gt2sjmaolag.html

[L07] 处理 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gt2lxwxbnys.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2icasdqlp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdoioifw.html

JS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gt2vhbegkan.html

TS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ipvzjjql.html

Java: resp.statusCode()
来源：http://dali.svipenyu.cn/Article/details/gt2bnywawuo.html

Go:   resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gt2pqlmkdvd.html

Ruby: resp.code.to_i
来源：http://dali.xylfe.cn/Article/details/gt2uynflttj.html

C#:   (int)resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gt2kycqjvan.html

[L08] 并发请求多个地址
来源：http://dali.gzhubu.top/Article/details/gt2wotedtiz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nwbrower.top/Article/details/gt2tnxqeccw.html

PHP:  curl_multi_init() 系列
来源：http://dali.sxryk.cn/Article/details/gt2salriyix.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gt2jvhyquqw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2brtwhyle.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.snrcjt.cn/Article/details/gt2qetmehxt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pycfn.com/Article/details/gt2ghfymtwg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yueranfly.top/Article/details/gt2uusxtnyw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.9152youxi.cn/Article/details/gt2lboxkcsr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fhszgixs.html

M. 命令行 / 进程 / 环境
来源：http://dali.0kj1m.cn/Article/details/gt2sslalwkd.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2hrelrxhl.html

[M01] 读取命令行参数
来源：http://dali.ehwqpu.com/Article/details/gt2giwxglkt.html

Py:   sys.argv[1:]
来源：http://dali.0kj1m.cn/Article/details/gt2aedobbhv.html

PHP:  $argv;  $argc;
来源：http://dali.sweek.top/Article/details/gt2pecisuac.html

JS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gt2pjtjubyn.html

TS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gt2xnoquhzr.html

Java: args 数组（main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gt2vvarctes.html

Go:   os.Args[1:]
来源：http://dali.jlsjyb.cn/Article/details/gt2dgrmxgfm.html

Ruby: ARGV
来源：http://dali.jqgufenzy.top/Article/details/gt2aptexjkx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gt2ixintxej.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gt2qeqvgzro.html

Py:   os.environ.get("HOME")
来源：http://dali.yuxming.cn/Article/details/gt2mtkwxedt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hammf.cn/Article/details/gt2bondfymi.html

JS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gt2xejljtea.html

TS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gt2hqghdwjn.html

Java: System.getenv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bvrfknmc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258.top/Article/details/gt2ppdqkeum.html

Ruby: ENV["HOME"]
来源：http://dali.ppjwa.cn/Article/details/gt2hfuqclrm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2tsfidbbg.html

[M03] 执行外部命令
来源：http://dali.jinqigfzy.top/Article/details/gt2cfdhvgky.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.iojbl.cn/Article/details/gt2pqceswrw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fzhhl.top/Article/details/gt2wghxtcgy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gt2xhtylomp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gt2ngptknyb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daria6918.cn/Article/details/gt2uhikbjoe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jyoumei.cn/Article/details/gt2agfdjqol.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuetiantiany.cn/Article/details/gt2qkbskawi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gt2uubnxqbd.html

[M04] 获取当前工作目录
来源：http://dali.316326.xyz/Article/details/gt2famjlnoy.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gt2ubfdbyvh.html

PHP:  getcwd();
来源：http://dali.shangyingyoupin.top/Article/details/gt2bkzebfia.html

JS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2tjgcaaru.html

TS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gt2eeqsjrnc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gotoacloud.top/Article/details/gt2xgkbqstd.html

Go:   os.Getwd()
来源：http://dali.havefunace.top/Article/details/gt2picytxfm.html

Ruby: Dir.pwd
来源：http://dali.dashuyun.cn/Article/details/gt2cpfwseyd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xziqi.cn/Article/details/gt2figweszo.html

[M05] 设置退出码
来源：http://dali.vqdsnc.cn/Article/details/gt2hwagqwsu.html

Py:   sys.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2ivdkhhis.html

PHP:  exit(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2csdyslbx.html

JS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2hbtwuscq.html

TS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2hiikbpbn.html

Java: System.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vhigrmex.html

Go:   os.Exit(1)
来源：http://dali.sufxvd.cn/Article/details/gt2iptbcanw.html

Ruby: exit 1
来源：http://dali.mhx1999.top/Article/details/gt2uraovrid.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sysykeji.top/Article/details/gt2eloudpcj.html

[M06] 向标准错误输出
来源：http://dali.zhoulong.xyz/Article/details/gt2xljdfevz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gt2fdujyjyx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oidxfeae.html

JS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eyiigrzv.html

TS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gt2uaspcuje.html

Java: System.err.println("err")
来源：http://dali.yj20258.top/Article/details/gt2oehpvnep.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2txdtfkvo.html

Ruby: warn "err"
来源：http://dali.yueranfly.top/Article/details/gt2ytczisaz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.kuanghao11.cn/Article/details/gt2lvjnmsdw.html

[M07] 判断是否为主入口
来源：http://dali.wangshuangyany.cn/Article/details/gt2osjsmcpj.html

Py:   if __name__ == "__main__":
来源：http://dali.zdqjudy.top/Article/details/gt2jorsiksc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gotoacloud.top/Article/details/gt2fnvviibp.html

JS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gt2zrtmdorb.html

TS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gt2zfnxnobj.html

Java: public static void main(String[] args)
来源：http://dali.chenzaomai.com/Article/details/gt2aijktuxw.html

Go:   func main()
来源：http://dali.jinqigfzy.top/Article/details/gt2tiaowkub.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258.top/Article/details/gt2nkdtlrgg.html

C#:   static void Main(string[] args)
来源：http://dali.yongpay.top/Article/details/gt2gpcvyjul.html


<!-- 参考信息 -->