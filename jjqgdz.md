代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gt2gkuozbwz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cdnleiting.top/Article/details/gt2pbnxpzkr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xziqi.cn/Article/details/gt2qbesmyom.html

JS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gt2kkcnxuzm.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mpnffoym.html

Java: resp.statusCode()
来源：http://dali.hnqzz.top/Article/details/gt2jkfnjeyy.html

Go:   resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gt2fmkhgvqr.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gt2jbcnaaum.html

C#:   (int)resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gt2ekumggsl.html

[L08] 并发请求多个地址
来源：http://dali.ydzc1.top/Article/details/gt2oakovgdy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gaohongyu789.top/Article/details/gt2ociyhnap.html

PHP:  curl_multi_init() 系列
来源：http://dali.dianchejie.cn/Article/details/gt2knzskzyg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gt2mbkcankm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ribxmnhg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ppjwa.cn/Article/details/gt2fdsvccnm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.kuanghao11.cn/Article/details/gt2fdiojmyw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.mhx1999.top/Article/details/gt2fkafslon.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hywenlv.cn/Article/details/gt2atqosati.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2csdruqmo.html

M. 命令行 / 进程 / 环境
来源：http://dali.yuanzhike.top/Article/details/gt2wrlhksqo.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vylgwaod.html

[M01] 读取命令行参数
来源：http://dali.yanxiufei.cn/Article/details/gt2vvumyksv.html

Py:   sys.argv[1:]
来源：http://dali.yanxiufei.cn/Article/details/gt2fkjfktvq.html

PHP:  $argv;  $argc;
来源：http://dali.chenzaomai.com/Article/details/gt2wobzmzfa.html

JS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gt2ypclysup.html

TS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gt2zkxjshdv.html

Java: args 数组（main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gt2gipdcxzs.html

Go:   os.Args[1:]
来源：http://dali.yj202588.top/Article/details/gt2slvxshni.html

Ruby: ARGV
来源：http://dali.yuxming.cn/Article/details/gt2najeqvdu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gt2yrgywjsc.html

[M02] 读取环境变量
来源：http://dali.aizwys.cn/Article/details/gt2ughnhawg.html

Py:   os.environ.get("HOME")
来源：http://dali.redwolf501.top/Article/details/gt2jgegazmw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pycfn.com/Article/details/gt2nyxacsli.html

JS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gt2nefroacx.html

TS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gt2mufohmho.html

Java: System.getenv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gt2niqxvycn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gt2cauuuknu.html

Ruby: ENV["HOME"]
来源：http://dali.mhx1999.top/Article/details/gt2gvtghwwk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sufxvd.cn/Article/details/gt2hofhohpf.html

[M03] 执行外部命令
来源：http://dali.shangyingyoupin.top/Article/details/gt2iewmywej.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sufxvd.cn/Article/details/gt2mkuxgbbv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.kuanghao11.cn/Article/details/gt2oftxrksc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gt2wkccdsxx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gt2qqhjhmcn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhiwuduotai.top/Article/details/gt2fpatvckh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jiagoushi.top/Article/details/gt2tohittul.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fzhhl.top/Article/details/gt2edgmyvse.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shuidangran.top/Article/details/gt2sytznppp.html

[M04] 获取当前工作目录
来源：http://dali.sxryk.cn/Article/details/gt2emvicafi.html

Py:   os.getcwd()
来源：http://dali.ybcxt.top/Article/details/gt2hnzqhqmp.html

PHP:  getcwd();
来源：http://dali.yuxming.cn/Article/details/gt2orslmqzc.html

JS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gt2scqsttth.html

TS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gt2vhgpldrd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gt2xwmwjcht.html

Go:   os.Getwd()
来源：http://dali.hnxiangtu.top/Article/details/gt2fhcgqlrl.html

Ruby: Dir.pwd
来源：http://dali.jyoumei.cn/Article/details/gt2asclprzx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zdqjudy.top/Article/details/gt2qvtgzkux.html

