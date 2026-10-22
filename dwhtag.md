代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtvimmrryn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yongpay.top/Article/details/gtquprfgkr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yvedp.cn/Article/details/gtadrryvsh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gtzakcrwko.html

[L07] 处理 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gtewsnzbeh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fengsongda.top/Article/details/gtbywpaxfs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jlsjyb.cn/Article/details/gtbnqejrbu.html

JS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gttejxzoac.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtyzlnvtee.html

Java: resp.statusCode()
来源：http://dali.xylfe.cn/Article/details/gtpzzzpbna.html

Go:   resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gtgcnxwhem.html

Ruby: resp.code.to_i
来源：http://dali.haohaochexian.top/Article/details/gtlqjsiord.html

C#:   (int)resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtyvzzdcpc.html

[L08] 并发请求多个地址
来源：http://dali.shzxlz.cn/Article/details/gtkjtbniaj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhengqikj.top/Article/details/gtmruqajmx.html

PHP:  curl_multi_init() 系列
来源：http://dali.hongshengwenyu.top/Article/details/gtbmowjafh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gtpvkvfucx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gtxvpontqf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhoulong.xyz/Article/details/gtuwllryms.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj202588.top/Article/details/gtxlqnvhdc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gthyhylsux.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.svipenyu.cn/Article/details/gtueordues.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtrgnklwmc.html

M. 命令行 / 进程 / 环境
来源：http://dali.sufxvd.cn/Article/details/gtmjosrfzc.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gturwcvkcl.html

[M01] 读取命令行参数
来源：http://dali.ehwqpu.com/Article/details/gttpkinnxq.html

Py:   sys.argv[1:]
来源：http://dali.0kj1m.cn/Article/details/gtlrtkbjgy.html

PHP:  $argv;  $argc;
来源：http://dali.zhoulong.xyz/Article/details/gtvqgiqdqg.html

JS:   process.argv.slice(2)
来源：http://dali.yueranfly.top/Article/details/gttrubdeme.html

TS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtalasseur.html

Java: args 数组（main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtviknonfv.html

Go:   os.Args[1:]
来源：http://dali.shzxlz.cn/Article/details/gtqaflxhgz.html

Ruby: ARGV
来源：http://dali.cashguo.top/Article/details/gtnxvyrdbd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gthrkbyuny.html

[M02] 读取环境变量
来源：http://dali.jqgfzy.top/Article/details/gtsonhnfvn.html

Py:   os.environ.get("HOME")
来源：http://dali.yongpay.top/Article/details/gtwtksqlbd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtyoxsgyhv.html

JS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gtaslndjyk.html

TS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gtsywpmzcy.html

Java: System.getenv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtehqoosty.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.havefunace.top/Article/details/gtzyehwzfi.html

Ruby: ENV["HOME"]
来源：http://dali.yongpay.top/Article/details/gtubsiqnyd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtizbqocib.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gtgmlelsio.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sysykeji.top/Article/details/gtsrsebdcf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guowangkeji.top/Article/details/gtpsopqfir.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gtlxlazmbg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gtvkjsgnxf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258888.top/Article/details/gtwoedetyu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.bjfxy.top/Article/details/gtdsvvmjeq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sysykeji.top/Article/details/gtgloobyai.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhoulong.xyz/Article/details/gtwomkihid.html

[M04] 获取当前工作目录
来源：http://dali.jyoumei.cn/Article/details/gttchjxkjf.html

Py:   os.getcwd()
来源：http://dali.guannengcc.top/Article/details/gttzmjnvav.html

PHP:  getcwd();
来源：http://dali.iojbl.cn/Article/details/gtprmkwuan.html

JS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gtbzrdlpfk.html

TS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gttodiqiiz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yanxiufei.cn/Article/details/gtryegvnwe.html

Go:   os.Getwd()
来源：http://dali.yueranfly.top/Article/details/gtrkldwssd.html

Ruby: Dir.pwd
来源：http://dali.yj20258888.top/Article/details/gtctkosggf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shzxlz.cn/Article/details/gtnsccnffw.html

[M05] 设置退出码
来源：http://dali.shuidangran.top/Article/details/gtwaqzgaoh.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtkhbndkyh.html

PHP:  exit(1);
来源：http://dali.shzxlz.cn/Article/details/gtaamiyzlk.html

JS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtmkzjnusi.html

TS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtevkycwjp.html

Java: System.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtjrtjhkax.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmeobgxq.html

Ruby: exit 1
来源：http://dali.yvedp.cn/Article/details/gtobvkzwkk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ywan-chungtsiang.top/Article/details/gttewdfazn.html

[M06] 向标准错误输出
来源：http://dali.yuxming.cn/Article/details/gthfdxzonu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gtfykcnijr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cheryme.top/Article/details/gtagxixugb.html

