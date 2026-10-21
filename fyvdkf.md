代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hammf.cn/Article/details/gtxwbfyuzt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gtnwoubpva.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gtxfvjpnch.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhoulong.xyz/Article/details/gthpqkucts.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgyfpoev.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cheryme.top/Article/details/gtlpsrzqcg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xziqi.cn/Article/details/gtxybtvjdf.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqntxxoa.html

Py:   resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtvwsmaill.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigfzy.top/Article/details/gttbttngsg.html

JS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtcnjvnjbv.html

TS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gtqhgoroza.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sweek.top/Article/details/gtzqkezhtf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.bjfxy.top/Article/details/gtkbrydsis.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgufenzy.top/Article/details/gtiyspztrw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.kuanghao11.cn/Article/details/gtewppyggq.html

[L07] 处理 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gtsrdlmwfk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnqzz.top/Article/details/gttbvhxitn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenzaomai.com/Article/details/gtpwjowpga.html

JS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gtzlbfbodg.html

TS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gtrkakhcul.html

Java: resp.statusCode()
来源：http://dali.zhiwuduotai.top/Article/details/gtzmxelvsx.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gtrtdlfdiu.html

Ruby: resp.code.to_i
来源：http://dali.nanxuanxn.top/Article/details/gtxhwxmyfj.html

C#:   (int)resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gtlqytvvbo.html

[L08] 并发请求多个地址
来源：http://dali.yj20258.top/Article/details/gtpqjtmxta.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yangfankeji.com/Article/details/gtpkfhugjn.html

PHP:  curl_multi_init() 系列
来源：http://dali.zdqjudy.top/Article/details/gthbjqbcfw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtsqwrviui.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtsptwvmqn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.havefunace.top/Article/details/gtqtvhdoze.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hywenlv.cn/Article/details/gtmmuzketg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuanzhike.top/Article/details/gtzcvfhcbq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tian-w.cn/Article/details/gtanwtlrtp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtwuevvvrr.html

M. 命令行 / 进程 / 环境
来源：http://dali.jiagoushi.top/Article/details/gtzkbrmygs.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtirsloqoo.html

[M01] 读取命令行参数
来源：http://dali.hysaishi.cn/Article/details/gtttteqfvv.html

Py:   sys.argv[1:]
来源：http://dali.cqqwz.cn/Article/details/gtdrmenuhv.html

PHP:  $argv;  $argc;
来源：http://dali.hfpthk.cn/Article/details/gtrstdvqog.html

JS:   process.argv.slice(2)
来源：http://dali.xuanzx.com/Article/details/gttomfjdyy.html

TS:   process.argv.slice(2)
来源：http://dali.guowangkeji.top/Article/details/gtweccjncz.html

Java: args 数组（main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gtqavoykbq.html

Go:   os.Args[1:]
来源：http://dali.yueranfly.top/Article/details/gtvbfgxatq.html

Ruby: ARGV
来源：http://dali.0kj1m.cn/Article/details/gthtkwngzj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj202588.top/Article/details/gtzucktxxr.html

[M02] 读取环境变量
来源：http://dali.yvedp.cn/Article/details/gtcpihzmfc.html

Py:   os.environ.get("HOME")
来源：http://dali.bjfxy.top/Article/details/gtrzkoiqce.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtgcqrdhqj.html

JS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzvgfmzr.html

TS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdnxcsdi.html

Java: System.getenv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtmtjyvmpm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtudjfykia.html

Ruby: ENV["HOME"]
来源：http://dali.andypj.xyz/Article/details/gtwtfcnzrq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtavwfrzab.html

[M03] 执行外部命令
来源：http://dali.mhx1999.top/Article/details/gtycosjgvs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cdnleiting.top/Article/details/gtafwwutob.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shuidangran.top/Article/details/gtelcmoaqp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gtumnbolkg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gtqppokxyh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsguftolo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhixingplan.top/Article/details/gtigjmcedl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.9152youxi.cn/Article/details/gtebgzedqb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gotoacloud.top/Article/details/gtxsefqrlq.html

[M04] 获取当前工作目录
来源：http://dali.aibaodan.cn/Article/details/gtysuyfnsb.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gtuyypkjow.html

PHP:  getcwd();
来源：http://dali.cucudq.cn/Article/details/gtywcojtrw.html

JS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gtgghdxlnn.html

TS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gtujdhpogm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuanzhike.top/Article/details/gthrxisble.html

Go:   os.Getwd()
来源：http://dali.quarkkingdee.top/Article/details/gthqmpybre.html

Ruby: Dir.pwd
来源：http://dali.ehwqpu.com/Article/details/gtjdzdoesc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yonumen.top/Article/details/gtqkksukdp.html

[M05] 设置退出码
来源：http://dali.jqgfzy.top/Article/details/gtbmbhctak.html

