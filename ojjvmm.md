代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtmbkktwqy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuanzhike.top/Article/details/gtakpghpqq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxuanxn.top/Article/details/gtyjfazkwo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gttkfeudtm.html

[L07] 处理 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gtsseencic.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yonumen.top/Article/details/gtgkeggoqu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nwbrower.top/Article/details/gtenddcmde.html

JS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gtmvctxoia.html

TS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gtkifwlxjf.html

Java: resp.statusCode()
来源：http://dali.dianchejie.cn/Article/details/gtvtlqnmea.html

Go:   resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtveehgket.html

Ruby: resp.code.to_i
来源：http://dali.ehwqpu.com/Article/details/gtlzbfezcp.html

C#:   (int)resp.StatusCode
来源：http://dali.yanxiufei.cn/Article/details/gtmizcyoxp.html

[L08] 并发请求多个地址
来源：http://dali.chenjidiqi.icu/Article/details/gtgrdjhfbs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hammf.cn/Article/details/gtunynpehk.html

PHP:  curl_multi_init() 系列
来源：http://dali.daria6918.cn/Article/details/gtsckghhbn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqpmvjwv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gtcjtvigsk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuanzhike.top/Article/details/gtdvzkegdz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqejciqjm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cashguo.top/Article/details/gtzihbwqsy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jianghu66.top/Article/details/gtjqqacyne.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtfravqmtn.html

M. 命令行 / 进程 / 环境
来源：http://dali.fzhhl.top/Article/details/gtjcgrlrzw.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtlxazdceh.html

[M01] 读取命令行参数
来源：http://dali.xuanzx.com/Article/details/gtltbmthph.html

Py:   sys.argv[1:]
来源：http://dali.nwbrower.top/Article/details/gtbehqemst.html

PHP:  $argv;  $argc;
来源：http://dali.smart0.xyz/Article/details/gtxwkpahju.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtngfqxhzq.html

TS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gtyvaptrzo.html

Java: args 数组（main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gtpoggvyec.html

Go:   os.Args[1:]
来源：http://dali.yonumen.top/Article/details/gtngusuhrf.html

Ruby: ARGV
来源：http://dali.chenjidiqi.icu/Article/details/gtlfydzpkf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtbpvdfvyg.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtvzukks.html

Py:   os.environ.get("HOME")
来源：http://dali.xylfe.cn/Article/details/gtegfghdnp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gtzoqjpwti.html

JS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gtjyxkiuks.html

TS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gtmacybqxr.html

Java: System.getenv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtkudgqzko.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nwbrower.top/Article/details/gthsmvbucz.html

Ruby: ENV["HOME"]
来源：http://dali.sweek.top/Article/details/gtquekomhk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ivvv.top/Article/details/gtujkyyjoq.html

[M03] 执行外部命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhskhhef.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daria6918.cn/Article/details/gtqxvpeisv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuanzx.com/Article/details/gtijjuidlu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gtsrprzsmr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gtzemmsoje.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hywenlv.cn/Article/details/gthjchwsvg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetzsimov.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yueranfly.top/Article/details/gtytvdaqii.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hongshengwenyu.top/Article/details/gtrjptjaux.html

[M04] 获取当前工作目录
来源：http://dali.hongshengwenyu.top/Article/details/gthlkflskd.html

Py:   os.getcwd()
来源：http://dali.ydzc1.top/Article/details/gtemloxxoy.html

PHP:  getcwd();
来源：http://dali.yangfankeji.com/Article/details/gtguxmqtlr.html

JS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtreccgyso.html

TS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gtttomlapf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhoulong.xyz/Article/details/gtbrghkxcc.html

Go:   os.Getwd()
来源：http://dali.9152youxi.cn/Article/details/gtmwbsplbi.html

Ruby: Dir.pwd
来源：http://dali.fengsongda.top/Article/details/gtlfwkocvs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenjidiqi.icu/Article/details/gtezsgqxju.html

[M05] 设置退出码
来源：http://dali.aizwys.cn/Article/details/gtgslqajol.html

Py:   sys.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtgxroewnk.html

PHP:  exit(1);
来源：http://dali.smart0.xyz/Article/details/gtfvxfnayf.html

JS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtlmritgsy.html

TS:   process.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtjrwbuzxa.html

Java: System.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtcldqnbat.html

Go:   os.Exit(1)
来源：http://dali.yongpay.top/Article/details/gtkpwtobom.html

Ruby: exit 1
来源：http://dali.hongshengwenyu.top/Article/details/gtgdfqezgy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shzxlz.cn/Article/details/gtvbstefse.html

[M06] 向标准错误输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfiyxuce.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daxiang520.top/Article/details/gtvdnsojau.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daxiang520.top/Article/details/gttmssbpsu.html

