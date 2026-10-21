代发 wailian999

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gtxttwyoqx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yonumen.top/Article/details/gtrfzgxckn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gtdcmhkuzp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gtsnlpbuqn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aibaodan.cn/Article/details/gtdeptblah.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.birdmap.top/Article/details/gtgiassknu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgfzy.top/Article/details/gtuqgpmgbn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sweek.top/Article/details/gtycosuals.html

[M04] 获取当前工作目录
来源：http://dali.hywenlv.cn/Article/details/gtloebhjnp.html

Py:   os.getcwd()
来源：http://dali.jinqigfzy.top/Article/details/gtstwyhgpv.html

PHP:  getcwd();
来源：http://dali.jinqigufen.top/Article/details/gteaohfvka.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebopxyrs.html

TS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gtugsuyjxd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zdqjudy.top/Article/details/gtsyjpkhge.html

Go:   os.Getwd()
来源：http://dali.zhengqikj.top/Article/details/gtjhtukhtl.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gthlccsxpk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cheryme.top/Article/details/gtyixhzsiw.html

[M05] 设置退出码
来源：http://dali.ivvv.top/Article/details/gtadhbrmqd.html

Py:   sys.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtvkpevvjl.html

PHP:  exit(1);
来源：http://dali.hnxiangtu.top/Article/details/gttazyubnu.html

JS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtulswjkbo.html

TS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtqeshexxk.html

Java: System.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqsnmlsos.html

Go:   os.Exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtbvdavaik.html

Ruby: exit 1
来源：http://dali.ppjwa.cn/Article/details/gtlqrdciuw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ppjwa.cn/Article/details/gtgqqqcpvk.html

[M06] 向标准错误输出
来源：http://dali.yongpay.top/Article/details/gtktarmcai.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gttpnftooj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cqqwz.cn/Article/details/gtakagqpgo.html

JS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gtvfnrpvpz.html

TS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgadingw.html

Java: System.err.println("err")
来源：http://dali.tianlin.xyz/Article/details/gtwqoffqlb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ybcxt.top/Article/details/gtcfxizqzk.html

Ruby: warn "err"
来源：http://dali.havefunace.top/Article/details/gtulpydtxp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhoulong.xyz/Article/details/gtfgddagon.html

[M07] 判断是否为主入口
来源：http://dali.fzhhl.top/Article/details/gtfhzwmbig.html

Py:   if __name__ == "__main__":
来源：http://dali.chenjidiqi.icu/Article/details/gtcqaulpbx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258.top/Article/details/gtorilvyud.html

JS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gtaqwidwhv.html

TS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gtlxslnllb.html

Java: public static void main(String[] args)
来源：http://dali.nanxinkj.top/Article/details/gtcommeklw.html

Go:   func main()
来源：http://dali.jiagoushi.top/Article/details/gtctstqtst.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nwbrower.top/Article/details/gtxfwkyhpj.html

C#:   static void Main(string[] args)
来源：http://dali.xuanzx.com/Article/details/gtdhwiefdr.html

[M08] 获取系统与运行时信息
来源：http://dali.smart0.xyz/Article/details/gtjyldxfys.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jlsjyb.cn/Article/details/gtjleckyfm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shangyingyoupin.top/Article/details/gtdgeylfga.html

JS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gtgwsatqzx.html

TS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtwlsxffok.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.snrcjt.cn/Article/details/gtekqiwqsl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aibaodan.cn/Article/details/gtzfrdnmwh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.redwolf501.top/Article/details/gtuchsddve.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.birdmap.top/Article/details/gtjptinzdf.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtaytficdp.html

N. 数据结构与算法
来源：http://dali.zdqjudy.top/Article/details/gtlvhtwvdn.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtgcvueysp.html

[N01] 二分查找（有序数组）
来源：http://dali.gogol.net.cn/Article/details/gtaipctjag.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gthpbuadln.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ybcxt.top/Article/details/gtqtiovafo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtbcozyhuq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtbjeoiogx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtaxbezczq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxmnluuk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yueranfly.top/Article/details/gtkdyjbfys.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtjsnwbmqw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tian-w.cn/Article/details/gtemvwptzs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jyoumei.cn/Article/details/gtrllkjxtf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.havefunace.top/Article/details/gtvokffpww.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnbrdmfz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtqympflup.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtatjfltwm.html

Go:   slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gtqozktagm.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gtflkrdnsz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yongpay.top/Article/details/gtbrqjnfsw.html

[N03] 快速排序（分治示例）
来源：http://dali.mhx1999.top/Article/details/gtckkjfnux.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hysaishi.cn/Article/details/gtqhrcfrlw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrhiiubr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuetiantiany.cn/Article/details/gthxnvbjsv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gtudjoqzna.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxuanxn.top/Article/details/gtxxdtzjen.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daxiang520.top/Article/details/gtlntvqtms.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.c1oappe.top/Article/details/gtwrmovtmj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ydzc1.top/Article/details/gturdvdrll.html

