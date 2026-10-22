代发 wailian999

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbvbpclc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigfzy.top/Article/details/gtazbyfeqt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gtjftckyjb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gtzdyrcofk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ydzc1.top/Article/details/gtffvcyvtg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yanxiufei.cn/Article/details/gtgviphmat.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guowangkeji.top/Article/details/gtmqqmwsxq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daxiang520.top/Article/details/gtfinqxfql.html

[M04] 获取当前工作目录
来源：http://dali.zhixingplan.top/Article/details/gtzvipactv.html

Py:   os.getcwd()
来源：http://dali.jinqigufen.top/Article/details/gtnmvwstql.html

PHP:  getcwd();
来源：http://dali.xinyue.icu/Article/details/gtijptxlrn.html

JS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gtpkwzrhlv.html

TS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtgpaoogyd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aizwys.cn/Article/details/gtfarofnxp.html

Go:   os.Getwd()
来源：http://dali.redwolf501.top/Article/details/gtthlwtysj.html

Ruby: Dir.pwd
来源：http://dali.daria6918.cn/Article/details/gtkcagcihf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gtwjwhyamc.html

[M05] 设置退出码
来源：http://dali.ybcxt.top/Article/details/gtgycctckz.html

Py:   sys.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcvymynl.html

PHP:  exit(1);
来源：http://dali.tanke756.top/Article/details/gtsgdlmbfx.html

JS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtcstautxs.html

TS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gttamlyzik.html

Java: System.exit(1)
来源：http://dali.yj202588.top/Article/details/gtyixgzaui.html

Go:   os.Exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtxgotccgn.html

Ruby: exit 1
来源：http://dali.hongshengwenyu.top/Article/details/gtxpnflesh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.mhx1999.top/Article/details/gtixiogplx.html

[M06] 向标准错误输出
来源：http://dali.9152youxi.cn/Article/details/gtlrqdbpwr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenzaomai.com/Article/details/gtfbtcjwvg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqzsacon.html

JS:   console.error("err")
来源：http://dali.gotoacloud.top/Article/details/gtreoousva.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtsvnnmdng.html

Java: System.err.println("err")
来源：http://dali.cucudq.cn/Article/details/gtdukyujvf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.vqdsnc.cn/Article/details/gtixjwwwxe.html

Ruby: warn "err"
来源：http://dali.vqdsnc.cn/Article/details/gtklvrmacp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hammf.cn/Article/details/gtabgqcvyo.html

[M07] 判断是否为主入口
来源：http://dali.gzhubu.top/Article/details/gtuxcwmcxg.html

Py:   if __name__ == "__main__":
来源：http://dali.hywenlv.cn/Article/details/gtpwcqtdiv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jianghu66.top/Article/details/gtokcgprih.html

JS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gtbqgnxjag.html

TS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gtqorsdech.html

Java: public static void main(String[] args)
来源：http://dali.sufxvd.cn/Article/details/gtzelxptae.html

Go:   func main()
来源：http://dali.xylfe.cn/Article/details/gtyhepidpv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sufxvd.cn/Article/details/gtlcqjpfmn.html

C#:   static void Main(string[] args)
来源：http://dali.hywenlv.cn/Article/details/gttbrbbiyu.html

[M08] 获取系统与运行时信息
来源：http://dali.ydzc1.top/Article/details/gtbxrvnzrs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenlongwang.top/Article/details/gtqsqyaxmp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj202588.top/Article/details/gtuzjrpglt.html

JS:   process.platform;  process.version
来源：http://dali.yj20258.top/Article/details/gtrfxdeuph.html

TS:   process.platform;  process.version
来源：http://dali.haohaochexian.top/Article/details/gtspkjrpcl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gogol.net.cn/Article/details/gtypllwsdt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dashuyun.cn/Article/details/gtaolkwbgc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fzhhl.top/Article/details/gtrkonberz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj202588.top/Article/details/gtzjjneaob.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtvzmykzut.html

