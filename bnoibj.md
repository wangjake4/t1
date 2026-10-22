代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.ybcxt.top/Article/details/gtmvrnesmy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhongyouzk.top/Article/details/gthqbbbamz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daria6918.cn/Article/details/gtrszvkgia.html

JS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gtgbtuniep.html

TS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gthtzeqesa.html

Java: resp.statusCode()
来源：http://dali.aibaodan.cn/Article/details/gtdoqjfedn.html

Go:   resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gtfelhnqjp.html

Ruby: resp.code.to_i
来源：http://dali.zhoulong.xyz/Article/details/gthkhqdbzi.html

C#:   (int)resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtincpugdi.html

[L08] 并发请求多个地址
来源：http://dali.aizwys.cn/Article/details/gtiwbwqara.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhengqikj.top/Article/details/gtctuajhxc.html

PHP:  curl_multi_init() 系列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzlrrulr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtmcfxnzro.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gtgxhlltgm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.havefunace.top/Article/details/gtdhcsvruw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzudqhfb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gteuxzxfmj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.havefunace.top/Article/details/gtmwxnewps.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtmrtefxax.html

M. 命令行 / 进程 / 环境
来源：http://dali.svipenyu.cn/Article/details/gtyerwtfwg.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gttohrmyxb.html

[M01] 读取命令行参数
来源：http://dali.jqgfzy.top/Article/details/gtykpdchkv.html

