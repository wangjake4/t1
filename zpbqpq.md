代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shangyingyoupin.top/Article/details/gtrrzdbwsb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtzrjudenj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hongshengwenyu.top/Article/details/gtdldozprn.html

Py:   pickle.dumps(obj)
来源：http://dali.chenlongwang.top/Article/details/gtlbrckeah.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jiagoushi.top/Article/details/gtpxahfvcr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gtbmqrnoms.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.guannengcc.top/Article/details/gtaxcsoauo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fzhhl.top/Article/details/gttniubceu.html

Go:   encoding/gob
来源：http://dali.redwolf501.top/Article/details/gtvyfhlxgn.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtmtdbcalz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gtfcjrqwis.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtnenjlhai.html

L. 网络请求
来源：http://dali.zhoulong.xyz/Article/details/gtfvsyysrr.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtskivzodw.html

[L01] 发送 GET 请求
来源：http://dali.yongpay.top/Article/details/gtcqeodgel.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxvixukl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cashguo.top/Article/details/gtfhwavgzg.html

JS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gtmyvalmvr.html

TS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gtxlfjaoqv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daxiang520.top/Article/details/gtzarlnesy.html

Go:   resp, err := http.Get(url)
来源：http://dali.9152youxi.cn/Article/details/gtcxomhyjh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yongpay.top/Article/details/gtguoyzaty.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtcyushxeb.html

[L02] 发送 POST JSON
来源：http://dali.daxiang520.top/Article/details/gtojujyfaj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zycfv.cn/Article/details/gtycoidcxg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cheryme.top/Article/details/gtvivprsgg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jianghu66.top/Article/details/gtmcejougr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gtncwvnksb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pycfn.com/Article/details/gtjpyptirv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gzhubu.top/Article/details/gtpyeffsqt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gaohongyu789.top/Article/details/gtlcmfvwqr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tanke756.top/Article/details/gtrjhbleuy.html

[L03] 设置自定义请求头
来源：http://dali.shzxlz.cn/Article/details/gthukkprtx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xylfe.cn/Article/details/gtusbiqdwp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ehwqpu.com/Article/details/gtnasuwwqv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gtmttxjzpr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gtbqfawmzp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj202588.top/Article/details/gtlpzuvgpc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gtxkftkgvs.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hammf.cn/Article/details/gtrafeunxn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gtfzihxtyx.html

[L04] 设置超时
来源：http://dali.nwbrower.top/Article/details/gtncgivydu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqaazyxxi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.iojbl.cn/Article/details/gtelvdtjvt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zycfv.cn/Article/details/gtcapthlkv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gtmbwnvvja.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jiagoushi.top/Article/details/gtqrgmkphp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sxryk.cn/Article/details/gttjxwzdjh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.snrcjt.cn/Article/details/gtxpntaedl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fzhhl.top/Article/details/gtilwrurpy.html

[L05] 上传文件（multipart）
来源：http://dali.pengpengdd.cyou/Article/details/gtzvzjhkgv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tanke756.top/Article/details/gtnhdgqekc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhongyouzk.top/Article/details/gtpuxmztef.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gthlwhywol.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtkothrfac.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.redwolf501.top/Article/details/gthsvgzith.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ivvv.top/Article/details/gtnbbwhsac.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.quarkkingdee.top/Article/details/gteowbrlxw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifovwpyn.html

[L06] 解析响应为 JSON
来源：http://dali.yvedp.cn/Article/details/gtbqtnvjqw.html

Py:   resp.json()
来源：http://dali.havefunace.top/Article/details/gtvyeufled.html

PHP:  json_decode($body, true);
来源：http://dali.bjfxy.top/Article/details/gthrmarpyd.html

JS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gtwcfgcpcg.html

TS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtchamfpbn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkepkelec.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yvedp.cn/Article/details/gtmntdpdab.html

Ruby: JSON.parse(resp.body)
来源：http://dali.andypj.xyz/Article/details/gtbcyjnjlc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.bjfxy.top/Article/details/gtshduxosw.html

[L07] 处理 HTTP 状态码
来源：http://dali.fengsongda.top/Article/details/gtcturghgq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cqqwz.cn/Article/details/gtnhkkqrzk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gotoacloud.top/Article/details/gtywiwwsoq.html

JS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gtatpjvlxb.html

TS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gtwmogvbug.html

Java: resp.statusCode()
来源：http://dali.kuanghao11.cn/Article/details/gtmvmljotz.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtzmyndmob.html

Ruby: resp.code.to_i
来源：http://dali.nwbrower.top/Article/details/gtcvyhunfm.html

C#:   (int)resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gtxvalpsdd.html

[L08] 并发请求多个地址
来源：http://dali.cashguo.top/Article/details/gtthzzelds.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258888.top/Article/details/gteqqtlebh.html

