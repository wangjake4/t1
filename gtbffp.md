代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gt2xwoyhizs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yuuqhxif.html

Ruby: JSON.parse(resp.body)
来源：http://dali.andypj.xyz/Article/details/gt2ohyelckh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nwbrower.top/Article/details/gt2eyjnnlss.html

[L07] 处理 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gt2bcragwlg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.9152youxi.cn/Article/details/gt2jwiqqmnl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zycfv.cn/Article/details/gt2dqtxxwkc.html

JS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iyqrumul.html

TS:   resp.ok;  resp.status
来源：http://dali.sufxvd.cn/Article/details/gt2hyaolacn.html

Java: resp.statusCode()
来源：http://dali.pengpengdd.cyou/Article/details/gt2nilizbtn.html

Go:   resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gt2bemkcmjf.html

Ruby: resp.code.to_i
来源：http://dali.ybcxt.top/Article/details/gt2ipapknwm.html

C#:   (int)resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gt2lyghwcwd.html

[L08] 并发请求多个地址
来源：http://dali.guannengcc.top/Article/details/gt2kbygtvre.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenzaomai.com/Article/details/gt2jcotlnyz.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigfzy.top/Article/details/gt2igiddser.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gt2imljqibn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gt2yqlvtbpa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258888.top/Article/details/gt2uqwijujr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pengpengdd.cyou/Article/details/gt2nnpmggth.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cucudq.cn/Article/details/gt2lrltmxun.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shzxlz.cn/Article/details/gt2rjeqsokj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2jtfagozh.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnqzz.top/Article/details/gt2hodlclti.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2xveaythe.html

[M01] 读取命令行参数
来源：http://dali.pycfn.com/Article/details/gt2livzfibs.html

Py:   sys.argv[1:]
来源：http://dali.tian-w.cn/Article/details/gt2xacmbsei.html

PHP:  $argv;  $argc;
来源：http://dali.tianlin.xyz/Article/details/gt2cdryunmp.html

JS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gt2bkkeivuk.html

TS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gt2czickmyf.html

Java: args 数组（main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gt2mzicemwj.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gt2dqmrgxyb.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gt2zuzlrjna.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dianchejie.cn/Article/details/gt2ytjszoiv.html

[M02] 读取环境变量
来源：http://dali.quarkkingdee.top/Article/details/gt2fwacuqnq.html

Py:   os.environ.get("HOME")
来源：http://dali.sxryk.cn/Article/details/gt2vhiugfbp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gt2neuucexl.html

JS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gt2pskqgdco.html

TS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gt2lzskrunc.html

Java: System.getenv("HOME")
来源：http://dali.iojbl.cn/Article/details/gt2ipmlvunh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gt2wubgxjjt.html

Ruby: ENV["HOME"]
来源：http://dali.xziqi.cn/Article/details/gt2zjqtzidw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gt2duoyydxq.html

[M03] 执行外部命令
来源：http://dali.jianghu66.top/Article/details/gt2adevyrza.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daria6918.cn/Article/details/gt2vjmcadlm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guannengcc.top/Article/details/gt2xnbpipci.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gt2fngsbwsk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gt2wudkhhyw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigufen.top/Article/details/gt2thzwxasn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fzhhl.top/Article/details/gt2dugvoppu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnxiangtu.top/Article/details/gt2hyprqelu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gzhubu.top/Article/details/gt2necqvbfh.html

[M04] 获取当前工作目录
来源：http://dali.jinqigufen.top/Article/details/gt2cybbyytm.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gt2sqgszhxn.html

PHP:  getcwd();
来源：http://dali.yangfankeji.com/Article/details/gt2nmutcmev.html

JS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gt2jlvufmpw.html

TS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gt2yatnjqjb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cashguo.top/Article/details/gt2tbctkkdj.html

Go:   os.Getwd()
来源：http://dali.jqgfzy.top/Article/details/gt2kxthubom.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gt2zejqtzah.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ydzc1.top/Article/details/gt2rrshxasc.html

