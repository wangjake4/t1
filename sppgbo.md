代发 wailian999

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2yzbsyulz.html

K. JSON 与序列化
来源：http://dali.0kj1m.cn/Article/details/gt2qrsfeudo.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2okykaaro.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhengqikj.top/Article/details/gt2fhhlqgfb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2akggmksh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258.top/Article/details/gt2qnpdzxqz.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2hsjpiqmz.html

TS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2rwhvfryf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2svhfuoon.html

Go:   json.Marshal(obj)
来源：http://dali.wangdashe.top/Article/details/gt2qwwostcf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yangfankeji.com/Article/details/gt2uauwzrbl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2prfqzbwl.html

[K02] JSON 字符串转对象
来源：http://dali.gzhubu.top/Article/details/gt2jhisyjst.html

Py:   json.loads(s)
来源：http://dali.yongpay.top/Article/details/gt2nidnulok.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sweek.top/Article/details/gt2lpvmmpdc.html

JS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gt2qfznneun.html

TS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gt2rkfkyovn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yvedp.cn/Article/details/gt2boxfrvij.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gt2ospjenwr.html

Ruby: JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gt2ikkiakfm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cucudq.cn/Article/details/gt2pbwagifq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gt2sizwyszg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gt2kzaimzfj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gt2skcyezcn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2xjrmezul.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gt2oephdabm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vonkgmtu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hywenlv.cn/Article/details/gt2famfglbi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.smart0.xyz/Article/details/gt2yxhfvgxd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258.top/Article/details/gt2shfxrwen.html

[K04] 读取 JSON 文件
来源：http://dali.andypj.xyz/Article/details/gt2bngjnovu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj202588.top/Article/details/gt2vaocobgc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhoulong.xyz/Article/details/gt2fsmljuvq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cwmyadmx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gt2ycwlceqh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ybcxt.top/Article/details/gt2lkcvetqi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gt2pxdipgho.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ybcxt.top/Article/details/gt2duthjpaz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gt2humuhfeg.html

[K05] 深拷贝对象
来源：http://dali.chenjidiqi.icu/Article/details/gt2wuvdaqxp.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xnpjnawb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yongpay.top/Article/details/gt2fgktmhxf.html

JS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gt2obuyekhs.html

TS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gt2eagwppkh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sufxvd.cn/Article/details/gt2rrkuazvb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hfpthk.cn/Article/details/gt2cxktqgku.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.bjfxy.top/Article/details/gt2pcsmsxki.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ydzc1.top/Article/details/gt2yiqlmvdn.html

[K06] 解析 URL 查询串
来源：http://dali.daria6918.cn/Article/details/gt2qarsmoio.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnqzz.top/Article/details/gt2gribagmn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.0kj1m.cn/Article/details/gt2bpfqznzi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2ikbrbabp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gt2bzraonbv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnxiangtu.top/Article/details/gt2fmenzbgs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gt2cbaisspd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gt2krjymlcd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gt2ykxiteym.html

[K07] 进制转换
来源：http://dali.hfpthk.cn/Article/details/gt2jemvoery.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gt2lpampxjb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ppjwa.cn/Article/details/gt2igapygwh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gt2goofieyw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2egksdqwj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2pqlfaljq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258888.top/Article/details/gt2hwpztedy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jihaphsb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2otwzcnxb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aizwys.cn/Article/details/gt2obaslmih.html

Py:   pickle.dumps(obj)
来源：http://dali.shuidangran.top/Article/details/gt2fwuunkqg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yongpay.top/Article/details/gt2fjyzcxxf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gt2zrzotwez.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gt2bgvegvpo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xinyue.icu/Article/details/gt2orelcnuz.html

Go:   encoding/gob
来源：http://dali.yuxming.cn/Article/details/gt2vvbxkurm.html

Ruby: Marshal.dump(obj)
来源：http://dali.bjfxy.top/Article/details/gt2hyxpwvqc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gt2gxcbbcul.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2zaytbumi.html

L. 网络请求
来源：http://dali.sufxvd.cn/Article/details/gt2thkvcexl.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zgufaezl.html

[L01] 发送 GET 请求
来源：http://dali.shuidangran.top/Article/details/gt2geioznbq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuetiantiany.cn/Article/details/gt2wvlxqrld.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.kuanghao11.cn/Article/details/gt2kbqexafd.html

JS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gt2ygsbdbue.html

TS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gt2gathaphu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cqqwz.cn/Article/details/gt2wrazbxdy.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ruvoiumg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jlsjyb.cn/Article/details/gt2ithfxfpl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xziqi.cn/Article/details/gt2kocrrhoy.html

