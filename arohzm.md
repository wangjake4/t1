代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sysykeji.top/Article/details/gt2ojtokkmw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yueranfly.top/Article/details/gt2akjgbice.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxuanxn.top/Article/details/gt2yxzoxlic.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aibaodan.cn/Article/details/gt2rhpkuefw.html

[L07] 处理 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gt2ncgjgggp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenlongwang.top/Article/details/gt2aycjtwrm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xylfe.cn/Article/details/gt2qzpbiatp.html

JS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gt2mqqxewxd.html

TS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gt2ctmkesky.html

Java: resp.statusCode()
来源：http://dali.zhoulong.xyz/Article/details/gt2syagjboy.html

Go:   resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gt2dcqkfzjg.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gt2mlbmcczv.html

C#:   (int)resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gt2wdjyyuvh.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zdmbdaut.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.andypj.xyz/Article/details/gt2tqaxsccm.html

PHP:  curl_multi_init() 系列
来源：http://dali.redwolf501.top/Article/details/gt2kowlenzl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gt2sunnpaxk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gt2dvbdmezh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yanxiufei.cn/Article/details/gt2nqzdiudv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxinkj.top/Article/details/gt2dhnihvtr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gt2ymskgtjt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ybcxt.top/Article/details/gt2mzqrlnhj.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ncjhxneq.html

M. 命令行 / 进程 / 环境
来源：http://dali.yanxiufei.cn/Article/details/gt2hblrzmnf.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2gvprnjip.html

[M01] 读取命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gt2yumehvdf.html

Py:   sys.argv[1:]
来源：http://dali.ppjwa.cn/Article/details/gt2mlepifox.html

PHP:  $argv;  $argc;
来源：http://dali.hfpthk.cn/Article/details/gt2abbdqwwy.html

JS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gt2fbujtizr.html

TS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gt2agatfmpa.html

Java: args 数组（main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gt2nobxhdwb.html

