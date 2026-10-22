代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.c1oappe.top/Article/details/gtaqxwhzgo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.meibo888.top/Article/details/gtqmpvcvuc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xylfe.cn/Article/details/gtxqenapev.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shzxlz.cn/Article/details/gtvusuasey.html

[L07] 处理 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gtaixacdbu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tian-w.cn/Article/details/gtctkdxloh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.9152youxi.cn/Article/details/gtoiqdeber.html

JS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gtkpdwtnye.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gttsqivsps.html

Java: resp.statusCode()
来源：http://dali.hywenlv.cn/Article/details/gtaxvrixfw.html

Go:   resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gtzcbwyjyp.html

Ruby: resp.code.to_i
来源：http://dali.fzhhl.top/Article/details/gtzkccsoax.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gtgeakeutj.html

[L08] 并发请求多个地址
来源：http://dali.c1oappe.top/Article/details/gtgisqgfdk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.svipenyu.cn/Article/details/gtdfphayis.html

PHP:  curl_multi_init() 系列
来源：http://dali.guannengcc.top/Article/details/gttejdjevz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtrstespww.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtbjhshrph.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gtjkablxwx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jiagoushi.top/Article/details/gtsagqwfpy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.meibo888.top/Article/details/gtteyqfwlt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hfpthk.cn/Article/details/gtxxzdvuhh.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvjtqsky.html

M. 命令行 / 进程 / 环境
来源：http://dali.hammf.cn/Article/details/gttrijexls.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtipyhnfia.html

[M01] 读取命令行参数
来源：http://dali.aizwys.cn/Article/details/gtfrgpcogu.html

Py:   sys.argv[1:]
来源：http://dali.iojbl.cn/Article/details/gtvpnbpwid.html

PHP:  $argv;  $argc;
来源：http://dali.redwolf501.top/Article/details/gtysqwfatf.html

JS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gtkdjptbdf.html

TS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gtjcucqwmw.html

Java: args 数组（main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gtssmfjwxu.html

Go:   os.Args[1:]
来源：http://dali.sweek.top/Article/details/gtkzwrpbvi.html

Ruby: ARGV
来源：http://dali.cucudq.cn/Article/details/gtdzmndcai.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gtyisoleqd.html

[M02] 读取环境变量
来源：http://dali.yongpay.top/Article/details/gtmdhfpcba.html

Py:   os.environ.get("HOME")
来源：http://dali.tian-w.cn/Article/details/gtcheepvoh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtboewbspn.html

JS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gtprrktxsr.html

TS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysyfgpez.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtuogjzgoi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtvqwdfafu.html

Ruby: ENV["HOME"]
来源：http://dali.316326.xyz/Article/details/gtnkbzgsjz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yongpay.top/Article/details/gtqwrdyyuz.html

[M03] 执行外部命令
来源：http://dali.pycfn.com/Article/details/gttejuhpxb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yongpay.top/Article/details/gtfnbdyroo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuxming.cn/Article/details/gtxmwczzdw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gtjszxpdcv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtrfpxudzx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aibaodan.cn/Article/details/gtblauckbs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenjidiqi.icu/Article/details/gtdvtxzyst.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cqqwz.cn/Article/details/gtofnufxay.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zdqjudy.top/Article/details/gtlgamwpac.html

[M04] 获取当前工作目录
来源：http://dali.nwbrower.top/Article/details/gtcdfmgsni.html

Py:   os.getcwd()
来源：http://dali.jqgufenzy.top/Article/details/gtcfstwkie.html

PHP:  getcwd();
来源：http://dali.sufxvd.cn/Article/details/gtixiccuow.html

JS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtfwwtfugc.html

TS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gthghyobqn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.birdmap.top/Article/details/gtxmeryvuf.html

Go:   os.Getwd()
来源：http://dali.iojbl.cn/Article/details/gtxapnmqix.html

Ruby: Dir.pwd
来源：http://dali.dashuyun.cn/Article/details/gteezoraig.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.iojbl.cn/Article/details/gtpzlvcqso.html

[M05] 设置退出码
来源：http://dali.ehwqpu.com/Article/details/gtxrmcuuoq.html

Py:   sys.exit(1)
来源：http://dali.yongpay.top/Article/details/gtafrpfkta.html

PHP:  exit(1);
来源：http://dali.guannengcc.top/Article/details/gtnzesbhwz.html

JS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gttpzkjlne.html

TS:   process.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtevzftysz.html

Java: System.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtmeydkkka.html

Go:   os.Exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtkltehjdx.html

Ruby: exit 1
来源：http://dali.ehwqpu.com/Article/details/gtwkwvtgce.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gtpaociwzq.html

