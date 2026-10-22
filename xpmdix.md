代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gtwiqtcvqd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gthaaerhne.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnxiangtu.top/Article/details/gtltzcyysd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gtrauwowok.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.svipenyu.cn/Article/details/gtpsyuauru.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxuanxn.top/Article/details/gtunhzngub.html

[L05] 上传文件（multipart）
来源：http://dali.sufxvd.cn/Article/details/gtzsdbszkq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sweek.top/Article/details/gtfaxccxje.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.c1oappe.top/Article/details/gtuienbsua.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gtotejuxiw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gtygrmxfyk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ivvv.top/Article/details/gtjclayijb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pycfn.com/Article/details/gtekggioxo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daxiang520.top/Article/details/gtntejylmu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.redwolf501.top/Article/details/gtwsitngau.html

[L06] 解析响应为 JSON
来源：http://dali.chenzaomai.com/Article/details/gtawnzcxen.html

Py:   resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtuztiuwgm.html

PHP:  json_decode($body, true);
来源：http://dali.ppjwa.cn/Article/details/gtciiapxhs.html

JS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gtiwpigvxr.html

TS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gtzfocratw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tanke756.top/Article/details/gtoaqscakn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtinaqblyh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenjidiqi.icu/Article/details/gtnnoorqfv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhongyouzk.top/Article/details/gtqxwygaaw.html

[L07] 处理 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gtdtoaercb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.havefunace.top/Article/details/gtxvdpuvox.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tanke756.top/Article/details/gthgrfvelt.html

JS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gtwfrgpwjs.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtqkmwkpph.html

Java: resp.statusCode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdaprntyp.html

Go:   resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtditalnwl.html

Ruby: resp.code.to_i
来源：http://dali.feifeiyinyue.top/Article/details/gtlchcviyq.html

C#:   (int)resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gtpluowopd.html

[L08] 并发请求多个地址
来源：http://dali.xuanzx.com/Article/details/gtckrlspgz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tanke756.top/Article/details/gtaqqxwuxj.html

PHP:  curl_multi_init() 系列
来源：http://dali.mhx1999.top/Article/details/gtxeonecbj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtammhwzkc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtflnxruql.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.havefunace.top/Article/details/gtwcalpnas.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xinyue.icu/Article/details/gtjsjedaot.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxinkj.top/Article/details/gtceozgbyl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zycfv.cn/Article/details/gtrvjxxocf.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtifdjjaum.html

M. 命令行 / 进程 / 环境
来源：http://dali.yongpay.top/Article/details/gtzruavoqp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtxadfljep.html

[M01] 读取命令行参数
来源：http://dali.hywenlv.cn/Article/details/gtehgujwjp.html

