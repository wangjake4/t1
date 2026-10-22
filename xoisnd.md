代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gt2lzzgttka.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xziqi.cn/Article/details/gt2wnhvndxi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gt2xqeyotxg.html

Ruby: JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bmkraell.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daxiang520.top/Article/details/gt2ffvhvxii.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuxming.cn/Article/details/gt2sgswcsry.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gt2ebenxjxh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gt2wgqetiyo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gt2npmpvofg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2uihoupqo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.redwolf501.top/Article/details/gt2dyojbzul.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.quarkkingdee.top/Article/details/gt2yanlumcj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nwbrower.top/Article/details/gt2wcnshtlq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.andypj.xyz/Article/details/gt2gijtuapi.html

[K04] 读取 JSON 文件
来源：http://dali.hnxiangtu.top/Article/details/gt2bzeoftuz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxinkj.top/Article/details/gt2botiunyx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hywenlv.cn/Article/details/gt2aitdifey.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gt2pxafpveu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2gkviavrm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shuidangran.top/Article/details/gt2jkvrtsam.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gt2yhbdvsmf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuxming.cn/Article/details/gt2sakdgdyk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sxryk.cn/Article/details/gt2jjtxcjaq.html

[K05] 深拷贝对象
来源：http://dali.cucudq.cn/Article/details/gt2yxbxjman.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2evfndsbx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gt2vguroeol.html

JS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2iokjbqde.html

TS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gt2pozselvd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258888.top/Article/details/gt2staepsbf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shzxlz.cn/Article/details/gt2akjtzymw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gt2pgpltusi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jlsjyb.cn/Article/details/gt2wzpjlhvs.html

[K06] 解析 URL 查询串
来源：http://dali.yongpay.top/Article/details/gt2lwqjinyt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gt2dquqrqxq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zciisilh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kvbatcgx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gt2nxfdeigu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fengsongda.top/Article/details/gt2nfqjvfbx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gt2sozfajfb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gt2upddaooz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gt2cgeyilzf.html

[K07] 进制转换
来源：http://dali.jinqigufen.top/Article/details/gt2izknuftn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xvwbnidp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sysykeji.top/Article/details/gt2wpefecxz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2xjvtpitf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2prtedxvz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2eqlabmbc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cqqwz.cn/Article/details/gt2apnjhujx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhoulong.xyz/Article/details/gt2qdqnnlzv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2rlinjfao.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj202588.top/Article/details/gt2czpkspxr.html

Py:   pickle.dumps(obj)
来源：http://dali.sxryk.cn/Article/details/gt2kdjgzwxp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2wcaydtbi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gt2oqdijicf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gt2lvoufoho.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhixingplan.top/Article/details/gt2iajdyhsc.html

Go:   encoding/gob
来源：http://dali.fengsongda.top/Article/details/gt2aencgynu.html

