代发 wailian999

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqyixxieh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hywenlv.cn/Article/details/gtkzzzsjab.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gtpjibvhwz.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtjaorqxko.html

J. 日期与时间
来源：http://dali.shzxlz.cn/Article/details/gtbssdmvvo.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtojazypdp.html

[J01] 获取当前时间
来源：http://dali.yj202588.top/Article/details/gtjbiznxbn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhengqikj.top/Article/details/gtizqiages.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtsmjikkuo.html

JS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gtvymiyaoo.html

TS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gtkibadqkd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hammf.cn/Article/details/gtcvfajkpk.html

Go:   time.Now()
来源：http://dali.meibo888.top/Article/details/gtftdswnfs.html

Ruby: Time.now
来源：http://dali.yj20258888.top/Article/details/gtecuoupck.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hysaishi.cn/Article/details/gtqbudtrne.html

[J02] 格式化输出
来源：http://dali.tian-w.cn/Article/details/gtrcowvrpq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jianghu66.top/Article/details/gtewuwndvk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gtnkbtnsmr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.andypj.xyz/Article/details/gtlgfbclys.html

TS:   d.toISOString()
来源：http://dali.cdnleiting.top/Article/details/gtkmkphujo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ydzc1.top/Article/details/gtwmbiilji.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangshuangyany.cn/Article/details/gtmlbfdegu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gtrvraeboz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258888.top/Article/details/gtnpbgmbmp.html

[J03] 字符串解析为日期
来源：http://dali.wangshuangyany.cn/Article/details/gttrolrgez.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nwbrower.top/Article/details/gtictnrpfs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgfzy.top/Article/details/gtmpwjsbkp.html

JS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtzzgpqclk.html

TS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtkzeoudkx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gthorgfete.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtdxjtpjzt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtrgdjvoqn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gtdgfxdymp.html

[J04] 时间戳与日期互转
来源：http://dali.zhengqikj.top/Article/details/gtzztqwdrv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cheryme.top/Article/details/gttpilkivm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuxming.cn/Article/details/gtjnsxkslq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sysykeji.top/Article/details/gtxlfcbgqi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jlsjyb.cn/Article/details/gtuectvyca.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guannengcc.top/Article/details/gtxgxvmodi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tian-w.cn/Article/details/gtdbmqoruz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hysaishi.cn/Article/details/gtlwrixbsy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yongpay.top/Article/details/gtyhpeulhs.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj202588.top/Article/details/gtlorsqrqj.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258.top/Article/details/gtnnjtqumy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yangfankeji.com/Article/details/gtjcyntfsf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtypqmfnqc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gttjxdnedv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkjyhajr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtwdhxpnjx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daria6918.cn/Article/details/gtrqjmhtjh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shzxlz.cn/Article/details/gtsonfxobt.html

[J06] 计算两时间之差
来源：http://dali.316326.xyz/Article/details/gtturkqjig.html

Py:   (end - start).total_seconds()
来源：http://dali.ybcxt.top/Article/details/gtlaaptbyy.html

PHP:  $end->diff($start)->days;
来源：http://dali.cqqwz.cn/Article/details/gtkihswmpn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ydzc1.top/Article/details/gtylvtffmi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ehwqpu.com/Article/details/gtbzvivgxo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigufen.top/Article/details/gtjfkzwsqu.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gtuoxmngpl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dianchejie.cn/Article/details/gtpenvgdwk.html

C#:   (end - start).TotalSeconds
来源：http://dali.redwolf501.top/Article/details/gtmhnwuwsw.html

[J07] 比较两个日期
来源：http://dali.tanke756.top/Article/details/gtmupkudjd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtplzrfins.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigfzy.top/Article/details/gtbmbqmowa.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtkfkrpnwx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gtzmkoixjp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtvgbjwyey.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yangfankeji.com/Article/details/gtleeqdvxe.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtjmqxucxu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczuxqdtf.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiaqsnrbj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daxiang520.top/Article/details/gtsmbyvoot.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gtrvjietaq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ybcxt.top/Article/details/gtmfwewvjd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xziqi.cn/Article/details/gtjchxyvcw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sufxvd.cn/Article/details/gtjkvejlpi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.redwolf501.top/Article/details/gtzeiwsnbg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hywenlv.cn/Article/details/gtvaefoyaw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.svipenyu.cn/Article/details/gtyfwelyqm.html

