代发 wailian999

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gt2lwwyjnqh.html

Ruby: ENV["HOME"]
来源：http://dali.dianchejie.cn/Article/details/gt2jxgblfpp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2ygwoekii.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gt2rmmsurcb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.c1oappe.top/Article/details/gt2ukgogehl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yanxiufei.cn/Article/details/gt2somsehtb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gt2dyjwmaqa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gt2smahygsk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqrcudyb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tanke756.top/Article/details/gt2lmitqmlp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ybcxt.top/Article/details/gt2sksjgsms.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnqzz.top/Article/details/gt2hislybzo.html

[M04] 获取当前工作目录
来源：http://dali.fzhhl.top/Article/details/gt2wftavcsm.html

Py:   os.getcwd()
来源：http://dali.aizwys.cn/Article/details/gt2txsrgqoc.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gt2wfexbgfg.html

JS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gt2xlwcgrri.html

TS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gt2aoddmyro.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenjidiqi.icu/Article/details/gt2pdfhnakz.html

Go:   os.Getwd()
来源：http://dali.hammf.cn/Article/details/gt2pmcfrury.html

Ruby: Dir.pwd
来源：http://dali.snrcjt.cn/Article/details/gt2icyqmvap.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.birdmap.top/Article/details/gt2kvdhsfvc.html

[M05] 设置退出码
来源：http://dali.hammf.cn/Article/details/gt2kgvrhkgc.html

Py:   sys.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2vrkepond.html

PHP:  exit(1);
来源：http://dali.yuxming.cn/Article/details/gt2mdtqnimt.html

JS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2swsdjnxx.html

TS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wgwzradu.html

Java: System.exit(1)
来源：http://dali.ybcxt.top/Article/details/gt2gaqxmyqz.html

Go:   os.Exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kudwxgez.html

Ruby: exit 1
来源：http://dali.yongpay.top/Article/details/gt2lxgytqwi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shuidangran.top/Article/details/gt2czpjnyaz.html

[M06] 向标准错误输出
来源：http://dali.nanxinkj.top/Article/details/gt2ygwvnyvi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxuanxn.top/Article/details/gt2fjoklfgf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxuanxn.top/Article/details/gt2dgapuclw.html

JS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gt2oqjnxpai.html

TS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gt2cauuzbuo.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqkfogcc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.guowangkeji.top/Article/details/gt2hvyyeyju.html

Ruby: warn "err"
来源：http://dali.316326.xyz/Article/details/gt2aznzzfph.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhengqikj.top/Article/details/gt2wzbxwuoi.html

[M07] 判断是否为主入口
来源：http://dali.xziqi.cn/Article/details/gt2xwayfzee.html

Py:   if __name__ == "__main__":
来源：http://dali.nwbrower.top/Article/details/gt2ibjcflkc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ivvv.top/Article/details/gt2tzulhuzn.html

JS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gt2syqqekgr.html

TS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gt2rbjopyry.html

Java: public static void main(String[] args)
来源：http://dali.shzxlz.cn/Article/details/gt2ueuzzooa.html

Go:   func main()
来源：http://dali.jyoumei.cn/Article/details/gt2jfqsvkhh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.smart0.xyz/Article/details/gt2gtfspnkr.html

C#:   static void Main(string[] args)
来源：http://dali.sufxvd.cn/Article/details/gt2mklabuxv.html

[M08] 获取系统与运行时信息
来源：http://dali.snrcjt.cn/Article/details/gt2zpfupctv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pycfn.com/Article/details/gt2fcyzsftp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuanzhike.top/Article/details/gt2pwbydrhd.html

JS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gt2vvrndjfk.html

TS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gt2qlycinif.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xylfe.cn/Article/details/gt2uqarbpdg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tian-w.cn/Article/details/gt2eigjphgr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yueranfly.top/Article/details/gt2atushfsr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ybcxt.top/Article/details/gt2nghhcill.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2ujzdhwwu.html

