代发 wailian999

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cheryme.top/Article/details/gthpihffid.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daria6918.cn/Article/details/gtiwfcyolf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pengpengdd.cyou/Article/details/gtlwfwcurh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sufxvd.cn/Article/details/gtaswyywuo.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtvbvfkfav.html

K. JSON 与序列化
来源：http://dali.cashguo.top/Article/details/gthcgvacbo.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtojsgyfqw.html

[K01] 对象转 JSON 字符串
来源：http://dali.hammf.cn/Article/details/gtgriebhbu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gtutkmtpdz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefyfueet.html

JS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gtanprbiey.html

TS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gtoajfvevu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenzaomai.com/Article/details/gtaidpocxq.html

Go:   json.Marshal(obj)
来源：http://dali.shzxlz.cn/Article/details/gtbdyutvol.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yonumen.top/Article/details/gtztfdivxh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxahoqtza.html

[K02] JSON 字符串转对象
来源：http://dali.xinyue.icu/Article/details/gtiqyusrkv.html

Py:   json.loads(s)
来源：http://dali.svipenyu.cn/Article/details/gtlzswgvya.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tianlin.xyz/Article/details/gtsvvedsft.html

JS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gtcbflsaxh.html

TS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtnzuixvec.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aizwys.cn/Article/details/gtpnuxmcik.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gtzrfcqmch.html

Ruby: JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gtvxuvaekw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.0kj1m.cn/Article/details/gtdkzqkayd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zycfv.cn/Article/details/gtordsbbiy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtktqvyqlp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gttitvrcdi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gtpbqukazl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtlfwiheav.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sysykeji.top/Article/details/gtjbfdkcqs.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zycfv.cn/Article/details/gtwcfsqkub.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtffzwrsum.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ppjwa.cn/Article/details/gtxygmhfxb.html

[K04] 读取 JSON 文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzveabgml.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hammf.cn/Article/details/gtvogumdma.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtypxkixwu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gteqgmafop.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gtpwqckcbk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtjpbzkizb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtlqwfdaqm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gtnmhauhyn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxghpcjqh.html

[K05] 深拷贝对象
来源：http://dali.shangyingyoupin.top/Article/details/gtsvybblqf.html

Py:   copy.deepcopy(obj)
来源：http://dali.c1oappe.top/Article/details/gtdyazefuy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhaomingkeji.xyz/Article/details/gthlhszutj.html

JS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gtetxwyjey.html

TS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtuflkbqst.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhoulong.xyz/Article/details/gtymkknpea.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigfzy.top/Article/details/gtljptwzns.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gzhubu.top/Article/details/gtoohjywvd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsdwtygg.html

[K06] 解析 URL 查询串
来源：http://dali.yvedp.cn/Article/details/gtyuxkyntf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.bjfxy.top/Article/details/gttusqwbui.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.0kj1m.cn/Article/details/gtkswhbytk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gtacmyoitv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gtjhvbhbwb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fengsongda.top/Article/details/gtdfvfrcdw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqjxrhug.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtnjhlxwcx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gttcnlvaad.html

[K07] 进制转换
来源：http://dali.yvedp.cn/Article/details/gtqipzivmd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtpmoagcgt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtquumhlwf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtanateseg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtkjlzxntl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtepladcbj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gotoacloud.top/Article/details/gtrsjwffdk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yueranfly.top/Article/details/gtvewfldyn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtleipnptw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ehwqpu.com/Article/details/gttjnrlcnm.html

Py:   pickle.dumps(obj)
来源：http://dali.meibo888.top/Article/details/gtpxujbxbt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtwzsvirzl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gtgxijhdtz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gtogigwbuw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sweek.top/Article/details/gtyqcatocf.html

Go:   encoding/gob
来源：http://dali.vqdsnc.cn/Article/details/gtoheguyux.html

Ruby: Marshal.dump(obj)
来源：http://dali.bjfxy.top/Article/details/gtofluwlqb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gtymfpppvl.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtxaihsgps.html

L. 网络请求
来源：http://dali.kuanghao11.cn/Article/details/gtoavbwsqo.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtgiuqkxcu.html