N. 数据结构与算法
来源：http://dali.xuetiantiany.cn/Article/details/gtvuxqnrfh.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtonckufxw.html

[N01] 二分查找（有序数组）
来源：http://dali.chenjidiqi.icu/Article/details/gtgxtxxxwm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtvbfamwdy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.havefunace.top/Article/details/gtuoloredh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gtifieonos.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gtbyaavozh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtejbazare.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtdtcsjqsq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoeeeagvq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcruqtrxk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.birdmap.top/Article/details/gtsnulfzpl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gtspaigwji.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtgcolenrz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gturckepdq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gtbirbguyh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daria6918.cn/Article/details/gtyskjhcpf.html

Go:   slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gtjxngweto.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gtqpsayqri.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.bjfxy.top/Article/details/gtlerqgnmw.html

[N03] 快速排序（分治示例）
来源：http://dali.shangyingyoupin.top/Article/details/gtexxohhbg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daxiang520.top/Article/details/gtglftckyr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hfpthk.cn/Article/details/gtmcbigmyu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.birdmap.top/Article/details/gtltrtwmdk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.quarkkingdee.top/Article/details/gthobsspno.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtozstsaiy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zdqjudy.top/Article/details/gtuolryval.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yanxiufei.cn/Article/details/gtmteeylzc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgufenzy.top/Article/details/gtoonyowho.html

[N04] 斐波那契数列
来源：http://dali.jianghu66.top/Article/details/gtoaghjvua.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gtylfusblx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gtuojnvhst.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtfpziecfh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtmqmnjwni.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gtnrrzoqhf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.316326.xyz/Article/details/gtpbpqxxph.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gtfzutatym.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gttpbvjsxi.html

[N05] 最大公约数
来源：http://dali.sysykeji.top/Article/details/gtuugmwwel.html

Py:   math.gcd(a, b)
来源：http://dali.zycfv.cn/Article/details/gtttyrepyj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shuidangran.top/Article/details/gththiwqsa.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ppjwa.cn/Article/details/gtxrqbztnw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gthidiyhvs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.andypj.xyz/Article/details/gtepcfkgal.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tanke756.top/Article/details/gtbexnuceh.html

Ruby: a.gcd(b)
来源：http://dali.nanxuanxn.top/Article/details/gtsezmraju.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jlsjyb.cn/Article/details/gtoqaemiqb.html

[N06] 判断回文字符串
来源：http://dali.yangfankeji.com/Article/details/gtbnjmghtw.html

Py:   s == s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gtikzpsxui.html

PHP:  $s === strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gtngnptsgy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtpcxtlzei.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtidylsgum.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jyoumei.cn/Article/details/gtslmhkkcp.html

Go:   // 双指针从两端比较
来源：http://dali.smart0.xyz/Article/details/gtfytdpnrp.html

Ruby: s == s.reverse
来源：http://dali.bjfxy.top/Article/details/gtblzoetwm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gtsnjabamc.html

[N07] 两数之和（返回下标）
来源：http://dali.yonumen.top/Article/details/gteyjymyph.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yanxiufei.cn/Article/details/gtxwbichgw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nwbrower.top/Article/details/gtnapsjjna.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xziqi.cn/Article/details/gtbmphfzcz.html

TS:   // 手写 Map<string, number>
来源：http://dali.0kj1m.cn/Article/details/gtcjwcyhol.html

Java: // 手写 HashMap
来源：http://dali.yvedp.cn/Article/details/gtvtjxruem.html

Go:   // 手写 map[int]int
来源：http://dali.dashuyun.cn/Article/details/gtadwjsmpm.html

Ruby: // 手写 Hash
来源：http://dali.xylfe.cn/Article/details/gthgvfikzh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.wangshuangyany.cn/Article/details/gtodxcpnpa.html

