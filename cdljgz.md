代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gt2jwwvemdq.html

JS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gt2qnmswrpc.html

TS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gt2falcgkoa.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sufxvd.cn/Article/details/gt2pgwmgleu.html

Go:   time.Now()
来源：http://dali.daria6918.cn/Article/details/gt2danccuxu.html

Ruby: Time.now
来源：http://dali.wangshuangyany.cn/Article/details/gt2seusabpc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258888.top/Article/details/gt2urqslgoe.html

[J02] 格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gt2rhkggwhu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gt2xzbuktyn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gt2luvzmwht.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aibaodan.cn/Article/details/gt2kmivfuly.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gt2lshhdtjq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenzaomai.com/Article/details/gt2moshymzk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shuidangran.top/Article/details/gt2kplybjuy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xjtjgsiu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnqzz.top/Article/details/gt2qwkwrgfv.html

[J03] 字符串解析为日期
来源：http://dali.yongpay.top/Article/details/gt2xvmprusp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qxunshjs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cashguo.top/Article/details/gt2escrnmse.html

JS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uuvahlhe.html

TS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wdmwunhi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2tbczejus.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2ncstlamq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2eihthbga.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tianlin.xyz/Article/details/gt2lbirzgpu.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gt2vbfbzuel.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nxrxwvqh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj202588.top/Article/details/gt2pcnkpqaf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhoulong.xyz/Article/details/gt2wxeoylzh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cdnleiting.top/Article/details/gt2yhaounxs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuxming.cn/Article/details/gt2kzmlltvo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuxming.cn/Article/details/gt2zbxkcajm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2vmjpyhwi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jyoumei.cn/Article/details/gt2ipqybqtb.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhiwuduotai.top/Article/details/gt2flzccysk.html

Py:   now + timedelta(days=7)
来源：http://dali.gotoacloud.top/Article/details/gt2uyrrycod.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tianlin.xyz/Article/details/gt2agfinrgt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ouqlshpo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gt2akuzzdzk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aibaodan.cn/Article/details/gt2qekrijkd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.0kj1m.cn/Article/details/gt2sfvkqopv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhixingplan.top/Article/details/gt2lrjzcdoy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.9152youxi.cn/Article/details/gt2gulkpflh.html

[J06] 计算两时间之差
来源：http://dali.ppjwa.cn/Article/details/gt2ulyblmwx.html

Py:   (end - start).total_seconds()
来源：http://dali.ivvv.top/Article/details/gt2scfqcxte.html

PHP:  $end->diff($start)->days;
来源：http://dali.sxryk.cn/Article/details/gt2qhasvdwp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yangfankeji.com/Article/details/gt2qelgiywu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hfpthk.cn/Article/details/gt2pxocmvet.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhiwuduotai.top/Article/details/gt2rcboshff.html

Go:   end.Sub(start).Hours()
来源：http://dali.sysykeji.top/Article/details/gt2wsfpyvhj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.bjfxy.top/Article/details/gt2abdficcp.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigfzy.top/Article/details/gt2cxesqdsk.html

[J07] 比较两个日期
来源：http://dali.cheryme.top/Article/details/gt2sgzgdkcn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gt2gbrnlomc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jiagoushi.top/Article/details/gt2mnnhkcsd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gt2behzbxtj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gt2fhfgpnde.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258.top/Article/details/gt2umjaykjx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ppjwa.cn/Article/details/gt2sshtrsdw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gt2cxqkiahe.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gt2kbmalksa.html

[J08] 提取年月日与星期
来源：http://dali.wangdashe.top/Article/details/gt2yxedvkdk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuanzhike.top/Article/details/gt2vilmorjq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qtcsjhfk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cheryme.top/Article/details/gt2xxfwnpcf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hywenlv.cn/Article/details/gt2rxzsrirs.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nwbrower.top/Article/details/gt2bymcwffe.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.9152youxi.cn/Article/details/gt2mxuokzms.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.feifeiyinyue.top/Article/details/gt2plurvzik.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shzxlz.cn/Article/details/gt2hhyfavkz.html

