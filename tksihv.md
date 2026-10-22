代发 wailian999

Py:   resp.json()
来源：http://dali.yvedp.cn/Article/details/gtlwnqgimw.html

PHP:  json_decode($body, true);
来源：http://dali.svipenyu.cn/Article/details/gtlrceapwz.html

JS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gtovjpoyew.html

TS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gtiwepvove.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtujzsgsia.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cashguo.top/Article/details/gtsfmykbsi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.c1oappe.top/Article/details/gtiwyldaxl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gotoacloud.top/Article/details/gtmeyzekya.html

[L07] 处理 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gtivhmkxis.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj202588.top/Article/details/gtkjcyrvgu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xziqi.cn/Article/details/gtinjtejzc.html

JS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtdswfubyu.html

TS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gtrzzucwlu.html

Java: resp.statusCode()
来源：http://dali.ehwqpu.com/Article/details/gtbbcclicd.html

Go:   resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtiadbmgab.html

Ruby: resp.code.to_i
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbuitxnv.html

C#:   (int)resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gttjgovroq.html

[L08] 并发请求多个地址
来源：http://dali.hywenlv.cn/Article/details/gtypcjpeeh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zdqjudy.top/Article/details/gtjkzgzrum.html

PHP:  curl_multi_init() 系列
来源：http://dali.daxiang520.top/Article/details/gtyudfmqbn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gtgvaagxaw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtmaevmfbi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yanxiufei.cn/Article/details/gtixxekwzb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangdashe.top/Article/details/gtvoysaecw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.smart0.xyz/Article/details/gtjcbchttc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pycfn.com/Article/details/gtfdgokpxz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtrbqyqcpe.html

M. 命令行 / 进程 / 环境
来源：http://dali.cqqwz.cn/Article/details/gtofqstnyk.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtaqatuicz.html

[M01] 读取命令行参数
来源：http://dali.aibaodan.cn/Article/details/gtuohnsrdz.html

Py:   sys.argv[1:]
来源：http://dali.hammf.cn/Article/details/gtyljwsjid.html

PHP:  $argv;  $argc;
来源：http://dali.feifeiyinyue.top/Article/details/gtfaqhabqf.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtsplnozhj.html

TS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtjekczwif.html

Java: args 数组（main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gtkdkuwxzx.html

Go:   os.Args[1:]
来源：http://dali.pycfn.com/Article/details/gtlvjqnkme.html

Ruby: ARGV
来源：http://dali.chenlongwang.top/Article/details/gtmwjinhwe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yongpay.top/Article/details/gtqixflcnh.html

[M02] 读取环境变量
来源：http://dali.yj202588.top/Article/details/gtdsymigxl.html

Py:   os.environ.get("HOME")
来源：http://dali.fengsongda.top/Article/details/gtruuoylve.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gtpiklerer.html

JS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gtmuxkrrbu.html

TS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtlndzguko.html

Java: System.getenv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtvzkufzvl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tian-w.cn/Article/details/gtgkaovcos.html

Ruby: ENV["HOME"]
来源：http://dali.yj202588.top/Article/details/gtvnainxtm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtzmveccsr.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gtbcgaxtro.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.316326.xyz/Article/details/gtuszrokoz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gaohongyu789.top/Article/details/gtnraoeaxk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtyzbvffbs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gtxgbcersn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jlsjyb.cn/Article/details/gthqnlmyzx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cdnleiting.top/Article/details/gtygphrpvm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvnlfpwlb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shangyingyoupin.top/Article/details/gtuxqcgvdy.html

[M04] 获取当前工作目录
来源：http://dali.yj202588.top/Article/details/gtozgyxmdg.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gtmlvpcsgp.html

PHP:  getcwd();
来源：http://dali.hnqzz.top/Article/details/gttguqrwjh.html

JS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gtbkysxucb.html

TS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gtvnfjpcik.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yanxiufei.cn/Article/details/gtcdwgarog.html

Go:   os.Getwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfcsiaoc.html

Ruby: Dir.pwd
来源：http://dali.cucudq.cn/Article/details/gtggsxeyzi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.haohaochexian.top/Article/details/gtshytqxla.html

[M05] 设置退出码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidogcehn.html

Py:   sys.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtdfetpoea.html

