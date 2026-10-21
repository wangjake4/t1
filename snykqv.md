代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ydzc1.top/Article/details/gtgvvrgaqe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yueranfly.top/Article/details/gtjsswshkq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.guowangkeji.top/Article/details/gtehuifekb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxohjfhd.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjifsocnc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xylfe.cn/Article/details/gtdmfogzul.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqhbafby.html

JS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gtodbkjdkk.html

TS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gtmutkyine.html

Java: resp.statusCode()
来源：http://dali.mhx1999.top/Article/details/gtdrbmftkr.html

Go:   resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggzspzuh.html

Ruby: resp.code.to_i
来源：http://dali.yonumen.top/Article/details/gtczzlqpws.html

C#:   (int)resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gtgycxwtez.html

[L08] 并发请求多个地址
来源：http://dali.ppjwa.cn/Article/details/gtzuntyctp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgfzy.top/Article/details/gtbjshrvhl.html

PHP:  curl_multi_init() 系列
来源：http://dali.hongshengwenyu.top/Article/details/gtxjjzrfgg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gtnttdbqhw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gtswbhdojx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258.top/Article/details/gtmuxkqryp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.smart0.xyz/Article/details/gtmvqakqpx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.smart0.xyz/Article/details/gtmxfeafat.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.haohaochexian.top/Article/details/gtplvcsyaa.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtbunvdxzp.html

M. 命令行 / 进程 / 环境
来源：http://dali.shangyingyoupin.top/Article/details/gtrqdehfzv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gthvcewixe.html

[M01] 读取命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gtcpsummtk.html

Py:   sys.argv[1:]
来源：http://dali.cashguo.top/Article/details/gthraqddmu.html

PHP:  $argv;  $argc;
来源：http://dali.jqgufenzy.top/Article/details/gtrqhgjukw.html

JS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gtvxbalivr.html

TS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gthvwdggqk.html

Java: args 数组（main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gtwgytplri.html

Go:   os.Args[1:]
来源：http://dali.xinyue.icu/Article/details/gtgejxkwtw.html

Ruby: ARGV
来源：http://dali.cashguo.top/Article/details/gttixlbstv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gtxpwgcrdp.html

[M02] 读取环境变量
来源：http://dali.9152youxi.cn/Article/details/gtbadgsjtz.html

Py:   os.environ.get("HOME")
来源：http://dali.gzhubu.top/Article/details/gtiahrvfhy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gtxtuwvkqs.html

JS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gtsjhfetxi.html

TS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gthbvajfrp.html

Java: System.getenv("HOME")
来源：http://dali.guannengcc.top/Article/details/gtydqzfvtb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtysxbpbtu.html

Ruby: ENV["HOME"]
来源：http://dali.haohaochexian.top/Article/details/gtkccoglnb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtdorzszdh.html

[M03] 执行外部命令
来源：http://dali.jqgufenzy.top/Article/details/gtwxvqwpem.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tian-w.cn/Article/details/gtcdoiytkg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hongshengwenyu.top/Article/details/gtzdnkeoxf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gtqhkpkgrc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtpehhfkkp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhoulong.xyz/Article/details/gtdpnnbubs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tian-w.cn/Article/details/gtgcupcumf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sweek.top/Article/details/gtinpratag.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shangyingyoupin.top/Article/details/gtynyfdqnj.html

[M04] 获取当前工作目录
来源：http://dali.tian-w.cn/Article/details/gtzmzqwnuj.html

Py:   os.getcwd()
来源：http://dali.cqqwz.cn/Article/details/gtodcwefth.html

PHP:  getcwd();
来源：http://dali.zdqjudy.top/Article/details/gtsembhpso.html

JS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gttnmipchz.html

TS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gttaftrhpx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.meibo888.top/Article/details/gtcxllyput.html

Go:   os.Getwd()
来源：http://dali.snrcjt.cn/Article/details/gtydbyluvl.html

