代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daria6918.cn/Article/details/gt2ylrrhbxm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gt2dczspnco.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gt2mpwxuuon.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuanzx.com/Article/details/gt2paojjzot.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jianghu66.top/Article/details/gt2wotaclsy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qwvpzfsu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sysykeji.top/Article/details/gt2ovwsbwfn.html

[J10] 取今天 / 本月第一天
来源：http://dali.ppjwa.cn/Article/details/gt2szzalgwl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lptdzddo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhongyouzk.top/Article/details/gt2mvaxlqun.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cqqwz.cn/Article/details/gt2ownzelda.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2innlybyg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eiayxisp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gt2nprvasmn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuanzhike.top/Article/details/gt2ramhwnoh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hysaishi.cn/Article/details/gt2ftynidmu.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2naeyxeif.html

K. JSON 与序列化
来源：http://dali.sweek.top/Article/details/gt2jxqvpfjv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2peragdnp.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2cvmadtyg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxloaru.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gt2cqdoqxpy.html

JS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gt2ldcrdero.html

TS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2szcxsjdo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.316326.xyz/Article/details/gt2brvyroyw.html

Go:   json.Marshal(obj)
来源：http://dali.316326.xyz/Article/details/gt2eywecgmz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gogol.net.cn/Article/details/gt2jkmttiov.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2rpyebbqi.html

[K02] JSON 字符串转对象
来源：http://dali.dianchejie.cn/Article/details/gt2hkgztgdp.html

Py:   json.loads(s)
来源：http://dali.smart0.xyz/Article/details/gt2dhxbapcd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgufenzy.top/Article/details/gt2bbvenkiy.html

JS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwfrruzo.html

TS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gt2jgujxyoz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zdqjudy.top/Article/details/gt2iupvuqkr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gt2mvvqgiey.html

Ruby: JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gt2pcnodmdt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tian-w.cn/Article/details/gt2uzdihnin.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dianchejie.cn/Article/details/gt2erqkjpjf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gt2ktizjinp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gt2pchwasth.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gt2vmdsckhj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gt2mepwvrvz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tanke756.top/Article/details/gt2gfjmceop.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.iojbl.cn/Article/details/gt2pilpefan.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zixdpkeg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.smart0.xyz/Article/details/gt2ufyahufl.html

[K04] 读取 JSON 文件
来源：http://dali.sxryk.cn/Article/details/gt2ijkbvdii.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ehwqpu.com/Article/details/gt2oxdxdjlz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shuidangran.top/Article/details/gt2omvuwkmz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gt2wruedwbd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gt2bzorukle.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cashguo.top/Article/details/gt2icazepfp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idalbdec.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gt2lgpwefkj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gt2eyzznyop.html

[K05] 深拷贝对象
来源：http://dali.zhiwuduotai.top/Article/details/gt2yrbogzph.html

