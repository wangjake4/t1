代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gtaagsyxfu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.vqdsnc.cn/Article/details/gtzeppvsjd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cqqwz.cn/Article/details/gtwhpwnsel.html

JS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtavvbsvou.html

TS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gtoxxcswet.html

Java: resp.statusCode()
来源：http://dali.yj202588.top/Article/details/gtzhrrdvww.html

Go:   resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gtiqbxxmfx.html

Ruby: resp.code.to_i
来源：http://dali.0kj1m.cn/Article/details/gtqrrnjoax.html

C#:   (int)resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gteeyuxidi.html

[L08] 并发请求多个地址
来源：http://dali.wangdashe.top/Article/details/gtghrvhjmw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258.top/Article/details/gtgwajflfl.html

PHP:  curl_multi_init() 系列
来源：http://dali.pengpengdd.cyou/Article/details/gthijnnnab.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtahneljwo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtirxzriks.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhiwuduotai.top/Article/details/gtsadcdctt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuanzhike.top/Article/details/gtmumresca.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gtkjmkaqih.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtggrvltgl.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtcvtbvxxb.html

M. 命令行 / 进程 / 环境
来源：http://dali.0kj1m.cn/Article/details/gtikmxuacd.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtvdqtuzos.html

[M01] 读取命令行参数
来源：http://dali.ivvv.top/Article/details/gtoivqdjca.html