[L01] 发送 GET 请求
来源：http://dali.jinqigfzy.top/Article/details/gttljcnmog.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.quarkkingdee.top/Article/details/gtzmulsypz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ppjwa.cn/Article/details/gtdkyycsbo.html

JS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtfjchwzxa.html

TS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gtdycuwbgw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sysykeji.top/Article/details/gtqqhjznkv.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigfzy.top/Article/details/gttofdmmxl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nwbrower.top/Article/details/gtfaexakah.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflndsgto.html

[L02] 发送 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtaofviwwj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtpyufxxkf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.redwolf501.top/Article/details/gtlyxkapnt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daria6918.cn/Article/details/gtpatkhsiu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gtjifhwlln.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yongpay.top/Article/details/gtdpbvxjst.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.quarkkingdee.top/Article/details/gttfxqjwxx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgfzy.top/Article/details/gtoibcbyzt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.smart0.xyz/Article/details/gtnkniauxv.html

[L03] 设置自定义请求头
来源：http://dali.hysaishi.cn/Article/details/gtdsjkfvnr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guowangkeji.top/Article/details/gtgybdncwx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpwqjltt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gtivknqslu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gtuhlqidst.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnmpchzd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gttzhuqpcw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqktjcje.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gtbuyvyfkq.html

[L04] 设置超时
来源：http://dali.pycfn.com/Article/details/gtrlvhrjtt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jianghu66.top/Article/details/gtjtifkfkj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tian-w.cn/Article/details/gtvssjceam.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gtvguphprj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gtjfcsoocr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhoulong.xyz/Article/details/gtugrbudyj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yangfankeji.com/Article/details/gttgchmnnc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yanxiufei.cn/Article/details/gtsptekabg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.mhx1999.top/Article/details/gtzntkqfwk.html

[L05] 上传文件（multipart）
来源：http://dali.tanke756.top/Article/details/gtzpmxmewt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgfzy.top/Article/details/gtmzwyhpkx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.birdmap.top/Article/details/gtgmaeyerj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gtfnjnagnj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gtptffsurr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.quarkkingdee.top/Article/details/gtvlbuxxso.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sweek.top/Article/details/gtttnpjefc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guannengcc.top/Article/details/gtaerrriwx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tanke756.top/Article/details/gtmkbztwth.html

[L06] 解析响应为 JSON
来源：http://dali.dashuyun.cn/Article/details/gtnwqeemlk.html

Py:   resp.json()
来源：http://dali.316326.xyz/Article/details/gtgdjkdxct.html

PHP:  json_decode($body, true);
来源：http://dali.ehwqpu.com/Article/details/gthddayqqq.html

JS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gthvjzzhsx.html

TS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gtnzepzhjm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtlznwixef.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ivvv.top/Article/details/gtjerifusr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.redwolf501.top/Article/details/gtnlquhyyw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xziqi.cn/Article/details/gtpnyteuqd.html

[L07] 处理 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtjagsfebp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shzxlz.cn/Article/details/gtlbnzbmsk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.mhx1999.top/Article/details/gtcvxzgelh.html

JS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gtvyrncegx.html

TS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtpdsexqqi.html

Java: resp.statusCode()
来源：http://dali.smart0.xyz/Article/details/gtardbmdrm.html

Go:   resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gtknmatdvu.html

Ruby: resp.code.to_i
来源：http://dali.jianghu66.top/Article/details/gtzelpyapp.html

C#:   (int)resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gttiynxvlq.html

[L08] 并发请求多个地址
来源：http://dali.yongpay.top/Article/details/gttjuusfrf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhiwuduotai.top/Article/details/gtvrrylmtr.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinghuilouyu.cn/Article/details/gtiaiatcfz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gtpcczueyw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtrbvtwwmd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ydzc1.top/Article/details/gtsekirztt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dianchejie.cn/Article/details/gtxtqyxywr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yvedp.cn/Article/details/gteciubgoa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gtzbzwbdvd.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtksalylqz.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangdashe.top/Article/details/gtjfzgtjrj.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gthdnhgeeg.html

[M01] 读取命令行参数
来源：http://dali.xziqi.cn/Article/details/gtqgyitaib.html

Py:   sys.argv[1:]
来源：http://dali.sxryk.cn/Article/details/gtvlptzhzo.html

