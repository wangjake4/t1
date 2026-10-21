代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtvmdrmbrd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtabkyxoci.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwbnchjb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.snrcjt.cn/Article/details/gtmeaxqjku.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnxiangtu.top/Article/details/gtoyvkpwld.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtowxuriex.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yangfankeji.com/Article/details/gtzarlhbkg.html

Py:   pickle.dumps(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtdjdflyln.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258888.top/Article/details/gtgdrrrddt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gtospgeugj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtdcobvlxc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fzhhl.top/Article/details/gttbtvutgd.html

Go:   encoding/gob
来源：http://dali.meibo888.top/Article/details/gtelldsoil.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtepuxpilk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtqsjvjcwx.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtktwivkkx.html

L. 网络请求
来源：http://dali.sxryk.cn/Article/details/gtekkzaqbk.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gttyiyxrqw.html

[L01] 发送 GET 请求
来源：http://dali.zhixingplan.top/Article/details/gtgkmpowoi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pengpengdd.cyou/Article/details/gtgifvekwf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuetiantiany.cn/Article/details/gtwpmupzwh.html

JS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gtsflfehsk.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gtljwpdmae.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxuanxn.top/Article/details/gtisyrovxr.html

Go:   resp, err := http.Get(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtehhoohuc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.feifeiyinyue.top/Article/details/gtohnnezkf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhongyouzk.top/Article/details/gtrgiicoit.html

[L02] 发送 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gtymsjkuze.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnqzz.top/Article/details/gtbhuxdzim.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.daria6918.cn/Article/details/gtosllcwgz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gtbavumpsv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gtuwwtstxf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xziqi.cn/Article/details/gtebmxhmnc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.kuanghao11.cn/Article/details/gtcwjjsynr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenlongwang.top/Article/details/gtcivmrjls.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hywenlv.cn/Article/details/gtssfsldgw.html

[L03] 设置自定义请求头
来源：http://dali.yuxming.cn/Article/details/gtmqvwreji.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aizwys.cn/Article/details/gtaoywczge.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xziqi.cn/Article/details/gtnkohfavi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gtqsqrpioz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gtlgpvjdip.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhiwuduotai.top/Article/details/gtepzgzxuf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gtopifmkwq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhongyouzk.top/Article/details/gtrkoeanbn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgngpugua.html

[L04] 设置超时
来源：http://dali.nanxinkj.top/Article/details/gtbjwxmmoh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenjidiqi.icu/Article/details/gtvccvsqaa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tian-w.cn/Article/details/gthivevzoc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gtbraerlqb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gtdiymmyes.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.quarkkingdee.top/Article/details/gthqmlnohb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigfzy.top/Article/details/gtoxddcdwm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiltdaqsn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.316326.xyz/Article/details/gtlurjqcki.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gtwwrnzdvt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yvedp.cn/Article/details/gtebuvftle.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgfzy.top/Article/details/gtzqmjxcrp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gtvlycumpn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gteesnyuid.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.redwolf501.top/Article/details/gtelulsuur.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtbuhucvro.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ydzc1.top/Article/details/gtnoefpkxw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.smart0.xyz/Article/details/gteynbboqx.html

[L06] 解析响应为 JSON
来源：http://dali.jyoumei.cn/Article/details/gtjiiethfa.html

Py:   resp.json()
来源：http://dali.sweek.top/Article/details/gtkzmcicrk.html

PHP:  json_decode($body, true);
来源：http://dali.zdqjudy.top/Article/details/gtunzzahhm.html

JS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gtliahceyf.html

TS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtvfzrqcqn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtnyikdvgn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhengqikj.top/Article/details/gtvqpzbhqi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yvedp.cn/Article/details/gttjjpzxsk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangdashe.top/Article/details/gtmjweijcv.html

[L07] 处理 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gtqqyxwuex.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.svipenyu.cn/Article/details/gthvrkzydj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.mhx1999.top/Article/details/gtgpinuvxz.html

JS:   resp.ok;  resp.status
来源：http://dali.sufxvd.cn/Article/details/gtnsubcehi.html

TS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gtugmcjyif.html

Java: resp.statusCode()
来源：http://dali.wangshuangyany.cn/Article/details/gtqzuuyfzo.html

Go:   resp.StatusCode
来源：http://dali.sufxvd.cn/Article/details/gtetaqnvxc.html

Ruby: resp.code.to_i
来源：http://dali.hnqzz.top/Article/details/gtfjwdajlj.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtppowqmaq.html

[L08] 并发请求多个地址
来源：http://dali.aizwys.cn/Article/details/gtemjxspsh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jianghu66.top/Article/details/gtkqcahksz.html

PHP:  curl_multi_init() 系列
来源：http://dali.ydzc1.top/Article/details/gtlddgwgik.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtriuoabqk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gtuqhoffhh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sysykeji.top/Article/details/gtncmbfsrj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgufenzy.top/Article/details/gthznubhpa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guowangkeji.top/Article/details/gtmiooqawc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.snrcjt.cn/Article/details/gtougxnpxt.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gttqliggoj.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfegzhip.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtomdijuzw.html

[M01] 读取命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gtnwdnxtvx.html

Py:   sys.argv[1:]
来源：http://dali.yueranfly.top/Article/details/gtjrxgqhar.html

PHP:  $argv;  $argc;
来源：http://dali.haohaochexian.top/Article/details/gtueaialec.html

JS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gtyecwiafx.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtystggmrr.html

Java: args 数组（main 方法参数）
来源：http://dali.birdmap.top/Article/details/gtehxmckpo.html

Go:   os.Args[1:]
来源：http://dali.cucudq.cn/Article/details/gtokxuxywx.html

Ruby: ARGV
来源：http://dali.0kj1m.cn/Article/details/gtexvzjroc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gtbmztxvws.html

[M02] 读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gtjqzkinan.html

Py:   os.environ.get("HOME")
来源：http://dali.ivvv.top/Article/details/gtvntwokka.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gtiwwnodta.html

JS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gtqinylhpy.html

TS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtgjaechwp.html

Java: System.getenv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtigwplsyt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtkntqwszn.html

Ruby: ENV["HOME"]
来源：http://dali.wangdashe.top/Article/details/gtjhaipiou.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtkaorakuy.html

[M03] 执行外部命令
来源：http://dali.hysaishi.cn/Article/details/gttdfnatdr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daxiang520.top/Article/details/gtwjfhemou.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigfzy.top/Article/details/gtfmqznfeh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxyybddx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxjqktkd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nwbrower.top/Article/details/gtieywrdnx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daria6918.cn/Article/details/gtyoffncbm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yongpay.top/Article/details/gtaqfywvjy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aibaodan.cn/Article/details/gtgukacoxo.html

[M04] 获取当前工作目录
来源：http://dali.316326.xyz/Article/details/gtwhbnbwdb.html

Py:   os.getcwd()
来源：http://dali.gzhubu.top/Article/details/gtwfyjvbhe.html

PHP:  getcwd();
来源：http://dali.yuxming.cn/Article/details/gtsmuwgnzg.html

JS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gtlajeyoxg.html

TS:   process.cwd()
来源：http://dali.jianghu66.top/Article/details/gtxgzsppki.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zycfv.cn/Article/details/gtsiexqkkt.html

Go:   os.Getwd()
来源：http://dali.yj202588.top/Article/details/gtgjzumrox.html

Ruby: Dir.pwd
来源：http://dali.tanke756.top/Article/details/gtdlvpedgb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cdnleiting.top/Article/details/gthapnmmqq.html

[M05] 设置退出码
来源：http://dali.gaohongyu789.top/Article/details/gtaxhpfrrw.html

Py:   sys.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtxqjaausf.html

PHP:  exit(1);
来源：http://dali.redwolf501.top/Article/details/gttemsrzta.html

JS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtjmmtzask.html

TS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtuyxeiqjb.html

Java: System.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtjiqjvkxx.html

Go:   os.Exit(1)
来源：http://dali.xinyue.icu/Article/details/gtqyzqzkrz.html

Ruby: exit 1
来源：http://dali.sufxvd.cn/Article/details/gtrqglfqkn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhoulong.xyz/Article/details/gtlxyjdpxu.html

[M06] 向标准错误输出
来源：http://dali.zhongyouzk.top/Article/details/gtdykvhtor.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrobxchfr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sufxvd.cn/Article/details/gtzckeevks.html

JS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gtttswroxd.html

TS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gtkszlbikj.html

Java: System.err.println("err")
来源：http://dali.aizwys.cn/Article/details/gtegnedoxn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dianchejie.cn/Article/details/gtorarygdf.html

Ruby: warn "err"
来源：http://dali.haohaochexian.top/Article/details/gtjgyynqdi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ehwqpu.com/Article/details/gttanggbfj.html

[M07] 判断是否为主入口
来源：http://dali.xuetiantiany.cn/Article/details/gtolmhyktp.html

Py:   if __name__ == "__main__":
来源：http://dali.cdnleiting.top/Article/details/gtacajfsyc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.iojbl.cn/Article/details/gtqhmdkheb.html

JS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gtcyketcbe.html

TS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gtwobtpduj.html

Java: public static void main(String[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gtockzdegt.html

Go:   func main()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxxjtoho.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhongyouzk.top/Article/details/gtjajufyfk.html

C#:   static void Main(string[] args)
来源：http://dali.316326.xyz/Article/details/gtrqqusgel.html

[M08] 获取系统与运行时信息
来源：http://dali.xuetiantiany.cn/Article/details/gtakgxfzzc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cashguo.top/Article/details/gtqpnpvley.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yvedp.cn/Article/details/gtlnkhdqcs.html

JS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gtgyrwdllr.html

TS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gtgurhqnyh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnqzz.top/Article/details/gtreygeuci.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.meibo888.top/Article/details/gthhkpvgha.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangdashe.top/Article/details/gteencxtuy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangtech.top/Article/details/gtuowmuamt.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtqdqvucmu.html

N. 数据结构与算法
来源：http://dali.jinghuilouyu.cn/Article/details/gtabwpobxx.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtkwzbmwti.html

[N01] 二分查找（有序数组）
来源：http://dali.yj202588.top/Article/details/gtvupzqvsn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hammf.cn/Article/details/gtcctivtif.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtjsqjeuub.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gtebudzwil.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gtchhuolmq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gticmcargw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtyverhmke.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ydzc1.top/Article/details/gtxbqyjlbc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtmydqafkg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.bjfxy.top/Article/details/gtkxjucmjq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gtqzmpofiq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pycfn.com/Article/details/gtyxavlfaw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtlyezsiha.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtwvkjshsi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj202588.top/Article/details/gtrtcplzjt.html

Go:   slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtxgkuirbv.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gtrothkxab.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxuanxn.top/Article/details/gtzvbepwrl.html

[N03] 快速排序（分治示例）
来源：http://dali.c1oappe.top/Article/details/gtkmgxaxwc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tian-w.cn/Article/details/gtkqhfcrlu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhengqikj.top/Article/details/gteqwzqoei.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhehhlit.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcbdfwkp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.9152youxi.cn/Article/details/gtkurkohpy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gotoacloud.top/Article/details/gtwxgyhmkh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.0kj1m.cn/Article/details/gtjnlqtrup.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.redwolf501.top/Article/details/gtcbfsknhv.html

[N04] 斐波那契数列
来源：http://dali.gogol.net.cn/Article/details/gtaexzhgyq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gtmapqwjxw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gtfujgtzbc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthspkaqje.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gtpjgrkier.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuanzx.com/Article/details/gttuatfgjl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guowangkeji.top/Article/details/gtbksxetkt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gtdyyrpawx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtsurmomgy.html

[N05] 最大公约数
来源：http://dali.hysaishi.cn/Article/details/gtwzbtfcwi.html

Py:   math.gcd(a, b)
来源：http://dali.gzhubu.top/Article/details/gtgezcxaan.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.316326.xyz/Article/details/gtrwpnamxu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gtttfrezpn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gtiuyiesfp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yvedp.cn/Article/details/gtypxamezu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigfzy.top/Article/details/gtgcgmtfov.html

Ruby: a.gcd(b)
来源：http://dali.zycfv.cn/Article/details/gtqkrtabym.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gtbmxtkoet.html

[N06] 判断回文字符串
来源：http://dali.c1oappe.top/Article/details/gtkwwsytpb.html

Py:   s == s[::-1]
来源：http://dali.yonumen.top/Article/details/gtoaudhkgm.html

PHP:  $s === strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtofbvdniy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtfatfcpww.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtqabqvfmb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.snrcjt.cn/Article/details/gtsyqoymeq.html

Go:   // 双指针从两端比较
来源：http://dali.hysaishi.cn/Article/details/gtxxfojkbw.html

Ruby: s == s.reverse
来源：http://dali.sweek.top/Article/details/gtybymtele.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gtwsbyvvbt.html

[N07] 两数之和（返回下标）
来源：http://dali.iojbl.cn/Article/details/gtdmdrwfia.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhengqikj.top/Article/details/gtlkxfvqyu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gtehervclw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zycfv.cn/Article/details/gtwnmeugbj.html

TS:   // 手写 Map<string, number>
来源：http://dali.quarkkingdee.top/Article/details/gtzaskqkac.html

Java: // 手写 HashMap
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvldezid.html

Go:   // 手写 map[int]int
来源：http://dali.xuanzx.com/Article/details/gtoxgspljf.html

Ruby: // 手写 Hash
来源：http://dali.aibaodan.cn/Article/details/gtrotzegme.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.kuanghao11.cn/Article/details/gtixzynkfu.html

[N08] 生成全排列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaswkqrsm.html

Py:   itertools.permutations(arr)
来源：http://dali.yongpay.top/Article/details/gtwihapomp.html

PHP:  // 手写递归交换
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxdqivmb.html

JS:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtrxfwhwsx.html

TS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtkyxhopkr.html

Java: // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtnckcebkt.html

Go:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtvramzldf.html

Ruby: arr.permutation.to_a
来源：http://dali.svipenyu.cn/Article/details/gtjddqcfwn.html

C#:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gttiodgqym.html

[N09] 栈与队列
来源：http://dali.yj20258.top/Article/details/gtrsbzhkcd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtwvxcegwr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtlzwllsup.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gthzesmxaq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sufxvd.cn/Article/details/gtrnndbrwb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtikdfybuo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgfzy.top/Article/details/gtjoywaxir.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtxparqjoo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tianlin.xyz/Article/details/gtmsgmcscs.html

[N10] 链表节点定义
来源：http://dali.cqqwz.cn/Article/details/gtgnouipxa.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tianlin.xyz/Article/details/gtubocylwk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hysaishi.cn/Article/details/gtwjpfiyop.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fengsongda.top/Article/details/gtpjoetvrg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sweek.top/Article/details/gtcoxjxnwu.html

Java: class Node { int v; Node next; }
来源：http://dali.nwbrower.top/Article/details/gtnbtdlqek.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ivvv.top/Article/details/gtvrpashhd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tian-w.cn/Article/details/gteswiphmg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xinyue.icu/Article/details/gtgfzqrjnw.html

[N11] 二叉树中序遍历
来源：http://dali.zycfv.cn/Article/details/gtjouxjinl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dashuyun.cn/Article/details/gthzzsyiib.html

PHP:  // 手写递归函数
来源：http://dali.yanxiufei.cn/Article/details/gtmefevkog.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gtvhbmwuqx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gtixsjwlnz.html

Java: // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtznagppea.html

Go:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtidfqjmol.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhiwuduotai.top/Article/details/gtcndwyymt.html

C#:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtlcgicxov.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigfzy.top/Article/details/gtsnvwnmfo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgfzy.top/Article/details/gtvvycspam.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pengpengdd.cyou/Article/details/gteitdgnak.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gtxgpttqsw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gtexqwommm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigufen.top/Article/details/gtekpxlrin.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jianghu66.top/Article/details/gtafygslne.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.0kj1m.cn/Article/details/gtiybfvshs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gaohongyu789.top/Article/details/gtjemsaubp.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtukhpghfz.html

O. 并发与异步
来源：http://dali.iojbl.cn/Article/details/gtuhtrxcql.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtnpahkdwj.html

[O01] 启动一个线程
来源：http://dali.jinqigfzy.top/Article/details/gtfrrnrxtt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxuanxn.top/Article/details/gtovhytdbk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxinkj.top/Article/details/gtszytxgmi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ybcxt.top/Article/details/gtsauqowxr.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gtelxnhmde.html

Java: new Thread(() -> f()).start()
来源：http://dali.gotoacloud.top/Article/details/gtqnyhhulb.html

Go:   go f()
来源：http://dali.ybcxt.top/Article/details/gtewmemjgq.html

Ruby: Thread.new { f }
来源：http://dali.smart0.xyz/Article/details/gtbhjmbppt.html

C#:   Task.Run(() => F());
来源：http://dali.mhx1999.top/Article/details/gtvqqpfkdb.html

[O02] 使用线程池
来源：http://dali.ybcxt.top/Article/details/gttvadnixk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cashguo.top/Article/details/gtmwdxkezm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.kuanghao11.cn/Article/details/gtnklxutkg.html

JS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gtgwxfefcd.html

TS:   // worker_threads 线程池
来源：http://dali.sxryk.cn/Article/details/gtquvysxup.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aibaodan.cn/Article/details/gtljkvktta.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnxiangtu.top/Article/details/gtslrusmri.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tanke756.top/Article/details/gtjojxyerq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.birdmap.top/Article/details/gtcezdxacx.html

[O03] 加锁保护共享数据
来源：http://dali.pycfn.com/Article/details/gtduvaawdk.html

Py:   with lock: shared += 1
来源：http://dali.dianchejie.cn/Article/details/gtoftyfvfz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.9152youxi.cn/Article/details/gtpzjvogdy.html


<!-- 参考信息 -->