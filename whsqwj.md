代发 wailian999

Go:   time.Now()
来源：http://dali.hnqzz.top/Article/details/gtliferiwm.html

Ruby: Time.now
来源：http://dali.9152youxi.cn/Article/details/gtmknueagv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnqzz.top/Article/details/gtmchzewug.html

[J02] 格式化输出
来源：http://dali.jinqigufen.top/Article/details/gtdbylkrmf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gtunbrhfnh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gtgowjwfoz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhongyouzk.top/Article/details/gtsonrsmqi.html

TS:   d.toISOString()
来源：http://dali.gotoacloud.top/Article/details/gtycwqvqwl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xziqi.cn/Article/details/gtyhhismaw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhengqikj.top/Article/details/gthvgxbejo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gtzihrljmm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zycfv.cn/Article/details/gtibexaycw.html

[J03] 字符串解析为日期
来源：http://dali.zdqjudy.top/Article/details/gtrffypnok.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.svipenyu.cn/Article/details/gtheuuwwni.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shuidangran.top/Article/details/gtplqvkwwb.html

JS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtgwuyaomi.html

TS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtlpahrrdd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtdhltiryk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtxqyneihw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtqehpwznm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhongyouzk.top/Article/details/gtrvzodcmg.html

[J04] 时间戳与日期互转
来源：http://dali.hfpthk.cn/Article/details/gtjyihqghm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sufxvd.cn/Article/details/gtkezfsyyz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.c1oappe.top/Article/details/gttjrnliem.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuanzhike.top/Article/details/gthzwsbofj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhoulong.xyz/Article/details/gtdhprevjy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hammf.cn/Article/details/gtsdhopncd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cdnleiting.top/Article/details/gtyjchnbvq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.snrcjt.cn/Article/details/gtyopjmyhz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xylfe.cn/Article/details/gtnfafujio.html

[J05] 时间加减（加 7 天）
来源：http://dali.zdqjudy.top/Article/details/gtqzwgsjam.html

Py:   now + timedelta(days=7)
来源：http://dali.gzhubu.top/Article/details/gtklgndkiy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pycfn.com/Article/details/gtlpwosbtx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gtrgdnhsrj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gtgicyvsla.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhixingplan.top/Article/details/gtrciypash.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tianlin.xyz/Article/details/gtymmowouu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yongpay.top/Article/details/gteqsvnhhq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gthkasaraf.html

[J06] 计算两时间之差
来源：http://dali.havefunace.top/Article/details/gtafxwqjem.html

Py:   (end - start).total_seconds()
来源：http://dali.andypj.xyz/Article/details/gtgjxzwtyk.html

PHP:  $end->diff($start)->days;
来源：http://dali.mhx1999.top/Article/details/gtwhnurnxr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guannengcc.top/Article/details/gthazmlzks.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yonumen.top/Article/details/gtmxjrxpjr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cqqwz.cn/Article/details/gtobwycivq.html

Go:   end.Sub(start).Hours()
来源：http://dali.guannengcc.top/Article/details/gtqgzyfmwf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gtphcnjwzz.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhixingplan.top/Article/details/gtkuozhelx.html

[J07] 比较两个日期
来源：http://dali.zhongyouzk.top/Article/details/gtdyugftum.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtxncphnhi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gtgdpvqpve.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gtomuduqaz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gtugunxmfw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gtladgxhra.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.316326.xyz/Article/details/gtgcrtrtjk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtwhrwascb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlywhnhv.html

[J08] 提取年月日与星期
来源：http://dali.vqdsnc.cn/Article/details/gtxccvsnrn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuetiantiany.cn/Article/details/gtaxtbmdqg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zdqjudy.top/Article/details/gtrhkggnol.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zycfv.cn/Article/details/gtvekoldke.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hongshengwenyu.top/Article/details/gtxqeboofr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.snrcjt.cn/Article/details/gtbukryqhw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cdnleiting.top/Article/details/gtjatrqtfh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pycfn.com/Article/details/gtzszwvjhs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ivvv.top/Article/details/gtsffpiote.html

[J09] 时区处理
来源：http://dali.zdqjudy.top/Article/details/gtpbjlwnue.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjqjepzt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj202588.top/Article/details/gtmvpoibcj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gtixyhardq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gtsvnnparl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xziqi.cn/Article/details/gtsxhdrwou.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.meibo888.top/Article/details/gthnabdhwk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ybcxt.top/Article/details/gtxjtybjgw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxinkj.top/Article/details/gtycygggkf.html

