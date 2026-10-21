代发 wailian999

Py:   resp.json()
来源：http://dali.cashguo.top/Article/details/gtddwprzej.html

PHP:  json_decode($body, true);
来源：http://dali.gaohongyu789.top/Article/details/gtfpnsnlsf.html

JS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gtalvptkfn.html

TS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gtpuitqbkw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtmhyystyq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthicrqdqo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.guowangkeji.top/Article/details/gtpvizhejl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258.top/Article/details/gtmyvlpzho.html

[L07] 处理 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtoffxpbca.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guannengcc.top/Article/details/gtuacptrmo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shuidangran.top/Article/details/gtxjhzmrve.html

JS:   resp.ok;  resp.status
来源：http://dali.shuidangran.top/Article/details/gtcdufjnca.html

TS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gttemiybpe.html

Java: resp.statusCode()
来源：http://dali.nanxuanxn.top/Article/details/gtbneiqrzm.html

Go:   resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtwxelrwuv.html

Ruby: resp.code.to_i
来源：http://dali.gzhubu.top/Article/details/gtcmfzdsho.html

C#:   (int)resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtwfegblzz.html

[L08] 并发请求多个地址
来源：http://dali.chenjidiqi.icu/Article/details/gtwohwwcpk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxuanxn.top/Article/details/gtizrpzmlh.html

PHP:  curl_multi_init() 系列
来源：http://dali.guannengcc.top/Article/details/gtmnphfkpq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtdqiedrhq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gtfkgrjxkp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sxryk.cn/Article/details/gtkptzarcs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shangyingyoupin.top/Article/details/gtecwogvjm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cdnleiting.top/Article/details/gtfvsgelzo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ppjwa.cn/Article/details/gtcfnfnifs.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtvggcfpbt.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj20258888.top/Article/details/gtgnrlpzvj.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtlyljcwsf.html

[M01] 读取命令行参数
来源：http://dali.wangshuangyany.cn/Article/details/gtajqlrlcn.html

