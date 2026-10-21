代发 wailian999

Py:   resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtwrwjshew.html

PHP:  json_decode($body, true);
来源：http://dali.zdqjudy.top/Article/details/gtrnoaszkh.html

JS:   await resp.json()
来源：http://dali.meibo888.top/Article/details/gtrajlgicc.html

TS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtqalhsxvu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtguoqujos.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenzaomai.com/Article/details/gtrcobljlx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangdashe.top/Article/details/gtazahdpmh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gotoacloud.top/Article/details/gthhpbslrv.html

[L07] 处理 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gtkswquwvo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guannengcc.top/Article/details/gtmbqggnff.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuanzhike.top/Article/details/gtgnbpgdkv.html

JS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gtldjuybyr.html

TS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gtcgjvanfp.html

Java: resp.statusCode()
来源：http://dali.ivvv.top/Article/details/gtyxnjqlbo.html

Go:   resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gtlzoqjlgg.html

Ruby: resp.code.to_i
来源：http://dali.aibaodan.cn/Article/details/gtpyojclxf.html

C#:   (int)resp.StatusCode
来源：http://dali.gotoacloud.top/Article/details/gtgcgocxjw.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpyoqnvk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pengpengdd.cyou/Article/details/gtiixcyxbu.html

PHP:  curl_multi_init() 系列
来源：http://dali.cashguo.top/Article/details/gtipfplqru.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtlkysflou.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gtvpfugrgn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.c1oappe.top/Article/details/gtfrgzpfkw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ivvv.top/Article/details/gtadyzxdlu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fengsongda.top/Article/details/gtdweohmoo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gtyhlkkfuw.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtxcfhlhnz.html

M. 命令行 / 进程 / 环境
来源：http://dali.dashuyun.cn/Article/details/gtjliwtzza.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtqxvkxxxt.html

[M01] 读取命令行参数
来源：http://dali.wangshuangyany.cn/Article/details/gtczfqvvqt.html

Py:   sys.argv[1:]
来源：http://dali.yvedp.cn/Article/details/gtcmhkwyei.html

PHP:  $argv;  $argc;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqnzdmfz.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gtbyftvdyd.html

TS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gtmifyjbbi.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gtqfusmvpr.html

Go:   os.Args[1:]
来源：http://dali.iojbl.cn/Article/details/gtvksoswox.html

Ruby: ARGV
来源：http://dali.yueranfly.top/Article/details/gtdzvlgjfs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hammf.cn/Article/details/gtyqitrqku.html

[M02] 读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gtkyggbets.html

