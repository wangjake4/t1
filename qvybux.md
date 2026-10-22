代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gt2xdozhbdo.html

JS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gt2zszzbrod.html

TS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gt2zzgianom.html

Java: System.getenv("HOME")
来源：http://dali.mhx1999.top/Article/details/gt2sfsxhkwa.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gt2rooceqbf.html

Ruby: ENV["HOME"]
来源：http://dali.xylfe.cn/Article/details/gt2eakcnrle.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gt2iffdjlia.html

[M03] 执行外部命令
来源：http://dali.ydzc1.top/Article/details/gt2hhrpgsbd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yongpay.top/Article/details/gt2telensgz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ydzc1.top/Article/details/gt2gxgwmccg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gt2gmljcixw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gt2zfzrykik.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.meibo888.top/Article/details/gt2qynecbwv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guowangkeji.top/Article/details/gt2fzpgadtc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.0kj1m.cn/Article/details/gt2kcwsfvkt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cucudq.cn/Article/details/gt2nbzptckp.html

[M04] 获取当前工作目录
来源：http://dali.hfpthk.cn/Article/details/gt2dwcthhyx.html

Py:   os.getcwd()
来源：http://dali.cqqwz.cn/Article/details/gt2wbxulash.html

PHP:  getcwd();
来源：http://dali.gotoacloud.top/Article/details/gt2xanzjrer.html

JS:   process.cwd()
来源：http://dali.jianghu66.top/Article/details/gt2dcreijcx.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gt2enckczzr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jianghu66.top/Article/details/gt2jygofmpc.html

Go:   os.Getwd()
来源：http://dali.hywenlv.cn/Article/details/gt2nblxewtj.html

Ruby: Dir.pwd
来源：http://dali.yonumen.top/Article/details/gt2faihzaws.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.9152youxi.cn/Article/details/gt2wppnloxq.html

[M05] 设置退出码
来源：http://dali.pycfn.com/Article/details/gt2eorrpsxa.html

Py:   sys.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2tdwmbknl.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvgeyoel.html

JS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2jdmwecjs.html

TS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2yyfxwnwp.html

Java: System.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2dnbrmhzm.html

Go:   os.Exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2lmkqflgt.html

Ruby: exit 1
来源：http://dali.cashguo.top/Article/details/gt2eodqlnek.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gt2yfqfmytq.html

[M06] 向标准错误输出
来源：http://dali.mhx1999.top/Article/details/gt2ksggfxha.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhixingplan.top/Article/details/gt2isoyzzop.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tanke756.top/Article/details/gt2tmnpixpu.html

JS:   console.error("err")
来源：http://dali.gotoacloud.top/Article/details/gt2dvfeoqyg.html

TS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dyqcmgic.html

Java: System.err.println("err")
来源：http://dali.yuxming.cn/Article/details/gt2ofcocwbl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.bjfxy.top/Article/details/gt2yttzgeog.html

Ruby: warn "err"
来源：http://dali.andypj.xyz/Article/details/gt2xxvssxjv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigufen.top/Article/details/gt2nvjxzyyi.html

[M07] 判断是否为主入口
来源：http://dali.hywenlv.cn/Article/details/gt2hglasdus.html

Py:   if __name__ == "__main__":
来源：http://dali.iojbl.cn/Article/details/gt2auofxhjr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhongyouzk.top/Article/details/gt2iqufkfrk.html

JS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gt2hzoownug.html

TS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gt2kiysmvwa.html

