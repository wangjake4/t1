代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aizwys.cn/Article/details/gtotgbmtng.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigfzy.top/Article/details/gtegdqkyys.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hysaishi.cn/Article/details/gtipmammoj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhongyouzk.top/Article/details/gtvopdyxsc.html

[L07] 处理 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gtrypnuiwx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.316326.xyz/Article/details/gthwkuvgfs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.snrcjt.cn/Article/details/gtkmdfkwef.html

JS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gtrgcsudte.html

TS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtndbnnqmw.html

Java: resp.statusCode()
来源：http://dali.316326.xyz/Article/details/gtlovszobx.html

Go:   resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gtfdnfxhlq.html

Ruby: resp.code.to_i
来源：http://dali.c1oappe.top/Article/details/gteuxlzpmz.html

C#:   (int)resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gtxqbdzxay.html

[L08] 并发请求多个地址
来源：http://dali.ivvv.top/Article/details/gtyfdrdenb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sufxvd.cn/Article/details/gtrteguxxe.html

PHP:  curl_multi_init() 系列
来源：http://dali.haohaochexian.top/Article/details/gttchcxmqe.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtshvqeaoo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gtygzrjdrc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shuidangran.top/Article/details/gtxdzvejas.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zycfv.cn/Article/details/gtkpztwqxq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dianchejie.cn/Article/details/gtqpannyqq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258888.top/Article/details/gtcpxeoooi.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtxkhelxvx.html

M. 命令行 / 进程 / 环境
来源：http://dali.hysaishi.cn/Article/details/gtjvkhphaz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtzjgbsugu.html

[M01] 读取命令行参数
来源：http://dali.yuanzhike.top/Article/details/gtmajxrpdu.html

Py:   sys.argv[1:]
来源：http://dali.smart0.xyz/Article/details/gtqyuotuuo.html

PHP:  $argv;  $argc;
来源：http://dali.9152youxi.cn/Article/details/gtqxwuzxux.html

JS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gtwfwhlhly.html

TS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gthukssibt.html

Java: args 数组（main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpdejlms.html

