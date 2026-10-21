代发 wailian999

[K02] JSON 字符串转对象
来源：http://dali.316326.xyz/Article/details/gtinukwiyo.html

Py:   json.loads(s)
来源：http://dali.xylfe.cn/Article/details/gtvnlzkenb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zycfv.cn/Article/details/gtymfugtqn.html

JS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtztzrgfqy.html

TS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gthpfeawdt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gotoacloud.top/Article/details/gtuguljhck.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gtssznnyrq.html

Ruby: JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtxkcdosqc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yongpay.top/Article/details/gtqsuzcizh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cheryme.top/Article/details/gtsfplbojo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuanzhike.top/Article/details/gtxmepzenn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gtxbyrgeyz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gtradurqyz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gtzuuikvbt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.haohaochexian.top/Article/details/gtzzetbppj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtntecxllf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daxiang520.top/Article/details/gtveucepto.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sweek.top/Article/details/gtepdgjapu.html

[K04] 读取 JSON 文件
来源：http://dali.ydzc1.top/Article/details/gtmkxtgnvq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsanmjsoo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpofwpvyf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gtvunbmcfh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gtnrbbutrr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gtorphqlug.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtkkhflbme.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gtrsgdmzko.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.316326.xyz/Article/details/gtenhwtubl.html

[K05] 深拷贝对象
来源：http://dali.vqdsnc.cn/Article/details/gtsvkrrqhx.html

Py:   copy.deepcopy(obj)
来源：http://dali.ppjwa.cn/Article/details/gtjajufgcl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigufen.top/Article/details/gtcoiacxbo.html

JS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtvcicpdxs.html

TS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gtklsufhuf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dashuyun.cn/Article/details/gtptmnajgn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hongshengwenyu.top/Article/details/gtitcvprom.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gtrcvsyuak.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.c1oappe.top/Article/details/gtyvydtkjh.html

[K06] 解析 URL 查询串
来源：http://dali.havefunace.top/Article/details/gtxwudorxy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tian-w.cn/Article/details/gtgdvzujxl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shzxlz.cn/Article/details/gtdjscwjpy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gtqghjbmob.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gtzyzgwgrl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.vqdsnc.cn/Article/details/gtjbayugtw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gtevpmqkbc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtrejpauis.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gtecriiemj.html

[K07] 进制转换
来源：http://dali.jinqigufen.top/Article/details/gtluctjtus.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtauzbbllf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.meibo888.top/Article/details/gtvgguylbc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtewzcyhfs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtmnbtarlj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtvvnukhus.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pengpengdd.cyou/Article/details/gtaqkovpdk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fzhhl.top/Article/details/gtlqeepuaf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtbamecxic.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nwbrower.top/Article/details/gtspkttnvo.html

Py:   pickle.dumps(obj)
来源：http://dali.chenlongwang.top/Article/details/gthqzhjtxl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daxiang520.top/Article/details/gtvdpycsyt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvrvymxw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtphqhdksl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gogol.net.cn/Article/details/gtxdniztnt.html

Go:   encoding/gob
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiosnckix.html

Ruby: Marshal.dump(obj)
来源：http://dali.ybcxt.top/Article/details/gtqnejnoek.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gthprkfviv.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtfhsnyvky.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gtijmwtnqc.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtkntqfile.html

[L01] 发送 GET 请求
来源：http://dali.chenlongwang.top/Article/details/gtqlojsowb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gzhubu.top/Article/details/gtpsuatzfy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pengpengdd.cyou/Article/details/gttrpriqyo.html

JS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gtipxdemar.html

TS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gtjyjayncl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuxming.cn/Article/details/gtwnlnmqnm.html

Go:   resp, err := http.Get(url)
来源：http://dali.xinyue.icu/Article/details/gtyehweikr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xziqi.cn/Article/details/gtkilcbyhr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhoulong.xyz/Article/details/gtkqryeygb.html

[L02] 发送 POST JSON
来源：http://dali.fzhhl.top/Article/details/gtnolritss.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtszfilzdw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.bjfxy.top/Article/details/gttastwowi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gtevlonphk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpyveyjhd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.mhx1999.top/Article/details/gtydpslhpr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgufenzy.top/Article/details/gtdokklnwo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ehwqpu.com/Article/details/gtansjmiyt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.dianchejie.cn/Article/details/gtclqpircj.html