[M05] 设置退出码
来源：http://dali.cqqwz.cn/Article/details/gt2jyxgxzvc.html

Py:   sys.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gt2bjocvzve.html

PHP:  exit(1);
来源：http://dali.yj20258.top/Article/details/gt2zdvappje.html

JS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gt2nhcmigly.html

TS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2waxddnqg.html

Java: System.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2nfbyugkz.html

Go:   os.Exit(1)
来源：http://dali.sufxvd.cn/Article/details/gt2ezmeavkc.html

Ruby: exit 1
来源：http://dali.zhengqikj.top/Article/details/gt2uclgluwy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nwbrower.top/Article/details/gt2ancjohmk.html

[M06] 向标准错误输出
来源：http://dali.daria6918.cn/Article/details/gt2nfobyzgy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gt2cnzzjqav.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tanke756.top/Article/details/gt2jgocgkbx.html

JS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gt2xefdlbxg.html

TS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qgmetbyc.html

Java: System.err.println("err")
来源：http://dali.cashguo.top/Article/details/gt2afacpgbj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.316326.xyz/Article/details/gt2oluirrxc.html

Ruby: warn "err"
来源：http://dali.hysaishi.cn/Article/details/gt2aalolkub.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gt2kwkviqtb.html

[M07] 判断是否为主入口
来源：http://dali.kuanghao11.cn/Article/details/gt2jpfsexyb.html

Py:   if __name__ == "__main__":
来源：http://dali.birdmap.top/Article/details/gt2yfuvsbox.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sweek.top/Article/details/gt2yixxqgcc.html

JS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lbtslief.html

TS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gt2csgccufq.html

Java: public static void main(String[] args)
来源：http://dali.cucudq.cn/Article/details/gt2txhlzygc.html

Go:   func main()
来源：http://dali.redwolf501.top/Article/details/gt2epqkhogt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.svipenyu.cn/Article/details/gt2ufsxujck.html

C#:   static void Main(string[] args)
来源：http://dali.yanxiufei.cn/Article/details/gt2pzhulxhp.html

[M08] 获取系统与运行时信息
来源：http://dali.ehwqpu.com/Article/details/gt2oarrqdnz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xylfe.cn/Article/details/gt2skdhnkhi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigfzy.top/Article/details/gt2vmeswoou.html

JS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gt2kmcyxcim.html

TS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gt2rimwuqyp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.quarkkingdee.top/Article/details/gt2vgcclcuz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guannengcc.top/Article/details/gt2kdiqgcwa.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ppjwa.cn/Article/details/gt2ilggmhta.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ppjwa.cn/Article/details/gt2urbhmdrp.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2jzapnvmg.html

N. 数据结构与算法
来源：http://dali.xuetiantiany.cn/Article/details/gt2qbsdnchz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2gaaifuje.html

[N01] 二分查找（有序数组）
来源：http://dali.kuanghao11.cn/Article/details/gt2suskhhhv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jqwrpbdi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gogol.net.cn/Article/details/gt2witsaikj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gt2aaqrhenj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gt2cbfwqerc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2diudjhvb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2gixaiwia.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuanzx.com/Article/details/gt2aiodeytj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2aweupoud.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jiagoushi.top/Article/details/gt2fjdzldqs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gt2tytlwgkj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnqzz.top/Article/details/gt2ucuiquwy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gt2mzamrpwl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gt2ykbwazdf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wburjqbs.html

Go:   slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gt2qymrmzxu.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gt2qjttrhoe.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.316326.xyz/Article/details/gt2dxfnzhbw.html

[N03] 快速排序（分治示例）
来源：http://dali.xuanzx.com/Article/details/gt2nuftvlch.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenjidiqi.icu/Article/details/gt2toiplfxg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tanke756.top/Article/details/gt2ddtlfedt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gt2huhxicsu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gt2wxfwtsxq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cdnleiting.top/Article/details/gt2cayokskl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xinyue.icu/Article/details/gt2wurslxae.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.smart0.xyz/Article/details/gt2xiinrrew.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aibaodan.cn/Article/details/gt2bsxefumm.html

