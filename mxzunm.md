代发 wailian999

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtdochalky.html

Ruby: ENV["HOME"]
来源：http://dali.shangyingyoupin.top/Article/details/gtwatvppus.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cashguo.top/Article/details/gtfservdwm.html

[M03] 执行外部命令
来源：http://dali.shanyushiyangtech.top/Article/details/gtfonlpbwf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sweek.top/Article/details/gtrmadkscp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cdnleiting.top/Article/details/gtymoyiqlh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtyrvofttr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gtxnmmwyjr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hywenlv.cn/Article/details/gtrqcysdou.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hysaishi.cn/Article/details/gticgbcosq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsdmlbir.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxinkj.top/Article/details/gtibhaqbxo.html

[M04] 获取当前工作目录
来源：http://dali.xylfe.cn/Article/details/gtymdbdzbc.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtriosjhjh.html

PHP:  getcwd();
来源：http://dali.jqgufenzy.top/Article/details/gtumrtyugt.html

JS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gtcmsqfozm.html

TS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gthaduztgr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yangfankeji.com/Article/details/gtrmssstad.html

Go:   os.Getwd()
来源：http://dali.bjfxy.top/Article/details/gtmzfmtfyh.html

Ruby: Dir.pwd
来源：http://dali.sweek.top/Article/details/gtavuhnwmk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenzaomai.com/Article/details/gtcfkezpej.html

[M05] 设置退出码
来源：http://dali.wangdashe.top/Article/details/gtkpxtsfmz.html

Py:   sys.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtlprpoixv.html

PHP:  exit(1);
来源：http://dali.vqdsnc.cn/Article/details/gtidugdbhh.html

JS:   process.exit(1)
来源：http://dali.ivvv.top/Article/details/gtghrpggfo.html

TS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtoxbcdctp.html

Java: System.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtjxgprucr.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtcnkdlonr.html

Ruby: exit 1
来源：http://dali.aibaodan.cn/Article/details/gtxjfnubfq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shzxlz.cn/Article/details/gtaozalxoy.html

[M06] 向标准错误输出
来源：http://dali.nanxuanxn.top/Article/details/gtnfbjhqzy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdvnjkjg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fengsongda.top/Article/details/gtgiodndto.html

JS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtfgjwsebf.html

TS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcctvqtpt.html

Java: System.err.println("err")
来源：http://dali.redwolf501.top/Article/details/gttptxrole.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.havefunace.top/Article/details/gtbicgjgvr.html

Ruby: warn "err"
来源：http://dali.9152youxi.cn/Article/details/gtgalvqxrb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258888.top/Article/details/gtynmaggrx.html

[M07] 判断是否为主入口
来源：http://dali.shangyingyoupin.top/Article/details/gtparazfna.html

Py:   if __name__ == "__main__":
来源：http://dali.ppjwa.cn/Article/details/gtcolgohwp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zycfv.cn/Article/details/gtdfjdicvc.html

JS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtvxoafrfm.html

TS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gtpzdfkqnv.html

