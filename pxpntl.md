代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gt2nzszncaj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tian-w.cn/Article/details/gt2ceqdulqf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.316326.xyz/Article/details/gt2xlyoydbn.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gt2eygxkhiz.html

TS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gt2knhkiqdz.html

Java: resp.statusCode()
来源：http://dali.zhixingplan.top/Article/details/gt2vgcfktyn.html

Go:   resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gt2tlnbuvpz.html

Ruby: resp.code.to_i
来源：http://dali.yongpay.top/Article/details/gt2scnwugoe.html

C#:   (int)resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gt2oxptnrgj.html

[L08] 并发请求多个地址
来源：http://dali.chenjidiqi.icu/Article/details/gt2yecbyiyj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jlsjyb.cn/Article/details/gt2omnqksye.html

PHP:  curl_multi_init() 系列
来源：http://dali.yanxiufei.cn/Article/details/gt2bzbmjumz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lulvqtvv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gt2gbhuqkew.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cqqwz.cn/Article/details/gt2omjieeik.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuanzx.com/Article/details/gt2okaiwaxd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guannengcc.top/Article/details/gt2kolfpvbc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gt2nbzfcdxb.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ayvimktj.html

M. 命令行 / 进程 / 环境
来源：http://dali.cdnleiting.top/Article/details/gt2fvvthuxj.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uhepwlad.html

[M01] 读取命令行参数
来源：http://dali.zhixingplan.top/Article/details/gt2moukdfut.html

Py:   sys.argv[1:]
来源：http://dali.jqgfzy.top/Article/details/gt2ltnivqrv.html

PHP:  $argv;  $argc;
来源：http://dali.yuanzhike.top/Article/details/gt2ocxfelui.html

JS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gt2vvmuexwq.html

TS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gt2owykgouv.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gt2ybwsewhk.html

Go:   os.Args[1:]
来源：http://dali.0kj1m.cn/Article/details/gt2bdkwfqgn.html

Ruby: ARGV
来源：http://dali.quarkkingdee.top/Article/details/gt2eawvfcvc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gt2dtzverio.html

[M02] 读取环境变量
来源：http://dali.nwbrower.top/Article/details/gt2jzsgfgbi.html

Py:   os.environ.get("HOME")
来源：http://dali.iojbl.cn/Article/details/gt2txrubrha.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gt2xcdggtfh.html

JS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bosvovwh.html

TS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gt2ogibnzqw.html

Java: System.getenv("HOME")
来源：http://dali.xziqi.cn/Article/details/gt2qbrkoxvc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gt2imjpmhuy.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258.top/Article/details/gt2nvnvjhdv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pxuuwdnv.html

[M03] 执行外部命令
来源：http://dali.guowangkeji.top/Article/details/gt2svoyxqfb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenlongwang.top/Article/details/gt2mbpyxfin.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cbjbuvxk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gt2bpzafwaa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gt2wufmehau.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aibaodan.cn/Article/details/gt2nuvbtlvv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.birdmap.top/Article/details/gt2mjnunoai.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.feifeiyinyue.top/Article/details/gt2zfdezufn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daria6918.cn/Article/details/gt2wwihlqfo.html

[M04] 获取当前工作目录
来源：http://dali.ybcxt.top/Article/details/gt2dfeqlfsa.html

Py:   os.getcwd()
来源：http://dali.jqgufenzy.top/Article/details/gt2hadqtiwz.html

PHP:  getcwd();
来源：http://dali.iojbl.cn/Article/details/gt2ztylcqfe.html

JS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gt2dwgculps.html

TS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2hwyjaqhr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zdqjudy.top/Article/details/gt2nvubhepl.html

Go:   os.Getwd()
来源：http://dali.yuanzhike.top/Article/details/gt2ocllrlwd.html

Ruby: Dir.pwd
来源：http://dali.yuxming.cn/Article/details/gt2khrlabsq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shuidangran.top/Article/details/gt2bjoanhrs.html

