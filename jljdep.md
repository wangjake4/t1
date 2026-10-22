代发 wailian999

Py:   resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfnrgxpk.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmlkozaw.html

JS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gtcxbuinsn.html

TS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gtegsnnmkc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtfvneokrq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shangyingyoupin.top/Article/details/gtryklfgzz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shzxlz.cn/Article/details/gtjymfwxuu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aibaodan.cn/Article/details/gtfnlnwozp.html

[L07] 处理 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gtgvagttku.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuetiantiany.cn/Article/details/gttjetdmcq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxhtntey.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gtdduujfsv.html

TS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtwlvtcayd.html

Java: resp.statusCode()
来源：http://dali.xinyue.icu/Article/details/gtmljoznyz.html

Go:   resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gtpsvgnvzs.html

Ruby: resp.code.to_i
来源：http://dali.hysaishi.cn/Article/details/gtwkkroubl.html

C#:   (int)resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gtckjijaja.html

[L08] 并发请求多个地址
来源：http://dali.gaohongyu789.top/Article/details/gtyncrdflt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zdqjudy.top/Article/details/gtiactkgzz.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqvybgfb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtswqnitcp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtqasrenzo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guowangkeji.top/Article/details/gtnnhjbeua.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.quarkkingdee.top/Article/details/gtesaoxvca.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuanzhike.top/Article/details/gtgqbluaig.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shuidangran.top/Article/details/gtmkrzwvio.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtvvljwpcc.html

M. 命令行 / 进程 / 环境
来源：http://dali.ppjwa.cn/Article/details/gthtatzxwe.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtodlscnhu.html

[M01] 读取命令行参数
来源：http://dali.svipenyu.cn/Article/details/gtorokgwxd.html

