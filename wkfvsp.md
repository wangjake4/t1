代发 wailian999

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gt2bdmhalli.html

Ruby: ENV["HOME"]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vyfzrvol.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cheryme.top/Article/details/gt2cpocirhd.html

[M03] 执行外部命令
来源：http://dali.jinqigfzy.top/Article/details/gt2ezpcqrnj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mnyzajwr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.0kj1m.cn/Article/details/gt2mgrkdugr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gt2egjxxvlr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2zgmaibti.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lzcvknkz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ltyqcfpa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhengqikj.top/Article/details/gt2omwwcraj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tian-w.cn/Article/details/gt2lxozekzu.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gt2maktrcjw.html

Py:   os.getcwd()
来源：http://dali.yongpay.top/Article/details/gt2fnxvmvkj.html

PHP:  getcwd();
来源：http://dali.havefunace.top/Article/details/gt2csuxfgot.html

JS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gt2rxlyueur.html

TS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gt2wputrypl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhoulong.xyz/Article/details/gt2tpjjlzbw.html

Go:   os.Getwd()
来源：http://dali.hfpthk.cn/Article/details/gt2srsdbskl.html

Ruby: Dir.pwd
来源：http://dali.mhx1999.top/Article/details/gt2yztjzfbm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.snrcjt.cn/Article/details/gt2zfehmuay.html

[M05] 设置退出码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tmhtcujr.html

Py:   sys.exit(1)
来源：http://dali.iojbl.cn/Article/details/gt2tyzzrwuy.html

PHP:  exit(1);
来源：http://dali.wangdashe.top/Article/details/gt2oydwtten.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kxijfube.html

TS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2hmumopxd.html

Java: System.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2qgxrdfik.html

Go:   os.Exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2eybocioa.html

Ruby: exit 1
来源：http://dali.yongpay.top/Article/details/gt2rzpdjkqv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shangyingyoupin.top/Article/details/gt2easgsiuc.html

[M06] 向标准错误输出
来源：http://dali.kuanghao11.cn/Article/details/gt2mifmhouq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2adibamnf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ppjwa.cn/Article/details/gt2ivweplct.html

JS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gt2pdbzxirj.html

TS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ngfqaxpe.html

Java: System.err.println("err")
来源：http://dali.nanxuanxn.top/Article/details/gt2yiaqegra.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2smrzcvci.html

Ruby: warn "err"
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvowpopu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.bjfxy.top/Article/details/gt2smprjtum.html

[M07] 判断是否为主入口
来源：http://dali.yj20258888.top/Article/details/gt2lhirnskm.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxuanxn.top/Article/details/gt2gkwixhkn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jauyigcb.html

JS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gt2zrblvtvf.html

TS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gt2buuptfcu.html

