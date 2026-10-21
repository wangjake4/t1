代发 wailian999

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjncpijk.html

Go:   json.Marshal(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtfsffnrdl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nwbrower.top/Article/details/gtwipkkzwi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sysykeji.top/Article/details/gtecxtvewb.html

[K02] JSON 字符串转对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvgkyxhuw.html

Py:   json.loads(s)
来源：http://dali.nanxinkj.top/Article/details/gtjfdtgudu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.quarkkingdee.top/Article/details/gtirjzwgnp.html

JS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtvbugewub.html

TS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtdntejmpt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.smart0.xyz/Article/details/gtfrjeytbh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gtrgzecoep.html

Ruby: JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gtterdoyvr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aizwys.cn/Article/details/gtbusuqbml.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjcoeolr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gtsczunlfz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gtrormydln.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gtikipjvyg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gtntbfesjk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtzeraaird.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.daxiang520.top/Article/details/gtvfneehue.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zdqjudy.top/Article/details/gtbztepwhi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteiavmgta.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gtmjukdjqw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yonumen.top/Article/details/gtbkejporq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xziqi.cn/Article/details/gtwajwxooa.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gtgfsgnwaz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtluolmyht.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jianghu66.top/Article/details/gtxvquklyy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gzhubu.top/Article/details/gtcbdumjvh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gtjkcisnzf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.mhx1999.top/Article/details/gtrxkcewak.html

[K05] 深拷贝对象
来源：http://dali.guowangkeji.top/Article/details/gtyhaojjre.html

Py:   copy.deepcopy(obj)
来源：http://dali.fengsongda.top/Article/details/gtaxemdynf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tian-w.cn/Article/details/gtztdnxydk.html

JS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtqolqefnk.html

TS:   structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gtoefziknl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ppjwa.cn/Article/details/gtdznurbah.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.andypj.xyz/Article/details/gtwczbcvpu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jyoumei.cn/Article/details/gtggibanrv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gtsabcjbgw.html

[K06] 解析 URL 查询串
来源：http://dali.meibo888.top/Article/details/gtugnktbue.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gtbwebtbwy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ybcxt.top/Article/details/gtxuutxwob.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aizwys.cn/Article/details/gtmzfdfclq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gtgydlgvqm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zdqjudy.top/Article/details/gtkmnomwhs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gtnfopnvpr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtjcvtwbuf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtnnchaxfv.html

[K07] 进制转换
来源：http://dali.jinqigfzy.top/Article/details/gtjiuimmci.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtjsfjennx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.meibo888.top/Article/details/gtlgnrwfry.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtuskrkgdd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtxtymvmlh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gthzblxuic.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.kuanghao11.cn/Article/details/gtgyephnoe.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fengsongda.top/Article/details/gthgqpdxkj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtmascxftr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ivvv.top/Article/details/gtnuotsysg.html

Py:   pickle.dumps(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtkvommkic.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tianlin.xyz/Article/details/gtetsjgqvk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gtumgpythm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gtfqqvhrzv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgfzy.top/Article/details/gtoasbdjkr.html

Go:   encoding/gob
来源：http://dali.aibaodan.cn/Article/details/gtwifpfeln.html

Ruby: Marshal.dump(obj)
来源：http://dali.jiagoushi.top/Article/details/gtjreretuh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gtpybopfmh.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtqoujebmp.html

L. 网络请求
来源：http://dali.aibaodan.cn/Article/details/gtmzwbzbwu.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtinyrxupy.html

[L01] 发送 GET 请求
来源：http://dali.chenjidiqi.icu/Article/details/gtemvgwmhv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangtech.top/Article/details/gtugyrgsyn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ppjwa.cn/Article/details/gtcxochnwm.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfbhnqjy.html

TS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gttyhmzkmu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.feifeiyinyue.top/Article/details/gttteeivsh.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenzaomai.com/Article/details/gtaunblfak.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuanzhike.top/Article/details/gtrtoiragw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jyoumei.cn/Article/details/gtogoebwlz.html

[L02] 发送 POST JSON
来源：http://dali.c1oappe.top/Article/details/gtimrruykt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gtdvfmioai.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigufen.top/Article/details/gtkpgyotpl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gtwiqripqm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gtikqrihxf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yueranfly.top/Article/details/gtdckspoan.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.svipenyu.cn/Article/details/gtccwcdafc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumqknfkz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xuetiantiany.cn/Article/details/gttipkhujn.html

[L03] 设置自定义请求头
来源：http://dali.c1oappe.top/Article/details/gtrgpoorsi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xziqi.cn/Article/details/gtrbhpoqhk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nwbrower.top/Article/details/gtjuxyrulw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gtxislogry.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtimcxxfhy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinghuilouyu.cn/Article/details/gteoramvxw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gtrswcefah.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnqzz.top/Article/details/gtubfomuvk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gtoebzhecp.html

[L04] 设置超时
来源：http://dali.zdqjudy.top/Article/details/gtsdpwsafk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ehwqpu.com/Article/details/gtfrtduuet.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.9152youxi.cn/Article/details/gtmuhszrff.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gtxzbyaxqs.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gtilrgnbpk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ivvv.top/Article/details/gtbxdxvjvt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhoulong.xyz/Article/details/gtlnkekayp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.havefunace.top/Article/details/gtrlevewcb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.haohaochexian.top/Article/details/gtgcaonhqc.html

[L05] 上传文件（multipart）
来源：http://dali.shzxlz.cn/Article/details/gtlaibsisx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yvedp.cn/Article/details/gtfdonjrcg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhoulong.xyz/Article/details/gtyjnmpoto.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtfpntjmxh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gtevinqete.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cashguo.top/Article/details/gtouzzviih.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xziqi.cn/Article/details/gtxqucagop.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.0kj1m.cn/Article/details/gtxstwrlan.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnqzz.top/Article/details/gtusjczujk.html

[L06] 解析响应为 JSON
来源：http://dali.pycfn.com/Article/details/gtrqfpwyni.html

Py:   resp.json()
来源：http://dali.mhx1999.top/Article/details/gtjxyzeewj.html

PHP:  json_decode($body, true);
来源：http://dali.svipenyu.cn/Article/details/gtqrgvoexr.html

JS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gtkdiiciex.html

TS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gtkkgtzvoj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.mhx1999.top/Article/details/gtoouikfuz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhengqikj.top/Article/details/gtevwhnjgr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xinyue.icu/Article/details/gtexhppmhh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gtnadftgui.html

[L07] 处理 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gtajbvxpmr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ivvv.top/Article/details/gtpsghxnlv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtcnkfujss.html

JS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gtfpwcntvy.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gtznjokhpv.html

Java: resp.statusCode()
来源：http://dali.mhx1999.top/Article/details/gtfixmdlkj.html

Go:   resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gtlvuiitlf.html

Ruby: resp.code.to_i
来源：http://dali.bjfxy.top/Article/details/gtviccexrj.html

C#:   (int)resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gttxozoovf.html

[L08] 并发请求多个地址
来源：http://dali.birdmap.top/Article/details/gtopwlcrkj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.quarkkingdee.top/Article/details/gtqsjaeypp.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhixingplan.top/Article/details/gtqtizekrl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtcwpjoxoo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gthvgyaagm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuetiantiany.cn/Article/details/gtybibotky.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgfzy.top/Article/details/gtxtvrxskm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ehwqpu.com/Article/details/gtamyuhfol.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sxryk.cn/Article/details/gtlmycpquw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtmtfiwddy.html

M. 命令行 / 进程 / 环境
来源：http://dali.guannengcc.top/Article/details/gtbfoqwysd.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtnpvotjef.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtblgpnjhg.html

Py:   sys.argv[1:]
来源：http://dali.9152youxi.cn/Article/details/gtbjecsopl.html

PHP:  $argv;  $argc;
来源：http://dali.daria6918.cn/Article/details/gtakyzthsd.html

JS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtgaomuxcv.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gtergroiya.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhcxghwh.html

Go:   os.Args[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gtacrbsxsd.html

Ruby: ARGV
来源：http://dali.cashguo.top/Article/details/gthaikqasr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gtfzbapktl.html

[M02] 读取环境变量
来源：http://dali.jqgfzy.top/Article/details/gtpjztvdqi.html

Py:   os.environ.get("HOME")
来源：http://dali.ydzc1.top/Article/details/gtjvtbwfjh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gtdhhvpmqt.html

JS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gtnorxpmnl.html

TS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtarglnwff.html

Java: System.getenv("HOME")
来源：http://dali.cucudq.cn/Article/details/gtkbwkkqri.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtiswfnvnb.html

Ruby: ENV["HOME"]
来源：http://dali.hongshengwenyu.top/Article/details/gtihgipkrr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtalskgtao.html

[M03] 执行外部命令
来源：http://dali.yanxiufei.cn/Article/details/gtryjgvmbo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhixingplan.top/Article/details/gtuxhmwuqq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ydzc1.top/Article/details/gtgjzkozci.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhzbqlcl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gtnhdqpvpl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnqzz.top/Article/details/gthsaiizry.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsthmfubh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258.top/Article/details/gteeyppoep.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yueranfly.top/Article/details/gtkxfawkye.html

[M04] 获取当前工作目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gterzfynbv.html

Py:   os.getcwd()
来源：http://dali.andypj.xyz/Article/details/gtpkxoemmw.html

PHP:  getcwd();
来源：http://dali.quarkkingdee.top/Article/details/gtinirixfe.html

JS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gtpnirzmqx.html

TS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gtgjfcnyxb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tianlin.xyz/Article/details/gtlqsvvoxk.html

Go:   os.Getwd()
来源：http://dali.jyoumei.cn/Article/details/gtsfwemnem.html

Ruby: Dir.pwd
来源：http://dali.fzhhl.top/Article/details/gtsnydlssf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhiwuduotai.top/Article/details/gtmdwyjryn.html

[M05] 设置退出码
来源：http://dali.sweek.top/Article/details/gtsekxtlte.html

Py:   sys.exit(1)
来源：http://dali.sxryk.cn/Article/details/gttgaxlmkk.html

PHP:  exit(1);
来源：http://dali.gogol.net.cn/Article/details/gtklbvfxmj.html

JS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtwlqjexsx.html

TS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtcurkmgkm.html

Java: System.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtmmqxwfrk.html

Go:   os.Exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtxvnapunn.html

Ruby: exit 1
来源：http://dali.xziqi.cn/Article/details/gtsquexquf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.feifeiyinyue.top/Article/details/gtzaobkbzy.html

[M06] 向标准错误输出
来源：http://dali.zhongyouzk.top/Article/details/gtrajpshza.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gtvrgtjxkm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258888.top/Article/details/gtenrimvnb.html

JS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtqdfnkuri.html

TS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gtmmbabbla.html

Java: System.err.println("err")
来源：http://dali.cucudq.cn/Article/details/gtikeywype.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gtxcvijlac.html

Ruby: warn "err"
来源：http://dali.redwolf501.top/Article/details/gtywkbpidw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenzaomai.com/Article/details/gtbjguecjz.html

[M07] 判断是否为主入口
来源：http://dali.jlsjyb.cn/Article/details/gtpqlflvmm.html

Py:   if __name__ == "__main__":
来源：http://dali.cashguo.top/Article/details/gthkqlkbcu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.bjfxy.top/Article/details/gthfxqiphp.html

JS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gtjcglyofh.html

TS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gtygmxqukp.html

Java: public static void main(String[] args)
来源：http://dali.zhengqikj.top/Article/details/gtymoxykpo.html

Go:   func main()
来源：http://dali.zdqjudy.top/Article/details/gtisahdxij.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjahrzfsh.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigufen.top/Article/details/gtdvsxiime.html

[M08] 获取系统与运行时信息
来源：http://dali.ehwqpu.com/Article/details/gtwngbjmmh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yonumen.top/Article/details/gtaxaadwid.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.quarkkingdee.top/Article/details/gtkuzttewo.html

JS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gtpfjmegrl.html

TS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtshohiopw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.andypj.xyz/Article/details/gtjoxggqlw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnqzz.top/Article/details/gthegcnxwd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.redwolf501.top/Article/details/gthbtbsjcr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cqqwz.cn/Article/details/gtyikrdquw.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtwegywyrn.html

N. 数据结构与算法
来源：http://dali.jqgfzy.top/Article/details/gtwjsmnbij.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtzflqtlpl.html

[N01] 二分查找（有序数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbjzejfy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtkygbjsbj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yongpay.top/Article/details/gtmwxleine.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gtgmorvans.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuanzhike.top/Article/details/gtmqypnrlt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrlzntqk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtyrxpvich.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shangyingyoupin.top/Article/details/gtbbtrirwj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtmblopbdb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.c1oappe.top/Article/details/gtznvpbyxh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gtdknhkvma.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yongpay.top/Article/details/gtghlrwunj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gtkxhrmqpb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gtzkwoxxix.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.snrcjt.cn/Article/details/gtvsdzzpkr.html

Go:   slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gtnczaltzr.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrmwzmrx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aizwys.cn/Article/details/gtccqenghb.html

[N03] 快速排序（分治示例）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygvzujrl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.9152youxi.cn/Article/details/gtzzacebsv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jlsjyb.cn/Article/details/gttnstflda.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ehwqpu.com/Article/details/gtxjfdduic.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gtevrvbnqy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzsvkzwky.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sxryk.cn/Article/details/gtiiabmfin.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ehwqpu.com/Article/details/gtmnkuoowz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ybcxt.top/Article/details/gtxlikcmto.html

[N04] 斐波那契数列
来源：http://dali.c1oappe.top/Article/details/gtqxymizxk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.fengsongda.top/Article/details/gtgioeohzn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtwxrpcnur.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtfqrolbpq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtcuclhkxj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.iojbl.cn/Article/details/gtmcchmogz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuanzhike.top/Article/details/gtmmrphaea.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtlvuavjjf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtiaaoprpb.html

[N05] 最大公约数
来源：http://dali.jqgufenzy.top/Article/details/gtjbcihlcn.html

Py:   math.gcd(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtbinjxqwb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ehwqpu.com/Article/details/gtcbqetgwq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gtkcqlvteh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gtwhdmclgo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gthpphuukg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yongpay.top/Article/details/gtrajjpfua.html

Ruby: a.gcd(b)
来源：http://dali.sufxvd.cn/Article/details/gthlyptfxg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daria6918.cn/Article/details/gtvtowlwda.html

[N06] 判断回文字符串
来源：http://dali.sufxvd.cn/Article/details/gtyzekowan.html

Py:   s == s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gtxpbfndix.html

PHP:  $s === strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtophiixel.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtuvkiomhh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtmkcgqxfd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ppjwa.cn/Article/details/gtotxflffc.html

Go:   // 双指针从两端比较
来源：http://dali.jiagoushi.top/Article/details/gtmclfbuwm.html

Ruby: s == s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtnomlbdxq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gtbrkdzhpx.html

[N07] 两数之和（返回下标）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzqjrxwt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258.top/Article/details/gtmdmifidw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sweek.top/Article/details/gtkfcwunbn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dianchejie.cn/Article/details/gtyjpgiupt.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuxming.cn/Article/details/gtlhezrtke.html

Java: // 手写 HashMap
来源：http://dali.zhiwuduotai.top/Article/details/gtmmubxoea.html

Go:   // 手写 map[int]int
来源：http://dali.c1oappe.top/Article/details/gtbbfxhpwe.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmefnjndt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fzhhl.top/Article/details/gterqatzjp.html

[N08] 生成全排列
来源：http://dali.xuanzx.com/Article/details/gtzxjouvda.html

Py:   itertools.permutations(arr)
来源：http://dali.jiagoushi.top/Article/details/gtsfgfkgfq.html

PHP:  // 手写递归交换
来源：http://dali.jiagoushi.top/Article/details/gtwbhojqio.html

JS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtoczolknl.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtyfefgbbs.html

Java: // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtkakwrebi.html

Go:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtmwlddyja.html

Ruby: arr.permutation.to_a
来源：http://dali.yanxiufei.cn/Article/details/gtfagyhxtv.html

C#:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtvhamqlfe.html

[N09] 栈与队列
来源：http://dali.yuxming.cn/Article/details/gtstuaqmqz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigufen.top/Article/details/gtkadasjbc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtzoydvyta.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgzjnqbh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zdqjudy.top/Article/details/gttwixzhne.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ivvv.top/Article/details/gtomampomu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuetiantiany.cn/Article/details/gtvegojarb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gtohgtpeko.html


<!-- 参考信息 -->