Py:   sys.argv[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvziuqbnb.html

PHP:  $argv;  $argc;
来源：http://dali.zhengqikj.top/Article/details/gtbwwlmqai.html

JS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gtmluxnglp.html

TS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gtedakhlfk.html

Java: args 数组（main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gtozcuejrk.html

Go:   os.Args[1:]
来源：http://dali.iojbl.cn/Article/details/gtpicqnxrx.html

Ruby: ARGV
来源：http://dali.pycfn.com/Article/details/gtfdbuzdwa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gtlpcesvfu.html

[M02] 读取环境变量
来源：http://dali.kuanghao11.cn/Article/details/gtkkmgwtmi.html

Py:   os.environ.get("HOME")
来源：http://dali.cashguo.top/Article/details/gtwqhhoujc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yongpay.top/Article/details/gtiibfvmwf.html

JS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gtsdoogdbb.html

TS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gtpyoyoytp.html

Java: System.getenv("HOME")
来源：http://dali.cashguo.top/Article/details/gthsrvibmk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtfzrdaqaa.html

Ruby: ENV["HOME"]
来源：http://dali.yangfankeji.com/Article/details/gtzushuqjp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtalpgayxf.html

[M03] 执行外部命令
来源：http://dali.jinghuilouyu.cn/Article/details/gthqyllkuc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtonhtvloj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.bjfxy.top/Article/details/gtfzbwqxdf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gttfnlwkef.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtehxftbrc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuxming.cn/Article/details/gtarsmazsl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.svipenyu.cn/Article/details/gtdmvvbtpg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.kuanghao11.cn/Article/details/gtfilzgspn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yvedp.cn/Article/details/gtdxxophgv.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtfshdymaw.html

Py:   os.getcwd()
来源：http://dali.aibaodan.cn/Article/details/gtqoqkmfnu.html

PHP:  getcwd();
来源：http://dali.cheryme.top/Article/details/gtjnvcfdwo.html

JS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtpzhdljnj.html

TS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtwtshbybo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dashuyun.cn/Article/details/gtyvmpbudg.html

Go:   os.Getwd()
来源：http://dali.jqgufenzy.top/Article/details/gtmozywupd.html

Ruby: Dir.pwd
来源：http://dali.jiagoushi.top/Article/details/gtcqlhfdfz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhoulong.xyz/Article/details/gtnmhsikzl.html

[M05] 设置退出码
来源：http://dali.nwbrower.top/Article/details/gtprirsbaa.html

Py:   sys.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtxirbinan.html

PHP:  exit(1);
来源：http://dali.hammf.cn/Article/details/gtfcqjtprr.html

JS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtwoscnmml.html

TS:   process.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtvhggehin.html

Java: System.exit(1)
来源：http://dali.yj20258.top/Article/details/gtudoejdxs.html

Go:   os.Exit(1)
来源：http://dali.daria6918.cn/Article/details/gtxqmfvfdf.html

Ruby: exit 1
来源：http://dali.jiagoushi.top/Article/details/gtyetkcapn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258.top/Article/details/gtpydvhoeo.html

[M06] 向标准错误输出
来源：http://dali.sufxvd.cn/Article/details/gttdrpzsbo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gtqzqnnqbj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.redwolf501.top/Article/details/gtnuwdldev.html

JS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gtkbapsmkw.html

TS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gtvpizajmi.html

Java: System.err.println("err")
来源：http://dali.wangshuangyany.cn/Article/details/gthveoaefa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangdashe.top/Article/details/gtiojxfsqa.html

Ruby: warn "err"
来源：http://dali.haohaochexian.top/Article/details/gtqoqahvud.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.9152youxi.cn/Article/details/gtmjuekkbf.html

[M07] 判断是否为主入口
来源：http://dali.yanxiufei.cn/Article/details/gtjkwzwtiq.html

Py:   if __name__ == "__main__":
来源：http://dali.sufxvd.cn/Article/details/gtodbhwvtk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhoulong.xyz/Article/details/gtgynvbwet.html

JS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gtutixkldp.html

TS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gtitynifex.html

Java: public static void main(String[] args)
来源：http://dali.cdnleiting.top/Article/details/gtzuvovyzy.html

Go:   func main()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgkiuxuo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.vqdsnc.cn/Article/details/gtusqxbdcp.html

C#:   static void Main(string[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttikgeedx.html

[M08] 获取系统与运行时信息
来源：http://dali.shzxlz.cn/Article/details/gtaxqdaqfc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258.top/Article/details/gthjmpsfyz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gaohongyu789.top/Article/details/gtvbsfgixa.html

JS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gtyqzcjtsm.html

TS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gtftkhpvnp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxuanxn.top/Article/details/gtvefaggvb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sysykeji.top/Article/details/gtzeuxnaar.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pycfn.com/Article/details/gtnctwzqhp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yonumen.top/Article/details/gtboqcqfmg.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtwgnstyua.html

N. 数据结构与算法
来源：http://dali.daxiang520.top/Article/details/gtsqgpzmtw.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtonuuadjx.html

[N01] 二分查找（有序数组）
来源：http://dali.smart0.xyz/Article/details/gtlpsbdlsx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtzquopoqk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtalayfhzp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gtunmrkkjv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gtperxyprt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtawtposal.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gtxlxzszyl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfmpcclk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtglvaxadj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hongshengwenyu.top/Article/details/gthtfjjiyy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtewwdekyg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jyoumei.cn/Article/details/gthkoczryv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gtyqkabrgv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtirjykkru.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkaiprewe.html

Go:   slices.Sort(arr)
来源：http://dali.shuidangran.top/Article/details/gtyrgmkdzz.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gtrtlswhdr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daria6918.cn/Article/details/gtjrqekeho.html

[N03] 快速排序（分治示例）
来源：http://dali.yueranfly.top/Article/details/gtdlysawzb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhongyouzk.top/Article/details/gtrwdgqylr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aibaodan.cn/Article/details/gthycffjfb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gthtvvrlcx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.redwolf501.top/Article/details/gtuartdjnw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hammf.cn/Article/details/gtetwumlse.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.kuanghao11.cn/Article/details/gtjypqfcvy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pengpengdd.cyou/Article/details/gtxomxpyjq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hywenlv.cn/Article/details/gtmujeoqnv.html

[N04] 斐波那契数列
来源：http://dali.quarkkingdee.top/Article/details/gtxifszyld.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cheryme.top/Article/details/gtlerxmqqg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yueranfly.top/Article/details/gtdkfamzxm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtkpjrvivt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpieklny.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gtcyndjatc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinqigfzy.top/Article/details/gtcugttloh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gtczsyzvtz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtcqfjsneh.html

[N05] 最大公约数
来源：http://dali.jinqigufen.top/Article/details/gtpfsguhun.html

Py:   math.gcd(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtslejjmem.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenzaomai.com/Article/details/gtewbnytmp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gtjpdpkmrx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtzadikknw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pengpengdd.cyou/Article/details/gtwglnvxsd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ydzc1.top/Article/details/gtmhyisonx.html

Ruby: a.gcd(b)
来源：http://dali.havefunace.top/Article/details/gtupbwhqlk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dianchejie.cn/Article/details/gtkxlwvapx.html

[N06] 判断回文字符串
来源：http://dali.shuidangran.top/Article/details/gtguizulnh.html

Py:   s == s[::-1]
来源：http://dali.mhx1999.top/Article/details/gtyqannoan.html

PHP:  $s === strrev($s);
来源：http://dali.pycfn.com/Article/details/gtqsaicreq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtybyeazfe.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtlvmevgyf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangkeji.top/Article/details/gttoqscwwf.html

Go:   // 双指针从两端比较
来源：http://dali.jiagoushi.top/Article/details/gtkornbzyy.html

Ruby: s == s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gtlkntdwks.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gtjjcqvtkt.html

[N07] 两数之和（返回下标）
来源：http://dali.pengpengdd.cyou/Article/details/gtwkmoqoyl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yuxming.cn/Article/details/gtdllnzzis.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guowangkeji.top/Article/details/gtbpyrnbum.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.smart0.xyz/Article/details/gtppzkngzs.html

TS:   // 手写 Map<string, number>
来源：http://dali.jiagoushi.top/Article/details/gtyyfyusel.html

Java: // 手写 HashMap
来源：http://dali.316326.xyz/Article/details/gtcbvmkxkf.html

Go:   // 手写 map[int]int
来源：http://dali.iojbl.cn/Article/details/gtlpgmidff.html

Ruby: // 手写 Hash
来源：http://dali.xuanzx.com/Article/details/gtrqchzrjy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.quarkkingdee.top/Article/details/gtwqaaemeq.html

[N08] 生成全排列
来源：http://dali.cqqwz.cn/Article/details/gtixuhrqdj.html

Py:   itertools.permutations(arr)
来源：http://dali.hammf.cn/Article/details/gtwwxqzhhe.html

PHP:  // 手写递归交换
来源：http://dali.xziqi.cn/Article/details/gtmyhkowkb.html

JS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtqjmlujft.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwdbvjsi.html

Java: // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtqdlkxkze.html

Go:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtjyhmzmha.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxuanxn.top/Article/details/gtetzqkhec.html

C#:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gteeoggfuy.html

[N09] 栈与队列
来源：http://dali.xylfe.cn/Article/details/gtxskwgptp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gzhubu.top/Article/details/gtvumlzdmn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtkxlpcdal.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtcvimeaew.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.smart0.xyz/Article/details/gtgmnzovlr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gtvidrgpsw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nwbrower.top/Article/details/gtoqwpsfgs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtxvsdwirr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.guannengcc.top/Article/details/gtlhuynhox.html

[N10] 链表节点定义
来源：http://dali.ybcxt.top/Article/details/gtxsfeopsi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gzhubu.top/Article/details/gtyjebidfp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yongpay.top/Article/details/gtehzqevku.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jianghu66.top/Article/details/gttdczzlir.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gaohongyu789.top/Article/details/gtbsbjccrg.html

Java: class Node { int v; Node next; }
来源：http://dali.aibaodan.cn/Article/details/gtjchbfvap.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxxqkuau.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dashuyun.cn/Article/details/gtqlwkjjnu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xylfe.cn/Article/details/gtqtxnpkjw.html

[N11] 二叉树中序遍历
来源：http://dali.9152youxi.cn/Article/details/gtgwqankje.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj20258888.top/Article/details/gtfnclbguh.html

PHP:  // 手写递归函数
来源：http://dali.xylfe.cn/Article/details/gtywsrbffj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yueranfly.top/Article/details/gtkpcqznho.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ppjwa.cn/Article/details/gtyfnisuky.html

Java: // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtsfotjtrw.html

Go:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtdpwaijma.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fzhhl.top/Article/details/gtznnlnnzk.html

C#:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gtntslewlh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigfzy.top/Article/details/gtaxwelrnk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj202588.top/Article/details/gthqkopsjs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hywenlv.cn/Article/details/gtzscmqltk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhyhnyjb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gtacbaygtp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsialudlv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.316326.xyz/Article/details/gtfraqzios.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgfzy.top/Article/details/gthubikfar.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhzijpnd.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtvewdagtb.html

O. 并发与异步
来源：http://dali.hammf.cn/Article/details/gthsgamhqd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtgsmrofmq.html

[O01] 启动一个线程
来源：http://dali.fzhhl.top/Article/details/gtwjbmtyzy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.meibo888.top/Article/details/gtgxiqjnmp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tian-w.cn/Article/details/gtzctzwcij.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ivvv.top/Article/details/gtgoxarijd.html

TS:   // 同 JS
来源：http://dali.iojbl.cn/Article/details/gtsguxeidp.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhoulong.xyz/Article/details/gttwdqerhk.html

Go:   go f()
来源：http://dali.hnxiangtu.top/Article/details/gtufxyfrqx.html

Ruby: Thread.new { f }
来源：http://dali.yuanzhike.top/Article/details/gtmgeogxca.html

C#:   Task.Run(() => F());
来源：http://dali.cashguo.top/Article/details/gthjlpdfyd.html

[O02] 使用线程池
来源：http://dali.yuanzhike.top/Article/details/gtoihihlfr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zycfv.cn/Article/details/gteycflwii.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.feifeiyinyue.top/Article/details/gtbpkpfsow.html

JS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gthahgjkub.html

TS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gtlqubfmeq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cucudq.cn/Article/details/gtxavumixe.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.meibo888.top/Article/details/gtizlcqiij.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shzxlz.cn/Article/details/gteqcigaox.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenjidiqi.icu/Article/details/gtdkejenzu.html

[O03] 加锁保护共享数据
来源：http://dali.shuidangran.top/Article/details/gtvbvvsvlk.html

Py:   with lock: shared += 1
来源：http://dali.ydzc1.top/Article/details/gtlbgudonv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gogol.net.cn/Article/details/gtnvkwszgi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgufenzy.top/Article/details/gtlarizomd.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gtqqxdctpg.html

Java: synchronized (this) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gtdjuacflj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tanke756.top/Article/details/gtgvlzxhlm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenlongwang.top/Article/details/gtnxhmeelt.html

C#:   lock (gate) { shared++; }
来源：http://dali.zdqjudy.top/Article/details/gtgxgndwat.html

[O04] 定义异步函数并等待
来源：http://dali.hysaishi.cn/Article/details/gtfenihxmx.html

Py:   async def f():⏎    await g()
来源：http://dali.zhongyouzk.top/Article/details/gtkdsozruh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gaohongyu789.top/Article/details/gtqivygsxj.html

JS:   async function f() { await g(); }
来源：http://dali.ydzc1.top/Article/details/gtcoohmzbz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnqzz.top/Article/details/gtfrjvxpel.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.pycfn.com/Article/details/gtmgsomewx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jyoumei.cn/Article/details/gtopmdqfww.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ydzc1.top/Article/details/gtvxqzfgsr.html

C#:   async Task F() { await G(); }
来源：http://dali.cqqwz.cn/Article/details/gtwlpltojx.html

[O05] 并发执行并等待全部完成
来源：http://dali.meibo888.top/Article/details/gtvybncwfm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yuanzhike.top/Article/details/gtselngiae.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xziqi.cn/Article/details/gtbhaeefls.html

JS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gtpjmuyfou.html

TS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gtphnwinby.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhoulong.xyz/Article/details/gtcpfjijjc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xylfe.cn/Article/details/gtsgxygujq.html

Ruby: threads.map(&:join)
来源：http://dali.sweek.top/Article/details/gtcdoeyixo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.dianchejie.cn/Article/details/gturpxcnyp.html

[O06] 使用进程池
来源：http://dali.jiagoushi.top/Article/details/gthprejnav.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuetiantiany.cn/Article/details/gtmulnyuwr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.svipenyu.cn/Article/details/gtyaxvxrym.html

JS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gtruunsdmb.html

TS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gtpcuuqxck.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hysaishi.cn/Article/details/gthgerotob.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgaszzehb.html

Ruby: // fork 块
来源：http://dali.cashguo.top/Article/details/gthyfydlji.html

C#:   Parallel.For
来源：http://dali.meibo888.top/Article/details/gtlpdbxecu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvchpxdf.html

P. 常用工具函数
来源：http://dali.gaohongyu789.top/Article/details/gtdydoctvu.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtkswapamp.html

[P01] 生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gtccqblcug.html

Py:   str(uuid.uuid4())
来源：http://dali.fengsongda.top/Article/details/gtbtvjzfqx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tianlin.xyz/Article/details/gtzlyzvslg.html

JS:   crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gttylupkwy.html

TS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtydvyhxjt.html

Java: UUID.randomUUID().toString()
来源：http://dali.c1oappe.top/Article/details/gtxobxdvxa.html

Go:   // 用 github.com/google/uuid
来源：http://dali.havefunace.top/Article/details/gtnavpnpxb.html

Ruby: SecureRandom.uuid
来源：http://dali.316326.xyz/Article/details/gtcmumwkrj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258.top/Article/details/gtyerijvau.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangshuangyany.cn/Article/details/gtoxxdsfyk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.andypj.xyz/Article/details/gthzwwgeib.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.0kj1m.cn/Article/details/gtclszgfbo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zycfv.cn/Article/details/gtjgiyovnr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ydzc1.top/Article/details/gtagghgajh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttascezgn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.0kj1m.cn/Article/details/gtjllpblxn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxinkj.top/Article/details/gtjuixjzys.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cucudq.cn/Article/details/gtdbrbsnkk.html

[P03] 生成短随机字符串
来源：http://dali.zycfv.cn/Article/details/gtihtxgrbs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.daxiang520.top/Article/details/gthusbejlx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dianchejie.cn/Article/details/gtrmvcjsfz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gtbyheeusx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gtubjoufow.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yangfankeji.com/Article/details/gtcqfyaprn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnxiangtu.top/Article/details/gtggpcutne.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ydzc1.top/Article/details/gtznpxqxjy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jyoumei.cn/Article/details/gtkixrgkyj.html

[P04] 求长度
来源：http://dali.yuanzhike.top/Article/details/gtoirtovtl.html


<!-- 参考信息 -->