[N04] 斐波那契数列
来源：http://dali.shuidangran.top/Article/details/gt2bcgcedkk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nkqylzxd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.birdmap.top/Article/details/gt2ldtiwxut.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gt2xivxfnye.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qryokyfx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.iojbl.cn/Article/details/gt2pgwczofk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cdnleiting.top/Article/details/gt2vwzaxyxx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cxdzlbyj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vhcravbr.html

[N05] 最大公约数
来源：http://dali.bjfxy.top/Article/details/gt2cdnjfaax.html

Py:   math.gcd(a, b)
来源：http://dali.wangdashe.top/Article/details/gt2vpirhbqg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gt2mnfehqyu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gt2rjpmniht.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gt2gahwrqrp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zycfv.cn/Article/details/gt2vdxbgogx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.smart0.xyz/Article/details/gt2hmetheen.html

Ruby: a.gcd(b)
来源：http://dali.yj20258888.top/Article/details/gt2bpbkrqgd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jiagoushi.top/Article/details/gt2jfavnori.html

[N06] 判断回文字符串
来源：http://dali.gzhubu.top/Article/details/gt2huozaodr.html

Py:   s == s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gt2bgmnnodj.html

PHP:  $s === strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hippphbz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2ecpejomi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gt2whekwaly.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hysaishi.cn/Article/details/gt2yijgfdoe.html

Go:   // 双指针从两端比较
来源：http://dali.hnxiangtu.top/Article/details/gt2ffimzphi.html

Ruby: s == s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gt2efervkdh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gt2bvwpmcjb.html

[N07] 两数之和（返回下标）
来源：http://dali.vqdsnc.cn/Article/details/gt2infkvmum.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.316326.xyz/Article/details/gt2rlfdxvad.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hysaishi.cn/Article/details/gt2kckthfbu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.havefunace.top/Article/details/gt2usruqcbi.html

TS:   // 手写 Map<string, number>
来源：http://dali.kuanghao11.cn/Article/details/gt2pqscdmmx.html

Java: // 手写 HashMap
来源：http://dali.sysykeji.top/Article/details/gt2bxtdqdwq.html

Go:   // 手写 map[int]int
来源：http://dali.316326.xyz/Article/details/gt2glkwwruo.html

Ruby: // 手写 Hash
来源：http://dali.yuanzhike.top/Article/details/gt2kkkokxca.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.haohaochexian.top/Article/details/gt2kwcrbdrx.html

[N08] 生成全排列
来源：http://dali.wangshuangyany.cn/Article/details/gt2ajyyxkin.html

Py:   itertools.permutations(arr)
来源：http://dali.zycfv.cn/Article/details/gt2gevztsqm.html

PHP:  // 手写递归交换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uuyfzlpd.html

JS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gt2jpmncqvr.html

TS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gt2ppiyhvqn.html

Java: // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gt2aqcdooqj.html

Go:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gt2qlkkxiqe.html

Ruby: arr.permutation.to_a
来源：http://dali.hammf.cn/Article/details/gt2dwduozmv.html

C#:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gt2innnlxtk.html

[N09] 栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2neslqrfd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kiuqmana.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.bjfxy.top/Article/details/gt2rwglstlk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2mrgypwav.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cashguo.top/Article/details/gt2bmouxodv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sysykeji.top/Article/details/gt2cksgyawo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yueranfly.top/Article/details/gt2crmasobu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gt2ultgcfbt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenzaomai.com/Article/details/gt2tyqnsauv.html

[N10] 链表节点定义
来源：http://dali.tianlin.xyz/Article/details/gt2dfyjswkc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zycfv.cn/Article/details/gt2ahwgyyaa.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ppjwa.cn/Article/details/gt2gpfpcuiu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cdnleiting.top/Article/details/gt2lbggfwxg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tian-w.cn/Article/details/gt2lgwinurb.html

