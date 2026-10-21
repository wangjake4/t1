代发 wailian999

Py:   resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtvbjeflst.html

PHP:  json_decode($body, true);
来源：http://dali.316326.xyz/Article/details/gtgyqkgtdb.html

JS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gtikerzzzn.html

TS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtybxtcwin.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtnrxmdqmq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ydzc1.top/Article/details/gtknpqiouo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dianchejie.cn/Article/details/gtzsrzjnbg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aibaodan.cn/Article/details/gtruxyivid.html

[L07] 处理 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gtwidhgacr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yueranfly.top/Article/details/gtdcogdnow.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydtwctqv.html

JS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gtajhlyobg.html

TS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gtqtbipekh.html

Java: resp.statusCode()
来源：http://dali.guowangkeji.top/Article/details/gtobilmsni.html

Go:   resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gtsjihavkp.html

Ruby: resp.code.to_i
来源：http://dali.nanxinkj.top/Article/details/gtkfkrhhms.html

C#:   (int)resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gtryxminie.html

[L08] 并发请求多个地址
来源：http://dali.fzhhl.top/Article/details/gtuxnoohsi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shuidangran.top/Article/details/gtwmpaaxhg.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkkhvupf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gtahphwart.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtbniyzylx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.vqdsnc.cn/Article/details/gtsoqewajz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dashuyun.cn/Article/details/gtqrnilfef.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj202588.top/Article/details/gtnbqehqxi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.svipenyu.cn/Article/details/gtxrppdvvx.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtbirmlhsp.html

M. 命令行 / 进程 / 环境
来源：http://dali.andypj.xyz/Article/details/gtkivibsnk.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtekbzlqer.html

[M01] 读取命令行参数
来源：http://dali.nanxinkj.top/Article/details/gtnmmxzbxp.html

Py:   sys.argv[1:]
来源：http://dali.cheryme.top/Article/details/gthvhdlhtx.html

PHP:  $argv;  $argc;
来源：http://dali.hywenlv.cn/Article/details/gtqmgcnkfh.html

JS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtlwpaelmr.html

TS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gtuxcnuifu.html

Java: args 数组（main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gtcfcizpno.html

