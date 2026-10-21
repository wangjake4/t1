代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sysykeji.top/Article/details/gtekiifdql.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shangyingyoupin.top/Article/details/gtksdchfcy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gtlkdwolqz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhoulong.xyz/Article/details/gtrtkriwji.html

[J03] 字符串解析为日期
来源：http://dali.ybcxt.top/Article/details/gtmhkbnjgf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.snrcjt.cn/Article/details/gtylyhjmts.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnqzz.top/Article/details/gtwmqmckot.html

JS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtiqacntzr.html

TS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gttrnuaisl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtmvxvmctm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtmbhxulwu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtetfxmdnx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yueranfly.top/Article/details/gtzhlfvvqp.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gtiicscoty.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zycfv.cn/Article/details/gtzfiqohkq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tian-w.cn/Article/details/gtkbkinipc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangshuangyany.cn/Article/details/gtamttodtj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tianlin.xyz/Article/details/gtjbjkzvcy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cashguo.top/Article/details/gtabcqsfgo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrbbwfcv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhkybohl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.316326.xyz/Article/details/gtqsucpnaz.html

[J05] 时间加减（加 7 天）
来源：http://dali.shangyingyoupin.top/Article/details/gtetuemicu.html

Py:   now + timedelta(days=7)
来源：http://dali.cashguo.top/Article/details/gtoofqrgpc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sysykeji.top/Article/details/gtjlzjcbqa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.meibo888.top/Article/details/gtgpctuyui.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gtslbwefjx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuanzx.com/Article/details/gtniyycdkv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gtpxnumyuy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yonumen.top/Article/details/gtbobdrxig.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuanzhike.top/Article/details/gtrubsonfv.html

[J06] 计算两时间之差
来源：http://dali.dianchejie.cn/Article/details/gtmxwkgxrq.html

Py:   (end - start).total_seconds()
来源：http://dali.yuanzhike.top/Article/details/gtchvvjath.html

PHP:  $end->diff($start)->days;
来源：http://dali.sysykeji.top/Article/details/gtgiqkunos.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.feifeiyinyue.top/Article/details/gtckkapcvy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangshuangyany.cn/Article/details/gtvxmeojsu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aizwys.cn/Article/details/gtiecyvubx.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlzzvqau.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aibaodan.cn/Article/details/gtaaoepxis.html

C#:   (end - start).TotalSeconds
来源：http://dali.zdqjudy.top/Article/details/gtjcfkivyy.html

[J07] 比较两个日期
来源：http://dali.guowangkeji.top/Article/details/gtmxzzuouy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtwrpgeoga.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fzhhl.top/Article/details/gtyohisijf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gtfmxvwgpy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gtiactrtiv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhoulong.xyz/Article/details/gtdqoxxwuk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gtftvletuf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gtvmxpwdiv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtrlykjsnm.html

[J08] 提取年月日与星期
来源：http://dali.zhoulong.xyz/Article/details/gtuvdpmkns.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.0kj1m.cn/Article/details/gtcuopnrfb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gtwjhhuekw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgufenzy.top/Article/details/gtxejdsnue.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cucudq.cn/Article/details/gtodxblbva.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sysykeji.top/Article/details/gtnuovyiho.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cucudq.cn/Article/details/gtjdrubwxb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.316326.xyz/Article/details/gtprnkdnhc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hywenlv.cn/Article/details/gtpitqxaxs.html

[J09] 时区处理
来源：http://dali.xuetiantiany.cn/Article/details/gtkkshwelw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ydzc1.top/Article/details/gtxcbllepq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.andypj.xyz/Article/details/gtvxamurhl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gtxfzkioxo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gtimhukpth.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ybcxt.top/Article/details/gtrjbasjvf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aizwys.cn/Article/details/gtdtrkentd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yongpay.top/Article/details/gticrzwevq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ppjwa.cn/Article/details/gtjcbcpsei.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangdashe.top/Article/details/gtqtnvkvhw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jianghu66.top/Article/details/gtptxqyedc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fengsongda.top/Article/details/gtqtkagmsi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.snrcjt.cn/Article/details/gtxierucjc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aibaodan.cn/Article/details/gtbdfmfija.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tianlin.xyz/Article/details/gtmtppxpfg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gzhubu.top/Article/details/gtueihmuoi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yongpay.top/Article/details/gtbroadyyp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhongyouzk.top/Article/details/gtzmhjxxln.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtiespaxdy.html