Go:   os.Args[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtbyngirkm.html

Ruby: ARGV
来源：http://dali.fengsongda.top/Article/details/gtjcztadxy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.meibo888.top/Article/details/gtrsgmfkrf.html

[M02] 读取环境变量
来源：http://dali.fengsongda.top/Article/details/gtvydgeplr.html

Py:   os.environ.get("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtzupbacyh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtsnmsjnuj.html

JS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjmabxqh.html

TS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gtmnmifkwm.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gttkgcjbep.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtabutwojx.html

Ruby: ENV["HOME"]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnsdkvts.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xziqi.cn/Article/details/gtsknlvbkd.html

[M03] 执行外部命令
来源：http://dali.fengsongda.top/Article/details/gtpolkqzhk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zycfv.cn/Article/details/gtousytlid.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.0kj1m.cn/Article/details/gtuhegjasx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjntwlorh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtzshnjrys.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.c1oappe.top/Article/details/gtkkzvpyve.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nwbrower.top/Article/details/gtjbmvcsuz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zdqjudy.top/Article/details/gtwrrwjpyi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhoulong.xyz/Article/details/gtgjzstlee.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangtech.top/Article/details/gteweoeiyv.html

Py:   os.getcwd()
来源：http://dali.yuanzhike.top/Article/details/gtcofcfhyq.html

PHP:  getcwd();
来源：http://dali.pengpengdd.cyou/Article/details/gtxywkpjbu.html

JS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpvpkaib.html

TS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gteeidcjnw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guowangkeji.top/Article/details/gtjmayrshz.html

Go:   os.Getwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtdvmfratt.html

Ruby: Dir.pwd
来源：http://dali.zhoulong.xyz/Article/details/gtinujbohg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenjidiqi.icu/Article/details/gtxblskjxg.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gtrxeoeadv.html

Py:   sys.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpmlvsvd.html

PHP:  exit(1);
来源：http://dali.aibaodan.cn/Article/details/gtkburbzpq.html

JS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtcfzexlbn.html

TS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtsohutjna.html

Java: System.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtkczkggtb.html

Go:   os.Exit(1)
来源：http://dali.xinyue.icu/Article/details/gtjkdbersj.html

Ruby: exit 1
来源：http://dali.jinqigufen.top/Article/details/gtfxuvjunv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yanxiufei.cn/Article/details/gtutyxsitf.html

[M06] 向标准错误输出
来源：http://dali.sufxvd.cn/Article/details/gtjridejvi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj202588.top/Article/details/gtrptymeej.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yvedp.cn/Article/details/gtiotzjqjr.html

JS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gtdgjcsowi.html

TS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtdanrvlhm.html

Java: System.err.println("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtwmgpjemj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cdnleiting.top/Article/details/gtzzqbxiqe.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gtdldbsgtc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fzhhl.top/Article/details/gtwniktpub.html

[M07] 判断是否为主入口
来源：http://dali.ehwqpu.com/Article/details/gtsfpwjleg.html

Py:   if __name__ == "__main__":
来源：http://dali.zhengqikj.top/Article/details/gtcxochcxd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tianlin.xyz/Article/details/gtyttobvgp.html

JS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gtygtpkcms.html

TS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gtroweovaa.html

Java: public static void main(String[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthilzxzmx.html

Go:   func main()
来源：http://dali.vqdsnc.cn/Article/details/gtltabzbuo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.kuanghao11.cn/Article/details/gtgdlszvmq.html

C#:   static void Main(string[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gtgumfweun.html

[M08] 获取系统与运行时信息
来源：http://dali.chenlongwang.top/Article/details/gtigkxayeq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jiagoushi.top/Article/details/gtgwmerqus.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhiwuduotai.top/Article/details/gtohryaqqg.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gtlxubomfx.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gtfljlvgpk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuanzx.com/Article/details/gtcnaxqdtm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnqzz.top/Article/details/gtwcdrzcmj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nwbrower.top/Article/details/gtaynxuwmv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.c1oappe.top/Article/details/gtozocbbhp.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrterewpb.html

N. 数据结构与算法
来源：http://dali.pengpengdd.cyou/Article/details/gtwrgxrvxb.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtwdwgmgkb.html

[N01] 二分查找（有序数组）
来源：http://dali.gotoacloud.top/Article/details/gtmxsoqyju.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gthmjctrnq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtndpmjzwd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gtouijgiez.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtdboqohlq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtulnudphe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtqbwrgesb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmyjsxnq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtconbtidp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hammf.cn/Article/details/gtxbgvcshi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtuuylwpdg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuanzhike.top/Article/details/gtvntzpgvb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gtzpxffqpt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtimxhextz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.andypj.xyz/Article/details/gtqwsfuvoz.html

Go:   slices.Sort(arr)
来源：http://dali.guannengcc.top/Article/details/gtursbpaak.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gtxxuigboa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yangfankeji.com/Article/details/gtitfvnypu.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxinkj.top/Article/details/gtcdfhvkii.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.snrcjt.cn/Article/details/gtmtsjjtzw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxuanxn.top/Article/details/gtudfhfdei.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gttislqudd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gtwnjayiux.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tianlin.xyz/Article/details/gtimwrnyki.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sufxvd.cn/Article/details/gtkywutqaw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shangyingyoupin.top/Article/details/gtaorgjiwr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnxiangtu.top/Article/details/gtkrkkkrml.html

[N04] 斐波那契数列
来源：http://dali.nwbrower.top/Article/details/gtqaebqhes.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gtwiedtolc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcdugmhn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtueaaxdnt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtefunjmxe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.guannengcc.top/Article/details/gtqtdncdgg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xinyue.icu/Article/details/gtevvdztvo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gtubkcsvcz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gtbxtzmdkj.html

[N05] 最大公约数
来源：http://dali.cheryme.top/Article/details/gtqrlqzgjc.html

Py:   math.gcd(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtzpnkrkxs.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgfzy.top/Article/details/gtllntlnze.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fzhhl.top/Article/details/gtqhtwnwxu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttakoccmp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sufxvd.cn/Article/details/gtarrdkaot.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tianlin.xyz/Article/details/gtykaxwjso.html

Ruby: a.gcd(b)
来源：http://dali.jqgufenzy.top/Article/details/gtiiosfphz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sxryk.cn/Article/details/gtewbiaeaj.html

[N06] 判断回文字符串
来源：http://dali.tian-w.cn/Article/details/gthzfvrfsw.html

Py:   s == s[::-1]
来源：http://dali.fzhhl.top/Article/details/gtasenqofv.html

PHP:  $s === strrev($s);
来源：http://dali.gzhubu.top/Article/details/gtscxujqjm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtidayadri.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtetgsmyuw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuanzhike.top/Article/details/gtchdyokwz.html

Go:   // 双指针从两端比较
来源：http://dali.ydzc1.top/Article/details/gtewjgqtzl.html

Ruby: s == s.reverse
来源：http://dali.hysaishi.cn/Article/details/gtmjoycbhl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gtbkwrkwwo.html

[N07] 两数之和（返回下标）
来源：http://dali.ppjwa.cn/Article/details/gtmtpyanmv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dashuyun.cn/Article/details/gtmdxqcsdy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cqqwz.cn/Article/details/gtzjnyunuy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ppjwa.cn/Article/details/gtamxpwoua.html

TS:   // 手写 Map<string, number>
来源：http://dali.cqqwz.cn/Article/details/gtgvrebwhx.html

Java: // 手写 HashMap
来源：http://dali.havefunace.top/Article/details/gtpcuapkhp.html

Go:   // 手写 map[int]int
来源：http://dali.jyoumei.cn/Article/details/gtqdkbzspt.html

Ruby: // 手写 Hash
来源：http://dali.gaohongyu789.top/Article/details/gtsdaxxnmu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinqigfzy.top/Article/details/gtgijixzdi.html

[N08] 生成全排列
来源：http://dali.svipenyu.cn/Article/details/gtsqdgnody.html

Py:   itertools.permutations(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtzmsbmjee.html

PHP:  // 手写递归交换
来源：http://dali.zhoulong.xyz/Article/details/gtqbuzbtre.html

JS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtaozztrpx.html

TS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqskaelix.html

Java: // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtbrfdzwrb.html

Go:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtzqlfzlov.html

Ruby: arr.permutation.to_a
来源：http://dali.jqgufenzy.top/Article/details/gtjufwlwlk.html

C#:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtwbipeefa.html

[N09] 栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtughkxrti.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhengqikj.top/Article/details/gtvxdrkbti.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtsoukqndn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtwwgztnnu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shangyingyoupin.top/Article/details/gtuyyucqca.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.c1oappe.top/Article/details/gtkqkbjekv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhixingplan.top/Article/details/gtvglcuceh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtccqlqinw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.svipenyu.cn/Article/details/gtlcrlfsiu.html

[N10] 链表节点定义
来源：http://dali.nanxinkj.top/Article/details/gtkverasnu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shuidangran.top/Article/details/gtzweewrcd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dianchejie.cn/Article/details/gtibcvpduh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprgpxzrf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258.top/Article/details/gtsabrvkwa.html

Java: class Node { int v; Node next; }
来源：http://dali.zhoulong.xyz/Article/details/gtpvvflfbe.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hammf.cn/Article/details/gtprjnhnqd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.quarkkingdee.top/Article/details/gthdxbnqvb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.birdmap.top/Article/details/gtieeamfqg.html

[N11] 二叉树中序遍历
来源：http://dali.gaohongyu789.top/Article/details/gtflqdrxfz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yuanzhike.top/Article/details/gterfmuvcl.html

PHP:  // 手写递归函数
来源：http://dali.nanxinkj.top/Article/details/gtkvagtmhh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gtdwpehxgq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yonumen.top/Article/details/gtlbqeamcy.html

Java: // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtzqyuqngr.html

Go:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtnjravohp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tian-w.cn/Article/details/gtryzroofj.html

C#:   // 手写递归
来源：http://dali.sweek.top/Article/details/gtbiatmwjg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cucudq.cn/Article/details/gtemkatwwi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.smart0.xyz/Article/details/gtndygdxvj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.guowangkeji.top/Article/details/gtireastsu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gtyizkttyk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gtdotjxyee.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtofgdzjjs.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.quarkkingdee.top/Article/details/gtlrvrkwrh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.haohaochexian.top/Article/details/gtsusiquqq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gtwefkwfwx.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtmbbqomse.html

O. 并发与异步
来源：http://dali.mhx1999.top/Article/details/gtwojiiqgg.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtxajnwrah.html

[O01] 启动一个线程
来源：http://dali.chenzaomai.com/Article/details/gtuifyqecr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxmrrqna.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hongshengwenyu.top/Article/details/gtgxrefffl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cdnleiting.top/Article/details/gtzncqlmxy.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gtwvbpxlkh.html

Java: new Thread(() -> f()).start()
来源：http://dali.shzxlz.cn/Article/details/gtdvcmmosg.html

Go:   go f()
来源：http://dali.daxiang520.top/Article/details/gtzluithgq.html

Ruby: Thread.new { f }
来源：http://dali.cheryme.top/Article/details/gtrkfekgox.html

C#:   Task.Run(() => F());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjwcjjrc.html

[O02] 使用线程池
来源：http://dali.kuanghao11.cn/Article/details/gtlbebsqkm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.snrcjt.cn/Article/details/gtxpfzkmav.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guowangkeji.top/Article/details/gtjithnjwm.html

JS:   // worker_threads 线程池
来源：http://dali.chenlongwang.top/Article/details/gtwvmhfybv.html

TS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpifvapa.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ivvv.top/Article/details/gtngzhvxqz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhiwuduotai.top/Article/details/gtjlyanrya.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuanzx.com/Article/details/gtcuvygxzl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cashguo.top/Article/details/gtyupsvdad.html

[O03] 加锁保护共享数据
来源：http://dali.zhixingplan.top/Article/details/gtqcvgkusi.html

Py:   with lock: shared += 1
来源：http://dali.pycfn.com/Article/details/gtosqwaepk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.bjfxy.top/Article/details/gtqhfwjeze.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tanke756.top/Article/details/gtjcnpdbpm.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gtyulvyjwp.html

Java: synchronized (this) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gtxwduoscu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.feifeiyinyue.top/Article/details/gtkzhaofqi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pengpengdd.cyou/Article/details/gtdhenjgmv.html

C#:   lock (gate) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gtiggbvhrx.html

[O04] 定义异步函数并等待
来源：http://dali.yueranfly.top/Article/details/gtgttfildl.html

Py:   async def f():⏎    await g()
来源：http://dali.svipenyu.cn/Article/details/gthvexpcwa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.bjfxy.top/Article/details/gtwsxlxgrg.html

JS:   async function f() { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gtuxowplqg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtfuisohba.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.quarkkingdee.top/Article/details/gtflghgkdx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuetiantiany.cn/Article/details/gtddjatdby.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xziqi.cn/Article/details/gtujczezwr.html

C#:   async Task F() { await G(); }
来源：http://dali.yanxiufei.cn/Article/details/gtowpbtqan.html

[O05] 并发执行并等待全部完成
来源：http://dali.ybcxt.top/Article/details/gtgfbrlnes.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtxyknthiv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jlsjyb.cn/Article/details/gtdnkkxyna.html

JS:   await Promise.all(tasks)
来源：http://dali.zhixingplan.top/Article/details/gttmerhbmq.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtmoivinvd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jiagoushi.top/Article/details/gtnctojrsg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhongyouzk.top/Article/details/gtemxtansn.html

Ruby: threads.map(&:join)
来源：http://dali.haohaochexian.top/Article/details/gtqlwdzuol.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.bjfxy.top/Article/details/gthxgkbfvm.html

[O06] 使用进程池
来源：http://dali.zhiwuduotai.top/Article/details/gtbpqkpwar.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhixingplan.top/Article/details/gtbzuchwct.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhongyouzk.top/Article/details/gtzirtzaex.html

JS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gtvhyfiwun.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gtrmoviwlt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.redwolf501.top/Article/details/gttwfjjxtb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hysaishi.cn/Article/details/gtbopqhdbi.html

Ruby: // fork 块
来源：http://dali.xinyue.icu/Article/details/gtpowtgkly.html

C#:   Parallel.For
来源：http://dali.zhixingplan.top/Article/details/gtepsxxyzn.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtivymxnor.html

P. 常用工具函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnzrcprk.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtmgmsptbr.html

[P01] 生成 UUID
来源：http://dali.aizwys.cn/Article/details/gtqxmipsdu.html

Py:   str(uuid.uuid4())
来源：http://dali.kuanghao11.cn/Article/details/gtjlfodxgu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gthnihkdqa.html

JS:   crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gtamirxptl.html

TS:   crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gtnpsnvnmt.html

Java: UUID.randomUUID().toString()
来源：http://dali.cdnleiting.top/Article/details/gtsjjavtfh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqwbfaaj.html

Ruby: SecureRandom.uuid
来源：http://dali.gzhubu.top/Article/details/gtrhbkhkwk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtonaayjkp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sweek.top/Article/details/gtnlyjofsg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuanzhike.top/Article/details/gtcxlqwcqd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cdnleiting.top/Article/details/gtvmshymck.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtgxtlnosr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jyoumei.cn/Article/details/gtwokrpeek.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258888.top/Article/details/gtekbnccnb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj202588.top/Article/details/gtohacoiyb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtcigimimq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shzxlz.cn/Article/details/gtoymbhrli.html

[P03] 生成短随机字符串
来源：http://dali.tian-w.cn/Article/details/gtdhrvxmjf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.snrcjt.cn/Article/details/gthnspxyqi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cdnleiting.top/Article/details/gtpmgcefyf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gtkigvypwp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuxming.cn/Article/details/gttcbifvhn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.haohaochexian.top/Article/details/gtvhwtldyh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aibaodan.cn/Article/details/gtbgtfdhsa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvwtqnmn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xuanzx.com/Article/details/gtauxpcthh.html

[P04] 求长度
来源：http://dali.dianchejie.cn/Article/details/gthhjwywkb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuxming.cn/Article/details/gtlpfrskfe.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gthkypinsw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gtxygizuss.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gtysldkbgb.html


<!-- 参考信息 -->