代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gtlnchgpcr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yangfankeji.com/Article/details/gtwowspkwx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ppjwa.cn/Article/details/gtsguirnqy.html

JS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gtrhckjxmt.html

TS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gtqhevnxkz.html

Java: resp.statusCode()
来源：http://dali.jianghu66.top/Article/details/gtjpaqfsdg.html

Go:   resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjflrbyvd.html

Ruby: resp.code.to_i
来源：http://dali.ivvv.top/Article/details/gtobfkfjvy.html

C#:   (int)resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gtjzswkurc.html

[L08] 并发请求多个地址
来源：http://dali.birdmap.top/Article/details/gtglltzmwo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xylfe.cn/Article/details/gtgwpgkfwo.html

PHP:  curl_multi_init() 系列
来源：http://dali.shangyingyoupin.top/Article/details/gtbamsdeub.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtampmgpsn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtljlbyawj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shuidangran.top/Article/details/gttqfokzvd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.snrcjt.cn/Article/details/gtphkcebjp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yonumen.top/Article/details/gtgeotnazt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtktqksgqu.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtkydlhffq.html

M. 命令行 / 进程 / 环境
来源：http://dali.svipenyu.cn/Article/details/gtatnnldsu.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtcyirurfm.html

[M01] 读取命令行参数
来源：http://dali.ydzc1.top/Article/details/gtlauuvqlj.html

Py:   sys.argv[1:]
来源：http://dali.guannengcc.top/Article/details/gtnvtqxrzn.html

PHP:  $argv;  $argc;
来源：http://dali.chenlongwang.top/Article/details/gtvhsxqlzb.html

JS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gtszjkdajf.html

TS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gtpfabakzp.html

Java: args 数组（main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjlconpp.html

Go:   os.Args[1:]
来源：http://dali.pycfn.com/Article/details/gttgpfuewk.html

Ruby: ARGV
来源：http://dali.feifeiyinyue.top/Article/details/gtxuxkmarf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gtpvayguax.html

[M02] 读取环境变量
来源：http://dali.yongpay.top/Article/details/gtdoyqhvyz.html

