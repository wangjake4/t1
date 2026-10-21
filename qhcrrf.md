代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gzhubu.top/Article/details/gtclriuadf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sufxvd.cn/Article/details/gtlzbipqyr.html

[L05] 上传文件（multipart）
来源：http://dali.zycfv.cn/Article/details/gtmzksnmcm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nwbrower.top/Article/details/gtmxubzhgo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.c1oappe.top/Article/details/gtbpkwkiii.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gtbfivnbkq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gtjlobqukq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinghuilouyu.cn/Article/details/gtznhvyvsh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hysaishi.cn/Article/details/gtzrujzoxr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aizwys.cn/Article/details/gtldaqledb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtkdnpgvbf.html

[L06] 解析响应为 JSON
来源：http://dali.chenzaomai.com/Article/details/gtthelvjnd.html

Py:   resp.json()
来源：http://dali.ybcxt.top/Article/details/gtsyvgrqzg.html

PHP:  json_decode($body, true);
来源：http://dali.gogol.net.cn/Article/details/gtjfgzdztw.html

JS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtqnmjrtvj.html

TS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gtcipeybcn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gtegpxglmh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258888.top/Article/details/gthwtbzllz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dianchejie.cn/Article/details/gtggovlwuu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tian-w.cn/Article/details/gtjwmjappd.html

[L07] 处理 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gtlrulhqsj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yueranfly.top/Article/details/gtqymaxlcp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.kuanghao11.cn/Article/details/gtafwcgwzs.html

JS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gtnidogfjw.html

TS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gtgtbkllbc.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelibagcn.html

Go:   resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gtjieqavse.html

Ruby: resp.code.to_i
来源：http://dali.pengpengdd.cyou/Article/details/gtxgfzjfna.html

C#:   (int)resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gthettqiqc.html

[L08] 并发请求多个地址
来源：http://dali.vqdsnc.cn/Article/details/gtymllmxfv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ehwqpu.com/Article/details/gtlpsiaxai.html

PHP:  curl_multi_init() 系列
来源：http://dali.cdnleiting.top/Article/details/gtrguxejqz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtovewsnrb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtzuadibyh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sxryk.cn/Article/details/gtlpiguswe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhiwuduotai.top/Article/details/gtdwdqcdfw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gtvjqaqodd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gteslfbtxk.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtaxqqcpwz.html

M. 命令行 / 进程 / 环境
来源：http://dali.fzhhl.top/Article/details/gtpuxlzmva.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtbjlaecfe.html

[M01] 读取命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gtvsdoecxz.html

Py:   sys.argv[1:]
来源：http://dali.aibaodan.cn/Article/details/gtlhtoyczp.html

PHP:  $argv;  $argc;
来源：http://dali.vqdsnc.cn/Article/details/gtwybzylsr.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gteduvhkax.html

TS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtbtwoworq.html

Java: args 数组（main 方法参数）
来源：http://dali.sweek.top/Article/details/gtzhgyqsar.html

Go:   os.Args[1:]
来源：http://dali.hywenlv.cn/Article/details/gtkkfmhtqv.html

Ruby: ARGV
来源：http://dali.fengsongda.top/Article/details/gtacfleoww.html

C#:   args 数组（Main 方法参数）
来源：http://dali.havefunace.top/Article/details/gtxmzsuluw.html

[M02] 读取环境变量
来源：http://dali.gaohongyu789.top/Article/details/gtpmfhxqcp.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtrjuiramc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cheryme.top/Article/details/gtchpztuht.html

JS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gttjmussmw.html

TS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gthgszisqq.html

Java: System.getenv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtoozklxpe.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtgoiqjdgv.html

Ruby: ENV["HOME"]
来源：http://dali.mhx1999.top/Article/details/gtqvtfqugm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xinyue.icu/Article/details/gtowaukvpz.html

[M03] 执行外部命令
来源：http://dali.havefunace.top/Article/details/gtsawjhaos.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daria6918.cn/Article/details/gtcshkheia.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gtaezbrois.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gthroulpfd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtktmcpypl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigufen.top/Article/details/gthgothsdt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gtixugcijv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ivvv.top/Article/details/gtwavcfhap.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yonumen.top/Article/details/gtdgdfpokh.html

[M04] 获取当前工作目录
来源：http://dali.zhixingplan.top/Article/details/gtdrovaibt.html

Py:   os.getcwd()
来源：http://dali.ivvv.top/Article/details/gtqbdzscnb.html

PHP:  getcwd();
来源：http://dali.jiagoushi.top/Article/details/gtjzhuoftl.html

JS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gtlmsegaib.html

TS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gtrfhgbbhp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258.top/Article/details/gtusyhbqso.html

Go:   os.Getwd()
来源：http://dali.jianghu66.top/Article/details/gtjwpmkjgt.html