N. 数据结构与算法
来源：http://dali.yuxming.cn/Article/details/gt2intgszbx.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2dsnintwn.html

[N01] 二分查找（有序数组）
来源：http://dali.feifeiyinyue.top/Article/details/gt2uzaphbaz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2duggaucc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ybcxt.top/Article/details/gt2lsvcaqbd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vylgvfqj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gt2aeaedgwr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ulewvezx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2enjlkhcs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258.top/Article/details/gt2ehqjadwn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2rvacamso.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyezivf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gt2ppcripmp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shuidangran.top/Article/details/gt2nngqifcy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gt2zknobgno.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gt2mfhfjswg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangdashe.top/Article/details/gt2vdrppapd.html

Go:   slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2yuomsxew.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gt2ejffqbzs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.kuanghao11.cn/Article/details/gt2qcugujmd.html

[N03] 快速排序（分治示例）
来源：http://dali.shangyingyoupin.top/Article/details/gt2nhjrtgno.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aizwys.cn/Article/details/gt2hhnbsnyc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rorpyetb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zdqjudy.top/Article/details/gt2vsjwbqhg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gt2yivlnenc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuanzx.com/Article/details/gt2nutsbwcq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xziqi.cn/Article/details/gt2bujisetc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigufen.top/Article/details/gt2vcdepdth.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cashguo.top/Article/details/gt2vbapmyam.html

[N04] 斐波那契数列
来源：http://dali.shangyingyoupin.top/Article/details/gt2mmqaiyzw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gt2vwmewfcy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gt2emnifjyf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2znioyvra.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gt2bqoesweb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pycfn.com/Article/details/gt2cftzhohp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenlongwang.top/Article/details/gt2wtuimknn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gt2zukscxqn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gt2pewheivp.html

[N05] 最大公约数
来源：http://dali.havefunace.top/Article/details/gt2pwnnyzal.html

Py:   math.gcd(a, b)
来源：http://dali.yuxming.cn/Article/details/gt2cxgegspf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ijadwupy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gt2oykjfita.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gt2czylebox.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.mhx1999.top/Article/details/gt2wdgimhqo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shzxlz.cn/Article/details/gt2lvldhtnv.html

Ruby: a.gcd(b)
来源：http://dali.gzhubu.top/Article/details/gt2eaycoyxm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuanzhike.top/Article/details/gt2ziqhuasc.html

[N06] 判断回文字符串
来源：http://dali.cucudq.cn/Article/details/gt2luekahuf.html

Py:   s == s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gt2stxwbvxf.html

PHP:  $s === strrev($s);
来源：http://dali.yonumen.top/Article/details/gt2ktmnqrdm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gt2vuriakbd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2dkhbcesl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hywenlv.cn/Article/details/gt2qiszeptf.html

Go:   // 双指针从两端比较
来源：http://dali.jyoumei.cn/Article/details/gt2zjlvcxvt.html

Ruby: s == s.reverse
来源：http://dali.jianghu66.top/Article/details/gt2ypefvhll.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenlongwang.top/Article/details/gt2dmgflpbz.html

[N07] 两数之和（返回下标）
来源：http://dali.dashuyun.cn/Article/details/gt2hmfxoulv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.quarkkingdee.top/Article/details/gt2otpbyfvq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tanke756.top/Article/details/gt2cntbssyf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2escxeipt.html

TS:   // 手写 Map<string, number>
来源：http://dali.yonumen.top/Article/details/gt2uqflaysi.html

Java: // 手写 HashMap
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bfsojlgo.html

Go:   // 手写 map[int]int
来源：http://dali.snrcjt.cn/Article/details/gt2jbrjtuco.html

Ruby: // 手写 Hash
来源：http://dali.tianlin.xyz/Article/details/gt2gyaqimdd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2swwcvfma.html

[N08] 生成全排列
来源：http://dali.ydzc1.top/Article/details/gt2bvjbxvgj.html

