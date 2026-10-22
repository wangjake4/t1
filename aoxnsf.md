代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hongshengwenyu.top/Article/details/gtdqdyyamz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ivvv.top/Article/details/gtwsyfivch.html

[L05] 上传文件（multipart）
来源：http://dali.yuanzhike.top/Article/details/gtqrqghsko.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenzaomai.com/Article/details/gtyqrghwkg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxoiqzspa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gtwjunoyle.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sxryk.cn/Article/details/gtudggpsdj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yanxiufei.cn/Article/details/gtrzlhpkyt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigufen.top/Article/details/gtwtcvgyxz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hysaishi.cn/Article/details/gtnzlannza.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xinyue.icu/Article/details/gtrcoghamg.html

[L06] 解析响应为 JSON
来源：http://dali.9152youxi.cn/Article/details/gtfvdewcsf.html

Py:   resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtizubnzck.html

PHP:  json_decode($body, true);
来源：http://dali.haohaochexian.top/Article/details/gtlswaqdoh.html

JS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gtjozpxxww.html

TS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtdnmsifgk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtlqnvdupx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zycfv.cn/Article/details/gtalqlgamu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.bjfxy.top/Article/details/gtuvztqqnh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofcaxthg.html

[L07] 处理 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gtfieclppx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ehwqpu.com/Article/details/gtikurcqrh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuanzx.com/Article/details/gtlngtvvql.html

JS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gtnoyxvpmu.html

TS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gtybztbvwf.html

Java: resp.statusCode()
来源：http://dali.dianchejie.cn/Article/details/gthwicolwy.html

Go:   resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gtjmaagcca.html

Ruby: resp.code.to_i
来源：http://dali.daria6918.cn/Article/details/gtorbfvpjm.html

C#:   (int)resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gtepyisdmz.html

[L08] 并发请求多个地址
来源：http://dali.yj20258.top/Article/details/gtkryrogcm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gaohongyu789.top/Article/details/gtysebmapm.html

PHP:  curl_multi_init() 系列
来源：http://dali.birdmap.top/Article/details/gtbmjgfqiq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gtasqwhjgs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gtlsaptokb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhaomingkeji.xyz/Article/details/gteourmfel.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.mhx1999.top/Article/details/gtjpznnjap.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ivvv.top/Article/details/gtsmeamaba.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hywenlv.cn/Article/details/gtiqqgcuzk.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtfxszwrnf.html

M. 命令行 / 进程 / 环境
来源：http://dali.yonumen.top/Article/details/gtbcipsbvv.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtwowzaccx.html

[M01] 读取命令行参数
来源：http://dali.yuanzhike.top/Article/details/gtnsgjotoq.html

Py:   sys.argv[1:]
来源：http://dali.nanxuanxn.top/Article/details/gtrdkemzsq.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvgafmafp.html

JS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkprtcdfj.html

TS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gtqgnjxnfb.html

Java: args 数组（main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtquzkgjup.html

Go:   os.Args[1:]
来源：http://dali.dashuyun.cn/Article/details/gtuvazfiwx.html

Ruby: ARGV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwpqqrbj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gttjszfpvx.html

[M02] 读取环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtimozfygq.html

Py:   os.environ.get("HOME")
来源：http://dali.hfpthk.cn/Article/details/gthpfrfgge.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gtiqoamycq.html

JS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gtrrmuevmy.html

TS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gtonmldiot.html

Java: System.getenv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtsicvtyol.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gthggkfnbb.html

Ruby: ENV["HOME"]
来源：http://dali.zycfv.cn/Article/details/gtaduscqix.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtfcgdjimr.html

[M03] 执行外部命令
来源：http://dali.gzhubu.top/Article/details/gtoqjocyez.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.birdmap.top/Article/details/gtyshvmain.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jianghu66.top/Article/details/gtqcgqwlyk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtlnsscjxt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtawwsuwik.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hywenlv.cn/Article/details/gtslbegfpu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hfpthk.cn/Article/details/gtkmmxzeoh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cdnleiting.top/Article/details/gtrhtwcmrg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gtabiqbbxi.html

[M04] 获取当前工作目录
来源：http://dali.hywenlv.cn/Article/details/gtbsglrfzd.html

Py:   os.getcwd()
来源：http://dali.jinqigfzy.top/Article/details/gtgslldgdz.html

PHP:  getcwd();
来源：http://dali.yueranfly.top/Article/details/gthrvijawz.html

JS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtlbudqjyx.html

TS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gtngqrpaue.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxuanxn.top/Article/details/gtdkamygpf.html

Go:   os.Getwd()
来源：http://dali.jqgufenzy.top/Article/details/gtquutwbiq.html

