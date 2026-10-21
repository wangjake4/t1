代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnxiangtu.top/Article/details/gtjaddpvxg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gtpmknmpbq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gtokrbqqgn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sweek.top/Article/details/gtjqlhlpom.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fzhhl.top/Article/details/gtbnzlopis.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.bjfxy.top/Article/details/gtdlvwnhjx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtujavtybc.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gtppwnkjot.html

Py:   resp.json()
来源：http://dali.daria6918.cn/Article/details/gtqhkzsayp.html

PHP:  json_decode($body, true);
来源：http://dali.sweek.top/Article/details/gtaigmymig.html

JS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gtzlitudkp.html

TS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gtzbjdrdwt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtttsxngli.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuanzx.com/Article/details/gthrskodbo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuetiantiany.cn/Article/details/gtwzmxohbw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nwbrower.top/Article/details/gtqanfsrwe.html

[L07] 处理 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gtugjdajxb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.316326.xyz/Article/details/gtonclvtzi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj202588.top/Article/details/gtwtouksvo.html

JS:   resp.ok;  resp.status
来源：http://dali.yueranfly.top/Article/details/gtsmepxrdp.html

TS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gtvuktbmkd.html

Java: resp.statusCode()
来源：http://dali.cashguo.top/Article/details/gtihbewfqe.html

Go:   resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gtevjablmh.html

Ruby: resp.code.to_i
来源：http://dali.smart0.xyz/Article/details/gtchjstczn.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjcavqhn.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzznhugzn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.iojbl.cn/Article/details/gtymjvjpls.html

PHP:  curl_multi_init() 系列
来源：http://dali.snrcjt.cn/Article/details/gtqialsrwn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gthtxyhmnv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtbyhnzjhv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cucudq.cn/Article/details/gthuivxusx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sxryk.cn/Article/details/gtbcketvvy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbvxqiwt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtfwmactdy.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtefdlhmcw.html

M. 命令行 / 进程 / 环境
来源：http://dali.gaohongyu789.top/Article/details/gtaiazjkag.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtihtolmnu.html

[M01] 读取命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gtaovmzkss.html