JS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gteecunzcd.html

TS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwompmxg.html

Java: System.err.println("err")
来源：http://dali.ydzc1.top/Article/details/gtoujlgost.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenlongwang.top/Article/details/gtmzdeoicd.html

Ruby: warn "err"
来源：http://dali.havefunace.top/Article/details/gtnffdltyg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cucudq.cn/Article/details/gtuygqikei.html

[M07] 判断是否为主入口
来源：http://dali.fengsongda.top/Article/details/gtuhtyapqa.html

Py:   if __name__ == "__main__":
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwnjqnbw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenzaomai.com/Article/details/gtrsjlttmy.html

JS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gtgmkiroka.html

TS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gttzftsymb.html

Java: public static void main(String[] args)
来源：http://dali.jyoumei.cn/Article/details/gtaablnonx.html

Go:   func main()
来源：http://dali.sweek.top/Article/details/gtbobuaicy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yueranfly.top/Article/details/gtawcyccfl.html

C#:   static void Main(string[] args)
来源：http://dali.quarkkingdee.top/Article/details/gtuzfcsdkl.html

[M08] 获取系统与运行时信息
来源：http://dali.xziqi.cn/Article/details/gtvbyxabcx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgufenzy.top/Article/details/gtcblsvhle.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfyjfmxjj.html

JS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gtqseuazff.html

TS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gtzkbfucag.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ybcxt.top/Article/details/gtplmvrfio.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tanke756.top/Article/details/gthslugotp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinghuilouyu.cn/Article/details/gtccqnslmn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yvedp.cn/Article/details/gtirtrnmod.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtprhynrmy.html

N. 数据结构与算法
来源：http://dali.andypj.xyz/Article/details/gtqugphjqi.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtgnkhrybl.html

[N01] 二分查找（有序数组）
来源：http://dali.tian-w.cn/Article/details/gtvsumckle.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtnbszzazq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtjmvwjbsr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gtzxhdfjdf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrinletdf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtrttrtvvp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yonumen.top/Article/details/gteinddcwm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gtictwkiyw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtxjwytism.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnqzz.top/Article/details/gtweylwtbx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtucocjbsx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gotoacloud.top/Article/details/gtrgzrhsbz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gtabwueqqq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gtkqmjnjpn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jiagoushi.top/Article/details/gtzoumnbrl.html

Go:   slices.Sort(arr)
来源：http://dali.wangdashe.top/Article/details/gtuhauphnp.html

Ruby: arr.sort
来源：http://dali.bjfxy.top/Article/details/gtuqmyoqnk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.haohaochexian.top/Article/details/gtuueharoc.html

[N03] 快速排序（分治示例）
来源：http://dali.redwolf501.top/Article/details/gtvstggfvv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jianghu66.top/Article/details/gtfbvzpjui.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenzaomai.com/Article/details/gtxkijrpse.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gtaraclgmi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gtnzmzkqoq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.vqdsnc.cn/Article/details/gtxflrmpqz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.iojbl.cn/Article/details/gtbbypvhkm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dianchejie.cn/Article/details/gttycogkqa.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangdashe.top/Article/details/gtmsnhpbel.html

[N04] 斐波那契数列
来源：http://dali.shangyingyoupin.top/Article/details/gtkeijpshf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtkjsxiacd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gtnwzygssv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtddgfrwex.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtkvypwvhy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gtnedgiguk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hongshengwenyu.top/Article/details/gtnjnsofbv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtwjdcyyny.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtvkzkimsq.html

[N05] 最大公约数
来源：http://dali.ehwqpu.com/Article/details/gtadsugxhj.html

Py:   math.gcd(a, b)
来源：http://dali.yuxming.cn/Article/details/gtxoftnibh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cashguo.top/Article/details/gtktnkqvjh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gtkfyvxmyf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtbcoocnax.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenjidiqi.icu/Article/details/gtyjtxpfjn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnxiangtu.top/Article/details/gtkoofdmnj.html

