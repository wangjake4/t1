代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gttlowzrbl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gtuutqqbuw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dianchejie.cn/Article/details/gtvnrglubm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guannengcc.top/Article/details/gtpzpgozwg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hfpthk.cn/Article/details/gtildozjis.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.andypj.xyz/Article/details/gterygyagg.html

[L05] 上传文件（multipart）
来源：http://dali.snrcjt.cn/Article/details/gtdsszrnwy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hysaishi.cn/Article/details/gtjdoevnbi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.kuanghao11.cn/Article/details/gtrtwtlrmh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gtjhmmiduj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gthwwyvjjy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tanke756.top/Article/details/gtbulpkwdj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daria6918.cn/Article/details/gtsuxlrkvn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shzxlz.cn/Article/details/gtbyznokju.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yueranfly.top/Article/details/gtrndzuxjh.html

[L06] 解析响应为 JSON
来源：http://dali.cqqwz.cn/Article/details/gtgrjrolvt.html

Py:   resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtfnipojlp.html

PHP:  json_decode($body, true);
来源：http://dali.yueranfly.top/Article/details/gtvqrwvtcw.html

JS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtoptlfifn.html

TS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhlhlxzm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cheryme.top/Article/details/gthahdtazm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guowangkeji.top/Article/details/gtdmeyaxwc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hfpthk.cn/Article/details/gtfvfwrupg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhixingplan.top/Article/details/gtiqfiuwwn.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gtebvzccpi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fzhhl.top/Article/details/gtzdghtobb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.pengpengdd.cyou/Article/details/gtltfbdezv.html

JS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gtbrznkrae.html

TS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gtnmzlosdz.html

Java: resp.statusCode()
来源：http://dali.zycfv.cn/Article/details/gtcdagprzk.html

Go:   resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtqtobktod.html

Ruby: resp.code.to_i
来源：http://dali.pycfn.com/Article/details/gtrkdkgeox.html

C#:   (int)resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gtiayyotiv.html

[L08] 并发请求多个地址
来源：http://dali.cqqwz.cn/Article/details/gtqfbiyqii.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gotoacloud.top/Article/details/gtkmdyeffz.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinghuilouyu.cn/Article/details/gtescmpjdv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gttlzhdead.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gtqevnufxa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gaohongyu789.top/Article/details/gtjunloqyc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daxiang520.top/Article/details/gtywpzdydx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gtbyzzgtpi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.bjfxy.top/Article/details/gtzaesucri.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtdrxmcxea.html

M. 命令行 / 进程 / 环境
来源：http://dali.sweek.top/Article/details/gttqfktlmt.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtjtgobayj.html

[M01] 读取命令行参数
来源：http://dali.cucudq.cn/Article/details/gtzhxbzvsu.html

Py:   sys.argv[1:]
来源：http://dali.hysaishi.cn/Article/details/gtqxtvijps.html

PHP:  $argv;  $argc;
来源：http://dali.jinghuilouyu.cn/Article/details/gthsexwxhi.html

JS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gthglvgtqw.html

TS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtwewgdape.html

Java: args 数组（main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtzoajoqpm.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtymzdzxco.html

Ruby: ARGV
来源：http://dali.chenlongwang.top/Article/details/gtzjyuxavc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gtsyemfiry.html

[M02] 读取环境变量
来源：http://dali.meibo888.top/Article/details/gtobisgolx.html

Py:   os.environ.get("HOME")
来源：http://dali.xylfe.cn/Article/details/gtdrdyyder.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gtwrynlbzu.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtsmpnxtfg.html

TS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtpofumfot.html

Java: System.getenv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtbvfbgitf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ivvv.top/Article/details/gtikiqjwcz.html

Ruby: ENV["HOME"]
来源：http://dali.tian-w.cn/Article/details/gtyharzcjy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtftlojeeg.html

[M03] 执行外部命令
来源：http://dali.quarkkingdee.top/Article/details/gtuvvdbayh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenlongwang.top/Article/details/gthnqaajxs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pycfn.com/Article/details/gtmsxzkjjd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gtbzineoua.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtbrlthlwq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.redwolf501.top/Article/details/gtldexuxjq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cucudq.cn/Article/details/gtfgqmpnxi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenzaomai.com/Article/details/gtkwuuhtmv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guowangkeji.top/Article/details/gteixtnyis.html

[M04] 获取当前工作目录
来源：http://dali.jiagoushi.top/Article/details/gtiyucybyy.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnpvsaca.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gtdobbmhkl.html

JS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gtwpccllmb.html

TS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwfbapqu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258.top/Article/details/gtjnozenpq.html

Go:   os.Getwd()
来源：http://dali.ybcxt.top/Article/details/gtqgfmifna.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhbdvjoo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yonumen.top/Article/details/gtamvhngxp.html