Py:   sys.argv[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtculjmrhi.html

PHP:  $argv;  $argc;
来源：http://dali.yuanzhike.top/Article/details/gthlidxbsx.html

JS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gtutwecgsn.html

TS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gtdkdmkadm.html

Java: args 数组（main 方法参数）
来源：http://dali.ivvv.top/Article/details/gtboawojzj.html

Go:   os.Args[1:]
来源：http://dali.meibo888.top/Article/details/gtmzfixnyg.html

Ruby: ARGV
来源：http://dali.jinqigufen.top/Article/details/gtxyjygrtn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gtastudvuj.html

[M02] 读取环境变量
来源：http://dali.guannengcc.top/Article/details/gtlhyxkgyq.html

Py:   os.environ.get("HOME")
来源：http://dali.cucudq.cn/Article/details/gtpenqjnds.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gtwyukfimt.html

JS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtckjpgyew.html

TS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gtqotengbk.html

Java: System.getenv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtmcuygnkj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtqrjzfhow.html

Ruby: ENV["HOME"]
来源：http://dali.shangyingyoupin.top/Article/details/gtgukhriqb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gthfztoyhb.html

[M03] 执行外部命令
来源：http://dali.zycfv.cn/Article/details/gtidgpjopi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sysykeji.top/Article/details/gteqmauubg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ppjwa.cn/Article/details/gthndkaidl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gtvvwornei.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gtpvixubts.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcbxctml.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cheryme.top/Article/details/gtxyoxyvqa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ydzc1.top/Article/details/gtihpezgxj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hfpthk.cn/Article/details/gtoxptccjd.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gtdccggfhw.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gtaibntexy.html

PHP:  getcwd();
来源：http://dali.yuxming.cn/Article/details/gtxyhwgffs.html

JS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gtuwxjquxi.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtzjgrvpkl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.smart0.xyz/Article/details/gthshigkgi.html

Go:   os.Getwd()
来源：http://dali.fzhhl.top/Article/details/gtagrdfmat.html

Ruby: Dir.pwd
来源：http://dali.daxiang520.top/Article/details/gtaesaaawr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcyhkywt.html

[M05] 设置退出码
来源：http://dali.jyoumei.cn/Article/details/gtwgovitvg.html

Py:   sys.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtszigxkot.html

PHP:  exit(1);
来源：http://dali.yanxiufei.cn/Article/details/gtotxyqizn.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtxagnodes.html

TS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gtkrkxljpg.html

Java: System.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gteertgmko.html

Go:   os.Exit(1)
来源：http://dali.tian-w.cn/Article/details/gtdcvnplbl.html

Ruby: exit 1
来源：http://dali.pycfn.com/Article/details/gtgsvidzji.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.snrcjt.cn/Article/details/gtccordnse.html

[M06] 向标准错误输出
来源：http://dali.guowangkeji.top/Article/details/gtznlnegjl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gtmygdxbco.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yueranfly.top/Article/details/gtbfuniieh.html

JS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gtcpiwuauy.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtqfyjkxhv.html

Java: System.err.println("err")
来源：http://dali.hnxiangtu.top/Article/details/gttctwcwnf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daria6918.cn/Article/details/gtvtaqtnpu.html

Ruby: warn "err"
来源：http://dali.zdqjudy.top/Article/details/gtcmkwbwlc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtscjqksov.html

[M07] 判断是否为主入口
来源：http://dali.nanxuanxn.top/Article/details/gtzrexgjfr.html

Py:   if __name__ == "__main__":
来源：http://dali.pengpengdd.cyou/Article/details/gtwtjaxlac.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fengsongda.top/Article/details/gtzgcpxepa.html

JS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gtawemmxhz.html

TS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gteppnzizh.html

Java: public static void main(String[] args)
来源：http://dali.havefunace.top/Article/details/gtjgjqymje.html

Go:   func main()
来源：http://dali.wangshuangyany.cn/Article/details/gtrqcvrwnv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xinyue.icu/Article/details/gtqxfpujud.html

C#:   static void Main(string[] args)
来源：http://dali.smart0.xyz/Article/details/gtrfduxmrd.html

[M08] 获取系统与运行时信息
来源：http://dali.jianghu66.top/Article/details/gtnnvvencu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yueranfly.top/Article/details/gtjvjurdml.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cashguo.top/Article/details/gtoqgabrzc.html

JS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gtnqtepwpm.html

TS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gtxqbrnuys.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ydzc1.top/Article/details/gtvhqbepbc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jyoumei.cn/Article/details/gtfpjresbv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shzxlz.cn/Article/details/gthftnonaw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhengqikj.top/Article/details/gtnaratflf.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtjbedzigc.html

N. 数据结构与算法
来源：http://dali.316326.xyz/Article/details/gtnbsxxuth.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gttsufbdxq.html

[N01] 二分查找（有序数组）
来源：http://dali.redwolf501.top/Article/details/gtrufnzfof.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yongpay.top/Article/details/gtjyoapiox.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.smart0.xyz/Article/details/gtqoomptuc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtbafwonft.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gtsyzdtxjp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gtksmkygih.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gttrnppang.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigfzy.top/Article/details/gtpxmanylp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtzpoaysnj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.9152youxi.cn/Article/details/gtautfdwjx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yanxiufei.cn/Article/details/gteeeeqvkz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258.top/Article/details/gtzocafxri.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtvxynrknl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtabmklqek.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hywenlv.cn/Article/details/gtlqzawzqc.html

Go:   slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtefpfkyxr.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gtkqicojuw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhixingplan.top/Article/details/gtbnuzslap.html

[N03] 快速排序（分治示例）
来源：http://dali.xylfe.cn/Article/details/gttzodzwgf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hammf.cn/Article/details/gtirfcssmu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfjawsgx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gtpivboxxb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gtekxoambs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yangfankeji.com/Article/details/gtjgyuuton.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.c1oappe.top/Article/details/gtrgtuvwdq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtouthqfid.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigfzy.top/Article/details/gtooolvtva.html

[N04] 斐波那契数列
来源：http://dali.316326.xyz/Article/details/gtolmvupmo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjniqaxr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangdashe.top/Article/details/gtedacgbbm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtzikitglb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtgsblfdoi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnqzz.top/Article/details/gttgazqary.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sxryk.cn/Article/details/gtvzcbsomc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gtcuunaert.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gthxlmyvlm.html

[N05] 最大公约数
来源：http://dali.dianchejie.cn/Article/details/gttdwbvyfx.html

Py:   math.gcd(a, b)
来源：http://dali.hfpthk.cn/Article/details/gttorpzyqo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sysykeji.top/Article/details/gtyxzrglfv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gtagnqgdza.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gtdooeyyyy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.smart0.xyz/Article/details/gtdhjmuarr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.feifeiyinyue.top/Article/details/gtiweoctrm.html

Ruby: a.gcd(b)
来源：http://dali.hysaishi.cn/Article/details/gtygzfjudd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ehwqpu.com/Article/details/gtaowzdlps.html

[N06] 判断回文字符串
来源：http://dali.sxryk.cn/Article/details/gtkevduuhk.html

Py:   s == s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gtcaaaluvz.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258.top/Article/details/gtytpoyfap.html

JS:   s === [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtlzhebrdo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtofslgbwr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.daria6918.cn/Article/details/gtsspzxuzv.html

Go:   // 双指针从两端比较
来源：http://dali.ppjwa.cn/Article/details/gtirjkqymc.html

Ruby: s == s.reverse
来源：http://dali.zhongyouzk.top/Article/details/gtznrizorg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkintruv.html

[N07] 两数之和（返回下标）
来源：http://dali.jianghu66.top/Article/details/gtuixkpecs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aibaodan.cn/Article/details/gtiwrqlrep.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxinkj.top/Article/details/gtyfbruecd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.fengsongda.top/Article/details/gtdqehpspc.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhiwuduotai.top/Article/details/gtcxxmsuor.html

Java: // 手写 HashMap
来源：http://dali.meibo888.top/Article/details/gtqbanwnpu.html

Go:   // 手写 map[int]int
来源：http://dali.ybcxt.top/Article/details/gtiazncqfy.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gtobqvielr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dianchejie.cn/Article/details/gttgaxuysf.html

[N08] 生成全排列
来源：http://dali.zhixingplan.top/Article/details/gtxehcnykc.html

Py:   itertools.permutations(arr)
来源：http://dali.chenzaomai.com/Article/details/gthabtfgwf.html

PHP:  // 手写递归交换
来源：http://dali.ydzc1.top/Article/details/gtrjmdaimp.html

JS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtjkamvdoo.html

TS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtzntsnktf.html

Java: // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtgedoqlcq.html

Go:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtrhmzsmsq.html

Ruby: arr.permutation.to_a
来源：http://dali.yanxiufei.cn/Article/details/gtpkhpukrx.html

C#:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtclytezkx.html

[N09] 栈与队列
来源：http://dali.xuanzx.com/Article/details/gttyrlwxaq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtbmojxwkq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtjgoitkbe.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtzinxnnau.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hammf.cn/Article/details/gtfcqbszja.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jianghu66.top/Article/details/gtdnvlaccy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhengqikj.top/Article/details/gtyfdhctkj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtvrgirizx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtywjdyzof.html

[N10] 链表节点定义
来源：http://dali.daria6918.cn/Article/details/gtlvmrtpkm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.mhx1999.top/Article/details/gtpwemuowm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zdqjudy.top/Article/details/gtlgnfsuzg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarrrfyqt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigfzy.top/Article/details/gtwrppbtvm.html

Java: class Node { int v; Node next; }
来源：http://dali.jlsjyb.cn/Article/details/gtizmoanqi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tian-w.cn/Article/details/gtpmyfqiyv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258.top/Article/details/gtbuouiigw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcrirmmr.html

[N11] 二叉树中序遍历
来源：http://dali.9152youxi.cn/Article/details/gtrwuiqpzw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.svipenyu.cn/Article/details/gtynguwnnl.html

PHP:  // 手写递归函数
来源：http://dali.jiagoushi.top/Article/details/gtxueqijnt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gtijifvwrv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gtyaanqntq.html

Java: // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gtpcvidzrm.html

Go:   // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gtitozjaux.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hongshengwenyu.top/Article/details/gtxunxniwu.html

C#:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtnnqagzvw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztbnyipi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gotoacloud.top/Article/details/gtneszglqw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gogol.net.cn/Article/details/gtccyksong.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gtrgkmlium.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtlzyoncni.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gtstgwitwz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shuidangran.top/Article/details/gtsqlcjeuv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xziqi.cn/Article/details/gtgvwewpsg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gtajtinrjf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtkodasosn.html

O. 并发与异步
来源：http://dali.jianghu66.top/Article/details/gtotkrgxma.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtbjluupfg.html

[O01] 启动一个线程
来源：http://dali.chenlongwang.top/Article/details/gtmxekxcdr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gotoacloud.top/Article/details/gtdltiazis.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ppjwa.cn/Article/details/gtikedibxe.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.smart0.xyz/Article/details/gtxhrwehlv.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gtdlwrbrqn.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258888.top/Article/details/gtnnkxkiys.html

Go:   go f()
来源：http://dali.daria6918.cn/Article/details/gtuqddkbny.html

Ruby: Thread.new { f }
来源：http://dali.tanke756.top/Article/details/gtoljrjmzf.html

C#:   Task.Run(() => F());
来源：http://dali.hongshengwenyu.top/Article/details/gtaxpiebpm.html

[O02] 使用线程池
来源：http://dali.zhoulong.xyz/Article/details/gtggxpzmrb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.vqdsnc.cn/Article/details/gtxkxqaxpx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sufxvd.cn/Article/details/gtvxbzztld.html

JS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gtewqoettr.html

TS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gtbjfofkuq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubhvpqkc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrpffmlb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shzxlz.cn/Article/details/gtmygoyjrv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.316326.xyz/Article/details/gtwuncweqz.html

[O03] 加锁保护共享数据
来源：http://dali.nanxinkj.top/Article/details/gtokzxozyi.html

Py:   with lock: shared += 1
来源：http://dali.tanke756.top/Article/details/gtlpaygviz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tian-w.cn/Article/details/gtlauolngj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.0kj1m.cn/Article/details/gtebvhjrtq.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gtusoqtvkj.html

Java: synchronized (this) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gtseizewtu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ivvv.top/Article/details/gtxynuwzig.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jyoumei.cn/Article/details/gtsdmskipa.html

C#:   lock (gate) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gtjsrajcad.html

[O04] 定义异步函数并等待
来源：http://dali.xylfe.cn/Article/details/gtybptxzaj.html

Py:   async def f():⏎    await g()
来源：http://dali.nwbrower.top/Article/details/gtoqnfubhb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hongshengwenyu.top/Article/details/gtwkbhcilx.html

JS:   async function f() { await g(); }
来源：http://dali.hammf.cn/Article/details/gtoqdvokhf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.daria6918.cn/Article/details/gtimuonzbu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.c1oappe.top/Article/details/gtbtypfebh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.birdmap.top/Article/details/gtyocnxjxn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tian-w.cn/Article/details/gtdlcarmis.html

C#:   async Task F() { await G(); }
来源：http://dali.yongpay.top/Article/details/gtjvzydbky.html

[O05] 并发执行并等待全部完成
来源：http://dali.sysykeji.top/Article/details/gtuazyrylf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cashguo.top/Article/details/gtwnzvwrye.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jyoumei.cn/Article/details/gtwxsnford.html

JS:   await Promise.all(tasks)
来源：http://dali.daria6918.cn/Article/details/gtqtamxxum.html

TS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gtcqhazpla.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tanke756.top/Article/details/gtwanebffv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xuetiantiany.cn/Article/details/gtrkbksebf.html

Ruby: threads.map(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapfdhxqz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzwdiwdb.html

[O06] 使用进程池
来源：http://dali.xuetiantiany.cn/Article/details/gtervrgidx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.havefunace.top/Article/details/gthzitwjeb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangshuangyany.cn/Article/details/gtnwuaojwj.html

JS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gtjxtspzzl.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gtnaeohnnk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yangfankeji.com/Article/details/gtdhgbgydz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.svipenyu.cn/Article/details/gtuqzcmiqb.html

Ruby: // fork 块
来源：http://dali.nanxuanxn.top/Article/details/gtlttikkmo.html

C#:   Parallel.For
来源：http://dali.sweek.top/Article/details/gtucydhoet.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtjxdnetva.html

P. 常用工具函数
来源：http://dali.nwbrower.top/Article/details/gtrncytyvc.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtypjgzwdh.html

[P01] 生成 UUID
来源：http://dali.jianghu66.top/Article/details/gtgamxqyru.html

Py:   str(uuid.uuid4())
来源：http://dali.zycfv.cn/Article/details/gtrvxgycjw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aizwys.cn/Article/details/gtjvtysods.html

JS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtehnjymwo.html

TS:   crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gtasiibebe.html

Java: UUID.randomUUID().toString()
来源：http://dali.yanxiufei.cn/Article/details/gtqxmhkvqm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.svipenyu.cn/Article/details/gthcuccsxp.html

Ruby: SecureRandom.uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtpgzcjgih.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cdnleiting.top/Article/details/gtbgphxnvu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.andypj.xyz/Article/details/gtzsigjwnn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hammf.cn/Article/details/gtssokbopc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtgcbfgjkf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdqaaguj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sweek.top/Article/details/gtcjmmdtqr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.c1oappe.top/Article/details/gtctwkkckn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fengsongda.top/Article/details/gtrjltchte.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnxiangtu.top/Article/details/gtbftrbpmg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guowangkeji.top/Article/details/gtuvmiwgno.html

[P03] 生成短随机字符串
来源：http://dali.yj202588.top/Article/details/gtcgxvcgji.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhongyouzk.top/Article/details/gtjlysflrs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jyoumei.cn/Article/details/gtxbybhctl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jianghu66.top/Article/details/gtiwbtfijk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jianghu66.top/Article/details/gtchfmzvwy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gzhubu.top/Article/details/gttkhwukzh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nanxinkj.top/Article/details/gtzsvlryiw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cucudq.cn/Article/details/gtfurzmmog.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cashguo.top/Article/details/gtgradurcr.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gtkwfghsae.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ydzc1.top/Article/details/gtxrgjfygw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtauzogrmh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gtemxpvuud.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuetiantiany.cn/Article/details/gtzqrefsqq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtbowkygje.html

Go:   len(arr);  len(m)
来源：http://dali.xziqi.cn/Article/details/gtyjbclzxm.html

Ruby: x.length;  x.size
来源：http://dali.jianghu66.top/Article/details/gtdzxkebfl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuxming.cn/Article/details/gtdynakqrn.html


<!-- 参考信息 -->