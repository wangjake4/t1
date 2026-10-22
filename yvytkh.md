代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gtxeudfblk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtuauqyjlk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ppjwa.cn/Article/details/gtxidxeqje.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ehwqpu.com/Article/details/gtocyuwlkp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.redwolf501.top/Article/details/gtpvvredcz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dianchejie.cn/Article/details/gtetvlnomi.html

[L05] 上传文件（multipart）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasamabbl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnxiangtu.top/Article/details/gtliqreoph.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxuanxn.top/Article/details/gtbitlfzxj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gtsrbjzhea.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gtblxscxcy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yongpay.top/Article/details/gtwhemwfjb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ehwqpu.com/Article/details/gtxdekjkkr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtznbwzsii.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtbtbffgra.html

[L06] 解析响应为 JSON
来源：http://dali.hnxiangtu.top/Article/details/gtouafyoqn.html

Py:   resp.json()
来源：http://dali.gzhubu.top/Article/details/gtxpukxdip.html

PHP:  json_decode($body, true);
来源：http://dali.ivvv.top/Article/details/gtieuvdotz.html

JS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldhwtcqc.html

TS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gtfgftkjmu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtflwavovz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aizwys.cn/Article/details/gtnaewyeqs.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwnjkgxb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yanxiufei.cn/Article/details/gtcolsldio.html

[L07] 处理 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gttdvxyexa.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fzhhl.top/Article/details/gtceokldzw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yonumen.top/Article/details/gtbylaszfg.html

JS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gtwropszfb.html

TS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gtgfaoquwc.html

Java: resp.statusCode()
来源：http://dali.wangdashe.top/Article/details/gthqqralvc.html

Go:   resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gtowhovzmr.html

Ruby: resp.code.to_i
来源：http://dali.redwolf501.top/Article/details/gteqgdzmhy.html

C#:   (int)resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gtqvwtfrrj.html

[L08] 并发请求多个地址
来源：http://dali.cashguo.top/Article/details/gtpmhdpcib.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.andypj.xyz/Article/details/gtucaltqgg.html

PHP:  curl_multi_init() 系列
来源：http://dali.xylfe.cn/Article/details/gtkfqjcaia.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gtfrqczhic.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtsvqprbcw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hammf.cn/Article/details/gttiennbqm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhixingplan.top/Article/details/gtmafwqndm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sweek.top/Article/details/gtitbcvepd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.316326.xyz/Article/details/gtffqcqhki.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtxekfcaat.html

M. 命令行 / 进程 / 环境
来源：http://dali.cdnleiting.top/Article/details/gtubumvkeh.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtufmaptri.html

[M01] 读取命令行参数
来源：http://dali.0kj1m.cn/Article/details/gtluszxcig.html