[M05] 设置退出码
来源：http://dali.gaohongyu789.top/Article/details/gtcobzrlue.html

Py:   sys.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtslwjaphw.html

PHP:  exit(1);
来源：http://dali.feifeiyinyue.top/Article/details/gtdzfzwkzr.html

JS:   process.exit(1)
来源：http://dali.ivvv.top/Article/details/gtvogadhmn.html

TS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gthuvnznfd.html

Java: System.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtwfveowdo.html

Go:   os.Exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtbakmouzf.html

Ruby: exit 1
来源：http://dali.tanke756.top/Article/details/gtqoigedah.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yangfankeji.com/Article/details/gtxjeijcpi.html

[M06] 向标准错误输出
来源：http://dali.svipenyu.cn/Article/details/gtljycivfd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gtkzazdmww.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhengqikj.top/Article/details/gtbugmelxw.html

JS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gtirrnvivn.html

TS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gthulzvgmu.html

Java: System.err.println("err")
来源：http://dali.jyoumei.cn/Article/details/gtufbtmfnn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sufxvd.cn/Article/details/gtrnikdhow.html

Ruby: warn "err"
来源：http://dali.hnqzz.top/Article/details/gttzcuiwqr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.mhx1999.top/Article/details/gtjgofxouz.html

[M07] 判断是否为主入口
来源：http://dali.aizwys.cn/Article/details/gtmzygmgee.html

Py:   if __name__ == "__main__":
来源：http://dali.yuxming.cn/Article/details/gtyatuqzxr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenzaomai.com/Article/details/gtoypdxblq.html

JS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gtkkexcccf.html

TS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtwmzdavbt.html

Java: public static void main(String[] args)
来源：http://dali.guowangkeji.top/Article/details/gtjpawzktz.html

Go:   func main()
来源：http://dali.jlsjyb.cn/Article/details/gttczwqnoz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aizwys.cn/Article/details/gtutsusxrx.html

C#:   static void Main(string[] args)
来源：http://dali.yj202588.top/Article/details/gtuydhwfaa.html

[M08] 获取系统与运行时信息
来源：http://dali.nwbrower.top/Article/details/gtipnvznbs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zycfv.cn/Article/details/gtvnemmnnx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pycfn.com/Article/details/gtlugprjve.html

JS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gtkeaitxvf.html

TS:   process.platform;  process.version
来源：http://dali.zhixingplan.top/Article/details/gtxvgsgjhi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shuidangran.top/Article/details/gtxtslyxqo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenzaomai.com/Article/details/gthovgdnzd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xuetiantiany.cn/Article/details/gtdfpalqfn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tanke756.top/Article/details/gtjvotsjmg.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtznaywbij.html

N. 数据结构与算法
来源：http://dali.nanxinkj.top/Article/details/gtbikmsmlz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtqeemddjl.html

[N01] 二分查找（有序数组）
来源：http://dali.hammf.cn/Article/details/gtulnamaiq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtazegorqp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtkcmbthbk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtxfbfrufi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwfkfhss.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtwymfbsjh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtkfavjset.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hysaishi.cn/Article/details/gtiklndwmo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtyrotrvqc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jianghu66.top/Article/details/gteikljeua.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.9152youxi.cn/Article/details/gtuhjeqgjc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.snrcjt.cn/Article/details/gtrmgidnuq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtfzonnfxs.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gtdughofqy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuetiantiany.cn/Article/details/gtaunozkmf.html

Go:   slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gtbjpnzyxo.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gtgztdjkad.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.snrcjt.cn/Article/details/gtkmfgxcrb.html

[N03] 快速排序（分治示例）
来源：http://dali.hfpthk.cn/Article/details/gtskwipeer.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hammf.cn/Article/details/gtbamiwfdm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shangyingyoupin.top/Article/details/gtiadighdv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gtsmaogsuu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gtxjbdxnbv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zdqjudy.top/Article/details/gtotiuuzsq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dianchejie.cn/Article/details/gtvgwqnbyy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yanxiufei.cn/Article/details/gtpxwpokrg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shangyingyoupin.top/Article/details/gttvgxorpy.html

[N04] 斐波那契数列
来源：http://dali.tianlin.xyz/Article/details/gtztcrzzoi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gtohifndik.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gtuyimurag.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtprbmkgkh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtjszrfrqm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.bjfxy.top/Article/details/gtwadqypbh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jyoumei.cn/Article/details/gtsnbvonwe.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gtxtvlyosq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtugxxkein.html

[N05] 最大公约数
来源：http://dali.kuanghao11.cn/Article/details/gtjylbyxlg.html

