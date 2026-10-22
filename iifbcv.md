代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gt2iedxzwil.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aibaodan.cn/Article/details/gt2cvbbahxf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gaohongyu789.top/Article/details/gt2adrvaedq.html

JS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gt2aghgyije.html

TS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gt2tsfuyjzj.html

Java: resp.statusCode()
来源：http://dali.316326.xyz/Article/details/gt2osasxora.html

Go:   resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gt2mzmekfma.html

Ruby: resp.code.to_i
来源：http://dali.xuetiantiany.cn/Article/details/gt2fzroulle.html

C#:   (int)resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gt2zxudkqev.html

[L08] 并发请求多个地址
来源：http://dali.zhiwuduotai.top/Article/details/gt2eqzfyqqq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ppjwa.cn/Article/details/gt2ihrvumhz.html

PHP:  curl_multi_init() 系列
来源：http://dali.ydzc1.top/Article/details/gt2byfrbiwy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gt2swkamnvb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gt2skdhnppg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sweek.top/Article/details/gt2kdizuaze.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.9152youxi.cn/Article/details/gt2arseuxlb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.c1oappe.top/Article/details/gt2heauoilj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gzhubu.top/Article/details/gt2avondnty.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2pjxlsjoz.html

M. 命令行 / 进程 / 环境
来源：http://dali.pengpengdd.cyou/Article/details/gt2gtkxftuo.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2zsretdam.html

[M01] 读取命令行参数
来源：http://dali.tanke756.top/Article/details/gt2piuxrpgf.html

Py:   sys.argv[1:]
来源：http://dali.chenlongwang.top/Article/details/gt2jxzkqiih.html

PHP:  $argv;  $argc;
来源：http://dali.xuetiantiany.cn/Article/details/gt2uvrepcak.html

JS:   process.argv.slice(2)
来源：http://dali.sysykeji.top/Article/details/gt2sprquwlq.html

TS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gt2cenowiep.html

Java: args 数组（main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gt2zxmddkxo.html

Go:   os.Args[1:]
来源：http://dali.yangfankeji.com/Article/details/gt2pnrrrzux.html

Ruby: ARGV
来源：http://dali.tian-w.cn/Article/details/gt2ikqrmfii.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gt2yjljiyob.html

[M02] 读取环境变量
来源：http://dali.jyoumei.cn/Article/details/gt2iaoqwbxh.html