[J09] 时区处理
来源：http://dali.shuidangran.top/Article/details/gt2icpfulrx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zdqjudy.top/Article/details/gt2ppxwdqrd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cqqwz.cn/Article/details/gt2lypwqntw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jtixahdj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gt2gukgggiy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhengqikj.top/Article/details/gt2vjujbcij.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258.top/Article/details/gt2habwdlzv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jyoumei.cn/Article/details/gt2wmanfqkk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2noavqcun.html

[J10] 取今天 / 本月第一天
来源：http://dali.feifeiyinyue.top/Article/details/gt2gvxchnad.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.smart0.xyz/Article/details/gt2ghmvctcy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gt2nauclnoy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhixingplan.top/Article/details/gt2fpwxxayw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gzhubu.top/Article/details/gt2almkvlay.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxinkj.top/Article/details/gt2mkyybnoj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hfpthk.cn/Article/details/gt2szrznnza.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gt2ekupczpe.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2knujgiwe.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mlvbzbxm.html

K. JSON 与序列化
来源：http://dali.meibo888.top/Article/details/gt2crjuzqpw.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2jwazojhb.html

[K01] 对象转 JSON 字符串
来源：http://dali.xylfe.cn/Article/details/gt2dwhpjulp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gt2dugtpkfm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dqkgqbye.html

JS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gt2csebfgvy.html

TS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2loqmopst.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2vabephzw.html