PHP:  curl_multi_init() 系列
来源：http://dali.jyoumei.cn/Article/details/gtxxioxuvc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gthxutwpok.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gtwpnfpswl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.svipenyu.cn/Article/details/gtoktpnzfx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yanxiufei.cn/Article/details/gtsfpbmqjk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.snrcjt.cn/Article/details/gtwhpbvfrc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.smart0.xyz/Article/details/gtnfgpbvlb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtjdofttbi.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj202588.top/Article/details/gtuqitcjmc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtxylutjax.html

[M01] 读取命令行参数
来源：http://dali.iojbl.cn/Article/details/gtzrudrjvj.html

Py:   sys.argv[1:]
来源：http://dali.iojbl.cn/Article/details/gthkfrkeaj.html

PHP:  $argv;  $argc;
来源：http://dali.cashguo.top/Article/details/gtntgqiekp.html

JS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gtafzcdugv.html

TS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gtaxlfbgkf.html

Java: args 数组（main 方法参数）
来源：http://dali.yj202588.top/Article/details/gtmhgfntub.html

Go:   os.Args[1:]
来源：http://dali.yvedp.cn/Article/details/gtvppkzyrk.html

Ruby: ARGV
来源：http://dali.0kj1m.cn/Article/details/gtjhbbrxlw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gtdjnzunmr.html

[M02] 读取环境变量
来源：http://dali.xziqi.cn/Article/details/gtbbihfsfn.html

Py:   os.environ.get("HOME")
来源：http://dali.daria6918.cn/Article/details/gtzpwbtero.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gtfuqwsytx.html

JS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gttubowtvn.html

TS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtzhkstquj.html

Java: System.getenv("HOME")
来源：http://dali.aizwys.cn/Article/details/gtxefbyoeg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtmflglicz.html

Ruby: ENV["HOME"]
来源：http://dali.zycfv.cn/Article/details/gtworxuocy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtxaqywdmd.html

[M03] 执行外部命令
来源：http://dali.xuanzx.com/Article/details/gtrshgpbkq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jyoumei.cn/Article/details/gtmkgrerul.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jianghu66.top/Article/details/gtemqkhqij.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gtbyvutkzw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gtfmzyjliz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aizwys.cn/Article/details/gtwxkfetal.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zycfv.cn/Article/details/gtfeyggojg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.vqdsnc.cn/Article/details/gtnnzawewp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.kuanghao11.cn/Article/details/gtchgpahbb.html

[M04] 获取当前工作目录
来源：http://dali.cheryme.top/Article/details/gtfnxlhxvq.html

Py:   os.getcwd()
来源：http://dali.yj20258.top/Article/details/gtuydeiruv.html

PHP:  getcwd();
来源：http://dali.ybcxt.top/Article/details/gtfnxatnpi.html

JS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gtfciktizj.html

TS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gthxhuwsls.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenzaomai.com/Article/details/gtztyvkrqe.html

Go:   os.Getwd()
来源：http://dali.cdnleiting.top/Article/details/gtxjtxjjjm.html

Ruby: Dir.pwd
来源：http://dali.birdmap.top/Article/details/gtzaxivtjq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnxiangtu.top/Article/details/gtckjxsrvn.html

[M05] 设置退出码
来源：http://dali.wangdashe.top/Article/details/gtimlzekgv.html

Py:   sys.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtrolzhmfd.html

PHP:  exit(1);
来源：http://dali.gotoacloud.top/Article/details/gtmrzvxesu.html

JS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtmqkpiqhk.html

TS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtdblvyaxd.html

Java: System.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtnhgldjcx.html

Go:   os.Exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtzwbcsohv.html

Ruby: exit 1
来源：http://dali.zycfv.cn/Article/details/gtdaclmlho.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zdqjudy.top/Article/details/gticbgavyv.html

[M06] 向标准错误输出
来源：http://dali.chenlongwang.top/Article/details/gtqpsevwyx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gtoxzbeaug.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.vqdsnc.cn/Article/details/gtbedoxdml.html

JS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gthsohpcyr.html

TS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gtxmdminsv.html

