代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cpudzivr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tianlin.xyz/Article/details/gt2cfmqqnlj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cqqwz.cn/Article/details/gt2ppagmlde.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.birdmap.top/Article/details/gt2mdpesdmg.html

[L07] 处理 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2itiasdkv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dashuyun.cn/Article/details/gt2kkqrbled.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gogol.net.cn/Article/details/gt2hcuyjsdl.html

JS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gt2wgmvtqje.html

TS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gt2vgczkxoz.html

Java: resp.statusCode()
来源：http://dali.nanxuanxn.top/Article/details/gt2nfawzhqa.html

Go:   resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gt2ftehquau.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gt2upvcvtpe.html

C#:   (int)resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gt2okvqdrgm.html

[L08] 并发请求多个地址
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bsylrrat.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gt2tuudglee.html

PHP:  curl_multi_init() 系列
来源：http://dali.pycfn.com/Article/details/gt2borwzvtx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gt2fvvgwqrk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gt2utfqaxeo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xylfe.cn/Article/details/gt2rpqbyqdo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guannengcc.top/Article/details/gt2ygtzcdsi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.9152youxi.cn/Article/details/gt2syynjehh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.meibo888.top/Article/details/gt2ijidnxvo.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2lrslnpqi.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnqzz.top/Article/details/gt2xlalkwfl.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2zuivqpey.html

[M01] 读取命令行参数
来源：http://dali.jianghu66.top/Article/details/gt2qnddgxdt.html

Py:   sys.argv[1:]
来源：http://dali.jlsjyb.cn/Article/details/gt2rswsaewo.html

PHP:  $argv;  $argc;
来源：http://dali.sxryk.cn/Article/details/gt2wjxmkmdv.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gt2njklbdpr.html

TS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mznoxesg.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gt2llmrmotg.html

Go:   os.Args[1:]
来源：http://dali.smart0.xyz/Article/details/gt2vybsedqo.html

Ruby: ARGV
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhpsbplp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sgzckmrh.html

[M02] 读取环境变量
来源：http://dali.aizwys.cn/Article/details/gt2vwcjlqhv.html

Py:   os.environ.get("HOME")
来源：http://dali.ppjwa.cn/Article/details/gt2synsygxg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gt2xuyadenu.html

JS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gt2njdlncjz.html

TS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gt2smrqhaiw.html

Java: System.getenv("HOME")
来源：http://dali.316326.xyz/Article/details/gt2uipzrevb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gt2iyjncolf.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258888.top/Article/details/gt2pampovhl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2pmtinyca.html

[M03] 执行外部命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ejcelhfd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigfzy.top/Article/details/gt2arfsicmf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dianchejie.cn/Article/details/gt2nukmtcmj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2itpbayuq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gt2uuiiofjk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.havefunace.top/Article/details/gt2kpfgjooe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kmncceve.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ivvv.top/Article/details/gt2sdotsrmj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgfzy.top/Article/details/gt2zazrphrb.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qlxwlpdt.html

Py:   os.getcwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2lcdkoezg.html

PHP:  getcwd();
来源：http://dali.nwbrower.top/Article/details/gt2tinzxrgg.html

JS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gt2nrpfnukv.html

TS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2zejghtxi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.iojbl.cn/Article/details/gt2izjtlaha.html

Go:   os.Getwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2isqefrlo.html

Ruby: Dir.pwd
来源：http://dali.shangyingyoupin.top/Article/details/gt2ofltezqd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenzaomai.com/Article/details/gt2nxlejszd.html

[M05] 设置退出码
来源：http://dali.xinyue.icu/Article/details/gt2mpbyjkqk.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2odbmtqhs.html

PHP:  exit(1);
来源：http://dali.bjfxy.top/Article/details/gt2toyouclz.html

JS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2nkkacqpb.html

TS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2bbvfgxgw.html

Java: System.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2lqimzmrh.html

Go:   os.Exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bltuwyam.html

Ruby: exit 1
来源：http://dali.snrcjt.cn/Article/details/gt2najgtiea.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.smart0.xyz/Article/details/gt2oeivikec.html

[M06] 向标准错误输出
来源：http://dali.zhoulong.xyz/Article/details/gt2ynzzivvu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hammf.cn/Article/details/gt2izkpalka.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daxiang520.top/Article/details/gt2fwbakrno.html

JS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gt2pdlezdrk.html

TS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gt2vjbmdhbf.html

Java: System.err.println("err")
来源：http://dali.xinyue.icu/Article/details/gt2dxcyjikx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zycfv.cn/Article/details/gt2nneviwyq.html

Ruby: warn "err"
来源：http://dali.pycfn.com/Article/details/gt2mlzljbkc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sufxvd.cn/Article/details/gt2tkmmpnwa.html

