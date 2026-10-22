代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtoikaofaf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhixingplan.top/Article/details/gtvpnctprc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cheryme.top/Article/details/gtbabtjudi.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtwmzgiqtw.html

TS:   resp.ok;  resp.status
来源：http://dali.hnxiangtu.top/Article/details/gtpgpcrqif.html

Java: resp.statusCode()
来源：http://dali.xylfe.cn/Article/details/gtmhyqonzm.html

Go:   resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gtamcdfzss.html

Ruby: resp.code.to_i
来源：http://dali.chenjidiqi.icu/Article/details/gtbhuazcgg.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gtppddckmh.html

[L08] 并发请求多个地址
来源：http://dali.dashuyun.cn/Article/details/gtgedmgweo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnqzz.top/Article/details/gtdwjjubtb.html

PHP:  curl_multi_init() 系列
来源：http://dali.iojbl.cn/Article/details/gtkzymepyb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtzbprzfuj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gtuzmmgxjn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsyfdjmk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ydzc1.top/Article/details/gtxphtdqcl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jqgufenzy.top/Article/details/gtvyzhmhjd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hywenlv.cn/Article/details/gttsjjzowy.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtpnzlaqhn.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuetiantiany.cn/Article/details/gtwuemysbq.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtridufyhf.html

[M01] 读取命令行参数
来源：http://dali.chenzaomai.com/Article/details/gtdonvgeij.html

Py:   sys.argv[1:]
来源：http://dali.ehwqpu.com/Article/details/gtqdmtwbxe.html

PHP:  $argv;  $argc;
来源：http://dali.cdnleiting.top/Article/details/gtnemyjewb.html

JS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtietsmwra.html

TS:   process.argv.slice(2)
来源：http://dali.sysykeji.top/Article/details/gtmfdayzct.html

Java: args 数组（main 方法参数）
来源：http://dali.birdmap.top/Article/details/gtmwfoppnm.html

Go:   os.Args[1:]
来源：http://dali.svipenyu.cn/Article/details/gtwplegytk.html

Ruby: ARGV
来源：http://dali.zhiwuduotai.top/Article/details/gtnszivbqf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gtytjtjxxa.html

[M02] 读取环境变量
来源：http://dali.xylfe.cn/Article/details/gttouyeoea.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtxowmihaa.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gtncnmdmhp.html

JS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gtkcopnuwp.html

TS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtynygnzhs.html

Java: System.getenv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtvgymtopj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtyfceqauh.html

Ruby: ENV["HOME"]
来源：http://dali.xylfe.cn/Article/details/gttvmljyrg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cheryme.top/Article/details/gtezqemycy.html

[M03] 执行外部命令
来源：http://dali.ybcxt.top/Article/details/gtsehqaimq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsyylbnvr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aibaodan.cn/Article/details/gttjdxhzmw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gtsgsnewko.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgljaphq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dashuyun.cn/Article/details/gtztulupeg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fengsongda.top/Article/details/gtpolmdyiv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aibaodan.cn/Article/details/gturpbroes.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aibaodan.cn/Article/details/gtlqycyudf.html

[M04] 获取当前工作目录
来源：http://dali.nanxinkj.top/Article/details/gtgsqkbdgj.html

Py:   os.getcwd()
来源：http://dali.hammf.cn/Article/details/gtlimmxgfi.html

PHP:  getcwd();
来源：http://dali.ppjwa.cn/Article/details/gtflfupcpy.html

JS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gtwiiwkydi.html

TS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gtspfucvgi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gtqrmdixfa.html

Go:   os.Getwd()
来源：http://dali.zdqjudy.top/Article/details/gttiaqhohg.html

Ruby: Dir.pwd
来源：http://dali.ybcxt.top/Article/details/gtnaijlyht.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigfzy.top/Article/details/gtlexctsgl.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gttlbslyrq.html

Py:   sys.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtssyyfgbc.html

PHP:  exit(1);
来源：http://dali.xuanzx.com/Article/details/gtmkcfpjee.html

JS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtykdvhdta.html

TS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtxbzimrcx.html

Java: System.exit(1)
来源：http://dali.xinyue.icu/Article/details/gthcgjallu.html

Go:   os.Exit(1)
来源：http://dali.xuanzx.com/Article/details/gtcmgquhal.html

Ruby: exit 1
来源：http://dali.quarkkingdee.top/Article/details/gtbdlvunbs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjklbjfv.html

[M06] 向标准错误输出
来源：http://dali.yj20258888.top/Article/details/gtpgletseq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gtrbsqvkzl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangshuangyany.cn/Article/details/gthntusqzt.html

JS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gtdcuvnmii.html

TS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gtvgfxaavj.html

