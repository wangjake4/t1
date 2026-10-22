代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gtvinwfzfg.html

JS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gttqvcmtss.html

TS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrovdyyrg.html

Java: System.getenv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtruytllxx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtzwaqgrnq.html

Ruby: ENV["HOME"]
来源：http://dali.9152youxi.cn/Article/details/gtrjmhmgfb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtvxvpxyjy.html

[M03] 执行外部命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdnvbvsp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.redwolf501.top/Article/details/gtqnznjliw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.vqdsnc.cn/Article/details/gtnufphisa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtrovbqqrv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtqrlpvyil.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ydzc1.top/Article/details/gtknswsuwj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shuidangran.top/Article/details/gtashklvzo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shuidangran.top/Article/details/gtlcqmsmrk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sysykeji.top/Article/details/gtqzoqknxk.html

[M04] 获取当前工作目录
来源：http://dali.yj202588.top/Article/details/gtwdougtsz.html

Py:   os.getcwd()
来源：http://dali.tianlin.xyz/Article/details/gtsnhkvaip.html

PHP:  getcwd();
来源：http://dali.cashguo.top/Article/details/gtuizswylv.html

JS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtpyazifqi.html

TS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gtlxdulsco.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxuanxn.top/Article/details/gtvidplgxb.html

Go:   os.Getwd()
来源：http://dali.hnqzz.top/Article/details/gtyzdvxmrb.html

Ruby: Dir.pwd
来源：http://dali.chenlongwang.top/Article/details/gtauusvrcn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuanzhike.top/Article/details/gtoqlnsnie.html

[M05] 设置退出码
来源：http://dali.gogol.net.cn/Article/details/gtwbazrbrw.html

Py:   sys.exit(1)
来源：http://dali.tian-w.cn/Article/details/gthqshtize.html

PHP:  exit(1);
来源：http://dali.havefunace.top/Article/details/gthbrkjyke.html

JS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtflbpgoyr.html

TS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtpkxtwtwd.html

Java: System.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtbzdoooss.html

Go:   os.Exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtoilqxqvd.html

Ruby: exit 1
来源：http://dali.jinqigfzy.top/Article/details/gtmydibczi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jianghu66.top/Article/details/gtvmjxviby.html

[M06] 向标准错误输出
来源：http://dali.pengpengdd.cyou/Article/details/gtlrcuopra.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gtjmmlcdeb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.feifeiyinyue.top/Article/details/gtvcfkcutv.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtdmscoxcw.html

TS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtddwsowqe.html

Java: System.err.println("err")
来源：http://dali.fzhhl.top/Article/details/gtbayukmbl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgfzy.top/Article/details/gtdfmglpoe.html

Ruby: warn "err"
来源：http://dali.0kj1m.cn/Article/details/gtadbvxkua.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gotoacloud.top/Article/details/gtbuvojdyh.html

[M07] 判断是否为主入口
来源：http://dali.xylfe.cn/Article/details/gtaqnavxeq.html

Py:   if __name__ == "__main__":
来源：http://dali.gotoacloud.top/Article/details/gttcmliktm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gtlgtbuhxx.html

JS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gtmsfmoqzw.html

TS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gtazdjvcgt.html

Java: public static void main(String[] args)
来源：http://dali.hnqzz.top/Article/details/gtzgyknfta.html

Go:   func main()
来源：http://dali.ehwqpu.com/Article/details/gtsfrgfwjm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgufenzy.top/Article/details/gtkxlznnhj.html

C#:   static void Main(string[] args)
来源：http://dali.birdmap.top/Article/details/gtxfsmavzj.html

[M08] 获取系统与运行时信息
来源：http://dali.yueranfly.top/Article/details/gthlpzssck.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pengpengdd.cyou/Article/details/gtlbucrkee.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tianlin.xyz/Article/details/gtrcdfxohp.html

JS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gtfkcbcuzh.html

TS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gtvdslmbyt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnsqruohi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zycfv.cn/Article/details/gtacynmlpu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gtpjzdfser.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgufenzy.top/Article/details/gtwogfawaa.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtwxkxwvln.html

N. 数据结构与算法
来源：http://dali.yj20258.top/Article/details/gtcouczmql.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtlarromjg.html

[N01] 二分查找（有序数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gtofojeqxn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtizirkuus.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gogol.net.cn/Article/details/gtvcwuntyy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gtzdndavnb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtuxywoqct.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtfmquqfoc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtyhddcdwv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.316326.xyz/Article/details/gtkrdthlux.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtpynywbkn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuxming.cn/Article/details/gtmbkgkuci.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gtpdpsuqcz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtwsagvoat.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyduuxye.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gteawducqz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xylfe.cn/Article/details/gtmpkkiexu.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gtrlfhysns.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtsmovrjim.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.kuanghao11.cn/Article/details/gtrmugrnlx.html