[M07] 判断是否为主入口
来源：http://dali.hysaishi.cn/Article/details/gt2rbhgyvno.html

Py:   if __name__ == "__main__":
来源：http://dali.ppjwa.cn/Article/details/gt2qjwdayde.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aibaodan.cn/Article/details/gt2wancpodw.html

JS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gt2srblrxjg.html

TS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gt2uezyacem.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2mupxqrqk.html

Go:   func main()
来源：http://dali.snrcjt.cn/Article/details/gt2seulchcc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxinkj.top/Article/details/gt2bgsnpqso.html

C#:   static void Main(string[] args)
来源：http://dali.9152youxi.cn/Article/details/gt2wyfuceqo.html

[M08] 获取系统与运行时信息
来源：http://dali.gzhubu.top/Article/details/gt2gaxyxqoo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aizwys.cn/Article/details/gt2pbezofut.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.redwolf501.top/Article/details/gt2mcqdwpzo.html

JS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gt2zcrzdayq.html

TS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gt2ctojcgwv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daria6918.cn/Article/details/gt2dahohscc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hysaishi.cn/Article/details/gt2tozncvgw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yonumen.top/Article/details/gt2hnkozaxs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.smart0.xyz/Article/details/gt2bbqtbesx.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2tleukxkw.html

N. 数据结构与算法
来源：http://dali.cashguo.top/Article/details/gt2iopwzknk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2wdvuvrve.html

[N01] 二分查找（有序数组）
来源：http://dali.ybcxt.top/Article/details/gt2actwglsy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2cwdcowzz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cdnleiting.top/Article/details/gt2ogoppbix.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gt2hxftfjot.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gt2jvzmgpet.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gt2tvovpodc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2jxgbxlvs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gaohongyu789.top/Article/details/gt2yhmlbrdj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2vydfgwms.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxuanxn.top/Article/details/gt2ctvlmgqw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gt2duehftiw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.snrcjt.cn/Article/details/gt2spvhgnim.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gt2ikbxcukz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gt2vuribgmx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daxiang520.top/Article/details/gt2ydktayfx.html

Go:   slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gt2jdfyluoh.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rsrhlais.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.9152youxi.cn/Article/details/gt2epsydxdb.html

[N03] 快速排序（分治示例）
来源：http://dali.jqgfzy.top/Article/details/gt2jayavppr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.316326.xyz/Article/details/gt2hqttdbjv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shuidangran.top/Article/details/gt2ufvuaqxa.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gt2akmdfbvg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gt2ckyhaxkc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuetiantiany.cn/Article/details/gt2mpifnpxi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ojbqgfre.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenlongwang.top/Article/details/gt2psmfivxi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gaohongyu789.top/Article/details/gt2rgalfjeo.html

[N04] 斐波那契数列
来源：http://dali.yj20258888.top/Article/details/gt2ykyhtazo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gogol.net.cn/Article/details/gt2viowetya.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xisekkqj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mdvuftft.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gt2psepmswv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gt2lsmlleio.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shzxlz.cn/Article/details/gt2byzrpvnn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lffofjit.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gt2hezcwsfg.html

[N05] 最大公约数
来源：http://dali.gzhubu.top/Article/details/gt2wkshcbaq.html

Py:   math.gcd(a, b)
来源：http://dali.dashuyun.cn/Article/details/gt2pbwbszrh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbcexfl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gt2gjveriak.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gt2wvxyfliu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ppjwa.cn/Article/details/gt2ogywntmo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgfzy.top/Article/details/gt2lbjeulrw.html

Ruby: a.gcd(b)
来源：http://dali.zhoulong.xyz/Article/details/gt2gtqwnzpx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pfgkigla.html

[N06] 判断回文字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2cexcldll.html

Py:   s == s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gt2kiwoosxy.html

PHP:  $s === strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gt2wzjfpxws.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gt2gkenjwyo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfadiefh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnxiangtu.top/Article/details/gt2rlftbkpx.html

Go:   // 双指针从两端比较
来源：http://dali.ydzc1.top/Article/details/gt2ycotkpdd.html

Ruby: s == s.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gt2hokzzjjg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gt2lhnjftdj.html

[N07] 两数之和（返回下标）
来源：http://dali.zhongyouzk.top/Article/details/gt2lrlozunx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jyoumei.cn/Article/details/gt2tdkmlfcy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.svipenyu.cn/Article/details/gt2mmdctylk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.fengsongda.top/Article/details/gt2sfpglpyr.html

TS:   // 手写 Map<string, number>
来源：http://dali.ybcxt.top/Article/details/gt2xlcugvfp.html

Java: // 手写 HashMap
来源：http://dali.jinqigfzy.top/Article/details/gt2upnkxseg.html

