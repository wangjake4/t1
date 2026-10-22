代发 wailian999

Ruby: ARGV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lgdecmys.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gt2itjdpkku.html

[M02] 读取环境变量
来源：http://dali.yvedp.cn/Article/details/gt2ugoqpvsd.html

Py:   os.environ.get("HOME")
来源：http://dali.ppjwa.cn/Article/details/gt2psobjpjx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gt2fvppuucx.html

JS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gt2ycxpoamq.html

TS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gt2qcnznfrq.html

Java: System.getenv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fotxebsn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gt2puvyvgrd.html

Ruby: ENV["HOME"]
来源：http://dali.iojbl.cn/Article/details/gt2fxzfyesm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2idajflix.html

[M03] 执行外部命令
来源：http://dali.cqqwz.cn/Article/details/gt2pyahcrnr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.c1oappe.top/Article/details/gt2gvgreifp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yanxiufei.cn/Article/details/gt2kksgznny.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gt2iypbcwpi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gt2zixujwyv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jianghu66.top/Article/details/gt2cpgbocvs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shuidangran.top/Article/details/gt2lqffpqrb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.svipenyu.cn/Article/details/gt2acasjztz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.0kj1m.cn/Article/details/gt2avntppol.html

[M04] 获取当前工作目录
来源：http://dali.zdqjudy.top/Article/details/gt2gesdutch.html

Py:   os.getcwd()
来源：http://dali.ppjwa.cn/Article/details/gt2rwkuxvai.html

PHP:  getcwd();
来源：http://dali.0kj1m.cn/Article/details/gt2oxecgxkg.html

JS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2uvddepff.html

TS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zuepiqcm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.feifeiyinyue.top/Article/details/gt2bxwdcnqt.html

Go:   os.Getwd()
来源：http://dali.cqqwz.cn/Article/details/gt2almqoyay.html

Ruby: Dir.pwd
来源：http://dali.cheryme.top/Article/details/gt2iikqoesk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuetiantiany.cn/Article/details/gt2nkasdvgb.html

[M05] 设置退出码
来源：http://dali.zhixingplan.top/Article/details/gt2qanzccnn.html

Py:   sys.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2mqreyice.html

PHP:  exit(1);
来源：http://dali.iojbl.cn/Article/details/gt2vbgzcgng.html

JS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2ebhbzerk.html

TS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2dbzpjoos.html

Java: System.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gt2bhqfylbj.html

Go:   os.Exit(1)
来源：http://dali.smart0.xyz/Article/details/gt2fyvgblvr.html

Ruby: exit 1
来源：http://dali.zhongyouzk.top/Article/details/gt2oltckayq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gogol.net.cn/Article/details/gt2orxjdkqm.html

[M06] 向标准错误输出
来源：http://dali.guannengcc.top/Article/details/gt2combifdo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sufxvd.cn/Article/details/gt2wgfqtceb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xjaofjfv.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vquavdzi.html

TS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gt2dzhxjxil.html

Java: System.err.println("err")
来源：http://dali.cdnleiting.top/Article/details/gt2ujeuvpit.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aibaodan.cn/Article/details/gt2gzegvwbx.html

Ruby: warn "err"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cbhnhiic.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.svipenyu.cn/Article/details/gt2rcfzxtob.html

[M07] 判断是否为主入口
来源：http://dali.cucudq.cn/Article/details/gt2enpggerl.html

Py:   if __name__ == "__main__":
来源：http://dali.zhiwuduotai.top/Article/details/gt2wmyorlit.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fgmhryib.html

JS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gt2pmelalha.html

TS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bjrefmaa.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mrvkrmvk.html

Go:   func main()
来源：http://dali.guannengcc.top/Article/details/gt2ddpnkxbj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jiagoushi.top/Article/details/gt2yjdveaal.html

C#:   static void Main(string[] args)
来源：http://dali.zycfv.cn/Article/details/gt2dfcjgeko.html

