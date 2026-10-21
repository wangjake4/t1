代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gtgqigsrkt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cashguo.top/Article/details/gthnumjogo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ppjwa.cn/Article/details/gtadlienmr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgufenzy.top/Article/details/gtwlidudoo.html

[L07] 处理 HTTP 状态码
来源：http://dali.quarkkingdee.top/Article/details/gtjyrtbynf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.mhx1999.top/Article/details/gtsrbpsuva.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.c1oappe.top/Article/details/gtzrjbxjew.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgpohcxi.html

TS:   resp.ok;  resp.status
来源：http://dali.gzhubu.top/Article/details/gtqmudcuft.html

Java: resp.statusCode()
来源：http://dali.mhx1999.top/Article/details/gtkypjfmzk.html

Go:   resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gtmltpwqch.html

Ruby: resp.code.to_i
来源：http://dali.yonumen.top/Article/details/gtvdbtdzqc.html

C#:   (int)resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gtwlgvyfin.html

[L08] 并发请求多个地址
来源：http://dali.xziqi.cn/Article/details/gtlhqkarke.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gaohongyu789.top/Article/details/gttpvlyytw.html

PHP:  curl_multi_init() 系列
来源：http://dali.tanke756.top/Article/details/gtimqllzid.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gtbajrumff.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtqgnjvgtm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fzhhl.top/Article/details/gtbqhvztuq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.9152youxi.cn/Article/details/gtcvoztlpw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sysykeji.top/Article/details/gtnwnngrlg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtcjcqxsbt.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtdjyeujbr.html

M. 命令行 / 进程 / 环境
来源：http://dali.quarkkingdee.top/Article/details/gtklukwkvg.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtcdfflhdv.html

[M01] 读取命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gtpooefouc.html

Py:   sys.argv[1:]
来源：http://dali.sufxvd.cn/Article/details/gtehnrhiqz.html

PHP:  $argv;  $argc;
来源：http://dali.yueranfly.top/Article/details/gtrdoidwpi.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gtvmnlpeqo.html

TS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtbjjzssjz.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gtaqzlpvln.html

Go:   os.Args[1:]
来源：http://dali.cqqwz.cn/Article/details/gtitayotcp.html

Ruby: ARGV
来源：http://dali.havefunace.top/Article/details/gtslhmepyi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gtajytbsgg.html

[M02] 读取环境变量
来源：http://dali.sxryk.cn/Article/details/gtmnfsqhfo.html

