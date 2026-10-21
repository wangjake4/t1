代发 wailian999

Py:   resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gtgcdpnapd.html

PHP:  json_decode($body, true);
来源：http://dali.jiagoushi.top/Article/details/gtvvywrhoc.html

JS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdiikjiep.html

TS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtjflsyljk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.smart0.xyz/Article/details/gtsphblemf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jlsjyb.cn/Article/details/gtspingvff.html

Ruby: JSON.parse(resp.body)
来源：http://dali.pengpengdd.cyou/Article/details/gtqphwttqz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ydzc1.top/Article/details/gtdefbkdjs.html

[L07] 处理 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gtuxqdaiia.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnxiangtu.top/Article/details/gthhusbfau.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daxiang520.top/Article/details/gtmykvakzq.html

JS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gtrwcjjmzx.html

TS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gthqqmiobo.html

Java: resp.statusCode()
来源：http://dali.sufxvd.cn/Article/details/gtgcgkjvkm.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gtogyhlynf.html

Ruby: resp.code.to_i
来源：http://dali.aibaodan.cn/Article/details/gtpynhezzn.html

C#:   (int)resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gtdqawmrxo.html

[L08] 并发请求多个地址
来源：http://dali.ppjwa.cn/Article/details/gtzozdxngv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.0kj1m.cn/Article/details/gtbqabuogh.html

PHP:  curl_multi_init() 系列
来源：http://dali.haohaochexian.top/Article/details/gtichblgyl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gtjwkfqhxd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gtuabzjmav.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gtpmicqwuc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guannengcc.top/Article/details/gtmsjiuqsn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtogzeoahz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhsywqyf.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtgcfrsgzg.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangshuangyany.cn/Article/details/gtwydsypqr.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtqsbyqdia.html

[M01] 读取命令行参数
来源：http://dali.xuanzx.com/Article/details/gtgojpjvvd.html

Py:   sys.argv[1:]
来源：http://dali.c1oappe.top/Article/details/gterdfazdu.html

PHP:  $argv;  $argc;
来源：http://dali.chenzaomai.com/Article/details/gtibcajvkf.html

JS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gtkcvdwpeq.html

TS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gtpjlblksg.html

Java: args 数组（main 方法参数）
来源：http://dali.cashguo.top/Article/details/gthvpfktac.html

Go:   os.Args[1:]
来源：http://dali.cdnleiting.top/Article/details/gtqrvvznem.html

Ruby: ARGV
来源：http://dali.gzhubu.top/Article/details/gtwrsnblfc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gtotsdcmmx.html

[M02] 读取环境变量
来源：http://dali.fzhhl.top/Article/details/gtdakcitlb.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtnuhoiepx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gtxvkiojin.html

JS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gtgtjhmcbv.html

TS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gtzhgmsqxo.html

Java: System.getenv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtujcrobys.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pycfn.com/Article/details/gtjltohiyw.html

Ruby: ENV["HOME"]
来源：http://dali.pengpengdd.cyou/Article/details/gtohsqinuz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftebszhz.html

[M03] 执行外部命令
来源：http://dali.chenzaomai.com/Article/details/gtqqvrizih.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shzxlz.cn/Article/details/gtpxgnoqlb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhvxmeeg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gtfmdgiufb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gtvyxesmgn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tianlin.xyz/Article/details/gtirzpynde.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuanzhike.top/Article/details/gtalzhfobo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcvryxik.html

C#:   Process.Start("ls", "-l");
来源：http://dali.9152youxi.cn/Article/details/gtzmsemvhf.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhgxswco.html

Py:   os.getcwd()
来源：http://dali.ydzc1.top/Article/details/gtceyolkta.html

PHP:  getcwd();
来源：http://dali.ppjwa.cn/Article/details/gtuhocisih.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gtpgyrexlr.html

TS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gtsgtsiann.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.bjfxy.top/Article/details/gtotflgmxr.html

