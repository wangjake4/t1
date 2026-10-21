代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gtukdjfygn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinghuilouyu.cn/Article/details/gtavhkpusy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.birdmap.top/Article/details/gtzgsjjbjm.html

JS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gtvbzmdehi.html

TS:   resp.ok;  resp.status
来源：http://dali.shuidangran.top/Article/details/gtlvmtzfxy.html

Java: resp.statusCode()
来源：http://dali.yueranfly.top/Article/details/gtbwxdiwku.html

Go:   resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gtfdxvwegr.html

Ruby: resp.code.to_i
来源：http://dali.cheryme.top/Article/details/gtzlfgfpqj.html

C#:   (int)resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gtxqyajfjk.html

[L08] 并发请求多个地址
来源：http://dali.zhengqikj.top/Article/details/gtvevweknb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gtzvqrxgcp.html

PHP:  curl_multi_init() 系列
来源：http://dali.birdmap.top/Article/details/gtsrfnnbzv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gtbjzgpepk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtxxwukuoa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.0kj1m.cn/Article/details/gtalzgvjse.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.mhx1999.top/Article/details/gtutrzaajt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gtnfghmeau.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.birdmap.top/Article/details/gtscllunka.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtvndhzuzj.html

M. 命令行 / 进程 / 环境
来源：http://dali.sysykeji.top/Article/details/gtjtancrxo.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtwxizvzwf.html

[M01] 读取命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtyksgbjos.html

Py:   sys.argv[1:]
来源：http://dali.yueranfly.top/Article/details/gtbauyxvag.html

PHP:  $argv;  $argc;
来源：http://dali.yvedp.cn/Article/details/gtgngqtczc.html

JS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gtoqkeydtx.html

TS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gthtgymdqu.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpczmzbco.html

Go:   os.Args[1:]
来源：http://dali.yonumen.top/Article/details/gtwcvznwom.html

Ruby: ARGV
来源：http://dali.yj202588.top/Article/details/gtagrdynqc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gttnlvdpco.html

[M02] 读取环境变量
来源：http://dali.daria6918.cn/Article/details/gtsekxbwsf.html

Py:   os.environ.get("HOME")
来源：http://dali.jianghu66.top/Article/details/gttyzadbeg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gtrycjvryi.html

JS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gthpcrvcaz.html

TS:   process.env.HOME
来源：http://dali.vqdsnc.cn/Article/details/gtvmfxphme.html

Java: System.getenv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtsfhbrpvx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtevhonfca.html

Ruby: ENV["HOME"]
来源：http://dali.havefunace.top/Article/details/gtywgocyfw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtqxxiypxt.html

[M03] 执行外部命令
来源：http://dali.xinyue.icu/Article/details/gtzyvhlalv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenjidiqi.icu/Article/details/gttgocsiyr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ydzc1.top/Article/details/gtpcgyzpbs.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gtygltxiec.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gtovhlfiqr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cashguo.top/Article/details/gtajgvccna.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.kuanghao11.cn/Article/details/gtwwszeqrf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ydzc1.top/Article/details/gtagtocaie.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fengsongda.top/Article/details/gtvtfhmxpz.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gtaagfyqri.html

Py:   os.getcwd()
来源：http://dali.chenzaomai.com/Article/details/gtloqwqmgw.html

PHP:  getcwd();
来源：http://dali.cdnleiting.top/Article/details/gtdgmhjnlz.html

JS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gtelfigrsb.html

TS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gtsqszxnux.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqkbhwot.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gttiqmfhvw.html

Ruby: Dir.pwd
来源：http://dali.nwbrower.top/Article/details/gtqrwfxkii.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tian-w.cn/Article/details/gtwbdgahka.html

[M05] 设置退出码
来源：http://dali.yangfankeji.com/Article/details/gtazbehxym.html

Py:   sys.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtkmoanvfw.html

PHP:  exit(1);
来源：http://dali.chenzaomai.com/Article/details/gtqjkdpcfy.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtzlbnugyi.html

TS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtukbpvbtt.html

Java: System.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtwuxcexyn.html

Go:   os.Exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtpowunlfx.html

Ruby: exit 1
来源：http://dali.ybcxt.top/Article/details/gtqwgssqij.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.316326.xyz/Article/details/gtdxhljkwh.html

[M06] 向标准错误输出
来源：http://dali.tian-w.cn/Article/details/gtdgfpacml.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gtsznctlce.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yueranfly.top/Article/details/gtkueopsqk.html

JS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtlateibid.html

TS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gttvlshgrx.html

Java: System.err.println("err")
来源：http://dali.yuxming.cn/Article/details/gtvmjwwarl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zycfv.cn/Article/details/gtjpaybnmc.html