Py:   os.environ.get("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2nspsphdb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gt2yesggzhf.html

JS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gt2cijkjpto.html

TS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gt2edwngplj.html

Java: System.getenv("HOME")
来源：http://dali.aizwys.cn/Article/details/gt2hhicryuj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gt2gpnmmbvm.html

Ruby: ENV["HOME"]
来源：http://dali.chenjidiqi.icu/Article/details/gt2kzfblntk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sysykeji.top/Article/details/gt2phetutka.html

[M03] 执行外部命令
来源：http://dali.tanke756.top/Article/details/gt2eohphccs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ppjwa.cn/Article/details/gt2ugcplprd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cucudq.cn/Article/details/gt2uixqizon.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gt2vjpmjenr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gt2yjsgbrqo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2npqdjdki.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sufxvd.cn/Article/details/gt2kbfoparp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgfzy.top/Article/details/gt2vpcaqtkj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xuanzx.com/Article/details/gt2eospxoto.html

[M04] 获取当前工作目录
来源：http://dali.hfpthk.cn/Article/details/gt2nmmikbpb.html

Py:   os.getcwd()
来源：http://dali.jyoumei.cn/Article/details/gt2pgugwwmi.html

PHP:  getcwd();
来源：http://dali.kuanghao11.cn/Article/details/gt2dartjgqj.html

JS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gt2xcvhaefy.html

TS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gt2iwnobcju.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvafjxy.html

Go:   os.Getwd()
来源：http://dali.jinqigfzy.top/Article/details/gt2nfqsyjnm.html

Ruby: Dir.pwd
来源：http://dali.shangyingyoupin.top/Article/details/gt2wqvmlodh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.guannengcc.top/Article/details/gt2vnjikgvv.html

[M05] 设置退出码
来源：http://dali.ybcxt.top/Article/details/gt2fxsknpni.html

Py:   sys.exit(1)
来源：http://dali.sweek.top/Article/details/gt2zpispeyb.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2dkcatrlz.html

JS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2mwkwujzo.html

TS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2vclkpbcz.html

Java: System.exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2rmuwdmct.html

Go:   os.Exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2ztauvtoe.html

Ruby: exit 1
来源：http://dali.shuidangran.top/Article/details/gt2aiiuygcy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guowangkeji.top/Article/details/gt2pgyozuvk.html

[M06] 向标准错误输出
来源：http://dali.zhoulong.xyz/Article/details/gt2iusxuimc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.havefunace.top/Article/details/gt2puturfsf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pengpengdd.cyou/Article/details/gt2tqpaibry.html

JS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gt2ymjyyszy.html

TS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gt2rysxjzqo.html

Java: System.err.println("err")
来源：http://dali.hysaishi.cn/Article/details/gt2glubkrhc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.c1oappe.top/Article/details/gt2vlsfsgmu.html

Ruby: warn "err"
来源：http://dali.0kj1m.cn/Article/details/gt2bbubxxrw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dianchejie.cn/Article/details/gt2dmoflzhe.html

[M07] 判断是否为主入口
来源：http://dali.cheryme.top/Article/details/gt2olyzwibc.html

Py:   if __name__ == "__main__":
来源：http://dali.sysykeji.top/Article/details/gt2btvndexk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yonumen.top/Article/details/gt2hsgaxuyy.html

JS:   require.main === module
来源：http://dali.snrcjt.cn/Article/details/gt2xtxbvpbc.html

TS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gt2yxvsbdtg.html

Java: public static void main(String[] args)
来源：http://dali.daxiang520.top/Article/details/gt2nkobliny.html

Go:   func main()
来源：http://dali.nanxuanxn.top/Article/details/gt2mbpxrjsx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenjidiqi.icu/Article/details/gt2dniqcnes.html

C#:   static void Main(string[] args)
来源：http://dali.yuxming.cn/Article/details/gt2zvrvowvx.html

[M08] 获取系统与运行时信息
来源：http://dali.tianlin.xyz/Article/details/gt2hsdteqcx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ehwqpu.com/Article/details/gt2ahybwmeo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sysykeji.top/Article/details/gt2pcyustpb.html

JS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gt2kssghete.html

TS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gt2dvapzxlr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxuanxn.top/Article/details/gt2pradbxuo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.9152youxi.cn/Article/details/gt2zngoblze.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xziqi.cn/Article/details/gt2nogqwglf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shangyingyoupin.top/Article/details/gt2sajgrwio.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2qqfafull.html

N. 数据结构与算法
来源：http://dali.yuanzhike.top/Article/details/gt2pqqumaas.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2aduichlh.html

[N01] 二分查找（有序数组）
来源：http://dali.guowangkeji.top/Article/details/gt2jaoarmpy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2ayxfriwo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sufxvd.cn/Article/details/gt2vnrvkrrz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gt2sivddwea.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gt2nejjtebf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2bygrncqh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2vgjbrina.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yueranfly.top/Article/details/gt2sqrgjqnp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2seutcnfp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.kuanghao11.cn/Article/details/gt2fqmiqblm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gt2bsabuiau.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgfzy.top/Article/details/gt2molndmtv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gt2uktgfeip.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gt2ufzpmnby.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gaohongyu789.top/Article/details/gt2cderqbqc.html

Go:   slices.Sort(arr)
来源：http://dali.tian-w.cn/Article/details/gt2xzdgrqsg.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gt2kpdkctzd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sweek.top/Article/details/gt2rhyhcrtg.html

[N03] 快速排序（分治示例）
来源：http://dali.hfpthk.cn/Article/details/gt2swukauaf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yangfankeji.com/Article/details/gt2pkcgvoba.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tanke756.top/Article/details/gt2lrqhvspq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gt2arebkawz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gt2wuvfvzcf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zycfv.cn/Article/details/gt2dpcvzstt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aizwys.cn/Article/details/gt2fsydaeey.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guannengcc.top/Article/details/gt2fbvpkzef.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jrvhyfcb.html

[N04] 斐波那契数列
来源：http://dali.zhiwuduotai.top/Article/details/gt2cfvxgdjz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gt2wncdntyt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daria6918.cn/Article/details/gt2sakpzhxz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gt2krowovkg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gt2cktidxln.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gt2ektjmklt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zdqjudy.top/Article/details/gt2aawkwiin.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gt2fwubbxqk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gt2ticghgpc.html

[N05] 最大公约数
来源：http://dali.hywenlv.cn/Article/details/gt2djtmgosw.html

Py:   math.gcd(a, b)
来源：http://dali.meibo888.top/Article/details/gt2nldfnhkk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ydzc1.top/Article/details/gt2zleeqqbd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gt2nbbnbfcf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gt2mbtgxaiv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.meibo888.top/Article/details/gt2wmguqbng.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cganuhdo.html

Ruby: a.gcd(b)
来源：http://dali.9152youxi.cn/Article/details/gt2nerikshf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tian-w.cn/Article/details/gt2jztsftyp.html

[N06] 判断回文字符串
来源：http://dali.nwbrower.top/Article/details/gt2dkilffpp.html

Py:   s == s[::-1]
来源：http://dali.xylfe.cn/Article/details/gt2anhpvykn.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uhvthhcv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gt2oaykskkc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gt2iohxjcfp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yanxiufei.cn/Article/details/gt2ulpyhprh.html

Go:   // 双指针从两端比较
来源：http://dali.cucudq.cn/Article/details/gt2kpawtanq.html

Ruby: s == s.reverse
来源：http://dali.guowangkeji.top/Article/details/gt2jqmgpmmd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gt2jnsppijr.html

[N07] 两数之和（返回下标）
来源：http://dali.zhengqikj.top/Article/details/gt2cgcwqwlu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xinyue.icu/Article/details/gt2gfkvadvo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuanzx.com/Article/details/gt2iblijggm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vchrctgf.html

TS:   // 手写 Map<string, number>
来源：http://dali.ehwqpu.com/Article/details/gt2bimwkibc.html

Java: // 手写 HashMap
来源：http://dali.yangfankeji.com/Article/details/gt2ebgaiqls.html

Go:   // 手写 map[int]int
来源：http://dali.tanke756.top/Article/details/gt2mugsyivr.html

Ruby: // 手写 Hash
来源：http://dali.gzhubu.top/Article/details/gt2tlxepaqh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sysykeji.top/Article/details/gt2arwygjta.html

[N08] 生成全排列
来源：http://dali.sxryk.cn/Article/details/gt2nasmtamx.html

Py:   itertools.permutations(arr)
来源：http://dali.bjfxy.top/Article/details/gt2dadipegk.html

PHP:  // 手写递归交换
来源：http://dali.sweek.top/Article/details/gt2cebmtexp.html

JS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cdpqsfyd.html

TS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2fimocfwr.html

Java: // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gt2diavkoia.html

Go:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gt2ykkrgqqh.html

Ruby: arr.permutation.to_a
来源：http://dali.wangshuangyany.cn/Article/details/gt2bqfifdol.html

C#:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hsctjgtf.html

[N09] 栈与队列
来源：http://dali.ydzc1.top/Article/details/gt2zlxbrdou.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wgxnorgq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gt2cahhmjxv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xylfe.cn/Article/details/gt2vtgzykqn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hammf.cn/Article/details/gt2bwporeyz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tanke756.top/Article/details/gt2abjteizd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xinyue.icu/Article/details/gt2kajljhme.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gt2udgpsafv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xylfe.cn/Article/details/gt2ydtyhkpy.html

[N10] 链表节点定义
来源：http://dali.svipenyu.cn/Article/details/gt2wcptudae.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xylfe.cn/Article/details/gt2qalrvazl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hufvmsiv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sufxvd.cn/Article/details/gt2auisfgpr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gzhubu.top/Article/details/gt2cfzmyouq.html

Java: class Node { int v; Node next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ylzbtdrb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cdnleiting.top/Article/details/gt2eywchplx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jianghu66.top/Article/details/gt2ytlrxmkr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnqzz.top/Article/details/gt2uaoklofy.html

[N11] 二叉树中序遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2rdipzwpn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jlsjyb.cn/Article/details/gt2zfadpzjy.html

PHP:  // 手写递归函数
来源：http://dali.cucudq.cn/Article/details/gt2whgrqgyk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zyvuzuvc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gt2ogmuyknd.html

Java: // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gt2ukvayxdk.html

Go:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gt2kcgaxblu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.havefunace.top/Article/details/gt2kgmlqbfb.html

C#:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gt2fcbbdzyh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.dashuyun.cn/Article/details/gt2liwreogb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ydzc1.top/Article/details/gt2hpvqgoye.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shzxlz.cn/Article/details/gt2ktljdfnr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hfpthk.cn/Article/details/gt2bshjhsia.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gt2fblcvjnj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sweek.top/Article/details/gt2rtydueov.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oxhmqtmb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.birdmap.top/Article/details/gt2ywfdammf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gt2petjtyyb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2wmrfjlmd.html

O. 并发与异步
来源：http://dali.pycfn.com/Article/details/gt2mgjxlfud.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2dlzjlvqm.html

[O01] 启动一个线程
来源：http://dali.sufxvd.cn/Article/details/gt2wlplpfud.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.bjfxy.top/Article/details/gt2csgtknpz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuanzhike.top/Article/details/gt2fnguhyel.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.fzhhl.top/Article/details/gt2ofeamxop.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gt2lvndjhbx.html

Java: new Thread(() -> f()).start()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qfbwhtir.html

Go:   go f()
来源：http://dali.fengsongda.top/Article/details/gt2iidpuiat.html

Ruby: Thread.new { f }
来源：http://dali.xinyue.icu/Article/details/gt2unumauzv.html

C#:   Task.Run(() => F());
来源：http://dali.sxryk.cn/Article/details/gt2ocygylso.html

[O02] 使用线程池
来源：http://dali.pengpengdd.cyou/Article/details/gt2uixcauzl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.c1oappe.top/Article/details/gt2gonnbwbe.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.c1oappe.top/Article/details/gt2hyxsvhjh.html

JS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gt2kglqbabn.html

TS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gt2xcytbhyb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.iojbl.cn/Article/details/gt2uzndozcf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gsmurawi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuetiantiany.cn/Article/details/gt2hzeuahzf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tznfsxut.html

[O03] 加锁保护共享数据
来源：http://dali.shzxlz.cn/Article/details/gt2eukpczlf.html

Py:   with lock: shared += 1
来源：http://dali.yuxming.cn/Article/details/gt2vjushhng.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xinyue.icu/Article/details/gt2dgkyhviu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hammf.cn/Article/details/gt2muoikszc.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gt2drgpqxtd.html

Java: synchronized (this) { shared++; }
来源：http://dali.yonumen.top/Article/details/gt2tsiemfvz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hongshengwenyu.top/Article/details/gt2qqbtjfin.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gwctzamg.html

C#:   lock (gate) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ypelxozs.html

[O04] 定义异步函数并等待
来源：http://dali.hnqzz.top/Article/details/gt2louavpsr.html

Py:   async def f():⏎    await g()
来源：http://dali.shuidangran.top/Article/details/gt2mvzqqswf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.aizwys.cn/Article/details/gt2uhknerid.html

JS:   async function f() { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gt2tnyobstr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sweek.top/Article/details/gt2yuxuxrfa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yongpay.top/Article/details/gt2eaelfzxn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hfpthk.cn/Article/details/gt2gpushxym.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.9152youxi.cn/Article/details/gt2vwlgmbuu.html

C#:   async Task F() { await G(); }
来源：http://dali.cucudq.cn/Article/details/gt2lczbgfoa.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhoulong.xyz/Article/details/gt2mwywnmmo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhongyouzk.top/Article/details/gt2xpcrmwsk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iwnqqblo.html

JS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gt2lrogrpeh.html

TS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gt2joqqbdpn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nwbrower.top/Article/details/gt2exxurwhf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhixingplan.top/Article/details/gt2wvyyhcwp.html

Ruby: threads.map(&:join)
来源：http://dali.xziqi.cn/Article/details/gt2dopsinhb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.9152youxi.cn/Article/details/gt2avzgdefg.html

[O06] 使用进程池
来源：http://dali.ivvv.top/Article/details/gt2ooetluxd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.aibaodan.cn/Article/details/gt2voxaryaz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.quarkkingdee.top/Article/details/gt2zhjvouxw.html

JS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gt2inobzgvq.html

TS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gt2xrjkbvsn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yueranfly.top/Article/details/gt2hjycgaau.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gogol.net.cn/Article/details/gt2wsvkwyzi.html

Ruby: // fork 块
来源：http://dali.dashuyun.cn/Article/details/gt2fwgahsrh.html

C#:   Parallel.For
来源：http://dali.tianlin.xyz/Article/details/gt2haojscbt.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2wlmxtmzu.html

P. 常用工具函数
来源：http://dali.redwolf501.top/Article/details/gt2qjattsca.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2niaiwavn.html

[P01] 生成 UUID
来源：http://dali.xuetiantiany.cn/Article/details/gt2waaslljf.html

Py:   str(uuid.uuid4())
来源：http://dali.zhiwuduotai.top/Article/details/gt2lmptucmj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gogol.net.cn/Article/details/gt2gaosjkab.html

JS:   crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gt2qkyffcgm.html

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cojusxgl.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigfzy.top/Article/details/gt2phkdvevz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dzmscaui.html

Ruby: SecureRandom.uuid
来源：http://dali.ppjwa.cn/Article/details/gt2nkkklkzp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aibaodan.cn/Article/details/gt2yjysljon.html

[P02] MD5 / SHA256 摘要
来源：http://dali.snrcjt.cn/Article/details/gt2usymmvsd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.birdmap.top/Article/details/gt2uzujbakc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj202588.top/Article/details/gt2stbajoyr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ppjwa.cn/Article/details/gt2lejesxmf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.vqdsnc.cn/Article/details/gt2xpnupujd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.mhx1999.top/Article/details/gt2ayfliqvc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yueranfly.top/Article/details/gt2wxtoqwco.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sxryk.cn/Article/details/gt2aqguoeju.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bkinypar.html

[P03] 生成短随机字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2yjvxldmz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sweek.top/Article/details/gt2uskhpfdv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daria6918.cn/Article/details/gt2rdjhvmsu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gt2ixjoxlma.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ehwqpu.com/Article/details/gt2xfuuehdr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sxryk.cn/Article/details/gt2zdfbykny.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fzhhl.top/Article/details/gt2fsdgfodv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gogol.net.cn/Article/details/gt2cqyuzawh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daria6918.cn/Article/details/gt2izqezlnx.html

[P04] 求长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ixfiwcma.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tianlin.xyz/Article/details/gt2ctwosefk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gt2tlkuoerc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyauswz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.316326.xyz/Article/details/gt2bawggyra.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shzxlz.cn/Article/details/gt2ojfsuezh.html

Go:   len(arr);  len(m)
来源：http://dali.ehwqpu.com/Article/details/gt2srqgqjyn.html

Ruby: x.length;  x.size
来源：http://dali.tianlin.xyz/Article/details/gt2oqiknrgs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.dianchejie.cn/Article/details/gt2mpvargzx.html


<!-- 参考信息 -->