PHP:  exit(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzcjsuwq.html

JS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gtuqpimytw.html

TS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtkaqqxlxu.html

Java: System.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtykifehnb.html

Go:   os.Exit(1)
来源：http://dali.yuxming.cn/Article/details/gtlznpyyyo.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gtsicndrnw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnqzz.top/Article/details/gtghzqnujs.html

[M06] 向标准错误输出
来源：http://dali.jianghu66.top/Article/details/gtfwkhuapf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxinkj.top/Article/details/gtvlnptqio.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hywenlv.cn/Article/details/gtwpctgqhx.html

JS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gtbapxkoah.html

TS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gtxsexpjye.html

Java: System.err.println("err")
来源：http://dali.smart0.xyz/Article/details/gtcoxjmhkv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yanxiufei.cn/Article/details/gtvgovjgvs.html

Ruby: warn "err"
来源：http://dali.tanke756.top/Article/details/gtysdljwdr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.c1oappe.top/Article/details/gttuwkjrkj.html

[M07] 判断是否为主入口
来源：http://dali.aibaodan.cn/Article/details/gtwulskeoy.html

Py:   if __name__ == "__main__":
来源：http://dali.chenzaomai.com/Article/details/gtdpdvxqmz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gogol.net.cn/Article/details/gtogupkyle.html

JS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gtmdvwmdbx.html

TS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gthfaxnnbx.html

Java: public static void main(String[] args)
来源：http://dali.ybcxt.top/Article/details/gtqvpdcdbt.html

Go:   func main()
来源：http://dali.xziqi.cn/Article/details/gtlfqnugzu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zycfv.cn/Article/details/gtubwzphml.html

C#:   static void Main(string[] args)
来源：http://dali.cucudq.cn/Article/details/gtsemndenr.html

[M08] 获取系统与运行时信息
来源：http://dali.ybcxt.top/Article/details/gtygxphuap.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yvedp.cn/Article/details/gtjtknofpk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhongyouzk.top/Article/details/gtuvdjdyuv.html

JS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gtrsccbfvt.html

TS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gtdwaqtvvi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.havefunace.top/Article/details/gtsffkiiqw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gotoacloud.top/Article/details/gtzrjukhsi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cheryme.top/Article/details/gtdcczfisw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jianghu66.top/Article/details/gtaugdgjbe.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtmzjzvvad.html

N. 数据结构与算法
来源：http://dali.jianghu66.top/Article/details/gtkefdtejn.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtaonjhgce.html

[N01] 二分查找（有序数组）
来源：http://dali.zhongyouzk.top/Article/details/gtcgrnmyxg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtrhuyagez.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.bjfxy.top/Article/details/gtomslyvhf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtswbuiugc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtmsfftvig.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtqpbzjjzm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtbfhyjxpe.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hammf.cn/Article/details/gtnbjxcfkr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtvonrpuep.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cdnleiting.top/Article/details/gtfwfhlpow.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.smart0.xyz/Article/details/gtywshhjrr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenlongwang.top/Article/details/gtzoctjgvg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gtohdzsrsl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gtdbcuftoa.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigufen.top/Article/details/gtlxenfkrv.html

Go:   slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gtcgsxzksd.html

Ruby: arr.sort
来源：http://dali.jqgfzy.top/Article/details/gtxqhfezrs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjbqltdl.html

[N03] 快速排序（分治示例）
来源：http://dali.bjfxy.top/Article/details/gthurmjian.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pengpengdd.cyou/Article/details/gtwlwiqhsb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dashuyun.cn/Article/details/gtfpasysru.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gtaknvssnx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gtpdojberp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.snrcjt.cn/Article/details/gtdkghqzuc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shzxlz.cn/Article/details/gtpgosrjom.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhoulong.xyz/Article/details/gtmbcavoko.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ppjwa.cn/Article/details/gtdyxdrcpm.html

[N04] 斐波那契数列
来源：http://dali.fzhhl.top/Article/details/gtfndangdr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gtteyymzzl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gtnyqzdmnk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gthwpnntgi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtctgmtzrv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumjnbogy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hysaishi.cn/Article/details/gtpbulsedm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.316326.xyz/Article/details/gtpkdususd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtnuwzriwf.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gtopsxkrqn.html

Py:   math.gcd(a, b)
来源：http://dali.yvedp.cn/Article/details/gtujnhtamw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.vqdsnc.cn/Article/details/gtrvuzgozn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gthxexnzph.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtggeyvbpk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmzeqmwh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aibaodan.cn/Article/details/gtwqalgjpr.html

Ruby: a.gcd(b)
来源：http://dali.xuanzx.com/Article/details/gtynuolufr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zdqjudy.top/Article/details/gtnnnxolnd.html

[N06] 判断回文字符串
来源：http://dali.cucudq.cn/Article/details/gtyscdkdnq.html

Py:   s == s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gtgeueuujl.html

PHP:  $s === strrev($s);
来源：http://dali.hammf.cn/Article/details/gtorqtfgbc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtvwzzzypu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtucoxxqqu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yanxiufei.cn/Article/details/gtyzddgtwm.html

Go:   // 双指针从两端比较
来源：http://dali.pengpengdd.cyou/Article/details/gtkzsxrtgm.html

Ruby: s == s.reverse
来源：http://dali.yuxming.cn/Article/details/gtgzjyohip.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gtxyhusidc.html

[N07] 两数之和（返回下标）
来源：http://dali.shuidangran.top/Article/details/gtsrtihvav.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.9152youxi.cn/Article/details/gtkwumvpzi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gotoacloud.top/Article/details/gtpmfkdyzx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.9152youxi.cn/Article/details/gtjflqpgan.html

TS:   // 手写 Map<string, number>
来源：http://dali.hongshengwenyu.top/Article/details/gtamjmdnhp.html

Java: // 手写 HashMap
来源：http://dali.chenzaomai.com/Article/details/gtswmkgfxj.html

Go:   // 手写 map[int]int
来源：http://dali.shangyingyoupin.top/Article/details/gtnntxdwtv.html

Ruby: // 手写 Hash
来源：http://dali.sufxvd.cn/Article/details/gtvinotehe.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbbcsofv.html

[N08] 生成全排列
来源：http://dali.dianchejie.cn/Article/details/gtcohfuudk.html

Py:   itertools.permutations(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtzscqohen.html

PHP:  // 手写递归交换
来源：http://dali.cdnleiting.top/Article/details/gtdenyfzxy.html

JS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtcosokpcb.html

TS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtbrwgtkai.html

Java: // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gthgxbhzba.html

Go:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtazyvnpvw.html

Ruby: arr.permutation.to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitkumjej.html

C#:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtxbuoiafu.html

[N09] 栈与队列
来源：http://dali.daxiang520.top/Article/details/gtapztjeas.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.c1oappe.top/Article/details/gtpehxrbnt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gtxtarkdbh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzzgoyfz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guannengcc.top/Article/details/gtffsyshnw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gaohongyu789.top/Article/details/gtlkuoywvz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xziqi.cn/Article/details/gtkbfxvpsu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtvhbhdxgb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jiagoushi.top/Article/details/gtrageqhsz.html

[N10] 链表节点定义
来源：http://dali.hnqzz.top/Article/details/gtbvtkawxw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.feifeiyinyue.top/Article/details/gtgadsbyve.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yvedp.cn/Article/details/gtgfqiczbu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.mhx1999.top/Article/details/gtnjymlshx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.redwolf501.top/Article/details/gtnfpjalny.html

Java: class Node { int v; Node next; }
来源：http://dali.gaohongyu789.top/Article/details/gtdvgupkmv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aizwys.cn/Article/details/gtfqrihvbm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jyoumei.cn/Article/details/gtsephdvhj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258.top/Article/details/gtpqwoxwfj.html

[N11] 二叉树中序遍历
来源：http://dali.zhoulong.xyz/Article/details/gtglilzmpn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guannengcc.top/Article/details/gtlfnnzgwz.html

PHP:  // 手写递归函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuutuczlv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gtamugcnbx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhfwoziz.html

Java: // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtfcerjqdu.html

Go:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtbiekgevj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guowangkeji.top/Article/details/gtkofrobkb.html

C#:   // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlouyahg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daxiang520.top/Article/details/gtoovuaigt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.haohaochexian.top/Article/details/gtymyqgfwd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhixingplan.top/Article/details/gthsuvsqmj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gtszzsgren.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gtzhtyfzci.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gtzyjvkeuv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigfzy.top/Article/details/gtrpwvfqwg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fengsongda.top/Article/details/gtfcxpxjdd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.redwolf501.top/Article/details/gtndrznmdg.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtffcjdhao.html

O. 并发与异步
来源：http://dali.9152youxi.cn/Article/details/gtlzptmwqh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtjcycyiqc.html

[O01] 启动一个线程
来源：http://dali.hysaishi.cn/Article/details/gteuxnxsvi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yonumen.top/Article/details/gtjrmanetu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xylfe.cn/Article/details/gttfqnkvga.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.smart0.xyz/Article/details/gtgefymewb.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtigpfqyhc.html

Java: new Thread(() -> f()).start()
来源：http://dali.daria6918.cn/Article/details/gtwkthqdny.html

Go:   go f()
来源：http://dali.zhiwuduotai.top/Article/details/gtrabmxfow.html

Ruby: Thread.new { f }
来源：http://dali.hfpthk.cn/Article/details/gtkeilyuts.html

C#:   Task.Run(() => F());
来源：http://dali.yonumen.top/Article/details/gthichkfjt.html

[O02] 使用线程池
来源：http://dali.bjfxy.top/Article/details/gthltzxaev.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hysaishi.cn/Article/details/gtambfigzt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daxiang520.top/Article/details/gtsmjlyfnt.html

JS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gtkkzjhxxi.html

TS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gtlswsluoo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yvedp.cn/Article/details/gtlcwoumxx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sweek.top/Article/details/gtjfaqkpok.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shzxlz.cn/Article/details/gttxzkkyli.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj202588.top/Article/details/gtdajhlbjw.html

[O03] 加锁保护共享数据
来源：http://dali.chenjidiqi.icu/Article/details/gtjwgmjbcf.html

Py:   with lock: shared += 1
来源：http://dali.0kj1m.cn/Article/details/gtycawpanv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.daria6918.cn/Article/details/gtlfdthwwv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.kuanghao11.cn/Article/details/gtumgyidda.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmqchzfx.html

Java: synchronized (this) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcsgmbbct.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yanxiufei.cn/Article/details/gtfhsbqtqq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zycfv.cn/Article/details/gtluqbgrsw.html

C#:   lock (gate) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gtuiuqagip.html

[O04] 定义异步函数并等待
来源：http://dali.chenlongwang.top/Article/details/gtktwacbwe.html

Py:   async def f():⏎    await g()
来源：http://dali.meibo888.top/Article/details/gtxptmnaes.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gotoacloud.top/Article/details/gthykhlofn.html

JS:   async function f() { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtrcolqcsn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.wangdashe.top/Article/details/gtxlejilxq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nanxinkj.top/Article/details/gtpneafkhk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.9152youxi.cn/Article/details/gtoiwvtrnp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.quarkkingdee.top/Article/details/gtoaldamyt.html

C#:   async Task F() { await G(); }
来源：http://dali.sufxvd.cn/Article/details/gtjdnmkapw.html

[O05] 并发执行并等待全部完成
来源：http://dali.jlsjyb.cn/Article/details/gtouioayga.html

Py:   asyncio.gather(*tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtiurndtey.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aibaodan.cn/Article/details/gtkhywezox.html

JS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gtdsrlgkwg.html

TS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gtohzufwfd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xziqi.cn/Article/details/gtxnwbmejb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspgfxddc.html

Ruby: threads.map(&:join)
来源：http://dali.sxryk.cn/Article/details/gtyqbeztbh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zdqjudy.top/Article/details/gtrykzewgb.html

[O06] 使用进程池
来源：http://dali.haohaochexian.top/Article/details/gtsktprhbf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xziqi.cn/Article/details/gtdqstwbjp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgfzy.top/Article/details/gtvinxujvj.html

JS:   // child_process / cluster 模块
来源：http://dali.jinqigufen.top/Article/details/gtrhondqqz.html

TS:   // child_process / cluster 模块
来源：http://dali.yj202588.top/Article/details/gtneyqaozk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenlongwang.top/Article/details/gtxdpzksdl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.vqdsnc.cn/Article/details/gtmcqcjayj.html

Ruby: // fork 块
来源：http://dali.jlsjyb.cn/Article/details/gtrxroohjf.html

C#:   Parallel.For
来源：http://dali.jiagoushi.top/Article/details/gtwtrtjnov.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtwaxnrwyt.html

P. 常用工具函数
来源：http://dali.nanxuanxn.top/Article/details/gtefxrztms.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzekspfj.html

[P01] 生成 UUID
来源：http://dali.gotoacloud.top/Article/details/gtcndgqyha.html

Py:   str(uuid.uuid4())
来源：http://dali.cashguo.top/Article/details/gtrpwgjapx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cqqwz.cn/Article/details/gtsboyeggr.html

JS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtwkrvldlr.html

TS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gtcmtskbcg.html

Java: UUID.randomUUID().toString()
来源：http://dali.yonumen.top/Article/details/gterwxhryk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gtztpmrona.html

Ruby: SecureRandom.uuid
来源：http://dali.yueranfly.top/Article/details/gtearzewjz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxinkj.top/Article/details/gtolsioogd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuxming.cn/Article/details/gtxogyimgv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.pycfn.com/Article/details/gtsgbsasel.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gttoioihst.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.vqdsnc.cn/Article/details/gtfqwittsn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yongpay.top/Article/details/gtzexbwqso.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenzaomai.com/Article/details/gtumwbrxds.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daxiang520.top/Article/details/gtnftiiqfr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.aizwys.cn/Article/details/gtdsoyvhmy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nwbrower.top/Article/details/gtsmrvglko.html

[P03] 生成短随机字符串
来源：http://dali.guowangkeji.top/Article/details/gthjhipmuu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fengsongda.top/Article/details/gtzhpeqodq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqpkcxcg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gtmgyzaqim.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gtyknajdxz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aizwys.cn/Article/details/gttoxaiypr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.kuanghao11.cn/Article/details/gtjikbgjap.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jlsjyb.cn/Article/details/gtmdezlbbd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hongshengwenyu.top/Article/details/gtsulcntxp.html

[P04] 求长度
来源：http://dali.jiagoushi.top/Article/details/gtfcvxetil.html


<!-- 参考信息 -->