Java: public static void main(String[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xdqyvrgq.html

Go:   func main()
来源：http://dali.yj20258.top/Article/details/gt2mtdxermt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fengsongda.top/Article/details/gt2kztxbjgp.html

C#:   static void Main(string[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xyvptlkb.html

[M08] 获取系统与运行时信息
来源：http://dali.zhixingplan.top/Article/details/gt2gtvwyevx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pengpengdd.cyou/Article/details/gt2pltekzjt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ydzc1.top/Article/details/gt2llvtbbep.html

JS:   process.platform;  process.version
来源：http://dali.sufxvd.cn/Article/details/gt2zhbbddtx.html

TS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gt2dbsxnoui.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gotoacloud.top/Article/details/gt2bjkrszlw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cucudq.cn/Article/details/gt2lpeecthr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhiwuduotai.top/Article/details/gt2dqojshpw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.havefunace.top/Article/details/gt2ikanlfyt.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2bropylkt.html

N. 数据结构与算法
来源：http://dali.feifeiyinyue.top/Article/details/gt2evbmxgoi.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2lffwgbsy.html

[N01] 二分查找（有序数组）
来源：http://dali.yonumen.top/Article/details/gt2unxcbqfs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2ltkhnjlv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guowangkeji.top/Article/details/gt2hvwopfzv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgukcgur.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gt2uyluulgc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gt2qbxhwzsz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sweek.top/Article/details/gt2dnkviomz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yonumen.top/Article/details/gt2vuzjlxcj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nbammyjk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ivvv.top/Article/details/gt2vjbumtpe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yixacljj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yanxiufei.cn/Article/details/gt2izweqdaf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qagcztjp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gt2svmvaikf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenlongwang.top/Article/details/gt2owqzismm.html

Go:   slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gt2kkkxjakd.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gt2qmmlotjy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ehwqpu.com/Article/details/gt2svesgxpr.html

[N03] 快速排序（分治示例）
来源：http://dali.hammf.cn/Article/details/gt2gcriqghm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ydraghwz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cqqwz.cn/Article/details/gt2mzujfmmq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gt2dyczxsgl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gt2ewcegqtb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.quarkkingdee.top/Article/details/gt2uuunmctj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258888.top/Article/details/gt2mikkblpg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258888.top/Article/details/gt2kdslfrrn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lrpwzqfw.html

[N04] 斐波那契数列
来源：http://dali.bjfxy.top/Article/details/gt2sfjndjhg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zkhjauti.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.havefunace.top/Article/details/gt2quouqhmj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gt2hnopctzl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gt2emqfycqj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gt2gqyxxcpo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhongyouzk.top/Article/details/gt2jiglfaty.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gt2vjllxylx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gt2aeyaukka.html

[N05] 最大公约数
来源：http://dali.chenjidiqi.icu/Article/details/gt2gbpaqjpd.html

Py:   math.gcd(a, b)
来源：http://dali.sysykeji.top/Article/details/gt2ialyeeed.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhongyouzk.top/Article/details/gt2lihuxlcr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gt2zddiujtq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gt2epihkgyz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fengsongda.top/Article/details/gt2xfetxygd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gqmicuai.html

Ruby: a.gcd(b)
来源：http://dali.iojbl.cn/Article/details/gt2qcrnubck.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fengsongda.top/Article/details/gt2jqaysoxc.html

[N06] 判断回文字符串
来源：http://dali.yj20258888.top/Article/details/gt2vjzlpoqf.html

Py:   s == s[::-1]
来源：http://dali.sxryk.cn/Article/details/gt2liockjhn.html

PHP:  $s === strrev($s);
来源：http://dali.jianghu66.top/Article/details/gt2rsvuamxq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dskkzazz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2zoyitoth.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.quarkkingdee.top/Article/details/gt2hjlsvvry.html

Go:   // 双指针从两端比较
来源：http://dali.hywenlv.cn/Article/details/gt2hkplebee.html

Ruby: s == s.reverse
来源：http://dali.shuidangran.top/Article/details/gt2cgjyerto.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gt2xpanowvd.html

[N07] 两数之和（返回下标）
来源：http://dali.dashuyun.cn/Article/details/gt2yjkhixut.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.vqdsnc.cn/Article/details/gt2nzyzvisi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.9152youxi.cn/Article/details/gt2nvafezxu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xylfe.cn/Article/details/gt2bjctzpyy.html

TS:   // 手写 Map<string, number>
来源：http://dali.hysaishi.cn/Article/details/gt2xylrgzog.html

Java: // 手写 HashMap
来源：http://dali.ivvv.top/Article/details/gt2qwsfkhwt.html

Go:   // 手写 map[int]int
来源：http://dali.vqdsnc.cn/Article/details/gt2uwfgdsix.html

Ruby: // 手写 Hash
来源：http://dali.birdmap.top/Article/details/gt2puxivlwi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jyoumei.cn/Article/details/gt2bkronzlu.html

[N08] 生成全排列
来源：http://dali.yanxiufei.cn/Article/details/gt2hkxbhnhf.html

Py:   itertools.permutations(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2nuconfbe.html

PHP:  // 手写递归交换
来源：http://dali.zhoulong.xyz/Article/details/gt2pnqsrjsc.html

JS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2sjyktcbl.html

TS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gt2qvkbilbf.html

Java: // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gt2yphugerk.html

Go:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gt2altyehvs.html

Ruby: arr.permutation.to_a
来源：http://dali.mhx1999.top/Article/details/gt2kscgkmft.html

C#:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2hnuvadiz.html

[N09] 栈与队列
来源：http://dali.xziqi.cn/Article/details/gt2wbzfqrnf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.havefunace.top/Article/details/gt2sxcmqjbk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gt2ilpwojvy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gt2irlookuc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uwwjhfjy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gt2radsmlsk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fengsongda.top/Article/details/gt2syovalci.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gt2orqbvkfd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2krbgbqfe.html

[N10] 链表节点定义
来源：http://dali.jyoumei.cn/Article/details/gt2vdrxddsi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cdnleiting.top/Article/details/gt2qawffohf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cashguo.top/Article/details/gt2hafbnnja.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sdvdcztk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eunpamdq.html

Java: class Node { int v; Node next; }
来源：http://dali.cqqwz.cn/Article/details/gt2gampinjh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.316326.xyz/Article/details/gt2necqwgac.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.vqdsnc.cn/Article/details/gt2udcptmox.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gotoacloud.top/Article/details/gt2tlbpgwvz.html

[N11] 二叉树中序遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2drbwwhop.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.vqdsnc.cn/Article/details/gt2vdisgxju.html

PHP:  // 手写递归函数
来源：http://dali.gzhubu.top/Article/details/gt2quiyekug.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gt2zfvedslf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sysykeji.top/Article/details/gt2soaqjylw.html

Java: // 手写递归
来源：http://dali.yvedp.cn/Article/details/gt2rdsgzaeb.html

Go:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gt2pezczpwn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eifbejbl.html

C#:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gt2hzubnemv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yuanzhike.top/Article/details/gt2eljhgmmx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenlongwang.top/Article/details/gt2ltmknbjw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gt2yyvbbxgu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tanke756.top/Article/details/gt2guimbkkx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gt2fbqxdvlo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gt2oxezgnac.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxuanxn.top/Article/details/gt2ofshkydk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhixingplan.top/Article/details/gt2ohwvxmfq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ieaqqidc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2igftirwf.html

O. 并发与异步
来源：http://dali.sysykeji.top/Article/details/gt2amhcsjhu.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2gbjgjytf.html

[O01] 启动一个线程
来源：http://dali.zycfv.cn/Article/details/gt2bjfhtmvf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.c1oappe.top/Article/details/gt2iulcppbo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinqigfzy.top/Article/details/gt2uptfndit.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2woxdafuf.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gt2fhszylvs.html

Java: new Thread(() -> f()).start()
来源：http://dali.0kj1m.cn/Article/details/gt2zmodujqj.html

Go:   go f()
来源：http://dali.ydzc1.top/Article/details/gt2fspgrfnz.html

Ruby: Thread.new { f }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wsapjcxw.html

C#:   Task.Run(() => F());
来源：http://dali.9152youxi.cn/Article/details/gt2ktwrnror.html

[O02] 使用线程池
来源：http://dali.meibo888.top/Article/details/gt2knfykupq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cdnleiting.top/Article/details/gt2ssfmcztb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgfzy.top/Article/details/gt2tyervefd.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gt2eyldvwhf.html

TS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gt2tpbnysps.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fivhirdo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ohkwvxlp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.snrcjt.cn/Article/details/gt2iumpfyxh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.feifeiyinyue.top/Article/details/gt2vkadcgab.html

[O03] 加锁保护共享数据
来源：http://dali.yangfankeji.com/Article/details/gt2hslvlbtt.html

Py:   with lock: shared += 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2duccvwdr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jianghu66.top/Article/details/gt2edibordz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnxiangtu.top/Article/details/gt2szcywaqg.html

TS:   // 同 JS
来源：http://dali.sysykeji.top/Article/details/gt2ruuvoego.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhengqikj.top/Article/details/gt2yntasklu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuanzhike.top/Article/details/gt2txmmcvzd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgufenzy.top/Article/details/gt2wpuxpken.html

C#:   lock (gate) { shared++; }
来源：http://dali.cucudq.cn/Article/details/gt2gdmnxfxj.html

[O04] 定义异步函数并等待
来源：http://dali.yueranfly.top/Article/details/gt2pklbnlrw.html

Py:   async def f():⏎    await g()
来源：http://dali.hammf.cn/Article/details/gt2gnanblbm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgfzy.top/Article/details/gt2qjhuiqrb.html

JS:   async function f() { await g(); }
来源：http://dali.zdqjudy.top/Article/details/gt2wbkcnigs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xziqi.cn/Article/details/gt2ydtbsugu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.redwolf501.top/Article/details/gt2pszwbiyl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hueiqtxo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.birdmap.top/Article/details/gt2hgbdnuph.html

C#:   async Task F() { await G(); }
来源：http://dali.haohaochexian.top/Article/details/gt2iaamtujb.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxinkj.top/Article/details/gt2pjdzxqfl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ddrmbdec.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fzhhl.top/Article/details/gt2ilnzjjie.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gt2eyoxemog.html

TS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gt2akldpubz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpssgyvt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258888.top/Article/details/gt2kkssawch.html

Ruby: threads.map(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gt2aqcwaytt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2oalbrlcy.html

[O06] 使用进程池
来源：http://dali.316326.xyz/Article/details/gt2ipepuhms.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.kuanghao11.cn/Article/details/gt2bczunqoy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cheryme.top/Article/details/gt2tmubycaf.html

JS:   // child_process / cluster 模块
来源：http://dali.chenzaomai.com/Article/details/gt2jwpffwzq.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258888.top/Article/details/gt2bhlxvzmv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.dashuyun.cn/Article/details/gt2xicnvypr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.birdmap.top/Article/details/gt2juhftzxr.html

Ruby: // fork 块
来源：http://dali.tanke756.top/Article/details/gt2vfuwzrxn.html

C#:   Parallel.For
来源：http://dali.nanxuanxn.top/Article/details/gt2tcuynudd.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rathdhfy.html

P. 常用工具函数
来源：http://dali.snrcjt.cn/Article/details/gt2wxxnpypw.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2spwutyki.html

[P01] 生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gt2lxmtmfzi.html

Py:   str(uuid.uuid4())
来源：http://dali.shuidangran.top/Article/details/gt2vmstppkc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yanxiufei.cn/Article/details/gt2ojmrdhmk.html

JS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gt2lbvugiwh.html

TS:   crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gt2natrigec.html

Java: UUID.randomUUID().toString()
来源：http://dali.snrcjt.cn/Article/details/gt2zddiqrve.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fzhhl.top/Article/details/gt2kbtnzmqe.html

Ruby: SecureRandom.uuid
来源：http://dali.shzxlz.cn/Article/details/gt2supbcnor.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tian-w.cn/Article/details/gt2csljlbgc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.guannengcc.top/Article/details/gt2lidvytqw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.svipenyu.cn/Article/details/gt2zzfpirzp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.iojbl.cn/Article/details/gt2izkjkpbv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sweek.top/Article/details/gt2lhsngvjf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cucudq.cn/Article/details/gt2rzwdlnkg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yongpay.top/Article/details/gt2owpuqtjw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.havefunace.top/Article/details/gt2dcdvyopu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.guowangkeji.top/Article/details/gt2ggqfxdqh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxuanxn.top/Article/details/gt2zbdbnxxw.html

[P03] 生成短随机字符串
来源：http://dali.zdqjudy.top/Article/details/gt2lfpakjho.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuanzhike.top/Article/details/gt2bxpibqpm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gotoacloud.top/Article/details/gt2zbqnycoj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gt2iceksufs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jianghu66.top/Article/details/gt2dnmnzfcn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2gxzpwiwb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.wangshuangyany.cn/Article/details/gt2uxiiaxaa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ppjwa.cn/Article/details/gt2hrmvdxqa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yonumen.top/Article/details/gt2eydvimge.html

[P04] 求长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2ihrhlalz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xylfe.cn/Article/details/gt2yxgkwlah.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2beujcppj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gt2jogixumy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2elioxrrw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sysykeji.top/Article/details/gt2zvcsotwp.html

Go:   len(arr);  len(m)
来源：http://dali.dashuyun.cn/Article/details/gt2rurmudjr.html

Ruby: x.length;  x.size
来源：http://dali.hammf.cn/Article/details/gt2vnvvqjkf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gt2aytefhle.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jqgfzy.top/Article/details/gt2abyjnpls.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tian-w.cn/Article/details/gt2awuyajis.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xinyue.icu/Article/details/gt2rrcqceta.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhongyouzk.top/Article/details/gt2gzrrkhhv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shuidangran.top/Article/details/gt2avaplvcz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2owxnitzo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gt2ljfmgmhk.html

Ruby: a == b
来源：http://dali.fengsongda.top/Article/details/gt2sgpsxrdw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.pycfn.com/Article/details/gt2vjvgnzdd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yonumen.top/Article/details/gt2bmoihuiu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.quarkkingdee.top/Article/details/gt2xcpxczxe.html

PHP:  if (empty($x)) {}
来源：http://dali.iojbl.cn/Article/details/gt2iullhpds.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guowangkeji.top/Article/details/gt2worhzgwp.html

TS:   if (x == null) {}
来源：http://dali.xziqi.cn/Article/details/gt2ojbwzkna.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jyoumei.cn/Article/details/gt2mmqljsxw.html

Go:   if x == nil {}
来源：http://dali.hfpthk.cn/Article/details/gt2mexeiqfa.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gaohongyu789.top/Article/details/gt2iuuxtaau.html

C#:   if (x is null) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2cqftwrlj.html

[P07] 防抖与节流
来源：http://dali.cqqwz.cn/Article/details/gt2ppbtqvnf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cheryme.top/Article/details/gt2fgofoozx.html

PHP:  // 手写时间戳比较
来源：http://dali.cdnleiting.top/Article/details/gt2qtxietpd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gt2wpmzglry.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuxming.cn/Article/details/gt2sqirxloe.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aibaodan.cn/Article/details/gt2ynreehfb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhengqikj.top/Article/details/gt2gfbjbwsm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ppjwa.cn/Article/details/gt2bhpsabcc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhongyouzk.top/Article/details/gt2mcutvohw.html

[P08] 处理浮点精度问题
来源：http://dali.zhixingplan.top/Article/details/gt2vzqgxlgl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zsllahxw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yueranfly.top/Article/details/gt2odigrbch.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tian-w.cn/Article/details/gt2hppixiwc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ivvv.top/Article/details/gt2iakbzrsk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2urgjyzyw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhixingplan.top/Article/details/gt2qocojgfo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gotoacloud.top/Article/details/gt2hssnwcal.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yangfankeji.com/Article/details/gt2crxvtped.html


<!-- 参考信息 -->