Go:   // 手写 map[int]int
来源：http://dali.ybcxt.top/Article/details/gt2gnnekjza.html

Ruby: // 手写 Hash
来源：http://dali.jianghu66.top/Article/details/gt2mikbnmar.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cashguo.top/Article/details/gt2visglhmn.html

[N08] 生成全排列
来源：http://dali.dianchejie.cn/Article/details/gt2yqsgocnt.html

Py:   itertools.permutations(arr)
来源：http://dali.cucudq.cn/Article/details/gt2bixrlkci.html

PHP:  // 手写递归交换
来源：http://dali.cheryme.top/Article/details/gt2oirzwabh.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2elsmcpca.html

TS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2fccgnevz.html

Java: // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gt2srodpvnd.html

Go:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gt2bixraqtg.html

Ruby: arr.permutation.to_a
来源：http://dali.havefunace.top/Article/details/gt2hpazeklk.html

C#:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gt2qzhhvajt.html

[N09] 栈与队列
来源：http://dali.0kj1m.cn/Article/details/gt2yzeirtno.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tianlin.xyz/Article/details/gt2zmglnitv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gt2mdveruur.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xylfe.cn/Article/details/gt2eanzylhu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuanzx.com/Article/details/gt2ysqicgjm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ivvv.top/Article/details/gt2eospwzxg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guannengcc.top/Article/details/gt2rrphsctx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gt2oyoqvere.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuanzx.com/Article/details/gt2cbvgxwdg.html

[N10] 链表节点定义
来源：http://dali.dashuyun.cn/Article/details/gt2acsacbcf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gzhubu.top/Article/details/gt2scqugizv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jianghu66.top/Article/details/gt2vxwezhhd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xinyue.icu/Article/details/gt2cjuxlmfe.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxinkj.top/Article/details/gt2badjamiz.html

Java: class Node { int v; Node next; }
来源：http://dali.yueranfly.top/Article/details/gt2fcjvtrlq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ppjwa.cn/Article/details/gt2wkehjcop.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yonumen.top/Article/details/gt2qcgicuni.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ybioksmo.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwzsgfe.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yongpay.top/Article/details/gt2nbthiaej.html

PHP:  // 手写递归函数
来源：http://dali.jiagoushi.top/Article/details/gt2sknmgrzl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gt2iijsecbw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gt2fdhuzfkg.html

Java: // 手写递归
来源：http://dali.aizwys.cn/Article/details/gt2oilzouoc.html

Go:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gt2nrxulrms.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hammf.cn/Article/details/gt2dxhfczlg.html

C#:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2kruoqwei.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daria6918.cn/Article/details/gt2btpfhdqj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangdashe.top/Article/details/gt2xlooxbdy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.0kj1m.cn/Article/details/gt2iwguuibs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gaohongyu789.top/Article/details/gt2iqbgngci.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gt2mzceqlrj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gt2clrblauy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenzaomai.com/Article/details/gt2taraqsqm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhongyouzk.top/Article/details/gt2mfhurvne.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gt2ohywszsx.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2szeqkrcs.html

O. 并发与异步
来源：http://dali.yangfankeji.com/Article/details/gt2ktmlukzq.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2rzphddrh.html

[O01] 启动一个线程
来源：http://dali.wangshuangyany.cn/Article/details/gt2qkmlcoqd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.mhx1999.top/Article/details/gt2pzrpkojx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxinkj.top/Article/details/gt2rkgskmza.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daxiang520.top/Article/details/gt2kdspbexg.html

TS:   // 同 JS
来源：http://dali.chenzaomai.com/Article/details/gt2czjvxekj.html

Java: new Thread(() -> f()).start()
来源：http://dali.316326.xyz/Article/details/gt2dadckjho.html

Go:   go f()
来源：http://dali.yangfankeji.com/Article/details/gt2esvrxtqy.html

Ruby: Thread.new { f }
来源：http://dali.cheryme.top/Article/details/gt2idbcwste.html

C#:   Task.Run(() => F());
来源：http://dali.9152youxi.cn/Article/details/gt2nfbqebho.html

[O02] 使用线程池
来源：http://dali.jqgufenzy.top/Article/details/gt2shxwwyis.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tianlin.xyz/Article/details/gt2blhimgoj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cdnleiting.top/Article/details/gt2sawvvawk.html

JS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gt2grioanbg.html

TS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gt2zbbvnaau.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.iojbl.cn/Article/details/gt2fypcjrxe.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aibaodan.cn/Article/details/gt2ilmnrejh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.guannengcc.top/Article/details/gt2wzinnnar.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhixingplan.top/Article/details/gt2xxuayqua.html