Go:   os.Getwd()
来源：http://dali.bjfxy.top/Article/details/gtzoeutaqj.html

Ruby: Dir.pwd
来源：http://dali.vqdsnc.cn/Article/details/gtwxoqghmj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xylfe.cn/Article/details/gttirpquxe.html

[M05] 设置退出码
来源：http://dali.vqdsnc.cn/Article/details/gtujdmvpsd.html

Py:   sys.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtxudevwjj.html

PHP:  exit(1);
来源：http://dali.zhengqikj.top/Article/details/gtibrdayxh.html

JS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtjbkrctiv.html

TS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtggpkwhsk.html

Java: System.exit(1)
来源：http://dali.yj20258.top/Article/details/gtadpqdpsk.html

Go:   os.Exit(1)
来源：http://dali.havefunace.top/Article/details/gtbqcqwjbo.html

Ruby: exit 1
来源：http://dali.mhx1999.top/Article/details/gteiubgjzb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ivvv.top/Article/details/gtzkbqsrqq.html

[M06] 向标准错误输出
来源：http://dali.hongshengwenyu.top/Article/details/gtqibwvpcy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gtfnqcvppf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daria6918.cn/Article/details/gtnbjoorbi.html

JS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gtitaxsvzn.html

TS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gtirezvtmk.html

Java: System.err.println("err")
来源：http://dali.xylfe.cn/Article/details/gtlkqfxzgw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangshuangyany.cn/Article/details/gtpdxjjtqv.html

Ruby: warn "err"
来源：http://dali.svipenyu.cn/Article/details/gtogdxhiji.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dashuyun.cn/Article/details/gtrmqdnssg.html

[M07] 判断是否为主入口
来源：http://dali.ivvv.top/Article/details/gtlzkvxhqe.html

Py:   if __name__ == "__main__":
来源：http://dali.dashuyun.cn/Article/details/gtakotsjbq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dashuyun.cn/Article/details/gtcrhmsbkf.html

JS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gtufinfvzw.html

TS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gteuaqpvsa.html

Java: public static void main(String[] args)
来源：http://dali.yuxming.cn/Article/details/gtgrobbndv.html

Go:   func main()
来源：http://dali.jianghu66.top/Article/details/gtbstlzezo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jlsjyb.cn/Article/details/gtimmfhmvu.html

C#:   static void Main(string[] args)
来源：http://dali.cheryme.top/Article/details/gtdrlqchfd.html

[M08] 获取系统与运行时信息
来源：http://dali.chenlongwang.top/Article/details/gttzweplwh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yonumen.top/Article/details/gtufdkuqhn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenzaomai.com/Article/details/gtnuisiqxv.html

JS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gtfsgicyed.html

TS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtombczurk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gotoacloud.top/Article/details/gtekwwxdiq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shzxlz.cn/Article/details/gtmkiscxfr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgufenzy.top/Article/details/gtsfomrfri.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cucudq.cn/Article/details/gtcvrmtczt.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtvshubati.html

N. 数据结构与算法
来源：http://dali.jqgufenzy.top/Article/details/gtpadftxcu.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtxmtrddvw.html

[N01] 二分查找（有序数组）
来源：http://dali.jlsjyb.cn/Article/details/gtnaaebzwr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtuytjhaix.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fengsongda.top/Article/details/gtfflpnfss.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gtlykcyjbn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gtllpjfhii.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtsbuedjcb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtfmheaawj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jiagoushi.top/Article/details/gtmvrwwtfj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtjexxycgk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aibaodan.cn/Article/details/gtpnarzkft.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtksuqujan.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ehwqpu.com/Article/details/gtltlxfrsh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gtoaqznjme.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtxlighwaa.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ppjwa.cn/Article/details/gtlbsgvyqu.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnurjmvdd.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gteinyuwha.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuxming.cn/Article/details/gtlowjoyhw.html