Py:   itertools.permutations(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2folsjdjj.html

PHP:  // 手写递归交换
来源：http://dali.nwbrower.top/Article/details/gt2dmnthuur.html

JS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gt2uraiovgu.html

TS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gt2qdypuody.html

Java: // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2ldylujwk.html

Go:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gt2hegybbmp.html

Ruby: arr.permutation.to_a
来源：http://dali.zdqjudy.top/Article/details/gt2cfzeogwh.html

C#:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gt2sxtoqgqf.html

[N09] 栈与队列
来源：http://dali.shzxlz.cn/Article/details/gt2piavqctx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhengqikj.top/Article/details/gt2dyeaefns.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shuidangran.top/Article/details/gt2apkdigse.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gt2xyyeznhd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxuanxn.top/Article/details/gt2kimyfoos.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daria6918.cn/Article/details/gt2eqcvpeki.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shzxlz.cn/Article/details/gt2dmbgtmtn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gt2vgycaijg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.9152youxi.cn/Article/details/gt2fkyfrcel.html

[N10] 链表节点定义
来源：http://dali.mhx1999.top/Article/details/gt2nswffktd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cdnleiting.top/Article/details/gt2extghxag.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.pycfn.com/Article/details/gt2twjhxrzk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guannengcc.top/Article/details/gt2euquvesm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ydzc1.top/Article/details/gt2danadqpk.html

Java: class Node { int v; Node next; }
来源：http://dali.hywenlv.cn/Article/details/gt2huncpbhz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cqqwz.cn/Article/details/gt2rxhuqucl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.birdmap.top/Article/details/gt2okowozxx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gzhubu.top/Article/details/gt2yzmaikii.html

[N11] 二叉树中序遍历
来源：http://dali.zdqjudy.top/Article/details/gt2ldbpqyyb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.haohaochexian.top/Article/details/gt2qjwjzvou.html

PHP:  // 手写递归函数
来源：http://dali.hammf.cn/Article/details/gt2lcrdqvvn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gt2rqcnskhj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2npdqaybm.html

Java: // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2ikkxxybt.html

Go:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gt2lwfjiacz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ivvv.top/Article/details/gt2kbxanjkb.html

C#:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gt2ofvyltmr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.vqdsnc.cn/Article/details/gt2xfblpbdx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yongpay.top/Article/details/gt2jfvphggl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yvedp.cn/Article/details/gt2kpithftg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sufxvd.cn/Article/details/gt2zfsnrlmb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.9152youxi.cn/Article/details/gt2hzcuvcxo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gt2mcbuuqyv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ivvv.top/Article/details/gt2utyfiqtj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ybcxt.top/Article/details/gt2vewdbulx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gt2tufomnwv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dzszvsfx.html

O. 并发与异步
来源：http://dali.cashguo.top/Article/details/gt2qwlkvcox.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2dyaibqvw.html

[O01] 启动一个线程
来源：http://dali.svipenyu.cn/Article/details/gt2kadmeblq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jiagoushi.top/Article/details/gt2bxyxhrsk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aibaodan.cn/Article/details/gt2smxmmhhw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhoulong.xyz/Article/details/gt2gwvfqutf.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gt2rnnwiotb.html

Java: new Thread(() -> f()).start()
来源：http://dali.aibaodan.cn/Article/details/gt2otqrydtz.html

Go:   go f()
来源：http://dali.yonumen.top/Article/details/gt2gsfcadqq.html

Ruby: Thread.new { f }
来源：http://dali.316326.xyz/Article/details/gt2mkeduuum.html

C#:   Task.Run(() => F());
来源：http://dali.nanxuanxn.top/Article/details/gt2kavnbmas.html

[O02] 使用线程池
来源：http://dali.tian-w.cn/Article/details/gt2ksxdfbrn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aibaodan.cn/Article/details/gt2lcrqjsex.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cdnleiting.top/Article/details/gt2vhxcpasb.html

JS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gt2wsgkrwjf.html

TS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gt2inydwjft.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jlsjyb.cn/Article/details/gt2bghwwxgp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shuidangran.top/Article/details/gt2yufekjap.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daxiang520.top/Article/details/gt2dridrzxd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhoulong.xyz/Article/details/gt2yakmnkfi.html

[O03] 加锁保护共享数据
来源：http://dali.fengsongda.top/Article/details/gt2qflddpto.html

Py:   with lock: shared += 1
来源：http://dali.wangdashe.top/Article/details/gt2gfxyzwck.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.mhx1999.top/Article/details/gt2qsukjrlf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sysykeji.top/Article/details/gt2ttzlbuaf.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gt2xauaoksk.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gt2kkvmosuk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jyoumei.cn/Article/details/gt2ajudaiuh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gaohongyu789.top/Article/details/gt2uvoqofyk.html

C#:   lock (gate) { shared++; }
来源：http://dali.tanke756.top/Article/details/gt2qlllridu.html

[O04] 定义异步函数并等待
来源：http://dali.jlsjyb.cn/Article/details/gt2uxxajjvo.html

Py:   async def f():⏎    await g()
来源：http://dali.9152youxi.cn/Article/details/gt2lswutwwk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.aizwys.cn/Article/details/gt2xiogvkeg.html

JS:   async function f() { await g(); }
来源：http://dali.hywenlv.cn/Article/details/gt2ddwublge.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.daria6918.cn/Article/details/gt2fyxcamwf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhoulong.xyz/Article/details/gt2wfxquikn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhixingplan.top/Article/details/gt2svuplwhn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.iojbl.cn/Article/details/gt2vugrugbq.html

C#:   async Task F() { await G(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nyyjxkyi.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhixingplan.top/Article/details/gt2seinzplo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhixingplan.top/Article/details/gt2otimevmn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yueranfly.top/Article/details/gt2hebeejvg.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gt2jehiscjm.html

TS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gt2ykwfbfez.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aibaodan.cn/Article/details/gt2wrfcgkmq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gogol.net.cn/Article/details/gt2conygkdj.html

Ruby: threads.map(&:join)
来源：http://dali.zycfv.cn/Article/details/gt2cswoekzj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.snrcjt.cn/Article/details/gt2tqdpdcsp.html

[O06] 使用进程池
来源：http://dali.hnxiangtu.top/Article/details/gt2fzwujuqu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yueranfly.top/Article/details/gt2pluulkpu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.aizwys.cn/Article/details/gt2czyimykk.html

JS:   // child_process / cluster 模块
来源：http://dali.jyoumei.cn/Article/details/gt2aixetdpc.html

TS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gt2huudmaoc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.vqdsnc.cn/Article/details/gt2hhiyttfn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yuxming.cn/Article/details/gt2sgthxfto.html

Ruby: // fork 块
来源：http://dali.daria6918.cn/Article/details/gt2sympuesf.html

C#:   Parallel.For
来源：http://dali.gogol.net.cn/Article/details/gt2hejifugh.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2mfuxhfxi.html

P. 常用工具函数
来源：http://dali.iojbl.cn/Article/details/gt2kkbnpjap.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2neclttkr.html

[P01] 生成 UUID
来源：http://dali.aibaodan.cn/Article/details/gt2hqrwawgw.html

Py:   str(uuid.uuid4())
来源：http://dali.yuanzhike.top/Article/details/gt2pwratdho.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guannengcc.top/Article/details/gt2bnapquye.html

JS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gt2akkdswgl.html

TS:   crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gt2elvnnsdb.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhongyouzk.top/Article/details/gt2fplxhulu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuanzhike.top/Article/details/gt2hyavxavk.html

Ruby: SecureRandom.uuid
来源：http://dali.316326.xyz/Article/details/gt2aeinvkuw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.snrcjt.cn/Article/details/gt2pcangruh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.meibo888.top/Article/details/gt2dpnnrqtt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hnxiangtu.top/Article/details/gt2ogzqdvwo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj202588.top/Article/details/gt2rocznhpr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yanxiufei.cn/Article/details/gt2tophqazw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangshuangyany.cn/Article/details/gt2nxzxqbjy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjnrmpk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2xzutusvq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhixingplan.top/Article/details/gt2miidqbor.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hfpthk.cn/Article/details/gt2hjvdazft.html

[P03] 生成短随机字符串
来源：http://dali.fengsongda.top/Article/details/gt2yujghanq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258.top/Article/details/gt2wgizozao.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zdqjudy.top/Article/details/gt2leeiahmx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2wkknhnyi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nclqcold.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhengqikj.top/Article/details/gt2dcwxzdlv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yueranfly.top/Article/details/gt2lednvwnr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuanzx.com/Article/details/gt2wbivrewx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhengqikj.top/Article/details/gt2bknnxlas.html

[P04] 求长度
来源：http://dali.yangfankeji.com/Article/details/gt2obdvrdis.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hongshengwenyu.top/Article/details/gt2exsdyfki.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gt2vznesccv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aibaodan.cn/Article/details/gt2czrwxuxq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.svipenyu.cn/Article/details/gt2hkzpcssp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yangfankeji.com/Article/details/gt2zoctfqlv.html

Go:   len(arr);  len(m)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ixloljmm.html

Ruby: x.length;  x.size
来源：http://dali.aibaodan.cn/Article/details/gt2ymuynvrn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uxztirrd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jqgufenzy.top/Article/details/gt2nvflohfd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenjidiqi.icu/Article/details/gt2qiuqjdhs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hfpthk.cn/Article/details/gt2odbwegou.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.mhx1999.top/Article/details/gt2cskpbqox.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gt2eckhhkqp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.mhx1999.top/Article/details/gt2wetcegeq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.snrcjt.cn/Article/details/gt2sbmlcfyh.html

Ruby: a == b
来源：http://dali.kuanghao11.cn/Article/details/gt2orvmuooo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jlsjyb.cn/Article/details/gt2evcoqrdk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.c1oappe.top/Article/details/gt2kchmltjf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gilkwgqs.html

PHP:  if (empty($x)) {}
来源：http://dali.gogol.net.cn/Article/details/gt2kaajkqhl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yanxiufei.cn/Article/details/gt2xlsecjbm.html

TS:   if (x == null) {}
来源：http://dali.jianghu66.top/Article/details/gt2enizaadn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gt2lgtnjinn.html

Go:   if x == nil {}
来源：http://dali.ivvv.top/Article/details/gt2atlsxcqz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oclietkq.html

C#:   if (x is null) {}
来源：http://dali.dianchejie.cn/Article/details/gt2pwoqqmgf.html

[P07] 防抖与节流
来源：http://dali.0kj1m.cn/Article/details/gt2xmfrzkgu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ivvv.top/Article/details/gt2gteltooq.html

PHP:  // 手写时间戳比较
来源：http://dali.sxryk.cn/Article/details/gt2skpflwey.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gt2bwzhgnue.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gt2xudjtass.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tianlin.xyz/Article/details/gt2ulqaulsh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tianlin.xyz/Article/details/gt2zjcsvhjr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jlsjyb.cn/Article/details/gt2lmthsefk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cmtbhcde.html

[P08] 处理浮点精度问题
来源：http://dali.chenlongwang.top/Article/details/gt2doeurkpa.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.iojbl.cn/Article/details/gt2nienecek.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ehwqpu.com/Article/details/gt2ckqaucea.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xziqi.cn/Article/details/gt2jdgarnxy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yvedp.cn/Article/details/gt2srsunosg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tian-w.cn/Article/details/gt2annrlazr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuxming.cn/Article/details/gt2lxkadruc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hfpthk.cn/Article/details/gt2lqasijwd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nwbrower.top/Article/details/gt2idqudnbi.html


<!-- 参考信息 -->