Java: System.err.println("err")
来源：http://dali.gaohongyu789.top/Article/details/gtmwprdqqx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlyrjdkjc.html

Ruby: warn "err"
来源：http://dali.hysaishi.cn/Article/details/gtixkyyydj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtoolfxbrf.html

[M07] 判断是否为主入口
来源：http://dali.zhengqikj.top/Article/details/gtiokeoazb.html

Py:   if __name__ == "__main__":
来源：http://dali.feifeiyinyue.top/Article/details/gtjkqwfxnl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gzhubu.top/Article/details/gtlwbkxncq.html

JS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gtdptblysi.html

TS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gttgppctub.html

Java: public static void main(String[] args)
来源：http://dali.kuanghao11.cn/Article/details/gtqfoivooh.html

Go:   func main()
来源：http://dali.yj202588.top/Article/details/gtwsncbdhj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aibaodan.cn/Article/details/gtuyakaqof.html

C#:   static void Main(string[] args)
来源：http://dali.nwbrower.top/Article/details/gteznlnlso.html

[M08] 获取系统与运行时信息
来源：http://dali.haohaochexian.top/Article/details/gtskbxqile.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zdqjudy.top/Article/details/gtrjtmvmta.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hammf.cn/Article/details/gtvgyhpuzx.html

JS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gtpvouonue.html

TS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gtcrzcfigj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hywenlv.cn/Article/details/gtlwsyavut.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pengpengdd.cyou/Article/details/gtgyygiosb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gogol.net.cn/Article/details/gtycnvoomn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuxming.cn/Article/details/gtplkdtpjk.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtkwagfixn.html

N. 数据结构与算法
来源：http://dali.yj202588.top/Article/details/gtczrcgbiy.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtgzncsitz.html

[N01] 二分查找（有序数组）
来源：http://dali.yuanzhike.top/Article/details/gtttfwodki.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gttdsacjya.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cucudq.cn/Article/details/gtiyobydbn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gtfvcjcfwk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtxtgcnzts.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtsrjygpvt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtbfjdswqu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cashguo.top/Article/details/gtuddhqros.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtnmrixqjb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258888.top/Article/details/gtryiqkcco.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gtrvjvlvqd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.0kj1m.cn/Article/details/gtxrhlexsy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gtfcodshyx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtjwcuzgmy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigufen.top/Article/details/gtrrusdore.html

Go:   slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gtzxjrldic.html

Ruby: arr.sort
来源：http://dali.yj20258888.top/Article/details/gtpyamvchw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shzxlz.cn/Article/details/gtojxbrgkb.html

[N03] 快速排序（分治示例）
来源：http://dali.tian-w.cn/Article/details/gtrmxqkmlb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuanzhike.top/Article/details/gtcvzjgsig.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xylfe.cn/Article/details/gtipygpfjp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zdqjudy.top/Article/details/gtydfcqyoi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gtcmziwltp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jyoumei.cn/Article/details/gtliomyrdq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj202588.top/Article/details/gtlpczwjkn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jlsjyb.cn/Article/details/gtoxwzymtm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigufen.top/Article/details/gtvpycsmna.html

[N04] 斐波那契数列
来源：http://dali.yangfankeji.com/Article/details/gtvkgxuoqf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.mhx1999.top/Article/details/gtwrkpbeop.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zycfv.cn/Article/details/gtmvftmwrg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtpwnrktnp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gtmzhmfhfp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gtcwxmutmj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yonumen.top/Article/details/gtjitxrvmf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gtulyrthjo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gttqftznnn.html

[N05] 最大公约数
来源：http://dali.jinqigfzy.top/Article/details/gtbxckkrgs.html

