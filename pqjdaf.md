代发 wailian999

Py:   resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtjvcldthq.html

PHP:  json_decode($body, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtdcbcyfyp.html

JS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtoqhituga.html

TS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gtnfiqbscr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtxkoqiojc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj202588.top/Article/details/gtbqqqssbn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cdnleiting.top/Article/details/gtyxcoroio.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tanke756.top/Article/details/gtunpzfgro.html

[L07] 处理 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gtevydmilq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuetiantiany.cn/Article/details/gtayxsuwxo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhengqikj.top/Article/details/gtjhrcidlk.html

JS:   resp.ok;  resp.status
来源：http://dali.sufxvd.cn/Article/details/gtohuyystr.html

TS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtwvacobpy.html

Java: resp.statusCode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjlugtqs.html

Go:   resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gtkavflwlc.html

Ruby: resp.code.to_i
来源：http://dali.yj202588.top/Article/details/gtiatrqjfp.html

C#:   (int)resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gtyzpfeymv.html

[L08] 并发请求多个地址
来源：http://dali.cheryme.top/Article/details/gtzjevwvhl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cdnleiting.top/Article/details/gtygroljdm.html

PHP:  curl_multi_init() 系列
来源：http://dali.sufxvd.cn/Article/details/gtlfhnkhhn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gtalbqvrre.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtctwumrqx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.kuanghao11.cn/Article/details/gtfbyvdhyj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jyoumei.cn/Article/details/gtyuwbsafj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gtggswthbe.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.bjfxy.top/Article/details/gtefvnrzcx.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtmsbxdfkk.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangshuangyany.cn/Article/details/gtkotudebt.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gttbkpwcsk.html

[M01] 读取命令行参数
来源：http://dali.yj20258.top/Article/details/gtnrnsgwjd.html

Py:   sys.argv[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtmdwzelzp.html

PHP:  $argv;  $argc;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjpofsavn.html

JS:   process.argv.slice(2)
来源：http://dali.xuanzx.com/Article/details/gtyurysmyt.html

TS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtrnnleveu.html

Java: args 数组（main 方法参数）
来源：http://dali.havefunace.top/Article/details/gtjakfunrw.html

Go:   os.Args[1:]
来源：http://dali.nanxuanxn.top/Article/details/gtiubpwwfq.html

Ruby: ARGV
来源：http://dali.jyoumei.cn/Article/details/gtnnkpurgz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gtlgfvqysm.html

[M02] 读取环境变量
来源：http://dali.redwolf501.top/Article/details/gtbhozkmki.html

Py:   os.environ.get("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtpspfnhgd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gtdlkiwzul.html

JS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gtppigitlk.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtntwdgcmj.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtbwrdbqjl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjuqonzmy.html

Ruby: ENV["HOME"]
来源：http://dali.hnqzz.top/Article/details/gtyaxerwzn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtvqcjqydh.html

[M03] 执行外部命令
来源：http://dali.chenlongwang.top/Article/details/gtnxkymrdf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtujrfdphi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnqzz.top/Article/details/gttnrbojaz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqjbtccq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gtphysooad.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigfzy.top/Article/details/gtxpujaicw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sweek.top/Article/details/gtobvmgdvv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guannengcc.top/Article/details/gtxsardknl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj202588.top/Article/details/gtnsoeeppo.html

[M04] 获取当前工作目录
来源：http://dali.cheryme.top/Article/details/gtrqcllwtw.html

Py:   os.getcwd()
来源：http://dali.zhixingplan.top/Article/details/gtufuatbfu.html

PHP:  getcwd();
来源：http://dali.xinyue.icu/Article/details/gtjdpxqtvw.html

JS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtgrqnzahc.html

TS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtjtqzbkdm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gotoacloud.top/Article/details/gtwhghkdxj.html

Go:   os.Getwd()
来源：http://dali.fengsongda.top/Article/details/gtqgerdcor.html

Ruby: Dir.pwd
来源：http://dali.fzhhl.top/Article/details/gtlwfltave.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aizwys.cn/Article/details/gtaptlxelk.html

[M05] 设置退出码
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvqgriuq.html

Py:   sys.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtfesqenrh.html

PHP:  exit(1);
来源：http://dali.ivvv.top/Article/details/gtsvigsbsg.html

JS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtotazjsri.html

TS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtvwicfenc.html

Java: System.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtnzhwjxcw.html

Go:   os.Exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtovclffub.html

Ruby: exit 1
来源：http://dali.yj202588.top/Article/details/gtejfsyrmh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnqzz.top/Article/details/gtrskgtrcp.html

[M06] 向标准错误输出
来源：http://dali.daria6918.cn/Article/details/gtpuuxhgta.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tian-w.cn/Article/details/gtdcswgdkf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.meibo888.top/Article/details/gtflstnahc.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtgakcjamm.html

TS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gtovvknitj.html

Java: System.err.println("err")
来源：http://dali.hywenlv.cn/Article/details/gtdcmupmov.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gaohongyu789.top/Article/details/gtfewwnwxs.html

Ruby: warn "err"
来源：http://dali.mhx1999.top/Article/details/gtvosfiyni.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenlongwang.top/Article/details/gtkafxnvvy.html

[M07] 判断是否为主入口
来源：http://dali.hysaishi.cn/Article/details/gtvuyosmoe.html

Py:   if __name__ == "__main__":
来源：http://dali.hnxiangtu.top/Article/details/gtqblbqupy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zdqjudy.top/Article/details/gtaltkrtfy.html

JS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gtdglzroff.html

TS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gtqhidkppo.html

Java: public static void main(String[] args)
来源：http://dali.chenzaomai.com/Article/details/gtoiebldel.html

Go:   func main()
来源：http://dali.jinqigufen.top/Article/details/gtiiahqwim.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.316326.xyz/Article/details/gtceiirmvc.html

C#:   static void Main(string[] args)
来源：http://dali.yvedp.cn/Article/details/gthafeducd.html

[M08] 获取系统与运行时信息
来源：http://dali.zhoulong.xyz/Article/details/gtudrskdnl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guowangkeji.top/Article/details/gtecepsqif.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuanzx.com/Article/details/gtbfbssvpy.html

JS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gttenywpav.html

TS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gtplozqpgw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pengpengdd.cyou/Article/details/gtsxuivdtt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhixingplan.top/Article/details/gtspiluoym.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhengqikj.top/Article/details/gtnoefuzir.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangtech.top/Article/details/gtzovakzmw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtbhkjovsj.html

N. 数据结构与算法
来源：http://dali.sufxvd.cn/Article/details/gtveyebjqe.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtbaxlobsc.html

[N01] 二分查找（有序数组）
来源：http://dali.tanke756.top/Article/details/gtnmjsysrw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtwlpgpqvq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gtpoelyosd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtarjdtfta.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtafymuiba.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtplmvujjy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtmpogvkvp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xziqi.cn/Article/details/gtyzgvpvwd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtwmjtfajq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.fzhhl.top/Article/details/gteuqeoasz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guannengcc.top/Article/details/gtxvphleyc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.birdmap.top/Article/details/gtkwraipte.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gtvfwmzdzc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtmfrlqraf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuettsiri.html

Go:   slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gtomeixexq.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gtgaulfvpq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenzaomai.com/Article/details/gtsxujlyod.html

[N03] 快速排序（分治示例）
来源：http://dali.daria6918.cn/Article/details/gtpgtkjxsb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aizwys.cn/Article/details/gtprzbisao.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhengqikj.top/Article/details/gtcsearyda.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gtnsokzzch.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gtdltdchrp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtyxtyhdxj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yongpay.top/Article/details/gtpuytwfxb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shzxlz.cn/Article/details/gtqvaldkyx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.9152youxi.cn/Article/details/gtppvjqsva.html

[N04] 斐波那契数列
来源：http://dali.aizwys.cn/Article/details/gtjrbnwcun.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzbrwila.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hammf.cn/Article/details/gtxhqmijbf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gthxkehinh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtqsagwwlo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gthnzpsglt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dianchejie.cn/Article/details/gtzxdsixng.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gtjkrdchqy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gtibbezkml.html

[N05] 最大公约数
来源：http://dali.haohaochexian.top/Article/details/gtbhlhattd.html

Py:   math.gcd(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtxclhdvin.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgufenzy.top/Article/details/gtkkozitke.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gtftodcuru.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gttbcnggtr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cheryme.top/Article/details/gtfeigkwlq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuxming.cn/Article/details/gtmdebrlzs.html

Ruby: a.gcd(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtxottiuar.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigufen.top/Article/details/gtukzkqnvl.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqlradur.html

Py:   s == s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gtcljourda.html

PHP:  $s === strrev($s);
来源：http://dali.yonumen.top/Article/details/gtuugcqrvl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtkcmbjcze.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtecrrmxze.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxpyyiyj.html

Go:   // 双指针从两端比较
来源：http://dali.nwbrower.top/Article/details/gtqtenhwxq.html

Ruby: s == s.reverse
来源：http://dali.0kj1m.cn/Article/details/gtuecoktny.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gtdkgspljr.html

[N07] 两数之和（返回下标）
来源：http://dali.gotoacloud.top/Article/details/gtpdjekihc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yanxiufei.cn/Article/details/gtiyrzdtjf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.feifeiyinyue.top/Article/details/gtrbjsjvpg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pengpengdd.cyou/Article/details/gthsinzwku.html

TS:   // 手写 Map<string, number>
来源：http://dali.hywenlv.cn/Article/details/gtdscnvsnn.html

Java: // 手写 HashMap
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjpuuzpz.html

Go:   // 手写 map[int]int
来源：http://dali.meibo888.top/Article/details/gtjbowptql.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gtfbrhktdp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhengqikj.top/Article/details/gtwommbuwj.html

[N08] 生成全排列
来源：http://dali.iojbl.cn/Article/details/gtykncuplw.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtebqsngth.html

PHP:  // 手写递归交换
来源：http://dali.nwbrower.top/Article/details/gtdevzrxcw.html

JS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyycgginy.html

TS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtklhriran.html

Java: // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtcnyqnruc.html

Go:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtbkacnwah.html

Ruby: arr.permutation.to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjrvspkq.html

C#:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtvldonxdc.html

[N09] 栈与队列
来源：http://dali.zhixingplan.top/Article/details/gtzrgygokf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dashuyun.cn/Article/details/gtdjevooju.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtcwqucenz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtqdahwmdf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fzhhl.top/Article/details/gtrqnzqxlp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yueranfly.top/Article/details/gtqonizhmg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenlongwang.top/Article/details/gtffehgqxj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gtfxkgnwra.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tanke756.top/Article/details/gtiutdkcsv.html

[N10] 链表节点定义
来源：http://dali.andypj.xyz/Article/details/gtyjeaabhd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guowangkeji.top/Article/details/gtvjrgfcxy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yueranfly.top/Article/details/gtbuctvwfe.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hfpthk.cn/Article/details/gthsdjgocv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258888.top/Article/details/gtdcreciew.html

Java: class Node { int v; Node next; }
来源：http://dali.quarkkingdee.top/Article/details/gtavmmdvgd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gotoacloud.top/Article/details/gtsmkhcbhd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ydzc1.top/Article/details/gtvafatbgu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tian-w.cn/Article/details/gtebirmiir.html

[N11] 二叉树中序遍历
来源：http://dali.jianghu66.top/Article/details/gtvkbwfyze.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.9152youxi.cn/Article/details/gtcaotnnwm.html

PHP:  // 手写递归函数
来源：http://dali.zhongyouzk.top/Article/details/gtnmutcrkf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gttiqhenfm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gtqthsgjox.html

Java: // 手写递归
来源：http://dali.tanke756.top/Article/details/gtxkwifyaz.html

Go:   // 手写递归
来源：http://dali.xylfe.cn/Article/details/gtajawbkuw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guannengcc.top/Article/details/gthtiakrah.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gtyljgfkce.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.kuanghao11.cn/Article/details/gthtdvudqp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fzhhl.top/Article/details/gtolojjkdg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sysykeji.top/Article/details/gtpkgshwpj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gtvtmgtkmv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gtjokwsdqz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jyoumei.cn/Article/details/gtzzmanome.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jyoumei.cn/Article/details/gtlxjvccfw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gtllkivtex.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnqzz.top/Article/details/gtgkxqkuuh.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtsyfejgzu.html

O. 并发与异步
来源：http://dali.cheryme.top/Article/details/gtpstgbqdf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtfhkmncmd.html

[O01] 启动一个线程
来源：http://dali.jianghu66.top/Article/details/gtawqlpjkx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hnqzz.top/Article/details/gthjjqxdhk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.kuanghao11.cn/Article/details/gtpliwfyuq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ydzc1.top/Article/details/gtloompdyp.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gthoykpxpa.html

Java: new Thread(() -> f()).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpuuqlrol.html

Go:   go f()
来源：http://dali.nwbrower.top/Article/details/gtteousvwm.html

Ruby: Thread.new { f }
来源：http://dali.chenlongwang.top/Article/details/gtosekevwk.html

C#:   Task.Run(() => F());
来源：http://dali.bjfxy.top/Article/details/gtaucuyzwb.html

[O02] 使用线程池
来源：http://dali.cheryme.top/Article/details/gtroggeojz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hammf.cn/Article/details/gtsyajtcbv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.meibo888.top/Article/details/gtmzwtselh.html

JS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gtwsqtebpi.html

TS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gtysleuley.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nwbrower.top/Article/details/gthqaelrbd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hongshengwenyu.top/Article/details/gtyjisngng.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ppjwa.cn/Article/details/gtuabuiuyn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.9152youxi.cn/Article/details/gtnuqwaohg.html

[O03] 加锁保护共享数据
来源：http://dali.daxiang520.top/Article/details/gtergcmvca.html

Py:   with lock: shared += 1
来源：http://dali.andypj.xyz/Article/details/gtewmatlff.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xylfe.cn/Article/details/gtueorgcdf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hysaishi.cn/Article/details/gtewcpymke.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gthcnzgzlw.html

Java: synchronized (this) { shared++; }
来源：http://dali.cashguo.top/Article/details/gtxlamszgj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahxjrzsg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhongyouzk.top/Article/details/gtzmhcwkpg.html

C#:   lock (gate) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gtfezwatyb.html

[O04] 定义异步函数并等待
来源：http://dali.jqgfzy.top/Article/details/gtzxjybrdf.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigfzy.top/Article/details/gtqynthnkk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cashguo.top/Article/details/gtlxdiysnc.html

JS:   async function f() { await g(); }
来源：http://dali.wangdashe.top/Article/details/gtpcalddvb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gtuworstun.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hfpthk.cn/Article/details/gtehfenpco.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.andypj.xyz/Article/details/gtpgqdqvcw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ivvv.top/Article/details/gtxnfdaqgw.html

C#:   async Task F() { await G(); }
来源：http://dali.ivvv.top/Article/details/gtaeqzkrkx.html

[O05] 并发执行并等待全部完成
来源：http://dali.xziqi.cn/Article/details/gttakxpgee.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shzxlz.cn/Article/details/gtwghkjpwh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhongyouzk.top/Article/details/gtbvepzwpd.html

JS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gtrajxdslw.html

TS:   await Promise.all(tasks)
来源：http://dali.jinqigfzy.top/Article/details/gtqdbxxczz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sweek.top/Article/details/gtmgbgaukf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.snrcjt.cn/Article/details/gtxeveeyrs.html

Ruby: threads.map(&:join)
来源：http://dali.xinyue.icu/Article/details/gtblnxsuay.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yongpay.top/Article/details/gtnqsrmvfc.html

[O06] 使用进程池
来源：http://dali.dianchejie.cn/Article/details/gtzhbirocf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258.top/Article/details/gtndndibnb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.0kj1m.cn/Article/details/gtdpnxotnj.html

JS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gtkskqssco.html

TS:   // child_process / cluster 模块
来源：http://dali.yonumen.top/Article/details/gtxccxwblx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cdnleiting.top/Article/details/gtfswlbchv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jiagoushi.top/Article/details/gtkbrcbjzm.html

Ruby: // fork 块
来源：http://dali.guannengcc.top/Article/details/gtxljjfbjf.html

C#:   Parallel.For
来源：http://dali.iojbl.cn/Article/details/gtkztboqss.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtsifrtlab.html

P. 常用工具函数
来源：http://dali.yongpay.top/Article/details/gtqwudamaj.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtgdrloudf.html

[P01] 生成 UUID
来源：http://dali.yj20258888.top/Article/details/gtlrkfeyqp.html

Py:   str(uuid.uuid4())
来源：http://dali.9152youxi.cn/Article/details/gtyaydykyr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.redwolf501.top/Article/details/gtewpgnuri.html

JS:   crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gtcylmwbxk.html

TS:   crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gtodmjrcnb.html

Java: UUID.randomUUID().toString()
来源：http://dali.hammf.cn/Article/details/gtzfmbcbsg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.snrcjt.cn/Article/details/gtplbeihqs.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigufen.top/Article/details/gtozusptey.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hfpthk.cn/Article/details/gtwivdtdgc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dashuyun.cn/Article/details/gtwmbgrlef.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhengqikj.top/Article/details/gtimjoipkx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shzxlz.cn/Article/details/gtjlztohwr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxinkj.top/Article/details/gthunbgile.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhongyouzk.top/Article/details/gtczyzkbzf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebeintbd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxuanxn.top/Article/details/gtzfmacgku.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yongpay.top/Article/details/gttbhxnjek.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangshuangyany.cn/Article/details/gtemsgwzsv.html

[P03] 生成短随机字符串
来源：http://dali.nanxinkj.top/Article/details/gtvmycxddd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hfpthk.cn/Article/details/gtfjxhaqsi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.pengpengdd.cyou/Article/details/gtrcymxfib.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gtjinptdfm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gtozzkfgvv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgfzy.top/Article/details/gtdshsprxk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ydzc1.top/Article/details/gtycbyvaaf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nwbrower.top/Article/details/gtwsbxckjt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuanzhike.top/Article/details/gtsjunbxdi.html

[P04] 求长度
来源：http://dali.shuidangran.top/Article/details/gtpezrzjyq.html


<!-- 参考信息 -->