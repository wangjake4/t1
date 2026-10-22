代发 wailian999

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cheryme.top/Article/details/gt2neyydwer.html

JS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gt2tomdbjbx.html

TS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wtgooiqh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigufen.top/Article/details/gt2gqfwebsz.html

Go:   resp, err := http.Get(url)
来源：http://dali.andypj.xyz/Article/details/gt2dzfotcmn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nanxinkj.top/Article/details/gt2wcpkeszn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yonumen.top/Article/details/gt2rloayayp.html

[L02] 发送 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gt2xxdogkcu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gt2tibvcplk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.smart0.xyz/Article/details/gt2imrkmjhl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gt2rpzxidad.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gt2ukirmtrn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.mhx1999.top/Article/details/gt2xyolqnng.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigufen.top/Article/details/gt2avhtykrn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ehwqpu.com/Article/details/gt2hrundsqr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cashguo.top/Article/details/gt2dabplryq.html

[L03] 设置自定义请求头
来源：http://dali.cheryme.top/Article/details/gt2vfedjpbu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.mhx1999.top/Article/details/gt2thnutdkc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sufxvd.cn/Article/details/gt2ayuyksso.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gt2pbbffihc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gt2vinxpqmr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jianghu66.top/Article/details/gt2xwxsqqju.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gt2kaygzwjh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hongshengwenyu.top/Article/details/gt2nccendqe.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2arwxygqr.html

[L04] 设置超时
来源：http://dali.nwbrower.top/Article/details/gt2lxnlxayf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenzaomai.com/Article/details/gt2gpgddxsa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shuidangran.top/Article/details/gt2ykvduzsr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vbdxshik.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gt2kglbkrqg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhixingplan.top/Article/details/gt2pwbinixl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gt2guipdmnw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigufen.top/Article/details/gt2eebzyncd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zdqjudy.top/Article/details/gt2hlqxvbvl.html

[L05] 上传文件（multipart）
来源：http://dali.kuanghao11.cn/Article/details/gt2ifrjhfmx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.feifeiyinyue.top/Article/details/gt2ubsjpcfz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.quarkkingdee.top/Article/details/gt2bykkvgpg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gt2ucpqmbvs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gt2jtwyeqld.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yanxiufei.cn/Article/details/gt2impjirbp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2ksgstxzy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.snrcjt.cn/Article/details/gt2yvedvnii.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cheryme.top/Article/details/gt2xiptxgjp.html

[L06] 解析响应为 JSON
来源：http://dali.gzhubu.top/Article/details/gt2swzqogxn.html

Py:   resp.json()
来源：http://dali.meibo888.top/Article/details/gt2mtrddhmi.html

PHP:  json_decode($body, true);
来源：http://dali.yonumen.top/Article/details/gt2rpxarbkg.html

JS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gt2sgwggnnw.html

TS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gt2kcpkifjf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daxiang520.top/Article/details/gt2gekffrbe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yangfankeji.com/Article/details/gt2urwvbtlo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgufenzy.top/Article/details/gt2dudrqfiw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ltyhvnjf.html

[L07] 处理 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gt2cwxamxwp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuanzhike.top/Article/details/gt2zszuuhro.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tian-w.cn/Article/details/gt2hfnzhjvo.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gt2teiexmtb.html

TS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gt2rghmiigj.html

Java: resp.statusCode()
来源：http://dali.shzxlz.cn/Article/details/gt2nvdxailh.html

Go:   resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gt2ymcxymuc.html

Ruby: resp.code.to_i
来源：http://dali.chenzaomai.com/Article/details/gt2rmvbtdqc.html

C#:   (int)resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gt2iqameiyk.html

[L08] 并发请求多个地址
来源：http://dali.gotoacloud.top/Article/details/gt2olrgfqux.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnxiangtu.top/Article/details/gt2zdyktcrm.html