Py:   math.gcd(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtanxnnbgw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dianchejie.cn/Article/details/gtqlrfazfh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gttitnhdru.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gtikwebhvp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhoulong.xyz/Article/details/gtffygkrou.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yangfankeji.com/Article/details/gtmsoteyxc.html

Ruby: a.gcd(b)
来源：http://dali.zdqjudy.top/Article/details/gtagzhdikj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gtkuxizliq.html

[N06] 判断回文字符串
来源：http://dali.sufxvd.cn/Article/details/gtvikazymz.html

Py:   s == s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gtabixpjhm.html

PHP:  $s === strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gthkotxeif.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtempyvylb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqcdwofi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangtech.top/Article/details/gtmaimrxlj.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gtjmdnjitn.html

Ruby: s == s.reverse
来源：http://dali.guannengcc.top/Article/details/gtmzhsfntq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gtvxoggioo.html

[N07] 两数之和（返回下标）
来源：http://dali.yj202588.top/Article/details/gtvmwtzfsc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.iojbl.cn/Article/details/gtrgpmjxsx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sysykeji.top/Article/details/gtgdqbdmxh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.snrcjt.cn/Article/details/gtanxqteml.html

TS:   // 手写 Map<string, number>
来源：http://dali.daria6918.cn/Article/details/gtpolmwouq.html

Java: // 手写 HashMap
来源：http://dali.shzxlz.cn/Article/details/gtxexlyavw.html

Go:   // 手写 map[int]int
来源：http://dali.sysykeji.top/Article/details/gtuccbptto.html

Ruby: // 手写 Hash
来源：http://dali.redwolf501.top/Article/details/gttilirffj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgfzy.top/Article/details/gtkhteheen.html

[N08] 生成全排列
来源：http://dali.hammf.cn/Article/details/gtplfpxeax.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtyfrcjpgb.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gtqisbsbpb.html

JS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtjdxfbczq.html

TS:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtocazqrin.html

Java: // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtmjvgshph.html

Go:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcyfrwqa.html

Ruby: arr.permutation.to_a
来源：http://dali.aibaodan.cn/Article/details/gthpzwgfod.html

C#:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtutmumxse.html

[N09] 栈与队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdskmqrtq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.meibo888.top/Article/details/gtqvqqobow.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtjfcwniik.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtvzncnbcx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.quarkkingdee.top/Article/details/gtmbajxxou.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cdnleiting.top/Article/details/gtuauakyns.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhengqikj.top/Article/details/gtwknpuesx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtnocrlgkm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhoulong.xyz/Article/details/gtjabvzpdl.html

[N10] 链表节点定义
来源：http://dali.zhiwuduotai.top/Article/details/gteiyjrqzr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nanxinkj.top/Article/details/gtmqjrajll.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hongshengwenyu.top/Article/details/gtlsudfezx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.iojbl.cn/Article/details/gtsihukhtp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.0kj1m.cn/Article/details/gtzqlrgejx.html

Java: class Node { int v; Node next; }
来源：http://dali.haohaochexian.top/Article/details/gttiuufxlv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhiwuduotai.top/Article/details/gtcqedjuhd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gzhubu.top/Article/details/gtehwrgtnx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yanxiufei.cn/Article/details/gtbqyervmw.html

[N11] 二叉树中序遍历
来源：http://dali.tian-w.cn/Article/details/gtsikswigy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.smart0.xyz/Article/details/gtuehqotem.html

PHP:  // 手写递归函数
来源：http://dali.cheryme.top/Article/details/gtyeccjrqh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gtzopnzeyu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhixingplan.top/Article/details/gtymhzdwxd.html

Java: // 手写递归
来源：http://dali.sweek.top/Article/details/gttpkcgcgn.html

Go:   // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gtwllsjlnp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hfpthk.cn/Article/details/gttytopfuj.html

C#:   // 手写递归
来源：http://dali.redwolf501.top/Article/details/gtbdciygjg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangdashe.top/Article/details/gtftvsrlig.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojdvkzwr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shuidangran.top/Article/details/gtaljfvowb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hfpthk.cn/Article/details/gtlcvxqbfa.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gaohongyu789.top/Article/details/gtbcecfwlb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gtngsgebid.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yanxiufei.cn/Article/details/gtiizgbtsd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aibaodan.cn/Article/details/gtcrrtrxny.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gtgqdgihmi.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtsweiqzkk.html

O. 并发与异步
来源：http://dali.ydzc1.top/Article/details/gttsvdomsu.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtnhrkkwoa.html

[O01] 启动一个线程
来源：http://dali.yuanzhike.top/Article/details/gtjiyubrgb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.0kj1m.cn/Article/details/gtkvvbqrxk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenzaomai.com/Article/details/gtriiidwuk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuetiantiany.cn/Article/details/gtdsssebbn.html

TS:   // 同 JS
来源：http://dali.c1oappe.top/Article/details/gtukcmveqh.html

Java: new Thread(() -> f()).start()
来源：http://dali.xziqi.cn/Article/details/gtbnstqtzs.html

Go:   go f()
来源：http://dali.zhiwuduotai.top/Article/details/gtrvzpvvfg.html

Ruby: Thread.new { f }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwudqvksi.html

C#:   Task.Run(() => F());
来源：http://dali.zhiwuduotai.top/Article/details/gtbjpwnlrp.html

[O02] 使用线程池
来源：http://dali.jiagoushi.top/Article/details/gtwhebowuh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.c1oappe.top/Article/details/gtpetzhhtb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.pycfn.com/Article/details/gtvmhupvms.html

JS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtkfvapoco.html

TS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gtcvnrlbry.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangdashe.top/Article/details/gtgemodcbt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.svipenyu.cn/Article/details/gtexphtzag.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jlsjyb.cn/Article/details/gtaxlanhub.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ehwqpu.com/Article/details/gtalmdiewk.html

[O03] 加锁保护共享数据
来源：http://dali.mhx1999.top/Article/details/gtjagtjhzd.html

Py:   with lock: shared += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrunvsww.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinyuanbaomall.cn/Article/details/gteajtyjhi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shuidangran.top/Article/details/gtjqyzzxel.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gtjpqsfiue.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gtyrmqtdue.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tian-w.cn/Article/details/gtgemymjlb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuxming.cn/Article/details/gtwfumjtsb.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrceiirmh.html

[O04] 定义异步函数并等待
来源：http://dali.guowangkeji.top/Article/details/gtdimyeorm.html

Py:   async def f():⏎    await g()
来源：http://dali.c1oappe.top/Article/details/gtrxwdwtqt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pycfn.com/Article/details/gtsbrsgocq.html

JS:   async function f() { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgjrfatx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gtducezmdw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhixingplan.top/Article/details/gtmxozugar.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.bjfxy.top/Article/details/gtxnfdyfjs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xylfe.cn/Article/details/gtccsirdga.html

C#:   async Task F() { await G(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwqmfbyr.html

[O05] 并发执行并等待全部完成
来源：http://dali.tian-w.cn/Article/details/gtachxcnji.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtsitugzgp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cashguo.top/Article/details/gtjjdqcvtu.html

JS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gtiofagqgj.html

TS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gtxgxsvluk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.meibo888.top/Article/details/gtdzvubbek.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xuetiantiany.cn/Article/details/gtdytrgbhn.html

Ruby: threads.map(&:join)
来源：http://dali.sxryk.cn/Article/details/gtrerltccs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cdnleiting.top/Article/details/gtaufuyydg.html

[O06] 使用进程池
来源：http://dali.aibaodan.cn/Article/details/gtmalfcmkk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.mhx1999.top/Article/details/gtgushrfbw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangdashe.top/Article/details/gtybihiczk.html

JS:   // child_process / cluster 模块
来源：http://dali.xziqi.cn/Article/details/gtizuegipr.html

TS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gttpddisrc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cucudq.cn/Article/details/gtewmfxibu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.havefunace.top/Article/details/gtuxjybocp.html

Ruby: // fork 块
来源：http://dali.sufxvd.cn/Article/details/gthtcddqzq.html

C#:   Parallel.For
来源：http://dali.gzhubu.top/Article/details/gtbseainsu.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtledzenwf.html

P. 常用工具函数
来源：http://dali.sufxvd.cn/Article/details/gtgbgbxitb.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtajknyule.html

[P01] 生成 UUID
来源：http://dali.cashguo.top/Article/details/gtbrcrigdm.html

Py:   str(uuid.uuid4())
来源：http://dali.chenzaomai.com/Article/details/gtokhxrxvd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtigbeaygy.html

JS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtbgqaerpz.html

TS:   crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gtchjmuvyv.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigfzy.top/Article/details/gtjcjugeuj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigfzy.top/Article/details/gtavmcxiri.html

Ruby: SecureRandom.uuid
来源：http://dali.birdmap.top/Article/details/gtqbmsqpdi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhiwuduotai.top/Article/details/gtarazccfy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.haohaochexian.top/Article/details/gtffbwqjkv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigufen.top/Article/details/gtiugjyzoo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gogol.net.cn/Article/details/gtvlcnsvok.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.316326.xyz/Article/details/gttbcneirp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fzhhl.top/Article/details/gtglickjyj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtioqarrwv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxinkj.top/Article/details/gtrkhpepqk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuanzhike.top/Article/details/gtihqsmnno.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.havefunace.top/Article/details/gtwmjwaozd.html

[P03] 生成短随机字符串
来源：http://dali.xuanzx.com/Article/details/gtuserrsnn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guowangkeji.top/Article/details/gtrqbwqyhd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenlongwang.top/Article/details/gtgxcggkmb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gtthzyzyur.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xinyue.icu/Article/details/gthbstztpq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhoulong.xyz/Article/details/gtnygznjwx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xylfe.cn/Article/details/gtmgrodpkr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sysykeji.top/Article/details/gtzurcdbww.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdsjxnvq.html

[P04] 求长度
来源：http://dali.chenzaomai.com/Article/details/gtabbkgwet.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenlongwang.top/Article/details/gtuxnmmzkn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtabhwovod.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gtrrpldjll.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gtiteltlpe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxinkj.top/Article/details/gtuugnehhm.html

Go:   len(arr);  len(m)
来源：http://dali.gogol.net.cn/Article/details/gtuuhvoqbq.html

Ruby: x.length;  x.size
来源：http://dali.hongshengwenyu.top/Article/details/gtogrcgmfb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.aibaodan.cn/Article/details/gtmnzofujn.html


<!-- 参考信息 -->