代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuxming.cn/Article/details/gtmopjpeyw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sysykeji.top/Article/details/gtemjtyjdl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gtjvcgxpbx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258888.top/Article/details/gtxgpslncm.html

[J03] 字符串解析为日期
来源：http://dali.316326.xyz/Article/details/gttiiahnwl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.0kj1m.cn/Article/details/gtkqzefqmo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hongshengwenyu.top/Article/details/gtlfqmlxao.html

JS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtisdsapar.html

TS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtmknjujqj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtokxqmjma.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gthwbjphnf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtggfokzgx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenzaomai.com/Article/details/gtxggkpaxb.html

[J04] 时间戳与日期互转
来源：http://dali.zhixingplan.top/Article/details/gtyggtyzul.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtznzsqncz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jyoumei.cn/Article/details/gtxagtvyto.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xziqi.cn/Article/details/gtdruducoq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gzhubu.top/Article/details/gtwyvwzjge.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tanke756.top/Article/details/gtnelqlrdt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yangfankeji.com/Article/details/gtkceuaopf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.9152youxi.cn/Article/details/gtoszixfvi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuanzhike.top/Article/details/gtmshhrurj.html

[J05] 时间加减（加 7 天）
来源：http://dali.daxiang520.top/Article/details/gtbwgykclx.html

Py:   now + timedelta(days=7)
来源：http://dali.fzhhl.top/Article/details/gtonkkbsit.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zdqjudy.top/Article/details/gtmpwcjdsv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtradbtepr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gtoiiyonbb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuanzx.com/Article/details/gtowwjhvot.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daxiang520.top/Article/details/gtpvlvcqrp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pycfn.com/Article/details/gtrtqlaqys.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gtjewmlljk.html

[J06] 计算两时间之差
来源：http://dali.cheryme.top/Article/details/gtgqdnfelt.html

Py:   (end - start).total_seconds()
来源：http://dali.ivvv.top/Article/details/gtolkowajs.html

PHP:  $end->diff($start)->days;
来源：http://dali.xylfe.cn/Article/details/gtlvnilvju.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcymrgxgu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sufxvd.cn/Article/details/gthmfnecsl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.bjfxy.top/Article/details/gtsjtnbbjs.html

Go:   end.Sub(start).Hours()
来源：http://dali.gogol.net.cn/Article/details/gtqduywviq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.haohaochexian.top/Article/details/gtoqtqyyfb.html

C#:   (end - start).TotalSeconds
来源：http://dali.xylfe.cn/Article/details/gtlkigkvve.html

[J07] 比较两个日期
来源：http://dali.sxryk.cn/Article/details/gtmfphzidu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gtxungclca.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenlongwang.top/Article/details/gthczlwepn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgfzy.top/Article/details/gtcuuqogoe.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gtcxdtcpkr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hammf.cn/Article/details/gtyacicrge.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daxiang520.top/Article/details/gtnbscoonu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gtdjqkpjow.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtixltzzvw.html

[J08] 提取年月日与星期
来源：http://dali.cheryme.top/Article/details/gtfmjeoxmi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.c1oappe.top/Article/details/gtxtwkknyh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sufxvd.cn/Article/details/gttftwvuqr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daxiang520.top/Article/details/gtalwalgyj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258.top/Article/details/gtwrfdofab.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sysykeji.top/Article/details/gtovirnnkl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pycfn.com/Article/details/gtxfmzjlbw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuanzx.com/Article/details/gtsidhxpbj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shuidangran.top/Article/details/gtqublqswb.html

[J09] 时区处理
来源：http://dali.bjfxy.top/Article/details/gtqlealwsd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nwbrower.top/Article/details/gtgqfjadou.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jlsjyb.cn/Article/details/gtrhbqacdq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtharmmxgy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gtvekuqjcv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yanxiufei.cn/Article/details/gteltkeqlp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigufen.top/Article/details/gtkmjexqrq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yonumen.top/Article/details/gtsipboens.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xziqi.cn/Article/details/gtvdfqhlfc.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gtyzfjnjhu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj20258.top/Article/details/gtjojtsajc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ivvv.top/Article/details/gtfkfqdpga.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yvedp.cn/Article/details/gtvzbpqqiy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cashguo.top/Article/details/gtaptvofui.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aizwys.cn/Article/details/gtxvzrobld.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shangyingyoupin.top/Article/details/gtxvgmbgcn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.0kj1m.cn/Article/details/gtfupisklo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cashguo.top/Article/details/gtsbcdbhad.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtxnlayido.html