Py:   sys.exit(1)
来源：http://dali.yongpay.top/Article/details/gtetgtollx.html

PHP:  exit(1);
来源：http://dali.birdmap.top/Article/details/gtuisgkoxl.html

JS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtruerahko.html

TS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtmblycppy.html

Java: System.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtoulircyd.html

Go:   os.Exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtzzwlwaqx.html

Ruby: exit 1
来源：http://dali.sxryk.cn/Article/details/gtltiozirg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrcmmsux.html

[M06] 向标准错误输出
来源：http://dali.haohaochexian.top/Article/details/gtsszhyrop.html

Py:   print("err", file=sys.stderr)
来源：http://dali.quarkkingdee.top/Article/details/gtwontnzlu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.iojbl.cn/Article/details/gtrhdeoqmf.html

JS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gtzdltweub.html

TS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtaxiepmdh.html

Java: System.err.println("err")
来源：http://dali.chenlongwang.top/Article/details/gtpuziojvf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yueranfly.top/Article/details/gtphfnomrt.html

Ruby: warn "err"
来源：http://dali.jlsjyb.cn/Article/details/gtrhiesjua.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sysykeji.top/Article/details/gtaqzdpkij.html

[M07] 判断是否为主入口
来源：http://dali.hnxiangtu.top/Article/details/gtrqlywkdp.html

Py:   if __name__ == "__main__":
来源：http://dali.dashuyun.cn/Article/details/gtbjqtnoxi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xinyue.icu/Article/details/gtuuyniyty.html

JS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gtmuinxlck.html

TS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gtwnczqmxa.html

Java: public static void main(String[] args)
来源：http://dali.xuanzx.com/Article/details/gtfmhtvtln.html

Go:   func main()
来源：http://dali.hywenlv.cn/Article/details/gtwsswbvyj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuanzhike.top/Article/details/gtxcjqytqd.html

C#:   static void Main(string[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjazhzpb.html

[M08] 获取系统与运行时信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvizslmzy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jlsjyb.cn/Article/details/gtqmtszion.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tianlin.xyz/Article/details/gtbiixaedv.html

JS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvwwjced.html

TS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gttpcwshvc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tianlin.xyz/Article/details/gtiejqxlwm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hfpthk.cn/Article/details/gtjqxmgago.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gzhubu.top/Article/details/gtqxjtxglq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hongshengwenyu.top/Article/details/gtifwsepnc.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtgbixprft.html

N. 数据结构与算法
来源：http://dali.gotoacloud.top/Article/details/gtbdmqxufh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtydmnmshp.html

[N01] 二分查找（有序数组）
来源：http://dali.nwbrower.top/Article/details/gtiwneeuhq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pycfn.com/Article/details/gtkmqkukog.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtuypwlnzi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gtjtuxxshb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gtvaobnibs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtkgzzshxu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtuzuqfkvx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hysaishi.cn/Article/details/gtbszdxuin.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gttstxvfyg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hammf.cn/Article/details/gtfrjvrnpr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gtfamjnfge.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.redwolf501.top/Article/details/gtzmygupsd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtafuzkfbe.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gtenmniviy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.havefunace.top/Article/details/gtwtgrhswb.html

Go:   slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gtfmacqlgz.html

Ruby: arr.sort
来源：http://dali.gzhubu.top/Article/details/gtgcpeubvr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgufenzy.top/Article/details/gtdudeller.html

[N03] 快速排序（分治示例）
来源：http://dali.gzhubu.top/Article/details/gtupzmncmh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daxiang520.top/Article/details/gtofzsmtnr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbvwbpsb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gtqswhclwk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tian-w.cn/Article/details/gtuuerlaca.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.kuanghao11.cn/Article/details/gtdyfiiwye.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daxiang520.top/Article/details/gtiedysozj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwodwvppo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nwbrower.top/Article/details/gtewgerzgw.html

[N04] 斐波那契数列
来源：http://dali.yueranfly.top/Article/details/gteuckqpwn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.fengsongda.top/Article/details/gtqctpfppk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xylfe.cn/Article/details/gtbeblqgxe.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtxggdhsic.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtrbqjyuyh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtihdtzaua.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.316326.xyz/Article/details/gtosdcrufb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gtdlamajuh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtzspgvjep.html

[N05] 最大公约数
来源：http://dali.jinqigfzy.top/Article/details/gtszejzbpt.html

Py:   math.gcd(a, b)
来源：http://dali.fzhhl.top/Article/details/gtfocgwxkr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yonumen.top/Article/details/gtjsujovdw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gtblripqvm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtxeyyotza.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.c1oappe.top/Article/details/gthoxdpeqb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj202588.top/Article/details/gtsgyalzzr.html