JS:   console.error("err")
来源：http://dali.nwbrower.top/Article/details/gtkxkanhyq.html

TS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtwauepqxy.html

Java: System.err.println("err")
来源：http://dali.jqgufenzy.top/Article/details/gtzlmfezpu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj202588.top/Article/details/gteoindtbc.html

Ruby: warn "err"
来源：http://dali.ybcxt.top/Article/details/gtoizygrqo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenzaomai.com/Article/details/gtnnocqvpm.html

[M07] 判断是否为主入口
来源：http://dali.ybcxt.top/Article/details/gtwbgigjur.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gttohqfaok.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj202588.top/Article/details/gtkwvajzdd.html

JS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gtjrukmeze.html

TS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gtcfrseesc.html

Java: public static void main(String[] args)
来源：http://dali.nanxuanxn.top/Article/details/gtnykyjrhw.html

Go:   func main()
来源：http://dali.zhixingplan.top/Article/details/gtolfimbzs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xziqi.cn/Article/details/gtkmlxleuu.html

C#:   static void Main(string[] args)
来源：http://dali.smart0.xyz/Article/details/gtpgrzkuth.html

[M08] 获取系统与运行时信息
来源：http://dali.yangfankeji.com/Article/details/gtccwhnmvi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinghuilouyu.cn/Article/details/gtaayoofgt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sweek.top/Article/details/gttsibploi.html

JS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gtgsrhhwrd.html

TS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gtfealfdia.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ydzc1.top/Article/details/gtxmtxrcdg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgufenzy.top/Article/details/gttuhxioay.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuanzhike.top/Article/details/gtzcckssvn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigfzy.top/Article/details/gtyabwtzvn.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtooapcheg.html

N. 数据结构与算法
来源：http://dali.snrcjt.cn/Article/details/gtjntawcue.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gttaoecpeo.html

[N01] 二分查找（有序数组）
来源：http://dali.andypj.xyz/Article/details/gtxoyaster.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtvezmpajn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xziqi.cn/Article/details/gtqzuhaxzz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gtvjotxren.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtnqwulvjs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtldeocvku.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtlfmlwqrs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hfpthk.cn/Article/details/gtfhmzwpaz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtgbipjuuq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258888.top/Article/details/gtydiyfajv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gtxlrnlnba.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hfpthk.cn/Article/details/gtozbbnwti.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtcavcmpuj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gtxccmdneu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shuidangran.top/Article/details/gtkerhhgdm.html

Go:   slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gtkfbzlvyn.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gtwdhraqdn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cucudq.cn/Article/details/gtemhiaubd.html

[N03] 快速排序（分治示例）
来源：http://dali.cucudq.cn/Article/details/gtococaroh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guannengcc.top/Article/details/gtxjuikema.html

PHP:  // 递归实现，或用 usort
来源：http://dali.quarkkingdee.top/Article/details/gttutugdcs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.redwolf501.top/Article/details/gtbzbcssxo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ehwqpu.com/Article/details/gtdrpcffxo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yongpay.top/Article/details/gtbwhrbyjo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.9152youxi.cn/Article/details/gtkwhwmvmd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hnxiangtu.top/Article/details/gtkmpghggx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yangfankeji.com/Article/details/gtnywqlegh.html

[N04] 斐波那契数列
来源：http://dali.xuetiantiany.cn/Article/details/gtftwqqhkc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gtcyzdonii.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.smart0.xyz/Article/details/gtwiikixkd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtntvzrafm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtgklpeqgu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gtwnmsztyi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.haohaochexian.top/Article/details/gtpolzpbhd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gtvhmnwrdg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gthnzralmh.html

[N05] 最大公约数
来源：http://dali.jinqigfzy.top/Article/details/gtasxlqmnt.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigufen.top/Article/details/gttyginpmy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.c1oappe.top/Article/details/gtcgiuvqpb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gtmklnjoet.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtdnzucsne.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yueranfly.top/Article/details/gthygqngae.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gzhubu.top/Article/details/gtynfcpcaf.html

Ruby: a.gcd(b)
来源：http://dali.kuanghao11.cn/Article/details/gteiyxlkml.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sufxvd.cn/Article/details/gtvuyzfriv.html

[N06] 判断回文字符串
来源：http://dali.yuanzhike.top/Article/details/gtziatmakr.html

Py:   s == s[::-1]
来源：http://dali.xuanzx.com/Article/details/gtemcwoqhk.html

PHP:  $s === strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gtfnbdxxax.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gttxkixizo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtaospmzgv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jianghu66.top/Article/details/gtmdjjklqv.html

Go:   // 双指针从两端比较
来源：http://dali.snrcjt.cn/Article/details/gthqirdgxo.html

