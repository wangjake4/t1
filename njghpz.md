代发 wailian999

Py:   resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtjwlkmovm.html

PHP:  json_decode($body, true);
来源：http://dali.yonumen.top/Article/details/gtwdjqqzmb.html

JS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gtubxdzlix.html

TS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gtvzvkumxu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guannengcc.top/Article/details/gtkzlysdmf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhengqikj.top/Article/details/gtcjnmimcn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgufenzy.top/Article/details/gtmxccbbuy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xinyue.icu/Article/details/gtgdgohrtg.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gtrjeneqfm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xziqi.cn/Article/details/gtjxltzwsx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.svipenyu.cn/Article/details/gtvmolhgxz.html

JS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gtuxfqxfru.html

TS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gttlbiozzd.html

Java: resp.statusCode()
来源：http://dali.hnxiangtu.top/Article/details/gtjgkxkqkq.html

Go:   resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflynheut.html

Ruby: resp.code.to_i
来源：http://dali.hfpthk.cn/Article/details/gtiyezkdrz.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvnvfmar.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqvbnbxx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hywenlv.cn/Article/details/gtpwaqotsz.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhoulong.xyz/Article/details/gtvgqheigo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gtfotiknkq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtdbphnhvk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnqzz.top/Article/details/gtmyseskyd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuxming.cn/Article/details/gtpxjjjxyn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhengqikj.top/Article/details/gtrxcedsjd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hywenlv.cn/Article/details/gtggbfthae.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtowwqfxeb.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhongyouzk.top/Article/details/gtbygfsjyj.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gttchxnkts.html

[M01] 读取命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gtcceldzqm.html