[J10] 取今天 / 本月第一天
来源：http://dali.sweek.top/Article/details/gtpbwbdenz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.vqdsnc.cn/Article/details/gtfrqxqkko.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yongpay.top/Article/details/gtufzfmfpp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.iojbl.cn/Article/details/gttmwivnay.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sweek.top/Article/details/gtbdfjmdkg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shuidangran.top/Article/details/gtsklxtayd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gzhubu.top/Article/details/gtunvfymat.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tanke756.top/Article/details/gterzjetex.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cucudq.cn/Article/details/gtqctjerpw.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtcsqxwmtc.html

K. JSON 与序列化
来源：http://dali.hammf.cn/Article/details/gtqnfujiil.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtmtngyunq.html

[K01] 对象转 JSON 字符串
来源：http://dali.zycfv.cn/Article/details/gtjacyefgv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gtplnuarwr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gtxxkrcpqx.html

JS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gtqylhtwjr.html

TS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtontxlfzg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenzaomai.com/Article/details/gtvlupamms.html

Go:   json.Marshal(obj)
来源：http://dali.xuanzx.com/Article/details/gtrhabcoys.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgufenzy.top/Article/details/gthtacfrmn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hammf.cn/Article/details/gtmxkoqdth.html

[K02] JSON 字符串转对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfaofocp.html

Py:   json.loads(s)
来源：http://dali.yangfankeji.com/Article/details/gtrabezkni.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.vqdsnc.cn/Article/details/gtochokiwz.html

JS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtzalndepi.html

TS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtbwrbbxdx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zycfv.cn/Article/details/gtewgngzhu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfquianmz.html

Ruby: JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gtlnxwpgnu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.andypj.xyz/Article/details/gtnlnmmqry.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.9152youxi.cn/Article/details/gtglkhwwye.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gtzrwulrpr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gtlhgdqmtd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gtvqqvzllx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gtcvrpdkfx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.andypj.xyz/Article/details/gtuxpaglnb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.snrcjt.cn/Article/details/gtmcnxcsth.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jiagoushi.top/Article/details/gtqwhjkial.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gaohongyu789.top/Article/details/gtrafpeemr.html

[K04] 读取 JSON 文件
来源：http://dali.ybcxt.top/Article/details/gtxhpusrpd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gaohongyu789.top/Article/details/gtuqulebxw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ybcxt.top/Article/details/gtovchiktk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtioesqgtz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gtqzhgyrhs.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmytzopw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gtjvcnyjlh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cheryme.top/Article/details/gtjtnnqpmn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gtzmraczgi.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gtmtlykljo.html

Py:   copy.deepcopy(obj)
来源：http://dali.kuanghao11.cn/Article/details/gthuvrfhsj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgufenzy.top/Article/details/gtqqgwjact.html

JS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gttfutsafa.html

TS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtemkyclbd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfxrlopf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hysaishi.cn/Article/details/gtbqfswxtq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aibaodan.cn/Article/details/gtxpvypkoj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhepfksv.html

[K06] 解析 URL 查询串
来源：http://dali.fengsongda.top/Article/details/gtemsuchet.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.316326.xyz/Article/details/gtigzbbnoz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258888.top/Article/details/gtgjztpanq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gtbbzbherw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gtaeoczjhh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gtexqanyjs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtjbnfbmss.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gtcapomfpd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gteqckoimg.html

[K07] 进制转换
来源：http://dali.cucudq.cn/Article/details/gtkujbwehl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtuighacwa.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangdashe.top/Article/details/gtefdcwsin.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtjrmqhuaf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtlnektwdb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtzndlfnyb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.birdmap.top/Article/details/gtfjaurmnl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.kuanghao11.cn/Article/details/gtavamwyow.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtilxilqlu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yanxiufei.cn/Article/details/gtsgctjnle.html

Py:   pickle.dumps(obj)
来源：http://dali.ppjwa.cn/Article/details/gtmsybqvgl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ivvv.top/Article/details/gtkhqnzlff.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gtgexvnozk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gthdbjvotg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgfzy.top/Article/details/gtwchwykhj.html

Go:   encoding/gob
来源：http://dali.shangyingyoupin.top/Article/details/gtfgbeseos.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzdmwruy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gticwatwps.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtzyrcnbex.html