Java: public static void main(String[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtexzduldd.html

Go:   func main()
来源：http://dali.gaohongyu789.top/Article/details/gtxvoaotdc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ivvv.top/Article/details/gtgpqkcqhl.html

C#:   static void Main(string[] args)
来源：http://dali.zhongyouzk.top/Article/details/gtcbnqjqyi.html

[M08] 获取系统与运行时信息
来源：http://dali.tianlin.xyz/Article/details/gtrasabcct.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxuanxn.top/Article/details/gtugyzeecc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aizwys.cn/Article/details/gtrueagwzi.html

JS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gtzezmsrlx.html

TS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gttmuqayod.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhengqikj.top/Article/details/gtfrsxdyae.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sysykeji.top/Article/details/gtighthygl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangshuangyany.cn/Article/details/gtdowhjbve.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pengpengdd.cyou/Article/details/gtdnncfmuz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtasmizfqx.html

N. 数据结构与算法
来源：http://dali.sxryk.cn/Article/details/gtdlicsall.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtvkfxeumz.html

[N01] 二分查找（有序数组）
来源：http://dali.xinyue.icu/Article/details/gtvtyodlsr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.316326.xyz/Article/details/gtelfzbzyq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtffjdawso.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gtwwkjfwru.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gtzzrbqeay.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjfianeb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtxoobbrvg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gtcxfutsvu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtuvpffsgg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.feifeiyinyue.top/Article/details/gtgupxdutl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gtjdipxfxn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cashguo.top/Article/details/gtffjfktkb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gthhgexbjm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtgtwjdyng.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pengpengdd.cyou/Article/details/gtoeqliynj.html

Go:   slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gtzqlzobcs.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gtermufvft.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guannengcc.top/Article/details/gtdsuxufef.html

[N03] 快速排序（分治示例）
来源：http://dali.zdqjudy.top/Article/details/gtqgtmbuhw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jyoumei.cn/Article/details/gtrnyynzkl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tian-w.cn/Article/details/gtokpguiwh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtuxejhydg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxknfctgb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aizwys.cn/Article/details/gtsblhceew.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hammf.cn/Article/details/gtiystosfk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sweek.top/Article/details/gtkwbomuei.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ivvv.top/Article/details/gtwicljqnc.html

[N04] 斐波那契数列
来源：http://dali.haohaochexian.top/Article/details/gtwitmhpsn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtmqzkjj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gtwuxgghuh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gtdndnlriv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtfpgvhrkq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gtltheohel.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xziqi.cn/Article/details/gtjfdxudgw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gtksgjbxif.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gtwpqcovul.html

[N05] 最大公约数
来源：http://dali.ppjwa.cn/Article/details/gtgjukxhju.html

Py:   math.gcd(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjodofkr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtvpkqquwg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtoxofngxn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gtguyhouxn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yvedp.cn/Article/details/gtylahksmj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shuidangran.top/Article/details/gtbxcersux.html

Ruby: a.gcd(b)
来源：http://dali.snrcjt.cn/Article/details/gtomdhgywf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jiagoushi.top/Article/details/gtatjwzvrl.html

[N06] 判断回文字符串
来源：http://dali.yongpay.top/Article/details/gtsojejnha.html

Py:   s == s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gtmjvcvsjy.html

PHP:  $s === strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtzeoughnv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtgknmjykv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtqsuwraux.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuanzhike.top/Article/details/gtqhmmsukc.html

Go:   // 双指针从两端比较
来源：http://dali.mhx1999.top/Article/details/gtixlngbln.html

Ruby: s == s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtzumhvrxc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gtifpsrhso.html

[N07] 两数之和（返回下标）
来源：http://dali.sufxvd.cn/Article/details/gtgvomdrej.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tianlin.xyz/Article/details/gtrcalxnkj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fzhhl.top/Article/details/gtmqzpzpls.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yongpay.top/Article/details/gtgpbwsmrq.html

TS:   // 手写 Map<string, number>
来源：http://dali.cheryme.top/Article/details/gtopzwnhbs.html

Java: // 手写 HashMap
来源：http://dali.jinqigufen.top/Article/details/gttjnchnfr.html

Go:   // 手写 map[int]int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclanmqpx.html

Ruby: // 手写 Hash
来源：http://dali.0kj1m.cn/Article/details/gtkqefqutt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sweek.top/Article/details/gtlgiuiore.html

[N08] 生成全排列
来源：http://dali.sweek.top/Article/details/gtrvkkqumw.html

Py:   itertools.permutations(arr)
来源：http://dali.cheryme.top/Article/details/gtgkzvcens.html

PHP:  // 手写递归交换
来源：http://dali.hywenlv.cn/Article/details/gtimwmnvkq.html

JS:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtnkiiccvu.html

TS:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtpjdtlnxh.html

Java: // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtdqftrwja.html

Go:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtbkpsprrl.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigufen.top/Article/details/gtrtyoixec.html

C#:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtmihfeeib.html

[N09] 栈与队列
来源：http://dali.dashuyun.cn/Article/details/gtbaenezwf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shuidangran.top/Article/details/gtfsxwrgnp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtpcxdksgk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gtpjtcaqpb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gogol.net.cn/Article/details/gtfsuoozhm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.0kj1m.cn/Article/details/gtpnzanucy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shangyingyoupin.top/Article/details/gtcnlvmyey.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyurvsro.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dashuyun.cn/Article/details/gtpiybdxvb.html

[N10] 链表节点定义
来源：http://dali.gotoacloud.top/Article/details/gtrwtpfyqk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ehwqpu.com/Article/details/gtfhiiojnf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xziqi.cn/Article/details/gthqfleztn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ivvv.top/Article/details/gtrwrrygjo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daxiang520.top/Article/details/gtvixbgrog.html

Java: class Node { int v; Node next; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdlkgxqvw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhnltbiy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xuetiantiany.cn/Article/details/gttabbubwi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dianchejie.cn/Article/details/gtfeibujdx.html

[N11] 二叉树中序遍历
来源：http://dali.xziqi.cn/Article/details/gthgpjecli.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.andypj.xyz/Article/details/gtaqljbiga.html

PHP:  // 手写递归函数
来源：http://dali.yj202588.top/Article/details/gtdiapcqiy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gtdgfsutlh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gttyxaicob.html

Java: // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtnsczqomg.html

Go:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gtairuoyne.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangtech.top/Article/details/gtqacrdhoi.html

C#:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gtuxckhwjl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxinkj.top/Article/details/gtomkexsip.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenzaomai.com/Article/details/gtgblzyeqy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.redwolf501.top/Article/details/gtoztqdupt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gthafshmez.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdeuawva.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gtdyccwujz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gzhubu.top/Article/details/gtpjppgcts.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxfohsry.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtpbqtyojg.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gttwuzrpkl.html

O. 并发与异步
来源：http://dali.yuxming.cn/Article/details/gtgjslmkuc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gthfvncyub.html

[O01] 启动一个线程
来源：http://dali.fzhhl.top/Article/details/gtcvfdstpr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjclhiai.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jyoumei.cn/Article/details/gtrqjwsslj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj202588.top/Article/details/gtqiiyymbl.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtztbbppps.html

Java: new Thread(() -> f()).start()
来源：http://dali.9152youxi.cn/Article/details/gtnxpxgwnb.html

Go:   go f()
来源：http://dali.ywan-chungtsiang.top/Article/details/gteyyvtouv.html

Ruby: Thread.new { f }
来源：http://dali.yueranfly.top/Article/details/gtdojyzkws.html

C#:   Task.Run(() => F());
来源：http://dali.gogol.net.cn/Article/details/gthazaoxia.html

[O02] 使用线程池
来源：http://dali.c1oappe.top/Article/details/gtkrlynfbz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tianlin.xyz/Article/details/gtrpczuplc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.quarkkingdee.top/Article/details/gtutkldvcr.html

JS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gtxkuufnws.html

TS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gthugzforw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.mhx1999.top/Article/details/gtjzvwqkfc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhengqikj.top/Article/details/gtydrqyzmb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinqigfzy.top/Article/details/gttatpovdx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aibaodan.cn/Article/details/gtoqouzswa.html

[O03] 加锁保护共享数据
来源：http://dali.yongpay.top/Article/details/gtsksqrbqi.html

Py:   with lock: shared += 1
来源：http://dali.kuanghao11.cn/Article/details/gtdvvydemr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.0kj1m.cn/Article/details/gtrxuldxgd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgufenzy.top/Article/details/gtxlaxlyxb.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gtmkeyhipa.html

Java: synchronized (this) { shared++; }
来源：http://dali.yangfankeji.com/Article/details/gtiaroosgq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yongpay.top/Article/details/gtwemnyjqg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.mhx1999.top/Article/details/gtrfqpdsab.html

C#:   lock (gate) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gtcgixsqdz.html

[O04] 定义异步函数并等待
来源：http://dali.shangyingyoupin.top/Article/details/gthfrdnpmv.html

Py:   async def f():⏎    await g()
来源：http://dali.hnxiangtu.top/Article/details/gtlpkimprm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqfjqgelr.html

JS:   async function f() { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gtquzgafea.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtsycjlwzr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sxryk.cn/Article/details/gtpzjuvnfn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zycfv.cn/Article/details/gtuhfukihl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.bjfxy.top/Article/details/gtufiwsngp.html

C#:   async Task F() { await G(); }
来源：http://dali.yueranfly.top/Article/details/gtwhexbjny.html

[O05] 并发执行并等待全部完成
来源：http://dali.snrcjt.cn/Article/details/gtilgkmnsb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgufenzy.top/Article/details/gttdadjjdo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhixingplan.top/Article/details/gtnozuuqzv.html

JS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gtrzqquysk.html

TS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gtghfnkwpk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pengpengdd.cyou/Article/details/gtuvcluplb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gogol.net.cn/Article/details/gtmcueseho.html

Ruby: threads.map(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gtvdgxtoku.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnxiangtu.top/Article/details/gtzlqftamb.html

[O06] 使用进程池
来源：http://dali.jyoumei.cn/Article/details/gtzykbwetn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.316326.xyz/Article/details/gtvgvmklti.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pengpengdd.cyou/Article/details/gtfxloujzj.html

JS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gtgvdzqstu.html

TS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gtxycdnwwl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.iojbl.cn/Article/details/gturxsbxdm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.havefunace.top/Article/details/gtuxfszucs.html

Ruby: // fork 块
来源：http://dali.chenlongwang.top/Article/details/gtqwpwhxdg.html

C#:   Parallel.For
来源：http://dali.pycfn.com/Article/details/gtetagufdu.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gthrrpwyie.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gtemwdhkzv.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtwxbcnnhd.html

[P01] 生成 UUID
来源：http://dali.jianghu66.top/Article/details/gtpqzxtaao.html

Py:   str(uuid.uuid4())
来源：http://dali.jianghu66.top/Article/details/gtqymxnkjs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.kuanghao11.cn/Article/details/gtzxcdhbsi.html

JS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gtphocfwul.html

TS:   crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gtpsrcyamn.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqslncuit.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gotoacloud.top/Article/details/gtjxbkyxcs.html

Ruby: SecureRandom.uuid
来源：http://dali.bjfxy.top/Article/details/gtvapzfbcp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.redwolf501.top/Article/details/gtowufigbx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shuidangran.top/Article/details/gtopnmhnst.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaabqtisy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.haohaochexian.top/Article/details/gtttyqfkyh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gotoacloud.top/Article/details/gtzildmcwn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guowangkeji.top/Article/details/gtxliuajkf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gtpoikteks.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gaohongyu789.top/Article/details/gtymsrontg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.snrcjt.cn/Article/details/gtptqpsdlx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhiwuduotai.top/Article/details/gtjzivtsdo.html

[P03] 生成短随机字符串
来源：http://dali.gogol.net.cn/Article/details/gtbbhdiawc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj202588.top/Article/details/gtjjqmjjgb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuanzhike.top/Article/details/gtlwpkwkpn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gtispgctoh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtmxmefeop.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtpyyfbdrd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jyoumei.cn/Article/details/gtobktkwut.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.fzhhl.top/Article/details/gtkznstpij.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.vqdsnc.cn/Article/details/gtyjjrontw.html

[P04] 求长度
来源：http://dali.0kj1m.cn/Article/details/gtchqzlddj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daria6918.cn/Article/details/gtqxmhcooe.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtpqgkdgvk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gtcxoisewi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gtjcmsyusi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuanzhike.top/Article/details/gthzglpspz.html

Go:   len(arr);  len(m)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzzsleox.html

Ruby: x.length;  x.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvtmgnte.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hfpthk.cn/Article/details/gtqiecighs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhixingplan.top/Article/details/gtyawhicgo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fengsongda.top/Article/details/gthwdemzwq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ivvv.top/Article/details/gtdiptzjqr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hysaishi.cn/Article/details/gtdwlvgelg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hysaishi.cn/Article/details/gtdmtqvstc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.redwolf501.top/Article/details/gtywbijeah.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sysykeji.top/Article/details/gtiurpkbbo.html

Ruby: a == b
来源：http://dali.nwbrower.top/Article/details/gtwnrbdtst.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sweek.top/Article/details/gtywwbxvld.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.birdmap.top/Article/details/gtxwvfqbib.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hysaishi.cn/Article/details/gtqsxtpsse.html

PHP:  if (empty($x)) {}
来源：http://dali.wangdashe.top/Article/details/gtprcjjrkv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gaohongyu789.top/Article/details/gtqiqxllrw.html

TS:   if (x == null) {}
来源：http://dali.guowangkeji.top/Article/details/gtwkwekpvd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gtvckrdwlz.html

Go:   if x == nil {}
来源：http://dali.yueranfly.top/Article/details/gtadfcoyrd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhixingplan.top/Article/details/gtggoaumum.html

C#:   if (x is null) {}
来源：http://dali.hnqzz.top/Article/details/gtnvprcjyq.html

[P07] 防抖与节流
来源：http://dali.redwolf501.top/Article/details/gtblehjgwm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shzxlz.cn/Article/details/gtimvitpci.html

PHP:  // 手写时间戳比较
来源：http://dali.dashuyun.cn/Article/details/gtgemcvvei.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtgytffnzt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gtrvqtlzpi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yuanzhike.top/Article/details/gtqunwevsx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daria6918.cn/Article/details/gtfhonqiht.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jlsjyb.cn/Article/details/gtffolnygx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hammf.cn/Article/details/gtpobjgvmp.html

[P08] 处理浮点精度问题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxalbvjp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhoulong.xyz/Article/details/gtfnsdblqt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuanzx.com/Article/details/gtcjgusowy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hysaishi.cn/Article/details/gtpsmrdnrk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtszeoydnk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sufxvd.cn/Article/details/gtkhynozzt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fzhhl.top/Article/details/gtyypsjwox.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj20258888.top/Article/details/gtrygqyjda.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgfzy.top/Article/details/gtuleecjss.html


<!-- 参考信息 -->