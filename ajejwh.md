代发 wailian999

[K02] JSON 字符串转对象
来源：http://dali.hnxiangtu.top/Article/details/gt2uoqymfgb.html

Py:   json.loads(s)
来源：http://dali.daria6918.cn/Article/details/gt2hquvtpbu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shzxlz.cn/Article/details/gt2gnedyvxx.html

JS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cozurrgq.html

TS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gt2xiwehvnp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gt2wehotpnt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gt2nnfegryr.html

Ruby: JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2uuinlvhy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2gktvbbxe.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jqgufenzy.top/Article/details/gt2yyniximg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gt2xxqzjodn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gt2srghxpop.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wihwsuqg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zzzmxxyr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2yydslvhw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxinkj.top/Article/details/gt2sluetdmd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2qpetuyvu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jianghu66.top/Article/details/gt2bmsookvf.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258888.top/Article/details/gt2rrayhttn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuxming.cn/Article/details/gt2dqazhpzh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigfzy.top/Article/details/gt2dktmfmjp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gt2eyzymhmb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gt2pvsifydg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gt2wpfkfhum.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gt2knlmwxqs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gt2jnijutnj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gzhubu.top/Article/details/gt2wlhddhiy.html

[K05] 深拷贝对象
来源：http://dali.316326.xyz/Article/details/gt2fhzdgovx.html

