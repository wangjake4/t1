代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gt2jmpohopx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gt2qkndgbst.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pycfn.com/Article/details/gt2whegvxjo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj202588.top/Article/details/gt2ylxqbief.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kcxchubb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenzaomai.com/Article/details/gt2nhqlpmln.html

[L05] 上传文件（multipart）
来源：http://dali.andypj.xyz/Article/details/gt2dtxxdzgg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxuanxn.top/Article/details/gt2zlpmahyo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tanke756.top/Article/details/gt2vmjcujcy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gt2ojxxmycb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gt2hfhjquxl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tianlin.xyz/Article/details/gt2dzluwrey.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuanzhike.top/Article/details/gt2ckzyigvy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pohxlfir.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2agyxrmtw.html

[L06] 解析响应为 JSON
来源：http://dali.nanxuanxn.top/Article/details/gt2ssgfrqdx.html

Py:   resp.json()
来源：http://dali.guannengcc.top/Article/details/gt2qrjtpmpy.html

PHP:  json_decode($body, true);
来源：http://dali.cashguo.top/Article/details/gt2hdmrewtd.html

JS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gt2cpvigvzi.html

TS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gt2mymxgiqi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nwbrower.top/Article/details/gt2kihlzcsa.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yanxiufei.cn/Article/details/gt2loakremi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qnzqtyoc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ydzc1.top/Article/details/gt2guytoykb.html

[L07] 处理 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gt2iejmspqu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenjidiqi.icu/Article/details/gt2sfzxxrkc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.mhx1999.top/Article/details/gt2lrmpvdin.html

JS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gt2ljwlmwzm.html

TS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gt2wwsbzklu.html

Java: resp.statusCode()
来源：http://dali.wangshuangyany.cn/Article/details/gt2vtgznqky.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gt2xzpwnkos.html

Ruby: resp.code.to_i
来源：http://dali.zhongyouzk.top/Article/details/gt2gvoyikzp.html

C#:   (int)resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gt2poqprito.html

[L08] 并发请求多个地址
来源：http://dali.vqdsnc.cn/Article/details/gt2pevxmjlj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cheryme.top/Article/details/gt2pxqsqrzr.html

PHP:  curl_multi_init() 系列
来源：http://dali.yonumen.top/Article/details/gt2ljroypkv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gt2xjdsfelv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gt2pzyjsair.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jyoumei.cn/Article/details/gt2rpzehoai.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.mhx1999.top/Article/details/gt2pkmrybim.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jqgufenzy.top/Article/details/gt2tgstypcv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.vqdsnc.cn/Article/details/gt2tojghezb.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxgadndw.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhengqikj.top/Article/details/gt2mnobsnbs.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2oyrmpgwg.html

[M01] 读取命令行参数
来源：http://dali.tian-w.cn/Article/details/gt2mtaocobd.html

Py:   sys.argv[1:]
来源：http://dali.haohaochexian.top/Article/details/gt2yxqszirc.html

PHP:  $argv;  $argc;
来源：http://dali.9152youxi.cn/Article/details/gt2diupukys.html

JS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gt2zlunctyn.html

TS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gt2mmvzjrti.html

Java: args 数组（main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gt2klopndvy.html

Go:   os.Args[1:]
来源：http://dali.aibaodan.cn/Article/details/gt2seofbilh.html

Ruby: ARGV
来源：http://dali.yanxiufei.cn/Article/details/gt2ezkmrlyv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2znizkrmo.html

[M02] 读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gt2rvikrgdj.html

Py:   os.environ.get("HOME")
来源：http://dali.guowangkeji.top/Article/details/gt2qlxpehme.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gt2jrmsqhap.html

JS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gt2vxeybxes.html

TS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gt2kyypxnbn.html

Java: System.getenv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gt2ajxqjzpj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vvkyoojd.html

Ruby: ENV["HOME"]
来源：http://dali.dashuyun.cn/Article/details/gt2fjbgyluc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2myapexsz.html