[N04] 斐波那契数列
来源：http://dali.yvedp.cn/Article/details/gtgzbhtdug.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hywenlv.cn/Article/details/gtolikmfji.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gtlgjqklxp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtdpgmvddx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtlkkemcrb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gthfgchgfn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.smart0.xyz/Article/details/gtjgikwdnw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gtleoltwyf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtivmrirpo.html

[N05] 最大公约数
来源：http://dali.guannengcc.top/Article/details/gtyiatthen.html

Py:   math.gcd(a, b)
来源：http://dali.gotoacloud.top/Article/details/gtztbxbzrz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj202588.top/Article/details/gtathllyda.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gtecoeribp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gtzayevxtj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.birdmap.top/Article/details/gtueabxelc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xylfe.cn/Article/details/gtpqxthmzn.html

Ruby: a.gcd(b)
来源：http://dali.cqqwz.cn/Article/details/gtagpbqhfy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.316326.xyz/Article/details/gtzysjtnqr.html

[N06] 判断回文字符串
来源：http://dali.jlsjyb.cn/Article/details/gtidyalfyr.html

Py:   s == s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gtridwtctk.html

PHP:  $s === strrev($s);
来源：http://dali.havefunace.top/Article/details/gtoiknwxbu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtwogqjudr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtjldbosvy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gtxvffhzig.html

Go:   // 双指针从两端比较
来源：http://dali.316326.xyz/Article/details/gtbqzmafxz.html

Ruby: s == s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtrazvunaf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aibaodan.cn/Article/details/gtkpptngne.html

[N07] 两数之和（返回下标）
来源：http://dali.tian-w.cn/Article/details/gtajfsqdbf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cdnleiting.top/Article/details/gthfbheqiw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ehwqpu.com/Article/details/gtveelvuxg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tianlin.xyz/Article/details/gtrrptcxil.html

TS:   // 手写 Map<string, number>
来源：http://dali.jiagoushi.top/Article/details/gtswbdzwvo.html

Java: // 手写 HashMap
来源：http://dali.xinyue.icu/Article/details/gtnrzswlgo.html

Go:   // 手写 map[int]int
来源：http://dali.cucudq.cn/Article/details/gtukwsvgze.html

Ruby: // 手写 Hash
来源：http://dali.mhx1999.top/Article/details/gtioqouwbp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.0kj1m.cn/Article/details/gthdmmlccq.html

[N08] 生成全排列
来源：http://dali.chenzaomai.com/Article/details/gtpmuujtxc.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthszbgsfc.html

PHP:  // 手写递归交换
来源：http://dali.cucudq.cn/Article/details/gtdirjrnrr.html

JS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtqcgepkqi.html

TS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtmmosljhu.html

Java: // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtoleptsdu.html

Go:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtaczfofcc.html

Ruby: arr.permutation.to_a
来源：http://dali.yj202588.top/Article/details/gtyvqsgapl.html

C#:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtnwmizbpz.html

[N09] 栈与队列
来源：http://dali.yuanzhike.top/Article/details/gtvvsmaujo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tianlin.xyz/Article/details/gtautzcdcg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangdashe.top/Article/details/gtscwtnghm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gtkbtxbznc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.smart0.xyz/Article/details/gthpmtmfuk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yanxiufei.cn/Article/details/gttfrqfprw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.daria6918.cn/Article/details/gtkuthzplk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtectmpcdz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.smart0.xyz/Article/details/gtpogvxkav.html

[N10] 链表节点定义
来源：http://dali.fzhhl.top/Article/details/gtaxvfuaej.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sxryk.cn/Article/details/gtrtanpblh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.meibo888.top/Article/details/gtwnsamnch.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cucudq.cn/Article/details/gtceagtczr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.feifeiyinyue.top/Article/details/gtrhnndcdl.html

Java: class Node { int v; Node next; }
来源：http://dali.sysykeji.top/Article/details/gtoyxckfzt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gotoacloud.top/Article/details/gtzmupgemb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hammf.cn/Article/details/gtwmugahpl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sxryk.cn/Article/details/gtkkeaxdlj.html

[N11] 二叉树中序遍历
来源：http://dali.316326.xyz/Article/details/gtnamggqys.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.snrcjt.cn/Article/details/gtbsytoora.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gtrchkhgmv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gtitoplpgd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gtmhszgoso.html

Java: // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gtjnsphker.html

Go:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gtfoegwhkx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hfpthk.cn/Article/details/gtqrjxidkp.html

