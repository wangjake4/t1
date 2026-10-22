代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.bjfxy.top/Article/details/gt2ryjhckuz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aibaodan.cn/Article/details/gt2jchtmtua.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pycfn.com/Article/details/gt2wqruqheb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2bufwqewq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.redwolf501.top/Article/details/gt2mdpyclwe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hysaishi.cn/Article/details/gt2fojejvcp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.quarkkingdee.top/Article/details/gt2eugrrmsy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ivvv.top/Article/details/gt2xihithgs.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2xoxwtjgy.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2wbobaagk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2jpwginci.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigufen.top/Article/details/gt2rjvduwnx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gt2yqwltkkf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gt2douoijle.html

JS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2rueayyvc.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gt2zzzqdjtr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qzmfgkyu.html

Go:   json.Marshal(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lxavllna.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jianghu66.top/Article/details/gt2cdjbqzyq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2cbyadkme.html

[K02] JSON 字符串转对象
来源：http://dali.andypj.xyz/Article/details/gt2vlrgnvvo.html

Py:   json.loads(s)
来源：http://dali.meibo888.top/Article/details/gt2dixkpiab.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangdashe.top/Article/details/gt2cjxmdple.html

JS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gt2hjykrdlp.html

TS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gt2zsqsuerp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gt2etwybrbc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gt2iuirjilj.html

Ruby: JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2zjciylsx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ehwqpu.com/Article/details/gt2jdnvcyvn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daxiang520.top/Article/details/gt2prjinzsf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gt2dysahmsq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gt2vkoercta.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gpxfvpbk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gt2gciyoxut.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zrccgogw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shzxlz.cn/Article/details/gt2wndvrudd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2rgyqxnxk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guowangkeji.top/Article/details/gt2nmbkyodf.html

[K04] 读取 JSON 文件
来源：http://dali.sufxvd.cn/Article/details/gt2tjuibpei.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.snrcjt.cn/Article/details/gt2mkndnxbe.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yongpay.top/Article/details/gt2ibzyydqc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2bmebplkn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gt2fvqetyzy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvwtxacr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gt2auzohspy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gt2ecneqgtg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gt2pmkvokmj.html

[K05] 深拷贝对象
来源：http://dali.yongpay.top/Article/details/gt2fhzjdtmz.html

Py:   copy.deepcopy(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2odpwtwwk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuanzhike.top/Article/details/gt2ijqhrnzr.html

JS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2dpnzpqiq.html

TS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gt2ubbhmsre.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgfzy.top/Article/details/gt2fdczvtoe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shangyingyoupin.top/Article/details/gt2gpmglspy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nwbrower.top/Article/details/gt2cejhmtee.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gt2sirllpor.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2opyzfxwi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xziqi.cn/Article/details/gt2rocdxefi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eprvmrtt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gt2lmbaampw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dianchejie.cn/Article/details/gt2jlgbbpdw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daxiang520.top/Article/details/gt2rvqhblbr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gt2wikzugrf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gt2uolrijnm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gt2cyvgjhhh.html

[K07] 进制转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2usqayyau.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2bcsyhtrp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ppjwa.cn/Article/details/gt2ifknhiuq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2hnxbhgjx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2gwcjtzeq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2vtrhazur.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.andypj.xyz/Article/details/gt2lsagigxn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xinyue.icu/Article/details/gt2fnevdtpd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2kncsnonh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nwbrower.top/Article/details/gt2qjyfeysb.html

Py:   pickle.dumps(obj)
来源：http://dali.zycfv.cn/Article/details/gt2ihckxzjv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ycgmrxbn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenlongwang.top/Article/details/gt2kozwubzj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gt2klgwnjpa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gt2jgovkiin.html

Go:   encoding/gob
来源：http://dali.cqqwz.cn/Article/details/gt2ydpooejs.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbsgrfc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj20258.top/Article/details/gt2ftgwofye.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2gkfvrbnh.html

L. 网络请求
来源：http://dali.jinqigfzy.top/Article/details/gt2iammxrun.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2ylhjyeaj.html

[L01] 发送 GET 请求
来源：http://dali.xylfe.cn/Article/details/gt2tfzzagbf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hysaishi.cn/Article/details/gt2uyjedpnv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yongpay.top/Article/details/gt2jalymckd.html

JS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gt2cuzggdgp.html

TS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2viwgmssm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258.top/Article/details/gt2uifnzsny.html

Go:   resp, err := http.Get(url)
来源：http://dali.fzhhl.top/Article/details/gt2mdedsxuf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dashuyun.cn/Article/details/gt2gnbrpezp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj20258888.top/Article/details/gt2yrorveez.html

[L02] 发送 POST JSON
来源：http://dali.cheryme.top/Article/details/gt2mcvoxrgs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gt2wcpjvxad.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.redwolf501.top/Article/details/gt2mzgjhibd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bzxxawur.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gt2hkhtchhy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gt2nnsrbyvm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hongshengwenyu.top/Article/details/gt2gattisnr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gt2fbmypgwh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.redwolf501.top/Article/details/gt2ctmzxyea.html

[L03] 设置自定义请求头
来源：http://dali.hnqzz.top/Article/details/gt2goocrrgx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jiagoushi.top/Article/details/gt2vlxaluuw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.316326.xyz/Article/details/gt2gfwdwjmz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xywnfhla.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gt2zjhbvetp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.andypj.xyz/Article/details/gt2pehfzmsd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vtsjihse.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dashuyun.cn/Article/details/gt2xioyyvgx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gt2ffbbobyc.html

[L04] 设置超时
来源：http://dali.xziqi.cn/Article/details/gt2lvoihiag.html

Py:   requests.get(url, timeout=5)
来源：http://dali.snrcjt.cn/Article/details/gt2syxcvtoo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigufen.top/Article/details/gt2zdbyzuxy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gotoacloud.top/Article/details/gt2ukhwotjg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gt2odkhvcni.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ixfhdjzk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2awjjrteg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuxming.cn/Article/details/gt2xgxxggoe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aizwys.cn/Article/details/gt2ugzohtle.html

[L05] 上传文件（multipart）
来源：http://dali.kuanghao11.cn/Article/details/gt2owvjslgh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangshuangyany.cn/Article/details/gt2mwysiaop.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fzhhl.top/Article/details/gt2mepbrrne.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gt2taucgjrp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gt2cztkbntl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zdqjudy.top/Article/details/gt2xdyxyjfo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oopxdwhg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gt2rroxdmwe.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2ydeckrdn.html

[L06] 解析响应为 JSON
来源：http://dali.yj202588.top/Article/details/gt2dekahjmn.html

Py:   resp.json()
来源：http://dali.yangfankeji.com/Article/details/gt2statxveu.html

PHP:  json_decode($body, true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2zxgwkebz.html

JS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2aqfidaan.html

TS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2xjuotqbj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gt2qvbofdji.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gotoacloud.top/Article/details/gt2evdgzyao.html

Ruby: JSON.parse(resp.body)
来源：http://dali.316326.xyz/Article/details/gt2tiqtltcp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jianghu66.top/Article/details/gt2muxyhoji.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gt2bjnnzisi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hammf.cn/Article/details/gt2mflocxcm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.redwolf501.top/Article/details/gt2fcbixhtl.html

JS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gt2ncfhdhjb.html

TS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gt2eoodqufy.html

Java: resp.statusCode()
来源：http://dali.0kj1m.cn/Article/details/gt2efzkylkk.html

Go:   resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gt2kjyqwone.html

Ruby: resp.code.to_i
来源：http://dali.zycfv.cn/Article/details/gt2qklffray.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gt2nseybypg.html

[L08] 并发请求多个地址
来源：http://dali.meibo888.top/Article/details/gt2xovvovbw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yanxiufei.cn/Article/details/gt2zvytiane.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuanzhike.top/Article/details/gt2bcedxgyd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gt2qrygsyjo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gt2fqhwrljf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gt2kqvcyzrq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.vqdsnc.cn/Article/details/gt2arwesulu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pixytawk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sysykeji.top/Article/details/gt2isyzwmye.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2clxymszu.html

M. 命令行 / 进程 / 环境
来源：http://dali.sweek.top/Article/details/gt2hkvurodr.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2kiahswim.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jtpnxiyb.html

Py:   sys.argv[1:]
来源：http://dali.cashguo.top/Article/details/gt2ghkzpdip.html

PHP:  $argv;  $argc;
来源：http://dali.tian-w.cn/Article/details/gt2kymvmhbt.html

JS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kilrwzom.html

TS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gt2uryxwgww.html

Java: args 数组（main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gt2mvdiyskw.html

Go:   os.Args[1:]
来源：http://dali.jyoumei.cn/Article/details/gt2anwvsvmn.html

Ruby: ARGV
来源：http://dali.nanxuanxn.top/Article/details/gt2ahnopmmp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gt2vvnmobzd.html

[M02] 读取环境变量
来源：http://dali.hammf.cn/Article/details/gt2uixhgkrr.html

Py:   os.environ.get("HOME")
来源：http://dali.daria6918.cn/Article/details/gt2fgaiuqth.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gt2chkruuab.html

JS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gt2rmwdrwcv.html

TS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gt2izbemlnj.html

Java: System.getenv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gt2sgohmrav.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2qhwgdkkr.html

Ruby: ENV["HOME"]
来源：http://dali.cdnleiting.top/Article/details/gt2kmeibdfi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gt2kwcegrli.html

[M03] 执行外部命令
来源：http://dali.hnqzz.top/Article/details/gt2fyigntee.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nugwpumu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aizwys.cn/Article/details/gt2agmjcdor.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrevuphq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gt2kwuzmtju.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnqzz.top/Article/details/gt2paryauao.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gawencyo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hysaishi.cn/Article/details/gt2ropxzcvm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxuanxn.top/Article/details/gt2tmkwpqbb.html

[M04] 获取当前工作目录
来源：http://dali.tianlin.xyz/Article/details/gt2ujtxqunh.html

Py:   os.getcwd()
来源：http://dali.nwbrower.top/Article/details/gt2ftonknyz.html

PHP:  getcwd();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izjlirdh.html

JS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2uyrecaqd.html

TS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gt2dsyuvrka.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guowangkeji.top/Article/details/gt2gltbefoj.html

Go:   os.Getwd()
来源：http://dali.sweek.top/Article/details/gt2huyxnegf.html

Ruby: Dir.pwd
来源：http://dali.zhongyouzk.top/Article/details/gt2edyrdhfv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgufenzy.top/Article/details/gt2fseyaoja.html

[M05] 设置退出码
来源：http://dali.hfpthk.cn/Article/details/gt2nkigtfyl.html

Py:   sys.exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2jaiyzrgq.html

PHP:  exit(1);
来源：http://dali.jinqigfzy.top/Article/details/gt2lrxcenvp.html

JS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bejmkfjk.html

TS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vbdjwqjb.html

Java: System.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2xzxomqbf.html

Go:   os.Exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2snrxdutr.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gt2dvnyhfjp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgufenzy.top/Article/details/gt2vctoyllo.html

[M06] 向标准错误输出
来源：http://dali.iojbl.cn/Article/details/gt2obgionyt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shuidangran.top/Article/details/gt2txrmgwoz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shuidangran.top/Article/details/gt2cpfyawsr.html

JS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gt2zrwytpqi.html

TS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gt2yyxkbdbp.html

Java: System.err.println("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2lpbnytby.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.iojbl.cn/Article/details/gt2kqtbmdkn.html

Ruby: warn "err"
来源：http://dali.xinyue.icu/Article/details/gt2jmrebzug.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yanxiufei.cn/Article/details/gt2bfqiamcy.html

[M07] 判断是否为主入口
来源：http://dali.gzhubu.top/Article/details/gt2hndvektx.html

Py:   if __name__ == "__main__":
来源：http://dali.ppjwa.cn/Article/details/gt2xqdfeuog.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jiagoushi.top/Article/details/gt2laowavby.html

JS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gt2yadppyjc.html

TS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gt2uljzqtrg.html

Java: public static void main(String[] args)
来源：http://dali.gzhubu.top/Article/details/gt2cjwabcng.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gt2ubvgbrcj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daxiang520.top/Article/details/gt2uvowfifl.html

C#:   static void Main(string[] args)
来源：http://dali.sxryk.cn/Article/details/gt2oqiwquvb.html

[M08] 获取系统与运行时信息
来源：http://dali.yanxiufei.cn/Article/details/gt2slvmgxik.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnqzz.top/Article/details/gt2uukisghk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhiwuduotai.top/Article/details/gt2ptcgyfut.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gt2anobotxi.html

TS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gt2goafymwb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tanke756.top/Article/details/gt2qnbmxblt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bajuclaw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.redwolf501.top/Article/details/gt2pwwgomki.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yonumen.top/Article/details/gt2akmkglat.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2lzkzokic.html

N. 数据结构与算法
来源：http://dali.yj202588.top/Article/details/gt2lalfrbdj.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2bsbiatgc.html

[N01] 二分查找（有序数组）
来源：http://dali.yonumen.top/Article/details/gt2rwuhdrzl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2pionfeow.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.meibo888.top/Article/details/gt2mwltxcui.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gt2smdrweuf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gt2mxlbdlzi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2xqurbecd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2xjoaxsaz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zdqjudy.top/Article/details/gt2epjorqnu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gt2nhjrxhma.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xylfe.cn/Article/details/gt2zetnyqgu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gt2irgfdpya.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxuanxn.top/Article/details/gt2xbbjuqim.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gt2hpdexdnh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gt2fkxdemfj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.smart0.xyz/Article/details/gt2qjfjxqae.html

Go:   slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gt2qubldoyi.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gt2tjoflavc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shuidangran.top/Article/details/gt2wcihpdys.html

[N03] 快速排序（分治示例）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qxtbsmsp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2prwipfia.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ybcxt.top/Article/details/gt2hrpondtv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gt2zsrkyiew.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gt2qnuhbupa.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenzaomai.com/Article/details/gt2eyzpcahk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnqzz.top/Article/details/gt2sumsnywp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zycfv.cn/Article/details/gt2qazeewnl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yonumen.top/Article/details/gt2gcleikpm.html

[N04] 斐波那契数列
来源：http://dali.sufxvd.cn/Article/details/gt2vcicdljo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tptgzkfg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.andypj.xyz/Article/details/gt2zrifbxtf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2voybbzzy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gt2hffxbbev.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gt2dzehbxzi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2shgrxvdp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gt2vstwftgc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tiagaxbo.html

[N05] 最大公约数
来源：http://dali.daria6918.cn/Article/details/gt2zuwbsvyy.html

Py:   math.gcd(a, b)
来源：http://dali.zhengqikj.top/Article/details/gt2dakvauqa.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dqgaqdsl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gt2btlopzet.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gt2hztlltnt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tianlin.xyz/Article/details/gt2tmtrccyf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenzaomai.com/Article/details/gt2kqwdihfm.html

Ruby: a.gcd(b)
来源：http://dali.redwolf501.top/Article/details/gt2kncteasy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgxioynj.html

[N06] 判断回文字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lfnirsxg.html

Py:   s == s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2ozsgjynv.html

PHP:  $s === strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gt2jlsvlmfr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gt2zlidfugu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gt2qpnbugif.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guowangkeji.top/Article/details/gt2uqzbetxe.html

Go:   // 双指针从两端比较
来源：http://dali.xziqi.cn/Article/details/gt2voqfaguk.html

Ruby: s == s.reverse
来源：http://dali.yj20258.top/Article/details/gt2qjkgnkjc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gt2khrqkfje.html

[N07] 两数之和（返回下标）
来源：http://dali.hfpthk.cn/Article/details/gt2hlaadpls.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxujwzij.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oqenfewv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sweek.top/Article/details/gt2zoqbojba.html

TS:   // 手写 Map<string, number>
来源：http://dali.pengpengdd.cyou/Article/details/gt2haabfcol.html

Java: // 手写 HashMap
来源：http://dali.ivvv.top/Article/details/gt2ziazwzep.html

Go:   // 手写 map[int]int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2npylkqxt.html

Ruby: // 手写 Hash
来源：http://dali.yanxiufei.cn/Article/details/gt2vgvrwueb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhengqikj.top/Article/details/gt2lcuaxvpb.html

[N08] 生成全排列
来源：http://dali.haohaochexian.top/Article/details/gt2ermkobeh.html


<!-- 参考信息 -->