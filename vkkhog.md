代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifcnjivm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.havefunace.top/Article/details/gthdsfbrki.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhoulong.xyz/Article/details/gtxixmgygy.html

JS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gtvpiftubg.html

TS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gthqoliamj.html

Java: resp.statusCode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsncsalnj.html

Go:   resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gtpnkisadj.html

Ruby: resp.code.to_i
来源：http://dali.hongshengwenyu.top/Article/details/gtztdwguvs.html

C#:   (int)resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gtjrtgzxsr.html

[L08] 并发请求多个地址
来源：http://dali.mhx1999.top/Article/details/gtrtxpkcxd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cdnleiting.top/Article/details/gtaqdnsuyd.html

PHP:  curl_multi_init() 系列
来源：http://dali.havefunace.top/Article/details/gtduxonqpi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtmoylaxub.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtyhjzhxjr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gtvhzqeang.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xziqi.cn/Article/details/gtowmldhmc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xinyue.icu/Article/details/gtahqmweql.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tian-w.cn/Article/details/gtcojzmyxm.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtchdffijg.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj20258.top/Article/details/gtekpjsmau.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtfyfbosgs.html

[M01] 读取命令行参数
来源：http://dali.birdmap.top/Article/details/gtevmkrtal.html

Py:   sys.argv[1:]
来源：http://dali.tian-w.cn/Article/details/gteqewqbhf.html

PHP:  $argv;  $argc;
来源：http://dali.yvedp.cn/Article/details/gtwloddzkc.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gttuskhyqn.html

TS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gtcxjymgct.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteypqyngj.html

Go:   os.Args[1:]
来源：http://dali.aibaodan.cn/Article/details/gtsaankkoc.html

Ruby: ARGV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtjlbktj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gtrxyzngvm.html

[M02] 读取环境变量
来源：http://dali.tianlin.xyz/Article/details/gtmxuualtc.html

Py:   os.environ.get("HOME")
来源：http://dali.wangdashe.top/Article/details/gtokaiccgt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtwaoydqtu.html

JS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gtdkietusd.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gtiyooolnp.html

Java: System.getenv("HOME")
来源：http://dali.fzhhl.top/Article/details/gtkxxrwxrz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuanzx.com/Article/details/gttmgvlvof.html

Ruby: ENV["HOME"]
来源：http://dali.hfpthk.cn/Article/details/gtgitjudoz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtodwwyblu.html

[M03] 执行外部命令
来源：http://dali.quarkkingdee.top/Article/details/gtxsobnwpc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxinkj.top/Article/details/gtnatmykue.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuetiantiany.cn/Article/details/gtdpgdzgux.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gteirdetjx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gtaydxmjmk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yongpay.top/Article/details/gtkxteioem.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.9152youxi.cn/Article/details/gtbpktslve.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuetiantiany.cn/Article/details/gtymrdxuet.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenjidiqi.icu/Article/details/gtfiwlecti.html

[M04] 获取当前工作目录
来源：http://dali.quarkkingdee.top/Article/details/gtoznzcebb.html

Py:   os.getcwd()
来源：http://dali.dashuyun.cn/Article/details/gtqlejxijs.html

PHP:  getcwd();
来源：http://dali.meibo888.top/Article/details/gtzjynihvu.html

JS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gtyzfbvpdf.html

TS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gtbxwrbqmd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sweek.top/Article/details/gtxabmrifm.html

Go:   os.Getwd()
来源：http://dali.smart0.xyz/Article/details/gtbzeuyrxs.html

Ruby: Dir.pwd
来源：http://dali.9152youxi.cn/Article/details/gtdsldyfyn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sufxvd.cn/Article/details/gtvnbxszoc.html

[M05] 设置退出码
来源：http://dali.nwbrower.top/Article/details/gtovbzztxr.html

Py:   sys.exit(1)
来源：http://dali.meibo888.top/Article/details/gtxalgaxem.html