C#:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gthqwdxony.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sufxvd.cn/Article/details/gtekojwmbj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangshuangyany.cn/Article/details/gtgtbjqniu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpmzeuos.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gtypjvntjl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtxavjuqeq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gtztlkaftd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzhxidec.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.birdmap.top/Article/details/gtjyfnvnbf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gtxiskhdol.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtuseetxyv.html

O. 并发与异步
来源：http://dali.snrcjt.cn/Article/details/gtvnvlefgr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtaihvywck.html

[O01] 启动一个线程
来源：http://dali.guannengcc.top/Article/details/gtgmjxdvwe.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fengsongda.top/Article/details/gtibxyrmyx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yonumen.top/Article/details/gtsdqrkhjb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ehwqpu.com/Article/details/gttnmbiekn.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gtyragmupk.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhiwuduotai.top/Article/details/gtnoymgnhj.html

Go:   go f()
来源：http://dali.shanyushiyangtech.top/Article/details/gthouyxddn.html

Ruby: Thread.new { f }
来源：http://dali.mhx1999.top/Article/details/gtrgyiuvmv.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangtech.top/Article/details/gtenahhlkv.html

[O02] 使用线程池
来源：http://dali.yuxming.cn/Article/details/gtilxkwjyv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.daria6918.cn/Article/details/gthwljuybh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.pengpengdd.cyou/Article/details/gtvcpqrwru.html

JS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gtucaypsjg.html

TS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gtznekintk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pycfn.com/Article/details/gthwhufffy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenzaomai.com/Article/details/gthmoorhrd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sxryk.cn/Article/details/gtjuziuaow.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tianlin.xyz/Article/details/gtggdfkhsw.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigufen.top/Article/details/gtemqqxgsq.html

Py:   with lock: shared += 1
来源：http://dali.birdmap.top/Article/details/gtmpbsnozj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ywan-chungtsiang.top/Article/details/gteehlowqb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jlsjyb.cn/Article/details/gtqmumufcq.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gtgryyzsnz.html

Java: synchronized (this) { shared++; }
来源：http://dali.zycfv.cn/Article/details/gtzldcepmq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yueranfly.top/Article/details/gtgbmcehmy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.andypj.xyz/Article/details/gtuejfolne.html

C#:   lock (gate) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gtebxacupg.html

[O04] 定义异步函数并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbudvjkcq.html

Py:   async def f():⏎    await g()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtdtnhgj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj202588.top/Article/details/gttqpegqlk.html

JS:   async function f() { await g(); }
来源：http://dali.aizwys.cn/Article/details/gtcptvjclx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.meibo888.top/Article/details/gtryhxisrp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cashguo.top/Article/details/gtwlpeizik.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nwbrower.top/Article/details/gtgawsyour.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jiagoushi.top/Article/details/gtycokdjmp.html

C#:   async Task F() { await G(); }
来源：http://dali.zycfv.cn/Article/details/gthbrqjglh.html

[O05] 并发执行并等待全部完成
来源：http://dali.iojbl.cn/Article/details/gtmuoycbvg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuanzx.com/Article/details/gtfqswupyy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hongshengwenyu.top/Article/details/gticwwhkzc.html

JS:   await Promise.all(tasks)
来源：http://dali.0kj1m.cn/Article/details/gtqbwtoimx.html

TS:   await Promise.all(tasks)
来源：http://dali.jyoumei.cn/Article/details/gtmgusqpnp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cdnleiting.top/Article/details/gtcqrmbsfy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pengpengdd.cyou/Article/details/gtaiofrmcq.html

Ruby: threads.map(&:join)
来源：http://dali.fzhhl.top/Article/details/gtbkokjtvu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnqzz.top/Article/details/gtltkdwill.html

[O06] 使用进程池
来源：http://dali.gogol.net.cn/Article/details/gtxcvknkmv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.feifeiyinyue.top/Article/details/gtenbohfwc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zycfv.cn/Article/details/gtnsvtyefl.html

JS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gtgwfrkqkc.html

TS:   // child_process / cluster 模块
来源：http://dali.wangdashe.top/Article/details/gtizjtdkvn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daxiang520.top/Article/details/gtuwkipenu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenzaomai.com/Article/details/gtnhebloij.html

Ruby: // fork 块
来源：http://dali.jiagoushi.top/Article/details/gtxsmszqqx.html

C#:   Parallel.For
来源：http://dali.zhoulong.xyz/Article/details/gtdtvxzqgd.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gthfqivrjw.html

P. 常用工具函数
来源：http://dali.gotoacloud.top/Article/details/gtrjwrckiu.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtrhcfobma.html

[P01] 生成 UUID
来源：http://dali.aizwys.cn/Article/details/gtujxkslhu.html

Py:   str(uuid.uuid4())
来源：http://dali.hammf.cn/Article/details/gtorgwutqm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cqqwz.cn/Article/details/gtmbymbcop.html