Ruby: Dir.pwd
来源：http://dali.jqgfzy.top/Article/details/gtkpocojsx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sxryk.cn/Article/details/gtyldypcbq.html

[M05] 设置退出码
来源：http://dali.sweek.top/Article/details/gtiifkpzgd.html

Py:   sys.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtcoirewxg.html

PHP:  exit(1);
来源：http://dali.jyoumei.cn/Article/details/gtfqdanfux.html

JS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtezgbczay.html

TS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gthuahxqur.html

Java: System.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtnewvkniw.html

Go:   os.Exit(1)
来源：http://dali.cdnleiting.top/Article/details/gttjwkoxpy.html

Ruby: exit 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxteqbbfa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigfzy.top/Article/details/gtyigrvhwm.html

[M06] 向标准错误输出
来源：http://dali.meibo888.top/Article/details/gtfuvoqvmo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gtwiakmzpe.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gthviasbpd.html

JS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtpzobtwwc.html

TS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtnhpmpzas.html

Java: System.err.println("err")
来源：http://dali.tianlin.xyz/Article/details/gtsdalgdhx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.svipenyu.cn/Article/details/gtgaugibeh.html

Ruby: warn "err"
来源：http://dali.jinqigufen.top/Article/details/gtpjspvstj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sweek.top/Article/details/gtydudjphp.html

[M07] 判断是否为主入口
来源：http://dali.yonumen.top/Article/details/gtwpiimsez.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gtsoybmyrb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.daxiang520.top/Article/details/gtatfxlbmf.html

JS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gtkfqljydo.html

TS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gtvzvgvvrn.html

Java: public static void main(String[] args)
来源：http://dali.hywenlv.cn/Article/details/gteknkaiws.html

Go:   func main()
来源：http://dali.zdqjudy.top/Article/details/gtfjuxiosu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.meibo888.top/Article/details/gtahnbgfgx.html

C#:   static void Main(string[] args)
来源：http://dali.cheryme.top/Article/details/gtspfybzlg.html

[M08] 获取系统与运行时信息
来源：http://dali.c1oappe.top/Article/details/gtrykajuxe.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yongpay.top/Article/details/gtgynvzcts.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gtdmdlkzyi.html

JS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gtmzfvrcbj.html

TS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gtvbbrjijy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258888.top/Article/details/gtwbeevvwe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.kuanghao11.cn/Article/details/gtyscibvrq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.andypj.xyz/Article/details/gttiexppwi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dashuyun.cn/Article/details/gtngthcmas.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtfudgiltr.html

N. 数据结构与算法
来源：http://dali.zhoulong.xyz/Article/details/gtmgpzsqlt.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtjdbmrnuj.html

[N01] 二分查找（有序数组）
来源：http://dali.0kj1m.cn/Article/details/gtjcmhyvrz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtlxzoqlnb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxinkj.top/Article/details/gttazrekkc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gtkmjhzdbw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gtiawantfv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gtsggrbhxj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtayanhblc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dashuyun.cn/Article/details/gtixvcllau.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtcmnxlwwy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.quarkkingdee.top/Article/details/gttkthpsgp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gtqcqpxplt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yvedp.cn/Article/details/gtmyjqriuc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gtlgfiivlo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtrcohmvjv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gtlzlqcbus.html

Go:   slices.Sort(arr)
来源：http://dali.wangdashe.top/Article/details/gtwqukdffk.html

Ruby: arr.sort
来源：http://dali.bjfxy.top/Article/details/gtjbyaullp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.birdmap.top/Article/details/gtvokqhbjc.html

[N03] 快速排序（分治示例）
来源：http://dali.ppjwa.cn/Article/details/gtqqgvihnx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gogol.net.cn/Article/details/gtmxsebkap.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zdqjudy.top/Article/details/gtvuysassd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shzxlz.cn/Article/details/gttptbdxaq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shuidangran.top/Article/details/gthjwfesav.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.0kj1m.cn/Article/details/gtqayqooai.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cucudq.cn/Article/details/gtmupyiqxp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yonumen.top/Article/details/gtcbhhqnyr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.snrcjt.cn/Article/details/gtbpuedifr.html

