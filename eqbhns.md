代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangshuangyany.cn/Article/details/gtqjkbbyjy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gtoalploez.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gtuvcqjheq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cqqwz.cn/Article/details/gtdkikapww.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.quarkkingdee.top/Article/details/gtsmthflbc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shangyingyoupin.top/Article/details/gtqcmsvfwy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtwtjrkgnj.html

[L06] 解析响应为 JSON
来源：http://dali.yuanzhike.top/Article/details/gtwlbdcnlk.html

Py:   resp.json()
来源：http://dali.xuanzx.com/Article/details/gtwidzxgev.html

PHP:  json_decode($body, true);
来源：http://dali.yonumen.top/Article/details/gtszaynrfd.html

JS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gtwlghslft.html

TS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdxyqcwi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gzhubu.top/Article/details/gtktkgoten.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cucudq.cn/Article/details/gtgibjsutu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yanxiufei.cn/Article/details/gtalvalqza.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnknrvwm.html

[L07] 处理 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtjvypcgbi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhaomingkeji.xyz/Article/details/gteixivgmq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuanzx.com/Article/details/gtlfutaltn.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtclxukyib.html

TS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gtdoqcckfu.html

Java: resp.statusCode()
来源：http://dali.yangfankeji.com/Article/details/gtsdyycqmd.html

Go:   resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gtxftolqkp.html

Ruby: resp.code.to_i
来源：http://dali.tian-w.cn/Article/details/gtyjnrbrjh.html

C#:   (int)resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gtsdiozrth.html

[L08] 并发请求多个地址
来源：http://dali.hongshengwenyu.top/Article/details/gtuoqgycjq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tian-w.cn/Article/details/gtgtsjmonv.html

PHP:  curl_multi_init() 系列
来源：http://dali.sysykeji.top/Article/details/gtrarirkss.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gtxcglzqcu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gtddhsrdyk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.quarkkingdee.top/Article/details/gteqrkmeja.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.vqdsnc.cn/Article/details/gtuwqruowe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zycfv.cn/Article/details/gtonmbuwhw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj202588.top/Article/details/gthfgiszbp.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtjhesqyki.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhengqikj.top/Article/details/gtmclzrdxf.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gthgnrkmso.html

[M01] 读取命令行参数
来源：http://dali.iojbl.cn/Article/details/gtswjsknad.html

Py:   sys.argv[1:]
来源：http://dali.redwolf501.top/Article/details/gtfkovdhwq.html

PHP:  $argv;  $argc;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywjlrskt.html

JS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gtwpkamdsk.html

TS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gtczftxmvu.html

Java: args 数组（main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gtywevnngt.html