K. JSON 与序列化
来源：http://dali.zdqjudy.top/Article/details/gtmmhhkhsw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmhrwnbg.html

[K01] 对象转 JSON 字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtsfhpzssg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gtknpsmbjb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtjpmoscom.html

JS:   JSON.stringify(obj)
来源：http://dali.yuanzhike.top/Article/details/gtjlpumoxt.html

TS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gtdmhqdymx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuxming.cn/Article/details/gtrwkloyiq.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gtwrfhnpzf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhixingplan.top/Article/details/gtmrcebncp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtwbjzxakz.html

[K02] JSON 字符串转对象
来源：http://dali.ybcxt.top/Article/details/gtpchsggtw.html

Py:   json.loads(s)
来源：http://dali.iojbl.cn/Article/details/gtxfkekxbr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.bjfxy.top/Article/details/gtwwmaqpad.html

JS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtyojhvvyc.html

TS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtviciycna.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcitkdwem.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gtonnjcvmt.html

Ruby: JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtunmksxlj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.316326.xyz/Article/details/gtztbukuti.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jiagoushi.top/Article/details/gtdlabwaxy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gtijnfjvgj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtmwlvfuau.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtcsqppcxi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gteckimxox.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fzhhl.top/Article/details/gtqpsddpca.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guannengcc.top/Article/details/gtcezhdlzk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jyoumei.cn/Article/details/gtoqqywikm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cheryme.top/Article/details/gtnefilqgy.html

[K04] 读取 JSON 文件
来源：http://dali.cqqwz.cn/Article/details/gtvrgkrmpb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.0kj1m.cn/Article/details/gttyxxgjia.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gzhubu.top/Article/details/gtypoppxbk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gtjsozsyvp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gtnrvloowy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtedprlsfz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gtrolrwxty.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwdfjlvc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.smart0.xyz/Article/details/gtaqdrtghx.html

[K05] 深拷贝对象
来源：http://dali.jqgfzy.top/Article/details/gtpzkfwtjv.html

Py:   copy.deepcopy(obj)
来源：http://dali.yangfankeji.com/Article/details/gtkztcsglo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hfpthk.cn/Article/details/gtsjsrzwmy.html

JS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gthzqimxqp.html

TS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gtmehbtjbt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sxryk.cn/Article/details/gtwmciryqn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangshuangyany.cn/Article/details/gtboxyejul.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daxiang520.top/Article/details/gtsprnmbod.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.iojbl.cn/Article/details/gtonbcyxyd.html

[K06] 解析 URL 查询串
来源：http://dali.vqdsnc.cn/Article/details/gtazkuoexi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.havefunace.top/Article/details/gtfmmrjngw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigfzy.top/Article/details/gtvoklabay.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gtfpusgozl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gtabesblkb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.redwolf501.top/Article/details/gtijjboxqe.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtmozsdppg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtleqqpbfe.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gtnfwfptbv.html

[K07] 进制转换
来源：http://dali.daria6918.cn/Article/details/gtroxirztw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttylrjvav.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddczxbed.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtlqvwnztq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtekysrezd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtayqqmwti.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sysykeji.top/Article/details/gtqgrbhvka.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guowangkeji.top/Article/details/gttvmngiaj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtwonhnnjs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xziqi.cn/Article/details/gtlceovppu.html

