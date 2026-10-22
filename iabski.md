代发 wailian999

Ruby: ARGV
来源：http://dali.gzhubu.top/Article/details/gt2ebfojeiy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ljbliczs.html

[M02] 读取环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2jdxgmpti.html

Py:   os.environ.get("HOME")
来源：http://dali.fengsongda.top/Article/details/gt2zgikhkzm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gt2ahylvluk.html

JS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gt2jdftteex.html

TS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gt2ilvvuduo.html

Java: System.getenv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gt2ekuxmgqs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vaivklph.html

Ruby: ENV["HOME"]
来源：http://dali.hammf.cn/Article/details/gt2wfyvnudr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.316326.xyz/Article/details/gt2hjollmwu.html

[M03] 执行外部命令
来源：http://dali.dashuyun.cn/Article/details/gt2ffobrekt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.havefunace.top/Article/details/gt2ssijcbem.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sufxvd.cn/Article/details/gt2fzeaipss.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gt2swxebztb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gt2kixlfolf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhoulong.xyz/Article/details/gt2oldbsyda.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jlsjyb.cn/Article/details/gt2amohjeih.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yonumen.top/Article/details/gt2kofmgcqa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gt2bhdymkjq.html

[M04] 获取当前工作目录
来源：http://dali.yueranfly.top/Article/details/gt2xavtawwx.html

Py:   os.getcwd()
来源：http://dali.jqgfzy.top/Article/details/gt2lvwohccs.html

PHP:  getcwd();
来源：http://dali.dashuyun.cn/Article/details/gt2soyigbkp.html

JS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gt2wlndguao.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gt2murphurg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daria6918.cn/Article/details/gt2arreckci.html

Go:   os.Getwd()
来源：http://dali.hfpthk.cn/Article/details/gt2igndgtqo.html

Ruby: Dir.pwd
来源：http://dali.yvedp.cn/Article/details/gt2tpqfeliq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xylfe.cn/Article/details/gt2vytqyvan.html

[M05] 设置退出码
来源：http://dali.jinqigufen.top/Article/details/gt2mydeoayy.html

Py:   sys.exit(1)
来源：http://dali.cashguo.top/Article/details/gt2qqbnarrl.html

PHP:  exit(1);
来源：http://dali.sysykeji.top/Article/details/gt2qsqkiolg.html

JS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rawwfvkq.html

TS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2olgvbcwb.html

Java: System.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbvvnbaq.html

Go:   os.Exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2ngqqgyji.html

Ruby: exit 1
来源：http://dali.haohaochexian.top/Article/details/gt2hmytqmhy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxuanxn.top/Article/details/gt2hlmzbecl.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gt2weparpvx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gt2jjdlfgui.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aizwys.cn/Article/details/gt2aijjbhql.html

JS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gt2zvwijbpc.html

TS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gt2beiklkcf.html