Py:   sys.argv[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvyxfllo.html

PHP:  $argv;  $argc;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtecwikdbq.html

JS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckjjfrlr.html

TS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtjqsorzbb.html

Java: args 数组（main 方法参数）
来源：http://dali.cashguo.top/Article/details/gtamljgkbv.html

Go:   os.Args[1:]
来源：http://dali.ybcxt.top/Article/details/gtqorpdeyg.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gtwswrqyvr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gtgmwwsxwl.html

[M02] 读取环境变量
来源：http://dali.xylfe.cn/Article/details/gtusiuggxf.html

Py:   os.environ.get("HOME")
来源：http://dali.iojbl.cn/Article/details/gtadwpbffu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gtbqheeder.html

JS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtmutkabmf.html

TS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gtxbaqllpp.html

Java: System.getenv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgzfbdgp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cucudq.cn/Article/details/gtlddvwbyw.html

Ruby: ENV["HOME"]
来源：http://dali.zhengqikj.top/Article/details/gteonxgfhk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtslxphxde.html

[M03] 执行外部命令
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhjwefed.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hammf.cn/Article/details/gtuxoejkqy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shuidangran.top/Article/details/gthebhrbjs.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gtwfxgftxn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gtyzrkoxio.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zycfv.cn/Article/details/gtmjzpcphm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuanzx.com/Article/details/gtheulzlsl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xylfe.cn/Article/details/gtnymtdvvt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxuanxn.top/Article/details/gtngyqrloo.html

[M04] 获取当前工作目录
来源：http://dali.zycfv.cn/Article/details/gtdqbowpxk.html

Py:   os.getcwd()
来源：http://dali.iojbl.cn/Article/details/gtaepmxuiq.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gtgysvtpld.html

JS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtymmoqgst.html

TS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gtinqinlsf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ivvv.top/Article/details/gtlqemkakh.html

Go:   os.Getwd()
来源：http://dali.yangfankeji.com/Article/details/gtkfzkfhjm.html

Ruby: Dir.pwd
来源：http://dali.cashguo.top/Article/details/gtlfydbzdo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.feifeiyinyue.top/Article/details/gtrhukhcqa.html

[M05] 设置退出码
来源：http://dali.ehwqpu.com/Article/details/gtqafknrpx.html

Py:   sys.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtkgjfhttc.html

PHP:  exit(1);
来源：http://dali.guannengcc.top/Article/details/gtbqgigobp.html

JS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtvqspdton.html

TS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gtdaojcgcd.html

Java: System.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtobhgpmsp.html

Go:   os.Exit(1)
来源：http://dali.ydzc1.top/Article/details/gtnuqspkgo.html

Ruby: exit 1
来源：http://dali.hammf.cn/Article/details/gthlvstqcy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jiagoushi.top/Article/details/gtglqmgzih.html

[M06] 向标准错误输出
来源：http://dali.yuanzhike.top/Article/details/gtqhegefdv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhoulong.xyz/Article/details/gtonajkdpt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tianlin.xyz/Article/details/gtysbaohqe.html

JS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtnbqnpuzd.html

TS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtindecvca.html

Java: System.err.println("err")
来源：http://dali.birdmap.top/Article/details/gtfovocnci.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gtaubwwmyd.html

Ruby: warn "err"
来源：http://dali.tian-w.cn/Article/details/gtwbpmkmqn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.andypj.xyz/Article/details/gtgpnedctc.html

[M07] 判断是否为主入口
来源：http://dali.mhx1999.top/Article/details/gthsdpexuh.html

Py:   if __name__ == "__main__":
来源：http://dali.snrcjt.cn/Article/details/gtlptrfmot.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cucudq.cn/Article/details/gtkspylugr.html

JS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gtcqzlnodf.html

TS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gtmhptpqoj.html

Java: public static void main(String[] args)
来源：http://dali.jianghu66.top/Article/details/gtsrobwaaq.html

Go:   func main()
来源：http://dali.cashguo.top/Article/details/gttyahcnzh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sysykeji.top/Article/details/gtktfznrxy.html

C#:   static void Main(string[] args)
来源：http://dali.dianchejie.cn/Article/details/gteegiziks.html

[M08] 获取系统与运行时信息
来源：http://dali.zdqjudy.top/Article/details/gtnqfvzune.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgufenzy.top/Article/details/gtctcexcpl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cucudq.cn/Article/details/gtucredhyj.html

JS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtadzizuub.html

TS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtdkfhnrdw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258.top/Article/details/gtfhpgdfxu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tianlin.xyz/Article/details/gtnqyxixwm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jianghu66.top/Article/details/gtciajhvky.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hfpthk.cn/Article/details/gtohssznsg.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtwtzlflhk.html

N. 数据结构与算法
来源：http://dali.havefunace.top/Article/details/gtbjofnsec.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtzongeivc.html

[N01] 二分查找（有序数组）
来源：http://dali.xuanzx.com/Article/details/gtfybkevvc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtyhuyczui.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtyexuuzbv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtawbdtdpv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtnntknlsd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtjinibpqy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtfozorokq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenzaomai.com/Article/details/gthugeevnf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtrcmvqhuu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gzhubu.top/Article/details/gtxykevyaf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvqmjqmk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sweek.top/Article/details/gtbimgwnaq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtvcaevcfl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtxvjzgvhu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xinyue.icu/Article/details/gtndjljyjh.html

Go:   slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gtmgssaaij.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gtwibhvtpa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhongyouzk.top/Article/details/gtoyxjxeeo.html

[N03] 快速排序（分治示例）
来源：http://dali.sysykeji.top/Article/details/gteceqslmh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuetiantiany.cn/Article/details/gtwjuslzkb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258.top/Article/details/gtbbunfyty.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gtstvjljvz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gtycebveom.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ydzc1.top/Article/details/gtqrcpspip.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yonumen.top/Article/details/gtlfpyhakp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shuidangran.top/Article/details/gtshifdvcc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cheryme.top/Article/details/gtjfdbgzan.html

[N04] 斐波那契数列
来源：http://dali.gaohongyu789.top/Article/details/gthriqlgns.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtrdeewtwt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gtahbuwvph.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtmlyxuxim.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflyobuxd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gtrniosdli.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.andypj.xyz/Article/details/gtaarrfybw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtybipzabp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgthvzasf.html

[N05] 最大公约数
来源：http://dali.yuxming.cn/Article/details/gtfhsyxcyh.html

Py:   math.gcd(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gtagvjkexn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqcvtjpcb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnpwgxlkp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtpnpqindx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sufxvd.cn/Article/details/gtubvjcley.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258888.top/Article/details/gteruuydnd.html

Ruby: a.gcd(b)
来源：http://dali.hammf.cn/Article/details/gtgbciwsjn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.meibo888.top/Article/details/gthbgwgddr.html

[N06] 判断回文字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtyfxpevxw.html

Py:   s == s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gtjycdgxqj.html

PHP:  $s === strrev($s);
来源：http://dali.jlsjyb.cn/Article/details/gtncraxzug.html

JS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtumyletbp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gtpnfwugci.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.9152youxi.cn/Article/details/gtfqjqvpgj.html

Go:   // 双指针从两端比较
来源：http://dali.yueranfly.top/Article/details/gttisgdyfw.html

Ruby: s == s.reverse
来源：http://dali.tian-w.cn/Article/details/gtczdepuzq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gtwjgjczoi.html

[N07] 两数之和（返回下标）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnukjcctk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yvedp.cn/Article/details/gtnalhhejt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cqqwz.cn/Article/details/gtmynkdywa.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.redwolf501.top/Article/details/gtvjhhjniv.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuxming.cn/Article/details/gtzuagqwzu.html

Java: // 手写 HashMap
来源：http://dali.cheryme.top/Article/details/gtglkasnak.html

Go:   // 手写 map[int]int
来源：http://dali.wangdashe.top/Article/details/gtuzhiqhmr.html

Ruby: // 手写 Hash
来源：http://dali.sweek.top/Article/details/gtemtnyqtl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuetiantiany.cn/Article/details/gtbufcrtwt.html

[N08] 生成全排列
来源：http://dali.xinyue.icu/Article/details/gtwydbfewt.html

Py:   itertools.permutations(arr)
来源：http://dali.jiagoushi.top/Article/details/gtftwskpwq.html

PHP:  // 手写递归交换
来源：http://dali.tian-w.cn/Article/details/gtoomkuaip.html

JS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtnekqtern.html

TS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtgdkwuspv.html

Java: // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtgymbpinr.html

Go:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtpvlcszqd.html

Ruby: arr.permutation.to_a
来源：http://dali.kuanghao11.cn/Article/details/gtcrikrdrk.html

C#:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtisjxpuhm.html

[N09] 栈与队列
来源：http://dali.zhixingplan.top/Article/details/gtpkzajolz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenlongwang.top/Article/details/gtxvkcwyhk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtpelrrrze.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtieecysdq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.andypj.xyz/Article/details/gtjjikyoku.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ppjwa.cn/Article/details/gtqvrkpfkp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhiwuduotai.top/Article/details/gtberavpmk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtojqcnrqv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxinkj.top/Article/details/gtmpftwkju.html

[N10] 链表节点定义
来源：http://dali.pengpengdd.cyou/Article/details/gtaaqjqbte.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj202588.top/Article/details/gtwyxxskhq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cucudq.cn/Article/details/gtmsvqoeij.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.birdmap.top/Article/details/gtxualmcos.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jiagoushi.top/Article/details/gtywtvtgsn.html

Java: class Node { int v; Node next; }
来源：http://dali.cashguo.top/Article/details/gtynsydfug.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.9152youxi.cn/Article/details/gtbzwujgle.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj202588.top/Article/details/gtimnmghcy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.smart0.xyz/Article/details/gtfqudvrpa.html

[N11] 二叉树中序遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrchsrbcs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnqzz.top/Article/details/gtuwfymysl.html

PHP:  // 手写递归函数
来源：http://dali.shangyingyoupin.top/Article/details/gtayqflhjg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dashuyun.cn/Article/details/gtfdqpsidb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gtrqtuthdg.html

Java: // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gteomkyidc.html

Go:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gtvujbxxyb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.c1oappe.top/Article/details/gtbdvocqrj.html

C#:   // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gtwlblbrlo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhengqikj.top/Article/details/gtjoiiiexc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yanxiufei.cn/Article/details/gtdqpqeubz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.feifeiyinyue.top/Article/details/gtlnuwzoef.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gtqaqquejl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sufxvd.cn/Article/details/gtpfjslnwm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlielpxfr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jlsjyb.cn/Article/details/gtpgpfnovn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cucudq.cn/Article/details/gtolwsjdec.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gtpoxpcrcq.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtuuxhbjwv.html

O. 并发与异步
来源：http://dali.yueranfly.top/Article/details/gtimxbylec.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gteyxtwhdp.html

[O01] 启动一个线程
来源：http://dali.pycfn.com/Article/details/gtafscsjrz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guannengcc.top/Article/details/gtlsnejkiq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jianghu66.top/Article/details/gtoplvqyqp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj202588.top/Article/details/gtmqrseoyl.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gtwzfylkqh.html

Java: new Thread(() -> f()).start()
来源：http://dali.sweek.top/Article/details/gtdyzzzqpm.html

Go:   go f()
来源：http://dali.hnxiangtu.top/Article/details/gttolwgbnd.html

Ruby: Thread.new { f }
来源：http://dali.bjfxy.top/Article/details/gttnsqvhvi.html

C#:   Task.Run(() => F());
来源：http://dali.ivvv.top/Article/details/gtrtusthpb.html

[O02] 使用线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtrmfpisls.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhengqikj.top/Article/details/gtakmwaxuh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yanxiufei.cn/Article/details/gtatpclsba.html

JS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbgnjxaz.html

TS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gtyqxigyqy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhiwuduotai.top/Article/details/gtjyescmuj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.meibo888.top/Article/details/gtdguzqdbu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yanxiufei.cn/Article/details/gtgotvoqax.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hammf.cn/Article/details/gtadodzjvi.html

[O03] 加锁保护共享数据
来源：http://dali.aizwys.cn/Article/details/gtmzlsszie.html

Py:   with lock: shared += 1
来源：http://dali.hnqzz.top/Article/details/gtgtbhfwic.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hysaishi.cn/Article/details/gtbitslecj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gogol.net.cn/Article/details/gtvvxckgyq.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gtslzqvoma.html

Java: synchronized (this) { shared++; }
来源：http://dali.hywenlv.cn/Article/details/gttjqfzljk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxinkj.top/Article/details/gtudznbeue.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.iojbl.cn/Article/details/gtlpsiyosz.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhtddalh.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gtirjipcbz.html

Py:   async def f():⏎    await g()
来源：http://dali.mhx1999.top/Article/details/gtarvkaynj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.meibo888.top/Article/details/gtyddqnbud.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gtzmiffzhf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gtdogdrqzt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.svipenyu.cn/Article/details/gtrambuiux.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.svipenyu.cn/Article/details/gtscotlzxw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.iojbl.cn/Article/details/gtlzbiaktg.html

C#:   async Task F() { await G(); }
来源：http://dali.c1oappe.top/Article/details/gtftcltlru.html

[O05] 并发执行并等待全部完成
来源：http://dali.aizwys.cn/Article/details/gthtorpgwp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigfzy.top/Article/details/gtvgfeilzk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.9152youxi.cn/Article/details/gtlfebskug.html

JS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtajvtkpnj.html

TS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtdhsqjpxf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhoulong.xyz/Article/details/gtkrzyijop.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xylfe.cn/Article/details/gtvflplvoc.html

Ruby: threads.map(&:join)
来源：http://dali.cqqwz.cn/Article/details/gttmtyjxuj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.meibo888.top/Article/details/gtrarbmdzz.html

[O06] 使用进程池
来源：http://dali.yongpay.top/Article/details/gtmxvsfgdz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hywenlv.cn/Article/details/gtdzaihkxs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daxiang520.top/Article/details/gtipgnnhzy.html

JS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gtuqaitsgr.html

TS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gtniextrrp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuxming.cn/Article/details/gtovfqntuk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gtepcnhtqv.html

Ruby: // fork 块
来源：http://dali.fzhhl.top/Article/details/gtnkzxkmto.html

C#:   Parallel.For
来源：http://dali.jianghu66.top/Article/details/gtvxujyfsf.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtbedqmfut.html

P. 常用工具函数
来源：http://dali.fzhhl.top/Article/details/gttarvmruh.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtvpslkjyt.html

[P01] 生成 UUID
来源：http://dali.zdqjudy.top/Article/details/gtouzldxdf.html

Py:   str(uuid.uuid4())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmpynyhy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.smart0.xyz/Article/details/gtmdlxyrsy.html

JS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtrkfnredx.html

TS:   crypto.randomUUID()
来源：http://dali.tianlin.xyz/Article/details/gtcpnbrnee.html

Java: UUID.randomUUID().toString()
来源：http://dali.fengsongda.top/Article/details/gtkermbqwp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ydzc1.top/Article/details/gtgwacvxdc.html

Ruby: SecureRandom.uuid
来源：http://dali.mhx1999.top/Article/details/gtvfzawqdn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.9152youxi.cn/Article/details/gtyokkhkys.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhxiwrpc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nanxuanxn.top/Article/details/gtklmirvbr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tian-w.cn/Article/details/gtigyeudwi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.feifeiyinyue.top/Article/details/gthmiyyqkq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hammf.cn/Article/details/gtagmjdkqn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yongpay.top/Article/details/gtsjmwbfyu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gtwhbgzjpt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gzhubu.top/Article/details/gtxcnztxpi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxuanxn.top/Article/details/gtvqrxxexj.html

[P03] 生成短随机字符串
来源：http://dali.yuanzhike.top/Article/details/gtnppjvphx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shzxlz.cn/Article/details/gthfpmapby.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.fengsongda.top/Article/details/gtqnfvqvez.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gtjbxbltdw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gtnnvbparb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuanzhike.top/Article/details/gtuqxzwkqp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dianchejie.cn/Article/details/gtlkqbcxlk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hywenlv.cn/Article/details/gtmlyezvph.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ehwqpu.com/Article/details/gtjbvmbqhh.html

[P04] 求长度
来源：http://dali.dashuyun.cn/Article/details/gtspmkviqf.html


<!-- 参考信息 -->