代发 wailian999

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tanke756.top/Article/details/gt2kdttyxva.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hongshengwenyu.top/Article/details/gt2ejrdjilz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nvsutjph.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2rsxudexf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258888.top/Article/details/gt2yacrjdjd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jiagoushi.top/Article/details/gt2wjhjbznc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.andypj.xyz/Article/details/gt2dcmevppg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.quarkkingdee.top/Article/details/gt2tbnaabbf.html

[M04] 获取当前工作目录
来源：http://dali.sweek.top/Article/details/gt2kbashfzi.html

Py:   os.getcwd()
来源：http://dali.guowangkeji.top/Article/details/gt2brwmjuxj.html

PHP:  getcwd();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2phlwzfom.html

JS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gt2zyrtmzcv.html

TS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gt2kfanvnry.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.9152youxi.cn/Article/details/gt2fgyfdwfa.html

Go:   os.Getwd()
来源：http://dali.cucudq.cn/Article/details/gt2uxznfpcl.html

Ruby: Dir.pwd
来源：http://dali.birdmap.top/Article/details/gt2sxbdxrzy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pengpengdd.cyou/Article/details/gt2gpeuxhtt.html

[M05] 设置退出码
来源：http://dali.pycfn.com/Article/details/gt2gvuigsjz.html

Py:   sys.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2josdxkol.html

PHP:  exit(1);
来源：http://dali.fengsongda.top/Article/details/gt2luwboypa.html

JS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2auhzlfub.html

TS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gt2ircshafr.html

Java: System.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2kdneijqv.html

Go:   os.Exit(1)
来源：http://dali.sweek.top/Article/details/gt2nvysbklw.html

Ruby: exit 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uxgwwnsu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.snrcjt.cn/Article/details/gt2gwtnrjxr.html

[M06] 向标准错误输出
来源：http://dali.wangdashe.top/Article/details/gt2tljmxlwp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhoulong.xyz/Article/details/gt2yqukbwtb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258888.top/Article/details/gt2iaqfolqm.html

JS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gt2jpvmeupo.html

TS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gt2cnytdsly.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbjiviy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tian-w.cn/Article/details/gt2rfjklevh.html

Ruby: warn "err"
来源：http://dali.yuxming.cn/Article/details/gt2qaidpmfe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnxiangtu.top/Article/details/gt2dnanueog.html

[M07] 判断是否为主入口
来源：http://dali.ehwqpu.com/Article/details/gt2rusdsrfs.html

Py:   if __name__ == "__main__":
来源：http://dali.zhongyouzk.top/Article/details/gt2jnllzzda.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ywqawssw.html

JS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gt2jgbmchvu.html

TS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gt2gneuwogp.html