Java: System.err.println("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2oplpawhl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pycfn.com/Article/details/gt2egscjzsc.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gt2sdicanlz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aizwys.cn/Article/details/gt2ojwovyft.html

[M07] 判断是否为主入口
来源：http://dali.mhx1999.top/Article/details/gt2qonakcsy.html

Py:   if __name__ == "__main__":
来源：http://dali.shzxlz.cn/Article/details/gt2oqcfmhmz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cashguo.top/Article/details/gt2bvmtzvdq.html

JS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gt2ycaolcdm.html

TS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gt2obbvkiya.html

Java: public static void main(String[] args)
来源：http://dali.snrcjt.cn/Article/details/gt2rryoljij.html

Go:   func main()
来源：http://dali.jianghu66.top/Article/details/gt2bsmiygrv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yanxiufei.cn/Article/details/gt2puzvpwtr.html

C#:   static void Main(string[] args)
来源：http://dali.svipenyu.cn/Article/details/gt2apkslubr.html

[M08] 获取系统与运行时信息
来源：http://dali.hywenlv.cn/Article/details/gt2vjxbgpgn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gzhubu.top/Article/details/gt2tttdpjks.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pycfn.com/Article/details/gt2eafhjzxx.html

JS:   process.platform;  process.version
来源：http://dali.sufxvd.cn/Article/details/gt2jzgptmup.html

TS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gt2gcurazyp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhixingplan.top/Article/details/gt2nanzrnrm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ydzc1.top/Article/details/gt2dahddjuh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hywenlv.cn/Article/details/gt2aogcydji.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuetiantiany.cn/Article/details/gt2nyratxtd.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2zlxglfof.html

N. 数据结构与算法
来源：http://dali.ehwqpu.com/Article/details/gt2xqtrnrah.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2nlvaozdt.html

[N01] 二分查找（有序数组）
来源：http://dali.mhx1999.top/Article/details/gt2xuexqndm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2lzlkmxwc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.snrcjt.cn/Article/details/gt2uwobsoss.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vmgminpn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gt2afvatguv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bqyscpti.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2liikzjsm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sxryk.cn/Article/details/gt2nfxwycka.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vvcmgtjy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dianchejie.cn/Article/details/gt2plwmkoaa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gt2ypwbrsru.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aizwys.cn/Article/details/gt2xaovvgdz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2knrrghwo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gt2agzvovaq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hysaishi.cn/Article/details/gt2kvwstucy.html

Go:   slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2tiugcvdy.html

Ruby: arr.sort
来源：http://dali.dianchejie.cn/Article/details/gt2mtmljywn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daxiang520.top/Article/details/gt2milxgivm.html

[N03] 快速排序（分治示例）
来源：http://dali.hysaishi.cn/Article/details/gt2zvgdeyet.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dianchejie.cn/Article/details/gt2boaxsybs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fzhhl.top/Article/details/gt2eslhoaig.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2thjupcaj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbyvzvhf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gaohongyu789.top/Article/details/gt2smmbbzeu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.0kj1m.cn/Article/details/gt2nvwzmkgo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xinyue.icu/Article/details/gt2ybqzywin.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shzxlz.cn/Article/details/gt2fcizwpma.html

[N04] 斐波那契数列
来源：http://dali.nanxuanxn.top/Article/details/gt2zzknsieo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gt2elesroyd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gt2kirprpmt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sboxtozx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rhnbfzzz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gt2slejbxkp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.bjfxy.top/Article/details/gt2euyxebgz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gt2bvqnfnpd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gt2xcnlzckc.html

[N05] 最大公约数
来源：http://dali.nanxinkj.top/Article/details/gt2lvzxaizz.html

Py:   math.gcd(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pbsjlqgz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gt2birflnxt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gt2rplnhqhj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gt2akzslavu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cheryme.top/Article/details/gt2reegadan.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tian-w.cn/Article/details/gt2orsfipei.html

Ruby: a.gcd(b)
来源：http://dali.pycfn.com/Article/details/gt2mocnzbgx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.haohaochexian.top/Article/details/gt2ldnpwxyu.html

[N06] 判断回文字符串
来源：http://dali.jianghu66.top/Article/details/gt2tbqvmmif.html

Py:   s == s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2ehilobho.html

PHP:  $s === strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gt2cmvjqksw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gt2wywluzek.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gt2izegxbyq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gogol.net.cn/Article/details/gt2ftwbhczv.html

Go:   // 双指针从两端比较
来源：http://dali.9152youxi.cn/Article/details/gt2jckmgzlw.html

Ruby: s == s.reverse
来源：http://dali.zhongyouzk.top/Article/details/gt2yjhifbtv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gt2gnleycxc.html

[N07] 两数之和（返回下标）
来源：http://dali.zdqjudy.top/Article/details/gt2lekispyp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhengqikj.top/Article/details/gt2otudjdxk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuanzx.com/Article/details/gt2zwoschow.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cheryme.top/Article/details/gt2tkgmghex.html

TS:   // 手写 Map<string, number>
来源：http://dali.hywenlv.cn/Article/details/gt2gabhttbm.html

Java: // 手写 HashMap
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mznbmhjt.html

Go:   // 手写 map[int]int
来源：http://dali.bjfxy.top/Article/details/gt2dknayuvx.html

Ruby: // 手写 Hash
来源：http://dali.xziqi.cn/Article/details/gt2yyquzjkr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.iojbl.cn/Article/details/gt2hexhyupx.html

[N08] 生成全排列
来源：http://dali.yuxming.cn/Article/details/gt2kpxpbktx.html

Py:   itertools.permutations(arr)
来源：http://dali.hnqzz.top/Article/details/gt2jlimfkad.html

PHP:  // 手写递归交换
来源：http://dali.yongpay.top/Article/details/gt2dfgttwmn.html

JS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2pxvwxyrl.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sxirmrge.html

Java: // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gt2hhlpmvon.html

Go:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gt2mkyycszw.html

Ruby: arr.permutation.to_a
来源：http://dali.nwbrower.top/Article/details/gt2oqxmauvk.html

C#:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2fxkibelp.html

[N09] 栈与队列
来源：http://dali.fzhhl.top/Article/details/gt2rlgjejws.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2iyuaieyk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gt2femxsyig.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gt2rwnhfqxx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xylfe.cn/Article/details/gt2ffowvkjh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ehwqpu.com/Article/details/gt2hhbqmxsd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.0kj1m.cn/Article/details/gt2qhdgciyj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gt2puxzrpcw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cashguo.top/Article/details/gt2fcnqjpxz.html

[N10] 链表节点定义
来源：http://dali.feifeiyinyue.top/Article/details/gt2getvgjyf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.iojbl.cn/Article/details/gt2kvbydble.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cucudq.cn/Article/details/gt2iissgouy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sufxvd.cn/Article/details/gt2wtztloxz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhengqikj.top/Article/details/gt2aqfbhixi.html

Java: class Node { int v; Node next; }
来源：http://dali.fzhhl.top/Article/details/gt2sjbpszqw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daria6918.cn/Article/details/gt2wcztohzz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuanzhike.top/Article/details/gt2zvqeorwj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yongpay.top/Article/details/gt2gokuwbxr.html

[N11] 二叉树中序遍历
来源：http://dali.hnqzz.top/Article/details/gt2ehtkbhze.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinghuilouyu.cn/Article/details/gt2etoakenf.html

PHP:  // 手写递归函数
来源：http://dali.xylfe.cn/Article/details/gt2onlcgpqn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yaqmhrsv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gt2cnfncsbx.html

Java: // 手写递归
来源：http://dali.gzhubu.top/Article/details/gt2gyksuwyy.html

Go:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2llxawqrz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.bjfxy.top/Article/details/gt2mzcssado.html

C#:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gt2gbxqdwhj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnqzz.top/Article/details/gt2ebulozip.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xylfe.cn/Article/details/gt2lxzzkewy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zycfv.cn/Article/details/gt2edpkforw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gt2pbxvpsnm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gt2aziwzhhz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gt2azcmqzey.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhengqikj.top/Article/details/gt2xjrzpzvn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuanzx.com/Article/details/gt2rsjykmoc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jlsjyb.cn/Article/details/gt2mtnqjzpd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvpnoep.html

O. 并发与异步
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qfhqnefa.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2iwvtxucx.html

[O01] 启动一个线程
来源：http://dali.zhengqikj.top/Article/details/gt2xlzicjgh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhiwuduotai.top/Article/details/gt2gfzfgbbu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.andypj.xyz/Article/details/gt2lehcvbmg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.9152youxi.cn/Article/details/gt2gozpsenz.html

TS:   // 同 JS
来源：http://dali.havefunace.top/Article/details/gt2azezvava.html

Java: new Thread(() -> f()).start()
来源：http://dali.tian-w.cn/Article/details/gt2zwsrwowu.html

Go:   go f()
来源：http://dali.tianlin.xyz/Article/details/gt2fkmaupta.html

Ruby: Thread.new { f }
来源：http://dali.tian-w.cn/Article/details/gt2odvclffj.html

C#:   Task.Run(() => F());
来源：http://dali.vqdsnc.cn/Article/details/gt2pvvfsubc.html

[O02] 使用线程池
来源：http://dali.cqqwz.cn/Article/details/gt2iurjajvr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258.top/Article/details/gt2lqlcumft.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yongpay.top/Article/details/gt2pjqrvorp.html

JS:   // worker_threads 线程池
来源：http://dali.snrcjt.cn/Article/details/gt2pforppfh.html

TS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gt2bruhnudi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yongpay.top/Article/details/gt2mesafdpk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangshuangyany.cn/Article/details/gt2iibbyhpw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangshuangyany.cn/Article/details/gt2povvwrml.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tian-w.cn/Article/details/gt2tcpkdibd.html

[O03] 加锁保护共享数据
来源：http://dali.snrcjt.cn/Article/details/gt2vhvxscgz.html

Py:   with lock: shared += 1
来源：http://dali.xylfe.cn/Article/details/gt2hlllstzt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinqigufen.top/Article/details/gt2xboirgzp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.meibo888.top/Article/details/gt2femdpckn.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zijmdccv.html

Java: synchronized (this) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gt2vlrccloh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hywenlv.cn/Article/details/gt2qdjlsmdd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cdnleiting.top/Article/details/gt2evxzhtov.html

C#:   lock (gate) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gt2yvlvjcet.html

[O04] 定义异步函数并等待
来源：http://dali.gotoacloud.top/Article/details/gt2ahdcrnvx.html

Py:   async def f():⏎    await g()
来源：http://dali.ybcxt.top/Article/details/gt2tmkfhjck.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.vqdsnc.cn/Article/details/gt2lzkmyvzc.html

JS:   async function f() { await g(); }
来源：http://dali.fzhhl.top/Article/details/gt2jhefadwn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.smart0.xyz/Article/details/gt2dbzbmedy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigfzy.top/Article/details/gt2eeudbhys.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yongpay.top/Article/details/gt2lktnxtue.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhixingplan.top/Article/details/gt2rvfsznvd.html

C#:   async Task F() { await G(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2nxpoygpb.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangshuangyany.cn/Article/details/gt2cserhhpn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hysaishi.cn/Article/details/gt2ydgwbybz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.havefunace.top/Article/details/gt2nvpyuxls.html

JS:   await Promise.all(tasks)
来源：http://dali.jiagoushi.top/Article/details/gt2zmxzbrvm.html

TS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gt2yflymioa.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ybcxt.top/Article/details/gt2sfeofsaw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhoulong.xyz/Article/details/gt2rlcmpikn.html

Ruby: threads.map(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hxbuilyx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vkakeeej.html

[O06] 使用进程池
来源：http://dali.yvedp.cn/Article/details/gt2whbgyqke.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ksfoezlq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgfzy.top/Article/details/gt2jrbrmeej.html

JS:   // child_process / cluster 模块
来源：http://dali.zhongyouzk.top/Article/details/gt2yhyhdscy.html

TS:   // child_process / cluster 模块
来源：http://dali.hnxiangtu.top/Article/details/gt2uunjlsjh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuanzx.com/Article/details/gt2isjybpxb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.birdmap.top/Article/details/gt2kxobexel.html

Ruby: // fork 块
来源：http://dali.jlsjyb.cn/Article/details/gt2vmuqkggr.html

C#:   Parallel.For
来源：http://dali.yj20258.top/Article/details/gt2cdawkuqd.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2wuyjzpuz.html

P. 常用工具函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rnahvwcm.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2upaiokca.html

[P01] 生成 UUID
来源：http://dali.jlsjyb.cn/Article/details/gt2nmjgltjk.html

Py:   str(uuid.uuid4())
来源：http://dali.zycfv.cn/Article/details/gt2qaomrhak.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.bjfxy.top/Article/details/gt2rvvnunnc.html

JS:   crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gt2dmiglfuc.html

TS:   crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gt2ycfseaav.html

Java: UUID.randomUUID().toString()
来源：http://dali.hfpthk.cn/Article/details/gt2ycylitas.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ydzc1.top/Article/details/gt2gzwqqgsh.html

Ruby: SecureRandom.uuid
来源：http://dali.ivvv.top/Article/details/gt2rfxfkdzb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dianchejie.cn/Article/details/gt2utzkdwcc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.9152youxi.cn/Article/details/gt2sffjlqqi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhongyouzk.top/Article/details/gt2bmzirsoe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guowangkeji.top/Article/details/gt2xtzpbkky.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tanke756.top/Article/details/gt2zfvhcvcc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hywenlv.cn/Article/details/gt2jzawjlng.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ejjkhuht.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zdqjudy.top/Article/details/gt2wdrnclzz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sysykeji.top/Article/details/gt2dcegzlxk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.andypj.xyz/Article/details/gt2wnfnvnqd.html

[P03] 生成短随机字符串
来源：http://dali.0kj1m.cn/Article/details/gt2oftpnzce.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jiagoushi.top/Article/details/gt2ltegmecz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigufen.top/Article/details/gt2erlbwswf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gt2sowiocey.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yueranfly.top/Article/details/gt2cjrxgwxd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cqqwz.cn/Article/details/gt2ykbwqkcj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuetiantiany.cn/Article/details/gt2tfxfluis.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangdashe.top/Article/details/gt2asrecxjs.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yongpay.top/Article/details/gt2jhzozsrl.html

[P04] 求长度
来源：http://dali.cucudq.cn/Article/details/gt2kapcctad.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daxiang520.top/Article/details/gt2jcfzlmku.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gt2pkzcjhxk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daria6918.cn/Article/details/gt2kirqhscj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gt2ggaijifs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nmqsqudb.html

Go:   len(arr);  len(m)
来源：http://dali.ydzc1.top/Article/details/gt2acclidan.html

Ruby: x.length;  x.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qslehaiu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.daria6918.cn/Article/details/gt2qensgdri.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dianchejie.cn/Article/details/gt2snyykcnm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258888.top/Article/details/gt2xzaskerx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vbihrijn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hywenlv.cn/Article/details/gt2atgdqmac.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gt2ygnimrao.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hammf.cn/Article/details/gt2ncztspfi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gt2txfsakjh.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfsoali.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhiwuduotai.top/Article/details/gt2znpathyd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cdnleiting.top/Article/details/gt2qqjilaqx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.mhx1999.top/Article/details/gt2rvwpahsp.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258888.top/Article/details/gt2vmoaxizj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuanzhike.top/Article/details/gt2qibsrrdc.html

TS:   if (x == null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bbconifg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gt2ftsyxnqo.html

Go:   if x == nil {}
来源：http://dali.yuxming.cn/Article/details/gt2vfxlbdcb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yanxiufei.cn/Article/details/gt2zgjnxbjj.html

C#:   if (x is null) {}
来源：http://dali.meibo888.top/Article/details/gt2nyfstbxr.html

[P07] 防抖与节流
来源：http://dali.tian-w.cn/Article/details/gt2kvbvwmka.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.andypj.xyz/Article/details/gt2howmfrma.html

PHP:  // 手写时间戳比较
来源：http://dali.yangfankeji.com/Article/details/gt2fpeqnrpg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gt2sahynvfe.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gt2xvsjxuii.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xylfe.cn/Article/details/gt2kziaeivb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eilvhfkd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gzhubu.top/Article/details/gt2ivowzawc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sweek.top/Article/details/gt2bxvikltv.html

[P08] 处理浮点精度问题
来源：http://dali.ydzc1.top/Article/details/gt2cyqznezf.html


<!-- 参考信息 -->