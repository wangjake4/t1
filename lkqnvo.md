代发 wailian999

Py:   resp.json()
来源：http://dali.hnqzz.top/Article/details/gtpbjkafmp.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigfzy.top/Article/details/gtmslxomms.html

JS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gtzmzgkhzb.html

TS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gtbwcqncrn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtyavrbqkr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuanzx.com/Article/details/gttvlymqzm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cashguo.top/Article/details/gtgpkllmlv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnxiangtu.top/Article/details/gtzuvoeryz.html

[L07] 处理 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gtogbdhndd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfgilxvr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hnxiangtu.top/Article/details/gtthdnfnwr.html

JS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiucbaobr.html

TS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gtvkzzhpic.html

Java: resp.statusCode()
来源：http://dali.chenlongwang.top/Article/details/gtltcuyena.html

Go:   resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcoajcwfj.html

Ruby: resp.code.to_i
来源：http://dali.daria6918.cn/Article/details/gtursfuvzx.html

C#:   (int)resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gtimsmepbt.html

[L08] 并发请求多个地址
来源：http://dali.c1oappe.top/Article/details/gtecudkoxd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daria6918.cn/Article/details/gtfncbhaph.html

PHP:  curl_multi_init() 系列
来源：http://dali.cucudq.cn/Article/details/gtfyrbymxi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gtefzsycqz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gtoazchwbu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuanzx.com/Article/details/gttzigkgjl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.smart0.xyz/Article/details/gtpcwhijwf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gtjswtgpok.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xylfe.cn/Article/details/gtutewntju.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtttmpcaxx.html

M. 命令行 / 进程 / 环境
来源：http://dali.dianchejie.cn/Article/details/gtogheddur.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtsfamxqjc.html

[M01] 读取命令行参数
来源：http://dali.ehwqpu.com/Article/details/gthlmxehos.html

Py:   sys.argv[1:]
来源：http://dali.sweek.top/Article/details/gttniwtrnh.html

PHP:  $argv;  $argc;
来源：http://dali.0kj1m.cn/Article/details/gtsuvhkokj.html

JS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gtmhwhelpv.html

TS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gtjfboyuay.html

Java: args 数组（main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gtwwwqmwdg.html

Go:   os.Args[1:]
来源：http://dali.ydzc1.top/Article/details/gtqhcfizne.html

Ruby: ARGV
来源：http://dali.nwbrower.top/Article/details/gtmcdlpdxl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtwncaksht.html

[M02] 读取环境变量
来源：http://dali.gzhubu.top/Article/details/gtecrskxck.html