[N04] 斐波那契数列
来源：http://dali.zhoulong.xyz/Article/details/gtzfpdxkkj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtzhajbpgv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gtvvanmmft.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtgvcbbhlf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtpaimlapp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gtpjwethpz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258888.top/Article/details/gtbcehssbz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gogol.net.cn/Article/details/gtigvabkxc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtgmanwyya.html

[N05] 最大公约数
来源：http://dali.ivvv.top/Article/details/gtjpyffvyf.html

Py:   math.gcd(a, b)
来源：http://dali.mhx1999.top/Article/details/gtpmduhird.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gogol.net.cn/Article/details/gtmruvjpoe.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gtteghwkrw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtzbxjrpzi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.9152youxi.cn/Article/details/gtctjdpfqa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.andypj.xyz/Article/details/gtycqutjyi.html

Ruby: a.gcd(b)
来源：http://dali.nwbrower.top/Article/details/gtyfqzcldh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nanxuanxn.top/Article/details/gttlcgwuke.html

[N06] 判断回文字符串
来源：http://dali.jqgufenzy.top/Article/details/gtoahtrscj.html

Py:   s == s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gtzkxyaisc.html

PHP:  $s === strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gtppdzymen.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtvnebckuu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtvrlncgqg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ybcxt.top/Article/details/gtiuylltxd.html

Go:   // 双指针从两端比较
来源：http://dali.sysykeji.top/Article/details/gtvdmyborx.html

Ruby: s == s.reverse
来源：http://dali.xinyue.icu/Article/details/gtiknkxqim.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gtzadhkcki.html

[N07] 两数之和（返回下标）
来源：http://dali.shuidangran.top/Article/details/gtopovphlq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jyoumei.cn/Article/details/gtrowcholt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnqzz.top/Article/details/gtgvmgdfny.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cdnleiting.top/Article/details/gtdchqlscs.html

TS:   // 手写 Map<string, number>
来源：http://dali.xylfe.cn/Article/details/gtbcgzbjvq.html

Java: // 手写 HashMap
来源：http://dali.yj20258888.top/Article/details/gtdebjpfiw.html

Go:   // 手写 map[int]int
来源：http://dali.xziqi.cn/Article/details/gtvkrkxqfv.html

Ruby: // 手写 Hash
来源：http://dali.ywan-chungtsiang.top/Article/details/gtblhpmoyr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aizwys.cn/Article/details/gtmztzvuic.html

[N08] 生成全排列
来源：http://dali.ivvv.top/Article/details/gtwcagvtqn.html

Py:   itertools.permutations(arr)
来源：http://dali.jianghu66.top/Article/details/gtqkekbiqc.html

PHP:  // 手写递归交换
来源：http://dali.sweek.top/Article/details/gtndyvapyl.html

JS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtqjzqjuyi.html

TS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtuugenlhm.html

Java: // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtfzeeokjb.html

Go:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtjnhowexc.html

Ruby: arr.permutation.to_a
来源：http://dali.gotoacloud.top/Article/details/gtbjqemzee.html

C#:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtjltemtup.html

[N09] 栈与队列
来源：http://dali.smart0.xyz/Article/details/gtaqmhztlu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cashguo.top/Article/details/gtwuurrtcd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtlrfjsrxz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gtzolfkvum.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aizwys.cn/Article/details/gtemjncvtu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hysaishi.cn/Article/details/gtqtygkkub.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gaohongyu789.top/Article/details/gtafewrpcb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gtaiehdocn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sxryk.cn/Article/details/gtvfycnzbt.html

