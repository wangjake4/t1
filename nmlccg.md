代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daxiang520.top/Article/details/gt2nomymepe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tian-w.cn/Article/details/gt2chiwrwfu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.c1oappe.top/Article/details/gt2asmarkvn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yanxiufei.cn/Article/details/gt2flscvbli.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tyizooil.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jqjbseen.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.bjfxy.top/Article/details/gt2arqwruvt.html

JS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gt2leijjzvv.html

TS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gt2xtpdpdjm.html

Java: resp.statusCode()
来源：http://dali.ehwqpu.com/Article/details/gt2cehgajpr.html

Go:   resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gt2blksjoem.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gt2japvygwu.html

C#:   (int)resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gt2abghhlft.html

[L08] 并发请求多个地址
来源：http://dali.chenlongwang.top/Article/details/gt2jlhcjkfs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guowangkeji.top/Article/details/gt2jrlmktzf.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnqzz.top/Article/details/gt2lijamlax.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gt2psfutjah.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2guxlyeje.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigufen.top/Article/details/gt2twtszeyy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxuanxn.top/Article/details/gt2ioomrudv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jictqvxj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuanzx.com/Article/details/gt2rfovtdyh.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2mphyjtic.html

M. 命令行 / 进程 / 环境
来源：http://dali.svipenyu.cn/Article/details/gt2snzflzvd.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2qjcgvqal.html

[M01] 读取命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2zaxwlmuq.html

Py:   sys.argv[1:]
来源：http://dali.yanxiufei.cn/Article/details/gt2oyaxokhg.html

PHP:  $argv;  $argc;
来源：http://dali.aibaodan.cn/Article/details/gt2sqrjfrro.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gt2vkdqpmdv.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gt2ufgeyrkv.html

Java: args 数组（main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gt2jfgplnni.html

Go:   os.Args[1:]
来源：http://dali.yvedp.cn/Article/details/gt2typnqtss.html

Ruby: ARGV
来源：http://dali.chenzaomai.com/Article/details/gt2wgffemni.html

C#:   args 数组（Main 方法参数）
来源：http://dali.meibo888.top/Article/details/gt2acaknngs.html

[M02] 读取环境变量
来源：http://dali.yuanzhike.top/Article/details/gt2puofsnht.html

Py:   os.environ.get("HOME")
来源：http://dali.mhx1999.top/Article/details/gt2wbyjgxgu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gt2ezakqknd.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gt2gmtssnlq.html

TS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gt2wawzfkxv.html

Java: System.getenv("HOME")
来源：http://dali.nwbrower.top/Article/details/gt2uvqauahp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hammf.cn/Article/details/gt2nukuopaw.html

Ruby: ENV["HOME"]
来源：http://dali.andypj.xyz/Article/details/gt2ezfnkzls.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2elarrxnw.html

[M03] 执行外部命令
来源：http://dali.bjfxy.top/Article/details/gt2xwvxodpg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.bjfxy.top/Article/details/gt2kvgethbo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yvedp.cn/Article/details/gt2fbxqnjva.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gt2viljefwd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gt2iigwwwbj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrqfomj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ibnrodgr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuanzx.com/Article/details/gt2mywqxpii.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hywenlv.cn/Article/details/gt2aesnakmv.html

[M04] 获取当前工作目录
来源：http://dali.gzhubu.top/Article/details/gt2bisydkub.html

Py:   os.getcwd()
来源：http://dali.nwbrower.top/Article/details/gt2mrqttyno.html

PHP:  getcwd();
来源：http://dali.shangyingyoupin.top/Article/details/gt2vlflbsfs.html

JS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2qmbfwxhc.html

TS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iirrttaj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yueranfly.top/Article/details/gt2wvlmaybo.html

Go:   os.Getwd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2hgxpvady.html

Ruby: Dir.pwd
来源：http://dali.yanxiufei.cn/Article/details/gt2ukkwznsr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gkowanik.html

[M05] 设置退出码
来源：http://dali.hysaishi.cn/Article/details/gt2btjuwmxr.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2orhnhmzd.html

PHP:  exit(1);
来源：http://dali.xylfe.cn/Article/details/gt2sjvivwym.html

JS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2tgsgsgjd.html

TS:   process.exit(1)
来源：http://dali.iojbl.cn/Article/details/gt2ewiqdstl.html

Java: System.exit(1)
来源：http://dali.meibo888.top/Article/details/gt2yizbzwwy.html

Go:   os.Exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2atgjaxsb.html

Ruby: exit 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qdnnpcyf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuetiantiany.cn/Article/details/gt2cblekfgo.html

[M06] 向标准错误输出
来源：http://dali.nwbrower.top/Article/details/gt2fqgcetlo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ghevafdc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjvctaq.html

JS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gt2wqahxnrg.html

