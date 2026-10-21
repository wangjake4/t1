代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gtfdbjnhet.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gtixesmfbw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gzhubu.top/Article/details/gtleesyakt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ehwqpu.com/Article/details/gtrtfazrvc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hammf.cn/Article/details/gtgujbfoid.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fzhhl.top/Article/details/gtfbzvyyni.html

[L05] 上传文件（multipart）
来源：http://dali.hywenlv.cn/Article/details/gtfcscshlr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.feifeiyinyue.top/Article/details/gtlbkuvibq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cheryme.top/Article/details/gtxklhrgaq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gttewfqemt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gtwqztsoro.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258888.top/Article/details/gtqfdtebry.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shangyingyoupin.top/Article/details/gtnnvrgkgn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigfzy.top/Article/details/gtbjgqmnst.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtappxwoxi.html

[L06] 解析响应为 JSON
来源：http://dali.daria6918.cn/Article/details/gtezxlbjnt.html

Py:   resp.json()
来源：http://dali.cucudq.cn/Article/details/gtxosxjkyu.html

PHP:  json_decode($body, true);
来源：http://dali.9152youxi.cn/Article/details/gtwiszuiax.html

JS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gtafffkpjr.html

TS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gtlhbwsnpk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtubreinli.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj202588.top/Article/details/gtsokgsitx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jiagoushi.top/Article/details/gtleijksaj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xziqi.cn/Article/details/gtmcpbwthm.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gtlazzbdne.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cdnleiting.top/Article/details/gtgwhvarpg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuxming.cn/Article/details/gtrcwsqwev.html

JS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtdovfdvoz.html

TS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gtchqefcio.html

Java: resp.statusCode()
来源：http://dali.yj20258888.top/Article/details/gtzryheusr.html

Go:   resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkbtnmvt.html

Ruby: resp.code.to_i
来源：http://dali.sufxvd.cn/Article/details/gtwgklissa.html

C#:   (int)resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtkbrjcuhm.html

[L08] 并发请求多个地址
来源：http://dali.hfpthk.cn/Article/details/gtcysdjdfz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.vqdsnc.cn/Article/details/gtlagsfgbj.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhiwuduotai.top/Article/details/gtabaapsxo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gtotuskccu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtdujrpqks.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.smart0.xyz/Article/details/gtrjydqtpp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fengsongda.top/Article/details/gtxgwevdyc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gtvkjyxjcg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenlongwang.top/Article/details/gtwwnptqac.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gttogpddph.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgfzy.top/Article/details/gtkipssojl.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtexhgrllj.html

[M01] 读取命令行参数
来源：http://dali.ivvv.top/Article/details/gticipdbwo.html

Py:   sys.argv[1:]
来源：http://dali.cucudq.cn/Article/details/gtaxhiylqx.html

PHP:  $argv;  $argc;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzcwqmrov.html

JS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gtiwuymuve.html

TS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gtmorrsjks.html

Java: args 数组（main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gtlmyrwvuc.html

Go:   os.Args[1:]
来源：http://dali.yvedp.cn/Article/details/gtgvnfludg.html

Ruby: ARGV
来源：http://dali.birdmap.top/Article/details/gtaevmifhy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258.top/Article/details/gtaufoyada.html

[M02] 读取环境变量
来源：http://dali.xuanzx.com/Article/details/gtbdspowfw.html