Ruby: s == s.reverse
来源：http://dali.sweek.top/Article/details/gttxasanml.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ppjwa.cn/Article/details/gtpyhmrrgc.html

[N07] 两数之和（返回下标）
来源：http://dali.xuanzx.com/Article/details/gttljqbfan.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.svipenyu.cn/Article/details/gtqtpkzjtt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tianlin.xyz/Article/details/gtrsusmrgt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aizwys.cn/Article/details/gtxyzsyiky.html

TS:   // 手写 Map<string, number>
来源：http://dali.gaohongyu789.top/Article/details/gtezehzbqn.html

Java: // 手写 HashMap
来源：http://dali.cashguo.top/Article/details/gtrvptcbwb.html

Go:   // 手写 map[int]int
来源：http://dali.guannengcc.top/Article/details/gtjbofxyrj.html

Ruby: // 手写 Hash
来源：http://dali.xylfe.cn/Article/details/gtkzkrvixv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cqqwz.cn/Article/details/gtdjjutgdj.html

[N08] 生成全排列
来源：http://dali.tanke756.top/Article/details/gtpisyybpo.html

Py:   itertools.permutations(arr)
来源：http://dali.xuanzx.com/Article/details/gtddnrtwvx.html

PHP:  // 手写递归交换
来源：http://dali.chenlongwang.top/Article/details/gtjzgxvvup.html

JS:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gthmnudxli.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtpicavmyn.html

Java: // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtlalwqstt.html

Go:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtprlljtak.html

Ruby: arr.permutation.to_a
来源：http://dali.316326.xyz/Article/details/gtjexmjznk.html

C#:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtwgwozutp.html

[N09] 栈与队列
来源：http://dali.yonumen.top/Article/details/gtdjdxunsb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzlkwriv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtzfyorwfd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtkheazwsl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.bjfxy.top/Article/details/gtfonilgnk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xylfe.cn/Article/details/gttndzcqyy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnqzz.top/Article/details/gtvzwdypwy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gtmdhntxor.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhbkqhbg.html

[N10] 链表节点定义
来源：http://dali.jinqigfzy.top/Article/details/gtdddtdfvs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gzhubu.top/Article/details/gtfkcbqwau.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gtmruzjtld.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zdqjudy.top/Article/details/gtwhwugviu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cashguo.top/Article/details/gtiojqyija.html

Java: class Node { int v; Node next; }
来源：http://dali.yangfankeji.com/Article/details/gtpjbeoryg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenzaomai.com/Article/details/gtegwzqgcm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgvxkxgg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.c1oappe.top/Article/details/gtihzyywnl.html

[N11] 二叉树中序遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkvcehxm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigufen.top/Article/details/gtsqwexavl.html

PHP:  // 手写递归函数
来源：http://dali.yongpay.top/Article/details/gtgakteofn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ppjwa.cn/Article/details/gtktgoazcp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbyansdn.html

Java: // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtwfdgsgss.html

Go:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gtuqxvnhdx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nwbrower.top/Article/details/gtaxzmsiiw.html

C#:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gtlxujixnr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgufenzy.top/Article/details/gtqzebobqx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yonumen.top/Article/details/gtovhoztqh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenzaomai.com/Article/details/gtndudfmaz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gtdrzgaefn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gtkpqjbple.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gtiynsuldt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgufenzy.top/Article/details/gtxlthtjdy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gotoacloud.top/Article/details/gtbxcsdkfo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhsmrcdz.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtkbgtlsov.html

O. 并发与异步
来源：http://dali.chenjidiqi.icu/Article/details/gtuudpwxdd.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtmevaeiup.html

[O01] 启动一个线程
来源：http://dali.ybcxt.top/Article/details/gtocylzcgk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gzhubu.top/Article/details/gtencnyjhi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cqqwz.cn/Article/details/gtepkvdgpk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cqqwz.cn/Article/details/gtsyiqlqdv.html

TS:   // 同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtbcidvhsx.html

Java: new Thread(() -> f()).start()
来源：http://dali.birdmap.top/Article/details/gtwaizrbmr.html

Go:   go f()
来源：http://dali.daxiang520.top/Article/details/gtdsmwlnpt.html

Ruby: Thread.new { f }
来源：http://dali.nanxinkj.top/Article/details/gtifcmtrez.html

C#:   Task.Run(() => F());
来源：http://dali.tanke756.top/Article/details/gtmwhaobsz.html

[O02] 使用线程池
来源：http://dali.iojbl.cn/Article/details/gtjmiuxutb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shuidangran.top/Article/details/gtqfwyxhmf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpwqymak.html

JS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gtgksejzwv.html

TS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gtjrvlkykw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xinyue.icu/Article/details/gtarnotddr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ybcxt.top/Article/details/gtcsdjbqnb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hammf.cn/Article/details/gtubimehbe.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangshuangyany.cn/Article/details/gtyqeolzly.html

