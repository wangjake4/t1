代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.meibo888.top/Article/details/gtcyyznamx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gtmpejzzeq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuanzx.com/Article/details/gtxweiyitt.html

[L06] 解析响应为 JSON
来源：http://dali.chenzaomai.com/Article/details/gtpsbyovzq.html

Py:   resp.json()
来源：http://dali.zycfv.cn/Article/details/gtuogdksem.html

PHP:  json_decode($body, true);
来源：http://dali.birdmap.top/Article/details/gtihgrnacx.html

JS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gtkwplnvwb.html

TS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtmmjkobtn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtygviconv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yangfankeji.com/Article/details/gtntfwqtbp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xziqi.cn/Article/details/gtkazxdqsm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shuidangran.top/Article/details/gtjzmgkjqa.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gtbmdgptay.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangshuangyany.cn/Article/details/gtclfwqrnm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gzhubu.top/Article/details/gtknzedhvd.html

JS:   resp.ok;  resp.status
来源：http://dali.shzxlz.cn/Article/details/gtwvwocuqk.html

TS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gtwnmbabvn.html

Java: resp.statusCode()
来源：http://dali.ivvv.top/Article/details/gtfnyjyoaa.html

Go:   resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gtjfouzypc.html

Ruby: resp.code.to_i
来源：http://dali.nwbrower.top/Article/details/gtpmdpxofy.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gtzvmejrvt.html

[L08] 并发请求多个地址
来源：http://dali.nanxuanxn.top/Article/details/gttombmvlm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangdashe.top/Article/details/gtywynznuo.html

PHP:  curl_multi_init() 系列
来源：http://dali.mhx1999.top/Article/details/gtfwhxhuyh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtcroxvrid.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnkyoqkg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.redwolf501.top/Article/details/gtybxwssfe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sysykeji.top/Article/details/gtvoghwota.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.c1oappe.top/Article/details/gttpcahchx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.c1oappe.top/Article/details/gtwaozccbn.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gttfvjkjgs.html

M. 命令行 / 进程 / 环境
来源：http://dali.snrcjt.cn/Article/details/gtmfgmkewr.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtzmktyleh.html

[M01] 读取命令行参数
来源：http://dali.havefunace.top/Article/details/gtgnjtzzfq.html

Py:   sys.argv[1:]
来源：http://dali.cdnleiting.top/Article/details/gtfffnnpud.html

PHP:  $argv;  $argc;
来源：http://dali.gotoacloud.top/Article/details/gtizpmbppm.html

JS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtjcdjcpis.html

TS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gtavjmkcya.html

Java: args 数组（main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gtcfamgldp.html

Go:   os.Args[1:]
来源：http://dali.yvedp.cn/Article/details/gtrkqxjzxw.html

Ruby: ARGV
来源：http://dali.vqdsnc.cn/Article/details/gtqejxjist.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gtoriclcwc.html

[M02] 读取环境变量
来源：http://dali.havefunace.top/Article/details/gtjghbydzg.html