Py:   os.environ.get("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtiatqtylt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbrpvbdg.html

JS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtupszukye.html

TS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtjhltguhi.html

Java: System.getenv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtyekdjuqy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtrrzntjgm.html

Ruby: ENV["HOME"]
来源：http://dali.xuanzx.com/Article/details/gtdhkosyog.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ehwqpu.com/Article/details/gttqpbzawp.html

[M03] 执行外部命令
来源：http://dali.xuanzx.com/Article/details/gtieauoypm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sxryk.cn/Article/details/gtzlcqtxbl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258888.top/Article/details/gtgnnbvlsq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.c1oappe.top/Article/details/gtszymxsca.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtxehmbqqp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cucudq.cn/Article/details/gtbwsvlqgq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gogol.net.cn/Article/details/gtdqscavvl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhoulong.xyz/Article/details/gtqtvqskph.html

C#:   Process.Start("ls", "-l");
来源：http://dali.316326.xyz/Article/details/gtyxmvmcpo.html

[M04] 获取当前工作目录
来源：http://dali.fengsongda.top/Article/details/gtxmrdvmhy.html

Py:   os.getcwd()
来源：http://dali.jianghu66.top/Article/details/gtqoscejnj.html

PHP:  getcwd();
来源：http://dali.guannengcc.top/Article/details/gtzksswgqa.html

JS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gtukvxchft.html

TS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gtgctktuis.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gogol.net.cn/Article/details/gttyswktnr.html

Go:   os.Getwd()
来源：http://dali.c1oappe.top/Article/details/gtghnhdrxa.html

Ruby: Dir.pwd
来源：http://dali.yongpay.top/Article/details/gtblhpfdhd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangdashe.top/Article/details/gtzsoscxsb.html

[M05] 设置退出码
来源：http://dali.sysykeji.top/Article/details/gtjfewdnmr.html

Py:   sys.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtmqforwcj.html

PHP:  exit(1);
来源：http://dali.havefunace.top/Article/details/gtsotdzomj.html

JS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtjlicymab.html

TS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtpctsitjw.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtblzmnswf.html

Go:   os.Exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtaconvccn.html

Ruby: exit 1
来源：http://dali.snrcjt.cn/Article/details/gtpzrenmta.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.vqdsnc.cn/Article/details/gteffsfnvl.html

[M06] 向标准错误输出
来源：http://dali.yj202588.top/Article/details/gtsibhofud.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pycfn.com/Article/details/gtnilhatpt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangdashe.top/Article/details/gtvjgrtknl.html

JS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gtwokpygch.html

TS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtvqoteust.html

Java: System.err.println("err")
来源：http://dali.zdqjudy.top/Article/details/gttghhxuge.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.andypj.xyz/Article/details/gtzojdfypl.html

Ruby: warn "err"
来源：http://dali.tanke756.top/Article/details/gtxicqlwcq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangdashe.top/Article/details/gteoqyjpix.html

[M07] 判断是否为主入口
来源：http://dali.jqgufenzy.top/Article/details/gtbtrlvwpf.html

Py:   if __name__ == "__main__":
来源：http://dali.cdnleiting.top/Article/details/gtuffxkfub.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yonumen.top/Article/details/gteocwdhfa.html

JS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gtcegbrhlq.html

TS:   require.main === module
来源：http://dali.yvedp.cn/Article/details/gtixdvuyhh.html

Java: public static void main(String[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gtjsacqrrf.html

Go:   func main()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiewoafws.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.havefunace.top/Article/details/gthjifiroo.html

C#:   static void Main(string[] args)
来源：http://dali.fengsongda.top/Article/details/gtvvafojfl.html

[M08] 获取系统与运行时信息
来源：http://dali.chenzaomai.com/Article/details/gtjgeufvea.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhiwuduotai.top/Article/details/gtdhfkucwr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daria6918.cn/Article/details/gtocnvryjl.html

JS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsmkugxt.html

TS:   process.platform;  process.version
来源：http://dali.yuanzhike.top/Article/details/gtpelscolh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jlsjyb.cn/Article/details/gtbbegpnld.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aizwys.cn/Article/details/gtdluijokf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.svipenyu.cn/Article/details/gthrofncfz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hysaishi.cn/Article/details/gtomapqmgq.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtgvrhvznc.html

N. 数据结构与算法
来源：http://dali.0kj1m.cn/Article/details/gtljlwdavi.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtvdsxcyda.html

[N01] 二分查找（有序数组）
来源：http://dali.havefunace.top/Article/details/gtdezvrhhr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtzpgtjgfc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cashguo.top/Article/details/gtgpzcyxir.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtvvylflyg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gtxtrjhrlg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gtpzjmwknq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cashguo.top/Article/details/gtldifvlcz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuetiantiany.cn/Article/details/gtjyksnhiu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtvueppuid.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.mhx1999.top/Article/details/gthpxxseks.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtwiwxjoog.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgufenzy.top/Article/details/gthlyarusu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtbphskqxh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gtlcejogib.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dianchejie.cn/Article/details/gtdvgbwelv.html

Go:   slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gtvhfwwrwq.html

Ruby: arr.sort
来源：http://dali.tian-w.cn/Article/details/gtbnjrdiit.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfrzfeje.html

[N03] 快速排序（分治示例）
来源：http://dali.316326.xyz/Article/details/gtlvtxiscs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.c1oappe.top/Article/details/gtozfeadsm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yongpay.top/Article/details/gtwgvgszuw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gtdezdkcok.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gthqggwrwr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.havefunace.top/Article/details/gtrsgtdozm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gtanteiopd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hysaishi.cn/Article/details/gtqsezsigp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shangyingyoupin.top/Article/details/gtnrhscnwl.html

[N04] 斐波那契数列
来源：http://dali.yanxiufei.cn/Article/details/gtyyupzpgq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtlpazemcb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gtrrdjxrlf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtwvjltjjo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gtonmoytye.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gtovsdaxfm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258888.top/Article/details/gtnpuynepp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtvyzsrhin.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gtrpxifwza.html

[N05] 最大公约数
来源：http://dali.tanke756.top/Article/details/gtcafpcgdd.html

Py:   math.gcd(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtaqiduede.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrayudfee.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gtecpbfwwd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gtppvjsseg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guowangkeji.top/Article/details/gttubbclzt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yonumen.top/Article/details/gtruuvpljs.html

Ruby: a.gcd(b)
来源：http://dali.yuxming.cn/Article/details/gtetmlldau.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenjidiqi.icu/Article/details/gtkvnqfbwf.html

[N06] 判断回文字符串
来源：http://dali.redwolf501.top/Article/details/gtrqocdrja.html

Py:   s == s[::-1]
来源：http://dali.daria6918.cn/Article/details/gtxoehyfmr.html

PHP:  $s === strrev($s);
来源：http://dali.tian-w.cn/Article/details/gtnnjunamg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtqtkflurb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtrwrdjabv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shangyingyoupin.top/Article/details/gtwjhgmngl.html

Go:   // 双指针从两端比较
来源：http://dali.zhoulong.xyz/Article/details/gtkimdtmsl.html

Ruby: s == s.reverse
来源：http://dali.cucudq.cn/Article/details/gthexhltyb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gtiumfpoaf.html

[N07] 两数之和（返回下标）
来源：http://dali.xuanzx.com/Article/details/gtundxqasb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hywenlv.cn/Article/details/gtohubqdoc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zycfv.cn/Article/details/gttxjlhqus.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yanxiufei.cn/Article/details/gtfehppatu.html

TS:   // 手写 Map<string, number>
来源：http://dali.dashuyun.cn/Article/details/gtcliafxkc.html

Java: // 手写 HashMap
来源：http://dali.jiagoushi.top/Article/details/gtdwyqvrbs.html

Go:   // 手写 map[int]int
来源：http://dali.hfpthk.cn/Article/details/gtlgwhgivw.html

Ruby: // 手写 Hash
来源：http://dali.hysaishi.cn/Article/details/gtmnmaxowr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sxryk.cn/Article/details/gtlwbnkgag.html

[N08] 生成全排列
来源：http://dali.redwolf501.top/Article/details/gtajmcnxai.html

Py:   itertools.permutations(arr)
来源：http://dali.ivvv.top/Article/details/gtikwmfzdt.html

PHP:  // 手写递归交换
来源：http://dali.kuanghao11.cn/Article/details/gtiqxozypy.html

JS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtteizzgec.html

TS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtunvjukso.html

Java: // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtcayzasql.html

Go:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtxcjknmlk.html

Ruby: arr.permutation.to_a
来源：http://dali.andypj.xyz/Article/details/gtcviaecat.html

C#:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcaxxifop.html

[N09] 栈与队列
来源：http://dali.fengsongda.top/Article/details/gtehwefkog.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.snrcjt.cn/Article/details/gtsgybjyrg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtzwtebvvh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgunbpun.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.c1oappe.top/Article/details/gtzjnrxoha.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shzxlz.cn/Article/details/gtgsvzhydx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tianlin.xyz/Article/details/gtcugtzdvh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtiklzyjuv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yangfankeji.com/Article/details/gthowblgpa.html

[N10] 链表节点定义
来源：http://dali.mhx1999.top/Article/details/gttsiituev.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shuidangran.top/Article/details/gtrvgcekyb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gaohongyu789.top/Article/details/gtdyyimwal.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nwbrower.top/Article/details/gtgkqyqdgk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hnxiangtu.top/Article/details/gtcjswfeve.html

Java: class Node { int v; Node next; }
来源：http://dali.vqdsnc.cn/Article/details/gthscrfqli.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.0kj1m.cn/Article/details/gtrafupjfz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangdashe.top/Article/details/gtmvbfhtth.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jyoumei.cn/Article/details/gtrksrgoag.html

[N11] 二叉树中序遍历
来源：http://dali.0kj1m.cn/Article/details/gtmuzllisn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenjidiqi.icu/Article/details/gtqyhcxsnw.html

PHP:  // 手写递归函数
来源：http://dali.dianchejie.cn/Article/details/gtgmnhappx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gtwgvfistk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gttfeucngi.html

Java: // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtebzfurgf.html

Go:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtfqdgbqef.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hysaishi.cn/Article/details/gtvqkrfwre.html

C#:   // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gtkffpnuph.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigfzy.top/Article/details/gtpboiboya.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgufenzy.top/Article/details/gtopyunhlg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yangfankeji.com/Article/details/gtediazemg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gtytuhpizy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnqzz.top/Article/details/gtvmdxrhvl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gtfmvbqjfy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigufen.top/Article/details/gteykybiqf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fengsongda.top/Article/details/gtkonrihep.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gtwmihvorz.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtnlctnjma.html

O. 并发与异步
来源：http://dali.chenzaomai.com/Article/details/gtcjztpxmf.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtsbbbijsd.html

[O01] 启动一个线程
来源：http://dali.xuetiantiany.cn/Article/details/gtjxlletgo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuetiantiany.cn/Article/details/gtohdzxcav.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydgwnqxa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nwbrower.top/Article/details/gtzvwcdevc.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtzwvmgury.html

Java: new Thread(() -> f()).start()
来源：http://dali.cashguo.top/Article/details/gtqfjiwlsz.html

Go:   go f()
来源：http://dali.yueranfly.top/Article/details/gttcjekyyc.html

Ruby: Thread.new { f }
来源：http://dali.jqgfzy.top/Article/details/gtqhbmckey.html

C#:   Task.Run(() => F());
来源：http://dali.vqdsnc.cn/Article/details/gtjpjhfxks.html

[O02] 使用线程池
来源：http://dali.yueranfly.top/Article/details/gtpbjrdxpx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ybcxt.top/Article/details/gtvppytnrs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xinyue.icu/Article/details/gtwvigkpsk.html

JS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gtvrhpiwxz.html

TS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gtildectzx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xylfe.cn/Article/details/gtxnswnprj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.redwolf501.top/Article/details/gtghdaoweg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gtjizcatsd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hywenlv.cn/Article/details/gthxqcweqh.html

[O03] 加锁保护共享数据
来源：http://dali.yj202588.top/Article/details/gtdraycemb.html

Py:   with lock: shared += 1
来源：http://dali.9152youxi.cn/Article/details/gtmlcgcebk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gotoacloud.top/Article/details/gtbpfmpmig.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.quarkkingdee.top/Article/details/gtcmbzkmbw.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gtsoeqdnek.html

Java: synchronized (this) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gtysaiebcn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.meibo888.top/Article/details/gtmecuihcu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yongpay.top/Article/details/gtyuftepah.html

C#:   lock (gate) { shared++; }
来源：http://dali.hywenlv.cn/Article/details/gttlmmzjnu.html

[O04] 定义异步函数并等待
来源：http://dali.fengsongda.top/Article/details/gtiudtwlcq.html

Py:   async def f():⏎    await g()
来源：http://dali.jyoumei.cn/Article/details/gtogzestvu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shuidangran.top/Article/details/gtalhsuvon.html

JS:   async function f() { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gtzcjhfkyk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuanzx.com/Article/details/gtoocwjknh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aibaodan.cn/Article/details/gtxmrkuscy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlifaiwxf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhongyouzk.top/Article/details/gtrplyjcnx.html

C#:   async Task F() { await G(); }
来源：http://dali.zhoulong.xyz/Article/details/gtprqicqrd.html

[O05] 并发执行并等待全部完成
来源：http://dali.hysaishi.cn/Article/details/gtlmombbxw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yueranfly.top/Article/details/gtkedehlvb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cqqwz.cn/Article/details/gtfkphnzji.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtloisgrkr.html

TS:   await Promise.all(tasks)
来源：http://dali.chenzaomai.com/Article/details/gtcmtxgyez.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shzxlz.cn/Article/details/gtnkjvkjgc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.snrcjt.cn/Article/details/gtkiwbwepc.html

Ruby: threads.map(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gtllnyubkc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sweek.top/Article/details/gtbhsrukjb.html

[O06] 使用进程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfyrqvpj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgufenzy.top/Article/details/gtziysusyy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.dashuyun.cn/Article/details/gtxijoatuz.html

JS:   // child_process / cluster 模块
来源：http://dali.xziqi.cn/Article/details/gtvheszscm.html

TS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gtpkdypexg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.birdmap.top/Article/details/gtckjtoifl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.redwolf501.top/Article/details/gtehhbxkjn.html

Ruby: // fork 块
来源：http://dali.xuanzx.com/Article/details/gtxywrwkaa.html

C#:   Parallel.For
来源：http://dali.hammf.cn/Article/details/gtgtkdvddk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gthvkxpvab.html

P. 常用工具函数
来源：http://dali.hammf.cn/Article/details/gtskyummcp.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtkzkqmndg.html

[P01] 生成 UUID
来源：http://dali.hnqzz.top/Article/details/gtqoucwzix.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258888.top/Article/details/gtsvghsvhv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xziqi.cn/Article/details/gtjuektyda.html

JS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gtmwbcgllu.html

TS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gthfmdekqs.html

Java: UUID.randomUUID().toString()
来源：http://dali.quarkkingdee.top/Article/details/gtunbwjuvt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jlsjyb.cn/Article/details/gtisfcdvnz.html

Ruby: SecureRandom.uuid
来源：http://dali.shzxlz.cn/Article/details/gtyhkkgvro.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnxbnelfs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhiwuduotai.top/Article/details/gtllloxsib.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yvedp.cn/Article/details/gtjtxfhnpr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aibaodan.cn/Article/details/gtccmerfng.html


<!-- 参考信息 -->