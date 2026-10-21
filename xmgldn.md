代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gtbrdmchgx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj202588.top/Article/details/gtnkrqedua.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jlsjyb.cn/Article/details/gtqergfadl.html

JS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gtrozqkakf.html

TS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gttcyomekh.html

Java: resp.statusCode()
来源：http://dali.ppjwa.cn/Article/details/gtdhsfwahz.html

Go:   resp.StatusCode
来源：http://dali.zhiwuduotai.top/Article/details/gtwzqpqrat.html

Ruby: resp.code.to_i
来源：http://dali.hammf.cn/Article/details/gtmmmtczjb.html

C#:   (int)resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gtvsjzpoje.html

[L08] 并发请求多个地址
来源：http://dali.yongpay.top/Article/details/gtkwzsxjzm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258.top/Article/details/gtmwmzthqh.html

PHP:  curl_multi_init() 系列
来源：http://dali.andypj.xyz/Article/details/gttapwfedw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtmqozzskf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gteqcjawuk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guowangkeji.top/Article/details/gttsfxsrek.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenlongwang.top/Article/details/gtwuizgutc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ppjwa.cn/Article/details/gtbszlwpvc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtqocoglbo.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtqumxkomz.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuanzx.com/Article/details/gtlfbqruve.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtuycpsoaa.html

[M01] 读取命令行参数
来源：http://dali.chenzaomai.com/Article/details/gtpdxweuls.html