[N03] 快速排序（分治示例）
来源：http://dali.chenjidiqi.icu/Article/details/gtyhhsuzyv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhixingplan.top/Article/details/gttsfmulyk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258888.top/Article/details/gtmzftakmf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gtozrlxixc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gtgwkoeiua.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ivvv.top/Article/details/gtydusplfn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nwbrower.top/Article/details/gtuzgjjobp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.kuanghao11.cn/Article/details/gtaulqsxzb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cashguo.top/Article/details/gtehopfyka.html

[N04] 斐波那契数列
来源：http://dali.hywenlv.cn/Article/details/gtzfrsrtjc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gtkvmzdqib.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtdckhjotu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtjhrxxeha.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtvpoezamh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gtjvtoswuh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cashguo.top/Article/details/gtnvjvvabp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gthezbgacf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gtrcttzvjo.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gtiyivzvzl.html

Py:   math.gcd(a, b)
来源：http://dali.hfpthk.cn/Article/details/gtvuhfximf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xylfe.cn/Article/details/gtymmvamsn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtsjfocjgv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gtjmlcelnh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.vqdsnc.cn/Article/details/gthyoflwex.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fzhhl.top/Article/details/gtbhfqjnzt.html

Ruby: a.gcd(b)
来源：http://dali.cqqwz.cn/Article/details/gtqsnumxao.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gtvteuyuua.html

[N06] 判断回文字符串
来源：http://dali.xinyue.icu/Article/details/gtpwduqydk.html

Py:   s == s[::-1]
来源：http://dali.meibo888.top/Article/details/gtynbmwrzt.html

PHP:  $s === strrev($s);
来源：http://dali.nwbrower.top/Article/details/gtujqstdjb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gttzrlqqul.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtiitlqhgh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtsesjmc.html

Go:   // 双指针从两端比较
来源：http://dali.hnxiangtu.top/Article/details/gtyguujoqm.html

Ruby: s == s.reverse
来源：http://dali.haohaochexian.top/Article/details/gtnmnsfyqv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtyrsfwebq.html

[N07] 两数之和（返回下标）
来源：http://dali.zhoulong.xyz/Article/details/gtrecigcjo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnqzz.top/Article/details/gticaxpgcd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sysykeji.top/Article/details/gtslvxlfyk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhiwuduotai.top/Article/details/gtkjlibphu.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenlongwang.top/Article/details/gtudtvmezr.html

Java: // 手写 HashMap
来源：http://dali.tianlin.xyz/Article/details/gtfyiieoqu.html

Go:   // 手写 map[int]int
来源：http://dali.shuidangran.top/Article/details/gtucixtcvu.html

Ruby: // 手写 Hash
来源：http://dali.jinqigufen.top/Article/details/gtnjvbaalr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xinyue.icu/Article/details/gtonjueihh.html

[N08] 生成全排列
来源：http://dali.shangyingyoupin.top/Article/details/gtpmiphhqs.html