Py:   sys.argv[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtzpohtatd.html

PHP:  $argv;  $argc;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqnwipki.html

JS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfyhxhjae.html

TS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gthqlwohfi.html

Java: args 数组（main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gtdnaoppuu.html

Go:   os.Args[1:]
来源：http://dali.ybcxt.top/Article/details/gtulesnuxx.html

Ruby: ARGV
来源：http://dali.sxryk.cn/Article/details/gtojjccwow.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gtikdpdkxb.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtbcxeqfkm.html

Py:   os.environ.get("HOME")
来源：http://dali.c1oappe.top/Article/details/gtzcjogpmv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gtjplkbppc.html

JS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gtmpxdwjvb.html

TS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gtkxmnkhqt.html

Java: System.getenv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtvrpelxsd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.c1oappe.top/Article/details/gtfxwdukiv.html

Ruby: ENV["HOME"]
来源：http://dali.hongshengwenyu.top/Article/details/gthcmywnwz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtvuhrdist.html

[M03] 执行外部命令
来源：http://dali.smart0.xyz/Article/details/gttxhuslua.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuxming.cn/Article/details/gtzijtnjfy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gtlukpkuwd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gtykbofrfz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gtqbytslfc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigfzy.top/Article/details/gtemhcdevh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.316326.xyz/Article/details/gtjlzpbiwu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pengpengdd.cyou/Article/details/gtibrathpq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuanzhike.top/Article/details/gtxpjikzhe.html

[M04] 获取当前工作目录
来源：http://dali.yueranfly.top/Article/details/gtmxoocivw.html

Py:   os.getcwd()
来源：http://dali.fzhhl.top/Article/details/gtrjxpcmqe.html

PHP:  getcwd();
来源：http://dali.nanxinkj.top/Article/details/gtupymxatd.html

JS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gtjxxypfdq.html

TS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gtjzljjoio.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258888.top/Article/details/gtjszmhszv.html

Go:   os.Getwd()
来源：http://dali.gogol.net.cn/Article/details/gtpnryqhce.html

Ruby: Dir.pwd
来源：http://dali.xuetiantiany.cn/Article/details/gtlfupgfnl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.vqdsnc.cn/Article/details/gttwfwslha.html

[M05] 设置退出码
来源：http://dali.yuanzhike.top/Article/details/gtjmrrgnga.html

Py:   sys.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtpdwlylwp.html

PHP:  exit(1);
来源：http://dali.haohaochexian.top/Article/details/gtmelvipww.html

JS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gtflgcqzgo.html

TS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gthwliezyl.html

Java: System.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtxfuelzdk.html

Go:   os.Exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtgsogqlyy.html

Ruby: exit 1
来源：http://dali.aibaodan.cn/Article/details/gtqubcrbtm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gzhubu.top/Article/details/gtkbrrjzrs.html

[M06] 向标准错误输出
来源：http://dali.sufxvd.cn/Article/details/gtnpzqkbds.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gtlbzowmlg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgfzy.top/Article/details/gtwsxqfmlm.html

JS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gtusecbvga.html

TS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gtkpgccdth.html

Java: System.err.println("err")
来源：http://dali.jinqigfzy.top/Article/details/gtpkowplzn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gotoacloud.top/Article/details/gtdtkbrvdn.html

Ruby: warn "err"
来源：http://dali.birdmap.top/Article/details/gthppzjubu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlkzgrgh.html

[M07] 判断是否为主入口
来源：http://dali.havefunace.top/Article/details/gtshxykvga.html

Py:   if __name__ == "__main__":
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvaqbjxn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnxiangtu.top/Article/details/gtplgmoiwh.html

JS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtvhjkdecr.html

TS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gtnnlkgtms.html

Java: public static void main(String[] args)
来源：http://dali.jinqigufen.top/Article/details/gtbkvofptd.html

Go:   func main()
来源：http://dali.hongshengwenyu.top/Article/details/gttcufmvec.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yueranfly.top/Article/details/gtlxkhbmzb.html

C#:   static void Main(string[] args)
来源：http://dali.316326.xyz/Article/details/gtutojfckh.html

[M08] 获取系统与运行时信息
来源：http://dali.jiagoushi.top/Article/details/gthzdiidau.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sxryk.cn/Article/details/gtjnzjvwyl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.birdmap.top/Article/details/gtezzqvacb.html

JS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gtdmcfzxdz.html

TS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gtlstylqqd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tanke756.top/Article/details/gtuqtcoozn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cheryme.top/Article/details/gtncudjehd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xylfe.cn/Article/details/gtfbunfsgz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zycfv.cn/Article/details/gtzkqxilld.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocmhillo.html

N. 数据结构与算法
来源：http://dali.shangyingyoupin.top/Article/details/gtpknfatvd.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtkcmrjbiw.html

[N01] 二分查找（有序数组）
来源：http://dali.wangdashe.top/Article/details/gtfsetemol.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ivvv.top/Article/details/gtnhvlklxu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daxiang520.top/Article/details/gtbfkuipsh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gthztflmhw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gtcwccyxhk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.316326.xyz/Article/details/gtrmvwtlnu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtlknvqyvf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hfpthk.cn/Article/details/gtjxoedhds.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtzavgotvo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dianchejie.cn/Article/details/gtdtrbsekp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gthroxavlv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuxming.cn/Article/details/gtxhoqfatc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtufxiygtd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtgjkkpaex.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenlongwang.top/Article/details/gtdnjpzzrb.html

Go:   slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtuqdenfnn.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gtezvwpeuo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aibaodan.cn/Article/details/gtquhbpmph.html

[N03] 快速排序（分治示例）
来源：http://dali.havefunace.top/Article/details/gtbsdtiybu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hywenlv.cn/Article/details/gtyrayrmsz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.bjfxy.top/Article/details/gtyrnhglmd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvffwqqq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gtbxwpbgvg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dianchejie.cn/Article/details/gtkweysjvs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zdqjudy.top/Article/details/gtzwwoewoj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangtech.top/Article/details/gthrnhbeaw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gogol.net.cn/Article/details/gtegzzcmbu.html

[N04] 斐波那契数列
来源：http://dali.hywenlv.cn/Article/details/gtktffcadc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gtlxakplmp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcutdrhhg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gtlnklvxdd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtfymlyeni.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.redwolf501.top/Article/details/gtretxaxpr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuxming.cn/Article/details/gtusvboych.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gticihqdjj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtbskhsuux.html

[N05] 最大公约数
来源：http://dali.redwolf501.top/Article/details/gtonzwsaxb.html

Py:   math.gcd(a, b)
来源：http://dali.meibo888.top/Article/details/gtaposzhmt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.svipenyu.cn/Article/details/gtuzzegvfu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtratbmcmr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guowangkeji.top/Article/details/gtkgkjqnkg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daxiang520.top/Article/details/gteaxviqzi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenzaomai.com/Article/details/gtgnkggbaw.html

Ruby: a.gcd(b)
来源：http://dali.mhx1999.top/Article/details/gtbqfiavbv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ybcxt.top/Article/details/gtbdxwwwaz.html

[N06] 判断回文字符串
来源：http://dali.pycfn.com/Article/details/gttuwvhgnc.html

Py:   s == s[::-1]
来源：http://dali.chenjidiqi.icu/Article/details/gtynneoudx.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258888.top/Article/details/gtihnhdwyk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtjmkhidkv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtdjfemwcc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuetiantiany.cn/Article/details/gtfpyokrfa.html

Go:   // 双指针从两端比较
来源：http://dali.yj202588.top/Article/details/gtewlakkpu.html

Ruby: s == s.reverse
来源：http://dali.cashguo.top/Article/details/gtfkmwxixp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tianlin.xyz/Article/details/gtzygxhfdh.html

[N07] 两数之和（返回下标）
来源：http://dali.shangyingyoupin.top/Article/details/gtfgtknser.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.vqdsnc.cn/Article/details/gtwguoqnaa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgufenzy.top/Article/details/gtraiicykf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gtjnyqqycd.html

TS:   // 手写 Map<string, number>
来源：http://dali.hongshengwenyu.top/Article/details/gtvsrvopls.html

Java: // 手写 HashMap
来源：http://dali.tianlin.xyz/Article/details/gtcwyafuca.html

Go:   // 手写 map[int]int
来源：http://dali.nanxuanxn.top/Article/details/gtyiygvznr.html

Ruby: // 手写 Hash
来源：http://dali.hammf.cn/Article/details/gtmcxfohls.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yangfankeji.com/Article/details/gtlshfoffg.html

[N08] 生成全排列
来源：http://dali.yueranfly.top/Article/details/gtrnyyxqns.html

Py:   itertools.permutations(arr)
来源：http://dali.zycfv.cn/Article/details/gtdgnhqvmv.html

PHP:  // 手写递归交换
来源：http://dali.haohaochexian.top/Article/details/gtniihktsd.html

JS:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtnsuvfmjp.html

TS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtpwsajtbs.html

Java: // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtayhrkwbp.html

Go:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtosmvbboo.html

Ruby: arr.permutation.to_a
来源：http://dali.hysaishi.cn/Article/details/gteumbnrpm.html

C#:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtuqficbyq.html

[N09] 栈与队列
来源：http://dali.ivvv.top/Article/details/gttefignlv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gthfifdhcm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtroscgfkt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.meibo888.top/Article/details/gtbkginrut.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutcefjcx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gtofulxilp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yangfankeji.com/Article/details/gtknrbsaod.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtbgczgozy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hysaishi.cn/Article/details/gtppiyubyk.html

[N10] 链表节点定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvndpijeq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nanxuanxn.top/Article/details/gtxnxcdjfn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxqasfbi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cqqwz.cn/Article/details/gtdqjoskec.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zycfv.cn/Article/details/gtobkvozkm.html

Java: class Node { int v; Node next; }
来源：http://dali.hnxiangtu.top/Article/details/gtzeyrvqnp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zycfv.cn/Article/details/gthkujehch.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.meibo888.top/Article/details/gtlxvfhevs.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.9152youxi.cn/Article/details/gtruwtbdxx.html

[N11] 二叉树中序遍历
来源：http://dali.feifeiyinyue.top/Article/details/gthyyhmeyg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shangyingyoupin.top/Article/details/gtycjzfzaa.html

PHP:  // 手写递归函数
来源：http://dali.xinyue.icu/Article/details/gtanekiaxv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtpwowfxmi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ybcxt.top/Article/details/gtbjcnubza.html

Java: // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtnlsfaley.html

Go:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtjjfyrsyk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258888.top/Article/details/gtjrxcmnra.html

C#:   // 手写递归
来源：http://dali.xziqi.cn/Article/details/gtswgabgqz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhiwuduotai.top/Article/details/gtoxajutwg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhongyouzk.top/Article/details/gtcilkymcb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cheryme.top/Article/details/gtwdhpumsm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gtdzzzspzt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.quarkkingdee.top/Article/details/gtshqcynca.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgufenzy.top/Article/details/gtrwhbbawl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hysaishi.cn/Article/details/gtdfiekjfm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gaohongyu789.top/Article/details/gtlupcbdgl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.birdmap.top/Article/details/gtzoixvunc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtazagnpes.html

O. 并发与异步
来源：http://dali.hnxiangtu.top/Article/details/gthfhkockx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtlcqwqvjo.html

[O01] 启动一个线程
来源：http://dali.cheryme.top/Article/details/gtknliqovr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ppjwa.cn/Article/details/gtscvqwdzw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aibaodan.cn/Article/details/gtlxhsbdve.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ehwqpu.com/Article/details/gtejevatej.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gtgnyclbck.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258888.top/Article/details/gtfacwwhqc.html

Go:   go f()
来源：http://dali.tian-w.cn/Article/details/gtfgjcgafo.html

Ruby: Thread.new { f }
来源：http://dali.yanxiufei.cn/Article/details/gtjmsvruya.html

C#:   Task.Run(() => F());
来源：http://dali.guowangkeji.top/Article/details/gtilhiirou.html

[O02] 使用线程池
来源：http://dali.redwolf501.top/Article/details/gtprzaofka.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hongshengwenyu.top/Article/details/gtxvlnimua.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hysaishi.cn/Article/details/gtjsocsabe.html

JS:   // worker_threads 线程池
来源：http://dali.chenlongwang.top/Article/details/gtumaafpyt.html

TS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gtgvujdmkg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pycfn.com/Article/details/gtlpmmqpvs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinqigufen.top/Article/details/gtdtljngli.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.andypj.xyz/Article/details/gtglcejveo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnqzz.top/Article/details/gtqxezuzwx.html

[O03] 加锁保护共享数据
来源：http://dali.guannengcc.top/Article/details/gttkpxhidl.html

Py:   with lock: shared += 1
来源：http://dali.hongshengwenyu.top/Article/details/gtfnsmghne.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjwmftjv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yanxiufei.cn/Article/details/gtfzopkhqm.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgpngaqw.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gtttdqylux.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxinkj.top/Article/details/gtxkqzzcph.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xziqi.cn/Article/details/gtsupqdvfz.html

C#:   lock (gate) { shared++; }
来源：http://dali.cucudq.cn/Article/details/gtpjoijbel.html

[O04] 定义异步函数并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gtyomwyvws.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gtgoibsmxw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuxming.cn/Article/details/gttmzkkoqf.html

JS:   async function f() { await g(); }
来源：http://dali.iojbl.cn/Article/details/gtqirworhm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtwnbjxfnh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilefjjxt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zdqjudy.top/Article/details/gtgthyziqk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zycfv.cn/Article/details/gtcykxlrmr.html

C#:   async Task F() { await G(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrpcezpd.html

[O05] 并发执行并等待全部完成
来源：http://dali.svipenyu.cn/Article/details/gthylufzaz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtgspzypxg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwoffbpb.html

JS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gtzmfgjknu.html

TS:   await Promise.all(tasks)
来源：http://dali.zhixingplan.top/Article/details/gtwqqhqfzl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gaohongyu789.top/Article/details/gtiruluref.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgufenzy.top/Article/details/gtfwfgfrdp.html

Ruby: threads.map(&:join)
来源：http://dali.shuidangran.top/Article/details/gtilajakhj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuanzx.com/Article/details/gtyoollyqs.html

[O06] 使用进程池
来源：http://dali.iojbl.cn/Article/details/gtcpslkuxl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hysaishi.cn/Article/details/gtmtsjdbqq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.smart0.xyz/Article/details/gtqtwssihf.html

JS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gtqhfslgvt.html

TS:   // child_process / cluster 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafqxklsi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjazssdck.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.smart0.xyz/Article/details/gtlystanlv.html

Ruby: // fork 块
来源：http://dali.gotoacloud.top/Article/details/gtshusoezd.html

C#:   Parallel.For
来源：http://dali.yongpay.top/Article/details/gtanjsohtu.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtlkolvfdb.html

P. 常用工具函数
来源：http://dali.xylfe.cn/Article/details/gtdhiitghh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtpyejomdz.html

[P01] 生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gtpsnzeuqh.html

Py:   str(uuid.uuid4())
来源：http://dali.yonumen.top/Article/details/gtfresxtjd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gogol.net.cn/Article/details/gtwkfsltsd.html

JS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbopucjz.html

TS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gthcipmkit.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptzhxbdd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtmfwaoflx.html

Ruby: SecureRandom.uuid
来源：http://dali.guowangkeji.top/Article/details/gtpemltrme.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yuanzhike.top/Article/details/gtckobpvck.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shzxlz.cn/Article/details/gtwkghfteu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jlsjyb.cn/Article/details/gtgfoevqcp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.snrcjt.cn/Article/details/gtwffdngqm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtowfbrrow.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgufenzy.top/Article/details/gtlqlualkk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtffsohruc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hammf.cn/Article/details/gttcdfggvm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.havefunace.top/Article/details/gttgicfwob.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.9152youxi.cn/Article/details/gtjilogiuy.html

[P03] 生成短随机字符串
来源：http://dali.daria6918.cn/Article/details/gtcgvadgrj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.kuanghao11.cn/Article/details/gtmrnmgnya.html


<!-- 参考信息 -->