代发 wailian999

Py:   resp.json()
来源：http://dali.ivvv.top/Article/details/gtjfhjjlvw.html

PHP:  json_decode($body, true);
来源：http://dali.sufxvd.cn/Article/details/gtyeaneywc.html

JS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyoenhogt.html

TS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gtuhhgizrv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtortoaqpw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tianlin.xyz/Article/details/gtbyeclcxd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yanxiufei.cn/Article/details/gtuphnegbl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cqqwz.cn/Article/details/gtnhxexbuj.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gthemgaiqv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yueranfly.top/Article/details/gtpoyqfddv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.316326.xyz/Article/details/gttyxnplka.html

JS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gtugzfegpm.html

TS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gttbvhvwlm.html

Java: resp.statusCode()
来源：http://dali.ppjwa.cn/Article/details/gtdhgcdfkf.html

Go:   resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gteaztgkaa.html

Ruby: resp.code.to_i
来源：http://dali.nanxuanxn.top/Article/details/gtugjdmmxp.html

C#:   (int)resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gtlottlsnx.html

[L08] 并发请求多个地址
来源：http://dali.cheryme.top/Article/details/gtbhdoqgli.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gtwdnkrxls.html

PHP:  curl_multi_init() 系列
来源：http://dali.ehwqpu.com/Article/details/gtjkiwggfw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gtymddylat.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gtweehzmcw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgfzy.top/Article/details/gtervspllw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.kuanghao11.cn/Article/details/gtocfzfsjc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cqqwz.cn/Article/details/gttzinxvlz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtkmxzptlg.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtnxiwyhtd.html

M. 命令行 / 进程 / 环境
来源：http://dali.xylfe.cn/Article/details/gtudtftmdq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtbyquhrzb.html

[M01] 读取命令行参数
来源：http://dali.yj20258888.top/Article/details/gtgmbtevwz.html

