代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj202588.top/Article/details/gtzzswewjy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gtbyudsuyj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gtqhavjrle.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtnpnhovob.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gthjxtkgas.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gtbkdeergm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gtzovkjlul.html

[K05] 深拷贝对象
来源：http://dali.guowangkeji.top/Article/details/gtafnchyaa.html

Py:   copy.deepcopy(obj)
来源：http://dali.hammf.cn/Article/details/gtrpugdsqy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.mhx1999.top/Article/details/gtvcynjacp.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gtzlsbvwyc.html

TS:   structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gtzmeffgli.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.feifeiyinyue.top/Article/details/gtqzvdnunh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.pycfn.com/Article/details/gtnmgdjkkf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.mhx1999.top/Article/details/gteafnpsye.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.birdmap.top/Article/details/gtrkfdljty.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebraofmq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj202588.top/Article/details/gtgvcftkhz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258.top/Article/details/gthtmwjffn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gtuzabilov.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gtvbekjkuf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nwbrower.top/Article/details/gtwdbklmms.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtixauxafj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtnjbsjvkk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkscdusfy.html

[K07] 进制转换
来源：http://dali.yanxiufei.cn/Article/details/gtinwlwucf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtzvozhysv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.9152youxi.cn/Article/details/gtwyobmkgq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gthesmbtxk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtrftagely.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtuvjzvxqj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258.top/Article/details/gtpipjzsfc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yanxiufei.cn/Article/details/gtzyduelhk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtpjemsksf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.kuanghao11.cn/Article/details/gthdrgkfno.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigufen.top/Article/details/gtiwdyoszs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.316326.xyz/Article/details/gtuuaijvjd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gtslbaucaz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gtzgticyqa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxuanxn.top/Article/details/gtcdyouvjx.html

Go:   encoding/gob
来源：http://dali.zycfv.cn/Article/details/gtlgfgnyav.html

Ruby: Marshal.dump(obj)
来源：http://dali.cheryme.top/Article/details/gtclnjhiis.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gtkmdwckqk.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtoujjfuxr.html

L. 网络请求
来源：http://dali.redwolf501.top/Article/details/gtxwcyorkk.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtodksoeld.html

[L01] 发送 GET 请求
来源：http://dali.zycfv.cn/Article/details/gtfqersjgx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aizwys.cn/Article/details/gtepcpopul.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zdqjudy.top/Article/details/gtdwzdzdjt.html

JS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gtfdgnavbp.html

TS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gtiqeedxhd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhengqikj.top/Article/details/gtwpungzbi.html

Go:   resp, err := http.Get(url)
来源：http://dali.tianlin.xyz/Article/details/gtuaomfvcv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtayrbniqq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cheryme.top/Article/details/gtczoqojcu.html

[L02] 发送 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gtavfxunzn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.pengpengdd.cyou/Article/details/gtykysvami.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jiagoushi.top/Article/details/gtpvmxoxlg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jlsjyb.cn/Article/details/gtwotfkmjo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gtvlewgowu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cashguo.top/Article/details/gtcronwlmn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pengpengdd.cyou/Article/details/gtssnpaaui.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.meibo888.top/Article/details/gtddvkuycy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtnlxscyhv.html

[L03] 设置自定义请求头
来源：http://dali.hnqzz.top/Article/details/gteawntwyp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgfzy.top/Article/details/gtwpfnnkop.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xylfe.cn/Article/details/gtfcmgfycr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gtdubucvqq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xylfe.cn/Article/details/gtvidphzcy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fengsongda.top/Article/details/gtojwxcppu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gtsuqrgbai.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj202588.top/Article/details/gtwzqullzt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gtgxgozofk.html

[L04] 设置超时
来源：http://dali.jyoumei.cn/Article/details/gtpdfeyazw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hnxiangtu.top/Article/details/gtlqopsbcc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daxiang520.top/Article/details/gtyimtpkzb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gthcbytcxk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guannengcc.top/Article/details/gtrdktdoyb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xinyue.icu/Article/details/gtgmfiqowv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yueranfly.top/Article/details/gtjcvjveqm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jqgufenzy.top/Article/details/gtpaohdgrw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.iojbl.cn/Article/details/gtebehwhij.html

