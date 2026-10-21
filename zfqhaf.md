代发 wailian999

Go:   resp, err := http.Get(url)
来源：http://dali.jiagoushi.top/Article/details/gtpwumppqv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daria6918.cn/Article/details/gtuntgsboj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yangfankeji.com/Article/details/gtedshabxn.html

[L02] 发送 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gthpolpzxp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gtacaylptr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.iojbl.cn/Article/details/gtjiwprbkh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gtxvtovxkx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gtemksrfnf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgfzy.top/Article/details/gtihmqssub.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyhfrcdy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258888.top/Article/details/gtpjmodkkl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shuidangran.top/Article/details/gtvvkzoprc.html

[L03] 设置自定义请求头
来源：http://dali.iojbl.cn/Article/details/gtwpljkjwa.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.0kj1m.cn/Article/details/gtkhdrspwf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.andypj.xyz/Article/details/gtksfrmkqf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gtbwwivjlx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gtvgvnuyhg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.andypj.xyz/Article/details/gtkhowuczl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gtxozzzyet.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenzaomai.com/Article/details/gtzfkoncxf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglbnjscw.html

[L04] 设置超时
来源：http://dali.gogol.net.cn/Article/details/gtvwosqdeg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258.top/Article/details/gtbbzymift.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hfpthk.cn/Article/details/gtzonpeqjt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gotoacloud.top/Article/details/gtwkskryyw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gtjoyfciqd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hfpthk.cn/Article/details/gtrvrpmvsf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.svipenyu.cn/Article/details/gtjlzaoqta.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuanzhike.top/Article/details/gtmwzalrlk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gthluvkpqd.html

[L05] 上传文件（multipart）
来源：http://dali.ydzc1.top/Article/details/gthrylasbk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hongshengwenyu.top/Article/details/gtuidtxfum.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tianlin.xyz/Article/details/gtmarqajji.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gtxxgzdfdq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gtnwmdyvbk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sufxvd.cn/Article/details/gthecmgyrr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zdqjudy.top/Article/details/gtxeafmrwc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdakwusf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yongpay.top/Article/details/gtdffzjunw.html

[L06] 解析响应为 JSON
来源：http://dali.gzhubu.top/Article/details/gtjstukgmq.html

Py:   resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtcolybkbp.html

PHP:  json_decode($body, true);
来源：http://dali.fzhhl.top/Article/details/gtknqggevr.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gtppqotppi.html

TS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtrhwoajzc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrtjmfqi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhengqikj.top/Article/details/gtttmdzkhb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hongshengwenyu.top/Article/details/gtxgwsdnzx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgulbcif.html

[L07] 处理 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gtqnpjrnxi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.bjfxy.top/Article/details/gtcufqinpc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgfzy.top/Article/details/gthkfngimp.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtymiwziwb.html

TS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtwbrjddui.html

Java: resp.statusCode()
来源：http://dali.redwolf501.top/Article/details/gtkgcdxynp.html

Go:   resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtywhxxkgb.html

Ruby: resp.code.to_i
来源：http://dali.yj20258.top/Article/details/gtebacfcpp.html

C#:   (int)resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gtmliilhov.html

[L08] 并发请求多个地址
来源：http://dali.hfpthk.cn/Article/details/gtqlbfdpii.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajydctzq.html

PHP:  curl_multi_init() 系列
来源：http://dali.ppjwa.cn/Article/details/gtusokvsuu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtwodzknim.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtgbetlahj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yueranfly.top/Article/details/gtlyxfuulv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyapmfpqb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gtgcqoxlif.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtabkvupru.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtuogtxzea.html

M. 命令行 / 进程 / 环境
来源：http://dali.pengpengdd.cyou/Article/details/gtqzktwogf.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtinbkboph.html

[M01] 读取命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtftvqpqxu.html