[M03] 执行外部命令
来源：http://dali.0kj1m.cn/Article/details/gt2uvubmyjt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258888.top/Article/details/gt2jostbwrd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.feifeiyinyue.top/Article/details/gt2vtztpfvj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gt2nsllpexo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gt2nfbppugs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sufxvd.cn/Article/details/gt2jgoapiix.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gzhubu.top/Article/details/gt2nggsplut.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pypqtbuq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xuetiantiany.cn/Article/details/gt2fialtzoa.html

[M04] 获取当前工作目录
来源：http://dali.ppjwa.cn/Article/details/gt2dpqxhtkd.html

Py:   os.getcwd()
来源：http://dali.dashuyun.cn/Article/details/gt2xqaxuufx.html

PHP:  getcwd();
来源：http://dali.quarkkingdee.top/Article/details/gt2tbbmkzhs.html

JS:   process.cwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2rxpwoalh.html

TS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gt2mjamfixp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgufenzy.top/Article/details/gt2ewbjsxiu.html

Go:   os.Getwd()
来源：http://dali.zhengqikj.top/Article/details/gt2jjcxcbpr.html

Ruby: Dir.pwd
来源：http://dali.smart0.xyz/Article/details/gt2dltrdqpt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cucudq.cn/Article/details/gt2pmprctae.html

[M05] 设置退出码
来源：http://dali.sxryk.cn/Article/details/gt2qadncxkx.html

Py:   sys.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mhmvdhcl.html

PHP:  exit(1);
来源：http://dali.xinyue.icu/Article/details/gt2vhjfylwz.html

JS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gt2aofonond.html

TS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2cqvwjeyu.html

Java: System.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2agravzbq.html

Go:   os.Exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2uwnoygvp.html

Ruby: exit 1
来源：http://dali.daria6918.cn/Article/details/gt2uoqoxjws.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.smart0.xyz/Article/details/gt2otzvwfvo.html

[M06] 向标准错误输出
来源：http://dali.hammf.cn/Article/details/gt2vlnnpriv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gt2ymydykub.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.kuanghao11.cn/Article/details/gt2kgsggtkf.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnvnqss.html

TS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gt2ihmxuupw.html

Java: System.err.println("err")
来源：http://dali.guannengcc.top/Article/details/gt2iiiwsbsd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhengqikj.top/Article/details/gt2kxzkgojj.html

Ruby: warn "err"
来源：http://dali.gogol.net.cn/Article/details/gt2jaqcjija.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hywenlv.cn/Article/details/gt2vhofkyze.html

[M07] 判断是否为主入口
来源：http://dali.andypj.xyz/Article/details/gt2xfjmettx.html

Py:   if __name__ == "__main__":
来源：http://dali.yuanzhike.top/Article/details/gt2appeuaww.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fengsongda.top/Article/details/gt2mpnbstri.html

JS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gt2eoyoiamr.html

TS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gt2tnodosnu.html

Java: public static void main(String[] args)
来源：http://dali.daria6918.cn/Article/details/gt2rzmlxymt.html

Go:   func main()
来源：http://dali.daria6918.cn/Article/details/gt2fjccrvic.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ydzc1.top/Article/details/gt2kavefqlt.html

C#:   static void Main(string[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mznrypas.html

[M08] 获取系统与运行时信息
来源：http://dali.yongpay.top/Article/details/gt2xmvjerzm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daxiang520.top/Article/details/gt2nzdztceg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ybcxt.top/Article/details/gt2olvhzypf.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gt2xqreqhis.html

TS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gt2iwhlcqrq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenlongwang.top/Article/details/gt2xrmdyajx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jianghu66.top/Article/details/gt2vppfking.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhengqikj.top/Article/details/gt2upoafjmi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cxxxxjly.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2chsmdlgh.html