Py:   os.environ.get("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtmgvvvrau.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gthszyrqfw.html

JS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtyvhvtwrd.html

TS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gttgfvmvuo.html

Java: System.getenv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gttfwctpdp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tian-w.cn/Article/details/gtztmqvwrl.html

Ruby: ENV["HOME"]
来源：http://dali.wangshuangyany.cn/Article/details/gthnfgkmtf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shuidangran.top/Article/details/gtysfoiemw.html

[M03] 执行外部命令
来源：http://dali.jiagoushi.top/Article/details/gtqrbsogot.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shzxlz.cn/Article/details/gtzznsdncm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.wangshuangyany.cn/Article/details/gtpszfnplo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gtblspkszh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtauwdahuh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuanzhike.top/Article/details/gtdrcjpdbx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tanke756.top/Article/details/gtzyqqvslx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sufxvd.cn/Article/details/gtvznooqbx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnqzz.top/Article/details/gtgierrjou.html

[M04] 获取当前工作目录
来源：http://dali.dianchejie.cn/Article/details/gtfidlqvnc.html

Py:   os.getcwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtrxeeujmp.html

PHP:  getcwd();
来源：http://dali.svipenyu.cn/Article/details/gtuoeclbyv.html

JS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gtwomywfjo.html

TS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gtzfukeksd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gotoacloud.top/Article/details/gtdzearyjg.html

Go:   os.Getwd()
来源：http://dali.yuxming.cn/Article/details/gtukhfneuc.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gtwbbwtyhv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.smart0.xyz/Article/details/gtbljxxmdk.html

[M05] 设置退出码
来源：http://dali.yuanzhike.top/Article/details/gtfexlcasu.html

Py:   sys.exit(1)
来源：http://dali.meibo888.top/Article/details/gtxiwjehwy.html

PHP:  exit(1);
来源：http://dali.jqgufenzy.top/Article/details/gtxajdhvdo.html

JS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtzddzwnlf.html

TS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtckmlzald.html

Java: System.exit(1)
来源：http://dali.hnqzz.top/Article/details/gthzvcjbkf.html

Go:   os.Exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtnwoboffv.html

Ruby: exit 1
来源：http://dali.andypj.xyz/Article/details/gtjditxleo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxuanxn.top/Article/details/gtfdabcwjk.html

[M06] 向标准错误输出
来源：http://dali.xinyue.icu/Article/details/gtghcyxtbq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ydzc1.top/Article/details/gtohfubcgr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zycfv.cn/Article/details/gtfpkvoacr.html

JS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gtbhpuhzvx.html

TS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gtlfhmvxkv.html

Java: System.err.println("err")
来源：http://dali.fzhhl.top/Article/details/gtwhbzfjuz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gtsarhbgpt.html

Ruby: warn "err"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwmqekit.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yongpay.top/Article/details/gtsyaawphz.html

[M07] 判断是否为主入口
来源：http://dali.9152youxi.cn/Article/details/gtylvgonqd.html

Py:   if __name__ == "__main__":
来源：http://dali.0kj1m.cn/Article/details/gtpvcbsvbk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.svipenyu.cn/Article/details/gtbulqdhnp.html

JS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gttsaaqbls.html

TS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gtzvxamqnp.html

Java: public static void main(String[] args)
来源：http://dali.daxiang520.top/Article/details/gtjgrogivo.html

Go:   func main()
来源：http://dali.tanke756.top/Article/details/gtnpoovneg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.meibo888.top/Article/details/gtplvchtbu.html

C#:   static void Main(string[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gtjmnshhrw.html

[M08] 获取系统与运行时信息
来源：http://dali.shuidangran.top/Article/details/gtfoimgasz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yvedp.cn/Article/details/gtoykujtmw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhoulong.xyz/Article/details/gtjrbivmyt.html

JS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gtqfjcjptr.html

TS:   process.platform;  process.version
来源：http://dali.gogol.net.cn/Article/details/gtjlqmknqs.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.9152youxi.cn/Article/details/gtcudjozio.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hfpthk.cn/Article/details/gtoebjyabl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazrxnoir.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dianchejie.cn/Article/details/gtuqnzzhmb.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtlmaipuav.html

N. 数据结构与算法
来源：http://dali.fengsongda.top/Article/details/gtvgmbkspr.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtdkbdbwmn.html

[N01] 二分查找（有序数组）
来源：http://dali.gotoacloud.top/Article/details/gtswoskxjc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ivvv.top/Article/details/gtrxeejtgb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ydzc1.top/Article/details/gtfzfeykxt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtpxnqajgz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gtuslbaacx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gthnhloqmu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtogweqdpa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dianchejie.cn/Article/details/gtwmuuhpxs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gtkgzftmmu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sxryk.cn/Article/details/gtvqubuwsa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtzjjiacpc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.birdmap.top/Article/details/gtfxhrknts.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gtnrjwpnie.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtqetzbqeh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tian-w.cn/Article/details/gtaarvuvkq.html

Go:   slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gtevfennkd.html

Ruby: arr.sort
来源：http://dali.guannengcc.top/Article/details/gtfumgpvgk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigfzy.top/Article/details/gtzuyvusfd.html

[N03] 快速排序（分治示例）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkovccnq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.vqdsnc.cn/Article/details/gtlvoiswnv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yanxiufei.cn/Article/details/gtvkbecfdj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gtbjsjvoke.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtxhgkoijy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pycfn.com/Article/details/gtwzbqsgvr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258888.top/Article/details/gtwontbbam.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pycfn.com/Article/details/gthjngadlb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.mhx1999.top/Article/details/gtfuaetxrk.html

[N04] 斐波那契数列
来源：http://dali.cashguo.top/Article/details/gtdpjpzgfq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.haohaochexian.top/Article/details/gtxhaftlvr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.birdmap.top/Article/details/gtejbtubnb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtqchnhadg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gtvvjusgwx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.havefunace.top/Article/details/gtmckqafze.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gogol.net.cn/Article/details/gtpzverjio.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gtsfjzrgtm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtaqsttgzc.html

[N05] 最大公约数
来源：http://dali.quarkkingdee.top/Article/details/gtcituaksr.html

Py:   math.gcd(a, b)
来源：http://dali.andypj.xyz/Article/details/gtqctdzuly.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daria6918.cn/Article/details/gtsybjwosn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.mhx1999.top/Article/details/gtajzfslqv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gtbbghmjlu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuetiantiany.cn/Article/details/gtsclqtctc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.birdmap.top/Article/details/gtcemwesee.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gtdralrxrj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cheryme.top/Article/details/gtluiohhlo.html

[N06] 判断回文字符串
来源：http://dali.kuanghao11.cn/Article/details/gtqrbfxaxx.html

Py:   s == s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gtznthjpxn.html

PHP:  $s === strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtmguirhsb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtanvyedmk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibvveqah.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tanke756.top/Article/details/gtsldufrzb.html

Go:   // 双指针从两端比较
来源：http://dali.guannengcc.top/Article/details/gtnmqymbkd.html

Ruby: s == s.reverse
来源：http://dali.tian-w.cn/Article/details/gtlyqboiup.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gtwflnpnar.html

[N07] 两数之和（返回下标）
来源：http://dali.zycfv.cn/Article/details/gtzuyjjmpx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.316326.xyz/Article/details/gtanwpxxpt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.havefunace.top/Article/details/gtplvwcbct.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtidrdfabx.html

TS:   // 手写 Map<string, number>
来源：http://dali.guannengcc.top/Article/details/gtplufjeby.html

Java: // 手写 HashMap
来源：http://dali.jlsjyb.cn/Article/details/gtjmeyhjcb.html

Go:   // 手写 map[int]int
来源：http://dali.meibo888.top/Article/details/gtmelarvxj.html

Ruby: // 手写 Hash
来源：http://dali.c1oappe.top/Article/details/gtnnxtpnzn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cashguo.top/Article/details/gtthwirfgd.html

[N08] 生成全排列
来源：http://dali.9152youxi.cn/Article/details/gtpidzlvfx.html

Py:   itertools.permutations(arr)
来源：http://dali.ydzc1.top/Article/details/gtllblldmr.html

PHP:  // 手写递归交换
来源：http://dali.hammf.cn/Article/details/gttjnpwcuv.html

JS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtljwaxmvj.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtffgpyzlt.html

Java: // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtvdkdqqle.html

Go:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtxciguhlz.html

Ruby: arr.permutation.to_a
来源：http://dali.zhongyouzk.top/Article/details/gtzgwyzoyl.html

C#:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtwcbjkmaf.html

[N09] 栈与队列
来源：http://dali.zhixingplan.top/Article/details/gtlvuahlfu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgfzy.top/Article/details/gtgplhnxpj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsawxvvw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtkhnpfzvk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yangfankeji.com/Article/details/gtzoouduzr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gtpsosufnb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ydzc1.top/Article/details/gtxdlluxkq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtrodaiyyl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnqzz.top/Article/details/gtkkpdixne.html

[N10] 链表节点定义
来源：http://dali.havefunace.top/Article/details/gthfnafryc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guannengcc.top/Article/details/gtdaovbzxp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aizwys.cn/Article/details/gtrjvpsgrk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gtfgpddlot.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.birdmap.top/Article/details/gtrnccloal.html

Java: class Node { int v; Node next; }
来源：http://dali.c1oappe.top/Article/details/gtuycrssrn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfafjvesc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zycfv.cn/Article/details/gthbialnbh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.snrcjt.cn/Article/details/gtolqyruxa.html

[N11] 二叉树中序遍历
来源：http://dali.meibo888.top/Article/details/gtebuivcvn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ivvv.top/Article/details/gtiinkihag.html

PHP:  // 手写递归函数
来源：http://dali.c1oappe.top/Article/details/gtxrbxvros.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shzxlz.cn/Article/details/gtuvshtmqy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gtfaekmmhh.html

Java: // 手写递归
来源：http://dali.meibo888.top/Article/details/gtvuyymrhn.html

Go:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gteblamgnn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sysykeji.top/Article/details/gtypepygss.html

C#:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gtigmvhdue.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.vqdsnc.cn/Article/details/gtidrxlewg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.dianchejie.cn/Article/details/gtejzfssqa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigufen.top/Article/details/gtjqesovcq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.9152youxi.cn/Article/details/gtaczjawwz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gtgfmtwdje.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gttnlirpnr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hysaishi.cn/Article/details/gtrvvvhuxu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gaohongyu789.top/Article/details/gtwkceinfe.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gtbxecskxo.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtrzmigccv.html

O. 并发与异步
来源：http://dali.birdmap.top/Article/details/gthumduqad.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gttcrzrwho.html

[O01] 启动一个线程
来源：http://dali.wangshuangyany.cn/Article/details/gtuwgbdprk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dianchejie.cn/Article/details/gtfswdvtpn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zycfv.cn/Article/details/gtcuqpiyic.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.mhx1999.top/Article/details/gtidtvncrn.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gtftouqzlc.html

Java: new Thread(() -> f()).start()
来源：http://dali.haohaochexian.top/Article/details/gtnmzsvgsi.html

Go:   go f()
来源：http://dali.haohaochexian.top/Article/details/gtelmtjfjz.html

Ruby: Thread.new { f }
来源：http://dali.yangfankeji.com/Article/details/gtgozlxcjq.html

C#:   Task.Run(() => F());
来源：http://dali.xinyue.icu/Article/details/gtlvxpsfhr.html

[O02] 使用线程池
来源：http://dali.jqgfzy.top/Article/details/gtdjcnqmuv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.pengpengdd.cyou/Article/details/gtyvzcbtuj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwadeean.html

JS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gtydwnpahw.html

TS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gtgtywzfgz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hywenlv.cn/Article/details/gtyljiqxle.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cucudq.cn/Article/details/gtgobunmlm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.redwolf501.top/Article/details/gtlumjhgwk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yongpay.top/Article/details/gtsfxygsrk.html

[O03] 加锁保护共享数据
来源：http://dali.xinyue.icu/Article/details/gtotzzscvr.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gtpxgazxew.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.svipenyu.cn/Article/details/gtsrhxkcas.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.daxiang520.top/Article/details/gtmiuaeqhi.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gtyijxricm.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtijpnssux.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daxiang520.top/Article/details/gtlprewvej.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gtbkctvhwa.html

C#:   lock (gate) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gtaepourkr.html

[O04] 定义异步函数并等待
来源：http://dali.nwbrower.top/Article/details/gtdfeeslzx.html

Py:   async def f():⏎    await g()
来源：http://dali.yuanzhike.top/Article/details/gtsjazfolv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cheryme.top/Article/details/gtrwvuqpad.html

JS:   async function f() { await g(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyrymczl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gthcmkluby.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zycfv.cn/Article/details/gtxzgewuvx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daxiang520.top/Article/details/gtntjsbfmx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhixingplan.top/Article/details/gtidwnldqs.html

C#:   async Task F() { await G(); }
来源：http://dali.tanke756.top/Article/details/gtoogykisb.html

[O05] 并发执行并等待全部完成
来源：http://dali.sxryk.cn/Article/details/gtngbjvtga.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtmuikfeds.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cheryme.top/Article/details/gteeiwdevk.html

JS:   await Promise.all(tasks)
来源：http://dali.yueranfly.top/Article/details/gtsfxmyakr.html

TS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtdusmjbga.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.316326.xyz/Article/details/gtyhxngtzp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgmlgdsr.html

Ruby: threads.map(&:join)
来源：http://dali.snrcjt.cn/Article/details/gtwhyovtpq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgjuelev.html

[O06] 使用进程池
来源：http://dali.sysykeji.top/Article/details/gtsugfrbbu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yueranfly.top/Article/details/gtpqoubccp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.andypj.xyz/Article/details/gtsqdjzoqi.html

JS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gtwlekycmd.html

TS:   // child_process / cluster 模块
来源：http://dali.wangdashe.top/Article/details/gtivbdvddg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrywrrdn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ivvv.top/Article/details/gtmmyyemih.html

Ruby: // fork 块
来源：http://dali.zhengqikj.top/Article/details/gtkigykjxq.html

C#:   Parallel.For
来源：http://dali.jiagoushi.top/Article/details/gtcuecwlfp.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtnfjnofcv.html

P. 常用工具函数
来源：http://dali.yj20258888.top/Article/details/gtfbxsxtua.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtosmrdhfk.html

[P01] 生成 UUID
来源：http://dali.aibaodan.cn/Article/details/gtdnfxxbuw.html

Py:   str(uuid.uuid4())
来源：http://dali.9152youxi.cn/Article/details/gtkmosiwgm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.birdmap.top/Article/details/gtutxfzkwj.html

JS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gtkwwoesbl.html

TS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtzvlecrfh.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangdashe.top/Article/details/gthgsmibad.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nwbrower.top/Article/details/gtlubxdtsr.html

Ruby: SecureRandom.uuid
来源：http://dali.hysaishi.cn/Article/details/gtncdwbjkn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.birdmap.top/Article/details/gtgfkgfvrx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhongyouzk.top/Article/details/gtwppddeou.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.0kj1m.cn/Article/details/gtqwxnbmzb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sufxvd.cn/Article/details/gtifidezyz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.fengsongda.top/Article/details/gtvnhumses.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhixingplan.top/Article/details/gtbpogaupd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258.top/Article/details/gtyedqzsiu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.iojbl.cn/Article/details/gthvmvcjqa.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tian-w.cn/Article/details/gtlcslngod.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daxiang520.top/Article/details/gtgcyujsbt.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gtlrjvttfq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhengqikj.top/Article/details/gtmoekxwfb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.vqdsnc.cn/Article/details/gtlhwlegpd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gtewgnyujo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jianghu66.top/Article/details/gttvrgwilj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuanzhike.top/Article/details/gtnmkuhhiz.html


<!-- 参考信息 -->