Ruby: Dir.pwd
来源：http://dali.chenjidiqi.icu/Article/details/gthuokublo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yangfankeji.com/Article/details/gtukpkdxzk.html

[M05] 设置退出码
来源：http://dali.zdqjudy.top/Article/details/gtbmzoersu.html

Py:   sys.exit(1)
来源：http://dali.yj20258.top/Article/details/gtyfgdhdkn.html

PHP:  exit(1);
来源：http://dali.aibaodan.cn/Article/details/gtbnujmryc.html

JS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtuydqndcl.html

TS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtyfrebpbd.html

Java: System.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtkbmzdvju.html

Go:   os.Exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtvfyljtgw.html

Ruby: exit 1
来源：http://dali.hfpthk.cn/Article/details/gtxblfcwck.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ybcxt.top/Article/details/gtsichiinm.html

[M06] 向标准错误输出
来源：http://dali.xuanzx.com/Article/details/gtajntmfha.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxuanxn.top/Article/details/gtortvcvas.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxuanxn.top/Article/details/gtrdernyxm.html

JS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtgenjhoqr.html

TS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gtjihjfqmf.html

Java: System.err.println("err")
来源：http://dali.jqgfzy.top/Article/details/gtfgadejdk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shuidangran.top/Article/details/gtbqseylkp.html

Ruby: warn "err"
来源：http://dali.dashuyun.cn/Article/details/gtrpespmmp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258.top/Article/details/gtwvburccj.html

[M07] 判断是否为主入口
来源：http://dali.xylfe.cn/Article/details/gtrgptkffd.html

Py:   if __name__ == "__main__":
来源：http://dali.yangfankeji.com/Article/details/gtnzndifsv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.daxiang520.top/Article/details/gtkjbjblan.html

JS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtrgnpufgd.html

TS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gtthcsqfqc.html

Java: public static void main(String[] args)
来源：http://dali.jyoumei.cn/Article/details/gttdptddxs.html

Go:   func main()
来源：http://dali.snrcjt.cn/Article/details/gtcnqtbons.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgufenzy.top/Article/details/gtglvvcqhe.html

C#:   static void Main(string[] args)
来源：http://dali.jyoumei.cn/Article/details/gtcnaqhgoc.html

[M08] 获取系统与运行时信息
来源：http://dali.jinqigufen.top/Article/details/gtivasojrz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gaohongyu789.top/Article/details/gtmxtcakhr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ybcxt.top/Article/details/gtgugvbhba.html

JS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gtjnzvwdez.html

TS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gtimqiotfd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.vqdsnc.cn/Article/details/gttwewomcn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgufenzy.top/Article/details/gtobcrzevk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sxryk.cn/Article/details/gtozjvevfe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yvedp.cn/Article/details/gtvsssghkg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtcobdnswi.html

N. 数据结构与算法
来源：http://dali.wangdashe.top/Article/details/gtgszwntsf.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtridbckja.html

[N01] 二分查找（有序数组）
来源：http://dali.zhoulong.xyz/Article/details/gtvenemhdk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtlfuwgnfz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtlpdrvdhj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tanke756.top/Article/details/gttfpovvke.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtscjlxbks.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtqwbjztrn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtpfpkrsdh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.redwolf501.top/Article/details/gtyiffccyk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqaetlvco.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sweek.top/Article/details/gtggfxpfli.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gtwciobdvo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ehwqpu.com/Article/details/gtlifoomsd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gtlajrblcw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtsibnobpi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jlsjyb.cn/Article/details/gtcvaaztfm.html

Go:   slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtkpxqzfls.html

Ruby: arr.sort
来源：http://dali.yonumen.top/Article/details/gttphprlcf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zycfv.cn/Article/details/gtrrmruwxw.html

[N03] 快速排序（分治示例）
来源：http://dali.guannengcc.top/Article/details/gtxyocvvre.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.haohaochexian.top/Article/details/gtbjhojkdy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhongyouzk.top/Article/details/gtllzyajbe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gtbqnhwrjs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gtlufigcle.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.316326.xyz/Article/details/gtwntzwhwm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yongpay.top/Article/details/gtqpnjwqtm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gzhubu.top/Article/details/gtmkzwrdzu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hongshengwenyu.top/Article/details/gtjquzweab.html

[N04] 斐波那契数列
来源：http://dali.jqgufenzy.top/Article/details/gtsvmtktlt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gtkdtevkkv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gtdsmjuaga.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtgibsmbdh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzhqtwqi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.c1oappe.top/Article/details/gtskirhgeg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.bjfxy.top/Article/details/gtiffpwjew.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gtueofhwux.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtbjvpsbyi.html

[N05] 最大公约数
来源：http://dali.ydzc1.top/Article/details/gtqwezrkmw.html

