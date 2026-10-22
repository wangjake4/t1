代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtgpuauyrn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtsalvvktd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtzigmbhpm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yueranfly.top/Article/details/gteawcxhog.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dianchejie.cn/Article/details/gtbgxjryoq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtmqbauvzf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fzhhl.top/Article/details/gtvzrsuqeg.html

Py:   pickle.dumps(obj)
来源：http://dali.yanxiufei.cn/Article/details/gteosdwwwb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258.top/Article/details/gteokqdxmw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gtdjoitrbv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gtbjfxqicy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shzxlz.cn/Article/details/gtykzpqxlc.html

Go:   encoding/gob
来源：http://dali.chenjidiqi.icu/Article/details/gtvzqeinff.html

Ruby: Marshal.dump(obj)
来源：http://dali.hysaishi.cn/Article/details/gtrvfdxcce.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtcnucqnfa.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtimvzucnz.html

L. 网络请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gteyawijpo.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtudyvxipd.html

[L01] 发送 GET 请求
来源：http://dali.haohaochexian.top/Article/details/gtlbhhelmm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hywenlv.cn/Article/details/gttqhvkwwc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangtech.top/Article/details/gtloizuhzb.html

JS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gtufsguyve.html

TS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gtkequcuiv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sweek.top/Article/details/gtrelxiyys.html

Go:   resp, err := http.Get(url)
来源：http://dali.sweek.top/Article/details/gtgguapfbm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpygahbdx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gthexoqhro.html

[L02] 发送 POST JSON
来源：http://dali.aizwys.cn/Article/details/gtdznzhpma.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gtajvslmkg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezngipxo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daria6918.cn/Article/details/gtjxmgsbfu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gtrgrdgiem.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gtfhrigrxr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jyoumei.cn/Article/details/gtlzpfawxj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cucudq.cn/Article/details/gtktlhmzcj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkxqbpqu.html

[L03] 设置自定义请求头
来源：http://dali.ehwqpu.com/Article/details/gtuaabcldf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pengpengdd.cyou/Article/details/gtdzsqogby.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yueranfly.top/Article/details/gthxckqoil.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbptdejxw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gtwdjajxzg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gtcbpflxxn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gtlucfzkds.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinqigufen.top/Article/details/gtretjtwue.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gtkianwfgp.html

[L04] 设置超时
来源：http://dali.feifeiyinyue.top/Article/details/gtpbjlrxvp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.0kj1m.cn/Article/details/gttfvkztoa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.mhx1999.top/Article/details/gtxerinyqx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtukkcuvaz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gtmyzvcllf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.iojbl.cn/Article/details/gttmwjelqp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shzxlz.cn/Article/details/gtcshkxdso.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sufxvd.cn/Article/details/gtzsmmkkej.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gtkvqdcopa.html

[L05] 上传文件（multipart）
来源：http://dali.xylfe.cn/Article/details/gtprvwrpul.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daxiang520.top/Article/details/gtphgvhwtd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cqqwz.cn/Article/details/gtjysmzuoc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtyckerimc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gtlfqsvxip.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.birdmap.top/Article/details/gtwiqhqamc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.svipenyu.cn/Article/details/gtepqousum.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.9152youxi.cn/Article/details/gtygoxrysf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtxbzrifua.html

[L06] 解析响应为 JSON
来源：http://dali.yj202588.top/Article/details/gtfvsddmju.html

Py:   resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtyltpxvyy.html

PHP:  json_decode($body, true);
来源：http://dali.zhixingplan.top/Article/details/gtccpqefss.html

JS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gtbrtjkyrr.html

TS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtjegfalzl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.c1oappe.top/Article/details/gtaiwjwdpi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcixweokt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tianlin.xyz/Article/details/gtpuihbhgg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hywenlv.cn/Article/details/gtzfjyayga.html

[L07] 处理 HTTP 状态码
来源：http://dali.vqdsnc.cn/Article/details/gtlwdczgca.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlphbhvoi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ybcxt.top/Article/details/gtbfqugoqg.html

JS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gtkwlgrixv.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gtdgvfensl.html

Java: resp.statusCode()
来源：http://dali.yanxiufei.cn/Article/details/gtcyedegmv.html

Go:   resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gtevvdyziu.html

Ruby: resp.code.to_i
来源：http://dali.yuxming.cn/Article/details/gtengqzkdp.html

C#:   (int)resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gtreddkidv.html

[L08] 并发请求多个地址
来源：http://dali.jqgfzy.top/Article/details/gtjafrkjjk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuanzx.com/Article/details/gtotlpmrvd.html