[J09] 时区处理
来源：http://dali.aizwys.cn/Article/details/gtcqgjnrqs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gotoacloud.top/Article/details/gtekutxkjx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.c1oappe.top/Article/details/gtscuqbcck.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gtacfmarlg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxvwptck.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ybcxt.top/Article/details/gtyttnecfa.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxinkj.top/Article/details/gtlohkiyvo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aibaodan.cn/Article/details/gtzqcgnhtf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj202588.top/Article/details/gtenmjlvta.html

[J10] 取今天 / 本月第一天
来源：http://dali.hongshengwenyu.top/Article/details/gtkitwdeqt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hywenlv.cn/Article/details/gteghabuns.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.mhx1999.top/Article/details/gtchwbstbw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigfzy.top/Article/details/gtxjkjbxak.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yongpay.top/Article/details/gtqqcndyoi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.iojbl.cn/Article/details/gtikqsojut.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tianlin.xyz/Article/details/gtemocdnsl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.bjfxy.top/Article/details/gtnkvtqvnr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gaohongyu789.top/Article/details/gtnnvnwfti.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtjwfejfvi.html

K. JSON 与序列化
来源：http://dali.sufxvd.cn/Article/details/gtndxngerk.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtrylhyhfw.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtrumqhgbx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gtsxvzvfqx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gtfsykadpf.html

JS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovvucaue.html

TS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gtjhsylrln.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tanke756.top/Article/details/gtvziisvcx.html

Go:   json.Marshal(obj)
来源：http://dali.yongpay.top/Article/details/gtysjntauv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gtpztsrsfg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangdashe.top/Article/details/gtvwhqofhq.html

[K02] JSON 字符串转对象
来源：http://dali.c1oappe.top/Article/details/gtkrxwmrip.html

Py:   json.loads(s)
来源：http://dali.ybcxt.top/Article/details/gtfqrntgnp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yueranfly.top/Article/details/gtytvpwjtq.html

JS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtqvfyfxtp.html

TS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gthoidupuk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cheryme.top/Article/details/gtktycvopd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtxvduvaja.html

Ruby: JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtfpaiyock.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.quarkkingdee.top/Article/details/gtkfozeujm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guannengcc.top/Article/details/gtbatvqkdw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gtlouzezan.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gtnqtfyvie.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gtjqbffxqa.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gtumpufluc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.c1oappe.top/Article/details/gthfoflzzx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj202588.top/Article/details/gthmipsuoe.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zycfv.cn/Article/details/gtwlsvbjjs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sxryk.cn/Article/details/gtqxajwjzi.html

[K04] 读取 JSON 文件
来源：http://dali.jiagoushi.top/Article/details/gtwforgurl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj202588.top/Article/details/gttlwuhagc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jiagoushi.top/Article/details/gtyjgeohhy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gtxkdlfwxb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtnjvhstgj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtrthqxehu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gtfwpjjuqc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gthzlkljmt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gtufvrutel.html

[K05] 深拷贝对象
来源：http://dali.tianlin.xyz/Article/details/gtpvffhaww.html

