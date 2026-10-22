代发 wailian999

Py:   resp.json()
来源：http://dali.hfpthk.cn/Article/details/gt2kpbjxtvh.html

PHP:  json_decode($body, true);
来源：http://dali.fengsongda.top/Article/details/gt2yuulbkfx.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gt2earefnuk.html

TS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lvfhozjj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gt2puisbxas.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.snrcjt.cn/Article/details/gt2tkxxzqxq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.316326.xyz/Article/details/gt2vmhwzogk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nwbrower.top/Article/details/gt2ozkkywry.html

[L07] 处理 HTTP 状态码
来源：http://dali.ybcxt.top/Article/details/gt2ofyylrrs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jyoumei.cn/Article/details/gt2lorufmhk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ppjwa.cn/Article/details/gt2ypubmnnv.html

JS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gt2fxzbskwt.html

TS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gt2ovstrebv.html

Java: resp.statusCode()
来源：http://dali.daxiang520.top/Article/details/gt2ouoolhzw.html

Go:   resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gt2nvztrrwp.html

Ruby: resp.code.to_i
来源：http://dali.nwbrower.top/Article/details/gt2wtgnmggx.html

C#:   (int)resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gt2hhmrvpso.html

[L08] 并发请求多个地址
来源：http://dali.ivvv.top/Article/details/gt2cfqeobmd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.kuanghao11.cn/Article/details/gt2ohoqigfm.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenlongwang.top/Article/details/gt2hntsxpsj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gt2yfaijnfc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gt2jzhdkzkz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigfzy.top/Article/details/gt2nuyxibvm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhengqikj.top/Article/details/gt2hybribma.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hywenlv.cn/Article/details/gt2uvsxutsy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gotoacloud.top/Article/details/gt2mwdcwbck.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2bxlumrek.html

M. 命令行 / 进程 / 环境
来源：http://dali.yvedp.cn/Article/details/gt2dqgxiqsu.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2yqzuuwdi.html

[M01] 读取命令行参数
来源：http://dali.daxiang520.top/Article/details/gt2vwnyxpoy.html

Py:   sys.argv[1:]
来源：http://dali.sxryk.cn/Article/details/gt2cfkymgmm.html

PHP:  $argv;  $argc;
来源：http://dali.hysaishi.cn/Article/details/gt2vfdppkih.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gt2jhndqeau.html

TS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gt2netbzscp.html

Java: args 数组（main 方法参数）
来源：http://dali.ivvv.top/Article/details/gt2sqrxitbm.html

Go:   os.Args[1:]
来源：http://dali.zhengqikj.top/Article/details/gt2nkxymrsr.html

Ruby: ARGV
来源：http://dali.gaohongyu789.top/Article/details/gt2yadtufbj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gt2vpxakpoh.html

[M02] 读取环境变量
来源：http://dali.hfpthk.cn/Article/details/gt2eblobjlh.html