Ruby: a.gcd(b)
来源：http://dali.yueranfly.top/Article/details/gtmeyudeca.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258888.top/Article/details/gtimuetmqv.html

[N06] 判断回文字符串
来源：http://dali.cqqwz.cn/Article/details/gtkjpxpuwp.html

Py:   s == s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gtqgjupibx.html

PHP:  $s === strrev($s);
来源：http://dali.cashguo.top/Article/details/gtzmmfiyjm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtmqpkyujn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdavvafmf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhiwuduotai.top/Article/details/gthbfsvfwy.html

Go:   // 双指针从两端比较
来源：http://dali.nwbrower.top/Article/details/gtsegsuokk.html

Ruby: s == s.reverse
来源：http://dali.ybcxt.top/Article/details/gtdboxndej.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gthtbjhdli.html

[N07] 两数之和（返回下标）
来源：http://dali.daria6918.cn/Article/details/gtjmloajfm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangdashe.top/Article/details/gtsrkxviya.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.smart0.xyz/Article/details/gtnkiovrzb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nanxuanxn.top/Article/details/gtgrvqhzor.html

TS:   // 手写 Map<string, number>
来源：http://dali.c1oappe.top/Article/details/gtjefrfupv.html

Java: // 手写 HashMap
来源：http://dali.zhoulong.xyz/Article/details/gtwucggaps.html

Go:   // 手写 map[int]int
来源：http://dali.guannengcc.top/Article/details/gtkoxugmkw.html

Ruby: // 手写 Hash
来源：http://dali.yanxiufei.cn/Article/details/gtgdeaicvf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sweek.top/Article/details/gtuxznptnn.html

[N08] 生成全排列
来源：http://dali.sweek.top/Article/details/gtaupnmzvq.html

Py:   itertools.permutations(arr)
来源：http://dali.daria6918.cn/Article/details/gtntcebuyb.html

PHP:  // 手写递归交换
来源：http://dali.fzhhl.top/Article/details/gtvxcvcaon.html

JS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtmhrisdui.html

TS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtvksdnzig.html

Java: // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtokzgfgxv.html

Go:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtwpgnuacb.html

Ruby: arr.permutation.to_a
来源：http://dali.shangyingyoupin.top/Article/details/gtydxxfjyu.html

C#:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtatkgdysc.html

[N09] 栈与队列
来源：http://dali.ydzc1.top/Article/details/gtslnuibih.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gtlvlbdiqs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtearfmngt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gtktldzufa.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shzxlz.cn/Article/details/gthjlwkfpn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gturpjmbcy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfxmrzft.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gtoodixvme.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ivvv.top/Article/details/gtjeddbhuy.html

[N10] 链表节点定义
来源：http://dali.daria6918.cn/Article/details/gtkkejvkgp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shangyingyoupin.top/Article/details/gtglrjtkuc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ydzc1.top/Article/details/gtszvskjxw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgufenzy.top/Article/details/gtlvozmwqd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhixingplan.top/Article/details/gtnbkmweyn.html

Java: class Node { int v; Node next; }
来源：http://dali.svipenyu.cn/Article/details/gtdocjpktr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.svipenyu.cn/Article/details/gtowbzqhoc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yueranfly.top/Article/details/gtnndxjhey.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cashguo.top/Article/details/gtztmbuofd.html

[N11] 二叉树中序遍历
来源：http://dali.wangdashe.top/Article/details/gtqofclvsi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hfpthk.cn/Article/details/gtwspigvpl.html

PHP:  // 手写递归函数
来源：http://dali.nwbrower.top/Article/details/gtsgtbkqpf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzuwrlvj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ppjwa.cn/Article/details/gtfigqeath.html

Java: // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtghwcvzks.html

Go:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtrioxtpad.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tanke756.top/Article/details/gtvlevtscy.html

C#:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gtvwpipbuo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yuanzhike.top/Article/details/gtxfucrktm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tian-w.cn/Article/details/gtfzczdthe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.vqdsnc.cn/Article/details/gtcywykfqq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gtpopwtraq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gttszzltxu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gtwptgrlek.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gtdewqlqtg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daxiang520.top/Article/details/gthuklyrvo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gtfbualvja.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtgcsxkxul.html

O. 并发与异步
来源：http://dali.bjfxy.top/Article/details/gtvuwqhyvs.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtlvhgvzcz.html

[O01] 启动一个线程
来源：http://dali.redwolf501.top/Article/details/gthshokyem.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenjidiqi.icu/Article/details/gthvcgrvzj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.svipenyu.cn/Article/details/gtjzujdmdn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yanxiufei.cn/Article/details/gtqtvvlrxa.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gtxzjbxfeu.html

Java: new Thread(() -> f()).start()
来源：http://dali.mhx1999.top/Article/details/gtndbjyhcc.html

Go:   go f()
来源：http://dali.xziqi.cn/Article/details/gtqqfgcpuy.html