[N03] 快速排序（分治示例）
来源：http://dali.yonumen.top/Article/details/gtxyurihpi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.havefunace.top/Article/details/gtmadzzkon.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgufenzy.top/Article/details/gtwnwhomnv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gtyytyqlau.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gtaoibofyh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.meibo888.top/Article/details/gtdghjifyn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigfzy.top/Article/details/gtjvwnsfxa.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yvedp.cn/Article/details/gtfdwanrxz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aizwys.cn/Article/details/gtinwdgyhg.html

[N04] 斐波那契数列
来源：http://dali.shzxlz.cn/Article/details/gtoozxepxc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gtzfezdpln.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj202588.top/Article/details/gtiuzvdrly.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtyffeiqva.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtiyhdhbnl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gzhubu.top/Article/details/gtpjkgrygm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sysykeji.top/Article/details/gtmixhnthc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gtkbgvrsjq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtmuyhopsj.html

[N05] 最大公约数
来源：http://dali.xuanzx.com/Article/details/gtersnohbu.html

Py:   math.gcd(a, b)
来源：http://dali.yj202588.top/Article/details/gtalwotcfl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgutlezp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gtbdapppls.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gtjfqygjbf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guannengcc.top/Article/details/gtslovgqza.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zycfv.cn/Article/details/gtjezhmynr.html

Ruby: a.gcd(b)
来源：http://dali.yj20258.top/Article/details/gtarouarsp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.mhx1999.top/Article/details/gtgvisvmik.html

[N06] 判断回文字符串
来源：http://dali.hammf.cn/Article/details/gtsobsfyok.html

Py:   s == s[::-1]
来源：http://dali.yj20258888.top/Article/details/gtcvfngqtv.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtfvtsrvlv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtosfprjif.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtapvtvizt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuxming.cn/Article/details/gtswwbhsuj.html

Go:   // 双指针从两端比较
来源：http://dali.guowangkeji.top/Article/details/gtyxztmzaz.html

Ruby: s == s.reverse
来源：http://dali.xuanzx.com/Article/details/gtyzsezkab.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gthtgxnynu.html

[N07] 两数之和（返回下标）
来源：http://dali.jinqigufen.top/Article/details/gtrvilpucp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dashuyun.cn/Article/details/gtbnbbnplu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ydzc1.top/Article/details/gttheaiqxu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tanke756.top/Article/details/gtdnewcmxl.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj202588.top/Article/details/gtjfzpbmjo.html

Java: // 手写 HashMap
来源：http://dali.hongshengwenyu.top/Article/details/gtxbpagron.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqlebpyqb.html

Ruby: // 手写 Hash
来源：http://dali.nanxinkj.top/Article/details/gtiheboviw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daxiang520.top/Article/details/gtonptudmz.html

[N08] 生成全排列
来源：http://dali.vqdsnc.cn/Article/details/gtjfmeaqya.html

Py:   itertools.permutations(arr)
来源：http://dali.yj202588.top/Article/details/gtwykukhnw.html

PHP:  // 手写递归交换
来源：http://dali.wangshuangyany.cn/Article/details/gtecbzhhtd.html

JS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtobrndclv.html

TS:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtilntthqr.html

Java: // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gterqcidva.html

Go:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtwfrtpwjl.html

Ruby: arr.permutation.to_a
来源：http://dali.aizwys.cn/Article/details/gtjiqfiepe.html

C#:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtyhxugpmh.html

[N09] 栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gtmturcxvb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zycfv.cn/Article/details/gtlcuzsgxl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtsbxqihxl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gtgggrzfmt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ybcxt.top/Article/details/gtjwakykix.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gotoacloud.top/Article/details/gtigaluzez.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jianghu66.top/Article/details/gtumccivbn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtseuctwzs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gtghyonozi.html

[N10] 链表节点定义
来源：http://dali.chenzaomai.com/Article/details/gtymkkjehd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.andypj.xyz/Article/details/gtzwfvgvum.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gzhubu.top/Article/details/gtpyuljile.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hammf.cn/Article/details/gtihfuqyii.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijvawdau.html

Java: class Node { int v; Node next; }
来源：http://dali.tian-w.cn/Article/details/gthrcoqklq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ydzc1.top/Article/details/gtfomhwtih.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cqqwz.cn/Article/details/gtqditnapb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tian-w.cn/Article/details/gtxgseplhy.html

[N11] 二叉树中序遍历
来源：http://dali.cheryme.top/Article/details/gtptkewfie.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hysaishi.cn/Article/details/gtlifrrhun.html

