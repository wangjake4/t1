代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gt2bwsurytc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hsqbtaas.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gt2wpbsiomw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgufenzy.top/Article/details/gt2wnwnxvtp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gt2mhwsqalx.html

[L04] 设置超时
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ayavjvpx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhongyouzk.top/Article/details/gt2tajcxyzs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.dashuyun.cn/Article/details/gt2vjlcyvdm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gt2thgervfb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zmsijemd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhengqikj.top/Article/details/gt2zoluhefa.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.c1oappe.top/Article/details/gt2jhyeohnr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gaohongyu789.top/Article/details/gt2zvwfsunf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guannengcc.top/Article/details/gt2pykdbmot.html

[L05] 上传文件（multipart）
来源：http://dali.ivvv.top/Article/details/gt2vwrskeyf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nwbrower.top/Article/details/gt2opqkxxph.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.316326.xyz/Article/details/gt2wuwbncie.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gt2cdnxdzml.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2peedkupy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hongshengwenyu.top/Article/details/gt2mxzkmspf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sxryk.cn/Article/details/gt2cshzbqve.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yangfankeji.com/Article/details/gt2qpjpgglp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2qkqklqdd.html

[L06] 解析响应为 JSON
来源：http://dali.gzhubu.top/Article/details/gt2ikyyzhhm.html

Py:   resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2fzikonmw.html

PHP:  json_decode($body, true);
来源：http://dali.hnxiangtu.top/Article/details/gt2wtyseizw.html

JS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gt2yyopaohf.html

TS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gt2ggwqcwlq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuanzx.com/Article/details/gt2aluslwar.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.vqdsnc.cn/Article/details/gt2svxjfwmq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xziqi.cn/Article/details/gt2gebxfamf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shuidangran.top/Article/details/gt2xevthylv.html

[L07] 处理 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gt2nngxrwbs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yonumen.top/Article/details/gt2tpvdebwr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenjidiqi.icu/Article/details/gt2qeturfce.html

JS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gt2bmrwaznh.html

TS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gt2bdbjlquo.html

Java: resp.statusCode()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jtrzuwpg.html

Go:   resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gt2jlvtnmxr.html

Ruby: resp.code.to_i
来源：http://dali.jianghu66.top/Article/details/gt2lkkcytdm.html

C#:   (int)resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gt2qvzuqcza.html

[L08] 并发请求多个地址
来源：http://dali.jianghu66.top/Article/details/gt2ohycswsk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hongshengwenyu.top/Article/details/gt2pueqenjg.html

PHP:  curl_multi_init() 系列
来源：http://dali.fzhhl.top/Article/details/gt2kzxsaeqo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gt2fjgfnbur.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gt2xzzbzere.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2eraysjus.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hysaishi.cn/Article/details/gt2zotdcdbg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gt2rhrmmmjk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2ecyhhfnn.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2xspwzqik.html

M. 命令行 / 进程 / 环境
来源：http://dali.ehwqpu.com/Article/details/gt2krnxrmrl.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2elcmfbki.html

[M01] 读取命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2bzqbaxex.html

Py:   sys.argv[1:]
来源：http://dali.ydzc1.top/Article/details/gt2pjddncgk.html

PHP:  $argv;  $argc;
来源：http://dali.xuanzx.com/Article/details/gt2iowymjdu.html

JS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gt2afofhhey.html

TS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gt2mhiszfeh.html

Java: args 数组（main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gt2bfxbralq.html