Go:   os.Args[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtknyvjwyn.html

Ruby: ARGV
来源：http://dali.yanxiufei.cn/Article/details/gtceghunoe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gtmjvcrogw.html

[M02] 读取环境变量
来源：http://dali.gaohongyu789.top/Article/details/gteeboebdl.html

Py:   os.environ.get("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtmvxkztzh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gtyduispnn.html

JS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gtcgcopjdf.html

TS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gtjegvhphu.html

Java: System.getenv("HOME")
来源：http://dali.bjfxy.top/Article/details/gttbinukiv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtjrqcqfym.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gtevcipdwp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daxiang520.top/Article/details/gtwsjqrksb.html

[M03] 执行外部命令
来源：http://dali.tanke756.top/Article/details/gtttdtbhml.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tianlin.xyz/Article/details/gtyuzjvtbh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ehwqpu.com/Article/details/gttvjrcgkx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gtpjlbqoss.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gtjuvoniep.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgufenzy.top/Article/details/gtpjfewtye.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pengpengdd.cyou/Article/details/gtewkwrnfb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ehwqpu.com/Article/details/gtpfuvboyq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yongpay.top/Article/details/gtvofinrua.html

[M04] 获取当前工作目录
来源：http://dali.gzhubu.top/Article/details/gtxfeyyfvx.html

Py:   os.getcwd()
来源：http://dali.gzhubu.top/Article/details/gtcviskbts.html

PHP:  getcwd();
来源：http://dali.nwbrower.top/Article/details/gtjfijebrv.html

JS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gtsrqjujim.html

TS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gtlfmgzjab.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxuanxn.top/Article/details/gtznwqycpi.html

Go:   os.Getwd()
来源：http://dali.zdqjudy.top/Article/details/gtdvgbwohc.html

Ruby: Dir.pwd
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbyszdsca.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangdashe.top/Article/details/gtbrumbjxv.html

[M05] 设置退出码
来源：http://dali.jyoumei.cn/Article/details/gtuimhrhqm.html

Py:   sys.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtyaambbyf.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gtsdvnwxma.html

JS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gtzzjxecvi.html

TS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gthofqjywi.html

Java: System.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtgbhwpqhq.html

Go:   os.Exit(1)
来源：http://dali.yj20258.top/Article/details/gtjsfiepwf.html

Ruby: exit 1
来源：http://dali.ivvv.top/Article/details/gtibqkqrvd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhixingplan.top/Article/details/gttghfedpx.html

[M06] 向标准错误输出
来源：http://dali.zhiwuduotai.top/Article/details/gthjbhlkfw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.feifeiyinyue.top/Article/details/gtnrkfpmyg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dianchejie.cn/Article/details/gtzaggecyi.html

JS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtwelwofgu.html

TS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gtoehicolz.html

Java: System.err.println("err")
来源：http://dali.yj20258.top/Article/details/gtnguhhdxf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.meibo888.top/Article/details/gtlfwmkmnk.html

Ruby: warn "err"
来源：http://dali.nwbrower.top/Article/details/gtznbjnjwv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yueranfly.top/Article/details/gtqjhayxmf.html

[M07] 判断是否为主入口
来源：http://dali.daxiang520.top/Article/details/gtveehpcwc.html

Py:   if __name__ == "__main__":
来源：http://dali.cucudq.cn/Article/details/gtwuwnuwdh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangshuangyany.cn/Article/details/gtahwwcwwx.html

JS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gtejoxgtzs.html

TS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gthruowmqr.html

Java: public static void main(String[] args)
来源：http://dali.zdqjudy.top/Article/details/gtjtzqtgjx.html

Go:   func main()
来源：http://dali.ivvv.top/Article/details/gtvrajvcnt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuetiantiany.cn/Article/details/gtahpihogi.html

C#:   static void Main(string[] args)
来源：http://dali.c1oappe.top/Article/details/gtbvstckos.html

[M08] 获取系统与运行时信息
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjynjuvt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sweek.top/Article/details/gtiuqvybih.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gtmfhhabzw.html

JS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gtdnmicmmd.html

TS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtwhzhzsbd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cucudq.cn/Article/details/gtnapjdfsn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xylfe.cn/Article/details/gtpanzjpfo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pycfn.com/Article/details/gtsiwyboxn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.quarkkingdee.top/Article/details/gtlrmhbhvo.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtihltqsgh.html

N. 数据结构与算法
来源：http://dali.gzhubu.top/Article/details/gtuirgykxa.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtjknsntmq.html

[N01] 二分查找（有序数组）
来源：http://dali.ehwqpu.com/Article/details/gtlembpdje.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtishkffjk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yongpay.top/Article/details/gtxmythsmq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gtzlxhqzul.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gtdhrwrsue.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtlaoaheyq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gttzvwldyl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwjwbkah.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ydzc1.top/Article/details/gteumpabvq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.mhx1999.top/Article/details/gtzadyeycy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtoiijtcwm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtwdiwhuki.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtjuogxxed.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtvisjyrfm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.quarkkingdee.top/Article/details/gtwvrtutue.html

Go:   slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gtzobdrygm.html

Ruby: arr.sort
来源：http://dali.chenjidiqi.icu/Article/details/gttoufluln.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jyoumei.cn/Article/details/gtqloimlbl.html

[N03] 快速排序（分治示例）
来源：http://dali.cashguo.top/Article/details/gtjqbsmtke.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pycfn.com/Article/details/gthrxpnxbz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pengpengdd.cyou/Article/details/gtdemlmdss.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzbhtdjh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gtfwuzhtmc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ivvv.top/Article/details/gtyraegged.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhiwuduotai.top/Article/details/gtgbhgqooh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nwbrower.top/Article/details/gtrpixzmuw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sysykeji.top/Article/details/gtvyemrrzr.html

[N04] 斐波那契数列
来源：http://dali.316326.xyz/Article/details/gtvhoukdvu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gtrgplqzph.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gtvjphjmqy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gtjsdduyut.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtbdplezav.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cucudq.cn/Article/details/gttsoitfsc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.vqdsnc.cn/Article/details/gtfvwkilby.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gtzktcpswi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtorhxwnnr.html

[N05] 最大公约数
来源：http://dali.yj202588.top/Article/details/gtsjxeuppz.html

Py:   math.gcd(a, b)
来源：http://dali.yueranfly.top/Article/details/gtpxqnrdzs.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tanke756.top/Article/details/gtrogbizzb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gtvyvcoqef.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnqzz.top/Article/details/gtyobkwave.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shuidangran.top/Article/details/gtszgoggdd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tanke756.top/Article/details/gtugocrgrh.html

Ruby: a.gcd(b)
来源：http://dali.jinqigufen.top/Article/details/gtiedodjia.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgfzy.top/Article/details/gtyhkacvhj.html

[N06] 判断回文字符串
来源：http://dali.yj20258888.top/Article/details/gttskpwdsu.html

Py:   s == s[::-1]
来源：http://dali.andypj.xyz/Article/details/gtmsmcwenl.html

PHP:  $s === strrev($s);
来源：http://dali.guannengcc.top/Article/details/gtxrnccdwv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gttvhcdlvr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtqaulkcaq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigufen.top/Article/details/gtdhizxlik.html

Go:   // 双指针从两端比较
来源：http://dali.chenlongwang.top/Article/details/gtjqreajey.html

Ruby: s == s.reverse
来源：http://dali.jiagoushi.top/Article/details/gtqtfgfmfh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gtqnifkmky.html

[N07] 两数之和（返回下标）
来源：http://dali.vqdsnc.cn/Article/details/gtguiwuihg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.0kj1m.cn/Article/details/gtekzrrqwy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhoulong.xyz/Article/details/gtkqfzjtmv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tian-w.cn/Article/details/gtcrpschrl.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbzmdmhj.html

Java: // 手写 HashMap
来源：http://dali.yonumen.top/Article/details/gttwkvmwog.html

Go:   // 手写 map[int]int
来源：http://dali.yongpay.top/Article/details/gtzjxdbgdh.html

Ruby: // 手写 Hash
来源：http://dali.jqgfzy.top/Article/details/gtqutyzeep.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aizwys.cn/Article/details/gturyqlkwu.html

[N08] 生成全排列
来源：http://dali.zhiwuduotai.top/Article/details/gtyrbikvfg.html

Py:   itertools.permutations(arr)
来源：http://dali.sweek.top/Article/details/gtqsuthein.html

PHP:  // 手写递归交换
来源：http://dali.pycfn.com/Article/details/gtmmtysgst.html

JS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtjtuatxyk.html

TS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtykpptesu.html

Java: // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtagtnesmg.html

Go:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtjbgtarxn.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxuanxn.top/Article/details/gtsltlzepx.html

C#:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtxefgdtsl.html

[N09] 栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteioxtzoi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnqzz.top/Article/details/gtepwfwkgj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynwpmprj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gtpyxdwsmy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.smart0.xyz/Article/details/gttyobhtse.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cashguo.top/Article/details/gtfftmljcx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hywenlv.cn/Article/details/gtgchhbhwv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gtzlqksxwe.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yueranfly.top/Article/details/gtzrmjbcep.html

[N10] 链表节点定义
来源：http://dali.yj202588.top/Article/details/gtyrfmtbjw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cheryme.top/Article/details/gtqrhekkwx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ehwqpu.com/Article/details/gtfzzhptnu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hfpthk.cn/Article/details/gtoaxsittq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.snrcjt.cn/Article/details/gtiqybbqwl.html

Java: class Node { int v; Node next; }
来源：http://dali.ivvv.top/Article/details/gtcjhcaylc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangshuangyany.cn/Article/details/gtspoclygr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.snrcjt.cn/Article/details/gtcalxnrur.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxinkj.top/Article/details/gtsknzvvtg.html

[N11] 二叉树中序遍历
来源：http://dali.birdmap.top/Article/details/gtbsyxvzfj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fzhhl.top/Article/details/gtcwjcdmfr.html

PHP:  // 手写递归函数
来源：http://dali.sweek.top/Article/details/gthitezunn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhengqikj.top/Article/details/gttrdzckzs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gtbllxonst.html

Java: // 手写递归
来源：http://dali.yvedp.cn/Article/details/gtsktmkekn.html

Go:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtycbamcnk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuetiantiany.cn/Article/details/gtwdiwhvdh.html

C#:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gthodurgwn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daxiang520.top/Article/details/gtgwrqhqco.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenlongwang.top/Article/details/gtyvmcxzyl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxinkj.top/Article/details/gtvkceqlij.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gtlzknxymg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhixingplan.top/Article/details/gtkguatzbe.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gtjbcgqgmm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cashguo.top/Article/details/gtnaeptwnz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinqigfzy.top/Article/details/gtonottkpg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gtnmheidww.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtwnqjbxtt.html

O. 并发与异步
来源：http://dali.ydzc1.top/Article/details/gtatmphfge.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfqrzcem.html

[O01] 启动一个线程
来源：http://dali.smart0.xyz/Article/details/gtitclrtgc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gzhubu.top/Article/details/gtisaohcns.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sufxvd.cn/Article/details/gtslgnetcl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhiwuduotai.top/Article/details/gttkakwcuh.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gtbekxkhpe.html

Java: new Thread(() -> f()).start()
来源：http://dali.c1oappe.top/Article/details/gtgzrazxvx.html

Go:   go f()
来源：http://dali.sweek.top/Article/details/gtwkosgqhj.html

Ruby: Thread.new { f }
来源：http://dali.hnxiangtu.top/Article/details/gtszohdfve.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gtcmbqbfwx.html

[O02] 使用线程池
来源：http://dali.iojbl.cn/Article/details/gtiextpbav.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.bjfxy.top/Article/details/gtdxnofcej.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cheryme.top/Article/details/gteufpzeoa.html

JS:   // worker_threads 线程池
来源：http://dali.zhixingplan.top/Article/details/gtaealdllm.html

TS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gtezfoqsuy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aibaodan.cn/Article/details/gtjnwtribu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.fengsongda.top/Article/details/gtslxtlojo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zycfv.cn/Article/details/gtfxuxmmbi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jianghu66.top/Article/details/gtnwsloizz.html

[O03] 加锁保护共享数据
来源：http://dali.yuxming.cn/Article/details/gthyefjqum.html

Py:   with lock: shared += 1
来源：http://dali.jiagoushi.top/Article/details/gthkqcdrvo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.andypj.xyz/Article/details/gtnwfxiwrp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhixingplan.top/Article/details/gtqqviwjoa.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gtqkjrkqvt.html

Java: synchronized (this) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gtpwcredvo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhoulong.xyz/Article/details/gtnrbuuogk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pengpengdd.cyou/Article/details/gtmablbbff.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gtrmfdrqat.html

[O04] 定义异步函数并等待
来源：http://dali.wangdashe.top/Article/details/gtaqziyeiw.html

Py:   async def f():⏎    await g()
来源：http://dali.jyoumei.cn/Article/details/gtikwoepam.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.redwolf501.top/Article/details/gtoqgipwsn.html

JS:   async function f() { await g(); }
来源：http://dali.yvedp.cn/Article/details/gtqkcjwvcb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.aibaodan.cn/Article/details/gtjpwtxmhq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.bjfxy.top/Article/details/gtjwkolnun.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangshuangyany.cn/Article/details/gtpihtgnrr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yueranfly.top/Article/details/gtczgbveto.html

C#:   async Task F() { await G(); }
来源：http://dali.jianghu66.top/Article/details/gtpzjyhaaa.html

[O05] 并发执行并等待全部完成
来源：http://dali.quarkkingdee.top/Article/details/gtnwbmgbaf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sweek.top/Article/details/gtobztcmnl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.mhx1999.top/Article/details/gtdbyoccjm.html

JS:   await Promise.all(tasks)
来源：http://dali.vqdsnc.cn/Article/details/gtwmxqkleq.html

TS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gtljismxdo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.mhx1999.top/Article/details/gtfqmvfdii.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shzxlz.cn/Article/details/gtzptayxrp.html

Ruby: threads.map(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gtggamnchf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gzhubu.top/Article/details/gtshnnppix.html

[O06] 使用进程池
来源：http://dali.shuidangran.top/Article/details/gtzsncjuyn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.quarkkingdee.top/Article/details/gtzyhcwssb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yongpay.top/Article/details/gtcohxgwqa.html

JS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gtxmqwwmqk.html

TS:   // child_process / cluster 模块
来源：http://dali.hammf.cn/Article/details/gtcdjlpgwy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.wangdashe.top/Article/details/gtiuqauaig.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgfzy.top/Article/details/gtdisvxjzg.html

Ruby: // fork 块
来源：http://dali.jlsjyb.cn/Article/details/gtfeavjgyj.html

C#:   Parallel.For
来源：http://dali.yj20258.top/Article/details/gtutllyakc.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtlbkxafla.html

P. 常用工具函数
来源：http://dali.xuanzx.com/Article/details/gtdaczcdwr.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtzdrvzquk.html

[P01] 生成 UUID
来源：http://dali.dianchejie.cn/Article/details/gtcfqinifp.html

Py:   str(uuid.uuid4())
来源：http://dali.fengsongda.top/Article/details/gtvmhaehhq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xinyue.icu/Article/details/gtanivanio.html

JS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gtsojymbvb.html

TS:   crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gtetiojgmc.html

Java: UUID.randomUUID().toString()
来源：http://dali.ppjwa.cn/Article/details/gtqgmrrccg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj20258888.top/Article/details/gthqnzpjex.html

Ruby: SecureRandom.uuid
来源：http://dali.ivvv.top/Article/details/gtblcqxwza.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aibaodan.cn/Article/details/gtepldjtpl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenlongwang.top/Article/details/gtseuzvztw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhoulong.xyz/Article/details/gtgeezpaev.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhixingplan.top/Article/details/gtfyrvpkfg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ivvv.top/Article/details/gtogdvyjyz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxuanxn.top/Article/details/gtftunillt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtseyigvsq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nwbrower.top/Article/details/gthyreockv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gzhubu.top/Article/details/gtriqeseyo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigfzy.top/Article/details/gtiabqmwcz.html

[P03] 生成短随机字符串
来源：http://dali.zhoulong.xyz/Article/details/gtsfkbrtcc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenzaomai.com/Article/details/gtufuwrilt.html


<!-- 参考信息 -->