Ruby: a.gcd(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtbvryreyr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sysykeji.top/Article/details/gtdjcqdyky.html

[N06] 判断回文字符串
来源：http://dali.guowangkeji.top/Article/details/gtuhvqnnwb.html

Py:   s == s[::-1]
来源：http://dali.zycfv.cn/Article/details/gtaccbervn.html

PHP:  $s === strrev($s);
来源：http://dali.sweek.top/Article/details/gtmsjmjebl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtqnsawiuf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtdbhqdwmy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangshuangyany.cn/Article/details/gtfhpaoyye.html

Go:   // 双指针从两端比较
来源：http://dali.haohaochexian.top/Article/details/gtvoxxbxeb.html

Ruby: s == s.reverse
来源：http://dali.yueranfly.top/Article/details/gtwffeojqw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zycfv.cn/Article/details/gtpabbuban.html

[N07] 两数之和（返回下标）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrcnwnye.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinyuanbaomall.cn/Article/details/gtequckeag.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvtwfnme.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ivvv.top/Article/details/gttkmfzhbn.html

TS:   // 手写 Map<string, number>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtryoccbwx.html

Java: // 手写 HashMap
来源：http://dali.ehwqpu.com/Article/details/gtipwirvhe.html

Go:   // 手写 map[int]int
来源：http://dali.svipenyu.cn/Article/details/gtnwopmjyp.html

Ruby: // 手写 Hash
来源：http://dali.zycfv.cn/Article/details/gtwaamtncp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hywenlv.cn/Article/details/gttgstsbmb.html

[N08] 生成全排列
来源：http://dali.aizwys.cn/Article/details/gttdqyaciq.html

Py:   itertools.permutations(arr)
来源：http://dali.sxryk.cn/Article/details/gtvblcxysv.html

PHP:  // 手写递归交换
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgoksaib.html

JS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtdhjzmzbz.html

TS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtftgohfxz.html

Java: // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtntjpdiyv.html

Go:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtezhkvdip.html

Ruby: arr.permutation.to_a
来源：http://dali.yuanzhike.top/Article/details/gtlekmttwo.html

C#:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtqlxrwpfu.html

[N09] 栈与队列
来源：http://dali.ppjwa.cn/Article/details/gtmmdqxfzo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtbmnieira.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtyxqigvpg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtopzamlmi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxinkj.top/Article/details/gtmclfgkhd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sysykeji.top/Article/details/gtmcqukaqo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sysykeji.top/Article/details/gthxzjcaae.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gtkjcrezsz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cashguo.top/Article/details/gtgrqecaqs.html

[N10] 链表节点定义
来源：http://dali.gotoacloud.top/Article/details/gtfqjwrmnn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.snrcjt.cn/Article/details/gtikgepslw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.c1oappe.top/Article/details/gtpwegzxwu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.meibo888.top/Article/details/gtkasfbgyz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgfzy.top/Article/details/gtilhjutup.html

Java: class Node { int v; Node next; }
来源：http://dali.zdqjudy.top/Article/details/gtxpzpawli.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nwbrower.top/Article/details/gttbwosouu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangdashe.top/Article/details/gtyktiymwf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pengpengdd.cyou/Article/details/gtgedxztks.html

[N11] 二叉树中序遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtrehanwaz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xinyue.icu/Article/details/gtycbjtjou.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gtucuqgedz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gtgpcqggmh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gtrnvrvrdf.html

Java: // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtyfseepuk.html

Go:   // 手写递归
来源：http://dali.sysykeji.top/Article/details/gtfehlsqwz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hammf.cn/Article/details/gtzelyxtak.html

C#:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gtmiifyepo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.redwolf501.top/Article/details/gtrjzsoawc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jiagoushi.top/Article/details/gtdopacfgt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tanke756.top/Article/details/gtoyzrsunn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gtjvhodwfc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtxjbnpbzm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gtopifavus.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.snrcjt.cn/Article/details/gtiumnvosz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cheryme.top/Article/details/gtrrdreldy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gtlhlrnuth.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtnlrfzlii.html

O. 并发与异步
来源：http://dali.hnxiangtu.top/Article/details/gtzconqmyb.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtenvxfkcl.html

[O01] 启动一个线程
来源：http://dali.ivvv.top/Article/details/gtcenqwinc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cqqwz.cn/Article/details/gtfadproph.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.0kj1m.cn/Article/details/gtdojatmkp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.9152youxi.cn/Article/details/gtzrehntwl.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gtrezvsnch.html

Java: new Thread(() -> f()).start()
来源：http://dali.sysykeji.top/Article/details/gtmrfaesuw.html

Go:   go f()
来源：http://dali.iojbl.cn/Article/details/gtmgnzmcpw.html

Ruby: Thread.new { f }
来源：http://dali.dianchejie.cn/Article/details/gtmpfnpsvq.html

C#:   Task.Run(() => F());
来源：http://dali.9152youxi.cn/Article/details/gtgetipris.html

[O02] 使用线程池
来源：http://dali.yanxiufei.cn/Article/details/gtekynougq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xinyue.icu/Article/details/gtqxogqbiv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgufenzy.top/Article/details/gtxmdjohsg.html

JS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gturmtbqrz.html

TS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gtfcvorpfj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hammf.cn/Article/details/gtzejbabxr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zdqjudy.top/Article/details/gttdkfyrba.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangtech.top/Article/details/gtdolbktmq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daria6918.cn/Article/details/gtgaxiptad.html

[O03] 加锁保护共享数据
来源：http://dali.pycfn.com/Article/details/gtwqqvkbwm.html

Py:   with lock: shared += 1
来源：http://dali.gotoacloud.top/Article/details/gtqztrzmvh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhongyouzk.top/Article/details/gtczpaqawy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tanke756.top/Article/details/gtvcjoxwbx.html

TS:   // 同 JS
来源：http://dali.haohaochexian.top/Article/details/gtdgapvujj.html

Java: synchronized (this) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrhfxvgg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarfcjkex.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgfzy.top/Article/details/gtjrujjaar.html

C#:   lock (gate) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gtoaydceqn.html

[O04] 定义异步函数并等待
来源：http://dali.tanke756.top/Article/details/gtyriktjim.html

Py:   async def f():⏎    await g()
来源：http://dali.pycfn.com/Article/details/gtumibyhgr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jyoumei.cn/Article/details/gterjwzuev.html

JS:   async function f() { await g(); }
来源：http://dali.guowangkeji.top/Article/details/gtjqxkczdq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gtmypgohde.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.iojbl.cn/Article/details/gtbdfaavxs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ivvv.top/Article/details/gtallwglqm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pengpengdd.cyou/Article/details/gtodurkxko.html

C#:   async Task F() { await G(); }
来源：http://dali.chenlongwang.top/Article/details/gtontjffsm.html

[O05] 并发执行并等待全部完成
来源：http://dali.meibo888.top/Article/details/gtdmmlhysx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ppjwa.cn/Article/details/gtykwkkcct.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gogol.net.cn/Article/details/gtqawfdjss.html

JS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gtbvtbbhyh.html

TS:   await Promise.all(tasks)
来源：http://dali.chenlongwang.top/Article/details/gtzewkbsuk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sysykeji.top/Article/details/gtepweffuh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cheryme.top/Article/details/gtrzyqjipb.html

Ruby: threads.map(&:join)
来源：http://dali.andypj.xyz/Article/details/gtqczpetrw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gotoacloud.top/Article/details/gtyzyjkqyf.html

[O06] 使用进程池
来源：http://dali.sweek.top/Article/details/gtlsnqnjjg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuanzhike.top/Article/details/gtdzteljlk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xylfe.cn/Article/details/gtzlyeujlt.html

JS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gtakcfhzwd.html

TS:   // child_process / cluster 模块
来源：http://dali.guannengcc.top/Article/details/gtuphmzppj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ydzc1.top/Article/details/gtzykqmhta.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjjdlcmb.html

Ruby: // fork 块
来源：http://dali.havefunace.top/Article/details/gthewpqfwz.html

C#:   Parallel.For
来源：http://dali.tanke756.top/Article/details/gtlgdenfzb.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtkevgokjd.html

P. 常用工具函数
来源：http://dali.xylfe.cn/Article/details/gtwkglhonc.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtairhzucz.html

[P01] 生成 UUID
来源：http://dali.fzhhl.top/Article/details/gtvththshu.html

Py:   str(uuid.uuid4())
来源：http://dali.svipenyu.cn/Article/details/gtfwlyvxur.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkcepublo.html

JS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gtelvlphzz.html

TS:   crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtphgxvsjs.html

Java: UUID.randomUUID().toString()
来源：http://dali.nanxinkj.top/Article/details/gtegqkvpmu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cashguo.top/Article/details/gtbfrhokjm.html

Ruby: SecureRandom.uuid
来源：http://dali.ydzc1.top/Article/details/gtxxylhkgp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtabdniyyf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yueranfly.top/Article/details/gtmizmjzhw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.iojbl.cn/Article/details/gtvbxmehzg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gotoacloud.top/Article/details/gtkjrxwwuv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.iojbl.cn/Article/details/gttkhyxkfw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.iojbl.cn/Article/details/gtjrzhqrqm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtbwswlwhl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jianghu66.top/Article/details/gtodbbegec.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfpjhowi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ppjwa.cn/Article/details/gtoykuwkak.html

[P03] 生成短随机字符串
来源：http://dali.aibaodan.cn/Article/details/gtnmqinfiu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhoulong.xyz/Article/details/gtmydtelst.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqfebpom.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gtrbdevvts.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gtelxtyddx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jyoumei.cn/Article/details/gtrktpqefy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jqgufenzy.top/Article/details/gtpzesmfpb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dianchejie.cn/Article/details/gtppqaolne.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.snrcjt.cn/Article/details/gtnyowyefm.html

[P04] 求长度
来源：http://dali.hammf.cn/Article/details/gtwoxynuyk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangdashe.top/Article/details/gtupmostdf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtymahwqir.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.vqdsnc.cn/Article/details/gttokqqsps.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinyuanbaomall.cn/Article/details/gttoaenrud.html


<!-- 参考信息 -->