Java: System.err.println("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtnefhqv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yonumen.top/Article/details/gtrzguebwz.html

Ruby: warn "err"
来源：http://dali.yuxming.cn/Article/details/gtvvwwmlcl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yanxiufei.cn/Article/details/gtcvhsxxim.html

[M07] 判断是否为主入口
来源：http://dali.jqgfzy.top/Article/details/gtpmrddrcq.html

Py:   if __name__ == "__main__":
来源：http://dali.xuanzx.com/Article/details/gtuzizdicp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xziqi.cn/Article/details/gtemdfsemq.html

JS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gtjjwynmsd.html

TS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gtzsowwaoy.html

Java: public static void main(String[] args)
来源：http://dali.zhongyouzk.top/Article/details/gtypgikkxq.html

Go:   func main()
来源：http://dali.hnqzz.top/Article/details/gtynlwrjmy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yueranfly.top/Article/details/gtckmiefvy.html

C#:   static void Main(string[] args)
来源：http://dali.sysykeji.top/Article/details/gtxgglruct.html

[M08] 获取系统与运行时信息
来源：http://dali.gaohongyu789.top/Article/details/gtsjeqowhw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guowangkeji.top/Article/details/gtwylkobnm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sxryk.cn/Article/details/gtrwrxsrri.html

JS:   process.platform;  process.version
来源：http://dali.hnxiangtu.top/Article/details/gtvdfparxd.html

TS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gtdjswrqcz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.snrcjt.cn/Article/details/gtlvtcumuv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gogol.net.cn/Article/details/gtsefxeexx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hfpthk.cn/Article/details/gtzejamdsm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hfpthk.cn/Article/details/gtryhtnptp.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtmiyjfobp.html

N. 数据结构与算法
来源：http://dali.shangyingyoupin.top/Article/details/gtbiagwgny.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtygknmbqm.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gtegsxvzad.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ivvv.top/Article/details/gtltxbtpiu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangdashe.top/Article/details/gtnlfrsrdn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtlytqhiks.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtjjwdvqre.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtgupsvszp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtcimypfxc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkulxqdf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsuvdpmsh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pycfn.com/Article/details/gtnmrnqhmy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ehwqpu.com/Article/details/gtybwaewfx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cheryme.top/Article/details/gtobhhsvzh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gtiiafqbft.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gthmsnjtxg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuetiantiany.cn/Article/details/gtoiwyshot.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyeqpwbas.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gtsenyhrer.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zdqjudy.top/Article/details/gtxothoxgz.html

[N03] 快速排序（分治示例）
来源：http://dali.kuanghao11.cn/Article/details/gtmptzhzrp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hywenlv.cn/Article/details/gtstirboyb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuanzhike.top/Article/details/gtrhjxflcb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gtmibcmevr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gtfqpikkfq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daxiang520.top/Article/details/gtfqdbcmwz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangshuangyany.cn/Article/details/gtugqdeejx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenlongwang.top/Article/details/gtaxzahtkc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zycfv.cn/Article/details/gtnoxbsmhc.html

[N04] 斐波那契数列
来源：http://dali.cqqwz.cn/Article/details/gtsbbgnzao.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiyieclol.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gtbmpuqocs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtbvuwexrw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtvftomlwt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.redwolf501.top/Article/details/gthoqmpzdy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.kuanghao11.cn/Article/details/gtybkpcbof.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gteturtydl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtaqenjewt.html

[N05] 最大公约数
来源：http://dali.sysykeji.top/Article/details/gtntfzksce.html

Py:   math.gcd(a, b)
来源：http://dali.shzxlz.cn/Article/details/gtolawkqcb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tanke756.top/Article/details/gtsfpvnswe.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtrxclckgl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gtjolgkglv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258888.top/Article/details/gteqajqfcy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.mhx1999.top/Article/details/gtnhqwouap.html

Ruby: a.gcd(b)
来源：http://dali.guowangkeji.top/Article/details/gtaeluemdg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.quarkkingdee.top/Article/details/gtbdppxymj.html

[N06] 判断回文字符串
来源：http://dali.guannengcc.top/Article/details/gtmoycwosu.html

Py:   s == s[::-1]
来源：http://dali.ydzc1.top/Article/details/gtrwgbbdkz.html

PHP:  $s === strrev($s);
来源：http://dali.hammf.cn/Article/details/gtlkubraov.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtagyjlirh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtpsmjuqzm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yvedp.cn/Article/details/gtxkhvhrlv.html

Go:   // 双指针从两端比较
来源：http://dali.jqgufenzy.top/Article/details/gtpesnaaic.html

Ruby: s == s.reverse
来源：http://dali.ydzc1.top/Article/details/gtmqwegzba.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gtaqorwjzx.html

[N07] 两数之和（返回下标）
来源：http://dali.sweek.top/Article/details/gtvrsqdpwd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.bjfxy.top/Article/details/gthideokrn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jianghu66.top/Article/details/gthktagrwh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yongpay.top/Article/details/gtefwvumbw.html

TS:   // 手写 Map<string, number>
来源：http://dali.yanxiufei.cn/Article/details/gtrmjhkzin.html

Java: // 手写 HashMap
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpuwlpido.html

Go:   // 手写 map[int]int
来源：http://dali.andypj.xyz/Article/details/gttxyhxwop.html

Ruby: // 手写 Hash
来源：http://dali.fzhhl.top/Article/details/gtegopphcy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.iojbl.cn/Article/details/gtduzfswnp.html

[N08] 生成全排列
来源：http://dali.yuxming.cn/Article/details/gtrnrcopcx.html

Py:   itertools.permutations(arr)
来源：http://dali.hammf.cn/Article/details/gtakqzzeln.html

PHP:  // 手写递归交换
来源：http://dali.gogol.net.cn/Article/details/gtzxovtixy.html

JS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtnozlwjbx.html

TS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gttyuyevwb.html

Java: // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtrnzotacg.html

Go:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtuuzluttz.html

Ruby: arr.permutation.to_a
来源：http://dali.shangyingyoupin.top/Article/details/gtxrewybrf.html

C#:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtqnbxgqck.html

[N09] 栈与队列
来源：http://dali.andypj.xyz/Article/details/gtolddmtgz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yonumen.top/Article/details/gtswyirpbk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gtbeqckzgf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtbklezybq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jiagoushi.top/Article/details/gtgekgcnew.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cqqwz.cn/Article/details/gthisgipri.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.0kj1m.cn/Article/details/gtksqzuctt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gtvuinneng.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dianchejie.cn/Article/details/gtfmjeataq.html

[N10] 链表节点定义
来源：http://dali.shzxlz.cn/Article/details/gtontisylb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tian-w.cn/Article/details/gtkqqdnenq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dashuyun.cn/Article/details/gtkbhxgpiy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tianlin.xyz/Article/details/gtceoqxtly.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.kuanghao11.cn/Article/details/gtqqgdyvma.html

Java: class Node { int v; Node next; }
来源：http://dali.guannengcc.top/Article/details/gtqaquodsn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jiagoushi.top/Article/details/gtxfdtwbpi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xinyue.icu/Article/details/gtxuvfljqr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgfzy.top/Article/details/gtqowmknyl.html

[N11] 二叉树中序遍历
来源：http://dali.aibaodan.cn/Article/details/gthemlphog.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hammf.cn/Article/details/gtlovqlaro.html

PHP:  // 手写递归函数
来源：http://dali.ivvv.top/Article/details/gtacxxmhuc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gtxahgawyk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gtoktcgegm.html

Java: // 手写递归
来源：http://dali.nwbrower.top/Article/details/gtludcudjj.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gtmlfvpyvm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xinyue.icu/Article/details/gtavegucpl.html

C#:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtfpcivbqk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fengsongda.top/Article/details/gtnfxzlvka.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.dashuyun.cn/Article/details/gtuyktchel.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.daria6918.cn/Article/details/gtyjanmkav.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfvrofsk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gtdtbnpdwu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtntcnmnos.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yangfankeji.com/Article/details/gtbfyxsmun.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258888.top/Article/details/gthqyagdqb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gtddukkrcj.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtkgsqwsbn.html

O. 并发与异步
来源：http://dali.nwbrower.top/Article/details/gtjcbzwhiw.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtwftafzgt.html

[O01] 启动一个线程
来源：http://dali.shzxlz.cn/Article/details/gtwjggcqfa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gzhubu.top/Article/details/gtmdzzmrjg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fzhhl.top/Article/details/gtzlrybfda.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hongshengwenyu.top/Article/details/gtxzyxmlkx.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gtszmslzso.html

Java: new Thread(() -> f()).start()
来源：http://dali.pycfn.com/Article/details/gtuiycahir.html

Go:   go f()
来源：http://dali.daria6918.cn/Article/details/gtzmgckmlz.html

Ruby: Thread.new { f }
来源：http://dali.xuanzx.com/Article/details/gtbtnnzxtc.html

C#:   Task.Run(() => F());
来源：http://dali.fengsongda.top/Article/details/gtltttdqxd.html

[O02] 使用线程池
来源：http://dali.zhengqikj.top/Article/details/gtszqqokla.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnqzz.top/Article/details/gtodarhgab.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenzaomai.com/Article/details/gtitbonkrc.html

JS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gtweyyrroh.html

TS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gtejbbxbva.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hammf.cn/Article/details/gtctrjrcjj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cqqwz.cn/Article/details/gtzulejbej.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yonumen.top/Article/details/gttonlouqv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangshuangyany.cn/Article/details/gtxcwdzjgq.html

[O03] 加锁保护共享数据
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmgxqpfn.html

Py:   with lock: shared += 1
来源：http://dali.9152youxi.cn/Article/details/gtdnmmsusj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xuetiantiany.cn/Article/details/gtxstibgkq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cqqwz.cn/Article/details/gtirxlbbwd.html

TS:   // 同 JS
来源：http://dali.chenzaomai.com/Article/details/gtzgjmjata.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhrnwasu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.kuanghao11.cn/Article/details/gtztmmrdtg.html


<!-- 参考信息 -->