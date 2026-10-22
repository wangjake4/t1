代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gtxkrgrkye.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cashguo.top/Article/details/gtenxeolpx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xinyue.icu/Article/details/gtruyuuupj.html

JS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtrewvxhob.html

TS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gtzfqdlrhj.html

Java: resp.statusCode()
来源：http://dali.svipenyu.cn/Article/details/gtgnphhqvj.html

Go:   resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtqcljgyae.html

Ruby: resp.code.to_i
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjowlpprx.html

C#:   (int)resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gtdiggrmic.html

[L08] 并发请求多个地址
来源：http://dali.ybcxt.top/Article/details/gthzgdawpt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.kuanghao11.cn/Article/details/gtnbuwyrvx.html

PHP:  curl_multi_init() 系列
来源：http://dali.ybcxt.top/Article/details/gthcpgesks.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gtxdygwzls.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtepwyigxs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnxiangtu.top/Article/details/gtzwnzixda.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.316326.xyz/Article/details/gtfhmcsnfz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ehwqpu.com/Article/details/gtqgtucntn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dashuyun.cn/Article/details/gtreermlym.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtfzsyldzl.html

M. 命令行 / 进程 / 环境
来源：http://dali.tian-w.cn/Article/details/gtuwjzwjmh.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtektnzmjr.html

[M01] 读取命令行参数
来源：http://dali.fzhhl.top/Article/details/gtfsxdqfkw.html