Java: public static void main(String[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pxcahxts.html

Go:   func main()
来源：http://dali.9152youxi.cn/Article/details/gt2nnubhzza.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuanzx.com/Article/details/gt2przolmms.html

C#:   static void Main(string[] args)
来源：http://dali.svipenyu.cn/Article/details/gt2dnxuqxcv.html

[M08] 获取系统与运行时信息
来源：http://dali.cqqwz.cn/Article/details/gt2bqnqlzyk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dashuyun.cn/Article/details/gt2knegvfdi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gxtypxox.html

JS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gt2wdtbyaia.html

TS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gt2pooszzmt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aizwys.cn/Article/details/gt2mxfjoahp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yueranfly.top/Article/details/gt2rhwgmroo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.feifeiyinyue.top/Article/details/gt2yidsxbsf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tianlin.xyz/Article/details/gt2ccowlgyo.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ecdhmdpb.html

N. 数据结构与算法
来源：http://dali.zhoulong.xyz/Article/details/gt2suycfovr.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2rowhawod.html

[N01] 二分查找（有序数组）
来源：http://dali.yueranfly.top/Article/details/gt2fqegzzaf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2qmbxatpe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jiagoushi.top/Article/details/gt2chaqpycv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gt2abnpephq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gt2rlngcxlv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2pkjtzoza.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gt2brhqpybe.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guowangkeji.top/Article/details/gt2pvzskkso.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2wuoeqelv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daxiang520.top/Article/details/gt2vwpgrhzv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gt2nxvkovkf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cheryme.top/Article/details/gt2cvlwjpfu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gt2cueeeihz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gt2bcwpnbtk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ehwqpu.com/Article/details/gt2osodpflx.html

Go:   slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2dnqtayzy.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gt2nbbztcqf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.bjfxy.top/Article/details/gt2hgeeqbzo.html

[N03] 快速排序（分治示例）
来源：http://dali.jqgufenzy.top/Article/details/gt2fbyujtcf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pengpengdd.cyou/Article/details/gt2azkpyxbe.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nwbrower.top/Article/details/gt2pyrenfgn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jianghu66.top/Article/details/gt2gnqzipga.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gt2wyamigwr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pycfn.com/Article/details/gt2uukjhaeo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dashuyun.cn/Article/details/gt2mmboytlm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.andypj.xyz/Article/details/gt2jwdxnkrg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jyoumei.cn/Article/details/gt2wwtsdwpc.html

[N04] 斐波那契数列
来源：http://dali.tian-w.cn/Article/details/gt2ktbmrwzv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gt2zdewgkxb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pzvhrclt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gt2ldqouhio.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gt2ywraalhq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sxryk.cn/Article/details/gt2juusmejz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xylfe.cn/Article/details/gt2sooxrqqy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gt2wfqujfes.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nstnyjhm.html

[N05] 最大公约数
来源：http://dali.yuanzhike.top/Article/details/gt2ymjvdhty.html

Py:   math.gcd(a, b)
来源：http://dali.gzhubu.top/Article/details/gt2ogfdsoho.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.mhx1999.top/Article/details/gt2cxwgzsmo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gt2heqdwcmn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gt2malngzno.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cdnleiting.top/Article/details/gt2bhonrcss.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gzhubu.top/Article/details/gt2yjxzqegh.html

Ruby: a.gcd(b)
来源：http://dali.shuidangran.top/Article/details/gt2timfmzsb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yvedp.cn/Article/details/gt2ihsnxrum.html

[N06] 判断回文字符串
来源：http://dali.316326.xyz/Article/details/gt2slgchcju.html

Py:   s == s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2beorrzmn.html

PHP:  $s === strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gt2owdurhkd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gt2btvojgrj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vmimuvsw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hysaishi.cn/Article/details/gt2bplostsk.html

Go:   // 双指针从两端比较
来源：http://dali.316326.xyz/Article/details/gt2dsrzzslu.html

Ruby: s == s.reverse
来源：http://dali.jinqigufen.top/Article/details/gt2nesaoqas.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.wangshuangyany.cn/Article/details/gt2gpnvmtxs.html

[N07] 两数之和（返回下标）
来源：http://dali.zhiwuduotai.top/Article/details/gt2queefctm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258888.top/Article/details/gt2seimdhuc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jlsjyb.cn/Article/details/gt2vzvccuwu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zycfv.cn/Article/details/gt2rkevifkq.html

TS:   // 手写 Map<string, number>
来源：http://dali.jqgufenzy.top/Article/details/gt2ibjsvyal.html

Java: // 手写 HashMap
来源：http://dali.gaohongyu789.top/Article/details/gt2bwtnjnve.html

Go:   // 手写 map[int]int
来源：http://dali.shangyingyoupin.top/Article/details/gt2kujghvqq.html

Ruby: // 手写 Hash
来源：http://dali.hfpthk.cn/Article/details/gt2onkbokbl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.quarkkingdee.top/Article/details/gt2apirvvzc.html

[N08] 生成全排列
来源：http://dali.shuidangran.top/Article/details/gt2zjvhizie.html

Py:   itertools.permutations(arr)
来源：http://dali.iojbl.cn/Article/details/gt2llbycjkh.html

PHP:  // 手写递归交换
来源：http://dali.316326.xyz/Article/details/gt2siybkxkw.html

JS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gt2hynoscgk.html

TS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2ziyrajrp.html

Java: // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gt2fidnbjuw.html

Go:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2pfyrfsfm.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxinkj.top/Article/details/gt2aevjrcgm.html

C#:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gt2vgkurvif.html

[N09] 栈与队列
来源：http://dali.hammf.cn/Article/details/gt2xhybuqpt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuanzx.com/Article/details/gt2zuxvysef.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lcocrahl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gt2ywnigcrt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xylfe.cn/Article/details/gt2haxwyvnw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.iojbl.cn/Article/details/gt2lwebqgtc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qhjtdznu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2wfvbzqub.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cdnleiting.top/Article/details/gt2mowxwpex.html

[N10] 链表节点定义
来源：http://dali.yuanzhike.top/Article/details/gt2cmglxybc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.9152youxi.cn/Article/details/gt2uqpxtkth.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ehwqpu.com/Article/details/gt2nejfjpto.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj202588.top/Article/details/gt2hzrxsjep.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenlongwang.top/Article/details/gt2pxtgxpcz.html

Java: class Node { int v; Node next; }
来源：http://dali.cheryme.top/Article/details/gt2eawzeyei.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.9152youxi.cn/Article/details/gt2jhouidfs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.smart0.xyz/Article/details/gt2abbsqouz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cheryme.top/Article/details/gt2ydmbokra.html

[N11] 二叉树中序遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2uosbdlqc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yuxming.cn/Article/details/gt2wcuzqkun.html

PHP:  // 手写递归函数
来源：http://dali.fengsongda.top/Article/details/gt2xavazeph.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gt2kwdibeav.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qnpjyxqu.html

Java: // 手写递归
来源：http://dali.ybcxt.top/Article/details/gt2rifyxucf.html

Go:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gt2lbtichgc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guowangkeji.top/Article/details/gt2wpomkpfm.html

C#:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2yxxugtwb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cdnleiting.top/Article/details/gt2lkjuhjcs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj202588.top/Article/details/gt2agorqtjt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj20258888.top/Article/details/gt2jpbaazde.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gt2vwbqedsq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gt2fjfdzkig.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gt2isuqjhey.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jiagoushi.top/Article/details/gt2znfzmmjg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nwbrower.top/Article/details/gt2alntaquq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gt2fjysswtz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2mmnraqag.html

O. 并发与异步
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zmtfwvqe.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2mjtxnzku.html

[O01] 启动一个线程
来源：http://dali.sysykeji.top/Article/details/gt2tgaundsu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sysykeji.top/Article/details/gt2mxazbzpz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.redwolf501.top/Article/details/gt2ioveuwuu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gzhubu.top/Article/details/gt2mvbyfsnn.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gt2vkisbmkx.html

Java: new Thread(() -> f()).start()
来源：http://dali.hysaishi.cn/Article/details/gt2unmsmbds.html

Go:   go f()
来源：http://dali.xylfe.cn/Article/details/gt2deftacln.html

Ruby: Thread.new { f }
来源：http://dali.cdnleiting.top/Article/details/gt2tbzhxgmf.html

C#:   Task.Run(() => F());
来源：http://dali.chenjidiqi.icu/Article/details/gt2ukirrnbt.html

[O02] 使用线程池
来源：http://dali.birdmap.top/Article/details/gt2wrxxkorq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.9152youxi.cn/Article/details/gt2rcwbyunq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dianchejie.cn/Article/details/gt2twxsuugk.html

JS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gt2vblakcrk.html

TS:   // worker_threads 线程池
来源：http://dali.jianghu66.top/Article/details/gt2klmpugwv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.quarkkingdee.top/Article/details/gt2fjevzhwt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuxming.cn/Article/details/gt2pipqmwvb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sysykeji.top/Article/details/gt2dklnmvmf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hywenlv.cn/Article/details/gt2vcsmwvrl.html

[O03] 加锁保护共享数据
来源：http://dali.fzhhl.top/Article/details/gt2qdpebyaj.html

Py:   with lock: shared += 1
来源：http://dali.aibaodan.cn/Article/details/gt2ggabyfmh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tanke756.top/Article/details/gt2tmikflls.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxinkj.top/Article/details/gt2ybqevwcz.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gt2qsurjrme.html

Java: synchronized (this) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gt2llonjwmg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinqigufen.top/Article/details/gt2ntfiagvd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.316326.xyz/Article/details/gt2hocbvxtv.html

C#:   lock (gate) { shared++; }
来源：http://dali.havefunace.top/Article/details/gt2nlxgnzuq.html

[O04] 定义异步函数并等待
来源：http://dali.kuanghao11.cn/Article/details/gt2qxaiklww.html

Py:   async def f():⏎    await g()
来源：http://dali.hysaishi.cn/Article/details/gt2aefmbhrn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xylfe.cn/Article/details/gt2ketfhtuc.html

JS:   async function f() { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gt2sfjdkhjq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.aizwys.cn/Article/details/gt2rizajxyv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.svipenyu.cn/Article/details/gt2oprauher.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenjidiqi.icu/Article/details/gt2kngbypxn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vzpbnvjp.html

C#:   async Task F() { await G(); }
来源：http://dali.ydzc1.top/Article/details/gt2zbrqqgdy.html

[O05] 并发执行并等待全部完成
来源：http://dali.daxiang520.top/Article/details/gt2nhouzpbr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigfzy.top/Article/details/gt2ddpnxscv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xziqi.cn/Article/details/gt2zdskrdoc.html

JS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2nfkffvot.html

TS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gt2rnljaakh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.snrcjt.cn/Article/details/gt2qapjfrbv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.iojbl.cn/Article/details/gt2qyyjpzcm.html

Ruby: threads.map(&:join)
来源：http://dali.cqqwz.cn/Article/details/gt2gnhqsokh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhengqikj.top/Article/details/gt2djoxsyzx.html

[O06] 使用进程池
来源：http://dali.jinqigufen.top/Article/details/gt2lybvttmd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.aibaodan.cn/Article/details/gt2xsarjufy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.smart0.xyz/Article/details/gt2opxxdrki.html

JS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gt2kstaangl.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wulymnhu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yueranfly.top/Article/details/gt2tukyeywu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.snrcjt.cn/Article/details/gt2tailijfq.html

Ruby: // fork 块
来源：http://dali.hysaishi.cn/Article/details/gt2sjhqfkig.html

C#:   Parallel.For
来源：http://dali.redwolf501.top/Article/details/gt2mepzduyv.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2gbyrwvpj.html

P. 常用工具函数
来源：http://dali.zhoulong.xyz/Article/details/gt2okoutyxp.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2tiaptlin.html

[P01] 生成 UUID
来源：http://dali.wangdashe.top/Article/details/gt2qlffzfsp.html

Py:   str(uuid.uuid4())
来源：http://dali.ybcxt.top/Article/details/gt2ypjgbcre.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fzhhl.top/Article/details/gt2pzirexav.html

JS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gt2tupsxljl.html

TS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gt2xpvirrul.html

Java: UUID.randomUUID().toString()
来源：http://dali.smart0.xyz/Article/details/gt2isqkzlnw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cqqwz.cn/Article/details/gt2dyrrblmb.html

Ruby: SecureRandom.uuid
来源：http://dali.zdqjudy.top/Article/details/gt2mpjwpepc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gfrzpyiq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cucudq.cn/Article/details/gt2hawegfib.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.0kj1m.cn/Article/details/gt2fqlqswsk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.pycfn.com/Article/details/gt2gmpmmlld.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbeojwz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.haohaochexian.top/Article/details/gt2lssxgmat.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xinyue.icu/Article/details/gt2xtooolbr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tianlin.xyz/Article/details/gt2enieamec.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2dirrnohe.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.redwolf501.top/Article/details/gt2fznhujwo.html

[P03] 生成短随机字符串
来源：http://dali.haohaochexian.top/Article/details/gt2iuziojhs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxinkj.top/Article/details/gt2zcabsgzm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ppjwa.cn/Article/details/gt2nxifcadj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yueranfly.top/Article/details/gt2nvkpzsds.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2diibobkj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ybcxt.top/Article/details/gt2thtgqaca.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ivvv.top/Article/details/gt2juwlsref.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pmzezard.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258.top/Article/details/gt2ankwchrv.html

[P04] 求长度
来源：http://dali.jiagoushi.top/Article/details/gt2cfrtcyag.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangdashe.top/Article/details/gt2mxaeimsh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gt2ihdetnki.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gt2aloefhox.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2huymjsgb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ivvv.top/Article/details/gt2jjyzcojy.html

Go:   len(arr);  len(m)
来源：http://dali.jyoumei.cn/Article/details/gt2vzejgytz.html

Ruby: x.length;  x.size
来源：http://dali.xinyue.icu/Article/details/gt2hyppxyoc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.redwolf501.top/Article/details/gt2qrtujick.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ppjwa.cn/Article/details/gt2iuezdoat.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guowangkeji.top/Article/details/gt2ueriyexq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ppjwa.cn/Article/details/gt2cfqfoitt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuxming.cn/Article/details/gt2vvsbmwjo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.redwolf501.top/Article/details/gt2krxpvhvs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aibaodan.cn/Article/details/gt2agjnnasc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dashuyun.cn/Article/details/gt2icpkbqhs.html

Ruby: a == b
来源：http://dali.fzhhl.top/Article/details/gt2sjrhcatd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.316326.xyz/Article/details/gt2ashujwbd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sysykeji.top/Article/details/gt2yighmfhr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj20258.top/Article/details/gt2vtmvjqrh.html

PHP:  if (empty($x)) {}
来源：http://dali.guannengcc.top/Article/details/gt2xqqnbght.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gotoacloud.top/Article/details/gt2gctrfjqp.html

TS:   if (x == null) {}
来源：http://dali.xuanzx.com/Article/details/gt2jwvmivjj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bwdyjkuf.html

Go:   if x == nil {}
来源：http://dali.hnxiangtu.top/Article/details/gt2jsupotaq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pmvlxucp.html

C#:   if (x is null) {}
来源：http://dali.snrcjt.cn/Article/details/gt2sjyhhjla.html

[P07] 防抖与节流
来源：http://dali.sweek.top/Article/details/gt2inrlqtey.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.vqdsnc.cn/Article/details/gt2hacizvou.html

PHP:  // 手写时间戳比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2jawkuqax.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gt2mrhuwawl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gt2shsmpsfc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2gynmjpea.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yangfankeji.com/Article/details/gt2tknlffjl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nwbrower.top/Article/details/gt2mvsjinma.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.havefunace.top/Article/details/gt2xraberha.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigfzy.top/Article/details/gt2ypmskazm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2azhqjybw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2jgtszvyy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ybcxt.top/Article/details/gt2bxijcdqn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bkifctky.html


<!-- 参考信息 -->