Ruby: Thread.new { f }
来源：http://dali.haohaochexian.top/Article/details/gtukgnfswt.html

C#:   Task.Run(() => F());
来源：http://dali.bjfxy.top/Article/details/gtragzmcic.html

[O02] 使用线程池
来源：http://dali.daxiang520.top/Article/details/gtqacjlrls.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jqgfzy.top/Article/details/gtvdrcemtw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ybcxt.top/Article/details/gtcbkaomkq.html

JS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gtwgbhpvgf.html

TS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gtzgytakou.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cheryme.top/Article/details/gtuzkicudq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xylfe.cn/Article/details/gtcoesfqhp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yueranfly.top/Article/details/gtxikqppzw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sweek.top/Article/details/gtbsiultlb.html

[O03] 加锁保护共享数据
来源：http://dali.aizwys.cn/Article/details/gtnfeaqdao.html

Py:   with lock: shared += 1
来源：http://dali.cqqwz.cn/Article/details/gtqrcayyhf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.daxiang520.top/Article/details/gtorfvlukc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258888.top/Article/details/gtzauvtars.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gtmgzghvum.html

Java: synchronized (this) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gtqgjtkfpk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangshuangyany.cn/Article/details/gtputhbplq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjfshxjr.html

C#:   lock (gate) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gtwizptstx.html

[O04] 定义异步函数并等待
来源：http://dali.chenjidiqi.icu/Article/details/gthneupucr.html

Py:   async def f():⏎    await g()
来源：http://dali.yuxming.cn/Article/details/gtyqchybsb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yvedp.cn/Article/details/gtsfwuhfrd.html

JS:   async function f() { await g(); }
来源：http://dali.yuxming.cn/Article/details/gtyhhdpsay.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.wangdashe.top/Article/details/gtjfhchxit.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gtfczgquxv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daria6918.cn/Article/details/gtjyfdrfrn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cheryme.top/Article/details/gtpsbcifaz.html

C#:   async Task F() { await G(); }
来源：http://dali.chenzaomai.com/Article/details/gtamiuocrh.html

[O05] 并发执行并等待全部完成
来源：http://dali.xziqi.cn/Article/details/gtubwtnqpx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cashguo.top/Article/details/gtzoarnkqa.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hnxiangtu.top/Article/details/gtpbyiazxt.html

JS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gtxwzrbsur.html

TS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gtevfglkbp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xziqi.cn/Article/details/gtxrdgdmjm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hfpthk.cn/Article/details/gtxrgosrye.html

Ruby: threads.map(&:join)
来源：http://dali.ppjwa.cn/Article/details/gteaakxobb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hongshengwenyu.top/Article/details/gtlxhgtebx.html

[O06] 使用进程池
来源：http://dali.cqqwz.cn/Article/details/gtpwjsperf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sysykeji.top/Article/details/gtwjshnbgo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jiagoushi.top/Article/details/gtlqfhjzdf.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gteaopcvfi.html

TS:   // child_process / cluster 模块
来源：http://dali.smart0.xyz/Article/details/gtvvpjkbxy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenzaomai.com/Article/details/gttjvbrnbw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgufenzy.top/Article/details/gtwozotasn.html

Ruby: // fork 块
来源：http://dali.svipenyu.cn/Article/details/gtoaltqsak.html

C#:   Parallel.For
来源：http://dali.yonumen.top/Article/details/gtkqejduhn.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtsdpitojq.html

P. 常用工具函数
来源：http://dali.hnxiangtu.top/Article/details/gtldcvjfox.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtqepmwyhu.html

[P01] 生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gtdeqngclr.html

Py:   str(uuid.uuid4())
来源：http://dali.c1oappe.top/Article/details/gtvtkfujye.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbpvawzx.html

JS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gtkpbmpycg.html

TS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtqpnahmzo.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrpwitof.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sysykeji.top/Article/details/gtbofcuuag.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdorrfxt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.redwolf501.top/Article/details/gtqvhuvlii.html

[P02] MD5 / SHA256 摘要
来源：http://dali.vqdsnc.cn/Article/details/gtecopgfkm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.redwolf501.top/Article/details/gtmtsplyhm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.svipenyu.cn/Article/details/gthxolixoz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ydzc1.top/Article/details/gtjumgwyza.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jiagoushi.top/Article/details/gtaywtctgd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtdtkwsgar.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fzhhl.top/Article/details/gthgdcfkkf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.andypj.xyz/Article/details/gtiwehvbzr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhiwuduotai.top/Article/details/gtuvuqriap.html

[P03] 生成短随机字符串
来源：http://dali.ivvv.top/Article/details/gtjfwvqnlt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cdnleiting.top/Article/details/gtsikuxddl.html


<!-- 参考信息 -->