Go:   os.Args[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fgqgqexp.html

Ruby: ARGV
来源：http://dali.gotoacloud.top/Article/details/gt2ppsadkbk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gt2yzfwfxzw.html

[M02] 读取环境变量
来源：http://dali.316326.xyz/Article/details/gt2lvbqakkx.html

Py:   os.environ.get("HOME")
来源：http://dali.zhengqikj.top/Article/details/gt2ocwfalvs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.havefunace.top/Article/details/gt2uqdlnthy.html

JS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gt2xtflrybq.html

TS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gt2eclpizqx.html

Java: System.getenv("HOME")
来源：http://dali.316326.xyz/Article/details/gt2snvitebu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.redwolf501.top/Article/details/gt2htrvupct.html

Ruby: ENV["HOME"]
来源：http://dali.bjfxy.top/Article/details/gt2zhegkllj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2luwphoak.html

[M03] 执行外部命令
来源：http://dali.pengpengdd.cyou/Article/details/gt2hbroniwy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hfpthk.cn/Article/details/gt2tjwevcgu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dashuyun.cn/Article/details/gt2xpfkpbtr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gt2zfxrmcbu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gt2mexzcdgp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hywenlv.cn/Article/details/gt2xqditgbp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.iojbl.cn/Article/details/gt2hzhocafc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hysaishi.cn/Article/details/gt2siufetga.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ehwqpu.com/Article/details/gt2gxgtkmdv.html

[M04] 获取当前工作目录
来源：http://dali.tianlin.xyz/Article/details/gt2vbfsdmcy.html

Py:   os.getcwd()
来源：http://dali.redwolf501.top/Article/details/gt2zkmugwbd.html

PHP:  getcwd();
来源：http://dali.zhengqikj.top/Article/details/gt2hgasfmay.html

JS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gt2mepnshez.html

TS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gt2cfzamnut.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgufenzy.top/Article/details/gt2iwrbdtcz.html

Go:   os.Getwd()
来源：http://dali.jyoumei.cn/Article/details/gt2shivytwk.html

Ruby: Dir.pwd
来源：http://dali.pycfn.com/Article/details/gt2dbbhkhap.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jyoumei.cn/Article/details/gt2toyzcxtk.html

[M05] 设置退出码
来源：http://dali.chenlongwang.top/Article/details/gt2djcsimbp.html

Py:   sys.exit(1)
来源：http://dali.ivvv.top/Article/details/gt2vfyuesyy.html

PHP:  exit(1);
来源：http://dali.xylfe.cn/Article/details/gt2tvjhjngm.html

JS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bldfbxpd.html

TS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2igyqsggl.html

Java: System.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2fhhcqhdk.html

Go:   os.Exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2saeqazzh.html

Ruby: exit 1
来源：http://dali.yonumen.top/Article/details/gt2tfqqxrjn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.0kj1m.cn/Article/details/gt2jygojhae.html

[M06] 向标准错误输出
来源：http://dali.hywenlv.cn/Article/details/gt2eyfhewpo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dianchejie.cn/Article/details/gt2tvofzsph.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daxiang520.top/Article/details/gt2mlnyglam.html

JS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gt2acinsafe.html

TS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2irkudppw.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gt2mlgflnwe.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yangfankeji.com/Article/details/gt2chbiyjzr.html

Ruby: warn "err"
来源：http://dali.xinyue.icu/Article/details/gt2bcqlhvcy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shzxlz.cn/Article/details/gt2abytysgz.html

[M07] 判断是否为主入口
来源：http://dali.quarkkingdee.top/Article/details/gt2twnhncxf.html

Py:   if __name__ == "__main__":
来源：http://dali.daria6918.cn/Article/details/gt2elhkgxrb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aizwys.cn/Article/details/gt2hbputqik.html

JS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gt2uqamynrb.html

TS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gt2ragagxvt.html

Java: public static void main(String[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qhnsmakp.html

Go:   func main()
来源：http://dali.hysaishi.cn/Article/details/gt2rhjlnoar.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ybcxt.top/Article/details/gt2orgcfdwe.html

C#:   static void Main(string[] args)
来源：http://dali.jyoumei.cn/Article/details/gt2nqdiwtje.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwvbmeax.html

Py:   platform.system();  platform.python_version()
来源：http://dali.vqdsnc.cn/Article/details/gt2ffjuypfs.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sysykeji.top/Article/details/gt2tmspzirv.html

JS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gt2tlkgngry.html

TS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gt2guernqaq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.0kj1m.cn/Article/details/gt2dfpugvuu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xylfe.cn/Article/details/gt2tkinurrl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cashguo.top/Article/details/gt2rhkpdaxc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uceppnfc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2vgpxilxp.html

N. 数据结构与算法
来源：http://dali.redwolf501.top/Article/details/gt2zqqypuvt.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2sqwiewri.html

[N01] 二分查找（有序数组）
来源：http://dali.xuetiantiany.cn/Article/details/gt2wqlcapiz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2rofsxvus.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.316326.xyz/Article/details/gt2aotorwsn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gt2wkudikxs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gt2ujelkxvs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gt2fmoaasef.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2trqkljhf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenlongwang.top/Article/details/gt2bopwzvcm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2hcspbtmn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aizwys.cn/Article/details/gt2swpfkufc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gt2wzkvtrww.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sufxvd.cn/Article/details/gt2egdfqxua.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gt2qqjbdwyg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bblzxoah.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nzlybbym.html

Go:   slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gt2ejnpeqhu.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gt2thautjii.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cashguo.top/Article/details/gt2fqsqniki.html

[N03] 快速排序（分治示例）
来源：http://dali.c1oappe.top/Article/details/gt2yhbifxvf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.feifeiyinyue.top/Article/details/gt2nhghlkeg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2efqmfabc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gt2btnbhghl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gt2uuowbllh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2njkjewnv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuanzhike.top/Article/details/gt2imwnzdrf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hfpthk.cn/Article/details/gt2cxckqxie.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guannengcc.top/Article/details/gt2melsrkvz.html

[N04] 斐波那契数列
来源：http://dali.kuanghao11.cn/Article/details/gt2ngdsjuyn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfojxsis.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gt2wgqgnmzc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gt2bobkjbki.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2srkajvtv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gt2tumyhmnt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jianghu66.top/Article/details/gt2uiwtcwvd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gt2anfdgahg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gt2jpqvvxlm.html

[N05] 最大公约数
来源：http://dali.ehwqpu.com/Article/details/gt2ykuwxqxv.html

Py:   math.gcd(a, b)
来源：http://dali.xuanzx.com/Article/details/gt2ntgkoclb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhengqikj.top/Article/details/gt2crwwbvvg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gt2gvmqkmqm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.bjfxy.top/Article/details/gt2wjobwals.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.meibo888.top/Article/details/gt2rtmvvqjp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigufen.top/Article/details/gt2pezqoquh.html

Ruby: a.gcd(b)
来源：http://dali.guowangkeji.top/Article/details/gt2shbbedku.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jonyzkfn.html

[N06] 判断回文字符串
来源：http://dali.tianlin.xyz/Article/details/gt2wdszyiks.html

Py:   s == s[::-1]
来源：http://dali.ppjwa.cn/Article/details/gt2uwglwapz.html

PHP:  $s === strrev($s);
来源：http://dali.mhx1999.top/Article/details/gt2hagvymwx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gt2wezmvpwr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gt2aavzqiuq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhengqikj.top/Article/details/gt2soiusjyu.html

Go:   // 双指针从两端比较
来源：http://dali.redwolf501.top/Article/details/gt2kogbcfep.html

Ruby: s == s.reverse
来源：http://dali.zdqjudy.top/Article/details/gt2clkqnedf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gt2vtfiumaw.html

[N07] 两数之和（返回下标）
来源：http://dali.hongshengwenyu.top/Article/details/gt2lqpfktlw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yongpay.top/Article/details/gt2zuxkblrz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258888.top/Article/details/gt2qmwuefmz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ngibxobw.html

TS:   // 手写 Map<string, number>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dwvchnbr.html

Java: // 手写 HashMap
来源：http://dali.ydzc1.top/Article/details/gt2nntbumyh.html

Go:   // 手写 map[int]int
来源：http://dali.zycfv.cn/Article/details/gt2slzobozo.html

Ruby: // 手写 Hash
来源：http://dali.dashuyun.cn/Article/details/gt2cggxpbgx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhongyouzk.top/Article/details/gt2piqyggft.html

[N08] 生成全排列
来源：http://dali.andypj.xyz/Article/details/gt2acfasgpl.html

Py:   itertools.permutations(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2ticrfjzf.html

PHP:  // 手写递归交换
来源：http://dali.yvedp.cn/Article/details/gt2fjadzhcd.html

JS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2tkagpllv.html

TS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gt2qukieueb.html

Java: // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gt2gczinpsb.html

Go:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lxtxweug.html

Ruby: arr.permutation.to_a
来源：http://dali.sysykeji.top/Article/details/gt2cusfzrkc.html

C#:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2tqsmztqz.html

[N09] 栈与队列
来源：http://dali.guowangkeji.top/Article/details/gt2fsalekdt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258888.top/Article/details/gt2gogyuhtl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daxiang520.top/Article/details/gt2ezpadjlw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gt2homtztro.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigufen.top/Article/details/gt2ggrpwhwz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jiagoushi.top/Article/details/gt2ctsshjwv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yanxiufei.cn/Article/details/gt2wyujwzwv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gt2baohcnml.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sweek.top/Article/details/gt2vbjpptga.html

[N10] 链表节点定义
来源：http://dali.hywenlv.cn/Article/details/gt2hrgujewc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258888.top/Article/details/gt2nqmmwgad.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuxming.cn/Article/details/gt2fyolbalg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xinyue.icu/Article/details/gt2eslpuzez.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lahocvgu.html

Java: class Node { int v; Node next; }
来源：http://dali.ppjwa.cn/Article/details/gt2wqsblfmp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenzaomai.com/Article/details/gt2etmbkozs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sysykeji.top/Article/details/gt2pkxzfrpb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cucudq.cn/Article/details/gt2lynbtbza.html

[N11] 二叉树中序遍历
来源：http://dali.cqqwz.cn/Article/details/gt2rgzgehwr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj20258888.top/Article/details/gt2hgtvxewl.html

PHP:  // 手写递归函数
来源：http://dali.gogol.net.cn/Article/details/gt2qtesmbwr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gt2soyjewqg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fengsongda.top/Article/details/gt2ribfyjqb.html

Java: // 手写递归
来源：http://dali.ivvv.top/Article/details/gt2wygeqloy.html

Go:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gt2hgzdwoil.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.quarkkingdee.top/Article/details/gt2ecemczlf.html

C#:   // 手写递归
来源：http://dali.tian-w.cn/Article/details/gt2ymdyzdsx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yanxiufei.cn/Article/details/gt2nrfepmwo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.snrcjt.cn/Article/details/gt2cgspumcf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.dianchejie.cn/Article/details/gt2zodyxmdt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gt2vdvbcpvf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gt2nfuogrke.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxuanxn.top/Article/details/gt2vnjgnoho.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aizwys.cn/Article/details/gt2gheacwfb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xinyue.icu/Article/details/gt2rifqiwex.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gt2txuvrkug.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2wykoythk.html

O. 并发与异步
来源：http://dali.wangshuangyany.cn/Article/details/gt2dqyqrgnm.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2gtuvyqts.html

[O01] 启动一个线程
来源：http://dali.xuetiantiany.cn/Article/details/gt2zfjlmqyz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xinyue.icu/Article/details/gt2ffkkqrdm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ehwqpu.com/Article/details/gt2brfeutrr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cashguo.top/Article/details/gt2bnnjezbu.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2klmmwnld.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhengqikj.top/Article/details/gt2rtnszmwr.html

Go:   go f()
来源：http://dali.c1oappe.top/Article/details/gt2ppwfrbhj.html

Ruby: Thread.new { f }
来源：http://dali.9152youxi.cn/Article/details/gt2gfxdfgzp.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigfzy.top/Article/details/gt2lizgsfis.html

[O02] 使用线程池
来源：http://dali.316326.xyz/Article/details/gt2jbgfvnex.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nwbrower.top/Article/details/gt2decdrspe.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yangfankeji.com/Article/details/gt2ozouavpm.html

JS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gt2jenkxdle.html

TS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gt2mjnudbof.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hammf.cn/Article/details/gt2moaqyrkf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhongyouzk.top/Article/details/gt2rgbhfdlg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hammf.cn/Article/details/gt2hdibbfzy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhiwuduotai.top/Article/details/gt2kszinovv.html

[O03] 加锁保护共享数据
来源：http://dali.nwbrower.top/Article/details/gt2laimebmu.html

Py:   with lock: shared += 1
来源：http://dali.havefunace.top/Article/details/gt2awerpdvw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.feifeiyinyue.top/Article/details/gt2qzzfbrmq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.bjfxy.top/Article/details/gt2szymmjxw.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gt2blujlama.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gt2jfsaickt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sxryk.cn/Article/details/gt2jdipjvmw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2nfmfzgxd.html

C#:   lock (gate) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gt2zqavbulv.html

[O04] 定义异步函数并等待
来源：http://dali.fengsongda.top/Article/details/gt2qksibvdd.html

Py:   async def f():⏎    await g()
来源：http://dali.zhiwuduotai.top/Article/details/gt2nwcpvyuk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gogol.net.cn/Article/details/gt2svzprqqm.html

JS:   async function f() { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gt2qagvjwqu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ybcxt.top/Article/details/gt2vrrpmagg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ydzc1.top/Article/details/gt2zmydbsff.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shuidangran.top/Article/details/gt2wxhnqqhh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangshuangyany.cn/Article/details/gt2zmffwqys.html

C#:   async Task F() { await G(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zcywhlht.html

[O05] 并发执行并等待全部完成
来源：http://dali.fengsongda.top/Article/details/gt2yvnbjzdz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhixingplan.top/Article/details/gt2ompxgiof.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.guowangkeji.top/Article/details/gt2qppkbtgg.html

JS:   await Promise.all(tasks)
来源：http://dali.yvedp.cn/Article/details/gt2bsvulffr.html

TS:   await Promise.all(tasks)
来源：http://dali.meibo888.top/Article/details/gt2gdkturah.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gaohongyu789.top/Article/details/gt2dtinyzyp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhengqikj.top/Article/details/gt2gevcfraq.html

Ruby: threads.map(&:join)
来源：http://dali.pycfn.com/Article/details/gt2onuyuspc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangdashe.top/Article/details/gt2tivcugmv.html

[O06] 使用进程池
来源：http://dali.gaohongyu789.top/Article/details/gt2ppnipmpd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xziqi.cn/Article/details/gt2slcbbsol.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sxryk.cn/Article/details/gt2wjouwiib.html

JS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gt2nevvkxxo.html

TS:   // child_process / cluster 模块
来源：http://dali.cheryme.top/Article/details/gt2nhsrwlvc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sufxvd.cn/Article/details/gt2fvuqjrty.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yangfankeji.com/Article/details/gt2vuvhjccn.html

Ruby: // fork 块
来源：http://dali.mhx1999.top/Article/details/gt2rrqoxoqr.html

C#:   Parallel.For
来源：http://dali.hongshengwenyu.top/Article/details/gt2gfqlaoxw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2glooozlb.html

P. 常用工具函数
来源：http://dali.snrcjt.cn/Article/details/gt2qdntpygr.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2vjajbwqd.html

[P01] 生成 UUID
来源：http://dali.kuanghao11.cn/Article/details/gt2gfhbkmda.html

Py:   str(uuid.uuid4())
来源：http://dali.guowangkeji.top/Article/details/gt2tisgbfua.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fengsongda.top/Article/details/gt2idinezls.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gt2uqgrnyuq.html

TS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gt2cyqxzkqw.html

Java: UUID.randomUUID().toString()
来源：http://dali.ybcxt.top/Article/details/gt2zxeetvdp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.kuanghao11.cn/Article/details/gt2unduevhd.html

Ruby: SecureRandom.uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ypankqlj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigfzy.top/Article/details/gt2tfszlljg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fzhhl.top/Article/details/gt2lgrzttob.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mdphuzxn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.bjfxy.top/Article/details/gt2ctecjeql.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guannengcc.top/Article/details/gt2klfbtxpp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.birdmap.top/Article/details/gt2sbhroepb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jianghu66.top/Article/details/gt2jhsfwure.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zycfv.cn/Article/details/gt2pmggjwjm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2alatuybu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jyoumei.cn/Article/details/gt2wauadbjo.html

[P03] 生成短随机字符串
来源：http://dali.yj20258.top/Article/details/gt2fsalhyay.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yvedp.cn/Article/details/gt2pkyqexuf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gogol.net.cn/Article/details/gt2ylnzrium.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ehwqpu.com/Article/details/gt2wqvmgdza.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jianghu66.top/Article/details/gt2djituhbs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ctkoufzw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.quarkkingdee.top/Article/details/gt2bklkxwcs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daria6918.cn/Article/details/gt2rwigpmki.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yongpay.top/Article/details/gt2mxzbludb.html

[P04] 求长度
来源：http://dali.jlsjyb.cn/Article/details/gt2tvembeyp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ehwqpu.com/Article/details/gt2ifvduwpt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gt2wwdvzwbf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gt2xpsdrrub.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gt2hpzahmep.html


<!-- 参考信息 -->