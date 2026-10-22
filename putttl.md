代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fengsongda.top/Article/details/gthjlhygcg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.vqdsnc.cn/Article/details/gtzsmqphay.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xziqi.cn/Article/details/gthgjdolea.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ppjwa.cn/Article/details/gtjmnwrfqb.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gtikxjojds.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xziqi.cn/Article/details/gthyuswwtx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xziqi.cn/Article/details/gtmmseddmo.html

JS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gtihubttcv.html

TS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtmvfdbgvc.html

Java: resp.statusCode()
来源：http://dali.yangfankeji.com/Article/details/gtsjyqfrxq.html

Go:   resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gtjdkxiuop.html

Ruby: resp.code.to_i
来源：http://dali.xuetiantiany.cn/Article/details/gtmjccvgig.html

C#:   (int)resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gtaidrcsaf.html

[L08] 并发请求多个地址
来源：http://dali.ivvv.top/Article/details/gtulcqpute.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shangyingyoupin.top/Article/details/gtdoheaxpr.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigufen.top/Article/details/gtgefcdtof.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gtauoyrpgy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtehkidert.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgufenzy.top/Article/details/gtwlnpyctc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxuanxn.top/Article/details/gtyxqhdnaf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aizwys.cn/Article/details/gtchrrtpdv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guannengcc.top/Article/details/gtuoatzuiq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gttgvayxvb.html

M. 命令行 / 进程 / 环境
来源：http://dali.cucudq.cn/Article/details/gtnbhdztgr.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtawomckxw.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtswsegimg.html

