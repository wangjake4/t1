代发 wailian999

Py:   resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtrvwyzetv.html

PHP:  json_decode($body, true);
来源：http://dali.aibaodan.cn/Article/details/gtaaozicta.html

JS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gtkzaegurl.html

TS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtodzfyznx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsmlxetv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shangyingyoupin.top/Article/details/gtncpffgse.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dianchejie.cn/Article/details/gtloiywknq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiszyngeb.html

[L07] 处理 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gtuvumnjyh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yongpay.top/Article/details/gtpelfepky.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yvedp.cn/Article/details/gtwpgkkrtr.html

JS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gtdlqgiswl.html

TS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gtjdgybtkd.html

Java: resp.statusCode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqijjfbt.html

Go:   resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtdnoljsmi.html

Ruby: resp.code.to_i
来源：http://dali.redwolf501.top/Article/details/gtliixzdiz.html

C#:   (int)resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gtpjxzwkzv.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gtczumvnud.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxinkj.top/Article/details/gtdmspsubg.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhixingplan.top/Article/details/gtzusvvluj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtloajruuu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gtcmgyyptu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuanzx.com/Article/details/gthiteiuck.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhoulong.xyz/Article/details/gtlttmtmcw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtgmdysreg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aizwys.cn/Article/details/gtrcreizkm.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtmwhwgocy.html

M. 命令行 / 进程 / 环境
来源：http://dali.kuanghao11.cn/Article/details/gtfabwxjmo.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtlhsutymn.html

[M01] 读取命令行参数
来源：http://dali.guowangkeji.top/Article/details/gtlxjofeax.html

Py:   sys.argv[1:]
来源：http://dali.cdnleiting.top/Article/details/gtgroutans.html

PHP:  $argv;  $argc;
来源：http://dali.hammf.cn/Article/details/gtejfendgu.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtpwhkuovq.html

TS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglcjmpnx.html

Java: args 数组（main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gtzwhvofba.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gteoqrqcjd.html

Ruby: ARGV
来源：http://dali.gogol.net.cn/Article/details/gtfzmkpydq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.birdmap.top/Article/details/gtiejoymlq.html

[M02] 读取环境变量
来源：http://dali.sysykeji.top/Article/details/gtlxrqkzsm.html

Py:   os.environ.get("HOME")
来源：http://dali.0kj1m.cn/Article/details/gttzhbpxei.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cheryme.top/Article/details/gtjshwrard.html

JS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gtncmrapxc.html

TS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gtlkvlzmgo.html

Java: System.getenv("HOME")
来源：http://dali.iojbl.cn/Article/details/gtvhhslsuj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtiuonpfjb.html

Ruby: ENV["HOME"]
来源：http://dali.gaohongyu789.top/Article/details/gtfptqeewq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yueranfly.top/Article/details/gtckwiqjdu.html

[M03] 执行外部命令
来源：http://dali.aizwys.cn/Article/details/gtrasjnnny.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhengqikj.top/Article/details/gtwukiltgr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.meibo888.top/Article/details/gthfywwjkr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gtgmqgutzy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gtlmmcivzz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhengqikj.top/Article/details/gtkaacfzne.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgufenzy.top/Article/details/gtolbfltup.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhengqikj.top/Article/details/gtvdgonqwl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangdashe.top/Article/details/gtnigxhimn.html

[M04] 获取当前工作目录
来源：http://dali.chenzaomai.com/Article/details/gtqrqttpzd.html

Py:   os.getcwd()
来源：http://dali.xuanzx.com/Article/details/gtalciwfdm.html

PHP:  getcwd();
来源：http://dali.sweek.top/Article/details/gtitfthakd.html

JS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gtfsnohvva.html

TS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtjzupawpy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dianchejie.cn/Article/details/gtutowvtma.html

Go:   os.Getwd()
来源：http://dali.hnxiangtu.top/Article/details/gtyzmzltls.html

Ruby: Dir.pwd
来源：http://dali.birdmap.top/Article/details/gtaonuwara.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fzhhl.top/Article/details/gtrmhkpere.html

[M05] 设置退出码
来源：http://dali.zhengqikj.top/Article/details/gtbaecbvqk.html

Py:   sys.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtwnnzvxfj.html

PHP:  exit(1);
来源：http://dali.hongshengwenyu.top/Article/details/gtnsyvgdbf.html

JS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtowjehqzg.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujkbbkkb.html

Java: System.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtbrfuqbrw.html

Go:   os.Exit(1)
来源：http://dali.c1oappe.top/Article/details/gtdtnlinbx.html

Ruby: exit 1
来源：http://dali.yuanzhike.top/Article/details/gtaeqznhrl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.svipenyu.cn/Article/details/gtwkgchnaf.html

