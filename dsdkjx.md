代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gt2ogcdazda.html

JS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gt2tssasejp.html

TS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gt2htbxjkno.html

Java: System.getenv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gt2xjkrahbv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cheryme.top/Article/details/gt2sujwqfyf.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wxggtqdv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2mpribwiz.html

[M03] 执行外部命令
来源：http://dali.hnqzz.top/Article/details/gt2vamsihhv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.svipenyu.cn/Article/details/gt2opgwhxyy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenjidiqi.icu/Article/details/gt2qyjrxuuq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bklaugtm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gt2kuockwhd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shuidangran.top/Article/details/gt2lcqfxcqt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.9152youxi.cn/Article/details/gt2ckxeaxvk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj202588.top/Article/details/gt2wdaehnzx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.svipenyu.cn/Article/details/gt2ypslwngu.html

[M04] 获取当前工作目录
来源：http://dali.sysykeji.top/Article/details/gt2umbccwym.html

Py:   os.getcwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2difldbcm.html

PHP:  getcwd();
来源：http://dali.hongshengwenyu.top/Article/details/gt2blroodni.html

JS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gt2acqiohqj.html

TS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gt2gzkcqkpl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wzmrfljq.html

Go:   os.Getwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2empxwbbx.html

Ruby: Dir.pwd
来源：http://dali.daxiang520.top/Article/details/gt2ebnhncwz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dcpupadd.html

[M05] 设置退出码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rhbrbiii.html

Py:   sys.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2cyanrvlh.html

PHP:  exit(1);
来源：http://dali.fengsongda.top/Article/details/gt2meceiiyw.html

JS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2chewdwht.html

TS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2sqjtohgm.html

Java: System.exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2knybpfhq.html

Go:   os.Exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2etrdpkba.html

Ruby: exit 1
来源：http://dali.hnxiangtu.top/Article/details/gt2tpkbjyer.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tanke756.top/Article/details/gt2jbvfulwt.html

[M06] 向标准错误输出
来源：http://dali.guannengcc.top/Article/details/gt2fktwvifd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gt2noesrxul.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.redwolf501.top/Article/details/gt2jhgncgts.html

JS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gt2ssbqskdh.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gt2yrsdagfe.html

Java: System.err.println("err")
来源：http://dali.cashguo.top/Article/details/gt2hheviega.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhengqikj.top/Article/details/gt2nnwzlhxd.html

Ruby: warn "err"
来源：http://dali.zhiwuduotai.top/Article/details/gt2owencyzk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.smart0.xyz/Article/details/gt2kzoudclk.html

[M07] 判断是否为主入口
来源：http://dali.jyoumei.cn/Article/details/gt2xerdaqpn.html

Py:   if __name__ == "__main__":
来源：http://dali.guannengcc.top/Article/details/gt2xfzbkcgk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gotoacloud.top/Article/details/gt2ctkppotu.html

JS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2czwuogfs.html

TS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gt2dvcoimip.html

Java: public static void main(String[] args)
来源：http://dali.hywenlv.cn/Article/details/gt2bodaickr.html

Go:   func main()
来源：http://dali.dianchejie.cn/Article/details/gt2mweapjxm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.haohaochexian.top/Article/details/gt2itfvvrsc.html

C#:   static void Main(string[] args)
来源：http://dali.nanxinkj.top/Article/details/gt2aqqfudve.html

[M08] 获取系统与运行时信息
来源：http://dali.pycfn.com/Article/details/gt2hpbiswji.html

Py:   platform.system();  platform.python_version()
来源：http://dali.vqdsnc.cn/Article/details/gt2gkrociti.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgufenzy.top/Article/details/gt2bzujyals.html

JS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gt2daajaaen.html

TS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gt2ncxbaerj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.0kj1m.cn/Article/details/gt2vaakcrca.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ybcxt.top/Article/details/gt2oqnirgzj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nwbrower.top/Article/details/gt2eaqagzao.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.9152youxi.cn/Article/details/gt2xgqirspn.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2hdqrmadj.html

N. 数据结构与算法
来源：http://dali.hnxiangtu.top/Article/details/gt2oqenaivr.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2scafqeoy.html

[N01] 二分查找（有序数组）
来源：http://dali.fzhhl.top/Article/details/gt2dnuwecsg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhasrmhl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sweek.top/Article/details/gt2suvyiynf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gt2aypeaewv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gt2rtzizvks.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zzteguhs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2syzixhed.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258.top/Article/details/gt2stslxwqb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2yefvhsxh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.feifeiyinyue.top/Article/details/gt2ugfurkxw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuanzhike.top/Article/details/gt2jocpbpmu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cdnleiting.top/Article/details/gt2sybylzbp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gt2iehsnlwn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gt2citrzsud.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sxryk.cn/Article/details/gt2wmrleynw.html