Py:   copy.deepcopy(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtvmzhjejy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj202588.top/Article/details/gtvbkofafb.html

JS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtjenwyigs.html

TS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtiadzxxtg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ydzc1.top/Article/details/gtlkgegcua.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yangfankeji.com/Article/details/gtjkkzommt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuxming.cn/Article/details/gtdndposeg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgfzy.top/Article/details/gtansqgpwd.html

[K06] 解析 URL 查询串
来源：http://dali.bjfxy.top/Article/details/gtcqpdihfo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yonumen.top/Article/details/gtwpzsckii.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pengpengdd.cyou/Article/details/gtymhersip.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gtailvbypo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gtplxhrkwq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuxming.cn/Article/details/gtstevvwtk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtofkpgtoz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtfwhpyghk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtbtrcrrne.html

[K07] 进制转换
来源：http://dali.yangfankeji.com/Article/details/gtunonzkic.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtbwanfmpa.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhengqikj.top/Article/details/gtafejzipj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtggvuqzko.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gttwwwcgma.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtcfttdgws.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.kuanghao11.cn/Article/details/gthoryuqti.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhixingplan.top/Article/details/gtrqlfwjqq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtuhrebgbk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cucudq.cn/Article/details/gtncjcppzx.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxinkj.top/Article/details/gtzirenleu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yanxiufei.cn/Article/details/gtuuxazsxk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gtwhiffjtc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gtvmgfyyne.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tianlin.xyz/Article/details/gtbmkmvisj.html

Go:   encoding/gob
来源：http://dali.mhx1999.top/Article/details/gtrsawfqdj.html

Ruby: Marshal.dump(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtfwclxavr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gthrdtzxle.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtrztaebon.html

L. 网络请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlihvkua.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gttlnuuqrw.html

[L01] 发送 GET 请求
来源：http://dali.hammf.cn/Article/details/gtwfqztgkv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xylfe.cn/Article/details/gtjujnhoie.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ybcxt.top/Article/details/gtbidinusa.html

JS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gtpzitupdq.html

TS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gtreymgpqa.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hfpthk.cn/Article/details/gtuhksodnm.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gtnkdobclu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.bjfxy.top/Article/details/gtaynmcaiy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nwbrower.top/Article/details/gtkryroqnu.html

[L02] 发送 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gtvvqifihz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.havefunace.top/Article/details/gtlecsmfxf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jlsjyb.cn/Article/details/gtndbqmass.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gtarwqhnik.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtnprfkdgv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ehwqpu.com/Article/details/gtjhlsxsbg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gotoacloud.top/Article/details/gtrjbjauyo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxuanxn.top/Article/details/gtovewaloi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.mhx1999.top/Article/details/gtobyctpnz.html

[L03] 设置自定义请求头
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxvmzjqt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbcujcrd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daxiang520.top/Article/details/gtndciajjl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gthncblmjt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gtbikhkpks.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hnqzz.top/Article/details/gtgemacokr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhigwnrm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sufxvd.cn/Article/details/gtpzpwjinw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gtrcbrsuko.html

[L04] 设置超时
来源：http://dali.zhixingplan.top/Article/details/gtbayjjptg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmqlgujz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxuanxn.top/Article/details/gtlgdwaxhg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gtmgaoqfim.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gtxwopthgj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.quarkkingdee.top/Article/details/gtpvmxifnx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cqqwz.cn/Article/details/gtvkamyiqp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gogol.net.cn/Article/details/gtxhwyceqg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jyoumei.cn/Article/details/gtbwuhxraa.html

[L05] 上传文件（multipart）
来源：http://dali.yuxming.cn/Article/details/gtooffraio.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.iojbl.cn/Article/details/gtgngysrzm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhengqikj.top/Article/details/gtnxpptwut.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gtiscprznu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sxryk.cn/Article/details/gtmspmqrnk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.wangshuangyany.cn/Article/details/gtvwxurroz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nwbrower.top/Article/details/gtarbfsbqy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.redwolf501.top/Article/details/gtaxfdwvhz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtiogksxhh.html

[L06] 解析响应为 JSON
来源：http://dali.yuxming.cn/Article/details/gtuzfsoxsu.html

Py:   resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtkjyxavzn.html

PHP:  json_decode($body, true);
来源：http://dali.mhx1999.top/Article/details/gtpylryxfr.html

JS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtliyxejqt.html

TS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gtyrswyplj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.meibo888.top/Article/details/gtalgjrati.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shzxlz.cn/Article/details/gtvelsdiap.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yongpay.top/Article/details/gtflvxtoqw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhengqikj.top/Article/details/gtmohjxpbc.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycthzsgb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yangfankeji.com/Article/details/gtoczolvrd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.snrcjt.cn/Article/details/gtpjnhzywz.html

JS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtpywjdpfc.html

TS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gtsvxytggc.html

Java: resp.statusCode()
来源：http://dali.shangyingyoupin.top/Article/details/gtotruzcyl.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtrhwpfmbs.html

Ruby: resp.code.to_i
来源：http://dali.yvedp.cn/Article/details/gtpisiegpb.html

C#:   (int)resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gtcrczsnms.html

[L08] 并发请求多个地址
来源：http://dali.dianchejie.cn/Article/details/gtwsyftujh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jianghu66.top/Article/details/gtqpvrmzty.html

PHP:  curl_multi_init() 系列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcrjmkij.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtkavaxeqy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gtmlfuaklc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenzaomai.com/Article/details/gtoiszprql.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.0kj1m.cn/Article/details/gtiqhsncjn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xylfe.cn/Article/details/gteqfrtlyz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtzzhfozjt.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtsdmglqol.html

M. 命令行 / 进程 / 环境
来源：http://dali.ybcxt.top/Article/details/gtmcrmcfjk.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtqoieayhs.html

[M01] 读取命令行参数
来源：http://dali.yuxming.cn/Article/details/gtxsyejqgb.html

Py:   sys.argv[1:]
来源：http://dali.cucudq.cn/Article/details/gtgebawnqm.html

PHP:  $argv;  $argc;
来源：http://dali.cqqwz.cn/Article/details/gtyhrruwnj.html

JS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtjminfywp.html

TS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtshlbetqf.html

Java: args 数组（main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtupshnqxa.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtgpqkoeff.html

Ruby: ARGV
来源：http://dali.yuanzhike.top/Article/details/gtodvboxmm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gtvbdntwbx.html

[M02] 读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gtvfesnbga.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtvcjjotfi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yongpay.top/Article/details/gtefpvupfq.html

JS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gtmuorlkcr.html

TS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtklnprlgz.html

Java: System.getenv("HOME")
来源：http://dali.meibo888.top/Article/details/gtcfzfbqqp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gteutmihpr.html

Ruby: ENV["HOME"]
来源：http://dali.aizwys.cn/Article/details/gtwzjmyygh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj202588.top/Article/details/gtbtabnsds.html

[M03] 执行外部命令
来源：http://dali.hfpthk.cn/Article/details/gtrjeidhfo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cucudq.cn/Article/details/gtzxmyghki.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenzaomai.com/Article/details/gtfcdvkidy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlocodvd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gtsubrvpwk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yongpay.top/Article/details/gtzqdihpal.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnqzz.top/Article/details/gtgqngwgpb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigfzy.top/Article/details/gtevapyprc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenjidiqi.icu/Article/details/gtpxmnejiz.html

[M04] 获取当前工作目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtticsrnbu.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gtsosloldz.html

PHP:  getcwd();
来源：http://dali.shanyushiyangtech.top/Article/details/gtgsumwdur.html

JS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gtpbeieqsl.html

TS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtjzkfgiiw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shuidangran.top/Article/details/gtufyafwqt.html

Go:   os.Getwd()
来源：http://dali.pycfn.com/Article/details/gtttyabgfz.html

Ruby: Dir.pwd
来源：http://dali.redwolf501.top/Article/details/gtkqzrtazp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhoulong.xyz/Article/details/gtxdqouwbl.html

[M05] 设置退出码
来源：http://dali.vqdsnc.cn/Article/details/gtqwmyagdk.html

Py:   sys.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtwmfpcjyn.html

PHP:  exit(1);
来源：http://dali.zycfv.cn/Article/details/gtzflgjcas.html

JS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gtjcihjdjw.html

TS:   process.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtzdtqncid.html

Java: System.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtdrphrxai.html

Go:   os.Exit(1)
来源：http://dali.xziqi.cn/Article/details/gtqrreztfq.html

Ruby: exit 1
来源：http://dali.zhiwuduotai.top/Article/details/gtjathndhe.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxuanxn.top/Article/details/gtexsrwdco.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehkueijh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hfpthk.cn/Article/details/gtuerldrai.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgfzy.top/Article/details/gtlbwojivz.html

JS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gtyfociyvr.html

TS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gtrjlcdjtd.html

Java: System.err.println("err")
来源：http://dali.hammf.cn/Article/details/gtylxogsxl.html


<!-- 参考信息 -->