Py:   sys.argv[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtpijziljg.html

PHP:  $argv;  $argc;
来源：http://dali.gaohongyu789.top/Article/details/gtobsdcwvd.html

JS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtkwyggauz.html

TS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gtyfmupicu.html

Java: args 数组（main 方法参数）
来源：http://dali.yongpay.top/Article/details/gtouejyhnb.html

Go:   os.Args[1:]
来源：http://dali.jiagoushi.top/Article/details/gtbmlelgiy.html

Ruby: ARGV
来源：http://dali.kuanghao11.cn/Article/details/gtqxheyfyw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hammf.cn/Article/details/gtvskfnpfo.html

[M02] 读取环境变量
来源：http://dali.xuanzx.com/Article/details/gtkhxukyft.html

Py:   os.environ.get("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnscexgzq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gtcuvaainu.html

JS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gtxhcrxpxx.html

TS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gtwkqjxexk.html

Java: System.getenv("HOME")
来源：http://dali.xuanzx.com/Article/details/gtfwudlwiu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fzhhl.top/Article/details/gtiurpbbcb.html

Ruby: ENV["HOME"]
来源：http://dali.jianghu66.top/Article/details/gtvysfmhiv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sxryk.cn/Article/details/gtwalrghnx.html

[M03] 执行外部命令
来源：http://dali.meibo888.top/Article/details/gtrjzuxvas.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgufenzy.top/Article/details/gtqsyxysgz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ydzc1.top/Article/details/gttmvwnlkm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gtlrzzfwwn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sufxvd.cn/Article/details/gtnsbavlfh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.meibo888.top/Article/details/gtlacweqib.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgufenzy.top/Article/details/gtjrzjxujb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yueranfly.top/Article/details/gtayqkvjfk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yueranfly.top/Article/details/gtkvowibiz.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gtroegivqm.html

Py:   os.getcwd()
来源：http://dali.zdqjudy.top/Article/details/gtzjypwzpj.html

PHP:  getcwd();
来源：http://dali.xziqi.cn/Article/details/gthcxihwib.html

JS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gtpbyuiebj.html

TS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gtjsnbsjqb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pycfn.com/Article/details/gtqavxamzr.html

Go:   os.Getwd()
来源：http://dali.xylfe.cn/Article/details/gtcwvwhtsy.html

Ruby: Dir.pwd
来源：http://dali.chenjidiqi.icu/Article/details/gtjqpxkvsj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gogol.net.cn/Article/details/gtjsvtkgnb.html

[M05] 设置退出码
来源：http://dali.pycfn.com/Article/details/gtrtraolbm.html

Py:   sys.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtxjvrpxxa.html

PHP:  exit(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrbmejwo.html

JS:   process.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgbbvgrqs.html

TS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gtovdkyeyy.html

Java: System.exit(1)
来源：http://dali.yj20258.top/Article/details/gtctelcelg.html

Go:   os.Exit(1)
来源：http://dali.tian-w.cn/Article/details/gtwgvoccyw.html

Ruby: exit 1
来源：http://dali.yonumen.top/Article/details/gtbkgvftbo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gotoacloud.top/Article/details/gtabfvqhqm.html

[M06] 向标准错误输出
来源：http://dali.shuidangran.top/Article/details/gtuvwqisll.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gogol.net.cn/Article/details/gtabouyjwk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxuanxn.top/Article/details/gtthdsocvi.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtslsfuaxo.html

TS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gtaayhumde.html

Java: System.err.println("err")
来源：http://dali.jyoumei.cn/Article/details/gtistfzqsx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258.top/Article/details/gtsacpnzmg.html

Ruby: warn "err"
来源：http://dali.fengsongda.top/Article/details/gtesyjoobq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xziqi.cn/Article/details/gtffcbaaan.html

[M07] 判断是否为主入口
来源：http://dali.gotoacloud.top/Article/details/gtorojywmk.html

Py:   if __name__ == "__main__":
来源：http://dali.dianchejie.cn/Article/details/gtjujycezh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cucudq.cn/Article/details/gtpbpoxeve.html

JS:   require.main === module
来源：http://dali.sweek.top/Article/details/gtmndorfxo.html

TS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gtdurrnbku.html

Java: public static void main(String[] args)
来源：http://dali.andypj.xyz/Article/details/gtttmoqyst.html

Go:   func main()
来源：http://dali.yj202588.top/Article/details/gtwhpcmqwz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.smart0.xyz/Article/details/gtadhclvvo.html

C#:   static void Main(string[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuyhslfll.html

[M08] 获取系统与运行时信息
来源：http://dali.cashguo.top/Article/details/gtsdiaajce.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hysaishi.cn/Article/details/gtwzbqpsur.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigufen.top/Article/details/gtzunbjvnx.html

JS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gtfcgcrago.html

TS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gtdfnzxjyo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.kuanghao11.cn/Article/details/gtzzdgcuoi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sxryk.cn/Article/details/gtormwapka.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.feifeiyinyue.top/Article/details/gtxupckgpg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhengqikj.top/Article/details/gtfccplnem.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtijxmisrz.html

N. 数据结构与算法
来源：http://dali.hfpthk.cn/Article/details/gtubzcjinm.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtmincdiyh.html

[N01] 二分查找（有序数组）
来源：http://dali.jyoumei.cn/Article/details/gtkftwnkpy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtusablxgc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtwjdhwajz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gtpkminokb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gtfhrtxxbb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gthjqpivqs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtxrhcbamy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dianchejie.cn/Article/details/gtuisghaed.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gthrojqmch.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyauxfwcw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gtfzmztvvf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hammf.cn/Article/details/gtxsvlmthn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gtcrweikwa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtzqabwigw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnqzz.top/Article/details/gtnjqikfyf.html

Go:   slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gtxvvmetnj.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gtiyqgyiwx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gaohongyu789.top/Article/details/gtxfqqzurp.html

[N03] 快速排序（分治示例）
来源：http://dali.havefunace.top/Article/details/gtjnsbhqms.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ybcxt.top/Article/details/gtxcvdlsqj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cqqwz.cn/Article/details/gtzzjhnsqh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gtyitqiipr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gtzxaqjbzd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guowangkeji.top/Article/details/gtvbtsmbca.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ppjwa.cn/Article/details/gtgqaulept.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.meibo888.top/Article/details/gtuwjbvzig.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daxiang520.top/Article/details/gtvgxzeaoy.html

[N04] 斐波那契数列
来源：http://dali.yuanzhike.top/Article/details/gtmdjwertp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gtemfnxljx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gtekpfouqt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtkgwnbnyq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gtpsinomsi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gtvoyuuoxj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xziqi.cn/Article/details/gtjaxignyc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gturrrfsrd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gtclvjufed.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gtwuyrejxl.html

Py:   math.gcd(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtkwssdhdg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ppjwa.cn/Article/details/gtrzwdvslo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzshxcya.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gtotkibbxb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fengsongda.top/Article/details/gtybiofpgn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gaohongyu789.top/Article/details/gtnevzppai.html

Ruby: a.gcd(b)
来源：http://dali.c1oappe.top/Article/details/gtsucnanfe.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yangfankeji.com/Article/details/gtsvtloyjy.html

[N06] 判断回文字符串
来源：http://dali.sxryk.cn/Article/details/gteltdizrg.html

Py:   s == s[::-1]
来源：http://dali.gzhubu.top/Article/details/gtmscyyldh.html

PHP:  $s === strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gtwdwlujdr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtaygwarjc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtxfucgjcl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shangyingyoupin.top/Article/details/gtihnowguc.html

Go:   // 双指针从两端比较
来源：http://dali.xziqi.cn/Article/details/gttqvoigyc.html

Ruby: s == s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtjattvinz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gtsouoyvkm.html

[N07] 两数之和（返回下标）
来源：http://dali.xuetiantiany.cn/Article/details/gtmnuyeqye.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.kuanghao11.cn/Article/details/gtvgxchiyr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guowangkeji.top/Article/details/gtkjfihdzh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daxiang520.top/Article/details/gtktydxmkn.html

TS:   // 手写 Map<string, number>
来源：http://dali.cashguo.top/Article/details/gtgwljnpwh.html

Java: // 手写 HashMap
来源：http://dali.smart0.xyz/Article/details/gtxjpirruv.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigufen.top/Article/details/gtvljwdhvp.html

Ruby: // 手写 Hash
来源：http://dali.9152youxi.cn/Article/details/gtmjhihfhy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.wangshuangyany.cn/Article/details/gtvupzahwh.html

[N08] 生成全排列
来源：http://dali.zhengqikj.top/Article/details/gtoevncqzr.html

Py:   itertools.permutations(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtxnngihup.html

PHP:  // 手写递归交换
来源：http://dali.ehwqpu.com/Article/details/gtcxxmttoa.html

JS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzmgbtvq.html

TS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtokbhrdmf.html

Java: // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtidworpgy.html

Go:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtuyfzkugw.html

Ruby: arr.permutation.to_a
来源：http://dali.yuanzhike.top/Article/details/gtvabaufem.html

C#:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtqjxwfxzo.html

[N09] 栈与队列
来源：http://dali.iojbl.cn/Article/details/gtwjtxpeku.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aizwys.cn/Article/details/gtacserrwy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtfwvujylp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtjwbswtst.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaokmtyby.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hywenlv.cn/Article/details/gttuvtqpmd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxinkj.top/Article/details/gtcpwugkvj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gtvbonfwnr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.mhx1999.top/Article/details/gteposxjif.html

[N10] 链表节点定义
来源：http://dali.ehwqpu.com/Article/details/gtmbtwriek.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dashuyun.cn/Article/details/gtylkznuhz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.wangdashe.top/Article/details/gtaylekcvo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgufenzy.top/Article/details/gtyhkpyitv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tianlin.xyz/Article/details/gtduljqeie.html

Java: class Node { int v; Node next; }
来源：http://dali.yongpay.top/Article/details/gtrdytipae.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtauptnqjj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.bjfxy.top/Article/details/gthkmmgdei.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aizwys.cn/Article/details/gtkceugeie.html

[N11] 二叉树中序遍历
来源：http://dali.jyoumei.cn/Article/details/gtbmgbcrma.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj202588.top/Article/details/gtclrhajom.html

PHP:  // 手写递归函数
来源：http://dali.zhixingplan.top/Article/details/gtugconbiy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gtvnlhkedw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gtidbyfntd.html

Java: // 手写递归
来源：http://dali.birdmap.top/Article/details/gtsdejfptm.html

Go:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtgicdfbnv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tanke756.top/Article/details/gtvwffquln.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gtzwzqwlbd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.iojbl.cn/Article/details/gtlpjfwtme.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.andypj.xyz/Article/details/gtthtacbmu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yvedp.cn/Article/details/gtrqgcuugu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gtdimlpgkc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gtdmegmvkz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gtfwltazis.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigufen.top/Article/details/gtmpihbvcb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteniosnsd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gtispdvwlm.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gthhlwkwhy.html

O. 并发与异步
来源：http://dali.yonumen.top/Article/details/gtoruhzevq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtgfgknfdx.html

[O01] 启动一个线程
来源：http://dali.jinqigfzy.top/Article/details/gtuecpvmyg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.birdmap.top/Article/details/gtfouceqfw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cdnleiting.top/Article/details/gttfvphqig.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxinkj.top/Article/details/gtlkfqtijg.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gtptjqjdcg.html

Java: new Thread(() -> f()).start()
来源：http://dali.daxiang520.top/Article/details/gtrjmnovuw.html

Go:   go f()
来源：http://dali.hfpthk.cn/Article/details/gtczmrxbly.html

Ruby: Thread.new { f }
来源：http://dali.aibaodan.cn/Article/details/gtlarkvtqr.html

C#:   Task.Run(() => F());
来源：http://dali.gaohongyu789.top/Article/details/gtfqurxhgv.html

[O02] 使用线程池
来源：http://dali.redwolf501.top/Article/details/gtfnyfxeys.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hfpthk.cn/Article/details/gtouohjaul.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dashuyun.cn/Article/details/gtgwkcelus.html

JS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gttjhtijtq.html

TS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gtflemkxhc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgfzy.top/Article/details/gtknmgkwtl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.feifeiyinyue.top/Article/details/gtaiwdqxjk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinqigfzy.top/Article/details/gtaixvmjxy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.vqdsnc.cn/Article/details/gtofrrdafh.html

[O03] 加锁保护共享数据
来源：http://dali.zhiwuduotai.top/Article/details/gtkaepzvdy.html

Py:   with lock: shared += 1
来源：http://dali.jiagoushi.top/Article/details/gtyixtjmsz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ehwqpu.com/Article/details/gtdqtchzzu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuetiantiany.cn/Article/details/gtgzyduzbn.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtjfvmwotf.html

Java: synchronized (this) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gtycrjsvrn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxinkj.top/Article/details/gtfjptfltl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yonumen.top/Article/details/gtrcupafoe.html

C#:   lock (gate) { shared++; }
来源：http://dali.hywenlv.cn/Article/details/gtxvktywvp.html

[O04] 定义异步函数并等待
来源：http://dali.daria6918.cn/Article/details/gtzqprguhb.html

Py:   async def f():⏎    await g()
来源：http://dali.xuanzx.com/Article/details/gtzjtbxsfg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxinkj.top/Article/details/gtiudqniou.html

JS:   async function f() { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gturbrfhun.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gtogygyjef.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuxming.cn/Article/details/gtljcyyxbe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jianghu66.top/Article/details/gtiwkrbkex.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.kuanghao11.cn/Article/details/gtcifhitmt.html

C#:   async Task F() { await G(); }
来源：http://dali.svipenyu.cn/Article/details/gtasdhzexn.html

[O05] 并发执行并等待全部完成
来源：http://dali.shuidangran.top/Article/details/gthjewwobq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.aibaodan.cn/Article/details/gtqsyaorpj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jiagoushi.top/Article/details/gtzwslwftj.html

JS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gtseoinovv.html

TS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gtbzcnlqnj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhixingplan.top/Article/details/gtdlcsbrky.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgvhztkz.html

Ruby: threads.map(&:join)
来源：http://dali.chenzaomai.com/Article/details/gtypjgxldf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hongshengwenyu.top/Article/details/gthgyocaxz.html

[O06] 使用进程池
来源：http://dali.chenlongwang.top/Article/details/gttvibucqw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shanyushiyangtech.top/Article/details/gtheesbmnk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ehwqpu.com/Article/details/gtsaqwzrab.html

JS:   // child_process / cluster 模块
来源：http://dali.vqdsnc.cn/Article/details/gtnriycaff.html

TS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuesstaxz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.snrcjt.cn/Article/details/gtsaodtolz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gogol.net.cn/Article/details/gtgszqwrrj.html

Ruby: // fork 块
来源：http://dali.hnxiangtu.top/Article/details/gtltauiaey.html

C#:   Parallel.For
来源：http://dali.yueranfly.top/Article/details/gtmjpcwnww.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtdwaicluu.html

P. 常用工具函数
来源：http://dali.hywenlv.cn/Article/details/gtawjrasuk.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtsyvtatzj.html

[P01] 生成 UUID
来源：http://dali.zhiwuduotai.top/Article/details/gtxrmuircb.html

Py:   str(uuid.uuid4())
来源：http://dali.yj202588.top/Article/details/gtyscqaovb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yanxiufei.cn/Article/details/gtbudtshxf.html

JS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtzhsdzgoq.html

TS:   crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gtduiaejlr.html

Java: UUID.randomUUID().toString()
来源：http://dali.vqdsnc.cn/Article/details/gtxqolbihd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.smart0.xyz/Article/details/gtjndipvcd.html

Ruby: SecureRandom.uuid
来源：http://dali.yuxming.cn/Article/details/gthdeavrcl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangshuangyany.cn/Article/details/gtecdlrlig.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sxryk.cn/Article/details/gtbspulfdt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yanxiufei.cn/Article/details/gtvnkagiql.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhoulong.xyz/Article/details/gtrbthrkvi.html


<!-- 参考信息 -->