代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gt2erpitefj.html

Java: resp.statusCode()
来源：http://dali.yangfankeji.com/Article/details/gt2fbgxxfba.html

Go:   resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gt2tteuysii.html

Ruby: resp.code.to_i
来源：http://dali.chenjidiqi.icu/Article/details/gt2iktzeqjt.html

C#:   (int)resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jxttvdgq.html

[L08] 并发请求多个地址
来源：http://dali.kuanghao11.cn/Article/details/gt2isuaxnms.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yvedp.cn/Article/details/gt2uyurjciu.html

PHP:  curl_multi_init() 系列
来源：http://dali.cqqwz.cn/Article/details/gt2mltatuwi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gt2oqojiins.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gt2bpwueaxn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dashuyun.cn/Article/details/gt2ussvulim.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cqqwz.cn/Article/details/gt2xecnirtc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zsehidlz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.birdmap.top/Article/details/gt2kgetszmo.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2wpkumzcz.html

M. 命令行 / 进程 / 环境
来源：http://dali.sxryk.cn/Article/details/gt2hhfbihwr.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2kqwvgzfa.html

[M01] 读取命令行参数
来源：http://dali.pycfn.com/Article/details/gt2mnzfyque.html

Py:   sys.argv[1:]
来源：http://dali.vqdsnc.cn/Article/details/gt2gexbmfgc.html

PHP:  $argv;  $argc;
来源：http://dali.cheryme.top/Article/details/gt2cqaviari.html

JS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gt2tzahqcde.html

TS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gt2hfnurgvi.html

Java: args 数组（main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gt2qhghccti.html

Go:   os.Args[1:]
来源：http://dali.hfpthk.cn/Article/details/gt2jecdgpux.html

Ruby: ARGV
来源：http://dali.hfpthk.cn/Article/details/gt2qhgteoxt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gt2dlcjmbpa.html

[M02] 读取环境变量
来源：http://dali.daria6918.cn/Article/details/gt2ejdetpnf.html

Py:   os.environ.get("HOME")
来源：http://dali.aizwys.cn/Article/details/gt2pwjgvsna.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gt2kgvgejqz.html

JS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gt2lpnzgbxw.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gt2jrnliztf.html

Java: System.getenv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gt2bsecwkzc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gt2qytlohqh.html

Ruby: ENV["HOME"]
来源：http://dali.mhx1999.top/Article/details/gt2mudikwcu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gotoacloud.top/Article/details/gt2fkezeoew.html

[M03] 执行外部命令
来源：http://dali.zycfv.cn/Article/details/gt2gfayihwp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tian-w.cn/Article/details/gt2kojsbhdb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gzhubu.top/Article/details/gt2jzgugnau.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gt2qgtnufxn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2sqiejhoi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guowangkeji.top/Article/details/gt2qqwvlqyq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dashuyun.cn/Article/details/gt2ntyvzyzu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cqqwz.cn/Article/details/gt2bhusxnsu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2txupomjy.html

[M04] 获取当前工作目录
来源：http://dali.hongshengwenyu.top/Article/details/gt2yctgpdsy.html

Py:   os.getcwd()
来源：http://dali.sxryk.cn/Article/details/gt2xqleaous.html

PHP:  getcwd();
来源：http://dali.bjfxy.top/Article/details/gt2ajvncffz.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfaxekg.html

TS:   process.cwd()
来源：http://dali.jianghu66.top/Article/details/gt2qawsbnzc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxinkj.top/Article/details/gt2dyxcymdt.html

Go:   os.Getwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wwpufwrt.html

Ruby: Dir.pwd
来源：http://dali.yj20258.top/Article/details/gt2pcpssgeb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sxryk.cn/Article/details/gt2rnwhvndr.html

[M05] 设置退出码
来源：http://dali.jyoumei.cn/Article/details/gt2vbarokgg.html

Py:   sys.exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2tadlelra.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gt2kokgzrqk.html

JS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2hcwmuiqa.html

TS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2hmabrutr.html

Java: System.exit(1)
来源：http://dali.guannengcc.top/Article/details/gt2dtpobnjp.html

Go:   os.Exit(1)
来源：http://dali.gogol.net.cn/Article/details/gt2jknbuodn.html

Ruby: exit 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2qtizlles.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jyamczmh.html

[M06] 向标准错误输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2myugsruy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gt2apijdcqc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigfzy.top/Article/details/gt2rilvdejk.html

JS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gt2swhmndld.html

TS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gt2kstasbvb.html

Java: System.err.println("err")
来源：http://dali.zycfv.cn/Article/details/gt2tgabbple.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxuanxn.top/Article/details/gt2rpfwkbiq.html

Ruby: warn "err"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dieutuvj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sysykeji.top/Article/details/gt2kanvzone.html