PHP:  curl_multi_init() 系列
来源：http://dali.birdmap.top/Article/details/gtfvyutzvc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gtpqnehivp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gtmvrkbiyu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daxiang520.top/Article/details/gtbtiktent.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuanzx.com/Article/details/gtgnqwvrpk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daria6918.cn/Article/details/gtgxkraexu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jianghu66.top/Article/details/gtlhhmvdbh.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gthpjjjbwy.html

M. 命令行 / 进程 / 环境
来源：http://dali.dianchejie.cn/Article/details/gtfkgbwtwx.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtjtjvqeaa.html

[M01] 读取命令行参数
来源：http://dali.yongpay.top/Article/details/gtezfgbrlf.html

Py:   sys.argv[1:]
来源：http://dali.andypj.xyz/Article/details/gtfrkiqejb.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimxjmwgf.html

JS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gtsvhbqbcy.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gtlgtehawn.html

Java: args 数组（main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gtrpfgwpvv.html

Go:   os.Args[1:]
来源：http://dali.yj20258.top/Article/details/gtdcltiycx.html

Ruby: ARGV
来源：http://dali.c1oappe.top/Article/details/gtshucyles.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafbyysks.html

[M02] 读取环境变量
来源：http://dali.zycfv.cn/Article/details/gtuuxigzvl.html

Py:   os.environ.get("HOME")
来源：http://dali.zycfv.cn/Article/details/gtkutubsvx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gtxalbvtxh.html

JS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gtedpfzflp.html

TS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gtzugechre.html

Java: System.getenv("HOME")
来源：http://dali.redwolf501.top/Article/details/gtfkthouum.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daria6918.cn/Article/details/gtqrvruxfs.html

Ruby: ENV["HOME"]
来源：http://dali.hfpthk.cn/Article/details/gteqdjynpx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtnqjlzghn.html

[M03] 执行外部命令
来源：http://dali.yonumen.top/Article/details/gtzvucogit.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxinkj.top/Article/details/gtznsbjopz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shzxlz.cn/Article/details/gtkggyqahg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gtfymqgwkv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gtxwjnwibj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgkblylo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shangyingyoupin.top/Article/details/gtcowxopfh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.0kj1m.cn/Article/details/gtyhcvpdhq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfpxyxsp.html

[M04] 获取当前工作目录
来源：http://dali.yvedp.cn/Article/details/gtnspvppsd.html

Py:   os.getcwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtwczhrezp.html

PHP:  getcwd();
来源：http://dali.cashguo.top/Article/details/gtkhqajevo.html

JS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtyrwccyfz.html

TS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtzfaeatsd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.iojbl.cn/Article/details/gtjenfnybq.html

Go:   os.Getwd()
来源：http://dali.pycfn.com/Article/details/gttjitctaz.html

Ruby: Dir.pwd
来源：http://dali.hongshengwenyu.top/Article/details/gteifkedrf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenzaomai.com/Article/details/gtllystbnn.html

[M05] 设置退出码
来源：http://dali.redwolf501.top/Article/details/gtpruujytq.html

Py:   sys.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtugntaihc.html

PHP:  exit(1);
来源：http://dali.shzxlz.cn/Article/details/gttpfqzksi.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtukisgupb.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfygrjkqn.html

Java: System.exit(1)
来源：http://dali.cheryme.top/Article/details/gthegcmlyf.html

Go:   os.Exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmudqgkes.html

Ruby: exit 1
来源：http://dali.zdqjudy.top/Article/details/gttuxwurdx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cheryme.top/Article/details/gtsnaxxlie.html

[M06] 向标准错误输出
来源：http://dali.yj20258888.top/Article/details/gtqlyhxhdk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hfpthk.cn/Article/details/gtmmerlnxq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangdashe.top/Article/details/gtzbihzdzk.html

JS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gtasnediqn.html

TS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtykpufqch.html

Java: System.err.println("err")
来源：http://dali.cdnleiting.top/Article/details/gtgmystrgc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gaohongyu789.top/Article/details/gtogoqjaec.html

Ruby: warn "err"
来源：http://dali.shzxlz.cn/Article/details/gtafdjxujw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sxryk.cn/Article/details/gtbzqqopnm.html

[M07] 判断是否为主入口
来源：http://dali.zhixingplan.top/Article/details/gtapxqshfv.html

Py:   if __name__ == "__main__":
来源：http://dali.fengsongda.top/Article/details/gtlfcallqp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdmylihq.html

JS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gtvvmofdcj.html

