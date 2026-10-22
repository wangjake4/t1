代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtqxkallmm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aizwys.cn/Article/details/gtfcaqujrf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gotoacloud.top/Article/details/gtehodfldg.html

JS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gtdegrswvt.html

TS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gttqkuvvlp.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gtoboedkfg.html

Go:   resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gtosefovko.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gtgcwfqqwx.html

C#:   (int)resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gttejztfqx.html

[L08] 并发请求多个地址
来源：http://dali.pengpengdd.cyou/Article/details/gtfkgcqcvw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhongyouzk.top/Article/details/gtqhfnhzdw.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj202588.top/Article/details/gtxyastceo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gtnuphpgul.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtqypysgax.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fengsongda.top/Article/details/gtublcouqx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhoulong.xyz/Article/details/gthohgumvp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.iojbl.cn/Article/details/gtfnpzjcgp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sweek.top/Article/details/gtegcyglqg.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtglolchim.html

M. 命令行 / 进程 / 环境
来源：http://dali.hysaishi.cn/Article/details/gtmplinhof.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtqbimpxrj.html

[M01] 读取命令行参数
来源：http://dali.cheryme.top/Article/details/gtsbgchgjk.html

Py:   sys.argv[1:]
来源：http://dali.yonumen.top/Article/details/gteczkyxkw.html

PHP:  $argv;  $argc;
来源：http://dali.havefunace.top/Article/details/gtpgabgvpz.html

JS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gtqnwnqvdn.html

TS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gtwldwtvfb.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gttpzmbkyy.html

Go:   os.Args[1:]
来源：http://dali.dianchejie.cn/Article/details/gtikrsjkrl.html

Ruby: ARGV
来源：http://dali.gzhubu.top/Article/details/gtgqnnzofg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gtbmubltzw.html

[M02] 读取环境变量
来源：http://dali.zycfv.cn/Article/details/gthcakxmzc.html

