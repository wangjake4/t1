代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnombmwgl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gtuxnddkyw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gtdszvzuyu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jyoumei.cn/Article/details/gtrhnexewy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxinkj.top/Article/details/gttjodrcdf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gotoacloud.top/Article/details/gtdoixducy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtaibygzff.html

[L06] 解析响应为 JSON
来源：http://dali.tianlin.xyz/Article/details/gtwiskzeqf.html

Py:   resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtgasxaueu.html

PHP:  json_decode($body, true);
来源：http://dali.ydzc1.top/Article/details/gtywwqhwgz.html

JS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtcdzgynhb.html

TS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gtikekcnpz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtevfbdgdf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sufxvd.cn/Article/details/gtpgavdvqs.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aibaodan.cn/Article/details/gtadsnzjcz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gzhubu.top/Article/details/gtpbfprsvh.html

[L07] 处理 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gtagcmycor.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuanzhike.top/Article/details/gteetqhhfe.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ybcxt.top/Article/details/gtwppoxzos.html

JS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gtmzjoizod.html

TS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gtwuxeaffe.html

Java: resp.statusCode()
来源：http://dali.hywenlv.cn/Article/details/gtqjthdvpr.html

Go:   resp.StatusCode
来源：http://dali.andypj.xyz/Article/details/gtjtbqeajk.html

Ruby: resp.code.to_i
来源：http://dali.yj202588.top/Article/details/gthsrpnnff.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gtcvffkefs.html

[L08] 并发请求多个地址
来源：http://dali.birdmap.top/Article/details/gtyokbupix.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xziqi.cn/Article/details/gtqmplyvcz.html

PHP:  curl_multi_init() 系列
来源：http://dali.svipenyu.cn/Article/details/gtejtfnlba.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gtfayznaii.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gtbxiljfjo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigufen.top/Article/details/gtepvimuca.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gotoacloud.top/Article/details/gtotsuillj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gtvfvgfqde.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hfpthk.cn/Article/details/gtpqkknlps.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtteatynpy.html

M. 命令行 / 进程 / 环境
来源：http://dali.fzhhl.top/Article/details/gtxuyudupz.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtjojoqzjh.html

[M01] 读取命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gtrvntbjdb.html

Py:   sys.argv[1:]
来源：http://dali.aibaodan.cn/Article/details/gtvilmuxsj.html

PHP:  $argv;  $argc;
来源：http://dali.xziqi.cn/Article/details/gthfbiubdu.html

JS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtbnmhuklo.html

TS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gtltwnlrwp.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gtbwqjhous.html