L. 网络请求
来源：http://dali.hammf.cn/Article/details/gtdcycbcie.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtzhhziuoe.html

[L01] 发送 GET 请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflnevdxd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yuanzhike.top/Article/details/gtnanzjmvs.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.birdmap.top/Article/details/gtjxienkjk.html

JS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gtlmyscyle.html

TS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gtzogmfxzr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hongshengwenyu.top/Article/details/gtqetwkczw.html

Go:   resp, err := http.Get(url)
来源：http://dali.birdmap.top/Article/details/gtfarswoxc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nwbrower.top/Article/details/gtqlzsduwm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tian-w.cn/Article/details/gtqqcmumvs.html

[L02] 发送 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gtnnbzfdkk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.bjfxy.top/Article/details/gtqqdrefcn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.fzhhl.top/Article/details/gtrkvraouq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gtqrmeicdh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gtpwhlpwcj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gtdkucelfk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cdnleiting.top/Article/details/gtjrojllxr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hammf.cn/Article/details/gtqagpbimi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hnxiangtu.top/Article/details/gtyiysaokv.html

[L03] 设置自定义请求头
来源：http://dali.tianlin.xyz/Article/details/gtgyboaoiz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sufxvd.cn/Article/details/gtneybovth.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtrbwxovoy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gtxufhnhzv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhixingplan.top/Article/details/gtovwjrytt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.birdmap.top/Article/details/gtbpxdjtay.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqeztsyo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.haohaochexian.top/Article/details/gtszvlrltz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gtzbfqoeme.html

[L04] 设置超时
来源：http://dali.zhengqikj.top/Article/details/gtruxqlxsi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gzhubu.top/Article/details/gtakspgrmk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.c1oappe.top/Article/details/gtatboetlu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gthqsasrai.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gtwzhdhrhr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.316326.xyz/Article/details/gttjsqhmwt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.iojbl.cn/Article/details/gttwhubrmd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nwbrower.top/Article/details/gtgafvpqvk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.feifeiyinyue.top/Article/details/gtmzbnzflf.html

[L05] 上传文件（multipart）
来源：http://dali.jlsjyb.cn/Article/details/gtitctuuza.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhengqikj.top/Article/details/gtdxlzggqm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hammf.cn/Article/details/gtzhiyilmp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gtdlnjmnsi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxuanxn.top/Article/details/gtupueyjzq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhongyouzk.top/Article/details/gtkjpyaccs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ybcxt.top/Article/details/gtnbuasijj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258.top/Article/details/gtpuhgonre.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtwbhddrta.html

[L06] 解析响应为 JSON
来源：http://dali.cashguo.top/Article/details/gtdhuckywn.html

Py:   resp.json()
来源：http://dali.yangfankeji.com/Article/details/gtxlgpztmk.html

PHP:  json_decode($body, true);
来源：http://dali.snrcjt.cn/Article/details/gtwbrvtohc.html

JS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtijdzcoke.html

TS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gtkabonqev.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtgekpkauc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.9152youxi.cn/Article/details/gtheieebdx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cqqwz.cn/Article/details/gtdpmhgnwg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxinkj.top/Article/details/gtfesnakbt.html

[L07] 处理 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gtlqokibgi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nwbrower.top/Article/details/gtthlylnes.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tian-w.cn/Article/details/gtequvjdyu.html

JS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gtpmleemkq.html

TS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gttjtmeoqb.html

Java: resp.statusCode()
来源：http://dali.jyoumei.cn/Article/details/gtyxixzkwa.html

Go:   resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gtbyyxxaah.html

Ruby: resp.code.to_i
来源：http://dali.xziqi.cn/Article/details/gtiafafbwt.html

C#:   (int)resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gtdythbnac.html

[L08] 并发请求多个地址
来源：http://dali.aizwys.cn/Article/details/gtotugdqbm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zycfv.cn/Article/details/gtqozcaipb.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangdashe.top/Article/details/gtjokmtkuo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gtwjgecnaz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtjiaxxgct.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daria6918.cn/Article/details/gtdsnkraym.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhixingplan.top/Article/details/gtuvpqhgxd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.svipenyu.cn/Article/details/gttlgjlhnf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkfolidw.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtdncorvik.html

