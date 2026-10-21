代发 wailian999

Py:   resp.json()
来源：http://dali.pycfn.com/Article/details/gtevfjkpgi.html

PHP:  json_decode($body, true);
来源：http://dali.yj202588.top/Article/details/gtiaqboowl.html

JS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gthtdbqidm.html

TS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtavtglhie.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jianghu66.top/Article/details/gtjevozslb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxuanxn.top/Article/details/gtxdoekfde.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgfzy.top/Article/details/gtdfqvbzsf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hfpthk.cn/Article/details/gtxiylocaw.html

[L07] 处理 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gtwuoesmht.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xylfe.cn/Article/details/gttmogargx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.bjfxy.top/Article/details/gtjtuygytu.html

JS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtbvfjiuer.html

TS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gtieggdjrg.html

Java: resp.statusCode()
来源：http://dali.sysykeji.top/Article/details/gtcfiibqgu.html

Go:   resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gtbyvznetn.html

Ruby: resp.code.to_i
来源：http://dali.yj202588.top/Article/details/gtvxdnzzrj.html

C#:   (int)resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtrwymppob.html

[L08] 并发请求多个地址
来源：http://dali.c1oappe.top/Article/details/gteysjahuq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sxryk.cn/Article/details/gteaxryauh.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhoulong.xyz/Article/details/gtkgghhgjv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtxtunqtam.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqtfsgty.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sweek.top/Article/details/gtkeqajiwv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jlsjyb.cn/Article/details/gtvgdqjqqh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sysykeji.top/Article/details/gtzdxvqmry.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jyoumei.cn/Article/details/gtvzwmyyhj.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtrjietnyb.html

M. 命令行 / 进程 / 环境
来源：http://dali.jyoumei.cn/Article/details/gtiwxwjlzc.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtwlrojlvq.html

[M01] 读取命令行参数
来源：http://dali.ivvv.top/Article/details/gthpgmiedh.html

Py:   sys.argv[1:]
来源：http://dali.mhx1999.top/Article/details/gtunbrfuiu.html

PHP:  $argv;  $argc;
来源：http://dali.bjfxy.top/Article/details/gtzajwmmmy.html

JS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtgyslofau.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtwmvrozeb.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtjnummlkq.html

Go:   os.Args[1:]
来源：http://dali.zhixingplan.top/Article/details/gtwdmxxypz.html

Ruby: ARGV
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgbcizuw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gtjrfuiqbm.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gtqrzhjhkc.html

Py:   os.environ.get("HOME")
来源：http://dali.jianghu66.top/Article/details/gtxdtyzvqj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtjdxwvpsp.html

JS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gtechelcqo.html

TS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gtloxqulha.html

Java: System.getenv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtrdabqary.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtsmjzfvcj.html

Ruby: ENV["HOME"]
来源：http://dali.yvedp.cn/Article/details/gtfvwcdtwo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtksivikca.html

[M03] 执行外部命令
来源：http://dali.cqqwz.cn/Article/details/gtymnpagaa.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jianghu66.top/Article/details/gtgttfqjrn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxinkj.top/Article/details/gtulengpkt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtqoszadds.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gtnjgnzllo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj202588.top/Article/details/gtbjynklub.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnqzz.top/Article/details/gtbmznpomw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fengsongda.top/Article/details/gtgbhkvrga.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gzhubu.top/Article/details/gtxypgcydr.html

[M04] 获取当前工作目录
来源：http://dali.xziqi.cn/Article/details/gtryhskfvu.html

Py:   os.getcwd()
来源：http://dali.guowangkeji.top/Article/details/gtqomnddlc.html

PHP:  getcwd();
来源：http://dali.zdqjudy.top/Article/details/gtopbqbtdk.html

JS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gtmufamdqy.html

TS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gtjbbngfmk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sysykeji.top/Article/details/gtkfalwxsc.html

Go:   os.Getwd()
来源：http://dali.hysaishi.cn/Article/details/gtazzcljcz.html

Ruby: Dir.pwd
来源：http://dali.gogol.net.cn/Article/details/gtkhuirdmz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhixingplan.top/Article/details/gtgskfdwff.html

[M05] 设置退出码
来源：http://dali.yj20258888.top/Article/details/gtaidfikrp.html

Py:   sys.exit(1)
来源：http://dali.birdmap.top/Article/details/gtqmifmpsq.html

PHP:  exit(1);
来源：http://dali.dianchejie.cn/Article/details/gtaxbzuusv.html

JS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gtwxpnpefg.html

TS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gtieemvcqi.html

Java: System.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqjosmxd.html

Go:   os.Exit(1)
来源：http://dali.c1oappe.top/Article/details/gtecmancew.html