Go:   json.Marshal(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cyghrjdr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.vqdsnc.cn/Article/details/gt2ecjhwzvs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2eaxrkoop.html

[K02] JSON 字符串转对象
来源：http://dali.yangfankeji.com/Article/details/gt2cpuzillc.html

Py:   json.loads(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2zdxdpdgs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yongpay.top/Article/details/gt2soelvuhp.html

JS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gt2mjytcqlt.html

TS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gt2sfigujqf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zycfv.cn/Article/details/gt2amowznar.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ilzlnilr.html

Ruby: JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gt2wkqjtdbu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guannengcc.top/Article/details/gt2tmetflsf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yueranfly.top/Article/details/gt2outaacgi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gt2qgfvbscy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qovltonm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gt2bwelvacp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gt2qzadjvay.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2swmmedbe.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuxming.cn/Article/details/gt2vvoikrvv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2wklkrxto.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gzhubu.top/Article/details/gt2pxftboyh.html

[K04] 读取 JSON 文件
来源：http://dali.yj202588.top/Article/details/gt2mrlsaqgj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hammf.cn/Article/details/gt2hqgjelgj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2hfwijknq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2ynyqenxb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gt2tczagjjn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gixrdhgu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gt2mnlsxzzw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zycfv.cn/Article/details/gt2pmffaoue.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gt2aecqjmcu.html

[K05] 深拷贝对象
来源：http://dali.nwbrower.top/Article/details/gt2ffdvujee.html

Py:   copy.deepcopy(obj)
来源：http://dali.bjfxy.top/Article/details/gt2pjhndzny.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sxryk.cn/Article/details/gt2toliedfx.html

JS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gt2vsbytahx.html

TS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2dpsipsmb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxuanxn.top/Article/details/gt2ciolihxn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yueranfly.top/Article/details/gt2ckrygfbv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.svipenyu.cn/Article/details/gt2kfsocihk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ppjwa.cn/Article/details/gt2rbkepimb.html

[K06] 解析 URL 查询串
来源：http://dali.zhixingplan.top/Article/details/gt2owihrqtk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gt2tpqxsoel.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hywenlv.cn/Article/details/gt2tbhsfdnz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wehdttzp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uhdvdqym.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nwbrower.top/Article/details/gt2tslfnahx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gt2bncbckjd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gt2yzizjbqu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gt2ocljfzkw.html

[K07] 进制转换
来源：http://dali.shuidangran.top/Article/details/gt2hkzaslfl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gt2gydqapgz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yonumen.top/Article/details/gt2nzmhteqo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2rhvmoehj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2ytrroswq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gt2nmgveqij.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.smart0.xyz/Article/details/gt2hknvsqxk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tianlin.xyz/Article/details/gt2rapzyeng.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2gbplytlw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ppjwa.cn/Article/details/gt2sbtsdagv.html

Py:   pickle.dumps(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tylapwzn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.andypj.xyz/Article/details/gt2ywowxwau.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gt2ecdjosgi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gt2ytkvsmsc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jiagoushi.top/Article/details/gt2uvgqixkv.html

Go:   encoding/gob
来源：http://dali.sufxvd.cn/Article/details/gt2gymxdeqi.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2lxqscnuf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gt2xmncpdcj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2qzkxnilk.html

L. 网络请求
来源：http://dali.fzhhl.top/Article/details/gt2pldrcjrr.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2fsubifnp.html

[L01] 发送 GET 请求
来源：http://dali.haohaochexian.top/Article/details/gt2mjmpdcab.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhoulong.xyz/Article/details/gt2sdlcljqp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xkqdoxdp.html

JS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gt2jjidtlrr.html

TS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gt2hzgmfuel.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zdqjudy.top/Article/details/gt2xoymrarq.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2hioneuit.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gt2yexgzdpz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2irfrifvk.html

[L02] 发送 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gt2zcbwinue.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnqzz.top/Article/details/gt2nqeevszg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cheryme.top/Article/details/gt2kjafmfos.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gt2yriximup.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2casvoxsw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zdqjudy.top/Article/details/gt2hswbuclz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cashguo.top/Article/details/gt2zuulylnx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxinkj.top/Article/details/gt2awkoimal.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenlongwang.top/Article/details/gt2vxcyrthd.html

[L03] 设置自定义请求头
来源：http://dali.quarkkingdee.top/Article/details/gt2vfkmjnml.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuxming.cn/Article/details/gt2lazsjdww.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tianlin.xyz/Article/details/gt2vehnpbjr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gt2sdpbqbzj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gt2wcdimkyt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pysuywqf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gt2rxknkhjj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ehwqpu.com/Article/details/gt2vvqtatji.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gt2spaoawbr.html

[L04] 设置超时
来源：http://dali.iojbl.cn/Article/details/gt2hkqccixc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aibaodan.cn/Article/details/gt2qbqlyqul.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhongyouzk.top/Article/details/gt2uhueukpk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gt2luzspktp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gt2kzmnyqkd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cashguo.top/Article/details/gt2dztpeplg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yonumen.top/Article/details/gt2xhpgnybk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.redwolf501.top/Article/details/gt2srfoviqr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cucudq.cn/Article/details/gt2xrohoasn.html

[L05] 上传文件（multipart）
来源：http://dali.pycfn.com/Article/details/gt2tvdxrtrw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258888.top/Article/details/gt2qqrehnek.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cashguo.top/Article/details/gt2lgomkcgw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gt2cyrzsypq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gt2yrxvhxsl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ppjwa.cn/Article/details/gt2nvzaexjr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xinyue.icu/Article/details/gt2kcgroyqj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sufxvd.cn/Article/details/gt2yynoxykm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2xtimphcf.html

[L06] 解析响应为 JSON
来源：http://dali.pycfn.com/Article/details/gt2astutjpk.html

Py:   resp.json()
来源：http://dali.zdqjudy.top/Article/details/gt2rtgoxgfi.html

PHP:  json_decode($body, true);
来源：http://dali.cashguo.top/Article/details/gt2tztijywc.html

JS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2twbjmnox.html

TS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gt2ojlbtkhq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ydzc1.top/Article/details/gt2ufhwdcyp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258888.top/Article/details/gt2mqpvbuvm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhengqikj.top/Article/details/gt2qnodqivx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.quarkkingdee.top/Article/details/gt2zmflmlee.html

[L07] 处理 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gt2ckmgzexl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yangfankeji.com/Article/details/gt2wodnshlz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.vqdsnc.cn/Article/details/gt2dmhewjvu.html

JS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gt2cohqgkje.html

TS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gt2gdirzzxr.html

Java: resp.statusCode()
来源：http://dali.daxiang520.top/Article/details/gt2kkwxyzrd.html

Go:   resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gt2oryclmqd.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gt2ejkxcdjy.html

C#:   (int)resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gt2ijoooioe.html

[L08] 并发请求多个地址
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dsiuapig.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sysykeji.top/Article/details/gt2ojgqlfkb.html

PHP:  curl_multi_init() 系列
来源：http://dali.yvedp.cn/Article/details/gt2mpahpjbx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gt2zznhyzmv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gt2ywrejzto.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuanzhike.top/Article/details/gt2topekiww.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2htbxknhl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cashguo.top/Article/details/gt2gswzlpgb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gt2acezadhy.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2srweyuvg.html

M. 命令行 / 进程 / 环境
来源：http://dali.quarkkingdee.top/Article/details/gt2fiflqjtr.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2fbvudxvu.html

[M01] 读取命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2zqzwmypq.html

Py:   sys.argv[1:]
来源：http://dali.xylfe.cn/Article/details/gt2ksrqnqgc.html

PHP:  $argv;  $argc;
来源：http://dali.vqdsnc.cn/Article/details/gt2afopjmio.html

JS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gt2ysevvhaq.html

TS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gt2slhdpqqs.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gt2eknvxukw.html

Go:   os.Args[1:]
来源：http://dali.316326.xyz/Article/details/gt2kpzrnxbo.html

Ruby: ARGV
来源：http://dali.nanxuanxn.top/Article/details/gt2mpgianpb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gt2posdpsyw.html

[M02] 读取环境变量
来源：http://dali.wangdashe.top/Article/details/gt2vgfcjdes.html

Py:   os.environ.get("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2ktqievdk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gt2fpkhasev.html

JS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gt2srmlfeza.html

TS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gt2eztbacgj.html

Java: System.getenv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gt2vpujxxxz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gt2bkytxvcu.html

Ruby: ENV["HOME"]
来源：http://dali.bjfxy.top/Article/details/gt2ngnmjths.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lbnxkazf.html

[M03] 执行外部命令
来源：http://dali.kuanghao11.cn/Article/details/gt2vgbxuhhm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gzhubu.top/Article/details/gt2ikjbywqk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2indrqmch.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gt2osfojqhq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gt2lepmeixw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dianchejie.cn/Article/details/gt2skzvvjvz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenjidiqi.icu/Article/details/gt2pasjwidl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guowangkeji.top/Article/details/gt2dqrtdqoz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daria6918.cn/Article/details/gt2upxteios.html

[M04] 获取当前工作目录
来源：http://dali.yj20258.top/Article/details/gt2bsvhcfol.html

Py:   os.getcwd()
来源：http://dali.jianghu66.top/Article/details/gt2zyxzhwoc.html

PHP:  getcwd();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2umreqafx.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxlxxfi.html

TS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gt2xeetsnwc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zycfv.cn/Article/details/gt2lvnfrrni.html

Go:   os.Getwd()
来源：http://dali.yj20258.top/Article/details/gt2kwqsysee.html

Ruby: Dir.pwd
来源：http://dali.shuidangran.top/Article/details/gt2maygstoa.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.haohaochexian.top/Article/details/gt2yqwprzhv.html

[M05] 设置退出码
来源：http://dali.guowangkeji.top/Article/details/gt2hnhsmguw.html

Py:   sys.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2vauwhktr.html

PHP:  exit(1);
来源：http://dali.snrcjt.cn/Article/details/gt2gvmfnoiz.html

JS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2caouxheh.html

TS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2tuvdzmrj.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2smzkzkjg.html

Go:   os.Exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zjlqmbah.html

Ruby: exit 1
来源：http://dali.tianlin.xyz/Article/details/gt2kqtyajlr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnxiangtu.top/Article/details/gt2ajhrybhh.html

[M06] 向标准错误输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rcehqgkc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cxpcedpi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gaohongyu789.top/Article/details/gt2mvsybuvz.html

JS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqzmclpr.html

TS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gt2moqefyah.html

Java: System.err.println("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zrhvtlol.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vczomzak.html

Ruby: warn "err"
来源：http://dali.jyoumei.cn/Article/details/gt2rjwphuyl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aizwys.cn/Article/details/gt2ztpogsks.html

[M07] 判断是否为主入口
来源：http://dali.cqqwz.cn/Article/details/gt2alnfmusk.html

Py:   if __name__ == "__main__":
来源：http://dali.snrcjt.cn/Article/details/gt2fwssusfk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pengpengdd.cyou/Article/details/gt2hdoqozlm.html

JS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gt2xgwxqxsb.html

TS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wbuzcqgu.html


<!-- 参考信息 -->