Py:   pickle.dumps(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtlitgwduu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.birdmap.top/Article/details/gttjyhymer.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gtueclxcjb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gtcmpmidec.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guannengcc.top/Article/details/gtmbncjepr.html

Go:   encoding/gob
来源：http://dali.tianlin.xyz/Article/details/gtvpcrnmwp.html

Ruby: Marshal.dump(obj)
来源：http://dali.redwolf501.top/Article/details/gtbmwqrfpy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gtaldgjuds.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtzhpvycsy.html

L. 网络请求
来源：http://dali.zycfv.cn/Article/details/gtyaprcqkg.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtkxstyrak.html

[L01] 发送 GET 请求
来源：http://dali.cashguo.top/Article/details/gthrexqwvt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.0kj1m.cn/Article/details/gtbcenmvmf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sxryk.cn/Article/details/gtshttqggk.html

JS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gtvvezvgoi.html

TS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gtmrkeeqhp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnxiangtu.top/Article/details/gtqglrlqtd.html

Go:   resp, err := http.Get(url)
来源：http://dali.haohaochexian.top/Article/details/gtmlyfvkmg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenlongwang.top/Article/details/gtxcdlpfvx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.havefunace.top/Article/details/gtfngzlajy.html

[L02] 发送 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtdgctajpu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258.top/Article/details/gtrvdbjliq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.iojbl.cn/Article/details/gtanrrcbdx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gtcyekufcl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gtknamefdw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yanxiufei.cn/Article/details/gtrvpyredj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.meibo888.top/Article/details/gtfuskfnzc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenlongwang.top/Article/details/gtiyzpwtrk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yvedp.cn/Article/details/gtomoypbjp.html

[L03] 设置自定义请求头
来源：http://dali.c1oappe.top/Article/details/gtbkdqjohx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daria6918.cn/Article/details/gtfrdbelgc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sufxvd.cn/Article/details/gtldxccwmg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtnbmbwncg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gtpamlhzog.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tianlin.xyz/Article/details/gtvaylvqwb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoaghqxpg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nwbrower.top/Article/details/gtpzzdkjwi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifnbxdix.html

[L04] 设置超时
来源：http://dali.316326.xyz/Article/details/gtetddsllp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgufenzy.top/Article/details/gtfyatklbn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cucudq.cn/Article/details/gtbegnizfr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gtwowtjknx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gtgqmommbu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gaohongyu789.top/Article/details/gthbfmmyqq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dianchejie.cn/Article/details/gtwodmctpx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgyxkotr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tanke756.top/Article/details/gtkzscxath.html

[L05] 上传文件（multipart）
来源：http://dali.sufxvd.cn/Article/details/gtmwoaznhu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.andypj.xyz/Article/details/gtrfpvntuk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ydzc1.top/Article/details/gtobxdcboj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gtcewopzqc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtwgmakuan.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gtcrgrpbdx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrvdnpvn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxzpylqz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtdnbvelwv.html

[L06] 解析响应为 JSON
来源：http://dali.sweek.top/Article/details/gtxxpvcuvy.html

Py:   resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtgunilyks.html

PHP:  json_decode($body, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtowtmfnps.html

JS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gtjyktbbwl.html

TS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gtfnxjlpdl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.mhx1999.top/Article/details/gtbscfrgcw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yongpay.top/Article/details/gtbiqorlws.html

Ruby: JSON.parse(resp.body)
来源：http://dali.bjfxy.top/Article/details/gthpcboeak.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigfzy.top/Article/details/gtrrcvyufk.html

[L07] 处理 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gthopjkivi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuanzx.com/Article/details/gtjogclhox.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gtjaewzeyc.html

JS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gthztdjyhr.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtlgowgbpn.html

Java: resp.statusCode()
来源：http://dali.tianlin.xyz/Article/details/gtatrdbhhc.html

Go:   resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gtdhuitwao.html

Ruby: resp.code.to_i
来源：http://dali.haohaochexian.top/Article/details/gtqmquybtt.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gtxupkcyvg.html

[L08] 并发请求多个地址
来源：http://dali.hysaishi.cn/Article/details/gtjdmkvvxb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yongpay.top/Article/details/gtfnmsorbp.html

PHP:  curl_multi_init() 系列
来源：http://dali.gogol.net.cn/Article/details/gtbpoeweqb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gtyiyqjlok.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gtwlbsbyyx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.quarkkingdee.top/Article/details/gtkvjzuzui.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.redwolf501.top/Article/details/gtjgpvmbia.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gtnwxyraqd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hammf.cn/Article/details/gtzrcdsyyi.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gttbwienhf.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenlongwang.top/Article/details/gtxlgsuwui.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtyhqvmeux.html

[M01] 读取命令行参数
来源：http://dali.fengsongda.top/Article/details/gtszbgydgh.html

Py:   sys.argv[1:]
来源：http://dali.zdqjudy.top/Article/details/gtrdzmapab.html

PHP:  $argv;  $argc;
来源：http://dali.bjfxy.top/Article/details/gtqpzuntfe.html

JS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtvbqqaidv.html

TS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gtabjwojyz.html

Java: args 数组（main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gtggosolqq.html

Go:   os.Args[1:]
来源：http://dali.cdnleiting.top/Article/details/gtpemsaowp.html

Ruby: ARGV
来源：http://dali.hysaishi.cn/Article/details/gtoxumfogb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtargynvhm.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtapirskjk.html

Py:   os.environ.get("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtslibdpzu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gtputiotlf.html

JS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnxchsgo.html

TS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gtokcmhyun.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtgvwwkdkg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtwgickeuv.html

Ruby: ENV["HOME"]
来源：http://dali.cqqwz.cn/Article/details/gtltciimpm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtasxebfub.html

[M03] 执行外部命令
来源：http://dali.yanxiufei.cn/Article/details/gtbnkndlzs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pycfn.com/Article/details/gtrnpjegnd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.wangshuangyany.cn/Article/details/gtwfobvoxd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gtngguupqf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtczltdube.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuanzhike.top/Article/details/gttjznukuv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yangfankeji.com/Article/details/gtaycrhvmm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.redwolf501.top/Article/details/gthvtejtik.html

C#:   Process.Start("ls", "-l");
来源：http://dali.andypj.xyz/Article/details/gtlvhhxjhz.html

[M04] 获取当前工作目录
来源：http://dali.jinqigufen.top/Article/details/gtnmxwjhzw.html

Py:   os.getcwd()
来源：http://dali.daria6918.cn/Article/details/gtcyugqqjp.html

PHP:  getcwd();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyebqbzjv.html

JS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gtjehzfiwn.html

TS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gtmnycykrl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jyoumei.cn/Article/details/gtphifysmx.html

Go:   os.Getwd()
来源：http://dali.yuxming.cn/Article/details/gtdnalkktr.html

Ruby: Dir.pwd
来源：http://dali.zycfv.cn/Article/details/gtuytabedw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aizwys.cn/Article/details/gtqkclsful.html

[M05] 设置退出码
来源：http://dali.tian-w.cn/Article/details/gtxqaztjyh.html

Py:   sys.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gthdoidbpa.html

PHP:  exit(1);
来源：http://dali.hysaishi.cn/Article/details/gtvprxepto.html

JS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtytbcnytz.html

TS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gtlnjtxoze.html

Java: System.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtuidptonc.html

Go:   os.Exit(1)
来源：http://dali.cashguo.top/Article/details/gtvxbcjmio.html

Ruby: exit 1
来源：http://dali.hysaishi.cn/Article/details/gtpylqhhxa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqfpjdcb.html

[M06] 向标准错误输出
来源：http://dali.tianlin.xyz/Article/details/gtyuqqaopq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gtrkgpratq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangshuangyany.cn/Article/details/gtlzvyplko.html

JS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gtnqgmchrv.html

TS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gtyptutkuj.html

Java: System.err.println("err")
来源：http://dali.zhongyouzk.top/Article/details/gtczokapbv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ydzc1.top/Article/details/gtagowqxxs.html

Ruby: warn "err"
来源：http://dali.jinghuilouyu.cn/Article/details/gtthyrmrsg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenzaomai.com/Article/details/gtslcrlxyc.html

[M07] 判断是否为主入口
来源：http://dali.shzxlz.cn/Article/details/gtnjfkrmpo.html

Py:   if __name__ == "__main__":
来源：http://dali.andypj.xyz/Article/details/gtujmioeut.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hongshengwenyu.top/Article/details/gtgnzygtfv.html

JS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkeucugbe.html

TS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gtkxpeszpq.html

Java: public static void main(String[] args)
来源：http://dali.hammf.cn/Article/details/gtmwingorp.html

Go:   func main()
来源：http://dali.cashguo.top/Article/details/gtrxxzgzcm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gogol.net.cn/Article/details/gtycopnsfm.html

C#:   static void Main(string[] args)
来源：http://dali.yanxiufei.cn/Article/details/gtvnjvbfvj.html

[M08] 获取系统与运行时信息
来源：http://dali.gaohongyu789.top/Article/details/gtseirpcxt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aizwys.cn/Article/details/gtvnurangj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinghuilouyu.cn/Article/details/gtzofmgntu.html

JS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gtvxwlvwaz.html

TS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gtfpfuqhzw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhixingplan.top/Article/details/gtafslbjsz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aibaodan.cn/Article/details/gtkhaolsbk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gotoacloud.top/Article/details/gthluzpizn.html


<!-- 参考信息 -->