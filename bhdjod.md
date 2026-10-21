代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtmxsdkfcl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhixingplan.top/Article/details/gtetswivpo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgufenzy.top/Article/details/gtdulnrlec.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgfzy.top/Article/details/gtfgilitsu.html

[L07] 处理 HTTP 状态码
来源：http://dali.yueranfly.top/Article/details/gtpttfstrh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuzkuotm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hfpthk.cn/Article/details/gtpdrwutsx.html

JS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gtaorueyjs.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gtcoczfbjw.html

Java: resp.statusCode()
来源：http://dali.sysykeji.top/Article/details/gtdmvtgkep.html

Go:   resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gtibwkohro.html

Ruby: resp.code.to_i
来源：http://dali.xinyue.icu/Article/details/gtoamkjwry.html

C#:   (int)resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gtpvbfcbgp.html

[L08] 并发请求多个地址
来源：http://dali.nanxuanxn.top/Article/details/gtlscomcpy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yongpay.top/Article/details/gtxjmmpmca.html

PHP:  curl_multi_init() 系列
来源：http://dali.xinyue.icu/Article/details/gtsshinlgu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gtytxjvmwg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtospkblnq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.smart0.xyz/Article/details/gtyfwffihm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnxiangtu.top/Article/details/gtkzcpjlrw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtwuxoyxna.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxinkj.top/Article/details/gtqysgaxzb.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gttvtggjqk.html

M. 命令行 / 进程 / 环境
来源：http://dali.guannengcc.top/Article/details/gtnergxwtf.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtgomfdtcf.html

[M01] 读取命令行参数
来源：http://dali.yonumen.top/Article/details/gtjvfckkwe.html