[L02] 发送 POST JSON
来源：http://dali.yonumen.top/Article/details/gt2zgryqita.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gt2zashqikl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.fengsongda.top/Article/details/gt2tefycwdl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gt2eqiorlqd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.havefunace.top/Article/details/gt2fcwxxcbk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sweek.top/Article/details/gt2nhikbyqm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nkltzicx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.mhx1999.top/Article/details/gt2jcjopylb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guannengcc.top/Article/details/gt2jlhevzql.html

[L03] 设置自定义请求头
来源：http://dali.dianchejie.cn/Article/details/gt2kivnchit.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sysykeji.top/Article/details/gt2dddbpzjr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dashuyun.cn/Article/details/gt2oljszzjk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenlongwang.top/Article/details/gt2vsgtefqn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gt2wvkcfiij.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hysaishi.cn/Article/details/gt2bvqxtoqp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gt2htzdqwse.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.9152youxi.cn/Article/details/gt2jrgpzgeh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gt2iozfzxid.html

[L04] 设置超时
来源：http://dali.hnxiangtu.top/Article/details/gt2ezlukqle.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sksfbvth.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ppjwa.cn/Article/details/gt2ouktmcnb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2wwqsuixq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gt2rnhqhgkq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cexwjxxc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.mhx1999.top/Article/details/gt2lxrktrpz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jiagoushi.top/Article/details/gt2bjovbxgu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hysaishi.cn/Article/details/gt2axcejcva.html

[L05] 上传文件（multipart）
来源：http://dali.vqdsnc.cn/Article/details/gt2wdrmfctb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cheryme.top/Article/details/gt2yxmncajy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhongyouzk.top/Article/details/gt2cavpuads.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gt2ldwtdziv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gt2hpmchvxd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aizwys.cn/Article/details/gt2lwhjvbue.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xinyue.icu/Article/details/gt2gwqspath.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aibaodan.cn/Article/details/gt2eovtujui.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.meibo888.top/Article/details/gt2zdvbctvb.html

[L06] 解析响应为 JSON
来源：http://dali.nwbrower.top/Article/details/gt2alwkktel.html

Py:   resp.json()
来源：http://dali.chenlongwang.top/Article/details/gt2cejmgeso.html

PHP:  json_decode($body, true);
来源：http://dali.guowangkeji.top/Article/details/gt2jpehswck.html

JS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2pjskcqgt.html

TS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gt2cibdctzt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gt2mrinqdqb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sxryk.cn/Article/details/gt2xyskdghz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yvedp.cn/Article/details/gt2pwolkjva.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jpmamhls.html

[L07] 处理 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gt2hjmzxtip.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yvedp.cn/Article/details/gt2uwcchxou.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.haohaochexian.top/Article/details/gt2bqbohrhz.html

JS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gt2pgtvlexl.html

TS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gt2dfaoqrnb.html

Java: resp.statusCode()
来源：http://dali.jinqigfzy.top/Article/details/gt2ztvwrycu.html

Go:   resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gt2mclhovaf.html

Ruby: resp.code.to_i
来源：http://dali.nanxinkj.top/Article/details/gt2uuflkmpo.html

C#:   (int)resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gt2dvtpqdyj.html

[L08] 并发请求多个地址
来源：http://dali.wangdashe.top/Article/details/gt2acmufpur.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cdnleiting.top/Article/details/gt2xrznidpl.html

PHP:  curl_multi_init() 系列
来源：http://dali.gogol.net.cn/Article/details/gt2hqwfhgew.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gt2gyxhtejs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gt2rbutwbgi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dashuyun.cn/Article/details/gt2kqpswkgr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258.top/Article/details/gt2oiomxqjq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fzhhl.top/Article/details/gt2pxvxquwd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tianlin.xyz/Article/details/gt2wjwcholo.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kusrsqjt.html

M. 命令行 / 进程 / 环境
来源：http://dali.jianghu66.top/Article/details/gt2vuoaefra.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2ezqgmvmx.html

[M01] 读取命令行参数
来源：http://dali.guowangkeji.top/Article/details/gt2orzowcfx.html

Py:   sys.argv[1:]
来源：http://dali.mhx1999.top/Article/details/gt2mfbhgfjv.html

PHP:  $argv;  $argc;
来源：http://dali.mhx1999.top/Article/details/gt2nsxcwrcj.html

JS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ftaphegv.html

TS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pranbuck.html

Java: args 数组（main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gt2srnpyvms.html

Go:   os.Args[1:]
来源：http://dali.sysykeji.top/Article/details/gt2mxntctjx.html

