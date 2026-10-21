代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtgvucyjgv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangshuangyany.cn/Article/details/gtxrhdbabr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cheryme.top/Article/details/gtwbchmblh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yangfankeji.com/Article/details/gttcuypdbq.html

[L07] 处理 HTTP 状态码
来源：http://dali.ppjwa.cn/Article/details/gtjbgkrcey.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dianchejie.cn/Article/details/gtzvsbddog.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtndjvimit.html

JS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtbyweyqmt.html

TS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttxlufhr.html

Java: resp.statusCode()
来源：http://dali.kuanghao11.cn/Article/details/gtlctggkmh.html

Go:   resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gtlyponbmw.html

Ruby: resp.code.to_i
来源：http://dali.hfpthk.cn/Article/details/gtavlyvbzg.html

C#:   (int)resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gtrxrmwiyx.html

[L08] 并发请求多个地址
来源：http://dali.jinqigufen.top/Article/details/gtuqvninqe.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cashguo.top/Article/details/gtxfhustzq.html

PHP:  curl_multi_init() 系列
来源：http://dali.fzhhl.top/Article/details/gtzvmbhigg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtanwcbdxv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtsukctlpn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuxming.cn/Article/details/gtwjgbweyc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangtech.top/Article/details/gtstapyhkt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhengqikj.top/Article/details/gtilihiegy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258.top/Article/details/gtrhemyqyx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtrcoprauq.html

M. 命令行 / 进程 / 环境
来源：http://dali.tian-w.cn/Article/details/gtmonrkkdr.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtevntoncc.html

[M01] 读取命令行参数
来源：http://dali.yj20258888.top/Article/details/gtnksuppbz.html

