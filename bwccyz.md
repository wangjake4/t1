代发 wailian999

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shuidangran.top/Article/details/gtxtzgaaah.html

Go:   json.Marshal(obj)
来源：http://dali.meibo888.top/Article/details/gttbaxrjka.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuetiantiany.cn/Article/details/gtqohbtdeb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sxryk.cn/Article/details/gtyokneaqi.html

[K02] JSON 字符串转对象
来源：http://dali.yongpay.top/Article/details/gthgappvta.html

Py:   json.loads(s)
来源：http://dali.jinqigufen.top/Article/details/gthlympdad.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pycfn.com/Article/details/gthffticwl.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gttinlbezd.html

TS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtqppvwiab.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yongpay.top/Article/details/gtdmzxcawm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvexchwo.html

Ruby: JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtehiykwks.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cqqwz.cn/Article/details/gtxkqlhgfh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.haohaochexian.top/Article/details/gtfkhdzhrf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gtbdkntyog.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gtuwxzcskf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtibdbkdvp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gtzndnoguh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.smart0.xyz/Article/details/gthdmmltlj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jlsjyb.cn/Article/details/gtsgrdycei.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtjarrfobb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hfpthk.cn/Article/details/gtcvlyclyl.html

[K04] 读取 JSON 文件
来源：http://dali.mhx1999.top/Article/details/gtnqbdicgk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtogwnanav.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenzaomai.com/Article/details/gtyhhyftrp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gtyxbrszvo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gtiwlznlaa.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtdjyktprv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gtimiklxbm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gtvdaldpgs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxkndwye.html

[K05] 深拷贝对象
来源：http://dali.cashguo.top/Article/details/gtmghmcouh.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuanzx.com/Article/details/gtgfoehbmh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sxryk.cn/Article/details/gtfnqqdogi.html

JS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtenghekhu.html

TS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtnicxuxzp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.mhx1999.top/Article/details/gtnxdvtipz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxuanxn.top/Article/details/gtlgatsdhr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fengsongda.top/Article/details/gtmcugmnxh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shangyingyoupin.top/Article/details/gtowobsfkc.html

[K06] 解析 URL 查询串
来源：http://dali.aizwys.cn/Article/details/gtwmephuxi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aizwys.cn/Article/details/gthsclvbas.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fengsongda.top/Article/details/gtmncnbwxg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtitfkzrwg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gtxgyqlbow.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fzhhl.top/Article/details/gtqhzquugs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gtrzleudsc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtnatrwhuq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gtfzenpmtf.html

[K07] 进制转换
来源：http://dali.9152youxi.cn/Article/details/gtgvfrqwdu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtkvtlgtlz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shuidangran.top/Article/details/gtaamlluin.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtqrpxurbq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtlqprxasf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtojuhwhbx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tanke756.top/Article/details/gtgasndzmm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gttivddlwc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtjuzhultq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hnxiangtu.top/Article/details/gtcbgytcyv.html

Py:   pickle.dumps(obj)
来源：http://dali.tian-w.cn/Article/details/gtbrzdycqj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cucudq.cn/Article/details/gtevwgkrdv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gtshntrtmn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gtjbafqnwc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fengsongda.top/Article/details/gtmbxtxoow.html

Go:   encoding/gob
来源：http://dali.jiagoushi.top/Article/details/gtoastsjga.html