[O03] 加锁保护共享数据
来源：http://dali.tianlin.xyz/Article/details/gt2oksjzykx.html

Py:   with lock: shared += 1
来源：http://dali.gogol.net.cn/Article/details/gt2qdybcatw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.c1oappe.top/Article/details/gt2duewkmnp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.316326.xyz/Article/details/gt2vfjkybbz.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gt2cbbmhbgy.html

Java: synchronized (this) { shared++; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rkjhpzix.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cashguo.top/Article/details/gt2bysoowzk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxuanxn.top/Article/details/gt2fpocwawa.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mseuzxrp.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dyflgzom.html

Py:   async def f():⏎    await g()
来源：http://dali.yuanzhike.top/Article/details/gt2hyudwmlh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gaohongyu789.top/Article/details/gt2phkgflac.html

JS:   async function f() { await g(); }
来源：http://dali.c1oappe.top/Article/details/gt2qbjknsls.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258.top/Article/details/gt2ujjjwsgp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tianlin.xyz/Article/details/gt2bckaemkq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhengqikj.top/Article/details/gt2opzxvjyg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gotoacloud.top/Article/details/gt2xidjkibo.html

C#:   async Task F() { await G(); }
来源：http://dali.hywenlv.cn/Article/details/gt2xqoklfer.html

[O05] 并发执行并等待全部完成
来源：http://dali.birdmap.top/Article/details/gt2uafpfyxl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2pttyxyqx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.quarkkingdee.top/Article/details/gt2gdsuxfom.html

JS:   await Promise.all(tasks)
来源：http://dali.guowangkeji.top/Article/details/gt2mghlycfh.html

TS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gt2utsqbpcd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gzhubu.top/Article/details/gt2ktovhtmd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jyoumei.cn/Article/details/gt2pgvvsxjf.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258888.top/Article/details/gt2kzuqwhlr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guowangkeji.top/Article/details/gt2hlrbfvwg.html

[O06] 使用进程池
来源：http://dali.yuxming.cn/Article/details/gt2padwpmmk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnqzz.top/Article/details/gt2xnnuopbm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj202588.top/Article/details/gt2howorpgw.html

JS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cyzajlsd.html

TS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gt2jgtbgvny.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shuidangran.top/Article/details/gt2iderybzj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenlongwang.top/Article/details/gt2sgoqyofx.html

Ruby: // fork 块
来源：http://dali.havefunace.top/Article/details/gt2pdjwdafa.html

C#:   Parallel.For
来源：http://dali.ivvv.top/Article/details/gt2vydccwrv.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2fqgdhzyz.html

P. 常用工具函数
来源：http://dali.jinqigufen.top/Article/details/gt2dzxpeexv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2ucxwexqi.html

[P01] 生成 UUID
来源：http://dali.feifeiyinyue.top/Article/details/gt2ewvrpxlm.html

Py:   str(uuid.uuid4())
来源：http://dali.gaohongyu789.top/Article/details/gt2fervboyq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jorqganp.html

JS:   crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vehgbilx.html

TS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gt2slqdncdg.html

Java: UUID.randomUUID().toString()
来源：http://dali.jyoumei.cn/Article/details/gt2cltuizuv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.birdmap.top/Article/details/gt2zylkkwsx.html

Ruby: SecureRandom.uuid
来源：http://dali.jlsjyb.cn/Article/details/gt2sbbabfld.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258888.top/Article/details/gt2tfdntdsl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhengqikj.top/Article/details/gt2vzplxbjt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jqgfzy.top/Article/details/gt2ptpazeea.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ppjwa.cn/Article/details/gt2zvqjfudl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cheryme.top/Article/details/gt2xdshyclb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pycfn.com/Article/details/gt2bmbmrgir.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tianlin.xyz/Article/details/gt2uiikqmpm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aibaodan.cn/Article/details/gt2rfgsgwyd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sxryk.cn/Article/details/gt2tysqwity.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cucudq.cn/Article/details/gt2coiiqcfl.html

[P03] 生成短随机字符串
来源：http://dali.haohaochexian.top/Article/details/gt2eusyujkq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cucudq.cn/Article/details/gt2wnunanbw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dianchejie.cn/Article/details/gt2roykzrmy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dtuhpldr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gt2vntadfui.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzvzgbyj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.0kj1m.cn/Article/details/gt2yubhvsmq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hammf.cn/Article/details/gt2abzpbpxl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.haohaochexian.top/Article/details/gt2oxpwyolo.html

[P04] 求长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xzewystq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ivvv.top/Article/details/gt2wrpfyull.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gt2hlfnfzml.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangdashe.top/Article/details/gt2sfkijrvv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258888.top/Article/details/gt2jfxjmzfx.html


<!-- 参考信息 -->