Py:   sys.argv[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtsrxqamcu.html

PHP:  $argv;  $argc;
来源：http://dali.c1oappe.top/Article/details/gtzgakkuta.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtdazpyeoc.html

TS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtesoaavgv.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gtylbljitu.html

Go:   os.Args[1:]
来源：http://dali.iojbl.cn/Article/details/gtrspoybui.html

Ruby: ARGV
来源：http://dali.birdmap.top/Article/details/gtyqqiedwu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegxxhpoe.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtrxukhkfa.html

Py:   os.environ.get("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtacwwdzzu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtbjtxokav.html

JS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gttedobaxs.html

TS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gtfwvbkjde.html

Java: System.getenv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtshhqceqg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258.top/Article/details/gtstmikkgd.html

Ruby: ENV["HOME"]
来源：http://dali.yonumen.top/Article/details/gtwyxqwidt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtzfxrxzim.html

[M03] 执行外部命令
来源：http://dali.vqdsnc.cn/Article/details/gtptlvpbsn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.snrcjt.cn/Article/details/gtfkurhuhm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxinkj.top/Article/details/gtmmwkluiu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gtndtkipsm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gtuwwyller.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhengqikj.top/Article/details/gtojcydxui.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnxiangtu.top/Article/details/gtjrfqgcsv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yangfankeji.com/Article/details/gtthjsmuwk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xylfe.cn/Article/details/gtxbnrivox.html

[M04] 获取当前工作目录
来源：http://dali.hongshengwenyu.top/Article/details/gtrvzolczi.html

Py:   os.getcwd()
来源：http://dali.hnqzz.top/Article/details/gttrxkkorh.html

PHP:  getcwd();
来源：http://dali.cashguo.top/Article/details/gtmmftuira.html

JS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gtoigskspq.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtahjvgjus.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gzhubu.top/Article/details/gtiepxcand.html

Go:   os.Getwd()
来源：http://dali.tianlin.xyz/Article/details/gtmopetlds.html

Ruby: Dir.pwd
来源：http://dali.zhiwuduotai.top/Article/details/gtvtvssnjb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pycfn.com/Article/details/gtfqfjdlvi.html

[M05] 设置退出码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcisujgby.html

Py:   sys.exit(1)
来源：http://dali.birdmap.top/Article/details/gtzcarhnvr.html

PHP:  exit(1);
来源：http://dali.cheryme.top/Article/details/gtzqutcqvc.html

JS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gtbwrvnzss.html

TS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtwmrvzhau.html

Java: System.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtnslraokx.html

Go:   os.Exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtjqauqzgb.html

Ruby: exit 1
来源：http://dali.hywenlv.cn/Article/details/gtzdevzgrf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.0kj1m.cn/Article/details/gttrxdfgxc.html

[M06] 向标准错误输出
来源：http://dali.fzhhl.top/Article/details/gttpqzfumr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pycfn.com/Article/details/gtjkoigecf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shzxlz.cn/Article/details/gtpskbsfdk.html

JS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlmtvwscr.html

TS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtenwgynar.html

Java: System.err.println("err")
来源：http://dali.ehwqpu.com/Article/details/gtskfewqrt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hongshengwenyu.top/Article/details/gtfhijrtnq.html

Ruby: warn "err"
来源：http://dali.yuanzhike.top/Article/details/gttaxnuuck.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.vqdsnc.cn/Article/details/gtenkeaobp.html

[M07] 判断是否为主入口
来源：http://dali.ivvv.top/Article/details/gtajgscyqt.html

Py:   if __name__ == "__main__":
来源：http://dali.jianghu66.top/Article/details/gtwgbtyxrw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnxiangtu.top/Article/details/gtgfkycrvi.html

JS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtmoiixvlc.html

TS:   require.main === module
来源：http://dali.sweek.top/Article/details/gtaownpdjf.html

Java: public static void main(String[] args)
来源：http://dali.cashguo.top/Article/details/gtyaeylkks.html

Go:   func main()
来源：http://dali.yvedp.cn/Article/details/gtwhytgegd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xylfe.cn/Article/details/gtilzulmlz.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258.top/Article/details/gtspljndqw.html

[M08] 获取系统与运行时信息
来源：http://dali.haohaochexian.top/Article/details/gtssbwmwus.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fzhhl.top/Article/details/gtrxvrxbpj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zycfv.cn/Article/details/gtoujvnmzl.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtdizctyjg.html

TS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gtktcqpnfy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dashuyun.cn/Article/details/gtbzzanlhv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nwbrower.top/Article/details/gtdntkouwo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxinkj.top/Article/details/gtcgbcofen.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yonumen.top/Article/details/gtlxqhjypb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtkpymkpzw.html

N. 数据结构与算法
来源：http://dali.chenlongwang.top/Article/details/gtwxwmuxuo.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtsfwwzmxe.html

[N01] 二分查找（有序数组）
来源：http://dali.feifeiyinyue.top/Article/details/gtutogzaiz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtuepdezms.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ivvv.top/Article/details/gtecbwvliw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtejiceftp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gtwzzpxfav.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtrpnmfyrj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtnrhqizni.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hywenlv.cn/Article/details/gtgfvbfymg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gtlnnvasil.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gtdemnmway.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gtwlnsafdf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.havefunace.top/Article/details/gtnxocmohs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtlegbkbzb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gtdxznaxys.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yonumen.top/Article/details/gtfnikfpzr.html

Go:   slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gthnjvskok.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gtlnwgkxnh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuuqlfcps.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxinkj.top/Article/details/gtshacluvj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisignsrb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxqmcccp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gtotkkvjmm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gtsoksdgiv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dashuyun.cn/Article/details/gtnohrcwtl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aizwys.cn/Article/details/gtgjpqntxx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tianlin.xyz/Article/details/gtuwprilef.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daxiang520.top/Article/details/gtyxvfwzbb.html

[N04] 斐波那契数列
来源：http://dali.redwolf501.top/Article/details/gtbcbdpjvx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gthygnhfhd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtysfaifmx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtkzwnlcua.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtupbfwbkj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtibqtebun.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenjidiqi.icu/Article/details/gtcbpmjgze.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tianlin.xyz/Article/details/gtymmwundk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gtahbdbyfh.html

[N05] 最大公约数
来源：http://dali.yangfankeji.com/Article/details/gtkhjzaxib.html

Py:   math.gcd(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtzmsyimvc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gzhubu.top/Article/details/gtruhleprm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gttgkzussl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gtpvrfcldk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslgdtbuv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aibaodan.cn/Article/details/gteuetqgcf.html

Ruby: a.gcd(b)
来源：http://dali.svipenyu.cn/Article/details/gttmxtteqx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tanke756.top/Article/details/gtyuaauvuu.html

[N06] 判断回文字符串
来源：http://dali.yueranfly.top/Article/details/gthqncagsi.html

Py:   s == s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gtuawmvipg.html

PHP:  $s === strrev($s);
来源：http://dali.aizwys.cn/Article/details/gtiaypjlzl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtishlqkhv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtdrghhtbs.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.fengsongda.top/Article/details/gtcxkzrnbz.html

Go:   // 双指针从两端比较
来源：http://dali.shangyingyoupin.top/Article/details/gtmfdoyxgw.html

Ruby: s == s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvgnwmjy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gthteiernr.html

[N07] 两数之和（返回下标）
来源：http://dali.cheryme.top/Article/details/gtszimpspv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fengsongda.top/Article/details/gtrsfqfyci.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ppjwa.cn/Article/details/gtgrodikmu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.meibo888.top/Article/details/gtmrdypcai.html

TS:   // 手写 Map<string, number>
来源：http://dali.cucudq.cn/Article/details/gtbkzeqnyy.html

Java: // 手写 HashMap
来源：http://dali.chenzaomai.com/Article/details/gtjmwbxycw.html

Go:   // 手写 map[int]int
来源：http://dali.nwbrower.top/Article/details/gtkyfyaauf.html

Ruby: // 手写 Hash
来源：http://dali.hywenlv.cn/Article/details/gteitoxkuk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gotoacloud.top/Article/details/gtklhyvqlf.html

[N08] 生成全排列
来源：http://dali.yanxiufei.cn/Article/details/gtdehwcttl.html

Py:   itertools.permutations(arr)
来源：http://dali.pycfn.com/Article/details/gtdtwuxprk.html

PHP:  // 手写递归交换
来源：http://dali.yj20258.top/Article/details/gtjnlmvnaf.html

JS:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtruargixw.html

TS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtndddanrs.html

Java: // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtsdumdooj.html

Go:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtnftcyjft.html

Ruby: arr.permutation.to_a
来源：http://dali.quarkkingdee.top/Article/details/gthvzroxkm.html

C#:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtsmtpshov.html

[N09] 栈与队列
来源：http://dali.andypj.xyz/Article/details/gttoknhjnn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gttqkidply.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuanzx.com/Article/details/gtrkxgynjy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtlkyiyqwp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ydzc1.top/Article/details/gtwcitcipz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258888.top/Article/details/gtvsppqxgt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tanke756.top/Article/details/gtcsgyzwhv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtziuojvpz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gaohongyu789.top/Article/details/gthnmzkutu.html

[N10] 链表节点定义
来源：http://dali.meibo888.top/Article/details/gtbckdlueu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dashuyun.cn/Article/details/gtlpoxwrmj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.c1oappe.top/Article/details/gtgwcpkydx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenlongwang.top/Article/details/gtesdqqmhi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yangfankeji.com/Article/details/gtyimaauno.html

Java: class Node { int v; Node next; }
来源：http://dali.birdmap.top/Article/details/gtviiibdgb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xinyue.icu/Article/details/gtkztfjdwg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangdashe.top/Article/details/gtlolveuae.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xuetiantiany.cn/Article/details/gttryfjasc.html

[N11] 二叉树中序遍历
来源：http://dali.sweek.top/Article/details/gtbgjrardb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gogol.net.cn/Article/details/gtsawwvmxl.html

PHP:  // 手写递归函数
来源：http://dali.sweek.top/Article/details/gtkhkozzwq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gtrlloirti.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gtkzgcgczn.html

Java: // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtkaxrrebc.html

Go:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gternluxll.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yanxiufei.cn/Article/details/gtsaaisnwp.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gtsukwfkzl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.c1oappe.top/Article/details/gtluberqyi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.meibo888.top/Article/details/gthynpitbp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yvedp.cn/Article/details/gtlecixfkr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gtmqtgytik.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gtrhqvuqvk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtqopyxqhc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.svipenyu.cn/Article/details/gtcppbmdwt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtvxijqlxb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gthjhmpgqd.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtumyogrfn.html

O. 并发与异步
来源：http://dali.aibaodan.cn/Article/details/gtssaabqph.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtrcpiqpql.html

[O01] 启动一个线程
来源：http://dali.bjfxy.top/Article/details/gtoiaztspk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenjidiqi.icu/Article/details/gtfmwnyrrv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxuanxn.top/Article/details/gtpwiklira.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.aizwys.cn/Article/details/gtvrjfhpqp.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gtleppjzed.html

Java: new Thread(() -> f()).start()
来源：http://dali.vqdsnc.cn/Article/details/gtxbhwdifa.html

Go:   go f()
来源：http://dali.wangshuangyany.cn/Article/details/gtcjjkadsl.html

Ruby: Thread.new { f }
来源：http://dali.tian-w.cn/Article/details/gttkpcpwkn.html

C#:   Task.Run(() => F());
来源：http://dali.zhengqikj.top/Article/details/gtbawhfksc.html

[O02] 使用线程池
来源：http://dali.jinqigufen.top/Article/details/gtwvyqtqum.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dashuyun.cn/Article/details/gtyqtpjgpt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhengqikj.top/Article/details/gtksqycoua.html

JS:   // worker_threads 线程池
来源：http://dali.sxryk.cn/Article/details/gtnzjhydmt.html

TS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gtaaxxgrzs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenlongwang.top/Article/details/gtbvqrmolq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jlsjyb.cn/Article/details/gtnlnojymh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhengqikj.top/Article/details/gtikmnvekr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yvedp.cn/Article/details/gtzweouvfn.html

[O03] 加锁保护共享数据
来源：http://dali.jlsjyb.cn/Article/details/gtrlssmper.html

Py:   with lock: shared += 1
来源：http://dali.c1oappe.top/Article/details/gtfxhadcwd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jyoumei.cn/Article/details/gtlcybuuge.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccywfwkp.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gtmfloebir.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkugmvixo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sweek.top/Article/details/gtljlyjphv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinqigfzy.top/Article/details/gtmfbuivyh.html

C#:   lock (gate) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtegasudbk.html

[O04] 定义异步函数并等待
来源：http://dali.hnxiangtu.top/Article/details/gtgtgkxujf.html

Py:   async def f():⏎    await g()
来源：http://dali.hysaishi.cn/Article/details/gtsvcrviar.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.snrcjt.cn/Article/details/gtizvsniyo.html

JS:   async function f() { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gtrngqeoav.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gtayneiycj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jiagoushi.top/Article/details/gtzyydvydb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ivvv.top/Article/details/gtztmevrvh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dashuyun.cn/Article/details/gtelejnqjk.html

C#:   async Task F() { await G(); }
来源：http://dali.sufxvd.cn/Article/details/gtqtkhtgpl.html

[O05] 并发执行并等待全部完成
来源：http://dali.tianlin.xyz/Article/details/gtpbkjysnf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtwmreipgw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxinkj.top/Article/details/gtnndugqwf.html

JS:   await Promise.all(tasks)
来源：http://dali.daria6918.cn/Article/details/gtchgmyxhb.html

TS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gtpuuyatlh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pycfn.com/Article/details/gtxumbyjyl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xinyue.icu/Article/details/gtwlcyjyxg.html

Ruby: threads.map(&:join)
来源：http://dali.zycfv.cn/Article/details/gttftohoko.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zdqjudy.top/Article/details/gtdqisbfwk.html

[O06] 使用进程池
来源：http://dali.xuetiantiany.cn/Article/details/gtdizifvon.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgfzy.top/Article/details/gtzehhofdk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhengqikj.top/Article/details/gtriorzsfs.html

JS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gtppjlpfzk.html

TS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gtuvypehlf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuanzx.com/Article/details/gtwmrlqucx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.havefunace.top/Article/details/gtvndopvpb.html

Ruby: // fork 块
来源：http://dali.jianghu66.top/Article/details/gtncfevbnt.html

C#:   Parallel.For
来源：http://dali.sysykeji.top/Article/details/gtwetxyckf.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtymkycjvb.html

P. 常用工具函数
来源：http://dali.mhx1999.top/Article/details/gtuuyjqkcm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtydwsccdn.html

[P01] 生成 UUID
来源：http://dali.yvedp.cn/Article/details/gtzoezafzx.html

Py:   str(uuid.uuid4())
来源：http://dali.gotoacloud.top/Article/details/gtdrxuxpuk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenzaomai.com/Article/details/gtaxspndys.html

JS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gttdoyeuss.html

TS:   crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtjshepuhb.html

Java: UUID.randomUUID().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtvkaxouxz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgufenzy.top/Article/details/gtfzgpoluj.html

Ruby: SecureRandom.uuid
来源：http://dali.xinyue.icu/Article/details/gttqgzilhd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxuanxn.top/Article/details/gtkvypopyb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgufenzy.top/Article/details/gtahowknok.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigufen.top/Article/details/gtqkbsmjou.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.316326.xyz/Article/details/gtjjprzwqy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sxryk.cn/Article/details/gtaqstfftm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shuidangran.top/Article/details/gtgsqbkicc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gtlzcwslts.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.pengpengdd.cyou/Article/details/gtoivrdimg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.havefunace.top/Article/details/gtmuzrozxd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuanzhike.top/Article/details/gtetzfufnv.html

[P03] 生成短随机字符串
来源：http://dali.birdmap.top/Article/details/gtootvnbjy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hnqzz.top/Article/details/gtazczelcv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinghuilouyu.cn/Article/details/gtavzagpcp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gtkeiywvpw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gtckbwcuwg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258888.top/Article/details/gttdgbuxnt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gzhubu.top/Article/details/gtkhxpygnl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.quarkkingdee.top/Article/details/gthpsjdifz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.dianchejie.cn/Article/details/gtltghkvor.html

[P04] 求长度
来源：http://dali.jqgfzy.top/Article/details/gtvdgqcnpa.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.meibo888.top/Article/details/gtxyqqhwza.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtfgsvquxx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gtyzzzsuet.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gtyaawpimi.html


<!-- 参考信息 -->