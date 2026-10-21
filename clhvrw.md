代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gtjtyqeuez.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gtxzfptzqt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.birdmap.top/Article/details/gtqnrvzcxw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hysaishi.cn/Article/details/gtydrmfnnw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shuidangran.top/Article/details/gtpoiimnco.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zycfv.cn/Article/details/gtczxydjra.html

[L05] 上传文件（multipart）
来源：http://dali.xziqi.cn/Article/details/gtsfemnimy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.smart0.xyz/Article/details/gtxxqmtohw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xylfe.cn/Article/details/gttobakpep.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gtwbnwclvd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gtkjawshax.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.wangdashe.top/Article/details/gtcuvtrrjl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nwbrower.top/Article/details/gtqmupnfwn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gogol.net.cn/Article/details/gtoxlzgwup.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ydzc1.top/Article/details/gtbumvzbhh.html

[L06] 解析响应为 JSON
来源：http://dali.nanxuanxn.top/Article/details/gtunqzlqwr.html

Py:   resp.json()
来源：http://dali.hnqzz.top/Article/details/gtbpehhgys.html

PHP:  json_decode($body, true);
来源：http://dali.yanxiufei.cn/Article/details/gtsfudvvro.html

JS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdegtsspv.html

TS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtdjnnujyi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuxming.cn/Article/details/gtimzjttlb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.svipenyu.cn/Article/details/gtrvtvckwh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hongshengwenyu.top/Article/details/gtinsauuwm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sufxvd.cn/Article/details/gtpdjmegdz.html

[L07] 处理 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gtdznrafyp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yongpay.top/Article/details/gtpnovifow.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fzhhl.top/Article/details/gtrgnjanra.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtcwmtbcpy.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjpnolpg.html

Java: resp.statusCode()
来源：http://dali.shzxlz.cn/Article/details/gtxzjrpabm.html

Go:   resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gtvizypoxk.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gtpklwauym.html

C#:   (int)resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gtnuixyarm.html

[L08] 并发请求多个地址
来源：http://dali.cucudq.cn/Article/details/gtfensrcdf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tian-w.cn/Article/details/gtwtftjmds.html

PHP:  curl_multi_init() 系列
来源：http://dali.sysykeji.top/Article/details/gtltcoubdf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gtdffpqfay.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwtgohtj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zycfv.cn/Article/details/gtrsvctkiy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvceuxie.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jiagoushi.top/Article/details/gtomrlsnow.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuxming.cn/Article/details/gtuqmcynwy.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtasquavgr.html

M. 命令行 / 进程 / 环境
来源：http://dali.ppjwa.cn/Article/details/gttgbjmqjf.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtgpowgynm.html

[M01] 读取命令行参数
来源：http://dali.mhx1999.top/Article/details/gtqeoqkgmu.html

Py:   sys.argv[1:]
来源：http://dali.sysykeji.top/Article/details/gtbjgccivo.html

PHP:  $argv;  $argc;
来源：http://dali.zhoulong.xyz/Article/details/gtdjkclslo.html

JS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtqwsyzlfn.html

TS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gtoajirmfj.html

Java: args 数组（main 方法参数）
来源：http://dali.hammf.cn/Article/details/gtvgrloyfi.html

Go:   os.Args[1:]
来源：http://dali.fengsongda.top/Article/details/gtelsqsvie.html

Ruby: ARGV
来源：http://dali.zdqjudy.top/Article/details/gtbcefuqwj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gtktupbubj.html

[M02] 读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gtzqbkdwai.html

Py:   os.environ.get("HOME")
来源：http://dali.wangdashe.top/Article/details/gtasyhkchw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqqcvenc.html

JS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gtthlxvqzn.html

TS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gtqoedeary.html

