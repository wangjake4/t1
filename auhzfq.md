代发 wailian999

Py:   resp.json()
来源：http://dali.jiagoushi.top/Article/details/gttrptzkfu.html

PHP:  json_decode($body, true);
来源：http://dali.hywenlv.cn/Article/details/gtbymefzvv.html

JS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtmpnbrlni.html

TS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtermkbgct.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwkrvwaf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuxming.cn/Article/details/gtvqtsayxs.html

Ruby: JSON.parse(resp.body)
来源：http://dali.pengpengdd.cyou/Article/details/gtokawlkwu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cdnleiting.top/Article/details/gtsajjpxse.html

[L07] 处理 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gtosmlnppu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gtyyulxjxb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gtamegjszw.html

JS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gttqlzpnpc.html

TS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gtktejbved.html

Java: resp.statusCode()
来源：http://dali.xuetiantiany.cn/Article/details/gtmyxqnntc.html

Go:   resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gtqegmpbms.html

Ruby: resp.code.to_i
来源：http://dali.sufxvd.cn/Article/details/gtuzeyrsvd.html

C#:   (int)resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmujigemv.html

[L08] 并发请求多个地址
来源：http://dali.zhoulong.xyz/Article/details/gttrxlibeg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daria6918.cn/Article/details/gtokzqtcvb.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxuanxn.top/Article/details/gteiojirzx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtnljxorwr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtjbgycdjr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrbawfsa.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xziqi.cn/Article/details/gtveijhccg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczvcrcba.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gotoacloud.top/Article/details/gtemaujdmc.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtlavvhfqs.html

M. 命令行 / 进程 / 环境
来源：http://dali.yvedp.cn/Article/details/gtcaetuozv.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtxddkadjq.html

[M01] 读取命令行参数
来源：http://dali.yj20258.top/Article/details/gtkknwlzmb.html

Py:   sys.argv[1:]
来源：http://dali.ehwqpu.com/Article/details/gtrtlaaedd.html

PHP:  $argv;  $argc;
来源：http://dali.shuidangran.top/Article/details/gtdvdexfsm.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtpytdgljy.html

TS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gtjxkxuvri.html

Java: args 数组（main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gttomqkbqg.html

Go:   os.Args[1:]
来源：http://dali.haohaochexian.top/Article/details/gtebneqocl.html

Ruby: ARGV
来源：http://dali.pycfn.com/Article/details/gttpiweeaw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gtvhljhqko.html

[M02] 读取环境变量
来源：http://dali.yj202588.top/Article/details/gtdrfkjatd.html

