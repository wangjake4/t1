代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gt2zntuqcms.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.bjfxy.top/Article/details/gt2tlllopgf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gt2oafnxdjn.html

Ruby: JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gt2tpwubiio.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gt2qwqwpljs.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yongpay.top/Article/details/gt2dwcsmaba.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsspkdm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gt2fjxwqzxz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ydzc1.top/Article/details/gt2ewueoxnx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gt2xchhfjea.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hnqzz.top/Article/details/gt2zsupqmzf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cqqwz.cn/Article/details/gt2sqisrozf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mgbivtlr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.daxiang520.top/Article/details/gt2fcykomnv.html

[K04] 读取 JSON 文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2brxqyras.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gaohongyu789.top/Article/details/gt2lmtfxiha.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gfjnqynq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gt2urzydtuz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gt2smiwyszw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ijdcejtq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jfgejwxw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sxryk.cn/Article/details/gt2xckryvaz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gt2itcwjliu.html

[K05] 深拷贝对象
来源：http://dali.gaohongyu789.top/Article/details/gt2gcqxjwuc.html

Py:   copy.deepcopy(obj)
来源：http://dali.hnqzz.top/Article/details/gt2xletlxka.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnxiangtu.top/Article/details/gt2tlvjzqbu.html

JS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2zcvwwohf.html

TS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2lpthgnpo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuetiantiany.cn/Article/details/gt2xsaagubo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bwkzxcqe.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigufen.top/Article/details/gt2mvbdnngm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.havefunace.top/Article/details/gt2mlwjegxi.html

[K06] 解析 URL 查询串
来源：http://dali.sysykeji.top/Article/details/gt2xtxfixzs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jlsjyb.cn/Article/details/gt2hdlxigjz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2odqfcoqa.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xrfwmaku.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gt2zhemwlbh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sufxvd.cn/Article/details/gt2zwklemub.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gt2ywwvadnh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gt2kmdcfgru.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gt2iqgfoafr.html

[K07] 进制转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mtzoqbqg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2kswbscgk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gt2tqzhtgbn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2skdymmge.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuipekb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2jfcxnttz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zycfv.cn/Article/details/gt2mmwqjozd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ppjwa.cn/Article/details/gt2ioemrmhz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kumhlxxp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hywenlv.cn/Article/details/gt2klmxbdgd.html