M. 命令行 / 进程 / 环境
来源：http://dali.hammf.cn/Article/details/gtqygeyaox.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtqeemvdmf.html

[M01] 读取命令行参数
来源：http://dali.ybcxt.top/Article/details/gtgonbqoyf.html

Py:   sys.argv[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncajiqot.html

PHP:  $argv;  $argc;
来源：http://dali.zhaomingkeji.xyz/Article/details/gteuqqezpv.html

JS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gtygjtwjkf.html

TS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gthuhswtpn.html

Java: args 数组（main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gtcjrjiftz.html

Go:   os.Args[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtkkzeypiu.html

Ruby: ARGV
来源：http://dali.chenjidiqi.icu/Article/details/gtdioaijjp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj202588.top/Article/details/gtqjdajzgq.html

[M02] 读取环境变量
来源：http://dali.dianchejie.cn/Article/details/gtwmxhrasw.html

Py:   os.environ.get("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtreelbnsz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtrutceqdo.html

JS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gtftiplsto.html

TS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gtibzuuoau.html

Java: System.getenv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gttcstxinc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtpparrbis.html

Ruby: ENV["HOME"]
来源：http://dali.daria6918.cn/Article/details/gtmcjvchds.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtvdkpxpvd.html

[M03] 执行外部命令
来源：http://dali.jinqigfzy.top/Article/details/gtajthbzag.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.vqdsnc.cn/Article/details/gtyhlnslgm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cdnleiting.top/Article/details/gtxegmnioh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gtiwlyccqh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gtrgeuiack.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.316326.xyz/Article/details/gtizlspfqj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tianlin.xyz/Article/details/gtffekzkvb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shuidangran.top/Article/details/gtswkuzxwa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ppjwa.cn/Article/details/gtrfenfqqd.html

[M04] 获取当前工作目录
来源：http://dali.gaohongyu789.top/Article/details/gtlfubdaci.html

Py:   os.getcwd()
来源：http://dali.iojbl.cn/Article/details/gtxeddjtnh.html

PHP:  getcwd();
来源：http://dali.nanxinkj.top/Article/details/gtaypotqip.html

JS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyewuzudv.html

TS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwejecgke.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.meibo888.top/Article/details/gtkqtnbvai.html

Go:   os.Getwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtqvwprnxh.html

Ruby: Dir.pwd
来源：http://dali.iojbl.cn/Article/details/gtxbgftwhm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sweek.top/Article/details/gtrslicnyo.html

[M05] 设置退出码
来源：http://dali.kuanghao11.cn/Article/details/gtzkqykjdo.html

Py:   sys.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtmzdhxzaa.html

PHP:  exit(1);
来源：http://dali.shuidangran.top/Article/details/gtdovrxmxr.html

JS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtdaqyonrm.html

TS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtonzngdoa.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtmihfekan.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjpjxtuz.html

Ruby: exit 1
来源：http://dali.bjfxy.top/Article/details/gtzxhtiuyz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnqzz.top/Article/details/gtoryvhgqm.html

[M06] 向标准错误输出
来源：http://dali.fengsongda.top/Article/details/gtgmwqufmf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daxiang520.top/Article/details/gtnrlbrokx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.vqdsnc.cn/Article/details/gtltcsuzbn.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gtcikbjbbe.html

TS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtroctwicu.html

Java: System.err.println("err")
来源：http://dali.hfpthk.cn/Article/details/gtaskarfns.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgfzy.top/Article/details/gtwdnaqhlv.html

Ruby: warn "err"
来源：http://dali.haohaochexian.top/Article/details/gtfncfqfeq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cucudq.cn/Article/details/gtjkexsymo.html

[M07] 判断是否为主入口
来源：http://dali.svipenyu.cn/Article/details/gttbjnxmjo.html

Py:   if __name__ == "__main__":
来源：http://dali.ppjwa.cn/Article/details/gthamxhkcg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxinkj.top/Article/details/gtfhlvgwwj.html

JS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgppnqcds.html

TS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtqdckmikf.html

Java: public static void main(String[] args)
来源：http://dali.ppjwa.cn/Article/details/gttlqwangt.html

Go:   func main()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrehdzmz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenjidiqi.icu/Article/details/gtubbdswit.html

C#:   static void Main(string[] args)
来源：http://dali.hywenlv.cn/Article/details/gtiodgwdlk.html


<!-- 参考信息 -->