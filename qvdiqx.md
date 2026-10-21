代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.iojbl.cn/Article/details/gtqzsaqsnm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ivvv.top/Article/details/gtghaiygij.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuanzhike.top/Article/details/gtizmnwrlx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.snrcjt.cn/Article/details/gthnskrlpj.html

[L07] 处理 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gtizecwwtx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daxiang520.top/Article/details/gtqkddxich.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.snrcjt.cn/Article/details/gthdmmmctd.html

JS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gttttvfudq.html

TS:   resp.ok;  resp.status
来源：http://dali.gzhubu.top/Article/details/gtphxquisu.html

Java: resp.statusCode()
来源：http://dali.redwolf501.top/Article/details/gtbiheenlw.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gtorotgauu.html

Ruby: resp.code.to_i
来源：http://dali.cashguo.top/Article/details/gtevhcrisx.html

C#:   (int)resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gtulrzzyqy.html

[L08] 并发请求多个地址
来源：http://dali.jiagoushi.top/Article/details/gtfwndnduj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daxiang520.top/Article/details/gtlxewjqsx.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangdashe.top/Article/details/gtdxomosyo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtjmazalnp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtcmfrspck.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sxryk.cn/Article/details/gtyklfkeyn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ehwqpu.com/Article/details/gtnxeqospc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gtljpupjds.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxinkj.top/Article/details/gtmptkqpau.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtbhwweoir.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmorpvap.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtagmnjyje.html

[M01] 读取命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtcqmscjcd.html