Py:   sys.argv[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtuazoqilm.html

PHP:  $argv;  $argc;
来源：http://dali.quarkkingdee.top/Article/details/gtuuehtnsg.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtkuhvxhnp.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtnemjbqpr.html

Java: args 数组（main 方法参数）
来源：http://dali.cashguo.top/Article/details/gtixcxregk.html

Go:   os.Args[1:]
来源：http://dali.sxryk.cn/Article/details/gtdxupbgyi.html

Ruby: ARGV
来源：http://dali.hnqzz.top/Article/details/gtgzluglvy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gtyxfbqqjg.html

[M02] 读取环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gtmawsxstr.html

Py:   os.environ.get("HOME")
来源：http://dali.yongpay.top/Article/details/gtypwyyepc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sweek.top/Article/details/gtlqmygwsl.html

JS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gtkxtoinrg.html

TS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmilujhc.html

Java: System.getenv("HOME")
来源：http://dali.yj202588.top/Article/details/gtubfphxnb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.andypj.xyz/Article/details/gttnunvjwq.html

Ruby: ENV["HOME"]
来源：http://dali.zycfv.cn/Article/details/gtncqcnrlo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtygvryato.html

[M03] 执行外部命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgemdyskp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shuidangran.top/Article/details/gtwfyeevve.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuxming.cn/Article/details/gtiqivijwd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gtqrwbzabz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gthtmlqifs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yangfankeji.com/Article/details/gtvodqywmo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sxryk.cn/Article/details/gtktkvblam.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hammf.cn/Article/details/gtbhgewyyc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aizwys.cn/Article/details/gtrlboiphh.html

[M04] 获取当前工作目录
来源：http://dali.hammf.cn/Article/details/gtzrdbufjb.html

Py:   os.getcwd()
来源：http://dali.jqgfzy.top/Article/details/gtgbnlzwtf.html

PHP:  getcwd();
来源：http://dali.smart0.xyz/Article/details/gtlbqkjzgu.html

JS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gtrvcgyzpz.html

TS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gtxhwtmgdr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tianlin.xyz/Article/details/gtcyzrvezc.html

Go:   os.Getwd()
来源：http://dali.xylfe.cn/Article/details/gtgrdpuszb.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gtiuvcsaqn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.meibo888.top/Article/details/gtnkmcvmdt.html

[M05] 设置退出码
来源：http://dali.hnqzz.top/Article/details/gtwapseqxd.html

Py:   sys.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtruarraql.html

PHP:  exit(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtneixivqk.html

JS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtxhehkmsk.html

TS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gtrvlxvttn.html

Java: System.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpiyiehx.html

Go:   os.Exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtclhdphst.html

Ruby: exit 1
来源：http://dali.hfpthk.cn/Article/details/gtwtyzrmuf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gogol.net.cn/Article/details/gtunguzbla.html

[M06] 向标准错误输出
来源：http://dali.jqgfzy.top/Article/details/gtxsnpgkxn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xziqi.cn/Article/details/gtigvbcvju.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nwbrower.top/Article/details/gtweqygrei.html

JS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtmdiguwxm.html

TS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gtoklruqtm.html

Java: System.err.println("err")
来源：http://dali.zycfv.cn/Article/details/gtimtfkhzp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenlongwang.top/Article/details/gtfdcrwowo.html

Ruby: warn "err"
来源：http://dali.wangdashe.top/Article/details/gtizkqrbbe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dianchejie.cn/Article/details/gtpmchtraz.html

[M07] 判断是否为主入口
来源：http://dali.chenjidiqi.icu/Article/details/gtbjrwhcdp.html

Py:   if __name__ == "__main__":
来源：http://dali.dianchejie.cn/Article/details/gtxnytlajc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.kuanghao11.cn/Article/details/gtlzeuwldc.html

JS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gtejfcheie.html

TS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gtsjshwhlg.html

Java: public static void main(String[] args)
来源：http://dali.pycfn.com/Article/details/gtfzvsofby.html

Go:   func main()
来源：http://dali.yj202588.top/Article/details/gtyodvdela.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhoulong.xyz/Article/details/gtswevogju.html

C#:   static void Main(string[] args)
来源：http://dali.jqgfzy.top/Article/details/gtxnuzznnu.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgfzy.top/Article/details/gtmssqvdfl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuanzhike.top/Article/details/gtxywqzgsu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenlongwang.top/Article/details/gtofemehwp.html

JS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gtshxphtvi.html

TS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gtyiljyeuz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258.top/Article/details/gtdfacafys.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yanxiufei.cn/Article/details/gtveernzae.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgfzy.top/Article/details/gtvkrocjho.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ybcxt.top/Article/details/gtgoqmojrw.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtbjldwdsc.html

N. 数据结构与算法
来源：http://dali.yuxming.cn/Article/details/gtlvfdzzir.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtchwudyhb.html

[N01] 二分查找（有序数组）
来源：http://dali.wangshuangyany.cn/Article/details/gtyidgqjly.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqqshpgc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj202588.top/Article/details/gtgvyyomll.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtytzmeuij.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtjmcsydik.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtgnogjguo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtxoyjarpf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxuanxn.top/Article/details/gtxsmiftuu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gtqrxggyuq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cucudq.cn/Article/details/gtbcscdhru.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gthpfbxadw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gttueqwdxl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gtxttzabzy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtivrsudqd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhiwuduotai.top/Article/details/gtgbgqtlfq.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gtbphdohad.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gtjtlmedfq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangdashe.top/Article/details/gtwzijuhnx.html

[N03] 快速排序（分治示例）
来源：http://dali.xinyue.icu/Article/details/gtfuxyojmp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pycfn.com/Article/details/gtuqbcsled.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aizwys.cn/Article/details/gthjrykzuw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gtiljoaczp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gtxrpsavwo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.smart0.xyz/Article/details/gtiqpjucsq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigufen.top/Article/details/gtodijsbje.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daria6918.cn/Article/details/gtrybaifyr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yanxiufei.cn/Article/details/gtivotrqwb.html

[N04] 斐波那契数列
来源：http://dali.cucudq.cn/Article/details/gtaepakwfm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gtiwlzsklk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nwbrower.top/Article/details/gtifuqdndl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtxbzemhcn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtdaeeaitz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gtvdwdcsjp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.kuanghao11.cn/Article/details/gtkvjrmwom.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gtsntxlrng.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtdkjozdqo.html

[N05] 最大公约数
来源：http://dali.cqqwz.cn/Article/details/gtghlacopk.html

Py:   math.gcd(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtralhpeaa.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyyncnpul.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gtvpwfntdq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gtfykvvues.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cheryme.top/Article/details/gtixylemuq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmmfhnrp.html

Ruby: a.gcd(b)
来源：http://dali.zhoulong.xyz/Article/details/gtqsdsvvqb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gtacafzsbh.html

[N06] 判断回文字符串
来源：http://dali.nwbrower.top/Article/details/gtwvyfuzhy.html

Py:   s == s[::-1]
来源：http://dali.iojbl.cn/Article/details/gtpouxxmxu.html

PHP:  $s === strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gtwrxixkdu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtbfutnpba.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtduhmimoo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.andypj.xyz/Article/details/gtfrlfilka.html

Go:   // 双指针从两端比较
来源：http://dali.yj20258.top/Article/details/gtfjzjcgka.html

Ruby: s == s.reverse
来源：http://dali.havefunace.top/Article/details/gtfzrnksnp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtrsgojtnb.html

[N07] 两数之和（返回下标）
来源：http://dali.gzhubu.top/Article/details/gtrznffhnz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gotoacloud.top/Article/details/gtissqzuzi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hywenlv.cn/Article/details/gtubtxcgvl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xinyue.icu/Article/details/gtritnshav.html

TS:   // 手写 Map<string, number>
来源：http://dali.quarkkingdee.top/Article/details/gthdphyury.html

Java: // 手写 HashMap
来源：http://dali.0kj1m.cn/Article/details/gtkkwknggf.html

Go:   // 手写 map[int]int
来源：http://dali.zhoulong.xyz/Article/details/gtjoegtbfh.html

Ruby: // 手写 Hash
来源：http://dali.zhoulong.xyz/Article/details/gtpflfxjcn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.vqdsnc.cn/Article/details/gtuuchjqim.html

[N08] 生成全排列
来源：http://dali.quarkkingdee.top/Article/details/gtcjhudogu.html

Py:   itertools.permutations(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttimyjhwg.html

PHP:  // 手写递归交换
来源：http://dali.zhixingplan.top/Article/details/gtylqumqjm.html

JS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtatdqxceg.html

TS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtsvcwhllb.html

Java: // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtbtxkqvnw.html

Go:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtbofhzutw.html

Ruby: arr.permutation.to_a
来源：http://dali.316326.xyz/Article/details/gtqczappha.html

C#:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtnlqvwvnq.html

[N09] 栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gtxjontjon.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gotoacloud.top/Article/details/gtbjosuquz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.havefunace.top/Article/details/gtpiomznuf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gtrvhnhxhk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigfzy.top/Article/details/gtwldbpofc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aibaodan.cn/Article/details/gtrdsmmihu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.vqdsnc.cn/Article/details/gtvvglafvj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtxvrtqptd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gtyrvplpnt.html

[N10] 链表节点定义
来源：http://dali.9152youxi.cn/Article/details/gtocbywbur.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shangyingyoupin.top/Article/details/gtbconuqhl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ybcxt.top/Article/details/gtoyuvgqls.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hfpthk.cn/Article/details/gtexdbtbrk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shzxlz.cn/Article/details/gtkscyspfm.html

Java: class Node { int v; Node next; }
来源：http://dali.chenzaomai.com/Article/details/gtmfxkfieu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gotoacloud.top/Article/details/gtiztltdir.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nwbrower.top/Article/details/gtebqoxtri.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.redwolf501.top/Article/details/gtqaofgvre.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigufen.top/Article/details/gtahbxndux.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jqgufenzy.top/Article/details/gtndheipnl.html

PHP:  // 手写递归函数
来源：http://dali.yongpay.top/Article/details/gtmcnhvgjq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sysykeji.top/Article/details/gtmeukubak.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gtofuoishz.html

Java: // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtzfgtaorv.html

Go:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtysansdgy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.snrcjt.cn/Article/details/gtjzxjrnvz.html

C#:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtizprrygl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ivvv.top/Article/details/gthgxcfpje.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwxfefae.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhongyouzk.top/Article/details/gtdpzvhoys.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gtlvkhmgrj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gtggeojmgx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gtuuxvhbcb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxinkj.top/Article/details/gtvmyyilln.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhixingplan.top/Article/details/gtrlskkgqt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ydzc1.top/Article/details/gtcyymxavx.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gthirbhqgw.html

O. 并发与异步
来源：http://dali.guowangkeji.top/Article/details/gtxtctmqmp.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtrqgapnwp.html

[O01] 启动一个线程
来源：http://dali.smart0.xyz/Article/details/gtjjqghfpr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiprixdoj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtgygktocr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.smart0.xyz/Article/details/gtzphpbgce.html

TS:   // 同 JS
来源：http://dali.316326.xyz/Article/details/gtxioulggu.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgfzy.top/Article/details/gtxzistiym.html

Go:   go f()
来源：http://dali.mhx1999.top/Article/details/gtdtuyihqg.html

Ruby: Thread.new { f }
来源：http://dali.yj20258888.top/Article/details/gthudjbkym.html

C#:   Task.Run(() => F());
来源：http://dali.quarkkingdee.top/Article/details/gtwroocism.html

[O02] 使用线程池
来源：http://dali.daxiang520.top/Article/details/gtxjoozdbf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzskijpm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gaohongyu789.top/Article/details/gtuqaisoee.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gtormadmid.html

TS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gtlybkzhtc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daxiang520.top/Article/details/gtodutgngw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuanzhike.top/Article/details/gtptcyzjvx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.haohaochexian.top/Article/details/gtunsdjfhe.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnxiangtu.top/Article/details/gtaqdinyhn.html

[O03] 加锁保护共享数据
来源：http://dali.gzhubu.top/Article/details/gtxchwqtsm.html

Py:   with lock: shared += 1
来源：http://dali.guannengcc.top/Article/details/gtjfibvsso.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.dashuyun.cn/Article/details/gtychhxaqs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.snrcjt.cn/Article/details/gtslwjfqxs.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gtzmmfqrie.html

Java: synchronized (this) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gtksyaxwbw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fengsongda.top/Article/details/gtjgojvvwz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.aizwys.cn/Article/details/gtymewveet.html

C#:   lock (gate) { shared++; }
来源：http://dali.316326.xyz/Article/details/gtrzimaxsf.html

[O04] 定义异步函数并等待
来源：http://dali.mhx1999.top/Article/details/gtfaqzqolf.html

Py:   async def f():⏎    await g()
来源：http://dali.tian-w.cn/Article/details/gtcpkchdpt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenjidiqi.icu/Article/details/gtdmwctwpl.html

JS:   async function f() { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gthlwexlgh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yueranfly.top/Article/details/gtgqshxcxu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.havefunace.top/Article/details/gtdpomkoot.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sufxvd.cn/Article/details/gtnfojohma.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cucudq.cn/Article/details/gtvzdhogte.html

C#:   async Task F() { await G(); }
来源：http://dali.gaohongyu789.top/Article/details/gtjhghrnid.html

[O05] 并发执行并等待全部完成
来源：http://dali.dianchejie.cn/Article/details/gtagjqaeeq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xinyue.icu/Article/details/gtqsycrgnh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxinkj.top/Article/details/gtfbywwupc.html

JS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gtduyzunfs.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gtritngonj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sysykeji.top/Article/details/gtjkowqqpy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fengsongda.top/Article/details/gtiwisgmql.html

Ruby: threads.map(&:join)
来源：http://dali.smart0.xyz/Article/details/gtrwswxhex.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tanke756.top/Article/details/gtdkbqznwf.html

[O06] 使用进程池
来源：http://dali.guannengcc.top/Article/details/gtssvzmxiz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gogol.net.cn/Article/details/gtknqoilgs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.redwolf501.top/Article/details/gtxeblvmne.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhwgosph.html

TS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gtswglzklu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gzhubu.top/Article/details/gtingntiuy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.feifeiyinyue.top/Article/details/gtyswcrppf.html

Ruby: // fork 块
来源：http://dali.vqdsnc.cn/Article/details/gtfxwjkqts.html

C#:   Parallel.For
来源：http://dali.hnxiangtu.top/Article/details/gtpbzmoqmb.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtmvrskirj.html

P. 常用工具函数
来源：http://dali.cheryme.top/Article/details/gtiljbbedr.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtyznexhle.html

[P01] 生成 UUID
来源：http://dali.316326.xyz/Article/details/gtcqekodhg.html

Py:   str(uuid.uuid4())
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrhbebda.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtlwxeylwj.html

JS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gtadvudwci.html

TS:   crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gtyglfxjws.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklabeamu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tianlin.xyz/Article/details/gtozhlpyek.html

Ruby: SecureRandom.uuid
来源：http://dali.c1oappe.top/Article/details/gtonkkjtdg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.meibo888.top/Article/details/gtfixxbvbz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xylfe.cn/Article/details/gtqsvoiiaj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmakuwfbl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tianlin.xyz/Article/details/gtbnhgoltp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.kuanghao11.cn/Article/details/gtksiqlxbl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.bjfxy.top/Article/details/gtwkbbxhou.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.andypj.xyz/Article/details/gtgpcovexo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yueranfly.top/Article/details/gtopnczggh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.vqdsnc.cn/Article/details/gtitpzdpys.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pycfn.com/Article/details/gtlphdaobu.html

[P03] 生成短随机字符串
来源：http://dali.hysaishi.cn/Article/details/gtsnoceoup.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yanxiufei.cn/Article/details/gtsgzrqbsq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.kuanghao11.cn/Article/details/gthilnzluk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tian-w.cn/Article/details/gtmierwomr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gogol.net.cn/Article/details/gtosksvygt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zdqjudy.top/Article/details/gtjhlincpe.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shuidangran.top/Article/details/gtrbtxszsv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yueranfly.top/Article/details/gtumhihthw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnxiangtu.top/Article/details/gtrkfitbpk.html

[P04] 求长度
来源：http://dali.yvedp.cn/Article/details/gtjswxzgxv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yueranfly.top/Article/details/gtrfxudbgs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtzenrdiwt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gtntczgynp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gtqiqjprge.html

Java: list.size();  map.size();  s.length()
来源：http://dali.316326.xyz/Article/details/gtykdyrizv.html

Go:   len(arr);  len(m)
来源：http://dali.daxiang520.top/Article/details/gtewtxibmn.html

Ruby: x.length;  x.size
来源：http://dali.kuanghao11.cn/Article/details/gtassqvcys.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gtllpmdutl.html


<!-- 参考信息 -->