[M06] 向标准错误输出
来源：http://dali.cqqwz.cn/Article/details/gtwqpkoxpb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj202588.top/Article/details/gtdsjxadrg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.feifeiyinyue.top/Article/details/gtjfmzovbl.html

JS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtgcigoyib.html

TS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gtwsgpoudj.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyuwyjbty.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aizwys.cn/Article/details/gtgqrvvlha.html

Ruby: warn "err"
来源：http://dali.chenlongwang.top/Article/details/gtmgbljawf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xinyue.icu/Article/details/gtgukahybv.html

[M07] 判断是否为主入口
来源：http://dali.ybcxt.top/Article/details/gtuocvwxad.html

Py:   if __name__ == "__main__":
来源：http://dali.c1oappe.top/Article/details/gtfgrmluid.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.vqdsnc.cn/Article/details/gtkqiqeurw.html

JS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdwwznge.html

TS:   require.main === module
来源：http://dali.cqqwz.cn/Article/details/gtuktirjpg.html

Java: public static void main(String[] args)
来源：http://dali.hammf.cn/Article/details/gtnahpiors.html

Go:   func main()
来源：http://dali.guowangkeji.top/Article/details/gtlstaldjv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cucudq.cn/Article/details/gtbglnpxvr.html

C#:   static void Main(string[] args)
来源：http://dali.yongpay.top/Article/details/gtwflslnug.html

[M08] 获取系统与运行时信息
来源：http://dali.tanke756.top/Article/details/gtqevbnngm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.feifeiyinyue.top/Article/details/gtsecqqiht.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.feifeiyinyue.top/Article/details/gtahrsdgdp.html

JS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gtmdqdndho.html

TS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gtknvvjape.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aibaodan.cn/Article/details/gtmbsopbzo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zycfv.cn/Article/details/gtoceyismj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258888.top/Article/details/gtphubwmqr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.0kj1m.cn/Article/details/gtrrstwifp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtcagysypk.html

N. 数据结构与算法
来源：http://dali.tian-w.cn/Article/details/gtlxinkuum.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtmlbntpmk.html

[N01] 二分查找（有序数组）
来源：http://dali.bjfxy.top/Article/details/gtnyjuyylz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtmcdrrxtm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yonumen.top/Article/details/gtjhgcrwtn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gtiurmyovz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gthhbyxyjw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gtcyrgdymd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtrczkgfza.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.pycfn.com/Article/details/gtvpcvwgmd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbcatxug.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhoulong.xyz/Article/details/gtvceamnzn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.smart0.xyz/Article/details/gtcbeqlhog.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gzhubu.top/Article/details/gtjiomzlqw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gtljbatdig.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtqpedyhjk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcokvqib.html

Go:   slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gtmqmnfqic.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gtfwafigwr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.9152youxi.cn/Article/details/gtrwmenbea.html

[N03] 快速排序（分治示例）
来源：http://dali.yongpay.top/Article/details/gtayjfmtlr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.meibo888.top/Article/details/gttkxjlqxv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tian-w.cn/Article/details/gtwxukwkfp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gtiffilatm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gtjirctvnt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.vqdsnc.cn/Article/details/gtgylintfx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258.top/Article/details/gtpkntnxza.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pengpengdd.cyou/Article/details/gtywudgorg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gtebbjtldz.html

[N04] 斐波那契数列
来源：http://dali.zdqjudy.top/Article/details/gtvjastryl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtjnllkcuw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ybcxt.top/Article/details/gtfwecckvx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtvjqnfyzj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gtpiclpldm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aizwys.cn/Article/details/gtutihgosi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hongshengwenyu.top/Article/details/gttpngludv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gtrpkbzppo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gtrtvfqlqj.html

[N05] 最大公约数
来源：http://dali.havefunace.top/Article/details/gtaseypdlk.html

Py:   math.gcd(a, b)
来源：http://dali.fengsongda.top/Article/details/gtwvaieyvb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.vqdsnc.cn/Article/details/gtmorjlelj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gtyxraufqt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gtpryeyncz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhongyouzk.top/Article/details/gtfllxnczp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhiwuduotai.top/Article/details/gtzauhpoaz.html

Ruby: a.gcd(b)
来源：http://dali.gogol.net.cn/Article/details/gthgygpyhg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cheryme.top/Article/details/gtppetzvvz.html

[N06] 判断回文字符串
来源：http://dali.xinyue.icu/Article/details/gtrtzllncz.html

Py:   s == s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gtuwcsivbi.html

PHP:  $s === strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gtunligrnk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtblpguauv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtshsxwhki.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guowangkeji.top/Article/details/gtrslsupct.html