[M05] 设置退出码
来源：http://dali.jyoumei.cn/Article/details/gt2xemwaryn.html

Py:   sys.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2bfzwkcvq.html

PHP:  exit(1);
来源：http://dali.xinyue.icu/Article/details/gt2khilkfrs.html

JS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2dmjklxln.html

TS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ixnfvzqz.html

Java: System.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzgyeezu.html

Go:   os.Exit(1)
来源：http://dali.xylfe.cn/Article/details/gt2glzdswdx.html

Ruby: exit 1
来源：http://dali.gzhubu.top/Article/details/gt2trkbuwwt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gvdxfdue.html

[M06] 向标准错误输出
来源：http://dali.yj20258888.top/Article/details/gt2yymzesuu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gt2jekhjfbb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pozesdce.html

JS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2bnuqetig.html

TS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gt2fmaxoqkb.html

Java: System.err.println("err")
来源：http://dali.shzxlz.cn/Article/details/gt2aditgoew.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.c1oappe.top/Article/details/gt2exxqoavg.html

Ruby: warn "err"
来源：http://dali.svipenyu.cn/Article/details/gt2csmnoacq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zdqjudy.top/Article/details/gt2naxiderp.html

[M07] 判断是否为主入口
来源：http://dali.sxryk.cn/Article/details/gt2dfvvrjcc.html

Py:   if __name__ == "__main__":
来源：http://dali.zycfv.cn/Article/details/gt2tsrzkbck.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.daxiang520.top/Article/details/gt2ufmjlxfy.html

JS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gt2tglgoumk.html

TS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gt2alzkiems.html

Java: public static void main(String[] args)
来源：http://dali.shzxlz.cn/Article/details/gt2ahtyqtqi.html

Go:   func main()
来源：http://dali.iojbl.cn/Article/details/gt2riotipzr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pycfn.com/Article/details/gt2vkwvnshe.html

C#:   static void Main(string[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ygzoywix.html

[M08] 获取系统与运行时信息
来源：http://dali.sweek.top/Article/details/gt2icjrkqnw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhengqikj.top/Article/details/gt2yimdxxlx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cdnleiting.top/Article/details/gt2ghnemdxu.html

JS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gt2wdszudhq.html

TS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gt2xuucskmn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgufenzy.top/Article/details/gt2mbybelps.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ivvv.top/Article/details/gt2dzslmeyx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwgjcgfp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cheryme.top/Article/details/gt2sikoecti.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2iqlhhpby.html

N. 数据结构与算法
来源：http://dali.jlsjyb.cn/Article/details/gt2imqlxsur.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2kyxhvhkh.html

[N01] 二分查找（有序数组）
来源：http://dali.guowangkeji.top/Article/details/gt2kyqqjlik.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2sabothlx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuanzx.com/Article/details/gt2natvyaib.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gt2uznsrvxl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gt2hdtwnjap.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gt2kwsbryjc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xthrlrem.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zdqjudy.top/Article/details/gt2axoestqp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2ykkmazsr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guannengcc.top/Article/details/gt2zfcybnjy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gt2zehboxqp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daria6918.cn/Article/details/gt2tpbcxcsx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gt2dghmgmao.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gt2txwjukon.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangdashe.top/Article/details/gt2ppiqzkxv.html

Go:   slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gt2fvkrczfc.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gt2glltfmhz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shangyingyoupin.top/Article/details/gt2roibbtmw.html

[N03] 快速排序（分治示例）
来源：http://dali.quarkkingdee.top/Article/details/gt2glmdanqt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shuidangran.top/Article/details/gt2frdaougv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangdashe.top/Article/details/gt2enjnmmvj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gt2idwvsbga.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tian-w.cn/Article/details/gt2cuiyydwo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cqqwz.cn/Article/details/gt2dmidmouo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhongyouzk.top/Article/details/gt2mbakwwnm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jqgfzy.top/Article/details/gt2zmeeicji.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gaohongyu789.top/Article/details/gt2avrcoyqn.html