Ruby: ARGV
来源：http://dali.yj202588.top/Article/details/gt2cczbebzg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qhcaaqen.html

[M02] 读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gt2htvhtbgi.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2ynktbnri.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gt2xxidseuo.html

JS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gt2dbmhlajb.html

TS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gt2alvxmouk.html

Java: System.getenv("HOME")
来源：http://dali.hnqzz.top/Article/details/gt2omhtycxc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.iojbl.cn/Article/details/gt2jrycftdk.html

Ruby: ENV["HOME"]
来源：http://dali.sysykeji.top/Article/details/gt2qbhiatjh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.9152youxi.cn/Article/details/gt2ismlmaon.html

[M03] 执行外部命令
来源：http://dali.hywenlv.cn/Article/details/gt2fvhwsubn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ixmhwrhu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.c1oappe.top/Article/details/gt2sdzqpyce.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gt2givvqfyn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gt2qvvpwzcd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fengsongda.top/Article/details/gt2alvkmqvi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhiwuduotai.top/Article/details/gt2rdkbprfj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aizwys.cn/Article/details/gt2kuvwkbgw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shangyingyoupin.top/Article/details/gt2lzjxpvaq.html

[M04] 获取当前工作目录
来源：http://dali.fengsongda.top/Article/details/gt2nuivkage.html

Py:   os.getcwd()
来源：http://dali.hysaishi.cn/Article/details/gt2fuohoqul.html

PHP:  getcwd();
来源：http://dali.nwbrower.top/Article/details/gt2hqpiotci.html

JS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gt2ovrstcij.html

TS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2hzhiadpi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jyoumei.cn/Article/details/gt2gnnkmxqn.html

Go:   os.Getwd()
来源：http://dali.bjfxy.top/Article/details/gt2ypjaouap.html

Ruby: Dir.pwd
来源：http://dali.chenlongwang.top/Article/details/gt2uhyrebbu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigufen.top/Article/details/gt2bxvblcyg.html

[M05] 设置退出码
来源：http://dali.svipenyu.cn/Article/details/gt2hqgyyivo.html

Py:   sys.exit(1)
来源：http://dali.316326.xyz/Article/details/gt2xjbfmnuz.html

PHP:  exit(1);
来源：http://dali.316326.xyz/Article/details/gt2xsowxitw.html

JS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gt2ouaaqgce.html

TS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2esrgmeon.html

Java: System.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2lbzpjnaq.html

Go:   os.Exit(1)
来源：http://dali.yvedp.cn/Article/details/gt2laifdpfz.html

Ruby: exit 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2dyatcfcs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jianghu66.top/Article/details/gt2htgiejgq.html

[M06] 向标准错误输出
来源：http://dali.bjfxy.top/Article/details/gt2ekyygdag.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gt2qphruitr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnxiangtu.top/Article/details/gt2ozbmrnjo.html

JS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gt2jypenxap.html

TS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gt2amsftuyu.html

Java: System.err.println("err")
来源：http://dali.guowangkeji.top/Article/details/gt2glnkuzum.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258.top/Article/details/gt2cwssaych.html

Ruby: warn "err"
来源：http://dali.dianchejie.cn/Article/details/gt2pebsybhu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2mztvkxbk.html

[M07] 判断是否为主入口
来源：http://dali.andypj.xyz/Article/details/gt2xewyjefj.html

Py:   if __name__ == "__main__":
来源：http://dali.sufxvd.cn/Article/details/gt2ljpbdeyy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2hefsbtqq.html

JS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gt2asffgufr.html

TS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gt2cbuhrier.html

Java: public static void main(String[] args)
来源：http://dali.jiagoushi.top/Article/details/gt2lnzonvlj.html

Go:   func main()
来源：http://dali.fzhhl.top/Article/details/gt2fgblmyak.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj202588.top/Article/details/gt2qkfasacx.html

C#:   static void Main(string[] args)
来源：http://dali.pycfn.com/Article/details/gt2jngtylem.html

[M08] 获取系统与运行时信息
来源：http://dali.daria6918.cn/Article/details/gt2hkhrswrk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cheryme.top/Article/details/gt2aqceytir.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhiwuduotai.top/Article/details/gt2fsxjzqkh.html

JS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gt2gqizuwpo.html

TS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2exestkvu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gaohongyu789.top/Article/details/gt2zktwjyya.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dianchejie.cn/Article/details/gt2fruhczhz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangdashe.top/Article/details/gt2qckgihhx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangtech.top/Article/details/gt2odrqyqsb.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2mozckoku.html

N. 数据结构与算法
来源：http://dali.jianghu66.top/Article/details/gt2kgccowng.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2kcwbkcdb.html