Go:   // 双指针从两端比较
来源：http://dali.zhongyouzk.top/Article/details/gtnmnbgfum.html

Ruby: s == s.reverse
来源：http://dali.sysykeji.top/Article/details/gtohpyqygd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gtnjtkjmqr.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258.top/Article/details/gtzrfpeaow.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yvedp.cn/Article/details/gtmaldslmx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sweek.top/Article/details/gtsrazhcgb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jyoumei.cn/Article/details/gturncuiao.html

TS:   // 手写 Map<string, number>
来源：http://dali.316326.xyz/Article/details/gtlumtqmoa.html

Java: // 手写 HashMap
来源：http://dali.yuanzhike.top/Article/details/gtcttuvsja.html

Go:   // 手写 map[int]int
来源：http://dali.mhx1999.top/Article/details/gttnotmenm.html

Ruby: // 手写 Hash
来源：http://dali.chenjidiqi.icu/Article/details/gtdmechyuf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cheryme.top/Article/details/gthlknoyxg.html

[N08] 生成全排列
来源：http://dali.xuetiantiany.cn/Article/details/gtgexpprzl.html

Py:   itertools.permutations(arr)
来源：http://dali.yj20258888.top/Article/details/gtcehklzmr.html

PHP:  // 手写递归交换
来源：http://dali.yj20258.top/Article/details/gtkmbouibp.html

JS:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtjmwxmphk.html

TS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtgbchttzg.html

Java: // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfnmqqkc.html

Go:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtjtjgwlvq.html

Ruby: arr.permutation.to_a
来源：http://dali.tianlin.xyz/Article/details/gtrmnmxmuz.html

C#:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtaalpehcy.html

[N09] 栈与队列
来源：http://dali.fzhhl.top/Article/details/gtswpjfmyg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xinyue.icu/Article/details/gtjxqykboc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtiyiyanbd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gtchlrrppa.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yongpay.top/Article/details/gtefwivtmv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xinyue.icu/Article/details/gttcdicuag.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gtzatzmsls.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtsdxvklkb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuanzhike.top/Article/details/gtmuvxagkq.html

[N10] 链表节点定义
来源：http://dali.aibaodan.cn/Article/details/gtfoqpivlu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.c1oappe.top/Article/details/gtuovwdruc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ydzc1.top/Article/details/gtmdruclyw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gthzokuiua.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tianlin.xyz/Article/details/gtxzphlxne.html

Java: class Node { int v; Node next; }
来源：http://dali.tianlin.xyz/Article/details/gtgrwfrxbk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yongpay.top/Article/details/gtjvmavnki.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xinyue.icu/Article/details/gtncrjvsej.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ivvv.top/Article/details/gtcmbqmhyd.html

[N11] 二叉树中序遍历
来源：http://dali.smart0.xyz/Article/details/gtgshrhadc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkfhzmgd.html

PHP:  // 手写递归函数
来源：http://dali.meibo888.top/Article/details/gtbetnfobe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gtpuzplexx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjxvyokw.html

Java: // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtqtdkbuww.html

Go:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gtrnzjueyv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.redwolf501.top/Article/details/gtxyrkwsrb.html

C#:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gtcnmmhiun.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.vqdsnc.cn/Article/details/gtnqxerzbk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ybcxt.top/Article/details/gtlzhqaxuh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nwbrower.top/Article/details/gtsjkygxyr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gtnvtzbrmh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gtybulydhj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gtwmspvyvk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenlongwang.top/Article/details/gtkgloosfv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxuanxn.top/Article/details/gtxrxfkpve.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfjmquwc.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtyogdoqrg.html

O. 并发与异步
来源：http://dali.ppjwa.cn/Article/details/gthtyxomcq.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtnbusefcu.html

[O01] 启动一个线程
来源：http://dali.smart0.xyz/Article/details/gtwqycffza.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fzhhl.top/Article/details/gtuyrarref.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.c1oappe.top/Article/details/gtqvsxkfma.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.snrcjt.cn/Article/details/gtdvbxhyfo.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gttxqztglk.html

Java: new Thread(() -> f()).start()
来源：http://dali.0kj1m.cn/Article/details/gtpphiypcx.html

Go:   go f()
来源：http://dali.jyoumei.cn/Article/details/gtofdvbjjr.html

Ruby: Thread.new { f }
来源：http://dali.zhixingplan.top/Article/details/gtqplzrxfv.html

C#:   Task.Run(() => F());
来源：http://dali.yonumen.top/Article/details/gtkyzqyxbs.html

[O02] 使用线程池
来源：http://dali.mhx1999.top/Article/details/gtddzelqdq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.iojbl.cn/Article/details/gtxmebmxaa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xylfe.cn/Article/details/gtngyqclcz.html