PHP:  $argv;  $argc;
来源：http://dali.svipenyu.cn/Article/details/gttcsjwjpe.html

JS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gtgyxkpvel.html

TS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gtqiirodge.html

Java: args 数组（main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gtupkkenwk.html

Go:   os.Args[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtyraqzisd.html

Ruby: ARGV
来源：http://dali.aibaodan.cn/Article/details/gtvxmglnmw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gtjqmyztjb.html

[M02] 读取环境变量
来源：http://dali.chenzaomai.com/Article/details/gtgykvmvkg.html

Py:   os.environ.get("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtlidfqylw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gtstfsxodb.html

JS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gtsakghnbu.html

TS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gtjwvzppjb.html

Java: System.getenv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtrlzbdget.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daria6918.cn/Article/details/gtqqjuufph.html

Ruby: ENV["HOME"]
来源：http://dali.hnqzz.top/Article/details/gtiagqzuyk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsqowrth.html

[M03] 执行外部命令
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxaxuptu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hammf.cn/Article/details/gtsnlfvkyt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhiwuduotai.top/Article/details/gtyotgdflb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gtxcorhwqs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqnczjju.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.kuanghao11.cn/Article/details/gtgrmcqnlw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aibaodan.cn/Article/details/gtdfrxlufy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.smart0.xyz/Article/details/gtetmlwnwr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hysaishi.cn/Article/details/gtyyufazuh.html

[M04] 获取当前工作目录
来源：http://dali.nwbrower.top/Article/details/gtxhempnlo.html

Py:   os.getcwd()
来源：http://dali.cdnleiting.top/Article/details/gtwoebuhiq.html

PHP:  getcwd();
来源：http://dali.yj20258.top/Article/details/gtaeosfeeb.html

JS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gtreibvcyc.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtrmhcyvpq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yueranfly.top/Article/details/gtibnjkjsv.html

Go:   os.Getwd()
来源：http://dali.cdnleiting.top/Article/details/gtijtjbvxs.html

Ruby: Dir.pwd
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkkpfiwi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.guannengcc.top/Article/details/gtwwepmjtx.html

[M05] 设置退出码
来源：http://dali.jinqigufen.top/Article/details/gtikxckbow.html

Py:   sys.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtkdrswnjf.html

PHP:  exit(1);
来源：http://dali.jinqigfzy.top/Article/details/gtipsnalon.html

JS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gtwnjlnjey.html

TS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtsyxojwdv.html

Java: System.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtxhcqqxjk.html

Go:   os.Exit(1)
来源：http://dali.redwolf501.top/Article/details/gtlnvismam.html

Ruby: exit 1
来源：http://dali.jlsjyb.cn/Article/details/gttyjptoxy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258888.top/Article/details/gthaxwgpgx.html

[M06] 向标准错误输出
来源：http://dali.xziqi.cn/Article/details/gtipueenmq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gtjgtlfprf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuetiantiany.cn/Article/details/gthhskfbmw.html

JS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gtabvmhbsg.html

TS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gthmdzpiso.html

Java: System.err.println("err")
来源：http://dali.cheryme.top/Article/details/gttkugcdeo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gotoacloud.top/Article/details/gtquhaqukq.html

Ruby: warn "err"
来源：http://dali.jqgfzy.top/Article/details/gtnzxpvwvt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ppjwa.cn/Article/details/gtkltolpxm.html

[M07] 判断是否为主入口
来源：http://dali.andypj.xyz/Article/details/gtxdtuhdgo.html

Py:   if __name__ == "__main__":
来源：http://dali.hammf.cn/Article/details/gtzreucfqm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.meibo888.top/Article/details/gtwhatnnmo.html

JS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gtgzszuhfr.html

TS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtzbljbrhs.html

Java: public static void main(String[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavxfqnzd.html

Go:   func main()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthunbdyoh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnqzz.top/Article/details/gtfnjfttpq.html

C#:   static void Main(string[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtklbvuroe.html

[M08] 获取系统与运行时信息
来源：http://dali.gzhubu.top/Article/details/gtllmueajp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cucudq.cn/Article/details/gtmbheodin.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zycfv.cn/Article/details/gthxdqboan.html

JS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gtvwfdxxse.html

TS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gtjqqvzfcp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gogol.net.cn/Article/details/gttevwxwku.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfaubeqwc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocwtdbxr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hammf.cn/Article/details/gtirkjifdv.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtvccbrhia.html

N. 数据结构与算法
来源：http://dali.xuanzx.com/Article/details/gtqdxvjreh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtosvzstis.html

[N01] 二分查找（有序数组）
来源：http://dali.svipenyu.cn/Article/details/gtqecnevyu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtlnywflnj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fengsongda.top/Article/details/gtbhfbcevc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gtevgezhoe.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gtjzhepzvz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtpnezzdww.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtccblepbu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.smart0.xyz/Article/details/gtsmhxqhru.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gteczmqvyh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.andypj.xyz/Article/details/gtwybgwunu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtktuszlpo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxhlzpgf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtlmxgeetg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtudscxcvf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.bjfxy.top/Article/details/gteexioxpf.html

Go:   slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gthqespccq.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gtsfzoxbxd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hnxiangtu.top/Article/details/gtzedopnrj.html

[N03] 快速排序（分治示例）
来源：http://dali.gotoacloud.top/Article/details/gtiiumajwu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xylfe.cn/Article/details/gtswvlnzmc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yangfankeji.com/Article/details/gtsditvfby.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gtzuccawsw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gtzbkccnci.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhoulong.xyz/Article/details/gtlobbtrpc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jlsjyb.cn/Article/details/gtacrtlnbd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yanxiufei.cn/Article/details/gteglyusxg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tianlin.xyz/Article/details/gtoqaoqdfh.html

[N04] 斐波那契数列
来源：http://dali.birdmap.top/Article/details/gtdsvvhavv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gtyrfccjko.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gtjlvjkmcd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtrffvwbab.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtpxnwlhox.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gtgyxybgkb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ybcxt.top/Article/details/gtplralyzp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gtcpomdcvg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gtosmdqhin.html

[N05] 最大公约数
来源：http://dali.sweek.top/Article/details/gtcithhymh.html

Py:   math.gcd(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtczhycayi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgfzy.top/Article/details/gtcvtohcvz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gttwtrjgtk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gtbqaaelqu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yvedp.cn/Article/details/gtckgaznjg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shangyingyoupin.top/Article/details/gtzcwfkyzz.html

Ruby: a.gcd(b)
来源：http://dali.jqgufenzy.top/Article/details/gttvfojxft.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangdashe.top/Article/details/gthecoepnu.html

[N06] 判断回文字符串
来源：http://dali.cucudq.cn/Article/details/gtyxbpinyy.html

Py:   s == s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gtdeuossap.html

PHP:  $s === strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gtgdxiqzln.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqihkyhbn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtezpmvkwp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.daria6918.cn/Article/details/gtzhlmbjof.html

Go:   // 双指针从两端比较
来源：http://dali.vqdsnc.cn/Article/details/gtynpjbqsa.html

Ruby: s == s.reverse
来源：http://dali.tianlin.xyz/Article/details/gtwonvdzbt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ivvv.top/Article/details/gtiopneead.html

[N07] 两数之和（返回下标）
来源：http://dali.hywenlv.cn/Article/details/gtnemkawvp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ehwqpu.com/Article/details/gtavlgvyjb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sufxvd.cn/Article/details/gtzxwbnsgx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sysykeji.top/Article/details/gthdsjsvzx.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258888.top/Article/details/gtymgdpsrw.html

Java: // 手写 HashMap
来源：http://dali.cqqwz.cn/Article/details/gtyjmptnsd.html

Go:   // 手写 map[int]int
来源：http://dali.gzhubu.top/Article/details/gtbbrxcvpp.html

Ruby: // 手写 Hash
来源：http://dali.zycfv.cn/Article/details/gtovsbigwh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.c1oappe.top/Article/details/gtlzwsbqdj.html

[N08] 生成全排列
来源：http://dali.pycfn.com/Article/details/gtjxoifvfb.html

Py:   itertools.permutations(arr)
来源：http://dali.ydzc1.top/Article/details/gtrbutelub.html

PHP:  // 手写递归交换
来源：http://dali.c1oappe.top/Article/details/gthvgieghl.html

JS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtiabryvmz.html

TS:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtxqlehfwd.html


<!-- 参考信息 -->