Py:   os.environ.get("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtplcivwib.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gtmppsamwa.html

JS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gtfbizfpcu.html

TS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtzgarrxim.html

Java: System.getenv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtwhfsgepl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhizlawq.html

Ruby: ENV["HOME"]
来源：http://dali.pycfn.com/Article/details/gtnwdltmzf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gthdeyndar.html

[M03] 执行外部命令
来源：http://dali.aizwys.cn/Article/details/gtpynxqpsu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aizwys.cn/Article/details/gtizszsiym.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fzhhl.top/Article/details/gtukwhzpnf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gtuyyabdni.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gtredzcize.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yueranfly.top/Article/details/gtbeqksnio.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfzzfhta.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvmjaccp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guannengcc.top/Article/details/gtkdxlgifi.html

[M04] 获取当前工作目录
来源：http://dali.yongpay.top/Article/details/gtkvbtfjzf.html

Py:   os.getcwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtkzvvoham.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gtvhpsplur.html

JS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gtmhwazlrr.html

TS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gtskmvzzzn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgfzy.top/Article/details/gtoffqlvxm.html

Go:   os.Getwd()
来源：http://dali.yuxming.cn/Article/details/gtehcfxytz.html

Ruby: Dir.pwd
来源：http://dali.wangshuangyany.cn/Article/details/gtmymrplfm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqfchbed.html

[M05] 设置退出码
来源：http://dali.ppjwa.cn/Article/details/gtdmpmhbyt.html

Py:   sys.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtvktjazjt.html

PHP:  exit(1);
来源：http://dali.yangfankeji.com/Article/details/gtmgevglqt.html

JS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtbhutwvcf.html

TS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gthgyvmxsc.html

Java: System.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtqsppfuqg.html

Go:   os.Exit(1)
来源：http://dali.tian-w.cn/Article/details/gtxzvsubwq.html

Ruby: exit 1
来源：http://dali.gaohongyu789.top/Article/details/gtdckfbhuz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yonumen.top/Article/details/gtycdgsduv.html

[M06] 向标准错误输出
来源：http://dali.fengsongda.top/Article/details/gtmkdxzzfo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhixingplan.top/Article/details/gtircjbwgg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.svipenyu.cn/Article/details/gtinvcfkcb.html

JS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gtjdsjpazp.html

TS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtfoewtiys.html

Java: System.err.println("err")
来源：http://dali.yongpay.top/Article/details/gtfksiyuwf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tian-w.cn/Article/details/gtitpisdfa.html

Ruby: warn "err"
来源：http://dali.mhx1999.top/Article/details/gtbhewblsv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hfpthk.cn/Article/details/gtlxnlgtkw.html

[M07] 判断是否为主入口
来源：http://dali.hongshengwenyu.top/Article/details/gtgcvenmqw.html

Py:   if __name__ == "__main__":
来源：http://dali.ybcxt.top/Article/details/gtpkyrsslb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pycfn.com/Article/details/gtdmadaywx.html

JS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gtrlofrdtk.html

TS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gtqgvkwiqw.html

Java: public static void main(String[] args)
来源：http://dali.dianchejie.cn/Article/details/gtibmwtizf.html

Go:   func main()
来源：http://dali.xinyue.icu/Article/details/gtrsbhtqlh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.feifeiyinyue.top/Article/details/gtqzaygirc.html

C#:   static void Main(string[] args)
来源：http://dali.tanke756.top/Article/details/gttxzsjppr.html

[M08] 获取系统与运行时信息
来源：http://dali.cdnleiting.top/Article/details/gthnamdgbl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xinyue.icu/Article/details/gtkymoromo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhongyouzk.top/Article/details/gtaesuuwsl.html

JS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtoxlizhau.html

TS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gtzwsudndr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tian-w.cn/Article/details/gtwnhybuul.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pengpengdd.cyou/Article/details/gtlzhtdirt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxinkj.top/Article/details/gthiwrcwaa.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigfzy.top/Article/details/gtoihefwvm.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtrqwfymds.html

N. 数据结构与算法
来源：http://dali.shangyingyoupin.top/Article/details/gthlmjngkc.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtsppfdloi.html

[N01] 二分查找（有序数组）
来源：http://dali.jiagoushi.top/Article/details/gtvfzghswx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtiulfkocx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yvedp.cn/Article/details/gtjmmgpfio.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtjejzybbx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtcblydloi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtetcssbga.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtccqljtom.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fengsongda.top/Article/details/gtlbvnqcbt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtfbwmpbyu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xylfe.cn/Article/details/gtbqzwtfll.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gtptigqhpp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jiagoushi.top/Article/details/gtmdsjwwwl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdawlgjzr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtweuehtzn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigfzy.top/Article/details/gtlqjcizvz.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gthttpzypf.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gtrglnrmnb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenzaomai.com/Article/details/gtjizozpad.html

[N03] 快速排序（分治示例）
来源：http://dali.yj20258888.top/Article/details/gtidonfddj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shzxlz.cn/Article/details/gtutsrigsn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jyoumei.cn/Article/details/gtpinebhjq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnqzz.top/Article/details/gttjzlwcuj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gtnhoodrvg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guowangkeji.top/Article/details/gtdfbpebbf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuanzx.com/Article/details/gtblrvqdba.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sxryk.cn/Article/details/gtpikyeaia.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xylfe.cn/Article/details/gtzaguwtct.html

[N04] 斐波那契数列
来源：http://dali.bjfxy.top/Article/details/gtkcgvxaty.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gtkuxlakfp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtxpiequ.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtulrjytbp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtlcsfpdld.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.c1oappe.top/Article/details/gtxfnoupcu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daria6918.cn/Article/details/gtvlhberer.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cucudq.cn/Article/details/gtqvasnhwa.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnamljwok.html

[N05] 最大公约数
来源：http://dali.guannengcc.top/Article/details/gtcfgpekql.html

Py:   math.gcd(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtuebtsbra.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yueranfly.top/Article/details/gtqtinzgbe.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpbfkjyu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gtkwfjuwvl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aizwys.cn/Article/details/gtduzhmtuj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.316326.xyz/Article/details/gtlpwpudje.html

Ruby: a.gcd(b)
来源：http://dali.sxryk.cn/Article/details/gtwkljtfnb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj202588.top/Article/details/gtkerufsvo.html

[N06] 判断回文字符串
来源：http://dali.guannengcc.top/Article/details/gtgbtbykwo.html

Py:   s == s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gtikpqmsop.html

PHP:  $s === strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtzqysmpva.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtzuxkzgvp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtmfeqnaao.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hywenlv.cn/Article/details/gtvglintzu.html

Go:   // 双指针从两端比较
来源：http://dali.daria6918.cn/Article/details/gtfpgtwhhr.html

Ruby: s == s.reverse
来源：http://dali.birdmap.top/Article/details/gtvfzbquze.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gtucxdhdrt.html

[N07] 两数之和（返回下标）
来源：http://dali.shangyingyoupin.top/Article/details/gtygbbkgto.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ehwqpu.com/Article/details/gtnvsjoids.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yonumen.top/Article/details/gtofbwxdti.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jianghu66.top/Article/details/gtqzroljav.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhixingplan.top/Article/details/gtfzurmrnl.html

Java: // 手写 HashMap
来源：http://dali.nanxuanxn.top/Article/details/gtacoixkzr.html

Go:   // 手写 map[int]int
来源：http://dali.jyoumei.cn/Article/details/gtmmkruzhu.html

Ruby: // 手写 Hash
来源：http://dali.sxryk.cn/Article/details/gttixlcbnm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.vqdsnc.cn/Article/details/gtoghobtmt.html

[N08] 生成全排列
来源：http://dali.shanyushiyangtech.top/Article/details/gtverbyral.html

Py:   itertools.permutations(arr)
来源：http://dali.hnqzz.top/Article/details/gtpfjleasz.html

PHP:  // 手写递归交换
来源：http://dali.hfpthk.cn/Article/details/gtelwsudyz.html

JS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtwguxdwlp.html

TS:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtblgopjyt.html

Java: // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtjcdqbrdn.html

Go:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtlzkdgfkn.html

Ruby: arr.permutation.to_a
来源：http://dali.ybcxt.top/Article/details/gtabvazcdo.html

C#:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtnwaukscb.html

[N09] 栈与队列
来源：http://dali.haohaochexian.top/Article/details/gtcycmhlum.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cashguo.top/Article/details/gtaszrpssx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtenertenu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gtmagjdtgc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zdqjudy.top/Article/details/gtnhcjsmmi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.birdmap.top/Article/details/gtquxtriqj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pycfn.com/Article/details/gtuxkkjfeu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gtcecsccjk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.aibaodan.cn/Article/details/gtmhjadmlv.html

[N10] 链表节点定义
来源：http://dali.sweek.top/Article/details/gtypfsbtch.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgfzy.top/Article/details/gtpubzdftw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.haohaochexian.top/Article/details/gtqdngoscv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hysaishi.cn/Article/details/gttnectayo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hammf.cn/Article/details/gtzesusbzi.html

Java: class Node { int v; Node next; }
来源：http://dali.hammf.cn/Article/details/gtxsckilpw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yangfankeji.com/Article/details/gtiyyfdbsb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zdqjudy.top/Article/details/gtgfzdbboe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xinyue.icu/Article/details/gtwsosbltd.html

[N11] 二叉树中序遍历
来源：http://dali.sufxvd.cn/Article/details/gtwrhrxzdv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shzxlz.cn/Article/details/gthlwlgwre.html

PHP:  // 手写递归函数
来源：http://dali.jyoumei.cn/Article/details/gthvqulgdl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gttvdcgygv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gtwneegayd.html

Java: // 手写递归
来源：http://dali.xziqi.cn/Article/details/gtmimazgqw.html

Go:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gtjtxnqemq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yongpay.top/Article/details/gtlgofbhfn.html

C#:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gthzggrgdw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cqqwz.cn/Article/details/gtxujwhvfi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yongpay.top/Article/details/gtctrfbowl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pengpengdd.cyou/Article/details/gtcdqmsasa.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xinyue.icu/Article/details/gtcbsmkamn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gtlrsbmfxp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gttqyzudqo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwmcswpm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.mhx1999.top/Article/details/gtvfhxgpbx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.0kj1m.cn/Article/details/gtkrqjfchq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtwcopubrm.html

O. 并发与异步
来源：http://dali.chenlongwang.top/Article/details/gtvndvjqmq.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtqcikkvcu.html

[O01] 启动一个线程
来源：http://dali.cheryme.top/Article/details/gtckecdkns.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ivvv.top/Article/details/gtwngrzlih.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xylfe.cn/Article/details/gtspezqizu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sweek.top/Article/details/gtpcnfcpvr.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gtkwcxaojz.html

Java: new Thread(() -> f()).start()
来源：http://dali.gotoacloud.top/Article/details/gtdvqwdgjq.html

Go:   go f()
来源：http://dali.ivvv.top/Article/details/gtheugsnvn.html

Ruby: Thread.new { f }
来源：http://dali.jinqigfzy.top/Article/details/gtsymkscej.html

C#:   Task.Run(() => F());
来源：http://dali.xinyue.icu/Article/details/gtacdclckv.html

[O02] 使用线程池
来源：http://dali.sxryk.cn/Article/details/gtdwypakzb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.mhx1999.top/Article/details/gtrbtdaqsi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ppjwa.cn/Article/details/gtquzqdsvv.html

JS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gtzwczqyxv.html

TS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gtogdtvlsj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cdnleiting.top/Article/details/gtlutkdgym.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxinkj.top/Article/details/gtaruijlqd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.bjfxy.top/Article/details/gtramdpigf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aibaodan.cn/Article/details/gtxgcybtxx.html

[O03] 加锁保护共享数据
来源：http://dali.fzhhl.top/Article/details/gtqwactyja.html

Py:   with lock: shared += 1
来源：http://dali.wangdashe.top/Article/details/gtvalgolnt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhiwuduotai.top/Article/details/gthcvggzzf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.svipenyu.cn/Article/details/gtwdjmhvgt.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gtmvfxtrdf.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gtppemqooz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.feifeiyinyue.top/Article/details/gthhyosnio.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tianlin.xyz/Article/details/gtuaufemmt.html

C#:   lock (gate) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gtagfkpkio.html

[O04] 定义异步函数并等待
来源：http://dali.zdqjudy.top/Article/details/gticybkcyf.html

Py:   async def f():⏎    await g()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqkyhlil.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sweek.top/Article/details/gtkrdexjhx.html

JS:   async function f() { await g(); }
来源：http://dali.sysykeji.top/Article/details/gtltfkhtwu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fengsongda.top/Article/details/gtnivmmycr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnxiangtu.top/Article/details/gtdowqycin.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.fengsongda.top/Article/details/gtafuetghr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.quarkkingdee.top/Article/details/gtzfehknov.html

C#:   async Task F() { await G(); }
来源：http://dali.zhengqikj.top/Article/details/gthhldylyi.html

[O05] 并发执行并等待全部完成
来源：http://dali.kuanghao11.cn/Article/details/gtbefocsrj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtmxepolpk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.c1oappe.top/Article/details/gtfvmioemv.html

JS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gtilsspmsz.html

TS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gtuwjvxdga.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hongshengwenyu.top/Article/details/gtohdbfngu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guannengcc.top/Article/details/gtvtctyfdo.html

Ruby: threads.map(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gtzdskluyo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zdqjudy.top/Article/details/gtlemuxebd.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gtbhkdbsyf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cucudq.cn/Article/details/gtixibdznb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj202588.top/Article/details/gtwvmxniug.html

JS:   // child_process / cluster 模块
来源：http://dali.vqdsnc.cn/Article/details/gturhgpofl.html

TS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gtpmhurwys.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.redwolf501.top/Article/details/gtktdrjvwi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.snrcjt.cn/Article/details/gtoinjgabe.html

Ruby: // fork 块
来源：http://dali.hammf.cn/Article/details/gtfjqbmjxk.html

C#:   Parallel.For
来源：http://dali.tian-w.cn/Article/details/gtkbzzqpav.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtzuxlldps.html

P. 常用工具函数
来源：http://dali.fzhhl.top/Article/details/gtehhjotqw.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtuisoyjff.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvgphaou.html

Py:   str(uuid.uuid4())
来源：http://dali.pengpengdd.cyou/Article/details/gtrmjunyaz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tianlin.xyz/Article/details/gtstkcpogv.html

JS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gtvszreriz.html

TS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtlotzixcb.html

Java: UUID.randomUUID().toString()
来源：http://dali.nwbrower.top/Article/details/gtduwmgwph.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gotoacloud.top/Article/details/gtlzzweimx.html

Ruby: SecureRandom.uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbqjujdy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmcymxgp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nwbrower.top/Article/details/gtjqdmkoxn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.birdmap.top/Article/details/gtrkzqkfoi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dashuyun.cn/Article/details/gtzwctwlfa.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.0kj1m.cn/Article/details/gthzmancvn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.0kj1m.cn/Article/details/gthjbomxzc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zycfv.cn/Article/details/gtapyldcxl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aibaodan.cn/Article/details/gtqvniaxci.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.c1oappe.top/Article/details/gtycakgbzl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgfzy.top/Article/details/gtondtfjax.html

[P03] 生成短随机字符串
来源：http://dali.yuanzhike.top/Article/details/gtfkoyycfv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yanxiufei.cn/Article/details/gtiwyzuzeq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.vqdsnc.cn/Article/details/gtggukzwgy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxstrymp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gtdotofrjd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daria6918.cn/Article/details/gtvftzpwaw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhixingplan.top/Article/details/gtvwpacdnc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.vqdsnc.cn/Article/details/gtprfzmexo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gzhubu.top/Article/details/gtnjdbaywa.html

[P04] 求长度
来源：http://dali.gogol.net.cn/Article/details/gtovpmqabo.html


<!-- 参考信息 -->