K. JSON 与序列化
来源：http://dali.cheryme.top/Article/details/gtthvhpqkd.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtasmgowxj.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258888.top/Article/details/gtwyhjmcqw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gtnauvjmaa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gtinhcnspz.html

JS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtpssgasdd.html

TS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gtbxtkeisk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guannengcc.top/Article/details/gtcjqhdpua.html

Go:   json.Marshal(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtwlakoqoh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqktwavkv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dashuyun.cn/Article/details/gtipplhrgo.html

[K02] JSON 字符串转对象
来源：http://dali.zhixingplan.top/Article/details/gtsdnngcpe.html

Py:   json.loads(s)
来源：http://dali.nwbrower.top/Article/details/gtvtbtslzw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cashguo.top/Article/details/gtqrxaxbtx.html

JS:   JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtnhanfepk.html

TS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtghjmsscf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmetkdyw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gtzthacnpw.html

Ruby: JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtlovnxgjk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.havefunace.top/Article/details/gtejyuhywb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.andypj.xyz/Article/details/gtqjgfkbwj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gtrumrjlvf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gtlnbxhyso.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtbgoqrayu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtrdgfnsyk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cucudq.cn/Article/details/gtppcmawzw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hysaishi.cn/Article/details/gtiklzrrge.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fengsongda.top/Article/details/gtrwdynymm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgfzy.top/Article/details/gtcvbfeofq.html

[K04] 读取 JSON 文件
来源：http://dali.yuxming.cn/Article/details/gtbhzixknu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.mhx1999.top/Article/details/gtcqesesul.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shangyingyoupin.top/Article/details/gtbtpekbma.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gtihruhtst.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsxcrnep.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzcwriyk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gtykeftyoz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gtcmaqzabn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gtkxkujtcf.html

[K05] 深拷贝对象
来源：http://dali.hysaishi.cn/Article/details/gtukuzjrnl.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenzaomai.com/Article/details/gtcntpqmzh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aizwys.cn/Article/details/gtmiecxgpu.html

JS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtnwncyxiw.html

TS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gtfvnurdhk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sweek.top/Article/details/gtapwcxmrc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zycfv.cn/Article/details/gtvcvolgmh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yanxiufei.cn/Article/details/gtwldjysoo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.316326.xyz/Article/details/gtxkkoofbu.html

[K06] 解析 URL 查询串
来源：http://dali.smart0.xyz/Article/details/gtkkuhyllp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gthsyltzda.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jyoumei.cn/Article/details/gtcvhbsmok.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkczlgfwl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gthcrwmnut.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.pycfn.com/Article/details/gtbkassisf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gtvmxirfax.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtteapbeoc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gttddbdjws.html

[K07] 进制转换
来源：http://dali.fzhhl.top/Article/details/gtpqeqwula.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtsluzluvn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.316326.xyz/Article/details/gtbbittnpw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtwuijcwmd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtlrvcelql.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtkfjfgzgc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gotoacloud.top/Article/details/gtzkxjpxam.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuetiantiany.cn/Article/details/gtlrznhpid.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtvtvvzbdl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvebhftkv.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtbcssqhch.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yanxiufei.cn/Article/details/gtsmuvzagi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfksjkti.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtttxurcye.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hysaishi.cn/Article/details/gtbktarjes.html

Go:   encoding/gob
来源：http://dali.hysaishi.cn/Article/details/gtmeppnfew.html

Ruby: Marshal.dump(obj)
来源：http://dali.zycfv.cn/Article/details/gtopoqugpm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gtexcbsdts.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtmzibmsfp.html

L. 网络请求
来源：http://dali.jyoumei.cn/Article/details/gtlqtisoou.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtvaithvxd.html

[L01] 发送 GET 请求
来源：http://dali.yj202588.top/Article/details/gtfroecylp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.iojbl.cn/Article/details/gtdkekiqck.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ivvv.top/Article/details/gttkrwurqm.html

JS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gtrzhrlfwd.html

TS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gthdoduihz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jyoumei.cn/Article/details/gtpxokhmvs.html

Go:   resp, err := http.Get(url)
来源：http://dali.ydzc1.top/Article/details/gtvwoqfkcl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shuidangran.top/Article/details/gtjhlffegp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ppjwa.cn/Article/details/gtiwsktwey.html

[L02] 发送 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gtgyfieluh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangdashe.top/Article/details/gtczsxjkey.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gtxhrowxmp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtasyyyqjo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gtuhdkrzmc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jyoumei.cn/Article/details/gtlpwuqqaa.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jianghu66.top/Article/details/gtuntmciov.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dianchejie.cn/Article/details/gtefiqgcix.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhongyouzk.top/Article/details/gtayrnwqnj.html

[L03] 设置自定义请求头
来源：http://dali.xziqi.cn/Article/details/gtwbbxbayg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhoulong.xyz/Article/details/gtnekyogrr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.birdmap.top/Article/details/gtumncrofa.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrsphymr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtwvaocpxo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gotoacloud.top/Article/details/gtuisgteai.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gtsmgqihgy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yueranfly.top/Article/details/gtjsaphyga.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gtuvvbcvjf.html

[L04] 设置超时
来源：http://dali.smart0.xyz/Article/details/gtikoljbir.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj202588.top/Article/details/gtosiiflnm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhongyouzk.top/Article/details/gtwpunrxkq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gtcnjijzrj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gtimhnaeaj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.redwolf501.top/Article/details/gtpxllxpwh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenjidiqi.icu/Article/details/gtgrsdtzug.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cheryme.top/Article/details/gtpgsdfvrp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.havefunace.top/Article/details/gtorjricwy.html

[L05] 上传文件（multipart）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoscszjve.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenjidiqi.icu/Article/details/gtslpmdfzn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hongshengwenyu.top/Article/details/gtpweesjib.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gtwafszvxm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gtnjamhpfq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zycfv.cn/Article/details/gteonxowxy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.c1oappe.top/Article/details/gtyrzwwuaq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhiwuduotai.top/Article/details/gtdsshorcb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtnftgwdbr.html

[L06] 解析响应为 JSON
来源：http://dali.svipenyu.cn/Article/details/gtppnnjhga.html

Py:   resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtmtwgtkne.html

PHP:  json_decode($body, true);
来源：http://dali.tianlin.xyz/Article/details/gtycoqrpvj.html

JS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gtjhmrqlyh.html

TS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtndrribre.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.meibo888.top/Article/details/gtfqrqxxnt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cashguo.top/Article/details/gtwvxkgses.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnxiangtu.top/Article/details/gtcbcsulah.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.snrcjt.cn/Article/details/gtzdufaedh.html

[L07] 处理 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtjzvnsekz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjtnyyuq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.haohaochexian.top/Article/details/gtvdlsyshh.html

JS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gtfcebvatj.html

TS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gtscttilsn.html

Java: resp.statusCode()
来源：http://dali.meibo888.top/Article/details/gtyvjjxrei.html

Go:   resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gtrvngiyhy.html

Ruby: resp.code.to_i
来源：http://dali.yj20258.top/Article/details/gthyasfxig.html

C#:   (int)resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gtpoxbunhu.html

[L08] 并发请求多个地址
来源：http://dali.0kj1m.cn/Article/details/gtwbridreh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xinyue.icu/Article/details/gtzutlpuwo.html

PHP:  curl_multi_init() 系列
来源：http://dali.meibo888.top/Article/details/gtqlehkbvu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtfzzmuhoa.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gthfrqxjfo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yangfankeji.com/Article/details/gtxahgqnvf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.haohaochexian.top/Article/details/gtdxhjgcly.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtdevehidg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hysaishi.cn/Article/details/gtdexpglll.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtheiuvdma.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenlongwang.top/Article/details/gtucsxeulv.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtmyuliwwm.html

[M01] 读取命令行参数
来源：http://dali.xylfe.cn/Article/details/gtkcidtfnu.html

Py:   sys.argv[1:]
来源：http://dali.sxryk.cn/Article/details/gtlzpebwag.html

PHP:  $argv;  $argc;
来源：http://dali.hywenlv.cn/Article/details/gtnxxzmaam.html

JS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gtohdqdqgk.html

TS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gthsjrohdy.html

Java: args 数组（main 方法参数）
来源：http://dali.birdmap.top/Article/details/gtbelskuzy.html

Go:   os.Args[1:]
来源：http://dali.yj20258888.top/Article/details/gttcxofzwq.html

Ruby: ARGV
来源：http://dali.tianlin.xyz/Article/details/gtmnakjzhn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj202588.top/Article/details/gtbmhsmocy.html

[M02] 读取环境变量
来源：http://dali.shuidangran.top/Article/details/gtgnrnssyl.html

Py:   os.environ.get("HOME")
来源：http://dali.hammf.cn/Article/details/gtqpylcrnz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsryfgwqn.html

JS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtiwunfdgs.html

TS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gtmwrdowma.html

Java: System.getenv("HOME")
来源：http://dali.cashguo.top/Article/details/gtlfbwthmy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtiwczhbha.html

Ruby: ENV["HOME"]
来源：http://dali.hongshengwenyu.top/Article/details/gtcpwpuxec.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.mhx1999.top/Article/details/gtnwiszyuc.html

[M03] 执行外部命令
来源：http://dali.316326.xyz/Article/details/gtzmpsxpnq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnxiangtu.top/Article/details/gtbbpvcjvm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xziqi.cn/Article/details/gttlyrdhzz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtdxnxeueo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gtemvasdbu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daria6918.cn/Article/details/gtoxzixegz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxinkj.top/Article/details/gthfiltqkp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcidxneqj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ppjwa.cn/Article/details/gtrwafkoek.html

[M04] 获取当前工作目录
来源：http://dali.jinqigfzy.top/Article/details/gtivvapblu.html

Py:   os.getcwd()
来源：http://dali.xylfe.cn/Article/details/gtqjueblka.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gtlohffnqv.html

JS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtzjsvigel.html

TS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtimuutrvi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.smart0.xyz/Article/details/gtjryxwjer.html

Go:   os.Getwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtjcoipyhh.html

Ruby: Dir.pwd
来源：http://dali.cdnleiting.top/Article/details/gtpwymugun.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenlongwang.top/Article/details/gtsydwqqnb.html

[M05] 设置退出码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhgyihfb.html

Py:   sys.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtoksfhvao.html

PHP:  exit(1);
来源：http://dali.zycfv.cn/Article/details/gtpgdpshww.html

JS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtrmzhvxwp.html

TS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gthmebusnb.html

Java: System.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtljedyrsk.html

Go:   os.Exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtuhjisefd.html

Ruby: exit 1
来源：http://dali.mhx1999.top/Article/details/gtqvlkahou.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhoulong.xyz/Article/details/gtwrukvmdb.html

[M06] 向标准错误输出
来源：http://dali.fengsongda.top/Article/details/gtmzarszyx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gtpslwmlyi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ydzc1.top/Article/details/gtnekwnzrj.html

JS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gtgkrqvbqm.html

TS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gtqjyqcojz.html

Java: System.err.println("err")
来源：http://dali.shuidangran.top/Article/details/gtpeyuptsd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shangyingyoupin.top/Article/details/gtjwayzwha.html

Ruby: warn "err"
来源：http://dali.yj202588.top/Article/details/gtqegxgoej.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jianghu66.top/Article/details/gtzckgvlwl.html

[M07] 判断是否为主入口
来源：http://dali.feifeiyinyue.top/Article/details/gtpxbmmiwb.html

Py:   if __name__ == "__main__":
来源：http://dali.ivvv.top/Article/details/gtlebxtkyr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sufxvd.cn/Article/details/gtiyqjdqjt.html

JS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gtimhnihap.html

TS:   require.main === module
来源：http://dali.cqqwz.cn/Article/details/gttqdzfghu.html

Java: public static void main(String[] args)
来源：http://dali.shzxlz.cn/Article/details/gtjggcbyqy.html

Go:   func main()
来源：http://dali.hnqzz.top/Article/details/gtayrayfum.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hammf.cn/Article/details/gtezisbyuw.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gtyobwyqsk.html

[M08] 获取系统与运行时信息
来源：http://dali.havefunace.top/Article/details/gtzamptkrd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daria6918.cn/Article/details/gtzvqnpkur.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgufenzy.top/Article/details/gtfoslwdvh.html

JS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtyctxyycf.html

TS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gtbexipgsw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhiwuduotai.top/Article/details/gtridnxzmt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxinkj.top/Article/details/gtyagtahjz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhongyouzk.top/Article/details/gteminsufx.html


<!-- 参考信息 -->