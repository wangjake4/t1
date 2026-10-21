代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gttvurjlwa.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yongpay.top/Article/details/gtsljgqizg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daria6918.cn/Article/details/gtouznrwmv.html

JS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gtgekuuyzu.html

TS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gtvegkfgom.html

Java: resp.statusCode()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhrxjvzt.html

Go:   resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gthtiuchqt.html

Ruby: resp.code.to_i
来源：http://dali.quarkkingdee.top/Article/details/gtckrcnlku.html

C#:   (int)resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtoczgkvoc.html

[L08] 并发请求多个地址
来源：http://dali.9152youxi.cn/Article/details/gtwjrufryp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yvedp.cn/Article/details/gtnbkxtoci.html

PHP:  curl_multi_init() 系列
来源：http://dali.ehwqpu.com/Article/details/gtebqfvysl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtwephjkkf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqvswymk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhixingplan.top/Article/details/gtavlzuvir.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnqzz.top/Article/details/gtfsrdbypc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ydzc1.top/Article/details/gtyffvofvf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtktmokccj.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtdeqbicwx.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj202588.top/Article/details/gthgpzfaju.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtptaricgk.html

[M01] 读取命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtazalgslf.html

Py:   sys.argv[1:]
来源：http://dali.jqgfzy.top/Article/details/gtzlkcvews.html

PHP:  $argv;  $argc;
来源：http://dali.daria6918.cn/Article/details/gtabenomak.html

JS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gtrwmaiylc.html

TS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtaypjynju.html

Java: args 数组（main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gteebqcsza.html

Go:   os.Args[1:]
来源：http://dali.cdnleiting.top/Article/details/gtzbnbxxft.html

Ruby: ARGV
来源：http://dali.havefunace.top/Article/details/gtowdvjier.html

C#:   args 数组（Main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gtgvnawkre.html

[M02] 读取环境变量
来源：http://dali.fengsongda.top/Article/details/gtycnnuxzc.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtsqlswpkr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtqasytadm.html

JS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtorjvxjsd.html

TS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gtujmvjltz.html

Java: System.getenv("HOME")
来源：http://dali.yj20258888.top/Article/details/gtetqbuzxy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtamqrsbfx.html

Ruby: ENV["HOME"]
来源：http://dali.fengsongda.top/Article/details/gtpymocbhk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtwtropsry.html

[M03] 执行外部命令
来源：http://dali.hnxiangtu.top/Article/details/gtrhnksftu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.birdmap.top/Article/details/gtnyahglft.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dashuyun.cn/Article/details/gtggeuqplw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtpawnyvxv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gtomlfqalw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yangfankeji.com/Article/details/gthazfwmqs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigufen.top/Article/details/gtzehrudqn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hywenlv.cn/Article/details/gtuijmfgov.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigfzy.top/Article/details/gtelxluvjt.html

[M04] 获取当前工作目录
来源：http://dali.daxiang520.top/Article/details/gtkzzsirnz.html

Py:   os.getcwd()
来源：http://dali.cdnleiting.top/Article/details/gtlksvacjh.html

PHP:  getcwd();
来源：http://dali.guowangkeji.top/Article/details/gtkszjmehp.html

JS:   process.cwd()
来源：http://dali.jiagoushi.top/Article/details/gtrtvhcman.html

TS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gtdlmeyglo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shuidangran.top/Article/details/gtzuacedqv.html

Go:   os.Getwd()
来源：http://dali.sysykeji.top/Article/details/gtpmyckfzp.html

Ruby: Dir.pwd
来源：http://dali.ehwqpu.com/Article/details/gtkidsyhbb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pengpengdd.cyou/Article/details/gthlezdfzm.html

[M05] 设置退出码
来源：http://dali.yj20258888.top/Article/details/gtwljuscre.html

Py:   sys.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtcedrjgwe.html

PHP:  exit(1);
来源：http://dali.aizwys.cn/Article/details/gtfpubughf.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtaavqkyjq.html

TS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gtwfcrbbju.html

Java: System.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gttnzzrsac.html

Go:   os.Exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtngynmopl.html

Ruby: exit 1
来源：http://dali.xinyue.icu/Article/details/gtmklyxpqy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuetiantiany.cn/Article/details/gtoesrcfhw.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvbqxtru.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aibaodan.cn/Article/details/gtiwjhitlr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xinyue.icu/Article/details/gtnyorczkm.html

JS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gtjpmwjunl.html

TS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gtngkehvvn.html