Py:   os.environ.get("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hfbpzeas.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tanke756.top/Article/details/gt2qmznviui.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rscpaxcz.html

TS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gt2hyytqhgx.html

Java: System.getenv("HOME")
来源：http://dali.xylfe.cn/Article/details/gt2qxmwnvnf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xziqi.cn/Article/details/gt2hiyusama.html

Ruby: ENV["HOME"]
来源：http://dali.guowangkeji.top/Article/details/gt2yezfsfch.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2jvhqtlsg.html

[M03] 执行外部命令
来源：http://dali.cucudq.cn/Article/details/gt2ljxopnex.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xuanzx.com/Article/details/gt2odubefte.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gotoacloud.top/Article/details/gt2gglxbfsd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gt2aoxwuwnc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gt2npeatcri.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hywenlv.cn/Article/details/gt2ybfcnbcr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guowangkeji.top/Article/details/gt2khtgnftt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yvedp.cn/Article/details/gt2mjjtrspk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vyhvedij.html

[M04] 获取当前工作目录
来源：http://dali.meibo888.top/Article/details/gt2kdsvvvfd.html

Py:   os.getcwd()
来源：http://dali.daria6918.cn/Article/details/gt2eujuhzsi.html

PHP:  getcwd();
来源：http://dali.hywenlv.cn/Article/details/gt2rwkzhtxe.html

JS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gt2ekeftalv.html

TS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gt2zyobyslm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuanzhike.top/Article/details/gt2mwnotmzy.html

Go:   os.Getwd()
来源：http://dali.gogol.net.cn/Article/details/gt2ticjymzx.html

Ruby: Dir.pwd
来源：http://dali.cucudq.cn/Article/details/gt2upakiinb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.snrcjt.cn/Article/details/gt2ldsruzde.html

[M05] 设置退出码
来源：http://dali.9152youxi.cn/Article/details/gt2cudcqdbn.html

Py:   sys.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ioahxcnh.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2hwnjqpzs.html

JS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2lknubxsb.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2gyvtxlkq.html

Java: System.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2gronkade.html

Go:   os.Exit(1)
来源：http://dali.c1oappe.top/Article/details/gt2vvfnldif.html

Ruby: exit 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2tieqdsrh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258.top/Article/details/gt2lngnubsb.html

[M06] 向标准错误输出
来源：http://dali.ydzc1.top/Article/details/gt2jmpqsfxr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.bjfxy.top/Article/details/gt2xgglmubm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2btlwhtyr.html

JS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gt2awvjorsj.html

TS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mciuoztw.html

Java: System.err.println("err")
来源：http://dali.sxryk.cn/Article/details/gt2ctaxzuyh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fengsongda.top/Article/details/gt2gdscbgpq.html

Ruby: warn "err"
来源：http://dali.jlsjyb.cn/Article/details/gt2dqobrzbk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gzhubu.top/Article/details/gt2qklgzgra.html

[M07] 判断是否为主入口
来源：http://dali.yj20258888.top/Article/details/gt2yftivdns.html

Py:   if __name__ == "__main__":
来源：http://dali.dashuyun.cn/Article/details/gt2rzrdugin.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhengqikj.top/Article/details/gt2eolsaovr.html

JS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gt2sjgaumex.html

TS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gt2dwwutwrz.html

Java: public static void main(String[] args)
来源：http://dali.fzhhl.top/Article/details/gt2snhsdgaz.html

Go:   func main()
来源：http://dali.xylfe.cn/Article/details/gt2owgbuqws.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tian-w.cn/Article/details/gt2jxfarkkn.html

C#:   static void Main(string[] args)
来源：http://dali.pycfn.com/Article/details/gt2rextdbmn.html

[M08] 获取系统与运行时信息
来源：http://dali.ybcxt.top/Article/details/gt2wcxcryky.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shuidangran.top/Article/details/gt2utjljkhx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhoulong.xyz/Article/details/gt2hadxhksy.html

JS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gt2nqxqecoa.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2evphzclq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ydzc1.top/Article/details/gt2mhvwsvwm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pycfn.com/Article/details/gt2mhpkaawb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yangfankeji.com/Article/details/gt2shlchvxp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuanzhike.top/Article/details/gt2iikltzxi.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2nsxbiiar.html

N. 数据结构与算法
来源：http://dali.gogol.net.cn/Article/details/gt2nhrhmeqd.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2cessbyex.html

[N01] 二分查找（有序数组）
来源：http://dali.cqqwz.cn/Article/details/gt2diccbmia.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2hmpuugvi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hammf.cn/Article/details/gt2jjegmewq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gt2aljbjqxw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gt2tuwdnglc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2pnviacqv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2vzieuebe.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wlctqjpx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2ewrtccti.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.kuanghao11.cn/Article/details/gt2ndvvmftt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gt2bhweyira.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tianlin.xyz/Article/details/gt2vplozpxr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gt2syecfiax.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gt2eioelauy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.c1oappe.top/Article/details/gt2gqrxbszr.html

Go:   slices.Sort(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2xpddpxrd.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gt2wadekscr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guowangkeji.top/Article/details/gt2sdziyitp.html

[N03] 快速排序（分治示例）
来源：http://dali.yanxiufei.cn/Article/details/gt2lxlzzkrh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hammf.cn/Article/details/gt2qinhsncu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuetiantiany.cn/Article/details/gt2oxppwshb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jiypdldi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gt2ywqwsbob.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangdashe.top/Article/details/gt2ycnhhgce.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnqzz.top/Article/details/gt2jbehjwfu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shzxlz.cn/Article/details/gt2obibczab.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.bjfxy.top/Article/details/gt2hgluahvj.html

[N04] 斐波那契数列
来源：http://dali.guannengcc.top/Article/details/gt2velqksoq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2gemmjmqq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gt2asajusvi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gt2bqhunhhd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gt2iqbdvuea.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daxiang520.top/Article/details/gt2txmvlxas.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenlongwang.top/Article/details/gt2chgeyigy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gt2qvfhxwwf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gt2imygraea.html

[N05] 最大公约数
来源：http://dali.quarkkingdee.top/Article/details/gt2uzsfyxuv.html

Py:   math.gcd(a, b)
来源：http://dali.cheryme.top/Article/details/gt2hjpyfuoj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zdqjudy.top/Article/details/gt2lcaibeoq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gt2xdedheqn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gt2lanfldpa.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shuidangran.top/Article/details/gt2megllybc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhixingplan.top/Article/details/gt2szdiyzia.html

Ruby: a.gcd(b)
来源：http://dali.jqgufenzy.top/Article/details/gt2iwnvfmtz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hnqzz.top/Article/details/gt2hozkklau.html

[N06] 判断回文字符串
来源：http://dali.yj20258888.top/Article/details/gt2qjbjytrr.html

Py:   s == s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2npmwrquo.html

PHP:  $s === strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2ixtbrnrf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gt2cumxwkrr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2vakbytta.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuetiantiany.cn/Article/details/gt2quyrtkfg.html

Go:   // 双指针从两端比较
来源：http://dali.jinghuilouyu.cn/Article/details/gt2elrnuiwj.html

Ruby: s == s.reverse
来源：http://dali.yangfankeji.com/Article/details/gt2glbrrbas.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gt2qljvxdrj.html

[N07] 两数之和（返回下标）
来源：http://dali.feifeiyinyue.top/Article/details/gt2auxnuofv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zycfv.cn/Article/details/gt2bvgnnadw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nwbrower.top/Article/details/gt2nuwbqtoz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nanxinkj.top/Article/details/gt2xllxafnd.html

TS:   // 手写 Map<string, number>
来源：http://dali.fzhhl.top/Article/details/gt2wgljpdco.html

Java: // 手写 HashMap
来源：http://dali.9152youxi.cn/Article/details/gt2lnyriree.html

Go:   // 手写 map[int]int
来源：http://dali.zdqjudy.top/Article/details/gt2xsifyloa.html

Ruby: // 手写 Hash
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cdnmueeq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tian-w.cn/Article/details/gt2diqhxfxh.html

[N08] 生成全排列
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmkauunl.html

Py:   itertools.permutations(arr)
来源：http://dali.316326.xyz/Article/details/gt2eakaedfr.html

PHP:  // 手写递归交换
来源：http://dali.wangdashe.top/Article/details/gt2wguawjjx.html

JS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gt2gujmptga.html

TS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gt2sdodacyl.html

Java: // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2fbyjjmwq.html

Go:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eqvasknu.html

Ruby: arr.permutation.to_a
来源：http://dali.sxryk.cn/Article/details/gt2uhqkjskc.html

C#:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xbypdvej.html

[N09] 栈与队列
来源：http://dali.meibo888.top/Article/details/gt2imeiidpb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.birdmap.top/Article/details/gt2dcglknua.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2fbbbsgni.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gt2evacpyhs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jiagoushi.top/Article/details/gt2bhrkzuea.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gotoacloud.top/Article/details/gt2dsfehgjt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jiagoushi.top/Article/details/gt2ccmtcbhq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nlzrkgjl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.meibo888.top/Article/details/gt2ssykfqwa.html

[N10] 链表节点定义
来源：http://dali.yvedp.cn/Article/details/gt2trqqqocm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhongyouzk.top/Article/details/gt2lflimopg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cqqwz.cn/Article/details/gt2reotkkat.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hnqzz.top/Article/details/gt2biuzvber.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yangfankeji.com/Article/details/gt2oizwmejt.html

Java: class Node { int v; Node next; }
来源：http://dali.cucudq.cn/Article/details/gt2jhvyubwk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ziwnwtob.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhengqikj.top/Article/details/gt2tpyzfyxv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yangfankeji.com/Article/details/gt2qlbnhjnz.html

[N11] 二叉树中序遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2fhkuftut.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.andypj.xyz/Article/details/gt2siicpgvr.html

PHP:  // 手写递归函数
来源：http://dali.vqdsnc.cn/Article/details/gt2mwklvvgq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gt2qsvsfboz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xziqi.cn/Article/details/gt2avlkdkwo.html

Java: // 手写递归
来源：http://dali.jianghu66.top/Article/details/gt2kedmmyrf.html

Go:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gt2qyztycqv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinqigufen.top/Article/details/gt2qbnevztx.html

C#:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gt2jedmqmtp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.redwolf501.top/Article/details/gt2sfkshmzb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fengsongda.top/Article/details/gt2yipacqic.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jqgfzy.top/Article/details/gt2qnacoupz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenjidiqi.icu/Article/details/gt2oqyzkzbi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gogol.net.cn/Article/details/gt2lhqpoizr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gt2gibaaneg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenjidiqi.icu/Article/details/gt2waghfjjy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2elfufqlh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gt2nvdamifr.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2vvrxnqvw.html

O. 并发与异步
来源：http://dali.hnxiangtu.top/Article/details/gt2cbgfjwjt.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2rpnfiyce.html

[O01] 启动一个线程
来源：http://dali.chenzaomai.com/Article/details/gt2qqmlwwss.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ehwqpu.com/Article/details/gt2igkpojxs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gzhubu.top/Article/details/gt2fvntbzji.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.vqdsnc.cn/Article/details/gt2dbmiklzf.html

TS:   // 同 JS
来源：http://dali.dianchejie.cn/Article/details/gt2mpgqjegh.html

Java: new Thread(() -> f()).start()
来源：http://dali.shuidangran.top/Article/details/gt2ypgkpthw.html

Go:   go f()
来源：http://dali.redwolf501.top/Article/details/gt2lrzlkqkq.html

Ruby: Thread.new { f }
来源：http://dali.jqgufenzy.top/Article/details/gt2rzxaydzl.html

C#:   Task.Run(() => F());
来源：http://dali.xuanzx.com/Article/details/gt2ujxfebrx.html

[O02] 使用线程池
来源：http://dali.hnxiangtu.top/Article/details/gt2bcsfoalh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.chenzaomai.com/Article/details/gt2qdufxnkw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hnxiangtu.top/Article/details/gt2hwwntujn.html

JS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gt2bwgjfssv.html

TS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gt2voioxygq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.meibo888.top/Article/details/gt2urmedirc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhixingplan.top/Article/details/gt2szrgdskh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhiwuduotai.top/Article/details/gt2xpnbiifk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yueranfly.top/Article/details/gt2ykvqmdye.html

[O03] 加锁保护共享数据
来源：http://dali.shuidangran.top/Article/details/gt2jicprzyz.html

Py:   with lock: shared += 1
来源：http://dali.sufxvd.cn/Article/details/gt2sjldwyka.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.dianchejie.cn/Article/details/gt2jajvwirq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guannengcc.top/Article/details/gt2pvzdnlug.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gt2qyewrzli.html

Java: synchronized (this) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ydiqgkcz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.aibaodan.cn/Article/details/gt2objdzejp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.birdmap.top/Article/details/gt2zwlnmecy.html

C#:   lock (gate) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gt2gqqttmbl.html

[O04] 定义异步函数并等待
来源：http://dali.jqgfzy.top/Article/details/gt2ydjxuksb.html

Py:   async def f():⏎    await g()
来源：http://dali.yj20258.top/Article/details/gt2fyitdbxt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenjidiqi.icu/Article/details/gt2nhmhujcx.html

JS:   async function f() { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gt2ednmhplh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xziqi.cn/Article/details/gt2truvsodu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hammf.cn/Article/details/gt2qqkhfyvv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258.top/Article/details/gt2pnhbffzn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhongyouzk.top/Article/details/gt2eqqxghbl.html

C#:   async Task F() { await G(); }
来源：http://dali.daxiang520.top/Article/details/gt2ggebrwku.html

[O05] 并发执行并等待全部完成
来源：http://dali.daria6918.cn/Article/details/gt2awfeknbr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cheryme.top/Article/details/gt2oudztzqk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.haohaochexian.top/Article/details/gt2pbmpsaaw.html

JS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gt2bxsjehrz.html

TS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gt2kydupcea.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fzhhl.top/Article/details/gt2opegjhzc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xziqi.cn/Article/details/gt2wxprksol.html

Ruby: threads.map(&:join)
来源：http://dali.iojbl.cn/Article/details/gt2zsncdwmc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnqzz.top/Article/details/gt2pbrermyd.html

[O06] 使用进程池
来源：http://dali.cucudq.cn/Article/details/gt2qqcmlbxo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.9152youxi.cn/Article/details/gt2gizkfaym.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mnrynsfo.html

JS:   // child_process / cluster 模块
来源：http://dali.pengpengdd.cyou/Article/details/gt2quxzolml.html

TS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gt2wqifufhc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gt2oicynngv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jiagoushi.top/Article/details/gt2cpgaaseu.html

Ruby: // fork 块
来源：http://dali.bjfxy.top/Article/details/gt2qjxsrpua.html

C#:   Parallel.For
来源：http://dali.daria6918.cn/Article/details/gt2rjnytvjy.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2lltgccuc.html

P. 常用工具函数
来源：http://dali.yuanzhike.top/Article/details/gt2rhhayrzg.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2duezjmwk.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bbqdsqfz.html

Py:   str(uuid.uuid4())
来源：http://dali.tianlin.xyz/Article/details/gt2txfrfbln.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cashguo.top/Article/details/gt2patgznqr.html

JS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gt2irlnjkie.html

TS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gt2rtgjches.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258.top/Article/details/gt2ixwmotko.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigfzy.top/Article/details/gt2xzzyhjsx.html

Ruby: SecureRandom.uuid
来源：http://dali.cheryme.top/Article/details/gt2eixdhxhf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2curgurje.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ydzc1.top/Article/details/gt2wnkbrjut.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuanzhike.top/Article/details/gt2fjudqehe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2hotzmluj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nwbrower.top/Article/details/gt2zqblgjzi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jianghu66.top/Article/details/gt2wgzpdagz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhixingplan.top/Article/details/gt2obugffvv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.smart0.xyz/Article/details/gt2oosgtxhp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.0kj1m.cn/Article/details/gt2khgyqgco.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cwlwdxno.html

[P03] 生成短随机字符串
来源：http://dali.ivvv.top/Article/details/gt2eodlppyk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zycfv.cn/Article/details/gt2nuixrkdw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhoulong.xyz/Article/details/gt2jvgmqqru.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gt2jcbughdw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gt2gdjfycuh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigufen.top/Article/details/gt2wveuvowo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tian-w.cn/Article/details/gt2txgzkjpi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yanxiufei.cn/Article/details/gt2lppkynlb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hfpthk.cn/Article/details/gt2rnzprkyf.html

[P04] 求长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2yblygskj.html


<!-- 参考信息 -->