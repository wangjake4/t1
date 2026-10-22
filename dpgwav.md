代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtvswljwwt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.bjfxy.top/Article/details/gtukpyuxcc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dianchejie.cn/Article/details/gtmkljmrtm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhoulong.xyz/Article/details/gtvhzpjkby.html

[L07] 处理 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gtbotvlcsf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.quarkkingdee.top/Article/details/gtbyzcaylu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenzaomai.com/Article/details/gthpukfmfa.html

JS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gtippcqjtd.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtzpxjtmph.html

Java: resp.statusCode()
来源：http://dali.cqqwz.cn/Article/details/gtxflmsahu.html

Go:   resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gttsjtzvdm.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gtdclziaot.html

C#:   (int)resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gtjngwzogy.html

[L08] 并发请求多个地址
来源：http://dali.pycfn.com/Article/details/gthvisffwm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.0kj1m.cn/Article/details/gthhlrtfxk.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenjidiqi.icu/Article/details/gtrkopsflr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gtymowfoub.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtbffotonb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigufen.top/Article/details/gtuwhvevad.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hongshengwenyu.top/Article/details/gtdvwgbawk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gttmxguwxe.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfatzsxo.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtnhnicsea.html

M. 命令行 / 进程 / 环境
来源：http://dali.iojbl.cn/Article/details/gtqwvrhaar.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskvcvezs.html

[M01] 读取命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gtlciibhhf.html

Py:   sys.argv[1:]
来源：http://dali.dianchejie.cn/Article/details/gtowqhmqog.html

PHP:  $argv;  $argc;
来源：http://dali.yongpay.top/Article/details/gtncxfiivp.html

JS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gtwcouzwpd.html

TS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gtiheamlex.html

Java: args 数组（main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtbipwxlqc.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gtbnrrnxtd.html

Ruby: ARGV
来源：http://dali.yonumen.top/Article/details/gtrfysrdbk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gttgwurmoz.html

[M02] 读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gtaqdxxnqy.html

