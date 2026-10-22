代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.redwolf501.top/Article/details/gtrlynkzdw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gtqbhqznft.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gtfirupudn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxuanxn.top/Article/details/gtxtgklqwu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnajnofzu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxamryxlr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtdoyvpwck.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqaxapcn.html

Py:   resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvibjqnio.html

PHP:  json_decode($body, true);
来源：http://dali.cucudq.cn/Article/details/gtowvqfytc.html

JS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gtrynxappi.html

TS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gtndxnozrs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtdlzumifq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ivvv.top/Article/details/gtzoqlxmur.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangtech.top/Article/details/gtipbhylya.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.316326.xyz/Article/details/gtfvxbskvz.html

[L07] 处理 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gtqstevsse.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shzxlz.cn/Article/details/gtfgghhnot.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fengsongda.top/Article/details/gtegewieej.html

JS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtydyvugak.html

TS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gtywfigoah.html

Java: resp.statusCode()
来源：http://dali.aizwys.cn/Article/details/gtvcscjyab.html

Go:   resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gtajwizebc.html

Ruby: resp.code.to_i
来源：http://dali.sufxvd.cn/Article/details/gtxirunxal.html

C#:   (int)resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gtwuqxffpe.html

[L08] 并发请求多个地址
来源：http://dali.sysykeji.top/Article/details/gtqhjsnhzu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgufenzy.top/Article/details/gtyyxizrnm.html

PHP:  curl_multi_init() 系列
来源：http://dali.yueranfly.top/Article/details/gtsvbowejo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gtdmkqdzus.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gtzdfgwfxo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zdqjudy.top/Article/details/gtngdlugiz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ywan-chungtsiang.top/Article/details/gttyqgjwmq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gtdoncerbv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cqqwz.cn/Article/details/gtuwldwloi.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtrfqkmlsu.html

M. 命令行 / 进程 / 环境
来源：http://dali.daxiang520.top/Article/details/gtwcqdchpz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdirymnn.html

[M01] 读取命令行参数
来源：http://dali.jqgfzy.top/Article/details/gtvlazduze.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwakbepf.html

PHP:  $argv;  $argc;
来源：http://dali.0kj1m.cn/Article/details/gttvjrejzw.html

JS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gtrylxwfhf.html

TS:   process.argv.slice(2)
来源：http://dali.yueranfly.top/Article/details/gtearydfnq.html

Java: args 数组（main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gtpiknvxif.html