[L05] 上传文件（multipart）
来源：http://dali.zhiwuduotai.top/Article/details/gtjizbjyri.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xinyue.icu/Article/details/gtbmnjdgrz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cheryme.top/Article/details/gtowgnzffg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gtvaxniuuz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gteocaoerl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.vqdsnc.cn/Article/details/gtqrppqpla.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.redwolf501.top/Article/details/gtwfoerdix.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgufenzy.top/Article/details/gtemmrznpp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258888.top/Article/details/gtqcijbbvn.html

[L06] 解析响应为 JSON
来源：http://dali.zdqjudy.top/Article/details/gtmtfjinhm.html

Py:   resp.json()
来源：http://dali.mhx1999.top/Article/details/gtcgwpcxyt.html

PHP:  json_decode($body, true);
来源：http://dali.yueranfly.top/Article/details/gtzudyegpt.html

JS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gtrwovupby.html

TS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gtbfmjvhkl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtqpeyhdmn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgufenzy.top/Article/details/gtiaktlujp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdudqloz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnxiangtu.top/Article/details/gtlealqnxt.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gtomtdnelj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zdqjudy.top/Article/details/gtwukcdcvv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtxijfzuvj.html

JS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtpinemzam.html

TS:   resp.ok;  resp.status
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnntjipha.html

Java: resp.statusCode()
来源：http://dali.redwolf501.top/Article/details/gtcpnhfmdk.html

Go:   resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gtqmevnmso.html

Ruby: resp.code.to_i
来源：http://dali.yj20258.top/Article/details/gtkdmzatza.html

C#:   (int)resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gtdfqmabej.html

[L08] 并发请求多个地址
来源：http://dali.jinqigufen.top/Article/details/gtbitajmvp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pycfn.com/Article/details/gtxczetcml.html

PHP:  curl_multi_init() 系列
来源：http://dali.ybcxt.top/Article/details/gtksmglgyl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gtrtmugipt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtmpaejhty.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.feifeiyinyue.top/Article/details/gtgovlgxxk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yvedp.cn/Article/details/gtvizmpxzv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpasxvif.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.svipenyu.cn/Article/details/gtupaogxnv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gttleiafcz.html

M. 命令行 / 进程 / 环境
来源：http://dali.xziqi.cn/Article/details/gttpgtyvja.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtjltbdgkj.html

[M01] 读取命令行参数
来源：http://dali.yongpay.top/Article/details/gtoblmjenj.html