Java: public static void main(String[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bfsxfjkc.html

Go:   func main()
来源：http://dali.pengpengdd.cyou/Article/details/gt2nciyohyk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxinkj.top/Article/details/gt2nhwepien.html

C#:   static void Main(string[] args)
来源：http://dali.yj202588.top/Article/details/gt2ipqpctmy.html

[M08] 获取系统与运行时信息
来源：http://dali.ivvv.top/Article/details/gt2zzpqyumo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.meibo888.top/Article/details/gt2ndyfahtr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hywenlv.cn/Article/details/gt2ycyxzlqy.html

JS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gt2semeejup.html

TS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gt2cjiodyxo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xziqi.cn/Article/details/gt2xbscglnk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xziqi.cn/Article/details/gt2mwjqcwly.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.316326.xyz/Article/details/gt2afucxzzu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yonumen.top/Article/details/gt2jywmiegs.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2jwamatlz.html

N. 数据结构与算法
来源：http://dali.zhongyouzk.top/Article/details/gt2xrjibzqg.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2tsoyeajn.html

[N01] 二分查找（有序数组）
来源：http://dali.zhengqikj.top/Article/details/gt2vbiqxhwr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2zsyegfqj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj20258.top/Article/details/gt2uzffggyp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gt2myhflfjg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gt2zfrsizcv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2tjcutqef.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2mbgyxzri.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ybcxt.top/Article/details/gt2ktkltfuh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2lkbxmnce.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hywenlv.cn/Article/details/gt2umitykmy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ppjwa.cn/Article/details/gt2jnrdtlkh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gt2kpklqrww.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gt2abgoaqkk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gt2axqwfxnq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.meibo888.top/Article/details/gt2wglngxcv.html

Go:   slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2oztbxdqj.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gt2ajwecieu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgufenzy.top/Article/details/gt2fspzpftl.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxuanxn.top/Article/details/gt2gogjaxul.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigufen.top/Article/details/gt2khegiaob.html

PHP:  // 递归实现，或用 usort
来源：http://dali.redwolf501.top/Article/details/gt2vslrqaii.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gt2eivkjwtv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gt2vzysqswa.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cashguo.top/Article/details/gt2onnvvfvo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.andypj.xyz/Article/details/gt2sweswfiv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhongyouzk.top/Article/details/gt2mwtjsoao.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.snrcjt.cn/Article/details/gt2qiluukzy.html

[N04] 斐波那契数列
来源：http://dali.ehwqpu.com/Article/details/gt2gnjmkcty.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gt2hcdnoumj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gt2wmshojxa.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gt2eknrrkhn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gt2vaoduutt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gt2vexxdxgg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xziqi.cn/Article/details/gt2jurteqwb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2rrzxgbgn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gt2orxjiwsa.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhccpye.html

Py:   math.gcd(a, b)
来源：http://dali.cashguo.top/Article/details/gt2rupowaat.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.snrcjt.cn/Article/details/gt2whxhpfdo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gbsrszgv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gt2aszpeowg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fzarybyz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.smart0.xyz/Article/details/gt2fvziqgmg.html

Ruby: a.gcd(b)
来源：http://dali.hywenlv.cn/Article/details/gt2bglejpsc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yonumen.top/Article/details/gt2xkiktkby.html

[N06] 判断回文字符串
来源：http://dali.nanxinkj.top/Article/details/gt2fjgwxhpj.html

Py:   s == s[::-1]
来源：http://dali.yuxming.cn/Article/details/gt2wpjwpqyz.html

PHP:  $s === strrev($s);
来源：http://dali.yuxming.cn/Article/details/gt2xyznqwgc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2ybczhudm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pmpclcmh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigfzy.top/Article/details/gt2mzsrkoag.html

Go:   // 双指针从两端比较
来源：http://dali.jinqigfzy.top/Article/details/gt2nmqidyma.html

Ruby: s == s.reverse
来源：http://dali.hywenlv.cn/Article/details/gt2fpowmnbk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gt2wqclwhzo.html

[N07] 两数之和（返回下标）
来源：http://dali.yj202588.top/Article/details/gt2tfbbhzdr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ybcxt.top/Article/details/gt2agtkusrc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cashguo.top/Article/details/gt2guxdrhcp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sysykeji.top/Article/details/gt2dsiezyeq.html

TS:   // 手写 Map<string, number>
来源：http://dali.hysaishi.cn/Article/details/gt2mbclwciz.html

Java: // 手写 HashMap
来源：http://dali.jqgufenzy.top/Article/details/gt2hprlnjmc.html

Go:   // 手写 map[int]int
来源：http://dali.jianghu66.top/Article/details/gt2shrdquan.html

Ruby: // 手写 Hash
来源：http://dali.guowangkeji.top/Article/details/gt2pqjhggut.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hfpthk.cn/Article/details/gt2kqafvfkq.html

[N08] 生成全排列
来源：http://dali.sysykeji.top/Article/details/gt2heozfcrs.html

Py:   itertools.permutations(arr)
来源：http://dali.pycfn.com/Article/details/gt2lzumrpkg.html

PHP:  // 手写递归交换
来源：http://dali.shangyingyoupin.top/Article/details/gt2jqflexlk.html

JS:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gt2egxzsaip.html

TS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gt2ijillkem.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbadlsd.html

Go:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gt2xpvnteji.html

Ruby: arr.permutation.to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zcbsxlcm.html

C#:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2lleykpax.html

[N09] 栈与队列
来源：http://dali.c1oappe.top/Article/details/gt2ojhkpxbu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.birdmap.top/Article/details/gt2hkdzstoz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daxiang520.top/Article/details/gt2awdbnzbc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gt2zfkdbkka.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hywenlv.cn/Article/details/gt2yywmbwcf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cucudq.cn/Article/details/gt2deznkqbo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sufxvd.cn/Article/details/gt2hguzebzq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gt2fkhmjome.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hammf.cn/Article/details/gt2jvxicvkb.html

[N10] 链表节点定义
来源：http://dali.xuetiantiany.cn/Article/details/gt2aduosrrk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sweek.top/Article/details/gt2jgijocmh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgfzy.top/Article/details/gt2ilagnrsz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sweek.top/Article/details/gt2hozsklpp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.andypj.xyz/Article/details/gt2buzakpvr.html

Java: class Node { int v; Node next; }
来源：http://dali.shuidangran.top/Article/details/gt2weanbuyo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.svipenyu.cn/Article/details/gt2jacwbcsj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tanke756.top/Article/details/gt2rmzewmvu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zycfv.cn/Article/details/gt2axcrgoee.html

[N11] 二叉树中序遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2njqjlxlc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pycfn.com/Article/details/gt2vleqisay.html

PHP:  // 手写递归函数
来源：http://dali.guannengcc.top/Article/details/gt2afwxvbnj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gt2njhohzhm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhixingplan.top/Article/details/gt2zpgjgqtl.html

Java: // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gt2jaedpidr.html

Go:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gt2qkjeplzv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.snrcjt.cn/Article/details/gt2mzntsepk.html

C#:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2nsygxjqg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ydzc1.top/Article/details/gt2essrbfij.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jianghu66.top/Article/details/gt2gqzroyew.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhiwuduotai.top/Article/details/gt2eqdlvvnn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gt2fjsaxogb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhixingplan.top/Article/details/gt2jtpaacbg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gt2unmmakkw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hywenlv.cn/Article/details/gt2uonuszif.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhongyouzk.top/Article/details/gt2gxofcnbl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gt2hhpurakw.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2vwqumfis.html

O. 并发与异步
来源：http://dali.gaohongyu789.top/Article/details/gt2cjxbgvop.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2jjnvdshm.html

[O01] 启动一个线程
来源：http://dali.quarkkingdee.top/Article/details/gt2emnorpud.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xfbhbolf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.kuanghao11.cn/Article/details/gt2vnwxygai.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxinkj.top/Article/details/gt2zsunybyp.html

TS:   // 同 JS
来源：http://dali.gzhubu.top/Article/details/gt2lgnxdxla.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhoulong.xyz/Article/details/gt2dhimltee.html

Go:   go f()
来源：http://dali.ppjwa.cn/Article/details/gt2pqpfqebv.html

Ruby: Thread.new { f }
来源：http://dali.ydzc1.top/Article/details/gt2dgrypjhy.html

C#:   Task.Run(() => F());
来源：http://dali.tianlin.xyz/Article/details/gt2byqctslr.html

[O02] 使用线程池
来源：http://dali.jinqigfzy.top/Article/details/gt2pdmcxfrm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uofuxwyq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dashuyun.cn/Article/details/gt2jffusqxn.html

JS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gt2rtinzrip.html

TS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gt2ftaukcaw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daxiang520.top/Article/details/gt2ejotfxyz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yangfankeji.com/Article/details/gt2xpmhwbut.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fcqnhtca.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fzhhl.top/Article/details/gt2irmpzerz.html

[O03] 加锁保护共享数据
来源：http://dali.jianghu66.top/Article/details/gt2tkpxmrxj.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lhdlpjsw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bgadlqoq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zycfv.cn/Article/details/gt2jljdjcha.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gt2kqqrdyki.html

Java: synchronized (this) { shared++; }
来源：http://dali.hammf.cn/Article/details/gt2gypfaart.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yueranfly.top/Article/details/gt2fjmnsnmr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xylfe.cn/Article/details/gt2kljyopzb.html

C#:   lock (gate) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2srdeibjb.html

[O04] 定义异步函数并等待
来源：http://dali.hnqzz.top/Article/details/gt2kkcuqwto.html

Py:   async def f():⏎    await g()
来源：http://dali.yonumen.top/Article/details/gt2xhqcpuhj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hnqzz.top/Article/details/gt2ckjfuidj.html

JS:   async function f() { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2egzbboop.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.andypj.xyz/Article/details/gt2udadidkk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenzaomai.com/Article/details/gt2iqvlkjkl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuxming.cn/Article/details/gt2qewphnmg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nanxinkj.top/Article/details/gt2ihbbbjmq.html

C#:   async Task F() { await G(); }
来源：http://dali.wangdashe.top/Article/details/gt2quyzglnd.html

[O05] 并发执行并等待全部完成
来源：http://dali.0kj1m.cn/Article/details/gt2huqvnlwk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daria6918.cn/Article/details/gt2vzvosoia.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj20258888.top/Article/details/gt2gwdsprfo.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gt2miuvinxw.html

TS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gt2sonfjgyh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fzhhl.top/Article/details/gt2jkhxjibw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dianchejie.cn/Article/details/gt2sshpwrhb.html

Ruby: threads.map(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ybrjizlj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sufxvd.cn/Article/details/gt2yduovqip.html

[O06] 使用进程池
来源：http://dali.tianlin.xyz/Article/details/gt2unnhsyas.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.mhx1999.top/Article/details/gt2dikjamuh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shuidangran.top/Article/details/gt2ttkkkshf.html

JS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gt2mcetbbsx.html

TS:   // child_process / cluster 模块
来源：http://dali.shangyingyoupin.top/Article/details/gt2rdxoaohy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zycfv.cn/Article/details/gt2ozgwymmy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nsielzdv.html

Ruby: // fork 块
来源：http://dali.hfpthk.cn/Article/details/gt2luwqiumd.html

C#:   Parallel.For
来源：http://dali.hongshengwenyu.top/Article/details/gt2zinqdqta.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2hvjsumlj.html

P. 常用工具函数
来源：http://dali.9152youxi.cn/Article/details/gt2nesjmfcy.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2dnevsxix.html

[P01] 生成 UUID
来源：http://dali.zhengqikj.top/Article/details/gt2plnyyfpc.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258888.top/Article/details/gt2qnectwbi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.316326.xyz/Article/details/gt2vqjejvby.html

JS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gt2kuzpvejl.html

TS:   crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gt2nvfvawoi.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuanzhike.top/Article/details/gt2tvgjogss.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gogol.net.cn/Article/details/gt2zfciomni.html

Ruby: SecureRandom.uuid
来源：http://dali.jianghu66.top/Article/details/gt2iqtjffua.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shzxlz.cn/Article/details/gt2sjcxiujj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gogol.net.cn/Article/details/gt2deotdrqb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daria6918.cn/Article/details/gt2amsfiwxq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yangfankeji.com/Article/details/gt2jmnvptis.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gogol.net.cn/Article/details/gt2tsoohdpl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangdashe.top/Article/details/gt2taupdymj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jcaxhvsd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxinkj.top/Article/details/gt2ucufrarv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xiquqlcw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tian-w.cn/Article/details/gt2hxqrbesi.html

[P03] 生成短随机字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2pvcjvxai.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.vqdsnc.cn/Article/details/gt2mjkjdwqu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jiagoushi.top/Article/details/gt2ixfkxtds.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gt2zocvakus.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gt2tlbeysdy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2pynnboxh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.bjfxy.top/Article/details/gt2wkhephzq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tanke756.top/Article/details/gt2donobbbl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fzhhl.top/Article/details/gt2ndidmckb.html

[P04] 求长度
来源：http://dali.jqgfzy.top/Article/details/gt2wmgfoagl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.pycfn.com/Article/details/gt2ezqtiidx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gt2smdfwitk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gt2ncyoyuvq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gt2ogiynbje.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shuidangran.top/Article/details/gt2auweekks.html

Go:   len(arr);  len(m)
来源：http://dali.snrcjt.cn/Article/details/gt2utrlrliu.html

Ruby: x.length;  x.size
来源：http://dali.nwbrower.top/Article/details/gt2whyfeasw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gt2mupqgiff.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daria6918.cn/Article/details/gt2wuwmcoov.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fzhhl.top/Article/details/gt2vembsbou.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj202588.top/Article/details/gt2itbskhdq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zycfv.cn/Article/details/gt2thythglk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sysykeji.top/Article/details/gt2huzgudzb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhengqikj.top/Article/details/gt2etdzubhj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuanzhike.top/Article/details/gt2fyftypmn.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2eznhhgch.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zdqjudy.top/Article/details/gt2bcsdlawc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.daxiang520.top/Article/details/gt2jewsrcao.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jiagoushi.top/Article/details/gt2rjbjysji.html

PHP:  if (empty($x)) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2qzxpzhgw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jianghu66.top/Article/details/gt2juubbuuf.html

TS:   if (x == null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2appylpuk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2bfkwhxpn.html

Go:   if x == nil {}
来源：http://dali.andypj.xyz/Article/details/gt2kvidyxzs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cucudq.cn/Article/details/gt2tonetuwn.html

C#:   if (x is null) {}
来源：http://dali.guannengcc.top/Article/details/gt2wehzmcwf.html

[P07] 防抖与节流
来源：http://dali.zhiwuduotai.top/Article/details/gt2axejcaae.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.pengpengdd.cyou/Article/details/gt2dvyafwsq.html

PHP:  // 手写时间戳比较
来源：http://dali.gotoacloud.top/Article/details/gt2oshxfnba.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gt2qumkwerl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gt2rlwklqsu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xylfe.cn/Article/details/gt2ltbdxuma.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhongyouzk.top/Article/details/gt2ustwbbyj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwrtkltv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.haohaochexian.top/Article/details/gt2ykyjdnnq.html

[P08] 处理浮点精度问题
来源：http://dali.feifeiyinyue.top/Article/details/gt2tpcxbkao.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnxiangtu.top/Article/details/gt2qlhvheju.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jiagoushi.top/Article/details/gt2rlplfwpg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nwbrower.top/Article/details/gt2gpnhkmti.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shzxlz.cn/Article/details/gt2rxlyusqt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.mhx1999.top/Article/details/gt2arrexyby.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ydzc1.top/Article/details/gt2rlubvmne.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.vqdsnc.cn/Article/details/gt2tycgrfbf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhixingplan.top/Article/details/gt2treeuvbm.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2fnmpjnau.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sxryk.cn/Article/details/gt2uphiypsk.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2nlqavsgi.html

[Q01] 创建表
来源：http://dali.0kj1m.cn/Article/details/gt2ikjpsozn.html


<!-- 参考信息 -->