Ruby: exit 1
来源：http://dali.gotoacloud.top/Article/details/gtzuqllkym.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.andypj.xyz/Article/details/gtvuoayzba.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gtftoosvra.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yangfankeji.com/Article/details/gtswxlcxxk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cqqwz.cn/Article/details/gteeiqfvvo.html

JS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gtkokdhhhx.html

TS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfevrzfvf.html

Java: System.err.println("err")
来源：http://dali.bjfxy.top/Article/details/gtartzppct.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jiagoushi.top/Article/details/gtfyhcypqe.html

Ruby: warn "err"
来源：http://dali.smart0.xyz/Article/details/gttspyqxcb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258.top/Article/details/gtpsjvywwo.html

[M07] 判断是否为主入口
来源：http://dali.quarkkingdee.top/Article/details/gtaxxfsxdl.html

Py:   if __name__ == "__main__":
来源：http://dali.yonumen.top/Article/details/gtwroxvgvs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgccswcu.html

JS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gtgtakzebt.html

TS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gtgukfzzlz.html

Java: public static void main(String[] args)
来源：http://dali.cqqwz.cn/Article/details/gtukjczcxf.html

Go:   func main()
来源：http://dali.daxiang520.top/Article/details/gtqnsmjatm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtandcoixu.html

C#:   static void Main(string[] args)
来源：http://dali.aibaodan.cn/Article/details/gtybqakmcl.html

[M08] 获取系统与运行时信息
来源：http://dali.snrcjt.cn/Article/details/gtgkxhebgo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tian-w.cn/Article/details/gtxsqqodfq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jiagoushi.top/Article/details/gtvvyfkxyo.html

JS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gtxujcalcu.html

TS:   process.platform;  process.version
来源：http://dali.xuanzx.com/Article/details/gtgbyvbist.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tianlin.xyz/Article/details/gtcrejvixg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yonumen.top/Article/details/gtrkzhaqrp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbazubxg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuanzx.com/Article/details/gtzwxnjwhr.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtaajfotoa.html

N. 数据结构与算法
来源：http://dali.hnqzz.top/Article/details/gtpsjvafrm.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtrojghgfq.html

[N01] 二分查找（有序数组）
来源：http://dali.fengsongda.top/Article/details/gtvcrxhpqs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlytytbkz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gttcisqret.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gtfoqssnse.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtbtswfhjj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtjisfiiyb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hammf.cn/Article/details/gtctebfmsx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sxryk.cn/Article/details/gtuazrvxaa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtunpkcyxj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxuanxn.top/Article/details/gthzxupddq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guannengcc.top/Article/details/gtbcadqwjm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.andypj.xyz/Article/details/gtypzobtrl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtorqeztio.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gtdivqfdsc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhongyouzk.top/Article/details/gtnszkbbjk.html

Go:   slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtbxfxkynm.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gttnbnelmr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xinyue.icu/Article/details/gtamiylpej.html

[N03] 快速排序（分治示例）
来源：http://dali.smart0.xyz/Article/details/gtrxyulhqs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigufen.top/Article/details/gtnfjzvtnd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxinkj.top/Article/details/gtrxfzpsyj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpzfqvxr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gtufifwpxo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigfzy.top/Article/details/gtglfhblrn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jyoumei.cn/Article/details/gtnwafgfpn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhengqikj.top/Article/details/gteezbbfte.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnfjardp.html

[N04] 斐波那契数列
来源：http://dali.yuanzhike.top/Article/details/gtdoyhjhkl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnxiangtu.top/Article/details/gtrmxyjobw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtzabpbadd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtxzvwbvae.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtjjogbzwo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.guannengcc.top/Article/details/gtvvzmwbkq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jiagoushi.top/Article/details/gtprcfdrdo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gtlpubkxhh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtxzvdgypf.html

[N05] 最大公约数
来源：http://dali.xinyue.icu/Article/details/gtcmtldxdo.html