Py:   copy.deepcopy(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2cyhocayj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuetiantiany.cn/Article/details/gt2vkujiors.html

JS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gt2zzhdsyut.html

TS:   structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2pndxaojo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yongpay.top/Article/details/gt2vanfcnvv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daxiang520.top/Article/details/gt2zgjsjuew.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dashuyun.cn/Article/details/gt2yixxxvfx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yuxming.cn/Article/details/gt2btibxptx.html

[K06] 解析 URL 查询串
来源：http://dali.feifeiyinyue.top/Article/details/gt2rmignvkj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2onpxqozh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.birdmap.top/Article/details/gt2bhjecobf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gt2hbsgkcer.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gt2cfwssdjg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aibaodan.cn/Article/details/gt2brgdbqkm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gt2ehctbbaf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gt2wpxtchvx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gt2agltrekw.html

[K07] 进制转换
来源：http://dali.hfpthk.cn/Article/details/gt2mitbfbbz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2vzyqbfsc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yanxiufei.cn/Article/details/gt2jsgdzzkt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2whqdltzo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2csancuxt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2yhezqncd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhengqikj.top/Article/details/gt2cepbytpz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.smart0.xyz/Article/details/gt2jfilrgaz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2dicemgkz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yueranfly.top/Article/details/gt2nkxvmdxh.html

Py:   pickle.dumps(obj)
来源：http://dali.xinyue.icu/Article/details/gt2gondhxza.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2ghhjehcn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gt2alpiihhj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gt2tqldlszy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tianlin.xyz/Article/details/gt2hwopxdhp.html

Go:   encoding/gob
来源：http://dali.xuetiantiany.cn/Article/details/gt2oozrjsiw.html

Ruby: Marshal.dump(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2iptuyjrr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gt2ztxcmeiq.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2yespjdsr.html

L. 网络请求
来源：http://dali.gzhubu.top/Article/details/gt2gavcuhkp.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2bocbixfb.html

[L01] 发送 GET 请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhqagzww.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yueranfly.top/Article/details/gt2izaiziwd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yonumen.top/Article/details/gt2acajgskk.html

JS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gt2nyxzggao.html

TS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gt2tswqovlg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xylfe.cn/Article/details/gt2tyodlexz.html

Go:   resp, err := http.Get(url)
来源：http://dali.dianchejie.cn/Article/details/gt2napukojv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangdashe.top/Article/details/gt2vgdixnpm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhoulong.xyz/Article/details/gt2iocdnqye.html

[L02] 发送 POST JSON
来源：http://dali.cucudq.cn/Article/details/gt2quxfnolm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gt2hwviivxk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.havefunace.top/Article/details/gt2pghahuqu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2suhgashs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gt2omofwwdn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xziqi.cn/Article/details/gt2itzfvdte.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.feifeiyinyue.top/Article/details/gt2diczgqsx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gaohongyu789.top/Article/details/gt2gynzeuby.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.mhx1999.top/Article/details/gt2bdpdttgt.html

[L03] 设置自定义请求头
来源：http://dali.aizwys.cn/Article/details/gt2lccijjga.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cqqwz.cn/Article/details/gt2odilunqu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxinkj.top/Article/details/gt2lgachbxu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gt2foysyvkq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gt2tjfapdad.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj202588.top/Article/details/gt2iklvufum.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gt2ldchikoq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.0kj1m.cn/Article/details/gt2bgpwuovj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daxiang520.top/Article/details/gt2kxhpoihu.html

[L04] 设置超时
来源：http://dali.havefunace.top/Article/details/gt2upjnlgpe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gzhubu.top/Article/details/gt2auowlrcd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.9152youxi.cn/Article/details/gt2ecigkdxw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gt2mmrbksrh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fzhhl.top/Article/details/gt2ihvufbix.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fzhhl.top/Article/details/gt2utrmiqfr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.meibo888.top/Article/details/gt2narchpsl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tian-w.cn/Article/details/gt2gjjvemrg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jlsjyb.cn/Article/details/gt2utlvigaj.html

[L05] 上传文件（multipart）
来源：http://dali.svipenyu.cn/Article/details/gt2pbwtjdmz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.kuanghao11.cn/Article/details/gt2tybjsbtz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2bhlilzwk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gt2fxcclwdd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgfzy.top/Article/details/gt2eiupjkia.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhengqikj.top/Article/details/gt2psuxwlmf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guannengcc.top/Article/details/gt2jcosruug.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ydzc1.top/Article/details/gt2bschblhl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2kcgxvvhv.html

[L06] 解析响应为 JSON
来源：http://dali.zhengqikj.top/Article/details/gt2tbpjtycp.html

Py:   resp.json()
来源：http://dali.c1oappe.top/Article/details/gt2rkholsic.html

PHP:  json_decode($body, true);
来源：http://dali.gogol.net.cn/Article/details/gt2vycegmwk.html

JS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gt2hqhbxocn.html

TS:   await resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gt2vfikedpl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gt2ydbjrnfo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2dytobxwd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.andypj.xyz/Article/details/gt2wmhmiyxl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuanzhike.top/Article/details/gt2ugxgpgns.html

[L07] 处理 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gt2jjqerfjo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhongyouzk.top/Article/details/gt2mpnktbtk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.haohaochexian.top/Article/details/gt2kuscioau.html

JS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gt2xtnyroyo.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xsswujmv.html

Java: resp.statusCode()
来源：http://dali.yj202588.top/Article/details/gt2quwfzfuj.html

Go:   resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gt2pcrngecs.html

Ruby: resp.code.to_i
来源：http://dali.haohaochexian.top/Article/details/gt2zngyibdt.html

C#:   (int)resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gt2rcdmxctz.html

[L08] 并发请求多个地址
来源：http://dali.cdnleiting.top/Article/details/gt2qmuvtpwo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.meibo888.top/Article/details/gt2rwxqwoub.html

PHP:  curl_multi_init() 系列
来源：http://dali.xylfe.cn/Article/details/gt2rwtjomcn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gt2kijfzwov.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gt2yulphcvr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigfzy.top/Article/details/gt2npvbxyed.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.aibaodan.cn/Article/details/gt2srwibzbw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2plkpzgbb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bauohula.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2gyzvvzie.html

M. 命令行 / 进程 / 环境
来源：http://dali.yvedp.cn/Article/details/gt2itrcnjzc.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2iszcztdk.html

[M01] 读取命令行参数
来源：http://dali.0kj1m.cn/Article/details/gt2edglskyr.html

Py:   sys.argv[1:]
来源：http://dali.sweek.top/Article/details/gt2mwvgjtve.html

PHP:  $argv;  $argc;
来源：http://dali.fengsongda.top/Article/details/gt2ytijainv.html

JS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gt2xtnmmwee.html

TS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gt2zmfeqtib.html

Java: args 数组（main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gt2faxvbxvl.html

Go:   os.Args[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xzqghxvn.html

Ruby: ARGV
来源：http://dali.haohaochexian.top/Article/details/gt2atbbrwhu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tian-w.cn/Article/details/gt2nzagttiw.html

[M02] 读取环境变量
来源：http://dali.aizwys.cn/Article/details/gt2drrsnklm.html

Py:   os.environ.get("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xfnrsnry.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gt2vfcwlajz.html

JS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gt2idqfmzpb.html

TS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gt2xiyxgbmx.html

Java: System.getenv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2tmrmznap.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gt2hlchhtiq.html

Ruby: ENV["HOME"]
来源：http://dali.zhiwuduotai.top/Article/details/gt2mpxydxpr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ydzc1.top/Article/details/gt2ohyhtkwg.html

[M03] 执行外部命令
来源：http://dali.aibaodan.cn/Article/details/gt2fdbppwrm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pycfn.com/Article/details/gt2wxlfrheq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.mhx1999.top/Article/details/gt2hpkmvmgo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uopyghmb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gt2hpsaoxwt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yanxiufei.cn/Article/details/gt2tipjkncv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jianghu66.top/Article/details/gt2ekcqugdq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sweek.top/Article/details/gt2dgbcehkr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgfzy.top/Article/details/gt2wnwbpyiu.html

[M04] 获取当前工作目录
来源：http://dali.yuxming.cn/Article/details/gt2bzmucawo.html

Py:   os.getcwd()
来源：http://dali.jinqigufen.top/Article/details/gt2aswzjgeb.html

PHP:  getcwd();
来源：http://dali.xuanzx.com/Article/details/gt2ifayxvbc.html

JS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gt2tljfxrla.html

TS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gt2saiwtszx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgufenzy.top/Article/details/gt2vxaygqhv.html

Go:   os.Getwd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2lkzvkosi.html

Ruby: Dir.pwd
来源：http://dali.redwolf501.top/Article/details/gt2njiwnvar.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cashguo.top/Article/details/gt2rsvcwvus.html

[M05] 设置退出码
来源：http://dali.chenjidiqi.icu/Article/details/gt2hchwjsmw.html

Py:   sys.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2gukyglji.html

PHP:  exit(1);
来源：http://dali.cqqwz.cn/Article/details/gt2eapobylz.html

JS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2snjsflra.html

TS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gt2kzvzgoix.html

Java: System.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2jgompuuw.html

Go:   os.Exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2abpwhmhi.html

Ruby: exit 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2gqkxwdpw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhixingplan.top/Article/details/gt2eemaohtp.html

[M06] 向标准错误输出
来源：http://dali.guowangkeji.top/Article/details/gt2duflqvpf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gt2yhvbqftu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnxiangtu.top/Article/details/gt2xebnmgls.html

JS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gt2gdmpiyia.html

TS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gt2yzvcthbr.html

Java: System.err.println("err")
来源：http://dali.sufxvd.cn/Article/details/gt2gyvwidkx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shuidangran.top/Article/details/gt2mwvpojys.html

Ruby: warn "err"
来源：http://dali.smart0.xyz/Article/details/gt2bcnvmqkh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cdnleiting.top/Article/details/gt2cgaqucys.html

[M07] 判断是否为主入口
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tyghixzc.html

Py:   if __name__ == "__main__":
来源：http://dali.guowangkeji.top/Article/details/gt2uhnitdww.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.guowangkeji.top/Article/details/gt2kckeahdt.html

JS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gt2nerlasky.html

TS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gt2yadgsiei.html

Java: public static void main(String[] args)
来源：http://dali.dashuyun.cn/Article/details/gt2vonwydxh.html

Go:   func main()
来源：http://dali.yj20258.top/Article/details/gt2icsbrqop.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ppjwa.cn/Article/details/gt2vpgiminx.html

C#:   static void Main(string[] args)
来源：http://dali.9152youxi.cn/Article/details/gt2urmyrtvj.html

[M08] 获取系统与运行时信息
来源：http://dali.redwolf501.top/Article/details/gt2sdguciny.html

Py:   platform.system();  platform.python_version()
来源：http://dali.svipenyu.cn/Article/details/gt2yealqrvz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangshuangyany.cn/Article/details/gt2qvdxqsij.html

JS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gt2loafpfcj.html

TS:   process.platform;  process.version
来源：http://dali.hongshengwenyu.top/Article/details/gt2ztgfhiqn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aozdtddf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gotoacloud.top/Article/details/gt2edhfacnw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fengsongda.top/Article/details/gt2poglckud.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daxiang520.top/Article/details/gt2ouxlwtnd.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2smeifzim.html

N. 数据结构与算法
来源：http://dali.aizwys.cn/Article/details/gt2wxmwrrcg.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2sskpjnuw.html

[N01] 二分查找（有序数组）
来源：http://dali.quarkkingdee.top/Article/details/gt2dmjlvrzr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2vyhlarpf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gt2swzilguo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gt2dywuvtld.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zychhofe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2butpexyv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2ywrrxcel.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.pycfn.com/Article/details/gt2lefqyjxq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ifxaojxl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yonumen.top/Article/details/gt2flhaejyv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iippwene.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sweek.top/Article/details/gt2eoimeakb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gt2oxlbcjkm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gt2ckiselwk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenzaomai.com/Article/details/gt2iorneniq.html

Go:   slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gt2rwbnnfvc.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gt2hrxovlae.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fengsongda.top/Article/details/gt2kyevevha.html

[N03] 快速排序（分治示例）
来源：http://dali.zhengqikj.top/Article/details/gt2rcktogtr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.birdmap.top/Article/details/gt2wvvbrorm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hywenlv.cn/Article/details/gt2taxtamco.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2jwftjenk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gt2yxgtsqsz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tjgidwni.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aizwys.cn/Article/details/gt2rnkmbgka.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fengsongda.top/Article/details/gt2bzkkrpjx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tpranxjk.html

[N04] 斐波那契数列
来源：http://dali.nanxinkj.top/Article/details/gt2ykihzrfv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gt2ywyqtqgy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gt2ksmvahju.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ktaeccrz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tspjadpe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.smart0.xyz/Article/details/gt2trthmhxe.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rerunwvx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gt2nzbungqk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gt2dbazynlb.html

[N05] 最大公约数
来源：http://dali.yangfankeji.com/Article/details/gt2phexgmvt.html

Py:   math.gcd(a, b)
来源：http://dali.gotoacloud.top/Article/details/gt2cayekkub.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gotoacloud.top/Article/details/gt2ffcnhvmt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gt2zfzizukw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cashguo.top/Article/details/gt2plwxhufn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xylfe.cn/Article/details/gt2vtcsrmbd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.andypj.xyz/Article/details/gt2ycdxbkbx.html

Ruby: a.gcd(b)
来源：http://dali.yuxming.cn/Article/details/gt2xihknofj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gotoacloud.top/Article/details/gt2iytdwrtd.html

[N06] 判断回文字符串
来源：http://dali.ydzc1.top/Article/details/gt2ebfrpavt.html

Py:   s == s[::-1]
来源：http://dali.ivvv.top/Article/details/gt2bbwysuss.html

PHP:  $s === strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gt2haisppeg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gt2ehgosyuv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gt2fguxnsyb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guowangkeji.top/Article/details/gt2bybeenve.html

Go:   // 双指针从两端比较
来源：http://dali.yuanzhike.top/Article/details/gt2jwdhhtfu.html

Ruby: s == s.reverse
来源：http://dali.hnqzz.top/Article/details/gt2zaatboci.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gt2nhovwpvj.html

[N07] 两数之和（返回下标）
来源：http://dali.jianghu66.top/Article/details/gt2xmmvjdyz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.0kj1m.cn/Article/details/gt2pbohjndw.html


<!-- 参考信息 -->