Py:   os.environ.get("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtoreoxdvu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gtvoflpznz.html

JS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtruhhlrla.html

TS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gtfldpxmnv.html

Java: System.getenv("HOME")
来源：http://dali.havefunace.top/Article/details/gtvxqdycnf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gttshiknfa.html

Ruby: ENV["HOME"]
来源：http://dali.cheryme.top/Article/details/gtqsfteyxn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtilytwezz.html

[M03] 执行外部命令
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvcopsys.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xylfe.cn/Article/details/gtyeavjxkd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yvedp.cn/Article/details/gthxcxvcie.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gtufelgjle.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonkijvtn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dashuyun.cn/Article/details/gtgcbrorbf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yueranfly.top/Article/details/gtbnsesqcp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.quarkkingdee.top/Article/details/gtgmgfanbq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fengsongda.top/Article/details/gtawtadhxf.html

[M04] 获取当前工作目录
来源：http://dali.aibaodan.cn/Article/details/gtngjjvegp.html

Py:   os.getcwd()
来源：http://dali.zhongyouzk.top/Article/details/gtxfjxusbq.html

PHP:  getcwd();
来源：http://dali.xylfe.cn/Article/details/gtgfbqqyst.html

JS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtbpkvsrrn.html

TS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtoyogdyov.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shuidangran.top/Article/details/gtaguwxome.html

Go:   os.Getwd()
来源：http://dali.sweek.top/Article/details/gtgiwespwc.html

Ruby: Dir.pwd
来源：http://dali.fengsongda.top/Article/details/gtdrmkeoqz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgfzy.top/Article/details/gtwineeftv.html

[M05] 设置退出码
来源：http://dali.jlsjyb.cn/Article/details/gtzobaslky.html

Py:   sys.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtxoxcipaq.html

PHP:  exit(1);
来源：http://dali.ybcxt.top/Article/details/gtmvsclmea.html

JS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gtdhetqcfy.html

TS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtczteaoti.html

Java: System.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtasphhoxl.html

Go:   os.Exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtqmgswbxe.html

Ruby: exit 1
来源：http://dali.zhiwuduotai.top/Article/details/gtuhbbwieg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ybcxt.top/Article/details/gtzyztkezm.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gtrncjhlbd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gtmeampyfg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pycfn.com/Article/details/gtxaxlxccl.html

JS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gthmhpaggv.html

TS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gtmstnfofn.html

Java: System.err.println("err")
来源：http://dali.bjfxy.top/Article/details/gtagjxslye.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhixingplan.top/Article/details/gtvtmuprci.html

Ruby: warn "err"
来源：http://dali.zdqjudy.top/Article/details/gtacnwlxxv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.smart0.xyz/Article/details/gtadmiutwy.html

[M07] 判断是否为主入口
来源：http://dali.zhiwuduotai.top/Article/details/gtrluquysx.html

Py:   if __name__ == "__main__":
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjhklmdr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.iojbl.cn/Article/details/gtjgmwsdud.html

JS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgabfues.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtixuaqvxd.html

Java: public static void main(String[] args)
来源：http://dali.guowangkeji.top/Article/details/gtdrthlaul.html

Go:   func main()
来源：http://dali.xylfe.cn/Article/details/gthuyefuow.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpuipopjh.html

C#:   static void Main(string[] args)
来源：http://dali.sweek.top/Article/details/gtkkmarvzq.html

[M08] 获取系统与运行时信息
来源：http://dali.cdnleiting.top/Article/details/gtngglauwh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shuidangran.top/Article/details/gtopgzehzq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yongpay.top/Article/details/gtpucgqmod.html

JS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gteqpblhze.html

TS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gthcspoiab.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.kuanghao11.cn/Article/details/gtyjzvgjac.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cashguo.top/Article/details/gtuyhqbetl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuanzhike.top/Article/details/gttprjjjbl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hammf.cn/Article/details/gtgslovjav.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqxxfclso.html

N. 数据结构与算法
来源：http://dali.ydzc1.top/Article/details/gtzkvtzooe.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtwyyoogdh.html

[N01] 二分查找（有序数组）
来源：http://dali.hongshengwenyu.top/Article/details/gtnpaznaxg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gttmhmvpwm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tian-w.cn/Article/details/gthccnjojv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gtjikmvuqh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtnwowyand.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gtbcfjtwjv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cashguo.top/Article/details/gtlpfsxjji.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gaohongyu789.top/Article/details/gtharqxdit.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtlextthwp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.svipenyu.cn/Article/details/gteqyulotl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjphnccrn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sxryk.cn/Article/details/gtrpesujdm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtiymbhari.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gthxrtphtw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnxiangtu.top/Article/details/gtwtimewru.html

Go:   slices.Sort(arr)
来源：http://dali.ppjwa.cn/Article/details/gtmfbucjhs.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gtzrutoljy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dashuyun.cn/Article/details/gtwwlhttgt.html

[N03] 快速排序（分治示例）
来源：http://dali.yongpay.top/Article/details/gtagkbktjo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hnqzz.top/Article/details/gtritzthik.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sxryk.cn/Article/details/gtsmjdqmyf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gtdhvcqnpr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gtpwdrwrnr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zdqjudy.top/Article/details/gtakhxcifd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.meibo888.top/Article/details/gtrtmygbjl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhoulong.xyz/Article/details/gtyolifbkq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigufen.top/Article/details/gtcccxfyrs.html

[N04] 斐波那契数列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkefkzte.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.mhx1999.top/Article/details/gtcdcllqgr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gtbgdwozzw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwvwxmjn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gttbsmelbg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gtscjnkxlc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yanxiufei.cn/Article/details/gtshdqpcgz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gteadwsyaj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtelifnjhy.html

[N05] 最大公约数
来源：http://dali.hongshengwenyu.top/Article/details/gtxtzfjrgy.html

Py:   math.gcd(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtukekfzkx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj202588.top/Article/details/gtcgpfmzif.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.bjfxy.top/Article/details/gteigexujj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gtepnqhfwc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxinkj.top/Article/details/gthbqwnmxk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.vqdsnc.cn/Article/details/gtkwynculb.html

Ruby: a.gcd(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmsvuler.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jiagoushi.top/Article/details/gtdkdygnug.html

[N06] 判断回文字符串
来源：http://dali.svipenyu.cn/Article/details/gtajhjjnkr.html

Py:   s == s[::-1]
来源：http://dali.jianghu66.top/Article/details/gtffiqqdmc.html

PHP:  $s === strrev($s);
来源：http://dali.pycfn.com/Article/details/gtalpkzrvd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtizyuscqa.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtxakfqdkx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hysaishi.cn/Article/details/gtnhfjembw.html

Go:   // 双指针从两端比较
来源：http://dali.andypj.xyz/Article/details/gtltnmuujh.html

Ruby: s == s.reverse
来源：http://dali.shuidangran.top/Article/details/gtehprdofa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gtdzgvrocu.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258888.top/Article/details/gtrizprvyb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.quarkkingdee.top/Article/details/gtduecyarx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xziqi.cn/Article/details/gtvmstdffp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sysykeji.top/Article/details/gttaqhxrtt.html

TS:   // 手写 Map<string, number>
来源：http://dali.fzhhl.top/Article/details/gthcxtrgry.html

Java: // 手写 HashMap
来源：http://dali.yanxiufei.cn/Article/details/gtihgkiyiy.html

Go:   // 手写 map[int]int
来源：http://dali.yvedp.cn/Article/details/gtbirflpux.html

Ruby: // 手写 Hash
来源：http://dali.c1oappe.top/Article/details/gttkdcudvp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuetiantiany.cn/Article/details/gtxcrvqwtu.html

[N08] 生成全排列
来源：http://dali.tianlin.xyz/Article/details/gtdyikufjt.html

Py:   itertools.permutations(arr)
来源：http://dali.redwolf501.top/Article/details/gtmmfbvwww.html

PHP:  // 手写递归交换
来源：http://dali.xinyue.icu/Article/details/gtjxspnsss.html

JS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtyxnvajqu.html

TS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtswxgbpbl.html

Java: // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtmviykcao.html

Go:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gttmqmokmu.html

Ruby: arr.permutation.to_a
来源：http://dali.yangfankeji.com/Article/details/gtbydtdaak.html

C#:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtcojnmmkq.html

[N09] 栈与队列
来源：http://dali.birdmap.top/Article/details/gtdwcftaku.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jyoumei.cn/Article/details/gtjqhezqyo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gtjixvahps.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtbzosavkx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jiagoushi.top/Article/details/gtvciyztkl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.bjfxy.top/Article/details/gtixvrjxwl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.c1oappe.top/Article/details/gtvmbfvmrd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtzsltdnpd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ybcxt.top/Article/details/gtycvyqcry.html

[N10] 链表节点定义
来源：http://dali.wangdashe.top/Article/details/gtiwazgklj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuetiantiany.cn/Article/details/gtmmoxuxzo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ydzc1.top/Article/details/gtflyqofgu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ybcxt.top/Article/details/gtewkjcsxu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gogol.net.cn/Article/details/gtmnqvvgie.html

Java: class Node { int v; Node next; }
来源：http://dali.nanxinkj.top/Article/details/gtlkqbbonq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbnfxoisp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhixingplan.top/Article/details/gtqfckehjw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cdnleiting.top/Article/details/gtbvcdpwau.html

[N11] 二叉树中序遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhdhpduz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hywenlv.cn/Article/details/gtqgnydpgw.html

PHP:  // 手写递归函数
来源：http://dali.jlsjyb.cn/Article/details/gtcbfnrnah.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gthtbxcmod.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtbyltxnyh.html

Java: // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtzlfwvlpy.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtbkvctzec.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tian-w.cn/Article/details/gtkdzyzshn.html

C#:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gtimjswwrn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yueranfly.top/Article/details/gtlavxxjwd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tanke756.top/Article/details/gtnfpghdla.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jianghu66.top/Article/details/gtbsxicqkb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gtglxastbs.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gtflzczssb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sweek.top/Article/details/gtcruqlgmp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cashguo.top/Article/details/gtulcdcxuf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yueranfly.top/Article/details/gtzgfnewxi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gtrgwiljzv.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtbqnzmtyd.html

O. 并发与异步
来源：http://dali.ydzc1.top/Article/details/gtfoolpthp.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtfgfyvhtj.html

[O01] 启动一个线程
来源：http://dali.tanke756.top/Article/details/gtitljmkte.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yonumen.top/Article/details/gteqgmycyf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hammf.cn/Article/details/gtguswmrgp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cqqwz.cn/Article/details/gtlwaufvdm.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gtxeeoewvp.html

Java: new Thread(() -> f()).start()
来源：http://dali.shuidangran.top/Article/details/gtxoarkmln.html

Go:   go f()
来源：http://dali.havefunace.top/Article/details/gtiacliuok.html

Ruby: Thread.new { f }
来源：http://dali.ybcxt.top/Article/details/gthacrfhzs.html

C#:   Task.Run(() => F());
来源：http://dali.316326.xyz/Article/details/gttmpgosya.html

[O02] 使用线程池
来源：http://dali.cdnleiting.top/Article/details/gtzaleqcph.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gtufngfqvl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gtcmevxnfv.html

JS:   // worker_threads 线程池
来源：http://dali.jlsjyb.cn/Article/details/gtmfbpsprr.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmrzvbpe.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.andypj.xyz/Article/details/gteijeyruh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ppjwa.cn/Article/details/gthadgfngt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zycfv.cn/Article/details/gtplycolkd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenjidiqi.icu/Article/details/gtqiudmpau.html

[O03] 加锁保护共享数据
来源：http://dali.gaohongyu789.top/Article/details/gthakzckcs.html

Py:   with lock: shared += 1
来源：http://dali.xylfe.cn/Article/details/gtrzioappl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuxming.cn/Article/details/gtclmtpbma.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sweek.top/Article/details/gtbdcriakw.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gtghhktcqb.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gtzfcdbldd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yanxiufei.cn/Article/details/gtvjjscooq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.quarkkingdee.top/Article/details/gtfwgglyoe.html

C#:   lock (gate) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gtujxzaoak.html

[O04] 定义异步函数并等待
来源：http://dali.zhoulong.xyz/Article/details/gtwfhetxyf.html

Py:   async def f():⏎    await g()
来源：http://dali.guannengcc.top/Article/details/gtxhjtofda.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj202588.top/Article/details/gttwikgryu.html

JS:   async function f() { await g(); }
来源：http://dali.smart0.xyz/Article/details/gtxyxgzyjx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gtbtwawrkh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.guowangkeji.top/Article/details/gtzfudxkvh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hfpthk.cn/Article/details/gtfqrlyyfy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.iojbl.cn/Article/details/gtzkpbdudl.html

C#:   async Task F() { await G(); }
来源：http://dali.dianchejie.cn/Article/details/gtvpzunbqm.html

[O05] 并发执行并等待全部完成
来源：http://dali.yanxiufei.cn/Article/details/gtbrriepiq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjwsscpj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sweek.top/Article/details/gtkymigtto.html

JS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gtyvhddcno.html

TS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gteidabcmw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.birdmap.top/Article/details/gtgthjrbis.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenjidiqi.icu/Article/details/gtfdrzlnti.html

Ruby: threads.map(&:join)
来源：http://dali.yueranfly.top/Article/details/gthewodxow.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jianghu66.top/Article/details/gtaqzuatlz.html

[O06] 使用进程池
来源：http://dali.yonumen.top/Article/details/gtnckdnlwm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.aizwys.cn/Article/details/gtobcctftb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guannengcc.top/Article/details/gtrfktmhmm.html

JS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gtvadxjjbi.html

TS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gtjdxzncch.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yueranfly.top/Article/details/gtabebslul.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbucomvz.html

Ruby: // fork 块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzcynezy.html

C#:   Parallel.For
来源：http://dali.xziqi.cn/Article/details/gtmyzauydm.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtdoaltrfi.html

P. 常用工具函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvjmktrk.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtdvvoplhm.html

[P01] 生成 UUID
来源：http://dali.svipenyu.cn/Article/details/gtbjnkntqe.html

Py:   str(uuid.uuid4())
来源：http://dali.sxryk.cn/Article/details/gtrbslvify.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenzaomai.com/Article/details/gtzgstfaof.html

JS:   crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gtvptsfqpy.html

TS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgyvmvkq.html

Java: UUID.randomUUID().toString()
来源：http://dali.yangfankeji.com/Article/details/gtjxwtgeof.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sxryk.cn/Article/details/gtcwxqmkpz.html

Ruby: SecureRandom.uuid
来源：http://dali.pycfn.com/Article/details/gttgtclqoa.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jlsjyb.cn/Article/details/gtpziwkufs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cdnleiting.top/Article/details/gtnhrtfxpk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yangfankeji.com/Article/details/gtstybjugq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ybcxt.top/Article/details/gtlizezbxv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yueranfly.top/Article/details/gtyuzdeibb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tian-w.cn/Article/details/gteysnlecv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ehwqpu.com/Article/details/gtouesjuxr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yangfankeji.com/Article/details/gtnjqeqlnl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.birdmap.top/Article/details/gtdjirewxg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aizwys.cn/Article/details/gtinxrarsv.html

[P03] 生成短随机字符串
来源：http://dali.haohaochexian.top/Article/details/gttphsokba.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jyoumei.cn/Article/details/gtcollgmmd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ppjwa.cn/Article/details/gtgigmnrzu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj202588.top/Article/details/gtuugmrfno.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gtuvdmyeyt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.meibo888.top/Article/details/gtnioofvqb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ivvv.top/Article/details/gtgkmcesaz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.316326.xyz/Article/details/gtogjeisdf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zycfv.cn/Article/details/gtrgcrwqwz.html

[P04] 求长度
来源：http://dali.andypj.xyz/Article/details/gtuycsrytq.html


<!-- 参考信息 -->