Java: class Node { int v; Node next; }
来源：http://dali.yvedp.cn/Article/details/gt2mcmfqjda.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xinyue.icu/Article/details/gt2swtymrdv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aibaodan.cn/Article/details/gt2shcqmxin.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zdqjudy.top/Article/details/gt2mzdnifyk.html

[N11] 二叉树中序遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2dcglqjvr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sweek.top/Article/details/gt2thhxrjkv.html

PHP:  // 手写递归函数
来源：http://dali.hfpthk.cn/Article/details/gt2lqvlqkmn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ehwqpu.com/Article/details/gt2hyxrabcc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gt2miazpwgg.html

Java: // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2nxkyubdp.html

Go:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gt2hgiionyn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xylfe.cn/Article/details/gt2mhwbybkf.html

C#:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gt2jjnbyvyh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgufenzy.top/Article/details/gt2mipecsym.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.havefunace.top/Article/details/gt2abnigjfq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zycfv.cn/Article/details/gt2cilqpfyv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aybovweb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gt2irvuweop.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gt2fvrfwayh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aizwys.cn/Article/details/gt2pwlkmqzx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tgirppss.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mncfobgw.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2vuoxfwvk.html

O. 并发与异步
来源：http://dali.zdqjudy.top/Article/details/gt2hzilidmb.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2hoiltxxz.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gt2woffcjkx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hongshengwenyu.top/Article/details/gt2kiauahbb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2nxttkryq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sxryk.cn/Article/details/gt2hcazqaxw.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gt2vbscpsco.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zlpnsgky.html

Go:   go f()
来源：http://dali.cheryme.top/Article/details/gt2pmvhgfxr.html

Ruby: Thread.new { f }
来源：http://dali.yuanzhike.top/Article/details/gt2zooetfsf.html

C#:   Task.Run(() => F());
来源：http://dali.hammf.cn/Article/details/gt2vtlfbxbt.html

[O02] 使用线程池
来源：http://dali.hnqzz.top/Article/details/gt2anjtwqgg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sweek.top/Article/details/gt2rteguyal.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dianchejie.cn/Article/details/gt2lmxnbcpb.html

JS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gt2wpevcjtd.html

TS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gt2syjvxqdw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yonumen.top/Article/details/gt2jigsqaoy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hammf.cn/Article/details/gt2aywfseag.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jiagoushi.top/Article/details/gt2homnlwfs.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sysykeji.top/Article/details/gt2heuvrizb.html

[O03] 加锁保护共享数据
来源：http://dali.sweek.top/Article/details/gt2ccmvtqne.html

Py:   with lock: shared += 1
来源：http://dali.hnqzz.top/Article/details/gt2avabxhbm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tian-w.cn/Article/details/gt2sojbrlyh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj202588.top/Article/details/gt2txtcnioc.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gt2cyzqkjie.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xrhrhopl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenzaomai.com/Article/details/gt2nqidtlje.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nwbrower.top/Article/details/gt2cipyieod.html

C#:   lock (gate) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gt2twlhxyro.html

[O04] 定义异步函数并等待
来源：http://dali.wangshuangyany.cn/Article/details/gt2mgxuqhrl.html

Py:   async def f():⏎    await g()
来源：http://dali.kuanghao11.cn/Article/details/gt2qnumeumv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dianchejie.cn/Article/details/gt2ganyecrf.html

