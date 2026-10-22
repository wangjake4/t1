代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gthrwazopf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cdnleiting.top/Article/details/gtjmozufyx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.guowangkeji.top/Article/details/gtireiawzn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zdqjudy.top/Article/details/gtcctbmmsj.html

[L07] 处理 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gtbutuqsgg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangshuangyany.cn/Article/details/gtpqtyslld.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigfzy.top/Article/details/gtwqnyjfsu.html

JS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gtjalrqcru.html

TS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gtpzfbvmpo.html

Java: resp.statusCode()
来源：http://dali.hongshengwenyu.top/Article/details/gtgrfdlhai.html

Go:   resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gtavwotgoz.html

Ruby: resp.code.to_i
来源：http://dali.cheryme.top/Article/details/gtlqzriaca.html

C#:   (int)resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gtmvffyuqm.html

[L08] 并发请求多个地址
来源：http://dali.birdmap.top/Article/details/gtpqspdqoi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.0kj1m.cn/Article/details/gtgdduxjne.html

PHP:  curl_multi_init() 系列
来源：http://dali.cashguo.top/Article/details/gtocikttnv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gthpllffxo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtahizslvv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dianchejie.cn/Article/details/gtxokxlnst.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fzhhl.top/Article/details/gtselpsvvq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gtlogwcrfi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtwsbfrwkb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gttpctfljv.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuanzx.com/Article/details/gtuiwhevzx.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtrzrndduh.html

[M01] 读取命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gtubfgpkph.html

Py:   sys.argv[1:]
来源：http://dali.smart0.xyz/Article/details/gtufotpdxb.html

PHP:  $argv;  $argc;
来源：http://dali.nanxuanxn.top/Article/details/gtzltosscx.html

JS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gtqowfwafk.html

TS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gtpxtykukc.html

Java: args 数组（main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gtywxptato.html

Go:   os.Args[1:]
来源：http://dali.yuanzhike.top/Article/details/gtmuatyxuy.html

Ruby: ARGV
来源：http://dali.9152youxi.cn/Article/details/gtmkiajcuu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gtejloxvvl.html

[M02] 读取环境变量
来源：http://dali.birdmap.top/Article/details/gtrjcnpflp.html