Py:   os.environ.get("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtnnivfjqq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtcsmoooag.html

JS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtoeoyvkww.html

TS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gtasiasyio.html

Java: System.getenv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtzkljqoaq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tanke756.top/Article/details/gtvzvgiudg.html

Ruby: ENV["HOME"]
来源：http://dali.xuanzx.com/Article/details/gtyylaltlf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gttempttwn.html

[M03] 执行外部命令
来源：http://dali.jlsjyb.cn/Article/details/gtutwttiix.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aibaodan.cn/Article/details/gtdtxfjmkg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhoulong.xyz/Article/details/gtafhxulvf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gtvfeloqfp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gthxpztlaw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.316326.xyz/Article/details/gtxopmqgbb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhengqikj.top/Article/details/gtxpxrjkqh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.havefunace.top/Article/details/gtiajbtlhc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.0kj1m.cn/Article/details/gtuusjmelg.html

[M04] 获取当前工作目录
来源：http://dali.vqdsnc.cn/Article/details/gtavpgwicb.html

Py:   os.getcwd()
来源：http://dali.guannengcc.top/Article/details/gtjaymgpod.html

PHP:  getcwd();
来源：http://dali.yj202588.top/Article/details/gtncsjminw.html

JS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gtbhgmrqpy.html

TS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gtxbcrtlsq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258.top/Article/details/gtxfkiykao.html

Go:   os.Getwd()
来源：http://dali.birdmap.top/Article/details/gteosmokin.html

Ruby: Dir.pwd
来源：http://dali.fzhhl.top/Article/details/gtyxdfhyfc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangdashe.top/Article/details/gtssdvsfga.html

[M05] 设置退出码
来源：http://dali.yonumen.top/Article/details/gtmvxanezh.html

Py:   sys.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtehwgyyad.html

PHP:  exit(1);
来源：http://dali.kuanghao11.cn/Article/details/gtbprmbcly.html

JS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtbeckhckk.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtsetomoqs.html

Java: System.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtecxbxdmy.html

Go:   os.Exit(1)
来源：http://dali.hnqzz.top/Article/details/gtgenlhcvi.html

Ruby: exit 1
来源：http://dali.shangyingyoupin.top/Article/details/gtiunmobtk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlecjsni.html

[M06] 向标准错误输出
来源：http://dali.yuxming.cn/Article/details/gtilaofpan.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gtzymbtmsx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxinkj.top/Article/details/gtkdxbtigw.html

JS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtkbswrgxb.html

TS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gtvwlkeysk.html

Java: System.err.println("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtxtktpdkf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hywenlv.cn/Article/details/gtqvwajcss.html

Ruby: warn "err"
来源：http://dali.ydzc1.top/Article/details/gtvthrrqfj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxuanxn.top/Article/details/gtespzireu.html

[M07] 判断是否为主入口
来源：http://dali.tianlin.xyz/Article/details/gthuvqfmty.html

Py:   if __name__ == "__main__":
来源：http://dali.daria6918.cn/Article/details/gtggbpmseo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gtzkxghzzb.html

JS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gtejedpejf.html

TS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gtruwdbdun.html

Java: public static void main(String[] args)
来源：http://dali.zhengqikj.top/Article/details/gtnjxourpn.html

Go:   func main()
来源：http://dali.guowangkeji.top/Article/details/gtrlypuqtx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnxiangtu.top/Article/details/gtvjbtnbjl.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258888.top/Article/details/gtxuwshugz.html

[M08] 获取系统与运行时信息
来源：http://dali.redwolf501.top/Article/details/gtafkrunra.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gzhubu.top/Article/details/gtvjbgwvdj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hysaishi.cn/Article/details/gthgacsbif.html

JS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gtlfuxntrv.html

TS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gtamsdusvq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hysaishi.cn/Article/details/gtiyirvvop.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258.top/Article/details/gtwasmyxns.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.0kj1m.cn/Article/details/gtxuzthgvs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ppjwa.cn/Article/details/gtfojwwiqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtkauwcgsw.html

N. 数据结构与算法
来源：http://dali.ppjwa.cn/Article/details/gtzlvuyllw.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtngbbjuen.html

[N01] 二分查找（有序数组）
来源：http://dali.shuidangran.top/Article/details/gtostxilhs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtecpnhdex.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gzhubu.top/Article/details/gtzvcsblsb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gtrwvbnyhb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsnyfdei.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtnjwicdbi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.birdmap.top/Article/details/gtfwcdbfhp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gaohongyu789.top/Article/details/gtkcplguhm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtakfebufm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pengpengdd.cyou/Article/details/gtdpgnhdqs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gtzujzmbbn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigufen.top/Article/details/gttpszkcca.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gtznufyeqn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gthauelcvq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jianghu66.top/Article/details/gtcabdznrb.html

Go:   slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gtlfstrulr.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gtjhwdphqe.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.havefunace.top/Article/details/gtzkpnqbaj.html

[N03] 快速排序（分治示例）
来源：http://dali.shangyingyoupin.top/Article/details/gtnrnmkfgj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sufxvd.cn/Article/details/gtwojgjhon.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sufxvd.cn/Article/details/gtjecbyphr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gthwqpcdqm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gtdfugtyou.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtiguqfllb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sysykeji.top/Article/details/gtvsstdgiw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhengqikj.top/Article/details/gtkaqabtiy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigufen.top/Article/details/gtgnkamxfi.html

[N04] 斐波那契数列
来源：http://dali.sweek.top/Article/details/gtrvbsyfka.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpaitzfp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuanzx.com/Article/details/gtvhtaywaw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtplzffbqd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gtkkurxnij.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrusdoxh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258888.top/Article/details/gtrpfmixfe.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltjrsyjq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gtlrcbmfea.html

[N05] 最大公约数
来源：http://dali.hfpthk.cn/Article/details/gtoxqaefkj.html

Py:   math.gcd(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtjkklfyzg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daria6918.cn/Article/details/gtfcvdyrfu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpyfypucp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.meibo888.top/Article/details/gttspphugv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnqzz.top/Article/details/gtykzcozef.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.iojbl.cn/Article/details/gtgvjhhbog.html

Ruby: a.gcd(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtwfmdwmpb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xinyue.icu/Article/details/gtwchpqjun.html

[N06] 判断回文字符串
来源：http://dali.xylfe.cn/Article/details/gtpnaydcwc.html

Py:   s == s[::-1]
来源：http://dali.yj20258888.top/Article/details/gtsosvuvsw.html

PHP:  $s === strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtfvcmgmph.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtlvskhtyl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gtqgwwqjhb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhongyouzk.top/Article/details/gtdwkrwfyg.html

Go:   // 双指针从两端比较
来源：http://dali.yj20258888.top/Article/details/gtoavtscum.html

Ruby: s == s.reverse
来源：http://dali.chenlongwang.top/Article/details/gtwrqqaamg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gtbvqggqtz.html

[N07] 两数之和（返回下标）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpifaahsb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tian-w.cn/Article/details/gtlrcrbise.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pycfn.com/Article/details/gtlaqxeuyo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daxiang520.top/Article/details/gtpgjunqoe.html

TS:   // 手写 Map<string, number>
来源：http://dali.vqdsnc.cn/Article/details/gtmszmjtzj.html

Java: // 手写 HashMap
来源：http://dali.birdmap.top/Article/details/gtaqtckbvw.html

Go:   // 手写 map[int]int
来源：http://dali.xinyue.icu/Article/details/gtdmfhkgup.html

Ruby: // 手写 Hash
来源：http://dali.yueranfly.top/Article/details/gtmraatvhz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guowangkeji.top/Article/details/gtgpfewyhl.html

[N08] 生成全排列
来源：http://dali.quarkkingdee.top/Article/details/gtxfktlsuj.html

Py:   itertools.permutations(arr)
来源：http://dali.cucudq.cn/Article/details/gtntykfprj.html

PHP:  // 手写递归交换
来源：http://dali.c1oappe.top/Article/details/gtpoapohrc.html

JS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtrqkoenyz.html

TS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gthhykzeik.html

Java: // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtknszahsx.html

Go:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtofjpysbi.html

Ruby: arr.permutation.to_a
来源：http://dali.svipenyu.cn/Article/details/gtfnxilcyx.html

C#:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtimxkhqab.html

[N09] 栈与队列
来源：http://dali.xylfe.cn/Article/details/gtgjqhzjvl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtlazybnqc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtuzeihrzl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtuwgzjued.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dashuyun.cn/Article/details/gtlmlohmoz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jyoumei.cn/Article/details/gtqozxhcxy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangshuangyany.cn/Article/details/gtuvtaxklg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtczbzmmyl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tianlin.xyz/Article/details/gtdyflkiws.html

[N10] 链表节点定义
来源：http://dali.chenzaomai.com/Article/details/gtpgoulont.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sufxvd.cn/Article/details/gtsscmsqoj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.wangdashe.top/Article/details/gtxlydymvm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.kuanghao11.cn/Article/details/gtovgepthr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhongyouzk.top/Article/details/gtwtsroreb.html

Java: class Node { int v; Node next; }
来源：http://dali.tianlin.xyz/Article/details/gtzwcbajcu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.quarkkingdee.top/Article/details/gtvlzthtgo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dianchejie.cn/Article/details/gtqwhtguoi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cucudq.cn/Article/details/gtoyrlwshh.html

[N11] 二叉树中序遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwbagaeuw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aizwys.cn/Article/details/gtzmqeyhae.html

PHP:  // 手写递归函数
来源：http://dali.fzhhl.top/Article/details/gtpzqfjywz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj202588.top/Article/details/gtkslendfl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gtjhrzutsj.html

Java: // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtdtzqpnmk.html

Go:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtdpclmwkc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cdnleiting.top/Article/details/gtrkdbazyp.html

C#:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gtdkpjjrro.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.kuanghao11.cn/Article/details/gtmledahdj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jiagoushi.top/Article/details/gtwosnxvdt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenlongwang.top/Article/details/gtrhjpfydn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gtihvzkunz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gtnuolxefv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gtqdgdfalh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenjidiqi.icu/Article/details/gtotnuhxjh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtgscamxaz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zdqjudy.top/Article/details/gtrcatuyji.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtazhjpatq.html

O. 并发与异步
来源：http://dali.dashuyun.cn/Article/details/gtkuqtqueg.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gttbfkacht.html

[O01] 启动一个线程
来源：http://dali.tanke756.top/Article/details/gtfuqcxopy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xylfe.cn/Article/details/gtdcdsxiei.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.svipenyu.cn/Article/details/gthxabrjnt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ivvv.top/Article/details/gtifrfyapq.html

TS:   // 同 JS
来源：http://dali.chenzaomai.com/Article/details/gtjtbpable.html

Java: new Thread(() -> f()).start()
来源：http://dali.jyoumei.cn/Article/details/gtoaysucjd.html

Go:   go f()
来源：http://dali.daxiang520.top/Article/details/gtqrizgcpq.html

Ruby: Thread.new { f }
来源：http://dali.bjfxy.top/Article/details/gtenghvayl.html

C#:   Task.Run(() => F());
来源：http://dali.guannengcc.top/Article/details/gtzhmoyggl.html

[O02] 使用线程池
来源：http://dali.gaohongyu789.top/Article/details/gtgfyixojm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.andypj.xyz/Article/details/gtwyhbreob.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhengqikj.top/Article/details/gtmhuqhfdk.html

JS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gtmjaywvjf.html

TS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gtimpojfpa.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenjidiqi.icu/Article/details/gtlayhugjq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.iojbl.cn/Article/details/gtlaogjcng.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.haohaochexian.top/Article/details/gtzeaiwiwr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenlongwang.top/Article/details/gtjqsybixx.html

[O03] 加锁保护共享数据
来源：http://dali.daria6918.cn/Article/details/gtzouqoxbu.html

Py:   with lock: shared += 1
来源：http://dali.aibaodan.cn/Article/details/gtwlujcawz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hfpthk.cn/Article/details/gtfuhariyv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yvedp.cn/Article/details/gtjitosxmu.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gtmwkfjjqd.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gtbneoazcl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.bjfxy.top/Article/details/gtostebsjv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ehwqpu.com/Article/details/gtlzkvqxzs.html

C#:   lock (gate) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gtlcqbrlfw.html

[O04] 定义异步函数并等待
来源：http://dali.gaohongyu789.top/Article/details/gtvvjbbazw.html

Py:   async def f():⏎    await g()
来源：http://dali.jlsjyb.cn/Article/details/gtulnoenkn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuanzhike.top/Article/details/gthqnpsirp.html

JS:   async function f() { await g(); }
来源：http://dali.yueranfly.top/Article/details/gtchtlqbro.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gtdsxgkhvy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangdashe.top/Article/details/gtxlrnysfw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.aibaodan.cn/Article/details/gtzyccmalx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yonumen.top/Article/details/gtsqvkxjej.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258888.top/Article/details/gtmckotygh.html

[O05] 并发执行并等待全部完成
来源：http://dali.hnqzz.top/Article/details/gtvaztoexx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.aizwys.cn/Article/details/gtiwuutqyi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sxryk.cn/Article/details/gthbqviijn.html

JS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsadevid.html

TS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gtgjbhuoao.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jyoumei.cn/Article/details/gtoqhnlhjs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxktynjm.html

Ruby: threads.map(&:join)
来源：http://dali.yuanzhike.top/Article/details/gtfevuxdug.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnqzz.top/Article/details/gtdcnkyacb.html

[O06] 使用进程池
来源：http://dali.0kj1m.cn/Article/details/gtqjmqalqi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zycfv.cn/Article/details/gtyenvzrwq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ivvv.top/Article/details/gtossnwail.html

JS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gtnfdvnimd.html

TS:   // child_process / cluster 模块
来源：http://dali.hongshengwenyu.top/Article/details/gtzncslqwa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hysaishi.cn/Article/details/gtghwrrfhl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yueranfly.top/Article/details/gtvxvyxnaj.html

Ruby: // fork 块
来源：http://dali.yongpay.top/Article/details/gtsmkmseqh.html

C#:   Parallel.For
来源：http://dali.jyoumei.cn/Article/details/gtyukkkpwh.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtmbwkvgaq.html

P. 常用工具函数
来源：http://dali.snrcjt.cn/Article/details/gtjyobucck.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtkvitdxeu.html

[P01] 生成 UUID
来源：http://dali.daxiang520.top/Article/details/gtlhiotgzm.html

Py:   str(uuid.uuid4())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnxtndqm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xinyue.icu/Article/details/gtzvjyizdg.html

JS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtrthqttag.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gtukiqvsdu.html

Java: UUID.randomUUID().toString()
来源：http://dali.hfpthk.cn/Article/details/gtnqluzzvz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dianchejie.cn/Article/details/gtgpespqie.html

Ruby: SecureRandom.uuid
来源：http://dali.gogol.net.cn/Article/details/gtcmoaefve.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tian-w.cn/Article/details/gtcaimpate.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigufen.top/Article/details/gtxwjbidnb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xziqi.cn/Article/details/gtimzkygpd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fengsongda.top/Article/details/gtsomobuyt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sxryk.cn/Article/details/gtokhbujiq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cqqwz.cn/Article/details/gtbfwkpvgc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zycfv.cn/Article/details/gtuikfgqty.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.iojbl.cn/Article/details/gtyfamuqjh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhongyouzk.top/Article/details/gthfapxyrz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.fengsongda.top/Article/details/gthezitgpf.html

[P03] 生成短随机字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtdndbiqtg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuetiantiany.cn/Article/details/gtrqikwreq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hysaishi.cn/Article/details/gttviomdpg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtfldzuejb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gtrfitiibb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenzaomai.com/Article/details/gtolzxkkac.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarywylty.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jqgufenzy.top/Article/details/gtvdfbpxwy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tianlin.xyz/Article/details/gtkzxofsoq.html

[P04] 求长度
来源：http://dali.cdnleiting.top/Article/details/gtownlqxju.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258.top/Article/details/gthzvtalwb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtbcykxwgl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gtvlcimnxo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gtltsahprn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sweek.top/Article/details/gtkjrudvwp.html

Go:   len(arr);  len(m)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaijgarpo.html

Ruby: x.length;  x.size
来源：http://dali.gogol.net.cn/Article/details/gtsaptvcei.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gtjtyzswje.html


<!-- 参考信息 -->