Go:   os.Args[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2kgvdxqcp.html

Ruby: ARGV
来源：http://dali.aibaodan.cn/Article/details/gt2robwlaeb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gt2cvnwqebp.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gt2qzseicqi.html

Py:   os.environ.get("HOME")
来源：http://dali.yuanzhike.top/Article/details/gt2krxwecgc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ubggnysi.html

JS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gt2olyfbmpr.html

TS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gt2qnfhdrsq.html

Java: System.getenv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gt2vwayayea.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zycfv.cn/Article/details/gt2wdjrfyzo.html

Ruby: ENV["HOME"]
来源：http://dali.aibaodan.cn/Article/details/gt2utljiies.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sxryk.cn/Article/details/gt2jdtnjgsh.html

[M03] 执行外部命令
来源：http://dali.aizwys.cn/Article/details/gt2rojzelku.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.bjfxy.top/Article/details/gt2ymxeacyd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258888.top/Article/details/gt2emoagnhq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gt2jnftlwfx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gt2flqchrgj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ivvv.top/Article/details/gt2yqzlywhl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.andypj.xyz/Article/details/gt2euzidzbm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ydzc1.top/Article/details/gt2ccmfiote.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hammf.cn/Article/details/gt2tyvzxlhj.html

[M04] 获取当前工作目录
来源：http://dali.yangfankeji.com/Article/details/gt2amkgdktz.html

Py:   os.getcwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2vblxxunv.html

PHP:  getcwd();
来源：http://dali.aibaodan.cn/Article/details/gt2cllfihhy.html

JS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gt2xfhohoxo.html

TS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gt2ichvdvtk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hywenlv.cn/Article/details/gt2ynugebvm.html

Go:   os.Getwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vpkonppx.html

Ruby: Dir.pwd
来源：http://dali.ehwqpu.com/Article/details/gt2sszvpiey.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.bjfxy.top/Article/details/gt2uefkfesn.html

[M05] 设置退出码
来源：http://dali.jinqigfzy.top/Article/details/gt2ydprravu.html

Py:   sys.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2jibdxdae.html

PHP:  exit(1);
来源：http://dali.cqqwz.cn/Article/details/gt2oxodbtmq.html

JS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2avqfyyas.html

TS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gt2rkjqahhl.html

Java: System.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bgjtahmb.html

Go:   os.Exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2uqrmcahn.html

Ruby: exit 1
来源：http://dali.sxryk.cn/Article/details/gt2tatvjsvh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rfrghybg.html

[M06] 向标准错误输出
来源：http://dali.sweek.top/Article/details/gt2njtkyxxv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gt2lvvbcmrs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhiwuduotai.top/Article/details/gt2escixvdu.html

JS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gt2jtxfdvzj.html

TS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gt2gtsyakxr.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gt2owjrgzqn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gzhubu.top/Article/details/gt2upmkeaao.html

Ruby: warn "err"
来源：http://dali.xuanzx.com/Article/details/gt2tmeyodvt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fzhhl.top/Article/details/gt2jxkbqkpa.html

[M07] 判断是否为主入口
来源：http://dali.hysaishi.cn/Article/details/gt2bhkkjnvf.html

Py:   if __name__ == "__main__":
来源：http://dali.mhx1999.top/Article/details/gt2lsruorqm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuanzhike.top/Article/details/gt2sgkilmrp.html

JS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2respjocj.html

TS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gt2hstuygyt.html

Java: public static void main(String[] args)
来源：http://dali.0kj1m.cn/Article/details/gt2javtxmgo.html

Go:   func main()
来源：http://dali.cashguo.top/Article/details/gt2pblziytp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.andypj.xyz/Article/details/gt2fpvocqtt.html

C#:   static void Main(string[] args)
来源：http://dali.hywenlv.cn/Article/details/gt2lqaekwho.html

[M08] 获取系统与运行时信息
来源：http://dali.kuanghao11.cn/Article/details/gt2pfqmrkow.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xinyue.icu/Article/details/gt2nlcpdniw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gt2bmdkyuni.html

JS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gt2nsfhrkij.html

TS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gt2dmrpvhpn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cbqxzcrx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ivvv.top/Article/details/gt2saictyys.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gogol.net.cn/Article/details/gt2hezaqfyl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258888.top/Article/details/gt2tvrajjlo.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2bznzdxwd.html

N. 数据结构与算法
来源：http://dali.birdmap.top/Article/details/gt2xbzhgwfj.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lxlfqohr.html

[N01] 二分查找（有序数组）
来源：http://dali.shzxlz.cn/Article/details/gt2pimvyjza.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2tmfndwsd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tianlin.xyz/Article/details/gt2vuoxpsfh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gt2oxpafosd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gt2vrznenqf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gt2qellweuk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jmomlahu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jlsjyb.cn/Article/details/gt2lyaljnky.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2ltmwyjkk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cashguo.top/Article/details/gt2bnkgyzri.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gotoacloud.top/Article/details/gt2ivlisqit.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cqqwz.cn/Article/details/gt2piwbwebs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gt2pqcfzkrt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gt2mjhaxppe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dashuyun.cn/Article/details/gt2lrwsftib.html

Go:   slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gt2djdcsiwt.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gt2uzbmwokf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daria6918.cn/Article/details/gt2ztbyoruf.html

[N03] 快速排序（分治示例）
来源：http://dali.jlsjyb.cn/Article/details/gt2pwkyoysr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.havefunace.top/Article/details/gt2yfyubrdr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yueranfly.top/Article/details/gt2fbvhacku.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gt2lwaajvyt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gt2jjqohtds.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ydzc1.top/Article/details/gt2utjxasip.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.haohaochexian.top/Article/details/gt2pvrlumea.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangdashe.top/Article/details/gt2xbcmfdni.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.smart0.xyz/Article/details/gt2zoepfrqb.html

[N04] 斐波那契数列
来源：http://dali.316326.xyz/Article/details/gt2vsdtvjrc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gt2dnninuif.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xinyue.icu/Article/details/gt2ldjbciwz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gt2qhnrteyz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gt2lxyrphsk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gzhubu.top/Article/details/gt2pmrsbxyr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cheryme.top/Article/details/gt2zsckpavl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gt2pjvfdmng.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gt2vuhnduml.html

[N05] 最大公约数
来源：http://dali.bjfxy.top/Article/details/gt2jiypgtgc.html

Py:   math.gcd(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2joshnyll.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hysaishi.cn/Article/details/gt2kxcvjeky.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gt2zyhzgonu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eftfoegx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yvedp.cn/Article/details/gt2sevomcfy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daxiang520.top/Article/details/gt2qizmwxss.html

Ruby: a.gcd(b)
来源：http://dali.ydzc1.top/Article/details/gt2rfzdoezx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.iojbl.cn/Article/details/gt2akxiabma.html

[N06] 判断回文字符串
来源：http://dali.nanxinkj.top/Article/details/gt2fkwgabqe.html

Py:   s == s[::-1]
来源：http://dali.ppjwa.cn/Article/details/gt2runkzibu.html

PHP:  $s === strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2dkbhqedi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gt2eanwdmeg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gt2bxgmgvfq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xylfe.cn/Article/details/gt2rngijqef.html

Go:   // 双指针从两端比较
来源：http://dali.gotoacloud.top/Article/details/gt2xktyoygo.html

Ruby: s == s.reverse
来源：http://dali.mhx1999.top/Article/details/gt2gomrcxjw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gt2jxglfryc.html

[N07] 两数之和（返回下标）
来源：http://dali.snrcjt.cn/Article/details/gt2iihthtet.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.bjfxy.top/Article/details/gt2nmoyodmb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xylfe.cn/Article/details/gt2ihdphedc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wnvgynpp.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2itfuybuj.html

Java: // 手写 HashMap
来源：http://dali.havefunace.top/Article/details/gt2sekkulii.html

Go:   // 手写 map[int]int
来源：http://dali.shuidangran.top/Article/details/gt2getnqrnk.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gijdvomy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fodonrsq.html

[N08] 生成全排列
来源：http://dali.cdnleiting.top/Article/details/gt2fhqvzsxk.html

Py:   itertools.permutations(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xvpqpccw.html

PHP:  // 手写递归交换
来源：http://dali.daria6918.cn/Article/details/gt2rfbkhive.html

JS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2ycihrlxz.html

TS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2bbsmjidi.html

Java: // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2ulqzyfvs.html

Go:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gt2eecsfloz.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gt2scdvwlzo.html

C#:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2dgyvumkm.html

[N09] 栈与队列
来源：http://dali.hfpthk.cn/Article/details/gt2rkkstqya.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hfpthk.cn/Article/details/gt2wzqfdojf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xziqi.cn/Article/details/gt2woofiszc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuxming.cn/Article/details/gt2yvwwicur.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tanke756.top/Article/details/gt2vjmooobi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gt2olfjhyrr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ppjwa.cn/Article/details/gt2lybzbqdq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gt2ouphsymj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gt2mvtiditp.html

[N10] 链表节点定义
来源：http://dali.cqqwz.cn/Article/details/gt2imeyydti.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258.top/Article/details/gt2igyguxqe.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnqzz.top/Article/details/gt2tydftczl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hysaishi.cn/Article/details/gt2cnfdqcxf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj202588.top/Article/details/gt2bierhvql.html

Java: class Node { int v; Node next; }
来源：http://dali.xuanzx.com/Article/details/gt2smlpvmyf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.bjfxy.top/Article/details/gt2qwjbidxj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ydyktizf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.smart0.xyz/Article/details/gt2gqhiraup.html

[N11] 二叉树中序遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nlazzdgc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pycfn.com/Article/details/gt2lamoxcww.html

PHP:  // 手写递归函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pguukbma.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gt2yxwzxvnu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gt2rzwbwroh.html

Java: // 手写递归
来源：http://dali.ydzc1.top/Article/details/gt2ypqrcjmj.html

Go:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gt2wpdxywfy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guowangkeji.top/Article/details/gt2lbqehhfg.html

C#:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gt2eahcejts.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daria6918.cn/Article/details/gt2lnkruutw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sxryk.cn/Article/details/gt2xyictudf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.daxiang520.top/Article/details/gt2vngwvyvc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gt2ssuaxllv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vggcedeb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gt2jzqlwkfd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ytkmddft.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ivvv.top/Article/details/gt2luabiiuo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gt2aeniyxok.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2rqtcriln.html

O. 并发与异步
来源：http://dali.yj20258.top/Article/details/gt2gegvzsgg.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2wtlqjfrq.html

[O01] 启动一个线程
来源：http://dali.haohaochexian.top/Article/details/gt2jslehxbf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gaohongyu789.top/Article/details/gt2dbozogae.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ivvv.top/Article/details/gt2ijhrwexd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cqqwz.cn/Article/details/gt2ufpkaixj.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gt2nxuyhnhz.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuxming.cn/Article/details/gt2ndbocfhn.html

Go:   go f()
来源：http://dali.9152youxi.cn/Article/details/gt2ierdywzn.html

Ruby: Thread.new { f }
来源：http://dali.mhx1999.top/Article/details/gt2sumwwman.html

C#:   Task.Run(() => F());
来源：http://dali.zhiwuduotai.top/Article/details/gt2lbdshluz.html

[O02] 使用线程池
来源：http://dali.xuetiantiany.cn/Article/details/gt2ilogcixd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.chenlongwang.top/Article/details/gt2khifbslz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sufxvd.cn/Article/details/gt2wsduswpu.html

JS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gt2knmonpnk.html

TS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gt2khgsyorx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hammf.cn/Article/details/gt2ftqtabjh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yangfankeji.com/Article/details/gt2xrpncjbr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jlsjyb.cn/Article/details/gt2urfrvecx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258888.top/Article/details/gt2zrrwbeye.html

[O03] 加锁保护共享数据
来源：http://dali.tianlin.xyz/Article/details/gt2cgqwunks.html

Py:   with lock: shared += 1
来源：http://dali.quarkkingdee.top/Article/details/gt2tevxqmyu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258888.top/Article/details/gt2uxwlnaok.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ntywuplr.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gt2ffulsjlf.html

Java: synchronized (this) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gt2lvuydjqw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuanzhike.top/Article/details/gt2osarbzxn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cucudq.cn/Article/details/gt2mbidwttu.html

C#:   lock (gate) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dcimljky.html

[O04] 定义异步函数并等待
来源：http://dali.dianchejie.cn/Article/details/gt2zorxeohp.html

Py:   async def f():⏎    await g()
来源：http://dali.ydzc1.top/Article/details/gt2zhcvynfd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.kuanghao11.cn/Article/details/gt2tpwtfswj.html

JS:   async function f() { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2moxsfoer.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.316326.xyz/Article/details/gt2rxtclxtv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hysaishi.cn/Article/details/gt2kpntoftu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gaohongyu789.top/Article/details/gt2vhntgaee.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fengsongda.top/Article/details/gt2tuddaskz.html

C#:   async Task F() { await G(); }
来源：http://dali.jiagoushi.top/Article/details/gt2vifwaivz.html

[O05] 并发执行并等待全部完成
来源：http://dali.dianchejie.cn/Article/details/gt2tsxiqggm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.c1oappe.top/Article/details/gt2fieppsre.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yakgjann.html

JS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gt2blgmpkuu.html

TS:   await Promise.all(tasks)
来源：http://dali.xinyue.icu/Article/details/gt2foxeydtx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnqzz.top/Article/details/gt2atuwemjc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jyoumei.cn/Article/details/gt2vsnuumyn.html

Ruby: threads.map(&:join)
来源：http://dali.cashguo.top/Article/details/gt2zltqycsw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yuxming.cn/Article/details/gt2wnhpjspf.html

[O06] 使用进程池
来源：http://dali.aizwys.cn/Article/details/gt2kxffqwou.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yangfankeji.com/Article/details/gt2rzgxxwpe.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daria6918.cn/Article/details/gt2rcukkxbx.html

JS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gt2epnpoqkg.html

TS:   // child_process / cluster 模块
来源：http://dali.yj202588.top/Article/details/gt2hnuaaevi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yangfankeji.com/Article/details/gt2meaitphh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aibaodan.cn/Article/details/gt2pynryvms.html

Ruby: // fork 块
来源：http://dali.redwolf501.top/Article/details/gt2mvgnaxsx.html

C#:   Parallel.For
来源：http://dali.ehwqpu.com/Article/details/gt2thuvbrwm.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2hgshddyd.html

P. 常用工具函数
来源：http://dali.xinyue.icu/Article/details/gt2pxrehvrs.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2ymfzwhyv.html

[P01] 生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gt2watbqlyp.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgufenzy.top/Article/details/gt2lwqacbwg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xziqi.cn/Article/details/gt2ygxalmrw.html

JS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gt2mjwhstjm.html


<!-- 参考信息 -->