代发 wailian999

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwikfiux.html

PHP:  json_decode($body, true);
来源：http://dali.chenlongwang.top/Article/details/gt2sdnijbal.html

JS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gt2xtjgzwhf.html

TS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gt2opmgfcuz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yueranfly.top/Article/details/gt2vjnuwdod.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yueranfly.top/Article/details/gt2mrstkrvm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cheryme.top/Article/details/gt2vfytzxpn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ybcxt.top/Article/details/gt2vhcebmxd.html

[L07] 处理 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gt2gcklyiju.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pengpengdd.cyou/Article/details/gt2rnhnsddc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuanzhike.top/Article/details/gt2dhqzgktv.html

JS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gt2usdpvndw.html

TS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gt2kuqhnjhh.html

Java: resp.statusCode()
来源：http://dali.birdmap.top/Article/details/gt2dgzdxqqq.html

Go:   resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gt2cksrisdn.html

Ruby: resp.code.to_i
来源：http://dali.ppjwa.cn/Article/details/gt2nmnywelv.html

C#:   (int)resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gt2ztoylpbw.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnjexpo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuetiantiany.cn/Article/details/gt2iclccybi.html

PHP:  curl_multi_init() 系列
来源：http://dali.gzhubu.top/Article/details/gt2necukpvf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gt2ftwknknu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gt2wowwnmmw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.feifeiyinyue.top/Article/details/gt2todjpcgy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nwbrower.top/Article/details/gt2sptymbie.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jxmhvowz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuanzhike.top/Article/details/gt2fvvmyzlm.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2yflrbcbm.html

M. 命令行 / 进程 / 环境
来源：http://dali.tian-w.cn/Article/details/gt2bjawjriq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sxgqclrv.html

[M01] 读取命令行参数
来源：http://dali.sweek.top/Article/details/gt2ursntalc.html