Py:   math.gcd(a, b)
来源：http://dali.daxiang520.top/Article/details/gtaklcqsfe.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbptojrp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gtkmukbcdk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvthxijsj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinghuilouyu.cn/Article/details/gtssswbtlm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258888.top/Article/details/gtxphgikrb.html

Ruby: a.gcd(b)
来源：http://dali.shuidangran.top/Article/details/gtunbcriwu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuetiantiany.cn/Article/details/gtwebhcitm.html

[N06] 判断回文字符串
来源：http://dali.yj20258.top/Article/details/gtfiixinhj.html

Py:   s == s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gtbulaqith.html

PHP:  $s === strrev($s);
来源：http://dali.cheryme.top/Article/details/gttyqeavfk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtrwrxajrh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtxdgudgly.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuetiantiany.cn/Article/details/gtfrfghixz.html

Go:   // 双指针从两端比较
来源：http://dali.dashuyun.cn/Article/details/gtvliiutzp.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtrnubvvsy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gtulodqsdn.html

[N07] 两数之和（返回下标）
来源：http://dali.hnxiangtu.top/Article/details/gtctrgxtrt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zdqjudy.top/Article/details/gtfqerihal.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.haohaochexian.top/Article/details/gtsynrdfde.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sufxvd.cn/Article/details/gttorplflx.html

TS:   // 手写 Map<string, number>
来源：http://dali.zdqjudy.top/Article/details/gtpkfuwvah.html

Java: // 手写 HashMap
来源：http://dali.xinyue.icu/Article/details/gtesjvynyh.html

Go:   // 手写 map[int]int
来源：http://dali.hfpthk.cn/Article/details/gtfimqbyxq.html

Ruby: // 手写 Hash
来源：http://dali.shangyingyoupin.top/Article/details/gtjvhgmaib.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.birdmap.top/Article/details/gtznxxsoqk.html

[N08] 生成全排列
来源：http://dali.xuanzx.com/Article/details/gtomkasjpd.html