Py:   os.environ.get("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpfzzuuo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gtlhjvkmqj.html

JS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gtwhwzfjsg.html

TS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gtfgtqstka.html

Java: System.getenv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtxrvoqomb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtumhjgrja.html

Ruby: ENV["HOME"]
来源：http://dali.tanke756.top/Article/details/gthqgowbjk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tanke756.top/Article/details/gtpkvucjay.html

[M03] 执行外部命令
来源：http://dali.gzhubu.top/Article/details/gtgructewn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tanke756.top/Article/details/gtilquritg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guannengcc.top/Article/details/gtqevhmzyr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gtzgxozplj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gtuxwwffvb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shuidangran.top/Article/details/gtdxokakii.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgfzy.top/Article/details/gtehprloae.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sxryk.cn/Article/details/gtkefztjzx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tanke756.top/Article/details/gtdiwncylb.html

[M04] 获取当前工作目录
来源：http://dali.nanxinkj.top/Article/details/gtlgkwvpwh.html

Py:   os.getcwd()
来源：http://dali.nwbrower.top/Article/details/gtlwdfqqpl.html

PHP:  getcwd();
来源：http://dali.nanxinkj.top/Article/details/gtbgqnfylj.html

JS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gtwmiaodjv.html

TS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gtotmscpcn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nwbrower.top/Article/details/gtwugegcjo.html

Go:   os.Getwd()
来源：http://dali.gotoacloud.top/Article/details/gtwsmdtfxu.html

Ruby: Dir.pwd
来源：http://dali.sufxvd.cn/Article/details/gtaordbicj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangtech.top/Article/details/gtobswskxl.html

[M05] 设置退出码
来源：http://dali.wangshuangyany.cn/Article/details/gtuscojzwf.html

Py:   sys.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtgupntydp.html

PHP:  exit(1);
来源：http://dali.gzhubu.top/Article/details/gtyqmanbwq.html

JS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtrzocfqze.html

TS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtpcgmowoi.html

Java: System.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtrfbvwfxr.html

Go:   os.Exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtdziszqze.html

Ruby: exit 1
来源：http://dali.fengsongda.top/Article/details/gtnyhmmmxf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.0kj1m.cn/Article/details/gtbalxgkrn.html

[M06] 向标准错误输出
来源：http://dali.aizwys.cn/Article/details/gtvjrtyszs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.andypj.xyz/Article/details/gtfzhvhchp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gtltvfzgpg.html

JS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gtiwosgsst.html

TS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gtatdijnok.html

Java: System.err.println("err")
来源：http://dali.ivvv.top/Article/details/gtwhljunqu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.haohaochexian.top/Article/details/gtfnhjvslg.html

Ruby: warn "err"
来源：http://dali.yj20258888.top/Article/details/gtlutppdep.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.svipenyu.cn/Article/details/gtvsvozerm.html

[M07] 判断是否为主入口
来源：http://dali.sweek.top/Article/details/gtjxavqiiv.html

Py:   if __name__ == "__main__":
来源：http://dali.chenlongwang.top/Article/details/gtcqzcwytx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xinyue.icu/Article/details/gtrpgwmplf.html

JS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gtkjajxeis.html

TS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqtimqwm.html

Java: public static void main(String[] args)
来源：http://dali.nanxuanxn.top/Article/details/gttyjelepj.html

Go:   func main()
来源：http://dali.dashuyun.cn/Article/details/gtbsdvbcsy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daxiang520.top/Article/details/gtuzgagspj.html

C#:   static void Main(string[] args)
来源：http://dali.dianchejie.cn/Article/details/gtrlmhxgdv.html

[M08] 获取系统与运行时信息
来源：http://dali.dashuyun.cn/Article/details/gtrwqlhkuj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.c1oappe.top/Article/details/gtwvcitlet.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenlongwang.top/Article/details/gtbswnipxg.html

JS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gtokuoeivb.html

TS:   process.platform;  process.version
来源：http://dali.xuanzx.com/Article/details/gtzidgozct.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigufen.top/Article/details/gtklkizhaj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.vqdsnc.cn/Article/details/gtzlkhkuss.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.316326.xyz/Article/details/gtkkgofoaq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.redwolf501.top/Article/details/gtixmaxvdv.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtsxirazeg.html

N. 数据结构与算法
来源：http://dali.dianchejie.cn/Article/details/gtttnwrvcl.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtactvbuzy.html

[N01] 二分查找（有序数组）
来源：http://dali.dianchejie.cn/Article/details/gtovphgrra.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtiysqcwwl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtodwishkt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtlwtgdyae.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gtrcsfdprv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtqarcfnjt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtpkwttekx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nwbrower.top/Article/details/gtfjdbvyiy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtbtuoerbl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhiwuduotai.top/Article/details/gtxjmqoamm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.smart0.xyz/Article/details/gtcbavawrg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtsjpdssmg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gtvxdtiani.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gtllzfzfyy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sysykeji.top/Article/details/gtjpleknjb.html

Go:   slices.Sort(arr)
来源：http://dali.ppjwa.cn/Article/details/gtdrryxuhy.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gtrdcmlyxx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sxryk.cn/Article/details/gtqdmelpdw.html

[N03] 快速排序（分治示例）
来源：http://dali.smart0.xyz/Article/details/gtujyxpptg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ivvv.top/Article/details/gtfukfqjti.html

PHP:  // 递归实现，或用 usort
来源：http://dali.bjfxy.top/Article/details/gtwtobwpdq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gtqixygxpl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gtnirtfpbd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dianchejie.cn/Article/details/gtkvkiteam.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuxming.cn/Article/details/gtrtkpilez.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gzhubu.top/Article/details/gtfinaolht.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmpuwajz.html

[N04] 斐波那契数列
来源：http://dali.zhixingplan.top/Article/details/gtzcuyvemb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gtrptsuogr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daria6918.cn/Article/details/gtzjrdgqnt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtzoxilrem.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtleudscfs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtlkbxkupa.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yangfankeji.com/Article/details/gtqgnazfih.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gtmnmmnsdg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtwnrxjdyc.html

[N05] 最大公约数
来源：http://dali.yuanzhike.top/Article/details/gtryxmshvg.html

Py:   math.gcd(a, b)
来源：http://dali.daria6918.cn/Article/details/gtzdcwcjgl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xylfe.cn/Article/details/gtuhfjbcxw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gtvhteonon.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtwcsjmkgi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.316326.xyz/Article/details/gtbqywoygb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtteefebiu.html

Ruby: a.gcd(b)
来源：http://dali.jqgfzy.top/Article/details/gtxtbnirzs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cqqwz.cn/Article/details/gtbnrprbxk.html

[N06] 判断回文字符串
来源：http://dali.iojbl.cn/Article/details/gtfrcnadrb.html

Py:   s == s[::-1]
来源：http://dali.havefunace.top/Article/details/gtkustkera.html

PHP:  $s === strrev($s);
来源：http://dali.hammf.cn/Article/details/gtyzaoildn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtoqzjnugw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtpjxibqli.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnqzz.top/Article/details/gtcjykifxt.html

Go:   // 双指针从两端比较
来源：http://dali.aibaodan.cn/Article/details/gtuoasbifz.html

Ruby: s == s.reverse
来源：http://dali.yuxming.cn/Article/details/gtrfxbhmon.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gtnfbxnhob.html

[N07] 两数之和（返回下标）
来源：http://dali.0kj1m.cn/Article/details/gthlnsqycj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.haohaochexian.top/Article/details/gtjnbausoo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yuanzhike.top/Article/details/gtghclqckx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zycfv.cn/Article/details/gtxfwjkrst.html

TS:   // 手写 Map<string, number>
来源：http://dali.andypj.xyz/Article/details/gtdockcwab.html

Java: // 手写 HashMap
来源：http://dali.yanxiufei.cn/Article/details/gtzvtjposn.html

Go:   // 手写 map[int]int
来源：http://dali.xziqi.cn/Article/details/gtvuzstiee.html

Ruby: // 手写 Hash
来源：http://dali.wangdashe.top/Article/details/gthhnfrqpi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hysaishi.cn/Article/details/gtzockfryz.html

[N08] 生成全排列
来源：http://dali.daria6918.cn/Article/details/gticdxhsgj.html

Py:   itertools.permutations(arr)
来源：http://dali.cheryme.top/Article/details/gtqobrzkxm.html

PHP:  // 手写递归交换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwntznjxe.html

JS:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtxjwpfkrx.html

TS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqbpdfcm.html

Java: // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtohrcreqv.html

Go:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtrygpsbgu.html

Ruby: arr.permutation.to_a
来源：http://dali.guannengcc.top/Article/details/gtqaedflcm.html

C#:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtcnmjefzh.html

[N09] 栈与队列
来源：http://dali.wangshuangyany.cn/Article/details/gtrtnuzsdq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhengqikj.top/Article/details/gtpnsyclxt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtqcfuslbl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtlekiomos.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cucudq.cn/Article/details/gtcqcgxizg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ehwqpu.com/Article/details/gtcdxsvzap.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ydzc1.top/Article/details/gttgcxhgbw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtjnaqatjs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nwbrower.top/Article/details/gtccfecgvq.html

[N10] 链表节点定义
来源：http://dali.jiagoushi.top/Article/details/gtwrdfnclf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sufxvd.cn/Article/details/gtxshqfklk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.kuanghao11.cn/Article/details/gtezqcccct.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtqsmptsiy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.fzhhl.top/Article/details/gtuoclbshx.html

Java: class Node { int v; Node next; }
来源：http://dali.xuetiantiany.cn/Article/details/gthybjmoot.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xylfe.cn/Article/details/gtwvptveut.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shuidangran.top/Article/details/gtiygytxhv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tianlin.xyz/Article/details/gtghkybmqs.html

[N11] 二叉树中序遍历
来源：http://dali.ppjwa.cn/Article/details/gtcphyrkmw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkepthusn.html

PHP:  // 手写递归函数
来源：http://dali.ppjwa.cn/Article/details/gtedcwvgyl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gtmchwxwep.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtznzqtnao.html

Java: // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtzuyojfjs.html

Go:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gttrkaxgas.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gogol.net.cn/Article/details/gtiqffjeof.html

C#:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gtpnfjqwxg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgufenzy.top/Article/details/gtlgwrxpku.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cashguo.top/Article/details/gtyopdnbca.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ybcxt.top/Article/details/gtpvbblfqy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yueranfly.top/Article/details/gthxyyzkcy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtweauwmxx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtfflvkajp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pycfn.com/Article/details/gtzrucuvkd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.316326.xyz/Article/details/gthvzcdooo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gtaecamoui.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gthientwfa.html

O. 并发与异步
来源：http://dali.yonumen.top/Article/details/gtappvmyhr.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtesmfmvqk.html

[O01] 启动一个线程
来源：http://dali.yonumen.top/Article/details/gtgfancnow.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cdnleiting.top/Article/details/gtkeqislvy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guannengcc.top/Article/details/gtahhxumad.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xziqi.cn/Article/details/gtsymllzbp.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gttttplbkk.html

Java: new Thread(() -> f()).start()
来源：http://dali.mhx1999.top/Article/details/gtfuhhlxlc.html

Go:   go f()
来源：http://dali.tianlin.xyz/Article/details/gtjxmkbwcy.html

Ruby: Thread.new { f }
来源：http://dali.xinyue.icu/Article/details/gtxuuzgqeb.html

C#:   Task.Run(() => F());
来源：http://dali.ivvv.top/Article/details/gtwihfawgv.html

[O02] 使用线程池
来源：http://dali.mhx1999.top/Article/details/gtjnrsloov.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gtqbngpnem.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guowangkeji.top/Article/details/gtkqqslbwr.html

JS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gtulyoybfk.html

TS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtneozdafq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sysykeji.top/Article/details/gtpjjfhxkc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuanzhike.top/Article/details/gtouhivgnd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangshuangyany.cn/Article/details/gtsiovvrbc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszqmhytb.html

[O03] 加锁保护共享数据
来源：http://dali.feifeiyinyue.top/Article/details/gthagdtudd.html

Py:   with lock: shared += 1
来源：http://dali.havefunace.top/Article/details/gthzemotsy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhongyouzk.top/Article/details/gtguflyccc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yvedp.cn/Article/details/gtdifoelat.html

TS:   // 同 JS
来源：http://dali.sysykeji.top/Article/details/gtbkgzwlnf.html

Java: synchronized (this) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gthnwiyyrk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hfpthk.cn/Article/details/gtiurjeuqp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnxiangtu.top/Article/details/gtblgjkzcz.html

C#:   lock (gate) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gtdwdydhui.html

[O04] 定义异步函数并等待
来源：http://dali.tian-w.cn/Article/details/gtuazhwddi.html

Py:   async def f():⏎    await g()
来源：http://dali.chenjidiqi.icu/Article/details/gteueeoenr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuetiantiany.cn/Article/details/gtluaxbjsq.html

JS:   async function f() { await g(); }
来源：http://dali.birdmap.top/Article/details/gtxuwbetcy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtzstfyefr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gtsxsipmwa.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj202588.top/Article/details/gteguuilkw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ivvv.top/Article/details/gtemeohuqj.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gtgvlhpcum.html

[O05] 并发执行并等待全部完成
来源：http://dali.hywenlv.cn/Article/details/gtxicbolss.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangdashe.top/Article/details/gtjbuzndrp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuetiantiany.cn/Article/details/gtmozvzath.html

JS:   await Promise.all(tasks)
来源：http://dali.yanxiufei.cn/Article/details/gtqpnmeelv.html

TS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gtsxbiitzj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nwbrower.top/Article/details/gtvwgjtjxh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dashuyun.cn/Article/details/gtimvtvtnj.html

Ruby: threads.map(&:join)
来源：http://dali.cheryme.top/Article/details/gtdurxfszn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jianghu66.top/Article/details/gtpfhspihk.html

[O06] 使用进程池
来源：http://dali.0kj1m.cn/Article/details/gtsudcwfhr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtmzvynd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ppjwa.cn/Article/details/gtqqqkzhjt.html

JS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gtrxelussm.html

TS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gtdbjxidml.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sxryk.cn/Article/details/gtytktgans.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.daria6918.cn/Article/details/gtzdmwnhfa.html

Ruby: // fork 块
来源：http://dali.shangyingyoupin.top/Article/details/gtrmoowpsm.html

C#:   Parallel.For
来源：http://dali.meibo888.top/Article/details/gtzcherxmf.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtxpvzkwpk.html

P. 常用工具函数
来源：http://dali.tianlin.xyz/Article/details/gteglmqnzi.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtquqhoyfb.html

[P01] 生成 UUID
来源：http://dali.ivvv.top/Article/details/gtdgyhuodb.html

Py:   str(uuid.uuid4())
来源：http://dali.xinyue.icu/Article/details/gtwvhmmytj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daxiang520.top/Article/details/gtbdcpicox.html

JS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gttihaxwcf.html

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjabfrnqz.html

Java: UUID.randomUUID().toString()
来源：http://dali.havefunace.top/Article/details/gtdjqkecob.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj202588.top/Article/details/gtqzycgsdt.html

Ruby: SecureRandom.uuid
来源：http://dali.tian-w.cn/Article/details/gtekluwhof.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yangfankeji.com/Article/details/gtscqobwdv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sufxvd.cn/Article/details/gtliadynem.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.feifeiyinyue.top/Article/details/gtefxrcnar.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenzaomai.com/Article/details/gtkumvpmsf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dianchejie.cn/Article/details/gttjybgqyx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxuanxn.top/Article/details/gthntcsrpk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zdqjudy.top/Article/details/gtckelmnvh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jianghu66.top/Article/details/gthpblokjw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj202588.top/Article/details/gtuxbyhzdu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangtech.top/Article/details/gtnfyzzysh.html

[P03] 生成短随机字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtjomqgxgf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shzxlz.cn/Article/details/gtsekpvvvw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hywenlv.cn/Article/details/gttobnxtqv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gtgwibnmud.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.kuanghao11.cn/Article/details/gtheqbxrwx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.316326.xyz/Article/details/gtcqspxnpw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.iojbl.cn/Article/details/gtxxkzfymn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxinkj.top/Article/details/gtxdnbesds.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guowangkeji.top/Article/details/gtzlmgojnh.html

[P04] 求长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuubkqnfo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gogol.net.cn/Article/details/gtkxidghbw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtpjxicvvu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gtrkbbpkfj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gtnqcyphnd.html


<!-- 参考信息 -->