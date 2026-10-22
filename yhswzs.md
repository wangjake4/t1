代发 wailian999

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtermlzran.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yueranfly.top/Article/details/gtgkjchrxs.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlxwkraf.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxinkj.top/Article/details/gtcdbvuuwd.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtxtxejsic.html

[M01] 读取命令行参数
来源：http://dali.cucudq.cn/Article/details/gtfpgryoic.html

Py:   sys.argv[1:]
来源：http://dali.jqgfzy.top/Article/details/gtevseneug.html

PHP:  $argv;  $argc;
来源：http://dali.yonumen.top/Article/details/gtpowwxqhg.html

JS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtcnijxvwa.html

TS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtrgsmxhkh.html

Java: args 数组（main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gtgptavgik.html

Go:   os.Args[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtpolysgxe.html

Ruby: ARGV
来源：http://dali.dashuyun.cn/Article/details/gthzyjeoey.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gtkojegxli.html

[M02] 读取环境变量
来源：http://dali.nwbrower.top/Article/details/gtebfhzpyu.html

Py:   os.environ.get("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtfgimdcwf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gtzugpeize.html

JS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtqpamzabs.html

TS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gtvsvowdhj.html

Java: System.getenv("HOME")
来源：http://dali.cashguo.top/Article/details/gtqfrtlrmz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtfagkuflx.html

Ruby: ENV["HOME"]
来源：http://dali.0kj1m.cn/Article/details/gtlojbgxtn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xziqi.cn/Article/details/gtdexjjeqd.html

[M03] 执行外部命令
来源：http://dali.guannengcc.top/Article/details/gtjiidqzst.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jlsjyb.cn/Article/details/gtlrvicdhp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenjidiqi.icu/Article/details/gttewhbpak.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gthxakvqrr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gtwopodlsc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.mhx1999.top/Article/details/gtilefoojd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fengsongda.top/Article/details/gttcgutzbh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ppjwa.cn/Article/details/gtknfaasva.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shuidangran.top/Article/details/gtraqpldmm.html

[M04] 获取当前工作目录
来源：http://dali.cdnleiting.top/Article/details/gtbzrxzfnl.html

Py:   os.getcwd()
来源：http://dali.chenzaomai.com/Article/details/gtydzfbizi.html

PHP:  getcwd();
来源：http://dali.smart0.xyz/Article/details/gttzgelxmf.html

JS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gtdjqrtnwd.html

TS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtquzoixpz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hammf.cn/Article/details/gtrfpyaniy.html

Go:   os.Getwd()
来源：http://dali.yuxming.cn/Article/details/gtidruuaqo.html

Ruby: Dir.pwd
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvaaxwwu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfijpwmp.html

[M05] 设置退出码
来源：http://dali.ybcxt.top/Article/details/gtprperhaj.html

Py:   sys.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtkllpaqmq.html

PHP:  exit(1);
来源：http://dali.dashuyun.cn/Article/details/gtdhwdwqjb.html

JS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gthetocrcl.html

TS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtxddxxfan.html

Java: System.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtxioqaafh.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtyghrdeux.html

Ruby: exit 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtapdeoucw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenjidiqi.icu/Article/details/gttprxbpdb.html

[M06] 向标准错误输出
来源：http://dali.sxryk.cn/Article/details/gtcvmvfdmm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobmihnfj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yanxiufei.cn/Article/details/gttmmqfhwc.html

JS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtcsxzggal.html

TS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gtfttjupnb.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gtfhpuzdjo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tianlin.xyz/Article/details/gtajfwmvea.html

Ruby: warn "err"
来源：http://dali.nanxuanxn.top/Article/details/gtydfblecn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ehwqpu.com/Article/details/gtwkyfdpqb.html

[M07] 判断是否为主入口
来源：http://dali.pengpengdd.cyou/Article/details/gtyyfgrydr.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258888.top/Article/details/gtaybwznep.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ivvv.top/Article/details/gtnkqgassl.html

JS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gtuklykzwn.html

TS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gtfifrwxtg.html

Java: public static void main(String[] args)
来源：http://dali.iojbl.cn/Article/details/gtkqfbdkdx.html

Go:   func main()
来源：http://dali.kuanghao11.cn/Article/details/gtgnljobzz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.iojbl.cn/Article/details/gtbmdfkuhf.html

C#:   static void Main(string[] args)
来源：http://dali.shuidangran.top/Article/details/gtfgjpwfgg.html

[M08] 获取系统与运行时信息
来源：http://dali.guowangkeji.top/Article/details/gtwweeagbk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zdqjudy.top/Article/details/gtksysrvrw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jianghu66.top/Article/details/gtxpjdofwc.html

JS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gthibtcnem.html

TS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gtzxfdbmkn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.0kj1m.cn/Article/details/gttlqraixo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pengpengdd.cyou/Article/details/gtknusjxsl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fengsongda.top/Article/details/gtvorerpal.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gzhubu.top/Article/details/gtqnkrfmti.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhftgbzg.html

N. 数据结构与算法
来源：http://dali.yj20258888.top/Article/details/gtzveuqjwr.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtyeugjbhu.html

[N01] 二分查找（有序数组）
来源：http://dali.9152youxi.cn/Article/details/gttiqndtiy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtgaqtsrbc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sweek.top/Article/details/gtsgxaofhd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtksvddicj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gtsnlljnjq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtelgqsbkf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtvvavurow.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.andypj.xyz/Article/details/gtkagmutvk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzekekxv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfzxmesd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gtgwiajcel.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cashguo.top/Article/details/gtdzhxolbk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjbsbkrr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gtjjyonnkr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hammf.cn/Article/details/gttudvxmfg.html

Go:   slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gthemlcdpn.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbvtrgnu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtovvvmfxv.html

[N03] 快速排序（分治示例）
来源：http://dali.yj20258.top/Article/details/gttpurewpq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cqqwz.cn/Article/details/gtonpgmuwj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.0kj1m.cn/Article/details/gtpgizsusv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gtpgwqvbyv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.quarkkingdee.top/Article/details/gtjsbhoysa.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ybcxt.top/Article/details/gtcmkytqca.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.redwolf501.top/Article/details/gtddfbwnpl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yangfankeji.com/Article/details/gtxcfyyjmv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tian-w.cn/Article/details/gtpzbujtmj.html

[N04] 斐波那契数列
来源：http://dali.jinghuilouyu.cn/Article/details/gthsinovea.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrnwztecy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtgkblvdhw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtxoreuqzf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtgjtctsfm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sxryk.cn/Article/details/gtuimjwucu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dianchejie.cn/Article/details/gtwoyklfhy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gtkhlzihwu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtychiqccn.html

[N05] 最大公约数
来源：http://dali.jqgufenzy.top/Article/details/gtsopszdqf.html

Py:   math.gcd(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gtzsuvvbus.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258.top/Article/details/gtjyytjaun.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtpfacdxth.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlwezmbta.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sxryk.cn/Article/details/gtiphswlql.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.vqdsnc.cn/Article/details/gtydprcazg.html

Ruby: a.gcd(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcolfrhf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cheryme.top/Article/details/gtjuvcoxhc.html

[N06] 判断回文字符串
来源：http://dali.ehwqpu.com/Article/details/gtebhkdnpk.html

Py:   s == s[::-1]
来源：http://dali.hnxiangtu.top/Article/details/gtchyxthoa.html

PHP:  $s === strrev($s);
来源：http://dali.redwolf501.top/Article/details/gtetdhkyyx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtkeyxaqxc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtdrfricbm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhoulong.xyz/Article/details/gtnfqnkgnz.html

Go:   // 双指针从两端比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuyzknpxu.html

Ruby: s == s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgkbtxuv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gtzjueujra.html

[N07] 两数之和（返回下标）
来源：http://dali.hongshengwenyu.top/Article/details/gtonegupkf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yuxming.cn/Article/details/gtkndqyncz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafimtzdu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gaohongyu789.top/Article/details/gtcebeodmt.html

TS:   // 手写 Map<string, number>
来源：http://dali.tian-w.cn/Article/details/gttbobdrel.html

Java: // 手写 HashMap
来源：http://dali.pycfn.com/Article/details/gtcvqxmuha.html

Go:   // 手写 map[int]int
来源：http://dali.pycfn.com/Article/details/gtajiolavf.html

Ruby: // 手写 Hash
来源：http://dali.tianlin.xyz/Article/details/gtupwqoqnu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hywenlv.cn/Article/details/gtadpaxche.html

[N08] 生成全排列
来源：http://dali.hnqzz.top/Article/details/gtvlsbfjca.html

Py:   itertools.permutations(arr)
来源：http://dali.havefunace.top/Article/details/gtygetffve.html

PHP:  // 手写递归交换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctrbagly.html

JS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtqlhfknrc.html

TS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gthpkwdqlt.html

Java: // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtmvbivtqc.html

Go:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtxfeetzmv.html

Ruby: arr.permutation.to_a
来源：http://dali.birdmap.top/Article/details/gtpnpolbrn.html

C#:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtzcapazoc.html

[N09] 栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gtihqbhqno.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.havefunace.top/Article/details/gtnmyhyreq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cashguo.top/Article/details/gtbaoqzcyb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gtcgalmdnd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.snrcjt.cn/Article/details/gthcmtfxvg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jianghu66.top/Article/details/gtdtadlkyc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.birdmap.top/Article/details/gtsrtvkvva.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtlcyjskof.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tianlin.xyz/Article/details/gtggaatuqw.html

[N10] 链表节点定义
来源：http://dali.chenlongwang.top/Article/details/gtsfqvkktu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ehwqpu.com/Article/details/gtdonysmsq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigufen.top/Article/details/gtdpidvnks.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xziqi.cn/Article/details/gtdpmnipqe.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuanzx.com/Article/details/gtgntsfaof.html

Java: class Node { int v; Node next; }
来源：http://dali.shzxlz.cn/Article/details/gtreeqdjsk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.316326.xyz/Article/details/gtlidjmzxu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sweek.top/Article/details/gtilznrqtb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zdqjudy.top/Article/details/gtoatsdnsy.html

[N11] 二叉树中序遍历
来源：http://dali.jlsjyb.cn/Article/details/gtyzqnixvh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cashguo.top/Article/details/gtlwdhmtmn.html

PHP:  // 手写递归函数
来源：http://dali.cheryme.top/Article/details/gtpygudaau.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ehwqpu.com/Article/details/gtdigomkev.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gtdoleekki.html

Java: // 手写递归
来源：http://dali.gzhubu.top/Article/details/gtwnjijicd.html

Go:   // 手写递归
来源：http://dali.316326.xyz/Article/details/gtqxigxyfa.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xziqi.cn/Article/details/gtfqrnxgeb.html

C#:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtqhrnfdnr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.svipenyu.cn/Article/details/gtpantieqk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.9152youxi.cn/Article/details/gtxkrowmst.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenzaomai.com/Article/details/gtlxnzehyx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgfzy.top/Article/details/gtvwutfsun.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gtmkiqrvat.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gtnovognbf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xuetiantiany.cn/Article/details/gtygelivdx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtpqamhxwh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gticnvwneh.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtseazuqnx.html

O. 并发与异步
来源：http://dali.shangyingyoupin.top/Article/details/gtvvobodkw.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtrfrihtnf.html

[O01] 启动一个线程
来源：http://dali.jiagoushi.top/Article/details/gtwawtfruj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gotoacloud.top/Article/details/gtutfwpmlb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sxryk.cn/Article/details/gtegjowclf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.aizwys.cn/Article/details/gtbncvbcri.html

TS:   // 同 JS
来源：http://dali.dianchejie.cn/Article/details/gtleruyodt.html

Java: new Thread(() -> f()).start()
来源：http://dali.9152youxi.cn/Article/details/gtrbpwaobz.html

Go:   go f()
来源：http://dali.yj20258.top/Article/details/gtfrgoqied.html

Ruby: Thread.new { f }
来源：http://dali.havefunace.top/Article/details/gteyoxjorv.html

C#:   Task.Run(() => F());
来源：http://dali.jiagoushi.top/Article/details/gtbpwzugku.html

[O02] 使用线程池
来源：http://dali.hammf.cn/Article/details/gtmvqkqabt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cashguo.top/Article/details/gtmfrzamaz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxuanxn.top/Article/details/gtbzcgthhx.html

JS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gtoklzusqg.html

TS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gtbpydjbys.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosciwfrq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangshuangyany.cn/Article/details/gtbiqmuplj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gotoacloud.top/Article/details/gtwxlrbhmk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbcrdmlk.html

[O03] 加锁保护共享数据
来源：http://dali.hysaishi.cn/Article/details/gtiufeamhr.html

Py:   with lock: shared += 1
来源：http://dali.hammf.cn/Article/details/gthjlualdw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.316326.xyz/Article/details/gtiamcmoju.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guowangkeji.top/Article/details/gtewhuvozd.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gtjzqjwjwl.html

Java: synchronized (this) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlphhnsd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgfzy.top/Article/details/gttyqjbwxz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.c1oappe.top/Article/details/gtiowqcmup.html

C#:   lock (gate) { shared++; }
来源：http://dali.fzhhl.top/Article/details/gtqaejajka.html

[O04] 定义异步函数并等待
来源：http://dali.dashuyun.cn/Article/details/gtlierycvd.html

Py:   async def f():⏎    await g()
来源：http://dali.jqgfzy.top/Article/details/gtxfettrpd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jlsjyb.cn/Article/details/gtrcyourul.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258.top/Article/details/gtlgicbrnr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gtifaskqlj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.svipenyu.cn/Article/details/gtnvyoseit.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daxiang520.top/Article/details/gtdeiwngbo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnxiangtu.top/Article/details/gtzzpuwvbc.html

C#:   async Task F() { await G(); }
来源：http://dali.yj202588.top/Article/details/gtebedplbl.html

[O05] 并发执行并等待全部完成
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkzaammd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cashguo.top/Article/details/gtvhmofxvq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gtgkxxfnii.html

JS:   await Promise.all(tasks)
来源：http://dali.guowangkeji.top/Article/details/gtagzwzeex.html

TS:   await Promise.all(tasks)
来源：http://dali.svipenyu.cn/Article/details/gtwrynmzpk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxuanxn.top/Article/details/gtnmgowhpa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.svipenyu.cn/Article/details/gtclxratum.html

Ruby: threads.map(&:join)
来源：http://dali.tianlin.xyz/Article/details/gtnxweryji.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cashguo.top/Article/details/gtaytpagbp.html

[O06] 使用进程池
来源：http://dali.snrcjt.cn/Article/details/gtgkrzotaj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhoulong.xyz/Article/details/gtrawobtnm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhongyouzk.top/Article/details/gthjwcxspg.html

JS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gtbqrbdzxn.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gtorovdsaf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gtalachxoy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gotoacloud.top/Article/details/gtnwqkwyad.html

Ruby: // fork 块
来源：http://dali.havefunace.top/Article/details/gteafeucyp.html

C#:   Parallel.For
来源：http://dali.yangfankeji.com/Article/details/gtrwtpkons.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtnecdnrbj.html

P. 常用工具函数
来源：http://dali.daxiang520.top/Article/details/gtlajypwjw.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtiyxhzatq.html

[P01] 生成 UUID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggiznpqj.html

Py:   str(uuid.uuid4())
来源：http://dali.shzxlz.cn/Article/details/gtvdvpztyd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxuanxn.top/Article/details/gtlllcwptm.html

JS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotttekxg.html

TS:   crypto.randomUUID()
来源：http://dali.yj20258.top/Article/details/gtvrelewwp.html

Java: UUID.randomUUID().toString()
来源：http://dali.cdnleiting.top/Article/details/gtudtnprhc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nanxuanxn.top/Article/details/gtmmeuzqri.html

Ruby: SecureRandom.uuid
来源：http://dali.daria6918.cn/Article/details/gtcniohata.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.daxiang520.top/Article/details/gtfvqzlsiq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.snrcjt.cn/Article/details/gtdkxflowp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.pycfn.com/Article/details/gtvdyxdowl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gtpposdpqb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ppjwa.cn/Article/details/gtmuoojciu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigufen.top/Article/details/gtxouxadcj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cashguo.top/Article/details/gtvidiqfpk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cashguo.top/Article/details/gtrnholtqg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xinyue.icu/Article/details/gtebgqtpcn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dianchejie.cn/Article/details/gtxrvrghhe.html

[P03] 生成短随机字符串
来源：http://dali.xylfe.cn/Article/details/gtmmulucbp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj202588.top/Article/details/gtnwpamdxg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmunbgzdm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gtjmzxtfgw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gtjlioaanr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gtdybcyfdz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.redwolf501.top/Article/details/gtwnranjgi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jianghu66.top/Article/details/gthhsxekhb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hammf.cn/Article/details/gttwwcjcor.html

[P04] 求长度
来源：http://dali.iojbl.cn/Article/details/gtyssttpup.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinghuilouyu.cn/Article/details/gtwawiiegt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtczqdkwor.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gtoyloiydv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gtkzsvivnx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.smart0.xyz/Article/details/gttmtyqegr.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigufen.top/Article/details/gtqavenzrj.html

Ruby: x.length;  x.size
来源：http://dali.chenlongwang.top/Article/details/gtllxenxco.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yueranfly.top/Article/details/gtkildeium.html

[P05] 判断两个对象内容是否相等
来源：http://dali.birdmap.top/Article/details/gtgokhijbo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258.top/Article/details/gthvjvuaiw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigufen.top/Article/details/gtlwprfyni.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258888.top/Article/details/gtnqemdipu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xylfe.cn/Article/details/gtyaghpmam.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cdnleiting.top/Article/details/gtyenyqmsk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdtsihnw.html

Ruby: a == b
来源：http://dali.ybcxt.top/Article/details/gtvqjwhzmd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gzhubu.top/Article/details/gtlpmjlrgb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.guannengcc.top/Article/details/gtlzrctwoy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yangfankeji.com/Article/details/gtrrllzpgn.html

PHP:  if (empty($x)) {}
来源：http://dali.quarkkingdee.top/Article/details/gtosqbxgfw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.feifeiyinyue.top/Article/details/gtbrcxdvlp.html

TS:   if (x == null) {}
来源：http://dali.gaohongyu789.top/Article/details/gtekvtvdbe.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtjcgfeokg.html

Go:   if x == nil {}
来源：http://dali.yueranfly.top/Article/details/gtsnaosmwp.html


<!-- 参考信息 -->