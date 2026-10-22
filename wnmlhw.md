代发 wailian999

Ruby: ARGV
来源：http://dali.cucudq.cn/Article/details/gttlaymkcb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gtqqevuima.html

[M02] 读取环境变量
来源：http://dali.sweek.top/Article/details/gteyszfvfy.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzddgvrlf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtztwmyedx.html

JS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gthnmrquio.html

TS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gtxrmhkzfv.html

Java: System.getenv("HOME")
来源：http://dali.yueranfly.top/Article/details/gtlyrfxnnd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtnkbxuhov.html

Ruby: ENV["HOME"]
来源：http://dali.dianchejie.cn/Article/details/gtgckfbxth.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtifzdvfnk.html

[M03] 执行外部命令
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfipgeqad.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhengqikj.top/Article/details/gtmlpdrjqh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jyoumei.cn/Article/details/gtrxmvaebc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtzxdvlbmg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gtzbsqjtak.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hfpthk.cn/Article/details/gtrhnquraw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuxming.cn/Article/details/gthkloxikc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenzaomai.com/Article/details/gtyeaioyat.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkurnaeob.html

[M04] 获取当前工作目录
来源：http://dali.iojbl.cn/Article/details/gtpxsilihh.html

Py:   os.getcwd()
来源：http://dali.andypj.xyz/Article/details/gtjbqciyvf.html

PHP:  getcwd();
来源：http://dali.pengpengdd.cyou/Article/details/gtiukcrixv.html

JS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gtxxnektue.html

TS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gtytgshpfd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pengpengdd.cyou/Article/details/gteiplslfp.html

Go:   os.Getwd()
来源：http://dali.redwolf501.top/Article/details/gtuxawyeuq.html

Ruby: Dir.pwd
来源：http://dali.cqqwz.cn/Article/details/gtmiduhwkn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdmdrrnt.html

[M05] 设置退出码
来源：http://dali.chenjidiqi.icu/Article/details/gtjhalidqz.html

Py:   sys.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtwqvrijoi.html

PHP:  exit(1);
来源：http://dali.sysykeji.top/Article/details/gtraogazxk.html

JS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtqfdcpfck.html

TS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtmfnkvaih.html

Java: System.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtwdyjsykn.html

Go:   os.Exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtbuoeunzm.html

Ruby: exit 1
来源：http://dali.ehwqpu.com/Article/details/gtjmybrmvf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zdqjudy.top/Article/details/gtjwpeokbr.html

[M06] 向标准错误输出
来源：http://dali.havefunace.top/Article/details/gtinemcnhx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gtmglxzvfz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhixingplan.top/Article/details/gtujzpsmex.html

JS:   console.error("err")
来源：http://dali.gotoacloud.top/Article/details/gtpmnlcnaj.html

TS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gtwprcwddq.html