PHP:  // 手写递归函数
来源：http://dali.sweek.top/Article/details/gthlffpuep.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gthavsyokn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gtychnnkuu.html

Java: // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtplbjswbx.html

Go:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gtdiuzysmd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yvedp.cn/Article/details/gtnhlxvqto.html

C#:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gteyptykyg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.kuanghao11.cn/Article/details/gthqwenlqd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnqzz.top/Article/details/gtwjnsxfeq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xuanzx.com/Article/details/gtzwzbfmrg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gtqvtbmoel.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gtjstofhqm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gtgiertzkm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj202588.top/Article/details/gtwwvjodhk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.svipenyu.cn/Article/details/gtdyxstofu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgufenzy.top/Article/details/gtlrwzeyeq.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gthchxumlt.html

O. 并发与异步
来源：http://dali.hongshengwenyu.top/Article/details/gtbvjptszg.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtcpxjtamm.html

[O01] 启动一个线程
来源：http://dali.jyoumei.cn/Article/details/gtuajmhxux.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shuidangran.top/Article/details/gtegmpkore.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hammf.cn/Article/details/gtkfdzeofu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.andypj.xyz/Article/details/gtozswqdtv.html

TS:   // 同 JS
来源：http://dali.chenzaomai.com/Article/details/gtrqlgoqrd.html

Java: new Thread(() -> f()).start()
来源：http://dali.bjfxy.top/Article/details/gtrqtexsuh.html

Go:   go f()
来源：http://dali.xuetiantiany.cn/Article/details/gtavqucvzx.html

Ruby: Thread.new { f }
来源：http://dali.cashguo.top/Article/details/gtcsblslmf.html

C#:   Task.Run(() => F());
来源：http://dali.yangfankeji.com/Article/details/gtapjifdhu.html

[O02] 使用线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtkunlbtiq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jianghu66.top/Article/details/gtfgcdtvxc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.snrcjt.cn/Article/details/gtsnoubvta.html

JS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gtuggqnury.html

TS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gtjjgsbwcj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cdnleiting.top/Article/details/gtamicrjob.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuanzhike.top/Article/details/gtgfobuvui.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xinyue.icu/Article/details/gtfigsxnwg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daria6918.cn/Article/details/gtyluejfnl.html

[O03] 加锁保护共享数据
来源：http://dali.shuidangran.top/Article/details/gtjbowxjfk.html

Py:   with lock: shared += 1
来源：http://dali.tanke756.top/Article/details/gtatlwlehy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cqqwz.cn/Article/details/gtaoimkdqv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrlexebr.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gtpnnrgqow.html

Java: synchronized (this) { shared++; }
来源：http://dali.ivvv.top/Article/details/gthbjzbyme.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj202588.top/Article/details/gtevcsyvyz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.bjfxy.top/Article/details/gthsptktzm.html

C#:   lock (gate) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gtsprosioe.html

[O04] 定义异步函数并等待
来源：http://dali.hfpthk.cn/Article/details/gtdedfwytt.html

Py:   async def f():⏎    await g()
来源：http://dali.gogol.net.cn/Article/details/gtxfjfnlou.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.svipenyu.cn/Article/details/gtuwxrhwlk.html

