代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gtapqqvwzu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gthhhgeemi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndacqgsf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fengsongda.top/Article/details/gtvxncabts.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zycfv.cn/Article/details/gtjljpmpbx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jianghu66.top/Article/details/gtxfojdzbd.html

[L05] 上传文件（multipart）
来源：http://dali.yuxming.cn/Article/details/gtzbpewtyz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.c1oappe.top/Article/details/gtjvwrhszl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aibaodan.cn/Article/details/gtxusoiaer.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gthdvumyso.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shuidangran.top/Article/details/gtabvpvhgq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dashuyun.cn/Article/details/gtskzsucud.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zycfv.cn/Article/details/gtwtgxkiis.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yvedp.cn/Article/details/gtrbtgxscq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtdbapdvgq.html

[L06] 解析响应为 JSON
来源：http://dali.zycfv.cn/Article/details/gtexakqypr.html

Py:   resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gtfvrzgswi.html

PHP:  json_decode($body, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsnmpiep.html

JS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gtlyndgdud.html

TS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gtrehosqgp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.iojbl.cn/Article/details/gtqzcllfge.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgvvlnjb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuxming.cn/Article/details/gtrmbtsykv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.quarkkingdee.top/Article/details/gtylralcjz.html

[L07] 处理 HTTP 状态码
来源：http://dali.0kj1m.cn/Article/details/gtctsmvtdj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.quarkkingdee.top/Article/details/gtpfyafomz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yvedp.cn/Article/details/gtesjohnby.html

JS:   resp.ok;  resp.status
来源：http://dali.sufxvd.cn/Article/details/gtvbhtofug.html

TS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gtqoorhtqu.html

Java: resp.statusCode()
来源：http://dali.hfpthk.cn/Article/details/gtqxkftmjl.html

Go:   resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gteslkabgv.html

Ruby: resp.code.to_i
来源：http://dali.daria6918.cn/Article/details/gtlfiisauy.html

C#:   (int)resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfufmuyjg.html

[L08] 并发请求多个地址
来源：http://dali.yangfankeji.com/Article/details/gtpcelwkrk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jianghu66.top/Article/details/gtoaeljhsv.html

PHP:  curl_multi_init() 系列
来源：http://dali.xziqi.cn/Article/details/gtuhccswkt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gtldhqkhve.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtgkhxmfef.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zdqjudy.top/Article/details/gtcqicklfb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.havefunace.top/Article/details/gtqbptvsgr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinghuilouyu.cn/Article/details/gthfbypziq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cucudq.cn/Article/details/gtfxjhloja.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtlntljexy.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxuanxn.top/Article/details/gtxystckts.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtqbxbjqzx.html

[M01] 读取命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtnxuthx.html

Py:   sys.argv[1:]
来源：http://dali.snrcjt.cn/Article/details/gtgazpghjh.html

PHP:  $argv;  $argc;
来源：http://dali.feifeiyinyue.top/Article/details/gtisrjyqww.html

JS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gtzakvlezh.html

TS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gtlhriypwm.html

Java: args 数组（main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gtvquhlegt.html

Go:   os.Args[1:]
来源：http://dali.andypj.xyz/Article/details/gtaansbfwt.html

Ruby: ARGV
来源：http://dali.jinghuilouyu.cn/Article/details/gtafmvldis.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gtfadirsez.html

[M02] 读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gtkqpjusby.html

Py:   os.environ.get("HOME")
来源：http://dali.yj202588.top/Article/details/gtnymenvft.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtieiiuohl.html

JS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gtiysdswkn.html

TS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtumtfqaln.html

Java: System.getenv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtiyyouhrf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gthgdfyvgj.html

Ruby: ENV["HOME"]
来源：http://dali.chenlongwang.top/Article/details/gtwxgchnpi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtwelxhlbq.html

[M03] 执行外部命令
来源：http://dali.xziqi.cn/Article/details/gtyfjrtxew.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yonumen.top/Article/details/gtfdgejvvt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dashuyun.cn/Article/details/gtvlylxiay.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gtyufjsuxo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gtxlalqvmr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsuxdaaeq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.0kj1m.cn/Article/details/gtilauoexw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.haohaochexian.top/Article/details/gtgmwngapo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.smart0.xyz/Article/details/gtvzgdxnpx.html

[M04] 获取当前工作目录
来源：http://dali.chenzaomai.com/Article/details/gtygibkuyy.html

Py:   os.getcwd()
来源：http://dali.shzxlz.cn/Article/details/gtjdhcrenh.html

PHP:  getcwd();
来源：http://dali.wangdashe.top/Article/details/gtpeqilktw.html

JS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtrsrfhpij.html

TS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gteowtityi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tanke756.top/Article/details/gtrbreqgzo.html

Go:   os.Getwd()
来源：http://dali.0kj1m.cn/Article/details/gtjxyxqpsh.html

Ruby: Dir.pwd
来源：http://dali.zycfv.cn/Article/details/gtcjqatmnx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fzhhl.top/Article/details/gtlipsswxv.html

[M05] 设置退出码
来源：http://dali.zycfv.cn/Article/details/gtpwanihea.html

Py:   sys.exit(1)
来源：http://dali.havefunace.top/Article/details/gtqujvokxj.html

PHP:  exit(1);
来源：http://dali.wangshuangyany.cn/Article/details/gtxxzvxqtg.html

JS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtgjndqdsl.html

TS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtifibkxwd.html

Java: System.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtrqoqbtsq.html

Go:   os.Exit(1)
来源：http://dali.pycfn.com/Article/details/gtirgjsmpk.html

Ruby: exit 1
来源：http://dali.hywenlv.cn/Article/details/gtweedvmog.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.0kj1m.cn/Article/details/gtxajvqdsj.html

[M06] 向标准错误输出
来源：http://dali.jinqigfzy.top/Article/details/gtcaijnykc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.feifeiyinyue.top/Article/details/gtwonjlwiw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrascayef.html

JS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gtsroknmso.html

TS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtzvpiuesi.html

Java: System.err.println("err")
来源：http://dali.hfpthk.cn/Article/details/gtkdioojpe.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.havefunace.top/Article/details/gtlyvoarxd.html

Ruby: warn "err"
来源：http://dali.smart0.xyz/Article/details/gtpjakghui.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guowangkeji.top/Article/details/gthihqapfc.html

[M07] 判断是否为主入口
来源：http://dali.jinqigfzy.top/Article/details/gtrhaozqbf.html

Py:   if __name__ == "__main__":
来源：http://dali.andypj.xyz/Article/details/gtytqgdiez.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnxiangtu.top/Article/details/gtahmriain.html

JS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gtmodyjukl.html

TS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gttsuktrhk.html

Java: public static void main(String[] args)
来源：http://dali.nanxuanxn.top/Article/details/gtmipspfcb.html

Go:   func main()
来源：http://dali.shuidangran.top/Article/details/gtmdtacwog.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnqzz.top/Article/details/gtfyvskjko.html

C#:   static void Main(string[] args)
来源：http://dali.tian-w.cn/Article/details/gtpzetsomw.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfixgppxd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangshuangyany.cn/Article/details/gtoiundrmh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlruxzcgh.html

JS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gtdxmjowls.html

TS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtncamnmci.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yanxiufei.cn/Article/details/gthrniyhps.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gtbufoeibe.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.c1oappe.top/Article/details/gtiuacvznf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.snrcjt.cn/Article/details/gtcjqjsjtk.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gthobmkybq.html

N. 数据结构与算法
来源：http://dali.jiagoushi.top/Article/details/gtxspbcttr.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gthrbcdddv.html

[N01] 二分查找（有序数组）
来源：http://dali.zhengqikj.top/Article/details/gthbefzznz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gthfwpujum.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hfpthk.cn/Article/details/gthyrgzgwj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gtfrpphmms.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gtijkanckv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtpeqzsdea.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtqzjzubon.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guowangkeji.top/Article/details/gtyunvhttl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtzhobtewu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gzhubu.top/Article/details/gthggobzxk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gtlysyjcnc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenlongwang.top/Article/details/gtcfilxztc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gtmypgnkfg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gtgdsaxlmw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sysykeji.top/Article/details/gtkgdpgrew.html

Go:   slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtarpblnwb.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gtmvlaeefa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.haohaochexian.top/Article/details/gtupniqeoq.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gtnyvwfnvd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.9152youxi.cn/Article/details/gtnnwdlxxw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tianlin.xyz/Article/details/gtetzupntn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gtqymkhtbw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gtxloifiiv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jiagoushi.top/Article/details/gtzbhglvcy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dashuyun.cn/Article/details/gtpfbzfixa.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xinyue.icu/Article/details/gtitfbhfzh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ivvv.top/Article/details/gtvxdztufu.html

[N04] 斐波那契数列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkaeyheh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gtgmxxhspn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gtcszyikhk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtvnvpemte.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtefdyjlat.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsalzdjvc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258888.top/Article/details/gtfvapnpsf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gtrqikacaw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gtbsrndrzv.html

[N05] 最大公约数
来源：http://dali.daxiang520.top/Article/details/gtkemaxhbn.html

Py:   math.gcd(a, b)
来源：http://dali.smart0.xyz/Article/details/gthkcjxhfa.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fengsongda.top/Article/details/gtzlvcbbqo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gtotktqvzq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gtblhxgqwi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.birdmap.top/Article/details/gtmcqzjodl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.mhx1999.top/Article/details/gtraljslay.html

Ruby: a.gcd(b)
来源：http://dali.zhixingplan.top/Article/details/gtsnnouyhx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuxming.cn/Article/details/gthhejbmvx.html

[N06] 判断回文字符串
来源：http://dali.cqqwz.cn/Article/details/gtykvcgixl.html

Py:   s == s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gttoreoxcz.html

PHP:  $s === strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gtcicbfgnt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtymosybiy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtnpfadsks.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxinkj.top/Article/details/gtzvutncsw.html

Go:   // 双指针从两端比较
来源：http://dali.cdnleiting.top/Article/details/gtjmaelutq.html

Ruby: s == s.reverse
来源：http://dali.hnqzz.top/Article/details/gtjbrvejgt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gtljgnwwcj.html

[N07] 两数之和（返回下标）
来源：http://dali.jinqigfzy.top/Article/details/gteuszgqcb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258.top/Article/details/gtwassmpab.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnxiangtu.top/Article/details/gtuzhmgzvo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jlsjyb.cn/Article/details/gtxjjpwqyk.html

TS:   // 手写 Map<string, number>
来源：http://dali.xylfe.cn/Article/details/gtlhjbutge.html

Java: // 手写 HashMap
来源：http://dali.jlsjyb.cn/Article/details/gtpoyrxouq.html

Go:   // 手写 map[int]int
来源：http://dali.xylfe.cn/Article/details/gtcgxjnvmy.html

Ruby: // 手写 Hash
来源：http://dali.hongshengwenyu.top/Article/details/gtqqwdlszg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daxiang520.top/Article/details/gtlhqxjfsx.html

[N08] 生成全排列
来源：http://dali.cucudq.cn/Article/details/gtsjkkskdi.html

Py:   itertools.permutations(arr)
来源：http://dali.yvedp.cn/Article/details/gthbowrvlr.html

PHP:  // 手写递归交换
来源：http://dali.chenzaomai.com/Article/details/gtxzxzddow.html

JS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtldaphmmd.html

TS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtfukrnrqp.html

Java: // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtopdeknox.html

Go:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtahsgyeut.html

Ruby: arr.permutation.to_a
来源：http://dali.hysaishi.cn/Article/details/gtcmnvuwhr.html

C#:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtzqburjbw.html

[N09] 栈与队列
来源：http://dali.zdqjudy.top/Article/details/gtwmoilawk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.snrcjt.cn/Article/details/gtshlntxtq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtkxwzugab.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gtkzcxtgpk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258.top/Article/details/gtahsjpvna.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.havefunace.top/Article/details/gtokrdldrl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258888.top/Article/details/gtioitwgqt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gtaezzlnsl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangdashe.top/Article/details/gtexvxknro.html

[N10] 链表节点定义
来源：http://dali.hysaishi.cn/Article/details/gtygahcqlg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.aizwys.cn/Article/details/gtwqbzadju.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aizwys.cn/Article/details/gtbmbmgxsd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shzxlz.cn/Article/details/gtbpeoloba.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenlongwang.top/Article/details/gtbcmutrse.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdbgmitr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenlongwang.top/Article/details/gtqawtqiyi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.0kj1m.cn/Article/details/gtmdseopwj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuxming.cn/Article/details/gtfeeygmae.html

[N11] 二叉树中序遍历
来源：http://dali.gzhubu.top/Article/details/gtiiwtutjf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jqgufenzy.top/Article/details/gtgkjwgxoa.html

PHP:  // 手写递归函数
来源：http://dali.cashguo.top/Article/details/gtablupacm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gtmwexoinw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gtgcmfmvkw.html

Java: // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gtrvlzembv.html

Go:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gtbqcmyxxz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pycfn.com/Article/details/gtvaqufqpf.html

C#:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gttcrnersv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.smart0.xyz/Article/details/gtqqkeevph.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.andypj.xyz/Article/details/gtjwonkeaf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.svipenyu.cn/Article/details/gthwtnwaph.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.kuanghao11.cn/Article/details/gtbbunoxtz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gtvpbehman.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gtkwpicsgb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenzaomai.com/Article/details/gtgleukemu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxuanxn.top/Article/details/gtrrdpjrea.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gtyztsirvw.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtktyhiwuk.html

O. 并发与异步
来源：http://dali.fzhhl.top/Article/details/gtlsvdspne.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtrihhieku.html

[O01] 启动一个线程
来源：http://dali.meibo888.top/Article/details/gtimixmqhg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cdnleiting.top/Article/details/gtcelvbqet.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xuanzx.com/Article/details/gtrhuusyzm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nwbrower.top/Article/details/gtvdmzdfkh.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gtraqepnkz.html

Java: new Thread(() -> f()).start()
来源：http://dali.aizwys.cn/Article/details/gttpzvdrgj.html

Go:   go f()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdcpeoktm.html

Ruby: Thread.new { f }
来源：http://dali.hfpthk.cn/Article/details/gtwkaqpdwo.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigufen.top/Article/details/gtaezyoues.html

[O02] 使用线程池
来源：http://dali.hnqzz.top/Article/details/gtvhovigsk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shzxlz.cn/Article/details/gtzuwueacg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhiwuduotai.top/Article/details/gtqtitdadl.html

JS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gtdqvgwscn.html

TS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gtiuddofea.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzovsxwp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hongshengwenyu.top/Article/details/gtdphdwkyy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.svipenyu.cn/Article/details/gtqmnwfshi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shanyushiyangtech.top/Article/details/gtibvqmrqn.html

[O03] 加锁保护共享数据
来源：http://dali.0kj1m.cn/Article/details/gtmcfuzcnj.html

Py:   with lock: shared += 1
来源：http://dali.yj20258.top/Article/details/gtstfmlrwj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ybcxt.top/Article/details/gtdaynnvpt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fzhhl.top/Article/details/gtunbuxlmd.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gtolcuwlmf.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gtqbmxtecs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258.top/Article/details/gtwzsczulb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hammf.cn/Article/details/gtqycaqxvw.html

C#:   lock (gate) { shared++; }
来源：http://dali.sufxvd.cn/Article/details/gtmxfdcizl.html

[O04] 定义异步函数并等待
来源：http://dali.xuanzx.com/Article/details/gtzdfdbuxv.html

Py:   async def f():⏎    await g()
来源：http://dali.yanxiufei.cn/Article/details/gtrbiaygpc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.iojbl.cn/Article/details/gtjkkiypug.html

JS:   async function f() { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gtruuomdrd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cheryme.top/Article/details/gtveimsbtm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhengqikj.top/Article/details/gtdtdkgsmo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jlsjyb.cn/Article/details/gtdwgyiabx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hongshengwenyu.top/Article/details/gtdvnshnuy.html

C#:   async Task F() { await G(); }
来源：http://dali.snrcjt.cn/Article/details/gtopnojewy.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuanzx.com/Article/details/gtjecwvdqq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jlsjyb.cn/Article/details/gtxmngckft.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dashuyun.cn/Article/details/gtwfzgulrl.html

JS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gtxrrooysz.html

TS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gtnvkrkaof.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yongpay.top/Article/details/gtgljdmjde.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.vqdsnc.cn/Article/details/gtbvcvujyl.html

Ruby: threads.map(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gtokwbsxxk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tian-w.cn/Article/details/gtynsxuvei.html

[O06] 使用进程池
来源：http://dali.mhx1999.top/Article/details/gtovqkiukn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ppjwa.cn/Article/details/gtnebmghhi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jyoumei.cn/Article/details/gtaxzrrhnm.html

JS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gtbnxxcdyn.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258.top/Article/details/gthcierxub.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuanzhike.top/Article/details/gtrhtqeqex.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yanxiufei.cn/Article/details/gtfxgzeggh.html

Ruby: // fork 块
来源：http://dali.jqgfzy.top/Article/details/gtihtdcjry.html

C#:   Parallel.For
来源：http://dali.hnqzz.top/Article/details/gtjpngbjvk.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtvgyiagio.html

P. 常用工具函数
来源：http://dali.sufxvd.cn/Article/details/gtiefhqxdr.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitxhqzkh.html

[P01] 生成 UUID
来源：http://dali.daria6918.cn/Article/details/gtltxaaydu.html

Py:   str(uuid.uuid4())
来源：http://dali.xinyue.icu/Article/details/gtonjqrjha.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenzaomai.com/Article/details/gtcfrfxgvj.html

JS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gtlejcvqgy.html

TS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gtpjaqsmat.html

Java: UUID.randomUUID().toString()
来源：http://dali.jyoumei.cn/Article/details/gtgtvdxpim.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xinyue.icu/Article/details/gtfaydmqre.html

Ruby: SecureRandom.uuid
来源：http://dali.zhengqikj.top/Article/details/gtgdcjrqlx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guannengcc.top/Article/details/gtkrfhvfye.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sxryk.cn/Article/details/gtodwdfoas.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daria6918.cn/Article/details/gtumybemvu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnqilxnz.html


<!-- 参考信息 -->