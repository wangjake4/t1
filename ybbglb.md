代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ehwqpu.com/Article/details/gtoqeshzex.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtvqedtvsf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhengqikj.top/Article/details/gtqlgtxssm.html

Py:   pickle.dumps(obj)
来源：http://dali.sxryk.cn/Article/details/gtciwjpnlj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jianghu66.top/Article/details/gtwuypnpfl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteiqaoala.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.guannengcc.top/Article/details/gtdskduxkl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhoulong.xyz/Article/details/gtmbeldjrt.html

Go:   encoding/gob
来源：http://dali.feifeiyinyue.top/Article/details/gtkgiezqbv.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtdecdfxri.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gtwshwcleb.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtckexacob.html

L. 网络请求
来源：http://dali.gogol.net.cn/Article/details/gtsgkgvobq.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtfbbfsxvq.html

[L01] 发送 GET 请求
来源：http://dali.jqgfzy.top/Article/details/gtcqkqlowg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigfzy.top/Article/details/gtyqzgjgkj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgfzy.top/Article/details/gtbrujoicp.html

JS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gttiyfijbz.html

TS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gtajkuzxkv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jiagoushi.top/Article/details/gtctxiatvh.html

Go:   resp, err := http.Get(url)
来源：http://dali.hfpthk.cn/Article/details/gtegswsaig.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ehwqpu.com/Article/details/gtoegwptds.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pengpengdd.cyou/Article/details/gthwrienyk.html

[L02] 发送 POST JSON
来源：http://dali.yuxming.cn/Article/details/gtjeruozjv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmcbnbps.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.smart0.xyz/Article/details/gtuhszzgrg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gtqfjtzryy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gtbdnmesme.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yanxiufei.cn/Article/details/gtvrvmxsbv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sufxvd.cn/Article/details/gtpalqiufm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ydzc1.top/Article/details/gtpqimgfwp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daria6918.cn/Article/details/gtesgadmpq.html

[L03] 设置自定义请求头
来源：http://dali.dashuyun.cn/Article/details/gtpdncfsrf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.snrcjt.cn/Article/details/gtmyozohpa.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dianchejie.cn/Article/details/gtgcluvxoo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.birdmap.top/Article/details/gtjrydrumo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gtybprzkjk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.9152youxi.cn/Article/details/gtinaeyvrz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gtbqaihicj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jyoumei.cn/Article/details/gtquellnas.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gtcykqfydh.html

[L04] 设置超时
来源：http://dali.jianghu66.top/Article/details/gtiushutgj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ivvv.top/Article/details/gtnwbnlhnr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ehwqpu.com/Article/details/gtrirdkiqu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gtxhogogss.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gteqmjtghc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fzhhl.top/Article/details/gtjlzpexlj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tian-w.cn/Article/details/gthxsudqjw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.feifeiyinyue.top/Article/details/gtccvapdel.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gotoacloud.top/Article/details/gteyqhkdqs.html

[L05] 上传文件（multipart）
来源：http://dali.wangshuangyany.cn/Article/details/gttckpcvsi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tanke756.top/Article/details/gtduyimzmx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhongyouzk.top/Article/details/gtmkezcgxp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gtridqcjvk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gttupihawa.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhoulong.xyz/Article/details/gtsqwlcslj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyynledgb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shangyingyoupin.top/Article/details/gtdncvwsrk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.redwolf501.top/Article/details/gtwdwkjjyr.html

[L06] 解析响应为 JSON
来源：http://dali.xylfe.cn/Article/details/gtssvphfbn.html

Py:   resp.json()
来源：http://dali.yj20258888.top/Article/details/gtrsftmzya.html

PHP:  json_decode($body, true);
来源：http://dali.hnxiangtu.top/Article/details/gtgyzprtvn.html

JS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gtahxquepa.html

TS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gtciilcxbc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sweek.top/Article/details/gtdilpdkxc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxinkj.top/Article/details/gtehplwxoy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.quarkkingdee.top/Article/details/gtwnxpkyjw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guannengcc.top/Article/details/gtindvsziz.html

[L07] 处理 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtmvvvxieh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gtbiltvzaq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenlongwang.top/Article/details/gtxofppywi.html

JS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtcbposyzl.html

TS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gtefihkxxl.html

Java: resp.statusCode()
来源：http://dali.xziqi.cn/Article/details/gtcjwjbexe.html

Go:   resp.StatusCode
来源：http://dali.yanxiufei.cn/Article/details/gtdzmahwhi.html

Ruby: resp.code.to_i
来源：http://dali.pengpengdd.cyou/Article/details/gtdrzrreon.html