Py:   sys.argv[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnkajdoq.html

PHP:  $argv;  $argc;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdnovirf.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtelkimaus.html

TS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtoerucppm.html

Java: args 数组（main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtbemporqr.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtgawxzewa.html

Ruby: ARGV
来源：http://dali.xuetiantiany.cn/Article/details/gtvbtcfivd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gtjcedmihd.html

[M02] 读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gtkxlgzykw.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gttsbrrgom.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gtssodiuwv.html

JS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtnkpqzbtv.html

TS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gtnccixuee.html

Java: System.getenv("HOME")
来源：http://dali.xuanzx.com/Article/details/gthppwlyyq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nwbrower.top/Article/details/gtcpmuwwrw.html

Ruby: ENV["HOME"]
来源：http://dali.0kj1m.cn/Article/details/gtbjkyziau.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtvssgnbbz.html

[M03] 执行外部命令
来源：http://dali.nwbrower.top/Article/details/gtfzrioakx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvtlqxil.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.svipenyu.cn/Article/details/gtegkfrozr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gtkhtyxxcr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ehwqpu.com/Article/details/gtawjwkfww.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cheryme.top/Article/details/gtgmitliwd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.kuanghao11.cn/Article/details/gtmsbbarge.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sxryk.cn/Article/details/gtuqyjejzn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenlongwang.top/Article/details/gtobswepwv.html

[M04] 获取当前工作目录
来源：http://dali.cucudq.cn/Article/details/gtapropiqs.html

Py:   os.getcwd()
来源：http://dali.sweek.top/Article/details/gtkaobvhrg.html

PHP:  getcwd();
来源：http://dali.zhengqikj.top/Article/details/gtcqviuclw.html

JS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gtwykmhzcc.html

TS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gtdvqbrfca.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yanxiufei.cn/Article/details/gttamoslmt.html

Go:   os.Getwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtxfpazn.html

Ruby: Dir.pwd
来源：http://dali.sweek.top/Article/details/gtflpfigca.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.andypj.xyz/Article/details/gthkcjzdde.html

[M05] 设置退出码
来源：http://dali.xuetiantiany.cn/Article/details/gtwauotkrc.html

Py:   sys.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtbgiypmak.html

PHP:  exit(1);
来源：http://dali.dianchejie.cn/Article/details/gtiukdzfzk.html

JS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtyhcaxdoj.html

TS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlkfnurx.html

Java: System.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtcuihirqp.html

Go:   os.Exit(1)
来源：http://dali.sxryk.cn/Article/details/gtqkrydkip.html

Ruby: exit 1
来源：http://dali.wangshuangyany.cn/Article/details/gtxqpoypdt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.9152youxi.cn/Article/details/gtjrugasve.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoehmktig.html

Py:   print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gtdvqvwiph.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shzxlz.cn/Article/details/gtuvxwkvcm.html

JS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjbwgjyl.html

TS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gtgpjqeraj.html

Java: System.err.println("err")
来源：http://dali.chenzaomai.com/Article/details/gtzscfyebc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sxryk.cn/Article/details/gtsliwusuf.html

Ruby: warn "err"
来源：http://dali.jiagoushi.top/Article/details/gtusxfljxl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gotoacloud.top/Article/details/gtazsfiftd.html

[M07] 判断是否为主入口
来源：http://dali.hammf.cn/Article/details/gtfkuwnwwl.html

Py:   if __name__ == "__main__":
来源：http://dali.xinyue.icu/Article/details/gtabpwtelb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258888.top/Article/details/gtilprlfgu.html

JS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gtrbnaasni.html

TS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gtlutgidmz.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvnhdtca.html

Go:   func main()
来源：http://dali.aibaodan.cn/Article/details/gtytyykrwk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tanke756.top/Article/details/gtpulccgiz.html

C#:   static void Main(string[] args)
来源：http://dali.kuanghao11.cn/Article/details/gtnyboihbr.html

[M08] 获取系统与运行时信息
来源：http://dali.kuanghao11.cn/Article/details/gtaqrzqsuy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gotoacloud.top/Article/details/gtrvfafayj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hywenlv.cn/Article/details/gtmssgdaik.html

JS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtfqjazesh.html

TS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtnijvvgjl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nwbrower.top/Article/details/gthufweauf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pycfn.com/Article/details/gtriobuhlm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sufxvd.cn/Article/details/gtqachkifg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shzxlz.cn/Article/details/gtjgnkjpga.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtththqtyq.html

N. 数据结构与算法
来源：http://dali.yangfankeji.com/Article/details/gttaqvktkf.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtdyulbumf.html

[N01] 二分查找（有序数组）
来源：http://dali.xinyue.icu/Article/details/gtypcfreqy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj20258888.top/Article/details/gttmzytxpl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sufxvd.cn/Article/details/gtecgcnrfl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtrkblglqc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gtscgqkdfw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gtcwyndieu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtsybpkkuw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.0kj1m.cn/Article/details/gtvbmhjbez.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtmdvqwmnh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinghuilouyu.cn/Article/details/gtyumzofxa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gtjzadqzui.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cashguo.top/Article/details/gtfuydeehr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtssuxomcb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gtcrnmwuyo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guannengcc.top/Article/details/gtufdtezwv.html

Go:   slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gthzkcwdzg.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcktodbsg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgufenzy.top/Article/details/gtcwkdsowo.html

[N03] 快速排序（分治示例）
来源：http://dali.feifeiyinyue.top/Article/details/gtkplvxzct.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yongpay.top/Article/details/gtxksuobdb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shzxlz.cn/Article/details/gtzxcgmxxj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gtqlissuga.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtbbfbaluq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.snrcjt.cn/Article/details/gthxqeiuub.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tanke756.top/Article/details/gtsjblvngi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuanzx.com/Article/details/gtlaiqguis.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shzxlz.cn/Article/details/gttwdadmoh.html

[N04] 斐波那契数列
来源：http://dali.zhengqikj.top/Article/details/gtkkafqdio.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gtesyspvnd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cheryme.top/Article/details/gttxvquqtm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtilsypjae.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtkvtldnom.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj202588.top/Article/details/gtdeejnvgj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cqqwz.cn/Article/details/gtqotljiqh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gtainjutei.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtaseywned.html

[N05] 最大公约数
来源：http://dali.haohaochexian.top/Article/details/gtubmzviud.html

Py:   math.gcd(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtafnytfce.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.snrcjt.cn/Article/details/gtpjiaihwa.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gtymkckhms.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtuqrsrvoo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfwsdedk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guowangkeji.top/Article/details/gtxgqwrvst.html

Ruby: a.gcd(b)
来源：http://dali.snrcjt.cn/Article/details/gtvllxqqpt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cqqwz.cn/Article/details/gttmkcfwig.html

[N06] 判断回文字符串
来源：http://dali.daria6918.cn/Article/details/gtryichhuj.html

Py:   s == s[::-1]
来源：http://dali.pycfn.com/Article/details/gteukyksql.html

PHP:  $s === strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gtouctaslc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtjwinriep.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtjyufjoxs.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.havefunace.top/Article/details/gtjabuxlap.html

Go:   // 双指针从两端比较
来源：http://dali.zhongyouzk.top/Article/details/gtyuqzipko.html

Ruby: s == s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkfrsblu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gtczqxedrt.html

[N07] 两数之和（返回下标）
来源：http://dali.gzhubu.top/Article/details/gthszvuply.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yueranfly.top/Article/details/gtgtyizorl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yongpay.top/Article/details/gtjskwncbk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cdnleiting.top/Article/details/gtbcnivcoi.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafvuqcnb.html

Java: // 手写 HashMap
来源：http://dali.hysaishi.cn/Article/details/gtuzjquxot.html

Go:   // 手写 map[int]int
来源：http://dali.nanxuanxn.top/Article/details/gtmstldevw.html

Ruby: // 手写 Hash
来源：http://dali.nanxuanxn.top/Article/details/gtjozgzomx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinqigfzy.top/Article/details/gtobhbmhcf.html

[N08] 生成全排列
来源：http://dali.guannengcc.top/Article/details/gtympvgjpn.html

Py:   itertools.permutations(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtrlvwbhql.html

PHP:  // 手写递归交换
来源：http://dali.gzhubu.top/Article/details/gtaqtjoeju.html

JS:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtwdalvsfa.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtnulnwjzk.html

Java: // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtjdaavnqq.html

Go:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtvngeiqii.html

Ruby: arr.permutation.to_a
来源：http://dali.zhoulong.xyz/Article/details/gtorphtwpc.html

C#:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtqerajjov.html

[N09] 栈与队列
来源：http://dali.bjfxy.top/Article/details/gtqwgjyiuq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tian-w.cn/Article/details/gttynpdfyx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yongpay.top/Article/details/gtuaigeqff.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gttcqrmwyn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jlsjyb.cn/Article/details/gtlghrcayj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtyxxexvgg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pengpengdd.cyou/Article/details/gtzbixepvv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtvdpswxzx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtrkihumxm.html

[N10] 链表节点定义
来源：http://dali.redwolf501.top/Article/details/gtkeusofie.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltrqiuey.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.smart0.xyz/Article/details/gtrharaizj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.redwolf501.top/Article/details/gtprhqnztx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcxdalja.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtebytublo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ppjwa.cn/Article/details/gtscsqhgjo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnxiangtu.top/Article/details/gtbdwigwcp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sufxvd.cn/Article/details/gtklunhqlx.html

[N11] 二叉树中序遍历
来源：http://dali.chenlongwang.top/Article/details/gtypolqhkc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.wangdashe.top/Article/details/gtfzodbzne.html

PHP:  // 手写递归函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdiyuwfl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtcuwlpoum.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gtjfvnmoig.html

Java: // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtaovinwkl.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gtysyqrctj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cashguo.top/Article/details/gtnuptiuhb.html

C#:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gtpznaudco.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jiagoushi.top/Article/details/gtvweperuq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigufen.top/Article/details/gtqxkjdnje.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlscqragb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gtsyeiduzq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gtfonwbvro.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gttbpvjqgs.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenzaomai.com/Article/details/gtrnhwxkga.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ybcxt.top/Article/details/gtajbapjxn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gtfrgwdbce.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtrtbvcgjc.html

O. 并发与异步
来源：http://dali.jlsjyb.cn/Article/details/gtpcxnvzyc.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtyfuwvxyg.html

[O01] 启动一个线程
来源：http://dali.shuidangran.top/Article/details/gtttcvunua.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xziqi.cn/Article/details/gtxqugtjzd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nwbrower.top/Article/details/gtyfedhdsk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj202588.top/Article/details/gtuwmyofxy.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gtmnznfuic.html

Java: new Thread(() -> f()).start()
来源：http://dali.tian-w.cn/Article/details/gtucgufokh.html

Go:   go f()
来源：http://dali.nwbrower.top/Article/details/gtrlidoedf.html

Ruby: Thread.new { f }
来源：http://dali.xylfe.cn/Article/details/gteguwvltf.html

C#:   Task.Run(() => F());
来源：http://dali.xinyue.icu/Article/details/gthhvqqzgx.html

[O02] 使用线程池
来源：http://dali.chenlongwang.top/Article/details/gtqupswids.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.quarkkingdee.top/Article/details/gtvuoylqwk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guowangkeji.top/Article/details/gtiinsatyo.html

JS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gthdleoozo.html

TS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlqnngmn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tian-w.cn/Article/details/gtmjmcbbcd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenzaomai.com/Article/details/gttxwvqflr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xinyue.icu/Article/details/gtpdxadjhj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yueranfly.top/Article/details/gtrqcttftd.html

[O03] 加锁保护共享数据
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvunrctp.html

Py:   with lock: shared += 1
来源：http://dali.yvedp.cn/Article/details/gtppwzozzh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.snrcjt.cn/Article/details/gtnnuastvt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.316326.xyz/Article/details/gtikiuftqr.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gtqkaylamg.html

Java: synchronized (this) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyklyywt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fzhhl.top/Article/details/gtgkizralx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sysykeji.top/Article/details/gtuyttfizn.html

C#:   lock (gate) { shared++; }
来源：http://dali.zdqjudy.top/Article/details/gtjbylveoo.html

[O04] 定义异步函数并等待
来源：http://dali.chenlongwang.top/Article/details/gtfxfjbfkx.html

Py:   async def f():⏎    await g()
来源：http://dali.aizwys.cn/Article/details/gteperzpji.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.svipenyu.cn/Article/details/gtkawrmjoe.html

JS:   async function f() { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gtryakybkb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sxryk.cn/Article/details/gtxelzixci.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hywenlv.cn/Article/details/gtmsxrpnfc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shuidangran.top/Article/details/gtqpksvhrg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cucudq.cn/Article/details/gtkfhlajci.html

C#:   async Task F() { await G(); }
来源：http://dali.ybcxt.top/Article/details/gtnzostcms.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenzaomai.com/Article/details/gtldwpieet.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgubddkgp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.smart0.xyz/Article/details/gtnyatsahj.html

JS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gtglmwusne.html

TS:   await Promise.all(tasks)
来源：http://dali.chenzaomai.com/Article/details/gtgwgxbmgj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuxming.cn/Article/details/gttlkftftf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jlsjyb.cn/Article/details/gtujjfdozj.html

Ruby: threads.map(&:join)
来源：http://dali.yueranfly.top/Article/details/gtstxxmvjs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ppjwa.cn/Article/details/gtjkimbldr.html

[O06] 使用进程池
来源：http://dali.gotoacloud.top/Article/details/gtbybcipdx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.316326.xyz/Article/details/gtdcnsctnz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gzhubu.top/Article/details/gtubxxqvkq.html

JS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gtgzkbjntb.html

TS:   // child_process / cluster 模块
来源：http://dali.tian-w.cn/Article/details/gtxzdhvuhr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jianghu66.top/Article/details/gtpssegjyc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gzhubu.top/Article/details/gtclyctqxx.html

Ruby: // fork 块
来源：http://dali.zhengqikj.top/Article/details/gtdphtmidh.html

C#:   Parallel.For
来源：http://dali.snrcjt.cn/Article/details/gtbpehkyck.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtisqnuxyy.html

P. 常用工具函数
来源：http://dali.zhiwuduotai.top/Article/details/gtpkpaatyk.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtbemgrzvp.html

[P01] 生成 UUID
来源：http://dali.fengsongda.top/Article/details/gtoumcgqzj.html

Py:   str(uuid.uuid4())
来源：http://dali.yvedp.cn/Article/details/gtnmdtyzmw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.mhx1999.top/Article/details/gtlolxcavy.html

JS:   crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gtksqozrgp.html

TS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gtxspgdtdj.html

Java: UUID.randomUUID().toString()
来源：http://dali.ehwqpu.com/Article/details/gteanqxnmd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.birdmap.top/Article/details/gtynigcuqi.html

Ruby: SecureRandom.uuid
来源：http://dali.yuanzhike.top/Article/details/gtgpsihtdr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgyheqeld.html

[P02] MD5 / SHA256 摘要
来源：http://dali.meibo888.top/Article/details/gtrmhudtso.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.guannengcc.top/Article/details/gteskobiga.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cucudq.cn/Article/details/gtlsodypxx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xylfe.cn/Article/details/gtgidiegeq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xylfe.cn/Article/details/gtorcwudcv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtfjwrfwkv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ppjwa.cn/Article/details/gtmgysnocg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtdcoqvepb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbhoeuho.html

[P03] 生成短随机字符串
来源：http://dali.guannengcc.top/Article/details/gthzpwazbx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.birdmap.top/Article/details/gtwyikzktn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xuanzx.com/Article/details/gtoswwwixn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gtwgowdvbj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gttdptkzjh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dianchejie.cn/Article/details/gtcbkqjrqd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.bjfxy.top/Article/details/gthgwndses.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.vqdsnc.cn/Article/details/gtbciauugs.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenzaomai.com/Article/details/gtrwszvmgz.html

[P04] 求长度
来源：http://dali.smart0.xyz/Article/details/gtnrnmunyo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gogol.net.cn/Article/details/gtsdoqvnpr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtftrfrjkr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxddxiax.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjozedxd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.c1oappe.top/Article/details/gtkriazfnb.html

Go:   len(arr);  len(m)
来源：http://dali.cucudq.cn/Article/details/gtoazyzqtq.html

Ruby: x.length;  x.size
来源：http://dali.cdnleiting.top/Article/details/gtoxfztsft.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cdnleiting.top/Article/details/gtieejoeoj.html


<!-- 参考信息 -->