PHP:  curl_multi_init() 系列
来源：http://dali.aibaodan.cn/Article/details/gt2mwhagbzb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gt2rahmahea.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gt2ezykikfo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sxryk.cn/Article/details/gt2fcesytai.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.redwolf501.top/Article/details/gt2ziieqwra.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zycfv.cn/Article/details/gt2hdbhgdel.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gt2gznwuuxg.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2eftnmpjq.html

M. 命令行 / 进程 / 环境
来源：http://dali.dianchejie.cn/Article/details/gt2jodzhupi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lifrtkww.html

[M01] 读取命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gt2sozlxnfq.html

Py:   sys.argv[1:]
来源：http://dali.jinqigufen.top/Article/details/gt2yidnwmxt.html

PHP:  $argv;  $argc;
来源：http://dali.meibo888.top/Article/details/gt2prmxdrtl.html

JS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gt2uhrkymht.html

TS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gt2imqlclzo.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258.top/Article/details/gt2okfmafnx.html

Go:   os.Args[1:]
来源：http://dali.dashuyun.cn/Article/details/gt2lldsgjdc.html

Ruby: ARGV
来源：http://dali.0kj1m.cn/Article/details/gt2zdyjfrmv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wngqtmuk.html

[M02] 读取环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2cfjtyvxq.html

Py:   os.environ.get("HOME")
来源：http://dali.tianlin.xyz/Article/details/gt2ktnmbixd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gt2rhxpgjim.html

JS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gt2xdeeydxp.html

TS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gt2utqhjtvy.html

Java: System.getenv("HOME")
来源：http://dali.fengsongda.top/Article/details/gt2wdncqzlj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2jwrztqds.html

Ruby: ENV["HOME"]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tjuvyxhc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.mhx1999.top/Article/details/gt2sgabrtxd.html

[M03] 执行外部命令
来源：http://dali.sxryk.cn/Article/details/gt2vvsiztlq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.kuanghao11.cn/Article/details/gt2dssliiob.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.vqdsnc.cn/Article/details/gt2vleiphvq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gt2udrekvrz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2nhhadwum.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.havefunace.top/Article/details/gt2dlpqivyu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jiagoushi.top/Article/details/gt2xybmccgt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shangyingyoupin.top/Article/details/gt2mfetvwxw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xinyue.icu/Article/details/gt2lviuhzps.html

[M04] 获取当前工作目录
来源：http://dali.svipenyu.cn/Article/details/gt2skqwphmj.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2vafsjsue.html

PHP:  getcwd();
来源：http://dali.andypj.xyz/Article/details/gt2qstfgiqo.html

JS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gt2vftbvkhj.html

TS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gt2lztyijmc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hysaishi.cn/Article/details/gt2cgyfdtrn.html

Go:   os.Getwd()
来源：http://dali.cashguo.top/Article/details/gt2baqgnlbq.html

Ruby: Dir.pwd
来源：http://dali.quarkkingdee.top/Article/details/gt2uwbqudad.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj202588.top/Article/details/gt2nwpdbuzb.html

[M05] 设置退出码
来源：http://dali.zycfv.cn/Article/details/gt2trvmmnuo.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoceqvax.html

PHP:  exit(1);
来源：http://dali.xinyue.icu/Article/details/gt2ghrlkkxg.html

JS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vnzmdtkj.html

TS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zttgzqhg.html

Java: System.exit(1)
来源：http://dali.xylfe.cn/Article/details/gt2ruhfaket.html

Go:   os.Exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2zbsxhgyj.html

Ruby: exit 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2gqarjodn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cqqwz.cn/Article/details/gt2gcdbwocu.html

[M06] 向标准错误输出
来源：http://dali.vqdsnc.cn/Article/details/gt2urcxwiad.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgfzy.top/Article/details/gt2pacudmhg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tianlin.xyz/Article/details/gt2rtmowobw.html

JS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gt2yvvaxryp.html

TS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gt2neorqsoa.html