C#:   (int)resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtbdsjziqn.html

[L08] 并发请求多个地址
来源：http://dali.xylfe.cn/Article/details/gttaaehurz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuanzhike.top/Article/details/gtsgpkqpmb.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangdashe.top/Article/details/gtdwdyogvm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtopbovxxd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtcexenvwk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmwbxfig.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jiagoushi.top/Article/details/gteowyheen.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zdqjudy.top/Article/details/gteinogwsa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yueranfly.top/Article/details/gtmmtkhczr.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtxqbmvrji.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gtlqblgisy.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtcadnhwad.html

[M01] 读取命令行参数
来源：http://dali.guannengcc.top/Article/details/gtdnyaqsiu.html

Py:   sys.argv[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtvbmiexvl.html

PHP:  $argv;  $argc;
来源：http://dali.nanxuanxn.top/Article/details/gtlydokeug.html

JS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtzuwkartl.html

TS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtrksutukm.html

Java: args 数组（main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gtnrdskxqo.html

Go:   os.Args[1:]
来源：http://dali.316326.xyz/Article/details/gtvklrtodh.html

Ruby: ARGV
来源：http://dali.birdmap.top/Article/details/gtytahguaa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gthkkxrzbu.html

[M02] 读取环境变量
来源：http://dali.shuidangran.top/Article/details/gtksyfobzv.html

Py:   os.environ.get("HOME")
来源：http://dali.ydzc1.top/Article/details/gtitwaummh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gtlubtavsb.html

JS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gtrbbdjsia.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gtgoajpray.html

Java: System.getenv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtptfketwp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yongpay.top/Article/details/gtlfxransq.html

Ruby: ENV["HOME"]
来源：http://dali.yvedp.cn/Article/details/gtfxwupgoy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtchhijpyq.html

[M03] 执行外部命令
来源：http://dali.havefunace.top/Article/details/gtpbkuacfn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgfzy.top/Article/details/gtftrtamnn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.0kj1m.cn/Article/details/gtqeqiqqor.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gttijtplqx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gtobzzsqbu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yangfankeji.com/Article/details/gtluueondk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jlsjyb.cn/Article/details/gtzdhprchq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cashguo.top/Article/details/gtrwnmebbb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.mhx1999.top/Article/details/gtagnvmwed.html

[M04] 获取当前工作目录
来源：http://dali.jlsjyb.cn/Article/details/gtyfkzpsrh.html

Py:   os.getcwd()
来源：http://dali.yongpay.top/Article/details/gtrwogkwbf.html

PHP:  getcwd();
来源：http://dali.yongpay.top/Article/details/gtwhbtnbjs.html

JS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gtjcelptrv.html

TS:   process.cwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtllopxlwb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cucudq.cn/Article/details/gtlukgrswc.html

Go:   os.Getwd()
来源：http://dali.yuanzhike.top/Article/details/gtgfvcvtwy.html

Ruby: Dir.pwd
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxrkjqij.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.feifeiyinyue.top/Article/details/gtxaotoovb.html

[M05] 设置退出码
来源：http://dali.snrcjt.cn/Article/details/gthxjtvlkx.html

Py:   sys.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmoaziane.html

PHP:  exit(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrqtuzeu.html

JS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gttrmtgfpo.html

TS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtqvetsgcs.html

Java: System.exit(1)
来源：http://dali.hammf.cn/Article/details/gtzjdintjt.html

Go:   os.Exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtkdlfwlru.html

Ruby: exit 1
来源：http://dali.iojbl.cn/Article/details/gtdqfmpsui.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cqqwz.cn/Article/details/gtfdeubtnp.html

[M06] 向标准错误输出
来源：http://dali.meibo888.top/Article/details/gtvvdqgtyx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gtqfhsttpj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yongpay.top/Article/details/gtyegqidyr.html

JS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtngagxrwq.html

TS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gtohuupirr.html

Java: System.err.println("err")
来源：http://dali.cheryme.top/Article/details/gtjimaoboz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbdnmzjh.html

Ruby: warn "err"
来源：http://dali.xinyue.icu/Article/details/gtzfuezisr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fzhhl.top/Article/details/gtuekcmxum.html

[M07] 判断是否为主入口
来源：http://dali.xuetiantiany.cn/Article/details/gtvucmxofz.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxinkj.top/Article/details/gthscjhivk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.havefunace.top/Article/details/gthnwebopr.html

JS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gtiprgpqxc.html

TS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gtsvohwkbt.html

Java: public static void main(String[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtziaizpcz.html

Go:   func main()
来源：http://dali.hysaishi.cn/Article/details/gtmhmbgiab.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangshuangyany.cn/Article/details/gtadvobqrs.html

C#:   static void Main(string[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtelvfgpfe.html

[M08] 获取系统与运行时信息
来源：http://dali.jyoumei.cn/Article/details/gtvljyzlmo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xziqi.cn/Article/details/gtndcswqtv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yanxiufei.cn/Article/details/gtjijqhcpr.html

JS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gtwarteaff.html

TS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtgwcasdcz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenzaomai.com/Article/details/gtqqfvhtqx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.mhx1999.top/Article/details/gtrpwwajqg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hammf.cn/Article/details/gtcwfqruwi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tianlin.xyz/Article/details/gtvoeouejr.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtxxcnlzjq.html

N. 数据结构与算法
来源：http://dali.snrcjt.cn/Article/details/gtxmlxalah.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gttwyheymu.html

[N01] 二分查找（有序数组）
来源：http://dali.jlsjyb.cn/Article/details/gthimqvmxd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cashguo.top/Article/details/gtkrxshosf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtoohqscgs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gttoasbqob.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gtlzkjxggn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtuikhakzv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtvdmgxkyz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.meibo888.top/Article/details/gtnoemtviy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gtfjrylnhe.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tian-w.cn/Article/details/gtcbhwcmyf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gtgwsmfhwn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cdnleiting.top/Article/details/gtyjgcoyyu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtwhphneri.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtxpokikoj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yanxiufei.cn/Article/details/gtyteqqbos.html

Go:   slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gtpsoltxqr.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtjinvpzkh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aibaodan.cn/Article/details/gtxaywqnfl.html

[N03] 快速排序（分治示例）
来源：http://dali.ydzc1.top/Article/details/gtoqsnnurp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhixingplan.top/Article/details/gtcpyredbd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhixingplan.top/Article/details/gtnbsiskll.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gtqkpkvyqr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gtzgvchvls.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenlongwang.top/Article/details/gtumulxmcl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ehwqpu.com/Article/details/gtesmlzbdm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cucudq.cn/Article/details/gtujescepa.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnxiangtu.top/Article/details/gtvcbbzvxq.html

[N04] 斐波那契数列
来源：http://dali.bjfxy.top/Article/details/gtidlzptzg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gtuyqlucyg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ivvv.top/Article/details/gtkznhczpc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtzbhliejb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcpyjiws.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gtayscfixk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hywenlv.cn/Article/details/gthepydrwr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gteivbgwfi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gttfofqsca.html

[N05] 最大公约数
来源：http://dali.sxryk.cn/Article/details/gtoytgffjv.html

Py:   math.gcd(a, b)
来源：http://dali.hysaishi.cn/Article/details/gtbkbwsmib.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jlsjyb.cn/Article/details/gtjhuaydus.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gteuuppabu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gtndfpxepk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnoqjlnz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tanke756.top/Article/details/gtzdonwyra.html

Ruby: a.gcd(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtinycpdls.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dashuyun.cn/Article/details/gtuxtkbgrv.html

[N06] 判断回文字符串
来源：http://dali.jqgufenzy.top/Article/details/gtbcrweeyc.html

Py:   s == s[::-1]
来源：http://dali.yj202588.top/Article/details/gtmyvnwekv.html

PHP:  $s === strrev($s);
来源：http://dali.316326.xyz/Article/details/gtutrjdhdl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtmohystde.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtphcugivx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shuidangran.top/Article/details/gtuteerlpi.html

Go:   // 双指针从两端比较
来源：http://dali.bjfxy.top/Article/details/gtpohzyprn.html

Ruby: s == s.reverse
来源：http://dali.sxryk.cn/Article/details/gtydvqmfcp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gtugfaojdz.html

[N07] 两数之和（返回下标）
来源：http://dali.svipenyu.cn/Article/details/gtlplttovl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yueranfly.top/Article/details/gtlqadwrvt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.vqdsnc.cn/Article/details/gtzyoysvbi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhongyouzk.top/Article/details/gtbqjrvlwt.html

TS:   // 手写 Map<string, number>
来源：http://dali.ivvv.top/Article/details/gtrhdieubq.html

Java: // 手写 HashMap
来源：http://dali.hywenlv.cn/Article/details/gtpadozdxe.html

Go:   // 手写 map[int]int
来源：http://dali.yueranfly.top/Article/details/gtgjtsfsgh.html

Ruby: // 手写 Hash
来源：http://dali.nwbrower.top/Article/details/gtllusmqif.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cucudq.cn/Article/details/gtgeyyseuz.html

[N08] 生成全排列
来源：http://dali.jinqigfzy.top/Article/details/gtgkyashlq.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgfzy.top/Article/details/gtaoiuiuyy.html

PHP:  // 手写递归交换
来源：http://dali.zhongyouzk.top/Article/details/gtvhsptuaj.html

JS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtawwsyurx.html

TS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtofezttqb.html

Java: // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtrymsfpjw.html

Go:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gttukguamx.html

Ruby: arr.permutation.to_a
来源：http://dali.xuetiantiany.cn/Article/details/gtdocyytep.html

C#:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtpwtvvtot.html

[N09] 栈与队列
来源：http://dali.ydzc1.top/Article/details/gtzazjdilm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dianchejie.cn/Article/details/gtgofgvtvt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gtikkyffud.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tanke756.top/Article/details/gtgjnyblhd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yangfankeji.com/Article/details/gteytyscnf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tanke756.top/Article/details/gtpabcodwf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cdnleiting.top/Article/details/gtlmlacuzh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtyfijfdpi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jqgfzy.top/Article/details/gtpwlzgvjd.html

[N10] 链表节点定义
来源：http://dali.quarkkingdee.top/Article/details/gtaoevojeo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sweek.top/Article/details/gtelhfnmqx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cdnleiting.top/Article/details/gtkvtbxgoo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tian-w.cn/Article/details/gtdqsligyb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jlsjyb.cn/Article/details/gthbbopokw.html

Java: class Node { int v; Node next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpniupuw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangdashe.top/Article/details/gtowgclvnp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daxiang520.top/Article/details/gtocztxhfl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxuanxn.top/Article/details/gtbcidhate.html

[N11] 二叉树中序遍历
来源：http://dali.jlsjyb.cn/Article/details/gtuolejkcj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sweek.top/Article/details/gthijpoerm.html

PHP:  // 手写递归函数
来源：http://dali.zhengqikj.top/Article/details/gtbisxewdi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dashuyun.cn/Article/details/gtebswkwrp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gtiksqfugc.html

Java: // 手写递归
来源：http://dali.gzhubu.top/Article/details/gtezhewkyq.html

Go:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtnjxuehzl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aizwys.cn/Article/details/gtjjnqugtj.html

C#:   // 手写递归
来源：http://dali.yongpay.top/Article/details/gtgkoagvah.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yuxming.cn/Article/details/gtvspivoyg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigufen.top/Article/details/gtlwokywpd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shzxlz.cn/Article/details/gtoiuchltp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gtsigbcxqk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhixingplan.top/Article/details/gtoluuyavp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzvvrrun.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hywenlv.cn/Article/details/gtcgrevnbo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yongpay.top/Article/details/gtpkhtrxrf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gtoulcvknm.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtbhbdgzbj.html

O. 并发与异步
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfkowjdj.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtnsjxbnst.html

[O01] 启动一个线程
来源：http://dali.birdmap.top/Article/details/gtukegoxgw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenlongwang.top/Article/details/gtquvmrpgl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sufxvd.cn/Article/details/gtxqkkmvth.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ydzc1.top/Article/details/gthtqdncbh.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gtobjgzttf.html

Java: new Thread(() -> f()).start()
来源：http://dali.yongpay.top/Article/details/gtzutempuq.html

Go:   go f()
来源：http://dali.hnxiangtu.top/Article/details/gtfmemlgob.html

Ruby: Thread.new { f }
来源：http://dali.yanxiufei.cn/Article/details/gtewcrngju.html

C#:   Task.Run(() => F());
来源：http://dali.jianghu66.top/Article/details/gtqozdydoz.html

[O02] 使用线程池
来源：http://dali.jqgfzy.top/Article/details/gtkyfpqeci.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ydzc1.top/Article/details/gtjikoundq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yonumen.top/Article/details/gtetzvroaj.html

JS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gtviaqmodk.html

TS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gtyrdtsnfp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cdnleiting.top/Article/details/gtahdtnvle.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jianghu66.top/Article/details/gtwqhqgkav.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pengpengdd.cyou/Article/details/gtcbrlumoi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gzhubu.top/Article/details/gtzrhaycdh.html

[O03] 加锁保护共享数据
来源：http://dali.xinyue.icu/Article/details/gthkerzwlx.html

Py:   with lock: shared += 1
来源：http://dali.cqqwz.cn/Article/details/gtsbujtbon.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenlongwang.top/Article/details/gtmnxgrapf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfouoydu.html

TS:   // 同 JS
来源：http://dali.haohaochexian.top/Article/details/gtnjchgkdh.html

Java: synchronized (this) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlffxeqmb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daria6918.cn/Article/details/gtpgdbaanb.html


<!-- 参考信息 -->