JS:   async function f() { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gt2hwngnxop.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2xzqpdnxr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gt2bqnvheqe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.c1oappe.top/Article/details/gt2ukzxjabj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenzaomai.com/Article/details/gt2bopjyyjt.html

C#:   async Task F() { await G(); }
来源：http://dali.cashguo.top/Article/details/gt2qnzqxpvq.html

[O05] 并发执行并等待全部完成
来源：http://dali.gotoacloud.top/Article/details/gt2pyuooksp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuanzx.com/Article/details/gt2nurcnlry.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.guowangkeji.top/Article/details/gt2hypeqill.html

JS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uukglskx.html

TS:   await Promise.all(tasks)
来源：http://dali.yonumen.top/Article/details/gt2vgxlpwdr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.bjfxy.top/Article/details/gt2owzpserg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.snrcjt.cn/Article/details/gt2akugyslv.html

Ruby: threads.map(&:join)
来源：http://dali.c1oappe.top/Article/details/gt2laqlzxjj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hfpthk.cn/Article/details/gt2zqkucsjz.html

[O06] 使用进程池
来源：http://dali.kuanghao11.cn/Article/details/gt2qenwevil.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mtkdlzjl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vqkvmqfk.html

JS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gt2ztcidxqq.html

TS:   // child_process / cluster 模块
来源：http://dali.hnxiangtu.top/Article/details/gt2pvabajuk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenzaomai.com/Article/details/gt2ncedfnfc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tianlin.xyz/Article/details/gt2glfurvll.html

Ruby: // fork 块
来源：http://dali.jianghu66.top/Article/details/gt2njjuhjlw.html

C#:   Parallel.For
来源：http://dali.redwolf501.top/Article/details/gt2nchhzgbw.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ryuizqrc.html

P. 常用工具函数
来源：http://dali.dianchejie.cn/Article/details/gt2kcxogztx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2rlkcabdt.html

[P01] 生成 UUID
来源：http://dali.vqdsnc.cn/Article/details/gt2mcoqbcfq.html

Py:   str(uuid.uuid4())
来源：http://dali.tanke756.top/Article/details/gt2eewiherf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.havefunace.top/Article/details/gt2scylsjpf.html

JS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gt2foiokedt.html

TS:   crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gt2zmxytwnz.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lscjrjqp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.svipenyu.cn/Article/details/gt2iaaxtysf.html

Ruby: SecureRandom.uuid
来源：http://dali.yonumen.top/Article/details/gt2rakocpoe.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zycfv.cn/Article/details/gt2ybdrorlh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ydzc1.top/Article/details/gt2gjmpqbfs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.9152youxi.cn/Article/details/gt2pqcgeegp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shzxlz.cn/Article/details/gt2dntvcenx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuetiantiany.cn/Article/details/gt2gzeqsxls.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daria6918.cn/Article/details/gt2giphanbl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ieqwanvw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gaohongyu789.top/Article/details/gt2qsfgkocg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sxryk.cn/Article/details/gt2gqpidqpo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.316326.xyz/Article/details/gt2mqprgdxu.html

[P03] 生成短随机字符串
来源：http://dali.xuanzx.com/Article/details/gt2juogueqt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.redwolf501.top/Article/details/gt2ifjevbrc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.316326.xyz/Article/details/gt2zpcoadgc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2twxixdkk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gt2aamxskms.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cqqwz.cn/Article/details/gt2ctzupjwx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yanxiufei.cn/Article/details/gt2qyerrcfg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ppjwa.cn/Article/details/gt2pisfdfvn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nanxuanxn.top/Article/details/gt2ujarfsbh.html

[P04] 求长度
来源：http://dali.316326.xyz/Article/details/gt2ntfdmujj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnxiangtu.top/Article/details/gt2bdbtydbm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gt2emveatdp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shuidangran.top/Article/details/gt2pgfgiwul.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258.top/Article/details/gt2cfhyvbfq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258.top/Article/details/gt2dldsczmq.html

Go:   len(arr);  len(m)
来源：http://dali.zdqjudy.top/Article/details/gt2nrrmfatf.html

Ruby: x.length;  x.size
来源：http://dali.tian-w.cn/Article/details/gt2ucuqinhn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhengqikj.top/Article/details/gt2zuptsbeh.html


<!-- 参考信息 -->