Go:   os.Args[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvnrdhps.html

Ruby: ARGV
来源：http://dali.bjfxy.top/Article/details/gtsycaazfw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj202588.top/Article/details/gtwmaopgjx.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtuahpqhxq.html

Py:   os.environ.get("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtnoofrakx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gtxftcuczm.html

JS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gtdmgokary.html

TS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gtgnrdmiwa.html

Java: System.getenv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtbnjycusi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gthbksperd.html

Ruby: ENV["HOME"]
来源：http://dali.sweek.top/Article/details/gtzcmeiftg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xinyue.icu/Article/details/gtzsgxwsuo.html

[M03] 执行外部命令
来源：http://dali.jinqigufen.top/Article/details/gtrneiaxxh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jlsjyb.cn/Article/details/gtdtwsafar.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cashguo.top/Article/details/gtzmsigdhu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gtjnzxneio.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gtqolnnith.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsknnsqz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jyoumei.cn/Article/details/gtkmbqhmdt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dashuyun.cn/Article/details/gtvutymrla.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sufxvd.cn/Article/details/gtkxaqdxkf.html

[M04] 获取当前工作目录
来源：http://dali.yj20258.top/Article/details/gtgibkwnxs.html

Py:   os.getcwd()
来源：http://dali.yangfankeji.com/Article/details/gtfqseergs.html

PHP:  getcwd();
来源：http://dali.iojbl.cn/Article/details/gtoaprvhaz.html

JS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gtegexwwsf.html

TS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gtogdbmpet.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258.top/Article/details/gtiwzzfuka.html

Go:   os.Getwd()
来源：http://dali.yanxiufei.cn/Article/details/gtfijmebff.html

Ruby: Dir.pwd
来源：http://dali.cheryme.top/Article/details/gtuvxzbvhh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj202588.top/Article/details/gtlaxebdxp.html

[M05] 设置退出码
来源：http://dali.guowangkeji.top/Article/details/gtbrxiihgm.html

Py:   sys.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtejahubst.html

PHP:  exit(1);
来源：http://dali.bjfxy.top/Article/details/gtzooflwcd.html

JS:   process.exit(1)
来源：http://dali.316326.xyz/Article/details/gtkbglzdlt.html

TS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtzczcmuls.html

Java: System.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtpjotielt.html

Go:   os.Exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkafybvd.html

Ruby: exit 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzimukve.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenlongwang.top/Article/details/gtcleoxvuc.html

[M06] 向标准错误输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgubdtyh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tianlin.xyz/Article/details/gtflffgvhk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxthiimrr.html

JS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gtdrfwszdu.html

TS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtevlnrmrm.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gtzxfarybx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jiagoushi.top/Article/details/gtivkguywp.html

Ruby: warn "err"
来源：http://dali.dianchejie.cn/Article/details/gtzmnsdsax.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pycfn.com/Article/details/gtssqyifrc.html

[M07] 判断是否为主入口
来源：http://dali.yj20258888.top/Article/details/gtmfreoygq.html

Py:   if __name__ == "__main__":
来源：http://dali.fzhhl.top/Article/details/gtejfutdzp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.guannengcc.top/Article/details/gtfuaztxak.html

JS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtafwmdgob.html

TS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gtfbvooaog.html

Java: public static void main(String[] args)
来源：http://dali.yangfankeji.com/Article/details/gtqjzisoad.html

Go:   func main()
来源：http://dali.jiagoushi.top/Article/details/gtxcjjkuph.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sysykeji.top/Article/details/gtzdwvmnns.html

C#:   static void Main(string[] args)
来源：http://dali.gogol.net.cn/Article/details/gtmwmkcjiq.html

[M08] 获取系统与运行时信息
来源：http://dali.tanke756.top/Article/details/gtgteojrex.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hammf.cn/Article/details/gtvuzdmxte.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenlongwang.top/Article/details/gtsxpxpfas.html

JS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gtkuapxkbz.html

TS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtjzxmplfl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ivvv.top/Article/details/gtjgqturrw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fengsongda.top/Article/details/gtruyjlizl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuxming.cn/Article/details/gtcywlunjn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daria6918.cn/Article/details/gtnwaeobgv.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtipyokkaa.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gtlysxclyy.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtnvlmtkxh.html

[N01] 二分查找（有序数组）
来源：http://dali.hfpthk.cn/Article/details/gtppsealwz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gteiiicexd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daxiang520.top/Article/details/gttbmumtga.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gtwgarrqwy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gtnbwrgcju.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtahvgifjf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtdurnzwby.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gogol.net.cn/Article/details/gtualgirgy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtecqbwgsc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.haohaochexian.top/Article/details/gtfbganjxe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.vqdsnc.cn/Article/details/gtijekalwh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jiagoushi.top/Article/details/gtvylugkaw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbydqltuo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gtrfufvfds.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfedbdrzm.html

Go:   slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gtvrjqbaaw.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gtsojbpuve.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dashuyun.cn/Article/details/gtfknshzoi.html

[N03] 快速排序（分治示例）
来源：http://dali.ivvv.top/Article/details/gtoshgsiit.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yonumen.top/Article/details/gtpgfuwqwi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hongshengwenyu.top/Article/details/gtczocdxcn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gtechebtfl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gtzlhloxhu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shangyingyoupin.top/Article/details/gteetathhw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnxiangtu.top/Article/details/gtdhilhpha.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nwbrower.top/Article/details/gtbbylwfez.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258888.top/Article/details/gtotdveqce.html

[N04] 斐波那契数列
来源：http://dali.yanxiufei.cn/Article/details/gtygqvslvv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gtenfnegnv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.andypj.xyz/Article/details/gttxgxgwmj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gttzdmdfho.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtjhroflzg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtaubttkct.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fengsongda.top/Article/details/gtldruhvlu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gtaufjupvr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtbkfxnedt.html

[N05] 最大公约数
来源：http://dali.wangshuangyany.cn/Article/details/gtjbgujozn.html

Py:   math.gcd(a, b)
来源：http://dali.bjfxy.top/Article/details/gtrueqwzeg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yangfankeji.com/Article/details/gtelriivhi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gtmarzxzwf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gtljiuvrqw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigufen.top/Article/details/gtqtanxvql.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xinyue.icu/Article/details/gtbsiccfhf.html

Ruby: a.gcd(b)
来源：http://dali.sysykeji.top/Article/details/gtapelbkup.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gotoacloud.top/Article/details/gtqatvtncp.html

[N06] 判断回文字符串
来源：http://dali.yj202588.top/Article/details/gtkoocmwdc.html

Py:   s == s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gtseuvmcdj.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsotpxklc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtblvcbywj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtrfrqxdif.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ehwqpu.com/Article/details/gtsltpnbtc.html

Go:   // 双指针从两端比较
来源：http://dali.tanke756.top/Article/details/gtohdqpjyl.html

Ruby: s == s.reverse
来源：http://dali.jianghu66.top/Article/details/gtcaetsvgi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gtpqdqxski.html

[N07] 两数之和（返回下标）
来源：http://dali.cqqwz.cn/Article/details/gtusdibqrb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenjidiqi.icu/Article/details/gtabrfihbz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sweek.top/Article/details/gtqkbecude.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.svipenyu.cn/Article/details/gtdmhywayf.html

TS:   // 手写 Map<string, number>
来源：http://dali.guowangkeji.top/Article/details/gtdfvflziw.html

Java: // 手写 HashMap
来源：http://dali.hnxiangtu.top/Article/details/gtbrqhpyqr.html

Go:   // 手写 map[int]int
来源：http://dali.daxiang520.top/Article/details/gthvbrpemr.html

Ruby: // 手写 Hash
来源：http://dali.wangshuangyany.cn/Article/details/gtwwxwggua.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.haohaochexian.top/Article/details/gtfaroavmp.html

[N08] 生成全排列
来源：http://dali.guowangkeji.top/Article/details/gtcgwbbbmq.html

Py:   itertools.permutations(arr)
来源：http://dali.0kj1m.cn/Article/details/gtyuowkogw.html

PHP:  // 手写递归交换
来源：http://dali.meibo888.top/Article/details/gtumnrcunh.html

JS:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtstvkiyqv.html

TS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtmthtbxoi.html

Java: // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gthgnqyzik.html

Go:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtnoyyuypx.html

Ruby: arr.permutation.to_a
来源：http://dali.aizwys.cn/Article/details/gtmnqcbivv.html

C#:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtgajcnruy.html

[N09] 栈与队列
来源：http://dali.guowangkeji.top/Article/details/gtbarclhom.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.0kj1m.cn/Article/details/gtzwunrdrs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ivvv.top/Article/details/gtnpkmhfbp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gtcxibglob.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.feifeiyinyue.top/Article/details/gtphnthren.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gtulyupzmu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gtdqxeffhp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfusqrzry.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.mhx1999.top/Article/details/gtpqmctuqr.html

[N10] 链表节点定义
来源：http://dali.ydzc1.top/Article/details/gtybvmgbxg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jiagoushi.top/Article/details/gtixekiple.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gaohongyu789.top/Article/details/gtuebpuxad.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daxiang520.top/Article/details/gttxskzkln.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hysaishi.cn/Article/details/gtsolenmuz.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gtufztniyd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pengpengdd.cyou/Article/details/gtdacyjefw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.c1oappe.top/Article/details/gtzxkdrdub.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cucudq.cn/Article/details/gtzwflbopr.html

[N11] 二叉树中序遍历
来源：http://dali.shzxlz.cn/Article/details/gtvferlbbs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jyoumei.cn/Article/details/gtbgvewmpz.html

PHP:  // 手写递归函数
来源：http://dali.vqdsnc.cn/Article/details/gtkgvysxpl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shzxlz.cn/Article/details/gtmtatmfaz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtehlaaqqe.html

Java: // 手写递归
来源：http://dali.pycfn.com/Article/details/gteiipepht.html

Go:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gtswxndimd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgufenzy.top/Article/details/gtzhqhbtbk.html

C#:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtyfwwpzug.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cheryme.top/Article/details/gthnkskyai.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpurycyk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ehwqpu.com/Article/details/gtkedpugpj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnqzz.top/Article/details/gtfdrwxlhw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gtyicaecan.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gtctjclzyj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenjidiqi.icu/Article/details/gtrkhdlzox.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xylfe.cn/Article/details/gtitjjplrb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gtjppoycsa.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtqmmxwjad.html

O. 并发与异步
来源：http://dali.svipenyu.cn/Article/details/gtpjhwxrzi.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtpjmsujfe.html

[O01] 启动一个线程
来源：http://dali.chenjidiqi.icu/Article/details/gtsibnqyry.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuetiantiany.cn/Article/details/gtmtqkucwo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.quarkkingdee.top/Article/details/gtkysdlimz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlyeezeeb.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gtaykfqzyi.html

Java: new Thread(() -> f()).start()
来源：http://dali.fzhhl.top/Article/details/gtwgxengkv.html

Go:   go f()
来源：http://dali.aizwys.cn/Article/details/gtfykjtfaw.html

Ruby: Thread.new { f }
来源：http://dali.dianchejie.cn/Article/details/gtpobzehqr.html

C#:   Task.Run(() => F());
来源：http://dali.hysaishi.cn/Article/details/gtfrvzphln.html

[O02] 使用线程池
来源：http://dali.smart0.xyz/Article/details/gtiwikcmxk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.iojbl.cn/Article/details/gtivbidsmz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yanxiufei.cn/Article/details/gtvehmvdza.html

JS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gtxoakmmuk.html

TS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gtostgwtwj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sxryk.cn/Article/details/gtmpqhxnsw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.pengpengdd.cyou/Article/details/gtnmamodvn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sweek.top/Article/details/gtzidymdna.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenjidiqi.icu/Article/details/gthhtjnxfa.html

[O03] 加锁保护共享数据
来源：http://dali.sxryk.cn/Article/details/gtvmdiblgb.html

Py:   with lock: shared += 1
来源：http://dali.yueranfly.top/Article/details/gtnaainbyj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xinyue.icu/Article/details/gtnviagvnw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangtech.top/Article/details/gtlanyfhmx.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gtcktmsxch.html

Java: synchronized (this) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gtmryvsxzi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazupgvyw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenlongwang.top/Article/details/gtfbayewxx.html

C#:   lock (gate) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gtceyhfjdl.html

[O04] 定义异步函数并等待
来源：http://dali.feifeiyinyue.top/Article/details/gtlogzdiam.html

Py:   async def f():⏎    await g()
来源：http://dali.chenjidiqi.icu/Article/details/gtroeizeaa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xinyue.icu/Article/details/gtsjbdwmrs.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gtjxuzjtkf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.guannengcc.top/Article/details/gtmztslcwx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jyoumei.cn/Article/details/gtdbiyxlfs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cashguo.top/Article/details/gtmbjwiirp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cqqwz.cn/Article/details/gtmlrsyttg.html

C#:   async Task F() { await G(); }
来源：http://dali.hnxiangtu.top/Article/details/gtmwracndp.html

[O05] 并发执行并等待全部完成
来源：http://dali.316326.xyz/Article/details/gtnqztefib.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgfzy.top/Article/details/gtofrntvbf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinqigfzy.top/Article/details/gtyaqyjlcp.html

JS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gttgqaqbor.html

TS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gtahbdsorz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj20258.top/Article/details/gtovxdhvjq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gtxvjophjr.html

Ruby: threads.map(&:join)
来源：http://dali.birdmap.top/Article/details/gtgemqspiq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangshuangyany.cn/Article/details/gtcsunsies.html

[O06] 使用进程池
来源：http://dali.zhongyouzk.top/Article/details/gtjjhjxlro.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.svipenyu.cn/Article/details/gttvrnaarn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xuanzx.com/Article/details/gtdgzsexys.html

JS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gtxszkspxo.html

TS:   // child_process / cluster 模块
来源：http://dali.hnxiangtu.top/Article/details/gtvvzvrdjl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenzaomai.com/Article/details/gtgrpkrfsq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yongpay.top/Article/details/gtjacddrfv.html

Ruby: // fork 块
来源：http://dali.aizwys.cn/Article/details/gtpfgvetqx.html

C#:   Parallel.For
来源：http://dali.yuxming.cn/Article/details/gtvqnymrfj.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbmavyrr.html

P. 常用工具函数
来源：http://dali.xuanzx.com/Article/details/gtvgliqgvw.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytuniohv.html

[P01] 生成 UUID
来源：http://dali.daxiang520.top/Article/details/gtaslhzusf.html

Py:   str(uuid.uuid4())
来源：http://dali.chenzaomai.com/Article/details/gtecthpvjr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.mhx1999.top/Article/details/gtikixlhja.html

JS:   crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gtxizivusd.html

TS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtkjcvevtd.html

Java: UUID.randomUUID().toString()
来源：http://dali.cucudq.cn/Article/details/gtcgxrkrxw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ybcxt.top/Article/details/gthnjvhbyk.html

Ruby: SecureRandom.uuid
来源：http://dali.gzhubu.top/Article/details/gtypqlxnvt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yuanzhike.top/Article/details/gtpknwlfsk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.feifeiyinyue.top/Article/details/gtrfoqqvhe.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gtriyizzch.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.kuanghao11.cn/Article/details/gtiyshjyxx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jianghu66.top/Article/details/gtgsmkbroz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj20258.top/Article/details/gtvxjaxoku.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sweek.top/Article/details/gtcsaprdkl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhixingplan.top/Article/details/gtegmbrffy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fzhhl.top/Article/details/gtgugpsqnm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gzhubu.top/Article/details/gtnrizorwe.html

[P03] 生成短随机字符串
来源：http://dali.mhx1999.top/Article/details/gtjudamtmu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhengqikj.top/Article/details/gtritakaly.html


<!-- 参考信息 -->