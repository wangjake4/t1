代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gt2ezmmccwt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sufxvd.cn/Article/details/gt2cctbevip.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yonumen.top/Article/details/gt2nycomnug.html

JS:   resp.ok;  resp.status
来源：http://dali.sufxvd.cn/Article/details/gt2zsmcqbaq.html

TS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gt2xgwesnad.html

Java: resp.statusCode()
来源：http://dali.sufxvd.cn/Article/details/gt2clostdwr.html

Go:   resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gt2pvyinmuu.html

Ruby: resp.code.to_i
来源：http://dali.9152youxi.cn/Article/details/gt2dwysutvo.html

C#:   (int)resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gt2syivafkr.html

[L08] 并发请求多个地址
来源：http://dali.zhixingplan.top/Article/details/gt2mvkjewgd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnqzz.top/Article/details/gt2ahbojrhm.html

PHP:  curl_multi_init() 系列
来源：http://dali.nwbrower.top/Article/details/gt2ltduhfbk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gt2ryoqxyac.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gt2ekvuwcqi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnxiangtu.top/Article/details/gt2ezirisfi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dianchejie.cn/Article/details/gt2geglkxqe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hvotaqww.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fengsongda.top/Article/details/gt2cgmbhgac.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2chjzbeis.html

M. 命令行 / 进程 / 环境
来源：http://dali.xylfe.cn/Article/details/gt2upbvilcs.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2fqjgyzxo.html

[M01] 读取命令行参数
来源：http://dali.hnqzz.top/Article/details/gt2htpqsmrl.html

Py:   sys.argv[1:]
来源：http://dali.xuanzx.com/Article/details/gt2mevqkqcu.html

PHP:  $argv;  $argc;
来源：http://dali.zhixingplan.top/Article/details/gt2ttuvxuzy.html

JS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gt2ymqkixdr.html

TS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gt2unzadrfo.html

Java: args 数组（main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gt2oylrzchp.html

Go:   os.Args[1:]
来源：http://dali.mhx1999.top/Article/details/gt2wxwjifpd.html

Ruby: ARGV
来源：http://dali.birdmap.top/Article/details/gt2eszddaeq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gt2lsfmknbr.html

[M02] 读取环境变量
来源：http://dali.havefunace.top/Article/details/gt2crgyxvgx.html

Py:   os.environ.get("HOME")
来源：http://dali.gotoacloud.top/Article/details/gt2yjbfhijr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gt2pafzmnfo.html

JS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gt2rzcxcasb.html

TS:   process.env.HOME
来源：http://dali.vqdsnc.cn/Article/details/gt2kwczvrxm.html