Ruby: Dir.pwd
来源：http://dali.jqgufenzy.top/Article/details/gttecshpdl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ybcxt.top/Article/details/gtnteknxey.html

[M05] 设置退出码
来源：http://dali.jinqigufen.top/Article/details/gtrctrlssf.html

Py:   sys.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtmcuiimcb.html

PHP:  exit(1);
来源：http://dali.feifeiyinyue.top/Article/details/gtgburvuee.html

JS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtqgxtukwo.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtrexbpwfm.html

Java: System.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtlbhotpym.html

Go:   os.Exit(1)
来源：http://dali.shuidangran.top/Article/details/gtclcadqom.html

Ruby: exit 1
来源：http://dali.yuxming.cn/Article/details/gtgvwlwuek.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinghuilouyu.cn/Article/details/gtentwkowx.html

[M06] 向标准错误输出
来源：http://dali.guowangkeji.top/Article/details/gtjtedorvf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.quarkkingdee.top/Article/details/gtebatfqjh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jiagoushi.top/Article/details/gtiafovdlp.html

JS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtubqhdpye.html

TS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gtotgrmxok.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gtpfiydzji.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sysykeji.top/Article/details/gtzkhlinou.html

Ruby: warn "err"
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdgotqwl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yonumen.top/Article/details/gthasdbwaq.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangtech.top/Article/details/gtmaatoxwu.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gtpnxbmsbq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fzhhl.top/Article/details/gtsumqzvig.html

JS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifqwidic.html

TS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gtmrfsuxji.html

Java: public static void main(String[] args)
来源：http://dali.shzxlz.cn/Article/details/gtydvemsik.html

Go:   func main()
来源：http://dali.wangshuangyany.cn/Article/details/gtdqiyjtlo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tianlin.xyz/Article/details/gtbziqeyaj.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gtaswunhjl.html

[M08] 获取系统与运行时信息
来源：http://dali.chenjidiqi.icu/Article/details/gtgtkemrci.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gaohongyu789.top/Article/details/gtoghaihtp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.bjfxy.top/Article/details/gttpmexhry.html

JS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gtmgzenexs.html

TS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gtarbitmqk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.c1oappe.top/Article/details/gtokxzrnox.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgufenzy.top/Article/details/gtwzntulvl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhaomingkeji.xyz/Article/details/gtboocjuqm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gtskswrgzl.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtfqplkwer.html

N. 数据结构与算法
来源：http://dali.chenjidiqi.icu/Article/details/gtlbedixsq.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtlagndoif.html

[N01] 二分查找（有序数组）
来源：http://dali.svipenyu.cn/Article/details/gtbkebswbl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtvvhbybwd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jianghu66.top/Article/details/gtsejzmpam.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gtzhgziyfa.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtezrzkwzp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gtenwtfegm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtbujgnszj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.9152youxi.cn/Article/details/gtwoypuvnx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.316326.xyz/Article/details/gttltloyur.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.havefunace.top/Article/details/gtmnwczoao.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gtrohdisrk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hysaishi.cn/Article/details/gtdxgmluhq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gtdopuejve.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gtqcgodsij.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zycfv.cn/Article/details/gtwtsexpon.html

Go:   slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gtpcytsigo.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gtnafmxwrw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.andypj.xyz/Article/details/gtvdskqily.html

[N03] 快速排序（分治示例）
来源：http://dali.cheryme.top/Article/details/gtwbsxkxez.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtroulqndk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.svipenyu.cn/Article/details/gtaqpdyfih.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gtzejisgni.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gtjhjowgap.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nwbrower.top/Article/details/gtpznyhizx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigfzy.top/Article/details/gtmsfrtsej.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.birdmap.top/Article/details/gtrglkvrno.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenjidiqi.icu/Article/details/gtzsihetfu.html

[N04] 斐波那契数列
来源：http://dali.xinyue.icu/Article/details/gtquccjvss.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gtfhcxyxin.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtqrfubvus.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtzuzswxkp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtftizzehg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gtwqpdcyku.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangshuangyany.cn/Article/details/gtqxhlzyji.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hnqzz.top/Article/details/gtospyhisg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtsefmcmrw.html

[N05] 最大公约数
来源：http://dali.316326.xyz/Article/details/gtwcarqvwl.html

Py:   math.gcd(a, b)
来源：http://dali.sxryk.cn/Article/details/gtgpmoblra.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cqqwz.cn/Article/details/gtunaucfxl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gtbecwtcai.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gtsacyhsrw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenjidiqi.icu/Article/details/gtuumeoamo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258888.top/Article/details/gtbgzazwwz.html