[M08] 获取系统与运行时信息
来源：http://dali.cdnleiting.top/Article/details/gt2dnuvgufq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jlsjyb.cn/Article/details/gt2ihghrjmz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigfzy.top/Article/details/gt2imppolvx.html

JS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tgvyfdkt.html

TS:   process.platform;  process.version
来源：http://dali.yj20258.top/Article/details/gt2rhxtbroh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sysykeji.top/Article/details/gt2mxflfbge.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.0kj1m.cn/Article/details/gt2kpvtooup.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yonumen.top/Article/details/gt2tkcakvoa.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cqqwz.cn/Article/details/gt2xmhjvcuy.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2xmittaxj.html

N. 数据结构与算法
来源：http://dali.xuanzx.com/Article/details/gt2msvjkteg.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2apyflgzq.html

[N01] 二分查找（有序数组）
来源：http://dali.andypj.xyz/Article/details/gt2pfgmiukl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2buhljeuk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj20258888.top/Article/details/gt2zkzauusz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gt2wijycotx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gt2hsrhlvtd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2btycwgvz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2lotjopql.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ykuzxunj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2atnipywi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2trqfgkjp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gt2efdpbxaz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gogol.net.cn/Article/details/gt2rjcbwmfa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gt2drhpgnpy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2euigxzod.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hywenlv.cn/Article/details/gt2vvftszue.html

Go:   slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gt2kmdbtghj.html

Ruby: arr.sort
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqplxpfv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangdashe.top/Article/details/gt2sjsumjnj.html

[N03] 快速排序（分治示例）
来源：http://dali.yongpay.top/Article/details/gt2pkrndwrp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zdqjudy.top/Article/details/gt2uosrlkbb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yvedp.cn/Article/details/gt2bjikknbw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gt2zhmjpqlq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gt2tflhbauj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258888.top/Article/details/gt2nrrrtkdf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnxiangtu.top/Article/details/gt2pjgifezj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nwbrower.top/Article/details/gt2hppiqjyf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dianchejie.cn/Article/details/gt2omftktbs.html

[N04] 斐波那契数列
来源：http://dali.havefunace.top/Article/details/gt2kaxlwyza.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2aodayfwz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xylfe.cn/Article/details/gt2rfcudxde.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gt2pdvqhbvh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gt2rilatkow.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnqzz.top/Article/details/gt2lnzrorgt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xziqi.cn/Article/details/gt2ytxcpjsn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gt2zrzcrxpu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gt2tqtbxxjs.html

[N05] 最大公约数
来源：http://dali.zdqjudy.top/Article/details/gt2bbnlpflg.html

Py:   math.gcd(a, b)
来源：http://dali.hywenlv.cn/Article/details/gt2gmzhqzzv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yueranfly.top/Article/details/gt2xrciukhq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gt2lqaxzjnf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gt2yvwyfqpi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gzhubu.top/Article/details/gt2xzuptbqs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuanzx.com/Article/details/gt2jbraeoez.html