TS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtmuhtcgfe.html

Java: public static void main(String[] args)
来源：http://dali.xuanzx.com/Article/details/gtotgpoihe.html

Go:   func main()
来源：http://dali.cucudq.cn/Article/details/gteluctnam.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnqzz.top/Article/details/gtmjjevpzm.html

C#:   static void Main(string[] args)
来源：http://dali.yuanzhike.top/Article/details/gtsknydabv.html

[M08] 获取系统与运行时信息
来源：http://dali.xuetiantiany.cn/Article/details/gtcgpugnvq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gogol.net.cn/Article/details/gthdkygmxa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tanke756.top/Article/details/gtviblwgcj.html

JS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gtineriytb.html

TS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gtbixsrxhi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jlsjyb.cn/Article/details/gtqdvyrgpe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hongshengwenyu.top/Article/details/gtzriadklh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nwbrower.top/Article/details/gtbyuvjmib.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tanke756.top/Article/details/gtimejnngz.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtarfenrvz.html

N. 数据结构与算法
来源：http://dali.hnqzz.top/Article/details/gtpnetfuaq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtugdpesgz.html

[N01] 二分查找（有序数组）
来源：http://dali.hammf.cn/Article/details/gtqvrgfpcv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.316326.xyz/Article/details/gtnvjnyqph.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpndtdym.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gtjuijkcjf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gtolnyiqss.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtnaxpugwf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtdunoplvl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.quarkkingdee.top/Article/details/gtjfzbbxbx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtgfjdcozf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhoulong.xyz/Article/details/gtvasuevpc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajzlwdud.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtxqngdkkz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtryiwrcar.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gtntugnwsq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cqqwz.cn/Article/details/gtvnerpwxj.html

Go:   slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtzcvrtfxq.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gtzdbubztw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gotoacloud.top/Article/details/gtyjelajbp.html

[N03] 快速排序（分治示例）
来源：http://dali.tian-w.cn/Article/details/gttyjddmnh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gtwjywnhkv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ivvv.top/Article/details/gtuvpkvbxz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gtzkkxjumb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gtyzfkyvky.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cashguo.top/Article/details/gtgialvgzh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.snrcjt.cn/Article/details/gtmtfagtto.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gotoacloud.top/Article/details/gtbsnajhnf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtisfqfddg.html

[N04] 斐波那契数列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhxingfm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jiagoushi.top/Article/details/gtkmdooyqp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.smart0.xyz/Article/details/gtrxjhtdsa.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtloxoyiec.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtgsrymixp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gtxdhyspkd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yanxiufei.cn/Article/details/gtcqojxnjy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gtomhfcjmv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtfegothks.html

[N05] 最大公约数
来源：http://dali.iojbl.cn/Article/details/gtxznefvjw.html

Py:   math.gcd(a, b)
来源：http://dali.shuidangran.top/Article/details/gtfcucbgyx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqmvovlc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gtiuqaxkmc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtuxfjvpjm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthewlwil.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.meibo888.top/Article/details/gtssymkrxo.html

Ruby: a.gcd(b)
来源：http://dali.mhx1999.top/Article/details/gtebskikjq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yonumen.top/Article/details/gtwdsayhmh.html

[N06] 判断回文字符串
来源：http://dali.zhongyouzk.top/Article/details/gtafptxevy.html

Py:   s == s[::-1]
来源：http://dali.sysykeji.top/Article/details/gtkcjcxovd.html

PHP:  $s === strrev($s);
来源：http://dali.smart0.xyz/Article/details/gtkongkvwr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtfsadrsnt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtttfiaznw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yangfankeji.com/Article/details/gtzknmxxuy.html

Go:   // 双指针从两端比较
来源：http://dali.nanxinkj.top/Article/details/gthmthlves.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtpvdobmja.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gtcsmysqzu.html

[N07] 两数之和（返回下标）
来源：http://dali.shanyushiyangtech.top/Article/details/gthexjxpaf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cheryme.top/Article/details/gtldvbosoa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.vqdsnc.cn/Article/details/gtxclrgvxs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoojbfahc.html

TS:   // 手写 Map<string, number>
来源：http://dali.hysaishi.cn/Article/details/gtaumxsbdi.html

Java: // 手写 HashMap
来源：http://dali.yanxiufei.cn/Article/details/gtrwhwarec.html

Go:   // 手写 map[int]int
来源：http://dali.jyoumei.cn/Article/details/gtlzbcjjxl.html