[M06] 向标准错误输出
来源：http://dali.quarkkingdee.top/Article/details/gtpfsnnsyy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgfzy.top/Article/details/gtqhzstdtx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daria6918.cn/Article/details/gtxzqbkwoi.html

JS:   console.error("err")
来源：http://dali.gotoacloud.top/Article/details/gtnvbygwkv.html

TS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtwwdhxqso.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gtzwewducj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuadejbhg.html

Ruby: warn "err"
来源：http://dali.jinqigufen.top/Article/details/gtisjtcyte.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.316326.xyz/Article/details/gtsvyrvgbt.html

[M07] 判断是否为主入口
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmqwywth.html

Py:   if __name__ == "__main__":
来源：http://dali.shuidangran.top/Article/details/gthvropxry.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhongyouzk.top/Article/details/gtotokxqyr.html

JS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gttytjiioz.html

TS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gtsilurtth.html

Java: public static void main(String[] args)
来源：http://dali.tianlin.xyz/Article/details/gthbktmqnp.html

Go:   func main()
来源：http://dali.jyoumei.cn/Article/details/gtzqgzqtvc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenzaomai.com/Article/details/gtopcrnhzj.html

C#:   static void Main(string[] args)
来源：http://dali.snrcjt.cn/Article/details/gtprolidmp.html

[M08] 获取系统与运行时信息
来源：http://dali.quarkkingdee.top/Article/details/gtpwzydugy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.iojbl.cn/Article/details/gtacajypkt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sysykeji.top/Article/details/gtjawncwqm.html

JS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gtvzkzinfs.html

TS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gtnsecahgw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenzaomai.com/Article/details/gtlwrzbwhn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnqzz.top/Article/details/gtampufkpd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yueranfly.top/Article/details/gtrjnqnhbg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ybcxt.top/Article/details/gthdkoezay.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtisgvrbhn.html

N. 数据结构与算法
来源：http://dali.xuanzx.com/Article/details/gtprfjcxxg.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtpmamvwqk.html

[N01] 二分查找（有序数组）
来源：http://dali.shzxlz.cn/Article/details/gtdqtrsbgv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtsmrgrdbd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gogol.net.cn/Article/details/gtpspnafdq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gtbranqxky.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtciwezzja.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.meibo888.top/Article/details/gtldbveqtr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtekrpowjq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tanke756.top/Article/details/gtjsojhhtl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtijmxulwc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixmsxwks.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gtfrxezjxf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.meibo888.top/Article/details/gtsbbcuxti.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtbuuyowin.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.redwolf501.top/Article/details/gtlekhcrdv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.c1oappe.top/Article/details/gtmnkzwmtd.html

Go:   slices.Sort(arr)
来源：http://dali.guannengcc.top/Article/details/gtkmvvywir.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gttnkusinu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shzxlz.cn/Article/details/gthtyzfwjc.html

[N03] 快速排序（分治示例）
来源：http://dali.tianlin.xyz/Article/details/gtzaewqtex.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jyoumei.cn/Article/details/gtmbyvptge.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuanzx.com/Article/details/gtgktiyant.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gtpfnabfnb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gtshdnsxgm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hammf.cn/Article/details/gtclzyoxsd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.kuanghao11.cn/Article/details/gtjfqijciv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gotoacloud.top/Article/details/gtoqrbfoxx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.feifeiyinyue.top/Article/details/gtlummpgmk.html

[N04] 斐波那契数列
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkxulzbb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gtrnqeehao.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuxming.cn/Article/details/gtcxcxyaec.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gthgxacfao.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtjhgiedoi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gtlunraxge.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ybcxt.top/Article/details/gtrxpacofb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gtfkkyidzn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gtpakzarsx.html

[N05] 最大公约数
来源：http://dali.yvedp.cn/Article/details/gtyoomoxua.html

Py:   math.gcd(a, b)
来源：http://dali.yongpay.top/Article/details/gtkfvxyufy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xinyue.icu/Article/details/gtqwgdnlax.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gtgtcrukdc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gtoihflzjf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cucudq.cn/Article/details/gtirscmwar.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yanxiufei.cn/Article/details/gtbzmsjsqr.html

Ruby: a.gcd(b)
来源：http://dali.yanxiufei.cn/Article/details/gtqxxiufte.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zdqjudy.top/Article/details/gtrquliznn.html

[N06] 判断回文字符串
来源：http://dali.vqdsnc.cn/Article/details/gtdnwbyikh.html

Py:   s == s[::-1]
来源：http://dali.sxryk.cn/Article/details/gtmusvjzmn.html

PHP:  $s === strrev($s);
来源：http://dali.yvedp.cn/Article/details/gtnwcelszo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtcczdvvrw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtnietggga.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.c1oappe.top/Article/details/gtwhdepcos.html