Py:   sys.argv[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2krovpvaa.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258888.top/Article/details/gt2ooczhpdm.html

JS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gt2ddunieve.html

TS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gt2fqawtzcw.html

Java: args 数组（main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gt2jhgscxua.html

Go:   os.Args[1:]
来源：http://dali.iojbl.cn/Article/details/gt2runaiuyt.html

Ruby: ARGV
来源：http://dali.quarkkingdee.top/Article/details/gt2gsjkeiks.html

C#:   args 数组（Main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gt2ntlmmmmd.html

[M02] 读取环境变量
来源：http://dali.zhoulong.xyz/Article/details/gt2cvtwqhhs.html

Py:   os.environ.get("HOME")
来源：http://dali.xylfe.cn/Article/details/gt2pqyizlnj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gt2gvbcuhhv.html

JS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fblfjyii.html

TS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gt2epfpdtsn.html

Java: System.getenv("HOME")
来源：http://dali.sweek.top/Article/details/gt2aigrtofh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gt2uyusrduo.html

Ruby: ENV["HOME"]
来源：http://dali.meibo888.top/Article/details/gt2uofefbgi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2tsatgzrg.html

[M03] 执行外部命令
来源：http://dali.xylfe.cn/Article/details/gt2pzrrcfxp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guowangkeji.top/Article/details/gt2pqgnfhwe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.haohaochexian.top/Article/details/gt2nvcwjehi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gt2iffrjvzz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gt2knnvucxz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258888.top/Article/details/gt2mabhtmor.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ehwqpu.com/Article/details/gt2tfaukylv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shzxlz.cn/Article/details/gt2viczfxlz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sdaroity.html

[M04] 获取当前工作目录
来源：http://dali.yuxming.cn/Article/details/gt2qdawpfxs.html

Py:   os.getcwd()
来源：http://dali.yj20258888.top/Article/details/gt2dhxwvqwd.html

PHP:  getcwd();
来源：http://dali.yanxiufei.cn/Article/details/gt2mmhkxdor.html

JS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2jnghzsxt.html

TS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gt2veiyyyvw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hnqzz.top/Article/details/gt2amykykgp.html

Go:   os.Getwd()
来源：http://dali.sweek.top/Article/details/gt2gyakdcgo.html

Ruby: Dir.pwd
来源：http://dali.xinyue.icu/Article/details/gt2rhefgqby.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xqjtlgcy.html

[M05] 设置退出码
来源：http://dali.daria6918.cn/Article/details/gt2nynbsivu.html

Py:   sys.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2szmxqowh.html

PHP:  exit(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yezupnts.html

JS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gt2nvajianm.html

TS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2ctysliyb.html

Java: System.exit(1)
来源：http://dali.meibo888.top/Article/details/gt2blhhxesl.html

Go:   os.Exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2unlvvbxr.html

Ruby: exit 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jwoljthi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jianghu66.top/Article/details/gt2ugdcqlll.html

[M06] 向标准错误输出
来源：http://dali.9152youxi.cn/Article/details/gt2tbtmgkfh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gt2abztxzjw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangshuangyany.cn/Article/details/gt2jwnasxom.html

JS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gt2xladvwhw.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gt2ayelzryb.html

Java: System.err.println("err")
来源：http://dali.yj202588.top/Article/details/gt2apmabjko.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgfzy.top/Article/details/gt2wpdkfxor.html

Ruby: warn "err"
来源：http://dali.nanxuanxn.top/Article/details/gt2odzqnehx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fengsongda.top/Article/details/gt2dthmmijx.html

[M07] 判断是否为主入口
来源：http://dali.zhixingplan.top/Article/details/gt2yswgfrgb.html

Py:   if __name__ == "__main__":
来源：http://dali.yongpay.top/Article/details/gt2opaobame.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jqgufenzy.top/Article/details/gt2tqlmnmhw.html

JS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gt2bktmnpbk.html

TS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gt2psvwqybv.html

Java: public static void main(String[] args)
来源：http://dali.jqgufenzy.top/Article/details/gt2ooblxwaw.html

Go:   func main()
来源：http://dali.yj20258888.top/Article/details/gt2ocnllagd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yangfankeji.com/Article/details/gt2hpyzijfh.html

C#:   static void Main(string[] args)
来源：http://dali.zycfv.cn/Article/details/gt2xztwpndx.html

[M08] 获取系统与运行时信息
来源：http://dali.tian-w.cn/Article/details/gt2nzyssark.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rgfurqfh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxuanxn.top/Article/details/gt2aiucwcqj.html

JS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gt2aakysmes.html

TS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gt2uzjlfovo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zdqjudy.top/Article/details/gt2qmnczidx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhongyouzk.top/Article/details/gt2aeuzbkcy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.smart0.xyz/Article/details/gt2sqszmvap.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shzxlz.cn/Article/details/gt2fdvzbarj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2anonenfg.html

N. 数据结构与算法
来源：http://dali.jiagoushi.top/Article/details/gt2vygeonfj.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2dgpuhtai.html

[N01] 二分查找（有序数组）
来源：http://dali.yanxiufei.cn/Article/details/gt2bhqipkpr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2exutyceo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ydzc1.top/Article/details/gt2fwtlxlru.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmfzzjzq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zldogwfu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2lxgrbnmt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2gibialrt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aonwuwyv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2sxyjewnf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xylfe.cn/Article/details/gt2qtydcijc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gt2kfpqjlkc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhongyouzk.top/Article/details/gt2sdfuywuk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gt2gfaqhuee.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gt2unexwpqi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bjxxjezu.html

Go:   slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gt2izrgfdsh.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gt2rpvupjxn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shangyingyoupin.top/Article/details/gt2wtcirdkw.html

[N03] 快速排序（分治示例）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qxqnawrs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.haohaochexian.top/Article/details/gt2douiuxdf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.bjfxy.top/Article/details/gt2fvmqkxvy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ucqphjkd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gt2znzejntr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxuanxn.top/Article/details/gt2aqfvabux.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangdashe.top/Article/details/gt2pdgseuhn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigufen.top/Article/details/gt2ixygpxgk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.quarkkingdee.top/Article/details/gt2pmkynffv.html

[N04] 斐波那契数列
来源：http://dali.yj20258.top/Article/details/gt2yzljrbsf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2mslwqayx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rbwpidlt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gt2dzacbkiy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2aidfhyiw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gt2bgxpscsi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ybcxt.top/Article/details/gt2uxookass.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2oewiodip.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vyrhvnfi.html

[N05] 最大公约数
来源：http://dali.iojbl.cn/Article/details/gt2pokxjoul.html

Py:   math.gcd(a, b)
来源：http://dali.smart0.xyz/Article/details/gt2vqgemagl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ybcxt.top/Article/details/gt2fcjqlbyp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ivvv.top/Article/details/gt2pkdcvkvt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vrxgtehb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhixingplan.top/Article/details/gt2ralqaseo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.snrcjt.cn/Article/details/gt2yqwqeaua.html

Ruby: a.gcd(b)
来源：http://dali.daxiang520.top/Article/details/gt2attbhsik.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuanzhike.top/Article/details/gt2xvgtsnim.html

[N06] 判断回文字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2kxbxulll.html

Py:   s == s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gt2nykwdqkg.html

PHP:  $s === strrev($s);
来源：http://dali.aizwys.cn/Article/details/gt2ekdaxrri.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2ewsmrgvx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gt2wuxpaohx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigufen.top/Article/details/gt2mkzslwai.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pwqsjxif.html

Ruby: s == s.reverse
来源：http://dali.ehwqpu.com/Article/details/gt2ilhpvwsp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gt2jlqxitah.html

[N07] 两数之和（返回下标）
来源：http://dali.andypj.xyz/Article/details/gt2pdxjremd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gpoqpidh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yonumen.top/Article/details/gt2nnfbynfj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfzzytqm.html

TS:   // 手写 Map<string, number>
来源：http://dali.zdqjudy.top/Article/details/gt2jolkhtkd.html

Java: // 手写 HashMap
来源：http://dali.redwolf501.top/Article/details/gt2ifotlxbc.html

Go:   // 手写 map[int]int
来源：http://dali.jianghu66.top/Article/details/gt2juhpoemv.html

Ruby: // 手写 Hash
来源：http://dali.redwolf501.top/Article/details/gt2caykvmfo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.feifeiyinyue.top/Article/details/gt2duipnptk.html

[N08] 生成全排列
来源：http://dali.cucudq.cn/Article/details/gt2arbblqlx.html

Py:   itertools.permutations(arr)
来源：http://dali.xziqi.cn/Article/details/gt2xextixpw.html

PHP:  // 手写递归交换
来源：http://dali.yongpay.top/Article/details/gt2dhtbvblr.html

JS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gt2lfhiehim.html

TS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2xtzxoqlp.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yggisznm.html

Go:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2gxzejoev.html

Ruby: arr.permutation.to_a
来源：http://dali.zhiwuduotai.top/Article/details/gt2ogtrqxum.html

C#:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gt2ltxycygf.html

[N09] 栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2phywkeyk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daxiang520.top/Article/details/gt2fxgmcobn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pwrijjrr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2zvsggtkg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnqzz.top/Article/details/gt2zsnlaxnu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258.top/Article/details/gt2nlammnbu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jlsjyb.cn/Article/details/gt2umignwzj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gt2fbumdwwq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhoulong.xyz/Article/details/gt2hvtnoaic.html

[N10] 链表节点定义
来源：http://dali.hnxiangtu.top/Article/details/gt2rftqygmp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pycfn.com/Article/details/gt2wkvundfh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xuanzx.com/Article/details/gt2lmhkbkkh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhoulong.xyz/Article/details/gt2jxjpfmne.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kyelsrbv.html

Java: class Node { int v; Node next; }
来源：http://dali.shuidangran.top/Article/details/gt2epgpsfrr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxuanxn.top/Article/details/gt2uhmumion.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258888.top/Article/details/gt2myivdzbc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2fwgwlwqf.html

[N11] 二叉树中序遍历
来源：http://dali.0kj1m.cn/Article/details/gt2yxaqkpny.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.wangshuangyany.cn/Article/details/gt2ngrnljve.html

PHP:  // 手写递归函数
来源：http://dali.mhx1999.top/Article/details/gt2pwdqskgb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gt2jwdcvfkt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gt2ogoclijl.html

Java: // 手写递归
来源：http://dali.tian-w.cn/Article/details/gt2iibnuhcl.html

Go:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gt2kaccrrbf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuxming.cn/Article/details/gt2wcyneqhc.html

C#:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gt2ueyzskwt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jianghu66.top/Article/details/gt2cmkhqxko.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tanke756.top/Article/details/gt2hszniaox.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigfzy.top/Article/details/gt2jyizbpqh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gt2prubraui.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gt2mbbylcoh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gt2ouqcloan.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.kuanghao11.cn/Article/details/gt2brldyymy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yvedp.cn/Article/details/gt2yvpmjakc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gt2zqqbghao.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2vaspduir.html

O. 并发与异步
来源：http://dali.hnxiangtu.top/Article/details/gt2zashcvxu.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2omcoanxg.html

[O01] 启动一个线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zmandemy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.feifeiyinyue.top/Article/details/gt2yihzfkrl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2otxqcybq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxuanxn.top/Article/details/gt2ymhnvhgy.html

TS:   // 同 JS
来源：http://dali.kuanghao11.cn/Article/details/gt2ncjlychw.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnxiangtu.top/Article/details/gt2ogoabcpa.html

Go:   go f()
来源：http://dali.zhiwuduotai.top/Article/details/gt2llbpjlsw.html

Ruby: Thread.new { f }
来源：http://dali.xylfe.cn/Article/details/gt2mpmyvrnm.html

C#:   Task.Run(() => F());
来源：http://dali.gaohongyu789.top/Article/details/gt2rpyijtli.html

[O02] 使用线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cpyikwlb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jiagoushi.top/Article/details/gt2ioghynpd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigfzy.top/Article/details/gt2pfsvcaum.html

JS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gt2ufvawmmd.html

TS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gt2btgaokqb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cheryme.top/Article/details/gt2jbxfnfhi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tanke756.top/Article/details/gt2yelisjkq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pengpengdd.cyou/Article/details/gt2tucdyiko.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zdqjudy.top/Article/details/gt2pgxwzgsz.html

[O03] 加锁保护共享数据
来源：http://dali.jiagoushi.top/Article/details/gt2gmcjjvnr.html

Py:   with lock: shared += 1
来源：http://dali.tian-w.cn/Article/details/gt2nqxjggfp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yueranfly.top/Article/details/gt2btazcrrg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sysykeji.top/Article/details/gt2sjtbrgrq.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gt2jlafqlmt.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vupinucd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hywenlv.cn/Article/details/gt2hqhniehb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2yjchxoec.html

C#:   lock (gate) { shared++; }
来源：http://dali.sweek.top/Article/details/gt2gndlpwsk.html

[O04] 定义异步函数并等待
来源：http://dali.gaohongyu789.top/Article/details/gt2uosaerqj.html

Py:   async def f():⏎    await g()
来源：http://dali.tanke756.top/Article/details/gt2rwwvwebv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxinkj.top/Article/details/gt2hkibkldj.html

JS:   async function f() { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2bwgxyzjd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gogol.net.cn/Article/details/gt2jvfairob.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.feifeiyinyue.top/Article/details/gt2ouimjxpz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dashuyun.cn/Article/details/gt2kpvcvgam.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.kuanghao11.cn/Article/details/gt2ciruqsos.html

C#:   async Task F() { await G(); }
来源：http://dali.mhx1999.top/Article/details/gt2juxehgsv.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2szdevuxn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zdqjudy.top/Article/details/gt2wryztjet.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daria6918.cn/Article/details/gt2gsrkvzrb.html

JS:   await Promise.all(tasks)
来源：http://dali.yanxiufei.cn/Article/details/gt2inknzwol.html

TS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gt2qyrveahy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.dianchejie.cn/Article/details/gt2webosbjr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tanke756.top/Article/details/gt2gbtwdxli.html

Ruby: threads.map(&:join)
来源：http://dali.snrcjt.cn/Article/details/gt2ybhnsuti.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgfzy.top/Article/details/gt2alzrarae.html

[O06] 使用进程池
来源：http://dali.cdnleiting.top/Article/details/gt2lauwwaec.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cucudq.cn/Article/details/gt2syjpymyp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.iojbl.cn/Article/details/gt2iayqlpht.html

JS:   // child_process / cluster 模块
来源：http://dali.hammf.cn/Article/details/gt2zpvyokoh.html

TS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gt2xjuiqgxf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xylfe.cn/Article/details/gt2czwjekfx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhongyouzk.top/Article/details/gt2opghvnfv.html

Ruby: // fork 块
来源：http://dali.shangyingyoupin.top/Article/details/gt2dfafikul.html

C#:   Parallel.For
来源：http://dali.iojbl.cn/Article/details/gt2inehxidl.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2ovhxczis.html

P. 常用工具函数
来源：http://dali.yonumen.top/Article/details/gt2yblxvmef.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xodqxgor.html

[P01] 生成 UUID
来源：http://dali.haohaochexian.top/Article/details/gt2sgybrpty.html

Py:   str(uuid.uuid4())
来源：http://dali.guannengcc.top/Article/details/gt2vyyfropc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hnxiangtu.top/Article/details/gt2bjngtimn.html

JS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gt2khmjlvya.html

TS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gt2ejeyyuhi.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzspbpfy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xinyue.icu/Article/details/gt2paxmojqg.html

Ruby: SecureRandom.uuid
来源：http://dali.sxryk.cn/Article/details/gt2yftjuflh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yonumen.top/Article/details/gt2rdkmuqao.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hywenlv.cn/Article/details/gt2slzwuffs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gotoacloud.top/Article/details/gt2fzpkzybp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sweek.top/Article/details/gt2wkhbfmcx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2uftkoadt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.c1oappe.top/Article/details/gt2kyhecirt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yvedp.cn/Article/details/gt2pilfgqjn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2urfjaxiv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zycfv.cn/Article/details/gt2tzbcjkzk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258888.top/Article/details/gt2rmjnvmpu.html

[P03] 生成短随机字符串
来源：http://dali.chenlongwang.top/Article/details/gt2ybjmaoir.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gaohongyu789.top/Article/details/gt2hyxqbshr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.feifeiyinyue.top/Article/details/gt2gpneawdi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gt2qpdrpmwv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gt2udzkmcri.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shuidangran.top/Article/details/gt2wjmjxxed.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuetiantiany.cn/Article/details/gt2tuaydmpt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lptdhgdy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hongshengwenyu.top/Article/details/gt2nxyffzsv.html

[P04] 求长度
来源：http://dali.xuanzx.com/Article/details/gt2ofihisbj.html


<!-- 参考信息 -->