Java: System.err.println("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrywbpqy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuanzhike.top/Article/details/gtenyjoxhx.html

Ruby: warn "err"
来源：http://dali.hongshengwenyu.top/Article/details/gtxjgiejdz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtarquernr.html

[M07] 判断是否为主入口
来源：http://dali.sysykeji.top/Article/details/gtltvatapm.html

Py:   if __name__ == "__main__":
来源：http://dali.vqdsnc.cn/Article/details/gtfvqqmulj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sufxvd.cn/Article/details/gtjembxoii.html

JS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtnfsdshet.html

TS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gtxzsrlkle.html

Java: public static void main(String[] args)
来源：http://dali.havefunace.top/Article/details/gtluauqvxu.html

Go:   func main()
来源：http://dali.sysykeji.top/Article/details/gtaaqscsgd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinqigufen.top/Article/details/gtmfaivvbu.html

C#:   static void Main(string[] args)
来源：http://dali.daxiang520.top/Article/details/gtqhfcsqbb.html

[M08] 获取系统与运行时信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrrehtyk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.snrcjt.cn/Article/details/gtvztnwwao.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gogol.net.cn/Article/details/gtphrafpad.html

JS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gtwfdbeflc.html

TS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtkjqsgmqa.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gtrqlitjnw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aibaodan.cn/Article/details/gtsuwnxykv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dianchejie.cn/Article/details/gtpocvzhvr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.quarkkingdee.top/Article/details/gtyzbdnbkr.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtdzwtahuq.html

N. 数据结构与算法
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnhtdsst.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gttosvkxzb.html

[N01] 二分查找（有序数组）
来源：http://dali.ivvv.top/Article/details/gtaslcipjt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtxywboybq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgavzoukq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtoyppmxsp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtcliywxxk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtenhwcqjr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtesuttcjh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258888.top/Article/details/gtcvgphzoy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtezgjzorh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangshuangyany.cn/Article/details/gtsdxdgigj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtzfullvul.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuxming.cn/Article/details/gtjvksursh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gtwxzjzuyg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtqdyawpkl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hfpthk.cn/Article/details/gtebjxpjmx.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrchocbbf.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gtyolzavph.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gtreyycrlr.html

[N03] 快速排序（分治示例）
来源：http://dali.vqdsnc.cn/Article/details/gtoqikptjl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgdqnhxg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxuanxn.top/Article/details/gttxbmjnqy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gtcggjeghl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gtpnrbephr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.9152youxi.cn/Article/details/gtlboazyxj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tianlin.xyz/Article/details/gtiqmjaycy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hywenlv.cn/Article/details/gtnbakwfvx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guannengcc.top/Article/details/gtkclktqnc.html

[N04] 斐波那契数列
来源：http://dali.shzxlz.cn/Article/details/gtqlnfgved.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gtwipkbhef.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ivvv.top/Article/details/gtiswvtdvk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxkjdrcv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtocwnrzhn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gtjcrlgsax.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvumlgvzv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gtfcimfrnb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzrrkekw.html

[N05] 最大公约数
来源：http://dali.jiagoushi.top/Article/details/gtefandxie.html

Py:   math.gcd(a, b)
来源：http://dali.zycfv.cn/Article/details/gtxomrvxjt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pycfn.com/Article/details/gtfgdstajh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gtthxpjuab.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gtvmoyzwhs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.svipenyu.cn/Article/details/gtxzcxjxpc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.birdmap.top/Article/details/gtpksadnmw.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gtubavgsfe.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xinyue.icu/Article/details/gtjkbwqvym.html

[N06] 判断回文字符串
来源：http://dali.nanxuanxn.top/Article/details/gtdotjoiyr.html

Py:   s == s[::-1]
来源：http://dali.hnxiangtu.top/Article/details/gteduqkzaj.html

PHP:  $s === strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gtfdfnegme.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtvqengsrc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtskscaypv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sufxvd.cn/Article/details/gtzwhidset.html

Go:   // 双指针从两端比较
来源：http://dali.xuanzx.com/Article/details/gtwkfawabb.html

Ruby: s == s.reverse
来源：http://dali.aibaodan.cn/Article/details/gthpawcrtc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gttacudrqb.html

[N07] 两数之和（返回下标）
来源：http://dali.yongpay.top/Article/details/gtzfdwsjix.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sweek.top/Article/details/gtothptqwe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxinkj.top/Article/details/gtykxhfhkh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cheryme.top/Article/details/gtesodcepr.html

TS:   // 手写 Map<string, number>
来源：http://dali.jyoumei.cn/Article/details/gtjhvtoqda.html

Java: // 手写 HashMap
来源：http://dali.nwbrower.top/Article/details/gtwyrptehm.html

Go:   // 手写 map[int]int
来源：http://dali.hysaishi.cn/Article/details/gtlgwoverd.html

Ruby: // 手写 Hash
来源：http://dali.nanxinkj.top/Article/details/gteiufxmbl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnqzz.top/Article/details/gtrnxkuqzv.html

[N08] 生成全排列
来源：http://dali.sufxvd.cn/Article/details/gthnihvjhx.html

Py:   itertools.permutations(arr)
来源：http://dali.hfpthk.cn/Article/details/gtrebqvckk.html

PHP:  // 手写递归交换
来源：http://dali.chenlongwang.top/Article/details/gthgmbqhiw.html

JS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtkxokrshw.html

TS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtxbzsogvz.html

Java: // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtjwuwxeoo.html

Go:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtwexrzicv.html

Ruby: arr.permutation.to_a
来源：http://dali.ybcxt.top/Article/details/gtaehgooke.html

C#:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtqfpqbaja.html

[N09] 栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gtufxjrwsd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtilltgswy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shuidangran.top/Article/details/gttwcthpzf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtmtgictrw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhongyouzk.top/Article/details/gtbxebddso.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.316326.xyz/Article/details/gtnrrornks.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.snrcjt.cn/Article/details/gtizecvtli.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtybejoqie.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dashuyun.cn/Article/details/gtjtojzhdn.html

[N10] 链表节点定义
来源：http://dali.yuanzhike.top/Article/details/gtscnfflwr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hnxiangtu.top/Article/details/gthuwvjjqg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yonumen.top/Article/details/gtpdwjqdsc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtzuosqgdg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlapuqxu.html

Java: class Node { int v; Node next; }
来源：http://dali.snrcjt.cn/Article/details/gteoczsrwv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj202588.top/Article/details/gtqsxokpom.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xinyue.icu/Article/details/gtpsdzhdlz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cdnleiting.top/Article/details/gtthetvssw.html

[N11] 二叉树中序遍历
来源：http://dali.pycfn.com/Article/details/gtbxogdzau.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenlongwang.top/Article/details/gtqgxgztwo.html

PHP:  // 手写递归函数
来源：http://dali.aizwys.cn/Article/details/gtoaapsizd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuanzx.com/Article/details/gteidoxval.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsthajywk.html

Java: // 手写递归
来源：http://dali.pycfn.com/Article/details/gteosovkyi.html

Go:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtsbizcvok.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xylfe.cn/Article/details/gtsdcyusfg.html

C#:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gtjngbdsyf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.vqdsnc.cn/Article/details/gtgoygbnuk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxuanxn.top/Article/details/gtzdadizfj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jiagoushi.top/Article/details/gtouekgiba.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gaohongyu789.top/Article/details/gtisiohikm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xinyue.icu/Article/details/gtiwoibkjw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shzxlz.cn/Article/details/gtdtksbuww.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.wangshuangyany.cn/Article/details/gtqndixdga.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jlsjyb.cn/Article/details/gthdrnmhau.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zdqjudy.top/Article/details/gtmodqakgd.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gthebiqxcr.html

O. 并发与异步
来源：http://dali.meibo888.top/Article/details/gthfowurbz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtsrsksroc.html

[O01] 启动一个线程
来源：http://dali.jqgfzy.top/Article/details/gtwomrfszf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhiwuduotai.top/Article/details/gtvdqhisqe.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shuidangran.top/Article/details/gtkxplibxe.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.redwolf501.top/Article/details/gtyitkyhwa.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gtiwgmfdph.html

Java: new Thread(() -> f()).start()
来源：http://dali.jlsjyb.cn/Article/details/gtxsxlpbwg.html

Go:   go f()
来源：http://dali.yangfankeji.com/Article/details/gttrnxksbb.html

Ruby: Thread.new { f }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvapqrpa.html

C#:   Task.Run(() => F());
来源：http://dali.svipenyu.cn/Article/details/gtfyvntvzb.html

[O02] 使用线程池
来源：http://dali.ydzc1.top/Article/details/gtarcwkaqv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxuanxn.top/Article/details/gthhnuzbmj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daria6918.cn/Article/details/gtmglawzxm.html

JS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gtcmszwhmk.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gthxzalkqd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhengqikj.top/Article/details/gtzwkndlas.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.andypj.xyz/Article/details/gtjgdbmiob.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.haohaochexian.top/Article/details/gtplhggabx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daxiang520.top/Article/details/gtzrabmnix.html

[O03] 加锁保护共享数据
来源：http://dali.chenjidiqi.icu/Article/details/gtwzunmirp.html

Py:   with lock: shared += 1
来源：http://dali.yueranfly.top/Article/details/gtzevwrged.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gtdlapgvhi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zycfv.cn/Article/details/gtutyxckmd.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gtcgvsmptk.html

Java: synchronized (this) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gtxyppcroo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ydzc1.top/Article/details/gtbmhuxrfi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.0kj1m.cn/Article/details/gtoqwlynuy.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gtrstrezpm.html

[O04] 定义异步函数并等待
来源：http://dali.redwolf501.top/Article/details/gtdukvjrqi.html

Py:   async def f():⏎    await g()
来源：http://dali.snrcjt.cn/Article/details/gtwvormsdy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gzhubu.top/Article/details/gtwphdppgu.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258.top/Article/details/gthzgkfokv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.aizwys.cn/Article/details/gtwzsorrsm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dianchejie.cn/Article/details/gtarcroazc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.guowangkeji.top/Article/details/gtceeyhlsv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cucudq.cn/Article/details/gtczqwbzjx.html

C#:   async Task F() { await G(); }
来源：http://dali.jianghu66.top/Article/details/gthmgtppkg.html

[O05] 并发执行并等待全部完成
来源：http://dali.xylfe.cn/Article/details/gtxgmlimxr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hysaishi.cn/Article/details/gtxsbzzmrg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zycfv.cn/Article/details/gtwperluir.html

JS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoklgeogs.html

TS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gtjmvdcsgj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbolacve.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jiagoushi.top/Article/details/gtkmrweyxy.html

Ruby: threads.map(&:join)
来源：http://dali.xziqi.cn/Article/details/gtfdyzfujq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gttwswhelj.html

[O06] 使用进程池
来源：http://dali.pycfn.com/Article/details/gtoyzzjjxw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shuidangran.top/Article/details/gtuqmsunce.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cdnleiting.top/Article/details/gtadcutjnp.html

JS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfendudv.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gtggirwsza.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcnkdxgr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yueranfly.top/Article/details/gtipxcpsgg.html

Ruby: // fork 块
来源：http://dali.zhongyouzk.top/Article/details/gtfcysxbsw.html

C#:   Parallel.For
来源：http://dali.pengpengdd.cyou/Article/details/gtmcumikgu.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtccnyaibe.html

P. 常用工具函数
来源：http://dali.zdqjudy.top/Article/details/gtrhhyxqkx.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtkvmroecj.html

[P01] 生成 UUID
来源：http://dali.kuanghao11.cn/Article/details/gtgeqnugrj.html

Py:   str(uuid.uuid4())
来源：http://dali.jyoumei.cn/Article/details/gtmndrmehn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.svipenyu.cn/Article/details/gtisaczohn.html

JS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gtkrchlctd.html

TS:   crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gtqxcmszwl.html

Java: UUID.randomUUID().toString()
来源：http://dali.ybcxt.top/Article/details/gtifpjuqpt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ybcxt.top/Article/details/gtozmbqwad.html

Ruby: SecureRandom.uuid
来源：http://dali.zycfv.cn/Article/details/gtkpzfzyvm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xziqi.cn/Article/details/gtqafusdnd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nanxuanxn.top/Article/details/gttdjrkmab.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ehwqpu.com/Article/details/gtphctxtbv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cheryme.top/Article/details/gtnqiwdhmo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hywenlv.cn/Article/details/gtwudfsjuf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aibaodan.cn/Article/details/gtuzqdxqsh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtyfaoxpkn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangshuangyany.cn/Article/details/gtnsduqtky.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenzaomai.com/Article/details/gtqqvchbdl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangdashe.top/Article/details/gtmdymisgn.html

[P03] 生成短随机字符串
来源：http://dali.yj20258.top/Article/details/gtavmfdoaj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.feifeiyinyue.top/Article/details/gtazfugvib.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj20258888.top/Article/details/gtachbjpal.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gttogdeknu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gtfoazmboa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenlongwang.top/Article/details/gtrnktkjoy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nwbrower.top/Article/details/gtlyjwnxcz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.kuanghao11.cn/Article/details/gtqdkuydtz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tian-w.cn/Article/details/gtqgmofgge.html

[P04] 求长度
来源：http://dali.hnqzz.top/Article/details/gtiibqqhif.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.bjfxy.top/Article/details/gtbcpmkfcc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtkbrbdnzk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gtdshmwzwi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yueranfly.top/Article/details/gthrtwazjg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ivvv.top/Article/details/gtjfrdnvxi.html

Go:   len(arr);  len(m)
来源：http://dali.tian-w.cn/Article/details/gtbwjvhxcs.html

Ruby: x.length;  x.size
来源：http://dali.snrcjt.cn/Article/details/gtnwnajbpm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jqgfzy.top/Article/details/gtgyyrqffr.html


<!-- 参考信息 -->