Py:   sys.argv[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhgvrksw.html

PHP:  $argv;  $argc;
来源：http://dali.nanxinkj.top/Article/details/gtqeywzzvc.html

JS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtqheeuiid.html

TS:   process.argv.slice(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfedgaxma.html

Java: args 数组（main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gtpkzjbxnh.html

Go:   os.Args[1:]
来源：http://dali.ppjwa.cn/Article/details/gtmmhldire.html

Ruby: ARGV
来源：http://dali.aibaodan.cn/Article/details/gtlddbfbmg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gtvmpxvyrc.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpwtjwuy.html

Py:   os.environ.get("HOME")
来源：http://dali.316326.xyz/Article/details/gtvxzxahpa.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gtidrdcwpa.html

JS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtpmxnjipo.html

TS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gtfvatufiu.html

Java: System.getenv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtrilrmmau.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwzwhwqj.html

Ruby: ENV["HOME"]
来源：http://dali.ybcxt.top/Article/details/gtriwnllik.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sxryk.cn/Article/details/gtrtxngmjs.html

[M03] 执行外部命令
来源：http://dali.hywenlv.cn/Article/details/gtiyatezfb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsdggtfn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhixingplan.top/Article/details/gtizskaxng.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtdqapqngp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gtgfbcvsrz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guowangkeji.top/Article/details/gthynufrvz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.birdmap.top/Article/details/gteipuknwr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yongpay.top/Article/details/gtyqzjvgtn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuanzhike.top/Article/details/gtxydjegyf.html

[M04] 获取当前工作目录
来源：http://dali.ivvv.top/Article/details/gtbisuxane.html

Py:   os.getcwd()
来源：http://dali.sufxvd.cn/Article/details/gtwrjrajrq.html

PHP:  getcwd();
来源：http://dali.dianchejie.cn/Article/details/gtvtjaommw.html

JS:   process.cwd()
来源：http://dali.yj20258888.top/Article/details/gtptblqluy.html

TS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtmyaghrkf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xziqi.cn/Article/details/gtlqenurot.html

Go:   os.Getwd()
来源：http://dali.tianlin.xyz/Article/details/gtctzauqws.html

Ruby: Dir.pwd
来源：http://dali.shangyingyoupin.top/Article/details/gtfiehazdo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daxiang520.top/Article/details/gtfgqgobur.html

[M05] 设置退出码
来源：http://dali.jyoumei.cn/Article/details/gtjacrzydb.html

Py:   sys.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtjdlefxqn.html

PHP:  exit(1);
来源：http://dali.jiagoushi.top/Article/details/gtidotullx.html

JS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtbsekaqvm.html

TS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtvxbmpico.html

Java: System.exit(1)
来源：http://dali.yj20258888.top/Article/details/gttcyodwcl.html

Go:   os.Exit(1)
来源：http://dali.daxiang520.top/Article/details/gtmsoovkdv.html

Ruby: exit 1
来源：http://dali.ybcxt.top/Article/details/gtqgggnzgr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zycfv.cn/Article/details/gtjnahahcx.html

[M06] 向标准错误输出
来源：http://dali.havefunace.top/Article/details/gtpugivwmf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gtmehdbwug.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangdashe.top/Article/details/gtnkazcrrx.html

JS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gtmxbqsmzz.html

TS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gtdmcwmpbg.html

Java: System.err.println("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtiyvmugap.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.smart0.xyz/Article/details/gthndetqta.html

Ruby: warn "err"
来源：http://dali.svipenyu.cn/Article/details/gtjoxvvjsx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gotoacloud.top/Article/details/gtzjuirrzd.html

[M07] 判断是否为主入口
来源：http://dali.fzhhl.top/Article/details/gtaavptols.html

Py:   if __name__ == "__main__":
来源：http://dali.hnxiangtu.top/Article/details/gtstyvlrwn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gtkckgcxhp.html

JS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtxwssmqzc.html

TS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtsculkfxb.html

Java: public static void main(String[] args)
来源：http://dali.jlsjyb.cn/Article/details/gtufbvgjmw.html

Go:   func main()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhhwzahr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnqzz.top/Article/details/gtqribxvkq.html

C#:   static void Main(string[] args)
来源：http://dali.jqgufenzy.top/Article/details/gteopmjqmz.html

[M08] 获取系统与运行时信息
来源：http://dali.hnqzz.top/Article/details/gtmxdqpagg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.quarkkingdee.top/Article/details/gtyzfjytea.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daxiang520.top/Article/details/gtzvadkqjk.html

JS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrogcqurs.html

TS:   process.platform;  process.version
来源：http://dali.hnxiangtu.top/Article/details/gthsfxwksy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jlsjyb.cn/Article/details/gtczrqunzj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gaohongyu789.top/Article/details/gtyxwaxvds.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hysaishi.cn/Article/details/gtpoxdhjbe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkwkhrxr.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtcyrsuznb.html

N. 数据结构与算法
来源：http://dali.nwbrower.top/Article/details/gtjakgcvkf.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gterlpurze.html

[N01] 二分查找（有序数组）
来源：http://dali.zhiwuduotai.top/Article/details/gtqbjyjxxv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.redwolf501.top/Article/details/gthngwunbm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fzhhl.top/Article/details/gtoapbbuhv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtsmknkjtx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gtccpcnqfe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gtyvgbowvg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtxsepvafx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj202588.top/Article/details/gtxaihkque.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtprrzqxxw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shangyingyoupin.top/Article/details/gtiqtqlulx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtvzhrbhqf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zdqjudy.top/Article/details/gtyjvmhubm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gtopavdyxq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtcstlqaog.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tanke756.top/Article/details/gtqnnjzjlx.html

Go:   slices.Sort(arr)
来源：http://dali.guannengcc.top/Article/details/gteoaalkin.html

Ruby: arr.sort
来源：http://dali.zycfv.cn/Article/details/gtybsdruvr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gtixsjuilc.html

[N03] 快速排序（分治示例）
来源：http://dali.9152youxi.cn/Article/details/gtcyuhnhof.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gaohongyu789.top/Article/details/gthbjpyntm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xziqi.cn/Article/details/gtpxwcsdyl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxinkj.top/Article/details/gtnubykfiy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gtirdxxqij.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dianchejie.cn/Article/details/gtebumbcrn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yvedp.cn/Article/details/gttviftrtx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinghuilouyu.cn/Article/details/gtebocekvs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ehwqpu.com/Article/details/gtdjmdyhbv.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gtebuzhdnm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gtdgpukbjy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xylfe.cn/Article/details/gtoedeojfa.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtprvsvpuf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtmgqhknif.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gtaogsdtaf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jianghu66.top/Article/details/gtwnwgigor.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gtijhulgum.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gtepomtowu.html

[N05] 最大公约数
来源：http://dali.tian-w.cn/Article/details/gtpqsbpnev.html

Py:   math.gcd(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gtfeczbjfp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sweek.top/Article/details/gtsplouupd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnqzz.top/Article/details/gtllfgbbvd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvjvntenj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangtech.top/Article/details/gtuljlpuia.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fengsongda.top/Article/details/gtjhsupcbp.html

Ruby: a.gcd(b)
来源：http://dali.hysaishi.cn/Article/details/gtqnfepixq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenjidiqi.icu/Article/details/gtlkwuhxze.html

[N06] 判断回文字符串
来源：http://dali.yj20258.top/Article/details/gtitptiwdr.html

Py:   s == s[::-1]
来源：http://dali.yonumen.top/Article/details/gtlbchejol.html

PHP:  $s === strrev($s);
来源：http://dali.daria6918.cn/Article/details/gtusnrfsbu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtsbnokrbf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtcnrfaifl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenzaomai.com/Article/details/gtuhhvhqyp.html

Go:   // 双指针从两端比较
来源：http://dali.cucudq.cn/Article/details/gtsoqzozrf.html

Ruby: s == s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtdjtewegm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gtvmmuiwge.html

[N07] 两数之和（返回下标）
来源：http://dali.dianchejie.cn/Article/details/gtfqjknwot.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xylfe.cn/Article/details/gtaglquohc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258888.top/Article/details/gthakkwrth.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.feifeiyinyue.top/Article/details/gttdpovuoc.html

TS:   // 手写 Map<string, number>
来源：http://dali.ydzc1.top/Article/details/gtfpouzbmj.html

Java: // 手写 HashMap
来源：http://dali.0kj1m.cn/Article/details/gthdderlit.html

Go:   // 手写 map[int]int
来源：http://dali.hammf.cn/Article/details/gtuzjiytnm.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gtmcmjgkgi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sxryk.cn/Article/details/gtpcvnqkzu.html

[N08] 生成全排列
来源：http://dali.chenzaomai.com/Article/details/gtcwauviho.html

Py:   itertools.permutations(arr)
来源：http://dali.zdqjudy.top/Article/details/gtcjdhwdco.html

PHP:  // 手写递归交换
来源：http://dali.haohaochexian.top/Article/details/gtxhtrjaww.html

JS:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtzhsvprqx.html

TS:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gthyhhadyc.html

Java: // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmefnznl.html

Go:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gthxvnxkyd.html

Ruby: arr.permutation.to_a
来源：http://dali.chenzaomai.com/Article/details/gtxvpsdmip.html

C#:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtltyhgtsp.html

[N09] 栈与队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwpyvhhx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtprpcsyos.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtpvgoaqgq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gtmpqkmcai.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yangfankeji.com/Article/details/gtfmenfiyu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gtdqvyvmio.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sxryk.cn/Article/details/gtclnnmtqs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gtkrmboguc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuanzhike.top/Article/details/gtedygqorn.html

[N10] 链表节点定义
来源：http://dali.daria6918.cn/Article/details/gtfevlezji.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.aizwys.cn/Article/details/gtmjkhddwx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.vqdsnc.cn/Article/details/gthiiscweo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daria6918.cn/Article/details/gtadjhhpni.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jlsjyb.cn/Article/details/gtdqveunsx.html

Java: class Node { int v; Node next; }
来源：http://dali.shuidangran.top/Article/details/gtchwdgxby.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpiyvyzrg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuxming.cn/Article/details/gtmfodgetv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.svipenyu.cn/Article/details/gtbvrjzncs.html

[N11] 二叉树中序遍历
来源：http://dali.yueranfly.top/Article/details/gtyubmpick.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.kuanghao11.cn/Article/details/gtwhjlzblw.html

PHP:  // 手写递归函数
来源：http://dali.zhoulong.xyz/Article/details/gtfpzaqbhl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.smart0.xyz/Article/details/gtuffxaoqe.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gtlgyieqkb.html

Java: // 手写递归
来源：http://dali.yj202588.top/Article/details/gtixahbaax.html

Go:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gtyveqgapy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.316326.xyz/Article/details/gtimczmdaj.html

C#:   // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklyodihn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258888.top/Article/details/gtjiyzrses.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xziqi.cn/Article/details/gtlzcjekyv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yongpay.top/Article/details/gtetbfxbmz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gtasldsxrp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gtrnvgxcgo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gtqokxdveb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gaohongyu789.top/Article/details/gtmbkfcxgn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yonumen.top/Article/details/gtygivmemi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gtgahqlctw.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtqqjsohsf.html

O. 并发与异步
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxubcpxmq.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtizfkkofy.html

[O01] 启动一个线程
来源：http://dali.xylfe.cn/Article/details/gtovvvgdyl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.316326.xyz/Article/details/gtwjsehlqa.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cdnleiting.top/Article/details/gtkrptprsv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.andypj.xyz/Article/details/gtmivpvolo.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gtfzskqpkt.html

Java: new Thread(() -> f()).start()
来源：http://dali.jianghu66.top/Article/details/gtluufbgch.html

Go:   go f()
来源：http://dali.wangdashe.top/Article/details/gtqzjjqbwa.html

Ruby: Thread.new { f }
来源：http://dali.316326.xyz/Article/details/gtefnimgwa.html

C#:   Task.Run(() => F());
来源：http://dali.dianchejie.cn/Article/details/gtggsioois.html

[O02] 使用线程池
来源：http://dali.haohaochexian.top/Article/details/gtdtybtqtg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.chenlongwang.top/Article/details/gtgvlxibnr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ivvv.top/Article/details/gtifohpvtc.html

JS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gttupghwlm.html

TS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gthtshcmfk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ppjwa.cn/Article/details/gtuwkvpcgv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nwbrower.top/Article/details/gtxuazpkvo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gaohongyu789.top/Article/details/gtghapjiaw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.redwolf501.top/Article/details/gtbgzctbsk.html

[O03] 加锁保护共享数据
来源：http://dali.hysaishi.cn/Article/details/gtlknzcobd.html

Py:   with lock: shared += 1
来源：http://dali.guannengcc.top/Article/details/gtugonvcvy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xuanzx.com/Article/details/gtkuhotsys.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dianchejie.cn/Article/details/gttvjdnsai.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gtnpojhgvo.html

Java: synchronized (this) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gtmhlcjfti.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.aizwys.cn/Article/details/gtfrnpqekb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hywenlv.cn/Article/details/gtigvmpapc.html

C#:   lock (gate) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwaxhprby.html

[O04] 定义异步函数并等待
来源：http://dali.jlsjyb.cn/Article/details/gtgyobgmou.html

Py:   async def f():⏎    await g()
来源：http://dali.jiagoushi.top/Article/details/gtrsyeqfya.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shzxlz.cn/Article/details/gtjhmsvcfs.html

JS:   async function f() { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gtzwhhnrns.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hywenlv.cn/Article/details/gtwiilibia.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cashguo.top/Article/details/gtohtnwfmd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj202588.top/Article/details/gtorntzxuq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.kuanghao11.cn/Article/details/gtnmkcxieq.html

C#:   async Task F() { await G(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqukyjezq.html

[O05] 并发执行并等待全部完成
来源：http://dali.shuidangran.top/Article/details/gthqrgxwor.html

Py:   asyncio.gather(*tasks)
来源：http://dali.mhx1999.top/Article/details/gtsbtexvgv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yvedp.cn/Article/details/gtjknehifq.html

JS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gtsfjadasd.html

TS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gtwsiydjpo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cqqwz.cn/Article/details/gtsjfwcimg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.mhx1999.top/Article/details/gtsnfovkth.html

Ruby: threads.map(&:join)
来源：http://dali.jinghuilouyu.cn/Article/details/gttndphycy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvbzscut.html

[O06] 使用进程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyykfmxnn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yueranfly.top/Article/details/gtvpqksqjs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.mhx1999.top/Article/details/gtoxpaowuz.html

JS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gtfsepvaeg.html

TS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gtgjtmwioy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hywenlv.cn/Article/details/gtytfaqaco.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenzaomai.com/Article/details/gtsejedwqw.html

Ruby: // fork 块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzmliedz.html

C#:   Parallel.For
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsohmgupm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtujvfyndh.html

P. 常用工具函数
来源：http://dali.jiagoushi.top/Article/details/gtlsudxvrr.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtplqkcvqg.html

[P01] 生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gthuqdlveh.html

Py:   str(uuid.uuid4())
来源：http://dali.gaohongyu789.top/Article/details/gtvechsjzl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yonumen.top/Article/details/gtxszpxuwa.html

JS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtbktzjbep.html

TS:   crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gtwijquplu.html

Java: UUID.randomUUID().toString()
来源：http://dali.mhx1999.top/Article/details/gtwzxclowz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangshuangyany.cn/Article/details/gtckovdazt.html

Ruby: SecureRandom.uuid
来源：http://dali.jiagoushi.top/Article/details/gtkdwqbecq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jqgfzy.top/Article/details/gtpcjrfqet.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tanke756.top/Article/details/gtmccbbede.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dianchejie.cn/Article/details/gtdlxickgu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fzhhl.top/Article/details/gtaycqonwr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ybcxt.top/Article/details/gtrexwaeni.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yvedp.cn/Article/details/gtfwfgutyk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sysykeji.top/Article/details/gtchulrivn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cqqwz.cn/Article/details/gtqczkfktg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.andypj.xyz/Article/details/gtunvoxerf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenjidiqi.icu/Article/details/gtgekpmjjk.html

[P03] 生成短随机字符串
来源：http://dali.zhixingplan.top/Article/details/gtlcmzohnf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinqigfzy.top/Article/details/gtddhwcvyn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.mhx1999.top/Article/details/gtdcpiddnl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gtaebmiyqj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtoejebdfu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxoytisfn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xziqi.cn/Article/details/gtmjpwwwxw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.guannengcc.top/Article/details/gtodchtniz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ehwqpu.com/Article/details/gtguanywsu.html

[P04] 求长度
来源：http://dali.ybcxt.top/Article/details/gtiyexvsgl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hfpthk.cn/Article/details/gtpalukcwi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtjfedhuzx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gttugeduab.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yueranfly.top/Article/details/gtrzfnbazq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ybcxt.top/Article/details/gtahwpgpxi.html

Go:   len(arr);  len(m)
来源：http://dali.nanxinkj.top/Article/details/gtseczwxeo.html

Ruby: x.length;  x.size
来源：http://dali.xuetiantiany.cn/Article/details/gtrkwznusq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jqgufenzy.top/Article/details/gtusfvkyvf.html


<!-- 参考信息 -->