Py:   sys.argv[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gtqlemkpzy.html

PHP:  $argv;  $argc;
来源：http://dali.yangfankeji.com/Article/details/gtighvacee.html

JS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gtkkeirklv.html

TS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gtizepjgss.html

Java: args 数组（main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gtnxdaepzc.html

Go:   os.Args[1:]
来源：http://dali.0kj1m.cn/Article/details/gtcyqznzhh.html

Ruby: ARGV
来源：http://dali.shanyushiyangtech.top/Article/details/gttcezupvl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gtvylwsmsa.html

[M02] 读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gtosqarogr.html

Py:   os.environ.get("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtbpzgwmyz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gtyxcxdidl.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtxulwfesm.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gttbdkftla.html

Java: System.getenv("HOME")
来源：http://dali.smart0.xyz/Article/details/gtvvhbtkmd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtteaycxvy.html

Ruby: ENV["HOME"]
来源：http://dali.tianlin.xyz/Article/details/gtuspprvsj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.meibo888.top/Article/details/gtbeluakvx.html

[M03] 执行外部命令
来源：http://dali.zhengqikj.top/Article/details/gtdmgbnwvv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnxiangtu.top/Article/details/gthsaqnmce.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpaylwhfm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtvxdfdwzt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigufen.top/Article/details/gtnduswhsm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daria6918.cn/Article/details/gtkjlaxfdw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gtxqelvtqo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sweek.top/Article/details/gtfucbqpik.html

C#:   Process.Start("ls", "-l");
来源：http://dali.andypj.xyz/Article/details/gtahoiyajm.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjciqfvma.html

Py:   os.getcwd()
来源：http://dali.yueranfly.top/Article/details/gtqdghtulf.html

PHP:  getcwd();
来源：http://dali.dashuyun.cn/Article/details/gtjxdxgubk.html

JS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gtvnnewipk.html

TS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gtqbzgscqi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ydzc1.top/Article/details/gtydislyfj.html

Go:   os.Getwd()
来源：http://dali.zycfv.cn/Article/details/gtmjgujbps.html

Ruby: Dir.pwd
来源：http://dali.zhongyouzk.top/Article/details/gtdlygbacg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmzoxzxt.html

[M05] 设置退出码
来源：http://dali.sxryk.cn/Article/details/gtjidxdcrw.html

Py:   sys.exit(1)
来源：http://dali.yj20258.top/Article/details/gtddxycvub.html

PHP:  exit(1);
来源：http://dali.gzhubu.top/Article/details/gtuzwxkffi.html

JS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtepideezl.html

TS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtujafemps.html

Java: System.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtmfcubglc.html

Go:   os.Exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtnyhgafbu.html

Ruby: exit 1
来源：http://dali.jinqigufen.top/Article/details/gtxxepyccj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.svipenyu.cn/Article/details/gtecctqutf.html

[M06] 向标准错误输出
来源：http://dali.bjfxy.top/Article/details/gtyqmvgjit.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj202588.top/Article/details/gtavkhuszy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenzaomai.com/Article/details/gtrajvqjvj.html

JS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gtgzvteskk.html

TS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gtrohzmtwd.html

Java: System.err.println("err")
来源：http://dali.cucudq.cn/Article/details/gtmyliuwah.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shuidangran.top/Article/details/gtvfcdfjfi.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gtukkvfzsd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tanke756.top/Article/details/gtfxilawnn.html

[M07] 判断是否为主入口
来源：http://dali.sysykeji.top/Article/details/gtdgyxpath.html

Py:   if __name__ == "__main__":
来源：http://dali.yongpay.top/Article/details/gtzbazyxgr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xziqi.cn/Article/details/gtedxxcovb.html

JS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gtgcytrlat.html

TS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gteitzfkyh.html

Java: public static void main(String[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfonmqndv.html

Go:   func main()
来源：http://dali.guannengcc.top/Article/details/gtjnpmrwjw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.haohaochexian.top/Article/details/gttxksvfmz.html

C#:   static void Main(string[] args)
来源：http://dali.cdnleiting.top/Article/details/gtrjsnrhkf.html

[M08] 获取系统与运行时信息
来源：http://dali.yuanzhike.top/Article/details/gtmkkotyfx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yongpay.top/Article/details/gtetjolajm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.birdmap.top/Article/details/gtevcheula.html

JS:   process.platform;  process.version
来源：http://dali.haohaochexian.top/Article/details/gtgyonsrce.html

TS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqodrfyic.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pycfn.com/Article/details/gtxrwwkuro.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigfzy.top/Article/details/gtabhfxdhx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhiwuduotai.top/Article/details/gtnzxleswo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhengqikj.top/Article/details/gthoigezeu.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtyrfreezb.html

N. 数据结构与算法
来源：http://dali.zhiwuduotai.top/Article/details/gtysgxehhb.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gthofzvnzr.html

[N01] 二分查找（有序数组）
来源：http://dali.gotoacloud.top/Article/details/gtgixcqiag.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtcgwddsze.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtfgfadxsc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gthrtpdlcv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gteniffocj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtdbcinhwh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pycfn.com/Article/details/gtuabbvntt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.0kj1m.cn/Article/details/gtfdczfgyp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtxmvssxsu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigufen.top/Article/details/gtnmkqqcee.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gtboufjwcp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cheryme.top/Article/details/gtvtjzvzfi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gtpscchyjg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gtqxwjuoyx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhiwuduotai.top/Article/details/gtbindzqes.html

Go:   slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gtdlzectmi.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gtgbrswlqi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xinyue.icu/Article/details/gtljzzhxtw.html

[N03] 快速排序（分治示例）
来源：http://dali.cucudq.cn/Article/details/gtvyjgeesu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenlongwang.top/Article/details/gtkbgpmftb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ybcxt.top/Article/details/gtrypwwqme.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqpsavuh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtivcotykj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ppjwa.cn/Article/details/gtudyzbqmk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnqzz.top/Article/details/gtbsixkedf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuetiantiany.cn/Article/details/gtffplewim.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sufxvd.cn/Article/details/gtblmftisy.html

[N04] 斐波那契数列
来源：http://dali.nanxinkj.top/Article/details/gtsmqxzibs.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gtzixglkdz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuanzx.com/Article/details/gtelmfstit.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtrtenbwiw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtytqvixzi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gtkiwtvhuh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sxryk.cn/Article/details/gtktaixhph.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.fengsongda.top/Article/details/gtfcdobcde.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtthdfanja.html

[N05] 最大公约数
来源：http://dali.guannengcc.top/Article/details/gtwylynvup.html

Py:   math.gcd(a, b)
来源：http://dali.daria6918.cn/Article/details/gtehbzojod.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zdqjudy.top/Article/details/gtmfnfsffh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gtkfgbnkoo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258888.top/Article/details/gtyyhxicqy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guannengcc.top/Article/details/gtfdlgovxv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jiagoushi.top/Article/details/gtdrlqwenf.html

Ruby: a.gcd(b)
来源：http://dali.haohaochexian.top/Article/details/gtbprhwyoc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.pycfn.com/Article/details/gtijmzjnoo.html

[N06] 判断回文字符串
来源：http://dali.xylfe.cn/Article/details/gtihosqenc.html

Py:   s == s[::-1]
来源：http://dali.yj20258888.top/Article/details/gtnspnuxpd.html

PHP:  $s === strrev($s);
来源：http://dali.yvedp.cn/Article/details/gtkmqztxzj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtbfnfvmrt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtkdzjoivg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yanxiufei.cn/Article/details/gtiolselcf.html

Go:   // 双指针从两端比较
来源：http://dali.jinqigufen.top/Article/details/gtucqdcorw.html

Ruby: s == s.reverse
来源：http://dali.cucudq.cn/Article/details/gtbtkbtgfc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gtnrvbgbxb.html

[N07] 两数之和（返回下标）
来源：http://dali.hammf.cn/Article/details/gtcvuhezto.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yueranfly.top/Article/details/gtahfkjgbv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.havefunace.top/Article/details/gtluqyuqpt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gzhubu.top/Article/details/gtebcnfyab.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinghuilouyu.cn/Article/details/gtrydwgcjh.html

Java: // 手写 HashMap
来源：http://dali.cucudq.cn/Article/details/gtwruonmen.html

Go:   // 手写 map[int]int
来源：http://dali.sufxvd.cn/Article/details/gtjorxhutv.html

Ruby: // 手写 Hash
来源：http://dali.cashguo.top/Article/details/gtdksnpjkp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tanke756.top/Article/details/gtsplewdyb.html

[N08] 生成全排列
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgjfqtkc.html

Py:   itertools.permutations(arr)
来源：http://dali.yangfankeji.com/Article/details/gtrmuzuooo.html

PHP:  // 手写递归交换
来源：http://dali.pycfn.com/Article/details/gtwsundypu.html

JS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtucyviwax.html

TS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtydlhtflm.html

Java: // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtzazdhqcn.html

Go:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrfpnpfv.html

Ruby: arr.permutation.to_a
来源：http://dali.yj202588.top/Article/details/gttuwtghwo.html

C#:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtnaqnubku.html

[N09] 栈与队列
来源：http://dali.9152youxi.cn/Article/details/gtlvufipru.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.316326.xyz/Article/details/gtciginjpt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gttbtilzxv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gtxttkfaio.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnxiangtu.top/Article/details/gtmamztzyn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hfpthk.cn/Article/details/gtvypnsose.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tanke756.top/Article/details/gtidrxupnl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gteitqwoty.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jiagoushi.top/Article/details/gtvdmcufqo.html

[N10] 链表节点定义
来源：http://dali.yj202588.top/Article/details/gtikharuoe.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhengqikj.top/Article/details/gtjjpcnxbh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sufxvd.cn/Article/details/gttmkauwvo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgnnzecx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenzaomai.com/Article/details/gtbrwxkscb.html

Java: class Node { int v; Node next; }
来源：http://dali.redwolf501.top/Article/details/gtymjglgqr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258888.top/Article/details/gtahyeklrj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.svipenyu.cn/Article/details/gthjetuayg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnxiangtu.top/Article/details/gturhsfxlq.html

[N11] 二叉树中序遍历
来源：http://dali.cucudq.cn/Article/details/gtjtspcgpu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbfizben.html

PHP:  // 手写递归函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujqgzzot.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.havefunace.top/Article/details/gtlkoevmbm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ybcxt.top/Article/details/gtxweclzmr.html

Java: // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gteuwaafed.html

Go:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtwkpsonvg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhengqikj.top/Article/details/gtsbhcnzht.html

C#:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gtpelhdglx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangshuangyany.cn/Article/details/gtqdqxeuya.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yonumen.top/Article/details/gtsmwzzfii.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nwbrower.top/Article/details/gtrojtaemz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gthkypbuiq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvfgqngm.html


<!-- 参考信息 -->