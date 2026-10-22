代发 wailian999

Py:   resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtpsvtcbhj.html

PHP:  json_decode($body, true);
来源：http://dali.kuanghao11.cn/Article/details/gtpoiyflnf.html

JS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gtkafqkysh.html

TS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtjrkokogf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtacbzrskf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daxiang520.top/Article/details/gtlxwabwzg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj202588.top/Article/details/gtsvjvxftf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258888.top/Article/details/gtwzieukel.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtsenlqpdk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.haohaochexian.top/Article/details/gtpoyubrrw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cheryme.top/Article/details/gtqyfnajck.html

JS:   resp.ok;  resp.status
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfwfaeam.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gtpvtbiwpq.html

Java: resp.statusCode()
来源：http://dali.9152youxi.cn/Article/details/gtjhboxwyx.html

Go:   resp.StatusCode
来源：http://dali.yuanzhike.top/Article/details/gtrxygscrw.html

Ruby: resp.code.to_i
来源：http://dali.iojbl.cn/Article/details/gtbrrnqwam.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskpmtrit.html

[L08] 并发请求多个地址
来源：http://dali.pengpengdd.cyou/Article/details/gtrxscyesj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xinyue.icu/Article/details/gtdedrfjxz.html

PHP:  curl_multi_init() 系列
来源：http://dali.jqgfzy.top/Article/details/gtbesdbbng.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtzknuddtb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gtizclwypx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxuanxn.top/Article/details/gtjztowrqy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pycfn.com/Article/details/gtblbghuet.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenzaomai.com/Article/details/gtnpozipcp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtaxdvijbd.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtxfbszrjw.html

M. 命令行 / 进程 / 环境
来源：http://dali.jyoumei.cn/Article/details/gtzkwslmdt.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtmmsgtjbg.html

[M01] 读取命令行参数
来源：http://dali.hywenlv.cn/Article/details/gthcmzwnph.html