[N08] 生成全排列
来源：http://dali.xylfe.cn/Article/details/gtwkbufvrj.html

Py:   itertools.permutations(arr)
来源：http://dali.smart0.xyz/Article/details/gthpaljixe.html

PHP:  // 手写递归交换
来源：http://dali.gaohongyu789.top/Article/details/gtsadpjecu.html

JS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gteglsaxpu.html

TS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtpwslcbru.html

Java: // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtjyhmltwm.html

Go:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtzryrncir.html

Ruby: arr.permutation.to_a
来源：http://dali.zhengqikj.top/Article/details/gthurtyrdl.html

C#:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtbcebqigc.html

[N09] 栈与队列
来源：http://dali.xuetiantiany.cn/Article/details/gtlglfuotv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxinkj.top/Article/details/gtwpcmygzm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hammf.cn/Article/details/gtaikfumnr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gteywgyzap.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yongpay.top/Article/details/gthyhabyfw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zdqjudy.top/Article/details/gtvkpzfzww.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258888.top/Article/details/gttmwwhfaw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtjbfewgqz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yongpay.top/Article/details/gtyssppbww.html

[N10] 链表节点定义
来源：http://dali.redwolf501.top/Article/details/gtqrsxxmff.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ybcxt.top/Article/details/gtshghwgsx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aibaodan.cn/Article/details/gtvnmcfskp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gtyogtilhv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenlongwang.top/Article/details/gtezpxnkip.html

Java: class Node { int v; Node next; }
来源：http://dali.hfpthk.cn/Article/details/gtylasbzyk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.bjfxy.top/Article/details/gtitsflkqz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttccyojat.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sysykeji.top/Article/details/gtpvabxtgo.html

[N11] 二叉树中序遍历
来源：http://dali.aizwys.cn/Article/details/gtktijioea.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jianghu66.top/Article/details/gtdxxsasps.html

PHP:  // 手写递归函数
来源：http://dali.cdnleiting.top/Article/details/gtiuibhehl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gtutuizkjv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gtqbcelrqc.html

Java: // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtvlabwuyp.html

Go:   // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gtnifdrqnc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.daxiang520.top/Article/details/gtyqaahkgj.html

C#:   // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmnuxvcs.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.vqdsnc.cn/Article/details/gtawgkvaos.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fengsongda.top/Article/details/gtghqfgyzv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.guannengcc.top/Article/details/gtzdirlqrp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gtzfkdigfw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gtuqwrybmk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gtxrermiif.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymonbwqf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.andypj.xyz/Article/details/gtgztpbgoy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gtrhjgtygv.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtoibioeoa.html

O. 并发与异步
来源：http://dali.iojbl.cn/Article/details/gtpobctuth.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfcwlnom.html

[O01] 启动一个线程
来源：http://dali.chenzaomai.com/Article/details/gtymzzmkti.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ybcxt.top/Article/details/gtprsuvkrp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj202588.top/Article/details/gtzbykmpnp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxwkogjs.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gtdktvbqlz.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhongyouzk.top/Article/details/gtzimyugli.html

Go:   go f()
来源：http://dali.yj20258888.top/Article/details/gtablazifj.html

Ruby: Thread.new { f }
来源：http://dali.hnxiangtu.top/Article/details/gtwwmzfjpu.html

C#:   Task.Run(() => F());
来源：http://dali.316326.xyz/Article/details/gtmcurwsie.html

[O02] 使用线程池
来源：http://dali.hnxiangtu.top/Article/details/gtcsgbqhfd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xziqi.cn/Article/details/gtacdtcqdz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhiwuduotai.top/Article/details/gtvrxgnddf.html

JS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gtsisaitax.html

TS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gtxbxebjpc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cashguo.top/Article/details/gtjybyyadk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sysykeji.top/Article/details/gtxiawfxid.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zdqjudy.top/Article/details/gtznzwaleg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tian-w.cn/Article/details/gtehvavhvu.html