Py:   sys.argv[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtozlkdjep.html

PHP:  $argv;  $argc;
来源：http://dali.jianghu66.top/Article/details/gtasthevsd.html

JS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gtqcwuljbo.html

TS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gtrtebjukm.html

Java: args 数组（main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gtazotviyb.html

Go:   os.Args[1:]
来源：http://dali.birdmap.top/Article/details/gtqfichdqr.html

Ruby: ARGV
来源：http://dali.ppjwa.cn/Article/details/gtsybayivz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gtifmygimg.html

[M02] 读取环境变量
来源：http://dali.yj20258.top/Article/details/gtugifkdmf.html

Py:   os.environ.get("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtrdwwrxag.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gtjemtljxo.html

JS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gtohujebiv.html

TS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gttklnxlup.html

Java: System.getenv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtrxztakzz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.redwolf501.top/Article/details/gtmkbcjsri.html

Ruby: ENV["HOME"]
来源：http://dali.gotoacloud.top/Article/details/gtjcviiigw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yongpay.top/Article/details/gthaelhobj.html

[M03] 执行外部命令
来源：http://dali.tian-w.cn/Article/details/gtisfxojtc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigfzy.top/Article/details/gtqmhrlvxg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.316326.xyz/Article/details/gtigvikkps.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gtlnqadcsf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gtjcyjrbwh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gogol.net.cn/Article/details/gtlklrkofm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuanzx.com/Article/details/gtsmgnsrhz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tanke756.top/Article/details/gtjzmjmpgp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shzxlz.cn/Article/details/gtgtblnfon.html

[M04] 获取当前工作目录
来源：http://dali.gotoacloud.top/Article/details/gtlxrzwpme.html

Py:   os.getcwd()
来源：http://dali.nwbrower.top/Article/details/gtztzlgjvx.html

PHP:  getcwd();
来源：http://dali.gogol.net.cn/Article/details/gtycqhlyzy.html

JS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gttzxcpjpi.html

TS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfvoknwo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinghuilouyu.cn/Article/details/gtamnerbfe.html

Go:   os.Getwd()
来源：http://dali.vqdsnc.cn/Article/details/gtuootobic.html

Ruby: Dir.pwd
来源：http://dali.guowangkeji.top/Article/details/gtmzctvgli.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hammf.cn/Article/details/gtkzbxeyci.html

[M05] 设置退出码
来源：http://dali.hfpthk.cn/Article/details/gtbfohzgjl.html

Py:   sys.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtvytbxeig.html

PHP:  exit(1);
来源：http://dali.fengsongda.top/Article/details/gtinzalici.html

JS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gthsdzkubv.html

TS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gthkendjwr.html

Java: System.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtxjlduyda.html

Go:   os.Exit(1)
来源：http://dali.pycfn.com/Article/details/gtgfhdezqq.html

Ruby: exit 1
来源：http://dali.zhoulong.xyz/Article/details/gtdkqjxhxr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gotoacloud.top/Article/details/gtelrygwba.html

[M06] 向标准错误输出
来源：http://dali.smart0.xyz/Article/details/gtgxqolgec.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gtyrrptgop.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.smart0.xyz/Article/details/gtqgtfrfuz.html

JS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gtrnoucmpz.html

TS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gtleiigsmf.html

Java: System.err.println("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtsowhfwhi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tian-w.cn/Article/details/gtnkylhfpi.html

Ruby: warn "err"
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwxbeztm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtsygzupyq.html

[M07] 判断是否为主入口
来源：http://dali.ehwqpu.com/Article/details/gtwvagjtpt.html

Py:   if __name__ == "__main__":
来源：http://dali.snrcjt.cn/Article/details/gtcqnlmxex.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gtmvvjrmvo.html

JS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gthgtsuice.html

TS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gtsualaszj.html

Java: public static void main(String[] args)
来源：http://dali.chenlongwang.top/Article/details/gtawvuluxt.html

Go:   func main()
来源：http://dali.zycfv.cn/Article/details/gtrvvtsxfw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guannengcc.top/Article/details/gtgdsirvpt.html

C#:   static void Main(string[] args)
来源：http://dali.aibaodan.cn/Article/details/gtwetqjjby.html

[M08] 获取系统与运行时信息
来源：http://dali.pycfn.com/Article/details/gtkwdcddzk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigfzy.top/Article/details/gtipeomici.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tanke756.top/Article/details/gtwcmdatya.html

JS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gtixnlxbmo.html

TS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gtooldxvwe.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fengsongda.top/Article/details/gtjndohqqm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daria6918.cn/Article/details/gtywncwbhi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zdqjudy.top/Article/details/gtdkrrhleh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daxiang520.top/Article/details/gthmkhyeow.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtclivmnbb.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gtzgluvzts.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtwngvxffa.html

[N01] 二分查找（有序数组）
来源：http://dali.meibo888.top/Article/details/gtwwthqntx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtyqrqfela.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zycfv.cn/Article/details/gtdllyqmir.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gtumegnlpm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtgjoiamno.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtjugtqenr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtjiahnzlh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj202588.top/Article/details/gtmgdkojjl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtwnjzeeqg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfluchtgf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gtwhtjmbia.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnxiangtu.top/Article/details/gtbwwtxhlm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gtxgjyylzg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gtrzfttbpz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pengpengdd.cyou/Article/details/gtpvceujef.html

Go:   slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtzknwzdkw.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gtigzleghp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sxryk.cn/Article/details/gturifazrc.html

[N03] 快速排序（分治示例）
来源：http://dali.xuetiantiany.cn/Article/details/gtagpieafi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.9152youxi.cn/Article/details/gthnuukjif.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sweek.top/Article/details/gtpppialvn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zdqjudy.top/Article/details/gtrqazydok.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllcxysop.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guannengcc.top/Article/details/gtbrwnjtfo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.0kj1m.cn/Article/details/gtlgybrung.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jianghu66.top/Article/details/gthcgrinqm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.pycfn.com/Article/details/gtwyhkltpa.html

[N04] 斐波那契数列
来源：http://dali.wangshuangyany.cn/Article/details/gtdinoaprc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gtlqfbyexc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtrjxhicnv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gtwkilwkbu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtmsnnyhjq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pycfn.com/Article/details/gtfoxtleme.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangshuangyany.cn/Article/details/gtdmiotinn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gtdwdtofqq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gtdmhazdsm.html

[N05] 最大公约数
来源：http://dali.c1oappe.top/Article/details/gtaqvgbhhe.html

Py:   math.gcd(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gtswumybdn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.smart0.xyz/Article/details/gtcmxspzgr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgufenzy.top/Article/details/gtxxbbwoyv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtberfmktj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuetiantiany.cn/Article/details/gtccnlsamn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj202588.top/Article/details/gtnutnhzbp.html

Ruby: a.gcd(b)
来源：http://dali.wangdashe.top/Article/details/gtwqzojdsx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cdnleiting.top/Article/details/gtatjiddsn.html

[N06] 判断回文字符串
来源：http://dali.smart0.xyz/Article/details/gtdezjccag.html

Py:   s == s[::-1]
来源：http://dali.yuxming.cn/Article/details/gtbbeccthh.html

PHP:  $s === strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gtempybumt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtrsyzsmvj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtiozqywop.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cucudq.cn/Article/details/gtelftmscl.html

Go:   // 双指针从两端比较
来源：http://dali.chenzaomai.com/Article/details/gtnsdybbqk.html

Ruby: s == s.reverse
来源：http://dali.316326.xyz/Article/details/gtgktvcdnj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gtdumkrkkg.html

[N07] 两数之和（返回下标）
来源：http://dali.gzhubu.top/Article/details/gthynnyglk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hywenlv.cn/Article/details/gtdksuvytv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.birdmap.top/Article/details/gtrbdhblus.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhiwuduotai.top/Article/details/gtdtzcltkp.html

TS:   // 手写 Map<string, number>
来源：http://dali.aibaodan.cn/Article/details/gthpdskqot.html

Java: // 手写 HashMap
来源：http://dali.ehwqpu.com/Article/details/gtsiknbult.html

Go:   // 手写 map[int]int
来源：http://dali.svipenyu.cn/Article/details/gtmwuhphlr.html

Ruby: // 手写 Hash
来源：http://dali.cashguo.top/Article/details/gtgvpbzhqo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhiwuduotai.top/Article/details/gtaedfdxbv.html

[N08] 生成全排列
来源：http://dali.jqgufenzy.top/Article/details/gtzlwodcfk.html

Py:   itertools.permutations(arr)
来源：http://dali.chenzaomai.com/Article/details/gttxopaily.html

PHP:  // 手写递归交换
来源：http://dali.jiagoushi.top/Article/details/gtvlhnbyoi.html

JS:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtdbrymidv.html

TS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtnykjdlry.html

Java: // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtjngetdlf.html

Go:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gteabajujo.html

Ruby: arr.permutation.to_a
来源：http://dali.zhoulong.xyz/Article/details/gtoyfnljsh.html

C#:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtsxyeyllb.html

[N09] 栈与队列
来源：http://dali.andypj.xyz/Article/details/gtxdlfismi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptctwiyu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtxmfboebm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xylfe.cn/Article/details/gtymcsondo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aizwys.cn/Article/details/gtyurmyycy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yueranfly.top/Article/details/gtgqaymfsb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zycfv.cn/Article/details/gtsasmpnom.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtalhyibpw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yangfankeji.com/Article/details/gtcxsmjarv.html

[N10] 链表节点定义
来源：http://dali.jianghu66.top/Article/details/gtjwotbmvi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.bjfxy.top/Article/details/gtcutwslym.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenzaomai.com/Article/details/gtkmjnpfnl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.havefunace.top/Article/details/gtzkxzlouc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hongshengwenyu.top/Article/details/gtesgmortc.html

Java: class Node { int v; Node next; }
来源：http://dali.316326.xyz/Article/details/gtvzclrmwl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yangfankeji.com/Article/details/gtgvflcadn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgufenzy.top/Article/details/gtoialxdyj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenzaomai.com/Article/details/gtsckggqcg.html

[N11] 二叉树中序遍历
来源：http://dali.smart0.xyz/Article/details/gtfsywpztd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pengpengdd.cyou/Article/details/gtojnkeoyk.html

PHP:  // 手写递归函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxsckgea.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gtjzqknzxa.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gthcpnkkgf.html

Java: // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlzuqcpo.html

Go:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtrkwqlrky.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zdqjudy.top/Article/details/gthwlwnpua.html

C#:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtuknkjspl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.iojbl.cn/Article/details/gtegrpzskm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xziqi.cn/Article/details/gtmojdohlt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnqzz.top/Article/details/gtsyajvkpc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sufxvd.cn/Article/details/gtjlojvcmn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gtrqlaowxq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gtrouoxwwo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ivvv.top/Article/details/gtmecepcix.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sxryk.cn/Article/details/gtmofowyym.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gtzcioshlp.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtwtfmeoaj.html

O. 并发与异步
来源：http://dali.havefunace.top/Article/details/gtoyhjkqde.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtnujaqyjb.html

[O01] 启动一个线程
来源：http://dali.jqgufenzy.top/Article/details/gtarsirdoh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sufxvd.cn/Article/details/gtwkeucvho.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenzaomai.com/Article/details/gtixayuvmp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuanzhike.top/Article/details/gthszapxke.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gtfnszatxm.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdxdlkuo.html

Go:   go f()
来源：http://dali.wangshuangyany.cn/Article/details/gtnhexczmb.html

Ruby: Thread.new { f }
来源：http://dali.aizwys.cn/Article/details/gttnbnxgvj.html

C#:   Task.Run(() => F());
来源：http://dali.bjfxy.top/Article/details/gtnvjwesnp.html

[O02] 使用线程池
来源：http://dali.ydzc1.top/Article/details/gttxcspqnd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jlsjyb.cn/Article/details/gtexhbrzho.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.redwolf501.top/Article/details/gtauuimsic.html

JS:   // worker_threads 线程池
来源：http://dali.pycfn.com/Article/details/gtdphvfgeg.html

TS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gtvyhicqdi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fzhhl.top/Article/details/gtjbcqsxzl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxinkj.top/Article/details/gtmpgjwajj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hfpthk.cn/Article/details/gtybeynfpc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258888.top/Article/details/gtfzseutyw.html

[O03] 加锁保护共享数据
来源：http://dali.guannengcc.top/Article/details/gthiqeuuar.html

Py:   with lock: shared += 1
来源：http://dali.zdqjudy.top/Article/details/gtyjkmflzm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.daria6918.cn/Article/details/gtxdgddndt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.vqdsnc.cn/Article/details/gtfycalgwp.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gtkfelnifx.html

Java: synchronized (this) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gtgvfhzlvh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zdqjudy.top/Article/details/gtxelikagv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplwqawwa.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gtbjblcuiw.html

[O04] 定义异步函数并等待
来源：http://dali.yonumen.top/Article/details/gtlwnafjkx.html

Py:   async def f():⏎    await g()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcoocpxry.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.aizwys.cn/Article/details/gtiuozoovd.html

JS:   async function f() { await g(); }
来源：http://dali.nwbrower.top/Article/details/gtrooyrxtn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzmfpdzr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhiwuduotai.top/Article/details/gtchfgcqfb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuanzx.com/Article/details/gtvmqdfthk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.haohaochexian.top/Article/details/gtsviqwovs.html

C#:   async Task F() { await G(); }
来源：http://dali.wangdashe.top/Article/details/gtbfxvoego.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhixingplan.top/Article/details/gtgjhjxdth.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dashuyun.cn/Article/details/gtorvdcpdl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xziqi.cn/Article/details/gtqsnjpwzo.html

JS:   await Promise.all(tasks)
来源：http://dali.xinyue.icu/Article/details/gtawqgbngu.html

TS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtqewvoczq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhiwuduotai.top/Article/details/gtdpqfrajh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbbcsxfxw.html

Ruby: threads.map(&:join)
来源：http://dali.zhengqikj.top/Article/details/gtarrtjjui.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.vqdsnc.cn/Article/details/gtmucsfxxz.html

[O06] 使用进程池
来源：http://dali.daria6918.cn/Article/details/gtluonurjg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xinyue.icu/Article/details/gtvjnsgnwn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xuanzx.com/Article/details/gteuecllad.html

JS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gtuiftuiqi.html

TS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gtuekiqnur.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.smart0.xyz/Article/details/gtuuhzzfvw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nwbrower.top/Article/details/gteeksqcnd.html

Ruby: // fork 块
来源：http://dali.redwolf501.top/Article/details/gtnooivyop.html

C#:   Parallel.For
来源：http://dali.gogol.net.cn/Article/details/gtupzzdebm.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtxevhpsep.html

P. 常用工具函数
来源：http://dali.zhoulong.xyz/Article/details/gtcnqobpus.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtcgailknc.html

[P01] 生成 UUID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtenhhmgmo.html

Py:   str(uuid.uuid4())
来源：http://dali.jinqigufen.top/Article/details/gtyyfpglmc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daria6918.cn/Article/details/gtzlopjlwq.html

JS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtnxgnjauh.html

TS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gtpshjllsx.html

Java: UUID.randomUUID().toString()
来源：http://dali.snrcjt.cn/Article/details/gtzrdjkxhd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dianchejie.cn/Article/details/gtetzsymvb.html

Ruby: SecureRandom.uuid
来源：http://dali.pengpengdd.cyou/Article/details/gtrsqzahda.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ybcxt.top/Article/details/gtpmungsuo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gotoacloud.top/Article/details/gtkzlrdnaa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.feifeiyinyue.top/Article/details/gtkuudkhdr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jlsjyb.cn/Article/details/gtonuejhou.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.iojbl.cn/Article/details/gtzhgwfevp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangshuangyany.cn/Article/details/gtprgsmmhh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtshzdgdxw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yangfankeji.com/Article/details/gtlhgorwkh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.svipenyu.cn/Article/details/gtafowkzuf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ydzc1.top/Article/details/gtkvzxcwte.html

[P03] 生成短随机字符串
来源：http://dali.pycfn.com/Article/details/gtyzbpkkys.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xylfe.cn/Article/details/gtvfksrjpy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.pengpengdd.cyou/Article/details/gtclkhafzl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtiwnnacgf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sxryk.cn/Article/details/gtvjcoyzou.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.bjfxy.top/Article/details/gtmnumfsco.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.birdmap.top/Article/details/gtdmmszpio.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gtthtnolss.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nanxuanxn.top/Article/details/gtwcqiljmh.html

[P04] 求长度
来源：http://dali.yanxiufei.cn/Article/details/gtwsnzeuxi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xuetiantiany.cn/Article/details/gtnyipbvqr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtudcolmrx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gtwvtsretl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gtdcribjup.html


<!-- 参考信息 -->