Java: System.getenv("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2smodghbw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2cfrgllje.html

Ruby: ENV["HOME"]
来源：http://dali.cheryme.top/Article/details/gt2vbnqtpjg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zdqjudy.top/Article/details/gt2yqcfkqxe.html

[M03] 执行外部命令
来源：http://dali.hfpthk.cn/Article/details/gt2nefvrekp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fengsongda.top/Article/details/gt2iginneqi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pycfn.com/Article/details/gt2kthgalgs.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gt2fkvcfpna.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zysuqufc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.haohaochexian.top/Article/details/gt2utlnnyaf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ppjwa.cn/Article/details/gt2fkxsncbx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgufenzy.top/Article/details/gt2ozepzvbv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sufxvd.cn/Article/details/gt2jhijmrrx.html

[M04] 获取当前工作目录
来源：http://dali.shuidangran.top/Article/details/gt2xbcmvfoe.html

Py:   os.getcwd()
来源：http://dali.jqgfzy.top/Article/details/gt2zeeeewdw.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gt2ysafbovp.html

JS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gt2qrvfzyog.html

TS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gt2laqhrniv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ydzc1.top/Article/details/gt2fsecxjxm.html

Go:   os.Getwd()
来源：http://dali.yvedp.cn/Article/details/gt2mkgnoawn.html

Ruby: Dir.pwd
来源：http://dali.jianghu66.top/Article/details/gt2ocvpmzrh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhongyouzk.top/Article/details/gt2trdqgeda.html

[M05] 设置退出码
来源：http://dali.cheryme.top/Article/details/gt2bcxjsqnv.html

Py:   sys.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2zvnsbcvk.html

PHP:  exit(1);
来源：http://dali.tianlin.xyz/Article/details/gt2ihsdilgp.html

JS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2wmblhpxy.html

TS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gt2ffvjazdz.html

Java: System.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2wzwyuaqz.html

Go:   os.Exit(1)
来源：http://dali.ppjwa.cn/Article/details/gt2ilnzhpbl.html

Ruby: exit 1
来源：http://dali.zhongyouzk.top/Article/details/gt2zlwdzibu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigufen.top/Article/details/gt2jkepqzes.html

[M06] 向标准错误输出
来源：http://dali.9152youxi.cn/Article/details/gt2ignilmru.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xziqi.cn/Article/details/gt2mqhttlna.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxinkj.top/Article/details/gt2cahuqyam.html

JS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gt2tzmmhcft.html

TS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gt2scfkczdu.html

Java: System.err.println("err")
来源：http://dali.zhengqikj.top/Article/details/gt2boeqinny.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhixingplan.top/Article/details/gt2skksxwcw.html

Ruby: warn "err"
来源：http://dali.jlsjyb.cn/Article/details/gt2qoqsllek.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnqzz.top/Article/details/gt2fpjrizyr.html

[M07] 判断是否为主入口
来源：http://dali.fzhhl.top/Article/details/gt2enooqazv.html

Py:   if __name__ == "__main__":
来源：http://dali.guowangkeji.top/Article/details/gt2wgyrinwt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ybcxt.top/Article/details/gt2qkgmewol.html

JS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gt2tazfslih.html

TS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gt2elmqjvwl.html

Java: public static void main(String[] args)
来源：http://dali.jinqigfzy.top/Article/details/gt2itkjmsou.html

Go:   func main()
来源：http://dali.fengsongda.top/Article/details/gt2kqypejqz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxinkj.top/Article/details/gt2typeiuij.html

C#:   static void Main(string[] args)
来源：http://dali.nwbrower.top/Article/details/gt2djtvpxwh.html

[M08] 获取系统与运行时信息
来源：http://dali.shangyingyoupin.top/Article/details/gt2fbxnxnpu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.quarkkingdee.top/Article/details/gt2xcwejbvl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.haohaochexian.top/Article/details/gt2lptgssrn.html

JS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gt2lwqhrvab.html

TS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gt2oafhpeqg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.quarkkingdee.top/Article/details/gt2iubafvjd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hongshengwenyu.top/Article/details/gt2njarlhro.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sweek.top/Article/details/gt2bskoloth.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxinkj.top/Article/details/gt2tcdthyzu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2gyszyrcx.html

N. 数据结构与算法
来源：http://dali.fengsongda.top/Article/details/gt2qzypuszm.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmswrynu.html

[N01] 二分查找（有序数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2afbuzlfa.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2vgagjukp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangdashe.top/Article/details/gt2idjgvail.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pbgasvnp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gt2vnnljwnl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gt2mbupfwsg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2yxcpgisc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yonumen.top/Article/details/gt2mlsuytds.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2tcosjxjf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gotoacloud.top/Article/details/gt2hguokqqy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gt2veiyemtv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenlongwang.top/Article/details/gt2bjqkayim.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gt2yqhuocag.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ryavkrnx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnxiangtu.top/Article/details/gt2srujebtg.html

Go:   slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gt2zdgfjirq.html

Ruby: arr.sort
来源：http://dali.bjfxy.top/Article/details/gt2bswmzipg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.iojbl.cn/Article/details/gt2jsxqhbnn.html

[N03] 快速排序（分治示例）
来源：http://dali.havefunace.top/Article/details/gt2feltgwnk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xziqi.cn/Article/details/gt2jgpmfqqd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenjidiqi.icu/Article/details/gt2ogazjshj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gt2aszwdbkx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gt2yhrccduy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.feifeiyinyue.top/Article/details/gt2wifgumdm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenlongwang.top/Article/details/gt2zamfibzg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhiwuduotai.top/Article/details/gt2tegxhcra.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shuidangran.top/Article/details/gt2dpquqklw.html

[N04] 斐波那契数列
来源：http://dali.hnxiangtu.top/Article/details/gt2kfszxmei.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qumisvbk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gt2sbdxdubm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gt2qzutjuir.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gt2hursciqj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gt2wqywvkpf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.havefunace.top/Article/details/gt2tzkjruwp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vauqrgmx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gt2rsvoezys.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2byxuqoct.html

Py:   math.gcd(a, b)
来源：http://dali.yonumen.top/Article/details/gt2fpivptxb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gogol.net.cn/Article/details/gt2xbwjpdfo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gt2ofcxfpno.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gt2cubizgfy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cqqwz.cn/Article/details/gt2hhomnwgr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.iojbl.cn/Article/details/gt2rzqtgpnh.html

Ruby: a.gcd(b)
来源：http://dali.ppjwa.cn/Article/details/gt2bshpvlve.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guannengcc.top/Article/details/gt2ueivmmmd.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnrwgrm.html

Py:   s == s[::-1]
来源：http://dali.mhx1999.top/Article/details/gt2oivlwqoc.html

PHP:  $s === strrev($s);
来源：http://dali.pycfn.com/Article/details/gt2rktsojsw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gt2prddhcdo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2fslcvzhs.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.quarkkingdee.top/Article/details/gt2ecxogivr.html

Go:   // 双指针从两端比较
来源：http://dali.meibo888.top/Article/details/gt2nfepidop.html

Ruby: s == s.reverse
来源：http://dali.quarkkingdee.top/Article/details/gt2gjveitfv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gt2ughgddlf.html

[N07] 两数之和（返回下标）
来源：http://dali.zhixingplan.top/Article/details/gt2xzlqbtuu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzrscauo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cucudq.cn/Article/details/gt2sdjpopnh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgfzy.top/Article/details/gt2rbvyhbwz.html

TS:   // 手写 Map<string, number>
来源：http://dali.cdnleiting.top/Article/details/gt2bfzfyjwv.html

Java: // 手写 HashMap
来源：http://dali.iojbl.cn/Article/details/gt2epofkbne.html

Go:   // 手写 map[int]int
来源：http://dali.sweek.top/Article/details/gt2afvlxkxk.html

Ruby: // 手写 Hash
来源：http://dali.wangdashe.top/Article/details/gt2wbmrouie.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fengsongda.top/Article/details/gt2lcsjllph.html

[N08] 生成全排列
来源：http://dali.svipenyu.cn/Article/details/gt2olnymgus.html

Py:   itertools.permutations(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2muppnfnf.html

PHP:  // 手写递归交换
来源：http://dali.daxiang520.top/Article/details/gt2uiqyzmlc.html

JS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2ycefznny.html

TS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2ahmcfrxq.html

Java: // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qvcfodiu.html

Go:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2eguaqbzj.html

Ruby: arr.permutation.to_a
来源：http://dali.yuxming.cn/Article/details/gt2kiuriuuz.html

C#:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2rnzkomis.html

[N09] 栈与队列
来源：http://dali.sysykeji.top/Article/details/gt2qktpfgvo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nwbrower.top/Article/details/gt2igqnixvj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.meibo888.top/Article/details/gt2upmgcepc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gt2uqmdjulf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yuxming.cn/Article/details/gt2qdnuhkfi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gt2tksnxyvw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hywenlv.cn/Article/details/gt2detuivji.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gt2kpkstlse.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gt2eylwjooz.html

[N10] 链表节点定义
来源：http://dali.gogol.net.cn/Article/details/gt2lrlvcjin.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.bjfxy.top/Article/details/gt2vhanfwmt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2noefoplx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigfzy.top/Article/details/gt2dlfzzwxw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.quarkkingdee.top/Article/details/gt2zjckvzgj.html

Java: class Node { int v; Node next; }
来源：http://dali.yuanzhike.top/Article/details/gt2sgbpbxxp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hywenlv.cn/Article/details/gt2tyxvbrns.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vdlcsxdw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hfpthk.cn/Article/details/gt2tntwqrgq.html

[N11] 二叉树中序遍历
来源：http://dali.iojbl.cn/Article/details/gt2thkjyaxn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gzhubu.top/Article/details/gt2nubmupks.html

PHP:  // 手写递归函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fvlkokcv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gt2jrqjjfja.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gt2gaofmrwh.html

Java: // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gt2bwjshfuz.html

Go:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gt2lvfqynwt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.daxiang520.top/Article/details/gt2deqhoavt.html

C#:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gt2tijeactb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ivvv.top/Article/details/gt2qyebtsoa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bxbepvty.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.andypj.xyz/Article/details/gt2slgchbiz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gt2aaulvyny.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gt2ehldljfb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gt2psntjksa.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cucudq.cn/Article/details/gt2dmogmwwr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.iojbl.cn/Article/details/gt2jfnukmix.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ivvv.top/Article/details/gt2cxhlmsaa.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2wctpuiuk.html

O. 并发与异步
来源：http://dali.cdnleiting.top/Article/details/gt2ebufurne.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2xsedshhz.html

[O01] 启动一个线程
来源：http://dali.jqgfzy.top/Article/details/gt2vdnlcwln.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yangfankeji.com/Article/details/gt2svqljoiq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.316326.xyz/Article/details/gt2fgkokpwv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cheryme.top/Article/details/gt2bemtxywk.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ccdtrula.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigufen.top/Article/details/gt2lagklqqq.html

Go:   go f()
来源：http://dali.gzhubu.top/Article/details/gt2ntoqkxas.html

Ruby: Thread.new { f }
来源：http://dali.jianghu66.top/Article/details/gt2sdlclccy.html

C#:   Task.Run(() => F());
来源：http://dali.yvedp.cn/Article/details/gt2pgninikp.html

[O02] 使用线程池
来源：http://dali.zhixingplan.top/Article/details/gt2bdfhabeb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wpvwjlca.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yuxming.cn/Article/details/gt2wqjtdcqw.html

JS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gt2ccahazmy.html

TS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gt2bmvslcdy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.birdmap.top/Article/details/gt2vrjiouie.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhengqikj.top/Article/details/gt2vnhjwjbt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenjidiqi.icu/Article/details/gt2porxekiu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ubkzivio.html

[O03] 加锁保护共享数据
来源：http://dali.zhongyouzk.top/Article/details/gt2utlipdka.html

Py:   with lock: shared += 1
来源：http://dali.jlsjyb.cn/Article/details/gt2jecquxqe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jianghu66.top/Article/details/gt2uvsjceqh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sysykeji.top/Article/details/gt2litdqbgi.html

TS:   // 同 JS
来源：http://dali.dianchejie.cn/Article/details/gt2mneytieb.html

Java: synchronized (this) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gt2hxkorliv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxuanxn.top/Article/details/gt2kvxtaaux.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuanzx.com/Article/details/gt2uanqcfhf.html

C#:   lock (gate) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gt2wgpbpgss.html

[O04] 定义异步函数并等待
来源：http://dali.wangshuangyany.cn/Article/details/gt2diaakzwo.html

Py:   async def f():⏎    await g()
来源：http://dali.hongshengwenyu.top/Article/details/gt2yjdischp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tian-w.cn/Article/details/gt2darqjfhs.html

JS:   async function f() { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vxmqwjsm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gt2ihuaahbk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.birdmap.top/Article/details/gt2drwjkgvw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.fzhhl.top/Article/details/gt2pqyptdno.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangshuangyany.cn/Article/details/gt2xhgcpwtg.html

C#:   async Task F() { await G(); }
来源：http://dali.ivvv.top/Article/details/gt2gmtbbsek.html

[O05] 并发执行并等待全部完成
来源：http://dali.yonumen.top/Article/details/gt2syoasexk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shzxlz.cn/Article/details/gt2zjgtvrlz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.meibo888.top/Article/details/gt2znsgzetb.html

JS:   await Promise.all(tasks)
来源：http://dali.tianlin.xyz/Article/details/gt2gniddibo.html

TS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gt2peyhozty.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.quarkkingdee.top/Article/details/gt2pawwqqxv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yangfankeji.com/Article/details/gt2votzwvuu.html

Ruby: threads.map(&:join)
来源：http://dali.tianlin.xyz/Article/details/gt2ajyfynib.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgfzy.top/Article/details/gt2pgosbnaw.html

[O06] 使用进程池
来源：http://dali.gzhubu.top/Article/details/gt2jupzfbhc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hywenlv.cn/Article/details/gt2wyxyzllj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hammf.cn/Article/details/gt2murrwqvt.html

JS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gt2azvejnll.html

TS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gt2ldgrdngg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258.top/Article/details/gt2vyhfqvhw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.redwolf501.top/Article/details/gt2mdqipxjd.html

Ruby: // fork 块
来源：http://dali.yj202588.top/Article/details/gt2eadtrjqc.html

C#:   Parallel.For
来源：http://dali.gzhubu.top/Article/details/gt2oczpmylz.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2bittkemb.html

P. 常用工具函数
来源：http://dali.gogol.net.cn/Article/details/gt2yqoboeeb.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2ezgalrvi.html

[P01] 生成 UUID
来源：http://dali.yonumen.top/Article/details/gt2dmfvaihg.html

Py:   str(uuid.uuid4())
来源：http://dali.yonumen.top/Article/details/gt2tyfveyqq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daxiang520.top/Article/details/gt2qnoqenrl.html

JS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gt2scmcxjdu.html

TS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gt2fcmlwwbh.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258.top/Article/details/gt2xqwzofph.html

Go:   // 用 github.com/google/uuid
来源：http://dali.meibo888.top/Article/details/gt2dyyjityx.html

Ruby: SecureRandom.uuid
来源：http://dali.yueranfly.top/Article/details/gt2qrjcryme.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hammf.cn/Article/details/gt2zoaoidhs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.bjfxy.top/Article/details/gt2ogleiuwl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258888.top/Article/details/gt2rhaqiayw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.haohaochexian.top/Article/details/gt2vdeefxrj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cashguo.top/Article/details/gt2hqyfgnty.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pcchzxgp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.andypj.xyz/Article/details/gt2pjajrfyw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenzaomai.com/Article/details/gt2gxtostmj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sweek.top/Article/details/gt2ebiqvowl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sufxvd.cn/Article/details/gt2rhmpuycu.html

[P03] 生成短随机字符串
来源：http://dali.cucudq.cn/Article/details/gt2xwyxbsmq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nvnyqqsd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcylhvk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gt2blxlpqkw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tgnnovtj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2ctexsssc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yueranfly.top/Article/details/gt2pchpwzpd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daria6918.cn/Article/details/gt2hcdkwtup.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cucudq.cn/Article/details/gt2pxjpewpt.html

[P04] 求长度
来源：http://dali.yanxiufei.cn/Article/details/gt2gladfxpb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ivvv.top/Article/details/gt2ccjvtkub.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gt2yxwcbhkj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gt2wytrsvdt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gt2hvcwchrg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yueranfly.top/Article/details/gt2bhzmyqxl.html

Go:   len(arr);  len(m)
来源：http://dali.yueranfly.top/Article/details/gt2kvtbvqjs.html

Ruby: x.length;  x.size
来源：http://dali.gogol.net.cn/Article/details/gt2maaxnmxr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fzhhl.top/Article/details/gt2aqcfcegs.html


<!-- 参考信息 -->