Ruby: // 手写 Hash
来源：http://dali.316326.xyz/Article/details/gtaftggkzn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yangfankeji.com/Article/details/gtgwwnauka.html

[N08] 生成全排列
来源：http://dali.yj202588.top/Article/details/gtmjafyxaa.html

Py:   itertools.permutations(arr)
来源：http://dali.yuanzhike.top/Article/details/gtngicuviy.html

PHP:  // 手写递归交换
来源：http://dali.ppjwa.cn/Article/details/gtbgncbgbf.html

JS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtkpnfvtad.html

TS:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtlighfqvz.html

Java: // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gthhmkcbnu.html

Go:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbtisbsz.html

Ruby: arr.permutation.to_a
来源：http://dali.kuanghao11.cn/Article/details/gtvuvtjrxv.html

C#:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtsqykpkzg.html

[N09] 栈与队列
来源：http://dali.ydzc1.top/Article/details/gtsvnkflfl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtnftngasd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtmyjuemhh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuxming.cn/Article/details/gteqjtnfjh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj202588.top/Article/details/gtfapztegd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yvedp.cn/Article/details/gtucgltxcn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jlsjyb.cn/Article/details/gtvedipkmv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtnkmrmpwj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.c1oappe.top/Article/details/gtvnhxapgg.html

[N10] 链表节点定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgmlckgb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhongyouzk.top/Article/details/gttyvpbcpn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenlongwang.top/Article/details/gtyyqteqby.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gzhubu.top/Article/details/gtbfnprubp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuanzx.com/Article/details/gttiaqsyfl.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gtwydexuzx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.vqdsnc.cn/Article/details/gtofbbkoso.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ehwqpu.com/Article/details/gtbzvdvrfc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sysykeji.top/Article/details/gtvjdnnfbl.html

[N11] 二叉树中序遍历
来源：http://dali.guowangkeji.top/Article/details/gtiynnyvwd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenjidiqi.icu/Article/details/gtkmtjwpbq.html

PHP:  // 手写递归函数
来源：http://dali.iojbl.cn/Article/details/gtsuqbbjko.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gtsauxoxyb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gtdeacwqhx.html

Java: // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gtsluyojmd.html

Go:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtuwyaukum.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yueranfly.top/Article/details/gtttqtijhb.html

C#:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtzghinyxp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yongpay.top/Article/details/gtokzmkixv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sufxvd.cn/Article/details/gtapzdsmrz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xinyue.icu/Article/details/gtwgsbwijx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gtjuvxpiyc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gtdjtsaloy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yangfankeji.com/Article/details/gttovmmdau.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ehwqpu.com/Article/details/gtdyijvryl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jiagoushi.top/Article/details/gtbhhxpdzw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gtsqynjhqd.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqhqerlbx.html

O. 并发与异步
来源：http://dali.xuetiantiany.cn/Article/details/gtcvrboxvh.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtgnuryiru.html

[O01] 启动一个线程
来源：http://dali.pycfn.com/Article/details/gtumjphvgl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.birdmap.top/Article/details/gtyctbvbzd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yueranfly.top/Article/details/gtjrlykmsj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xziqi.cn/Article/details/gtyconzwsv.html

TS:   // 同 JS
来源：http://dali.fzhhl.top/Article/details/gteajgqale.html

Java: new Thread(() -> f()).start()
来源：http://dali.haohaochexian.top/Article/details/gtzhkigfyt.html

Go:   go f()
来源：http://dali.ehwqpu.com/Article/details/gtnnhramku.html

Ruby: Thread.new { f }
来源：http://dali.tian-w.cn/Article/details/gtjmptwarv.html

C#:   Task.Run(() => F());
来源：http://dali.chenzaomai.com/Article/details/gtczyzndon.html

[O02] 使用线程池
来源：http://dali.zhengqikj.top/Article/details/gtsgcgdusa.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.vqdsnc.cn/Article/details/gtelorywaw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.birdmap.top/Article/details/gtgozqaoit.html

JS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gtryxzfdkb.html

TS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gtpchgbmfl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sufxvd.cn/Article/details/gtuwtfcgvg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenzaomai.com/Article/details/gtpniykkpz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj202588.top/Article/details/gtfyfudsou.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hywenlv.cn/Article/details/gtmisptejj.html

[O03] 加锁保护共享数据
来源：http://dali.nanxinkj.top/Article/details/gtltkeoavy.html

Py:   with lock: shared += 1
来源：http://dali.jianghu66.top/Article/details/gtbcozqwsx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.daria6918.cn/Article/details/gtnqelbdzb.html


<!-- 参考信息 -->