N. 数据结构与算法
来源：http://dali.0kj1m.cn/Article/details/gt2osirpuiz.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2gwnfcpnl.html

[N01] 二分查找（有序数组）
来源：http://dali.iojbl.cn/Article/details/gt2xvgwyqev.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2qcnylyzg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnqzz.top/Article/details/gt2bobsvzyk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuanzhike.top/Article/details/gt2begftgvq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gt2anwgvhzq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaexrhm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2lodfjibg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.redwolf501.top/Article/details/gt2zzrirgpo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2shixwmkt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.birdmap.top/Article/details/gt2gbwsoscg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gt2rqgdwemh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgfzy.top/Article/details/gt2xjauepzd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gt2vwbutumi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gt2pbovsago.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.andypj.xyz/Article/details/gt2jbstfqnu.html

Go:   slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2ojvwmezl.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gt2ozzyxgwt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenlongwang.top/Article/details/gt2gaoxfvds.html

[N03] 快速排序（分治示例）
来源：http://dali.mhx1999.top/Article/details/gt2uxryvycl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sysykeji.top/Article/details/gt2qthwylnl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gt2mwfvkwrr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gt2iksmhjst.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2undrdmfy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gaohongyu789.top/Article/details/gt2kszswumg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgfzy.top/Article/details/gt2lqtusdmg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ehwqpu.com/Article/details/gt2zutckxib.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jiagoushi.top/Article/details/gt2gdbwpfrj.html

[N04] 斐波那契数列
来源：http://dali.shzxlz.cn/Article/details/gt2rwfaneso.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cucudq.cn/Article/details/gt2vpsusida.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gt2yzebqtgz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2efnjxesa.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gt2ungpinds.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gt2jfzayyqc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.birdmap.top/Article/details/gt2bieitosd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2gnhqosli.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gt2fygdayha.html

[N05] 最大公约数
来源：http://dali.zycfv.cn/Article/details/gt2lgblxghl.html