[N01] 二分查找（有序数组）
来源：http://dali.0kj1m.cn/Article/details/gt2pbibtqzb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wtxmtghj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yonumen.top/Article/details/gt2qifijczh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gt2jzkbhiuz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2igqdohtq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2drmvvwob.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2uiebzwkq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.0kj1m.cn/Article/details/gt2jozennfu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2clnyeodj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aibaodan.cn/Article/details/gt2lcduxxmk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gt2zocotljn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.havefunace.top/Article/details/gt2uwfteqrh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gt2scyhvafd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gt2nhxnfybz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yueranfly.top/Article/details/gt2sildqdcs.html

Go:   slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gt2khtqrhwj.html

Ruby: arr.sort
来源：http://dali.shangyingyoupin.top/Article/details/gt2ygxdoska.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.meibo888.top/Article/details/gt2gmcclgnc.html

[N03] 快速排序（分治示例）
来源：http://dali.wangdashe.top/Article/details/gt2ligggidk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.andypj.xyz/Article/details/gt2dhrtywfz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhoulong.xyz/Article/details/gt2wzdyhbbe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gt2zvqvbgmg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jianghu66.top/Article/details/gt2cvlbhwuw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yangfankeji.com/Article/details/gt2ehxpndtx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhongyouzk.top/Article/details/gt2hydtnmeo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.0kj1m.cn/Article/details/gt2ltdeimvv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj202588.top/Article/details/gt2wjcjusjh.html

[N04] 斐波那契数列
来源：http://dali.zhiwuduotai.top/Article/details/gt2tvnwxywj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gt2jxmdikmj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gnmvtbsk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gt2owlklmof.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gt2gvrjimqb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zcqpxydc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aizwys.cn/Article/details/gt2tohhlomd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ilwsrdre.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gt2rismcegd.html

[N05] 最大公约数
来源：http://dali.svipenyu.cn/Article/details/gt2exlilwmx.html

Py:   math.gcd(a, b)
来源：http://dali.bjfxy.top/Article/details/gt2uraqqrxk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2brnznttu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gt2oersmonc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnqzz.top/Article/details/gt2drvszxex.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hywenlv.cn/Article/details/gt2hschfmxz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhoulong.xyz/Article/details/gt2dnkvhfzg.html

Ruby: a.gcd(b)
来源：http://dali.ydzc1.top/Article/details/gt2qiwzuhie.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hysaishi.cn/Article/details/gt2ntapvazh.html

[N06] 判断回文字符串
来源：http://dali.guowangkeji.top/Article/details/gt2dxdujwhl.html

Py:   s == s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gt2eovhcvmu.html

PHP:  $s === strrev($s);
来源：http://dali.yongpay.top/Article/details/gt2owouwfsp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bjcurocd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gt2howmzyct.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.smart0.xyz/Article/details/gt2qvvyhsnu.html

Go:   // 双指针从两端比较
来源：http://dali.shzxlz.cn/Article/details/gt2swhhmfby.html

Ruby: s == s.reverse
来源：http://dali.aibaodan.cn/Article/details/gt2hwezifbn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gt2sbuyules.html

[N07] 两数之和（返回下标）
来源：http://dali.yvedp.cn/Article/details/gt2nixzbode.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guannengcc.top/Article/details/gt2jbabhdpw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shuidangran.top/Article/details/gt2wnonuinv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yangfankeji.com/Article/details/gt2rcqigxed.html

TS:   // 手写 Map<string, number>
来源：http://dali.feifeiyinyue.top/Article/details/gt2mrrkpxdi.html

Java: // 手写 HashMap
来源：http://dali.kuanghao11.cn/Article/details/gt2xjrxeopf.html

Go:   // 手写 map[int]int
来源：http://dali.hfpthk.cn/Article/details/gt2ywduaoxx.html

Ruby: // 手写 Hash
来源：http://dali.9152youxi.cn/Article/details/gt2boyqldnw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jlsjyb.cn/Article/details/gt2wjqbubyh.html

[N08] 生成全排列
来源：http://dali.tanke756.top/Article/details/gt2bceafhea.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2shdpbnfg.html

PHP:  // 手写递归交换
来源：http://dali.shuidangran.top/Article/details/gt2akklifqn.html

JS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gt2axniwpum.html

TS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2ftqnwpzd.html

Java: // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gt2ocksplzr.html

Go:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2nfsfuxtu.html

Ruby: arr.permutation.to_a
来源：http://dali.jlsjyb.cn/Article/details/gt2ihgsyzog.html

C#:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gt2emnraiwx.html


<!-- 参考信息 -->