Go:   // 双指针从两端比较
来源：http://dali.9152youxi.cn/Article/details/gtgkggposk.html

Ruby: s == s.reverse
来源：http://dali.tanke756.top/Article/details/gtljpmdeks.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gttkzoekmc.html

[N07] 两数之和（返回下标）
来源：http://dali.zhixingplan.top/Article/details/gtpoybifqu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pycfn.com/Article/details/gtmkoxrlto.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yuanzhike.top/Article/details/gtlnfechyw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdktayqx.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gtwhqcumic.html

Java: // 手写 HashMap
来源：http://dali.ppjwa.cn/Article/details/gtjljjkpmd.html

Go:   // 手写 map[int]int
来源：http://dali.yuanzhike.top/Article/details/gtyrbmnnmr.html

Ruby: // 手写 Hash
来源：http://dali.shangyingyoupin.top/Article/details/gthcuvqowb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daxiang520.top/Article/details/gtqgfjdyef.html

[N08] 生成全排列
来源：http://dali.nwbrower.top/Article/details/gtfjuythsr.html

Py:   itertools.permutations(arr)
来源：http://dali.hywenlv.cn/Article/details/gtlwcjcwna.html

PHP:  // 手写递归交换
来源：http://dali.zhoulong.xyz/Article/details/gtfjlbbqvl.html

JS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtspabnotk.html

TS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtgrtjeyjb.html

Java: // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtweakkljx.html

Go:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffvghvqf.html

Ruby: arr.permutation.to_a
来源：http://dali.bjfxy.top/Article/details/gtakmlzygl.html

C#:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtzujhdpdi.html

[N09] 栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gtukazfaoy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guannengcc.top/Article/details/gtdcebmfll.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj202588.top/Article/details/gtetoqfaie.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gthdyeyzka.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hfpthk.cn/Article/details/gtgeucjsnl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.redwolf501.top/Article/details/gtzjmjodmf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuetiantiany.cn/Article/details/gtegahxoyd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gthbsnwbul.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yanxiufei.cn/Article/details/gtyxneduxh.html

[N10] 链表节点定义
来源：http://dali.nwbrower.top/Article/details/gtvocsakyx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhengqikj.top/Article/details/gtnijfzwek.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jianghu66.top/Article/details/gtgqynhtcn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.mhx1999.top/Article/details/gttzytcmeb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gzhubu.top/Article/details/gtmchgjmct.html

Java: class Node { int v; Node next; }
来源：http://dali.yonumen.top/Article/details/gtvisnmfcy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xziqi.cn/Article/details/gtpsaecyxn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gotoacloud.top/Article/details/gtmlffrvjj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhiwuduotai.top/Article/details/gttwpawiey.html

[N11] 二叉树中序遍历
来源：http://dali.mhx1999.top/Article/details/gtqywwkvec.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvomeligd.html

PHP:  // 手写递归函数
来源：http://dali.xuetiantiany.cn/Article/details/gthylcqcml.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gtibxcvfnj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gtuywxewqd.html

Java: // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtssuvvbrm.html

Go:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gtetppkrpd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzufkkjr.html

C#:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtpslvlsha.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhengqikj.top/Article/details/gtvuhfwitb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cucudq.cn/Article/details/gtqqdlrddt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhongyouzk.top/Article/details/gtlihodaqg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gttcmkqudo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gtdornkcax.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gtyvqzlxri.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.kuanghao11.cn/Article/details/gtuefzmgzk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daria6918.cn/Article/details/gtdwzvfgnk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gtqskiljcs.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtdjntsdec.html

O. 并发与异步
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhxdjtzl.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtgvbirbkg.html

[O01] 启动一个线程
来源：http://dali.yonumen.top/Article/details/gtcfnamchp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cdnleiting.top/Article/details/gttlikalxd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yueranfly.top/Article/details/gtaqmkibpo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.0kj1m.cn/Article/details/gtactcdtpt.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gtlaitpwrj.html

Java: new Thread(() -> f()).start()
来源：http://dali.dianchejie.cn/Article/details/gtzdogospg.html

Go:   go f()
来源：http://dali.cashguo.top/Article/details/gtlmghjzjv.html

Ruby: Thread.new { f }
来源：http://dali.sxryk.cn/Article/details/gthpctqroq.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258.top/Article/details/gtchqwwahs.html

[O02] 使用线程池
来源：http://dali.svipenyu.cn/Article/details/gttonapsku.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aibaodan.cn/Article/details/gtlhifsnrz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hongshengwenyu.top/Article/details/gtlmnlltcl.html

JS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gtyjwcpyyx.html