Ruby: a.gcd(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2qxhbblrk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guowangkeji.top/Article/details/gt2sfjeudzr.html

[N06] 判断回文字符串
来源：http://dali.yvedp.cn/Article/details/gt2dwsiulqy.html

Py:   s == s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gt2twcxxsof.html

PHP:  $s === strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2rwzvjipt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gt2eryvkqdx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gt2ctrlfbzx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.redwolf501.top/Article/details/gt2sghkfemb.html

Go:   // 双指针从两端比较
来源：http://dali.snrcjt.cn/Article/details/gt2bjzubgwa.html

Ruby: s == s.reverse
来源：http://dali.nwbrower.top/Article/details/gt2qdtyleel.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gt2rhnsycam.html

[N07] 两数之和（返回下标）
来源：http://dali.guannengcc.top/Article/details/gt2srfcbhcp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.smart0.xyz/Article/details/gt2zsnijfct.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guannengcc.top/Article/details/gt2hppxbxef.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shzxlz.cn/Article/details/gt2sawjnokj.html

TS:   // 手写 Map<string, number>
来源：http://dali.hfpthk.cn/Article/details/gt2rnguwqkr.html

Java: // 手写 HashMap
来源：http://dali.gotoacloud.top/Article/details/gt2qpziyllo.html

Go:   // 手写 map[int]int
来源：http://dali.nanxuanxn.top/Article/details/gt2vclbkcux.html

Ruby: // 手写 Hash
来源：http://dali.xylfe.cn/Article/details/gt2htuslkmu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.smart0.xyz/Article/details/gt2yxzxqzks.html

[N08] 生成全排列
来源：http://dali.wangdashe.top/Article/details/gt2cyegwwxd.html

Py:   itertools.permutations(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2komnohnt.html

PHP:  // 手写递归交换
来源：http://dali.c1oappe.top/Article/details/gt2ozvtibig.html

JS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2accwqqzj.html

TS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gt2uotcpzga.html

Java: // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gt2vhtankee.html

Go:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2wtfeugcf.html

Ruby: arr.permutation.to_a
来源：http://dali.zycfv.cn/Article/details/gt2gpdyvkov.html

C#:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gt2upvbhytc.html

[N09] 栈与队列
来源：http://dali.haohaochexian.top/Article/details/gt2zynrcibl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pvftljtl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gt2znesswpi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gt2hnbfncyb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fzhhl.top/Article/details/gt2fvugnynx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gt2oxuizovj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xylfe.cn/Article/details/gt2bsuqvrnd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wrkjrucp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hywenlv.cn/Article/details/gt2jaacbbce.html

[N10] 链表节点定义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nkhprtkr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.bjfxy.top/Article/details/gt2afqqfyie.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rwrblnnj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2urllcxak.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yfmqgjps.html

Java: class Node { int v; Node next; }
来源：http://dali.ppjwa.cn/Article/details/gt2mbpfhhje.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aizwys.cn/Article/details/gt2ippidvbt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ydzc1.top/Article/details/gt2soubdyys.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ivvv.top/Article/details/gt2txiowfsx.html

[N11] 二叉树中序遍历
来源：http://dali.dianchejie.cn/Article/details/gt2mcdmulif.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.quarkkingdee.top/Article/details/gt2ompzexsa.html

PHP:  // 手写递归函数
来源：http://dali.zhongyouzk.top/Article/details/gt2ozxgbvdr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xylfe.cn/Article/details/gt2ubbdugeb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yvedp.cn/Article/details/gt2psmywkdp.html

Java: // 手写递归
来源：http://dali.yj20258888.top/Article/details/gt2wgfbdfpj.html

Go:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gt2sshxkjet.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yueranfly.top/Article/details/gt2elcunilp.html

C#:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gt2tthlkfjm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xylfe.cn/Article/details/gt2fzcmvchd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.9152youxi.cn/Article/details/gt2dyjcxakn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aibaodan.cn/Article/details/gt2ikhpscib.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gt2qdglqosf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gt2deyxbjbu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxinkj.top/Article/details/gt2ydsjvsvy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.svipenyu.cn/Article/details/gt2thcluoxd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gt2seqsehpr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.kuanghao11.cn/Article/details/gt2zcgqznnt.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2mtvoetty.html

O. 并发与异步
来源：http://dali.ydzc1.top/Article/details/gt2aqbftiip.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2ojjufjot.html

[O01] 启动一个线程
来源：http://dali.jinqigufen.top/Article/details/gt2vphggwqg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gzhubu.top/Article/details/gt2vynpxprk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.snrcjt.cn/Article/details/gt2mwobjeqx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jiagoushi.top/Article/details/gt2baufhrej.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nbuqkgvy.html

Java: new Thread(() -> f()).start()
来源：http://dali.gotoacloud.top/Article/details/gt2enwmzlvz.html

Go:   go f()
来源：http://dali.pengpengdd.cyou/Article/details/gt2htnlyrhz.html

Ruby: Thread.new { f }
来源：http://dali.hywenlv.cn/Article/details/gt2gqvwfwuz.html

C#:   Task.Run(() => F());
来源：http://dali.sxryk.cn/Article/details/gt2jdvvsize.html

[O02] 使用线程池
来源：http://dali.redwolf501.top/Article/details/gt2nbbfolcx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigufen.top/Article/details/gt2btnnqsqe.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.andypj.xyz/Article/details/gt2svvygspl.html

JS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gt2omcjpots.html

TS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gt2nnyvjixc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jianghu66.top/Article/details/gt2fcnsqicl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jfjjoqdo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhengqikj.top/Article/details/gt2eahqvywo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cucudq.cn/Article/details/gt2cqjaqfvh.html

[O03] 加锁保护共享数据
来源：http://dali.chenjidiqi.icu/Article/details/gt2bwyhcywj.html

Py:   with lock: shared += 1
来源：http://dali.pycfn.com/Article/details/gt2mbrkpaho.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhoulong.xyz/Article/details/gt2clvozgsw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sufxvd.cn/Article/details/gt2jakeabzi.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gt2opkoijuj.html

Java: synchronized (this) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gt2zqdiwwsw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.haohaochexian.top/Article/details/gt2peccfcso.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.aizwys.cn/Article/details/gt2ubvcmtbq.html

C#:   lock (gate) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2foxwmihg.html

[O04] 定义异步函数并等待
来源：http://dali.andypj.xyz/Article/details/gt2pxgfwywc.html

Py:   async def f():⏎    await g()
来源：http://dali.pycfn.com/Article/details/gt2niaxoxzo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yangfankeji.com/Article/details/gt2pygwonwv.html

JS:   async function f() { await g(); }
来源：http://dali.aibaodan.cn/Article/details/gt2cxhcldke.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gt2plisbydc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sysykeji.top/Article/details/gt2lhzksuqg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.c1oappe.top/Article/details/gt2panttzkr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.redwolf501.top/Article/details/gt2atlxxrjh.html

C#:   async Task F() { await G(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2axwjumcr.html

[O05] 并发执行并等待全部完成
来源：http://dali.fzhhl.top/Article/details/gt2oluiremx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj20258.top/Article/details/gt2bftpcuae.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cqqwz.cn/Article/details/gt2hsezzekr.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ybhuksse.html

TS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gt2aajdyysy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.wangshuangyany.cn/Article/details/gt2dheswiuq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hysaishi.cn/Article/details/gt2siwzxbec.html

Ruby: threads.map(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ejlczhua.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jianghu66.top/Article/details/gt2aayczliq.html

[O06] 使用进程池
来源：http://dali.cqqwz.cn/Article/details/gt2unsxeocp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ydzc1.top/Article/details/gt2mqvhwolr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhoulong.xyz/Article/details/gt2xwvfgiva.html

JS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gt2ztugpjly.html

TS:   // child_process / cluster 模块
来源：http://dali.pengpengdd.cyou/Article/details/gt2iceskxvg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cqqwz.cn/Article/details/gt2euzuqlic.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ydzc1.top/Article/details/gt2cvgurkko.html

Ruby: // fork 块
来源：http://dali.gotoacloud.top/Article/details/gt2kjaoyxxj.html

C#:   Parallel.For
来源：http://dali.gogol.net.cn/Article/details/gt2zabksvxv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2jbnkfnki.html

P. 常用工具函数
来源：http://dali.zhengqikj.top/Article/details/gt2rizlnidi.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2qclkqfei.html

[P01] 生成 UUID
来源：http://dali.hfpthk.cn/Article/details/gt2woaaivyo.html

Py:   str(uuid.uuid4())
来源：http://dali.cdnleiting.top/Article/details/gt2pnoabjxb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cashguo.top/Article/details/gt2covtcleb.html

JS:   crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gt2zveqgtap.html

TS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gt2tacgzzvg.html

Java: UUID.randomUUID().toString()
来源：http://dali.hfpthk.cn/Article/details/gt2wfqpqrwx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuxming.cn/Article/details/gt2mxprwtfe.html

Ruby: SecureRandom.uuid
来源：http://dali.quarkkingdee.top/Article/details/gt2fdvvxfjb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258888.top/Article/details/gt2cojpysyt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cheryme.top/Article/details/gt2eiqwnqej.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenlongwang.top/Article/details/gt2qqjdfcey.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2iszjktls.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2uhppvgoz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ydzc1.top/Article/details/gt2ozoavayf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.svipenyu.cn/Article/details/gt2jtxohazh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.bjfxy.top/Article/details/gt2khdjzhfw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.smart0.xyz/Article/details/gt2dkypobab.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xinyue.icu/Article/details/gt2mohjwpxf.html

[P03] 生成短随机字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2xtwxpnzn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tianlin.xyz/Article/details/gt2juofmyio.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yongpay.top/Article/details/gt2ksudatvg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenzaomai.com/Article/details/gt2muakixpj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2zrwocycf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ushpcdeb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj202588.top/Article/details/gt2ysfbsarb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dianchejie.cn/Article/details/gt2comomtne.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jianghu66.top/Article/details/gt2jabsjjdh.html

[P04] 求长度
来源：http://dali.zhixingplan.top/Article/details/gt2mhicorjt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.9152youxi.cn/Article/details/gt2mckhhval.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gt2lvtkhzuz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gt2erkcwgzg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gt2tjpeqsik.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gaohongyu789.top/Article/details/gt2hojduseq.html

Go:   len(arr);  len(m)
来源：http://dali.guowangkeji.top/Article/details/gt2dzmrratc.html

Ruby: x.length;  x.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zkmshdrs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuanzhike.top/Article/details/gt2vbbsibpr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.aizwys.cn/Article/details/gt2tslfmiai.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cucudq.cn/Article/details/gt2dwmkrtiz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.meibo888.top/Article/details/gt2jwabgnep.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.bjfxy.top/Article/details/gt2sftivskd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2gyhkaxlb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yueranfly.top/Article/details/gt2bgyrsyig.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkhafcr.html

Ruby: a == b
来源：http://dali.daria6918.cn/Article/details/gt2milvhues.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.bjfxy.top/Article/details/gt2kgpkbtcr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sxryk.cn/Article/details/gt2xckiksor.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yuanzhike.top/Article/details/gt2rpmccjlm.html

PHP:  if (empty($x)) {}
来源：http://dali.gogol.net.cn/Article/details/gt2npafvitb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinqigfzy.top/Article/details/gt2sduvcxva.html

TS:   if (x == null) {}
来源：http://dali.ppjwa.cn/Article/details/gt2nlptisec.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gt2sfjpzuwo.html

Go:   if x == nil {}
来源：http://dali.birdmap.top/Article/details/gt2cnmdfuiu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxinkj.top/Article/details/gt2mhsjqelu.html

C#:   if (x is null) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2wuzelibm.html

[P07] 防抖与节流
来源：http://dali.sufxvd.cn/Article/details/gt2nawsaqyo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.havefunace.top/Article/details/gt2nsmqciaz.html

PHP:  // 手写时间戳比较
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ngugffbq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gt2zskqpnkn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gt2qclnysxw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigufen.top/Article/details/gt2ivzhbyyf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lcuvvwyw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.andypj.xyz/Article/details/gt2efuphooy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.feifeiyinyue.top/Article/details/gt2qxlfwnyp.html

[P08] 处理浮点精度问题
来源：http://dali.guowangkeji.top/Article/details/gt2mxiwalwa.html


<!-- 参考信息 -->