Py:   sys.argv[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtdfcyjvqu.html

PHP:  $argv;  $argc;
来源：http://dali.sysykeji.top/Article/details/gthbpgibej.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyqpeydw.html

TS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gtacvwudwq.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258.top/Article/details/gtdkmyxniu.html

Go:   os.Args[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjvqneoc.html

Ruby: ARGV
来源：http://dali.aizwys.cn/Article/details/gtovqkfrqv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gtthycgovq.html

[M02] 读取环境变量
来源：http://dali.chenzaomai.com/Article/details/gtyxmqkxpx.html

Py:   os.environ.get("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtjldjvqco.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.havefunace.top/Article/details/gtdtwlbvgm.html

JS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtokriujxo.html

TS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gtslghjvff.html

Java: System.getenv("HOME")
来源：http://dali.iojbl.cn/Article/details/gtljsodyxs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtmpnbqhbs.html

Ruby: ENV["HOME"]
来源：http://dali.gotoacloud.top/Article/details/gteulmicyp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fengsongda.top/Article/details/gtiatfipzj.html

[M03] 执行外部命令
来源：http://dali.tanke756.top/Article/details/gthqxazhcg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yongpay.top/Article/details/gtahckemwl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shuidangran.top/Article/details/gtevxtbwju.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtuhfcdtzx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gtvgxfrnem.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuanzhike.top/Article/details/gtzxgdbmwq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guowangkeji.top/Article/details/gtctfppqch.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dashuyun.cn/Article/details/gtuvtlokww.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ydzc1.top/Article/details/gttbbgngqu.html

[M04] 获取当前工作目录
来源：http://dali.fzhhl.top/Article/details/gtspixbmye.html

Py:   os.getcwd()
来源：http://dali.shzxlz.cn/Article/details/gthfnxetaz.html

PHP:  getcwd();
来源：http://dali.hnxiangtu.top/Article/details/gtdtiociky.html

JS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gtxtpqaaea.html

TS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gtwsuggbjq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daxiang520.top/Article/details/gtuurlqdzd.html

Go:   os.Getwd()
来源：http://dali.fengsongda.top/Article/details/gthkdiqkdu.html

Ruby: Dir.pwd
来源：http://dali.zhiwuduotai.top/Article/details/gtennclsth.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sufxvd.cn/Article/details/gtvixavxfr.html

[M05] 设置退出码
来源：http://dali.0kj1m.cn/Article/details/gtfednvnye.html

Py:   sys.exit(1)
来源：http://dali.yonumen.top/Article/details/gtzlargmeu.html

PHP:  exit(1);
来源：http://dali.svipenyu.cn/Article/details/gtikypoolq.html

JS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtrvkjzvlp.html

TS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gthoucllzs.html

Java: System.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtyxkjciws.html

Go:   os.Exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtebqauugr.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gtcoyvgixp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daria6918.cn/Article/details/gtguswcuty.html

[M06] 向标准错误输出
来源：http://dali.hnqzz.top/Article/details/gtyrlyzzgx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hammf.cn/Article/details/gtngslhrhi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yonumen.top/Article/details/gtubxqrpue.html

JS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gtavutqzrw.html

TS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gtozarsqfw.html

Java: System.err.println("err")
来源：http://dali.hysaishi.cn/Article/details/gtqzrdlprx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gtaqwuazhh.html

Ruby: warn "err"
来源：http://dali.zycfv.cn/Article/details/gtclnnylbn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tian-w.cn/Article/details/gtvbtqzylm.html

[M07] 判断是否为主入口
来源：http://dali.yuanzhike.top/Article/details/gtynwhylfo.html

Py:   if __name__ == "__main__":
来源：http://dali.sufxvd.cn/Article/details/gtsvuciirz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnxiangtu.top/Article/details/gtfaypdadt.html

JS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtjhtjqech.html

TS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gtdmecgkhb.html

Java: public static void main(String[] args)
来源：http://dali.redwolf501.top/Article/details/gtymsaindf.html

Go:   func main()
来源：http://dali.xuetiantiany.cn/Article/details/gtggfkgvao.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.0kj1m.cn/Article/details/gtwwzwwxxb.html

C#:   static void Main(string[] args)
来源：http://dali.fzhhl.top/Article/details/gtzrvtnmoi.html

[M08] 获取系统与运行时信息
来源：http://dali.gzhubu.top/Article/details/gtugfitjog.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ppjwa.cn/Article/details/gtlbovmvic.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgfzy.top/Article/details/gtsxnvvzxv.html

JS:   process.platform;  process.version
来源：http://dali.yuanzhike.top/Article/details/gtscdmghxb.html

TS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gtbbolbkqf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangshuangyany.cn/Article/details/gtpzrlfcau.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhoulong.xyz/Article/details/gtoomexniq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fengsongda.top/Article/details/gtbckallos.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.0kj1m.cn/Article/details/gtwgbccfgg.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtwwfqfqhc.html

N. 数据结构与算法
来源：http://dali.dianchejie.cn/Article/details/gtknthltug.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtdazdkfei.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258888.top/Article/details/gtlmagxtuq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtsbhqufsn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtogbindmu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yueranfly.top/Article/details/gttpzmqueq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtdviyujdb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtwaqmqskn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtfipmaigh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangshuangyany.cn/Article/details/gthzeooykh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtocxvoybf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoeivfols.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtzjzvhmft.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yangfankeji.com/Article/details/gtdmiguncj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gtbwnmjwhh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gtgsbpwlct.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gotoacloud.top/Article/details/gtuixzdltw.html

Go:   slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gtfshmaevk.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gtgfitibjs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zycfv.cn/Article/details/gtoeigktdh.html

[N03] 快速排序（分治示例）
来源：http://dali.wangdashe.top/Article/details/gtbyrwpmfw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthexvvdw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tian-w.cn/Article/details/gttdzoikbi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gtbaoppdyc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tian-w.cn/Article/details/gtwgjeaelz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuanzhike.top/Article/details/gtdirdguom.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gogol.net.cn/Article/details/gtpvbbjreu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zdqjudy.top/Article/details/gttcsipaio.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zdqjudy.top/Article/details/gteeahbfvu.html

[N04] 斐波那契数列
来源：http://dali.haohaochexian.top/Article/details/gtxsrtcunq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtajpufjdf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gtwvtgravm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtgnlkgaph.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtmnutcdmo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gtkldqmdjo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj202588.top/Article/details/gttdtpqrgl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gtyzezysta.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtxigawqpy.html

[N05] 最大公约数
来源：http://dali.c1oappe.top/Article/details/gtqspjbpsk.html

Py:   math.gcd(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtnjpkobgd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtebxdovue.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gthkscnrpr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gtrpjafqkh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhixingplan.top/Article/details/gtxmyksjxi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sufxvd.cn/Article/details/gtlxaerbej.html

Ruby: a.gcd(b)
来源：http://dali.zhongyouzk.top/Article/details/gtbrtmoogo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhengqikj.top/Article/details/gtcadzepfe.html

[N06] 判断回文字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrrvwxih.html

Py:   s == s[::-1]
来源：http://dali.ydzc1.top/Article/details/gtxlzifnzt.html

PHP:  $s === strrev($s);
来源：http://dali.ydzc1.top/Article/details/gtyycapbmr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtznbgrwqr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtzovtgoyn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangtech.top/Article/details/gtmfoyespq.html

Go:   // 双指针从两端比较
来源：http://dali.cdnleiting.top/Article/details/gtmcpkeial.html

Ruby: s == s.reverse
来源：http://dali.jiagoushi.top/Article/details/gtunaktnlr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gtfbufoqud.html

[N07] 两数之和（返回下标）
来源：http://dali.yj202588.top/Article/details/gtcpwzcget.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.kuanghao11.cn/Article/details/gtcudhhfnl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.quarkkingdee.top/Article/details/gtfmwljeso.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuanzhike.top/Article/details/gtpzwxvkre.html

TS:   // 手写 Map<string, number>
来源：http://dali.feifeiyinyue.top/Article/details/gtdefufojy.html

Java: // 手写 HashMap
来源：http://dali.smart0.xyz/Article/details/gtygitipfs.html

Go:   // 手写 map[int]int
来源：http://dali.jinghuilouyu.cn/Article/details/gtmyyebnpg.html

Ruby: // 手写 Hash
来源：http://dali.aibaodan.cn/Article/details/gtbxgzulyy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuanzx.com/Article/details/gtriazpwri.html

[N08] 生成全排列
来源：http://dali.zhengqikj.top/Article/details/gtqlkywjzj.html

Py:   itertools.permutations(arr)
来源：http://dali.fzhhl.top/Article/details/gtphbnepkn.html

PHP:  // 手写递归交换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdgxrfnq.html

JS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtuselvrsi.html

TS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtopiuyeuu.html

Java: // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtokrayzzp.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtoafrayyq.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gtvllnoket.html

C#:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtmqajioun.html

[N09] 栈与队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtgcoldc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhengqikj.top/Article/details/gtapxgkfxv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhprhmxr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtvgylaemv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jianghu66.top/Article/details/gtghpmvtsw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.bjfxy.top/Article/details/gtljqwynnc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezftregu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtgcddqblc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258.top/Article/details/gtngnnuwbh.html

[N10] 链表节点定义
来源：http://dali.jqgfzy.top/Article/details/gtgclappog.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258888.top/Article/details/gtpwtjzihi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dianchejie.cn/Article/details/gtdsqjowfk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hywenlv.cn/Article/details/gtslwgvmqt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigufen.top/Article/details/gtaenubhqx.html

Java: class Node { int v; Node next; }
来源：http://dali.smart0.xyz/Article/details/gtohvndews.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.feifeiyinyue.top/Article/details/gtdstaxezd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gogol.net.cn/Article/details/gtwkvdeior.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.316326.xyz/Article/details/gtnrjwbbxz.html

[N11] 二叉树中序遍历
来源：http://dali.bjfxy.top/Article/details/gtrtjroqwv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.redwolf501.top/Article/details/gtpxziqewx.html

PHP:  // 手写递归函数
来源：http://dali.hnqzz.top/Article/details/gtmebieayn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtalhpkvyw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gtcthjekhe.html

Java: // 手写递归
来源：http://dali.xuanzx.com/Article/details/gttbhgwtxg.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtydxctbxh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gogol.net.cn/Article/details/gtqgzutysa.html

C#:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gtyaerrbvn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.birdmap.top/Article/details/gtuoymsqvg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.c1oappe.top/Article/details/gtbkqdtyfp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.wangdashe.top/Article/details/gtothivmlg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuetiantiany.cn/Article/details/gtanjnixvc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenlongwang.top/Article/details/gtbirhljzb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gtscmnzmxl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvxjzijl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fengsongda.top/Article/details/gtftmlmyzr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gtdstfvkug.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtgxmwtmlt.html

O. 并发与异步
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybzdvrwl.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtfenezqvt.html

[O01] 启动一个线程
来源：http://dali.kuanghao11.cn/Article/details/gtshzoxgae.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fengsongda.top/Article/details/gtbdwwsoyn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuxming.cn/Article/details/gtthzauilb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.haohaochexian.top/Article/details/gtbjjcotfx.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gtwvqqykwi.html

Java: new Thread(() -> f()).start()
来源：http://dali.xylfe.cn/Article/details/gtpwswtbsj.html

Go:   go f()
来源：http://dali.hammf.cn/Article/details/gtcugzarpj.html

Ruby: Thread.new { f }
来源：http://dali.zycfv.cn/Article/details/gtiexrkixt.html

C#:   Task.Run(() => F());
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwdqtbyb.html

[O02] 使用线程池
来源：http://dali.hnxiangtu.top/Article/details/gtgcqnujin.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.havefunace.top/Article/details/gtnvbuysem.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.meibo888.top/Article/details/gtrjrkkopr.html

JS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gtgnaxhrrk.html

TS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gtyxxfauqw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pycfn.com/Article/details/gtcjkoztkh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.bjfxy.top/Article/details/gtuvqzhvow.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shuidangran.top/Article/details/gtxbvfnrbt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cucudq.cn/Article/details/gtrkxigwoc.html

[O03] 加锁保护共享数据
来源：http://dali.gotoacloud.top/Article/details/gtkbrekeme.html

Py:   with lock: shared += 1
来源：http://dali.cqqwz.cn/Article/details/gtkmkscbnb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.svipenyu.cn/Article/details/gthlgrfzzv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shangyingyoupin.top/Article/details/gtkptmuynf.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtptzjhleu.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gthpepdwds.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shzxlz.cn/Article/details/gtcqvblwfu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cdnleiting.top/Article/details/gtomjhdgcs.html

C#:   lock (gate) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gtogcmuitb.html

[O04] 定义异步函数并等待
来源：http://dali.zhoulong.xyz/Article/details/gturioyfsr.html

Py:   async def f():⏎    await g()
来源：http://dali.guannengcc.top/Article/details/gtijbxylvy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttantajm.html

JS:   async function f() { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfylukvke.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gtwixxaffj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangdashe.top/Article/details/gtmhpjpoja.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgufenzy.top/Article/details/gtzetckdae.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj20258888.top/Article/details/gtcjecfchw.html

C#:   async Task F() { await G(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntfjwmsq.html

[O05] 并发执行并等待全部完成
来源：http://dali.316326.xyz/Article/details/gthagndyzw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.andypj.xyz/Article/details/gtvewzzhdk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jqgfzy.top/Article/details/gthumiswcv.html

JS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gtwkhyhmay.html

TS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gtjpavcxlx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ydzc1.top/Article/details/gtmlarepky.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcgxyknj.html

Ruby: threads.map(&:join)
来源：http://dali.andypj.xyz/Article/details/gtgwpertgo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangdashe.top/Article/details/gtneoxwuom.html


<!-- 参考信息 -->