[M05] 设置退出码
来源：http://dali.yongpay.top/Article/details/gt2iozmdpjp.html

Py:   sys.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dxcojobf.html

PHP:  exit(1);
来源：http://dali.jianghu66.top/Article/details/gt2tekjfkua.html

JS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgojakzv.html

TS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2qvsjuvbx.html

Java: System.exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2yplzvxnz.html

Go:   os.Exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2hhxoketv.html

Ruby: exit 1
来源：http://dali.yvedp.cn/Article/details/gt2undxepjh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.quarkkingdee.top/Article/details/gt2cocbxrmh.html

[M06] 向标准错误输出
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rgpzqvqd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hfpthk.cn/Article/details/gt2ponumvuz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhengqikj.top/Article/details/gt2udnkpail.html

JS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gt2lezxhrvl.html

TS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gt2pvkinxdm.html

Java: System.err.println("err")
来源：http://dali.cdnleiting.top/Article/details/gt2ivgpmiqg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sweek.top/Article/details/gt2eurwizcv.html

Ruby: warn "err"
来源：http://dali.gaohongyu789.top/Article/details/gt2bexitqiz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sufxvd.cn/Article/details/gt2budlbqld.html

[M07] 判断是否为主入口
来源：http://dali.sysykeji.top/Article/details/gt2lwdhpkbg.html

Py:   if __name__ == "__main__":
来源：http://dali.bjfxy.top/Article/details/gt2hmjwqoah.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sxryk.cn/Article/details/gt2qmidexns.html

JS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aunekevx.html

TS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gt2qmbeixnc.html

Java: public static void main(String[] args)
来源：http://dali.jqgufenzy.top/Article/details/gt2osjlocxf.html

Go:   func main()
来源：http://dali.guannengcc.top/Article/details/gt2ktiipmuu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yangfankeji.com/Article/details/gt2coakmhjt.html

C#:   static void Main(string[] args)
来源：http://dali.jqgufenzy.top/Article/details/gt2yecjprqc.html

[M08] 获取系统与运行时信息
来源：http://dali.zhoulong.xyz/Article/details/gt2ebdnwnjr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.iojbl.cn/Article/details/gt2ufdqojmx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenjidiqi.icu/Article/details/gt2dqzuotdx.html

JS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ypdisxpl.html

TS:   process.platform;  process.version
来源：http://dali.sufxvd.cn/Article/details/gt2iltquqxu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuxming.cn/Article/details/gt2gneqxhth.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sufxvd.cn/Article/details/gt2bccafeoy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gzhubu.top/Article/details/gt2fgvkzxwq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yonumen.top/Article/details/gt2ruuaidhw.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2wivjdwzq.html

N. 数据结构与算法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2exvtafki.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2urxupsnd.html

[N01] 二分查找（有序数组）
来源：http://dali.pengpengdd.cyou/Article/details/gt2jvfkmpxz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2xthplipg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kbskgcym.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gt2brgwtoyc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gt2upyojhdi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2awkrmywc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sweek.top/Article/details/gt2mgvdxujm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ydzc1.top/Article/details/gt2jjwbzyza.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2zczmzdwu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gzhubu.top/Article/details/gt2jumgybrp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gt2vdfuhaxw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fzhhl.top/Article/details/gt2dpvtvvwz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gt2tyylgwff.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gt2vtvhbzqt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigfzy.top/Article/details/gt2znjjuwox.html

Go:   slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gt2penywuew.html

Ruby: arr.sort
来源：http://dali.shzxlz.cn/Article/details/gt2pfiubffv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.mhx1999.top/Article/details/gt2vilinnwl.html

