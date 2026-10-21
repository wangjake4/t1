代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtyvkpozio.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guannengcc.top/Article/details/gtefwnefgp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gaohongyu789.top/Article/details/gtppmklzql.html

JS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gtugphmnzl.html

TS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gtyvdmpctp.html

Java: resp.statusCode()
来源：http://dali.wangshuangyany.cn/Article/details/gtmiliqdvi.html

Go:   resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gtdcibkwdj.html

Ruby: resp.code.to_i
来源：http://dali.chenlongwang.top/Article/details/gthrxuovyh.html

C#:   (int)resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gtulfeboot.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gtrrzcdpja.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj202588.top/Article/details/gtuxjyoyas.html

PHP:  curl_multi_init() 系列
来源：http://dali.tianlin.xyz/Article/details/gtrrwvxcgf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gtdjouhupa.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gtjusnkyfs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tianlin.xyz/Article/details/gtbiouihpa.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fengsongda.top/Article/details/gtvzizfzrm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gtsjnvlszl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hysaishi.cn/Article/details/gtnmnmvgdl.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtldzbjcuk.html

M. 命令行 / 进程 / 环境
来源：http://dali.ydzc1.top/Article/details/gtjbyfouuc.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtfwwkafaw.html

[M01] 读取命令行参数
来源：http://dali.xziqi.cn/Article/details/gtvacxcsdk.html

Py:   sys.argv[1:]
来源：http://dali.zycfv.cn/Article/details/gtcpwazhwp.html

PHP:  $argv;  $argc;
来源：http://dali.316326.xyz/Article/details/gtyhfzwmjf.html

JS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gtfqwhibkk.html

TS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtkilhecdw.html

Java: args 数组（main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gtjlicbxlb.html

Go:   os.Args[1:]
来源：http://dali.chenlongwang.top/Article/details/gttnoitypt.html

Ruby: ARGV
来源：http://dali.meibo888.top/Article/details/gtidnbzhsc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gtvtsznrih.html

[M02] 读取环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gtyqybnmej.html

Py:   os.environ.get("HOME")
来源：http://dali.sxryk.cn/Article/details/gtqsnbgdii.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gttjfjunak.html

JS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gtjbyuhplg.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtuirxafzx.html

Java: System.getenv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gttcvvjhop.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yongpay.top/Article/details/gtufzgbvmf.html

Ruby: ENV["HOME"]
来源：http://dali.ehwqpu.com/Article/details/gtulrjuzrs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gtejfzmxjk.html

[M03] 执行外部命令
来源：http://dali.zhixingplan.top/Article/details/gtjxwalaqu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yongpay.top/Article/details/gttccvjumw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gotoacloud.top/Article/details/gtjampghkm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gtcijbtgkh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gtfpkehsel.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sweek.top/Article/details/gtpjyunphk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.9152youxi.cn/Article/details/gtpqyczlsp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzyrhjjq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.meibo888.top/Article/details/gtkgjzmyra.html

[M04] 获取当前工作目录
来源：http://dali.nwbrower.top/Article/details/gtvnlyyusj.html

Py:   os.getcwd()
来源：http://dali.yonumen.top/Article/details/gtovgdqgpj.html

PHP:  getcwd();
来源：http://dali.smart0.xyz/Article/details/gtnhlccomx.html

JS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gtekzhdedh.html

TS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gtlxzjrnil.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ppjwa.cn/Article/details/gtfpmxjvwq.html

Go:   os.Getwd()
来源：http://dali.zdqjudy.top/Article/details/gtcbsjlfet.html

Ruby: Dir.pwd
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwwfhmzv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuetiantiany.cn/Article/details/gtesazffuz.html

[M05] 设置退出码
来源：http://dali.shanyushiyangtech.top/Article/details/gtctphozme.html

Py:   sys.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtesfoutfx.html

PHP:  exit(1);
来源：http://dali.dianchejie.cn/Article/details/gtejmvphyp.html

JS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtcpnsscka.html

TS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtwdumpkod.html

Java: System.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtstvmcmgm.html

Go:   os.Exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtxccyeget.html

Ruby: exit 1
来源：http://dali.bjfxy.top/Article/details/gtjncqnfdq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zdqjudy.top/Article/details/gtjyfavmyd.html

[M06] 向标准错误输出
来源：http://dali.jiagoushi.top/Article/details/gtnxgzkozc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigfzy.top/Article/details/gthlpxtkgg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnqzz.top/Article/details/gtngjsmwwc.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gthzavqfom.html

TS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gtreqqqkif.html

Java: System.err.println("err")
来源：http://dali.chenlongwang.top/Article/details/gtfehvviha.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangdashe.top/Article/details/gtxgjrqbtd.html