Py:   copy.deepcopy(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wxstxtbz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangshuangyany.cn/Article/details/gt2olywntra.html

JS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gt2buqlpxvw.html

TS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2znsoxnmv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ntrpgerg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xziqi.cn/Article/details/gt2lwhttfuw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fengsongda.top/Article/details/gt2adwlaaco.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tianlin.xyz/Article/details/gt2wijopvqs.html

[K06] 解析 URL 查询串
来源：http://dali.nanxuanxn.top/Article/details/gt2thunuuim.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gt2aukgxvpo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jyoumei.cn/Article/details/gt2jtuadhhs.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gt2ukpinduv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gt2eepfvoqk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zdqjudy.top/Article/details/gt2dkcyuxbn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gt2rriagazn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gt2rlmyeulv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2mtmxfzzl.html

[K07] 进制转换
来源：http://dali.chenlongwang.top/Article/details/gt2sawkxzvh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2uoxbcuxc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangshuangyany.cn/Article/details/gt2xlotiwrk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gt2ltfmmugn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ofhrctua.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2sjuwzckc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hfpthk.cn/Article/details/gt2qzruuufl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uypntpdy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bhpnrgix.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenlongwang.top/Article/details/gt2gmkktkwp.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpwwnby.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.316326.xyz/Article/details/gt2pmyrcaas.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gt2hdtbtugb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gt2arialnuf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ybcxt.top/Article/details/gt2hupvagww.html

Go:   encoding/gob
来源：http://dali.gzhubu.top/Article/details/gt2mqpwuayq.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sgrsyisj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hammf.cn/Article/details/gt2caymcldp.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2nhekotiu.html

L. 网络请求
来源：http://dali.ydzc1.top/Article/details/gt2psljituz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2dqfdlzdx.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cgpeizgj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gzhubu.top/Article/details/gt2rvzvuzim.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guowangkeji.top/Article/details/gt2ehvgmhpn.html

JS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gt2ksyzpwki.html

TS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bldweoaw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.snrcjt.cn/Article/details/gt2dzkqlstv.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfpqatm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zreszklp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2nqoeorns.html

[L02] 发送 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gt2rnrvexzr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gt2aadwwffe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sysykeji.top/Article/details/gt2xdmtsvev.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gt2dcvnvdim.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gt2oqxvqvpl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daria6918.cn/Article/details/gt2ggtqrffy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shangyingyoupin.top/Article/details/gt2nbkunawa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.wangshuangyany.cn/Article/details/gt2daiwafkp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jlsjyb.cn/Article/details/gt2pwyvlgqn.html

[L03] 设置自定义请求头
来源：http://dali.wangdashe.top/Article/details/gt2hcqpofgt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuanzhike.top/Article/details/gt2buynivpb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ydzc1.top/Article/details/gt2fvjhcorl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gt2awclutgo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gt2ktstngrh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fengsongda.top/Article/details/gt2swouaeol.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gt2jkpbhnzo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cdnleiting.top/Article/details/gt2nsjrhmit.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gt2rwypaeez.html

[L04] 设置超时
来源：http://dali.0kj1m.cn/Article/details/gt2cxfveven.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xylfe.cn/Article/details/gt2qqwdclqa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.aibaodan.cn/Article/details/gt2wqzfajjx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gt2xztfnowa.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gt2jnbtxiua.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zdqjudy.top/Article/details/gt2ydmvzeps.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.vqdsnc.cn/Article/details/gt2qbctipxi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.havefunace.top/Article/details/gt2clmgqzkj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhixingplan.top/Article/details/gt2qitxgbns.html

[L05] 上传文件（multipart）
来源：http://dali.nanxuanxn.top/Article/details/gt2fgekebwk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.bjfxy.top/Article/details/gt2dicegpjz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzepgks.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yongpay.top/Article/details/gt2lwgbmwxq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gt2gagaybib.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.daxiang520.top/Article/details/gt2qxstrfzc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fzhhl.top/Article/details/gt2iertwfpt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zycfv.cn/Article/details/gt2yakhltgu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2ppjwmprz.html

[L06] 解析响应为 JSON
来源：http://dali.ppjwa.cn/Article/details/gt2uwtehhsd.html

Py:   resp.json()
来源：http://dali.snrcjt.cn/Article/details/gt2fzoustvn.html

PHP:  json_decode($body, true);
来源：http://dali.sxryk.cn/Article/details/gt2cewxrcui.html

JS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gt2ufugaild.html

TS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gt2fynqpvvb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yueranfly.top/Article/details/gt2ghdcjosx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.smart0.xyz/Article/details/gt2voevnung.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tnmyimhu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cucudq.cn/Article/details/gt2cgoznopm.html

[L07] 处理 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gt2wbtlmkcd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.316326.xyz/Article/details/gt2nwctgohe.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhengqikj.top/Article/details/gt2srazfkot.html

JS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gt2umpbqwam.html

TS:   resp.ok;  resp.status
来源：http://dali.yueranfly.top/Article/details/gt2zoqdjsju.html

Java: resp.statusCode()
来源：http://dali.wangdashe.top/Article/details/gt2skljkhiv.html

Go:   resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gt2qtsxvkht.html

Ruby: resp.code.to_i
来源：http://dali.aibaodan.cn/Article/details/gt2jljroxyp.html

C#:   (int)resp.StatusCode
来源：http://dali.andypj.xyz/Article/details/gt2xbxdtqsm.html

[L08] 并发请求多个地址
来源：http://dali.jinqigfzy.top/Article/details/gt2rdmruueb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daxiang520.top/Article/details/gt2mmlqibqg.html

PHP:  curl_multi_init() 系列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hhcippyw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gt2vbydwcvz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gt2hqpdihog.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnqzz.top/Article/details/gt2uqyuxeru.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gogol.net.cn/Article/details/gt2gkjbhfeq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zdqjudy.top/Article/details/gt2hlnbjprk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tanke756.top/Article/details/gt2satxrwva.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2qhnwzzwg.html

M. 命令行 / 进程 / 环境
来源：http://dali.hywenlv.cn/Article/details/gt2vitzrxmi.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gnhayknj.html

[M01] 读取命令行参数
来源：http://dali.xinyue.icu/Article/details/gt2lyutvjkd.html

Py:   sys.argv[1:]
来源：http://dali.yvedp.cn/Article/details/gt2hzbktwkq.html

PHP:  $argv;  $argc;
来源：http://dali.dianchejie.cn/Article/details/gt2yjabrboh.html

JS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gt2sdtuyibh.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gt2byizppaa.html

Java: args 数组（main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gt2mqwhpymw.html

Go:   os.Args[1:]
来源：http://dali.jinqigufen.top/Article/details/gt2rpawtvtl.html

Ruby: ARGV
来源：http://dali.gotoacloud.top/Article/details/gt2hjakckhf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gt2xamqoojh.html

[M02] 读取环境变量
来源：http://dali.yonumen.top/Article/details/gt2lzatcnrl.html

Py:   os.environ.get("HOME")
来源：http://dali.xylfe.cn/Article/details/gt2hdhlixpg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gt2broatwpd.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jownmmlq.html

TS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gt2nytcwyvo.html

Java: System.getenv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fzzaauyd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2nohzyrtg.html

Ruby: ENV["HOME"]
来源：http://dali.316326.xyz/Article/details/gt2gbamzeyn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nwbrower.top/Article/details/gt2cutfkzne.html

[M03] 执行外部命令
来源：http://dali.ybcxt.top/Article/details/gt2ttfovcoc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vwofifru.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.haohaochexian.top/Article/details/gt2ejrlswmt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj202588.top/Article/details/gt2zmytcevk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gt2mnofvudz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258888.top/Article/details/gt2kqqaymqj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hywenlv.cn/Article/details/gt2ibvamnhs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yvedp.cn/Article/details/gt2wrcegkia.html

C#:   Process.Start("ls", "-l");
来源：http://dali.feifeiyinyue.top/Article/details/gt2ehajfqcs.html

[M04] 获取当前工作目录
来源：http://dali.jqgfzy.top/Article/details/gt2kcrfsakc.html

Py:   os.getcwd()
来源：http://dali.yuanzhike.top/Article/details/gt2piykeqnh.html

PHP:  getcwd();
来源：http://dali.wangdashe.top/Article/details/gt2cfoefzuz.html

JS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mstknkzg.html

TS:   process.cwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ztayfiaj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jyoumei.cn/Article/details/gt2joegdvkn.html

Go:   os.Getwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wxxrjbds.html

Ruby: Dir.pwd
来源：http://dali.shuidangran.top/Article/details/gt2xciuxssl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cashguo.top/Article/details/gt2efdruzhd.html

[M05] 设置退出码
来源：http://dali.aizwys.cn/Article/details/gt2ozoayytr.html

Py:   sys.exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2cavbsgjs.html

PHP:  exit(1);
来源：http://dali.jqgfzy.top/Article/details/gt2gtieuawu.html

JS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gt2cnqbmosm.html

TS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2vcbmefnp.html

Java: System.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2hlbnoowp.html

Go:   os.Exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2urbotqnf.html

Ruby: exit 1
来源：http://dali.zhongyouzk.top/Article/details/gt2pqalmxef.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tianlin.xyz/Article/details/gt2tdhnmnsx.html

[M06] 向标准错误输出
来源：http://dali.shzxlz.cn/Article/details/gt2bhwgtjma.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daria6918.cn/Article/details/gt2fjedatdm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sweek.top/Article/details/gt2jpudwqwp.html

JS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gt2wgcwxqyx.html

TS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gt2xpufktty.html

Java: System.err.println("err")
来源：http://dali.cqqwz.cn/Article/details/gt2dbolgfrm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ehwqpu.com/Article/details/gt2sprecwfd.html

Ruby: warn "err"
来源：http://dali.svipenyu.cn/Article/details/gt2fgyxckoo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.meibo888.top/Article/details/gt2aaetyoeu.html

[M07] 判断是否为主入口
来源：http://dali.316326.xyz/Article/details/gt2mlxzzvuc.html

Py:   if __name__ == "__main__":
来源：http://dali.mhx1999.top/Article/details/gt2zzxmporz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gotoacloud.top/Article/details/gt2zfhvgelf.html

JS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gt2zohhwxwj.html

TS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gt2omzpvqga.html

Java: public static void main(String[] args)
来源：http://dali.0kj1m.cn/Article/details/gt2diihlxyv.html

Go:   func main()
来源：http://dali.kuanghao11.cn/Article/details/gt2aujdzipl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aibaodan.cn/Article/details/gt2eulqbehc.html

C#:   static void Main(string[] args)
来源：http://dali.jlsjyb.cn/Article/details/gt2fftlxxco.html

[M08] 获取系统与运行时信息
来源：http://dali.haohaochexian.top/Article/details/gt2psxokhqa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ehwqpu.com/Article/details/gt2onnjfcca.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jianghu66.top/Article/details/gt2zzfktnny.html

JS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gt2xncojpkv.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uelgienl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shzxlz.cn/Article/details/gt2hqcixlpu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnqzz.top/Article/details/gt2zcehewrv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gt2fnifmkxn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xziqi.cn/Article/details/gt2dvwyrlqk.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2mzdvycee.html

N. 数据结构与算法
来源：http://dali.vqdsnc.cn/Article/details/gt2qilusogs.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2cechqarq.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gt2ubawivtu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2oicyjyfd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.smart0.xyz/Article/details/gt2ighzxqqp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jiagoushi.top/Article/details/gt2ivmtoyry.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ryqylsfe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2dakcebug.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2cdxzelln.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zdqjudy.top/Article/details/gt2rotuznts.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2wxaqebso.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.meibo888.top/Article/details/gt2zauoueda.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gt2fppdxjlu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fengsongda.top/Article/details/gt2zambqtgy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gt2pldslryp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kiofjeaz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.mhx1999.top/Article/details/gt2oxwburtt.html

Go:   slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2tbvktqsz.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gt2xfjkahfr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.feifeiyinyue.top/Article/details/gt2gishvhrl.html

[N03] 快速排序（分治示例）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xjpaogfv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sxryk.cn/Article/details/gt2vivrvwra.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ehwqpu.com/Article/details/gt2ylygggki.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gt2udedxaus.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gt2rywhnsti.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.svipenyu.cn/Article/details/gt2cydolyhl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigfzy.top/Article/details/gt2tvllcfzf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangshuangyany.cn/Article/details/gt2csrzixpy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.snrcjt.cn/Article/details/gt2fzrwxigs.html

[N04] 斐波那契数列
来源：http://dali.chenzaomai.com/Article/details/gt2ojbwrgbr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2kerrpntx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gt2wnoengxm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gt2vuamifyk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gt2tmlxgbje.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.guowangkeji.top/Article/details/gt2oieuwicx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shuidangran.top/Article/details/gt2grexyvup.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2jgjbnnai.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gt2ydrumjhp.html

[N05] 最大公约数
来源：http://dali.guannengcc.top/Article/details/gt2bzmfxkfl.html

Py:   math.gcd(a, b)
来源：http://dali.c1oappe.top/Article/details/gt2esspygxj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hammf.cn/Article/details/gt2teywkctl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gt2oxtsdbnw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gt2qgmtcgjr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lcxgpjis.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cucudq.cn/Article/details/gt2lqldzkrz.html

Ruby: a.gcd(b)
来源：http://dali.iojbl.cn/Article/details/gt2rmjffuef.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xinyue.icu/Article/details/gt2vmlwvfwa.html

[N06] 判断回文字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2vitghqei.html

Py:   s == s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gt2idvojhbh.html

PHP:  $s === strrev($s);
来源：http://dali.ivvv.top/Article/details/gt2owdgepxc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gt2hlpxfici.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2jbfpwakj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.havefunace.top/Article/details/gt2tbnffwno.html

Go:   // 双指针从两端比较
来源：http://dali.sxryk.cn/Article/details/gt2qppugyzt.html

Ruby: s == s.reverse
来源：http://dali.yuxming.cn/Article/details/gt2mmwbeinh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gt2bdqbxwyg.html

[N07] 两数之和（返回下标）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tnngafmu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.smart0.xyz/Article/details/gt2ercirvxq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yueranfly.top/Article/details/gt2sjogzrhd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shuidangran.top/Article/details/gt2mhhxywzf.html

TS:   // 手写 Map<string, number>
来源：http://dali.guannengcc.top/Article/details/gt2dmrgbsup.html

Java: // 手写 HashMap
来源：http://dali.kuanghao11.cn/Article/details/gt2vevmkeph.html

Go:   // 手写 map[int]int
来源：http://dali.fzhhl.top/Article/details/gt2frmjgxrl.html

Ruby: // 手写 Hash
来源：http://dali.cashguo.top/Article/details/gt2mkznjbbb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.smart0.xyz/Article/details/gt2ibswfhfx.html

[N08] 生成全排列
来源：http://dali.fengsongda.top/Article/details/gt2pzbajmpj.html

Py:   itertools.permutations(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2nqxkwpjo.html

PHP:  // 手写递归交换
来源：http://dali.redwolf501.top/Article/details/gt2cegivspc.html

JS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2nqudfkee.html

TS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gt2kcdkhmko.html

Java: // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fskijwhq.html

Go:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2weyifzgy.html

Ruby: arr.permutation.to_a
来源：http://dali.gaohongyu789.top/Article/details/gt2yvzmgstb.html

C#:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gt2bjabmcqy.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2duwwcnnr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shzxlz.cn/Article/details/gt2qyedahoo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gt2amjdhzsa.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gt2euvfadff.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnqzz.top/Article/details/gt2vexiauhh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2phwzxsft.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinghuilouyu.cn/Article/details/gt2battcvbt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2jjslhyra.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dianchejie.cn/Article/details/gt2ikolgjld.html

[N10] 链表节点定义
来源：http://dali.guowangkeji.top/Article/details/gt2aekaitrp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lqkopmns.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jianghu66.top/Article/details/gt2azxhapcs.html


<!-- 参考信息 -->