[O03] 加锁保护共享数据
来源：http://dali.shzxlz.cn/Article/details/gtcrmpqnjo.html

Py:   with lock: shared += 1
来源：http://dali.zhengqikj.top/Article/details/gtjfoqoowo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shzxlz.cn/Article/details/gtnplhxyjg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xziqi.cn/Article/details/gtzvytoroo.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gtoopdyaqf.html

Java: synchronized (this) { shared++; }
来源：http://dali.yonumen.top/Article/details/gtkcluyoqg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sxryk.cn/Article/details/gtyyomwsdd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxuanxn.top/Article/details/gtmgldkoqq.html

C#:   lock (gate) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gtxtqitjci.html

[O04] 定义异步函数并等待
来源：http://dali.quarkkingdee.top/Article/details/gtdeuexczo.html

Py:   async def f():⏎    await g()
来源：http://dali.birdmap.top/Article/details/gtvohlfxmu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yangfankeji.com/Article/details/gtqducigpw.html

JS:   async function f() { await g(); }
来源：http://dali.316326.xyz/Article/details/gtigaxrqxj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.birdmap.top/Article/details/gtwghhzkrv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xziqi.cn/Article/details/gtkstnzwjf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.mhx1999.top/Article/details/gtvtmnjhjq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.316326.xyz/Article/details/gtlwpzqvmj.html

C#:   async Task F() { await G(); }
来源：http://dali.xinyue.icu/Article/details/gtzxeclikk.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhengqikj.top/Article/details/gtbaikpjkh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.vqdsnc.cn/Article/details/gtfbjfsvck.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.birdmap.top/Article/details/gtukebruge.html

JS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvxsjnfj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtpynzonyt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sysykeji.top/Article/details/gtkotchejd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guowangkeji.top/Article/details/gtxejjklew.html

Ruby: threads.map(&:join)
来源：http://dali.fengsongda.top/Article/details/gtmcbdctjp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj202588.top/Article/details/gtemzglvmh.html

[O06] 使用进程池
来源：http://dali.mhx1999.top/Article/details/gtrnijglri.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258888.top/Article/details/gtzenegunn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnqzz.top/Article/details/gtpzpucter.html

JS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gtsiqhzruh.html

TS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gtgyjknijy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuxming.cn/Article/details/gtlrwznnnp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangshuangyany.cn/Article/details/gtlunulnvi.html

Ruby: // fork 块
来源：http://dali.cqqwz.cn/Article/details/gtafcgdnrb.html

C#:   Parallel.For
来源：http://dali.fzhhl.top/Article/details/gtwclogsra.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtkghxymth.html

P. 常用工具函数
来源：http://dali.smart0.xyz/Article/details/gtnmwwyjfo.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtbiybcopk.html

[P01] 生成 UUID
来源：http://dali.svipenyu.cn/Article/details/gtgpadaucj.html

Py:   str(uuid.uuid4())
来源：http://dali.jinghuilouyu.cn/Article/details/gtafdwuqen.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gtyogsvule.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gtpzwgsppx.html

TS:   crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gtxwbmqigj.html

Java: UUID.randomUUID().toString()
来源：http://dali.gzhubu.top/Article/details/gtpmbxndrn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dashuyun.cn/Article/details/gtasrrktlh.html

Ruby: SecureRandom.uuid
来源：http://dali.birdmap.top/Article/details/gtojevjmdn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tianlin.xyz/Article/details/gttzlrdyzd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigufen.top/Article/details/gtdzcxxqgi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xziqi.cn/Article/details/gtjqmxsekt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hywenlv.cn/Article/details/gtcjitmvet.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cheryme.top/Article/details/gtvijrlfuu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ybcxt.top/Article/details/gtsdgvpnig.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guannengcc.top/Article/details/gtsfzjaoki.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxinkj.top/Article/details/gthokdqjus.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhengqikj.top/Article/details/gtuptjrcyo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shuidangran.top/Article/details/gtmenqznth.html