[M07] 判断是否为主入口
来源：http://dali.tianlin.xyz/Article/details/gt2pyeklxqp.html

Py:   if __name__ == "__main__":
来源：http://dali.zdqjudy.top/Article/details/gt2oppqvqqo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cashguo.top/Article/details/gt2sxtqurme.html

JS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gt2gtcxlwyg.html

TS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gt2rmklexcy.html

Java: public static void main(String[] args)
来源：http://dali.gotoacloud.top/Article/details/gt2dcweiwtf.html

Go:   func main()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fummzvar.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhengqikj.top/Article/details/gt2ucxyxrmc.html

C#:   static void Main(string[] args)
来源：http://dali.jyoumei.cn/Article/details/gt2eofynmea.html

[M08] 获取系统与运行时信息
来源：http://dali.xylfe.cn/Article/details/gt2hqvmdwyo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hfpthk.cn/Article/details/gt2effjpkzi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.birdmap.top/Article/details/gt2cbspxmrt.html

JS:   process.platform;  process.version
来源：http://dali.yuanzhike.top/Article/details/gt2pwqzogrd.html

TS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gt2jxlxpcaf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cheryme.top/Article/details/gt2gpethlkp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.andypj.xyz/Article/details/gt2zoelhzve.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dianchejie.cn/Article/details/gt2zlowcubm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuxming.cn/Article/details/gt2tiuzkpcj.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2sdqckmvo.html

N. 数据结构与算法
来源：http://dali.jianghu66.top/Article/details/gt2gfjvhyst.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2wpfogzne.html

[N01] 二分查找（有序数组）
来源：http://dali.hywenlv.cn/Article/details/gt2cktmklzg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2iayhofhl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ydzc1.top/Article/details/gt2tehtuwje.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gt2bjvrrkak.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gt2inlmagur.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bsexcbbs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2ovyvsjch.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xinyue.icu/Article/details/gt2impuccuf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2qosmpkhz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgfzy.top/Article/details/gt2ilcicvjf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gt2clnmuqfs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2laisimqp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gt2ichthdtr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gt2zkegzzqz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guowangkeji.top/Article/details/gt2aeqraksz.html

Go:   slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2jumbyepo.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gt2tcupqgfu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cheryme.top/Article/details/gt2avgmfvzr.html

[N03] 快速排序（分治示例）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ytpbekmj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.kuanghao11.cn/Article/details/gt2lsfaebtp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tianlin.xyz/Article/details/gt2aprnxsii.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gt2trmdhtxp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gt2pszancqp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yueranfly.top/Article/details/gt2ozimvhco.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhongyouzk.top/Article/details/gt2sbsdntlt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zdqjudy.top/Article/details/gt2udwdgxhh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jiagoushi.top/Article/details/gt2ykaqlnkg.html

[N04] 斐波那契数列
来源：http://dali.ivvv.top/Article/details/gt2gplskdqm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gt2qczumxmc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gt2csyjoxdd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gt2pvituumw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2hxltepbk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.havefunace.top/Article/details/gt2bojjbtzk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cucudq.cn/Article/details/gt2taokudxv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gt2aitrjply.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2heyxxhsv.html

[N05] 最大公约数
来源：http://dali.daxiang520.top/Article/details/gt2tvcokxxs.html

Py:   math.gcd(a, b)
来源：http://dali.bjfxy.top/Article/details/gt2asnxpsyj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daxiang520.top/Article/details/gt2tztxnrvv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.c1oappe.top/Article/details/gt2hgcvdvrz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gt2xuuzxgjy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jyoumei.cn/Article/details/gt2cwhhghmb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ehwqpu.com/Article/details/gt2bsraukog.html

Ruby: a.gcd(b)
来源：http://dali.xziqi.cn/Article/details/gt2blsomkxq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nanxuanxn.top/Article/details/gt2egugdkzx.html

[N06] 判断回文字符串
来源：http://dali.tianlin.xyz/Article/details/gt2sifohttj.html

Py:   s == s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gt2zhoomjpg.html

PHP:  $s === strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2idfrohwv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gt2eceuwagb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2atsoffio.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.316326.xyz/Article/details/gt2dvintiml.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zoymjjdz.html

Ruby: s == s.reverse
来源：http://dali.zhongyouzk.top/Article/details/gt2vheuovdw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gt2hfljpdvg.html

[N07] 两数之和（返回下标）
来源：http://dali.hongshengwenyu.top/Article/details/gt2eqblokti.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gaohongyu789.top/Article/details/gt2tdafuhwg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jsalavmj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhiwuduotai.top/Article/details/gt2okfvsiyv.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuanzhike.top/Article/details/gt2ctletqtg.html

Java: // 手写 HashMap
来源：http://dali.jinqigfzy.top/Article/details/gt2ltvyrzly.html