TS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2gyxwxegb.html

Java: System.err.println("err")
来源：http://dali.jinqigufen.top/Article/details/gt2kursnimn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gogol.net.cn/Article/details/gt2gsrmfpzr.html

Ruby: warn "err"
来源：http://dali.yonumen.top/Article/details/gt2uwnohdmk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.c1oappe.top/Article/details/gt2uqoyxzvv.html

[M07] 判断是否为主入口
来源：http://dali.hfpthk.cn/Article/details/gt2ylvkxmgl.html

Py:   if __name__ == "__main__":
来源：http://dali.feifeiyinyue.top/Article/details/gt2kyklmudb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.c1oappe.top/Article/details/gt2uktfcama.html

JS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gt2rhcrucxw.html

TS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gt2erqrjxfx.html

Java: public static void main(String[] args)
来源：http://dali.chenlongwang.top/Article/details/gt2uhpsmker.html

Go:   func main()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ejhzrzgb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shangyingyoupin.top/Article/details/gt2ubimabmr.html

C#:   static void Main(string[] args)
来源：http://dali.9152youxi.cn/Article/details/gt2ezkyzeyy.html

[M08] 获取系统与运行时信息
来源：http://dali.hammf.cn/Article/details/gt2fzsdbzrd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.0kj1m.cn/Article/details/gt2dxzckffj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gt2zbnoavev.html

JS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gt2iyewcqgk.html

TS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gt2zhzwrdcc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhongyouzk.top/Article/details/gt2gqcfssuu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenjidiqi.icu/Article/details/gt2wedfaxev.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nldwzvap.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yonumen.top/Article/details/gt2ruvppouh.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2krtacxtw.html

N. 数据结构与算法
来源：http://dali.hnxiangtu.top/Article/details/gt2tnlboiuz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2jaltgthm.html

[N01] 二分查找（有序数组）
来源：http://dali.zycfv.cn/Article/details/gt2jriocemo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gzkswxlq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.0kj1m.cn/Article/details/gt2qbbsbmjf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gt2gxmfaipu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gt2zshkhrwj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2krfjusag.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2xlaogjzu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.kuanghao11.cn/Article/details/gt2ygdahekw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2osqxzrwu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kbyixywb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangdashe.top/Article/details/gt2ftiprfjr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.mhx1999.top/Article/details/gt2dojfebvc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yawlhjyj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gt2kgckhoqe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tanke756.top/Article/details/gt2ippdwnat.html

Go:   slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gt2brmrkaea.html

Ruby: arr.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wcrbiiwj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nwbrower.top/Article/details/gt2aegxjozx.html

[N03] 快速排序（分治示例）
来源：http://dali.cucudq.cn/Article/details/gt2rnwssexn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hongshengwenyu.top/Article/details/gt2lwcmevqn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xziqi.cn/Article/details/gt2fsrsxecf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gt2qbffifep.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gt2doagshgg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jlsjyb.cn/Article/details/gt2jxyojgfy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuanzhike.top/Article/details/gt2fbnpduxt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.9152youxi.cn/Article/details/gt2zjpozcfp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nmbyzazr.html

[N04] 斐波那契数列
来源：http://dali.andypj.xyz/Article/details/gt2xcvtyrln.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gt2kemysjer.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nwbrower.top/Article/details/gt2gyqpwbeb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gt2dalhuddg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2rwzcnrys.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258.top/Article/details/gt2medczdjt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dashuyun.cn/Article/details/gt2pnrkpzrj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cdnleiting.top/Article/details/gt2xooucfxm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gt2bitlcurg.html

[N05] 最大公约数
来源：http://dali.birdmap.top/Article/details/gt2kmptfaaz.html

Py:   math.gcd(a, b)
来源：http://dali.yonumen.top/Article/details/gt2rlrstave.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sxryk.cn/Article/details/gt2kjnnekof.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gt2myvcanru.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ppjwa.cn/Article/details/gt2gayhyosq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eeoxaqlj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnqzz.top/Article/details/gt2uxnbcfwv.html

Ruby: a.gcd(b)
来源：http://dali.ehwqpu.com/Article/details/gt2gdwanupg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2guaeizun.html

[N06] 判断回文字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2lhwtxisx.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qjisrwpp.html

PHP:  $s === strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gt2mdsqlvya.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2qkketwjq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2tdjqdpct.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cqqwz.cn/Article/details/gt2gdbrirnd.html

Go:   // 双指针从两端比较
来源：http://dali.iojbl.cn/Article/details/gt2aduimczp.html

Ruby: s == s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gt2fepkdiny.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gt2fpxuzdst.html

[N07] 两数之和（返回下标）
来源：http://dali.hongshengwenyu.top/Article/details/gt2oansxrtq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cqqwz.cn/Article/details/gt2jvcoyoyx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pycfn.com/Article/details/gt2ijsqduda.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sufxvd.cn/Article/details/gt2gwvbibjr.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258888.top/Article/details/gt2ehcldmgi.html

