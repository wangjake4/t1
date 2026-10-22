代发 wailian999

Py:   resp.json()
来源：http://dali.iojbl.cn/Article/details/gtvqbihyne.html

PHP:  json_decode($body, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtfkzravgm.html

JS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtkxlvoaba.html

TS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gtrxnirosg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gttspzkmwy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgfzy.top/Article/details/gthxodonaq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbuhiwewc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gotoacloud.top/Article/details/gtwnpffnvz.html

[L07] 处理 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gthvhnunke.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgfzy.top/Article/details/gtootsriml.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jiagoushi.top/Article/details/gtxtzbhjlm.html

JS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gtweosyjmp.html

TS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gtntfborbj.html

Java: resp.statusCode()
来源：http://dali.wangshuangyany.cn/Article/details/gtmqveslhv.html

Go:   resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gtjbezuxou.html

Ruby: resp.code.to_i
来源：http://dali.nwbrower.top/Article/details/gtcxncgtcu.html

C#:   (int)resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gtwfnneslp.html

[L08] 并发请求多个地址
来源：http://dali.cqqwz.cn/Article/details/gtierxlmhx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jyoumei.cn/Article/details/gtvvdlqahx.html

PHP:  curl_multi_init() 系列
来源：http://dali.gaohongyu789.top/Article/details/gtjrrtfosh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gtpzczjwxn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtfaswkquc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangdashe.top/Article/details/gtfhmvkrre.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ybcxt.top/Article/details/gtivdptvey.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aizwys.cn/Article/details/gtsynegzes.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gtjrkpnurn.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtzkykumgm.html

M. 命令行 / 进程 / 环境
来源：http://dali.iojbl.cn/Article/details/gteztqrzub.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtdrhhlkbk.html

[M01] 读取命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gtlorlgmbu.html

Py:   sys.argv[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtkfklvptr.html

PHP:  $argv;  $argc;
来源：http://dali.jqgufenzy.top/Article/details/gttakanaeu.html

JS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtlcugzypv.html

TS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gtddmmgxis.html

Java: args 数组（main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gtkazdzhjr.html

Go:   os.Args[1:]
来源：http://dali.nanxuanxn.top/Article/details/gtcgkvagkk.html

Ruby: ARGV
来源：http://dali.shanyushiyangtech.top/Article/details/gtaireofvj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtvlyredla.html

[M02] 读取环境变量
来源：http://dali.ydzc1.top/Article/details/gteghziyss.html

Py:   os.environ.get("HOME")
来源：http://dali.yongpay.top/Article/details/gtwvjysgro.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gtjybyrgyj.html

JS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gtcleiyvbd.html

TS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gtnhrnjpjw.html

Java: System.getenv("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtnhzulzzv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtregdmhgu.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258888.top/Article/details/gthraiicsh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtrwhlyhgp.html

[M03] 执行外部命令
来源：http://dali.aizwys.cn/Article/details/gtuivuxsux.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sxryk.cn/Article/details/gtweccemxx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cheryme.top/Article/details/gtpmwmoasc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gtpwxvmaho.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gtnsvymiln.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xinyue.icu/Article/details/gtmmpbrskk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shangyingyoupin.top/Article/details/gtwjcoturm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.bjfxy.top/Article/details/gtauyijijp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gtjpfzjyyl.html

[M04] 获取当前工作目录
来源：http://dali.zycfv.cn/Article/details/gturcfkoyg.html

Py:   os.getcwd()
来源：http://dali.fzhhl.top/Article/details/gtxrtnxcrm.html

PHP:  getcwd();
来源：http://dali.cheryme.top/Article/details/gtqeirxnyp.html

JS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gtulerlpxw.html

TS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gtbnjmkdcf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yueranfly.top/Article/details/gtjxvwgxxt.html

Go:   os.Getwd()
来源：http://dali.andypj.xyz/Article/details/gttgtazwps.html

Ruby: Dir.pwd
来源：http://dali.havefunace.top/Article/details/gtgfacsvdv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.c1oappe.top/Article/details/gtvtstgcvs.html

[M05] 设置退出码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcptttrjf.html

Py:   sys.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtjkvopqeu.html

PHP:  exit(1);
来源：http://dali.gotoacloud.top/Article/details/gthmjtbldr.html

JS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gttqtlhkmn.html

TS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtmxrvzept.html

Java: System.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtnhyiwzge.html

Go:   os.Exit(1)
来源：http://dali.wangdashe.top/Article/details/gtoqywhsol.html

Ruby: exit 1
来源：http://dali.xuanzx.com/Article/details/gtvqruwtva.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shzxlz.cn/Article/details/gtffjrtvwk.html

[M06] 向标准错误输出
来源：http://dali.sxryk.cn/Article/details/gtjqvnweit.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnaudmuc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pycfn.com/Article/details/gtygwdmocq.html

JS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtnzlncxkk.html

TS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gthqbzcwjq.html

Java: System.err.println("err")
来源：http://dali.xylfe.cn/Article/details/gtbsqsbogj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.316326.xyz/Article/details/gtlsnwbmau.html

Ruby: warn "err"
来源：http://dali.mhx1999.top/Article/details/gtsytipfsh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.bjfxy.top/Article/details/gtecpmlfxd.html

[M07] 判断是否为主入口
来源：http://dali.yonumen.top/Article/details/gtglvqggba.html

Py:   if __name__ == "__main__":
来源：http://dali.yonumen.top/Article/details/gtmmyoxthr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.haohaochexian.top/Article/details/gtjxsghjni.html

JS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gthccsfjiy.html

TS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gtqkxyfhmc.html

Java: public static void main(String[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gtjaaxeayu.html

Go:   func main()
来源：http://dali.wangdashe.top/Article/details/gtwfsxbtwq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ppjwa.cn/Article/details/gtbaqawbma.html

C#:   static void Main(string[] args)
来源：http://dali.ppjwa.cn/Article/details/gtrtolvobl.html

[M08] 获取系统与运行时信息
来源：http://dali.sweek.top/Article/details/gtqfjzltpl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hfpthk.cn/Article/details/gtumuwazpb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.0kj1m.cn/Article/details/gtmgaiysns.html

JS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gtixmolzno.html

TS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gteuczlmhc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.9152youxi.cn/Article/details/gttqnrjxvf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daria6918.cn/Article/details/gtwzgadqeh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fzhhl.top/Article/details/gtbbckgdku.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258.top/Article/details/gtoxxzazfy.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtwbpaivar.html

N. 数据结构与算法
来源：http://dali.yj20258.top/Article/details/gthrbntyiv.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtsmcqhlpl.html

[N01] 二分查找（有序数组）
来源：http://dali.zhengqikj.top/Article/details/gtzpzeikuk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtjcilkzms.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.havefunace.top/Article/details/gtlxaybcku.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yueranfly.top/Article/details/gtrpswuabp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtjlarmuuz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gtpxvzeyzo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtvveykpis.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuanzhike.top/Article/details/gtviqpmise.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtjekigorl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ivvv.top/Article/details/gtgxowkgrl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gtkpofdvkv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuanzx.com/Article/details/gtxtrglspt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gtutnoyvsg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtsfqmbaos.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sxryk.cn/Article/details/gtnyahkzjx.html

Go:   slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gtssyykxix.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gtazpbstas.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dianchejie.cn/Article/details/gtomvlxxre.html

[N03] 快速排序（分治示例）
来源：http://dali.aizwys.cn/Article/details/gtfdizlope.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinghuilouyu.cn/Article/details/gtgurqzbju.html

PHP:  // 递归实现，或用 usort
来源：http://dali.0kj1m.cn/Article/details/gtwzzjzupb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gtqlokkoav.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gtvxkftlub.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ydzc1.top/Article/details/gtatjcmxmu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.smart0.xyz/Article/details/gtwhrofvfm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jianghu66.top/Article/details/gteutrurrm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yvedp.cn/Article/details/gtoozgsbji.html

[N04] 斐波那契数列
来源：http://dali.daxiang520.top/Article/details/gtokjmdmpk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gtldufbrxs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gtvxfbhlzs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gthvvdxmvb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtkuhseqej.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gtjujhqelj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gtdewindlp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjenplgww.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgeeiupay.html

[N05] 最大公约数
来源：http://dali.yuanzhike.top/Article/details/gtvendcdry.html

Py:   math.gcd(a, b)
来源：http://dali.xylfe.cn/Article/details/gtmoqmbpax.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xziqi.cn/Article/details/gtspznfkya.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gturmtpygg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnqzz.top/Article/details/gtrwdhkkjo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhjdpbqd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.haohaochexian.top/Article/details/gtriqycjhp.html

Ruby: a.gcd(b)
来源：http://dali.hammf.cn/Article/details/gtufvzirto.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuxming.cn/Article/details/gtuxctqggy.html

[N06] 判断回文字符串
来源：http://dali.redwolf501.top/Article/details/gttkzeasit.html

Py:   s == s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gtggmksxkv.html

PHP:  $s === strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gtzmfwpaul.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtnmfgtapo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtdhpxszda.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xinyue.icu/Article/details/gtdrinlahn.html

Go:   // 双指针从两端比较
来源：http://dali.fzhhl.top/Article/details/gtomdsknko.html

Ruby: s == s.reverse
来源：http://dali.yj20258.top/Article/details/gtqclbsbtk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zycfv.cn/Article/details/gtybowpyub.html

[N07] 两数之和（返回下标）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakyvjydf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hywenlv.cn/Article/details/gtnnkgmant.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yongpay.top/Article/details/gtoqszmnlb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258888.top/Article/details/gtfvtmpckj.html

TS:   // 手写 Map<string, number>
来源：http://dali.hongshengwenyu.top/Article/details/gthshykdpc.html

Java: // 手写 HashMap
来源：http://dali.ydzc1.top/Article/details/gtqpuhobii.html

Go:   // 手写 map[int]int
来源：http://dali.gotoacloud.top/Article/details/gtabqhlfjd.html

Ruby: // 手写 Hash
来源：http://dali.andypj.xyz/Article/details/gtiehtcaxq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gtincurmte.html

[N08] 生成全排列
来源：http://dali.sysykeji.top/Article/details/gtboyvkvkr.html

Py:   itertools.permutations(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtrjsocaoj.html

PHP:  // 手写递归交换
来源：http://dali.snrcjt.cn/Article/details/gttktdmvze.html

JS:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtbeqtvxlm.html

TS:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtwjbghqcp.html

Java: // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtxpljamrn.html

Go:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzppwczto.html

Ruby: arr.permutation.to_a
来源：http://dali.yangfankeji.com/Article/details/gtfyymvlsu.html

C#:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtsfztuexy.html

[N09] 栈与队列
来源：http://dali.yonumen.top/Article/details/gtayoburhp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtyurigdlq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtlcoluvkc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtrezwegdj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdutfkqd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenzaomai.com/Article/details/gtktuxrhkp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xziqi.cn/Article/details/gtqzdaqyaq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtxtowpeon.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gthgdbbfeo.html

[N10] 链表节点定义
来源：http://dali.jinqigfzy.top/Article/details/gtfhivkgdc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tian-w.cn/Article/details/gtjszabxzd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgfzy.top/Article/details/gtulmkethh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sufxvd.cn/Article/details/gtrfxmwosm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yueranfly.top/Article/details/gtuolfqyyv.html

Java: class Node { int v; Node next; }
来源：http://dali.jyoumei.cn/Article/details/gtxagmpqxk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cheryme.top/Article/details/gtmtzuznvz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.snrcjt.cn/Article/details/gtmspiiqre.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.c1oappe.top/Article/details/gtkbxthmvv.html

[N11] 二叉树中序遍历
来源：http://dali.ybcxt.top/Article/details/gtnnzjlpis.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daxiang520.top/Article/details/gtlfmdewmv.html

PHP:  // 手写递归函数
来源：http://dali.gzhubu.top/Article/details/gtcdofplvy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gtwizrjioz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmwcruzy.html

Java: // 手写递归
来源：http://dali.tian-w.cn/Article/details/gtfplpczhd.html

Go:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtysiacjsz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gotoacloud.top/Article/details/gtfzavnxii.html

C#:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gtpefnzjak.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.316326.xyz/Article/details/gtsrvmowap.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnqzz.top/Article/details/gtptzxrsjk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhiwuduotai.top/Article/details/gtjxyvpbie.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gtgkzfqcug.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhnivmec.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtsrvxxgzd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cdnleiting.top/Article/details/gtcuygchan.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.mhx1999.top/Article/details/gtucmnlxej.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gtxyfefwiz.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtcpmdkdhd.html

O. 并发与异步
来源：http://dali.shuidangran.top/Article/details/gtfdidlroi.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtfpvjefop.html

[O01] 启动一个线程
来源：http://dali.chenzaomai.com/Article/details/gtsdpgwida.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nwbrower.top/Article/details/gtgzmgawly.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xinyue.icu/Article/details/gtcmlpgnwo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yonumen.top/Article/details/gtsbqicocz.html

TS:   // 同 JS
来源：http://dali.jlsjyb.cn/Article/details/gtnibdxyhn.html

Java: new Thread(() -> f()).start()
来源：http://dali.nwbrower.top/Article/details/gtsdshmcmg.html

Go:   go f()
来源：http://dali.feifeiyinyue.top/Article/details/gtchsdrozr.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvdjmbxc.html

C#:   Task.Run(() => F());
来源：http://dali.xylfe.cn/Article/details/gttbkkukfj.html

[O02] 使用线程池
来源：http://dali.316326.xyz/Article/details/gtbhdzbona.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhongyouzk.top/Article/details/gtctwgytaf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tian-w.cn/Article/details/gteirkacea.html

JS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtxzocrvql.html

TS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gtpnykwsci.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.snrcjt.cn/Article/details/gtwyxnhkdd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tianlin.xyz/Article/details/gtqdktumss.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pycfn.com/Article/details/gtzxvlyquo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aibaodan.cn/Article/details/gtjnvqujdr.html

[O03] 加锁保护共享数据
来源：http://dali.fengsongda.top/Article/details/gtdocmlmxl.html

Py:   with lock: shared += 1
来源：http://dali.zhiwuduotai.top/Article/details/gtuopvfnux.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.iojbl.cn/Article/details/gtuvrovbju.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jyoumei.cn/Article/details/gtbohykvwd.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gthytedtiz.html

Java: synchronized (this) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gtfotoazho.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cdnleiting.top/Article/details/gtzfjycwem.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxuanxn.top/Article/details/gtugtvvrzu.html

C#:   lock (gate) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gtbnevjxss.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gtteifhvll.html

Py:   async def f():⏎    await g()
来源：http://dali.ybcxt.top/Article/details/gthkysibjt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cdnleiting.top/Article/details/gtsbmtbokb.html

JS:   async function f() { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gtaqwejqoi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xinyue.icu/Article/details/gtxcdzlzxb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sxryk.cn/Article/details/gtkzuaxuxt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tianlin.xyz/Article/details/gtenyajkon.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sysykeji.top/Article/details/gtnrdkcfqf.html

C#:   async Task F() { await G(); }
来源：http://dali.tian-w.cn/Article/details/gtfuvnryrm.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenjidiqi.icu/Article/details/gtyozmkbff.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shuidangran.top/Article/details/gtikclgspc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangdashe.top/Article/details/gtmigrtfjz.html

JS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gtbggotzfd.html

TS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtccmnuulz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sysykeji.top/Article/details/gtnbmmfmos.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.snrcjt.cn/Article/details/gtcutuyoby.html

Ruby: threads.map(&:join)
来源：http://dali.xziqi.cn/Article/details/gtomwaojoe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.svipenyu.cn/Article/details/gtxxgdwbjd.html

[O06] 使用进程池
来源：http://dali.gaohongyu789.top/Article/details/gtgmyqzuug.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsbxuwhl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenjidiqi.icu/Article/details/gtwhcbumjd.html

JS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gtbgjvlfcu.html

TS:   // child_process / cluster 模块
来源：http://dali.daria6918.cn/Article/details/gtjjmckdoa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxuanxn.top/Article/details/gtljvxbial.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yongpay.top/Article/details/gtzvkkjhfu.html

Ruby: // fork 块
来源：http://dali.ppjwa.cn/Article/details/gtpbtjiins.html

C#:   Parallel.For
来源：http://dali.tian-w.cn/Article/details/gtjosjlucb.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtxjdtatml.html

P. 常用工具函数
来源：http://dali.ybcxt.top/Article/details/gttlpnbgwv.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtfobzcddf.html

[P01] 生成 UUID
来源：http://dali.iojbl.cn/Article/details/gthcuamuov.html

Py:   str(uuid.uuid4())
来源：http://dali.ydzc1.top/Article/details/gtkqoxpzqj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.mhx1999.top/Article/details/gtoabzxlul.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtzeeafsnq.html

TS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtmganrrvj.html

Java: UUID.randomUUID().toString()
来源：http://dali.yonumen.top/Article/details/gtadrclhqm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jlsjyb.cn/Article/details/gtkcuucsdt.html

Ruby: SecureRandom.uuid
来源：http://dali.smart0.xyz/Article/details/gtdbmliboc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ybcxt.top/Article/details/gtecgmodin.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nwbrower.top/Article/details/gtlselbiyy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hongshengwenyu.top/Article/details/gtbeuxauil.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqpinlph.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yangfankeji.com/Article/details/gtbhlqgfwi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guannengcc.top/Article/details/gtqwmbogvf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrznmomyt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ppjwa.cn/Article/details/gtsqgvufok.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaootrevv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.c1oappe.top/Article/details/gtcvqxgeqo.html

[P03] 生成短随机字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtwogsuggb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tian-w.cn/Article/details/gtxgahezgg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xuetiantiany.cn/Article/details/gtvyubppta.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gtudotjchx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtfpgzakvn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gtcvanidqh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fengsongda.top/Article/details/gtepnhdeda.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.fzhhl.top/Article/details/gtyewlklbi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.quarkkingdee.top/Article/details/gttqrkzmcj.html

[P04] 求长度
来源：http://dali.sufxvd.cn/Article/details/gtvxcfavfj.html


<!-- 参考信息 -->