Ruby: warn "err"
来源：http://dali.wangshuangyany.cn/Article/details/gtzwfbdcnq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tianlin.xyz/Article/details/gtdnsixycn.html

[M07] 判断是否为主入口
来源：http://dali.jianghu66.top/Article/details/gtdwjrhusr.html

Py:   if __name__ == "__main__":
来源：http://dali.shuidangran.top/Article/details/gtgfryxfqo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shuidangran.top/Article/details/gtcjppcvoz.html

JS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gtzagvfebq.html

TS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gtfvvhlnki.html

Java: public static void main(String[] args)
来源：http://dali.ppjwa.cn/Article/details/gtnbpzfdix.html

Go:   func main()
来源：http://dali.nanxinkj.top/Article/details/gtjdajittl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuxming.cn/Article/details/gtmwbcrekg.html

C#:   static void Main(string[] args)
来源：http://dali.sufxvd.cn/Article/details/gtvdcxklmr.html

[M08] 获取系统与运行时信息
来源：http://dali.andypj.xyz/Article/details/gtlspwqzie.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ivvv.top/Article/details/gtgwuttcqg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnxiangtu.top/Article/details/gtleaegghw.html

JS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gtornrwqkr.html

TS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtesqtkkrf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aizwys.cn/Article/details/gtxfptufny.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cheryme.top/Article/details/gtclbelmgb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shzxlz.cn/Article/details/gtzjwtmxcy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zycfv.cn/Article/details/gtbiegcuib.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtymlwrhco.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gtdruucflx.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtlfxsfdye.html

[N01] 二分查找（有序数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwicdeke.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtgrkehmpm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gzhubu.top/Article/details/gtqrsaoxdr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrajxhgra.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jiagoushi.top/Article/details/gteeufiezr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtarsbyndr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtzpkfxalc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigfzy.top/Article/details/gtrilmxypv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtrqsenjsz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigufen.top/Article/details/gtrtratado.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gtidewqsbx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sysykeji.top/Article/details/gtoyzlwdam.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gtzjtnaysp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gtqdqvdkzf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmqooaal.html

Go:   slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtpwhnbidp.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gtnsyxavyz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sxryk.cn/Article/details/gteiibygha.html

[N03] 快速排序（分治示例）
来源：http://dali.cashguo.top/Article/details/gtdrmwheun.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ydzc1.top/Article/details/gtkkkpicpv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hywenlv.cn/Article/details/gtjvrrjcnn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gtaquvnfoh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gtqgdaporb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhoulong.xyz/Article/details/gtabfweiql.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenjidiqi.icu/Article/details/gtuaotmnly.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zycfv.cn/Article/details/gtcpapjqvp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.vqdsnc.cn/Article/details/gtxpkwlpir.html

[N04] 斐波那契数列
来源：http://dali.shangyingyoupin.top/Article/details/gttiujhnxl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.mhx1999.top/Article/details/gtaqzvawvz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gtkvysxeqh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtdeolrafi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gtijjtweea.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.havefunace.top/Article/details/gtqfsbaagf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenjidiqi.icu/Article/details/gtxijsyxow.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefrpqzah.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gtwiujqcyv.html

[N05] 最大公约数
来源：http://dali.sysykeji.top/Article/details/gtsbvrndqa.html

Py:   math.gcd(a, b)
来源：http://dali.daxiang520.top/Article/details/gtboaerkbv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xylfe.cn/Article/details/gtltgorxdj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.vqdsnc.cn/Article/details/gtbyqwednq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ppjwa.cn/Article/details/gtjnccofdt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.0kj1m.cn/Article/details/gtybyuuebe.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gaohongyu789.top/Article/details/gtwvpuprda.html

Ruby: a.gcd(b)
来源：http://dali.jqgufenzy.top/Article/details/gtfjiuxzxn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhoulong.xyz/Article/details/gtrzplmumt.html

[N06] 判断回文字符串
来源：http://dali.fengsongda.top/Article/details/gtreoaiocd.html

Py:   s == s[::-1]
来源：http://dali.yonumen.top/Article/details/gtyfnzunmk.html

PHP:  $s === strrev($s);
来源：http://dali.redwolf501.top/Article/details/gtuqexsmle.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtncpmmmwd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtmzitixne.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.vqdsnc.cn/Article/details/gtyiymjttk.html

Go:   // 双指针从两端比较
来源：http://dali.tanke756.top/Article/details/gtvpvurkoe.html

Ruby: s == s.reverse
来源：http://dali.yuxming.cn/Article/details/gtufgyzemj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gtnmnjnmdt.html