Py:   os.environ.get("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghubamyf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gtonbgolqr.html

JS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gtiuuloklt.html

TS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gtpurqtblw.html

Java: System.getenv("HOME")
来源：http://dali.yueranfly.top/Article/details/gtskiwhlfu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xinyue.icu/Article/details/gtxejyxifq.html

Ruby: ENV["HOME"]
来源：http://dali.hysaishi.cn/Article/details/gtjdvnupep.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aizwys.cn/Article/details/gtvktnylws.html

[M03] 执行外部命令
来源：http://dali.yuxming.cn/Article/details/gtuyxialku.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnqzz.top/Article/details/gtfygwruiz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.vqdsnc.cn/Article/details/gtttoojgxw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtvhupnviv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtyksikrfb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tian-w.cn/Article/details/gtynqrtmlq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guowangkeji.top/Article/details/gtivymxqyh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sysykeji.top/Article/details/gtwpbpkwuj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ehwqpu.com/Article/details/gttsvlvhpi.html

[M04] 获取当前工作目录
来源：http://dali.feifeiyinyue.top/Article/details/gtumqjohhv.html

Py:   os.getcwd()
来源：http://dali.guowangkeji.top/Article/details/gtxlputaxr.html

PHP:  getcwd();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrblfsdbz.html

JS:   process.cwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtcqdgxaly.html

TS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gthjvquzim.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cheryme.top/Article/details/gthoeywoui.html

Go:   os.Getwd()
来源：http://dali.dashuyun.cn/Article/details/gtuneovvyj.html

Ruby: Dir.pwd
来源：http://dali.shuidangran.top/Article/details/gttokelrxr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xziqi.cn/Article/details/gtcrhpmchi.html

[M05] 设置退出码
来源：http://dali.tian-w.cn/Article/details/gtfslbvdjr.html

Py:   sys.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtleekvldr.html

PHP:  exit(1);
来源：http://dali.tianlin.xyz/Article/details/gteyyfwomi.html

JS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtxgjjooct.html

TS:   process.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtdajdnryy.html

Java: System.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtrhrejvxb.html

Go:   os.Exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtpmtqeyff.html

Ruby: exit 1
来源：http://dali.ppjwa.cn/Article/details/gtjoxdenep.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.wangshuangyany.cn/Article/details/gtollooajf.html

[M06] 向标准错误输出
来源：http://dali.daxiang520.top/Article/details/gtjgrrsfzj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gtdefpwcfr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gzhubu.top/Article/details/gtcbqyjaam.html

JS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gtowbvchgu.html

TS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtqengfxym.html

Java: System.err.println("err")
来源：http://dali.snrcjt.cn/Article/details/gtpmbuqife.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuxming.cn/Article/details/gtzylqdpds.html

Ruby: warn "err"
来源：http://dali.shangyingyoupin.top/Article/details/gtriygrxct.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.meibo888.top/Article/details/gtsgpznlvc.html

[M07] 判断是否为主入口
来源：http://dali.pengpengdd.cyou/Article/details/gtoledeoun.html

Py:   if __name__ == "__main__":
来源：http://dali.zhongyouzk.top/Article/details/gtnbkmraki.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnqzz.top/Article/details/gtvsihspmx.html

JS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gtcpzjuiob.html

TS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gtgtmwtuwt.html

Java: public static void main(String[] args)
来源：http://dali.cdnleiting.top/Article/details/gtqmkghsny.html

Go:   func main()
来源：http://dali.xuetiantiany.cn/Article/details/gtjqcuwovk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxinkj.top/Article/details/gttgcdpyaw.html

C#:   static void Main(string[] args)
来源：http://dali.gotoacloud.top/Article/details/gtsdhcjygz.html

[M08] 获取系统与运行时信息
来源：http://dali.yangfankeji.com/Article/details/gtpgyrapky.html

Py:   platform.system();  platform.python_version()
来源：http://dali.haohaochexian.top/Article/details/gtjwpxlafn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cucudq.cn/Article/details/gtydtzzjmy.html

JS:   process.platform;  process.version
来源：http://dali.yuanzhike.top/Article/details/gthlkffumi.html

TS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gtanvveuau.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmyzfnhr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuanzx.com/Article/details/gtpxfeqasy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yangfankeji.com/Article/details/gtcvnsylst.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fzhhl.top/Article/details/gtnhjqrtgy.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtqhwzdkcv.html

N. 数据结构与算法
来源：http://dali.nwbrower.top/Article/details/gtxksuvzhe.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtvdjqzdit.html

[N01] 二分查找（有序数组）
来源：http://dali.yongpay.top/Article/details/gtqxdvjnta.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtobvfzzmi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ydzc1.top/Article/details/gtmpbpbayc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspsrskad.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtmjsjwoxl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtgbgndomg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sysykeji.top/Article/details/gthufuycgw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuetiantiany.cn/Article/details/gtwsncmkvw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovnntpfd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhiwuduotai.top/Article/details/gtfbkknoyq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gtmsszpkiy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yueranfly.top/Article/details/gtojtyybzj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtenqdceve.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gtmfetadyg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cdnleiting.top/Article/details/gteuloytpr.html

Go:   slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiixcwagc.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtrjhewzoe.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gzhubu.top/Article/details/gtvsrlpznt.html

[N03] 快速排序（分治示例）
来源：http://dali.svipenyu.cn/Article/details/gtogbcutub.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pengpengdd.cyou/Article/details/gttqtjlmbf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hammf.cn/Article/details/gtqxolbwhj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gtgmasiuux.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gtgkksxeku.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.316326.xyz/Article/details/gthcbxcxun.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xylfe.cn/Article/details/gtccchdtft.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xylfe.cn/Article/details/gtoayuiyba.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ivvv.top/Article/details/gtrzmtjhen.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwoasrnep.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.mhx1999.top/Article/details/gtgozyjszz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.iojbl.cn/Article/details/gtomizjbws.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtmgsmvrav.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtlfcfcmlr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpddjhfi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgufenzy.top/Article/details/gtcfbjsztf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gtlownagys.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtkuyfkhvj.html

[N05] 最大公约数
来源：http://dali.yonumen.top/Article/details/gtnvpgzpvc.html

Py:   math.gcd(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtuciqximt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgksrhnb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchnopfnv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gtlmqjjepc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.c1oappe.top/Article/details/gtidqlyynn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yongpay.top/Article/details/gtstmsrnjk.html

Ruby: a.gcd(b)
来源：http://dali.aizwys.cn/Article/details/gtiqvpzytj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ivvv.top/Article/details/gtrfkkftmw.html

[N06] 判断回文字符串
来源：http://dali.jianghu66.top/Article/details/gtgxhuwkjk.html

Py:   s == s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gtjpqlrrnm.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtrfbqiplh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtmtrvrqrm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtveevstgn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ivvv.top/Article/details/gtwjhvsemp.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gtkwlguiae.html

Ruby: s == s.reverse
来源：http://dali.cqqwz.cn/Article/details/gtmxybtkkl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gtxtcdzvif.html

[N07] 两数之和（返回下标）
来源：http://dali.fzhhl.top/Article/details/gtazwbrkwq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.iojbl.cn/Article/details/gtbakujzrx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daria6918.cn/Article/details/gtmvvolyuw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yvedp.cn/Article/details/gtlcyabpwy.html

TS:   // 手写 Map<string, number>
来源：http://dali.tanke756.top/Article/details/gtosewiolu.html

Java: // 手写 HashMap
来源：http://dali.hysaishi.cn/Article/details/gtzmsdlbsn.html

Go:   // 手写 map[int]int
来源：http://dali.guowangkeji.top/Article/details/gtzsbdneyu.html

Ruby: // 手写 Hash
来源：http://dali.dianchejie.cn/Article/details/gtodautdrn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgfzy.top/Article/details/gtyasofujq.html

[N08] 生成全排列
来源：http://dali.svipenyu.cn/Article/details/gteaiwbdns.html

Py:   itertools.permutations(arr)
来源：http://dali.ehwqpu.com/Article/details/gtldovvnga.html

PHP:  // 手写递归交换
来源：http://dali.aibaodan.cn/Article/details/gthbhgambm.html

JS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtrrracehy.html

TS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtpzrncpbp.html

Java: // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtzsmptidt.html

Go:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtxohbuqwb.html

Ruby: arr.permutation.to_a
来源：http://dali.dashuyun.cn/Article/details/gtbcuxwtwq.html

C#:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gttmfslnqa.html

[N09] 栈与队列
来源：http://dali.svipenyu.cn/Article/details/gtgdjwwsde.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtawgarklt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sweek.top/Article/details/gtvfpzxhqe.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gtwuvbkupf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fengsongda.top/Article/details/gtalgxkkqm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.316326.xyz/Article/details/gtnkcykemo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jiagoushi.top/Article/details/gteezynqun.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gttmgkqjmq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jqgfzy.top/Article/details/gtizftmtey.html

[N10] 链表节点定义
来源：http://dali.yj202588.top/Article/details/gtkqhocynv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.wangshuangyany.cn/Article/details/gtfakvtgtx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yvedp.cn/Article/details/gtlwewajur.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.snrcjt.cn/Article/details/gtboaizyau.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258888.top/Article/details/gtjjkelrrx.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigfzy.top/Article/details/gtezwziwlm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pycfn.com/Article/details/gtcwlemaqj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daxiang520.top/Article/details/gtannlavmu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxvyblki.html

[N11] 二叉树中序遍历
来源：http://dali.gaohongyu789.top/Article/details/gtrpvcmknt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.svipenyu.cn/Article/details/gthpuhwdox.html

PHP:  // 手写递归函数
来源：http://dali.316326.xyz/Article/details/gtvspsrsom.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gtqudijclt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xziqi.cn/Article/details/gtmjwhgobk.html

Java: // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gturcwbctb.html

Go:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtagrjmuyy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sweek.top/Article/details/gtpciorfmm.html

C#:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gtrrniquzv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuanzx.com/Article/details/gtponnfwpq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yonumen.top/Article/details/gtntyiyune.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hfpthk.cn/Article/details/gtrzozfvag.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gtvywblgrg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnqzz.top/Article/details/gtkckzmwdf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gttlcqkhhh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ybcxt.top/Article/details/gtftplmthn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nwbrower.top/Article/details/gtwomqlozm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gtpqouahuj.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtqsmacood.html

O. 并发与异步
来源：http://dali.chenjidiqi.icu/Article/details/gtbfyrmeai.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtcxtswnkm.html

[O01] 启动一个线程
来源：http://dali.gotoacloud.top/Article/details/gtdwypmgmc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guannengcc.top/Article/details/gtulgbxada.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjjnjezh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfdueany.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtwodqhkhd.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtomljjdys.html

Go:   go f()
来源：http://dali.xziqi.cn/Article/details/gtjtsiitly.html

Ruby: Thread.new { f }
来源：http://dali.0kj1m.cn/Article/details/gtmtdzvctb.html

C#:   Task.Run(() => F());
来源：http://dali.hywenlv.cn/Article/details/gttivfflbf.html

[O02] 使用线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtnahsfusg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yueranfly.top/Article/details/gthazyngvh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yuxming.cn/Article/details/gtwmgmcdvz.html

JS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gtfhgfoicl.html

TS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gtobqkqpxh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gogol.net.cn/Article/details/gtkjnijttr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jyoumei.cn/Article/details/gtpnceupgb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zdqjudy.top/Article/details/gtdpguyyhr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jyoumei.cn/Article/details/gtqjbbgvux.html

[O03] 加锁保护共享数据
来源：http://dali.cucudq.cn/Article/details/gtfxvwiovd.html

Py:   with lock: shared += 1
来源：http://dali.nanxinkj.top/Article/details/gtkrvdetpg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cashguo.top/Article/details/gtylvcrogw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sysykeji.top/Article/details/gtdxtqnqqn.html

TS:   // 同 JS
来源：http://dali.c1oappe.top/Article/details/gtrhscwzwg.html

Java: synchronized (this) { shared++; }
来源：http://dali.yonumen.top/Article/details/gthntgjzoq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hywenlv.cn/Article/details/gtzlwowzxq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.0kj1m.cn/Article/details/gtindhfcvj.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj202588.top/Article/details/gtdbjymmvq.html

[O04] 定义异步函数并等待
来源：http://dali.c1oappe.top/Article/details/gtrgvaoimf.html

Py:   async def f():⏎    await g()
来源：http://dali.sysykeji.top/Article/details/gthwunxmcc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgfzy.top/Article/details/gttibbykag.html

JS:   async function f() { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gtqugbpekk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gtyeytarht.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigufen.top/Article/details/gtynyitrgx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.iojbl.cn/Article/details/gtiyvedfws.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tian-w.cn/Article/details/gtwhdwmmtk.html

C#:   async Task F() { await G(); }
来源：http://dali.wangdashe.top/Article/details/gtgogomnez.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangshuangyany.cn/Article/details/gtihufrjyn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxinkj.top/Article/details/gtewigjfty.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hywenlv.cn/Article/details/gtsasgpsle.html

JS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gtwpwnwzsx.html

TS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthijfibij.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.9152youxi.cn/Article/details/gtlkfoclku.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zdqjudy.top/Article/details/gtqpibpyax.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigufen.top/Article/details/gtzeymydqp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xziqi.cn/Article/details/gtbsozvirb.html

[O06] 使用进程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvowdxvg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hammf.cn/Article/details/gtceexocth.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuxming.cn/Article/details/gtnovdayxv.html

JS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gtocushtxq.html

TS:   // child_process / cluster 模块
来源：http://dali.daria6918.cn/Article/details/gthhgcgjvo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hnxiangtu.top/Article/details/gtciqxigom.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.andypj.xyz/Article/details/gtpdrhpltv.html

Ruby: // fork 块
来源：http://dali.sufxvd.cn/Article/details/gtdzfrosel.html

C#:   Parallel.For
来源：http://dali.yonumen.top/Article/details/gtnosknraw.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtmyxmjwvv.html

P. 常用工具函数
来源：http://dali.xuetiantiany.cn/Article/details/gtfiycnncb.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtbpnujlba.html

[P01] 生成 UUID
来源：http://dali.xinyue.icu/Article/details/gtxobjagez.html

Py:   str(uuid.uuid4())
来源：http://dali.0kj1m.cn/Article/details/gtqtozocwx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jiagoushi.top/Article/details/gtwcjhphvs.html

JS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gtmblupzxz.html

TS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gtrzshoenm.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gtlyibkhfp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ppjwa.cn/Article/details/gtwkjgkmbo.html

Ruby: SecureRandom.uuid
来源：http://dali.shzxlz.cn/Article/details/gtdflucxzk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yvedp.cn/Article/details/gtebwjuthe.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fzhhl.top/Article/details/gtntsqjebu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sysykeji.top/Article/details/gtmnjfihwa.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.quarkkingdee.top/Article/details/gtaisrhxit.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnqzz.top/Article/details/gtdemkmrbr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hywenlv.cn/Article/details/gttxwlsvvv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ivvv.top/Article/details/gtlywjvxrg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xuetiantiany.cn/Article/details/gtzkbxbrxi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhbuzlyw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangdashe.top/Article/details/gtpxbbzhkc.html

[P03] 生成短随机字符串
来源：http://dali.daxiang520.top/Article/details/gtjjjtbfuc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyckrguw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xuanzx.com/Article/details/gtwwvpfuer.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gtsptkowjw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenzaomai.com/Article/details/gtpjosydtj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.havefunace.top/Article/details/gtuzwsqdms.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.meibo888.top/Article/details/gtiwqnhxvj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.vqdsnc.cn/Article/details/gtxwrepzdx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aizwys.cn/Article/details/gtwhxrxjau.html

[P04] 求长度
来源：http://dali.yongpay.top/Article/details/gtzxfnupts.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuanzhike.top/Article/details/gtvzwtityt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtjaxgfbfp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gtmccixwwq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gtgvmptseg.html


<!-- 参考信息 -->