Py:   os.environ.get("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtbhxzmnre.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hammf.cn/Article/details/gtpyuyavsd.html

JS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gtpnwqwiod.html

TS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gtjinobxyz.html

Java: System.getenv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtxvhofepm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtjxpfezzt.html

Ruby: ENV["HOME"]
来源：http://dali.yanxiufei.cn/Article/details/gtzdgdhsgd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.c1oappe.top/Article/details/gtyxquoxfy.html

[M03] 执行外部命令
来源：http://dali.sufxvd.cn/Article/details/gtmislwujo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yangfankeji.com/Article/details/gtjwyaovip.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tianlin.xyz/Article/details/gtqlqljldu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtnieodiqj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gtcobpjukc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aizwys.cn/Article/details/gtigojmppf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.bjfxy.top/Article/details/gtlpjgazbc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuanzx.com/Article/details/gtblcfbkmt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aibaodan.cn/Article/details/gttwzososi.html

[M04] 获取当前工作目录
来源：http://dali.jiagoushi.top/Article/details/gtmrjicafq.html

Py:   os.getcwd()
来源：http://dali.zhoulong.xyz/Article/details/gtwterpmew.html

PHP:  getcwd();
来源：http://dali.xinyue.icu/Article/details/gtqpzzmiah.html

JS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gtxprwojlx.html

TS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gtldpdwevg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxinkj.top/Article/details/gtpccnamox.html

Go:   os.Getwd()
来源：http://dali.guannengcc.top/Article/details/gtwmkiscrf.html

Ruby: Dir.pwd
来源：http://dali.smart0.xyz/Article/details/gtrhwrivzg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yanxiufei.cn/Article/details/gtyxxdcbia.html

[M05] 设置退出码
来源：http://dali.jinqigufen.top/Article/details/gtyicouzuq.html

Py:   sys.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtjxugnsvw.html

PHP:  exit(1);
来源：http://dali.aizwys.cn/Article/details/gtmlzocywi.html

JS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtjbhcvmja.html

TS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gtsjydzipd.html

Java: System.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtatoyrbfv.html

Go:   os.Exit(1)
来源：http://dali.jyoumei.cn/Article/details/gthqxaxgqt.html

Ruby: exit 1
来源：http://dali.pengpengdd.cyou/Article/details/gtawmzgfpx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258.top/Article/details/gtfvpxovjn.html

[M06] 向标准错误输出
来源：http://dali.cheryme.top/Article/details/gtdlyspvme.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guannengcc.top/Article/details/gtippowysp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zycfv.cn/Article/details/gtggtdvkbd.html

JS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtzjtqkwmo.html

TS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gtlcrvtmku.html

Java: System.err.println("err")
来源：http://dali.jiagoushi.top/Article/details/gtyyvyrbbn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangshuangyany.cn/Article/details/gtcmssmppg.html

Ruby: warn "err"
来源：http://dali.yongpay.top/Article/details/gtazbnanho.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gttqcuqweq.html

[M07] 判断是否为主入口
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpjljyhg.html

Py:   if __name__ == "__main__":
来源：http://dali.jiagoushi.top/Article/details/gtyecswegp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenjidiqi.icu/Article/details/gtajdxqakc.html

JS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gtpnddnvbd.html

TS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gtxcqjiana.html

Java: public static void main(String[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkirfsmj.html

Go:   func main()
来源：http://dali.gogol.net.cn/Article/details/gtcwqbwrcm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnqzz.top/Article/details/gtdsrlfidj.html

C#:   static void Main(string[] args)
来源：http://dali.tianlin.xyz/Article/details/gtshysetwr.html

[M08] 获取系统与运行时信息
来源：http://dali.nwbrower.top/Article/details/gtljixcebj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.svipenyu.cn/Article/details/gttdiwysrt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cqqwz.cn/Article/details/gthgqsmocj.html

JS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gtgqaryvec.html

TS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gthcponpxt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cheryme.top/Article/details/gthhamhvhk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gtmraqgqck.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.iojbl.cn/Article/details/gtfnztfpkb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daria6918.cn/Article/details/gtwxsvibnd.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtogfejgow.html

N. 数据结构与算法
来源：http://dali.tanke756.top/Article/details/gtzzpyossg.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtacbhtaon.html

[N01] 二分查找（有序数组）
来源：http://dali.fzhhl.top/Article/details/gtrynizncd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtuwoycevl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ydzc1.top/Article/details/gtkzbswoqr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gtthpjdeks.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtwtdbuvdp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gttcgbrbfq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtzykgrjhl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.andypj.xyz/Article/details/gtcyyaejzy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gtghwsvcjh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yonumen.top/Article/details/gtlfupmhta.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tianlin.xyz/Article/details/gteglbgloq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.quarkkingdee.top/Article/details/gtqxnbeiwn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtcojpjaxn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gtvquoinun.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.haohaochexian.top/Article/details/gtbistejrb.html

Go:   slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtsopniugx.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gtpruruivl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.svipenyu.cn/Article/details/gtwnvbvlhg.html

[N03] 快速排序（分治示例）
来源：http://dali.ydzc1.top/Article/details/gtnkvtxwbb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gtmdzxuaqx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.smart0.xyz/Article/details/gttpxeyved.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gtxmcdllpt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gtcxktbeqs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hysaishi.cn/Article/details/gtsvwzsxlu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigufen.top/Article/details/gtcowvhudt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258888.top/Article/details/gtlhexlhjk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gzhubu.top/Article/details/gtrlruqsjv.html

[N04] 斐波那契数列
来源：http://dali.pycfn.com/Article/details/gtousktikt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnxiangtu.top/Article/details/gtrmjxijmh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtqerknqaj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtgibdyaym.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtobngmhmk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtnztbvdqb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yongpay.top/Article/details/gtmqstyccq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gtjaeahmha.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gthazxebwz.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gtyfqyeslk.html

Py:   math.gcd(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtqlezoqdn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shuidangran.top/Article/details/gtibghrqra.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gthtfjfxcl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ppjwa.cn/Article/details/gtgeszucag.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyubxpuhz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnqzz.top/Article/details/gtdrkcbfeo.html

Ruby: a.gcd(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtaprqlefy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yangfankeji.com/Article/details/gtrgqgmiix.html

[N06] 判断回文字符串
来源：http://dali.daria6918.cn/Article/details/gtjwzjmxbe.html

Py:   s == s[::-1]
来源：http://dali.yonumen.top/Article/details/gtpstfmhld.html

PHP:  $s === strrev($s);
来源：http://dali.xziqi.cn/Article/details/gtnhyybibu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtqirukmuy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtakkvxfdg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xziqi.cn/Article/details/gtmfuzqihf.html

Go:   // 双指针从两端比较
来源：http://dali.aibaodan.cn/Article/details/gtzssmjanr.html

Ruby: s == s.reverse
来源：http://dali.cheryme.top/Article/details/gtupzojkcc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gtmghtelhw.html

[N07] 两数之和（返回下标）
来源：http://dali.cqqwz.cn/Article/details/gtkelwsuar.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tian-w.cn/Article/details/gtlfjbimcm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yonumen.top/Article/details/gtfiiyyrzx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shangyingyoupin.top/Article/details/gtpzgtcjnh.html

TS:   // 手写 Map<string, number>
来源：http://dali.bjfxy.top/Article/details/gtufgzlinf.html

Java: // 手写 HashMap
来源：http://dali.yuanzhike.top/Article/details/gtclyzdzrm.html

Go:   // 手写 map[int]int
来源：http://dali.jyoumei.cn/Article/details/gtlnnflypz.html

Ruby: // 手写 Hash
来源：http://dali.quarkkingdee.top/Article/details/gtbzoxvlcu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yvedp.cn/Article/details/gtrhnotnoi.html

[N08] 生成全排列
来源：http://dali.quarkkingdee.top/Article/details/gtetxlftuw.html

Py:   itertools.permutations(arr)
来源：http://dali.yuxming.cn/Article/details/gtlsdqwqhc.html

PHP:  // 手写递归交换
来源：http://dali.sweek.top/Article/details/gtfzkmxrtz.html

JS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtjjwwljaf.html

TS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtyhrsjlcg.html

Java: // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtjdteaqva.html

Go:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtgymvysyn.html

Ruby: arr.permutation.to_a
来源：http://dali.cucudq.cn/Article/details/gtxwvvjpib.html

C#:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtkrqahziw.html

[N09] 栈与队列
来源：http://dali.iojbl.cn/Article/details/gtgtfparsj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrtysnds.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.fzhhl.top/Article/details/gtknrrbaqt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gtknsrvxlw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.c1oappe.top/Article/details/gtixmlxiqi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yvedp.cn/Article/details/gtpknlpmvb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.0kj1m.cn/Article/details/gtwhozonuv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtcnrdimtp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258888.top/Article/details/gtrfwjwlbf.html

[N10] 链表节点定义
来源：http://dali.shuidangran.top/Article/details/gtfcrvaxld.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hammf.cn/Article/details/gtijgtaxqy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cashguo.top/Article/details/gtncpimasg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.smart0.xyz/Article/details/gtrdaempig.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dashuyun.cn/Article/details/gteecyzofd.html

Java: class Node { int v; Node next; }
来源：http://dali.bjfxy.top/Article/details/gtyxqqfswh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yanxiufei.cn/Article/details/gtnmjjokan.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xinyue.icu/Article/details/gtsxlfdmuj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tanke756.top/Article/details/gtkakxnpcd.html

[N11] 二叉树中序遍历
来源：http://dali.dianchejie.cn/Article/details/gtqlktkqan.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ppjwa.cn/Article/details/gtcagnyesh.html

PHP:  // 手写递归函数
来源：http://dali.fzhhl.top/Article/details/gtukevnwmb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknjfpwnn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gtfbohqkfr.html

Java: // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtekphctjv.html

Go:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gtbsxrmjgo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.c1oappe.top/Article/details/gttdldtfla.html

C#:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtknyxqiyy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cheryme.top/Article/details/gtvdsxspdj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aizwys.cn/Article/details/gtvynkzgxw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ivvv.top/Article/details/gtsejkxhrm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtpiheqbiu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gtljkdnwdp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gtvbqwenkg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj202588.top/Article/details/gtemosukjj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hammf.cn/Article/details/gtuonwqzpw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gtcbrllynm.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtksknmuav.html

O. 并发与异步
来源：http://dali.yvedp.cn/Article/details/gtckdvazqg.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtjvogomzp.html

[O01] 启动一个线程
来源：http://dali.gzhubu.top/Article/details/gtubofhcxq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xylfe.cn/Article/details/gtjlgsgkxo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenzaomai.com/Article/details/gtzbulhmre.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.dianchejie.cn/Article/details/gtftdmlchp.html

TS:   // 同 JS
来源：http://dali.gzhubu.top/Article/details/gtynmlsrzt.html

Java: new Thread(() -> f()).start()
来源：http://dali.ppjwa.cn/Article/details/gtkregxfqd.html

Go:   go f()
来源：http://dali.zhixingplan.top/Article/details/gtjavfnedu.html

Ruby: Thread.new { f }
来源：http://dali.xinyue.icu/Article/details/gtlvfucshi.html

C#:   Task.Run(() => F());
来源：http://dali.bjfxy.top/Article/details/gthxroeybu.html

[O02] 使用线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtialijqce.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhongyouzk.top/Article/details/gtptqgozjz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258888.top/Article/details/gtjahowzob.html

JS:   // worker_threads 线程池
来源：http://dali.snrcjt.cn/Article/details/gtopkmvfvo.html

TS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gtewuysbji.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ydzc1.top/Article/details/gtjkhyrntl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgduwfyw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaujmfbka.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigufen.top/Article/details/gteyjzqfvu.html

[O03] 加锁保护共享数据
来源：http://dali.fengsongda.top/Article/details/gtfrtiyvll.html

Py:   with lock: shared += 1
来源：http://dali.jqgufenzy.top/Article/details/gtrghdikvr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sweek.top/Article/details/gtcxmtieps.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sysykeji.top/Article/details/gtytuuiikc.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gtmxfnnbpq.html

Java: synchronized (this) { shared++; }
来源：http://dali.dashuyun.cn/Article/details/gtujxfyyss.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sysykeji.top/Article/details/gtitoceisa.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgufenzy.top/Article/details/gtkhwxlomn.html

C#:   lock (gate) { shared++; }
来源：http://dali.shuidangran.top/Article/details/gtwysowesl.html

[O04] 定义异步函数并等待
来源：http://dali.gogol.net.cn/Article/details/gtbwgbmmma.html

Py:   async def f():⏎    await g()
来源：http://dali.hfpthk.cn/Article/details/gtnkcoxdvu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ydzc1.top/Article/details/gtqbgbddqd.html

JS:   async function f() { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtudfjnbiy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.c1oappe.top/Article/details/gtdyyoayfd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258888.top/Article/details/gtnymkptmq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258888.top/Article/details/gtptcczryh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yueranfly.top/Article/details/gtexlbbngz.html

C#:   async Task F() { await G(); }
来源：http://dali.ehwqpu.com/Article/details/gtckosbzuq.html

[O05] 并发执行并等待全部完成
来源：http://dali.pengpengdd.cyou/Article/details/gtsonzqxmb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xziqi.cn/Article/details/gtbpqcieds.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shanyushiyangtech.top/Article/details/gtufcovjsp.html

JS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gtgpktnvci.html

TS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gtskvbybfb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxinkj.top/Article/details/gtjyodgqud.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258888.top/Article/details/gtjyzuovsd.html

Ruby: threads.map(&:join)
来源：http://dali.bjfxy.top/Article/details/gtqxmnfxjp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.vqdsnc.cn/Article/details/gtlzqbrqwj.html

[O06] 使用进程池
来源：http://dali.cdnleiting.top/Article/details/gtqffhyloq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daxiang520.top/Article/details/gtvwnkmfet.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daria6918.cn/Article/details/gteekhwipo.html

JS:   // child_process / cluster 模块
来源：http://dali.hnqzz.top/Article/details/gtrvnawxrc.html

TS:   // child_process / cluster 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpgynfbt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ppjwa.cn/Article/details/gtlyybvzga.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guannengcc.top/Article/details/gtgayuoscw.html

Ruby: // fork 块
来源：http://dali.aibaodan.cn/Article/details/gtdhquxxhy.html

C#:   Parallel.For
来源：http://dali.iojbl.cn/Article/details/gtyopylcob.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtekroawis.html

P. 常用工具函数
来源：http://dali.wangshuangyany.cn/Article/details/gtmxfvooly.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtwlpfqrxf.html

[P01] 生成 UUID
来源：http://dali.ybcxt.top/Article/details/gtejhbkfts.html

Py:   str(uuid.uuid4())
来源：http://dali.yangfankeji.com/Article/details/gtudwbxtfn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj202588.top/Article/details/gthhctjnil.html

JS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtdfwmsfhc.html

TS:   crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gtjcojccjg.html

Java: UUID.randomUUID().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtyhoimhde.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ppjwa.cn/Article/details/gtvvadhssz.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigufen.top/Article/details/gtmlhkcghw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shangyingyoupin.top/Article/details/gthqieaibr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hysaishi.cn/Article/details/gtsaxvfeoh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.vqdsnc.cn/Article/details/gtrewgmats.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xylfe.cn/Article/details/gtbgzzqdfv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aibaodan.cn/Article/details/gtmaqmytux.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yvedp.cn/Article/details/gtjphzdxyu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenzaomai.com/Article/details/gtrnsrfrnv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gtjwvpdvny.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yueranfly.top/Article/details/gtjdjlqbhx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nwbrower.top/Article/details/gtlvhdsrpz.html

[P03] 生成短随机字符串
来源：http://dali.aibaodan.cn/Article/details/gthaveonwq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sweek.top/Article/details/gtxqimaqkl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.9152youxi.cn/Article/details/gtgqarvxlc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gtavktdfja.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtuutzcasu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sweek.top/Article/details/gtbnpmgdbx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hysaishi.cn/Article/details/gtjcdvrkpb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.0kj1m.cn/Article/details/gtdeglrkuq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gzhubu.top/Article/details/gteyxusznw.html

[P04] 求长度
来源：http://dali.snrcjt.cn/Article/details/gtbachucwh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.bjfxy.top/Article/details/gtzlayajsu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtnxbxqqbn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gtgucpmitu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenzaomai.com/Article/details/gtcmawakmk.html


<!-- 参考信息 -->