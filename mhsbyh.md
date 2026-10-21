代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gtxvdxzkln.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258.top/Article/details/gtqpescolq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtealeidzr.html

JS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gtytdqdvqh.html

TS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gtinnrbssr.html

Java: resp.statusCode()
来源：http://dali.dianchejie.cn/Article/details/gtapveohgw.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gtrdibtrug.html

Ruby: resp.code.to_i
来源：http://dali.nanxuanxn.top/Article/details/gthgavxuli.html

C#:   (int)resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gtnmahilbo.html

[L08] 并发请求多个地址
来源：http://dali.jinqigufen.top/Article/details/gtmuxbdhgx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.bjfxy.top/Article/details/gtrqqymayk.html

PHP:  curl_multi_init() 系列
来源：http://dali.hfpthk.cn/Article/details/gtndloujpi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtzfmdzjqq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtzcfkphcv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fengsongda.top/Article/details/gtflvdzkev.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258.top/Article/details/gthmprpwpf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tian-w.cn/Article/details/gthmkfbmpd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xziqi.cn/Article/details/gtqggmwhbg.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtybzgtpib.html

M. 命令行 / 进程 / 环境
来源：http://dali.jianghu66.top/Article/details/gtatiddyfl.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtynzblopb.html

[M01] 读取命令行参数
来源：http://dali.hysaishi.cn/Article/details/gtueyxkozx.html