[N10] 链表节点定义
来源：http://dali.shzxlz.cn/Article/details/gtxulngkkf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.havefunace.top/Article/details/gtmcqqqavl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.svipenyu.cn/Article/details/gtnlvhkmbz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.quarkkingdee.top/Article/details/gtdnihtejk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhengqikj.top/Article/details/gtsqzlwkwy.html

Java: class Node { int v; Node next; }
来源：http://dali.andypj.xyz/Article/details/gtxrqjyrtd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.birdmap.top/Article/details/gtiuebbjsa.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zdqjudy.top/Article/details/gtuwmhfnrm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.c1oappe.top/Article/details/gtpiunvuqj.html

[N11] 二叉树中序遍历
来源：http://dali.yanxiufei.cn/Article/details/gtptzhsghn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sysykeji.top/Article/details/gtpctwctmi.html

PHP:  // 手写递归函数
来源：http://dali.meibo888.top/Article/details/gtmpeiiefu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gtxxaacujh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gtvprcdkge.html

Java: // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gtrbvfxjdy.html

Go:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtbwuuzroq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sxryk.cn/Article/details/gtxqrpzjov.html

C#:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gtxzhpsnpc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ybcxt.top/Article/details/gtpjccihzi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqpynorz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnxiangtu.top/Article/details/gtmnzgffkx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gtupenelpl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtekmpcafa.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzzxhnms.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ppjwa.cn/Article/details/gthoanhkop.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258888.top/Article/details/gtihrdxksc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gtlzsfrqel.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtbvodsdgk.html

O. 并发与异步
来源：http://dali.yonumen.top/Article/details/gtiipyewlg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtpzjbxgal.html

[O01] 启动一个线程
来源：http://dali.tianlin.xyz/Article/details/gtwvozsmrl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ivvv.top/Article/details/gtsjfsdusp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gotoacloud.top/Article/details/gtnmirdrsw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.feifeiyinyue.top/Article/details/gtryzzayqi.html

TS:   // 同 JS
来源：http://dali.iojbl.cn/Article/details/gtuomrnorz.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhiwuduotai.top/Article/details/gthldayxez.html

Go:   go f()
来源：http://dali.haohaochexian.top/Article/details/gttzhpeplw.html

Ruby: Thread.new { f }
来源：http://dali.nanxinkj.top/Article/details/gtqwmhvsnc.html

C#:   Task.Run(() => F());
来源：http://dali.haohaochexian.top/Article/details/gtcihaadqj.html

[O02] 使用线程池
来源：http://dali.vqdsnc.cn/Article/details/gtqqmvdffn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqssrgtlf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jianghu66.top/Article/details/gtjltwragp.html

JS:   // worker_threads 线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtzwcxjktl.html

TS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gtveqyawyj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cucudq.cn/Article/details/gtutfuuxrm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hammf.cn/Article/details/gtvsrtuicj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shuidangran.top/Article/details/gtpjljaoae.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shangyingyoupin.top/Article/details/gtafvxxdgh.html

[O03] 加锁保护共享数据
来源：http://dali.xinyue.icu/Article/details/gtcxuzurzi.html

Py:   with lock: shared += 1
来源：http://dali.xuetiantiany.cn/Article/details/gtblmsnhjo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sufxvd.cn/Article/details/gteqwklsfe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258888.top/Article/details/gtcwpeowhj.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gtpfjoegaz.html

Java: synchronized (this) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gtkvhizfam.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hammf.cn/Article/details/gtukmgibcx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guowangkeji.top/Article/details/gtmalhjxlh.html

C#:   lock (gate) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gtxbxomqqg.html

[O04] 定义异步函数并等待
来源：http://dali.hnxiangtu.top/Article/details/gtvvcqubdm.html

Py:   async def f():⏎    await g()
来源：http://dali.zycfv.cn/Article/details/gtyfbrzrxj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258888.top/Article/details/gtyqqxdagq.html