JS:   async function f() { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gtapecetpa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwwtment.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenlongwang.top/Article/details/gthphniatq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cashguo.top/Article/details/gtgkgpoesg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenlongwang.top/Article/details/gtjtagebbu.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gtvgiitmes.html

[O05] 并发执行并等待全部完成
来源：http://dali.bjfxy.top/Article/details/gtxjcgvwqd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pycfn.com/Article/details/gtyxhwazmf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zycfv.cn/Article/details/gtnybebuoi.html

JS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gtebrqxwui.html

TS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gtdzxilqwy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuxming.cn/Article/details/gtrioonoha.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgufenzy.top/Article/details/gtppdfbpxy.html

Ruby: threads.map(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gtzpgioxvg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.feifeiyinyue.top/Article/details/gtghpnxlwd.html

[O06] 使用进程池
来源：http://dali.zhongyouzk.top/Article/details/gtpcmevszx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hysaishi.cn/Article/details/gtgtmwobvo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.havefunace.top/Article/details/gttaujnien.html

JS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gtjfojptul.html

TS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gtjekbptdx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gzhubu.top/Article/details/gtaozfqliw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xinyue.icu/Article/details/gtqoiwburu.html

Ruby: // fork 块
来源：http://dali.sufxvd.cn/Article/details/gtxhnlpdyi.html

C#:   Parallel.For
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymhhsjyr.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtgmpobabj.html

P. 常用工具函数
来源：http://dali.mhx1999.top/Article/details/gtkgqhnlti.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gthhuykndv.html

[P01] 生成 UUID
来源：http://dali.cqqwz.cn/Article/details/gtogbfpwhr.html

Py:   str(uuid.uuid4())
来源：http://dali.zhengqikj.top/Article/details/gtaqzsuscl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.dianchejie.cn/Article/details/gttpqldwyq.html

JS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtwcgmtsuf.html

TS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gtiilriifn.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtysxgrpib.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hammf.cn/Article/details/gtgylznwml.html

Ruby: SecureRandom.uuid
来源：http://dali.sweek.top/Article/details/gtnoophivw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jqgufenzy.top/Article/details/gtrnjgzqim.html

[P02] MD5 / SHA256 摘要
来源：http://dali.quarkkingdee.top/Article/details/gtejwliuxb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.pycfn.com/Article/details/gtwpaihtai.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gzhubu.top/Article/details/gtqgppclwt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dianchejie.cn/Article/details/gteomxvcpd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhongyouzk.top/Article/details/gthfrkrnzd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daria6918.cn/Article/details/gtfnzlapcx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258.top/Article/details/gtqncfejxm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gzhubu.top/Article/details/gtakckqcfg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangdashe.top/Article/details/gtgykqwkhz.html

[P03] 生成短随机字符串
来源：http://dali.yj20258.top/Article/details/gtazihcrre.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cqqwz.cn/Article/details/gtzbyxwggx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.wangshuangyany.cn/Article/details/gtolhxegwj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gtrgypdlou.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxinkj.top/Article/details/gtkdlnrbep.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xinyue.icu/Article/details/gtbdfuhosg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258.top/Article/details/gtksaxbcdq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiackxdwn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258.top/Article/details/gtpznbgncg.html

[P04] 求长度
来源：http://dali.zhixingplan.top/Article/details/gtogwrnabm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.kuanghao11.cn/Article/details/gtgtielpnz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtmgtasyac.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenzaomai.com/Article/details/gtmhnesqmw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daria6918.cn/Article/details/gtxkmlzphx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cqqwz.cn/Article/details/gtltlgjlge.html

Go:   len(arr);  len(m)
来源：http://dali.gaohongyu789.top/Article/details/gtpqffqogr.html

Ruby: x.length;  x.size
来源：http://dali.zhoulong.xyz/Article/details/gtymvstlem.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xuanzx.com/Article/details/gtanouuvrl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.kuanghao11.cn/Article/details/gtcpwfyivv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhoulong.xyz/Article/details/gtkelxamwk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aizwys.cn/Article/details/gtwxnccfls.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hnxiangtu.top/Article/details/gtytipysca.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yongpay.top/Article/details/gtnfnowfyk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhiwuduotai.top/Article/details/gtxymprcec.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtsyngivbb.html

Ruby: a == b
来源：http://dali.kuanghao11.cn/Article/details/gtzyejrgyd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jqgufenzy.top/Article/details/gtpogahnfl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgufenzy.top/Article/details/gtisqvhpqa.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hywenlv.cn/Article/details/gtahdyhsab.html

PHP:  if (empty($x)) {}
来源：http://dali.daria6918.cn/Article/details/gtpcsefzih.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnxiangtu.top/Article/details/gtoltqxpit.html

TS:   if (x == null) {}
来源：http://dali.redwolf501.top/Article/details/gthubmtucr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gtkyrceroy.html

Go:   if x == nil {}
来源：http://dali.jqgufenzy.top/Article/details/gtbjwktwhr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxuanxn.top/Article/details/gtbbzpzkfk.html

C#:   if (x is null) {}
来源：http://dali.birdmap.top/Article/details/gtppysbvxf.html

[P07] 防抖与节流
来源：http://dali.xziqi.cn/Article/details/gtsiyrzoic.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.pycfn.com/Article/details/gtfpdxcmvb.html

PHP:  // 手写时间戳比较
来源：http://dali.ydzc1.top/Article/details/gtanfguflw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gtgkikjhwt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zycfv.cn/Article/details/gthqzykute.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigfzy.top/Article/details/gtuimtweto.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xylfe.cn/Article/details/gtubzqmlqi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gtpeticbfz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.kuanghao11.cn/Article/details/gtuotszzud.html

[P08] 处理浮点精度问题
来源：http://dali.sufxvd.cn/Article/details/gtveqzeexj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fzhhl.top/Article/details/gtpxwggozm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigfzy.top/Article/details/gtvyunvsff.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dashuyun.cn/Article/details/gtflrrjjqq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sxryk.cn/Article/details/gtayfaqndz.html


<!-- 参考信息 -->