Py:   itertools.permutations(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtulnkfrur.html

PHP:  // 手写递归交换
来源：http://dali.haohaochexian.top/Article/details/gtsbjygknk.html

JS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtikdhpugx.html

TS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtspdmqgqu.html

Java: // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtppfttdlw.html

Go:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtcpkndlje.html

Ruby: arr.permutation.to_a
来源：http://dali.bjfxy.top/Article/details/gtrwinslkw.html

C#:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtcfegslfk.html

[N09] 栈与队列
来源：http://dali.snrcjt.cn/Article/details/gtgrkjnbtg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xziqi.cn/Article/details/gtbtgvaxzw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj202588.top/Article/details/gtebcevbiq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtwxfvpcqd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuetiantiany.cn/Article/details/gtqwicycdd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gtlywtoavs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dianchejie.cn/Article/details/gtsqbacaei.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtttajeshg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xziqi.cn/Article/details/gtypllkxic.html

[N10] 链表节点定义
来源：http://dali.zhengqikj.top/Article/details/gtnsucuogy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhiwuduotai.top/Article/details/gteyeusahs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gotoacloud.top/Article/details/gtyzlolszs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tian-w.cn/Article/details/gtgegsiymb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.haohaochexian.top/Article/details/gttrmrlkjh.html

Java: class Node { int v; Node next; }
来源：http://dali.sxryk.cn/Article/details/gtphuqlinr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.birdmap.top/Article/details/gtkzyblozq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnqzz.top/Article/details/gtnjtikggq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xylfe.cn/Article/details/gtidzwdrqq.html

[N11] 二叉树中序遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtvrtfmbqu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.316326.xyz/Article/details/gtlricaaxq.html

PHP:  // 手写递归函数
来源：http://dali.hammf.cn/Article/details/gtcchjhvvw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gtlwcrwllq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gttlgujman.html

Java: // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtaxetrovn.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtkavzqtnc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yongpay.top/Article/details/gtjpjbagjc.html

C#:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtfvyhlvtg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenlongwang.top/Article/details/gtyecahycv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sweek.top/Article/details/gttxwxfqer.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbtkrorn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhengqikj.top/Article/details/gtdfndwjjb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gtbsawrxtf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvnqdcxn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ppjwa.cn/Article/details/gtylfwphnt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.svipenyu.cn/Article/details/gtiuchuyfh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtoohybvsp.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsvzttnk.html

O. 并发与异步
来源：http://dali.yuxming.cn/Article/details/gtvcscphzr.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtlyenlzkf.html

[O01] 启动一个线程
来源：http://dali.shzxlz.cn/Article/details/gtzhgocrdv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jlsjyb.cn/Article/details/gtubicbmdo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.mhx1999.top/Article/details/gtuhdmyjpc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yongpay.top/Article/details/gtfebvjpbq.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gteminjwyx.html

Java: new Thread(() -> f()).start()
来源：http://dali.ydzc1.top/Article/details/gtlhkutvus.html

Go:   go f()
来源：http://dali.ybcxt.top/Article/details/gtqlfxtect.html

Ruby: Thread.new { f }
来源：http://dali.jyoumei.cn/Article/details/gtvhtghndx.html

C#:   Task.Run(() => F());
来源：http://dali.hammf.cn/Article/details/gtixkeddlk.html

[O02] 使用线程池
来源：http://dali.pycfn.com/Article/details/gtyxjcnsiy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jlsjyb.cn/Article/details/gtikchrelv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guowangkeji.top/Article/details/gtyjyfpcfy.html

JS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gtaofxrszf.html

TS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gtfenzwigg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cheryme.top/Article/details/gtvvyslzyb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.fengsongda.top/Article/details/gtqkjjotjt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.havefunace.top/Article/details/gtfuefnwek.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.pengpengdd.cyou/Article/details/gtspyhsmxw.html

[O03] 加锁保护共享数据
来源：http://dali.sysykeji.top/Article/details/gtnzyumnwc.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gttkynuppx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cdnleiting.top/Article/details/gtsjqmoqpl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hywenlv.cn/Article/details/gtjiahnngh.html

TS:   // 同 JS
来源：http://dali.daria6918.cn/Article/details/gtwtuguevn.html

Java: synchronized (this) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gtneduozzp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.9152youxi.cn/Article/details/gtrtdaymmi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jlsjyb.cn/Article/details/gtdehjqefd.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gtackhiejy.html

[O04] 定义异步函数并等待
来源：http://dali.gogol.net.cn/Article/details/gtidaudaua.html

Py:   async def f():⏎    await g()
来源：http://dali.xylfe.cn/Article/details/gtbxbrqfmw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cashguo.top/Article/details/gttwmkxmeo.html

JS:   async function f() { await g(); }
来源：http://dali.hywenlv.cn/Article/details/gtjrkotasa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnqzz.top/Article/details/gtmdhupcja.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tanke756.top/Article/details/gtbthbdxju.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cqqwz.cn/Article/details/gtamlrnfrt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yuxming.cn/Article/details/gtikekupkf.html

C#:   async Task F() { await G(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtcdbbklcs.html

[O05] 并发执行并等待全部完成
来源：http://dali.gogol.net.cn/Article/details/gtfxjlzatq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhixingplan.top/Article/details/gtnenjlfju.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxuanxn.top/Article/details/gtxcixysyf.html

JS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gtuorhtuzv.html

TS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gttrmglrew.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.dianchejie.cn/Article/details/gtfvjctjbf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hammf.cn/Article/details/gtjgagfjdf.html

Ruby: threads.map(&:join)
来源：http://dali.meibo888.top/Article/details/gtvywfqvwn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnqzz.top/Article/details/gtjguzpxyl.html

[O06] 使用进程池
来源：http://dali.yuxming.cn/Article/details/gtpikvasli.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jiagoushi.top/Article/details/gtkmxpscqd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ehwqpu.com/Article/details/gtsieahpax.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gtihhxcywo.html

TS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gtdizxpvyl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.mhx1999.top/Article/details/gtguzaevpz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guannengcc.top/Article/details/gtqbwjptru.html

Ruby: // fork 块
来源：http://dali.yuanzhike.top/Article/details/gtgbnuzcai.html

C#:   Parallel.For
来源：http://dali.yonumen.top/Article/details/gtflcbetgk.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtowrgwdqa.html

P. 常用工具函数
来源：http://dali.9152youxi.cn/Article/details/gtxbzghpdg.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtcvnjzekl.html

[P01] 生成 UUID
来源：http://dali.nanxinkj.top/Article/details/gtbncocvpr.html

Py:   str(uuid.uuid4())
来源：http://dali.quarkkingdee.top/Article/details/gtqfogvrgw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tianlin.xyz/Article/details/gtnwuurhce.html

JS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gtrpqoierf.html

TS:   crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gttokmeqkj.html

Java: UUID.randomUUID().toString()
来源：http://dali.aizwys.cn/Article/details/gtfoydswbz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhongyouzk.top/Article/details/gtrvsaszjq.html

Ruby: SecureRandom.uuid
来源：http://dali.sufxvd.cn/Article/details/gtikloxpmi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxinkj.top/Article/details/gtxmsekwoa.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gogol.net.cn/Article/details/gtecgrzsmk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sweek.top/Article/details/gtvwelxhzx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cheryme.top/Article/details/gtmrdxzeia.html


<!-- 参考信息 -->