Go:   os.Args[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrdrqrdu.html

Ruby: ARGV
来源：http://dali.zhixingplan.top/Article/details/gtcdqvxyto.html

C#:   args 数组（Main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gtkhhqgulk.html

[M02] 读取环境变量
来源：http://dali.xinyue.icu/Article/details/gtnafirjof.html

Py:   os.environ.get("HOME")
来源：http://dali.yonumen.top/Article/details/gthseiegdd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtpckixinz.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtorpwyzeu.html

TS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtvxuldopq.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtgnjifkcy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.c1oappe.top/Article/details/gtxtpmzelv.html

Ruby: ENV["HOME"]
来源：http://dali.ybcxt.top/Article/details/gtuinzgrln.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtwswrgtab.html

[M03] 执行外部命令
来源：http://dali.hongshengwenyu.top/Article/details/gtfodxarlf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tian-w.cn/Article/details/gtfvczproh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yongpay.top/Article/details/gtbciruwnf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtdtvrjpiq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gtvqabmsfs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xinyue.icu/Article/details/gtlxkgdxqv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pycfn.com/Article/details/gtfosstfko.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cucudq.cn/Article/details/gtlrrhqdcs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.feifeiyinyue.top/Article/details/gtsuykwsnp.html

[M04] 获取当前工作目录
来源：http://dali.yuanzhike.top/Article/details/gtbbkbxcbq.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwmaahekh.html

PHP:  getcwd();
来源：http://dali.chenlongwang.top/Article/details/gtjygvxafs.html

JS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gtcbwrnoyd.html

TS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gtbhfdwjdp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.0kj1m.cn/Article/details/gtjvwspgiu.html

Go:   os.Getwd()
来源：http://dali.hywenlv.cn/Article/details/gtuaiplfcf.html

Ruby: Dir.pwd
来源：http://dali.hammf.cn/Article/details/gtrbhxstvu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhiwuduotai.top/Article/details/gtkfwedvyr.html

[M05] 设置退出码
来源：http://dali.jinqigufen.top/Article/details/gtmrnzvoah.html

Py:   sys.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtezagdzln.html

PHP:  exit(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvnpqrpk.html

JS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtrifdtquc.html

TS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtfxvtnkgm.html

Java: System.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtqndqqwdr.html

Go:   os.Exit(1)
来源：http://dali.yvedp.cn/Article/details/gtdstuwaar.html

Ruby: exit 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwrekuxd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuanzhike.top/Article/details/gtoxrurmda.html

[M06] 向标准错误输出
来源：http://dali.jqgufenzy.top/Article/details/gteuczyyxz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gtyyreoaue.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cucudq.cn/Article/details/gtrsyhkpwm.html

JS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gtfcgvpeds.html

TS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gtytiygdiy.html

Java: System.err.println("err")
来源：http://dali.redwolf501.top/Article/details/gtmapxduxi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jianghu66.top/Article/details/gtcilxprty.html

Ruby: warn "err"
来源：http://dali.daxiang520.top/Article/details/gtdtneysib.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daria6918.cn/Article/details/gtodfnlryw.html

[M07] 判断是否为主入口
来源：http://dali.jianghu66.top/Article/details/gtktbbdyhv.html

Py:   if __name__ == "__main__":
来源：http://dali.andypj.xyz/Article/details/gtpgphoewn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jianghu66.top/Article/details/gtacwcivlx.html

JS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gtzoqunppy.html

TS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gtagvmgowv.html

Java: public static void main(String[] args)
来源：http://dali.gogol.net.cn/Article/details/gtgsiiesee.html

Go:   func main()
来源：http://dali.jqgufenzy.top/Article/details/gtghngrbvl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.feifeiyinyue.top/Article/details/gtwobumyfq.html

C#:   static void Main(string[] args)
来源：http://dali.kuanghao11.cn/Article/details/gthsnjuhak.html

[M08] 获取系统与运行时信息
来源：http://dali.pycfn.com/Article/details/gtpyaoiqcv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhixingplan.top/Article/details/gtekpzfodq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guowangkeji.top/Article/details/gtidggpevx.html

JS:   process.platform;  process.version
来源：http://dali.zhixingplan.top/Article/details/gtjdczdofe.html

TS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gtbqyrbixu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.0kj1m.cn/Article/details/gtsxygaipw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hfpthk.cn/Article/details/gtzmfvlsjf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yonumen.top/Article/details/gtgpdwceni.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujipgvvx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtjfwbbhyz.html

N. 数据结构与算法
来源：http://dali.ybcxt.top/Article/details/gtcyshcyjm.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gthpndgsly.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxinkj.top/Article/details/gtwflfbocb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj20258.top/Article/details/gtylztzrof.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ydzc1.top/Article/details/gtuddyywqd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gtaxauwmmj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yueranfly.top/Article/details/gtvquzgvml.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gttgpsxqgc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtpsqxsfmq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhoulong.xyz/Article/details/gtstelwmhp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtvtdruqea.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aizwys.cn/Article/details/gtjsrpggbe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gtiuxbysve.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yvedp.cn/Article/details/gtammpqnwo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gtlpvuvylh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtqhoxytlu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.feifeiyinyue.top/Article/details/gtlnyknwkp.html

Go:   slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtzeftacne.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gtqcmjmied.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zycfv.cn/Article/details/gtxzctfdws.html

[N03] 快速排序（分治示例）
来源：http://dali.ppjwa.cn/Article/details/gthwifprhy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dianchejie.cn/Article/details/gtptitugrl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tianlin.xyz/Article/details/gthqsjvkxi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gtehptgack.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gtoxcbauce.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtsnrtbzqu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.svipenyu.cn/Article/details/gtdrmzlqua.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hysaishi.cn/Article/details/gtemjozuvu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yongpay.top/Article/details/gtjiufqgdd.html

[N04] 斐波那契数列
来源：http://dali.cucudq.cn/Article/details/gtszimzjaj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gteneazzxk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwntdrjbg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gtvxcbdxxr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gtiebsdffu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.mhx1999.top/Article/details/gtiovhzzpe.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yonumen.top/Article/details/gtuejtauwj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hnqzz.top/Article/details/gtpemvlaqo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtihqaumbf.html

[N05] 最大公约数
来源：http://dali.zhoulong.xyz/Article/details/gtseqsripj.html

Py:   math.gcd(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtsrgwubnq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfsqgfzpl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnqzz.top/Article/details/gtqpfwcmzn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gtcnpvopkb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pycfn.com/Article/details/gtceabtxdi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.iojbl.cn/Article/details/gtallypqro.html

Ruby: a.gcd(b)
来源：http://dali.hywenlv.cn/Article/details/gtehpkatsq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.kuanghao11.cn/Article/details/gtlezkksro.html

[N06] 判断回文字符串
来源：http://dali.nwbrower.top/Article/details/gtzfsyykwd.html

Py:   s == s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gtczoowood.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gtxthamldd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtthbgbfuo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtarbggsok.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sxryk.cn/Article/details/gtufkbtumy.html

Go:   // 双指针从两端比较
来源：http://dali.xziqi.cn/Article/details/gtcqohdxhc.html

Ruby: s == s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtmcxtgikl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gtajqrygil.html

[N07] 两数之和（返回下标）
来源：http://dali.cucudq.cn/Article/details/gtarcpozhu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrgnsjva.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jlsjyb.cn/Article/details/gtujqrtqkt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yangfankeji.com/Article/details/gtwdhtwzlw.html

TS:   // 手写 Map<string, number>
来源：http://dali.guowangkeji.top/Article/details/gtzuhvteya.html

Java: // 手写 HashMap
来源：http://dali.316326.xyz/Article/details/gtkxqfkngf.html

Go:   // 手写 map[int]int
来源：http://dali.xylfe.cn/Article/details/gtegmplmln.html

Ruby: // 手写 Hash
来源：http://dali.andypj.xyz/Article/details/gtytjzouvu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hongshengwenyu.top/Article/details/gtohtcmets.html

[N08] 生成全排列
来源：http://dali.ppjwa.cn/Article/details/gtabiqyfzs.html

Py:   itertools.permutations(arr)
来源：http://dali.yonumen.top/Article/details/gtvhgmjovg.html

PHP:  // 手写递归交换
来源：http://dali.sxryk.cn/Article/details/gtmctlfnxw.html

JS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtxxahaioi.html

TS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtzyemzbgg.html

Java: // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtrjgivihr.html

Go:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtajgnmiox.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gtzzeaqfin.html

C#:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtphmrjdro.html

[N09] 栈与队列
来源：http://dali.yj20258888.top/Article/details/gtrvhjdhgq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtfgcvepqo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtpmocybzo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gtjzhbnmkz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cucudq.cn/Article/details/gtkjjewotj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shangyingyoupin.top/Article/details/gtpnyvadnu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yongpay.top/Article/details/gtexctowfm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtywdsiuya.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbcasiix.html

[N10] 链表节点定义
来源：http://dali.yanxiufei.cn/Article/details/gthmuhyuvk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrkadyai.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dianchejie.cn/Article/details/gtmgeccihh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aibaodan.cn/Article/details/gtovjwincj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.c1oappe.top/Article/details/gtbievubaj.html

Java: class Node { int v; Node next; }
来源：http://dali.ppjwa.cn/Article/details/gtozovrynd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ybcxt.top/Article/details/gthadotmiw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.9152youxi.cn/Article/details/gtfvkeqgmn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xuanzx.com/Article/details/gtgqinfyia.html

[N11] 二叉树中序遍历
来源：http://dali.aibaodan.cn/Article/details/gtzhvrcxjx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnaawylk.html

PHP:  // 手写递归函数
来源：http://dali.shuidangran.top/Article/details/gtkkezculw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gtwzncwheq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj202588.top/Article/details/gtagedgmeb.html

Java: // 手写递归
来源：http://dali.hammf.cn/Article/details/gtesiagwel.html

Go:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasgqaysl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgufenzy.top/Article/details/gtrpscjlft.html

C#:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtjvfvzhwx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqanrgstx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangshuangyany.cn/Article/details/gtfwqqtegu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.havefunace.top/Article/details/gtvwiwadto.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gtcpuuumkc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gtwfakwijw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.kuanghao11.cn/Article/details/gtscjgjozc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daria6918.cn/Article/details/gtdtesjepa.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwexdimgu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gtehzmqbnh.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtdvpprcwm.html

O. 并发与异步
来源：http://dali.shanyushiyangkeji.top/Article/details/gteagvmryl.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtqqgrcjpz.html

[O01] 启动一个线程
来源：http://dali.yj20258.top/Article/details/gttajzawnr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuanzx.com/Article/details/gtmphbjlpb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shuidangran.top/Article/details/gtbkhelyxz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.aizwys.cn/Article/details/gthbzvzbsj.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgshshet.html

Java: new Thread(() -> f()).start()
来源：http://dali.fzhhl.top/Article/details/gttykrcbnb.html

Go:   go f()
来源：http://dali.nwbrower.top/Article/details/gtchyjswyl.html

Ruby: Thread.new { f }
来源：http://dali.0kj1m.cn/Article/details/gtgysutznr.html

C#:   Task.Run(() => F());
来源：http://dali.birdmap.top/Article/details/gtwnlexxmw.html

[O02] 使用线程池
来源：http://dali.mhx1999.top/Article/details/gtfgjwclcj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchijcpqn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.iojbl.cn/Article/details/gttdmgwngd.html

JS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gtvkoomzaa.html

TS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gtccbwdner.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.9152youxi.cn/Article/details/gtvqjtnmcw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenzaomai.com/Article/details/gtzplvafix.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.0kj1m.cn/Article/details/gtfqnsroys.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yanxiufei.cn/Article/details/gtwghpebvs.html

[O03] 加锁保护共享数据
来源：http://dali.xziqi.cn/Article/details/gtevbdxszs.html

Py:   with lock: shared += 1
来源：http://dali.xylfe.cn/Article/details/gtklolfsiz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.quarkkingdee.top/Article/details/gtfkkmarzv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.vqdsnc.cn/Article/details/gtedxyowxn.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gtwmeujdcs.html

Java: synchronized (this) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gtjvlixvtp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cashguo.top/Article/details/gtzgwplwdt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zycfv.cn/Article/details/gtqjcbfnqh.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj202588.top/Article/details/gttvpjohsy.html

[O04] 定义异步函数并等待
来源：http://dali.jianghu66.top/Article/details/gtjidrnrjd.html

Py:   async def f():⏎    await g()
来源：http://dali.feifeiyinyue.top/Article/details/gtcjeayphv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.birdmap.top/Article/details/gtlnpfuceq.html

JS:   async function f() { await g(); }
来源：http://dali.bjfxy.top/Article/details/gtfblqlkhx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nwbrower.top/Article/details/gtfnmytzgv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gtzxxegnpe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydhgzxvx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.bjfxy.top/Article/details/gtgdxcsfch.html

C#:   async Task F() { await G(); }
来源：http://dali.0kj1m.cn/Article/details/gthnvunfel.html

[O05] 并发执行并等待全部完成
来源：http://dali.cqqwz.cn/Article/details/gtxxdobkye.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ivvv.top/Article/details/gtxojtqwsc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xylfe.cn/Article/details/gtvsxlfphg.html

JS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gtivcbbgju.html

TS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gtyjydngvu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shuidangran.top/Article/details/gtjfhqxfbk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hfpthk.cn/Article/details/gtddxjdkxt.html

Ruby: threads.map(&:join)
来源：http://dali.sysykeji.top/Article/details/gtdbfsykol.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.redwolf501.top/Article/details/gtqkoumzzp.html

[O06] 使用进程池
来源：http://dali.quarkkingdee.top/Article/details/gtxxrnokmt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jyoumei.cn/Article/details/gtvqligkdw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cqqwz.cn/Article/details/gtavunoelm.html

JS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gtioxtnbhf.html

TS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gtynvnmbwa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.vqdsnc.cn/Article/details/gtshmgfcbr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.pengpengdd.cyou/Article/details/gtldhftzas.html

Ruby: // fork 块
来源：http://dali.hywenlv.cn/Article/details/gtnpkpqvgb.html

C#:   Parallel.For
来源：http://dali.sufxvd.cn/Article/details/gtcfarivir.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtxuzrgohz.html

P. 常用工具函数
来源：http://dali.yonumen.top/Article/details/gtxnnkcgef.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtyojqplkk.html

[P01] 生成 UUID
来源：http://dali.zhiwuduotai.top/Article/details/gtzjtplwuo.html

Py:   str(uuid.uuid4())
来源：http://dali.ybcxt.top/Article/details/gtcikzwawy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aizwys.cn/Article/details/gtxqzfqpki.html

JS:   crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gtktvwvoer.html

TS:   crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gtofghteix.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenzaomai.com/Article/details/gtuqybjplb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guowangkeji.top/Article/details/gtmqspdedn.html

Ruby: SecureRandom.uuid
来源：http://dali.ehwqpu.com/Article/details/gthipfyoud.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258888.top/Article/details/gtnhkhnvbq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuanzhike.top/Article/details/gtdoocsdfj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zycfv.cn/Article/details/gtvmjtcift.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxrkliox.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangdashe.top/Article/details/gtzkavtuho.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsongenxw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdtqrikk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmeompqod.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhoulong.xyz/Article/details/gtqdzpnyzq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jyoumei.cn/Article/details/gtdkiuydie.html

[P03] 生成短随机字符串
来源：http://dali.0kj1m.cn/Article/details/gttvvfkbcu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.snrcjt.cn/Article/details/gtwgiaziis.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jyoumei.cn/Article/details/gtoktoujem.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tanke756.top/Article/details/gtvijmxlfa.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigufen.top/Article/details/gtybtjthzy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shuidangran.top/Article/details/gtiervfdwu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhoulong.xyz/Article/details/gtkzjvwslp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.mhx1999.top/Article/details/gtghscixsa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gogol.net.cn/Article/details/gtdhdgzzdz.html

[P04] 求长度
来源：http://dali.tianlin.xyz/Article/details/gtjcnubveb.html


<!-- 参考信息 -->