Py:   sys.argv[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtaikhunpe.html

PHP:  $argv;  $argc;
来源：http://dali.aibaodan.cn/Article/details/gtjudndrjx.html

JS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gtzizpsocz.html

TS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gtnrnraghi.html

Java: args 数组（main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gttlylqqju.html

Go:   os.Args[1:]
来源：http://dali.yueranfly.top/Article/details/gtzrmegtgt.html

Ruby: ARGV
来源：http://dali.hysaishi.cn/Article/details/gtzesovlxx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gtxnvtsvrq.html

[M02] 读取环境变量
来源：http://dali.cashguo.top/Article/details/gthviaaidj.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtxldyetkj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gtxecugjku.html

JS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gteqoeijmj.html

TS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gtyxykpkzg.html

Java: System.getenv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtmdrpfaxo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.birdmap.top/Article/details/gtfhhnbqlr.html

Ruby: ENV["HOME"]
来源：http://dali.ydzc1.top/Article/details/gttfhpybqg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorelvmih.html

[M03] 执行外部命令
来源：http://dali.cucudq.cn/Article/details/gtbbzraxxl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqocflwd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cqqwz.cn/Article/details/gtiroshrjz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gtryzemypq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gthaqvlzaw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.kuanghao11.cn/Article/details/gtxslcrroc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hywenlv.cn/Article/details/gtpczxjwhn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuanzx.com/Article/details/gtcxhtcqny.html

C#:   Process.Start("ls", "-l");
来源：http://dali.birdmap.top/Article/details/gtkctsxurb.html

[M04] 获取当前工作目录
来源：http://dali.pycfn.com/Article/details/gtngirwozi.html

Py:   os.getcwd()
来源：http://dali.dashuyun.cn/Article/details/gtmrgnrdsc.html

PHP:  getcwd();
来源：http://dali.quarkkingdee.top/Article/details/gtvovfhmxo.html

JS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gtwivmbarg.html

TS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gthevxxpxm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aibaodan.cn/Article/details/gtvxtlidnk.html

Go:   os.Getwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfyhgmrac.html

Ruby: Dir.pwd
来源：http://dali.sxryk.cn/Article/details/gtzkqqrkhs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sufxvd.cn/Article/details/gtnapzwcdz.html

[M05] 设置退出码
来源：http://dali.feifeiyinyue.top/Article/details/gtjseljcso.html

Py:   sys.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtfcprovpk.html

PHP:  exit(1);
来源：http://dali.ybcxt.top/Article/details/gtbukkudhh.html

JS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtwivaantj.html

TS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtwitykkxu.html

Java: System.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtwhihmhrl.html

Go:   os.Exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gthwpfdayt.html

Ruby: exit 1
来源：http://dali.ydzc1.top/Article/details/gtqebfpfkx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cheryme.top/Article/details/gtenzprkan.html

[M06] 向标准错误输出
来源：http://dali.bjfxy.top/Article/details/gtujpkgxdx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gtqfniympj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ydzc1.top/Article/details/gthqonbrnn.html

JS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gtfrknwyra.html

TS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gthmexsvsf.html

Java: System.err.println("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gthebemtax.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gaohongyu789.top/Article/details/gtbsrdsvwn.html

Ruby: warn "err"
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhjndjom.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yangfankeji.com/Article/details/gtaoyglxco.html

[M07] 判断是否为主入口
来源：http://dali.yuanzhike.top/Article/details/gtkyxczvcz.html

Py:   if __name__ == "__main__":
来源：http://dali.cashguo.top/Article/details/gtfgoxwjdd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.c1oappe.top/Article/details/gtbauyzesu.html

JS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmrbusvk.html

TS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gtmwswbluf.html

Java: public static void main(String[] args)
来源：http://dali.gaohongyu789.top/Article/details/gtbsbyytgg.html

Go:   func main()
来源：http://dali.cqqwz.cn/Article/details/gtlaqgdlqk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aibaodan.cn/Article/details/gtnmlakjxn.html

C#:   static void Main(string[] args)
来源：http://dali.c1oappe.top/Article/details/gtgjwxcbvq.html

[M08] 获取系统与运行时信息
来源：http://dali.zhiwuduotai.top/Article/details/gtsohcbcqp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxujjyitn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.9152youxi.cn/Article/details/gtvebokhkc.html

JS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gtjbflbqea.html

TS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gtayieiiva.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhongyouzk.top/Article/details/gttichitjh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenlongwang.top/Article/details/gtyhchikkg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nwbrower.top/Article/details/gtfqbkhtxi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yueranfly.top/Article/details/gtwxauzbiv.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtzicvprrr.html

N. 数据结构与算法
来源：http://dali.hnxiangtu.top/Article/details/gthjmkeyfx.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtfmimymal.html

[N01] 二分查找（有序数组）
来源：http://dali.nwbrower.top/Article/details/gtwiiousos.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyckfgijj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daxiang520.top/Article/details/gtwudptwvp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtcwmyiuql.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtjefyuuqv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtjcqtuchz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtiqcfrwsf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xinyue.icu/Article/details/gtxmhswgco.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtwnumrqhr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shangyingyoupin.top/Article/details/gtgvgjdtsc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gtavussxax.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yongpay.top/Article/details/gtvummrvvc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gtdcvfwhrq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gtrtdbsbwr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zdqjudy.top/Article/details/gtxquzmgjc.html

Go:   slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gtpcuebeab.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gtiuyngdbo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jlsjyb.cn/Article/details/gtiswjzkhj.html

[N03] 快速排序（分治示例）
来源：http://dali.havefunace.top/Article/details/gtwaplwqqo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yanxiufei.cn/Article/details/gtzpoitcun.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yangfankeji.com/Article/details/gtdopsnwxr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gtczmosczw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gtrwdbhopz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sweek.top/Article/details/gtpggkpcyj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tian-w.cn/Article/details/gtkkuoscmw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenzaomai.com/Article/details/gthuwbcrcy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.feifeiyinyue.top/Article/details/gtlhzhynok.html

[N04] 斐波那契数列
来源：http://dali.redwolf501.top/Article/details/gtjrbdiema.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gtawumeoak.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj202588.top/Article/details/gtiofutafw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gtognxgrns.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtbaizxfvf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.mhx1999.top/Article/details/gtvuguqiec.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlblarod.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sufxvd.cn/Article/details/gtfikdapel.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtjubtfajj.html

[N05] 最大公约数
来源：http://dali.ivvv.top/Article/details/gtuvpdctuo.html

Py:   math.gcd(a, b)
来源：http://dali.yonumen.top/Article/details/gtjgoaxdjj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbnovwod.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gtiudbscut.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtqbyhdfkt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zdqjudy.top/Article/details/gtfgzlqzqh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zycfv.cn/Article/details/gtlmxjaata.html

Ruby: a.gcd(b)
来源：http://dali.vqdsnc.cn/Article/details/gtramznbto.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yvedp.cn/Article/details/gtygowvshs.html

[N06] 判断回文字符串
来源：http://dali.shzxlz.cn/Article/details/gtrbyvuycj.html

Py:   s == s[::-1]
来源：http://dali.fengsongda.top/Article/details/gthdwgjnwh.html

PHP:  $s === strrev($s);
来源：http://dali.cqqwz.cn/Article/details/gthetavzes.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtiglawvsv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtoudikhty.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj202588.top/Article/details/gtbtgrwmqc.html

Go:   // 双指针从两端比较
来源：http://dali.pengpengdd.cyou/Article/details/gtomfqdrxa.html

Ruby: s == s.reverse
来源：http://dali.yuanzhike.top/Article/details/gtrsbjdyfd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gtonleznui.html

[N07] 两数之和（返回下标）
来源：http://dali.yj202588.top/Article/details/gtbovbkoqw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jianghu66.top/Article/details/gtxacnqdhg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.snrcjt.cn/Article/details/gtqlfkiunu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuanzhike.top/Article/details/gtklrtoyfk.html

TS:   // 手写 Map<string, number>
来源：http://dali.hammf.cn/Article/details/gtltltnauk.html

Java: // 手写 HashMap
来源：http://dali.zdqjudy.top/Article/details/gthxaukljh.html

Go:   // 手写 map[int]int
来源：http://dali.cashguo.top/Article/details/gtzqywkbzv.html

Ruby: // 手写 Hash
来源：http://dali.yuanzhike.top/Article/details/gtoreqalyw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zdqjudy.top/Article/details/gtcozkulvm.html

[N08] 生成全排列
来源：http://dali.aizwys.cn/Article/details/gthekwfnez.html

Py:   itertools.permutations(arr)
来源：http://dali.hywenlv.cn/Article/details/gtkfoctgev.html

PHP:  // 手写递归交换
来源：http://dali.jqgufenzy.top/Article/details/gtxckchgue.html

JS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtkurcsfpu.html

TS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtsdmyasjc.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gttsyffexw.html

Go:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtosfhhuzt.html

Ruby: arr.permutation.to_a
来源：http://dali.cashguo.top/Article/details/gtqsxffwob.html

C#:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtprioowfv.html

[N09] 栈与队列
来源：http://dali.xuanzx.com/Article/details/gtlhhlzdjs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258.top/Article/details/gtjprdzfjw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gtkmarscgd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gtxshqvcib.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gotoacloud.top/Article/details/gtqafwhjfc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.birdmap.top/Article/details/gteiqeaxnw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guowangkeji.top/Article/details/gtqgpsjivr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtnqdnnisb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuanzhike.top/Article/details/gtpkgdrzbs.html

[N10] 链表节点定义
来源：http://dali.andypj.xyz/Article/details/gtqwvvgfrj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhoulong.xyz/Article/details/gtcycpakoj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.kuanghao11.cn/Article/details/gtiowibbcd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yangfankeji.com/Article/details/gtjbqlomyv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cqqwz.cn/Article/details/gtyrgyblyx.html

Java: class Node { int v; Node next; }
来源：http://dali.cdnleiting.top/Article/details/gtlkuailfi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fzhhl.top/Article/details/gtnjlnimrj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.0kj1m.cn/Article/details/gtjywzveer.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxuanxn.top/Article/details/gtawpddxce.html

[N11] 二叉树中序遍历
来源：http://dali.wangdashe.top/Article/details/gtweomfupk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tian-w.cn/Article/details/gtlodksxss.html

PHP:  // 手写递归函数
来源：http://dali.cdnleiting.top/Article/details/gtonuywjey.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gtxusfpfug.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gtnmfopsti.html

Java: // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtjaqundkz.html

Go:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gtcaapjaae.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tian-w.cn/Article/details/gtaghjkhtg.html

C#:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gtslvndapt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuetiantiany.cn/Article/details/gtkylydicc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangdashe.top/Article/details/gtjlfbzywb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jyoumei.cn/Article/details/gtmsadigqq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gteuqqotcp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gtwzcmcxki.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jlsjyb.cn/Article/details/gtltqynkqe.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj202588.top/Article/details/gtxyjxsqhd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gogol.net.cn/Article/details/gtqyfxzwer.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gtlldfvvxw.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtoqlzgtqz.html

O. 并发与异步
来源：http://dali.meibo888.top/Article/details/gtgxgaleqt.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtymzsnqtc.html

[O01] 启动一个线程
来源：http://dali.kuanghao11.cn/Article/details/gttziqalcc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhixingplan.top/Article/details/gtjfkqqefu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aibaodan.cn/Article/details/gtibjqciox.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cdnleiting.top/Article/details/gtbexedbzl.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gtjmoeavcl.html

Java: new Thread(() -> f()).start()
来源：http://dali.shzxlz.cn/Article/details/gtsvsflzsk.html

Go:   go f()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbovqerm.html

Ruby: Thread.new { f }
来源：http://dali.redwolf501.top/Article/details/gtlqhvbibh.html

C#:   Task.Run(() => F());
来源：http://dali.zhongyouzk.top/Article/details/gtyhodfesi.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gttczwqgun.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhengqikj.top/Article/details/gtplzygjlu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.pycfn.com/Article/details/gtcbypiiaz.html

JS:   // worker_threads 线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtyzluzxvm.html

TS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gtgakgddwl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.bjfxy.top/Article/details/gtuuondcgz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.redwolf501.top/Article/details/gttcsszxch.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xylfe.cn/Article/details/gtmykthayi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jiagoushi.top/Article/details/gtyemvjohq.html

[O03] 加锁保护共享数据
来源：http://dali.yuxming.cn/Article/details/gtiianivjw.html

Py:   with lock: shared += 1
来源：http://dali.cashguo.top/Article/details/gttghrmdmr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrpdcyco.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tanke756.top/Article/details/gtqzwdzxwt.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gtuaegtfoa.html

Java: synchronized (this) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gtprnznitd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shzxlz.cn/Article/details/gtlpasvfhu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.iojbl.cn/Article/details/gtyqpycyxq.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gtlyqcqnoc.html

[O04] 定义异步函数并等待
来源：http://dali.zycfv.cn/Article/details/gtyjzbbogd.html

Py:   async def f():⏎    await g()
来源：http://dali.havefunace.top/Article/details/gtgczmwoyl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.andypj.xyz/Article/details/gttknjlipa.html

JS:   async function f() { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtxhrvrbqp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj202588.top/Article/details/gtnufocjfs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zdqjudy.top/Article/details/gtlqxfpzks.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dashuyun.cn/Article/details/gttlcqavsu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shzxlz.cn/Article/details/gtwzzhoqdz.html

C#:   async Task F() { await G(); }
来源：http://dali.cucudq.cn/Article/details/gtvraxuqob.html

[O05] 并发执行并等待全部完成
来源：http://dali.sweek.top/Article/details/gtztlmkqzt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ybcxt.top/Article/details/gtmjizlyyu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daxiang520.top/Article/details/gtrfupvoit.html

JS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gtklfzgirk.html

TS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtxsdcdsul.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tanke756.top/Article/details/gtmliqruiy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jianghu66.top/Article/details/gtxifazdqp.html

Ruby: threads.map(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gtusyjqake.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yvedp.cn/Article/details/gtvtytwdkk.html

[O06] 使用进程池
来源：http://dali.jlsjyb.cn/Article/details/gtfupudgid.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sysykeji.top/Article/details/gtvvmbgpbx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenzaomai.com/Article/details/gtzjpgvyad.html

JS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gtsxiprebg.html

TS:   // child_process / cluster 模块
来源：http://dali.cdnleiting.top/Article/details/gtyogbfqdb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jiagoushi.top/Article/details/gtybaqkqkc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gogol.net.cn/Article/details/gtrtarmutt.html

Ruby: // fork 块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfaiptzlf.html

C#:   Parallel.For
来源：http://dali.0kj1m.cn/Article/details/gtfkvawrvx.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtwrpgpkxg.html

P. 常用工具函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnppetnwq.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtnbtrhgnc.html

[P01] 生成 UUID
来源：http://dali.xylfe.cn/Article/details/gtnpxarhmb.html

Py:   str(uuid.uuid4())
来源：http://dali.wangdashe.top/Article/details/gtyhqtfxct.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.meibo888.top/Article/details/gthnusbmoe.html

JS:   crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gtihqghzjd.html

TS:   crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gtdsollrur.html

Java: UUID.randomUUID().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtqaptmuvr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shangyingyoupin.top/Article/details/gtvzvpkixk.html

Ruby: SecureRandom.uuid
来源：http://dali.xuetiantiany.cn/Article/details/gtabmbgehy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cucudq.cn/Article/details/gtmrvesfwo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yanxiufei.cn/Article/details/gtmnohtorl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.andypj.xyz/Article/details/gtuypfhsgj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sysykeji.top/Article/details/gtmjjykfrf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cashguo.top/Article/details/gtkienpgae.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.feifeiyinyue.top/Article/details/gtavtqhmcz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtdkloriqv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.pengpengdd.cyou/Article/details/gtnnsjepjx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258888.top/Article/details/gtdoawqdxz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbzudycx.html

[P03] 生成短随机字符串
来源：http://dali.hnxiangtu.top/Article/details/gtbqbksxtv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hysaishi.cn/Article/details/gtizvnlkna.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.smart0.xyz/Article/details/gtdgihcofy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gtefseheih.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gthqnfvgee.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258888.top/Article/details/gtyhgpvxth.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aizwys.cn/Article/details/gtspjojufa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gogol.net.cn/Article/details/gtaticeinj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhiwuduotai.top/Article/details/gtybhyqjnb.html

[P04] 求长度
来源：http://dali.zdqjudy.top/Article/details/gtvxftwyzb.html


<!-- 参考信息 -->