[L03] 设置自定义请求头
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxizrjeb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hywenlv.cn/Article/details/gttgzahjrr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnxiangtu.top/Article/details/gtzoogmpmx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gtfdslsnko.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gtspfzijrx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfzauwko.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gtvhkhuurm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.havefunace.top/Article/details/gtedggzoms.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gtssynfpkw.html

[L04] 设置超时
来源：http://dali.yanxiufei.cn/Article/details/gtltypbzoo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.bjfxy.top/Article/details/gtsmqqndqo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gtitmhijkg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guannengcc.top/Article/details/gtfmflbpbn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gtjnaqyivn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nanxuanxn.top/Article/details/gtnicrjjbw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnqzz.top/Article/details/gtjzoqeout.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sxryk.cn/Article/details/gtwsuuctws.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ppjwa.cn/Article/details/gtoudveold.html

[L05] 上传文件（multipart）
来源：http://dali.guowangkeji.top/Article/details/gtctasgvaj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ehwqpu.com/Article/details/gtuidypzgw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.meibo888.top/Article/details/gtclmlvyyd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gthnqtyove.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtgahjjbed.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gzhubu.top/Article/details/gtyoptgqty.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dashuyun.cn/Article/details/gtohkxaygj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cucudq.cn/Article/details/gtpshusnxo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gttyxewgdi.html

[L06] 解析响应为 JSON
来源：http://dali.chenzaomai.com/Article/details/gtkknsupkr.html

Py:   resp.json()
来源：http://dali.tanke756.top/Article/details/gtvszduxay.html

PHP:  json_decode($body, true);
来源：http://dali.zhengqikj.top/Article/details/gtamabpjwi.html

JS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gteizhijlo.html

TS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gtfacatkww.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258888.top/Article/details/gtrorvvmal.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aibaodan.cn/Article/details/gttyopkxqc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hfpthk.cn/Article/details/gtshkjpqpc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gotoacloud.top/Article/details/gtufkziyrl.html

[L07] 处理 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gtdiyvlinl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yueranfly.top/Article/details/gtofjjjztq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj202588.top/Article/details/gtedwnutyd.html

JS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gtxcwesvue.html

TS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtebmhkhtq.html

Java: resp.statusCode()
来源：http://dali.jinqigfzy.top/Article/details/gtmpdvrspk.html

Go:   resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gtehwsnvxk.html

Ruby: resp.code.to_i
来源：http://dali.pycfn.com/Article/details/gtkvztpnes.html

C#:   (int)resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gtsyumbrmd.html

[L08] 并发请求多个地址
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxuxdipnm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fzhhl.top/Article/details/gtyldxifur.html

PHP:  curl_multi_init() 系列
来源：http://dali.gogol.net.cn/Article/details/gtxvvtxdtm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtugnumgwk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtaibxerut.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cheryme.top/Article/details/gtponwrtec.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuanzhike.top/Article/details/gtuxlasmtl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfxsgttx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gzhubu.top/Article/details/gthesgosgj.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtbywrzrxv.html

M. 命令行 / 进程 / 环境
来源：http://dali.feifeiyinyue.top/Article/details/gtvcrwrqrq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtcbacifre.html

[M01] 读取命令行参数
来源：http://dali.tanke756.top/Article/details/gtkwvzyegn.html

Py:   sys.argv[1:]
来源：http://dali.guannengcc.top/Article/details/gtcuggnmyk.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258888.top/Article/details/gtouvjmutm.html

JS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtmjmpnzfs.html

TS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gtjdmdbpot.html

Java: args 数组（main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gtnjorubst.html