Ruby: warn "err"
来源：http://dali.9152youxi.cn/Article/details/gtzrsjuqca.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sysykeji.top/Article/details/gthdvfmupj.html

[M07] 判断是否为主入口
来源：http://dali.jinghuilouyu.cn/Article/details/gtrifroiin.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxinkj.top/Article/details/gtvynozzun.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tianlin.xyz/Article/details/gtdvjjafua.html

JS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gteulbowje.html

TS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gtfvxytdxi.html

Java: public static void main(String[] args)
来源：http://dali.vqdsnc.cn/Article/details/gteqkvhoel.html

Go:   func main()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlaixxasc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dianchejie.cn/Article/details/gtowofymdt.html

C#:   static void Main(string[] args)
来源：http://dali.xylfe.cn/Article/details/gtkfgszfzr.html

[M08] 获取系统与运行时信息
来源：http://dali.xylfe.cn/Article/details/gtxelbfvqs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hywenlv.cn/Article/details/gtlvqidply.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dianchejie.cn/Article/details/gtoacvunfk.html

JS:   process.platform;  process.version
来源：http://dali.yj20258.top/Article/details/gtlqgiqmkm.html

TS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gttkyyjxkf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xziqi.cn/Article/details/gtjxahcnoh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfijjquoi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangdashe.top/Article/details/gttwawieih.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jyoumei.cn/Article/details/gtdmieiwms.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtkhzwjtnz.html

N. 数据结构与算法
来源：http://dali.snrcjt.cn/Article/details/gtcxhcuzmm.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtkrjuakpt.html

[N01] 二分查找（有序数组）
来源：http://dali.c1oappe.top/Article/details/gtosbuinps.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtxchdplmg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.svipenyu.cn/Article/details/gtsszltedq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxblsvnnd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gtsvyogxgi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtjehiyjga.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtdvzzdohe.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fengsongda.top/Article/details/gtzlmlotmn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtvhhglghr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daria6918.cn/Article/details/gtklzyhhzu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gtaqyyldzh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dianchejie.cn/Article/details/gtvwyrsigu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtfvmjexid.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gtsdyudrkz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hysaishi.cn/Article/details/gtxlvliyeu.html

Go:   slices.Sort(arr)
来源：http://dali.snrcjt.cn/Article/details/gtapwflsan.html

Ruby: arr.sort
来源：http://dali.hnxiangtu.top/Article/details/gtaiqeyrzg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aibaodan.cn/Article/details/gtkmxvfsum.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigufen.top/Article/details/gtzwsqqkpo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhengqikj.top/Article/details/gtagbnqsxd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.redwolf501.top/Article/details/gtkwzkkeim.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gtcqmqudtp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxlbuhzk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxinkj.top/Article/details/gtimohitat.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhongyouzk.top/Article/details/gtpfprewcx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jlsjyb.cn/Article/details/gtwqlsxbfj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ydzc1.top/Article/details/gtyswlieke.html

[N04] 斐波那契数列
来源：http://dali.zhengqikj.top/Article/details/gtebqnudec.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gtlnsnpsnf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxxoabbo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtzlbqezuo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gtskjfecrs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gtikaktxsu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cashguo.top/Article/details/gtskyjsveb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gtgnyenbpi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtrjhtizdd.html

[N05] 最大公约数
来源：http://dali.sweek.top/Article/details/gtppgfzroe.html