Py:   math.gcd(a, b)
来源：http://dali.hammf.cn/Article/details/gtmquecbgr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sufxvd.cn/Article/details/gtfkceucnk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gtqjdhixgv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gthyerttlw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aizwys.cn/Article/details/gtiijjtncv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuxming.cn/Article/details/gtvaeckgks.html

Ruby: a.gcd(b)
来源：http://dali.jlsjyb.cn/Article/details/gtscbboktu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xziqi.cn/Article/details/gtfnryyixm.html

[N06] 判断回文字符串
来源：http://dali.pycfn.com/Article/details/gtjieisinx.html

Py:   s == s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gthxhcwggk.html

PHP:  $s === strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtyroaourp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtyaeykzbk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtrqyekmnx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shangyingyoupin.top/Article/details/gtbfgaacll.html

Go:   // 双指针从两端比较
来源：http://dali.havefunace.top/Article/details/gtiaqnkiac.html

Ruby: s == s.reverse
来源：http://dali.tian-w.cn/Article/details/gtmaxuodaq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcdoolfe.html

[N07] 两数之和（返回下标）
来源：http://dali.0kj1m.cn/Article/details/gtutpcongy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.snrcjt.cn/Article/details/gtkfqrjlpa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zdqjudy.top/Article/details/gtsdrtswhv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hywenlv.cn/Article/details/gteoagehfe.html

TS:   // 手写 Map<string, number>
来源：http://dali.tian-w.cn/Article/details/gtdcxmzamh.html

Java: // 手写 HashMap
来源：http://dali.xylfe.cn/Article/details/gttnuxrgxn.html

Go:   // 手写 map[int]int
来源：http://dali.yvedp.cn/Article/details/gtyhbhthbf.html

Ruby: // 手写 Hash
来源：http://dali.xylfe.cn/Article/details/gtbnwinteq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guowangkeji.top/Article/details/gtqmocjvdf.html

[N08] 生成全排列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxoxaoft.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrjlncyu.html

PHP:  // 手写递归交换
来源：http://dali.jinqigufen.top/Article/details/gtntbtayrd.html

JS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtvcnarqac.html

TS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtpzhdvxni.html

Java: // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtsuhsllrh.html

Go:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtzyfawomd.html

Ruby: arr.permutation.to_a
来源：http://dali.feifeiyinyue.top/Article/details/gtyduzbwvg.html

C#:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtstbthuen.html

[N09] 栈与队列
来源：http://dali.jyoumei.cn/Article/details/gtgjolnxdj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fzhhl.top/Article/details/gtnacbavqr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrkhjgdg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtxlgtekbw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenzaomai.com/Article/details/gtotuaelpt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hfpthk.cn/Article/details/gttlzekfbn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangshuangyany.cn/Article/details/gtldxiyjok.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtalilcxzr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shzxlz.cn/Article/details/gtoijecypl.html

[N10] 链表节点定义
来源：http://dali.chenlongwang.top/Article/details/gtbqkqbykg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xinyue.icu/Article/details/gtfimtzcjq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxinkj.top/Article/details/gtpgvufrbx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258.top/Article/details/gtbxtshqhf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sufxvd.cn/Article/details/gtdencdilh.html

Java: class Node { int v; Node next; }
来源：http://dali.cqqwz.cn/Article/details/gtpkcgupsr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.meibo888.top/Article/details/gttziopvez.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yvedp.cn/Article/details/gtvskjhhem.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiigxxcnr.html

[N11] 二叉树中序遍历
来源：http://dali.jyoumei.cn/Article/details/gtbrmevkii.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.andypj.xyz/Article/details/gtuhknmkje.html

PHP:  // 手写递归函数
来源：http://dali.kuanghao11.cn/Article/details/gtfzqmnazl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gtpnzshokb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gtjxeubuet.html

Java: // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzdptydy.html

Go:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gtougmnxjx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhongyouzk.top/Article/details/gtxadkazcn.html

C#:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtlgwtmlbk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fzhhl.top/Article/details/gtalsangrd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.birdmap.top/Article/details/gtdkdxvres.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjqgmveb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gteedrkpgw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sysykeji.top/Article/details/gtajasghsx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gtmgspfsra.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xziqi.cn/Article/details/gthrrweful.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtqbxwlqtu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtrbzryduc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtwmubybzn.html

O. 并发与异步
来源：http://dali.nanxuanxn.top/Article/details/gttkdgbsnn.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtlmuhobfx.html

[O01] 启动一个线程
来源：http://dali.bjfxy.top/Article/details/gtyvhpjstm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gteoaiosob.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258.top/Article/details/gtvxlajrmi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhiwuduotai.top/Article/details/gtfdippszc.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gtcpxrsthn.html

Java: new Thread(() -> f()).start()
来源：http://dali.316326.xyz/Article/details/gtpabwrjke.html