Ruby: Marshal.dump(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2cjhhtnmi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gt2zwhqfgkl.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ofzyqtzm.html

L. 网络请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rfofjmdu.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ncvpyjlf.html

[L01] 发送 GET 请求
来源：http://dali.pycfn.com/Article/details/gt2uldafxpg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnqzz.top/Article/details/gt2zwfvhsss.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sweek.top/Article/details/gt2ozwgnhur.html

JS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gt2vmizrima.html

TS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gt2pzbslyyr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhoulong.xyz/Article/details/gt2xkpxdnqk.html

Go:   resp, err := http.Get(url)
来源：http://dali.hysaishi.cn/Article/details/gt2xzgqldyl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nwbrower.top/Article/details/gt2nauttirl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2uedsqdjf.html

[L02] 发送 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xorfxziw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gt2kqimgulz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.vqdsnc.cn/Article/details/gt2qjhyhtlo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gt2hpxijezo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gt2ocrjxpfx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.haohaochexian.top/Article/details/gt2eowjsjzi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yongpay.top/Article/details/gt2deiyhfsk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxnbhoci.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.iojbl.cn/Article/details/gt2pbhqmfls.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qnqfqaio.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.9152youxi.cn/Article/details/gt2qecirlsx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.svipenyu.cn/Article/details/gt2kichexbv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gt2acgdldzu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gt2cpcxkvwj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258888.top/Article/details/gt2wruhidxl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gt2ibhlqhvy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxinkj.top/Article/details/gt2orrkudei.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gt2vrdozjyk.html

[L04] 设置超时
来源：http://dali.redwolf501.top/Article/details/gt2uajtkrvr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj202588.top/Article/details/gt2mwopliqa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cucudq.cn/Article/details/gt2cnlrudha.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2bplbvxle.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gt2iwqurqqa.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cqqwz.cn/Article/details/gt2qvjfmhhw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.redwolf501.top/Article/details/gt2ieiojqca.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258.top/Article/details/gt2mfgktrun.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gaohongyu789.top/Article/details/gt2gtwiehlh.html

[L05] 上传文件（multipart）
来源：http://dali.hongshengwenyu.top/Article/details/gt2kylmhrtq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.iojbl.cn/Article/details/gt2tkocrwyv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.snrcjt.cn/Article/details/gt2mscxoili.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gt2wqvfxzmg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gt2lhiwneye.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aibaodan.cn/Article/details/gt2hqnoizck.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gzhubu.top/Article/details/gt2vlglijfa.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuanzhike.top/Article/details/gt2fzifusvu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2qohoanzg.html

[L06] 解析响应为 JSON
来源：http://dali.wangdashe.top/Article/details/gt2ypynwbix.html

Py:   resp.json()
来源：http://dali.andypj.xyz/Article/details/gt2yohocomw.html

PHP:  json_decode($body, true);
来源：http://dali.fengsongda.top/Article/details/gt2ilvzpfqp.html

JS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gt2gcsdvafb.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmduadfy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gt2jrixxokd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zyelqzty.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shangyingyoupin.top/Article/details/gt2eehcydbt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.0kj1m.cn/Article/details/gt2rkqtvbfu.html

[L07] 处理 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gt2dkjfpexi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangdashe.top/Article/details/gt2ghywgurb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xziqi.cn/Article/details/gt2ovpafrhk.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gt2hpmqljhb.html

TS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gt2kmoxlffu.html

Java: resp.statusCode()
来源：http://dali.fengsongda.top/Article/details/gt2rprsfcml.html

Go:   resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gt2hvltlefy.html

Ruby: resp.code.to_i
来源：http://dali.tian-w.cn/Article/details/gt2pigltxzv.html

C#:   (int)resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gt2vlkmpghb.html

[L08] 并发请求多个地址
来源：http://dali.zycfv.cn/Article/details/gt2uplcoylg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yvedp.cn/Article/details/gt2oczrimzu.html

PHP:  curl_multi_init() 系列
来源：http://dali.haohaochexian.top/Article/details/gt2hfriweaq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gt2ecbfvral.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gt2dduhdtmr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhongyouzk.top/Article/details/gt2qwuicbsh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daria6918.cn/Article/details/gt2voujrfzh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jqgfzy.top/Article/details/gt2grpkqgky.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jyoumei.cn/Article/details/gt2xefvfbop.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2ucxwouhk.html

M. 命令行 / 进程 / 环境
来源：http://dali.hysaishi.cn/Article/details/gt2dsgcpgrw.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2fjkmttsd.html

[M01] 读取命令行参数
来源：http://dali.yueranfly.top/Article/details/gt2zrxiotgs.html

Py:   sys.argv[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qhidrpah.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258888.top/Article/details/gt2wbkfqhvz.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjbinuyp.html

TS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rxqxfnrg.html

Java: args 数组（main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gt2xnazqalc.html

Go:   os.Args[1:]
来源：http://dali.snrcjt.cn/Article/details/gt2lqdzbwtu.html

Ruby: ARGV
来源：http://dali.yonumen.top/Article/details/gt2oswhkpda.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gt2tliqqvfk.html

[M02] 读取环境变量
来源：http://dali.yuxming.cn/Article/details/gt2yebbgges.html

Py:   os.environ.get("HOME")
来源：http://dali.fzhhl.top/Article/details/gt2cyrdcccm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cdnleiting.top/Article/details/gt2jerfdntk.html

JS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gt2gkjqnlvr.html

TS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gt2hmbherxx.html

Java: System.getenv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gt2tmqnyujw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.smart0.xyz/Article/details/gt2fvhgwlhe.html

Ruby: ENV["HOME"]
来源：http://dali.jqgufenzy.top/Article/details/gt2asgiperb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gt2gcgmgayb.html

[M03] 执行外部命令
来源：http://dali.ehwqpu.com/Article/details/gt2mobkerkf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yanxiufei.cn/Article/details/gt2qlkzvzyz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cashguo.top/Article/details/gt2xccehjmk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gt2ulhinkrv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gt2gzokujxn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.redwolf501.top/Article/details/gt2ipdbagqq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xylfe.cn/Article/details/gt2ikibkvwt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aizwys.cn/Article/details/gt2wsuqijrw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jianghu66.top/Article/details/gt2anounouf.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gt2qowyvizi.html

Py:   os.getcwd()
来源：http://dali.jianghu66.top/Article/details/gt2eshufpzn.html

PHP:  getcwd();
来源：http://dali.gotoacloud.top/Article/details/gt2aaaqnccc.html

JS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qyoubkpc.html

TS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gt2rqcnbgxh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gotoacloud.top/Article/details/gt2woacthrm.html

Go:   os.Getwd()
来源：http://dali.hysaishi.cn/Article/details/gt2hegnaxvo.html

Ruby: Dir.pwd
来源：http://dali.zhongyouzk.top/Article/details/gt2aphivrmb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lxzskesl.html

[M05] 设置退出码
来源：http://dali.guowangkeji.top/Article/details/gt2fncypzpd.html

Py:   sys.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2ngtelbki.html

PHP:  exit(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xgbgkmpb.html

JS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2hwjywdgc.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sqqdfkow.html

Java: System.exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2fbbatnls.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gt2odmkesig.html

Ruby: exit 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wuhkhcwf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258888.top/Article/details/gt2njobesqt.html

[M06] 向标准错误输出
来源：http://dali.yvedp.cn/Article/details/gt2zfkpefip.html

Py:   print("err", file=sys.stderr)
来源：http://dali.meibo888.top/Article/details/gt2ldzyudix.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gzhubu.top/Article/details/gt2javcfhjr.html

JS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gt2mipdvimn.html

TS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gt2isydbcpu.html

Java: System.err.println("err")
来源：http://dali.jianghu66.top/Article/details/gt2hqntjnbr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bztumvma.html

Ruby: warn "err"
来源：http://dali.hongshengwenyu.top/Article/details/gt2diryruvv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vsvzdhsq.html

[M07] 判断是否为主入口
来源：http://dali.sweek.top/Article/details/gt2deotelcc.html

Py:   if __name__ == "__main__":
来源：http://dali.tian-w.cn/Article/details/gt2gyvfekka.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pycfn.com/Article/details/gt2tfxyahqe.html

JS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bhmeayqp.html

TS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gt2belzewur.html

Java: public static void main(String[] args)
来源：http://dali.hywenlv.cn/Article/details/gt2mejmabwl.html

Go:   func main()
来源：http://dali.cucudq.cn/Article/details/gt2iuetiqts.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.andypj.xyz/Article/details/gt2ywnpyiwu.html

C#:   static void Main(string[] args)
来源：http://dali.jianghu66.top/Article/details/gt2scvtilum.html

[M08] 获取系统与运行时信息
来源：http://dali.jlsjyb.cn/Article/details/gt2afhwgqbu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.havefunace.top/Article/details/gt2vhdchthw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnqzz.top/Article/details/gt2etkxkdhc.html

JS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gt2cfxshrcx.html

TS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gt2xvbjpcpc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cheryme.top/Article/details/gt2zhcgxzmb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jyoumei.cn/Article/details/gt2tclaxzuh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhiwuduotai.top/Article/details/gt2luabohcr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nukacges.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xtegzprc.html

N. 数据结构与算法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bnwfaguv.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2vssftljd.html

[N01] 二分查找（有序数组）
来源：http://dali.meibo888.top/Article/details/gt2iajqliao.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2hccoxqcs.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gt2amcdfhbe.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xgpczhlz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gt2siavsjhj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2kwjchegd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2wvfswdxz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.redwolf501.top/Article/details/gt2usnrdnay.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2xvrcximi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cheryme.top/Article/details/gt2oobmtasx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jkrigrwn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.andypj.xyz/Article/details/gt2rbircysm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2utfdgqnn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gt2kosqcytw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnxiangtu.top/Article/details/gt2vzpgunfx.html

Go:   slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jkzwfwik.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gt2rjxpoazo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.feifeiyinyue.top/Article/details/gt2cybghxan.html

[N03] 快速排序（分治示例）
来源：http://dali.zdqjudy.top/Article/details/gt2jhetskom.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuetiantiany.cn/Article/details/gt2kkduuwbr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jyoumei.cn/Article/details/gt2famafblz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gt2uibzfctc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gt2nlydzhhu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fzhhl.top/Article/details/gt2fisqypsz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhoulong.xyz/Article/details/gt2knbjyqbl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zdqjudy.top/Article/details/gt2jmynvjhp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxinkj.top/Article/details/gt2azznengs.html

[N04] 斐波那契数列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uatfgowl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gt2odsqldpd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rrunvypg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gt2jkqupwno.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gt2rkkrovaj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zwshwlua.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tanke756.top/Article/details/gt2ygbxecaz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gt2hxyjnnfp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gt2fblkpldd.html

[N05] 最大公约数
来源：http://dali.meibo888.top/Article/details/gt2qnugfqas.html

Py:   math.gcd(a, b)
来源：http://dali.havefunace.top/Article/details/gt2pvomxjzk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.9152youxi.cn/Article/details/gt2fznsporp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gt2whqgbheb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gt2prqrfrbn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cqqwz.cn/Article/details/gt2upbxovrn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mgbjidqg.html

Ruby: a.gcd(b)
来源：http://dali.aibaodan.cn/Article/details/gt2sncspjtr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjhxamop.html

[N06] 判断回文字符串
来源：http://dali.yj20258.top/Article/details/gt2dovngksa.html

Py:   s == s[::-1]
来源：http://dali.sysykeji.top/Article/details/gt2ypdehnmf.html

PHP:  $s === strrev($s);
来源：http://dali.shuidangran.top/Article/details/gt2xodtyviq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uidgofms.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gt2iebpvgvn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cheryme.top/Article/details/gt2iwgmdakc.html

Go:   // 双指针从两端比较
来源：http://dali.jiagoushi.top/Article/details/gt2zqijpill.html

Ruby: s == s.reverse
来源：http://dali.jqgfzy.top/Article/details/gt2cgvmrkqv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gt2vfrwipbo.html

[N07] 两数之和（返回下标）
来源：http://dali.snrcjt.cn/Article/details/gt2xpvpmjsk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.feifeiyinyue.top/Article/details/gt2ilwbdnmw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.316326.xyz/Article/details/gt2xmqhzapq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cheryme.top/Article/details/gt2ysiseyku.html

TS:   // 手写 Map<string, number>
来源：http://dali.xinyue.icu/Article/details/gt2eonvfyrh.html

Java: // 手写 HashMap
来源：http://dali.gotoacloud.top/Article/details/gt2zydxelbw.html

Go:   // 手写 map[int]int
来源：http://dali.jianghu66.top/Article/details/gt2ymlhnuat.html

Ruby: // 手写 Hash
来源：http://dali.zhengqikj.top/Article/details/gt2xxbciswy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zycfv.cn/Article/details/gt2uggisshy.html

[N08] 生成全排列
来源：http://dali.mhx1999.top/Article/details/gt2huzenugo.html

Py:   itertools.permutations(arr)
来源：http://dali.hammf.cn/Article/details/gt2kfjbqxqs.html

PHP:  // 手写递归交换
来源：http://dali.hnqzz.top/Article/details/gt2rivgzsdp.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wiabfnoy.html

TS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2wwvdlqoj.html

Java: // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2olmykfip.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvuthyg.html

Ruby: arr.permutation.to_a
来源：http://dali.yongpay.top/Article/details/gt2kocdpkeq.html

C#:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gt2xbfqcstr.html

[N09] 栈与队列
来源：http://dali.fengsongda.top/Article/details/gt2uskxbufr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigfzy.top/Article/details/gt2onnxkbgu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gt2smgcxpkk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gt2inctzevq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ncakxwmr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sysykeji.top/Article/details/gt2hiylodvv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ehwqpu.com/Article/details/gt2ffabrcsr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2shwmaojp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zycfv.cn/Article/details/gt2ntqnhhgd.html

[N10] 链表节点定义
来源：http://dali.yj202588.top/Article/details/gt2kxqprqrz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shuidangran.top/Article/details/gt2jocwzghn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hywenlv.cn/Article/details/gt2eyjgdhuy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hongshengwenyu.top/Article/details/gt2obsrvhtn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daria6918.cn/Article/details/gt2qsknqqeb.html

Java: class Node { int v; Node next; }
来源：http://dali.zdqjudy.top/Article/details/gt2ajolmxla.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.snrcjt.cn/Article/details/gt2wvollele.html


<!-- 参考信息 -->