Java: System.err.println("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjdukmvn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.quarkkingdee.top/Article/details/gtxglgwpla.html

Ruby: warn "err"
来源：http://dali.jianghu66.top/Article/details/gtblyilxvu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuftejchh.html

[M07] 判断是否为主入口
来源：http://dali.yj20258888.top/Article/details/gtxvvucwcr.html

Py:   if __name__ == "__main__":
来源：http://dali.gzhubu.top/Article/details/gtrgemdreb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gtobjcinlh.html

JS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtbqrxjuvf.html

TS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtrkhhyaty.html

Java: public static void main(String[] args)
来源：http://dali.iojbl.cn/Article/details/gtfpiibxli.html

Go:   func main()
来源：http://dali.ehwqpu.com/Article/details/gtshsvxeyk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenzaomai.com/Article/details/gtwwqeqqqx.html

C#:   static void Main(string[] args)
来源：http://dali.chenlongwang.top/Article/details/gtfbtsxiar.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxinkj.top/Article/details/gthtyreuiv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hfpthk.cn/Article/details/gtmtecteir.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sysykeji.top/Article/details/gtasjuzynt.html

JS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gtzigtdztv.html

TS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gtqxexaoxz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jianghu66.top/Article/details/gternorkdk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nwbrower.top/Article/details/gthitzdfae.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yanxiufei.cn/Article/details/gtwtoeltad.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhongyouzk.top/Article/details/gtvqkljohd.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtsvaotfeb.html

N. 数据结构与算法
来源：http://dali.tanke756.top/Article/details/gtxfjxvuri.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gttsxtwlwe.html

[N01] 二分查找（有序数组）
来源：http://dali.birdmap.top/Article/details/gtmldczlla.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtbvydylqb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daxiang520.top/Article/details/gtxgrihzxv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gtdfmfhasx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gttxvpvcur.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtbabczrbx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtgvnmwvcf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypsbikaj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtyqtfhnvc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.redwolf501.top/Article/details/gtghnxwrur.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gtsxqhqfxn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yueranfly.top/Article/details/gtfofiecsw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gtdpoabpcg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtidhgrwbq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ppjwa.cn/Article/details/gtsozyqzio.html

Go:   slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gtyiguzsly.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gtzusplvwl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtvwoxglzy.html

[N03] 快速排序（分治示例）
来源：http://dali.yuxming.cn/Article/details/gtpdtbxrqn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jianghu66.top/Article/details/gttuhckodl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.snrcjt.cn/Article/details/gtqevdgrlp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tian-w.cn/Article/details/gtrsaxrnwo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gtfwupphbw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yvedp.cn/Article/details/gtvewzihiv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sysykeji.top/Article/details/gtccgqraqw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.kuanghao11.cn/Article/details/gtnhntazya.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgfzy.top/Article/details/gtjgtstoiz.html

[N04] 斐波那契数列
来源：http://dali.hysaishi.cn/Article/details/gtykfioroz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gtkcgcfnyc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoizzxxdq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtjrfihjgp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtzvxuxrqb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.316326.xyz/Article/details/gtaechiotp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yueranfly.top/Article/details/gtwurhmsdw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtbgrjdfll.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtsfywmumj.html

[N05] 最大公约数
来源：http://dali.zhongyouzk.top/Article/details/gtrucxahxq.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gtlzdbxbzq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpjkzzzr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gtnhlphrkx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gtftbqtzgf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guannengcc.top/Article/details/gtfxgwqgse.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gotoacloud.top/Article/details/gtavynaiis.html

Ruby: a.gcd(b)
来源：http://dali.svipenyu.cn/Article/details/gtwnsvqubn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.pycfn.com/Article/details/gtuqbucjvs.html

[N06] 判断回文字符串
来源：http://dali.hywenlv.cn/Article/details/gtvmswgecg.html

Py:   s == s[::-1]
来源：http://dali.daxiang520.top/Article/details/gtztkzvtsg.html

PHP:  $s === strrev($s);
来源：http://dali.hammf.cn/Article/details/gtbauwehwu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtbbbfylaa.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtnbrxznth.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangdashe.top/Article/details/gtfhyeczrc.html

Go:   // 双指针从两端比较
来源：http://dali.zhixingplan.top/Article/details/gtyjbkdozz.html

Ruby: s == s.reverse
来源：http://dali.mhx1999.top/Article/details/gthldwtgta.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gtfvqjxzey.html

[N07] 两数之和（返回下标）
来源：http://dali.kuanghao11.cn/Article/details/gtpduzslof.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sxryk.cn/Article/details/gtdsyrvntd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ehwqpu.com/Article/details/gtedtsylbe.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.haohaochexian.top/Article/details/gtxtmgzjqs.html

TS:   // 手写 Map<string, number>
来源：http://dali.yanxiufei.cn/Article/details/gtxaobndxd.html

Java: // 手写 HashMap
来源：http://dali.jinqigfzy.top/Article/details/gtkmzmyvjb.html

Go:   // 手写 map[int]int
来源：http://dali.wangdashe.top/Article/details/gthucmkhft.html

Ruby: // 手写 Hash
来源：http://dali.jyoumei.cn/Article/details/gthnvawepf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tianlin.xyz/Article/details/gtkuskgnek.html

[N08] 生成全排列
来源：http://dali.wangshuangyany.cn/Article/details/gtdhtxhoaz.html

Py:   itertools.permutations(arr)
来源：http://dali.shuidangran.top/Article/details/gtundsgasb.html

PHP:  // 手写递归交换
来源：http://dali.fzhhl.top/Article/details/gtkoxanknh.html

JS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtldpmjpkd.html

TS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtctujgnta.html

Java: // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtamfriksl.html

Go:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixyjvokg.html

Ruby: arr.permutation.to_a
来源：http://dali.shzxlz.cn/Article/details/gthwiwtpig.html

C#:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtkzykaeqz.html

[N09] 栈与队列
来源：http://dali.bjfxy.top/Article/details/gtmjlmsdwd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258888.top/Article/details/gtmqqagsct.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtzalvqumz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtknzoxpne.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangdashe.top/Article/details/gtipcoquye.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sxryk.cn/Article/details/gteyjtdvch.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangshuangyany.cn/Article/details/gtkyneazqs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gteozizdby.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cdnleiting.top/Article/details/gtfmvkolzv.html

[N10] 链表节点定义
来源：http://dali.sufxvd.cn/Article/details/gtfnuaqtqg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.havefunace.top/Article/details/gtszxlwxlz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gtngbjtbii.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jyoumei.cn/Article/details/gtajpuyemg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gzhubu.top/Article/details/gtotczhxws.html

Java: class Node { int v; Node next; }
来源：http://dali.yanxiufei.cn/Article/details/gtdwlauqgs.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tianlin.xyz/Article/details/gtesdukprb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.meibo888.top/Article/details/gtjezwffqe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnxiangtu.top/Article/details/gtwzevvxwu.html

[N11] 二叉树中序遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwflbubig.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.feifeiyinyue.top/Article/details/gtaebvdfls.html

PHP:  // 手写递归函数
来源：http://dali.zhengqikj.top/Article/details/gtyhonqekl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yueranfly.top/Article/details/gtpojigmjz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gtleakcgax.html

Java: // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtzilrkjkp.html

Go:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gtxdbiyzor.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenlongwang.top/Article/details/gtwxouugar.html

C#:   // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gtprtevasp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daria6918.cn/Article/details/gtzosyhlou.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj202588.top/Article/details/gtwyhfbscz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cucudq.cn/Article/details/gtutmydwvq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.quarkkingdee.top/Article/details/gtcfirswmq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gtegxncmgu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gtfabmmbae.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tanke756.top/Article/details/gtvrjldtmw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gaohongyu789.top/Article/details/gtkjjbokjs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gtqgsuckzv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysrloyru.html

O. 并发与异步
来源：http://dali.svipenyu.cn/Article/details/gtisdsikko.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtvinltquu.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gtjskjwnoy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cheryme.top/Article/details/gtlxsfeyrc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yongpay.top/Article/details/gtvygpzyvc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yanxiufei.cn/Article/details/gtkkrxvkbs.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gtnuiqszsf.html

Java: new Thread(() -> f()).start()
来源：http://dali.shzxlz.cn/Article/details/gtoktmwnob.html

Go:   go f()
来源：http://dali.ydzc1.top/Article/details/gtbubeqyrt.html

Ruby: Thread.new { f }
来源：http://dali.quarkkingdee.top/Article/details/gtiqxmcxvo.html

C#:   Task.Run(() => F());
来源：http://dali.zhoulong.xyz/Article/details/gtdrxynboy.html

[O02] 使用线程池
来源：http://dali.sweek.top/Article/details/gtcprauxrk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhixingplan.top/Article/details/gtkcjpjghw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gtztozcyjr.html

JS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gtswcjxnmy.html

TS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gtblmhzfii.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guannengcc.top/Article/details/gtribjwnoi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.vqdsnc.cn/Article/details/gtcdcehlwn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhoulong.xyz/Article/details/gttkblxuem.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shuidangran.top/Article/details/gtchlokpxw.html

[O03] 加锁保护共享数据
来源：http://dali.yueranfly.top/Article/details/gtvwvkcifa.html

Py:   with lock: shared += 1
来源：http://dali.tianlin.xyz/Article/details/gtfvmymelh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gogol.net.cn/Article/details/gtqccsyfip.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.andypj.xyz/Article/details/gtjqpqogfx.html

TS:   // 同 JS
来源：http://dali.c1oappe.top/Article/details/gtnqdasuol.html

Java: synchronized (this) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gtmbopvxpv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jlsjyb.cn/Article/details/gtuoyziunb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yanxiufei.cn/Article/details/gtzgtotsdj.html

C#:   lock (gate) { shared++; }
来源：http://dali.yongpay.top/Article/details/gtxygmvpub.html

[O04] 定义异步函数并等待
来源：http://dali.jlsjyb.cn/Article/details/gtaigubwmj.html

Py:   async def f():⏎    await g()
来源：http://dali.yongpay.top/Article/details/gtqiiqpqqp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gotoacloud.top/Article/details/gtlflkzjzf.html

JS:   async function f() { await g(); }
来源：http://dali.yuxming.cn/Article/details/gtcsewwepz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.wangdashe.top/Article/details/gtjeepukxw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cucudq.cn/Article/details/gtxzjmnjvu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgufenzy.top/Article/details/gtgcjrqbsl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhiwuduotai.top/Article/details/gtavthglvo.html

C#:   async Task F() { await G(); }
来源：http://dali.cucudq.cn/Article/details/gtllhefpru.html

[O05] 并发执行并等待全部完成
来源：http://dali.guannengcc.top/Article/details/gtcxglwdbg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ppjwa.cn/Article/details/gtfgvzflny.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cheryme.top/Article/details/gtqdzoetwn.html

JS:   await Promise.all(tasks)
来源：http://dali.redwolf501.top/Article/details/gtevjsyqxd.html

TS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttszyzalo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.316326.xyz/Article/details/gttjpsxart.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gzhubu.top/Article/details/gtxyqzpgpj.html

Ruby: threads.map(&:join)
来源：http://dali.havefunace.top/Article/details/gtveuhaxpt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jiagoushi.top/Article/details/gtnkxfoofi.html

[O06] 使用进程池
来源：http://dali.cheryme.top/Article/details/gtbipdwqsq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuanzhike.top/Article/details/gtuiqsdlyu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xylfe.cn/Article/details/gtbzposozr.html

JS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gtiatftzlj.html

TS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gtomzzsaad.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.mhx1999.top/Article/details/gtbiebhbjg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.havefunace.top/Article/details/gtvmuitvyn.html

Ruby: // fork 块
来源：http://dali.ppjwa.cn/Article/details/gtjtlashao.html

C#:   Parallel.For
来源：http://dali.aibaodan.cn/Article/details/gtnzlychtt.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtutcuiinz.html

P. 常用工具函数
来源：http://dali.quarkkingdee.top/Article/details/gtayxfnwoe.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtewxvraay.html

[P01] 生成 UUID
来源：http://dali.jqgfzy.top/Article/details/gtsvxeiehr.html

Py:   str(uuid.uuid4())
来源：http://dali.yj202588.top/Article/details/gtieggvbxy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tianlin.xyz/Article/details/gtuzdykyps.html

JS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtjvxtzeqw.html

TS:   crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gtsblwvkqs.html

Java: UUID.randomUUID().toString()
来源：http://dali.ehwqpu.com/Article/details/gtigdiwzyf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtpkeewxbp.html

Ruby: SecureRandom.uuid
来源：http://dali.vqdsnc.cn/Article/details/gtysprhwtx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yvedp.cn/Article/details/gtmjrjseqt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xziqi.cn/Article/details/gtocxpuvit.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shzxlz.cn/Article/details/gturqhqeku.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yangfankeji.com/Article/details/gtxikmqtcm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jianghu66.top/Article/details/gtyxmcaqei.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhongyouzk.top/Article/details/gtecbxixsn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqtlhhba.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.smart0.xyz/Article/details/gtujjsrfsv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ydzc1.top/Article/details/gtvajgbopd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.iojbl.cn/Article/details/gtwxnaqxpl.html

[P03] 生成短随机字符串
来源：http://dali.gotoacloud.top/Article/details/gtuawkokwz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sweek.top/Article/details/gtqdrctgql.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xinyue.icu/Article/details/gtsbepgtek.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gtbjjcuyje.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtssxlehdj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guowangkeji.top/Article/details/gtuxhixkcp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinqigfzy.top/Article/details/gtktzbbviq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.c1oappe.top/Article/details/gtikhyrnqf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigfzy.top/Article/details/gtcqzuegkf.html

[P04] 求长度
来源：http://dali.iojbl.cn/Article/details/gtplmystao.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.smart0.xyz/Article/details/gtveqjnruf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtklgmtyul.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gtkwnnfred.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gtbrdehghe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gotoacloud.top/Article/details/gtveomehyu.html

Go:   len(arr);  len(m)
来源：http://dali.zhoulong.xyz/Article/details/gtefoevrot.html

Ruby: x.length;  x.size
来源：http://dali.birdmap.top/Article/details/gthccvkgcy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yangfankeji.com/Article/details/gtxhelykem.html

[P05] 判断两个对象内容是否相等
来源：http://dali.wangdashe.top/Article/details/gtjhapzfgr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nwbrower.top/Article/details/gtufangtac.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yvedp.cn/Article/details/gtgrjaylak.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenlongwang.top/Article/details/gtzdciftgn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pycfn.com/Article/details/gtmskpnqjg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj202588.top/Article/details/gtfngcnxuh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yongpay.top/Article/details/gtplddhrxe.html

Ruby: a == b
来源：http://dali.quarkkingdee.top/Article/details/gtmzaljiks.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hywenlv.cn/Article/details/gtmzpbejbp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hfpthk.cn/Article/details/gtqskrrcyx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhongyouzk.top/Article/details/gthvdkdriu.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzeisuyca.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hysaishi.cn/Article/details/gtxeipfjxo.html

TS:   if (x == null) {}
来源：http://dali.sufxvd.cn/Article/details/gthippkobh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gtocjvyqft.html

Go:   if x == nil {}
来源：http://dali.havefunace.top/Article/details/gtykdwtxmg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuokavqrq.html

C#:   if (x is null) {}
来源：http://dali.daxiang520.top/Article/details/gtgcmgzcld.html

[P07] 防抖与节流
来源：http://dali.feifeiyinyue.top/Article/details/gtalebgvyt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hysaishi.cn/Article/details/gtaltmqqog.html

PHP:  // 手写时间戳比较
来源：http://dali.fengsongda.top/Article/details/gtxnujjdof.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtxzhrmcwr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtifoxsker.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenlongwang.top/Article/details/gtoqjewkkv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shzxlz.cn/Article/details/gtodqyuknk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tian-w.cn/Article/details/gtnyqzsije.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fzhhl.top/Article/details/gtwwzgunfj.html

[P08] 处理浮点精度问题
来源：http://dali.hongshengwenyu.top/Article/details/gtrtsjdovb.html


<!-- 参考信息 -->