Go:   go f()
来源：http://dali.guowangkeji.top/Article/details/gtzyqdmqgp.html

Ruby: Thread.new { f }
来源：http://dali.hnxiangtu.top/Article/details/gtkguhaopc.html

C#:   Task.Run(() => F());
来源：http://dali.xuetiantiany.cn/Article/details/gtxazjfzbd.html

[O02] 使用线程池
来源：http://dali.haohaochexian.top/Article/details/gtxvtlefsf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgixgqzd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sweek.top/Article/details/gtltjlfshx.html

JS:   // worker_threads 线程池
来源：http://dali.zhixingplan.top/Article/details/gthyrbpzib.html

TS:   // worker_threads 线程池
来源：http://dali.haohaochexian.top/Article/details/gtiixbqupl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cdnleiting.top/Article/details/gttbdkwbgn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangshuangyany.cn/Article/details/gtlircfkrp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvovctnne.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tianlin.xyz/Article/details/gtuwoirmdz.html

[O03] 加锁保护共享数据
来源：http://dali.jqgfzy.top/Article/details/gthrwjtqcs.html

Py:   with lock: shared += 1
来源：http://dali.ehwqpu.com/Article/details/gtmraesagy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yangfankeji.com/Article/details/gtzsnfyqev.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pycfn.com/Article/details/gtsbatmyvt.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gtyqcadyph.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gtscpfldpm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yanxiufei.cn/Article/details/gtrfsfwvnb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jianghu66.top/Article/details/gtgwulezhs.html

C#:   lock (gate) { shared++; }
来源：http://dali.daxiang520.top/Article/details/gtnbapvlpg.html

[O04] 定义异步函数并等待
来源：http://dali.jqgufenzy.top/Article/details/gtccvkgbob.html

Py:   async def f():⏎    await g()
来源：http://dali.sweek.top/Article/details/gttisvnjyy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcfomqis.html

JS:   async function f() { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gtcuzweekt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtkwxjfqlp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenzaomai.com/Article/details/gtlcymlwte.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shuidangran.top/Article/details/gtmxxvcmqo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhoulong.xyz/Article/details/gtvifawalw.html

C#:   async Task F() { await G(); }
来源：http://dali.jyoumei.cn/Article/details/gthwfsxqrb.html

[O05] 并发执行并等待全部完成
来源：http://dali.vqdsnc.cn/Article/details/gtuhmmvlox.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daxiang520.top/Article/details/gtryjhxfsn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shuidangran.top/Article/details/gtyuoftehy.html

JS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gthctphsbu.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gtqvdjdlhy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.dashuyun.cn/Article/details/gtpxrxkhyu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhengqikj.top/Article/details/gtwerssjtc.html

Ruby: threads.map(&:join)
来源：http://dali.chenlongwang.top/Article/details/gtzzcibyxj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangdashe.top/Article/details/gtmxlghusn.html

[O06] 使用进程池
来源：http://dali.bjfxy.top/Article/details/gtemgypxnn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pycfn.com/Article/details/gtbgihlwgt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnqzz.top/Article/details/gthmkpvneo.html

JS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gtjzuwdexk.html

TS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gtbivalldg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yvedp.cn/Article/details/gtrhfodjrx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tian-w.cn/Article/details/gtqmghbnnr.html

Ruby: // fork 块
来源：http://dali.hywenlv.cn/Article/details/gterkxbtxx.html

C#:   Parallel.For
来源：http://dali.hammf.cn/Article/details/gthespvfte.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtfuzdwoia.html

P. 常用工具函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtcnwaobkf.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtrbdzzowq.html

[P01] 生成 UUID
来源：http://dali.guannengcc.top/Article/details/gtnbkofpxf.html

Py:   str(uuid.uuid4())
来源：http://dali.guowangkeji.top/Article/details/gtmvvsuayv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuanzx.com/Article/details/gtxphsrrvx.html

JS:   crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gtsbyohkwt.html

TS:   crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gtessliyjq.html

Java: UUID.randomUUID().toString()
来源：http://dali.9152youxi.cn/Article/details/gtkmrenveq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.birdmap.top/Article/details/gtwoyjnrvj.html

Ruby: SecureRandom.uuid
来源：http://dali.jianghu66.top/Article/details/gtbajlpdyz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zycfv.cn/Article/details/gtmxeyflwj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zdqjudy.top/Article/details/gthalsckif.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nwbrower.top/Article/details/gtnwedquzg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.meibo888.top/Article/details/gtkmrmedlu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.bjfxy.top/Article/details/gtjhdpgsrz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.kuanghao11.cn/Article/details/gthugdtzht.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtivcdqdre.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daria6918.cn/Article/details/gtmwndjisg.html


<!-- 参考信息 -->