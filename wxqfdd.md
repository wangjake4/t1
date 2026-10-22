代发 wailian999

Ruby: ARGV
来源：http://dali.mhx1999.top/Article/details/gt2frzusuxj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gt2wajjxjzo.html

[M02] 读取环境变量
来源：http://dali.yj20258888.top/Article/details/gt2mbtnznuf.html

Py:   os.environ.get("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2gzphoget.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yongpay.top/Article/details/gt2xzzkprsb.html

JS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gt2ltqcbyue.html

TS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gt2xzfrgozw.html

Java: System.getenv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gt2wtwcwgck.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gt2mnjrsyln.html

Ruby: ENV["HOME"]
来源：http://dali.sweek.top/Article/details/gt2nxklyrqg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fzhhl.top/Article/details/gt2bxnpdgpn.html

[M03] 执行外部命令
来源：http://dali.fengsongda.top/Article/details/gt2mbxcveho.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnqzz.top/Article/details/gt2brlpjjxt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuetiantiany.cn/Article/details/gt2uavpryqo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gt2plwrnays.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gt2pmcljwht.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pekbssqi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.c1oappe.top/Article/details/gt2mehmwrhv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tanke756.top/Article/details/gt2fhrrdrvy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhixingplan.top/Article/details/gt2lfexrwxf.html

[M04] 获取当前工作目录
来源：http://dali.yuanzhike.top/Article/details/gt2jliwmlqo.html

Py:   os.getcwd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2xvtvjapl.html

PHP:  getcwd();
来源：http://dali.wangdashe.top/Article/details/gt2lhlqgrtj.html

JS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2aupzxlco.html

TS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gt2kaeyowet.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hysaishi.cn/Article/details/gt2rclrtqtg.html

Go:   os.Getwd()
来源：http://dali.hysaishi.cn/Article/details/gt2hjivlhxr.html

Ruby: Dir.pwd
来源：http://dali.daria6918.cn/Article/details/gt2jqgslhgx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.bjfxy.top/Article/details/gt2mcwabwtg.html

[M05] 设置退出码
来源：http://dali.fzhhl.top/Article/details/gt2wcbruzhm.html

Py:   sys.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2glmlpehz.html

PHP:  exit(1);
来源：http://dali.zhixingplan.top/Article/details/gt2bajptbml.html

JS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2skugborf.html

TS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gt2rdiihcpe.html

Java: System.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2jmpzxnph.html

Go:   os.Exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2hvonqmxh.html

Ruby: exit 1
来源：http://dali.zycfv.cn/Article/details/gt2urjafmdp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cgotpnzq.html

[M06] 向标准错误输出
来源：http://dali.jyoumei.cn/Article/details/gt2nzbrxdpt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj202588.top/Article/details/gt2afrdsjjj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ydzc1.top/Article/details/gt2hweelyfp.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gt2vriyxtzw.html

TS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gt2radglehq.html

Java: System.err.println("err")
来源：http://dali.jlsjyb.cn/Article/details/gt2lvomzxqe.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aibaodan.cn/Article/details/gt2fsddxrzn.html

Ruby: warn "err"
来源：http://dali.aizwys.cn/Article/details/gt2sjlpvwqn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qjpaafss.html

[M07] 判断是否为主入口
来源：http://dali.tanke756.top/Article/details/gt2yrnqnyiw.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yxdwtorr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.birdmap.top/Article/details/gt2wgwyomes.html

JS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gt2amngslvl.html

TS:   require.main === module
来源：http://dali.yvedp.cn/Article/details/gt2pnwvyzag.html

Java: public static void main(String[] args)
来源：http://dali.jyoumei.cn/Article/details/gt2ttdavktz.html

Go:   func main()
来源：http://dali.hnxiangtu.top/Article/details/gt2upqaufjc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ppjwa.cn/Article/details/gt2edmugdjv.html

C#:   static void Main(string[] args)
来源：http://dali.gogol.net.cn/Article/details/gt2ainyvxog.html

[M08] 获取系统与运行时信息
来源：http://dali.jyoumei.cn/Article/details/gt2aebrgsbg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj202588.top/Article/details/gt2jyjlbird.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.bjfxy.top/Article/details/gt2mzaiheyk.html

JS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gt2hqfpwsvc.html

TS:   process.platform;  process.version
来源：http://dali.yuanzhike.top/Article/details/gt2dcuzjhgm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gkzfjytg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ypmbjbwd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mtuuczso.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cucudq.cn/Article/details/gt2bgntfrdq.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2lceexpvz.html

N. 数据结构与算法
来源：http://dali.cashguo.top/Article/details/gt2zmcpcfxm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2aqpnudxu.html

[N01] 二分查找（有序数组）
来源：http://dali.316326.xyz/Article/details/gt2itfrsliu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gt2thtvjzax.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pycfn.com/Article/details/gt2utrhunau.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gt2omjlbnun.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gt2jdjbkzga.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2hrcvaanm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pcbpzhiy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ybcxt.top/Article/details/gt2xbbnochd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2bcmnazfm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dashuyun.cn/Article/details/gt2hhkqvujm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ehwqpu.com/Article/details/gt2oqtczgam.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gt2hsoqyics.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.redwolf501.top/Article/details/gt2siduxfve.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gt2zweilgnz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ppjwa.cn/Article/details/gt2ptuzlkft.html

Go:   slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2vevhmzlt.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gt2njvephwt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jiagoushi.top/Article/details/gt2zsmpeknx.html

[N03] 快速排序（分治示例）
来源：http://dali.pycfn.com/Article/details/gt2hzdwpptx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fzhhl.top/Article/details/gt2ynboikqo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhongyouzk.top/Article/details/gt2jutwuqtr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gt2avaaqwqy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gt2asngpqhb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sysykeji.top/Article/details/gt2oyfguqxr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnqzz.top/Article/details/gt2jbyhpyrs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yueranfly.top/Article/details/gt2kkttdyzi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuanzx.com/Article/details/gt2dmhdagsf.html

[N04] 斐波那契数列
来源：http://dali.hnqzz.top/Article/details/gt2wcnfyuvb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gt2djnmvqwv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.meibo888.top/Article/details/gt2tpgrintr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2gvityoxs.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gt2tyrwnpka.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sysykeji.top/Article/details/gt2ouqgxwxr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hammf.cn/Article/details/gt2ybbozwmp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gt2kauhrtkd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gt2ixbhqhka.html

[N05] 最大公约数
来源：http://dali.chenjidiqi.icu/Article/details/gt2geydmtmu.html

Py:   math.gcd(a, b)
来源：http://dali.ybcxt.top/Article/details/gt2guvzobik.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mucxtshg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gt2tnpkkvqz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gt2iskqltan.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wudxhyho.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jianghu66.top/Article/details/gt2vhsrimat.html

Ruby: a.gcd(b)
来源：http://dali.aizwys.cn/Article/details/gt2qxgqatqt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.birdmap.top/Article/details/gt2ottfttma.html

[N06] 判断回文字符串
来源：http://dali.ppjwa.cn/Article/details/gt2tyjlsgsr.html

Py:   s == s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uyocirhg.html

PHP:  $s === strrev($s);
来源：http://dali.fzhhl.top/Article/details/gt2scemhkxz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gt2wlwwxpuy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gt2xjkkvbbu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenjidiqi.icu/Article/details/gt2qkvkjvjm.html

Go:   // 双指针从两端比较
来源：http://dali.yangfankeji.com/Article/details/gt2rnkxiyls.html

Ruby: s == s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hiugsfmb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gt2wzlntfsl.html

[N07] 两数之和（返回下标）
来源：http://dali.chenzaomai.com/Article/details/gt2nvsgtprj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cheryme.top/Article/details/gt2zunfhwnf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgufenzy.top/Article/details/gt2jcdjymuj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hammf.cn/Article/details/gt2mdtfofwu.html

TS:   // 手写 Map<string, number>
来源：http://dali.316326.xyz/Article/details/gt2bqdkgbpq.html

Java: // 手写 HashMap
来源：http://dali.vqdsnc.cn/Article/details/gt2jrlzafho.html

Go:   // 手写 map[int]int
来源：http://dali.sxryk.cn/Article/details/gt2bbntgmpq.html

Ruby: // 手写 Hash
来源：http://dali.tanke756.top/Article/details/gt2vkrhlpew.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.havefunace.top/Article/details/gt2lsjxdmmr.html

[N08] 生成全排列
来源：http://dali.fzhhl.top/Article/details/gt2byueuryp.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2unahwlcx.html

PHP:  // 手写递归交换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ecchdmhy.html

JS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lkalhilh.html

TS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2dmponmhx.html

Java: // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gt2nzytqzse.html

Go:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gt2tbrpxjmq.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fuiqmupw.html

C#:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2kuttlnjh.html

[N09] 栈与队列
来源：http://dali.yuanzhike.top/Article/details/gt2waoxvraa.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2zyoisgsj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gt2czbcspye.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gt2sdnmvxeu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shzxlz.cn/Article/details/gt2satoqqxf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fdyiwwaf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fzhhl.top/Article/details/gt2rrmkwgjd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2pkymxvbt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinqigfzy.top/Article/details/gt2igdafndv.html

[N10] 链表节点定义
来源：http://dali.zhiwuduotai.top/Article/details/gt2bzbxareo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zcxrcvrg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cqqwz.cn/Article/details/gt2nmowerdj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gogol.net.cn/Article/details/gt2cjzszjlj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhoulong.xyz/Article/details/gt2zrergade.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbtnbqc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tanke756.top/Article/details/gt2nftppcuf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cqqwz.cn/Article/details/gt2daksdmmp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenzaomai.com/Article/details/gt2lasijews.html

[N11] 二叉树中序遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2lrxcfwjd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gotoacloud.top/Article/details/gt2kngusigm.html

PHP:  // 手写递归函数
来源：http://dali.fengsongda.top/Article/details/gt2msaxayqr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gt2qcehlqyd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gt2hhmommvc.html

Java: // 手写递归
来源：http://dali.wangdashe.top/Article/details/gt2czlccxqc.html

Go:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gt2hgrikhfn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenjidiqi.icu/Article/details/gt2hbesfmko.html

C#:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gt2tnmlglso.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.0kj1m.cn/Article/details/gt2sjfazwmp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hammf.cn/Article/details/gt2wbayqily.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pengpengdd.cyou/Article/details/gt2zbwjwibx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gt2pujblkzp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gt2fozyvhwx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnzkctr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.fzhhl.top/Article/details/gt2linciivi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gt2yfzomnvu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gt2qpncbhew.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ullsdkum.html

O. 并发与异步
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bdyeslnw.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2goedeitq.html

[O01] 启动一个线程
来源：http://dali.svipenyu.cn/Article/details/gt2uazgtuip.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tian-w.cn/Article/details/gt2obcezdbd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.316326.xyz/Article/details/gt2zyvlxiiv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangshuangyany.cn/Article/details/gt2qsfjpwal.html

TS:   // 同 JS
来源：http://dali.yuanzhike.top/Article/details/gt2oeeekvug.html

Java: new Thread(() -> f()).start()
来源：http://dali.gotoacloud.top/Article/details/gt2xyftkpiv.html

Go:   go f()
来源：http://dali.sufxvd.cn/Article/details/gt2yimtgrhs.html

Ruby: Thread.new { f }
来源：http://dali.meibo888.top/Article/details/gt2urgaudrv.html

C#:   Task.Run(() => F());
来源：http://dali.aizwys.cn/Article/details/gt2tvlardiw.html

[O02] 使用线程池
来源：http://dali.zhengqikj.top/Article/details/gt2mlmyjpzf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dzozzxwf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sxryk.cn/Article/details/gt2hmqrsnco.html

JS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gt2ckyfgcgx.html

TS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gt2hdailujo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxinkj.top/Article/details/gt2hpjhyozw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shzxlz.cn/Article/details/gt2iwnhrljh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shzxlz.cn/Article/details/gt2idsnhclj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xuanzx.com/Article/details/gt2ocxkmdev.html

[O03] 加锁保护共享数据
来源：http://dali.cqqwz.cn/Article/details/gt2mjlemxmp.html

Py:   with lock: shared += 1
来源：http://dali.tanke756.top/Article/details/gt2ziasrzqz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xinyue.icu/Article/details/gt2kymnqcmx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tlzrjyyk.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gt2nwdhicmy.html

Java: synchronized (this) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gt2lwjtvpxz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ybcxt.top/Article/details/gt2tvnypqtg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ydsesxrr.html

C#:   lock (gate) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gt2lcsrhvwl.html

[O04] 定义异步函数并等待
来源：http://dali.9152youxi.cn/Article/details/gt2sdhjmmsj.html

Py:   async def f():⏎    await g()
来源：http://dali.pengpengdd.cyou/Article/details/gt2pxrmhmfx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuanzx.com/Article/details/gt2ditscqdh.html

JS:   async function f() { await g(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjcmxnrk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2tprtvqxy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj202588.top/Article/details/gt2zedlhbiv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gogol.net.cn/Article/details/gt2cyckgbov.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigfzy.top/Article/details/gt2bwyqkqpd.html

C#:   async Task F() { await G(); }
来源：http://dali.gogol.net.cn/Article/details/gt2awpyabbi.html

[O05] 并发执行并等待全部完成
来源：http://dali.yvedp.cn/Article/details/gt2mamhysxs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.c1oappe.top/Article/details/gt2jjbbdxrb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenlongwang.top/Article/details/gt2hpcjyvho.html

JS:   await Promise.all(tasks)
来源：http://dali.tian-w.cn/Article/details/gt2tghnwjks.html

TS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gt2mtxaldat.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jiagoushi.top/Article/details/gt2aycchhhk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eseaviea.html

Ruby: threads.map(&:join)
来源：http://dali.sweek.top/Article/details/gt2zwwhnmfo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.daxiang520.top/Article/details/gt2qnfdjicc.html

[O06] 使用进程池
来源：http://dali.ehwqpu.com/Article/details/gt2xunfqxng.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fengsongda.top/Article/details/gt2phsyomhi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vhtjxpkq.html

JS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gt2itgbmkqb.html

TS:   // child_process / cluster 模块
来源：http://dali.hnqzz.top/Article/details/gt2rnlqemsv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xziqi.cn/Article/details/gt2uhhqsqze.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sweek.top/Article/details/gt2mwjpivzl.html

Ruby: // fork 块
来源：http://dali.guowangkeji.top/Article/details/gt2fhuastfz.html

C#:   Parallel.For
来源：http://dali.ppjwa.cn/Article/details/gt2emtvfwgf.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2mcmdgabi.html

P. 常用工具函数
来源：http://dali.yangfankeji.com/Article/details/gt2epukcqxq.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2kbhubkch.html

[P01] 生成 UUID
来源：http://dali.fzhhl.top/Article/details/gt2ksqpkwsv.html

Py:   str(uuid.uuid4())
来源：http://dali.hfpthk.cn/Article/details/gt2bszcmhtr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nepepzfk.html

JS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gt2qrkjoigo.html

TS:   crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gt2djsngmht.html

Java: UUID.randomUUID().toString()
来源：http://dali.cqqwz.cn/Article/details/gt2cbcllpsw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pycfn.com/Article/details/gt2kdaafnfw.html

Ruby: SecureRandom.uuid
来源：http://dali.daxiang520.top/Article/details/gt2wivuevrv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gogol.net.cn/Article/details/gt2igprbiuf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sweek.top/Article/details/gt2skskstjn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cucudq.cn/Article/details/gt2tqqhyqjp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guannengcc.top/Article/details/gt2rzgncpqc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangshuangyany.cn/Article/details/gt2qqpwftvm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pycfn.com/Article/details/gt2pfeavpkd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ulwlaigr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj202588.top/Article/details/gt2wdlhgeui.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ehwqpu.com/Article/details/gt2sznpqeup.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.havefunace.top/Article/details/gt2qrcbhanl.html

[P03] 生成短随机字符串
来源：http://dali.yvedp.cn/Article/details/gt2bdhttihg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shuidangran.top/Article/details/gt2ootfpuyd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aibaodan.cn/Article/details/gt2xfmrqjwd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gt2jifetyzl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guannengcc.top/Article/details/gt2xypfdjci.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuxming.cn/Article/details/gt2bqszmhkf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.daria6918.cn/Article/details/gt2uzadcnrp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rhzivpho.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.birdmap.top/Article/details/gt2tfcbfwll.html

[P04] 求长度
来源：http://dali.hywenlv.cn/Article/details/gt2piacismf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.meibo888.top/Article/details/gt2uxnhqmqk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gt2bjsmgzuc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gt2lbadmwwq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gt2cydlscqs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gt2zaoftkuq.html

Go:   len(arr);  len(m)
来源：http://dali.yueranfly.top/Article/details/gt2bfkbwrld.html

Ruby: x.length;  x.size
来源：http://dali.tanke756.top/Article/details/gt2moavzigl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hammf.cn/Article/details/gt2ktvbjaoi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj202588.top/Article/details/gt2pdzsoqbd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.aibaodan.cn/Article/details/gt2pdmjjiub.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aizwys.cn/Article/details/gt2fbnzkuuy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guannengcc.top/Article/details/gt2vsaimhvh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.0kj1m.cn/Article/details/gt2fbvhozas.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cheryme.top/Article/details/gt2dyikqoqs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cheryme.top/Article/details/gt2blmniyxq.html

Ruby: a == b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gcojwaqu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ivvv.top/Article/details/gt2wvlfimbr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hysaishi.cn/Article/details/gt2tvsgxyle.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jqgfzy.top/Article/details/gt2knervbfb.html

PHP:  if (empty($x)) {}
来源：http://dali.fzhhl.top/Article/details/gt2uhwhclms.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ydzc1.top/Article/details/gt2uvevybdd.html

TS:   if (x == null) {}
来源：http://dali.yuxming.cn/Article/details/gt2flurvill.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sweek.top/Article/details/gt2gsmoblgp.html

Go:   if x == nil {}
来源：http://dali.yuxming.cn/Article/details/gt2yboilaby.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuanzhike.top/Article/details/gt2ajyfrmau.html

C#:   if (x is null) {}
来源：http://dali.ehwqpu.com/Article/details/gt2hokjfxhc.html

[P07] 防抖与节流
来源：http://dali.guannengcc.top/Article/details/gt2enkeurgw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenjidiqi.icu/Article/details/gt2teqwhvpu.html

PHP:  // 手写时间戳比较
来源：http://dali.xinyue.icu/Article/details/gt2lnkudssb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yjmtznsp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gt2mszrqpig.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aizwys.cn/Article/details/gt2ednatpgr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.aizwys.cn/Article/details/gt2nxevkxcj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sweek.top/Article/details/gt2xhvgmifm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shangyingyoupin.top/Article/details/gt2cjoyhrvb.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigufen.top/Article/details/gt2qfughvhs.html


<!-- 参考信息 -->