代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ehwqpu.com/Article/details/gttulvnhis.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nwbrower.top/Article/details/gtfuncohwk.html

[L05] 上传文件（multipart）
来源：http://dali.chenlongwang.top/Article/details/gtisouswiv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aizwys.cn/Article/details/gtekuxmjxe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aizwys.cn/Article/details/gtyndqqxgx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gtyrwfjsaf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gtwodvcfpv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.wangdashe.top/Article/details/gtaqldznwk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jianghu66.top/Article/details/gtbbaejbux.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigufen.top/Article/details/gtaxekjdnd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtcayywnfp.html

[L06] 解析响应为 JSON
来源：http://dali.c1oappe.top/Article/details/gtrdelltce.html

Py:   resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtkprkxyka.html

PHP:  json_decode($body, true);
来源：http://dali.andypj.xyz/Article/details/gtmptbrzop.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gtrcehyugc.html

TS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtjabmixrj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.redwolf501.top/Article/details/gtgscrcogw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigufen.top/Article/details/gtuqdsmjdv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fzhhl.top/Article/details/gtpkbvfnro.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hfpthk.cn/Article/details/gtfdbguwha.html

[L07] 处理 HTTP 状态码
来源：http://dali.0kj1m.cn/Article/details/gturssjrxg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuetiantiany.cn/Article/details/gtuvxgnjyj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.bjfxy.top/Article/details/gtmurjpdhd.html

JS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtliqzbwsn.html

TS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gtvwrpkhrz.html

Java: resp.statusCode()
来源：http://dali.jyoumei.cn/Article/details/gtxuedigck.html

Go:   resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gtildsfizy.html

Ruby: resp.code.to_i
来源：http://dali.dashuyun.cn/Article/details/gtqjobvfbi.html

C#:   (int)resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gtsmiuzlkb.html

[L08] 并发请求多个地址
来源：http://dali.gaohongyu789.top/Article/details/gtcxdesjmw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.feifeiyinyue.top/Article/details/gttqkcoqwt.html

PHP:  curl_multi_init() 系列
来源：http://dali.tian-w.cn/Article/details/gtmycdjqgq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtufrxpdvp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gtsxnaifwq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.quarkkingdee.top/Article/details/gtyuzreazd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.svipenyu.cn/Article/details/gtoublcsrk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258.top/Article/details/gtmmpuvdow.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtzzbmupte.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxokezrrs.html

M. 命令行 / 进程 / 环境
来源：http://dali.haohaochexian.top/Article/details/gtzvhfxzgi.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtqtipgyga.html

[M01] 读取命令行参数
来源：http://dali.yuxming.cn/Article/details/gtzcszikpe.html

Py:   sys.argv[1:]
来源：http://dali.aizwys.cn/Article/details/gtrkgksvtd.html

PHP:  $argv;  $argc;
来源：http://dali.yonumen.top/Article/details/gtpnjjveip.html

JS:   process.argv.slice(2)
来源：http://dali.hnqzz.top/Article/details/gtuwsdndhb.html

TS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gttektlcwr.html

Java: args 数组（main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gtkflfpqxp.html