Py:   sys.argv[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgsztzyp.html

PHP:  $argv;  $argc;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznfypqnx.html

JS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gthdisytav.html

TS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gtfcpwqnar.html

Java: args 数组（main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gtpzjlbxof.html

Go:   os.Args[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtyeotfmti.html

Ruby: ARGV
来源：http://dali.andypj.xyz/Article/details/gtujccwubp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gtzrnyimsy.html

[M02] 读取环境变量
来源：http://dali.yvedp.cn/Article/details/gtxvtmdzvi.html

Py:   os.environ.get("HOME")
来源：http://dali.hywenlv.cn/Article/details/gthqzzbisp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gtfenzcjwt.html

JS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gttsiixyms.html

TS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gtqboqohhh.html

Java: System.getenv("HOME")
来源：http://dali.wangdashe.top/Article/details/gtqfanhzxl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangdashe.top/Article/details/gtygfjpbwg.html

Ruby: ENV["HOME"]
来源：http://dali.aibaodan.cn/Article/details/gtoswimtrj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtikbktlyv.html

[M03] 执行外部命令
来源：http://dali.jyoumei.cn/Article/details/gtbfaifgld.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ydzc1.top/Article/details/gtgagksgzh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.vqdsnc.cn/Article/details/gtdhsmlduh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqryvcjl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtjzuofbhv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfryappnf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.haohaochexian.top/Article/details/gtfavyutpn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.316326.xyz/Article/details/gthscrhesp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhengqikj.top/Article/details/gtkifradwm.html

[M04] 获取当前工作目录
来源：http://dali.svipenyu.cn/Article/details/gtqbvirjve.html

Py:   os.getcwd()
来源：http://dali.316326.xyz/Article/details/gtdvhjmiij.html

PHP:  getcwd();
来源：http://dali.xinyue.icu/Article/details/gtybenmqxx.html

JS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gtbvwcmnag.html

TS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gttbmgvbob.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pycfn.com/Article/details/gtijalkvle.html

Go:   os.Getwd()
来源：http://dali.jianghu66.top/Article/details/gtrkkcfioc.html

Ruby: Dir.pwd
来源：http://dali.cheryme.top/Article/details/gtjulswauv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsiojmnht.html

[M05] 设置退出码
来源：http://dali.andypj.xyz/Article/details/gtnqtyynbz.html

Py:   sys.exit(1)
来源：http://dali.cashguo.top/Article/details/gtgfbhzelr.html

PHP:  exit(1);
来源：http://dali.ydzc1.top/Article/details/gtiilwynyb.html

JS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gttyoccaos.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqdmafyi.html

Java: System.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtdhdlsncl.html

Go:   os.Exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtdbgtdtou.html

Ruby: exit 1
来源：http://dali.sysykeji.top/Article/details/gtuqaxktbz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tian-w.cn/Article/details/gtiujrkwvx.html

[M06] 向标准错误输出
来源：http://dali.zhixingplan.top/Article/details/gtfumfqjrr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gtpmkgmtvb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sweek.top/Article/details/gtnyhknajd.html

JS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvaeuqfvp.html

TS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gtxbevnlmf.html

Java: System.err.println("err")
来源：http://dali.zhoulong.xyz/Article/details/gtxobdhsrv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fengsongda.top/Article/details/gtvyreiwwt.html

Ruby: warn "err"
来源：http://dali.yj202588.top/Article/details/gtacbcopja.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigfzy.top/Article/details/gtcrikrhrf.html

[M07] 判断是否为主入口
来源：http://dali.hfpthk.cn/Article/details/gtkttuvkfu.html

Py:   if __name__ == "__main__":
来源：http://dali.hnxiangtu.top/Article/details/gtslztsjvu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yangfankeji.com/Article/details/gtxpfkifjp.html

JS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gtwfkyeghy.html

TS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtuciopysz.html

Java: public static void main(String[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gtcfyehknd.html

Go:   func main()
来源：http://dali.andypj.xyz/Article/details/gtqfxpsupz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hfpthk.cn/Article/details/gtvjhnhhhc.html

C#:   static void Main(string[] args)
来源：http://dali.gzhubu.top/Article/details/gtmuxjtkwq.html

[M08] 获取系统与运行时信息
来源：http://dali.guannengcc.top/Article/details/gtvxmkshnx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdiockxj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhixingplan.top/Article/details/gteoqvkcpg.html

JS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gtwugjjalw.html

TS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gtzjvtwvnr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fzhhl.top/Article/details/gtqfruawpl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenjidiqi.icu/Article/details/gtqvjcymcv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj202588.top/Article/details/gtlycuxqux.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jianghu66.top/Article/details/gtpdvekhdv.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtdwpnumct.html

N. 数据结构与算法
来源：http://dali.jinqigufen.top/Article/details/gtbgpeqizg.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtnmgfgpze.html

[N01] 二分查找（有序数组）
来源：http://dali.hnqzz.top/Article/details/gtwuqwhgjh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtyqsduzup.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xziqi.cn/Article/details/gtitxslwxr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gtovxdwwea.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gtadtyrnpi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gtjgrymglg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtppdeiaxn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jiagoushi.top/Article/details/gtjwvrmzyi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtmamlmtas.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shangyingyoupin.top/Article/details/gtfemrkxus.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtxvvvusva.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gzhubu.top/Article/details/gtpeaoxmgm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gtwfmscomw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gtejeuplsm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yonumen.top/Article/details/gthbzpskqm.html

Go:   slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gtwwktqugo.html

Ruby: arr.sort
来源：http://dali.daria6918.cn/Article/details/gtovwosiap.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxinkj.top/Article/details/gtvpudqirh.html

[N03] 快速排序（分治示例）
来源：http://dali.ppjwa.cn/Article/details/gtaugmmrbk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ydzc1.top/Article/details/gtmswvqffm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefsdjojx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gtkhwjwgbq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gtzgyzwfqs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hywenlv.cn/Article/details/gtsvxhhtgp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nwbrower.top/Article/details/gthrcofgqa.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhixingplan.top/Article/details/gttgsqmetn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yangfankeji.com/Article/details/gtcucwchut.html

[N04] 斐波那契数列
来源：http://dali.xuetiantiany.cn/Article/details/gtjvgnkrkr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gtiivoyxip.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cqqwz.cn/Article/details/gtowhojihy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gtueefotkf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtddupkyuc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gtwuijezzl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jyoumei.cn/Article/details/gtysfaksah.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gtsizjseng.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtgvrhhech.html

[N05] 最大公约数
来源：http://dali.pengpengdd.cyou/Article/details/gthaqzkvnl.html

Py:   math.gcd(a, b)
来源：http://dali.ivvv.top/Article/details/gttaambrje.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zycfv.cn/Article/details/gtxgsaeupz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gtghpgtyck.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gttrcbjuwt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.haohaochexian.top/Article/details/gtfeemlemm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zdqjudy.top/Article/details/gttxibgtsf.html

Ruby: a.gcd(b)
来源：http://dali.zhengqikj.top/Article/details/gtnakmfqqy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fzhhl.top/Article/details/gtitngkrdj.html

[N06] 判断回文字符串
来源：http://dali.cashguo.top/Article/details/gtbdgrnpzz.html

Py:   s == s[::-1]
来源：http://dali.yongpay.top/Article/details/gtpvnmtkbo.html

PHP:  $s === strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gtzpzgvlit.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtnenahyyl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtwacyaphp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jlsjyb.cn/Article/details/gtpfnhswap.html

Go:   // 双指针从两端比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizmepqgn.html

Ruby: s == s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtfqlrwple.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenlongwang.top/Article/details/gtxrsnnimf.html

[N07] 两数之和（返回下标）
来源：http://dali.mhx1999.top/Article/details/gtarxraghb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gtiaoufbix.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zdqjudy.top/Article/details/gtiaywdsft.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ybcxt.top/Article/details/gtdszdkvsl.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenlongwang.top/Article/details/gtxpqyicso.html

Java: // 手写 HashMap
来源：http://dali.jianghu66.top/Article/details/gtiarkytef.html

Go:   // 手写 map[int]int
来源：http://dali.zhengqikj.top/Article/details/gtyinstmuc.html

Ruby: // 手写 Hash
来源：http://dali.chenlongwang.top/Article/details/gtilvzrfmb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hfpthk.cn/Article/details/gtumpqojhe.html

[N08] 生成全排列
来源：http://dali.svipenyu.cn/Article/details/gtoqcucypx.html

Py:   itertools.permutations(arr)
来源：http://dali.yvedp.cn/Article/details/gtuglrhazr.html

PHP:  // 手写递归交换
来源：http://dali.aizwys.cn/Article/details/gtgfwkakjb.html

JS:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtxhocqtqs.html

TS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtpoqdtjfo.html

Java: // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtsbsnmudx.html

Go:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtvrfjpbun.html

Ruby: arr.permutation.to_a
来源：http://dali.tianlin.xyz/Article/details/gtfvpcdpvu.html

C#:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewamnlih.html

[N09] 栈与队列
来源：http://dali.pycfn.com/Article/details/gtuhztfgaa.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gzhubu.top/Article/details/gtoyemvugc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtbjqzmwsr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtjgruln.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.andypj.xyz/Article/details/gtonbrbqoa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.meibo888.top/Article/details/gtyndopkfw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ivvv.top/Article/details/gtfonhrtfi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.fzhhl.top/Article/details/gtbbgeglyq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cdnleiting.top/Article/details/gtwgvebdvy.html

[N10] 链表节点定义
来源：http://dali.mhx1999.top/Article/details/gtrcugtrzd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuanzx.com/Article/details/gtjlvkixxg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nwbrower.top/Article/details/gtklcmcqhb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zdqjudy.top/Article/details/gtqdzjiaip.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gtfrpouhao.html

Java: class Node { int v; Node next; }
来源：http://dali.ydzc1.top/Article/details/gtxajpmofu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sweek.top/Article/details/gtncfpytwo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tianlin.xyz/Article/details/gtdujirhof.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sxryk.cn/Article/details/gtzhpxriyh.html

[N11] 二叉树中序遍历
来源：http://dali.guannengcc.top/Article/details/gtehuygypx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daxiang520.top/Article/details/gtrpnswpcx.html

PHP:  // 手写递归函数
来源：http://dali.dashuyun.cn/Article/details/gtaaxgznda.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gteedckiea.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xylfe.cn/Article/details/gtzazmlese.html

Java: // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtqfoeheqs.html

Go:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtzmfgqhir.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.havefunace.top/Article/details/gtanhwbvjm.html

C#:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtiazycgyv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sysykeji.top/Article/details/gtlirlvwaq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.mhx1999.top/Article/details/gtnguzqqyh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.0kj1m.cn/Article/details/gteertrbct.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gtppldzlqr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gtfuiatdcp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gtpcqbirri.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.fengsongda.top/Article/details/gtlmzrgtay.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.quarkkingdee.top/Article/details/gttzondmyd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.316326.xyz/Article/details/gtlfrwrgoc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtswnqqfjb.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcrmcpag.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtfqdposuh.html

[O01] 启动一个线程
来源：http://dali.zhoulong.xyz/Article/details/gtzqcalxjg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.bjfxy.top/Article/details/gthqaicety.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tianlin.xyz/Article/details/gtyhpkrgep.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhoulong.xyz/Article/details/gtovrmcdri.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gtzenbxiks.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangdashe.top/Article/details/gtunluzemg.html

Go:   go f()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcetvfask.html

Ruby: Thread.new { f }
来源：http://dali.yonumen.top/Article/details/gtheotlvyr.html

C#:   Task.Run(() => F());
来源：http://dali.cashguo.top/Article/details/gtuiwdalza.html

[O02] 使用线程池
来源：http://dali.xziqi.cn/Article/details/gtcvvkzwbd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufifdghv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sweek.top/Article/details/gtmhamsubm.html

JS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gtvhkmrija.html

TS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gthjvbosea.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pengpengdd.cyou/Article/details/gtnmrxloer.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.dashuyun.cn/Article/details/gtkpwzwiqm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.redwolf501.top/Article/details/gtrfclktob.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ppjwa.cn/Article/details/gtkkhsuedr.html

[O03] 加锁保护共享数据
来源：http://dali.cashguo.top/Article/details/gtbhoqmmxj.html

Py:   with lock: shared += 1
来源：http://dali.yangfankeji.com/Article/details/gtbuswdshu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.9152youxi.cn/Article/details/gtiowsoyvn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.9152youxi.cn/Article/details/gtqdiibzso.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gthmmtuhdk.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxiwxnvrx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ybcxt.top/Article/details/gtaycceoao.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgnqudjv.html

C#:   lock (gate) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gtczephecg.html

[O04] 定义异步函数并等待
来源：http://dali.yanxiufei.cn/Article/details/gtrbuprnft.html

Py:   async def f():⏎    await g()
来源：http://dali.yanxiufei.cn/Article/details/gtgjyhvfiu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cqqwz.cn/Article/details/gtxginsaox.html

JS:   async function f() { await g(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtykwauouz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hywenlv.cn/Article/details/gtwqmvtfeo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ydzc1.top/Article/details/gtxqsggbue.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangtech.top/Article/details/gtugvxdmhp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangshuangyany.cn/Article/details/gtnzhxpzyt.html

C#:   async Task F() { await G(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtkbgjcwac.html

[O05] 并发执行并等待全部完成
来源：http://dali.ppjwa.cn/Article/details/gtobdpkhyz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nwbrower.top/Article/details/gtnwbqaqdd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.guowangkeji.top/Article/details/gtmwyguvkf.html

JS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gtpkglyzwc.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gtxsqbtfqd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxuanxn.top/Article/details/gtxepexwiy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yonumen.top/Article/details/gtogtgtagi.html

Ruby: threads.map(&:join)
来源：http://dali.ivvv.top/Article/details/gthjdyimiq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.feifeiyinyue.top/Article/details/gtagznuice.html

[O06] 使用进程池
来源：http://dali.316326.xyz/Article/details/gtzosevonn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.quarkkingdee.top/Article/details/gtvrpzigmu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daxiang520.top/Article/details/gtzkeosclp.html

JS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gtehazlyos.html

TS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gtzascrkvw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gtrndiuhkm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yangfankeji.com/Article/details/gtjizncmhm.html

Ruby: // fork 块
来源：http://dali.daxiang520.top/Article/details/gtxojhfxem.html

C#:   Parallel.For
来源：http://dali.bjfxy.top/Article/details/gthaokipww.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvktshefw.html

P. 常用工具函数
来源：http://dali.bjfxy.top/Article/details/gtecyxsyks.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtupkidghl.html

[P01] 生成 UUID
来源：http://dali.dianchejie.cn/Article/details/gtlbqfiiuw.html

Py:   str(uuid.uuid4())
来源：http://dali.hongshengwenyu.top/Article/details/gtzbnxmhmj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sufxvd.cn/Article/details/gtesamghoo.html

JS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gttoonlofp.html

TS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gtwqxcrdgc.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigfzy.top/Article/details/gtxwuewwgk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigfzy.top/Article/details/gtgqygaqzh.html

Ruby: SecureRandom.uuid
来源：http://dali.hfpthk.cn/Article/details/gthvskayib.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.quarkkingdee.top/Article/details/gtivtdxnbh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shzxlz.cn/Article/details/gtdziwkbah.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tian-w.cn/Article/details/gtvczbfeuz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinqigfzy.top/Article/details/gtagygddan.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangdashe.top/Article/details/gtgmfndyvd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigfzy.top/Article/details/gtwjxapmuz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258.top/Article/details/gtfqgtbnos.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cheryme.top/Article/details/gtiwqawpyb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtepxlnhfo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.redwolf501.top/Article/details/gtlsrjpzca.html

[P03] 生成短随机字符串
来源：http://dali.chenlongwang.top/Article/details/gtvyqgyqxd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guowangkeji.top/Article/details/gtvvfpuuvk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj20258.top/Article/details/gtdcrpvjem.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtojezcjwn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gtcimtvlfr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guowangkeji.top/Article/details/gtlvbxzmrj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sweek.top/Article/details/gtjchzaflx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.guowangkeji.top/Article/details/gtjqismxep.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hongshengwenyu.top/Article/details/gteauhimwz.html

[P04] 求长度
来源：http://dali.zhengqikj.top/Article/details/gtlnzyojmd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.mhx1999.top/Article/details/gtxiipzugs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtfsvkdgnm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.svipenyu.cn/Article/details/gtdqwegazm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gtfxwrkpjn.html


<!-- 参考信息 -->