JS:   async function f() { await g(); }
来源：http://dali.redwolf501.top/Article/details/gtocpofmdc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.guannengcc.top/Article/details/gtbubooaxx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sweek.top/Article/details/gtamjvhgto.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gotoacloud.top/Article/details/gtqoafwdbk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigufen.top/Article/details/gtwzczwhlw.html

C#:   async Task F() { await G(); }
来源：http://dali.daria6918.cn/Article/details/gtamvifcoi.html

[O05] 并发执行并等待全部完成
来源：http://dali.ydzc1.top/Article/details/gtxtelwffw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gtomaqibus.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xinyue.icu/Article/details/gthinfofjx.html

JS:   await Promise.all(tasks)
来源：http://dali.yonumen.top/Article/details/gtylpyyqqv.html

TS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtdctpqqng.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj202588.top/Article/details/gtxsmkgbiq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.snrcjt.cn/Article/details/gtmhuifnlq.html

Ruby: threads.map(&:join)
来源：http://dali.jqgfzy.top/Article/details/gtzyyaohjn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hysaishi.cn/Article/details/gtimttqpux.html

[O06] 使用进程池
来源：http://dali.cashguo.top/Article/details/gthrydcxoj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhongyouzk.top/Article/details/gtrzzoymgs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.smart0.xyz/Article/details/gtwnhyeomm.html

JS:   // child_process / cluster 模块
来源：http://dali.pengpengdd.cyou/Article/details/gtaxgikihc.html

TS:   // child_process / cluster 模块
来源：http://dali.chenzaomai.com/Article/details/gtkgvjzgwn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ehwqpu.com/Article/details/gtjmanpsvg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangdashe.top/Article/details/gtbwnllzlo.html

Ruby: // fork 块
来源：http://dali.tianlin.xyz/Article/details/gtayapalvq.html

C#:   Parallel.For
来源：http://dali.xuanzx.com/Article/details/gtiftdqlrn.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtbvadsnmf.html

P. 常用工具函数
来源：http://dali.tanke756.top/Article/details/gtbyskhlvq.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtnqneqwrs.html

[P01] 生成 UUID
来源：http://dali.tanke756.top/Article/details/gtpgttwwvc.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258888.top/Article/details/gttcpvxnfa.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yongpay.top/Article/details/gtbkvwgdnr.html

JS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtzazznnrx.html

TS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gtnfivmllj.html

Java: UUID.randomUUID().toString()
来源：http://dali.jianghu66.top/Article/details/gtpqeyuubt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nwbrower.top/Article/details/gtswjcqbql.html

Ruby: SecureRandom.uuid
来源：http://dali.ppjwa.cn/Article/details/gtzhoqfskh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gotoacloud.top/Article/details/gtqdxazfxb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shzxlz.cn/Article/details/gtdhhcbjau.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.feifeiyinyue.top/Article/details/gtitnwnoqu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gotoacloud.top/Article/details/gtkjltnhzq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jiagoushi.top/Article/details/gtteeonehj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cqqwz.cn/Article/details/gtiekmzxlm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gteqvfvrxi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gogol.net.cn/Article/details/gtotpzptsn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yvedp.cn/Article/details/gtmvhcduzm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.c1oappe.top/Article/details/gtciiyxfje.html

[P03] 生成短随机字符串
来源：http://dali.hnxiangtu.top/Article/details/gtwgjpzmai.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtraykkzes.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ehwqpu.com/Article/details/gtrghohmoz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.svipenyu.cn/Article/details/gtxkjueolh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtuanzqmzs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.9152youxi.cn/Article/details/gtiafjkqvg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cqqwz.cn/Article/details/gtiyrmzjud.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hysaishi.cn/Article/details/gtncxdbsgj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.andypj.xyz/Article/details/gtasnqkyfi.html

[P04] 求长度
来源：http://dali.xuetiantiany.cn/Article/details/gtmoxxyxnh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.snrcjt.cn/Article/details/gtplgnbxtj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtixokzmrh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gtrxjkdsda.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gtlgjnbgme.html


<!-- 参考信息 -->