JS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhfbkeri.html

TS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtoycsyrmn.html

Java: UUID.randomUUID().toString()
来源：http://dali.quarkkingdee.top/Article/details/gtieqxuwis.html

Go:   // 用 github.com/google/uuid
来源：http://dali.kuanghao11.cn/Article/details/gtiqhowzay.html

Ruby: SecureRandom.uuid
来源：http://dali.quarkkingdee.top/Article/details/gtiexamxkf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxinkj.top/Article/details/gteksyxdon.html

[P02] MD5 / SHA256 摘要
来源：http://dali.haohaochexian.top/Article/details/gtldpftcjt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.guowangkeji.top/Article/details/gtnchksdcj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ivvv.top/Article/details/gthiqbbjdo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.fengsongda.top/Article/details/gtsyauyhis.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigfzy.top/Article/details/gtpfrnhply.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj202588.top/Article/details/gtsocxdxyi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yanxiufei.cn/Article/details/gtrvchtutg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuanzx.com/Article/details/gtkiejhywz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ivvv.top/Article/details/gtwrdwtqog.html

[P03] 生成短随机字符串
来源：http://dali.jiagoushi.top/Article/details/gtetjlbcxz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.svipenyu.cn/Article/details/gtemrvebex.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jiagoushi.top/Article/details/gtjeoifctj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dianchejie.cn/Article/details/gtvwjjmsaz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gtoppebabo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guannengcc.top/Article/details/gttoetyoiw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.andypj.xyz/Article/details/gtjosgqtgb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gogol.net.cn/Article/details/gtvcgpqlbh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nanxinkj.top/Article/details/gtbmnvavgj.html

[P04] 求长度
来源：http://dali.jiagoushi.top/Article/details/gthzupkyei.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenjidiqi.icu/Article/details/gtozgddjlq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtwauwtcry.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258888.top/Article/details/gtumrmuaaz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.havefunace.top/Article/details/gtqdzwnzac.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hysaishi.cn/Article/details/gtjmpoxebq.html

Go:   len(arr);  len(m)
来源：http://dali.yanxiufei.cn/Article/details/gtsbzsuduq.html

Ruby: x.length;  x.size
来源：http://dali.fengsongda.top/Article/details/gtlwmmpdjj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.iojbl.cn/Article/details/gtcveohowy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gaohongyu789.top/Article/details/gterqfhfcu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinghuilouyu.cn/Article/details/gtxccqxqvt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.havefunace.top/Article/details/gtvubaijbo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hnqzz.top/Article/details/gtvmggeich.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jlsjyb.cn/Article/details/gtxkwenxnt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.snrcjt.cn/Article/details/gtifripbhg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtsbksixjd.html

Ruby: a == b
来源：http://dali.yonumen.top/Article/details/gtpumjjwwz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yanxiufei.cn/Article/details/gtmhwjgnwh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvoybwabx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.smart0.xyz/Article/details/gtfwntgbph.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigfzy.top/Article/details/gtsbyvwshz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.wangshuangyany.cn/Article/details/gttbhdyexj.html

TS:   if (x == null) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtquctckvu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gtgubqrxdr.html

Go:   if x == nil {}
来源：http://dali.zhixingplan.top/Article/details/gttnevxjob.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aizwys.cn/Article/details/gtabhzkddp.html

C#:   if (x is null) {}
来源：http://dali.ydzc1.top/Article/details/gtsopifhqq.html

[P07] 防抖与节流
来源：http://dali.9152youxi.cn/Article/details/gtmdgjzxms.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.bjfxy.top/Article/details/gtkorxujcu.html

PHP:  // 手写时间戳比较
来源：http://dali.xuetiantiany.cn/Article/details/gtytyyfpfs.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtdttgxjlt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtivtyvrdu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtiyouhsko.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenlongwang.top/Article/details/gteonfynhn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yongpay.top/Article/details/gtmwvbtwcx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cucudq.cn/Article/details/gtaatzwtee.html

[P08] 处理浮点精度问题
来源：http://dali.haohaochexian.top/Article/details/gtlxxvzflc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258.top/Article/details/gtqxkidscr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xinyue.icu/Article/details/gtoqzqafwr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuanzx.com/Article/details/gtuwvywvql.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gtabtaeqdm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.iojbl.cn/Article/details/gtyebbmwxc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.svipenyu.cn/Article/details/gtekhcijkw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.haohaochexian.top/Article/details/gtyrvuegte.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dianchejie.cn/Article/details/gtyozykfwr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtybpewoqe.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhongyouzk.top/Article/details/gtnomyxzrx.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gthqrfgfml.html

[Q01] 创建表
来源：http://dali.hongshengwenyu.top/Article/details/gtwnhtrlty.html


<!-- 参考信息 -->