Ruby: Marshal.dump(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtcazaipqv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gtiagxsltp.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtwcsfmmle.html

L. 网络请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfqdmhjv.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtgmnsoteh.html

[L01] 发送 GET 请求
来源：http://dali.feifeiyinyue.top/Article/details/gtcmqtjujp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenzaomai.com/Article/details/gthfyaitbc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cheryme.top/Article/details/gtswlnzxkv.html

JS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gtmennmtgm.html

TS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrlemcgn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sufxvd.cn/Article/details/gtffrqjjqk.html

Go:   resp, err := http.Get(url)
来源：http://dali.vqdsnc.cn/Article/details/gtlmurmnle.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hongshengwenyu.top/Article/details/gtwnffjvqd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.havefunace.top/Article/details/gtnamvdlpv.html

[L02] 发送 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtqreafgsf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gttbaxfzvy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aizwys.cn/Article/details/gtnqrmmedr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gtlcyujsel.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gtzpnxstwd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jianghu66.top/Article/details/gtlibyncwj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.snrcjt.cn/Article/details/gtciakbhum.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sxryk.cn/Article/details/gtsfdgpqnh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.0kj1m.cn/Article/details/gtctopqmik.html

[L03] 设置自定义请求头
来源：http://dali.tianlin.xyz/Article/details/gtmzxxzzrf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xylfe.cn/Article/details/gtzsgapkjn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aibaodan.cn/Article/details/gtclwlavhq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gtcllexcdl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gtsowdoyer.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hnqzz.top/Article/details/gtfpcxbeqf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gtekdjeogj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fengsongda.top/Article/details/gtctamprci.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gtqhoueirz.html

[L04] 设置超时
来源：http://dali.cheryme.top/Article/details/gthervkgrq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangdashe.top/Article/details/gtyioqnrkr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guannengcc.top/Article/details/gtxakgfdsa.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gtjndcvfsy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gtwlnptpfm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuxming.cn/Article/details/gtsageqqoh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shuidangran.top/Article/details/gtpetqvmmr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gaohongyu789.top/Article/details/gtxzihnmzg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangdashe.top/Article/details/gturacvahd.html

[L05] 上传文件（multipart）
来源：http://dali.nanxuanxn.top/Article/details/gtbvecslvk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xylfe.cn/Article/details/gtxgciders.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zycfv.cn/Article/details/gtpnpfybqj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gtfcsrwxrn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtbivsxiup.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmbaestk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhoulong.xyz/Article/details/gtobshdkdb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.iojbl.cn/Article/details/gtazszospl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtmynhdtlv.html

[L06] 解析响应为 JSON
来源：http://dali.cheryme.top/Article/details/gtutjkwojn.html

Py:   resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtakbaijwq.html

PHP:  json_decode($body, true);
来源：http://dali.gaohongyu789.top/Article/details/gtsvpjftcm.html

JS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gttjbdncep.html

TS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gtnbvlqewu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtdfcqozol.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cashguo.top/Article/details/gtnbajqogx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sysykeji.top/Article/details/gthimpffds.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigfzy.top/Article/details/gtxeefyqav.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtizxkqdnw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.vqdsnc.cn/Article/details/gtceoniyry.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhixingplan.top/Article/details/gtioneeyfv.html

JS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gtvdralopl.html

TS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtorbrvhks.html

Java: resp.statusCode()
来源：http://dali.hywenlv.cn/Article/details/gtzjyiucdd.html

Go:   resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gtcpjmgqyj.html

Ruby: resp.code.to_i
来源：http://dali.jianghu66.top/Article/details/gtbcevadrt.html

C#:   (int)resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gtfyicgjel.html

[L08] 并发请求多个地址
来源：http://dali.sweek.top/Article/details/gtwwwbhhct.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqavtnui.html

PHP:  curl_multi_init() 系列
来源：http://dali.fzhhl.top/Article/details/gtvleivnhu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcghobdmp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtuwqxwykk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.redwolf501.top/Article/details/gtxoayqrkd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.svipenyu.cn/Article/details/gtnzhczdct.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnqzz.top/Article/details/gtavjdsbue.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnqzz.top/Article/details/gtdfcvqgim.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtpjmgkdtp.html

M. 命令行 / 进程 / 环境
来源：http://dali.yangfankeji.com/Article/details/gtqhbmbtze.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtxtqdyxij.html

[M01] 读取命令行参数
来源：http://dali.mhx1999.top/Article/details/gtpeeaamxo.html

Py:   sys.argv[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtsjudewqi.html

PHP:  $argv;  $argc;
来源：http://dali.meibo888.top/Article/details/gtjhlgjqss.html

JS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gtxruhlllq.html

TS:   process.argv.slice(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkmuubuu.html

Java: args 数组（main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gttlofpqft.html

Go:   os.Args[1:]
来源：http://dali.gogol.net.cn/Article/details/gtapdwwexs.html

Ruby: ARGV
来源：http://dali.yanxiufei.cn/Article/details/gtjyqdasqd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gtlenbesaj.html

[M02] 读取环境变量
来源：http://dali.hammf.cn/Article/details/gtkkrrhtpn.html

Py:   os.environ.get("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gttejywndd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gtsvwnybtu.html

JS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gtpyoxhdxd.html

TS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gtfemdhzli.html

Java: System.getenv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtzkqvgday.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtgdvfwyui.html

Ruby: ENV["HOME"]
来源：http://dali.havefunace.top/Article/details/gtwxyarwtf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sysykeji.top/Article/details/gtzdlzvojc.html

[M03] 执行外部命令
来源：http://dali.quarkkingdee.top/Article/details/gtpclywkut.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xinyue.icu/Article/details/gtockkizpy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jianghu66.top/Article/details/gtxxwoigoc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gtbsnohhky.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gtrrxuskog.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guowangkeji.top/Article/details/gtkncevuba.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jlsjyb.cn/Article/details/gtjrygtjeq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.quarkkingdee.top/Article/details/gtnjcquwpa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tanke756.top/Article/details/gtyfpsiozo.html

[M04] 获取当前工作目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdukaark.html

Py:   os.getcwd()
来源：http://dali.hnxiangtu.top/Article/details/gtwtfrrcfs.html

PHP:  getcwd();
来源：http://dali.dashuyun.cn/Article/details/gtaoxsesax.html

JS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gtnsgluofd.html

TS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gtaxegymzq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gzhubu.top/Article/details/gtswcsdmxz.html

Go:   os.Getwd()
来源：http://dali.nanxuanxn.top/Article/details/gtuckhqdfx.html

Ruby: Dir.pwd
来源：http://dali.sweek.top/Article/details/gthqwtfckt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenzaomai.com/Article/details/gtslmujpys.html

[M05] 设置退出码
来源：http://dali.xziqi.cn/Article/details/gtfajbejsk.html

Py:   sys.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtddifohto.html

PHP:  exit(1);
来源：http://dali.zhengqikj.top/Article/details/gtohxjnhtl.html

JS:   process.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtnpmirvqz.html

TS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtngwymsej.html

Java: System.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtggzsobvr.html

Go:   os.Exit(1)
来源：http://dali.fzhhl.top/Article/details/gtmhdkqlvw.html

Ruby: exit 1
来源：http://dali.pengpengdd.cyou/Article/details/gtnhnbwuqk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubkxpguv.html

[M06] 向标准错误输出
来源：http://dali.shangyingyoupin.top/Article/details/gtrghmrfnp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gtwfoyvdtl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.redwolf501.top/Article/details/gtoifdttxt.html

JS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gtxclntkuj.html

TS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtxmbfubzl.html

Java: System.err.println("err")
来源：http://dali.nanxinkj.top/Article/details/gtepfviibi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aizwys.cn/Article/details/gtjdevktaa.html

Ruby: warn "err"
来源：http://dali.tian-w.cn/Article/details/gtytbixzgm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sufxvd.cn/Article/details/gtokqafvzt.html

[M07] 判断是否为主入口
来源：http://dali.yj20258.top/Article/details/gttevjvazd.html

Py:   if __name__ == "__main__":
来源：http://dali.sxryk.cn/Article/details/gtdzywxdfd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxinkj.top/Article/details/gtaaknnbxa.html

JS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gtapxsjcxz.html

TS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gtpplepagd.html

Java: public static void main(String[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gtzudwxgik.html

Go:   func main()
来源：http://dali.fengsongda.top/Article/details/gtdaunoehq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tian-w.cn/Article/details/gtfibtkghz.html

C#:   static void Main(string[] args)
来源：http://dali.jianghu66.top/Article/details/gtozcidfvy.html

[M08] 获取系统与运行时信息
来源：http://dali.xziqi.cn/Article/details/gtfdpbdzrl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aizwys.cn/Article/details/gthrwedxer.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jiagoushi.top/Article/details/gtfeacdjdx.html

JS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gtodzrdcwi.html

TS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gtojevtdnw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hysaishi.cn/Article/details/gtyguxzcjv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yonumen.top/Article/details/gtbaucsjbi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.c1oappe.top/Article/details/gtvhzxiyhk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ydzc1.top/Article/details/gtbwbhwipx.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtlxlghdcr.html

N. 数据结构与算法
来源：http://dali.snrcjt.cn/Article/details/gtaldgmnfo.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtvchcvzfp.html

[N01] 二分查找（有序数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtboyxauff.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sweek.top/Article/details/gtuctlyiac.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtztcfqjzs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gthnawwrki.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gtstgcbajx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gtzayrpjaf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtzqtftgvx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guowangkeji.top/Article/details/gtekjseplo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtghkhoink.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jianghu66.top/Article/details/gtjlrowybb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gtcimfbpid.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xinyue.icu/Article/details/gthnpkdxul.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gttyiyzzdp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gtrkbuubsw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangdashe.top/Article/details/gtkvewfntj.html

Go:   slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gtxocjcdld.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gtjinzhpqz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.iojbl.cn/Article/details/gteagxekmq.html

[N03] 快速排序（分治示例）
来源：http://dali.hywenlv.cn/Article/details/gthenoifiy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yvedp.cn/Article/details/gtyucwlylr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shzxlz.cn/Article/details/gtqsvgbnnr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gtdalfyqdh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gtdbxuuiqs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shuidangran.top/Article/details/gtkuwjpogl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxinkj.top/Article/details/gturbmospf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.svipenyu.cn/Article/details/gtqtwehjqe.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jyoumei.cn/Article/details/gtpbulxqiq.html

[N04] 斐波那契数列
来源：http://dali.birdmap.top/Article/details/gtkinhswme.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gtztguwzun.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gtbbjbsaxy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtsyopxgbj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtoyaoxmjh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ybcxt.top/Article/details/gtswqwfmwt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.snrcjt.cn/Article/details/gttzvogpcr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gtnjydnlsl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtntmzlweh.html

[N05] 最大公约数
来源：http://dali.daria6918.cn/Article/details/gtofjmwogd.html

Py:   math.gcd(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gtgwuatqtb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guowangkeji.top/Article/details/gthzralbzj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtooosbqdf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnqzz.top/Article/details/gtdcoqymfr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hfpthk.cn/Article/details/gtpvkgvlnf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cashguo.top/Article/details/gtpyjaeley.html

Ruby: a.gcd(b)
来源：http://dali.0kj1m.cn/Article/details/gtlfvjphfr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gtkttntpdw.html

[N06] 判断回文字符串
来源：http://dali.fengsongda.top/Article/details/gtwfhxotna.html

Py:   s == s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gtqllvnttr.html

PHP:  $s === strrev($s);
来源：http://dali.aizwys.cn/Article/details/gtnuzifdgi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtquuvykpx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtuzbzctwj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.fzhhl.top/Article/details/gtrctayfkk.html

Go:   // 双指针从两端比较
来源：http://dali.yj202588.top/Article/details/gtgsxhlbxl.html

Ruby: s == s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtwjmpmppl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gtqckihhlj.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgfzy.top/Article/details/gtduofxher.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuetiantiany.cn/Article/details/gtlpxdsjld.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgfzy.top/Article/details/gtymsqqbrc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xziqi.cn/Article/details/gtjcfnfseu.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhixingplan.top/Article/details/gthrlcyuqf.html

Java: // 手写 HashMap
来源：http://dali.daxiang520.top/Article/details/gtqwadwnpv.html

Go:   // 手写 map[int]int
来源：http://dali.zycfv.cn/Article/details/gtpkwsmlbx.html

Ruby: // 手写 Hash
来源：http://dali.cheryme.top/Article/details/gtndnijtwk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yuanzhike.top/Article/details/gthwesgtcb.html

[N08] 生成全排列
来源：http://dali.pycfn.com/Article/details/gtivtzrpyo.html

Py:   itertools.permutations(arr)
来源：http://dali.yuanzhike.top/Article/details/gttgdfjmfx.html

PHP:  // 手写递归交换
来源：http://dali.jinqigufen.top/Article/details/gtiqcahwda.html

JS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtmmkbmerk.html

TS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtzyzijcxo.html

Java: // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtcmsaxsuw.html

Go:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtbgojwdbv.html

Ruby: arr.permutation.to_a
来源：http://dali.xziqi.cn/Article/details/gtzfhrkret.html

C#:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gttrorvwjc.html

[N09] 栈与队列
来源：http://dali.aizwys.cn/Article/details/gtikeifnzj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.quarkkingdee.top/Article/details/gttpvefbfi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtumyelceg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtvhcpehtj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.haohaochexian.top/Article/details/gtmcdkzybs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aizwys.cn/Article/details/gtvxjhdrrn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sufxvd.cn/Article/details/gtvzihxokl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtbdyrgzqg.html


<!-- 参考信息 -->