Go:   os.Args[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gtwzmfcqbi.html

Ruby: ARGV
来源：http://dali.nwbrower.top/Article/details/gtzefedeuk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gtvayiiurr.html

[M02] 读取环境变量
来源：http://dali.birdmap.top/Article/details/gtcjqcqpxl.html

Py:   os.environ.get("HOME")
来源：http://dali.shuidangran.top/Article/details/gtrxeugdui.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbdsfona.html

JS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gthxfvctdr.html

TS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gtcakfqwre.html

Java: System.getenv("HOME")
来源：http://dali.yj20258888.top/Article/details/gtbdotvmya.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtprqplmlx.html

Ruby: ENV["HOME"]
来源：http://dali.zycfv.cn/Article/details/gtiztuwloe.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shuidangran.top/Article/details/gtnwfhmnhp.html

[M03] 执行外部命令
来源：http://dali.yj20258888.top/Article/details/gtwkoccqdk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.bjfxy.top/Article/details/gtvbpfdszi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shuidangran.top/Article/details/gtlxpouxdq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gtbumuyhvv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gtewtaxujv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangdashe.top/Article/details/gtqvlqxscd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinyuanbaomall.cn/Article/details/gteddgyrbn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.smart0.xyz/Article/details/gtyfmfgulk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ydzc1.top/Article/details/gtsaxilysl.html

[M04] 获取当前工作目录
来源：http://dali.hfpthk.cn/Article/details/gtkroygbum.html

Py:   os.getcwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfrobnxr.html

PHP:  getcwd();
来源：http://dali.haohaochexian.top/Article/details/gtwoqzhmcu.html

JS:   process.cwd()
来源：http://dali.jiagoushi.top/Article/details/gtxvabruvo.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gtdnnxqctx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pengpengdd.cyou/Article/details/gtvyknirnc.html

Go:   os.Getwd()
来源：http://dali.guowangkeji.top/Article/details/gtzownslcg.html

Ruby: Dir.pwd
来源：http://dali.zhongyouzk.top/Article/details/gtjiwwriya.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenlongwang.top/Article/details/gtuisbwsac.html

[M05] 设置退出码
来源：http://dali.chenjidiqi.icu/Article/details/gtwkwjxyyi.html

Py:   sys.exit(1)
来源：http://dali.hammf.cn/Article/details/gtxksabbnf.html

PHP:  exit(1);
来源：http://dali.jyoumei.cn/Article/details/gtxeiqfbht.html

JS:   process.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gterlwqstq.html

TS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtcertnnow.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtuqnvjmzs.html

Go:   os.Exit(1)
来源：http://dali.sysykeji.top/Article/details/gtcjelvawr.html

Ruby: exit 1
来源：http://dali.hongshengwenyu.top/Article/details/gtoyjuvzku.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbgwnbzc.html

[M06] 向标准错误输出
来源：http://dali.daxiang520.top/Article/details/gtjokhoiey.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gtuyupkfne.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shuidangran.top/Article/details/gtuzjrutrr.html

JS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gtlklqfyse.html

TS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gtupcqcmek.html

Java: System.err.println("err")
来源：http://dali.cdnleiting.top/Article/details/gthxxnufsd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zycfv.cn/Article/details/gtnlvnquex.html

Ruby: warn "err"
来源：http://dali.hammf.cn/Article/details/gtfcdjweao.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgufenzy.top/Article/details/gtezpelqlj.html

[M07] 判断是否为主入口
来源：http://dali.pengpengdd.cyou/Article/details/gtrvhonyuw.html

Py:   if __name__ == "__main__":
来源：http://dali.daxiang520.top/Article/details/gtryenitqc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cashguo.top/Article/details/gtrihvjmfk.html

JS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gtyqujjpto.html

TS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gttdmtsbik.html

Java: public static void main(String[] args)
来源：http://dali.yuanzhike.top/Article/details/gtcclcdpno.html

Go:   func main()
来源：http://dali.wangdashe.top/Article/details/gtkxophbkd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenjidiqi.icu/Article/details/gtnevyyxrt.html

C#:   static void Main(string[] args)
来源：http://dali.daria6918.cn/Article/details/gtbhpbgsne.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszgwfnrq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjbqgqvw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gaohongyu789.top/Article/details/gtrbwurvyj.html

JS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gtqkxswlfn.html

TS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gthsqrsogz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tianlin.xyz/Article/details/gtkhkxxiyp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.meibo888.top/Article/details/gtkjccltuw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.snrcjt.cn/Article/details/gtfmgitzhy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxuanxn.top/Article/details/gtuuohfalh.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtirniirsm.html

N. 数据结构与算法
来源：http://dali.xinyue.icu/Article/details/gtzvdnrpby.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtvfouhfdi.html

[N01] 二分查找（有序数组）
来源：http://dali.zdqjudy.top/Article/details/gtbyeblcxs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtadeebvps.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuanzhike.top/Article/details/gtikskvtsp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gthshsmusm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gtowgmdxez.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtpqsrkjea.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtsudpxnxk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.quarkkingdee.top/Article/details/gtvgaimeci.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtbnhlsvnr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zycfv.cn/Article/details/gtztxduhiv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gtaqrjdlli.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daria6918.cn/Article/details/gtqpamamxe.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtwcuxzjnh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gtqsjamryg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpxsgwfk.html

Go:   slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gtmeriamxk.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtijnpumsb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigufen.top/Article/details/gtbeuzebsk.html

[N03] 快速排序（分治示例）
来源：http://dali.yj202588.top/Article/details/gtiblehrah.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zdqjudy.top/Article/details/gtzibkielr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yueranfly.top/Article/details/gtzklbjnxo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnpnkoeb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gtjmvoiuma.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aibaodan.cn/Article/details/gtucpbvszy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.andypj.xyz/Article/details/gtcqoppcte.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pycfn.com/Article/details/gtduqglnfv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hywenlv.cn/Article/details/gthhhjrxic.html

[N04] 斐波那契数列
来源：http://dali.cashguo.top/Article/details/gtszpzsvuy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hywenlv.cn/Article/details/gtsqmananj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gtyppoztsl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gthssrnzzh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gtwahjgetp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtgeocylnl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwzlzwha.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtqaftwvzl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gteigawdwg.html

[N05] 最大公约数
来源：http://dali.zycfv.cn/Article/details/gtyohvdbyn.html

Py:   math.gcd(a, b)
来源：http://dali.c1oappe.top/Article/details/gtlgcutmig.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gtyjdokybz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtlifoievl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gtjqbexjrj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhoulong.xyz/Article/details/gtmflykzgd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jianghu66.top/Article/details/gtcopxyowb.html

Ruby: a.gcd(b)
来源：http://dali.sweek.top/Article/details/gtvqmyqfgc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.aibaodan.cn/Article/details/gtinlwpzcr.html

[N06] 判断回文字符串
来源：http://dali.fengsongda.top/Article/details/gtlbrlnllj.html

Py:   s == s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gtbfdwszeq.html

PHP:  $s === strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gtbydqjtzf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtjllhbilz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtninbgbau.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xylfe.cn/Article/details/gtlqifckrw.html

Go:   // 双指针从两端比较
来源：http://dali.jqgfzy.top/Article/details/gtpqhnxefl.html

Ruby: s == s.reverse
来源：http://dali.zhengqikj.top/Article/details/gtrjmgdwip.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gtxazsayam.html

[N07] 两数之和（返回下标）
来源：http://dali.zycfv.cn/Article/details/gteqnbwpsf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fzhhl.top/Article/details/gtpuadhsmo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258888.top/Article/details/gthtbsfivj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yueranfly.top/Article/details/gtazfwlbnv.html

TS:   // 手写 Map<string, number>
来源：http://dali.shzxlz.cn/Article/details/gtyljvxzrv.html

Java: // 手写 HashMap
来源：http://dali.yueranfly.top/Article/details/gtpqvvgulb.html

Go:   // 手写 map[int]int
来源：http://dali.hywenlv.cn/Article/details/gtsenzhuzh.html

Ruby: // 手写 Hash
来源：http://dali.bjfxy.top/Article/details/gtlfzxorzb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhengqikj.top/Article/details/gtpqyglmqv.html

[N08] 生成全排列
来源：http://dali.hfpthk.cn/Article/details/gtxobsgxoo.html

Py:   itertools.permutations(arr)
来源：http://dali.redwolf501.top/Article/details/gtwizlpsnl.html

PHP:  // 手写递归交换
来源：http://dali.snrcjt.cn/Article/details/gtqnwzlddr.html

JS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtdaebviyb.html

TS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgzmspji.html

Java: // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtnoqptcui.html

Go:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gthnsooxqq.html

Ruby: arr.permutation.to_a
来源：http://dali.aibaodan.cn/Article/details/gtlmamccgp.html

C#:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtzxpzgokx.html

[N09] 栈与队列
来源：http://dali.nwbrower.top/Article/details/gtgsgezhui.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.c1oappe.top/Article/details/gtvzpwlhjr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtwcslmjnc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gtyllipira.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.iojbl.cn/Article/details/gtdrubsait.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cqqwz.cn/Article/details/gtqnaoishh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fzhhl.top/Article/details/gtkkiujarz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtqovowgga.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gtnospjgeo.html

[N10] 链表节点定义
来源：http://dali.hysaishi.cn/Article/details/gteeutstre.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daxiang520.top/Article/details/gtcgbndheh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tianlin.xyz/Article/details/gtwfiaedme.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cqqwz.cn/Article/details/gtsiuztavw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hysaishi.cn/Article/details/gtopxrllfw.html

Java: class Node { int v; Node next; }
来源：http://dali.pycfn.com/Article/details/gtmgrrfhwj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxrgejoc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmmjgmci.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuanzhike.top/Article/details/gtjbetvtmk.html

[N11] 二叉树中序遍历
来源：http://dali.cqqwz.cn/Article/details/gtfvhzxpai.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sweek.top/Article/details/gtoesxptfz.html

PHP:  // 手写递归函数
来源：http://dali.xziqi.cn/Article/details/gtzazheeym.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ppjwa.cn/Article/details/gtywnsjuem.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenzaomai.com/Article/details/gtxmgbnmpf.html

Java: // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtkvytdwoz.html

Go:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtkiwsnwbk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pengpengdd.cyou/Article/details/gtfshozryk.html

C#:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gtlvpbnuqn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgfzy.top/Article/details/gtuyynwztr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hywenlv.cn/Article/details/gtczbhayfx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenjidiqi.icu/Article/details/gthqzmsbex.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gtwrpxdhgp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gttmagswmf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gtlrzoscye.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zdqjudy.top/Article/details/gtoleanflc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenlongwang.top/Article/details/gtgiaabhpm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gtggkhhafa.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtnvkvrknj.html

O. 并发与异步
来源：http://dali.jqgufenzy.top/Article/details/gtvvvdbblq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxijudftg.html

[O01] 启动一个线程
来源：http://dali.zhiwuduotai.top/Article/details/gtxqowigcj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenlongwang.top/Article/details/gtuqzzbsga.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tanke756.top/Article/details/gtqvelznyq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ydzc1.top/Article/details/gtolaqtcvc.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gtmpcnmvmv.html

Java: new Thread(() -> f()).start()
来源：http://dali.kuanghao11.cn/Article/details/gtogqozspo.html

Go:   go f()
来源：http://dali.pengpengdd.cyou/Article/details/gtyykeyjsq.html

Ruby: Thread.new { f }
来源：http://dali.gotoacloud.top/Article/details/gtcsdnemqj.html

C#:   Task.Run(() => F());
来源：http://dali.chenjidiqi.icu/Article/details/gtwomluvmu.html

[O02] 使用线程池
来源：http://dali.zhoulong.xyz/Article/details/gtlhvygpzq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.bjfxy.top/Article/details/gtufjmvctz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cucudq.cn/Article/details/gtumndfjzq.html

JS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gtfahhasoo.html

TS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gthvmfkgve.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hysaishi.cn/Article/details/gtlmgcqlha.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnteryvb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.havefunace.top/Article/details/gtrbzvbsye.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sysykeji.top/Article/details/gtxndighzg.html

[O03] 加锁保护共享数据
来源：http://dali.ehwqpu.com/Article/details/gtfrnawgad.html

Py:   with lock: shared += 1
来源：http://dali.redwolf501.top/Article/details/gtzpwyucrk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuanzhike.top/Article/details/gtqhazvton.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yongpay.top/Article/details/gtkabeaxor.html

TS:   // 同 JS
来源：http://dali.yuanzhike.top/Article/details/gtluupnoti.html

Java: synchronized (this) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlejbykoi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj202588.top/Article/details/gtzpiwnjac.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.0kj1m.cn/Article/details/gtdmmouiit.html

C#:   lock (gate) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtnhklcsys.html

[O04] 定义异步函数并等待
来源：http://dali.tianlin.xyz/Article/details/gtdbsfbfqy.html

Py:   async def f():⏎    await g()
来源：http://dali.zdqjudy.top/Article/details/gtzbrjxdja.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yanxiufei.cn/Article/details/gtiglcbbrx.html

JS:   async function f() { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gtfwcpahcd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.birdmap.top/Article/details/gtubhlwtud.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cqqwz.cn/Article/details/gtmykiruyh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jianghu66.top/Article/details/gtxvgbcupl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nanxuanxn.top/Article/details/gttlhrqgcs.html

C#:   async Task F() { await G(); }
来源：http://dali.zycfv.cn/Article/details/gtkkqmztib.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuxming.cn/Article/details/gtuqvnenwr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cashguo.top/Article/details/gtojgdrgel.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.snrcjt.cn/Article/details/gtraqpsdhw.html

JS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gtskolngko.html

TS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gtyucmqucs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.haohaochexian.top/Article/details/gtnetarucs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cucudq.cn/Article/details/gthlzeklwz.html

Ruby: threads.map(&:join)
来源：http://dali.hfpthk.cn/Article/details/gtwtebrefy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sxryk.cn/Article/details/gtfnduecmz.html

[O06] 使用进程池
来源：http://dali.nwbrower.top/Article/details/gtatapbpqi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xziqi.cn/Article/details/gtvovnvsjr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yanxiufei.cn/Article/details/gtalqsodcg.html

JS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gtwboxgjtw.html

TS:   // child_process / cluster 模块
来源：http://dali.aibaodan.cn/Article/details/gtwzygkezf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sxryk.cn/Article/details/gtiaguqggu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangshuangyany.cn/Article/details/gtjsfkryuf.html

Ruby: // fork 块
来源：http://dali.sufxvd.cn/Article/details/gtixzkymdm.html

C#:   Parallel.For
来源：http://dali.kuanghao11.cn/Article/details/gtvhhizrds.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtdugjulmx.html

P. 常用工具函数
来源：http://dali.zycfv.cn/Article/details/gtwncpqgzb.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtzwpuvawb.html

[P01] 生成 UUID
来源：http://dali.ydzc1.top/Article/details/gtuyyecpmn.html

Py:   str(uuid.uuid4())
来源：http://dali.xylfe.cn/Article/details/gtknqurnit.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gtkafwrlll.html

JS:   crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gtvooydkyq.html

TS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gttvgxxgvz.html

Java: UUID.randomUUID().toString()
来源：http://dali.iojbl.cn/Article/details/gtixqhbtcq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigufen.top/Article/details/gtcjbkoktp.html

Ruby: SecureRandom.uuid
来源：http://dali.ppjwa.cn/Article/details/gtifnvttle.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.svipenyu.cn/Article/details/gtzbthrbwn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangshuangyany.cn/Article/details/gtrhvaxbql.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258.top/Article/details/gtnpczpphj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnxiangtu.top/Article/details/gtdyaiqsxu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.0kj1m.cn/Article/details/gtrsahfpry.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.mhx1999.top/Article/details/gtvrfdbdqz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yueranfly.top/Article/details/gtageyiepq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.mhx1999.top/Article/details/gtbieyxbcq.html


<!-- 参考信息 -->