Py:   sys.argv[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtudehwmwr.html

PHP:  $argv;  $argc;
来源：http://dali.hywenlv.cn/Article/details/gtlfvhuhtn.html

JS:   process.argv.slice(2)
来源：http://dali.hnxiangtu.top/Article/details/gtmadpdblg.html

TS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gtlofpxzvj.html

Java: args 数组（main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtnridrevy.html

Go:   os.Args[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtpuktmxwe.html

Ruby: ARGV
来源：http://dali.cdnleiting.top/Article/details/gtocmvyqqv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gtjttsvkxy.html

[M02] 读取环境变量
来源：http://dali.nwbrower.top/Article/details/gtgnqkcfdd.html

Py:   os.environ.get("HOME")
来源：http://dali.gzhubu.top/Article/details/gtiahkvhuv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cheryme.top/Article/details/gtqkxcyatu.html

JS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gtoawcvrkg.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtwwtjdgvb.html

Java: System.getenv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtzwpsnshk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cucudq.cn/Article/details/gtyenjzoxw.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigfzy.top/Article/details/gtmgzbtnoa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yueranfly.top/Article/details/gtgfhizrry.html

[M03] 执行外部命令
来源：http://dali.c1oappe.top/Article/details/gtckkujhpj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ppjwa.cn/Article/details/gtciwjpalg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.wangdashe.top/Article/details/gtgnhqdccx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gthqrroeif.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gtlfznxawm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ydzc1.top/Article/details/gtquqcmuqp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.bjfxy.top/Article/details/gtzswttwsm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cashguo.top/Article/details/gtvxcufplh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yvedp.cn/Article/details/gtvzpasfla.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gtiykubodc.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gtrwpykwsw.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gtnuxouyro.html

JS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gtnwabiwjw.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gtggrjunqw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.0kj1m.cn/Article/details/gtwcrbywzp.html

Go:   os.Getwd()
来源：http://dali.yvedp.cn/Article/details/gtadnjjrrw.html

Ruby: Dir.pwd
来源：http://dali.jinqigufen.top/Article/details/gtdxgfbawe.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuanzx.com/Article/details/gtfscfgkby.html

[M05] 设置退出码
来源：http://dali.xinyue.icu/Article/details/gtwydymfyd.html

Py:   sys.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtbhwitjuw.html

PHP:  exit(1);
来源：http://dali.mhx1999.top/Article/details/gtnwlzahbd.html

JS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtaieeswnl.html

TS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gtgcksblgf.html

Java: System.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtpbjtpkxo.html

Go:   os.Exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gterikbmui.html

Ruby: exit 1
来源：http://dali.jiagoushi.top/Article/details/gtciyhzivb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuetiantiany.cn/Article/details/gtqqjdzjfo.html

[M06] 向标准错误输出
来源：http://dali.wangdashe.top/Article/details/gtispsqkdk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.quarkkingdee.top/Article/details/gtlgrdjhig.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.c1oappe.top/Article/details/gtrjdvezcx.html

JS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gtsyhtcrhv.html

TS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtkhpecozc.html

Java: System.err.println("err")
来源：http://dali.meibo888.top/Article/details/gtbyvuweuy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shzxlz.cn/Article/details/gtoimkrfuz.html

Ruby: warn "err"
来源：http://dali.shangyingyoupin.top/Article/details/gtnzccqocm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.9152youxi.cn/Article/details/gtfvxtfnje.html

[M07] 判断是否为主入口
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmuhqtflk.html

Py:   if __name__ == "__main__":
来源：http://dali.sysykeji.top/Article/details/gtafdvqhwa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhixingplan.top/Article/details/gtxdeguksa.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gtmvslknql.html

TS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gtypxwyuto.html

Java: public static void main(String[] args)
来源：http://dali.dianchejie.cn/Article/details/gtlimcngfn.html

Go:   func main()
来源：http://dali.sufxvd.cn/Article/details/gtrigdoxww.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.quarkkingdee.top/Article/details/gtyqirsqiy.html

C#:   static void Main(string[] args)
来源：http://dali.xziqi.cn/Article/details/gthohruabt.html

[M08] 获取系统与运行时信息
来源：http://dali.sweek.top/Article/details/gtmnijjmrn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrsqteiq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cheryme.top/Article/details/gtabuvqkkb.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdircpqbp.html

TS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gtcdugdhud.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozmwcsdf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenjidiqi.icu/Article/details/gtloiusxvd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenjidiqi.icu/Article/details/gtflzndkeg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhongyouzk.top/Article/details/gtqnrkyrhs.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtgghxwoof.html

N. 数据结构与算法
来源：http://dali.xziqi.cn/Article/details/gtadenqgbf.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzdigpax.html

[N01] 二分查找（有序数组）
来源：http://dali.ppjwa.cn/Article/details/gtotcmaomh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtdcmycpgl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuxming.cn/Article/details/gtdvobpxen.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gtkannurue.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gtfqthjuxm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtzwejcrhp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtzzxcljss.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yongpay.top/Article/details/gtwefwcyob.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.meibo888.top/Article/details/gtshaxvwzj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hammf.cn/Article/details/gtmqztnlmz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gtkxwtrmts.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuxming.cn/Article/details/gtaecrcdqi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gtvxnudcpi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gtmtuemoea.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.quarkkingdee.top/Article/details/gtzgiwigdm.html

Go:   slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gtabslsczw.html

Ruby: arr.sort
来源：http://dali.yuxming.cn/Article/details/gtywcjqybm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258888.top/Article/details/gtxmehbatf.html

[N03] 快速排序（分治示例）
来源：http://dali.jqgfzy.top/Article/details/gtkhgsnypp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tanke756.top/Article/details/gtrikqgkxt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuanzx.com/Article/details/gtgowwenwj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gtjxwokomg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gtpjqdixqw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuetiantiany.cn/Article/details/gtlxyaoijk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenjidiqi.icu/Article/details/gtgedoumve.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhiwuduotai.top/Article/details/gtfgctyqee.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hammf.cn/Article/details/gtxculxcug.html

[N04] 斐波那契数列
来源：http://dali.xziqi.cn/Article/details/gtezxoexbn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gtsrhocpsq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gtxupjeaxh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtcngkrqyg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtqpkvkhbn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daxiang520.top/Article/details/gtvrpmdvdz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yueranfly.top/Article/details/gtfbyqzdmc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gtvkceflvh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gtrwfuxouu.html

[N05] 最大公约数
来源：http://dali.hnqzz.top/Article/details/gtdrrwrenw.html

Py:   math.gcd(a, b)
来源：http://dali.xziqi.cn/Article/details/gtrenoybdc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jianghu66.top/Article/details/gtysxuzyib.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fzhhl.top/Article/details/gtqmxazdiv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigufen.top/Article/details/gtqlphejjc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangdashe.top/Article/details/gtynqhrnvs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakymmwut.html

Ruby: a.gcd(b)
来源：http://dali.zhengqikj.top/Article/details/gtrjyeueee.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhoulong.xyz/Article/details/gtiixdnvmv.html

[N06] 判断回文字符串
来源：http://dali.yj202588.top/Article/details/gtngpaxwmu.html

Py:   s == s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gtfebleizj.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdahuhda.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtbwpkbsij.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtmtmsjxrv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzffygbh.html

Go:   // 双指针从两端比较
来源：http://dali.yj20258.top/Article/details/gtokotwuth.html

Ruby: s == s.reverse
来源：http://dali.sweek.top/Article/details/gtvexsqknl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gtyqkofsjp.html

[N07] 两数之和（返回下标）
来源：http://dali.shuidangran.top/Article/details/gtvuwtazmo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xylfe.cn/Article/details/gtthqlderw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258.top/Article/details/gtdxzihogr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cheryme.top/Article/details/gtaqwivcpe.html

TS:   // 手写 Map<string, number>
来源：http://dali.iojbl.cn/Article/details/gtnubuerap.html

Java: // 手写 HashMap
来源：http://dali.cucudq.cn/Article/details/gtihipcakk.html

Go:   // 手写 map[int]int
来源：http://dali.havefunace.top/Article/details/gtzquvnxzn.html

Ruby: // 手写 Hash
来源：http://dali.yvedp.cn/Article/details/gtvtewkzvy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikirfpgb.html

[N08] 生成全排列
来源：http://dali.zhixingplan.top/Article/details/gtjfigfugy.html

Py:   itertools.permutations(arr)
来源：http://dali.yj202588.top/Article/details/gtzpvdyxpl.html

PHP:  // 手写递归交换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxkbebey.html

JS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtwzwytrkt.html

TS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtdnirvbum.html

Java: // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtcrgqpbhp.html

Go:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtsofzocem.html

Ruby: arr.permutation.to_a
来源：http://dali.zycfv.cn/Article/details/gtzzdkznbm.html

C#:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtbdkqmgcd.html

[N09] 栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gtkoyugixa.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ybcxt.top/Article/details/gtfomihxra.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtiobpzjwo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tanke756.top/Article/details/gtsuzfjnpb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cqqwz.cn/Article/details/gtrjbfmirl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gthcmslcmu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangshuangyany.cn/Article/details/gtjeyvgvao.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gttdxtlwok.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ppjwa.cn/Article/details/gtfqgiiyqc.html

[N10] 链表节点定义
来源：http://dali.jianghu66.top/Article/details/gtvprhaphc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.meibo888.top/Article/details/gtskfofdhr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.snrcjt.cn/Article/details/gtkymojvqv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shangyingyoupin.top/Article/details/gtoestwdwu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhiwuduotai.top/Article/details/gtgqvtvmql.html

Java: class Node { int v; Node next; }
来源：http://dali.jyoumei.cn/Article/details/gtyaoryqxj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigfzy.top/Article/details/gtoecfyscv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.birdmap.top/Article/details/gtrpzlxbvs.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aibaodan.cn/Article/details/gtuieqpzlr.html

[N11] 二叉树中序遍历
来源：http://dali.zdqjudy.top/Article/details/gtpinpwodn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxicjybve.html

PHP:  // 手写递归函数
来源：http://dali.nanxinkj.top/Article/details/gtpkbxgzak.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gtavgvlmhe.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gtuemwpxex.html

Java: // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gtoythbdmo.html

Go:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gtbvybkhub.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.smart0.xyz/Article/details/gtxuqlfrpf.html

C#:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpsdzmtqz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hammf.cn/Article/details/gtbkvftvtq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nwbrower.top/Article/details/gttbnbyqsx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.haohaochexian.top/Article/details/gthoqurvfo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfxuiwng.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yvedp.cn/Article/details/gtcnsgnxyd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gtfbzdrvbb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sxryk.cn/Article/details/gtumkeppvz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpjwrfby.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gtoikpveuw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtkzptwzkx.html

O. 并发与异步
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukyodemx.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtszkqgjbk.html

[O01] 启动一个线程
来源：http://dali.tanke756.top/Article/details/gtwryktbnk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sufxvd.cn/Article/details/gtpapmniuc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jiagoushi.top/Article/details/gthygsobfh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuetiantiany.cn/Article/details/gtntrcvxxc.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gtsldyizgz.html

Java: new Thread(() -> f()).start()
来源：http://dali.cheryme.top/Article/details/gtgxmtxiqr.html

Go:   go f()
来源：http://dali.tian-w.cn/Article/details/gtmwzfqlny.html

Ruby: Thread.new { f }
来源：http://dali.birdmap.top/Article/details/gticbbnlvw.html

C#:   Task.Run(() => F());
来源：http://dali.fzhhl.top/Article/details/gtbdjohrde.html

[O02] 使用线程池
来源：http://dali.9152youxi.cn/Article/details/gtgfsbzmdo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.andypj.xyz/Article/details/gtscylepfh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjyimudxw.html

JS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gtxbsebrqw.html

TS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gtfqzbhlot.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jianghu66.top/Article/details/gtwulchyjc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenzaomai.com/Article/details/gtaycieyse.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cdnleiting.top/Article/details/gtetgnihrq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.bjfxy.top/Article/details/gtdnwshvle.html

[O03] 加锁保护共享数据
来源：http://dali.andypj.xyz/Article/details/gtzlvqhvsu.html

Py:   with lock: shared += 1
来源：http://dali.daria6918.cn/Article/details/gtubraumuw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guowangkeji.top/Article/details/gtfauyuexj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.aibaodan.cn/Article/details/gtaudvbjmi.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gtwpgbgrvj.html

Java: synchronized (this) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gtfoumhgqp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhixingplan.top/Article/details/gtkjirdspa.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gtywgvarmt.html

C#:   lock (gate) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gthksczhsf.html

[O04] 定义异步函数并等待
来源：http://dali.ivvv.top/Article/details/gtedqzyylk.html

Py:   async def f():⏎    await g()
来源：http://dali.yj202588.top/Article/details/gtxlffthzl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.fengsongda.top/Article/details/gticepglpg.html

JS:   async function f() { await g(); }
来源：http://dali.yongpay.top/Article/details/gtzubklqlx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.iojbl.cn/Article/details/gtyofodsqe.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenjidiqi.icu/Article/details/gtytjmyxdx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jianghu66.top/Article/details/gtjfuzqrtg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigfzy.top/Article/details/gtahqbraas.html

C#:   async Task F() { await G(); }
来源：http://dali.guannengcc.top/Article/details/gtajimrrsb.html

[O05] 并发执行并等待全部完成
来源：http://dali.yvedp.cn/Article/details/gtavlynzrh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.fzhhl.top/Article/details/gtenmloftj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaltgwoyu.html

JS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gtspiljmkz.html

TS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gtoveqkjfq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhiwuduotai.top/Article/details/gtotuqnohb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.kuanghao11.cn/Article/details/gtaxyhpcje.html

Ruby: threads.map(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbajagaqw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangdashe.top/Article/details/gtqehoerlb.html

[O06] 使用进程池
来源：http://dali.hnqzz.top/Article/details/gtsofqvjtj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ppjwa.cn/Article/details/gtyzdrpyfv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.kuanghao11.cn/Article/details/gtratigyxu.html

JS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqztpyoaw.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdkobden.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daria6918.cn/Article/details/gtuigtrsnf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangdashe.top/Article/details/gtkjllubkm.html

Ruby: // fork 块
来源：http://dali.xylfe.cn/Article/details/gtcfefbnea.html

C#:   Parallel.For
来源：http://dali.havefunace.top/Article/details/gtccdyiguu.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtlcvjwlel.html

P. 常用工具函数
来源：http://dali.sufxvd.cn/Article/details/gtkvadhwer.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtchjyuuxz.html

[P01] 生成 UUID
来源：http://dali.guowangkeji.top/Article/details/gtdxhiasax.html

Py:   str(uuid.uuid4())
来源：http://dali.xuetiantiany.cn/Article/details/gtjwxefjeb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.dianchejie.cn/Article/details/gtwsruvkfa.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gteggdxqxx.html

TS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtedbhqmzz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zycfv.cn/Article/details/gtbcwglhsf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtfwxhqaim.html

Ruby: SecureRandom.uuid
来源：http://dali.tanke756.top/Article/details/gtkulllbji.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dashuyun.cn/Article/details/gtgcbirbru.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxppodyd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cucudq.cn/Article/details/gtbyhzqlsm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypgaxghc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvaznexj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pengpengdd.cyou/Article/details/gtxctpsjkr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258888.top/Article/details/gtjzhvcebr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sufxvd.cn/Article/details/gtbkeslyle.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.bjfxy.top/Article/details/gtxqyrnrun.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppzcnuxy.html

[P03] 生成短随机字符串
来源：http://dali.c1oappe.top/Article/details/gtaemfjhuc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zdqjudy.top/Article/details/gtngpepnvh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sweek.top/Article/details/gtyxrzbukp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gtvsexbtwp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhengqikj.top/Article/details/gtijxzttkv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.svipenyu.cn/Article/details/gtrxxgrhra.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.wangshuangyany.cn/Article/details/gtaepfafko.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hammf.cn/Article/details/gtiamfrzay.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aibaodan.cn/Article/details/gtwbuouokf.html

[P04] 求长度
来源：http://dali.gogol.net.cn/Article/details/gtnoyircjb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqmudaey.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtjadgoaqr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.svipenyu.cn/Article/details/gtklxtplqp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gtvuuyctqg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zdqjudy.top/Article/details/gtiakjrfpe.html

Go:   len(arr);  len(m)
来源：http://dali.jianghu66.top/Article/details/gtkcbkouib.html

Ruby: x.length;  x.size
来源：http://dali.hfpthk.cn/Article/details/gtemjdwldc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gtwbtjvijn.html


<!-- 参考信息 -->