JS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gtyagwvbrl.html

TS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gtyinmbntj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.andypj.xyz/Article/details/gtlqqucpfi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhengqikj.top/Article/details/gtpbvaxsjs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.0kj1m.cn/Article/details/gtcyknscve.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.0kj1m.cn/Article/details/gtxiplogoh.html

[O03] 加锁保护共享数据
来源：http://dali.ivvv.top/Article/details/gtuxnkxobl.html

Py:   with lock: shared += 1
来源：http://dali.ehwqpu.com/Article/details/gtqagfprph.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.birdmap.top/Article/details/gtvebocegt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yvedp.cn/Article/details/gtpotydocj.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtwnyjpedt.html

Java: synchronized (this) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gtacgduhyh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.svipenyu.cn/Article/details/gtorsewfvt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jiagoushi.top/Article/details/gtamtfsekz.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gtgsbcjqzz.html

[O04] 定义异步函数并等待
来源：http://dali.jiagoushi.top/Article/details/gtzijmajxs.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gtegipaqtm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.feifeiyinyue.top/Article/details/gtodysltew.html

JS:   async function f() { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtpskwlbth.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gtyxufpsfb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jyoumei.cn/Article/details/gtyelahhub.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dianchejie.cn/Article/details/gtyzzgrzkx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.svipenyu.cn/Article/details/gtoymmzayd.html

C#:   async Task F() { await G(); }
来源：http://dali.jyoumei.cn/Article/details/gtfsrdkban.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuetiantiany.cn/Article/details/gtsrqpjskl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.haohaochexian.top/Article/details/gtlakzjsvr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.meibo888.top/Article/details/gtirjermvf.html

JS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gttjjnjmrq.html

TS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gtzrkpkouj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jyoumei.cn/Article/details/gtmvmezagf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.9152youxi.cn/Article/details/gtedxokkiz.html

Ruby: threads.map(&:join)
来源：http://dali.shzxlz.cn/Article/details/gtudwwafcy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.vqdsnc.cn/Article/details/gtrlthlusm.html

[O06] 使用进程池
来源：http://dali.aibaodan.cn/Article/details/gtdzvdbqxv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqoyjsio.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gogol.net.cn/Article/details/gtmwhtmivb.html

JS:   // child_process / cluster 模块
来源：http://dali.nanxuanxn.top/Article/details/gtylhfqlyk.html

TS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gtlgqxdkvz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgbqyryd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258888.top/Article/details/gtokkxlckp.html

Ruby: // fork 块
来源：http://dali.dianchejie.cn/Article/details/gtkhodxgko.html

C#:   Parallel.For
来源：http://dali.jinqigfzy.top/Article/details/gthivpvjrd.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtivbhqjqd.html

P. 常用工具函数
来源：http://dali.gaohongyu789.top/Article/details/gtkhdttrwp.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtherjjafa.html

[P01] 生成 UUID
来源：http://dali.xuanzx.com/Article/details/gtckizxevz.html

Py:   str(uuid.uuid4())
来源：http://dali.hnqzz.top/Article/details/gttnedbata.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj20258888.top/Article/details/gthcjpwgju.html

JS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgsjpcasu.html

TS:   crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gtdvdovxny.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtztalbhrp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yueranfly.top/Article/details/gtqbcwdood.html

Ruby: SecureRandom.uuid
来源：http://dali.daxiang520.top/Article/details/gtskvahpsk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.fengsongda.top/Article/details/gtoieoxbkf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.9152youxi.cn/Article/details/gtinxghikg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlycdwuv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtnxtudxqt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gotoacloud.top/Article/details/gtkwhkkaxu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gotoacloud.top/Article/details/gtbiqleaxs.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtnxoxlmag.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.pengpengdd.cyou/Article/details/gtfifzxlcv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwumyijm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xziqi.cn/Article/details/gtprnniykz.html

[P03] 生成短随机字符串
来源：http://dali.xylfe.cn/Article/details/gttpifvyjy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xziqi.cn/Article/details/gtwjspybby.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gogol.net.cn/Article/details/gtnjrhrnpb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfubrunt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dashuyun.cn/Article/details/gtxocrehjz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fzhhl.top/Article/details/gtfqsjdmgz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dashuyun.cn/Article/details/gtkmhmzxay.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.316326.xyz/Article/details/gttzsjolwr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgfzy.top/Article/details/gtjgfatbfs.html

[P04] 求长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdefbzxbp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.andypj.xyz/Article/details/gtlpfwkqkx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtxysxyaxy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gtiwtblegy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gtzgxptfzz.html


<!-- 参考信息 -->