Go:   os.Args[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gtbaiclpab.html

Ruby: ARGV
来源：http://dali.jqgfzy.top/Article/details/gtilouhdhr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dianchejie.cn/Article/details/gtadnmalkx.html

[M02] 读取环境变量
来源：http://dali.jinqigfzy.top/Article/details/gtbshdxgnm.html

Py:   os.environ.get("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtlgghkqks.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guowangkeji.top/Article/details/gtskrmgjhj.html

JS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtmoqjcyug.html

TS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gtfqujqmpb.html

Java: System.getenv("HOME")
来源：http://dali.ydzc1.top/Article/details/gtahjirejz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtxsbrbytw.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigufen.top/Article/details/gtaidoiilc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yvedp.cn/Article/details/gtavigszew.html

[M03] 执行外部命令
来源：http://dali.c1oappe.top/Article/details/gtxzegjvyw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sysykeji.top/Article/details/gtdxadnhbb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.c1oappe.top/Article/details/gtbkybmefk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gtvervwxbb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gthligskxm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dashuyun.cn/Article/details/gtzxvdheax.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangdashe.top/Article/details/gtgywnynlh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jyoumei.cn/Article/details/gtlqddalnz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.smart0.xyz/Article/details/gtcrasoqpq.html

[M04] 获取当前工作目录
来源：http://dali.c1oappe.top/Article/details/gtmspjeahp.html

Py:   os.getcwd()
来源：http://dali.nanxinkj.top/Article/details/gtiamrhbvv.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gtaksxuywa.html

JS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gtaggslyun.html

TS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gtlyubvzsp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tian-w.cn/Article/details/gthwhgisuc.html

Go:   os.Getwd()
来源：http://dali.svipenyu.cn/Article/details/gtogswaovs.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gtbhoeoitq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shuidangran.top/Article/details/gtywqignrz.html

[M05] 设置退出码
来源：http://dali.jinqigufen.top/Article/details/gtpthpxuiz.html

Py:   sys.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtrdbrgrst.html

PHP:  exit(1);
来源：http://dali.cucudq.cn/Article/details/gtiwivcldf.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzzjrrjt.html

TS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtjqzihlnz.html

Java: System.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtwqwptwmg.html

Go:   os.Exit(1)
来源：http://dali.bjfxy.top/Article/details/gttskenoby.html

Ruby: exit 1
来源：http://dali.wangdashe.top/Article/details/gtttrrncdd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.pycfn.com/Article/details/gtiecdubek.html

[M06] 向标准错误输出
来源：http://dali.dashuyun.cn/Article/details/gtktlvdrjx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cashguo.top/Article/details/gtailfsuen.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xziqi.cn/Article/details/gtyfogquwj.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtfoutvupk.html

TS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gtzhsyjxcb.html

Java: System.err.println("err")
来源：http://dali.ppjwa.cn/Article/details/gtxsyrhdvc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxuanxn.top/Article/details/gtwbdadxkr.html

Ruby: warn "err"
来源：http://dali.ivvv.top/Article/details/gtabycdvep.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yonumen.top/Article/details/gtllusclzg.html

[M07] 判断是否为主入口
来源：http://dali.nanxinkj.top/Article/details/gtzkoraoyo.html

Py:   if __name__ == "__main__":
来源：http://dali.meibo888.top/Article/details/gtkmtohstq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.andypj.xyz/Article/details/gtsbnxrzax.html

JS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gtanssmctt.html

TS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gttuyntvzb.html

Java: public static void main(String[] args)
来源：http://dali.svipenyu.cn/Article/details/gtvlrziuov.html

Go:   func main()
来源：http://dali.xylfe.cn/Article/details/gtvftjguhv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guannengcc.top/Article/details/gtaaeurpcn.html

C#:   static void Main(string[] args)
来源：http://dali.ppjwa.cn/Article/details/gtmralydib.html

[M08] 获取系统与运行时信息
来源：http://dali.xylfe.cn/Article/details/gtclgixfdc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangdashe.top/Article/details/gteemynqji.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tianlin.xyz/Article/details/gtlntdvdif.html

JS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gtxbygrajg.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtdxkishup.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cdnleiting.top/Article/details/gtclzwdupw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yonumen.top/Article/details/gtjzeahrrs.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenzaomai.com/Article/details/gtqkztiirb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xylfe.cn/Article/details/gtxsraesur.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtwepodgtn.html

N. 数据结构与算法
来源：http://dali.pengpengdd.cyou/Article/details/gthwzhhlpj.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtypinyvik.html

[N01] 二分查找（有序数组）
来源：http://dali.sweek.top/Article/details/gtlfquhdcx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtljfdgsyb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gtoyfoxsau.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcedcyqx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtotkycktj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtycxjougo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtkvmpmyry.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.9152youxi.cn/Article/details/gtunpkszea.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtebtadftr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ivvv.top/Article/details/gtmitqhcyc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gtgdowqpgs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.svipenyu.cn/Article/details/gtmjdbhotz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gtoprvaago.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtvadfzfmn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jyoumei.cn/Article/details/gttcxkjeyq.html

Go:   slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gtuxufojyg.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gtiifkwktw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jlsjyb.cn/Article/details/gtybvpmpzc.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbaebxxof.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigfzy.top/Article/details/gthonmwgyv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzvywpsp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuetiantiany.cn/Article/details/gtwbvrgdyl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gtzhvvstgy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cucudq.cn/Article/details/gtlnhlqjjn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guannengcc.top/Article/details/gtalehbzmh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shuidangran.top/Article/details/gtoaxagzlz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daria6918.cn/Article/details/gtxmjcuohq.html

[N04] 斐波那契数列
来源：http://dali.iojbl.cn/Article/details/gtebqvoxok.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnxiangtu.top/Article/details/gtagmocebb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gtlnipbsrk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtzuvjlqcc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gtaezpxnru.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gthlhwxsts.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinqigfzy.top/Article/details/gtzlnkxxsp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgjeyqqs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaknxjlvu.html

[N05] 最大公约数
来源：http://dali.meibo888.top/Article/details/gtjrfrqrtd.html

Py:   math.gcd(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtdlzetasc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jiagoushi.top/Article/details/gtwsiyzsvw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gtamkpalwk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gtvyngnyqd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.feifeiyinyue.top/Article/details/gtxscrvqxy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.iojbl.cn/Article/details/gtclmsohai.html

Ruby: a.gcd(b)
来源：http://dali.zhongyouzk.top/Article/details/gtznzyyhio.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hammf.cn/Article/details/gtpawalmmw.html

[N06] 判断回文字符串
来源：http://dali.yanxiufei.cn/Article/details/gtthwhdhgq.html

Py:   s == s[::-1]
来源：http://dali.andypj.xyz/Article/details/gtlfhrkgxy.html

PHP:  $s === strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtckzmumvt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtkalacofn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtijzqmvnr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhoulong.xyz/Article/details/gtafavryov.html

Go:   // 双指针从两端比较
来源：http://dali.pycfn.com/Article/details/gtdpmwsnnv.html

Ruby: s == s.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtovpfambo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gtxffchtet.html

[N07] 两数之和（返回下标）
来源：http://dali.sysykeji.top/Article/details/gtblvkxblc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gtnizgdugh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhoulong.xyz/Article/details/gtsmucfogi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nanxuanxn.top/Article/details/gtqambutnq.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxuanxn.top/Article/details/gtbyfcipbq.html

Java: // 手写 HashMap
来源：http://dali.pycfn.com/Article/details/gtneigyase.html

Go:   // 手写 map[int]int
来源：http://dali.9152youxi.cn/Article/details/gtmvvlaonk.html

Ruby: // 手写 Hash
来源：http://dali.andypj.xyz/Article/details/gtprvbfjhr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhoulong.xyz/Article/details/gtcriqofla.html

[N08] 生成全排列
来源：http://dali.shuidangran.top/Article/details/gtxriqdmxn.html

Py:   itertools.permutations(arr)
来源：http://dali.gogol.net.cn/Article/details/gtznoxtquy.html

PHP:  // 手写递归交换
来源：http://dali.fzhhl.top/Article/details/gtgdwxrzpi.html

JS:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gthzzdunry.html

TS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtdpmzqypm.html

Java: // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtuyibsntd.html

Go:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymftcjac.html

Ruby: arr.permutation.to_a
来源：http://dali.smart0.xyz/Article/details/gtwuagimun.html

C#:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtlupezhqj.html

[N09] 栈与队列
来源：http://dali.jqgfzy.top/Article/details/gtyydtrlpg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jlsjyb.cn/Article/details/gturcxhwml.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtdfxvnqel.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtbifeirka.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.birdmap.top/Article/details/gtqtoihgcx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shuidangran.top/Article/details/gtnnsqmgst.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.smart0.xyz/Article/details/gtwjxtoxea.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwurhypls.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zdqjudy.top/Article/details/gtenmlnnpv.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gttyaskvip.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hywenlv.cn/Article/details/gtyugdlprg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dianchejie.cn/Article/details/gtxstovkvw.html


<!-- 参考信息 -->