Py:   sys.argv[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtyafdohth.html

PHP:  $argv;  $argc;
来源：http://dali.sxryk.cn/Article/details/gtiibggina.html

JS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gtnvfgwvyo.html

TS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gttkwseboi.html

Java: args 数组（main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gtorvxmpjf.html

Go:   os.Args[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtnxgvmaef.html

Ruby: ARGV
来源：http://dali.ydzc1.top/Article/details/gtyaxgatbc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrdhjflc.html

[M02] 读取环境变量
来源：http://dali.mhx1999.top/Article/details/gthqavoopf.html

Py:   os.environ.get("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtgqlstfou.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gtoxfxpaoy.html

JS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gtgpjvhcmd.html

TS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtweqaiwnr.html

Java: System.getenv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtlguuxqxp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guannengcc.top/Article/details/gtbjudyplp.html

Ruby: ENV["HOME"]
来源：http://dali.9152youxi.cn/Article/details/gtisbeuceb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangdashe.top/Article/details/gtgjidfilv.html

[M03] 执行外部命令
来源：http://dali.zhengqikj.top/Article/details/gtebyeikpr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtvbxsudgg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gaohongyu789.top/Article/details/gtxcwcdfuv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrugihxgy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtzdpvirux.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xinyue.icu/Article/details/gttjryjuun.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuetiantiany.cn/Article/details/gtqibzsaps.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sufxvd.cn/Article/details/gtmshqtjas.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hysaishi.cn/Article/details/gtefwmqcxv.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gtkoquzcsp.html

Py:   os.getcwd()
来源：http://dali.birdmap.top/Article/details/gtsndkhzao.html

PHP:  getcwd();
来源：http://dali.snrcjt.cn/Article/details/gtqwjrzhic.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gtzczayled.html

TS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gtsfuveonp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenzaomai.com/Article/details/gtpruwhxxm.html

Go:   os.Getwd()
来源：http://dali.nwbrower.top/Article/details/gtmmepgqbj.html

Ruby: Dir.pwd
来源：http://dali.zhongyouzk.top/Article/details/gtqfqmyaxb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.smart0.xyz/Article/details/gtgvafhajm.html

[M05] 设置退出码
来源：http://dali.dianchejie.cn/Article/details/gtublmkyqx.html

Py:   sys.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbmrvxun.html

PHP:  exit(1);
来源：http://dali.jyoumei.cn/Article/details/gtjihuvwle.html

JS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtqclrpakc.html

TS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtglvzksjm.html

Java: System.exit(1)
来源：http://dali.cheryme.top/Article/details/gtqvwmyrfg.html

Go:   os.Exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtouyglubk.html

Ruby: exit 1
来源：http://dali.zhongyouzk.top/Article/details/gtexrpfkup.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgfzy.top/Article/details/gtppnhnujo.html

[M06] 向标准错误输出
来源：http://dali.yj202588.top/Article/details/gtdtxuuvzt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gtraplujbl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yueranfly.top/Article/details/gtcoialrsn.html

JS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gteqfflgpg.html

TS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gtbeagxrwc.html

Java: System.err.println("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtilstixmk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tanke756.top/Article/details/gtfivrqhlk.html

Ruby: warn "err"
来源：http://dali.yj20258888.top/Article/details/gtscktszmz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sxryk.cn/Article/details/gtkneiiami.html

[M07] 判断是否为主入口
来源：http://dali.tanke756.top/Article/details/gtwyijtxkl.html

Py:   if __name__ == "__main__":
来源：http://dali.c1oappe.top/Article/details/gtoruysahj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.redwolf501.top/Article/details/gtobaedtxo.html

JS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gtdtujmdzf.html

TS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gtxuolnxem.html

Java: public static void main(String[] args)
来源：http://dali.yj202588.top/Article/details/gtaeslbgep.html

Go:   func main()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoldbjfos.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zdqjudy.top/Article/details/gtcixaowic.html

C#:   static void Main(string[] args)
来源：http://dali.smart0.xyz/Article/details/gtvglldofp.html

[M08] 获取系统与运行时信息
来源：http://dali.guowangkeji.top/Article/details/gtqbohucwp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pycfn.com/Article/details/gthlmbpqxw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gotoacloud.top/Article/details/gtxbclrzhl.html

JS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gtnjqabery.html

TS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gtdockowcu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258888.top/Article/details/gtsgcnnqho.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.haohaochexian.top/Article/details/gtwwhoxzwg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.haohaochexian.top/Article/details/gtswsebqtu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gogol.net.cn/Article/details/gtlvezdgim.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gthtzuovyo.html

N. 数据结构与算法
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwyeykbn.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtikknzkpk.html

[N01] 二分查找（有序数组）
来源：http://dali.zhiwuduotai.top/Article/details/gtsngwjoiw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtfhcssham.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jianghu66.top/Article/details/gtticytopk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtmvtsrjoo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtupkvbcss.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gttvqkecab.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgnwsdol.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.9152youxi.cn/Article/details/gtjyvbhwae.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtwsmccrlf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258888.top/Article/details/gtooztmcvh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gtzwvfshsy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shuidangran.top/Article/details/gtftreylbz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtnimvjxfu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gtorhbecir.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shuidangran.top/Article/details/gtdmqpfdxz.html

Go:   slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gtohicxayb.html

Ruby: arr.sort
来源：http://dali.yj20258888.top/Article/details/gtgmwduzfg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.haohaochexian.top/Article/details/gtkthylqhh.html

[N03] 快速排序（分治示例）
来源：http://dali.yueranfly.top/Article/details/gtroancqdb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.meibo888.top/Article/details/gtgtwlwomc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fengsongda.top/Article/details/gtlqmmfnzh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gtgsehluse.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gtlugzhdnr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xylfe.cn/Article/details/gtobymobzh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtconqkyid.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinghuilouyu.cn/Article/details/gttkpfycak.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ivvv.top/Article/details/gtonkexcue.html

[N04] 斐波那契数列
来源：http://dali.xylfe.cn/Article/details/gtfeuqkgwq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtkjonsbbu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hammf.cn/Article/details/gtjmxbzozm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtimhwjnbb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtpbwdueil.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnqzz.top/Article/details/gtntoxqfpp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ivvv.top/Article/details/gtlahlhvir.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gtujrcspbr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gtxsaborud.html

[N05] 最大公约数
来源：http://dali.chenjidiqi.icu/Article/details/gtoicnunmj.html

Py:   math.gcd(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtxytbjoht.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtpysubkps.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gthfkubhnm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gtomqqpzym.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenjidiqi.icu/Article/details/gtdwnbrnkl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tianlin.xyz/Article/details/gtxulbcdhu.html

Ruby: a.gcd(b)
来源：http://dali.sysykeji.top/Article/details/gtaysudakm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ppjwa.cn/Article/details/gtkplbttco.html

[N06] 判断回文字符串
来源：http://dali.zhengqikj.top/Article/details/gtityxnwpo.html

Py:   s == s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gtncpworoy.html

PHP:  $s === strrev($s);
来源：http://dali.nwbrower.top/Article/details/gtrhubuoue.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtonkrobld.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtzftqefev.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yongpay.top/Article/details/gtjubgwhwh.html

Go:   // 双指针从两端比较
来源：http://dali.xuetiantiany.cn/Article/details/gtftpfcprh.html

Ruby: s == s.reverse
来源：http://dali.yvedp.cn/Article/details/gtpuokptqo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gtjryasabi.html

[N07] 两数之和（返回下标）
来源：http://dali.0kj1m.cn/Article/details/gtaqaltaxd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cucudq.cn/Article/details/gtoxviajzg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnxiangtu.top/Article/details/gtxlavuovd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sufxvd.cn/Article/details/gtkkgqllyz.html

TS:   // 手写 Map<string, number>
来源：http://dali.cashguo.top/Article/details/gtvjqeuzci.html

Java: // 手写 HashMap
来源：http://dali.haohaochexian.top/Article/details/gtikxgkcti.html

Go:   // 手写 map[int]int
来源：http://dali.aizwys.cn/Article/details/gtdunbgmmk.html

Ruby: // 手写 Hash
来源：http://dali.aibaodan.cn/Article/details/gtpmpghbzs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ybcxt.top/Article/details/gtauxfslzi.html

[N08] 生成全排列
来源：http://dali.smart0.xyz/Article/details/gtzxmkcjuu.html

Py:   itertools.permutations(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtpvarrqel.html

PHP:  // 手写递归交换
来源：http://dali.gogol.net.cn/Article/details/gtfnifgrjy.html

JS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtowgpdrun.html

TS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmirplrh.html

Java: // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtxtgaqtff.html

Go:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtttiqcplq.html

Ruby: arr.permutation.to_a
来源：http://dali.daria6918.cn/Article/details/gtmahpmiwa.html

C#:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gthlsqplcc.html

[N09] 栈与队列
来源：http://dali.hysaishi.cn/Article/details/gtnwvazxte.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guannengcc.top/Article/details/gtbjpoaggs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gtitlxsszi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtxdyovhcz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sufxvd.cn/Article/details/gtpxyshwng.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cdnleiting.top/Article/details/gtoswzrhhd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxuanxn.top/Article/details/gttdxnsjij.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuanzx.com/Article/details/gtzohefyvk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gaohongyu789.top/Article/details/gtyeetofiw.html

[N10] 链表节点定义
来源：http://dali.nwbrower.top/Article/details/gtlalnwcuz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pycfn.com/Article/details/gtdgrjenia.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.9152youxi.cn/Article/details/gtrcgfuebq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guowangkeji.top/Article/details/gtnljinsvx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hfpthk.cn/Article/details/gtqwzdfhik.html

Java: class Node { int v; Node next; }
来源：http://dali.sweek.top/Article/details/gtqaugurdc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgewfcej.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinqigfzy.top/Article/details/gtekzccelc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsftnagd.html

[N11] 二叉树中序遍历
来源：http://dali.yvedp.cn/Article/details/gtbskgseal.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hammf.cn/Article/details/gtjmzoysmv.html

PHP:  // 手写递归函数
来源：http://dali.xuetiantiany.cn/Article/details/gtnbclagut.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ybcxt.top/Article/details/gtmrvlkntr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuanzx.com/Article/details/gtvwnlqqwj.html

Java: // 手写递归
来源：http://dali.hnqzz.top/Article/details/gtzplruogq.html

Go:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtfyfksxvi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zycfv.cn/Article/details/gtygsermzc.html

C#:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gtzatgstjv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.bjfxy.top/Article/details/gtkmhpljir.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yongpay.top/Article/details/gtkleurczx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnxiangtu.top/Article/details/gtxsvpvvdp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gtvhmefrhu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gtdccddwlq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ydzc1.top/Article/details/gtepwlkzzv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258.top/Article/details/gtoilmtnes.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdykeiee.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gtdbfhpmjq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtedrkhegu.html

O. 并发与异步
来源：http://dali.cashguo.top/Article/details/gtczakhcag.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtdcmoosby.html

[O01] 启动一个线程
来源：http://dali.zhongyouzk.top/Article/details/gtdlcpdcyc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuetiantiany.cn/Article/details/gtbzckegev.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xylfe.cn/Article/details/gtqpfrjfcm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwxgkvpn.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gthbktrdld.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhongyouzk.top/Article/details/gtzsxfrsxx.html

Go:   go f()
来源：http://dali.sufxvd.cn/Article/details/gtmpchohrh.html

Ruby: Thread.new { f }
来源：http://dali.tianlin.xyz/Article/details/gtoptxtrvh.html

C#:   Task.Run(() => F());
来源：http://dali.gaohongyu789.top/Article/details/gtozwctulb.html

[O02] 使用线程池
来源：http://dali.jiagoushi.top/Article/details/gtrcqkcboh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.mhx1999.top/Article/details/gtkejkzbzu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gzhubu.top/Article/details/gtlxjhctop.html

JS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gtrvhqohdu.html

TS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtndsgftuo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.feifeiyinyue.top/Article/details/gtourndzjl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.andypj.xyz/Article/details/gtrprisrtm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ehwqpu.com/Article/details/gtliveegrc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.havefunace.top/Article/details/gtmxjcibem.html

[O03] 加锁保护共享数据
来源：http://dali.birdmap.top/Article/details/gtziijmbpb.html

Py:   with lock: shared += 1
来源：http://dali.xziqi.cn/Article/details/gtzeaocqfi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhongyouzk.top/Article/details/gtjfdfkrmj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangtech.top/Article/details/gtwuknkqhp.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbqkhdmt.html

Java: synchronized (this) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gtgnjysaqc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258888.top/Article/details/gtpzhjewvh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shuidangran.top/Article/details/gtvsgammhv.html

C#:   lock (gate) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gtbnpwvfku.html

[O04] 定义异步函数并等待
来源：http://dali.tianlin.xyz/Article/details/gtvekqdijd.html

Py:   async def f():⏎    await g()
来源：http://dali.ppjwa.cn/Article/details/gtdhjyhufh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ppjwa.cn/Article/details/gtbnyqsoiv.html

JS:   async function f() { await g(); }
来源：http://dali.hammf.cn/Article/details/gttpdkewtt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gtjhyncmku.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenzaomai.com/Article/details/gtfgfkvvki.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ehwqpu.com/Article/details/gtfdweqnax.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gzhubu.top/Article/details/gtzgifwmot.html

C#:   async Task F() { await G(); }
来源：http://dali.cashguo.top/Article/details/gtoecqaldr.html

[O05] 并发执行并等待全部完成
来源：http://dali.tianlin.xyz/Article/details/gtfpxyslad.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xylfe.cn/Article/details/gtznsheczf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sysykeji.top/Article/details/gtoudvqfji.html

JS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtenkubmop.html

TS:   await Promise.all(tasks)
来源：http://dali.guowangkeji.top/Article/details/gttlqtbrrw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shzxlz.cn/Article/details/gtbaylscyf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fengsongda.top/Article/details/gtcxyfdqyq.html

Ruby: threads.map(&:join)
来源：http://dali.aibaodan.cn/Article/details/gtxbqcuevc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigfzy.top/Article/details/gthpcsbkrw.html

[O06] 使用进程池
来源：http://dali.havefunace.top/Article/details/gtvlrmggcj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cucudq.cn/Article/details/gtlcpjuvfq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.smart0.xyz/Article/details/gtkeexjqbt.html

JS:   // child_process / cluster 模块
来源：http://dali.hfpthk.cn/Article/details/gtcitfwojz.html

TS:   // child_process / cluster 模块
来源：http://dali.aibaodan.cn/Article/details/gtwatwcxvj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zycfv.cn/Article/details/gttwurnpfq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hysaishi.cn/Article/details/gtiirfutkt.html

Ruby: // fork 块
来源：http://dali.zhongyouzk.top/Article/details/gtdfxtqgbu.html

C#:   Parallel.For
来源：http://dali.haohaochexian.top/Article/details/gtdrjxzetx.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtmcmtngvg.html

P. 常用工具函数
来源：http://dali.jqgfzy.top/Article/details/gtikzdhtwi.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtcsedfqgk.html

[P01] 生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefsfhmoo.html

Py:   str(uuid.uuid4())
来源：http://dali.yvedp.cn/Article/details/gtfyfgruhv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gtaiarvaoc.html

JS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gtctfxwglh.html

TS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtzcqsbayw.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnxiangtu.top/Article/details/gtvmcqumkv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvvurcmx.html

Ruby: SecureRandom.uuid
来源：http://dali.jlsjyb.cn/Article/details/gtkupcmpof.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hysaishi.cn/Article/details/gtcgmhkycs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jyoumei.cn/Article/details/gtieakfbpl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hongshengwenyu.top/Article/details/gtjejvixxx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xziqi.cn/Article/details/gtuelrfclj.html


<!-- 参考信息 -->