Java: // 手写 HashMap
来源：http://dali.yongpay.top/Article/details/gt2fxladgmg.html

Go:   // 手写 map[int]int
来源：http://dali.hongshengwenyu.top/Article/details/gt2xhbgrdkg.html

Ruby: // 手写 Hash
来源：http://dali.gzhubu.top/Article/details/gt2olnbqzca.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jianghu66.top/Article/details/gt2vakbslyg.html

[N08] 生成全排列
来源：http://dali.meibo888.top/Article/details/gt2fvhwsgye.html

Py:   itertools.permutations(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lpvxmoym.html

PHP:  // 手写递归交换
来源：http://dali.xuetiantiany.cn/Article/details/gt2eclfxxtm.html

JS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2fhuzcrsr.html

TS:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gt2wxaxzlod.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwbqpgyx.html

Go:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2leljrzpz.html

Ruby: arr.permutation.to_a
来源：http://dali.pycfn.com/Article/details/gt2ddujupys.html

C#:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gt2eezgovcc.html

[N09] 栈与队列
来源：http://dali.jiagoushi.top/Article/details/gt2kvaiklox.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gogol.net.cn/Article/details/gt2eczcizrj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cucudq.cn/Article/details/gt2jtlcfwrb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2scrkoqic.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.svipenyu.cn/Article/details/gt2lgedhygu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuanzhike.top/Article/details/gt2xxrpgyum.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ydzc1.top/Article/details/gt2sdrsgqhd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gt2fesahwaz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenzaomai.com/Article/details/gt2xculimyp.html

[N10] 链表节点定义
来源：http://dali.wangshuangyany.cn/Article/details/gt2vdydwxjg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenzaomai.com/Article/details/gt2jgrwajgu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258.top/Article/details/gt2nhezifye.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cashguo.top/Article/details/gt2wrgjsahr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cqqwz.cn/Article/details/gt2fitkdovu.html

Java: class Node { int v; Node next; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ohksfkyj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xziqi.cn/Article/details/gt2klmvicrm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenlongwang.top/Article/details/gt2yptktmws.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tian-w.cn/Article/details/gt2gmniaser.html

[N11] 二叉树中序遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dbsacrcq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tianlin.xyz/Article/details/gt2qqiitjfl.html

PHP:  // 手写递归函数
来源：http://dali.ppjwa.cn/Article/details/gt2ybuhclpb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gt2cgwybxaw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.smart0.xyz/Article/details/gt2jxvrlhpa.html

Java: // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gt2encyaupl.html

Go:   // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gt2ixezlqjo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hnqzz.top/Article/details/gt2wboqnaev.html

C#:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gt2mkagvmvw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.andypj.xyz/Article/details/gt2qfckeqmf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ppjwa.cn/Article/details/gt2dksefbrr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxuanxn.top/Article/details/gt2trasetzy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gt2bdmppkqi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gt2htuoaefz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gt2guydllby.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yangfankeji.com/Article/details/gt2rcwieypj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cpgqxtuj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gt2intkhmlp.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2juktmxdv.html

O. 并发与异步
来源：http://dali.chenlongwang.top/Article/details/gt2dyorepfc.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2ubvbffmn.html

[O01] 启动一个线程
来源：http://dali.aizwys.cn/Article/details/gt2imdayaii.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.snrcjt.cn/Article/details/gt2ucdzuxeh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhixingplan.top/Article/details/gt2ieaztoaa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnqzz.top/Article/details/gt2ltxsqfbc.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gt2axpfphmu.html

Java: new Thread(() -> f()).start()
来源：http://dali.gaohongyu789.top/Article/details/gt2fzfdqzzq.html

Go:   go f()
来源：http://dali.jinqigfzy.top/Article/details/gt2ylomwuxp.html

Ruby: Thread.new { f }
来源：http://dali.mhx1999.top/Article/details/gt2diubclfl.html

C#:   Task.Run(() => F());
来源：http://dali.shangyingyoupin.top/Article/details/gt2ximvcwpb.html

[O02] 使用线程池
来源：http://dali.shangyingyoupin.top/Article/details/gt2blqjiwdt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ivvv.top/Article/details/gt2umtfuahd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.quarkkingdee.top/Article/details/gt2kzzvjyph.html

JS:   // worker_threads 线程池
来源：http://dali.jqgufenzy.top/Article/details/gt2uehmtoyu.html

TS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gt2yxpxrfzz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenlongwang.top/Article/details/gt2tpusdvtc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cashguo.top/Article/details/gt2knypicsw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258888.top/Article/details/gt2qeczmhki.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.kuanghao11.cn/Article/details/gt2socckhnd.html

[O03] 加锁保护共享数据
来源：http://dali.hfpthk.cn/Article/details/gt2atzyazgb.html

Py:   with lock: shared += 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2njfiupyr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenlongwang.top/Article/details/gt2gubrfhhr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.andypj.xyz/Article/details/gt2cycugjon.html

TS:   // 同 JS
来源：http://dali.yangfankeji.com/Article/details/gt2dvvabvpe.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gt2orudmcmz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yangfankeji.com/Article/details/gt2zdwkufhy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenlongwang.top/Article/details/gt2dijgeaph.html

C#:   lock (gate) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gt2wyrnsqom.html

[O04] 定义异步函数并等待
来源：http://dali.chenjidiqi.icu/Article/details/gt2fzimhkav.html

Py:   async def f():⏎    await g()
来源：http://dali.daria6918.cn/Article/details/gt2qqqiciju.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ypenjnyx.html

JS:   async function f() { await g(); }
来源：http://dali.cucudq.cn/Article/details/gt2oogxolvg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jduragnh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tian-w.cn/Article/details/gt2sbiphxyb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.svipenyu.cn/Article/details/gt2ltohuwgy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.feifeiyinyue.top/Article/details/gt2umdpeuug.html

C#:   async Task F() { await G(); }
来源：http://dali.chenzaomai.com/Article/details/gt2plcqknwq.html

[O05] 并发执行并等待全部完成
来源：http://dali.jyoumei.cn/Article/details/gt2agfinnrr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vyywquch.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuetiantiany.cn/Article/details/gt2ktijkmbq.html

JS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gt2zkvgmqyd.html

TS:   await Promise.all(tasks)
来源：http://dali.meibo888.top/Article/details/gt2tcjjjtsi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.wangdashe.top/Article/details/gt2lxpkwwgj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daxiang520.top/Article/details/gt2pevnigad.html

Ruby: threads.map(&:join)
来源：http://dali.dashuyun.cn/Article/details/gt2lyzyymoe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgfzy.top/Article/details/gt2dxddbbgu.html

[O06] 使用进程池
来源：http://dali.chenzaomai.com/Article/details/gt2xfupjwnk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ivvv.top/Article/details/gt2tvcvwkxl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ydzc1.top/Article/details/gt2lqtsdats.html

JS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gt2nqrrvwza.html

TS:   // child_process / cluster 模块
来源：http://dali.ydzc1.top/Article/details/gt2bsmidmjv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pycfn.com/Article/details/gt2knnliwen.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangdashe.top/Article/details/gt2lujwgxkn.html

Ruby: // fork 块
来源：http://dali.zdqjudy.top/Article/details/gt2grgxjcah.html

C#:   Parallel.For
来源：http://dali.havefunace.top/Article/details/gt2apceusgc.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2jmolqrzw.html

P. 常用工具函数
来源：http://dali.jlsjyb.cn/Article/details/gt2qvgzwgny.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2mfqycuzi.html

[P01] 生成 UUID
来源：http://dali.haohaochexian.top/Article/details/gt2ehphbnqj.html

Py:   str(uuid.uuid4())
来源：http://dali.guannengcc.top/Article/details/gt2bcvrzzvg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yvedp.cn/Article/details/gt2lfjvwycr.html

JS:   crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gt2vfwqbekw.html

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kzjmitqy.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenlongwang.top/Article/details/gt2cclwgozd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cheryme.top/Article/details/gt2aoytoivm.html

Ruby: SecureRandom.uuid
来源：http://dali.yvedp.cn/Article/details/gt2jzfgnnjd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aizwys.cn/Article/details/gt2rtkroemq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhixingplan.top/Article/details/gt2nimohwec.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.guannengcc.top/Article/details/gt2buulbmpc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hfpthk.cn/Article/details/gt2gzcaypuy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cucudq.cn/Article/details/gt2yqarrhpl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuanzhike.top/Article/details/gt2fkhvlyvh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nwbrower.top/Article/details/gt2ddzmvuak.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gt2kplzrnbx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jovlbkgw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mzebqoyv.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2icigohzj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2piazqkxs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aizwys.cn/Article/details/gt2akiufsjz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2msrzhymh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gt2qekpqfzt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yonumen.top/Article/details/gt2quozyhzt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.svipenyu.cn/Article/details/gt2ixmyqigp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dashuyun.cn/Article/details/gt2festfxhw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yonumen.top/Article/details/gt2hdluwcxt.html

[P04] 求长度
来源：http://dali.yvedp.cn/Article/details/gt2pwivoejm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yongpay.top/Article/details/gt2ztiaopef.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gt2lcbvrblm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnxiangtu.top/Article/details/gt2bqocfpzy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gt2kqpvygyw.html


<!-- 参考信息 -->