Py:   sys.argv[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gtywrrreoy.html

PHP:  $argv;  $argc;
来源：http://dali.nanxinkj.top/Article/details/gtaaviqtbn.html

JS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gtjflsybri.html

TS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtnudfnict.html

Java: args 数组（main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gtvaraetar.html

Go:   os.Args[1:]
来源：http://dali.tanke756.top/Article/details/gtosngulfs.html

Ruby: ARGV
来源：http://dali.hammf.cn/Article/details/gtszrgxpcj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gthswvtxei.html

[M02] 读取环境变量
来源：http://dali.hywenlv.cn/Article/details/gtyjrcrhot.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtpmdpepni.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdyxsdave.html

JS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gtbsijqtxz.html

TS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gtsybuaxix.html

Java: System.getenv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtkutvllqw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zdqjudy.top/Article/details/gttdckesdu.html

Ruby: ENV["HOME"]
来源：http://dali.redwolf501.top/Article/details/gtaczlgpvt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.iojbl.cn/Article/details/gtvtvqsbil.html

[M03] 执行外部命令
来源：http://dali.jyoumei.cn/Article/details/gtxbjhxgnh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtlaqdkesv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aibaodan.cn/Article/details/gtcvehypza.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtdyrncprw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gthzylowll.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuanzhike.top/Article/details/gtveibvxgg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.c1oappe.top/Article/details/gtyijlinla.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxinkj.top/Article/details/gteajxjkwc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.c1oappe.top/Article/details/gtfijhnbzv.html

[M04] 获取当前工作目录
来源：http://dali.gzhubu.top/Article/details/gtvrhbemww.html

Py:   os.getcwd()
来源：http://dali.yuxming.cn/Article/details/gtswwwdzpc.html

PHP:  getcwd();
来源：http://dali.nanxinkj.top/Article/details/gtknsljhlq.html

JS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gtosgxrxna.html

TS:   process.cwd()
来源：http://dali.svipenyu.cn/Article/details/gtrkploati.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daria6918.cn/Article/details/gtwcyjiubv.html

Go:   os.Getwd()
来源：http://dali.pycfn.com/Article/details/gtuncblxic.html

Ruby: Dir.pwd
来源：http://dali.yuanzhike.top/Article/details/gtjzyntrtp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gtptcgpegs.html

[M05] 设置退出码
来源：http://dali.shuidangran.top/Article/details/gtgbiuzaqq.html

Py:   sys.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtinailqdx.html

PHP:  exit(1);
来源：http://dali.chenzaomai.com/Article/details/gtfxnptbgv.html

JS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtiljxqbbo.html

TS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtombektoq.html

Java: System.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtcrwyrvjf.html

Go:   os.Exit(1)
来源：http://dali.wangdashe.top/Article/details/gtluadalwt.html

Ruby: exit 1
来源：http://dali.shangyingyoupin.top/Article/details/gtlryenuqv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.pycfn.com/Article/details/gtwugvbche.html

[M06] 向标准错误输出
来源：http://dali.jqgufenzy.top/Article/details/gtkcazpaof.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pengpengdd.cyou/Article/details/gtximxoayz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuanzhike.top/Article/details/gtuomgmhlv.html

JS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gtcafsauop.html

TS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gtjrogmfke.html

Java: System.err.println("err")
来源：http://dali.cucudq.cn/Article/details/gtpqlaxpbb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dashuyun.cn/Article/details/gtvvqsspbl.html

Ruby: warn "err"
来源：http://dali.ivvv.top/Article/details/gtcbctodef.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.0kj1m.cn/Article/details/gtagwfyblj.html

[M07] 判断是否为主入口
来源：http://dali.pycfn.com/Article/details/gtpoxuscos.html

Py:   if __name__ == "__main__":
来源：http://dali.dashuyun.cn/Article/details/gtisxbgtje.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ybcxt.top/Article/details/gteuqtfwzr.html

JS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gtcllcgsrp.html

TS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gtbhkbalkq.html

Java: public static void main(String[] args)
来源：http://dali.hfpthk.cn/Article/details/gtqrkjvark.html

Go:   func main()
来源：http://dali.c1oappe.top/Article/details/gtumpcrsmj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuanzx.com/Article/details/gtityoygmw.html

C#:   static void Main(string[] args)
来源：http://dali.tanke756.top/Article/details/gtsmgoxmbj.html

[M08] 获取系统与运行时信息
来源：http://dali.316326.xyz/Article/details/gtronccfoc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ydzc1.top/Article/details/gtornifezz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.birdmap.top/Article/details/gtwirgxjqh.html

JS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtgeuofvyd.html

TS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gteqvealcr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.bjfxy.top/Article/details/gtnsouqrpe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zdqjudy.top/Article/details/gtilggretv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.vqdsnc.cn/Article/details/gtnrokmpbr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dashuyun.cn/Article/details/gtefjdvkqg.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtfssvzgrs.html

N. 数据结构与算法
来源：http://dali.tianlin.xyz/Article/details/gtaxmuncyj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtjhmsoeuz.html

[N01] 二分查找（有序数组）
来源：http://dali.cashguo.top/Article/details/gtbzsxmymf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtlaxiyrcq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tian-w.cn/Article/details/gtlkerznae.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gthoslfcta.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtjarzjlqg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtcbqjnvwi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtcgdonaka.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dashuyun.cn/Article/details/gtqywzyhua.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gthoaiapju.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenlongwang.top/Article/details/gtnnazvyqi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gtgddyxnpx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ehwqpu.com/Article/details/gtggeuqvfq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gtvlrkegde.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gthyqsullz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sxryk.cn/Article/details/gtdnkxoxjr.html

Go:   slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gtoeprtdox.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gthrhwsbbb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.quarkkingdee.top/Article/details/gtkpxbdvui.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxuanxn.top/Article/details/gtmljyyotw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.birdmap.top/Article/details/gtidmokbmm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhengqikj.top/Article/details/gtfrzouzno.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gtlajzlakf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gtbathwvlb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.haohaochexian.top/Article/details/gthlsdwuta.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hysaishi.cn/Article/details/gtieymhpwm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangtech.top/Article/details/gtcinzmzfu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.snrcjt.cn/Article/details/gtzkozpurp.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxthptkhl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gtnmolnbii.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtanovfvhf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtaixsiqcj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gtcetamjyy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yonumen.top/Article/details/gtdwmgurhn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenzaomai.com/Article/details/gtonbapvkr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gtaiphgcqp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtrewjhjul.html

[N05] 最大公约数
来源：http://dali.yuxming.cn/Article/details/gtjdfjjafo.html

Py:   math.gcd(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtxdesjows.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxgvmwlvz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtssoyinkf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gtxxgvibsk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.snrcjt.cn/Article/details/gtfbtqpxzy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigufen.top/Article/details/gtlimukbdr.html

Ruby: a.gcd(b)
来源：http://dali.tanke756.top/Article/details/gtlvthdmuj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hfpthk.cn/Article/details/gtidzukbim.html

[N06] 判断回文字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvypmpbf.html

Py:   s == s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gtpjbqrpei.html

PHP:  $s === strrev($s);
来源：http://dali.tanke756.top/Article/details/gtwllzwnxb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtsgetoyct.html

TS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtezczzpez.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gtfgcsgfmi.html

Go:   // 双指针从两端比较
来源：http://dali.mhx1999.top/Article/details/gtvnpszlhq.html

Ruby: s == s.reverse
来源：http://dali.cucudq.cn/Article/details/gtgbyoxyko.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gtdlwtlyym.html

[N07] 两数之和（返回下标）
来源：http://dali.ppjwa.cn/Article/details/gtaigecknf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jlsjyb.cn/Article/details/gthgipxtbv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nwbrower.top/Article/details/gtkopieguf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sweek.top/Article/details/gtvtpdsnyh.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenjidiqi.icu/Article/details/gttmhwqpad.html

Java: // 手写 HashMap
来源：http://dali.xuetiantiany.cn/Article/details/gtlpxtovuy.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258.top/Article/details/gtivkuvcoa.html

Ruby: // 手写 Hash
来源：http://dali.zhixingplan.top/Article/details/gtweklyggn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sxryk.cn/Article/details/gtziadfgui.html

[N08] 生成全排列
来源：http://dali.dashuyun.cn/Article/details/gtfrhisxbg.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgfzy.top/Article/details/gtphiziamn.html

PHP:  // 手写递归交换
来源：http://dali.tanke756.top/Article/details/gtohmjldir.html

JS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxvhsaak.html

TS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtpkyvqwkh.html

Java: // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtobolqidx.html

Go:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtdrvftkrd.html

Ruby: arr.permutation.to_a
来源：http://dali.sufxvd.cn/Article/details/gtcqeaybla.html

C#:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtcybjrfse.html

[N09] 栈与队列
来源：http://dali.jianghu66.top/Article/details/gtwhuwvfde.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftopxwtu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtwzlqswjl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtzhizpaqn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuetiantiany.cn/Article/details/gttvgulfmv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dianchejie.cn/Article/details/gtflvdaxdp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hysaishi.cn/Article/details/gtprqnhbfg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gtfztgyrji.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nwbrower.top/Article/details/gtecxpnnqj.html

[N10] 链表节点定义
来源：http://dali.zhixingplan.top/Article/details/gtnldkkktd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuetiantiany.cn/Article/details/gtnpafydso.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.kuanghao11.cn/Article/details/gtoutcfpea.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj202588.top/Article/details/gtwjzptmhw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cqqwz.cn/Article/details/gtuuxzlaor.html

Java: class Node { int v; Node next; }
来源：http://dali.dashuyun.cn/Article/details/gtlbjftevn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.redwolf501.top/Article/details/gtaliagtrp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tanke756.top/Article/details/gtmurfdgih.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.9152youxi.cn/Article/details/gtvqamwgik.html

[N11] 二叉树中序遍历
来源：http://dali.zhixingplan.top/Article/details/gtzdrtngrm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xylfe.cn/Article/details/gtkbgjqrkl.html

PHP:  // 手写递归函数
来源：http://dali.fzhhl.top/Article/details/gtvkmyrodg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gtjatfueyw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtssozyrdx.html

Java: // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtdxdoklyd.html

Go:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gtrcyggdsr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tanke756.top/Article/details/gtrhaebgph.html

C#:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtjujkmuwp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ydzc1.top/Article/details/gtdjcjlsuc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cashguo.top/Article/details/gtmfbwgjal.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tianlin.xyz/Article/details/gtenostyuz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gtkoohcjuv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gtcewsxtcs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtjuhciomn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhongyouzk.top/Article/details/gtldpbxcac.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yvedp.cn/Article/details/gtidmikeor.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gtteeeuszo.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtqycbvmmx.html

O. 并发与异步
来源：http://dali.iojbl.cn/Article/details/gtccecwjcn.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtmdlljhgc.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gtpcxodnna.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guowangkeji.top/Article/details/gtqxblgorp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhixingplan.top/Article/details/gtnllnmodf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yueranfly.top/Article/details/gtvjmgfnvz.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gtxnmqmtnt.html

Java: new Thread(() -> f()).start()
来源：http://dali.hywenlv.cn/Article/details/gtybozgmzr.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gtykrddkbs.html

Ruby: Thread.new { f }
来源：http://dali.yanxiufei.cn/Article/details/gtngtnurht.html

C#:   Task.Run(() => F());
来源：http://dali.quarkkingdee.top/Article/details/gtfqmfnmih.html

[O02] 使用线程池
来源：http://dali.xylfe.cn/Article/details/gtqsknbrlc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tanke756.top/Article/details/gtnsmgfain.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yanxiufei.cn/Article/details/gthlksislb.html

JS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gthbpdpsod.html

TS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gteuvualyx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.redwolf501.top/Article/details/gtglmzmqar.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuanzhike.top/Article/details/gttgncytyq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhixingplan.top/Article/details/gtucujyvye.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gogol.net.cn/Article/details/gtiucxydpo.html

[O03] 加锁保护共享数据
来源：http://dali.zhiwuduotai.top/Article/details/gtobrrtabk.html

Py:   with lock: shared += 1
来源：http://dali.cucudq.cn/Article/details/gtshcmdndp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.smart0.xyz/Article/details/gtjrqyvwqc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nwbrower.top/Article/details/gtlmabpsdu.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gtawnpxegi.html

Java: synchronized (this) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gtabfebfih.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gzhubu.top/Article/details/gtiggefoic.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cdnleiting.top/Article/details/gtyeanikvj.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gtregcxbon.html

[O04] 定义异步函数并等待
来源：http://dali.yuanzhike.top/Article/details/gthmmkfjyb.html

Py:   async def f():⏎    await g()
来源：http://dali.yongpay.top/Article/details/gtbacfqjue.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.iojbl.cn/Article/details/gtopcuubny.html

JS:   async function f() { await g(); }
来源：http://dali.bjfxy.top/Article/details/gtaqobyqwn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.daria6918.cn/Article/details/gtqdinyehh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgosjogp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gtaaumvukx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jiagoushi.top/Article/details/gtmjcidcke.html

C#:   async Task F() { await G(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelfnvukc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhixingplan.top/Article/details/gtdudzilsi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xinyue.icu/Article/details/gtmngbkgbw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinqigufen.top/Article/details/gtrvenzzot.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gtevpwzuhu.html

TS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gtrtmyyqsq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sysykeji.top/Article/details/gtjcuuixdf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.havefunace.top/Article/details/gtavbiopbo.html

Ruby: threads.map(&:join)
来源：http://dali.andypj.xyz/Article/details/gtrihcbpfe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.meibo888.top/Article/details/gthmmohvvm.html

[O06] 使用进程池
来源：http://dali.yangfankeji.com/Article/details/gthifoantc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgufenzy.top/Article/details/gtcvrdlodu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cheryme.top/Article/details/gtljsusdhx.html

JS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gtyvudqmfo.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxuanxn.top/Article/details/gtzshnrbnw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gotoacloud.top/Article/details/gtqbhrctbo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxinkj.top/Article/details/gtxetcusvg.html

Ruby: // fork 块
来源：http://dali.zycfv.cn/Article/details/gtgjcoueqj.html

C#:   Parallel.For
来源：http://dali.sufxvd.cn/Article/details/gtoknxbzpa.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtkttqavzf.html

P. 常用工具函数
来源：http://dali.hammf.cn/Article/details/gtlsgtuhyq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtxrgtsnml.html

[P01] 生成 UUID
来源：http://dali.daria6918.cn/Article/details/gtvxtzbpag.html

Py:   str(uuid.uuid4())
来源：http://dali.cdnleiting.top/Article/details/gtagfxzncr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ivvv.top/Article/details/gtwzjszprm.html

JS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gtahcusjah.html

TS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtwujaujyd.html

Java: UUID.randomUUID().toString()
来源：http://dali.daxiang520.top/Article/details/gthyalkfwp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.aizwys.cn/Article/details/gtbtcrzsyb.html

Ruby: SecureRandom.uuid
来源：http://dali.gotoacloud.top/Article/details/gtmhlnkcyu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guannengcc.top/Article/details/gtfesjvcif.html

[P02] MD5 / SHA256 摘要
来源：http://dali.aibaodan.cn/Article/details/gthwreeisc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jianghu66.top/Article/details/gtylxvpxxq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fengsongda.top/Article/details/gtthlckhno.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xylfe.cn/Article/details/gtwgfonxlc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guannengcc.top/Article/details/gtgugnrsui.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yueranfly.top/Article/details/gtkeajbvxv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangdashe.top/Article/details/gtcjqdjspa.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gaohongyu789.top/Article/details/gtwgnbumcd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.0kj1m.cn/Article/details/gtyhzfkcpb.html

[P03] 生成短随机字符串
来源：http://dali.ivvv.top/Article/details/gtbpikjyzq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxuanxn.top/Article/details/gtiltmfrcu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.birdmap.top/Article/details/gtpjmgialn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gthgcypwae.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gtdfrxtloe.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pycfn.com/Article/details/gtmlvmhmcy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhiwuduotai.top/Article/details/gtuulaumun.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.aizwys.cn/Article/details/gtqzbfrvew.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.quarkkingdee.top/Article/details/gtfupkropc.html

[P04] 求长度
来源：http://dali.yj20258888.top/Article/details/gtjbosflix.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258.top/Article/details/gtpiwaxeyy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtafwsdcyv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gtowkkqrxg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258.top/Article/details/gtqsrkwuhh.html


<!-- 参考信息 -->