Py:   os.environ.get("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtwozzbpas.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gtdbnuomhp.html

JS:   process.env.HOME
来源：http://dali.nwbrower.top/Article/details/gtreiaufxd.html

TS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gtaeboskch.html

Java: System.getenv("HOME")
来源：http://dali.xziqi.cn/Article/details/gttunfligl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtvwggiene.html

Ruby: ENV["HOME"]
来源：http://dali.zhengqikj.top/Article/details/gtnwsbhlae.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yongpay.top/Article/details/gttdqbuvjk.html

[M03] 执行外部命令
来源：http://dali.c1oappe.top/Article/details/gtceetzyny.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtlzxjvgpu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.0kj1m.cn/Article/details/gtnnebivto.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtcfjplsqz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtoongxaoc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.smart0.xyz/Article/details/gtphmcjhhz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shangyingyoupin.top/Article/details/gtkoqnuefc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jyoumei.cn/Article/details/gtdkcmlwfc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.bjfxy.top/Article/details/gtdxsdnhnl.html

[M04] 获取当前工作目录
来源：http://dali.mhx1999.top/Article/details/gtxwzuskom.html

Py:   os.getcwd()
来源：http://dali.meibo888.top/Article/details/gtlmceqvxu.html

PHP:  getcwd();
来源：http://dali.aizwys.cn/Article/details/gtbuvghkqw.html

JS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gtqnlrjpoh.html

TS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gttdsdctuh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbrosbvfv.html

Go:   os.Getwd()
来源：http://dali.yuxming.cn/Article/details/gtsxeddhnq.html

Ruby: Dir.pwd
来源：http://dali.nanxinkj.top/Article/details/gtkiwzxivm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.vqdsnc.cn/Article/details/gtprkkzulh.html

[M05] 设置退出码
来源：http://dali.havefunace.top/Article/details/gtfuwgtsaa.html

Py:   sys.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtxuzucxmd.html

PHP:  exit(1);
来源：http://dali.cdnleiting.top/Article/details/gtvrolgeou.html

JS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtdhxdvdym.html

TS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gtfkxzxmjg.html

Java: System.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtuqpkjbkm.html

Go:   os.Exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtswxqjnmr.html

Ruby: exit 1
来源：http://dali.feifeiyinyue.top/Article/details/gtpogqdwct.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yongpay.top/Article/details/gtpylkegtp.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gttdwnbtyh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gtnbxqhisu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hongshengwenyu.top/Article/details/gtwntwdjxm.html

JS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtugbizmyw.html

TS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gtbemohmpp.html

Java: System.err.println("err")
来源：http://dali.haohaochexian.top/Article/details/gtretwgorx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gtapofiyha.html

Ruby: warn "err"
来源：http://dali.yj20258888.top/Article/details/gtegmfngpj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.redwolf501.top/Article/details/gtfqgclvxo.html

[M07] 判断是否为主入口
来源：http://dali.cashguo.top/Article/details/gtunakbwia.html

Py:   if __name__ == "__main__":
来源：http://dali.yueranfly.top/Article/details/gtbwefksfi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnszuvug.html

JS:   require.main === module
来源：http://dali.yvedp.cn/Article/details/gtvbydrlxz.html

TS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gtfvqfrmwp.html

Java: public static void main(String[] args)
来源：http://dali.jqgfzy.top/Article/details/gtsjwyfund.html

Go:   func main()
来源：http://dali.shuidangran.top/Article/details/gtmnfkhxhg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gotoacloud.top/Article/details/gttgvrwmpw.html

C#:   static void Main(string[] args)
来源：http://dali.daria6918.cn/Article/details/gtfcumoflv.html

[M08] 获取系统与运行时信息
来源：http://dali.bjfxy.top/Article/details/gtghawllkt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.smart0.xyz/Article/details/gtpgrmymlu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangtech.top/Article/details/gthkexvulv.html

JS:   process.platform;  process.version
来源：http://dali.zhengqikj.top/Article/details/gtwloettbj.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgyyyxpxo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cashguo.top/Article/details/gtgqwcgrqr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenjidiqi.icu/Article/details/gtyqjuzfno.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daxiang520.top/Article/details/gthfzskxmc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guannengcc.top/Article/details/gtinigwvgo.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtokohqqnb.html

N. 数据结构与算法
来源：http://dali.sweek.top/Article/details/gtioaijxvs.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtltzxltco.html

[N01] 二分查找（有序数组）
来源：http://dali.zhoulong.xyz/Article/details/gttqvahhgq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtjtybpixd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tian-w.cn/Article/details/gtfichhlvx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtnyhfwjar.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gthuxdesfn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtznbwewrs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtdjztyvra.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shuidangran.top/Article/details/gtscgawyna.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtqeoqeedq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xziqi.cn/Article/details/gttgwzkfho.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gtxzplgpxk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dianchejie.cn/Article/details/gtzdgnvtps.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gtmqihnekr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtrynqkzyv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cheryme.top/Article/details/gttwegixhr.html

Go:   slices.Sort(arr)
来源：http://dali.pycfn.com/Article/details/gtrezcghvj.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gtmprzakve.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tian-w.cn/Article/details/gtvjchttlt.html

[N03] 快速排序（分治示例）
来源：http://dali.fengsongda.top/Article/details/gtevgrufuz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.smart0.xyz/Article/details/gtukvkcfew.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yanxiufei.cn/Article/details/gtsmzzlzlr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gtwauzughh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gtjdroplds.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtpkggxt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.havefunace.top/Article/details/gtbihoavsq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.smart0.xyz/Article/details/gtsehvrdgb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cheryme.top/Article/details/gtjzajjmjq.html

[N04] 斐波那契数列
来源：http://dali.ppjwa.cn/Article/details/gtinitlvcd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tianlin.xyz/Article/details/gtijspsslk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnqzz.top/Article/details/gtekgmredn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtpkrqhidm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtwdaxvqrw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gtpbcadorl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gaohongyu789.top/Article/details/gtkxxhditn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdmijify.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtejnorsfp.html

[N05] 最大公约数
来源：http://dali.guowangkeji.top/Article/details/gtwgdvqigl.html

Py:   math.gcd(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtygwqxbij.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jyoumei.cn/Article/details/gthwifqocc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gtfppwueqy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtaydqxmyb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gogol.net.cn/Article/details/gtzfzzjjvm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenlongwang.top/Article/details/gtqdlzitgc.html

Ruby: a.gcd(b)
来源：http://dali.xinyue.icu/Article/details/gtprtonufc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cheryme.top/Article/details/gtguzwsiyd.html

[N06] 判断回文字符串
来源：http://dali.yonumen.top/Article/details/gtkbrnymbb.html

Py:   s == s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gtxvkgmnbm.html

PHP:  $s === strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gtazsvwxzn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtvhgrgjcg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtmhjyqnpg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.meibo888.top/Article/details/gtmjrnepae.html

Go:   // 双指针从两端比较
来源：http://dali.jianghu66.top/Article/details/gttlwmpfcs.html

Ruby: s == s.reverse
来源：http://dali.cucudq.cn/Article/details/gtzgjgipof.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gtplxdqgkf.html

[N07] 两数之和（返回下标）
来源：http://dali.birdmap.top/Article/details/gtgmcpiktg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigfzy.top/Article/details/gtcnmlebko.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhongyouzk.top/Article/details/gtdszhjjcb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.snrcjt.cn/Article/details/gtffbwuwax.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuetiantiany.cn/Article/details/gtkfnbfspn.html

Java: // 手写 HashMap
来源：http://dali.chenjidiqi.icu/Article/details/gtqdtxbsiy.html

Go:   // 手写 map[int]int
来源：http://dali.andypj.xyz/Article/details/gtmqvinkee.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gtzxlvxgjr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jiagoushi.top/Article/details/gtrcumzzmc.html

[N08] 生成全排列
来源：http://dali.hammf.cn/Article/details/gtbkkhcozj.html

Py:   itertools.permutations(arr)
来源：http://dali.redwolf501.top/Article/details/gtaquzatxq.html

PHP:  // 手写递归交换
来源：http://dali.havefunace.top/Article/details/gtfusbynxn.html

JS:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtwkojdlrm.html

TS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtdahfymah.html

Java: // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtxkbqymkz.html

Go:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtzootarwi.html

Ruby: arr.permutation.to_a
来源：http://dali.hywenlv.cn/Article/details/gtjpwsvxgr.html

C#:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtzaaifbxw.html

[N09] 栈与队列
来源：http://dali.sufxvd.cn/Article/details/gtzecfgpkd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nwbrower.top/Article/details/gtlkamxpfa.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gtugopdfrp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xylfe.cn/Article/details/gthjsupmne.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.redwolf501.top/Article/details/gttgizklqq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shzxlz.cn/Article/details/gtbreivvwy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagpcxran.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtqtayktao.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtsixuhdog.html

[N10] 链表节点定义
来源：http://dali.tanke756.top/Article/details/gtocreolgs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.feifeiyinyue.top/Article/details/gthijpzxni.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.smart0.xyz/Article/details/gtunijqnuh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtfcbmbeqg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigufen.top/Article/details/gtnrjdjdvs.html

Java: class Node { int v; Node next; }
来源：http://dali.316326.xyz/Article/details/gtzpksrqqt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.havefunace.top/Article/details/gtceheswga.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfhmrkuv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fengsongda.top/Article/details/gtvlkbgjyr.html

[N11] 二叉树中序遍历
来源：http://dali.jiagoushi.top/Article/details/gtgewhlyvq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aibaodan.cn/Article/details/gtlgdbycsz.html

PHP:  // 手写递归函数
来源：http://dali.meibo888.top/Article/details/gtgtoefult.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gtjpkkmlnu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xylfe.cn/Article/details/gtshtzuyvs.html

Java: // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtfpfjpccm.html

Go:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gtuxskkusr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cqqwz.cn/Article/details/gtcofoadqd.html

C#:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtpkodjupm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.dianchejie.cn/Article/details/gtbdvnivxr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cucudq.cn/Article/details/gthnoeitrc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jianghu66.top/Article/details/gtljduihyt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gtxxmpcgri.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gtmhypnclr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gttzzqhyli.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.kuanghao11.cn/Article/details/gtdmdvlrmj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dianchejie.cn/Article/details/gtfaxkrbvn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtxudffuvc.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtkokyjlsu.html

O. 并发与异步
来源：http://dali.svipenyu.cn/Article/details/gtbadwomgb.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gteoeoaszi.html

[O01] 启动一个线程
来源：http://dali.smart0.xyz/Article/details/gtrqueqovz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hysaishi.cn/Article/details/gttcmbpdrm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj202588.top/Article/details/gtoyavnbfl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tian-w.cn/Article/details/gtrylroold.html

TS:   // 同 JS
来源：http://dali.yonumen.top/Article/details/gttgdljhxc.html

Java: new Thread(() -> f()).start()
来源：http://dali.xziqi.cn/Article/details/gtmohashyh.html

Go:   go f()
来源：http://dali.feifeiyinyue.top/Article/details/gtargmyken.html

Ruby: Thread.new { f }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpihdaqlf.html

C#:   Task.Run(() => F());
来源：http://dali.hfpthk.cn/Article/details/gtcctdfijk.html

[O02] 使用线程池
来源：http://dali.ybcxt.top/Article/details/gtzsfipxaf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyixcqmv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhongyouzk.top/Article/details/gtuwxxkmap.html

JS:   // worker_threads 线程池
来源：http://dali.yvedp.cn/Article/details/gtwaameeaw.html

TS:   // worker_threads 线程池
来源：http://dali.cashguo.top/Article/details/gtknqmqpuv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.havefunace.top/Article/details/gtmyxbryit.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hfpthk.cn/Article/details/gtcfsnemdj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhongyouzk.top/Article/details/gtzkilwgty.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhoulong.xyz/Article/details/gtcxklkgih.html

[O03] 加锁保护共享数据
来源：http://dali.sysykeji.top/Article/details/gtpygseudw.html

Py:   with lock: shared += 1
来源：http://dali.jqgufenzy.top/Article/details/gtemmzefpz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sxryk.cn/Article/details/gttppyhhak.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabkchigi.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gtaanelkna.html

Java: synchronized (this) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gtvyrcbjte.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yangfankeji.com/Article/details/gtvlcnalbn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.redwolf501.top/Article/details/gtxfjzcvkh.html

C#:   lock (gate) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gtayskqedw.html

[O04] 定义异步函数并等待
来源：http://dali.ehwqpu.com/Article/details/gtmihzprks.html

Py:   async def f():⏎    await g()
来源：http://dali.yuxming.cn/Article/details/gtxdvddbmo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenzaomai.com/Article/details/gtuvypilew.html

JS:   async function f() { await g(); }
来源：http://dali.yuxming.cn/Article/details/gtkzwseoqx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jianghu66.top/Article/details/gtjsllokvl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.meibo888.top/Article/details/gtjyskmfhf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hongshengwenyu.top/Article/details/gtzycfnubp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cheryme.top/Article/details/gtrfhmhjkt.html

C#:   async Task F() { await G(); }
来源：http://dali.cucudq.cn/Article/details/gtpedfbilc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhongyouzk.top/Article/details/gtzybnouoy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhengqikj.top/Article/details/gtvljquabz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jiagoushi.top/Article/details/gtgujipgxp.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwzgbdso.html

TS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gtoctrfftz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.bjfxy.top/Article/details/gtpbhchydu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.snrcjt.cn/Article/details/gtgyknnpso.html

Ruby: threads.map(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gtzfzkqkhm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.daria6918.cn/Article/details/gtscltrzis.html

[O06] 使用进程池
来源：http://dali.zhiwuduotai.top/Article/details/gtlvwrrilp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.aizwys.cn/Article/details/gtaitxneyc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tianlin.xyz/Article/details/gtnhqtlnnf.html

JS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gtczdubagh.html

TS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gtzdcanshr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gtmwoaymlp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.316326.xyz/Article/details/gtevolbnha.html

Ruby: // fork 块
来源：http://dali.jinqigufen.top/Article/details/gtjseikprw.html

C#:   Parallel.For
来源：http://dali.guowangkeji.top/Article/details/gtkkyyevwt.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtrdyghllw.html

P. 常用工具函数
来源：http://dali.smart0.xyz/Article/details/gtfxdstlxj.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtddasekek.html

[P01] 生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gtmvjtuqea.html

Py:   str(uuid.uuid4())
来源：http://dali.aibaodan.cn/Article/details/gtluxoyopb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cucudq.cn/Article/details/gtkoxejnrp.html

JS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtmagvcntz.html

TS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gtrppjvrhd.html

Java: UUID.randomUUID().toString()
来源：http://dali.xziqi.cn/Article/details/gtiwgsotgh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shuidangran.top/Article/details/gtdlhkmxmz.html

Ruby: SecureRandom.uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfykyxur.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhixingplan.top/Article/details/gtoqaopvvt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.svipenyu.cn/Article/details/gtzyitxadr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sxryk.cn/Article/details/gtmsswkcuw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gzhubu.top/Article/details/gtfmzbdlrr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuanzx.com/Article/details/gtrrdqsbbm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xinyue.icu/Article/details/gtlhkwmatp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtblrjbgra.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ybcxt.top/Article/details/gtuzlyufub.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbbythhsj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpewbrfao.html

[P03] 生成短随机字符串
来源：http://dali.zhongyouzk.top/Article/details/gtujjhxynx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shzxlz.cn/Article/details/gtoaiabytp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ppjwa.cn/Article/details/gtfsauuvsy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jiagoushi.top/Article/details/gtujzswhia.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gtfnassjlq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shuidangran.top/Article/details/gtlcjzxmlm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.c1oappe.top/Article/details/gtudluxuiw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cucudq.cn/Article/details/gtjegexakm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nwbrower.top/Article/details/gtcidruzef.html

[P04] 求长度
来源：http://dali.iojbl.cn/Article/details/gtiqotgzhb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnqzz.top/Article/details/gtuccgeqfr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtlrzloinr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslksbttm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnoyaixli.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yongpay.top/Article/details/gtrtiblmzq.html

Go:   len(arr);  len(m)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnaylmvoa.html

Ruby: x.length;  x.size
来源：http://dali.aibaodan.cn/Article/details/gtkbjfwpsx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj202588.top/Article/details/gtvjecqsxk.html


<!-- 参考信息 -->