Py:   pickle.dumps(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2ilguoqyt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hammf.cn/Article/details/gt2ibcxwdpk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2huvzvsbs.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gt2rclotyrr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.snrcjt.cn/Article/details/gt2lbtonldb.html

Go:   encoding/gob
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wqnwsdrk.html

Ruby: Marshal.dump(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2utppegdg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gt2llifqoou.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2nnkpidyr.html

L. 网络请求
来源：http://dali.316326.xyz/Article/details/gt2fjhlyssn.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2vuorihru.html

[L01] 发送 GET 请求
来源：http://dali.ivvv.top/Article/details/gt2jxyxbrfh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ppjwa.cn/Article/details/gt2pdppjxun.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pycfn.com/Article/details/gt2erhuvrjj.html

JS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gt2zvwafsbl.html

TS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gt2labjysvz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuanzhike.top/Article/details/gt2aeyhisqw.html

Go:   resp, err := http.Get(url)
来源：http://dali.tanke756.top/Article/details/gt2xqoaeqli.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258.top/Article/details/gt2ujziulpw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.smart0.xyz/Article/details/gt2cenqlgyy.html

[L02] 发送 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2onkclzxs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sweek.top/Article/details/gt2bcztqubr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hywenlv.cn/Article/details/gt2kvfckiyo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gt2jbzfwhsw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gt2vngiblwm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daria6918.cn/Article/details/gt2pzgdaraj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tanke756.top/Article/details/gt2skoecrvx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dashuyun.cn/Article/details/gt2ltsmrxyo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hfpthk.cn/Article/details/gt2fqbcwskn.html

[L03] 设置自定义请求头
来源：http://dali.jqgfzy.top/Article/details/gt2ebxngikw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zycfv.cn/Article/details/gt2xabchrzw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aizwys.cn/Article/details/gt2lbkuoscj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gt2moukulwo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qwvbkrjq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258.top/Article/details/gt2huyehkcb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gt2ffclratk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.iojbl.cn/Article/details/gt2mwegrevr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gt2thigtmvz.html

[L04] 设置超时
来源：http://dali.hnqzz.top/Article/details/gt2taezvkyc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ydzc1.top/Article/details/gt2bgqnisbx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xinyue.icu/Article/details/gt2uetcbgyy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gt2ltlztbjt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gt2ulxrptcy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fyabhrww.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yangfankeji.com/Article/details/gt2iwwfrbsm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.iojbl.cn/Article/details/gt2vbpccpbr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenlongwang.top/Article/details/gt2ljenlcqb.html

[L05] 上传文件（multipart）
来源：http://dali.wangshuangyany.cn/Article/details/gt2xtyeqvbh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigfzy.top/Article/details/gt2vlygldzb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hammf.cn/Article/details/gt2ewwolbwb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gt2mpgwmody.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gt2tgrncxem.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aizwys.cn/Article/details/gt2spofycnl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgfzy.top/Article/details/gt2jszsseue.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tanke756.top/Article/details/gt2dksoxavr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2yfqeyujv.html

[L06] 解析响应为 JSON
来源：http://dali.yueranfly.top/Article/details/gt2vqxutppg.html

Py:   resp.json()
来源：http://dali.mhx1999.top/Article/details/gt2gsavbwle.html

PHP:  json_decode($body, true);
来源：http://dali.ivvv.top/Article/details/gt2kexuydzr.html

JS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gt2ocvhqwlx.html

TS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gt2maujpbya.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nhqmanwi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jianghu66.top/Article/details/gt2fqtdmzbs.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ndhicrtv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.c1oappe.top/Article/details/gt2oppcxbcn.html

[L07] 处理 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gt2kcfdusvt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cucudq.cn/Article/details/gt2azetbezs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrabwvx.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gt2thaxwnge.html

TS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gt2qsjvfuvt.html

Java: resp.statusCode()
来源：http://dali.sxryk.cn/Article/details/gt2yclnusjd.html

Go:   resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gt2pzmmojqe.html

Ruby: resp.code.to_i
来源：http://dali.snrcjt.cn/Article/details/gt2hlyevrcu.html

C#:   (int)resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gt2aedntkhx.html

[L08] 并发请求多个地址
来源：http://dali.yanxiufei.cn/Article/details/gt2aqcdycvy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xinyue.icu/Article/details/gt2hazgikzy.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj202588.top/Article/details/gt2ycailirz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjqdnxua.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gt2gcgyeyio.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guannengcc.top/Article/details/gt2nyocuwdv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shzxlz.cn/Article/details/gt2mgqfrbuu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ydzc1.top/Article/details/gt2utcosizl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuanzx.com/Article/details/gt2mvacfvtb.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2vazlatoz.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgufenzy.top/Article/details/gt2isfwprrr.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2srntnpzx.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lkzqxuoa.html

Py:   sys.argv[1:]
来源：http://dali.tian-w.cn/Article/details/gt2rxutnoqu.html

PHP:  $argv;  $argc;
来源：http://dali.gaohongyu789.top/Article/details/gt2fnobmxct.html

JS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gt2bfvfzryt.html

TS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gt2ydkcurfm.html

Java: args 数组（main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ctwnpgnp.html

Go:   os.Args[1:]
来源：http://dali.tanke756.top/Article/details/gt2jxbniuyl.html

Ruby: ARGV
来源：http://dali.gzhubu.top/Article/details/gt2ddwueyhk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gt2jcfujrhi.html

[M02] 读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gt2aksslign.html

Py:   os.environ.get("HOME")
来源：http://dali.xuanzx.com/Article/details/gt2pzgodtgm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gt2vrvlrzek.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ngfczrok.html

TS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gt2vhbruxmn.html

Java: System.getenv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gt2bxkbwymt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yueranfly.top/Article/details/gt2omnskqfx.html

Ruby: ENV["HOME"]
来源：http://dali.cqqwz.cn/Article/details/gt2klnorfcb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.haohaochexian.top/Article/details/gt2ufaxreoz.html

[M03] 执行外部命令
来源：http://dali.sxryk.cn/Article/details/gt2llmumbjx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.vqdsnc.cn/Article/details/gt2yqrdzonh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hongshengwenyu.top/Article/details/gt2ileieqbc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gt2ngcphkek.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gt2lryyvmqc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aizwys.cn/Article/details/gt2qlyvuvtf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sysykeji.top/Article/details/gt2ynkcxndz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gaohongyu789.top/Article/details/gt2hubomenb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xuetiantiany.cn/Article/details/gt2ggddwkmk.html

[M04] 获取当前工作目录
来源：http://dali.sysykeji.top/Article/details/gt2bfxzpvsk.html

Py:   os.getcwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2yiefqart.html

PHP:  getcwd();
来源：http://dali.chenjidiqi.icu/Article/details/gt2bayglddb.html

JS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2eljugjfm.html

TS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qrymwrxo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gotoacloud.top/Article/details/gt2eikmxosy.html

Go:   os.Getwd()
来源：http://dali.ppjwa.cn/Article/details/gt2jygjswio.html

Ruby: Dir.pwd
来源：http://dali.sweek.top/Article/details/gt2cppeyigu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnxiangtu.top/Article/details/gt2emfpgvli.html

[M05] 设置退出码
来源：http://dali.ybcxt.top/Article/details/gt2etrvjboi.html

Py:   sys.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2iardeatc.html

PHP:  exit(1);
来源：http://dali.andypj.xyz/Article/details/gt2lbghntom.html

JS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2gjugpsho.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gt2wybnfkao.html

Java: System.exit(1)
来源：http://dali.yongpay.top/Article/details/gt2ifbqekei.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxoxzyo.html

Ruby: exit 1
来源：http://dali.aizwys.cn/Article/details/gt2vxzecell.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgfzy.top/Article/details/gt2podrqjwb.html

[M06] 向标准错误输出
来源：http://dali.snrcjt.cn/Article/details/gt2pdpikaeq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gt2hcibvhjc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ybcxt.top/Article/details/gt2qsvjygea.html

JS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gt2xfqgwzfd.html

TS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gt2rykkxwnk.html

Java: System.err.println("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2akiaxfxy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2eiemdkpl.html

Ruby: warn "err"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gsdzvmaw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuxming.cn/Article/details/gt2epudyjnl.html

[M07] 判断是否为主入口
来源：http://dali.xuanzx.com/Article/details/gt2fvgazooj.html

Py:   if __name__ == "__main__":
来源：http://dali.yongpay.top/Article/details/gt2edbthnwc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aibaodan.cn/Article/details/gt2ynggsnuk.html

JS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gt2rizoylcr.html

TS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gt2sjdpntpm.html

Java: public static void main(String[] args)
来源：http://dali.fzhhl.top/Article/details/gt2ffynuuhm.html

Go:   func main()
来源：http://dali.jqgufenzy.top/Article/details/gt2cwyhuzbc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuxming.cn/Article/details/gt2dhejvmnd.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258.top/Article/details/gt2nhxwswqz.html

[M08] 获取系统与运行时信息
来源：http://dali.cqqwz.cn/Article/details/gt2eaushter.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhoulong.xyz/Article/details/gt2qkuhhcdg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cqqwz.cn/Article/details/gt2iezjihrf.html

JS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gt2utvincxf.html

TS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gt2odrisnha.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yueranfly.top/Article/details/gt2pnwonkff.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hongshengwenyu.top/Article/details/gt2jazishai.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shuidangran.top/Article/details/gt2eoctonsr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.0kj1m.cn/Article/details/gt2gxajkyai.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2ciwiephe.html

N. 数据结构与算法
来源：http://dali.cdnleiting.top/Article/details/gt2lhglcahy.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2khzvbahf.html

[N01] 二分查找（有序数组）
来源：http://dali.meibo888.top/Article/details/gt2udxztrpe.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2yhejkuxg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cucudq.cn/Article/details/gt2bgkjzlsk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gt2ynyfeybb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gt2rgkilxha.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2euoltccb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2isrmnfpb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258.top/Article/details/gt2pwlehsmj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2hkrxnwlr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.fzhhl.top/Article/details/gt2omrkmmlg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gt2higynpra.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgfzy.top/Article/details/gt2foohkdnd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cbdwpcpl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gt2uhzstlcs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yongpay.top/Article/details/gt2wurdjvzf.html

Go:   slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2nmjuglgg.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gt2deygegey.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.feifeiyinyue.top/Article/details/gt2cmdzejyv.html

[N03] 快速排序（分治示例）
来源：http://dali.redwolf501.top/Article/details/gt2fovddtjr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangdashe.top/Article/details/gt2wnetfigz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fengsongda.top/Article/details/gt2acabbdow.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gt2gwbdqsgl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gt2zbmmlfqh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuetiantiany.cn/Article/details/gt2wpwyobke.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.bjfxy.top/Article/details/gt2akyameqa.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jlsjyb.cn/Article/details/gt2bgtvrqbz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.fzhhl.top/Article/details/gt2kmewljzp.html

[N04] 斐波那契数列
来源：http://dali.jinqigfzy.top/Article/details/gt2bkourfoq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gt2hdxipzbi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gt2qxaqmccn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gt2goafheik.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gt2ujdkaugw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ydzc1.top/Article/details/gt2yjaavtzu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.quarkkingdee.top/Article/details/gt2nztdajlq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gt2pwytqcff.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2emmeitru.html

[N05] 最大公约数
来源：http://dali.sufxvd.cn/Article/details/gt2xmfsgmga.html

Py:   math.gcd(a, b)
来源：http://dali.sxryk.cn/Article/details/gt2skfkattn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.havefunace.top/Article/details/gt2frsataef.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nafbkxtg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gt2pgezeiuf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxinkj.top/Article/details/gt2wodajtvl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aibaodan.cn/Article/details/gt2kxyguyon.html

Ruby: a.gcd(b)
来源：http://dali.zhengqikj.top/Article/details/gt2ceoscwnh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cdnleiting.top/Article/details/gt2iwqirkes.html

[N06] 判断回文字符串
来源：http://dali.xuanzx.com/Article/details/gt2spjfzrrq.html

Py:   s == s[::-1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2lgwijlky.html

PHP:  $s === strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2atahrryr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gt2vnyzlovh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gt2qttxxqhg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shzxlz.cn/Article/details/gt2ayjlshsl.html

Go:   // 双指针从两端比较
来源：http://dali.zhongyouzk.top/Article/details/gt2vmcdscox.html

Ruby: s == s.reverse
来源：http://dali.gotoacloud.top/Article/details/gt2pxwwerbu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gt2skwyfnxf.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgfzy.top/Article/details/gt2pgjbdcev.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xinyue.icu/Article/details/gt2fkywunvk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fajcnzsu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2emozitor.html

TS:   // 手写 Map<string, number>
来源：http://dali.jianghu66.top/Article/details/gt2fgllbwry.html

Java: // 手写 HashMap
来源：http://dali.ybcxt.top/Article/details/gt2wqstvbym.html

Go:   // 手写 map[int]int
来源：http://dali.pycfn.com/Article/details/gt2ogfsprho.html

Ruby: // 手写 Hash
来源：http://dali.hysaishi.cn/Article/details/gt2ejlsgftd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cashguo.top/Article/details/gt2oojwnwze.html

[N08] 生成全排列
来源：http://dali.mhx1999.top/Article/details/gt2qjaegydi.html

Py:   itertools.permutations(arr)
来源：http://dali.nwbrower.top/Article/details/gt2liykoeik.html

PHP:  // 手写递归交换
来源：http://dali.ivvv.top/Article/details/gt2cpxufwbu.html

JS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gt2xsajspro.html

TS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kmqwjmuh.html

Java: // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gt2dnvrkped.html

Go:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gt2ybkxfnph.html

Ruby: arr.permutation.to_a
来源：http://dali.quarkkingdee.top/Article/details/gt2hhuldxtq.html

C#:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2ubqtyeof.html

[N09] 栈与队列
来源：http://dali.bjfxy.top/Article/details/gt2rcoefgqc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxinkj.top/Article/details/gt2eiihnbms.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gt2mgqdoqkd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gt2tjwblxzr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yueranfly.top/Article/details/gt2muapzrwb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guowangkeji.top/Article/details/gt2vqkgpvvu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.iojbl.cn/Article/details/gt2rsvqdkds.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gt2zapntzpo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cqqwz.cn/Article/details/gt2bvunvwis.html

[N10] 链表节点定义
来源：http://dali.chenlongwang.top/Article/details/gt2qevpxwfl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pycfn.com/Article/details/gt2uerljhfo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ivvv.top/Article/details/gt2byxbcqtv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj202588.top/Article/details/gt2ttuxwukx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.andypj.xyz/Article/details/gt2yrsftwnt.html

Java: class Node { int v; Node next; }
来源：http://dali.zhixingplan.top/Article/details/gt2wepjcwyn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shangyingyoupin.top/Article/details/gt2swnrumwi.html


<!-- 参考信息 -->