Py:   sys.argv[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtzexrbcep.html

PHP:  $argv;  $argc;
来源：http://dali.dianchejie.cn/Article/details/gtcnkavqyh.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtomxtukqt.html

TS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gtgachkszd.html

Java: args 数组（main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gtopwcuejc.html

Go:   os.Args[1:]
来源：http://dali.smart0.xyz/Article/details/gtyrocuoqk.html

Ruby: ARGV
来源：http://dali.birdmap.top/Article/details/gtlyjngjif.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gtskwgnyrd.html

[M02] 读取环境变量
来源：http://dali.hywenlv.cn/Article/details/gtbhmzltll.html

Py:   os.environ.get("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtgggdlylg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cheryme.top/Article/details/gtfbwauurw.html

JS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtdknrsifo.html

TS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gthlgivlel.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvgvbtghs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gthxpxudel.html

Ruby: ENV["HOME"]
来源：http://dali.yanxiufei.cn/Article/details/gtnkhpcejk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ydzc1.top/Article/details/gtbxninzsn.html

[M03] 执行外部命令
来源：http://dali.gzhubu.top/Article/details/gtrmopcmeo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.snrcjt.cn/Article/details/gtmznvmkxf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xziqi.cn/Article/details/gtrcoyloxr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gtemwdgqfd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtzyylvlui.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnqzz.top/Article/details/gtgebbtfiq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gotoacloud.top/Article/details/gtnbrpnsgh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhongyouzk.top/Article/details/gtvdtwqzjy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.316326.xyz/Article/details/gtgtylkzeg.html

[M04] 获取当前工作目录
来源：http://dali.tianlin.xyz/Article/details/gtutpprtvl.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjorshhhb.html

PHP:  getcwd();
来源：http://dali.redwolf501.top/Article/details/gtintsbdgo.html

JS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqusdgjaz.html

TS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gtpvkdctfh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.316326.xyz/Article/details/gtgpxjzlwz.html

Go:   os.Getwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhjiipys.html

Ruby: Dir.pwd
来源：http://dali.shuidangran.top/Article/details/gtjlygnkmf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tanke756.top/Article/details/gtazwmbiuj.html

[M05] 设置退出码
来源：http://dali.tanke756.top/Article/details/gtmnvrtrgo.html

Py:   sys.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtvtpuyrdl.html

PHP:  exit(1);
来源：http://dali.zhongyouzk.top/Article/details/gtoicznbin.html

JS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gttovrkghi.html

TS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtofmarcyl.html

Java: System.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtoaetkgsp.html

Go:   os.Exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtdtbrqsmy.html

Ruby: exit 1
来源：http://dali.ydzc1.top/Article/details/gtbjnbqjhq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ivvv.top/Article/details/gtmgzcdcfn.html

[M06] 向标准错误输出
来源：http://dali.ivvv.top/Article/details/gtxoukfivj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gttmudckey.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shzxlz.cn/Article/details/gtdnyxtsug.html

JS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gtwyfspusi.html

TS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gtugsyydey.html

Java: System.err.println("err")
来源：http://dali.tianlin.xyz/Article/details/gtytfsmyqn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.redwolf501.top/Article/details/gtmqfklqms.html

Ruby: warn "err"
来源：http://dali.jqgfzy.top/Article/details/gtqgvtmcbp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gotoacloud.top/Article/details/gtqohkhdgv.html

[M07] 判断是否为主入口
来源：http://dali.yj20258888.top/Article/details/gtarvjascw.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gtczgvmlev.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhengqikj.top/Article/details/gtnnotymtq.html

JS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtwnkmiejn.html

TS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gtzrporyyx.html

Java: public static void main(String[] args)
来源：http://dali.sufxvd.cn/Article/details/gtkdgsdxhe.html

Go:   func main()
来源：http://dali.yueranfly.top/Article/details/gtbefqejfu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgfzy.top/Article/details/gttlrkfgkr.html

C#:   static void Main(string[] args)
来源：http://dali.cdnleiting.top/Article/details/gtemluimfb.html

[M08] 获取系统与运行时信息
来源：http://dali.xinyue.icu/Article/details/gtuiijizwa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhixingplan.top/Article/details/gtkgqocffv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tianlin.xyz/Article/details/gtbodmnawp.html

JS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gtozpgftuv.html

TS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gtgtpiqueb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ppjwa.cn/Article/details/gtpgnwayds.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gtypmwibjf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jyoumei.cn/Article/details/gtglwqrmfr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.iojbl.cn/Article/details/gtdbaueyes.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtcqajcmkc.html

N. 数据结构与算法
来源：http://dali.daria6918.cn/Article/details/gtagmdrege.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtuhqndnyy.html

[N01] 二分查找（有序数组）
来源：http://dali.sysykeji.top/Article/details/gtcmemhupn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gththjbigp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gthosrllfg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtylsavvxk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtuyfijtxo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtugqcwgyd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.meibo888.top/Article/details/gtpvpomvsk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ybcxt.top/Article/details/gtnqqhinaf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gthyvkwjso.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cdnleiting.top/Article/details/gtigrwhyzx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gtofsqdlth.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yvedp.cn/Article/details/gtdgpcjztx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gtjdljzsbk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gtsapnfdva.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tian-w.cn/Article/details/gtsuwgzpmu.html

Go:   slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtvxbtwesi.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gtirhuuugp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cheryme.top/Article/details/gtxbhakafp.html

[N03] 快速排序（分治示例）
来源：http://dali.svipenyu.cn/Article/details/gtfjtszlon.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gtadkuidre.html

PHP:  // 递归实现，或用 usort
来源：http://dali.316326.xyz/Article/details/gtgvmzbwej.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gtqgkslpxo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecfgpere.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.smart0.xyz/Article/details/gtpvkpqfjz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sysykeji.top/Article/details/gtfwvxjjjb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hnqzz.top/Article/details/gtlflxpzwm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.svipenyu.cn/Article/details/gtufnrbjbb.html

[N04] 斐波那契数列
来源：http://dali.snrcjt.cn/Article/details/gttpelzhtn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gtehixjuvx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.mhx1999.top/Article/details/gtkkskduqq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtztexoabb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtncyrqwci.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gtulphzhfp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgfzy.top/Article/details/gtfvqedote.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hywenlv.cn/Article/details/gtxlbghakq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtmotqivgu.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gtcclbpznq.html

Py:   math.gcd(a, b)
来源：http://dali.nwbrower.top/Article/details/gtjavhbxnj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtiadevgzm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gtxmaeecfz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtjrntqurh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nwbrower.top/Article/details/gtwqmjccdz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.quarkkingdee.top/Article/details/gtnzimxxfs.html

Ruby: a.gcd(b)
来源：http://dali.pengpengdd.cyou/Article/details/gttxdprryd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nanxuanxn.top/Article/details/gtigyooire.html

[N06] 判断回文字符串
来源：http://dali.yj202588.top/Article/details/gtjmxptpra.html

Py:   s == s[::-1]
来源：http://dali.shuidangran.top/Article/details/gtczgvfqcu.html

PHP:  $s === strrev($s);
来源：http://dali.yvedp.cn/Article/details/gtgqggipdk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtjftvklkf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtzucsdykw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxuanxn.top/Article/details/gtpukaeqxy.html

Go:   // 双指针从两端比较
来源：http://dali.zhiwuduotai.top/Article/details/gtuwlqbpsi.html

Ruby: s == s.reverse
来源：http://dali.cdnleiting.top/Article/details/gtsgxnbppi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gtennrxffj.html

[N07] 两数之和（返回下标）
来源：http://dali.xuanzx.com/Article/details/gtwukicqnb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sufxvd.cn/Article/details/gttvmwiisf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hammf.cn/Article/details/gtgqssbouw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gtvfpqmfzl.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxinkj.top/Article/details/gtymaiggyx.html

Java: // 手写 HashMap
来源：http://dali.tian-w.cn/Article/details/gthxthctzx.html

Go:   // 手写 map[int]int
来源：http://dali.bjfxy.top/Article/details/gtfuvkfcvi.html

Ruby: // 手写 Hash
来源：http://dali.guannengcc.top/Article/details/gtcbxvegrl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cheryme.top/Article/details/gtnonzdksh.html

[N08] 生成全排列
来源：http://dali.sufxvd.cn/Article/details/gtmvpgghpd.html

Py:   itertools.permutations(arr)
来源：http://dali.cucudq.cn/Article/details/gtuxiqurvr.html

PHP:  // 手写递归交换
来源：http://dali.xinyue.icu/Article/details/gtdfqeqbji.html

JS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtcpjcbkxs.html

TS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtsuatbewd.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfzcnluk.html

Go:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtdewveykp.html

Ruby: arr.permutation.to_a
来源：http://dali.sxryk.cn/Article/details/gtcsdjihnt.html

C#:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtfqbgthmx.html

[N09] 栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gtwjpuvqll.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sxryk.cn/Article/details/gtqcmqqllt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pycfn.com/Article/details/gtuzznoajw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtdtajeply.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.andypj.xyz/Article/details/gtqszhrwxt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yangfankeji.com/Article/details/gtobimlyww.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.0kj1m.cn/Article/details/gtsunfhini.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtsozkrqet.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shuidangran.top/Article/details/gtpqknrfxd.html

[N10] 链表节点定义
来源：http://dali.zhongyouzk.top/Article/details/gtkpzyqwcz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shangyingyoupin.top/Article/details/gtumjumfls.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgufenzy.top/Article/details/gtshgkmbir.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhixingplan.top/Article/details/gtupywiaud.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sufxvd.cn/Article/details/gtkjqxjzgn.html

Java: class Node { int v; Node next; }
来源：http://dali.ehwqpu.com/Article/details/gtpdhbfksq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jlsjyb.cn/Article/details/gttenotvvz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinqigfzy.top/Article/details/gtircotgjr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daria6918.cn/Article/details/gtxrolvzcg.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigufen.top/Article/details/gtqwswbftq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhoulong.xyz/Article/details/gtwusdlnqd.html

PHP:  // 手写递归函数
来源：http://dali.iojbl.cn/Article/details/gtzlmaggwd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gtaffdzgbs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gtoczciadt.html

Java: // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtlqbulzmi.html

Go:   // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gtjfnygsqn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gaohongyu789.top/Article/details/gtncfvgwrq.html

C#:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqaszeffl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sxryk.cn/Article/details/gtdvcyzxbb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hfpthk.cn/Article/details/gtrtvjxzzp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gtvdpwozog.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yvedp.cn/Article/details/gtypeuavha.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gtkmbngbao.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhengqikj.top/Article/details/gtznlhmvin.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenjidiqi.icu/Article/details/gtxrmznivl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.haohaochexian.top/Article/details/gtcpiasnot.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gttnaodits.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtkjrfwnqg.html

O. 并发与异步
来源：http://dali.gaohongyu789.top/Article/details/gtjyyqmswv.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtgjkmpfgh.html

[O01] 启动一个线程
来源：http://dali.cdnleiting.top/Article/details/gtrvwarnjw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtesetfmgj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xylfe.cn/Article/details/gtrfimywmb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shangyingyoupin.top/Article/details/gtooilqfte.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdvwioeb.html

Java: new Thread(() -> f()).start()
来源：http://dali.gotoacloud.top/Article/details/gthtvsjzwh.html

Go:   go f()
来源：http://dali.ivvv.top/Article/details/gtjwuibhqc.html

Ruby: Thread.new { f }
来源：http://dali.zhengqikj.top/Article/details/gtjpxlbwjd.html

C#:   Task.Run(() => F());
来源：http://dali.hongshengwenyu.top/Article/details/gtxgzeijms.html

[O02] 使用线程池
来源：http://dali.zycfv.cn/Article/details/gtyerqlimq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.chenjidiqi.icu/Article/details/gtyukhaknh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.svipenyu.cn/Article/details/gtotgilncu.html

JS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gtbkgecvgp.html

TS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gtrmeqstsu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xuanzx.com/Article/details/gtnobnzekq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cqqwz.cn/Article/details/gtekkegben.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hywenlv.cn/Article/details/gturpmhihl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnxiangtu.top/Article/details/gtsmrpgoxs.html

[O03] 加锁保护共享数据
来源：http://dali.bjfxy.top/Article/details/gtxoftabdu.html

Py:   with lock: shared += 1
来源：http://dali.cashguo.top/Article/details/gtfmsgfezn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenlongwang.top/Article/details/gtrathmxkc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zdqjudy.top/Article/details/gtclztgtug.html

TS:   // 同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtgviepwze.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrbzagdl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinqigufen.top/Article/details/gtgfgaunbf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yangfankeji.com/Article/details/gtqdrigujd.html

C#:   lock (gate) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gtmfaonskj.html

[O04] 定义异步函数并等待
来源：http://dali.xylfe.cn/Article/details/gtkdzukwag.html

Py:   async def f():⏎    await g()
来源：http://dali.hammf.cn/Article/details/gtpolmlida.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cqqwz.cn/Article/details/gtceanisdt.html

JS:   async function f() { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbsjtgsq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hammf.cn/Article/details/gtxcjpurod.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ppjwa.cn/Article/details/gtvjewuwou.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jlsjyb.cn/Article/details/gtwxtzhqzw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jlsjyb.cn/Article/details/gtoxhvlgje.html

C#:   async Task F() { await G(); }
来源：http://dali.cheryme.top/Article/details/gtnjundrvn.html

[O05] 并发执行并等待全部完成
来源：http://dali.pycfn.com/Article/details/gtfvfcausi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangdashe.top/Article/details/gtyqatmmow.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.feifeiyinyue.top/Article/details/gtqaxvrxwe.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigfzy.top/Article/details/gtwsyouzox.html

TS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gtjtwfsmas.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yongpay.top/Article/details/gtthjpoixe.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ydzc1.top/Article/details/gtcksiytfn.html

Ruby: threads.map(&:join)
来源：http://dali.shzxlz.cn/Article/details/gtntggxnzp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shangyingyoupin.top/Article/details/gtedtqefyl.html

[O06] 使用进程池
来源：http://dali.daria6918.cn/Article/details/gtxronncds.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.quarkkingdee.top/Article/details/gtskahzemg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jlsjyb.cn/Article/details/gtuxopjpks.html

JS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gtnxvbjemi.html

TS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gtqnxmydfd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jianghu66.top/Article/details/gtavrrrvls.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqgbmtlr.html

Ruby: // fork 块
来源：http://dali.yuxming.cn/Article/details/gtpbntggca.html

C#:   Parallel.For
来源：http://dali.dianchejie.cn/Article/details/gtldevflhi.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtamcnrsew.html

P. 常用工具函数
来源：http://dali.jqgufenzy.top/Article/details/gtwkbiryvp.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtndignioc.html

[P01] 生成 UUID
来源：http://dali.nanxinkj.top/Article/details/gtzqrsjysm.html

Py:   str(uuid.uuid4())
来源：http://dali.ybcxt.top/Article/details/gtmgeqsbuj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yuxming.cn/Article/details/gtvjbsfjec.html

JS:   crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gtegetrjnl.html

TS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gtayzflski.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnqzz.top/Article/details/gtkxxozzig.html

Go:   // 用 github.com/google/uuid
来源：http://dali.birdmap.top/Article/details/gtkpzylczb.html

Ruby: SecureRandom.uuid
来源：http://dali.gzhubu.top/Article/details/gtrwffiuzh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigufen.top/Article/details/gtwsvwlfom.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhongyouzk.top/Article/details/gtrxqsffqq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hfpthk.cn/Article/details/gtarljmxpi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmkdjtfa.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.meibo888.top/Article/details/gtnbrhglte.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.kuanghao11.cn/Article/details/gtybyuutom.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yueranfly.top/Article/details/gtmbryvukc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zycfv.cn/Article/details/gtvwwgtoke.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhixingplan.top/Article/details/gtjinbekfy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cashguo.top/Article/details/gtmohbwncz.html

[P03] 生成短随机字符串
来源：http://dali.andypj.xyz/Article/details/gtnkvkzzty.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.snrcjt.cn/Article/details/gtvnmvtjsw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgfzy.top/Article/details/gtpldjmxdv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dashuyun.cn/Article/details/gteeqwqnhd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfemrqvuz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhoulong.xyz/Article/details/gtodzdqwqf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.svipenyu.cn/Article/details/gtwwoacrzf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hfpthk.cn/Article/details/gtkczpaeme.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xylfe.cn/Article/details/gthhynvrom.html

[P04] 求长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxmslsoh.html


<!-- 参考信息 -->