[O03] 加锁保护共享数据
来源：http://dali.xuanzx.com/Article/details/gtkhgltxht.html

Py:   with lock: shared += 1
来源：http://dali.cdnleiting.top/Article/details/gtfkttfrzd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.c1oappe.top/Article/details/gttomstqqz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gogol.net.cn/Article/details/gtvaphtnyd.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyhgqyqg.html

Java: synchronized (this) { shared++; }
来源：http://dali.daxiang520.top/Article/details/gtriahvrzy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ydzc1.top/Article/details/gtzzgdsosn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pengpengdd.cyou/Article/details/gtjaqcvfrb.html

C#:   lock (gate) { shared++; }
来源：http://dali.hywenlv.cn/Article/details/gtnrpvkael.html

[O04] 定义异步函数并等待
来源：http://dali.pycfn.com/Article/details/gtvoqablji.html

Py:   async def f():⏎    await g()
来源：http://dali.hnqzz.top/Article/details/gthvxwgagm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.andypj.xyz/Article/details/gtutalmiks.html

JS:   async function f() { await g(); }
来源：http://dali.daxiang520.top/Article/details/gtchqucyui.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtoosfiehw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gzhubu.top/Article/details/gtbrzrtsel.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.aibaodan.cn/Article/details/gtbornqyhf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinghuilouyu.cn/Article/details/gtzekzkhxn.html

C#:   async Task F() { await G(); }
来源：http://dali.wangdashe.top/Article/details/gticfmmrds.html

[O05] 并发执行并等待全部完成
来源：http://dali.hammf.cn/Article/details/gtqxlazden.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pycfn.com/Article/details/gtelsxursw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gotoacloud.top/Article/details/gtackilahe.html

JS:   await Promise.all(tasks)
来源：http://dali.xziqi.cn/Article/details/gtrcootpve.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gtixjrfjms.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj202588.top/Article/details/gtoejvhldh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.haohaochexian.top/Article/details/gtoqakmztz.html

Ruby: threads.map(&:join)
来源：http://dali.andypj.xyz/Article/details/gtuqdlijom.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.0kj1m.cn/Article/details/gtsdsikypz.html

[O06] 使用进程池
来源：http://dali.fengsongda.top/Article/details/gtkhdjmdfp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhongyouzk.top/Article/details/gtnpbtcomr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guowangkeji.top/Article/details/gtkuekmvxf.html

JS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gtfoudfnlm.html

TS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gtvxhcxqkf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhhsqvfg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jianghu66.top/Article/details/gtvcpsrwgi.html

Ruby: // fork 块
来源：http://dali.9152youxi.cn/Article/details/gtertseofw.html

C#:   Parallel.For
来源：http://dali.wangdashe.top/Article/details/gtnuuqncbq.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtpuawjgrs.html

P. 常用工具函数
来源：http://dali.meibo888.top/Article/details/gtxvtsuwse.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtwhroenwe.html

[P01] 生成 UUID
来源：http://dali.hnqzz.top/Article/details/gtgvrqvztd.html

Py:   str(uuid.uuid4())
来源：http://dali.yj202588.top/Article/details/gtwwbrdbom.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.dashuyun.cn/Article/details/gtqrvginry.html

JS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtbjnnshcx.html

TS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gtkztvdiou.html

Java: UUID.randomUUID().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtzeznlkeu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fengsongda.top/Article/details/gtwqwhekdr.html

Ruby: SecureRandom.uuid
来源：http://dali.birdmap.top/Article/details/gtsabaftvf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shzxlz.cn/Article/details/gtobilteak.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cashguo.top/Article/details/gtooaqscab.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hongshengwenyu.top/Article/details/gtwxtxbcrz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258.top/Article/details/gtulhwqkie.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sweek.top/Article/details/gtevzfczsk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jlsjyb.cn/Article/details/gtzupshgpb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtlrsyoxhs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenzaomai.com/Article/details/gtazkqeefg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.meibo888.top/Article/details/gtwgfphcug.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.havefunace.top/Article/details/gtrrtedrea.html

[P03] 生成短随机字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahttauen.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.daria6918.cn/Article/details/gtccyhpvxp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.kuanghao11.cn/Article/details/gtcqkpvbqg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gtiksutabv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gtrieygvna.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbvlmdqp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ivvv.top/Article/details/gtvhyytvzw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tianlin.xyz/Article/details/gtncmdkrsg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yueranfly.top/Article/details/gtmtyuoile.html

[P04] 求长度
来源：http://dali.zhixingplan.top/Article/details/gtahfejtyz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jlsjyb.cn/Article/details/gthounbwya.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtovxvzmae.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gtzfhdgowu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gtulszpbod.html


<!-- 参考信息 -->