Go:   // 手写 map[int]int
来源：http://dali.hongshengwenyu.top/Article/details/gt2wfinlnid.html

Ruby: // 手写 Hash
来源：http://dali.jinqigufen.top/Article/details/gt2rqvsbzun.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ignwzzvv.html

[N08] 生成全排列
来源：http://dali.guowangkeji.top/Article/details/gt2vxdoyogw.html

Py:   itertools.permutations(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wmigjjul.html

PHP:  // 手写递归交换
来源：http://dali.jianghu66.top/Article/details/gt2omzhooui.html

JS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gt2vhfpozgl.html

TS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2soljjbzy.html

Java: // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qlolrevv.html

Go:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gt2iivirmkv.html

Ruby: arr.permutation.to_a
来源：http://dali.hammf.cn/Article/details/gt2eqpbcxqf.html

C#:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2wuhylbfp.html

[N09] 栈与队列
来源：http://dali.aibaodan.cn/Article/details/gt2zyrdvilk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgfzy.top/Article/details/gt2wmnktxxc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gt2wdghbecf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gt2vznagvvu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yuxming.cn/Article/details/gt2gpazjfix.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.0kj1m.cn/Article/details/gt2bvrxugdu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dashuyun.cn/Article/details/gt2lnkbiary.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gt2vbmtqode.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cucudq.cn/Article/details/gt2vegkuffs.html

[N10] 链表节点定义
来源：http://dali.tanke756.top/Article/details/gt2kfjnbzke.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgfzy.top/Article/details/gt2iwptyhtk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2uzrodzga.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgfzy.top/Article/details/gt2jzequfwo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.feifeiyinyue.top/Article/details/gt2sqwnwpau.html

Java: class Node { int v; Node next; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2znimvogb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jianghu66.top/Article/details/gt2wnwdaczq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wjplvzeg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jakmccvw.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jddxgxbd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinghuilouyu.cn/Article/details/gt2igedktjc.html

PHP:  // 手写递归函数
来源：http://dali.cashguo.top/Article/details/gt2khzcrjav.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gt2gjpouamu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhixingplan.top/Article/details/gt2cdoxcvng.html

Java: // 手写递归
来源：http://dali.tanke756.top/Article/details/gt2otmmilbe.html

Go:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gt2omblokfw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ogphsjmk.html

C#:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gt2njsffuvu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jianghu66.top/Article/details/gt2shryinmn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.kuanghao11.cn/Article/details/gt2yftmaofj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.haohaochexian.top/Article/details/gt2erhcwyqk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guowangkeji.top/Article/details/gt2rufaifsx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fengsongda.top/Article/details/gt2hkqfqokw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aibaodan.cn/Article/details/gt2dbrysqvv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.birdmap.top/Article/details/gt2dtiloshx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenjidiqi.icu/Article/details/gt2pkwehtem.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gt2mnllyfso.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2laggcmok.html

O. 并发与异步
来源：http://dali.feifeiyinyue.top/Article/details/gt2tkiaxdnz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2ejngokss.html

[O01] 启动一个线程
来源：http://dali.zhongyouzk.top/Article/details/gt2vzhxbojj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ivvv.top/Article/details/gt2zczpehzl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenlongwang.top/Article/details/gt2xefpsjrc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.meibo888.top/Article/details/gt2gnilygfa.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gt2gtfgirum.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigufen.top/Article/details/gt2icmjmxrf.html

Go:   go f()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qiaydhsd.html

Ruby: Thread.new { f }
来源：http://dali.gaohongyu789.top/Article/details/gt2noznetkp.html

C#:   Task.Run(() => F());
来源：http://dali.cashguo.top/Article/details/gt2soihqhrd.html

[O02] 使用线程池
来源：http://dali.andypj.xyz/Article/details/gt2nobnzdqn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.c1oappe.top/Article/details/gt2ynmbaemn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ykspibnm.html

JS:   // worker_threads 线程池
来源：http://dali.sxryk.cn/Article/details/gt2drpdwdso.html

TS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gt2cyttionl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shuidangran.top/Article/details/gt2lafkgxjc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gogol.net.cn/Article/details/gt2akoqzxeu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ehwqpu.com/Article/details/gt2yvtbhtba.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yuxming.cn/Article/details/gt2mkxmsbue.html

[O03] 加锁保护共享数据
来源：http://dali.svipenyu.cn/Article/details/gt2hltushsl.html

Py:   with lock: shared += 1
来源：http://dali.tianlin.xyz/Article/details/gt2aeegoirc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.redwolf501.top/Article/details/gt2czlrypoe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangdashe.top/Article/details/gt2fgtjwlxu.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gt2nefrphrf.html

Java: synchronized (this) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gt2zmojjwau.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cashguo.top/Article/details/gt2wxfxibhq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gaohongyu789.top/Article/details/gt2zhevowak.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gt2hmqytcqc.html

[O04] 定义异步函数并等待
来源：http://dali.ydzc1.top/Article/details/gt2nyqvvbog.html

Py:   async def f():⏎    await g()
来源：http://dali.ivvv.top/Article/details/gt2qktzkvwr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tian-w.cn/Article/details/gt2ozzyjbmq.html

JS:   async function f() { await g(); }
来源：http://dali.hywenlv.cn/Article/details/gt2cuqtcuoq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.mhx1999.top/Article/details/gt2gomzuxnv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dkbkmsoy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.smart0.xyz/Article/details/gt2qfplccjh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rvqkjkzf.html

C#:   async Task F() { await G(); }
来源：http://dali.cheryme.top/Article/details/gt2lxsaeeom.html

[O05] 并发执行并等待全部完成
来源：http://dali.bjfxy.top/Article/details/gt2xzpuuwzg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.smart0.xyz/Article/details/gt2lekyhbnt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenjidiqi.icu/Article/details/gt2luijryzw.html

JS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gt2ejxcjhiy.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gt2dsazfzoj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ppjwa.cn/Article/details/gt2eznadlcy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zdqjudy.top/Article/details/gt2updibdgt.html

Ruby: threads.map(&:join)
来源：http://dali.redwolf501.top/Article/details/gt2kdhpsaoz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.quarkkingdee.top/Article/details/gt2hmmnjbka.html

[O06] 使用进程池
来源：http://dali.cashguo.top/Article/details/gt2dkuabirk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yonumen.top/Article/details/gt2lkoaesqz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxuanxn.top/Article/details/gt2belvomvn.html

JS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gt2dtrdcbat.html

TS:   // child_process / cluster 模块
来源：http://dali.fzhhl.top/Article/details/gt2exqpstwz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenzaomai.com/Article/details/gt2lynudkci.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gaohongyu789.top/Article/details/gt2zwaxicxw.html

Ruby: // fork 块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2soitfvbt.html

C#:   Parallel.For
来源：http://dali.pengpengdd.cyou/Article/details/gt2fibmtxfc.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2ujwqnakc.html

P. 常用工具函数
来源：http://dali.xylfe.cn/Article/details/gt2louegmti.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ackfodst.html

[P01] 生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gt2desdidwo.html

Py:   str(uuid.uuid4())
来源：http://dali.cdnleiting.top/Article/details/gt2huoiabhz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gt2cbzszqqv.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gt2dlalbzli.html

TS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gt2mqvxaetc.html

Java: UUID.randomUUID().toString()
来源：http://dali.andypj.xyz/Article/details/gt2hwkuzbcf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gotoacloud.top/Article/details/gt2nnsjjwjs.html

Ruby: SecureRandom.uuid
来源：http://dali.xuetiantiany.cn/Article/details/gt2bhjozjow.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gzhubu.top/Article/details/gt2pyuekdlf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.redwolf501.top/Article/details/gt2czvfedjd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dianchejie.cn/Article/details/gt2czbzmnro.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.andypj.xyz/Article/details/gt2pdkxjtyp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2jotupavj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guowangkeji.top/Article/details/gt2ocbanhpb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.svipenyu.cn/Article/details/gt2lblxkbfb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shzxlz.cn/Article/details/gt2zeeupwsn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ysciduur.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yongpay.top/Article/details/gt2kbvpasfe.html

[P03] 生成短随机字符串
来源：http://dali.haohaochexian.top/Article/details/gt2hxxbpbyi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenzaomai.com/Article/details/gt2ngyrvdqq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuxming.cn/Article/details/gt2zlinkfcy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gt2xydnxbpg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dashuyun.cn/Article/details/gt2ccfruusf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yonumen.top/Article/details/gt2zqkmcyov.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nwbrower.top/Article/details/gt2rcaldyxf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigfzy.top/Article/details/gt2twbjvuho.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aibaodan.cn/Article/details/gt2bwyooxqt.html

[P04] 求长度
来源：http://dali.cdnleiting.top/Article/details/gt2pbgafozt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cqqwz.cn/Article/details/gt2omrjvvzc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2ajplatws.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gt2bsbnzxdh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gt2nqjekqbe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gt2zhzmftto.html

Go:   len(arr);  len(m)
来源：http://dali.cqqwz.cn/Article/details/gt2rgidwfnv.html

Ruby: x.length;  x.size
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aunjhwbw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gt2rshcyrif.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lrkpilcw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.316326.xyz/Article/details/gt2dpundxau.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hfpthk.cn/Article/details/gt2lbvttrvp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cashguo.top/Article/details/gt2zdaenxsu.html


<!-- 参考信息 -->