[N07] 两数之和（返回下标）
来源：http://dali.hongshengwenyu.top/Article/details/gtkecfrnty.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzllcfakm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yuanzhike.top/Article/details/gtowuvdxid.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangdashe.top/Article/details/gtsdwdbzgl.html

TS:   // 手写 Map<string, number>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomevrunv.html

Java: // 手写 HashMap
来源：http://dali.redwolf501.top/Article/details/gtawbzmywc.html

Go:   // 手写 map[int]int
来源：http://dali.zdqjudy.top/Article/details/gtzpxqdeha.html

Ruby: // 手写 Hash
来源：http://dali.hfpthk.cn/Article/details/gtgyudkotp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinqigufen.top/Article/details/gtaxcmcfhg.html

[N08] 生成全排列
来源：http://dali.feifeiyinyue.top/Article/details/gtgfexokhr.html

Py:   itertools.permutations(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjfqxalc.html

PHP:  // 手写递归交换
来源：http://dali.yangfankeji.com/Article/details/gtexhxtcww.html

JS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtkxnqhlcx.html

TS:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtvmyqdnfg.html

Java: // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuftjwtas.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gthlokmguw.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258888.top/Article/details/gtununemvu.html

C#:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtxvkusyal.html

[N09] 栈与队列
来源：http://dali.sxryk.cn/Article/details/gtsjjyvtrs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtgcvderjd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtsvytmwhq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gtqnmqdrqo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.daxiang520.top/Article/details/gtklbcgjfr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aibaodan.cn/Article/details/gthspazjex.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.snrcjt.cn/Article/details/gtjzkovlwq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtmiyrbinz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtvrzfwcrz.html

[N10] 链表节点定义
来源：http://dali.316326.xyz/Article/details/gtwhejtvyq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hnxiangtu.top/Article/details/gtumjmuwlq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cucudq.cn/Article/details/gtrawpogvi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shzxlz.cn/Article/details/gtybxkjxcj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.haohaochexian.top/Article/details/gtxiewgxer.html

Java: class Node { int v; Node next; }
来源：http://dali.quarkkingdee.top/Article/details/gtguqhpqew.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hywenlv.cn/Article/details/gtjyoeybzm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gtqcfvmmqe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dianchejie.cn/Article/details/gthofwvptv.html

[N11] 二叉树中序遍历
来源：http://dali.xylfe.cn/Article/details/gtoyvldbsg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sufxvd.cn/Article/details/gttvpnxrcu.html

PHP:  // 手写递归函数
来源：http://dali.nanxinkj.top/Article/details/gtortjfnae.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gtgulueomy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhixingplan.top/Article/details/gtlfmogdpv.html

Java: // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtxltalboi.html

Go:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtxldewibu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhixingplan.top/Article/details/gtgfhixxlw.html

C#:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gttqgbpwxb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.feifeiyinyue.top/Article/details/gtutvvthqc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sxryk.cn/Article/details/gtlzpdigtk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ydzc1.top/Article/details/gtenjykzir.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmzedapm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gtzlagueer.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shzxlz.cn/Article/details/gtvkatnhuv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hywenlv.cn/Article/details/gttuikclmv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtnwxwrkqx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gteufykzua.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtofgmyovq.html

O. 并发与异步
来源：http://dali.zhengqikj.top/Article/details/gtpyowdskn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtrnsqcajw.html

[O01] 启动一个线程
来源：http://dali.hfpthk.cn/Article/details/gtrndtmwfc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cucudq.cn/Article/details/gtsddwjuvz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.0kj1m.cn/Article/details/gtfavubdph.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258888.top/Article/details/gtcuexdioy.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gtkdxnxeaq.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhongyouzk.top/Article/details/gtuzsibsjo.html

Go:   go f()
来源：http://dali.vqdsnc.cn/Article/details/gtxiyqgbvt.html

Ruby: Thread.new { f }
来源：http://dali.xuetiantiany.cn/Article/details/gtetfozflr.html

C#:   Task.Run(() => F());
来源：http://dali.yonumen.top/Article/details/gtblftyuzx.html

[O02] 使用线程池
来源：http://dali.c1oappe.top/Article/details/gtclfdblus.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.smart0.xyz/Article/details/gtfrfgfasx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xylfe.cn/Article/details/gtzsmiobdw.html

JS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gtvnojjzht.html

TS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gtkgjlqycf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhoulong.xyz/Article/details/gtnlbliwmu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.birdmap.top/Article/details/gtvthzcgqn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jyoumei.cn/Article/details/gtxruyzebk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.kuanghao11.cn/Article/details/gtcmtwjqmq.html

[O03] 加锁保护共享数据
来源：http://dali.cashguo.top/Article/details/gtrwuosymg.html

Py:   with lock: shared += 1
来源：http://dali.zhengqikj.top/Article/details/gtdikjkued.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xylfe.cn/Article/details/gtswbmuhfl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.meibo888.top/Article/details/gtkuywmvhl.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gtytacjodp.html

Java: synchronized (this) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gtafeqfjag.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jyoumei.cn/Article/details/gtdbcdetxf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shzxlz.cn/Article/details/gtvxyszmbu.html

C#:   lock (gate) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gtmctxrgae.html

[O04] 定义异步函数并等待
来源：http://dali.daria6918.cn/Article/details/gthduoobgs.html

Py:   async def f():⏎    await g()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtpklrma.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuxming.cn/Article/details/gthidqanok.html

JS:   async function f() { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gtrnbtotia.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.316326.xyz/Article/details/gtigaxwvkd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuanzhike.top/Article/details/gttrtebzvd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258.top/Article/details/gtedrshvsa.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.havefunace.top/Article/details/gttockdbvl.html

C#:   async Task F() { await G(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxtgazeg.html

[O05] 并发执行并等待全部完成
来源：http://dali.yongpay.top/Article/details/gtbfvdqsuz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedhkupyc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dianchejie.cn/Article/details/gttozbaqtw.html

JS:   await Promise.all(tasks)
来源：http://dali.sxryk.cn/Article/details/gtmffbypxi.html

TS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gtmovqsccd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gogol.net.cn/Article/details/gtsohmtxbc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zycfv.cn/Article/details/gtmsetomli.html

Ruby: threads.map(&:join)
来源：http://dali.guannengcc.top/Article/details/gtfnpzciqu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zdqjudy.top/Article/details/gtrerbutop.html

[O06] 使用进程池
来源：http://dali.daria6918.cn/Article/details/gtgyosztkh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cdnleiting.top/Article/details/gtmxrcvkos.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.kuanghao11.cn/Article/details/gtxycoazsw.html

JS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gttaultddn.html

TS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gtlevwavsu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.birdmap.top/Article/details/gtrqiozece.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.dianchejie.cn/Article/details/gtrlmclfrt.html

Ruby: // fork 块
来源：http://dali.yj20258888.top/Article/details/gtpusdphwq.html

C#:   Parallel.For
来源：http://dali.vqdsnc.cn/Article/details/gtdvpxrnuo.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtmgioffeg.html

P. 常用工具函数
来源：http://dali.jianghu66.top/Article/details/gtmxempqqj.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtqjkxcpyw.html

[P01] 生成 UUID
来源：http://dali.ehwqpu.com/Article/details/gtpcfzufvn.html

Py:   str(uuid.uuid4())
来源：http://dali.wangshuangyany.cn/Article/details/gtaqdghfgb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gogol.net.cn/Article/details/gtgxrgvkmx.html

JS:   crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gtvfolrqze.html

TS:   crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gthqavalzt.html

Java: UUID.randomUUID().toString()
来源：http://dali.fzhhl.top/Article/details/gtrdmogbue.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nanxuanxn.top/Article/details/gtcolyijqz.html

Ruby: SecureRandom.uuid
来源：http://dali.tianlin.xyz/Article/details/gtefffhvur.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hongshengwenyu.top/Article/details/gtowtxyzgs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.aibaodan.cn/Article/details/gtifvzsonr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.9152youxi.cn/Article/details/gtperbmwqp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tianlin.xyz/Article/details/gtfkkafiea.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlurkwdnf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shzxlz.cn/Article/details/gtgqsihpiq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yuxming.cn/Article/details/gtyblubyeh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.feifeiyinyue.top/Article/details/gtpahwefwf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.birdmap.top/Article/details/gtvjddhyss.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nwbrower.top/Article/details/gttmrmxgnr.html

[P03] 生成短随机字符串
来源：http://dali.hammf.cn/Article/details/gtdzathque.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gogol.net.cn/Article/details/gtbzaynadi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnqzz.top/Article/details/gtfovnhjvj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gtepotkzxe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjelqkllm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cucudq.cn/Article/details/gtkmmukmoa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj202588.top/Article/details/gtmcamsqmt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.svipenyu.cn/Article/details/gtyhoxcust.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.bjfxy.top/Article/details/gtpwsfbuhh.html

[P04] 求长度
来源：http://dali.fengsongda.top/Article/details/gtxxfbpybf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskzhtduh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtubqbprbc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gtyqqpgdda.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtmzlkmkki.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daria6918.cn/Article/details/gtvnghdztm.html

Go:   len(arr);  len(m)
来源：http://dali.zhixingplan.top/Article/details/gtevjbgdlf.html

Ruby: x.length;  x.size
来源：http://dali.yj20258.top/Article/details/gtnpgiwdtg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtcykjwmdt.html


<!-- 参考信息 -->