Py:   math.gcd(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtzacvnsqi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xziqi.cn/Article/details/gtpnzuutwa.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvrfgvkpa.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xinyue.icu/Article/details/gtybzrtobl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hongshengwenyu.top/Article/details/gtjvttbqam.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hysaishi.cn/Article/details/gtnklyykln.html

Ruby: a.gcd(b)
来源：http://dali.hywenlv.cn/Article/details/gtwnldoouy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daxiang520.top/Article/details/gtrewdfzpn.html

[N06] 判断回文字符串
来源：http://dali.xinyue.icu/Article/details/gtlprpmiqe.html

Py:   s == s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gtcebuujaj.html

PHP:  $s === strrev($s);
来源：http://dali.sysykeji.top/Article/details/gtrnkaiqkk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gttfnbxclz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtyjsxsbrv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.andypj.xyz/Article/details/gtzydyhgfu.html

Go:   // 双指针从两端比较
来源：http://dali.snrcjt.cn/Article/details/gtxutvufcv.html

Ruby: s == s.reverse
来源：http://dali.guannengcc.top/Article/details/gtwvbzkorg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yueranfly.top/Article/details/gtfmijgtxh.html

[N07] 两数之和（返回下标）
来源：http://dali.smart0.xyz/Article/details/gtihnxbjwz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guowangkeji.top/Article/details/gtgoongimp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gogol.net.cn/Article/details/gtlprkrchf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuanzhike.top/Article/details/gtptmlgyus.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangdashe.top/Article/details/gtvnnrxcxb.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangtech.top/Article/details/gtiodbvdnp.html

Go:   // 手写 map[int]int
来源：http://dali.ehwqpu.com/Article/details/gttmwwujvo.html

Ruby: // 手写 Hash
来源：http://dali.wangshuangyany.cn/Article/details/gtxmxusgah.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhoulong.xyz/Article/details/gtivqdygai.html

[N08] 生成全排列
来源：http://dali.quarkkingdee.top/Article/details/gtcmpknocq.html

Py:   itertools.permutations(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtmiradqsw.html

PHP:  // 手写递归交换
来源：http://dali.xziqi.cn/Article/details/gtdfhjubdd.html

JS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtxojxozoq.html

TS:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtaqznrsht.html

Java: // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtmjqlbpcu.html

Go:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtkvitmrac.html

Ruby: arr.permutation.to_a
来源：http://dali.ehwqpu.com/Article/details/gtkixeovfx.html

C#:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtnmttzkwn.html

[N09] 栈与队列
来源：http://dali.gaohongyu789.top/Article/details/gtbliazzsf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sxryk.cn/Article/details/gtjpvkpdxb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pycfn.com/Article/details/gtpabyqmhn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtkeaiwukr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sxryk.cn/Article/details/gtmhhduziu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.kuanghao11.cn/Article/details/gtxyvvfjsk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zdqjudy.top/Article/details/gtduadstkx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gtdsiqruca.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cashguo.top/Article/details/gtgvpfckac.html

[N10] 链表节点定义
来源：http://dali.cucudq.cn/Article/details/gtukflhwfg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daria6918.cn/Article/details/gtoisuxsdi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258888.top/Article/details/gtrnlkylns.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tianlin.xyz/Article/details/gtenvntzll.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhixingplan.top/Article/details/gttikswwvr.html

Java: class Node { int v; Node next; }
来源：http://dali.hnqzz.top/Article/details/gtwycuqeer.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jlsjyb.cn/Article/details/gthoskrrir.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dashuyun.cn/Article/details/gtmuiulwiu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.guowangkeji.top/Article/details/gtjxxmbcyy.html

[N11] 二叉树中序遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtousfoidm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjzxwezb.html

PHP:  // 手写递归函数
来源：http://dali.dashuyun.cn/Article/details/gtrhaxmbnb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fengsongda.top/Article/details/gthdyxmzzq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuanzx.com/Article/details/gtmpjryyuq.html

Java: // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gtvijfitxm.html

Go:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtmgzylwcy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.quarkkingdee.top/Article/details/gtmxcfxkuu.html

C#:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gtxqiwaadr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gthfqkfaer.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shuidangran.top/Article/details/gtxayrlezd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sxryk.cn/Article/details/gthprkjwwx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtlvnmhfza.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtxgrrnxxz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gtncijukyl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yvedp.cn/Article/details/gtyqqhjlrx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenjidiqi.icu/Article/details/gtogjpxjgr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gtoiugllpl.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtynllszqb.html

O. 并发与异步
来源：http://dali.aizwys.cn/Article/details/gtovzevjxa.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtdrjtecdp.html

[O01] 启动一个线程
来源：http://dali.bjfxy.top/Article/details/gtfzqryaha.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ehwqpu.com/Article/details/gtufwukkov.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ppjwa.cn/Article/details/gtrgebumfm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.dashuyun.cn/Article/details/gtpbfzgmfa.html

TS:   // 同 JS
来源：http://dali.mhx1999.top/Article/details/gtbznwxgjf.html

Java: new Thread(() -> f()).start()
来源：http://dali.shuidangran.top/Article/details/gtqoajaver.html

Go:   go f()
来源：http://dali.jqgfzy.top/Article/details/gthebmkzox.html

Ruby: Thread.new { f }
来源：http://dali.ydzc1.top/Article/details/gtjtjxdiua.html

C#:   Task.Run(() => F());
来源：http://dali.jianghu66.top/Article/details/gtaxqmdppf.html

[O02] 使用线程池
来源：http://dali.nanxuanxn.top/Article/details/gttutqvobm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aizwys.cn/Article/details/gtlrpzrvhi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yangfankeji.com/Article/details/gtcycdvjge.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gtghkakfjb.html

TS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gtfdcafgsk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hongshengwenyu.top/Article/details/gtkabrxnbv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cdnleiting.top/Article/details/gtupxgeshd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcdriyzy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhiwuduotai.top/Article/details/gtxvvwjnlg.html

[O03] 加锁保护共享数据
来源：http://dali.svipenyu.cn/Article/details/gtrrbgenbf.html

Py:   with lock: shared += 1
来源：http://dali.hammf.cn/Article/details/gtxswuenwv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinghuilouyu.cn/Article/details/gtpanekqce.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgufenzy.top/Article/details/gtuebhjtoi.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gtzlibdjhq.html

Java: synchronized (this) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gtnejcluif.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.0kj1m.cn/Article/details/gtpumzzjcn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnqzz.top/Article/details/gtztsgjgvq.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gtqcixecrx.html

[O04] 定义异步函数并等待
来源：http://dali.chenzaomai.com/Article/details/gtlibevdnv.html

Py:   async def f():⏎    await g()
来源：http://dali.gzhubu.top/Article/details/gtqqlyppso.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cqqwz.cn/Article/details/gtcrwabnbu.html

JS:   async function f() { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gtazmcechs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xziqi.cn/Article/details/gtzibrwnke.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fengsongda.top/Article/details/gtmgxeraee.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jiagoushi.top/Article/details/gtrfutqywk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgfzy.top/Article/details/gtockrfatm.html

C#:   async Task F() { await G(); }
来源：http://dali.ydzc1.top/Article/details/gtxbckimpb.html

[O05] 并发执行并等待全部完成
来源：http://dali.ivvv.top/Article/details/gttzgvdmsy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhengqikj.top/Article/details/gtlqptdnoi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ppjwa.cn/Article/details/gtkunhpcjd.html

JS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gthnuaegeq.html

TS:   await Promise.all(tasks)
来源：http://dali.fengsongda.top/Article/details/gtuvmvwmlb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhixingplan.top/Article/details/gtrqeftuuy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinqigufen.top/Article/details/gtgbrgzrsb.html

Ruby: threads.map(&:join)
来源：http://dali.birdmap.top/Article/details/gtrvtpxtsx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nanxuanxn.top/Article/details/gtyzrwayqg.html

[O06] 使用进程池
来源：http://dali.guannengcc.top/Article/details/gtfrvxqvls.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ydzc1.top/Article/details/gtvcxxgshs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ehwqpu.com/Article/details/gtefqhtsxd.html

JS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gtxbazlcjh.html

TS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gtapgzilzw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hysaishi.cn/Article/details/gtsxbuxmls.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xuetiantiany.cn/Article/details/gtlbgvjmru.html

Ruby: // fork 块
来源：http://dali.aibaodan.cn/Article/details/gtcssqkncv.html

C#:   Parallel.For
来源：http://dali.xylfe.cn/Article/details/gtpbidjvih.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtvapaoufy.html

P. 常用工具函数
来源：http://dali.zhiwuduotai.top/Article/details/gtytslolrv.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtldvowrpi.html

[P01] 生成 UUID
来源：http://dali.quarkkingdee.top/Article/details/gtkowxufuk.html

Py:   str(uuid.uuid4())
来源：http://dali.xinyue.icu/Article/details/gtocrfdffz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfdxjhct.html

JS:   crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gtwsserkvf.html

TS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtpvedywmk.html

Java: UUID.randomUUID().toString()
来源：http://dali.guannengcc.top/Article/details/gtxwzfcray.html

Go:   // 用 github.com/google/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtagsjplcz.html

Ruby: SecureRandom.uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gtndmziblj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dashuyun.cn/Article/details/gtgllnahpe.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigfzy.top/Article/details/gtpejczrcn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sxryk.cn/Article/details/gtqspqtwdz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yonumen.top/Article/details/gtimycmdat.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yongpay.top/Article/details/gtkyhjxftk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tian-w.cn/Article/details/gtoyzviqus.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gtfqhyxbuq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.316326.xyz/Article/details/gtxtrclbve.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.kuanghao11.cn/Article/details/gtypkkdmff.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cucudq.cn/Article/details/gttfvwfbea.html

[P03] 生成短随机字符串
来源：http://dali.nwbrower.top/Article/details/gtensnpasd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangshuangyany.cn/Article/details/gtjszcbgqm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yangfankeji.com/Article/details/gthnslbiyw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshcrgbel.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gtyerugrry.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsmykcoa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aizwys.cn/Article/details/gtjwocmtbd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cqqwz.cn/Article/details/gtbmqssnqy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgufenzy.top/Article/details/gtxafeyqpt.html

[P04] 求长度
来源：http://dali.tianlin.xyz/Article/details/gtprsfiyfg.html


<!-- 参考信息 -->