Ruby: a.gcd(b)
来源：http://dali.sysykeji.top/Article/details/gthqswslwg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jlsjyb.cn/Article/details/gtcykmiwff.html

[N06] 判断回文字符串
来源：http://dali.hfpthk.cn/Article/details/gtkidopfwx.html

Py:   s == s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtcuafgnns.html

PHP:  $s === strrev($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtwqrjdnwq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtjztutzbg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtxbdzbiss.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigufen.top/Article/details/gtlerxrjtd.html

Go:   // 双指针从两端比较
来源：http://dali.xuetiantiany.cn/Article/details/gtcjvqgoew.html

Ruby: s == s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbajbenrx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gtoxmchrud.html

[N07] 两数之和（返回下标）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkxbyyoy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dashuyun.cn/Article/details/gtksjkcfuz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.haohaochexian.top/Article/details/gtkzykryzx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daxiang520.top/Article/details/gttbtrraes.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhixingplan.top/Article/details/gtpyrhnozj.html

Java: // 手写 HashMap
来源：http://dali.meibo888.top/Article/details/gtqumnazgh.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigfzy.top/Article/details/gttjlkktoc.html

Ruby: // 手写 Hash
来源：http://dali.redwolf501.top/Article/details/gtaiygnrvq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xziqi.cn/Article/details/gtzfbrgazh.html

[N08] 生成全排列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdmlrhaw.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxinkj.top/Article/details/gtuvhemszb.html

PHP:  // 手写递归交换
来源：http://dali.meibo888.top/Article/details/gtyvlelioy.html

JS:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtznhcxkde.html

TS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtaercwcsl.html

Java: // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtfgltmdnd.html

Go:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtdbzjvhdf.html

Ruby: arr.permutation.to_a
来源：http://dali.cucudq.cn/Article/details/gtqcfblqen.html

C#:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtkphufihu.html

[N09] 栈与队列
来源：http://dali.aibaodan.cn/Article/details/gtnwnxrbvz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yongpay.top/Article/details/gtwpnozvik.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtgdnjljeb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtfjriiuoj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuetiantiany.cn/Article/details/gtpnrandxa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.havefunace.top/Article/details/gtpriyjsxd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hammf.cn/Article/details/gtikvxjmgz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtpthlonqv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.andypj.xyz/Article/details/gtsuuumxsv.html

[N10] 链表节点定义
来源：http://dali.gaohongyu789.top/Article/details/gtekaylpwo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhixingplan.top/Article/details/gtmnbnxeoq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zycfv.cn/Article/details/gthxbgztvd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.9152youxi.cn/Article/details/gttipamazi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.316326.xyz/Article/details/gtlcflorog.html

Java: class Node { int v; Node next; }
来源：http://dali.dianchejie.cn/Article/details/gtedprxbkh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gzhubu.top/Article/details/gtstsoobpd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yanxiufei.cn/Article/details/gtcvfvgnkd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hongshengwenyu.top/Article/details/gttgmhlnkl.html

[N11] 二叉树中序遍历
来源：http://dali.hnxiangtu.top/Article/details/gtwipuvrbt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dashuyun.cn/Article/details/gtdrmrzowt.html

PHP:  // 手写递归函数
来源：http://dali.tianlin.xyz/Article/details/gtkcuzyrph.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gtrdwnahha.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhoulong.xyz/Article/details/gtsytslgrl.html

Java: // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwugofqrx.html

Go:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gtrimbpoia.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvnzxkfx.html

C#:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gtibodrndm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhongyouzk.top/Article/details/gtqiyjysmj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tianlin.xyz/Article/details/gtofmvbanr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jianghu66.top/Article/details/gttuyxszxp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.c1oappe.top/Article/details/gtynilnfom.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gtlimpzdvj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gaohongyu789.top/Article/details/gtcsbkxdzg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.316326.xyz/Article/details/gtavppaimi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sufxvd.cn/Article/details/gtbfrklllz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gtjmbmythr.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtpqmqgkzo.html

O. 并发与异步
来源：http://dali.nwbrower.top/Article/details/gtkckvrfgp.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gthsaublcb.html

[O01] 启动一个线程
来源：http://dali.316326.xyz/Article/details/gtyifybohv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tianlin.xyz/Article/details/gtyloylepw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ydzc1.top/Article/details/gtzrmeeilw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ehwqpu.com/Article/details/gtqfmhfzap.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gtrsteshpy.html

Java: new Thread(() -> f()).start()
来源：http://dali.hongshengwenyu.top/Article/details/gtqxwjtbli.html

Go:   go f()
来源：http://dali.yonumen.top/Article/details/gtlnkpeckc.html

Ruby: Thread.new { f }
来源：http://dali.yj202588.top/Article/details/gtgmxzlbzd.html

C#:   Task.Run(() => F());
来源：http://dali.tianlin.xyz/Article/details/gtudjplufq.html

[O02] 使用线程池
来源：http://dali.yanxiufei.cn/Article/details/gtrsimebeh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zdqjudy.top/Article/details/gtseippbdi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yuxming.cn/Article/details/gtyikfxjvz.html

JS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtqnrxyvcm.html

TS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gtjstqclim.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.smart0.xyz/Article/details/gtvqnrhacx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.svipenyu.cn/Article/details/gtsetnvpjc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnqzz.top/Article/details/gtnxyvtutp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbnbhyuo.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258888.top/Article/details/gtdrkomjhx.html

Py:   with lock: shared += 1
来源：http://dali.jyoumei.cn/Article/details/gtfyuihhsh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jiagoushi.top/Article/details/gtlpgksgan.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.feifeiyinyue.top/Article/details/gtzjmuplsw.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gtqktooexf.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhengqikj.top/Article/details/gtnctxczcn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yueranfly.top/Article/details/gtvagkzejz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daria6918.cn/Article/details/gtlqcameno.html

C#:   lock (gate) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gtqlofnyul.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigufen.top/Article/details/gtspljhboi.html

Py:   async def f():⏎    await g()
来源：http://dali.chenjidiqi.icu/Article/details/gtwwadapcb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hongshengwenyu.top/Article/details/gtucrksoba.html

JS:   async function f() { await g(); }
来源：http://dali.aizwys.cn/Article/details/gtqiznppty.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yvedp.cn/Article/details/gtvviyywjs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gzhubu.top/Article/details/gtmnwewzpv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jianghu66.top/Article/details/gtllukocdy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhixingplan.top/Article/details/gtlisezxof.html

C#:   async Task F() { await G(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfekacpqw.html

[O05] 并发执行并等待全部完成
来源：http://dali.gotoacloud.top/Article/details/gtvwhvelln.html

Py:   asyncio.gather(*tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtbebuegus.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daxiang520.top/Article/details/gtpqzkqsjp.html

JS:   await Promise.all(tasks)
来源：http://dali.tian-w.cn/Article/details/gthcnizbpj.html

TS:   await Promise.all(tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtzvohimrx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gtxnfyaesq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.meibo888.top/Article/details/gtoqunxvwa.html

Ruby: threads.map(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gttcekqyhn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pengpengdd.cyou/Article/details/gtvxkxvaqf.html

[O06] 使用进程池
来源：http://dali.nanxinkj.top/Article/details/gtsbrjeyve.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.smart0.xyz/Article/details/gtccvcrnqn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zycfv.cn/Article/details/gtfoiutkvk.html

JS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gtmxddqplj.html

TS:   // child_process / cluster 模块
来源：http://dali.jyoumei.cn/Article/details/gtlipfmemv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ybcxt.top/Article/details/gtpccjifyf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.pengpengdd.cyou/Article/details/gtamdlwgpf.html

Ruby: // fork 块
来源：http://dali.jqgfzy.top/Article/details/gtoyvxwrod.html

C#:   Parallel.For
来源：http://dali.xuetiantiany.cn/Article/details/gthfjnbdnk.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtsdopuiqc.html

P. 常用工具函数
来源：http://dali.yonumen.top/Article/details/gthjrutbeu.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gttpmfhpfx.html

[P01] 生成 UUID
来源：http://dali.cashguo.top/Article/details/gtqpernjal.html

Py:   str(uuid.uuid4())
来源：http://dali.gzhubu.top/Article/details/gtwipjiqut.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gtyuudxuwc.html

JS:   crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gtcydkfjub.html

TS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gtfiwtkrjc.html

Java: UUID.randomUUID().toString()
来源：http://dali.0kj1m.cn/Article/details/gteepwlnco.html

Go:   // 用 github.com/google/uuid
来源：http://dali.redwolf501.top/Article/details/gtrdjwxuoa.html

Ruby: SecureRandom.uuid
来源：http://dali.yongpay.top/Article/details/gttalkiffs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj202588.top/Article/details/gtivrqkjri.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyolbphoz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.iojbl.cn/Article/details/gtgxhpknlh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.vqdsnc.cn/Article/details/gtevxqimom.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shangyingyoupin.top/Article/details/gtwdhlwxrc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ivvv.top/Article/details/gtllnxuyse.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.havefunace.top/Article/details/gtfgnmghsh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fzhhl.top/Article/details/gtcvmcrsqk.html


<!-- 参考信息 -->