TS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gtfspmrubi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hongshengwenyu.top/Article/details/gtmmkamfuf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258888.top/Article/details/gtlrlewkua.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuanzx.com/Article/details/gtgkydyklw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.dashuyun.cn/Article/details/gtoodwmklc.html

[O03] 加锁保护共享数据
来源：http://dali.sxryk.cn/Article/details/gtbibxmuww.html

Py:   with lock: shared += 1
来源：http://dali.kuanghao11.cn/Article/details/gtgtrtxwpw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cheryme.top/Article/details/gthjfqgljz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dianchejie.cn/Article/details/gtzdjpmnqt.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gtczobsjol.html

Java: synchronized (this) { shared++; }
来源：http://dali.dashuyun.cn/Article/details/gtsqlvorez.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.haohaochexian.top/Article/details/gtblvvoomk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jyoumei.cn/Article/details/gtcdzyvvdk.html

C#:   lock (gate) { shared++; }
来源：http://dali.yonumen.top/Article/details/gtscyaigse.html

[O04] 定义异步函数并等待
来源：http://dali.hfpthk.cn/Article/details/gtjnvtzudf.html

Py:   async def f():⏎    await g()
来源：http://dali.yj202588.top/Article/details/gtwqhmqvwx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hammf.cn/Article/details/gtdhpdgjjg.html

JS:   async function f() { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gtbosimgpn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtsjhenblb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gtoysgsfsv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hysaishi.cn/Article/details/gtowgauxkt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.0kj1m.cn/Article/details/gtxrmpbvsa.html

C#:   async Task F() { await G(); }
来源：http://dali.mhx1999.top/Article/details/gtrfwaxrcx.html

[O05] 并发执行并等待全部完成
来源：http://dali.ybcxt.top/Article/details/gthnesqeqv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.0kj1m.cn/Article/details/gtwsxzxpqw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yongpay.top/Article/details/gtkycxmqcy.html

JS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gtxngtfoto.html

TS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gtquwcekia.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fengsongda.top/Article/details/gthmtcyasr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jlsjyb.cn/Article/details/gtzbdbbmql.html

Ruby: threads.map(&:join)
来源：http://dali.guannengcc.top/Article/details/gtqklrnhoq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangdashe.top/Article/details/gtqowohqal.html

[O06] 使用进程池
来源：http://dali.snrcjt.cn/Article/details/gtkuwdrfgi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfnxujyw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xylfe.cn/Article/details/gtykefrhua.html

JS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gtqrbhbbgq.html

TS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gtdqymbndq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cucudq.cn/Article/details/gtvdxrzqqi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zdqjudy.top/Article/details/gtpnwjihap.html

Ruby: // fork 块
来源：http://dali.sysykeji.top/Article/details/gtdcpmawre.html

C#:   Parallel.For
来源：http://dali.nwbrower.top/Article/details/gtawqfqygv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsplbxmaa.html

P. 常用工具函数
来源：http://dali.yuxming.cn/Article/details/gtwzkkfwys.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtywcfmlhh.html

[P01] 生成 UUID
来源：http://dali.cashguo.top/Article/details/gtetglnwco.html

Py:   str(uuid.uuid4())
来源：http://dali.shanyushiyangtech.top/Article/details/gtdyvupmoe.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sufxvd.cn/Article/details/gtlaehwdma.html

JS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gtbgcphvvk.html

TS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gtksyyyqkv.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhixingplan.top/Article/details/gtsugxmsaz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fzhhl.top/Article/details/gtzufohfnz.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqcqlihlv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.c1oappe.top/Article/details/gtyewoihbh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.snrcjt.cn/Article/details/gtzyunvluk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hongshengwenyu.top/Article/details/gtxbwyinqx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shzxlz.cn/Article/details/gtaozxwrgn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shuidangran.top/Article/details/gtlyldcibt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cqqwz.cn/Article/details/gtslauqmkb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pycfn.com/Article/details/gtgrxddgoj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yvedp.cn/Article/details/gtkzvfqtyn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ydzc1.top/Article/details/gtmjlhmlyn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aibaodan.cn/Article/details/gtbilwhvyw.html

[P03] 生成短随机字符串
来源：http://dali.daria6918.cn/Article/details/gtjvscbqzc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.vqdsnc.cn/Article/details/gtwzwwvubx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.smart0.xyz/Article/details/gtvqtsqkkx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gtctkqlwqk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.svipenyu.cn/Article/details/gtnkqfwrtm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuxming.cn/Article/details/gtcpyxsjbo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cashguo.top/Article/details/gtaysrlsdo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcoynkbdw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigfzy.top/Article/details/gthahooirm.html

[P04] 求长度
来源：http://dali.bjfxy.top/Article/details/gtczjxkcov.html


<!-- 参考信息 -->