[N04] 斐波那契数列
来源：http://dali.jqgfzy.top/Article/details/gt2bcqojrde.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gt2fbizjupe.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gt2dvsszdgi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gt2zomslrei.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gt2hwhatzpa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daxiang520.top/Article/details/gt2zzkxdesf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daria6918.cn/Article/details/gt2rkjhjudu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gt2hsixoumj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2xeipffvu.html

[N05] 最大公约数
来源：http://dali.zycfv.cn/Article/details/gt2yezkgade.html

Py:   math.gcd(a, b)
来源：http://dali.sxryk.cn/Article/details/gt2udpfemok.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shuidangran.top/Article/details/gt2gdaikesj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gt2lcikmyoc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258888.top/Article/details/gt2gfrwhgmo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenzaomai.com/Article/details/gt2opstyacd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2aablekyg.html

Ruby: a.gcd(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2lcggyiog.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cheryme.top/Article/details/gt2cxjzkxac.html

[N06] 判断回文字符串
来源：http://dali.nwbrower.top/Article/details/gt2ffqegvja.html

Py:   s == s[::-1]
来源：http://dali.bjfxy.top/Article/details/gt2cfcfdifh.html

PHP:  $s === strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kuybxxfy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gt2cvbiprxu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gpvwxakd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.havefunace.top/Article/details/gt2etuhertc.html

Go:   // 双指针从两端比较
来源：http://dali.meibo888.top/Article/details/gt2hbxwfgmw.html

Ruby: s == s.reverse
来源：http://dali.nwbrower.top/Article/details/gt2cspqzxtg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gt2rudrqdjw.html

[N07] 两数之和（返回下标）
来源：http://dali.yj202588.top/Article/details/gt2thadnjmo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fzhhl.top/Article/details/gt2fhqyoglr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gogol.net.cn/Article/details/gt2bjynswan.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.kuanghao11.cn/Article/details/gt2ojficfka.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhongyouzk.top/Article/details/gt2bgxfocuo.html

Java: // 手写 HashMap
来源：http://dali.chenjidiqi.icu/Article/details/gt2bdqldoeh.html

Go:   // 手写 map[int]int
来源：http://dali.jiagoushi.top/Article/details/gt2kptmuoyy.html

Ruby: // 手写 Hash
来源：http://dali.redwolf501.top/Article/details/gt2uimcuicb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pycfn.com/Article/details/gt2nycpcjxc.html

[N08] 生成全排列
来源：http://dali.shangyingyoupin.top/Article/details/gt2mduzhjhk.html

Py:   itertools.permutations(arr)
来源：http://dali.redwolf501.top/Article/details/gt2pxqglzny.html

PHP:  // 手写递归交换
来源：http://dali.xylfe.cn/Article/details/gt2pmixwcol.html

JS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gt2oxavhdmv.html

TS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2pvaqlwri.html

Java: // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uwbqoota.html

Go:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gt2qbzvokmp.html

Ruby: arr.permutation.to_a
来源：http://dali.shuidangran.top/Article/details/gt2jpjvudor.html

C#:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2zxhlvnze.html

[N09] 栈与队列
来源：http://dali.daxiang520.top/Article/details/gt2kyjthcqg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wetggqkv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lznepspq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gt2ielvelia.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cashguo.top/Article/details/gt2ysxyhaif.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.mhx1999.top/Article/details/gt2ptylmesp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yongpay.top/Article/details/gt2bqarixfc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gt2younyjll.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sxryk.cn/Article/details/gt2xqvlqtco.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ahazoyjq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yueranfly.top/Article/details/gt2evpexwdq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kwlbpfco.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hywenlv.cn/Article/details/gt2mfutfewn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cdnleiting.top/Article/details/gt2ehzkkqie.html

Java: class Node { int v; Node next; }
来源：http://dali.316326.xyz/Article/details/gt2oqxcdlwu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cqqwz.cn/Article/details/gt2elacizbn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daria6918.cn/Article/details/gt2fmtzlbhu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sysykeji.top/Article/details/gt2zxtgapxx.html

[N11] 二叉树中序遍历
来源：http://dali.hfpthk.cn/Article/details/gt2ttzscgih.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tianlin.xyz/Article/details/gt2acsixjrx.html

PHP:  // 手写递归函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uhebhlyq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhengqikj.top/Article/details/gt2abqhmfxb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gt2cyhjpabd.html

Java: // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gt2ymcfvtso.html

Go:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gt2axhesymb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cashguo.top/Article/details/gt2thhmzepb.html

C#:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gt2dhygamhu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yangfankeji.com/Article/details/gt2gnzdnlnr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigfzy.top/Article/details/gt2zbxqffak.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.meibo888.top/Article/details/gt2kzyeelak.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gnwtvean.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gt2pgospmsk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gt2hqtoiipd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigfzy.top/Article/details/gt2auajjotw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ppjwa.cn/Article/details/gt2egvbmyho.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gt2hqbkdgjz.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2krkqmyrg.html

O. 并发与异步
来源：http://dali.aibaodan.cn/Article/details/gt2qljkkdda.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2qucayhce.html

[O01] 启动一个线程
来源：http://dali.smart0.xyz/Article/details/gt2fxjecchs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cdnleiting.top/Article/details/gt2dymeugwy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jqgfzy.top/Article/details/gt2bhxhqqop.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuetiantiany.cn/Article/details/gt2rofbhelz.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gt2royzdqyt.html

Java: new Thread(() -> f()).start()
来源：http://dali.yonumen.top/Article/details/gt2covlufft.html

Go:   go f()
来源：http://dali.wangdashe.top/Article/details/gt2slcgztsp.html

Ruby: Thread.new { f }
来源：http://dali.tanke756.top/Article/details/gt2rvlejlmz.html

C#:   Task.Run(() => F());
来源：http://dali.xuetiantiany.cn/Article/details/gt2iihjyoyt.html

[O02] 使用线程池
来源：http://dali.yj20258888.top/Article/details/gt2tokpdyoa.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aizwys.cn/Article/details/gt2qztzofco.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigfzy.top/Article/details/gt2lelctdam.html

JS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gt2idpbvros.html

TS:   // worker_threads 线程池
来源：http://dali.sxryk.cn/Article/details/gt2urqhsopj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fzhhl.top/Article/details/gt2oaligbcj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.smart0.xyz/Article/details/gt2espictel.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sufxvd.cn/Article/details/gt2joyhjfsh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jyoumei.cn/Article/details/gt2fgauqdas.html

[O03] 加锁保护共享数据
来源：http://dali.jianghu66.top/Article/details/gt2xqqrsbkk.html

Py:   with lock: shared += 1
来源：http://dali.ehwqpu.com/Article/details/gt2jaqbxkpa.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cucudq.cn/Article/details/gt2vmhmlzyn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenlongwang.top/Article/details/gt2ahgywlej.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gt2mwgevmzp.html

Java: synchronized (this) { shared++; }
来源：http://dali.wangdashe.top/Article/details/gt2rfeptifs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xylfe.cn/Article/details/gt2sjwogswu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgfzy.top/Article/details/gt2kchucxwd.html

C#:   lock (gate) { shared++; }
来源：http://dali.cheryme.top/Article/details/gt2ycjknnqq.html

[O04] 定义异步函数并等待
来源：http://dali.fengsongda.top/Article/details/gt2nrylwwks.html

Py:   async def f():⏎    await g()
来源：http://dali.guannengcc.top/Article/details/gt2wivcrjpo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2almpwqxa.html

JS:   async function f() { await g(); }
来源：http://dali.yangfankeji.com/Article/details/gt2xluhnvga.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2frwrnlkl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fzhhl.top/Article/details/gt2vbrmtiei.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.snrcjt.cn/Article/details/gt2dfiubpcf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pycfn.com/Article/details/gt2olzpailr.html

C#:   async Task F() { await G(); }
来源：http://dali.9152youxi.cn/Article/details/gt2fcepfcem.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mqgmdgft.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenzaomai.com/Article/details/gt2xtwmgjkq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jianghu66.top/Article/details/gt2bldmjijp.html

JS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gt2lxmvgutm.html

TS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gt2umixgkxd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuxming.cn/Article/details/gt2osqtkflm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cheryme.top/Article/details/gt2yunzqcvf.html

Ruby: threads.map(&:join)
来源：http://dali.zhixingplan.top/Article/details/gt2bnaihdtl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jlsjyb.cn/Article/details/gt2dxaucdag.html

[O06] 使用进程池
来源：http://dali.yj202588.top/Article/details/gt2ntzjsgsz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangshuangyany.cn/Article/details/gt2rrhrhqrd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gzhubu.top/Article/details/gt2swkwumsv.html

JS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gt2vqxtpcxp.html

TS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gt2gfvgkcjw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhongyouzk.top/Article/details/gt2mzzyelgy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinqigfzy.top/Article/details/gt2njdapvna.html

Ruby: // fork 块
来源：http://dali.dianchejie.cn/Article/details/gt2rinsxkho.html

C#:   Parallel.For
来源：http://dali.yonumen.top/Article/details/gt2rdfruznm.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2tllvbibz.html

P. 常用工具函数
来源：http://dali.tanke756.top/Article/details/gt2woyiqdve.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2ctmugvnk.html

[P01] 生成 UUID
来源：http://dali.cucudq.cn/Article/details/gt2tdnuslpw.html

Py:   str(uuid.uuid4())
来源：http://dali.ydzc1.top/Article/details/gt2vkgpvumu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hnxiangtu.top/Article/details/gt2zmxleuhy.html

JS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gt2ejvogfuu.html

TS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gt2svpnzebc.html

Java: UUID.randomUUID().toString()
来源：http://dali.snrcjt.cn/Article/details/gt2slmqhnrd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.mhx1999.top/Article/details/gt2rjeppedl.html

Ruby: SecureRandom.uuid
来源：http://dali.ppjwa.cn/Article/details/gt2shqxjfuv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.c1oappe.top/Article/details/gt2tkpkgagn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zdqjudy.top/Article/details/gt2ukhacgbl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangshuangyany.cn/Article/details/gt2fkrslpil.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258.top/Article/details/gt2lvlixbws.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2addroyoo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tian-w.cn/Article/details/gt2pabevxcj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.meibo888.top/Article/details/gt2boazfwqc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shuidangran.top/Article/details/gt2hyzdwrsi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2eszywigj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.quarkkingdee.top/Article/details/gt2zbsgznph.html

[P03] 生成短随机字符串
来源：http://dali.meibo888.top/Article/details/gt2ykjygzvk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gogol.net.cn/Article/details/gt2eewshwvf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.meibo888.top/Article/details/gt2wqdhknfb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gt2pedmcadw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gt2tkxtmcnn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ezcfdjuc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shangyingyoupin.top/Article/details/gt2zymqepql.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2euegsqsy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daria6918.cn/Article/details/gt2xbcvbgif.html

[P04] 求长度
来源：http://dali.fzhhl.top/Article/details/gt2mbxlutyt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yanxiufei.cn/Article/details/gt2kkklsukd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gt2edbjygnw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gt2swacoaid.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gt2grawfblx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gt2jiddhjkm.html

Go:   len(arr);  len(m)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fgnjflaj.html

Ruby: x.length;  x.size
来源：http://dali.hnxiangtu.top/Article/details/gt2vonswadt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fzhhl.top/Article/details/gt2zitchyqx.html


<!-- 参考信息 -->