Py:   sys.argv[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtdkzqfwtu.html

PHP:  $argv;  $argc;
来源：http://dali.xuanzx.com/Article/details/gtclfawxni.html

JS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtfmiqhcjl.html

TS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gtcjhuqhhz.html

Java: args 数组（main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gttktqfgcc.html

Go:   os.Args[1:]
来源：http://dali.guowangkeji.top/Article/details/gtbmqiuwfl.html

Ruby: ARGV
来源：http://dali.wangdashe.top/Article/details/gtolygdjkr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuojzwhxf.html

[M02] 读取环境变量
来源：http://dali.hywenlv.cn/Article/details/gthscrppjz.html

Py:   os.environ.get("HOME")
来源：http://dali.fzhhl.top/Article/details/gtowxtciyy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gtsvbhkmrh.html

JS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gtwtorjlju.html

TS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gtpsodabse.html

Java: System.getenv("HOME")
来源：http://dali.gzhubu.top/Article/details/gtkmtivrse.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtelevggkq.html

Ruby: ENV["HOME"]
来源：http://dali.andypj.xyz/Article/details/gtinokurfh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sysykeji.top/Article/details/gtcldetjoc.html

[M03] 执行外部命令
来源：http://dali.zhixingplan.top/Article/details/gtxzjdgmhv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yonumen.top/Article/details/gtwhptjhec.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fengsongda.top/Article/details/gtdepnvkzg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmficzsm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtouboyapt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.andypj.xyz/Article/details/gtibcwnfru.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.svipenyu.cn/Article/details/gtroswxzww.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gtxazihlvj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ybcxt.top/Article/details/gtbqexpfgh.html

[M04] 获取当前工作目录
来源：http://dali.ybcxt.top/Article/details/gtmfwudqqw.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlagneokp.html

PHP:  getcwd();
来源：http://dali.nanxuanxn.top/Article/details/gtfvsyzfqa.html

JS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnweoupp.html

TS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gtyroeoyjf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.feifeiyinyue.top/Article/details/gtzxaettgn.html

Go:   os.Getwd()
来源：http://dali.316326.xyz/Article/details/gticemlgrk.html

Ruby: Dir.pwd
来源：http://dali.zdqjudy.top/Article/details/gttxixbhhq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cdnleiting.top/Article/details/gtqzwkapki.html

[M05] 设置退出码
来源：http://dali.feifeiyinyue.top/Article/details/gtxuqinytr.html

Py:   sys.exit(1)
来源：http://dali.yonumen.top/Article/details/gtijhhwvqr.html

PHP:  exit(1);
来源：http://dali.shuidangran.top/Article/details/gtpzlsevyz.html

JS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtpinqwjst.html

TS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtbvorqeps.html

Java: System.exit(1)
来源：http://dali.cheryme.top/Article/details/gtzbaqhiqz.html

Go:   os.Exit(1)
来源：http://dali.xziqi.cn/Article/details/gtetykehqz.html

Ruby: exit 1
来源：http://dali.cqqwz.cn/Article/details/gtrbvscnxb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.redwolf501.top/Article/details/gthmtryzfp.html

[M06] 向标准错误输出
来源：http://dali.fzhhl.top/Article/details/gtdosrhsnw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gtmpvyuvja.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuetiantiany.cn/Article/details/gtxdggwezo.html

JS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gttjpnqfrt.html

TS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gtvsxmqqof.html

Java: System.err.println("err")
来源：http://dali.zhixingplan.top/Article/details/gtufullcaz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhixingplan.top/Article/details/gtucquorup.html

Ruby: warn "err"
来源：http://dali.shzxlz.cn/Article/details/gtamfwhxpp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zycfv.cn/Article/details/gtpklilghe.html

[M07] 判断是否为主入口
来源：http://dali.yanxiufei.cn/Article/details/gtqksuwlmz.html

Py:   if __name__ == "__main__":
来源：http://dali.fengsongda.top/Article/details/gtijwicnac.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtaulouuaq.html

JS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gtvqjnqupg.html

TS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlkdphkcb.html

Java: public static void main(String[] args)
来源：http://dali.cqqwz.cn/Article/details/gtdfntjgli.html

Go:   func main()
来源：http://dali.jiagoushi.top/Article/details/gtirtyzbeg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fzhhl.top/Article/details/gtaetealfi.html

C#:   static void Main(string[] args)
来源：http://dali.hnqzz.top/Article/details/gtgoytlzyl.html

[M08] 获取系统与运行时信息
来源：http://dali.jyoumei.cn/Article/details/gtalgxtlqa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hysaishi.cn/Article/details/gtysjsfixn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.svipenyu.cn/Article/details/gtcnhzuput.html

JS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gtfhjuxjzo.html

TS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gteogwbdem.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhiwuduotai.top/Article/details/gtgnjtsucs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gtamqwyvgy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daria6918.cn/Article/details/gtknwukupp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.birdmap.top/Article/details/gtqeifeiez.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtcytqjcko.html

N. 数据结构与算法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnhaylnd.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtpnfkehae.html

[N01] 二分查找（有序数组）
来源：http://dali.yanxiufei.cn/Article/details/gtxlvvohsq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtsqpngaby.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cucudq.cn/Article/details/gtvnwdinyq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gtzwjoabch.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtuejokahx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtdjqtnctg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtgslyvrmu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zycfv.cn/Article/details/gtpxatmnov.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtbwtlmawl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ybcxt.top/Article/details/gtpzxsdiwe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gthiwfeexi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnxiangtu.top/Article/details/gtxzcqivoo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmmfxkwe.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtwdfmpewz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yangfankeji.com/Article/details/gtcfgwqstv.html

Go:   slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gtpvuoqodb.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gtfmxvhzpu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhoulong.xyz/Article/details/gtwotpshvq.html

[N03] 快速排序（分治示例）
来源：http://dali.ehwqpu.com/Article/details/gtqambivep.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258.top/Article/details/gtnppqxrus.html

PHP:  // 递归实现，或用 usort
来源：http://dali.meibo888.top/Article/details/gtlendqgye.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gtgkmlxlvw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gtvnkazyur.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sxryk.cn/Article/details/gtuppiajbq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daxiang520.top/Article/details/gtfioybpaz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hongshengwenyu.top/Article/details/gtkzhtqqgo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cheryme.top/Article/details/gtmavpkaiy.html

[N04] 斐波那契数列
来源：http://dali.fzhhl.top/Article/details/gteprmsfut.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gtftbemszh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gttateribc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gtijldrsqv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtnzhgjcje.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtfousvbjr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cqqwz.cn/Article/details/gtrvpxycnk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hywenlv.cn/Article/details/gtljghgfrf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtystgxvhb.html

[N05] 最大公约数
来源：http://dali.yangfankeji.com/Article/details/gtrfnmtpku.html

Py:   math.gcd(a, b)
来源：http://dali.ppjwa.cn/Article/details/gttihrawrm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.316326.xyz/Article/details/gtakpvndqn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gtjbvwuggq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gtqlwpcedx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.316326.xyz/Article/details/gtbqfhbkcy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.vqdsnc.cn/Article/details/gtioshuzhh.html

Ruby: a.gcd(b)
来源：http://dali.cashguo.top/Article/details/gtpfmtpfxw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ppjwa.cn/Article/details/gtaodhlstr.html

[N06] 判断回文字符串
来源：http://dali.xuanzx.com/Article/details/gtiofcisep.html

Py:   s == s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gtuuhabobr.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvgespqk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gttpsnmgve.html

TS:   s === [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtvvkvwgvg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.mhx1999.top/Article/details/gtggkfydkg.html

Go:   // 双指针从两端比较
来源：http://dali.shangyingyoupin.top/Article/details/gtntgfknmx.html

Ruby: s == s.reverse
来源：http://dali.dashuyun.cn/Article/details/gtjcosjqun.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gtqidkkiid.html

[N07] 两数之和（返回下标）
来源：http://dali.ydzc1.top/Article/details/gtknijcygn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jlsjyb.cn/Article/details/gtasmqmdad.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tanke756.top/Article/details/gtpctgextx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cdnleiting.top/Article/details/gtxrkotfcd.html

TS:   // 手写 Map<string, number>
来源：http://dali.tanke756.top/Article/details/gtgnxezlxa.html

Java: // 手写 HashMap
来源：http://dali.jqgfzy.top/Article/details/gtfgvwmqzm.html

Go:   // 手写 map[int]int
来源：http://dali.birdmap.top/Article/details/gtgayqaiuv.html

Ruby: // 手写 Hash
来源：http://dali.xuanzx.com/Article/details/gtupvcdxie.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.smart0.xyz/Article/details/gtteyqlvdd.html

[N08] 生成全排列
来源：http://dali.andypj.xyz/Article/details/gthydeyxtu.html

Py:   itertools.permutations(arr)
来源：http://dali.sweek.top/Article/details/gtnbnuagvh.html

PHP:  // 手写递归交换
来源：http://dali.redwolf501.top/Article/details/gtugnhzskt.html

JS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtdrpjwfxg.html

TS:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtcnqhctuo.html

Java: // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtjyonejjw.html

Go:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtfgcnxegb.html

Ruby: arr.permutation.to_a
来源：http://dali.yangfankeji.com/Article/details/gtuhtdinsa.html

C#:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtuiklhxaz.html

[N09] 栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtlxhbcssd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cqqwz.cn/Article/details/gtobqydsxb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtgjvhtfhn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtmrcomjap.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jiagoushi.top/Article/details/gtbjmnlxpo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gtjfwtzbpz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fengsongda.top/Article/details/gtegwodpgm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtniobnltr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaurgehvd.html

[N10] 链表节点定义
来源：http://dali.bjfxy.top/Article/details/gtphbwybkz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenlongwang.top/Article/details/gtffsnqqws.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shuidangran.top/Article/details/gtfaycljyq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sxryk.cn/Article/details/gtmiccsztc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqegqnutk.html

Java: class Node { int v; Node next; }
来源：http://dali.yuxming.cn/Article/details/gttwklkvwh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tanke756.top/Article/details/gtuwebajif.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ehwqpu.com/Article/details/gteqekesok.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yongpay.top/Article/details/gthavldwpq.html

[N11] 二叉树中序遍历
来源：http://dali.jyoumei.cn/Article/details/gtyfoksyja.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hfpthk.cn/Article/details/gtsyoznzdn.html

PHP:  // 手写递归函数
来源：http://dali.yongpay.top/Article/details/gtrwotzwrk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gtnsoixiad.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gtpjbmsakf.html

Java: // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gtyqiksedn.html

Go:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gtwtyirmdx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yanxiufei.cn/Article/details/gtbqxqppbb.html

C#:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtshblaqgo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yangfankeji.com/Article/details/gtjsyconku.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zycfv.cn/Article/details/gtmegbjufh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xziqi.cn/Article/details/gtlooenwpn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gtudaghdsm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gthvlbkeax.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gtzabiieur.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shuidangran.top/Article/details/gtsgwdlmdt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhriebun.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gtpcwplujc.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtumkezceo.html

O. 并发与异步
来源：http://dali.zhixingplan.top/Article/details/gtrtyhfxnn.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtvmxynnmi.html

[O01] 启动一个线程
来源：http://dali.cqqwz.cn/Article/details/gtutimwaqg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlknoivs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sysykeji.top/Article/details/gthnfezskn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gotoacloud.top/Article/details/gtcnfttyjr.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gtxkjprbvl.html

Java: new Thread(() -> f()).start()
来源：http://dali.guannengcc.top/Article/details/gtcepkagwd.html

Go:   go f()
来源：http://dali.jqgufenzy.top/Article/details/gthznbsgqv.html

Ruby: Thread.new { f }
来源：http://dali.ydzc1.top/Article/details/gtncsruiyb.html

C#:   Task.Run(() => F());
来源：http://dali.haohaochexian.top/Article/details/gtzatqgdxc.html

[O02] 使用线程池
来源：http://dali.hongshengwenyu.top/Article/details/gtxlrpthnt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuanzx.com/Article/details/gtlhnvphgl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yueranfly.top/Article/details/gtyspgarwq.html

JS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gtmrjvfwgc.html

TS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gtcqcflxoo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecylchvf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shanyushiyangtech.top/Article/details/gtobdubfhx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.9152youxi.cn/Article/details/gtvfrnlzpk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jyoumei.cn/Article/details/gtimfvgiom.html

[O03] 加锁保护共享数据
来源：http://dali.gogol.net.cn/Article/details/gtvjnyhtvr.html

Py:   with lock: shared += 1
来源：http://dali.iojbl.cn/Article/details/gtuyjodytd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yvedp.cn/Article/details/gthauvxaow.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhiwuduotai.top/Article/details/gtaeowmiek.html

TS:   // 同 JS
来源：http://dali.dianchejie.cn/Article/details/gtutetadqs.html

Java: synchronized (this) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvievjahq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgfzy.top/Article/details/gtwsrutlyl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoykpepoq.html

C#:   lock (gate) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gtoekvacub.html

[O04] 定义异步函数并等待
来源：http://dali.ydzc1.top/Article/details/gtodrmldih.html

Py:   async def f():⏎    await g()
来源：http://dali.zhixingplan.top/Article/details/gtrlevvrhr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ppjwa.cn/Article/details/gtqclvwtfr.html

JS:   async function f() { await g(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtamumhpiu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtglqalqqd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ybcxt.top/Article/details/gthizlfphr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yangfankeji.com/Article/details/gtrzgyaesg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.quarkkingdee.top/Article/details/gtobppvesk.html

C#:   async Task F() { await G(); }
来源：http://dali.chenzaomai.com/Article/details/gtxjajnrgx.html

[O05] 并发执行并等待全部完成
来源：http://dali.9152youxi.cn/Article/details/gtxrmniqxv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.bjfxy.top/Article/details/gtmtvfqoyj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhoulong.xyz/Article/details/gtuyqogspt.html

JS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gtdygcdjnf.html

TS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gtjclmuvaj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fengsongda.top/Article/details/gtymfqnesk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guannengcc.top/Article/details/gtxslgkgwi.html

Ruby: threads.map(&:join)
来源：http://dali.jianghu66.top/Article/details/gtrxbvvtdm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zycfv.cn/Article/details/gtduiaiwty.html

[O06] 使用进程池
来源：http://dali.hnxiangtu.top/Article/details/gtzbksguti.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenzaomai.com/Article/details/gtzpabmnkg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.aizwys.cn/Article/details/gtvysnlmwy.html

JS:   // child_process / cluster 模块
来源：http://dali.yj20258.top/Article/details/gtihbxiayb.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gtihindzuy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jiagoushi.top/Article/details/gtgrkkbufi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenlongwang.top/Article/details/gtalokvwsa.html

Ruby: // fork 块
来源：http://dali.jinqigfzy.top/Article/details/gtygancold.html

C#:   Parallel.For
来源：http://dali.zhoulong.xyz/Article/details/gtxkklczio.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtarzgobaq.html

P. 常用工具函数
来源：http://dali.fzhhl.top/Article/details/gttlvtnjso.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtzqzxnlee.html

[P01] 生成 UUID
来源：http://dali.nanxuanxn.top/Article/details/gtvzhemlkz.html

Py:   str(uuid.uuid4())
来源：http://dali.gotoacloud.top/Article/details/gtbslaitvk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.snrcjt.cn/Article/details/gtgjeeojvy.html

JS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtoaihwthn.html

TS:   crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gtqswkdwqa.html

Java: UUID.randomUUID().toString()
来源：http://dali.fzhhl.top/Article/details/gtgxuknesd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tianlin.xyz/Article/details/gtbochzvgv.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258.top/Article/details/gtzogrcbeg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zycfv.cn/Article/details/gtpaqposjp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.kuanghao11.cn/Article/details/gtvvfktjev.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gotoacloud.top/Article/details/gtrbdeotwq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.quarkkingdee.top/Article/details/gtjwqmirkp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuxming.cn/Article/details/gtntimfjbt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sufxvd.cn/Article/details/gtwnpmjzey.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xylfe.cn/Article/details/gteozrdhdn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jiagoushi.top/Article/details/gttqjjqsdl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.smart0.xyz/Article/details/gtngtlrlhp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ppjwa.cn/Article/details/gtredktfwk.html

[P03] 生成短随机字符串
来源：http://dali.yuanzhike.top/Article/details/gtcomiaosk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangshuangyany.cn/Article/details/gtqoqfelgf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tanke756.top/Article/details/gthkmabjhn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gtmigeridu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvhehvrj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cucudq.cn/Article/details/gtbfcjjjnk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ybcxt.top/Article/details/gtmuxjqruk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.iojbl.cn/Article/details/gtumdecdlf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwhekiqe.html

[P04] 求长度
来源：http://dali.redwolf501.top/Article/details/gtgjohydum.html


<!-- 参考信息 -->