Py:   math.gcd(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtzzdizndv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cqqwz.cn/Article/details/gtknpcvgdw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtmhqsctby.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gotoacloud.top/Article/details/gthsqnirtt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yueranfly.top/Article/details/gtcevgrnqy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.wangshuangyany.cn/Article/details/gtcmdefnoz.html

Ruby: a.gcd(b)
来源：http://dali.wangdashe.top/Article/details/gtbwghviqr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.andypj.xyz/Article/details/gtxgdzjdmb.html

[N06] 判断回文字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtjqnklokd.html

Py:   s == s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gtlkozlhap.html

PHP:  $s === strrev($s);
来源：http://dali.sysykeji.top/Article/details/gtqryhjejp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtbbhivzie.html

TS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtovbyhnrd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cashguo.top/Article/details/gtgtwkysaj.html

Go:   // 双指针从两端比较
来源：http://dali.guannengcc.top/Article/details/gtcndczmeq.html

Ruby: s == s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtxrdmysro.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gtsevoncsl.html

[N07] 两数之和（返回下标）
来源：http://dali.gotoacloud.top/Article/details/gtcupnpqiq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tianlin.xyz/Article/details/gtklxyjcbr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cdnleiting.top/Article/details/gtbkpyxyet.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sufxvd.cn/Article/details/gtulylclcg.html

TS:   // 手写 Map<string, number>
来源：http://dali.cqqwz.cn/Article/details/gtfcpapdnx.html

Java: // 手写 HashMap
来源：http://dali.hysaishi.cn/Article/details/gtyvvpevbt.html

Go:   // 手写 map[int]int
来源：http://dali.chenjidiqi.icu/Article/details/gthcxxhcbx.html

Ruby: // 手写 Hash
来源：http://dali.yonumen.top/Article/details/gtcmdaxdwp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvxppwvc.html

[N08] 生成全排列
来源：http://dali.pycfn.com/Article/details/gtzlgxanuw.html

Py:   itertools.permutations(arr)
来源：http://dali.ivvv.top/Article/details/gtpbwbuffq.html

PHP:  // 手写递归交换
来源：http://dali.9152youxi.cn/Article/details/gtpmgdtamb.html

JS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtgvctpatt.html

TS:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtlymcszgy.html

Java: // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtnwcxvdzx.html

Go:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtouneubbj.html

Ruby: arr.permutation.to_a
来源：http://dali.ydzc1.top/Article/details/gtdqgzjrzk.html

C#:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtxsvktxdw.html

[N09] 栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqdwiary.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhengqikj.top/Article/details/gtvabdttjp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtjzunjxqe.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtdrjdmyvv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fengsongda.top/Article/details/gtbkulcjgq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yvedp.cn/Article/details/gtyvtdxbly.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hysaishi.cn/Article/details/gtkqwsvnqq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtbrhoxlfy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258888.top/Article/details/gtdfirnmrz.html

[N10] 链表节点定义
来源：http://dali.tianlin.xyz/Article/details/gtihkdvlae.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xylfe.cn/Article/details/gtcdnvjsbp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowrlwbwc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cucudq.cn/Article/details/gtervenlxw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ivvv.top/Article/details/gtqaqiydqy.html

Java: class Node { int v; Node next; }
来源：http://dali.fzhhl.top/Article/details/gtxroolucr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aizwys.cn/Article/details/gtffwgaveu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenzaomai.com/Article/details/gtlybfcbog.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yongpay.top/Article/details/gthevchiqu.html

[N11] 二叉树中序遍历
来源：http://dali.yonumen.top/Article/details/gtzjlbxmkh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ybcxt.top/Article/details/gtkemcjxur.html

PHP:  // 手写递归函数
来源：http://dali.jinqigfzy.top/Article/details/gteuadzppg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgllnojeo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gtdzazfaiq.html

Java: // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtpnmtxzpo.html

Go:   // 手写递归
来源：http://dali.sweek.top/Article/details/gtlrivnwlj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgnpcehs.html

C#:   // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gtpdhitkuj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmoefxsnf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hysaishi.cn/Article/details/gtiujmifne.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenzaomai.com/Article/details/gthyuvezey.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gthllcpshn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gtycbcxkjr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gtysysmrye.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hongshengwenyu.top/Article/details/gttfijxnvu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258888.top/Article/details/gtwdjmmqcz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gtgttplkmk.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtgcpodjrl.html

O. 并发与异步
来源：http://dali.ydzc1.top/Article/details/gtfyqvqauy.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzomuchj.html

[O01] 启动一个线程
来源：http://dali.yj20258888.top/Article/details/gtorajswti.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gaohongyu789.top/Article/details/gtvdejaqas.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pycfn.com/Article/details/gtsrlrtvzd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gtgeapvcmu.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gtbusrjmjx.html

Java: new Thread(() -> f()).start()
来源：http://dali.redwolf501.top/Article/details/gtustfqtjl.html

Go:   go f()
来源：http://dali.gaohongyu789.top/Article/details/gtxlvdkwjb.html

Ruby: Thread.new { f }
来源：http://dali.zycfv.cn/Article/details/gtctemvhby.html

C#:   Task.Run(() => F());
来源：http://dali.zhiwuduotai.top/Article/details/gtgogcsruf.html

[O02] 使用线程池
来源：http://dali.hfpthk.cn/Article/details/gttgfiuhmg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aizwys.cn/Article/details/gtxvltmefm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.redwolf501.top/Article/details/gtzpaivrns.html

JS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gtdwoioczh.html

TS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gtypqldjcl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shuidangran.top/Article/details/gtnyyipgcg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yvedp.cn/Article/details/gtrqistjmj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.kuanghao11.cn/Article/details/gtbjhtjira.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gzhubu.top/Article/details/gtghanearz.html

[O03] 加锁保护共享数据
来源：http://dali.aibaodan.cn/Article/details/gtczihenei.html

Py:   with lock: shared += 1
来源：http://dali.gogol.net.cn/Article/details/gtfotwgjqn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aizwys.cn/Article/details/gtmpjkifji.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhixingplan.top/Article/details/gtyfwanruy.html

TS:   // 同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gtngdwzitc.html

Java: synchronized (this) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gtvqwzeehg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yongpay.top/Article/details/gtzezogywf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangdashe.top/Article/details/gttlaolevr.html

C#:   lock (gate) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gtelvgfroj.html

[O04] 定义异步函数并等待
来源：http://dali.yangfankeji.com/Article/details/gtzemufrdh.html

Py:   async def f():⏎    await g()
来源：http://dali.wangdashe.top/Article/details/gtrimvakan.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cucudq.cn/Article/details/gtiwwwnrzk.html

JS:   async function f() { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gtphwqkuee.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gogol.net.cn/Article/details/gtlztajmei.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsqydatr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuetiantiany.cn/Article/details/gtshofcczs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.vqdsnc.cn/Article/details/gtokhiyjdy.html

C#:   async Task F() { await G(); }
来源：http://dali.tianlin.xyz/Article/details/gtitbtnibl.html

[O05] 并发执行并等待全部完成
来源：http://dali.xinyue.icu/Article/details/gtvtpskjrv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xinyue.icu/Article/details/gtzbumresx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.bjfxy.top/Article/details/gtnvprnzse.html

JS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtubhqbrky.html

TS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gtamtywiyl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.redwolf501.top/Article/details/gtwsgzoosm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ydzc1.top/Article/details/gthcpwvozh.html

Ruby: threads.map(&:join)
来源：http://dali.daxiang520.top/Article/details/gtldmeiizb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ybcxt.top/Article/details/gtxvtenllq.html

[O06] 使用进程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjjucjep.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.quarkkingdee.top/Article/details/gtkifxsorq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.vqdsnc.cn/Article/details/gtcybhtjnr.html

JS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gtkulqytls.html

TS:   // child_process / cluster 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelcdoknk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cqqwz.cn/Article/details/gtommttmew.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.vqdsnc.cn/Article/details/gtaghyxkyi.html

Ruby: // fork 块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqznuyvlp.html

C#:   Parallel.For
来源：http://dali.xuanzx.com/Article/details/gtweyjlmpa.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtmzkvxkeu.html

P. 常用工具函数
来源：http://dali.9152youxi.cn/Article/details/gtnmuyzpgk.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtkjbvcaxa.html

[P01] 生成 UUID
来源：http://dali.zycfv.cn/Article/details/gtmwgvikda.html

Py:   str(uuid.uuid4())
来源：http://dali.daxiang520.top/Article/details/gtwbwegkpz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jiagoushi.top/Article/details/gtumkkncyh.html

JS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gthprlcqpo.html

TS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gtdtxdpeat.html

Java: UUID.randomUUID().toString()
来源：http://dali.kuanghao11.cn/Article/details/gtflanrnky.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tanke756.top/Article/details/gthuopwgdg.html

Ruby: SecureRandom.uuid
来源：http://dali.wangshuangyany.cn/Article/details/gtzeggzyga.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258888.top/Article/details/gtxqzvidlq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.meibo888.top/Article/details/gtgupbzwpd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenlongwang.top/Article/details/gtoclggyyc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xinyue.icu/Article/details/gtyzkurxas.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hfpthk.cn/Article/details/gtkwqitpuf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shzxlz.cn/Article/details/gtzisqbrcv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.fengsongda.top/Article/details/gtxuwyssnc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.bjfxy.top/Article/details/gtqjmdizqi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtmfytjpre.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sysykeji.top/Article/details/gtmxpuqdzm.html

[P03] 生成短随机字符串
来源：http://dali.mhx1999.top/Article/details/gtqhsxnrig.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shuidangran.top/Article/details/gtlxvvalni.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cucudq.cn/Article/details/gtukvtbbac.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gtdcxrentd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gtfonnhzgl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ybcxt.top/Article/details/gtulrmngmk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.redwolf501.top/Article/details/gtvcmflybx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.snrcjt.cn/Article/details/gtbtdurmbv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yanxiufei.cn/Article/details/gtbrucoylb.html

[P04] 求长度
来源：http://dali.nanxuanxn.top/Article/details/gtstseibgo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ybcxt.top/Article/details/gtibykxmat.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtvogazpia.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gtuqpzmuid.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cqqwz.cn/Article/details/gtbxpqxbgd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.birdmap.top/Article/details/gtkypmqhzh.html

Go:   len(arr);  len(m)
来源：http://dali.ydzc1.top/Article/details/gtmqmhzwxe.html

Ruby: x.length;  x.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsuoxjvg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrvwdkpg.html


<!-- 参考信息 -->