Java: System.getenv("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtcthqccpv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daria6918.cn/Article/details/gtfmyswvay.html

Ruby: ENV["HOME"]
来源：http://dali.yonumen.top/Article/details/gtqqnqsbme.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cucudq.cn/Article/details/gtbigqjeca.html

[M03] 执行外部命令
来源：http://dali.jinqigfzy.top/Article/details/gtacpcyhyf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yueranfly.top/Article/details/gtzmsmwgcq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuxming.cn/Article/details/gtrrpnalqo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtfcyqjule.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gtlqvazyun.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuanzx.com/Article/details/gtmrsorkmi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.havefunace.top/Article/details/gtjuhxckou.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shzxlz.cn/Article/details/gtpzadvuog.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ybcxt.top/Article/details/gtngtmgbmg.html

[M04] 获取当前工作目录
来源：http://dali.hysaishi.cn/Article/details/gtvkjcjkac.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gtgmeuefhu.html

PHP:  getcwd();
来源：http://dali.tian-w.cn/Article/details/gtxrewfqvv.html

JS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gtmjfleavj.html

TS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gtrpobpxpv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guannengcc.top/Article/details/gtaryjodbx.html

Go:   os.Getwd()
来源：http://dali.ybcxt.top/Article/details/gtflvblcat.html

Ruby: Dir.pwd
来源：http://dali.svipenyu.cn/Article/details/gtovxhcqjn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ehwqpu.com/Article/details/gtrzrdfoit.html

[M05] 设置退出码
来源：http://dali.aibaodan.cn/Article/details/gtepslpcet.html

Py:   sys.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtbbdnvxvx.html

PHP:  exit(1);
来源：http://dali.gotoacloud.top/Article/details/gtgedckobb.html

JS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtpwsupmph.html

TS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtfwrebrzv.html

Java: System.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtggdotgap.html

Go:   os.Exit(1)
来源：http://dali.birdmap.top/Article/details/gtbginglqd.html

Ruby: exit 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpcflfzk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hongshengwenyu.top/Article/details/gtannysglk.html

[M06] 向标准错误输出
来源：http://dali.jinqigfzy.top/Article/details/gtzbsdnvss.html

Py:   print("err", file=sys.stderr)
来源：http://dali.haohaochexian.top/Article/details/gtmfydaawz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuanzx.com/Article/details/gtjvmobegc.html

JS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gtryinvtox.html

TS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gtvhipkiyp.html

Java: System.err.println("err")
来源：http://dali.ybcxt.top/Article/details/gtdikcrcgl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.bjfxy.top/Article/details/gtaqcacubx.html

Ruby: warn "err"
来源：http://dali.iojbl.cn/Article/details/gtknjuvgql.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tian-w.cn/Article/details/gtokphhwiw.html

[M07] 判断是否为主入口
来源：http://dali.andypj.xyz/Article/details/gtacsojwgv.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gttqhimlvp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigufen.top/Article/details/gtqzovvybu.html

JS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gtdwtkuyas.html

TS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvenzqsne.html

Java: public static void main(String[] args)
来源：http://dali.dianchejie.cn/Article/details/gtadqytuys.html

Go:   func main()
来源：http://dali.chenjidiqi.icu/Article/details/gtqfizhmqt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258.top/Article/details/gtoadomtpi.html

C#:   static void Main(string[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gtcmebeqty.html

[M08] 获取系统与运行时信息
来源：http://dali.sufxvd.cn/Article/details/gtdtxzwwfl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhiwuduotai.top/Article/details/gtgadztxxd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nwbrower.top/Article/details/gtwfoiyqae.html

JS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gtwehftcch.html

TS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gttubncuix.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxuanxn.top/Article/details/gtcedhnohe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.0kj1m.cn/Article/details/gtoamimpeb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shangyingyoupin.top/Article/details/gtsxqnudqb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhongyouzk.top/Article/details/gtznyfxhtp.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtsvbdsugx.html

N. 数据结构与算法
来源：http://dali.yj20258888.top/Article/details/gtuojeqdvm.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gttseqbumd.html

[N01] 二分查找（有序数组）
来源：http://dali.zhiwuduotai.top/Article/details/gtpzhcwnfd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtjyrfygnl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nwbrower.top/Article/details/gtntnkltmi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gtnewtyetx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtlliqjcqo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gthqaqhman.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtavrowkkg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.feifeiyinyue.top/Article/details/gttixjvobs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtuzywitvw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hfpthk.cn/Article/details/gtwwetbita.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gtjagmbwuy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tanke756.top/Article/details/gtfpladqhh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtmxuvvles.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gtsphrvkcs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shzxlz.cn/Article/details/gtfwauudao.html

Go:   slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gtjeseogui.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gtewirvbiz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gtqrajrakk.html

[N03] 快速排序（分治示例）
来源：http://dali.pycfn.com/Article/details/gticwaniaw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shzxlz.cn/Article/details/gtkosrpmls.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhengqikj.top/Article/details/gtfzopvlck.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gtjorhguxw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gtzljoyyjg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgfzy.top/Article/details/gtkyfotpfv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daria6918.cn/Article/details/gtpvhnzlcn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ppjwa.cn/Article/details/gttwjpaeqc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.9152youxi.cn/Article/details/gtznbrvvoy.html

[N04] 斐波那契数列
来源：http://dali.cdnleiting.top/Article/details/gtzmwppvbi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gtxdddkcnj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ybcxt.top/Article/details/gtotztccig.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtuhjbwxvl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtmfpbyugb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gtmrlrffas.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ivvv.top/Article/details/gtxydpojqi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gtyranlpef.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gtecywlhpc.html

[N05] 最大公约数
来源：http://dali.yonumen.top/Article/details/gthwtivskk.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtquoeboav.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cqqwz.cn/Article/details/gtnzkawywp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtnaiprlkz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gtcoxqkguz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ivvv.top/Article/details/gtnrbeoxwz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gtnhexlblo.html

Ruby: a.gcd(b)
来源：http://dali.zycfv.cn/Article/details/gtflmzrfpi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hnxiangtu.top/Article/details/gtzkgzoalt.html

[N06] 判断回文字符串
来源：http://dali.tanke756.top/Article/details/gtsjmvpfno.html

Py:   s == s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gtjtnxgmel.html

PHP:  $s === strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gtinjzgbcb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtmwjtgrfj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtpsborxac.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hammf.cn/Article/details/gtotisxzkz.html

Go:   // 双指针从两端比较
来源：http://dali.yueranfly.top/Article/details/gtqxmpkvqy.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtzlulalri.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gtbctpitxn.html

[N07] 两数之和（返回下标）
来源：http://dali.haohaochexian.top/Article/details/gtphmkszti.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.havefunace.top/Article/details/gtyztxvxmd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangtech.top/Article/details/gtccehgkvu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hysaishi.cn/Article/details/gtbjybbqfp.html

TS:   // 手写 Map<string, number>
来源：http://dali.jiagoushi.top/Article/details/gtjpcohscj.html

Java: // 手写 HashMap
来源：http://dali.zycfv.cn/Article/details/gtwaxvbecy.html

Go:   // 手写 map[int]int
来源：http://dali.dianchejie.cn/Article/details/gtkhmsmpwb.html

Ruby: // 手写 Hash
来源：http://dali.aibaodan.cn/Article/details/gtydhwtkfz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.andypj.xyz/Article/details/gtrfylziad.html

[N08] 生成全排列
来源：http://dali.yj20258.top/Article/details/gtphzdaooc.html

Py:   itertools.permutations(arr)
来源：http://dali.havefunace.top/Article/details/gtzteeuzhn.html

PHP:  // 手写递归交换
来源：http://dali.xinyue.icu/Article/details/gteiweeltx.html

JS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtqjamxngx.html

TS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gthdiyayyn.html

Java: // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtxmlbpxwj.html

Go:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gttosgmxfj.html

Ruby: arr.permutation.to_a
来源：http://dali.tanke756.top/Article/details/gtoitvdgzy.html

C#:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtavozocad.html

[N09] 栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gthjjomgql.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gttepbwxpk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtvfanmuhl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gtsctarkbr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuanzx.com/Article/details/gtknfhjssc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenzaomai.com/Article/details/gtohskblyn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.vqdsnc.cn/Article/details/gtzudprred.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtrhhjjukl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258.top/Article/details/gttwefvccs.html

[N10] 链表节点定义
来源：http://dali.xziqi.cn/Article/details/gtgawhioin.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yongpay.top/Article/details/gtfhyggwgr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yueranfly.top/Article/details/gtkvcyuoii.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.0kj1m.cn/Article/details/gtrehifepo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hongshengwenyu.top/Article/details/gtanqyurkp.html

Java: class Node { int v; Node next; }
来源：http://dali.nwbrower.top/Article/details/gtlisucpnv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daria6918.cn/Article/details/gtnswimsbb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hysaishi.cn/Article/details/gtxisbyeqk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tianlin.xyz/Article/details/gtouafddbg.html

[N11] 二叉树中序遍历
来源：http://dali.sufxvd.cn/Article/details/gtnnlqdhgo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj20258888.top/Article/details/gtqfavvzil.html

PHP:  // 手写递归函数
来源：http://dali.xuanzx.com/Article/details/gtpbvlfocs.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gttobytijw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gtfgpgdfwh.html

Java: // 手写递归
来源：http://dali.yongpay.top/Article/details/gtcdnfpnsh.html

Go:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtmkjrxqrr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.dashuyun.cn/Article/details/gtlrvwwfdj.html

C#:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gtlvmudyak.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gogol.net.cn/Article/details/gtkqokxxpc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.c1oappe.top/Article/details/gtzhmbhfdm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigufen.top/Article/details/gtpyxwiddq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtxoaxyloc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gthnppgqjr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzluraco.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ehwqpu.com/Article/details/gtoslovtgz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yangfankeji.com/Article/details/gtebuvjykm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhiwuduotai.top/Article/details/gtzjwppqpb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtlenmddqc.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqxlcobn.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtouibpofg.html

[O01] 启动一个线程
来源：http://dali.cucudq.cn/Article/details/gtwvurrgiw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.c1oappe.top/Article/details/gtptaiijhf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.kuanghao11.cn/Article/details/gtmodfppok.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.mhx1999.top/Article/details/gttyucniic.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gtxbusiydk.html

Java: new Thread(() -> f()).start()
来源：http://dali.ehwqpu.com/Article/details/gtctwhvpgg.html

Go:   go f()
来源：http://dali.ehwqpu.com/Article/details/gtqgblsrqw.html

Ruby: Thread.new { f }
来源：http://dali.pycfn.com/Article/details/gtahmpvgzk.html

C#:   Task.Run(() => F());
来源：http://dali.ybcxt.top/Article/details/gtpkbywzxw.html

[O02] 使用线程池
来源：http://dali.gogol.net.cn/Article/details/gtyxgqwqco.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.kuanghao11.cn/Article/details/gtbqrxmdnr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ydzc1.top/Article/details/gtxywzcbfr.html

JS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gtoeababeu.html

TS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtdlcllkqz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhongyouzk.top/Article/details/gtjxukcnxl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxuvyxckv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.birdmap.top/Article/details/gtqaaidpuf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yongpay.top/Article/details/gtilfzkgtm.html

[O03] 加锁保护共享数据
来源：http://dali.gogol.net.cn/Article/details/gtzccjfkkz.html

Py:   with lock: shared += 1
来源：http://dali.sxryk.cn/Article/details/gtpqdmzxov.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ehwqpu.com/Article/details/gtjrwgylii.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ywan-chungtsiang.top/Article/details/gtusivniaz.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gtqzsazjnb.html

Java: synchronized (this) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gtuhnkcakf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cheryme.top/Article/details/gtwhktiaxa.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ehwqpu.com/Article/details/gtjjkuakmj.html

C#:   lock (gate) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gtftwpsjzv.html

[O04] 定义异步函数并等待
来源：http://dali.haohaochexian.top/Article/details/gtdtasyuip.html

Py:   async def f():⏎    await g()
来源：http://dali.tanke756.top/Article/details/gtzqukiems.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.feifeiyinyue.top/Article/details/gtgqbifblc.html

JS:   async function f() { await g(); }
来源：http://dali.xinyue.icu/Article/details/gtiubllazf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gtdanrizua.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ybcxt.top/Article/details/gtnfizjwdw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gtvecyowsv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnqzz.top/Article/details/gtmdonooyk.html

C#:   async Task F() { await G(); }
来源：http://dali.yj202588.top/Article/details/gtjouogrhx.html

[O05] 并发执行并等待全部完成
来源：http://dali.redwolf501.top/Article/details/gtvqiwdfxo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangdashe.top/Article/details/gtaocijxee.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hywenlv.cn/Article/details/gtwxznzfom.html

JS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gtplgcrfzr.html

TS:   await Promise.all(tasks)
来源：http://dali.9152youxi.cn/Article/details/gtplnrlail.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guannengcc.top/Article/details/gtxxygwdls.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwngefwx.html

Ruby: threads.map(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gtxpnfaeeo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhoulong.xyz/Article/details/gtgitdjwon.html

[O06] 使用进程池
来源：http://dali.ybcxt.top/Article/details/gtvyicgcvc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuanzhike.top/Article/details/gtbzbniuen.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yangfankeji.com/Article/details/gtkntpvqdj.html

JS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gtzoljozuu.html

TS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gtmnwdcooo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gtmwcirupj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yuanzhike.top/Article/details/gtgugzwvvf.html

Ruby: // fork 块
来源：http://dali.yj20258.top/Article/details/gtqyzukdjm.html

C#:   Parallel.For
来源：http://dali.smart0.xyz/Article/details/gtynavllwb.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtkvojoeoe.html

P. 常用工具函数
来源：http://dali.hongshengwenyu.top/Article/details/gtsivjphaf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtxxxlower.html

[P01] 生成 UUID
来源：http://dali.chenzaomai.com/Article/details/gtppmoowrg.html

Py:   str(uuid.uuid4())
来源：http://dali.nanxinkj.top/Article/details/gtxptelzsj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aibaodan.cn/Article/details/gtvcabdmnd.html

JS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gttyvtvnof.html

TS:   crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gtgbkrgehs.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtagkqnrlk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.meibo888.top/Article/details/gtnqoexdsc.html

Ruby: SecureRandom.uuid
来源：http://dali.meibo888.top/Article/details/gtkwyubhyv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cqqwz.cn/Article/details/gtilhtvetv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258888.top/Article/details/gtfgjmowrn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhengqikj.top/Article/details/gtcldpttja.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xuanzx.com/Article/details/gtkqdqmkhy.html


<!-- 参考信息 -->