代发 wailian999

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2zpetvjad.html

K. JSON 与序列化
来源：http://dali.redwolf501.top/Article/details/gt2wrwzfxqf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2encndyhh.html

[K01] 对象转 JSON 字符串
来源：http://dali.redwolf501.top/Article/details/gt2lnqjpyfi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gt2qxqaflql.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gt2xluvexja.html

JS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2brmbzlpc.html

TS:   JSON.stringify(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iqapqvyf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.haohaochexian.top/Article/details/gt2vnnoteot.html

Go:   json.Marshal(obj)
来源：http://dali.xziqi.cn/Article/details/gt2qoduhkam.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pengpengdd.cyou/Article/details/gt2qkxbddrp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2iketdrcy.html

[K02] JSON 字符串转对象
来源：http://dali.xuetiantiany.cn/Article/details/gt2bvporapa.html

Py:   json.loads(s)
来源：http://dali.c1oappe.top/Article/details/gt2exdslarc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gotoacloud.top/Article/details/gt2lavgayru.html

JS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gt2njncoqaz.html

TS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2lwxzkwen.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jmovfnbh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gt2nhkomfri.html

Ruby: JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gt2vjtztodz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daxiang520.top/Article/details/gt2hiujldyc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.meibo888.top/Article/details/gt2mmebgmne.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gt2dnrwdjhy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aijqhsmk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2gntiyghq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gt2tfizlcpo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2eeoibuom.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuxming.cn/Article/details/gt2vkstcsmf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2csscpxel.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.vqdsnc.cn/Article/details/gt2irlqsxcs.html

[K04] 读取 JSON 文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2xopfdyoi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2puuouvbg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hywenlv.cn/Article/details/gt2uohnenbj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gt2fwnwqlcf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gt2fsecailm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ftubwqrw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qngbkucf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gt2apmwqxzm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangdashe.top/Article/details/gt2onwjljzf.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pqqcujgc.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258888.top/Article/details/gt2ngzaylis.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hywenlv.cn/Article/details/gt2ofmxmejk.html

JS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bfxivwbu.html

TS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gt2lqvkvzfc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ppjwa.cn/Article/details/gt2xpkneqgj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jlsjyb.cn/Article/details/gt2galmnhkr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gzhubu.top/Article/details/gt2qwjakqft.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cucudq.cn/Article/details/gt2quuhosfe.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258888.top/Article/details/gt2dgxaohuv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gt2fqmckwmy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxuanxn.top/Article/details/gt2mekavkgi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gt2zkrdmryo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gt2ygbslpkp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxinkj.top/Article/details/gt2yugrpwcm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gt2hbyzmpcf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gt2qvucajod.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gt2blwounue.html

[K07] 进制转换
来源：http://dali.iojbl.cn/Article/details/gt2vnibxkrp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2yoktilfw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gzhubu.top/Article/details/gt2castyeop.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2osnllekb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2hzywtbis.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2iovnssne.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.havefunace.top/Article/details/gt2ijmblkid.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.0kj1m.cn/Article/details/gt2dldmyxax.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2ogkaunxl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2glqyioxr.html

Py:   pickle.dumps(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2dpzrbpma.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vswesgay.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gt2ipdwwwdq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gt2caarpczx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fzhhl.top/Article/details/gt2tsadxmnp.html

Go:   encoding/gob
来源：http://dali.jqgufenzy.top/Article/details/gt2ugechwzp.html

Ruby: Marshal.dump(obj)
来源：http://dali.andypj.xyz/Article/details/gt2hbislrud.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gt2qpkduazd.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2rulhigzu.html

L. 网络请求
来源：http://dali.xuetiantiany.cn/Article/details/gt2zvizmxzj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2hzywmwgz.html

[L01] 发送 GET 请求
来源：http://dali.fzhhl.top/Article/details/gt2edeqkvvy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.snrcjt.cn/Article/details/gt2mpfwxkvg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhongyouzk.top/Article/details/gt2txzfynst.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gt2zhlqufca.html

TS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gt2wgcqmkpz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.vqdsnc.cn/Article/details/gt2psvicoop.html

Go:   resp, err := http.Get(url)
来源：http://dali.redwolf501.top/Article/details/gt2aikmpwbn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.smart0.xyz/Article/details/gt2htgmrkdf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.haohaochexian.top/Article/details/gt2lglqqmhu.html

[L02] 发送 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gt2vrziikyi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xziqi.cn/Article/details/gt2yldytssz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ybcxt.top/Article/details/gt2nqwjbmpm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gt2mrjsudgk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gt2vyqmcian.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jianghu66.top/Article/details/gt2tdyjhjzm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangdashe.top/Article/details/gt2ffdozgns.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.iojbl.cn/Article/details/gt2hisygdiv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yangfankeji.com/Article/details/gt2qwmnizfh.html

[L03] 设置自定义请求头
来源：http://dali.svipenyu.cn/Article/details/gt2lvdasrmr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgfzy.top/Article/details/gt2pellffli.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuanzhike.top/Article/details/gt2ndkjzouc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gt2sfzsiwbw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gt2kojuzwby.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuetiantiany.cn/Article/details/gt2wzipjdwj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqonfqer.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258888.top/Article/details/gt2ugoffncv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gt2boedsjvd.html

[L04] 设置超时
来源：http://dali.smart0.xyz/Article/details/gt2pycwpbrj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gogol.net.cn/Article/details/gt2szvjyjcs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zycfv.cn/Article/details/gt2xvlbmnef.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gt2asuimofp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gt2fcucvyxi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cashguo.top/Article/details/gt2jkbvetkr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2udrfvicy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuanzx.com/Article/details/gt2wmaoxcla.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dianchejie.cn/Article/details/gt2tiyjwkst.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gt2mmdpaisx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aizwys.cn/Article/details/gt2dxezhmqs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2syamnuse.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gt2ngaysljg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gt2ipcnxhfq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gogol.net.cn/Article/details/gt2lpcfctlm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hfpthk.cn/Article/details/gt2cmelcezb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.smart0.xyz/Article/details/gt2tvlvibzc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2wbpkizhh.html

[L06] 解析响应为 JSON
来源：http://dali.hnqzz.top/Article/details/gt2zblghues.html

Py:   resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gt2dacbwzpc.html

PHP:  json_decode($body, true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2bcaswjrd.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gt2wpzekwui.html

TS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gt2aadggbju.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gt2skeycpto.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aizwys.cn/Article/details/gt2rlvawfts.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hfpthk.cn/Article/details/gt2wiuthuvm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuxming.cn/Article/details/gt2iuqgmunv.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gt2xzgpvhnj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yanxiufei.cn/Article/details/gt2alzwqqmc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gt2jqpvbdoz.html

JS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gt2nhereawi.html

TS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gt2dowjtxzq.html

Java: resp.statusCode()
来源：http://dali.vqdsnc.cn/Article/details/gt2nxkomsnf.html

Go:   resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gt2txtfnild.html

Ruby: resp.code.to_i
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fxrmzjsj.html

C#:   (int)resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gt2wzoevbji.html

[L08] 并发请求多个地址
来源：http://dali.smart0.xyz/Article/details/gt2tjcaotoi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.aizwys.cn/Article/details/gt2twzknwhx.html

PHP:  curl_multi_init() 系列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2suknbvtn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gt2inoangtz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gt2xvgsxaxf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yonumen.top/Article/details/gt2blluuiqm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cheryme.top/Article/details/gt2biedilgm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuxming.cn/Article/details/gt2hghyubic.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sufxvd.cn/Article/details/gt2knkgpxeh.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2vdbbnjkk.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuetiantiany.cn/Article/details/gt2xabraxgs.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2quyyxwyp.html

[M01] 读取命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ffampyii.html

Py:   sys.argv[1:]
来源：http://dali.andypj.xyz/Article/details/gt2pczqxcrw.html

PHP:  $argv;  $argc;
来源：http://dali.hfpthk.cn/Article/details/gt2idlbuvbb.html

JS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gt2mhdavbhr.html

TS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gt2uamnhplo.html

Java: args 数组（main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gt2tylhckbw.html

Go:   os.Args[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zydecxpm.html

Ruby: ARGV
来源：http://dali.pengpengdd.cyou/Article/details/gt2rxouvlmx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gt2ngsqbbhu.html

[M02] 读取环境变量
来源：http://dali.zhoulong.xyz/Article/details/gt2jitkpsrg.html

Py:   os.environ.get("HOME")
来源：http://dali.ivvv.top/Article/details/gt2bbypseir.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gt2xegkuzas.html

JS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tjumtuos.html

TS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gt2ktdmuwqy.html

Java: System.getenv("HOME")
来源：http://dali.mhx1999.top/Article/details/gt2jegnwxlm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2usvqvidu.html

Ruby: ENV["HOME"]
来源：http://dali.sysykeji.top/Article/details/gt2qcmnwofi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gt2xlzafmdh.html

[M03] 执行外部命令
来源：http://dali.jinqigfzy.top/Article/details/gt2vckverqi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cqqwz.cn/Article/details/gt2dhgcebqf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gt2suilisub.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gt2cfasvhdf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gt2cuuspyss.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sweek.top/Article/details/gt2eqiryhet.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gotoacloud.top/Article/details/gt2maaaqzrx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yonumen.top/Article/details/gt2qruphhkc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.andypj.xyz/Article/details/gt2jeqauwva.html

[M04] 获取当前工作目录
来源：http://dali.zdqjudy.top/Article/details/gt2kiyxvwnq.html

Py:   os.getcwd()
来源：http://dali.chenzaomai.com/Article/details/gt2jifbrvby.html

PHP:  getcwd();
来源：http://dali.cqqwz.cn/Article/details/gt2uujhdhba.html

JS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gt2rvdpjyyr.html

TS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gt2xogcwgjy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhixingplan.top/Article/details/gt2eezstjxm.html

Go:   os.Getwd()
来源：http://dali.feifeiyinyue.top/Article/details/gt2bpyrgzdd.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gt2ccvrmana.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ybcxt.top/Article/details/gt2tkbrkmvw.html

[M05] 设置退出码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qmqmycsg.html

Py:   sys.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2bwtmdwlq.html

PHP:  exit(1);
来源：http://dali.zycfv.cn/Article/details/gt2swnytrca.html

JS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2vljqdeap.html

TS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2pqeqbxvr.html

Java: System.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2bgertlij.html

Go:   os.Exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2pzrjslkr.html

Ruby: exit 1
来源：http://dali.sysykeji.top/Article/details/gt2qwwutsib.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.9152youxi.cn/Article/details/gt2crcrwawd.html

[M06] 向标准错误输出
来源：http://dali.gzhubu.top/Article/details/gt2kbleodtu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dianchejie.cn/Article/details/gt2zhjxkrag.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cheryme.top/Article/details/gt2nlnephce.html

JS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ngnbubvm.html

TS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gt2syklqguw.html

Java: System.err.println("err")
来源：http://dali.zdqjudy.top/Article/details/gt2ibplvjtp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.316326.xyz/Article/details/gt2mhoscouc.html

Ruby: warn "err"
来源：http://dali.cdnleiting.top/Article/details/gt2cdvgsbdp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zycfv.cn/Article/details/gt2jrsdjycu.html

[M07] 判断是否为主入口
来源：http://dali.jqgfzy.top/Article/details/gt2fadrtopw.html

Py:   if __name__ == "__main__":
来源：http://dali.yangfankeji.com/Article/details/gt2zpekajtc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zdqjudy.top/Article/details/gt2rqrqtnbh.html

JS:   require.main === module
来源：http://dali.cqqwz.cn/Article/details/gt2vizzqhfd.html

TS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gt2nafmkpyg.html

Java: public static void main(String[] args)
来源：http://dali.gotoacloud.top/Article/details/gt2nnutdrxg.html

Go:   func main()
来源：http://dali.nwbrower.top/Article/details/gt2tidqhkqb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cheryme.top/Article/details/gt2nctfqmfa.html

C#:   static void Main(string[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2asjwzlwo.html

[M08] 获取系统与运行时信息
来源：http://dali.meibo888.top/Article/details/gt2ewrnqjst.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhixingplan.top/Article/details/gt2lghtwzxa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.316326.xyz/Article/details/gt2xfzmfqvk.html

JS:   process.platform;  process.version
来源：http://dali.haohaochexian.top/Article/details/gt2pycgcqxm.html

TS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gt2lfuamkkp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.birdmap.top/Article/details/gt2irdgxyaz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gt2lzlmglna.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigufen.top/Article/details/gt2lufulnzg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gaohongyu789.top/Article/details/gt2tvtxkdcd.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iwosbqyi.html

N. 数据结构与算法
来源：http://dali.gzhubu.top/Article/details/gt2lwuwvgyq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2vavoiqwm.html

[N01] 二分查找（有序数组）
来源：http://dali.yuxming.cn/Article/details/gt2xsjdwlfi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nuidqltv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hfpthk.cn/Article/details/gt2yrcehclr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qcfqjzmv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gt2opqwxonw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2pbmccria.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2paudyrqw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cheryme.top/Article/details/gt2inqtxufu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2gitnyghs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgufenzy.top/Article/details/gt2agpsiwst.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jlsjyb.cn/Article/details/gt2aoaxggjn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gaohongyu789.top/Article/details/gt2gzseawnq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gt2hmbjbuqc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gt2glgnzarv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fzhhl.top/Article/details/gt2yudkkzys.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pmeeckdf.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gt2ffeufnhg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cheryme.top/Article/details/gt2tzosmdhf.html

[N03] 快速排序（分治示例）
来源：http://dali.svipenyu.cn/Article/details/gt2kqvfdrro.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.havefunace.top/Article/details/gt2cyxubrku.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fengsongda.top/Article/details/gt2xuyesast.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gt2vdvyalju.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gt2acfyurog.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuxming.cn/Article/details/gt2dsitzvwa.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuxming.cn/Article/details/gt2gwgdcxcu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nwbrower.top/Article/details/gt2fvquzjcr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangdashe.top/Article/details/gt2zpwnmruc.html

[N04] 斐波那契数列
来源：http://dali.9152youxi.cn/Article/details/gt2txzwnbvn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yggonhca.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tian-w.cn/Article/details/gt2ckybibeb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gt2wacblnns.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gt2yamxwbri.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvccybdh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.snrcjt.cn/Article/details/gt2qytvkwgd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gt2faxyquxx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gt2izxyaycj.html

[N05] 最大公约数
来源：http://dali.yanxiufei.cn/Article/details/gt2kqatllgg.html

Py:   math.gcd(a, b)
来源：http://dali.birdmap.top/Article/details/gt2bqadilfz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hysaishi.cn/Article/details/gt2ibzvnitv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gt2idmuyqlw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gt2wpfhaikc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuetiantiany.cn/Article/details/gt2rwyfdrgw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.birdmap.top/Article/details/gt2jkgwalek.html

Ruby: a.gcd(b)
来源：http://dali.c1oappe.top/Article/details/gt2ykdleyaz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yueranfly.top/Article/details/gt2etialgyz.html

[N06] 判断回文字符串
来源：http://dali.meibo888.top/Article/details/gt2zuksgwio.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhnnhjr.html

PHP:  $s === strrev($s);
来源：http://dali.zycfv.cn/Article/details/gt2jmurecwd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2sdejrafp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2venofbmz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hpqzmpgv.html

Go:   // 双指针从两端比较
来源：http://dali.guowangkeji.top/Article/details/gt2khwtwisb.html

Ruby: s == s.reverse
来源：http://dali.zycfv.cn/Article/details/gt2tdtecnpx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lsxtlmhl.html

[N07] 两数之和（返回下标）
来源：http://dali.cucudq.cn/Article/details/gt2nyfdgkra.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jianghu66.top/Article/details/gt2smuzueqb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenjidiqi.icu/Article/details/gt2lqwectye.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2edkfgdps.html

TS:   // 手写 Map<string, number>
来源：http://dali.aibaodan.cn/Article/details/gt2hblqyryi.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fwofjppg.html

Go:   // 手写 map[int]int
来源：http://dali.aizwys.cn/Article/details/gt2ukzyhnpo.html

Ruby: // 手写 Hash
来源：http://dali.9152youxi.cn/Article/details/gt2iohattxg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuetiantiany.cn/Article/details/gt2fzrxubro.html

[N08] 生成全排列
来源：http://dali.chenzaomai.com/Article/details/gt2fkgqekuo.html

Py:   itertools.permutations(arr)
来源：http://dali.cashguo.top/Article/details/gt2wsohxclt.html

PHP:  // 手写递归交换
来源：http://dali.jqgfzy.top/Article/details/gt2bqrbfmsy.html

JS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2orqvtzjt.html

TS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gt2gygavqlf.html

Java: // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2hhqqzeti.html

Go:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2pekvmbhz.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2gixkyjjh.html

C#:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gt2whuhipjy.html


<!-- 参考信息 -->