Java: System.err.println("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ysblgqjn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ybcxt.top/Article/details/gt2txnwxedt.html

Ruby: warn "err"
来源：http://dali.sufxvd.cn/Article/details/gt2xzwbiifu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.andypj.xyz/Article/details/gt2jbjdlbrm.html

[M07] 判断是否为主入口
来源：http://dali.sysykeji.top/Article/details/gt2ebofcxay.html

Py:   if __name__ == "__main__":
来源：http://dali.zhixingplan.top/Article/details/gt2jwrjnlzv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj202588.top/Article/details/gt2dxzszkbb.html

JS:   require.main === module
来源：http://dali.cqqwz.cn/Article/details/gt2ncnrdxrc.html

TS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gt2fenmgzra.html

Java: public static void main(String[] args)
来源：http://dali.snrcjt.cn/Article/details/gt2pcwubckb.html

Go:   func main()
来源：http://dali.jinqigufen.top/Article/details/gt2smibsguw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cqqwz.cn/Article/details/gt2ponlizik.html

C#:   static void Main(string[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zdgchvau.html

[M08] 获取系统与运行时信息
来源：http://dali.tanke756.top/Article/details/gt2yxkzaxnx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258.top/Article/details/gt2dolevqdb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.9152youxi.cn/Article/details/gt2raqbnupb.html

JS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gt2ifvmrgaf.html

TS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gt2wseviagt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangdashe.top/Article/details/gt2nlsiscab.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cqqwz.cn/Article/details/gt2revpknwb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangshuangyany.cn/Article/details/gt2yrcbzozf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnqzz.top/Article/details/gt2bxzugzqi.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2xzzjlphz.html

N. 数据结构与算法
来源：http://dali.fengsongda.top/Article/details/gt2gksbzwtt.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2lpjmwcwk.html

[N01] 二分查找（有序数组）
来源：http://dali.0kj1m.cn/Article/details/gt2mrcebtam.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2mhmaqbqw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.mhx1999.top/Article/details/gt2pmypqllq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gt2kiaepyme.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gt2sopqyyzg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2zpfwnsvr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2comkwbpx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sxryk.cn/Article/details/gt2wmkjtain.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2ikszdxsa.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aibaodan.cn/Article/details/gt2lcsfgqtm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gt2vpbjqjek.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zdqjudy.top/Article/details/gt2xwwlkynt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gt2yjnbezya.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gt2apekiytu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guowangkeji.top/Article/details/gt2bstljizh.html

Go:   slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2gqdfnkcy.html

Ruby: arr.sort
来源：http://dali.xuanzx.com/Article/details/gt2ldkvbnrn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pycfn.com/Article/details/gt2aevqofwz.html

[N03] 快速排序（分治示例）
来源：http://dali.guowangkeji.top/Article/details/gt2otwauamh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sufxvd.cn/Article/details/gt2heisyfnr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zycfv.cn/Article/details/gt2boohlqvj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gt2iegnfbbu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gt2xkxzivqt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fzhhl.top/Article/details/gt2uspunujx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.meibo888.top/Article/details/gt2ryvxwrvp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ybcxt.top/Article/details/gt2ypmccjvq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guowangkeji.top/Article/details/gt2hpfvbwmd.html

[N04] 斐波那契数列
来源：http://dali.tian-w.cn/Article/details/gt2lrbymsbq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gt2xpjnkqvf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qijjieml.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2tbavewfr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gt2ildhjopy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gt2bbcemlib.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cqqwz.cn/Article/details/gt2shdcyjgw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gt2rywzjyhl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gt2lzqsvhxg.html

[N05] 最大公约数
来源：http://dali.yanxiufei.cn/Article/details/gt2opqfbiyy.html

Py:   math.gcd(a, b)
来源：http://dali.gzhubu.top/Article/details/gt2tynscmgz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.316326.xyz/Article/details/gt2yzlqobbc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gt2dkefwiua.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gt2fgnssnna.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sxryk.cn/Article/details/gt2kkdmxtmd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zdqjudy.top/Article/details/gt2wbdtnewa.html

Ruby: a.gcd(b)
来源：http://dali.hfpthk.cn/Article/details/gt2ldnmbfii.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.mhx1999.top/Article/details/gt2jbtxhbjn.html

[N06] 判断回文字符串
来源：http://dali.xziqi.cn/Article/details/gt2nszygarb.html

Py:   s == s[::-1]
来源：http://dali.hammf.cn/Article/details/gt2fjiclubo.html

PHP:  $s === strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gt2erzgadmw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gt2sfujeqmv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gt2lwuqicpw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yonumen.top/Article/details/gt2vbrvssph.html

Go:   // 双指针从两端比较
来源：http://dali.ppjwa.cn/Article/details/gt2ctoteucx.html

Ruby: s == s.reverse
来源：http://dali.yvedp.cn/Article/details/gt2inntvrhh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gt2ngrvtbzg.html

[N07] 两数之和（返回下标）
来源：http://dali.guannengcc.top/Article/details/gt2jjbeqxnp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.redwolf501.top/Article/details/gt2lubxwxwy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jianghu66.top/Article/details/gt2efngjnfs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nwbrower.top/Article/details/gt2uggdbcke.html

TS:   // 手写 Map<string, number>
来源：http://dali.daria6918.cn/Article/details/gt2psagdjsq.html

Java: // 手写 HashMap
来源：http://dali.gaohongyu789.top/Article/details/gt2bwvbfxzn.html

Go:   // 手写 map[int]int
来源：http://dali.quarkkingdee.top/Article/details/gt2homdjpjy.html

Ruby: // 手写 Hash
来源：http://dali.ppjwa.cn/Article/details/gt2cmdilsxz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yuxming.cn/Article/details/gt2grlunzqa.html

[N08] 生成全排列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2izlwfuim.html

Py:   itertools.permutations(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2osbrovwm.html

PHP:  // 手写递归交换
来源：http://dali.svipenyu.cn/Article/details/gt2lxjrlegx.html

JS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gt2mgjfybqn.html

TS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2icnnrurf.html

Java: // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gt2nvmugwlm.html

Go:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2pdbqcmcb.html

Ruby: arr.permutation.to_a
来源：http://dali.jlsjyb.cn/Article/details/gt2ktijvvrx.html

C#:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gt2hgyidiip.html

[N09] 栈与队列
来源：http://dali.zhixingplan.top/Article/details/gt2pwnmkqfe.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hywenlv.cn/Article/details/gt2rddlrcgh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gt2uqnlfqxa.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gt2fmvxtbuj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fzhhl.top/Article/details/gt2bpnyhzqq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gt2ghemnliu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zycfv.cn/Article/details/gt2lptylnzu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gt2naurseww.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xziqi.cn/Article/details/gt2sbzrfoec.html

[N10] 链表节点定义
来源：http://dali.fengsongda.top/Article/details/gt2rtfnjhjt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shangyingyoupin.top/Article/details/gt2vkwlxwyz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aizwys.cn/Article/details/gt2rzthplbz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jyoumei.cn/Article/details/gt2gupcrohd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xylfe.cn/Article/details/gt2raheyqnr.html

Java: class Node { int v; Node next; }
来源：http://dali.dashuyun.cn/Article/details/gt2qoczlzzb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jlsjyb.cn/Article/details/gt2vjqtfofj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.meibo888.top/Article/details/gt2bhhyupjp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fzhhl.top/Article/details/gt2xumuuino.html

[N11] 二叉树中序遍历
来源：http://dali.bjfxy.top/Article/details/gt2veqmtaty.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.wangshuangyany.cn/Article/details/gt2myjhuzcq.html

PHP:  // 手写递归函数
来源：http://dali.cheryme.top/Article/details/gt2mwhiboyf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.havefunace.top/Article/details/gt2tewlbnov.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fengsongda.top/Article/details/gt2xjqzuwze.html

Java: // 手写递归
来源：http://dali.iojbl.cn/Article/details/gt2pjtfzmub.html

Go:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gt2rnjemjvk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gotoacloud.top/Article/details/gt2qldywrly.html

C#:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mpxmexki.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhixingplan.top/Article/details/gt2kkfzebzs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cucudq.cn/Article/details/gt2nzqatfyk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aizwys.cn/Article/details/gt2pgocxjrg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gt2olwcwgqd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gt2ksfttycu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.kuanghao11.cn/Article/details/gt2sprqdhdo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.smart0.xyz/Article/details/gt2luiwbctj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.tian-w.cn/Article/details/gt2htdrtbyj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.kuanghao11.cn/Article/details/gt2vmrjbopv.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dcfcfjil.html

O. 并发与异步
来源：http://dali.yj20258888.top/Article/details/gt2pahhrwlg.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2styjxcfv.html

[O01] 启动一个线程
来源：http://dali.yanxiufei.cn/Article/details/gt2alfnuhli.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.redwolf501.top/Article/details/gt2yovepjdl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2lhshhoxl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cucudq.cn/Article/details/gt2fezokgtp.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gt2sisryhjy.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pytqbjmc.html

Go:   go f()
来源：http://dali.haohaochexian.top/Article/details/gt2cyowdgkq.html

Ruby: Thread.new { f }
来源：http://dali.havefunace.top/Article/details/gt2dkmubdgk.html

C#:   Task.Run(() => F());
来源：http://dali.yongpay.top/Article/details/gt2snjsuwda.html

[O02] 使用线程池
来源：http://dali.gotoacloud.top/Article/details/gt2isdzwnaz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jlsjyb.cn/Article/details/gt2dwkccfum.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenlongwang.top/Article/details/gt2jbifraud.html

JS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gt2aqzeflye.html

TS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gt2lkcyxaxh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fnudczxq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zdqjudy.top/Article/details/gt2zqoandpp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinqigufen.top/Article/details/gt2zuwhotqi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258.top/Article/details/gt2vapwrcme.html

[O03] 加锁保护共享数据
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fvperqyj.html

Py:   with lock: shared += 1
来源：http://dali.jiagoushi.top/Article/details/gt2drcsbszq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sweek.top/Article/details/gt2asfrkzzn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.mhx1999.top/Article/details/gt2ulvytdso.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gt2nxaiwqgy.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zuktwvgd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yueranfly.top/Article/details/gt2avpaowtp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.fzhhl.top/Article/details/gt2zopneeeo.html

C#:   lock (gate) { shared++; }
来源：http://dali.bjfxy.top/Article/details/gt2tlzntjaz.html

[O04] 定义异步函数并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gt2brwjpucq.html

Py:   async def f():⏎    await g()
来源：http://dali.smart0.xyz/Article/details/gt2rsikcono.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinqigfzy.top/Article/details/gt2uupuybhb.html

JS:   async function f() { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gt2qdxfzypw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.havefunace.top/Article/details/gt2yqjtvcsd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yueranfly.top/Article/details/gt2gtzpqzxy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxinkj.top/Article/details/gt2yoihuztt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.iojbl.cn/Article/details/gt2zrfsscdq.html

C#:   async Task F() { await G(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zqkkoiso.html

[O05] 并发执行并等待全部完成
来源：http://dali.hongshengwenyu.top/Article/details/gt2egwhfthj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigfzy.top/Article/details/gt2igxflqtb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.vqdsnc.cn/Article/details/gt2uandgctd.html

JS:   await Promise.all(tasks)
来源：http://dali.xziqi.cn/Article/details/gt2colvvqlv.html

TS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gt2vyzidrtw.html


<!-- 参考信息 -->