[N03] 快速排序（分治示例）
来源：http://dali.ivvv.top/Article/details/gt2hhuinoui.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aibaodan.cn/Article/details/gt2ssonhrxr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuanzx.com/Article/details/gt2llpfvygb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gt2ddplxtva.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gt2ewlziwkt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xylfe.cn/Article/details/gt2kkgcprdn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jlsjyb.cn/Article/details/gt2tqqsietk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gaohongyu789.top/Article/details/gt2msvikrlb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.birdmap.top/Article/details/gt2pujmcdtm.html

[N04] 斐波那契数列
来源：http://dali.hongshengwenyu.top/Article/details/gt2odbrsaxz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pnvocqwo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gt2pvqnvqyy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2zdbkexgp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gt2ulxgleyy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gt2iagvzveq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2maxzejku.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gt2bgirhunq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gt2kskkkawj.html

[N05] 最大公约数
来源：http://dali.vqdsnc.cn/Article/details/gt2rrdzubwj.html

Py:   math.gcd(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2evdgltrj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.0kj1m.cn/Article/details/gt2aillncbw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gt2aakemrlw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gt2uoscudsv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.vqdsnc.cn/Article/details/gt2uqhihnqc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2emifyggo.html

Ruby: a.gcd(b)
来源：http://dali.chenzaomai.com/Article/details/gt2mvlwqzsf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigfzy.top/Article/details/gt2vpdskjpo.html

[N06] 判断回文字符串
来源：http://dali.hysaishi.cn/Article/details/gt2rojjzywa.html

Py:   s == s[::-1]
来源：http://dali.fengsongda.top/Article/details/gt2bknnwvsh.html

PHP:  $s === strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gt2zztfqsoj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2hduugjtj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gt2wdmywwdo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.fzhhl.top/Article/details/gt2yguppzms.html

Go:   // 双指针从两端比较
来源：http://dali.yangfankeji.com/Article/details/gt2qhzqrnus.html

Ruby: s == s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gt2mqkallwa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gt2ionxztxg.html

[N07] 两数之和（返回下标）
来源：http://dali.snrcjt.cn/Article/details/gt2kdnfpfsz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fypfvvnb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj202588.top/Article/details/gt2qntuovfn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnqzz.top/Article/details/gt2ucerbpdi.html

TS:   // 手写 Map<string, number>
来源：http://dali.ppjwa.cn/Article/details/gt2usjioyeh.html

Java: // 手写 HashMap
来源：http://dali.sxryk.cn/Article/details/gt2dkodeezl.html

Go:   // 手写 map[int]int
来源：http://dali.cqqwz.cn/Article/details/gt2fhzlfsiv.html

Ruby: // 手写 Hash
来源：http://dali.wangshuangyany.cn/Article/details/gt2lhbrkikg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jiagoushi.top/Article/details/gt2hwoylwvw.html

[N08] 生成全排列
来源：http://dali.hfpthk.cn/Article/details/gt2qbsuzbki.html

Py:   itertools.permutations(arr)
来源：http://dali.hammf.cn/Article/details/gt2kcxquoam.html

PHP:  // 手写递归交换
来源：http://dali.sysykeji.top/Article/details/gt2fogmsrdm.html

JS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gt2fnypvskn.html

TS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2uskbxwpn.html

Java: // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gt2gamedhdb.html

Go:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2obotyirn.html

Ruby: arr.permutation.to_a
来源：http://dali.hammf.cn/Article/details/gt2gwofzgoo.html

C#:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gt2heggkbon.html

[N09] 栈与队列
来源：http://dali.yuanzhike.top/Article/details/gt2fwqnhrmn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fzhhl.top/Article/details/gt2vdvprhrw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daxiang520.top/Article/details/gt2hhjoymek.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuanzx.com/Article/details/gt2guraozap.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258888.top/Article/details/gt2hqemkdcu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jianghu66.top/Article/details/gt2fwpgslvi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jneycqrg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gt2nywgzqgr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.guowangkeji.top/Article/details/gt2luizpypx.html

[N10] 链表节点定义
来源：http://dali.feifeiyinyue.top/Article/details/gt2omcpjjlx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yueranfly.top/Article/details/gt2giuewuqw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgufenzy.top/Article/details/gt2biteqemk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jpmplanj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guowangkeji.top/Article/details/gt2pyobvoec.html

Java: class Node { int v; Node next; }
来源：http://dali.yanxiufei.cn/Article/details/gt2urcppqcn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangshuangyany.cn/Article/details/gt2orlnuuze.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sweek.top/Article/details/gt2rvsytpum.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cashguo.top/Article/details/gt2nxkzbumg.html

[N11] 二叉树中序遍历
来源：http://dali.pycfn.com/Article/details/gt2rmdjinmz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yueranfly.top/Article/details/gt2ondyomfb.html

PHP:  // 手写递归函数
来源：http://dali.chenlongwang.top/Article/details/gt2aozgfqwq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.bjfxy.top/Article/details/gt2wxdfkcsl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gt2xwjosito.html

Java: // 手写递归
来源：http://dali.bjfxy.top/Article/details/gt2rrmqgfjs.html

Go:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gt2zfkugzcr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pycfn.com/Article/details/gt2yjvndzwh.html

C#:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gt2dyfaxafr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.316326.xyz/Article/details/gt2rtrgbgaj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pengpengdd.cyou/Article/details/gt2vcwxmier.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ydzc1.top/Article/details/gt2ffvfwtle.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gt2fefdxykh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhengqikj.top/Article/details/gt2mbbqrfcy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dianchejie.cn/Article/details/gt2upqdrtre.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigfzy.top/Article/details/gt2ckvlirvu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2flxloxyb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gt2tzjheigv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2oxkqnmsn.html

O. 并发与异步
来源：http://dali.haohaochexian.top/Article/details/gt2qaigcctc.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2abalyxen.html

[O01] 启动一个线程
来源：http://dali.fengsongda.top/Article/details/gt2wekukrrd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yanxiufei.cn/Article/details/gt2wcntgryg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2afvukmyl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hongshengwenyu.top/Article/details/gt2lggnwesg.html

TS:   // 同 JS
来源：http://dali.chenzaomai.com/Article/details/gt2hqhowtbm.html

Java: new Thread(() -> f()).start()
来源：http://dali.hywenlv.cn/Article/details/gt2rlrboalf.html

Go:   go f()
来源：http://dali.yanxiufei.cn/Article/details/gt2grrxykss.html

Ruby: Thread.new { f }
来源：http://dali.birdmap.top/Article/details/gt2nbzddqxf.html

C#:   Task.Run(() => F());
来源：http://dali.quarkkingdee.top/Article/details/gt2tssimkav.html

[O02] 使用线程池
来源：http://dali.xuetiantiany.cn/Article/details/gt2phdluftb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gt2qfatwfgu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gogol.net.cn/Article/details/gt2qesituwp.html

JS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gt2azfdcjjx.html

TS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cahgsjqe.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dianchejie.cn/Article/details/gt2vwcydyom.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinqigufen.top/Article/details/gt2icmgppbk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.birdmap.top/Article/details/gt2wpcwrzyo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nanxinkj.top/Article/details/gt2oqxmivbo.html

[O03] 加锁保护共享数据
来源：http://dali.daxiang520.top/Article/details/gt2ojtdarcq.html

Py:   with lock: shared += 1
来源：http://dali.gotoacloud.top/Article/details/gt2azqyibll.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rnsrvlyy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.316326.xyz/Article/details/gt2zecnqhxp.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gt2rwrlzqdt.html

Java: synchronized (this) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gt2yibegbje.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuanzhike.top/Article/details/gt2osaesljo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yangfankeji.com/Article/details/gt2heludfto.html

C#:   lock (gate) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ycsxbqqt.html

[O04] 定义异步函数并等待
来源：http://dali.cheryme.top/Article/details/gt2xmlcupsz.html

Py:   async def f():⏎    await g()
来源：http://dali.chenlongwang.top/Article/details/gt2atbsgaao.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tian-w.cn/Article/details/gt2plhtnlim.html

JS:   async function f() { await g(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vxhbmgbi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnqzz.top/Article/details/gt2mytjrboy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xuetiantiany.cn/Article/details/gt2xwufvpre.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cucudq.cn/Article/details/gt2fkkqncyw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.0kj1m.cn/Article/details/gt2syurzmxj.html

C#:   async Task F() { await G(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2xtfjtizi.html

[O05] 并发执行并等待全部完成
来源：http://dali.birdmap.top/Article/details/gt2rhoegdrc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.guowangkeji.top/Article/details/gt2itfjtpzz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dianchejie.cn/Article/details/gt2kzgdwdkc.html

JS:   await Promise.all(tasks)
来源：http://dali.vqdsnc.cn/Article/details/gt2qxyiuynp.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gt2myjhihox.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shuidangran.top/Article/details/gt2fafjfqxm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgufenzy.top/Article/details/gt2loaxnuqa.html

Ruby: threads.map(&:join)
来源：http://dali.havefunace.top/Article/details/gt2xkjyjgzw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jlsjyb.cn/Article/details/gt2aqvvalez.html

[O06] 使用进程池
来源：http://dali.yongpay.top/Article/details/gt2okenwied.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2whdsizls.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sxryk.cn/Article/details/gt2qibqrfin.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2grulxwsz.html

TS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bojnubxk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zicqitsf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.haohaochexian.top/Article/details/gt2dqjhviys.html

Ruby: // fork 块
来源：http://dali.hammf.cn/Article/details/gt2ugigowyf.html

C#:   Parallel.For
来源：http://dali.dianchejie.cn/Article/details/gt2eisemccd.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2prbsmbvi.html

P. 常用工具函数
来源：http://dali.9152youxi.cn/Article/details/gt2qgmvlylu.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2qwacatsc.html

[P01] 生成 UUID
来源：http://dali.zhoulong.xyz/Article/details/gt2gtqehpjf.html

Py:   str(uuid.uuid4())
来源：http://dali.zdqjudy.top/Article/details/gt2nsjuastx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangdashe.top/Article/details/gt2tiytbhlg.html

JS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gt2qemyeeir.html

TS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gt2tsgpzifa.html

Java: UUID.randomUUID().toString()
来源：http://dali.fzhhl.top/Article/details/gt2cpsjxehw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nwbrower.top/Article/details/gt2yqbdgrxs.html

Ruby: SecureRandom.uuid
来源：http://dali.hysaishi.cn/Article/details/gt2ltwuhjrb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zqxfmkdi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.havefunace.top/Article/details/gt2izliaeus.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenjidiqi.icu/Article/details/gt2rfbbpayc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tanke756.top/Article/details/gt2gtpudhsw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ydzc1.top/Article/details/gt2nvdhdxha.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxinkj.top/Article/details/gt2bevrbwuf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.bjfxy.top/Article/details/gt2ecvmtipb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.316326.xyz/Article/details/gt2ktvhdshy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.guannengcc.top/Article/details/gt2ywqzjrsc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ydzc1.top/Article/details/gt2topxdren.html

[P03] 生成短随机字符串
来源：http://dali.zycfv.cn/Article/details/gt2prdnmxlp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gogol.net.cn/Article/details/gt2fuqyomnq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hfpthk.cn/Article/details/gt2alycsjiy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gt2vviiuqgq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gt2syudibuf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2ijbbjfbh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nanxuanxn.top/Article/details/gt2rkgpzmdp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuanzx.com/Article/details/gt2sdafaxyj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lcovwlhw.html

[P04] 求长度
来源：http://dali.9152youxi.cn/Article/details/gt2uomaulkt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hongshengwenyu.top/Article/details/gt2qsrvlhxk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gt2ccunlgsg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gt2mintonvx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gt2xzsytgdf.html


<!-- 参考信息 -->