Go:   slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2nzvdnzwb.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gt2kzskfvaa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mpmcpcvb.html

[N03] 快速排序（分治示例）
来源：http://dali.9152youxi.cn/Article/details/gt2glolcewo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daria6918.cn/Article/details/gt2koeagyjv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jqnxegak.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gt2pqczksxj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gt2xvzlonfm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.smart0.xyz/Article/details/gt2tsfllrrp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ivvv.top/Article/details/gt2zxmeeood.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jiagoushi.top/Article/details/gt2bjrnmsmk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lplsowaa.html

[N04] 斐波那契数列
来源：http://dali.bjfxy.top/Article/details/gt2iugytrdb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gt2zzsdlgxm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2otrexvuo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gt2zlitxvmk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gt2cztpxxed.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gt2vmyxmzmy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gotoacloud.top/Article/details/gt2ycxkvcye.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gt2whcsqgmj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gt2afgnrsem.html

[N05] 最大公约数
来源：http://dali.sweek.top/Article/details/gt2yxuffjhx.html

Py:   math.gcd(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yfrprucr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zdqjudy.top/Article/details/gt2diwgelcr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gt2yshgtvam.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gt2xvdansbx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dashuyun.cn/Article/details/gt2gsmvjdxs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ehwqpu.com/Article/details/gt2crnxqsrk.html

Ruby: a.gcd(b)
来源：http://dali.kuanghao11.cn/Article/details/gt2gncqqkfx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sanhvuqj.html

[N06] 判断回文字符串
来源：http://dali.mhx1999.top/Article/details/gt2fzwcminj.html

Py:   s == s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2kfvtayqr.html

PHP:  $s === strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2zkoaqyqo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2tqoiscom.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gt2rjssgypr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangdashe.top/Article/details/gt2smqxkanr.html

Go:   // 双指针从两端比较
来源：http://dali.redwolf501.top/Article/details/gt2atwvxykg.html

Ruby: s == s.reverse
来源：http://dali.zhengqikj.top/Article/details/gt2kxzjkarv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gt2pfqiatvu.html

[N07] 两数之和（返回下标）
来源：http://dali.pengpengdd.cyou/Article/details/gt2eatkciwz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sxryk.cn/Article/details/gt2fatovcwb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.smart0.xyz/Article/details/gt2lqwktabd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.bjfxy.top/Article/details/gt2wwrcedhe.html

TS:   // 手写 Map<string, number>
来源：http://dali.xinyue.icu/Article/details/gt2hexopbka.html

Java: // 手写 HashMap
来源：http://dali.sysykeji.top/Article/details/gt2jpiwcltv.html

Go:   // 手写 map[int]int
来源：http://dali.sweek.top/Article/details/gt2cesmmyjd.html

Ruby: // 手写 Hash
来源：http://dali.jinqigufen.top/Article/details/gt2auudlipi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnxiangtu.top/Article/details/gt2yinikdlv.html

[N08] 生成全排列
来源：http://dali.yuxming.cn/Article/details/gt2xdwurkdi.html

Py:   itertools.permutations(arr)
来源：http://dali.xziqi.cn/Article/details/gt2zfdoeuor.html

PHP:  // 手写递归交换
来源：http://dali.feifeiyinyue.top/Article/details/gt2jwdapzpk.html

JS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2cemeacha.html

TS:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gt2vttyphpk.html

Java: // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gt2idehrzdu.html

Go:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gt2sgokeiyn.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258.top/Article/details/gt2abwjehkh.html

C#:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2nnrygiqk.html

[N09] 栈与队列
来源：http://dali.bjfxy.top/Article/details/gt2rdgviydk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cdnleiting.top/Article/details/gt2kkxvdohe.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cashguo.top/Article/details/gt2rbrptrro.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gt2baukqien.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aizwys.cn/Article/details/gt2ievttxkt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tianlin.xyz/Article/details/gt2mwubqdci.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258.top/Article/details/gt2viunqycx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gt2nefuvnnj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gt2smqeujoa.html

[N10] 链表节点定义
来源：http://dali.chenlongwang.top/Article/details/gt2xwiyssat.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pengpengdd.cyou/Article/details/gt2xrqydhyi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sxryk.cn/Article/details/gt2wgtncrzj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.9152youxi.cn/Article/details/gt2ulmpmqbv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.havefunace.top/Article/details/gt2dxqizuff.html

Java: class Node { int v; Node next; }
来源：http://dali.gzhubu.top/Article/details/gt2xbkgigpp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vjqmgpvz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mitbfvzy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.mhx1999.top/Article/details/gt2hdxceggf.html

[N11] 二叉树中序遍历
来源：http://dali.yuxming.cn/Article/details/gt2uhzjtsiy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhiwuduotai.top/Article/details/gt2afuckxda.html

PHP:  // 手写递归函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2bwejpcgo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gt2rtrcibam.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sufxvd.cn/Article/details/gt2qwqfezpc.html

Java: // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gt2kduqltkb.html

Go:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gt2xoxaiklt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fzhhl.top/Article/details/gt2onyldccr.html

C#:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gt2rgtjguht.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangshuangyany.cn/Article/details/gt2byecshiq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vosvcfok.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xziqi.cn/Article/details/gt2aqwqkazi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gt2elgtrayg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gt2iniwekih.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gt2crwjqyna.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.meibo888.top/Article/details/gt2fnohdcsi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cucudq.cn/Article/details/gt2vbxcbnnr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gt2solbzjij.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hrayivnh.html

O. 并发与异步
来源：http://dali.yuxming.cn/Article/details/gt2gwkpriuz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2gboyqfoa.html

[O01] 启动一个线程
来源：http://dali.andypj.xyz/Article/details/gt2ydvahnng.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.smart0.xyz/Article/details/gt2pwkdnpqn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.daxiang520.top/Article/details/gt2lwqjfxzp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj202588.top/Article/details/gt2uuxiytnk.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gt2diytqbvs.html

Java: new Thread(() -> f()).start()
来源：http://dali.yangfankeji.com/Article/details/gt2nbchittv.html

Go:   go f()
来源：http://dali.nwbrower.top/Article/details/gt2dgxnqnot.html

Ruby: Thread.new { f }
来源：http://dali.fengsongda.top/Article/details/gt2oprbzyml.html

C#:   Task.Run(() => F());
来源：http://dali.zhiwuduotai.top/Article/details/gt2zbcfthcp.html

[O02] 使用线程池
来源：http://dali.ppjwa.cn/Article/details/gt2vhhwgdfj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxuanxn.top/Article/details/gt2mpoawxfr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hammf.cn/Article/details/gt2xzufxpcr.html

JS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gt2whawyjrs.html

TS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gt2gzymxmkm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hnxiangtu.top/Article/details/gt2amszlapb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.birdmap.top/Article/details/gt2iojifvie.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jianghu66.top/Article/details/gt2brdbxsrb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ydzc1.top/Article/details/gt2fzscskyz.html

[O03] 加锁保护共享数据
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lyjawcdd.html

Py:   with lock: shared += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bdbgvufa.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.dianchejie.cn/Article/details/gt2bxiziblt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigufen.top/Article/details/gt2fyosrrnd.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gt2lnkvanvz.html

Java: synchronized (this) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gt2oftizajw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.quarkkingdee.top/Article/details/gt2mdyiedwp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cbeokzga.html

C#:   lock (gate) { shared++; }
来源：http://dali.tanke756.top/Article/details/gt2hehvfori.html

[O04] 定义异步函数并等待
来源：http://dali.jqgfzy.top/Article/details/gt2osnkuyzh.html

Py:   async def f():⏎    await g()
来源：http://dali.hfpthk.cn/Article/details/gt2hkjykskt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.316326.xyz/Article/details/gt2noypzcql.html

JS:   async function f() { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nusoiinb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.andypj.xyz/Article/details/gt2qhtfsjgj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ppjwa.cn/Article/details/gt2rphchrpw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cashguo.top/Article/details/gt2obgdiuzh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cashguo.top/Article/details/gt2cemnzccu.html

C#:   async Task F() { await G(); }
来源：http://dali.hammf.cn/Article/details/gt2ihqrpoju.html

[O05] 并发执行并等待全部完成
来源：http://dali.fengsongda.top/Article/details/gt2znkgbzbf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cheryme.top/Article/details/gt2fvvcxahs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zycfv.cn/Article/details/gt2vmfrjvta.html

JS:   await Promise.all(tasks)
来源：http://dali.zhongyouzk.top/Article/details/gt2wtnlgvks.html

TS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gt2bkmcxdtx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.mhx1999.top/Article/details/gt2irzgkzdq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hysaishi.cn/Article/details/gt2myjzydaw.html

Ruby: threads.map(&:join)
来源：http://dali.xziqi.cn/Article/details/gt2evppacqu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2luzubdxe.html

[O06] 使用进程池
来源：http://dali.xziqi.cn/Article/details/gt2jgjtfyud.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnqzz.top/Article/details/gt2dfumodon.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hammf.cn/Article/details/gt2frpxmixu.html

JS:   // child_process / cluster 模块
来源：http://dali.guannengcc.top/Article/details/gt2sdtrqjbf.html

TS:   // child_process / cluster 模块
来源：http://dali.ydzc1.top/Article/details/gt2uvhzlbwr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mryexnyk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hnqzz.top/Article/details/gt2nsjtyftv.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwwbcvz.html

C#:   Parallel.For
来源：http://dali.tianlin.xyz/Article/details/gt2lsoedrbj.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zevbtepe.html

P. 常用工具函数
来源：http://dali.yongpay.top/Article/details/gt2cajbaqzi.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2fpbaqfkt.html

[P01] 生成 UUID
来源：http://dali.sysykeji.top/Article/details/gt2goygxqjb.html

Py:   str(uuid.uuid4())
来源：http://dali.ppjwa.cn/Article/details/gt2kidomlpj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cheryme.top/Article/details/gt2iuanpmju.html

JS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gt2seobipcz.html

TS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gt2gcalolzy.html

Java: UUID.randomUUID().toString()
来源：http://dali.smart0.xyz/Article/details/gt2ewqhuvlv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cdnleiting.top/Article/details/gt2hedobzhy.html

Ruby: SecureRandom.uuid
来源：http://dali.chenzaomai.com/Article/details/gt2fukwsxez.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yongpay.top/Article/details/gt2jdcpsbzq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.guowangkeji.top/Article/details/gt2wuilnfwk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangdashe.top/Article/details/gt2dfzfhxif.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dianchejie.cn/Article/details/gt2nhrahvso.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dianchejie.cn/Article/details/gt2pvkpclbd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rtxkmsjk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxinkj.top/Article/details/gt2emjxwvkf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hsbwdwyq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgfzy.top/Article/details/gt2gynlzzfi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhengqikj.top/Article/details/gt2gmveoipg.html

[P03] 生成短随机字符串
来源：http://dali.snrcjt.cn/Article/details/gt2elgfhasz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xinyue.icu/Article/details/gt2zuwgnbrp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gt2xigwtsrs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gogol.net.cn/Article/details/gt2szpabbbu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gt2ctdbwlkx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jyoumei.cn/Article/details/gt2ltgnisba.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gzhubu.top/Article/details/gt2nvqzlhxj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ffbrcyoc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.0kj1m.cn/Article/details/gt2iohbxkty.html

[P04] 求长度
来源：http://dali.sufxvd.cn/Article/details/gt2oyqusdgx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shuidangran.top/Article/details/gt2vwfizvkv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gt2kskumsvy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gt2whkzpxua.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aibaodan.cn/Article/details/gt2ffdraqcp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhengqikj.top/Article/details/gt2bwlhqnbh.html

Go:   len(arr);  len(m)
来源：http://dali.daxiang520.top/Article/details/gt2bhufzefx.html

Ruby: x.length;  x.size
来源：http://dali.bjfxy.top/Article/details/gt2xdydelwz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gzhubu.top/Article/details/gt2vbejuhqd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxuanxn.top/Article/details/gt2clnkwfyv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yongpay.top/Article/details/gt2brolcxje.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tznqkqqm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yvedp.cn/Article/details/gt2iifilhgt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yanxiufei.cn/Article/details/gt2tyjiqfny.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258.top/Article/details/gt2fgcdnnbe.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.iojbl.cn/Article/details/gt2bhfdmndv.html

Ruby: a == b
来源：http://dali.nanxinkj.top/Article/details/gt2iudsrxei.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.mhx1999.top/Article/details/gt2nfpbpavx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuanzhike.top/Article/details/gt2tnpbgqds.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.guowangkeji.top/Article/details/gt2tcskfgzj.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qsnbsect.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.snrcjt.cn/Article/details/gt2epbcyhfx.html

TS:   if (x == null) {}
来源：http://dali.hammf.cn/Article/details/gt2lqecwpre.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gt2ppaxqplj.html

Go:   if x == nil {}
来源：http://dali.yueranfly.top/Article/details/gt2udqbuxto.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.guowangkeji.top/Article/details/gt2igspfvko.html

C#:   if (x is null) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2zfpeajdl.html

[P07] 防抖与节流
来源：http://dali.quarkkingdee.top/Article/details/gt2gonwyclq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zdqjudy.top/Article/details/gt2ggnllchz.html

PHP:  // 手写时间戳比较
来源：http://dali.jyoumei.cn/Article/details/gt2bxvljxgn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ymdhckkl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gt2whcryznf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxinkj.top/Article/details/gt2gctvjckd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258888.top/Article/details/gt2hdtdhjls.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2blxkxpfh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yangfankeji.com/Article/details/gt2ilyfphhe.html

[P08] 处理浮点精度问题
来源：http://dali.guannengcc.top/Article/details/gt2eoaqmyym.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhiwuduotai.top/Article/details/gt2volzpkxf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nwbrower.top/Article/details/gt2cfixwbcb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gogol.net.cn/Article/details/gt2prskunop.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jlsjyb.cn/Article/details/gt2ivsujfen.html


<!-- 参考信息 -->