PHP:  exit(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevhjycfh.html

JS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixhdbdpq.html

TS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtewchxswx.html

Java: System.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtvnbjbjls.html

Go:   os.Exit(1)
来源：http://dali.ybcxt.top/Article/details/gtbryairin.html

Ruby: exit 1
来源：http://dali.cashguo.top/Article/details/gttanydbja.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hywenlv.cn/Article/details/gtktcxcxlk.html

[M06] 向标准错误输出
来源：http://dali.nanxuanxn.top/Article/details/gtqpiotqrb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gtfdbfpzvs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cashguo.top/Article/details/gtlbzisdtq.html

JS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gtkybyfzyk.html

TS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gtgvdjbzgr.html

Java: System.err.println("err")
来源：http://dali.9152youxi.cn/Article/details/gtapyrtftb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hfpthk.cn/Article/details/gtstzeqwbd.html

Ruby: warn "err"
来源：http://dali.zhiwuduotai.top/Article/details/gtgtcxrlmc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgfzy.top/Article/details/gtwonrjwkf.html

[M07] 判断是否为主入口
来源：http://dali.meibo888.top/Article/details/gtodcwmftk.html

Py:   if __name__ == "__main__":
来源：http://dali.xuetiantiany.cn/Article/details/gtfuoosbom.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnqzz.top/Article/details/gtogvxppeo.html

JS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gtmyhajwzv.html

TS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gtbxvuviqc.html

Java: public static void main(String[] args)
来源：http://dali.chenzaomai.com/Article/details/gtvofdavfq.html

Go:   func main()
来源：http://dali.ydzc1.top/Article/details/gtxoaklnyr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenzaomai.com/Article/details/gtruijvqjy.html

C#:   static void Main(string[] args)
来源：http://dali.tian-w.cn/Article/details/gtvflmelaf.html

[M08] 获取系统与运行时信息
来源：http://dali.meibo888.top/Article/details/gtkppcywiq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.mhx1999.top/Article/details/gtavozzmsv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangdashe.top/Article/details/gtjznrtrgs.html

JS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gtkglaayhk.html

TS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gtqxovpnvd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.iojbl.cn/Article/details/gtluyyljwn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgfzy.top/Article/details/gtcbvqdedm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnxiangtu.top/Article/details/gtmqstmxwi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tian-w.cn/Article/details/gtnaethhis.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtrhbbdfvx.html

N. 数据结构与算法
来源：http://dali.dianchejie.cn/Article/details/gtfrkyfxwd.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtywrsymkm.html

[N01] 二分查找（有序数组）
来源：http://dali.jianghu66.top/Article/details/gtjoqonakc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtnbnqsdrw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtnmdvbpbs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtiubrhzpq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtuphaxqow.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtwnazsjgb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtmqfsiukl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ydzc1.top/Article/details/gtirilsaeu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnaektmwz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.redwolf501.top/Article/details/gtmywxtiwl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gtgbzathzv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cucudq.cn/Article/details/gtuqjxnsxj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gtawzlvegj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gtvjzlrlfr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqwgjcvp.html

Go:   slices.Sort(arr)
来源：http://dali.guannengcc.top/Article/details/gteqqjghvf.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gtnsrbplal.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.birdmap.top/Article/details/gtjlyrintx.html

[N03] 快速排序（分治示例）
来源：http://dali.nwbrower.top/Article/details/gtdynblqvj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pengpengdd.cyou/Article/details/gtvhixikiw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sweek.top/Article/details/gtrowjvdhi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gtvwxbikmc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gtgdszhaee.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.haohaochexian.top/Article/details/gthaxgjxuk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ppjwa.cn/Article/details/gtxsaqdzuc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jiagoushi.top/Article/details/gtvhaauzua.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.smart0.xyz/Article/details/gtwyrtgtdt.html

[N04] 斐波那契数列
来源：http://dali.yangfankeji.com/Article/details/gttdtdmlom.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gthotonisr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gtiywgngis.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvibjazlv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtpqqebmsy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tanke756.top/Article/details/gttuaziibh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dianchejie.cn/Article/details/gtnblybqtf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtyopjgqap.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvwvlcrt.html

[N05] 最大公约数
来源：http://dali.jiagoushi.top/Article/details/gtvflogdms.html

Py:   math.gcd(a, b)
来源：http://dali.cdnleiting.top/Article/details/gtbdraaxyd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgufenzy.top/Article/details/gtarbxxkeh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gtuaxfzqwp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gtbsacnzxa.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jiagoushi.top/Article/details/gtaidepybq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gogol.net.cn/Article/details/gtqelttavp.html

Ruby: a.gcd(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtvmjuqydx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xinyue.icu/Article/details/gtkagkyfgh.html

[N06] 判断回文字符串
来源：http://dali.cucudq.cn/Article/details/gtkqgihgfx.html

Py:   s == s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gtdnaasljm.html

PHP:  $s === strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gtbeitwymz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtgblfwwza.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmvcvkti.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ehwqpu.com/Article/details/gtnqaytgoh.html

Go:   // 双指针从两端比较
来源：http://dali.zycfv.cn/Article/details/gtueogmrah.html

Ruby: s == s.reverse
来源：http://dali.smart0.xyz/Article/details/gtvewhctrl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenjidiqi.icu/Article/details/gtkvmramjd.html

[N07] 两数之和（返回下标）
来源：http://dali.ybcxt.top/Article/details/gtaytpjqxi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenjidiqi.icu/Article/details/gtpiduvkgr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuetiantiany.cn/Article/details/gtiezycruz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jiagoushi.top/Article/details/gtfjewawel.html

TS:   // 手写 Map<string, number>
来源：http://dali.haohaochexian.top/Article/details/gtjrigbrxj.html

Java: // 手写 HashMap
来源：http://dali.iojbl.cn/Article/details/gtkkivfenm.html

Go:   // 手写 map[int]int
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnkzovvw.html

Ruby: // 手写 Hash
来源：http://dali.pengpengdd.cyou/Article/details/gtbmktqlei.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guannengcc.top/Article/details/gtuiyzglua.html

[N08] 生成全排列
来源：http://dali.hnxiangtu.top/Article/details/gtmpyxwnoi.html

Py:   itertools.permutations(arr)
来源：http://dali.cucudq.cn/Article/details/gttiedssvh.html

PHP:  // 手写递归交换
来源：http://dali.zycfv.cn/Article/details/gtojpajoos.html

JS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtbdmodlbk.html

TS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtjzkppveh.html

Java: // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtptrdkofd.html

Go:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtpgctzgqq.html

Ruby: arr.permutation.to_a
来源：http://dali.chenjidiqi.icu/Article/details/gtoiixzyfl.html

C#:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtjrkqvsrp.html

[N09] 栈与队列
来源：http://dali.sufxvd.cn/Article/details/gtlrteyuiu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj202588.top/Article/details/gtfrzyneoy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj20258.top/Article/details/gtrvxitgmu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gtnprvugho.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangdashe.top/Article/details/gtopkejkjn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guannengcc.top/Article/details/gtcdheqvgc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yonumen.top/Article/details/gtnjhkctot.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrjgyrna.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuanzx.com/Article/details/gtwkimahdx.html

[N10] 链表节点定义
来源：http://dali.yvedp.cn/Article/details/gtxmxrwuux.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.9152youxi.cn/Article/details/gttrfumsiu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ydzc1.top/Article/details/gtsjfeckjf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sxryk.cn/Article/details/gtvzvjnjgi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tian-w.cn/Article/details/gtbhwzzrxw.html

Java: class Node { int v; Node next; }
来源：http://dali.ivvv.top/Article/details/gteqahlyia.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gogol.net.cn/Article/details/gtcjilgblr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ivvv.top/Article/details/gtvzxwvhgu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.snrcjt.cn/Article/details/gtkavszjjg.html

[N11] 二叉树中序遍历
来源：http://dali.tian-w.cn/Article/details/gtisilvkfb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fengsongda.top/Article/details/gtrlqhebnn.html

PHP:  // 手写递归函数
来源：http://dali.svipenyu.cn/Article/details/gtmmtseuns.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gtqluiyaaq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gtvvwfuzho.html

Java: // 手写递归
来源：http://dali.yvedp.cn/Article/details/gtdvexcngq.html

Go:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gtnzbfsloz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guowangkeji.top/Article/details/gttdrrrrdb.html

C#:   // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqogybtg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigfzy.top/Article/details/gtnyijmpsr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sysykeji.top/Article/details/gtdgilfwvh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhoulong.xyz/Article/details/gtetkacsst.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gtmfwrubgu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gtnyorfrbd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gtpfzxkpdj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.vqdsnc.cn/Article/details/gtogpyorkp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gtseaotxzx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gtydhoxkoo.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtevgvwqps.html

O. 并发与异步
来源：http://dali.jqgfzy.top/Article/details/gtnoygjhvs.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtumncbgvs.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gtjycnajed.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hammf.cn/Article/details/gtzyhqramw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.daxiang520.top/Article/details/gtpoipkbxk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.quarkkingdee.top/Article/details/gtfmttfjku.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gtnubedwfl.html

Java: new Thread(() -> f()).start()
来源：http://dali.yongpay.top/Article/details/gtxfneaomj.html

Go:   go f()
来源：http://dali.cucudq.cn/Article/details/gtisklvepl.html

Ruby: Thread.new { f }
来源：http://dali.yangfankeji.com/Article/details/gtomrvwlwg.html

C#:   Task.Run(() => F());
来源：http://dali.yangfankeji.com/Article/details/gtnitvxzhd.html

[O02] 使用线程池
来源：http://dali.cqqwz.cn/Article/details/gtufgrtdae.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnxiangtu.top/Article/details/gtdzcxdnst.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hongshengwenyu.top/Article/details/gtdjspnmmv.html

JS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gtgyviagpa.html

TS:   // worker_threads 线程池
来源：http://dali.guowangkeji.top/Article/details/gtulgllxnb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangshuangyany.cn/Article/details/gtgrlqrghj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkluauoer.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cashguo.top/Article/details/gtqioaglon.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllcetqpn.html

[O03] 加锁保护共享数据
来源：http://dali.birdmap.top/Article/details/gtdgfcfrhz.html

Py:   with lock: shared += 1
来源：http://dali.hnxiangtu.top/Article/details/gtoonsqgdf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tianlin.xyz/Article/details/gtrfbyacak.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xinyue.icu/Article/details/gtlmqlpayk.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gtfguwoduo.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthlotcnn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tian-w.cn/Article/details/gtnfbhwiyn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuxming.cn/Article/details/gtkqqkcrtj.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqlkquae.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlaevqwbd.html

Py:   async def f():⏎    await g()
来源：http://dali.dianchejie.cn/Article/details/gtolgymmom.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gaohongyu789.top/Article/details/gtmrkrmscp.html

JS:   async function f() { await g(); }
来源：http://dali.birdmap.top/Article/details/gttyagrdtc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gtprmclhhi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ybcxt.top/Article/details/gtcslkavza.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258888.top/Article/details/gtyxdfmmjy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.smart0.xyz/Article/details/gtplaxwckl.html

C#:   async Task F() { await G(); }
来源：http://dali.sweek.top/Article/details/gtkqshdjyo.html

[O05] 并发执行并等待全部完成
来源：http://dali.tianlin.xyz/Article/details/gtlwrkltcv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yonumen.top/Article/details/gtjkijaxve.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hywenlv.cn/Article/details/gtnnthydwa.html

JS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gtnairznye.html

TS:   await Promise.all(tasks)
来源：http://dali.fzhhl.top/Article/details/gtzdjvxjiq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ybcxt.top/Article/details/gtgxajikfk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dianchejie.cn/Article/details/gtnkuqcshs.html

Ruby: threads.map(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtukimfxhi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nanxuanxn.top/Article/details/gteegkkklj.html

[O06] 使用进程池
来源：http://dali.hysaishi.cn/Article/details/gtjqugqslu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dianchejie.cn/Article/details/gtaigsbkjb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yueranfly.top/Article/details/gtefmyjsul.html

JS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gtxydsbgdy.html

TS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gtyzwvlbaf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yanxiufei.cn/Article/details/gtojbljxzk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nwbrower.top/Article/details/gtxwvrousz.html

Ruby: // fork 块
来源：http://dali.hfpthk.cn/Article/details/gtgcrqyfxz.html

C#:   Parallel.For
来源：http://dali.hammf.cn/Article/details/gtclsigdje.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqjzswhkw.html

P. 常用工具函数
来源：http://dali.c1oappe.top/Article/details/gtupjxaldj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtmmsdiefi.html

[P01] 生成 UUID
来源：http://dali.chenzaomai.com/Article/details/gtuyhxvhqe.html

Py:   str(uuid.uuid4())
来源：http://dali.kuanghao11.cn/Article/details/gtbvotwqyo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gthtqrsepq.html

JS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gtaiiwmqns.html

TS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gtwehytfrx.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnxiangtu.top/Article/details/gtxlremjxg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxandshc.html

Ruby: SecureRandom.uuid
来源：http://dali.aizwys.cn/Article/details/gtvjjxkrym.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.bjfxy.top/Article/details/gtlwapgrqj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gotoacloud.top/Article/details/gtejfsoxis.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigfzy.top/Article/details/gtqtvdbyrl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sweek.top/Article/details/gtcoxnhhor.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.9152youxi.cn/Article/details/gtoalhhnfs.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gogol.net.cn/Article/details/gthurhgrjp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jqgfzy.top/Article/details/gtjiqjtszq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.havefunace.top/Article/details/gtvgfnyrfa.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hywenlv.cn/Article/details/gtyocavhot.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatfqkyni.html

[P03] 生成短随机字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqzngzak.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenzaomai.com/Article/details/gtklhqdtas.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tian-w.cn/Article/details/gtcohghdww.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gtdcvhkvbl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gtbuieopms.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aibaodan.cn/Article/details/gtnakpcckd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.meibo888.top/Article/details/gtgvzlnlya.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.aizwys.cn/Article/details/gtsqyznjyn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.smart0.xyz/Article/details/gttmzchhue.html

[P04] 求长度
来源：http://dali.xziqi.cn/Article/details/gtdquxumci.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ehwqpu.com/Article/details/gtqnjokgcj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtqsmjnhyy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gtuybsmlhb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknzgiiep.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtfcoczugo.html

Go:   len(arr);  len(m)
来源：http://dali.xuetiantiany.cn/Article/details/gtqoyxzlob.html

Ruby: x.length;  x.size
来源：http://dali.snrcjt.cn/Article/details/gtrxtcyvjs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tanke756.top/Article/details/gtchexjubw.html


<!-- 参考信息 -->