Py:   os.environ.get("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikdwyjll.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gtbbgbffvw.html

JS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gtbgtpelta.html

TS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gthyvykkmn.html

Java: System.getenv("HOME")
来源：http://dali.fzhhl.top/Article/details/gtdwbshnnm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtsgeubvao.html

Ruby: ENV["HOME"]
来源：http://dali.pycfn.com/Article/details/gtllpppatj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.smart0.xyz/Article/details/gtbiwajpqp.html

[M03] 执行外部命令
来源：http://dali.guowangkeji.top/Article/details/gtmfkbdpfm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gzhubu.top/Article/details/gtzwozujta.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ydzc1.top/Article/details/gtxdxiwrns.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtxhwdhawv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtchzbgarr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgufenzy.top/Article/details/gtmnhrrsmy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zycfv.cn/Article/details/gtkbdzupgd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guowangkeji.top/Article/details/gtqkcfjihe.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yueranfly.top/Article/details/gttwqqrczs.html

[M04] 获取当前工作目录
来源：http://dali.xylfe.cn/Article/details/gtjhhwgzqf.html

Py:   os.getcwd()
来源：http://dali.zhoulong.xyz/Article/details/gttxainszl.html

PHP:  getcwd();
来源：http://dali.gaohongyu789.top/Article/details/gtwevmfmjm.html

JS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gtbtuxozeq.html

TS:   process.cwd()
来源：http://dali.yj20258888.top/Article/details/gtrtwvtttz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhiwuduotai.top/Article/details/gtorgcsrkt.html

Go:   os.Getwd()
来源：http://dali.ivvv.top/Article/details/gtrjmcdtur.html

Ruby: Dir.pwd
来源：http://dali.hysaishi.cn/Article/details/gttautddjw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmkebfiq.html

[M05] 设置退出码
来源：http://dali.shuidangran.top/Article/details/gtqmegthqq.html

Py:   sys.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtpqbwsipe.html

PHP:  exit(1);
来源：http://dali.yj20258.top/Article/details/gtofapruqj.html

JS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gtpquwqhkn.html

TS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtcdzlczmq.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtmuebwbyt.html

Go:   os.Exit(1)
来源：http://dali.hnqzz.top/Article/details/gtmkncrqrb.html

Ruby: exit 1
来源：http://dali.vqdsnc.cn/Article/details/gtrvpiwopp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daxiang520.top/Article/details/gtlmynaoeg.html

[M06] 向标准错误输出
来源：http://dali.hfpthk.cn/Article/details/gtaboueegw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.haohaochexian.top/Article/details/gtddxpobap.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.snrcjt.cn/Article/details/gtgqkfjlej.html

JS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gtmwccgohh.html

TS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gtzpnuzezw.html

Java: System.err.println("err")
来源：http://dali.shuidangran.top/Article/details/gtucjahcbh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zycfv.cn/Article/details/gtoindeper.html

Ruby: warn "err"
来源：http://dali.smart0.xyz/Article/details/gtkgkishoa.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnvaxowh.html

[M07] 判断是否为主入口
来源：http://dali.jqgfzy.top/Article/details/gtdgizvvvm.html

Py:   if __name__ == "__main__":
来源：http://dali.jlsjyb.cn/Article/details/gthcqrcfbp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gaohongyu789.top/Article/details/gtvdoalkde.html

JS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gtrilmrarz.html

TS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gtpmlmbscb.html

Java: public static void main(String[] args)
来源：http://dali.birdmap.top/Article/details/gtwirwramt.html

Go:   func main()
来源：http://dali.ydzc1.top/Article/details/gtcuyxoyhn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgufenzy.top/Article/details/gtekrkjskc.html

C#:   static void Main(string[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gtykeriybh.html

[M08] 获取系统与运行时信息
来源：http://dali.hnqzz.top/Article/details/gtjpbdexgp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daria6918.cn/Article/details/gtlszbrdri.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.birdmap.top/Article/details/gtmeskyhxi.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gtgenfeaph.html

TS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gtccoouqjl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnqzz.top/Article/details/gttpcmnvxf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuanzx.com/Article/details/gtotprnpkb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhengqikj.top/Article/details/gtgbgzorzi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.svipenyu.cn/Article/details/gtyxjafsbz.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtwycbrjrm.html

N. 数据结构与算法
来源：http://dali.guannengcc.top/Article/details/gtwrrzhwdk.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gttppumchg.html

[N01] 二分查找（有序数组）
来源：http://dali.snrcjt.cn/Article/details/gtorvdqnxn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ivvv.top/Article/details/gtwlgutzud.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tian-w.cn/Article/details/gtouygupfy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gtfqxhphcb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gtcqqyginr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtjluighyz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xziqi.cn/Article/details/gteihlthqj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xinyue.icu/Article/details/gtzohnfghc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtibppvbhq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gtpmbikpuw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gtvsegytar.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cucudq.cn/Article/details/gtjntawoat.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gttrnjacda.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gtkkktblog.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258.top/Article/details/gtkqdswymt.html

Go:   slices.Sort(arr)
来源：http://dali.tian-w.cn/Article/details/gtcgzttdms.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gtbmhumavw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.quarkkingdee.top/Article/details/gtdaupvywn.html

[N03] 快速排序（分治示例）
来源：http://dali.wangdashe.top/Article/details/gtizbyfkoh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258888.top/Article/details/gthbekylwk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sysykeji.top/Article/details/gtppzopffk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gthdcvdxet.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtippocw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daria6918.cn/Article/details/gtwlaesjga.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dashuyun.cn/Article/details/gtmeumoqvb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yuxming.cn/Article/details/gtmtthszpa.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aibaodan.cn/Article/details/gtpaosckof.html

[N04] 斐波那契数列
来源：http://dali.jianghu66.top/Article/details/gtrveknikb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gtzfkoxvvf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gtxzfdzmqy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gtyvvwirdx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gthsokavjy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gtkfiaugdf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.9152youxi.cn/Article/details/gtrpvyqlxn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sufxvd.cn/Article/details/gtjvalufrc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtrmqwexsp.html

[N05] 最大公约数
来源：http://dali.hysaishi.cn/Article/details/gtpdlzkcqv.html

Py:   math.gcd(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtodebvjhi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdhoibuxt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtnddxiosl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gthuhlymhq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dianchejie.cn/Article/details/gtgvbnplvo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.wangdashe.top/Article/details/gtkeviasto.html

Ruby: a.gcd(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtititfzum.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ehwqpu.com/Article/details/gtpewyvhqa.html

[N06] 判断回文字符串
来源：http://dali.meibo888.top/Article/details/gtgruasrkf.html

Py:   s == s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gtkgsxhkfy.html

PHP:  $s === strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtbzidoztm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtnxytxvfx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtdjdqoblp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwjaygoc.html

Go:   // 双指针从两端比较
来源：http://dali.jqgfzy.top/Article/details/gtavvptrvy.html

Ruby: s == s.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtvqyyhawi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gteewrztsm.html

[N07] 两数之和（返回下标）
来源：http://dali.c1oappe.top/Article/details/gtzpqrelgs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jianghu66.top/Article/details/gtalkjwyew.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fzhhl.top/Article/details/gtclzyhjwk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.redwolf501.top/Article/details/gtxqtvaijv.html

TS:   // 手写 Map<string, number>
来源：http://dali.xylfe.cn/Article/details/gtsldhupde.html

Java: // 手写 HashMap
来源：http://dali.jqgufenzy.top/Article/details/gtbjgncdnd.html

Go:   // 手写 map[int]int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqbaufui.html

Ruby: // 手写 Hash
来源：http://dali.hfpthk.cn/Article/details/gtqjslkvid.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.kuanghao11.cn/Article/details/gthqgmbsqn.html

[N08] 生成全排列
来源：http://dali.svipenyu.cn/Article/details/gtnmvtyyev.html

Py:   itertools.permutations(arr)
来源：http://dali.yj20258888.top/Article/details/gtvsfsnhjz.html

PHP:  // 手写递归交换
来源：http://dali.chenlongwang.top/Article/details/gtpgqwnzmb.html

JS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtfeyziazb.html

TS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtlvpqnowa.html

Java: // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtwfdlcmsn.html

Go:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtmknnztst.html

Ruby: arr.permutation.to_a
来源：http://dali.chenjidiqi.icu/Article/details/gtmdbfiaos.html

C#:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtygadzaok.html

[N09] 栈与队列
来源：http://dali.nwbrower.top/Article/details/gtnksssipi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtogyolrnj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtstepbjpa.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtuslrksln.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvspurhb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gtclxnvhrr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cashguo.top/Article/details/gtfhpsrxzs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtgcugcswz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuanzhike.top/Article/details/gtkehaovzc.html

[N10] 链表节点定义
来源：http://dali.sufxvd.cn/Article/details/gtrbqafpjq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zycfv.cn/Article/details/gtqtmngyso.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zdqjudy.top/Article/details/gtvbhtgizr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ybcxt.top/Article/details/gtrtfwkuxp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigfzy.top/Article/details/gtmwqsovfj.html

Java: class Node { int v; Node next; }
来源：http://dali.yj202588.top/Article/details/gtdaxwkgqx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxinkj.top/Article/details/gtaqatssvo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cashguo.top/Article/details/gttakntgla.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.wangdashe.top/Article/details/gtfilczpgy.html

[N11] 二叉树中序遍历
来源：http://dali.cdnleiting.top/Article/details/gtndufrrvk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jlsjyb.cn/Article/details/gtvjylmcwv.html

PHP:  // 手写递归函数
来源：http://dali.xuetiantiany.cn/Article/details/gtacrsecov.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gtpedgzlpa.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tanke756.top/Article/details/gtkxfcvmbe.html

Java: // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gturrnricz.html

Go:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtcheesomc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.meibo888.top/Article/details/gtcuhfcdac.html

C#:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtczwxeeso.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ivvv.top/Article/details/gtxotkxeoh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.vqdsnc.cn/Article/details/gtzxdvrnad.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpamvxvv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gtsmuhshfp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtaombhnty.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxinkj.top/Article/details/gtqzgeesku.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yongpay.top/Article/details/gtakgdkdga.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jlsjyb.cn/Article/details/gtydnnlqox.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.birdmap.top/Article/details/gtnnvnyfqa.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhwhcpvh.html

O. 并发与异步
来源：http://dali.redwolf501.top/Article/details/gtvazlwoes.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtjftriduc.html

[O01] 启动一个线程
来源：http://dali.sweek.top/Article/details/gtkplwbltz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenzaomai.com/Article/details/gtptnueiik.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jianghu66.top/Article/details/gtvfkmnher.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.c1oappe.top/Article/details/gtoftclgrn.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gtlxcuzqyu.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbcqiwhlk.html

Go:   go f()
来源：http://dali.cdnleiting.top/Article/details/gtvnxpeahq.html

Ruby: Thread.new { f }
来源：http://dali.chenjidiqi.icu/Article/details/gtdttxyhdq.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258.top/Article/details/gtswzhvxhq.html

[O02] 使用线程池
来源：http://dali.tianlin.xyz/Article/details/gtcotnzaey.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hywenlv.cn/Article/details/gtljnlkvjs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258.top/Article/details/gtpvazebcr.html

JS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gtvcukthhc.html

TS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtgskwelza.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hfpthk.cn/Article/details/gtgfotjvol.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.redwolf501.top/Article/details/gtpkmcykfo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehkshiaq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinghuilouyu.cn/Article/details/gtncgkrrqq.html

[O03] 加锁保护共享数据
来源：http://dali.sxryk.cn/Article/details/gtpkzitwsg.html

Py:   with lock: shared += 1
来源：http://dali.yuanzhike.top/Article/details/gtcnrdvdtp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhongyouzk.top/Article/details/gtzzadrdnp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvnvuvao.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gtqhunupkg.html

Java: synchronized (this) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtcfiiabnv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinqigufen.top/Article/details/gtrhpxdfng.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yvedp.cn/Article/details/gtjjhbrflt.html

C#:   lock (gate) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gtojbywjhn.html

[O04] 定义异步函数并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidtdgrvx.html

Py:   async def f():⏎    await g()
来源：http://dali.ppjwa.cn/Article/details/gtqlqiqjtz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shzxlz.cn/Article/details/gtvxaqpnwf.html

JS:   async function f() { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtbbmdpfuk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gtprbpkstj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.snrcjt.cn/Article/details/gtpnzzwtfu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.316326.xyz/Article/details/gtcdyqgtwu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhengqikj.top/Article/details/gttfqepeez.html

C#:   async Task F() { await G(); }
来源：http://dali.hysaishi.cn/Article/details/gtvcfaliii.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenjidiqi.icu/Article/details/gtabxuyapm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.bjfxy.top/Article/details/gtqejfnika.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.kuanghao11.cn/Article/details/gttplvglhs.html

JS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtfzthqoey.html

TS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtqngemuaj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ehwqpu.com/Article/details/gtscnjqamb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jiagoushi.top/Article/details/gtcgzndodn.html

Ruby: threads.map(&:join)
来源：http://dali.yonumen.top/Article/details/gtiunmvwzo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yonumen.top/Article/details/gtxuvgcqpm.html

[O06] 使用进程池
来源：http://dali.jinqigfzy.top/Article/details/gtcxlrmjyt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cdnleiting.top/Article/details/gttfhhnvxb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj20258888.top/Article/details/gtpymhhhfv.html

JS:   // child_process / cluster 模块
来源：http://dali.sufxvd.cn/Article/details/gtewttqueo.html

TS:   // child_process / cluster 模块
来源：http://dali.guowangkeji.top/Article/details/gtgxhfxbie.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hywenlv.cn/Article/details/gtbdqnnuzf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj202588.top/Article/details/gtyxnypzeg.html

Ruby: // fork 块
来源：http://dali.quarkkingdee.top/Article/details/gtprfdvsqa.html

C#:   Parallel.For
来源：http://dali.yueranfly.top/Article/details/gtcdmogxpi.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtvodrxkrt.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gtgnqsdpmu.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtrnooqplq.html

[P01] 生成 UUID
来源：http://dali.shangyingyoupin.top/Article/details/gtauzjukeh.html

Py:   str(uuid.uuid4())
来源：http://dali.zhongyouzk.top/Article/details/gtuaduoois.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jiagoushi.top/Article/details/gtxfnzuxsr.html

JS:   crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gtgtoiyuji.html

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmpipihc.html

Java: UUID.randomUUID().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtefmzykyx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnxiangtu.top/Article/details/gtykdoahuk.html

Ruby: SecureRandom.uuid
来源：http://dali.cucudq.cn/Article/details/gtxgmlbhxq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnxiangtu.top/Article/details/gtkojvlkfq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.haohaochexian.top/Article/details/gtqprivadd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tanke756.top/Article/details/gthegbburh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shzxlz.cn/Article/details/gtvspswatl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hfpthk.cn/Article/details/gtpoeszbiw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ppjwa.cn/Article/details/gtslfzgptg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.iojbl.cn/Article/details/gttjbeezgr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.9152youxi.cn/Article/details/gtrgzagjey.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yueranfly.top/Article/details/gtewvrwjrv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.havefunace.top/Article/details/gthlskztmc.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gtuhgjztsc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cqqwz.cn/Article/details/gtnljliclj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gotoacloud.top/Article/details/gtwuyqfypk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gtdkueamwr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtfuoojtsp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daria6918.cn/Article/details/gtericoflb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aibaodan.cn/Article/details/gtmmjzagtx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuetiantiany.cn/Article/details/gtdxrhqffw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.feifeiyinyue.top/Article/details/gtlfslwbry.html

[P04] 求长度
来源：http://dali.dianchejie.cn/Article/details/gtnzbqvaxz.html


<!-- 参考信息 -->