Py:   math.gcd(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gt2kkcmpuzr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ppjwa.cn/Article/details/gt2aichnapd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gt2mdmphxok.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2iqawlgbc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxuanxn.top/Article/details/gt2fnnqbczj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.iojbl.cn/Article/details/gt2voudncjq.html

Ruby: a.gcd(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zqojilor.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gogol.net.cn/Article/details/gt2rgqryiak.html

[N06] 判断回文字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2pedtyzxt.html

Py:   s == s[::-1]
来源：http://dali.pycfn.com/Article/details/gt2rjpqxqqf.html

PHP:  $s === strrev($s);
来源：http://dali.jinqigufen.top/Article/details/gt2cclwauho.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2onrmfopl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2tmhmljyi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.birdmap.top/Article/details/gt2opzqjmxw.html

Go:   // 双指针从两端比较
来源：http://dali.shzxlz.cn/Article/details/gt2rieaakwi.html

Ruby: s == s.reverse
来源：http://dali.sysykeji.top/Article/details/gt2ountbxli.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.pengpengdd.cyou/Article/details/gt2eogvyxsg.html

[N07] 两数之和（返回下标）
来源：http://dali.hongshengwenyu.top/Article/details/gt2ncwbcjkf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.mhx1999.top/Article/details/gt2ejycyrod.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.smart0.xyz/Article/details/gt2fdbwkvub.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.vqdsnc.cn/Article/details/gt2vtdtlskx.html

TS:   // 手写 Map<string, number>
来源：http://dali.zycfv.cn/Article/details/gt2ergaglot.html

Java: // 手写 HashMap
来源：http://dali.tianlin.xyz/Article/details/gt2wykzbubw.html

Go:   // 手写 map[int]int
来源：http://dali.iojbl.cn/Article/details/gt2teuvalsw.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gt2jginqwyq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nwbrower.top/Article/details/gt2fxjoxvin.html

[N08] 生成全排列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fxqssghl.html

Py:   itertools.permutations(arr)
来源：http://dali.birdmap.top/Article/details/gt2xzpxzmpk.html

PHP:  // 手写递归交换
来源：http://dali.chenlongwang.top/Article/details/gt2jxjgzvhl.html

JS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2laskqyjz.html

TS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gt2zaseewzv.html

Java: // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gt2muqhrbcj.html

Go:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gt2erruktec.html

Ruby: arr.permutation.to_a
来源：http://dali.aibaodan.cn/Article/details/gt2tmaqkkrr.html

C#:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lujkuuqi.html

[N09] 栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gt2jzrpugqz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgufenzy.top/Article/details/gt2qmianmnp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tanke756.top/Article/details/gt2amrzvyqp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gt2dkunjiwn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjgcyps.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cdnleiting.top/Article/details/gt2xfocowgu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tianlin.xyz/Article/details/gt2uauktrdt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gt2tljpijak.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ivvv.top/Article/details/gt2bxripxjq.html

[N10] 链表节点定义
来源：http://dali.yj20258.top/Article/details/gt2nwydxoyg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ybcxt.top/Article/details/gt2yxsphxiy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.mhx1999.top/Article/details/gt2hlayytgu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.316326.xyz/Article/details/gt2rhmpzwam.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenzaomai.com/Article/details/gt2amhlwgfb.html

Java: class Node { int v; Node next; }
来源：http://dali.fzhhl.top/Article/details/gt2cizluwfe.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.bjfxy.top/Article/details/gt2fmaalcfh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2imwfvmja.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258.top/Article/details/gt2hxpmumqf.html

[N11] 二叉树中序遍历
来源：http://dali.xylfe.cn/Article/details/gt2ptiywpbd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.bjfxy.top/Article/details/gt2ulxmepcg.html

PHP:  // 手写递归函数
来源：http://dali.hywenlv.cn/Article/details/gt2godlswff.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gt2xmjudwkb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gt2tjhvoloc.html

Java: // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gt2wlqvndwk.html

Go:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gt2zpoatpfh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vzjlqtcn.html

C#:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gt2ogbtycnm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.havefunace.top/Article/details/gt2twxbmbwg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.316326.xyz/Article/details/gt2zplvkgsk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhongyouzk.top/Article/details/gt2djrhmicl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gt2fyiwunlh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gt2ybrjgaqv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.kuanghao11.cn/Article/details/gt2jjsichbm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xylfe.cn/Article/details/gt2oyasmrao.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ppjwa.cn/Article/details/gt2evactdrp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gt2ucpmnokn.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2xlxfgeyy.html

O. 并发与异步
来源：http://dali.guowangkeji.top/Article/details/gt2lesnsoov.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2btfqhgxb.html

[O01] 启动一个线程
来源：http://dali.ivvv.top/Article/details/gt2ikglxrmg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nwbrower.top/Article/details/gt2wotlaztx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cdnleiting.top/Article/details/gt2mwdhsvoi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.smart0.xyz/Article/details/gt2oisbhvne.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gt2voxprcfd.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258888.top/Article/details/gt2dfddqdxb.html

Go:   go f()
来源：http://dali.aizwys.cn/Article/details/gt2bzyyoklw.html

Ruby: Thread.new { f }
来源：http://dali.cqqwz.cn/Article/details/gt2hmcvyrcz.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigfzy.top/Article/details/gt2yumlsbrh.html

[O02] 使用线程池
来源：http://dali.daria6918.cn/Article/details/gt2yztommvr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gotoacloud.top/Article/details/gt2okhssjua.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nwbrower.top/Article/details/gt2eutzwxtm.html

JS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gt2bfwktaql.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2diqfaqqh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nwbrower.top/Article/details/gt2ntpwvldg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxuanxn.top/Article/details/gt2trkztuku.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xjbsjwtc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.birdmap.top/Article/details/gt2uqyjcsvu.html

[O03] 加锁保护共享数据
来源：http://dali.quarkkingdee.top/Article/details/gt2ummiedcv.html

Py:   with lock: shared += 1
来源：http://dali.cucudq.cn/Article/details/gt2ekaclcml.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yongpay.top/Article/details/gt2cdzmoxgf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnxiangtu.top/Article/details/gt2gsqrphyt.html

TS:   // 同 JS
来源：http://dali.316326.xyz/Article/details/gt2jzpbwpjl.html

Java: synchronized (this) { shared++; }
来源：http://dali.zycfv.cn/Article/details/gt2zqotqnwr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gogol.net.cn/Article/details/gt2nuktxbaa.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnqzz.top/Article/details/gt2lzdrruos.html

C#:   lock (gate) { shared++; }
来源：http://dali.yongpay.top/Article/details/gt2dmwsjcoo.html

[O04] 定义异步函数并等待
来源：http://dali.zycfv.cn/Article/details/gt2fbaslgea.html

Py:   async def f():⏎    await g()
来源：http://dali.tian-w.cn/Article/details/gt2ihypgiku.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj202588.top/Article/details/gt2hjaedyhz.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuwrcia.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shuidangran.top/Article/details/gt2bxhlsqvr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fcbvotyh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xinyue.icu/Article/details/gt2egbiaiyh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.quarkkingdee.top/Article/details/gt2pwciawhq.html

C#:   async Task F() { await G(); }
来源：http://dali.sweek.top/Article/details/gt2lxklxecr.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lpzpfbbw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dianchejie.cn/Article/details/gt2flzxchob.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xziqi.cn/Article/details/gt2jlrlnxkm.html

JS:   await Promise.all(tasks)
来源：http://dali.xinyue.icu/Article/details/gt2akzknfet.html

TS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gt2bsyezaan.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.svipenyu.cn/Article/details/gt2itxytmab.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shangyingyoupin.top/Article/details/gt2gaaicbcp.html

Ruby: threads.map(&:join)
来源：http://dali.dashuyun.cn/Article/details/gt2uluispyf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cucudq.cn/Article/details/gt2gwwwuwas.html

[O06] 使用进程池
来源：http://dali.zdqjudy.top/Article/details/gt2ruypbsfy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daria6918.cn/Article/details/gt2vyzippet.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gzhubu.top/Article/details/gt2idwltsmf.html

JS:   // child_process / cluster 模块
来源：http://dali.hongshengwenyu.top/Article/details/gt2qnnkyiad.html

TS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gt2msfapflx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuanzhike.top/Article/details/gt2wcmcvzwp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.316326.xyz/Article/details/gt2qlnbwblh.html

Ruby: // fork 块
来源：http://dali.bjfxy.top/Article/details/gt2bruviqde.html

C#:   Parallel.For
来源：http://dali.jiagoushi.top/Article/details/gt2cmyclyzj.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2ngiwsrlg.html

P. 常用工具函数
来源：http://dali.zycfv.cn/Article/details/gt2lxeigtbo.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2voynpshh.html

[P01] 生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gt2xbzojmxz.html

Py:   str(uuid.uuid4())
来源：http://dali.chenlongwang.top/Article/details/gt2optvsukc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ivvv.top/Article/details/gt2cmrhjoxg.html

JS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gt2evqskvel.html

TS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gt2hsidculx.html

Java: UUID.randomUUID().toString()
来源：http://dali.shzxlz.cn/Article/details/gt2cnmgpbsx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhoulong.xyz/Article/details/gt2jlyshfuz.html

Ruby: SecureRandom.uuid
来源：http://dali.kuanghao11.cn/Article/details/gt2equoojah.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hfpthk.cn/Article/details/gt2iojwnbcu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tianlin.xyz/Article/details/gt2frcybryi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tanke756.top/Article/details/gt2oplgztpf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.birdmap.top/Article/details/gt2kjpgmuro.html


<!-- 参考信息 -->