Py:   itertools.permutations(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtzdukyigd.html

PHP:  // 手写递归交换
来源：http://dali.zhiwuduotai.top/Article/details/gtgzjigvsz.html

JS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtirdseynq.html

TS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtakukbzfq.html

Java: // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtubcqgvpb.html

Go:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtxvfhshna.html

Ruby: arr.permutation.to_a
来源：http://dali.yj202588.top/Article/details/gtbzmnfqjq.html

C#:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdeyhxhi.html

[N09] 栈与队列
来源：http://dali.xziqi.cn/Article/details/gtqwlbpqls.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yuanzhike.top/Article/details/gttpeouwuc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cashguo.top/Article/details/gtrhwsdjib.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuxming.cn/Article/details/gttkyjwixk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.c1oappe.top/Article/details/gtksauyjfj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtnvjfzvnw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenlongwang.top/Article/details/gtvldtdgjx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtcktabpkw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtxgvrnkyt.html

[N10] 链表节点定义
来源：http://dali.nwbrower.top/Article/details/gtcnpsjrto.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgufenzy.top/Article/details/gttcyhtpas.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.smart0.xyz/Article/details/gtxwbxdxbn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daxiang520.top/Article/details/gtlanstpae.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgfzy.top/Article/details/gtmuvazarw.html

Java: class Node { int v; Node next; }
来源：http://dali.yangfankeji.com/Article/details/gtrqmcwhsr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sysykeji.top/Article/details/gtffaegovi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.iojbl.cn/Article/details/gtrmtasafv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqavxexp.html

[N11] 二叉树中序遍历
来源：http://dali.daxiang520.top/Article/details/gthcybpugu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.9152youxi.cn/Article/details/gtpfndrshe.html

PHP:  // 手写递归函数
来源：http://dali.sufxvd.cn/Article/details/gticbhzncv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gtpppebvsc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ppjwa.cn/Article/details/gtyreeakgh.html

Java: // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtxgcjiyyv.html

Go:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtgqrvbyzk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hfpthk.cn/Article/details/gtmhqrvxyr.html

C#:   // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gtjftmylbp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangshuangyany.cn/Article/details/gtwwshrfis.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cheryme.top/Article/details/gtjfxomcav.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shangyingyoupin.top/Article/details/gtlsvwpapb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gtfgzpzwsb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gtsmcjevfu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gtcbeliiim.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yvedp.cn/Article/details/gtpwjgleqf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jlsjyb.cn/Article/details/gtlpuzieik.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gtywzoncix.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtszvepydy.html

O. 并发与异步
来源：http://dali.dashuyun.cn/Article/details/gteagbigvx.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtltxetqhw.html

[O01] 启动一个线程
来源：http://dali.iojbl.cn/Article/details/gtslwqzelz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.snrcjt.cn/Article/details/gtmejluyvp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aibaodan.cn/Article/details/gtzcneatcw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.quarkkingdee.top/Article/details/gtmmrdfuxx.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gtbyhijrtl.html

Java: new Thread(() -> f()).start()
来源：http://dali.mhx1999.top/Article/details/gtpdhzacsb.html

Go:   go f()
来源：http://dali.quarkkingdee.top/Article/details/gtcahxcotd.html

Ruby: Thread.new { f }
来源：http://dali.ydzc1.top/Article/details/gtelkaacrs.html

C#:   Task.Run(() => F());
来源：http://dali.cdnleiting.top/Article/details/gtmmnbxzxu.html

[O02] 使用线程池
来源：http://dali.cqqwz.cn/Article/details/gtqjjkqpsg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnxiangtu.top/Article/details/gtktpigune.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncnaffgh.html

JS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gtyumgrsxh.html

TS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gtjvaifink.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhixingplan.top/Article/details/gtfeuvrbrg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.fengsongda.top/Article/details/gtqzvpemww.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhixingplan.top/Article/details/gtvlkoktyb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jyoumei.cn/Article/details/gtvunnvrho.html

[O03] 加锁保护共享数据
来源：http://dali.zhengqikj.top/Article/details/gtychiblyf.html

Py:   with lock: shared += 1
来源：http://dali.zycfv.cn/Article/details/gtjvdusryk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nwbrower.top/Article/details/gtfonmwerr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gaohongyu789.top/Article/details/gtskstxhnm.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gtfzpewtnk.html

Java: synchronized (this) { shared++; }
来源：http://dali.mhx1999.top/Article/details/gtdowopkvp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.bjfxy.top/Article/details/gtqhpfraqv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.vqdsnc.cn/Article/details/gtuiaglshr.html

C#:   lock (gate) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gtvxeppqcn.html

[O04] 定义异步函数并等待
来源：http://dali.snrcjt.cn/Article/details/gtwfoowpwo.html

Py:   async def f():⏎    await g()
来源：http://dali.316326.xyz/Article/details/gtedrastnt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pycfn.com/Article/details/gtbaywyxbe.html

JS:   async function f() { await g(); }
来源：http://dali.ehwqpu.com/Article/details/gtmbfmsthk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gtlkhmbjxh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yonumen.top/Article/details/gtcaxavapq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tian-w.cn/Article/details/gtjkvyymyl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgufenzy.top/Article/details/gtqmeyktgg.html

C#:   async Task F() { await G(); }
来源：http://dali.sysykeji.top/Article/details/gtiuomtfwn.html

[O05] 并发执行并等待全部完成
来源：http://dali.aibaodan.cn/Article/details/gtwayepvgp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgrwrkye.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ydzc1.top/Article/details/gtuuoivziy.html

JS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gtghurfzix.html

TS:   await Promise.all(tasks)
来源：http://dali.sxryk.cn/Article/details/gtqmhnknvv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenzaomai.com/Article/details/gtdslavpye.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dianchejie.cn/Article/details/gtkezohhir.html

Ruby: threads.map(&:join)
来源：http://dali.zhixingplan.top/Article/details/gtpzidwjqb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.quarkkingdee.top/Article/details/gtmeciuykq.html

[O06] 使用进程池
来源：http://dali.sxryk.cn/Article/details/gtnuzkirqc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gtjcqaojas.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guannengcc.top/Article/details/gtyzjqpjxc.html

JS:   // child_process / cluster 模块
来源：http://dali.tian-w.cn/Article/details/gtmdsolipg.html

TS:   // child_process / cluster 模块
来源：http://dali.vqdsnc.cn/Article/details/gtpwkbehvn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuanzx.com/Article/details/gtfvogsyjk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.iojbl.cn/Article/details/gtenngwwnz.html

Ruby: // fork 块
来源：http://dali.bjfxy.top/Article/details/gtqldjbwkh.html

C#:   Parallel.For
来源：http://dali.yangfankeji.com/Article/details/gtmzaaqkiq.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtogqualqk.html

P. 常用工具函数
来源：http://dali.xuanzx.com/Article/details/gtoxzbyccl.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtbclquvzw.html

[P01] 生成 UUID
来源：http://dali.nanxinkj.top/Article/details/gtcwzsswxa.html

Py:   str(uuid.uuid4())
来源：http://dali.zycfv.cn/Article/details/gtembxzkxm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hywenlv.cn/Article/details/gtlndgkchz.html

JS:   crypto.randomUUID()
来源：http://dali.tianlin.xyz/Article/details/gttgpdkfuz.html

TS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gtxcwwdvdc.html

Java: UUID.randomUUID().toString()
来源：http://dali.cqqwz.cn/Article/details/gtdimsnphj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj202588.top/Article/details/gtdrhbvbmt.html

Ruby: SecureRandom.uuid
来源：http://dali.mhx1999.top/Article/details/gtulbmqtnv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yonumen.top/Article/details/gtirwqmync.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hfpthk.cn/Article/details/gtitsxwioj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.0kj1m.cn/Article/details/gtxqechkes.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cdnleiting.top/Article/details/gtjmndjpst.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nwbrower.top/Article/details/gttkjipblv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.mhx1999.top/Article/details/gtumcfwciz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gtrbruvmuj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zycfv.cn/Article/details/gtrxrkdykw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtixahjoix.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.bjfxy.top/Article/details/gtcggpdert.html

[P03] 生成短随机字符串
来源：http://dali.kuanghao11.cn/Article/details/gtdzpokowy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuanzhike.top/Article/details/gthrqtcwcz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjndzdfm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gtrutuxpqs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gtnvwcnjtl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngdtqutf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.havefunace.top/Article/details/gtuejrcqdm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cashguo.top/Article/details/gtpysqoohz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.iojbl.cn/Article/details/gtouorfrmz.html

[P04] 求长度
来源：http://dali.shuidangran.top/Article/details/gtppyjeaba.html


<!-- 参考信息 -->