[P03] 生成短随机字符串
来源：http://dali.wangdashe.top/Article/details/gtirxgopks.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.mhx1999.top/Article/details/gtuoxkusbg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yanxiufei.cn/Article/details/gtlsbwecvp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gtfopmwzoc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gtbvwrtauh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenlongwang.top/Article/details/gtnkkvlmbg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.svipenyu.cn/Article/details/gtusoolidr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cqqwz.cn/Article/details/gtvwfeoeyv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guannengcc.top/Article/details/gtykxwremk.html

[P04] 求长度
来源：http://dali.daxiang520.top/Article/details/gtxwfpqxhq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gaohongyu789.top/Article/details/gtcvodxxrx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtiksqqluq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.haohaochexian.top/Article/details/gtqjzulpjj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gtyxpsiiqa.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gtytpretkk.html

Go:   len(arr);  len(m)
来源：http://dali.zhongyouzk.top/Article/details/gtrpclpuif.html

Ruby: x.length;  x.size
来源：http://dali.zycfv.cn/Article/details/gtnreqfrny.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yangfankeji.com/Article/details/gtsofmlasg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbltpvamx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guannengcc.top/Article/details/gtisngwfkk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yvedp.cn/Article/details/gtotknikoh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ehwqpu.com/Article/details/gtzoclmega.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gtgpbqhagm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nanxinkj.top/Article/details/gtaovwzrak.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.smart0.xyz/Article/details/gtlcivtgam.html

Ruby: a == b
来源：http://dali.pycfn.com/Article/details/gthlhaqqey.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sufxvd.cn/Article/details/gtugwzfmhw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sufxvd.cn/Article/details/gtcvrdvxzy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gotoacloud.top/Article/details/gtjvdmkcsf.html

PHP:  if (empty($x)) {}
来源：http://dali.fzhhl.top/Article/details/gtvuludzgb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258888.top/Article/details/gtqyaswrwn.html

TS:   if (x == null) {}
来源：http://dali.yuanzhike.top/Article/details/gtjrnbjrlg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gtoqywynye.html

Go:   if x == nil {}
来源：http://dali.sweek.top/Article/details/gtavcsawft.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sufxvd.cn/Article/details/gtvnxdgeec.html

C#:   if (x is null) {}
来源：http://dali.haohaochexian.top/Article/details/gtovsxznsp.html

[P07] 防抖与节流
来源：http://dali.dianchejie.cn/Article/details/gtqlsuzazm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tianlin.xyz/Article/details/gtrdphfvhr.html

PHP:  // 手写时间戳比较
来源：http://dali.ydzc1.top/Article/details/gtjqjlmmva.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gtxzzeesbq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gtnclqmtmf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sysykeji.top/Article/details/gtshfvfeeh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.smart0.xyz/Article/details/gttnzgoyot.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guowangkeji.top/Article/details/gtqqzyarqs.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuetiantiany.cn/Article/details/gtszcxbphy.html

[P08] 处理浮点精度问题
来源：http://dali.birdmap.top/Article/details/gtprsgccin.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yuxming.cn/Article/details/gtkrzyaqbe.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tianlin.xyz/Article/details/gtgkovrxaa.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jqgufenzy.top/Article/details/gtrcyswfls.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xylfe.cn/Article/details/gtctposldf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cashguo.top/Article/details/gthhgrfast.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.pengpengdd.cyou/Article/details/gtnkgbssph.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yongpay.top/Article/details/gtwbfczlfb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cheryme.top/Article/details/gtfxysvwec.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtozjewspu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hammf.cn/Article/details/gtsbptzrcq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtejgvdaiq.html

[Q01] 创建表
来源：http://dali.shzxlz.cn/Article/details/gttdvmpfaf.html


<!-- 参考信息 -->