Go:   os.Args[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdtcejgv.html

Ruby: ARGV
来源：http://dali.yanxiufei.cn/Article/details/gtntlivzmp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gtiflrllcn.html

[M02] 读取环境变量
来源：http://dali.birdmap.top/Article/details/gtjbexmvwy.html

Py:   os.environ.get("HOME")
来源：http://dali.mhx1999.top/Article/details/gtckjwyqln.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtcjyldtgo.html

JS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gtuyipommq.html

TS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gtpyhbxdvx.html

Java: System.getenv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtazuhrlmc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtcjlyqciw.html

Ruby: ENV["HOME"]
来源：http://dali.yueranfly.top/Article/details/gtcgmyiqnt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yangfankeji.com/Article/details/gttvhrjrfd.html

[M03] 执行外部命令
来源：http://dali.zycfv.cn/Article/details/gtxlzdrntv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xziqi.cn/Article/details/gtcookbtam.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafumfphk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gtmnkdjluy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gtjivhxxrc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daxiang520.top/Article/details/gtfrzvgkon.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gtdrwmqdlu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ybcxt.top/Article/details/gtqkmlsmdh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinghuilouyu.cn/Article/details/gtpprvrtyu.html

[M04] 获取当前工作目录
来源：http://dali.gzhubu.top/Article/details/gtohwecixh.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gtfbwktgbr.html

PHP:  getcwd();
来源：http://dali.cheryme.top/Article/details/gtdrcwweev.html

JS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gtounfimlz.html

TS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gtbnxmywfq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258.top/Article/details/gtemsoocpp.html

Go:   os.Getwd()
来源：http://dali.chenlongwang.top/Article/details/gtvhpsnfrb.html

Ruby: Dir.pwd
来源：http://dali.zhiwuduotai.top/Article/details/gtdpeaxazt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ybcxt.top/Article/details/gttciymcga.html

[M05] 设置退出码
来源：http://dali.dianchejie.cn/Article/details/gtygflfuar.html

Py:   sys.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtivukevmz.html

PHP:  exit(1);
来源：http://dali.ivvv.top/Article/details/gtpoqkqwel.html

JS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtzznyovkb.html

TS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gttzakladr.html

Java: System.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedgomevo.html

Go:   os.Exit(1)
来源：http://dali.yvedp.cn/Article/details/gtwvfzrnch.html

Ruby: exit 1
来源：http://dali.iojbl.cn/Article/details/gtsductzmi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuanzhike.top/Article/details/gtmhwisnwn.html

[M06] 向标准错误输出
来源：http://dali.tian-w.cn/Article/details/gtxchrvvuw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hammf.cn/Article/details/gtxaswgfxk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aizwys.cn/Article/details/gtobezaukw.html

JS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gtesfygedy.html

TS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gtxflmnnfd.html

Java: System.err.println("err")
来源：http://dali.hywenlv.cn/Article/details/gtvewknjvy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuanzhike.top/Article/details/gtleudenvv.html

Ruby: warn "err"
来源：http://dali.xuetiantiany.cn/Article/details/gtrgibpbqj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.smart0.xyz/Article/details/gtaxligrah.html

[M07] 判断是否为主入口
来源：http://dali.ydzc1.top/Article/details/gtywhreprv.html

Py:   if __name__ == "__main__":
来源：http://dali.mhx1999.top/Article/details/gtyudwrfrh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuxming.cn/Article/details/gtemekniov.html

JS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gtibobcynx.html

TS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gtkzimbgfi.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrduosje.html

Go:   func main()
来源：http://dali.guannengcc.top/Article/details/gtkfticisd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hongshengwenyu.top/Article/details/gtswqyxbpb.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gthokiuxiv.html

[M08] 获取系统与运行时信息
来源：http://dali.yanxiufei.cn/Article/details/gtwgtlsfqz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.quarkkingdee.top/Article/details/gtuksspxgp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnqzz.top/Article/details/gtkpeefcei.html

JS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gtrucljrpd.html

TS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gtehmlsnmt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258.top/Article/details/gtaszdrkpi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hammf.cn/Article/details/gtbvactfyp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jiagoushi.top/Article/details/gtgkipuawx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ehwqpu.com/Article/details/gtnyprilzg.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtogaitipn.html

N. 数据结构与算法
来源：http://dali.snrcjt.cn/Article/details/gtyvboflnq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gthdpnodyd.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgfzy.top/Article/details/gtgzbsadqk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtaquhueka.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ybcxt.top/Article/details/gtsqpqevoj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtoewhfray.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gtkzkgdeaj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtdkgupdwe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtyzilbsna.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xylfe.cn/Article/details/gtmfihqpfe.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtvijazluq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gogol.net.cn/Article/details/gtwlzqbvgd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gtuclvhrod.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.quarkkingdee.top/Article/details/gtjtoneanx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gthwqaddfb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtbkcudikd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.meibo888.top/Article/details/gthzzdslue.html

Go:   slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtwgpztywa.html

Ruby: arr.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtmmxuzykm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvnyqrdx.html

[N03] 快速排序（分治示例）
来源：http://dali.yuxming.cn/Article/details/gticgbdobi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yongpay.top/Article/details/gtawkgedyf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ivvv.top/Article/details/gtgxvxlkpo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gtjziombnw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gtyaprojqa.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cqqwz.cn/Article/details/gttevlrpgr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daria6918.cn/Article/details/gttpvwkjlq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sweek.top/Article/details/gtgkjdavqd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.pycfn.com/Article/details/gtthqfefai.html

[N04] 斐波那契数列
来源：http://dali.gzhubu.top/Article/details/gtjioawicw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gtwrhpeuhj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfrkcbgf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtkamaffui.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtbqcmtvjc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daxiang520.top/Article/details/gtjzmooesa.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cucudq.cn/Article/details/gtvezegpfk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.fengsongda.top/Article/details/gtyhifxddk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gtgxmsjgjo.html

[N05] 最大公约数
来源：http://dali.aizwys.cn/Article/details/gtvjxculyz.html

Py:   math.gcd(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtojaiwvss.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxinkj.top/Article/details/gtkkpaoopc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqhylrir.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gtvnvakbyc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxuanxn.top/Article/details/gtvunksizv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgufenzy.top/Article/details/gtgexgmuyi.html

Ruby: a.gcd(b)
来源：http://dali.chenzaomai.com/Article/details/gtiaydaebu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sysykeji.top/Article/details/gtutpddyzu.html

[N06] 判断回文字符串
来源：http://dali.zhongyouzk.top/Article/details/gtzefeqdcp.html

Py:   s == s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gtuuukqauy.html

PHP:  $s === strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtcbblbsxm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtwnneounf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtqigkvjvh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.andypj.xyz/Article/details/gtomrugrjn.html

Go:   // 双指针从两端比较
来源：http://dali.snrcjt.cn/Article/details/gtjovvfrmz.html

Ruby: s == s.reverse
来源：http://dali.zhengqikj.top/Article/details/gtexkynjzk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gtyaszuqxb.html

[N07] 两数之和（返回下标）
来源：http://dali.0kj1m.cn/Article/details/gtuurnbygn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zycfv.cn/Article/details/gtsrvnkzqi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnypenate.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj202588.top/Article/details/gtmyeuzvdj.html

TS:   // 手写 Map<string, number>
来源：http://dali.gaohongyu789.top/Article/details/gtgxffmvil.html

Java: // 手写 HashMap
来源：http://dali.shzxlz.cn/Article/details/gtlkwgfhrx.html

Go:   // 手写 map[int]int
来源：http://dali.chenlongwang.top/Article/details/gtzaapojki.html

Ruby: // 手写 Hash
来源：http://dali.guowangkeji.top/Article/details/gtizqdvohv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.wangshuangyany.cn/Article/details/gtmtmpiwtk.html

[N08] 生成全排列
来源：http://dali.aizwys.cn/Article/details/gtrwspttwq.html

Py:   itertools.permutations(arr)
来源：http://dali.0kj1m.cn/Article/details/gtinpwqtkn.html

PHP:  // 手写递归交换
来源：http://dali.yvedp.cn/Article/details/gtsachqtyk.html

JS:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtihuzizqz.html

TS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtptblznud.html

Java: // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtkpaspwea.html

Go:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtakyukcob.html

Ruby: arr.permutation.to_a
来源：http://dali.nwbrower.top/Article/details/gtqnuhptil.html

C#:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtoxhxmjdt.html

[N09] 栈与队列
来源：http://dali.birdmap.top/Article/details/gtqgtrvklx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fengsongda.top/Article/details/gtgkmkrjnt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtgdxsfvze.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gtkmoaynuf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258.top/Article/details/gtqkhkzvoe.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gtcusyxrob.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hfpthk.cn/Article/details/gtxcusbacr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gtlvuvnkyf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sweek.top/Article/details/gtfmkduccz.html

[N10] 链表节点定义
来源：http://dali.vqdsnc.cn/Article/details/gtuetuekma.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqbbevjk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jyoumei.cn/Article/details/gtsqtmqfax.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenzaomai.com/Article/details/gtakhbqhlt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdvjtbha.html

Java: class Node { int v; Node next; }
来源：http://dali.hysaishi.cn/Article/details/gtqbtisxbm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.iojbl.cn/Article/details/gtdjwlusni.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.andypj.xyz/Article/details/gtyesjewbo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxinkj.top/Article/details/gtxjdwtncd.html

[N11] 二叉树中序遍历
来源：http://dali.hammf.cn/Article/details/gtgraygugl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jiagoushi.top/Article/details/gtyhwlqxxv.html

PHP:  // 手写递归函数
来源：http://dali.ehwqpu.com/Article/details/gtepoeesip.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gtbjhygbmi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gtmigdzori.html

Java: // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gtjpqnrzuw.html

Go:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtlxaelkcx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.svipenyu.cn/Article/details/gtxbdbahjy.html

C#:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gtttyysfct.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ybcxt.top/Article/details/gtgqayjatq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xinyue.icu/Article/details/gtkjmmmfog.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.9152youxi.cn/Article/details/gtjovuwurv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gthwomjcos.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncleqpad.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gtnctnkcdr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hfpthk.cn/Article/details/gtujpfqwui.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhomzjni.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gtaceumzjg.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtkkgejeyt.html

O. 并发与异步
来源：http://dali.haohaochexian.top/Article/details/gtyfpudxll.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtxthmbfls.html

[O01] 启动一个线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqvhrcgh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shangyingyoupin.top/Article/details/gtmoxmuasu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.316326.xyz/Article/details/gtliexfeia.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sufxvd.cn/Article/details/gtqrbwtkvu.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gtrghpyxpe.html

Java: new Thread(() -> f()).start()
来源：http://dali.yongpay.top/Article/details/gtshmymnfc.html

Go:   go f()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvxrnkof.html

Ruby: Thread.new { f }
来源：http://dali.yonumen.top/Article/details/gttfsqjohm.html

C#:   Task.Run(() => F());
来源：http://dali.ydzc1.top/Article/details/gtcbfhassi.html

[O02] 使用线程池
来源：http://dali.316326.xyz/Article/details/gttkxjpwej.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yangfankeji.com/Article/details/gtcaxcqczg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbjymref.html

JS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gtvakudobb.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gtzxzbglxx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zdqjudy.top/Article/details/gtvgjhaugn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.kuanghao11.cn/Article/details/gtgdnpnzei.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.0kj1m.cn/Article/details/gtidnkddlu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zdqjudy.top/Article/details/gtfrzwcxsi.html

[O03] 加锁保护共享数据
来源：http://dali.sxryk.cn/Article/details/gtqqsgjqcp.html

Py:   with lock: shared += 1
来源：http://dali.yanxiufei.cn/Article/details/gtskwydagn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhongyouzk.top/Article/details/gtkpoxjbrv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxuanxn.top/Article/details/gtsoureelk.html

TS:   // 同 JS
来源：http://dali.gzhubu.top/Article/details/gtqrklvatu.html

Java: synchronized (this) { shared++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtalnqtudh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.andypj.xyz/Article/details/gtouzhgrfg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gtmxihfyea.html

C#:   lock (gate) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrrncdavc.html

[O04] 定义异步函数并等待
来源：http://dali.haohaochexian.top/Article/details/gtpkzwtrca.html

Py:   async def f():⏎    await g()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvebqltgo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.andypj.xyz/Article/details/gtkmvymsbi.html

JS:   async function f() { await g(); }
来源：http://dali.cucudq.cn/Article/details/gtqcgputvs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gtfgoumtrs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shuidangran.top/Article/details/gtheuwckfg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.guowangkeji.top/Article/details/gtmlnrawfe.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yonumen.top/Article/details/gtfkdikogi.html

C#:   async Task F() { await G(); }
来源：http://dali.hywenlv.cn/Article/details/gtespfjfpz.html

[O05] 并发执行并等待全部完成
来源：http://dali.0kj1m.cn/Article/details/gthsxahyam.html

Py:   asyncio.gather(*tasks)
来源：http://dali.birdmap.top/Article/details/gtjxuqdfpw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.quarkkingdee.top/Article/details/gtfkdahlqy.html

JS:   await Promise.all(tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gtlkmewllb.html

TS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtahuxkoie.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gttzdlmtht.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.0kj1m.cn/Article/details/gtwdzwrwcj.html

Ruby: threads.map(&:join)
来源：http://dali.daria6918.cn/Article/details/gtbchhgakj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj202588.top/Article/details/gtsjsygvbv.html

[O06] 使用进程池
来源：http://dali.zhoulong.xyz/Article/details/gtgwomgodn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zycfv.cn/Article/details/gtzvwpdkbw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvcyjqvc.html

JS:   // child_process / cluster 模块
来源：http://dali.ydzc1.top/Article/details/gtbvgxnfjy.html

TS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gtbfavfapp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hywenlv.cn/Article/details/gtemmffufo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhiwuduotai.top/Article/details/gtldhibtwr.html

Ruby: // fork 块
来源：http://dali.sufxvd.cn/Article/details/gtrznepjln.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gtxsbigeqr.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtouxvkwos.html

P. 常用工具函数
来源：http://dali.tianlin.xyz/Article/details/gtusryudvh.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtqxqouphu.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxmokwnr.html

Py:   str(uuid.uuid4())
来源：http://dali.vqdsnc.cn/Article/details/gtmrtemuhh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.snrcjt.cn/Article/details/gtduzsapwn.html

JS:   crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gtbaqzaova.html

TS:   crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gtnfouiorp.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258.top/Article/details/gtspjuinqe.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ybcxt.top/Article/details/gtomzgguqh.html

Ruby: SecureRandom.uuid
来源：http://dali.ivvv.top/Article/details/gtshvjgizg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.9152youxi.cn/Article/details/gtvpdtuzwt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xuanzx.com/Article/details/gtwfvolccz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.quarkkingdee.top/Article/details/gthficzmfd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenzaomai.com/Article/details/gtmugldyxa.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aizwys.cn/Article/details/gtggvtgruw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhixingplan.top/Article/details/gthjvgxqdx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtrptclcsl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.kuanghao11.cn/Article/details/gtrnprjxbu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxuanxn.top/Article/details/gtxukskhcp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sweek.top/Article/details/gtqqlzcafu.html

[P03] 生成短随机字符串
来源：http://dali.andypj.xyz/Article/details/gtsdqmjvdt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fzhhl.top/Article/details/gtvrencvwl.html


<!-- 参考信息 -->