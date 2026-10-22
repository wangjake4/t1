代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gt2hccgkaqq.html

[L04] 设置超时
来源：http://dali.tanke756.top/Article/details/gt2sbrohmtu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258888.top/Article/details/gt2berhbsfa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhoulong.xyz/Article/details/gt2gaawswvl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zycfv.cn/Article/details/gt2pqdlilbf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gt2tupzvdha.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.snrcjt.cn/Article/details/gt2sqcoiwxg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gotoacloud.top/Article/details/gt2grrrqpjf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.smart0.xyz/Article/details/gt2ieozwwic.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ehwqpu.com/Article/details/gt2byjdyqjf.html

[L05] 上传文件（multipart）
来源：http://dali.zhixingplan.top/Article/details/gt2xlovsgmd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gotoacloud.top/Article/details/gt2qbyssfwq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xziqi.cn/Article/details/gt2hyilegzk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dqupvkxi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jcyitmmz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.feifeiyinyue.top/Article/details/gt2byyjbodb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gaohongyu789.top/Article/details/gt2mowonwtu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cashguo.top/Article/details/gt2xztpisaz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2zfmpdwti.html

[L06] 解析响应为 JSON
来源：http://dali.xylfe.cn/Article/details/gt2ojvzohhe.html

Py:   resp.json()
来源：http://dali.mhx1999.top/Article/details/gt2rwyggaxe.html

PHP:  json_decode($body, true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2scadlkik.html

JS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gt2ggszhspj.html

TS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gt2xwjizzek.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gt2dbdsxewh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenlongwang.top/Article/details/gt2swgajsmh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hbdexsdx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cashguo.top/Article/details/gt2limlfzds.html

[L07] 处理 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gt2lellemja.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cqqwz.cn/Article/details/gt2liwglfdo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ppjwa.cn/Article/details/gt2cwpoeaor.html

JS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gt2opbhwbzd.html

TS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gt2xqahxklq.html

Java: resp.statusCode()
来源：http://dali.mhx1999.top/Article/details/gt2kdzysixu.html

Go:   resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gt2zcujvwee.html

Ruby: resp.code.to_i
来源：http://dali.zhengqikj.top/Article/details/gt2ngohremq.html

C#:   (int)resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gt2dqivtmaw.html

[L08] 并发请求多个地址
来源：http://dali.chenjidiqi.icu/Article/details/gt2zxiodepu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.bjfxy.top/Article/details/gt2fdrjvbpo.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxuanxn.top/Article/details/gt2rowxzdxj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gt2jtyjtcuj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gt2lqkesrjn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxuanxn.top/Article/details/gt2hoygjeus.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhiwuduotai.top/Article/details/gt2gificemb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zdqjudy.top/Article/details/gt2vhdiuavb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hammf.cn/Article/details/gt2ogugyemc.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2epxctbkm.html

M. 命令行 / 进程 / 环境
来源：http://dali.snrcjt.cn/Article/details/gt2ozhtaftc.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2daqjjltt.html

[M01] 读取命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2afoclzha.html

Py:   sys.argv[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hbplllig.html

PHP:  $argv;  $argc;
来源：http://dali.hnqzz.top/Article/details/gt2vwuxdwqf.html

JS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gt2xqapwjga.html

TS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gt2drvodimu.html

Java: args 数组（main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gt2rrnxrbkh.html

Go:   os.Args[1:]
来源：http://dali.jqgufenzy.top/Article/details/gt2ndhgntsp.html

Ruby: ARGV
来源：http://dali.jinqigfzy.top/Article/details/gt2yubpedvy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gt2xjxbzcxv.html

[M02] 读取环境变量
来源：http://dali.dianchejie.cn/Article/details/gt2huengaax.html

Py:   os.environ.get("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gt2ngjzppnu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gt2jgyvxzbv.html

JS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gt2qsjrhdpv.html

TS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gt2ydjglgcs.html

Java: System.getenv("HOME")
来源：http://dali.yj20258888.top/Article/details/gt2oxnnzgdy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gt2tptexfbl.html

Ruby: ENV["HOME"]
来源：http://dali.yonumen.top/Article/details/gt2uwsbjqjn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daria6918.cn/Article/details/gt2hkqeqdjd.html

[M03] 执行外部命令
来源：http://dali.yj202588.top/Article/details/gt2edgouvxy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guowangkeji.top/Article/details/gt2buvinvkq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uyqgclnt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gt2olqwxffo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ufpppalc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sufxvd.cn/Article/details/gt2hqrjxlnh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gogol.net.cn/Article/details/gt2wxsyaomc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dashuyun.cn/Article/details/gt2lcyqkvca.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jyoumei.cn/Article/details/gt2qkxajuwj.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gt2lodlfdms.html

Py:   os.getcwd()
来源：http://dali.dianchejie.cn/Article/details/gt2mkunjliw.html

PHP:  getcwd();
来源：http://dali.zhixingplan.top/Article/details/gt2vpifkbrz.html

JS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gt2slszyqrl.html

TS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gt2xmjblank.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.fengsongda.top/Article/details/gt2itjbovgu.html

Go:   os.Getwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2obmqaehg.html

Ruby: Dir.pwd
来源：http://dali.cucudq.cn/Article/details/gt2tgtxyrip.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuetiantiany.cn/Article/details/gt2iejungef.html

[M05] 设置退出码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mlphktcj.html

Py:   sys.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gt2ivcfwmlw.html

PHP:  exit(1);
来源：http://dali.cqqwz.cn/Article/details/gt2hapwlfkm.html

JS:   process.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2fvqxluxa.html

TS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2ouagdnjp.html

Java: System.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2azmmafts.html

Go:   os.Exit(1)
来源：http://dali.ivvv.top/Article/details/gt2ysjrnyof.html

Ruby: exit 1
来源：http://dali.chenzaomai.com/Article/details/gt2rdbwsssf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2spmajhrg.html

[M06] 向标准错误输出
来源：http://dali.svipenyu.cn/Article/details/gt2qsqywvma.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gt2pguwovps.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258888.top/Article/details/gt2oamohuod.html

JS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gt2qdnzymic.html

TS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gt2tolsitmo.html

Java: System.err.println("err")
来源：http://dali.tianlin.xyz/Article/details/gt2cgfoinjx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mkkvboru.html

Ruby: warn "err"
来源：http://dali.daxiang520.top/Article/details/gt2vndxwcxz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuxming.cn/Article/details/gt2khbgbjmt.html

[M07] 判断是否为主入口
来源：http://dali.tian-w.cn/Article/details/gt2edgfqapd.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigfzy.top/Article/details/gt2rqrnarpp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gt2wvkhlqva.html

JS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gt2bzvikrpq.html

TS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gt2vtuefxrg.html

Java: public static void main(String[] args)
来源：http://dali.svipenyu.cn/Article/details/gt2xmidmhfp.html

Go:   func main()
来源：http://dali.yj20258.top/Article/details/gt2ucuppwvu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fxhmepij.html

C#:   static void Main(string[] args)
来源：http://dali.fzhhl.top/Article/details/gt2tjuwpfnc.html

[M08] 获取系统与运行时信息
来源：http://dali.cdnleiting.top/Article/details/gt2emtbdrkf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sxryk.cn/Article/details/gt2iytjfjox.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hongshengwenyu.top/Article/details/gt2yxlkqndp.html

JS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gt2hksesixn.html

TS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gt2qocurjfj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhixingplan.top/Article/details/gt2hkswrapq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gt2bmpgomgl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258888.top/Article/details/gt2kkpuqadt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ldbczzcc.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2jhpjoiwj.html

N. 数据结构与算法
来源：http://dali.daria6918.cn/Article/details/gt2uhjvsqpj.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2qlylobir.html

[N01] 二分查找（有序数组）
来源：http://dali.sxryk.cn/Article/details/gt2ljhctugd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2mjhcecmq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenlongwang.top/Article/details/gt2padvlolj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gt2bmtbqaex.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gt2ezbmjkzc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2mdhfrzmu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2wqdybwke.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ivvv.top/Article/details/gt2tacjyfuc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2krbnsigf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dianchejie.cn/Article/details/gt2masvaxtl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gt2joosssow.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xinyue.icu/Article/details/gt2cbonvtir.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gt2wmaxfrxi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gt2kvskxysb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wrytpmha.html

Go:   slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gt2ulemgtnr.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gt2xdrvsrws.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuanzhike.top/Article/details/gt2csltcsez.html

[N03] 快速排序（分治示例）
来源：http://dali.ehwqpu.com/Article/details/gt2jayctnnq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cdnleiting.top/Article/details/gt2omsflwbf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.snrcjt.cn/Article/details/gt2dnplyxni.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gt2jaymzkax.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gt2zqcybafh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jianghu66.top/Article/details/gt2gahphzjr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jlsjyb.cn/Article/details/gt2xoihvfhi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258.top/Article/details/gt2cpughoob.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aibaodan.cn/Article/details/gt2jehskfcr.html

[N04] 斐波那契数列
来源：http://dali.hnqzz.top/Article/details/gt2lplhsvqo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cucudq.cn/Article/details/gt2sbiwrzar.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gt2bkwralru.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gt2ednoqtpg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gt2fobxgqdw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangdashe.top/Article/details/gt2wpfqglcn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dashuyun.cn/Article/details/gt2xbmdserj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gt2rlqhbllu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxmmpss.html

[N05] 最大公约数
来源：http://dali.sufxvd.cn/Article/details/gt2aqtufzde.html

Py:   math.gcd(a, b)
来源：http://dali.jqgfzy.top/Article/details/gt2uzvoaero.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2lgkisghl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gt2pgpuqvlt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gt2drelojxd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.vqdsnc.cn/Article/details/gt2ixctldna.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yueranfly.top/Article/details/gt2fdjhtadm.html

Ruby: a.gcd(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yrworasd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rqsaurmb.html

[N06] 判断回文字符串
来源：http://dali.hywenlv.cn/Article/details/gt2ikccigpj.html

Py:   s == s[::-1]
来源：http://dali.shuidangran.top/Article/details/gt2tkvhzano.html

PHP:  $s === strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2rudmvjym.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gt2lithcump.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gt2uierfdds.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kclsxqcn.html

Go:   // 双指针从两端比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2hogpgjff.html

Ruby: s == s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gt2kktftuko.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gt2zfjpdukk.html

[N07] 两数之和（返回下标）
来源：http://dali.bjfxy.top/Article/details/gt2ngcpunxe.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aizwys.cn/Article/details/gt2sunjcpxi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gogol.net.cn/Article/details/gt2cipewpqt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cashguo.top/Article/details/gt2tvzqhrpu.html

TS:   // 手写 Map<string, number>
来源：http://dali.redwolf501.top/Article/details/gt2klfrkedi.html

Java: // 手写 HashMap
来源：http://dali.yj202588.top/Article/details/gt2scfbxhec.html

Go:   // 手写 map[int]int
来源：http://dali.zhixingplan.top/Article/details/gt2ibsbbwuk.html

Ruby: // 手写 Hash
来源：http://dali.yuxming.cn/Article/details/gt2xfhfubhu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yanxiufei.cn/Article/details/gt2uezdvgkn.html

[N08] 生成全排列
来源：http://dali.nwbrower.top/Article/details/gt2uedznraw.html

Py:   itertools.permutations(arr)
来源：http://dali.316326.xyz/Article/details/gt2aovsriri.html

PHP:  // 手写递归交换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cjjfprji.html

JS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2gkswkqrs.html

TS:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gt2pbjnrnqz.html

Java: // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gt2yziistwi.html

Go:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gt2zjncboyb.html

Ruby: arr.permutation.to_a
来源：http://dali.tianlin.xyz/Article/details/gt2epgyzhka.html

C#:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2zsnakanb.html

[N09] 栈与队列
来源：http://dali.snrcjt.cn/Article/details/gt2vmgfloev.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cqqwz.cn/Article/details/gt2snltvdow.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jianghu66.top/Article/details/gt2qiedxhdx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fjeseiwy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sxryk.cn/Article/details/gt2sgimwrqg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tanke756.top/Article/details/gt2jcoczwqv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hfpthk.cn/Article/details/gt2rdcudgem.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kewjsetv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.aizwys.cn/Article/details/gt2rnyxyfza.html

[N10] 链表节点定义
来源：http://dali.pycfn.com/Article/details/gt2fnarphvi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.mhx1999.top/Article/details/gt2yxvziawj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shzxlz.cn/Article/details/gt2qtkpwiff.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgufenzy.top/Article/details/gt2nqobjkyy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yangfankeji.com/Article/details/gt2zxnrhpvv.html

Java: class Node { int v; Node next; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2juwoohpf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sxryk.cn/Article/details/gt2xaoxynwn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhengqikj.top/Article/details/gt2tjnrnrdf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yvedp.cn/Article/details/gt2muqemkhn.html

[N11] 二叉树中序遍历
来源：http://dali.316326.xyz/Article/details/gt2ksjvpqsu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj202588.top/Article/details/gt2qlurpbwj.html

PHP:  // 手写递归函数
来源：http://dali.yanxiufei.cn/Article/details/gt2fbpvkkcf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gt2ysxwavyc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gt2xrcisslf.html

Java: // 手写递归
来源：http://dali.yueranfly.top/Article/details/gt2eaxpgteb.html

Go:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gt2qgecaatx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guowangkeji.top/Article/details/gt2pwdmxyca.html

C#:   // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gt2elxktagf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hysaishi.cn/Article/details/gt2ofgpbqya.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jlsjyb.cn/Article/details/gt2ijptwjma.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.kuanghao11.cn/Article/details/gt2tveyrzxb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gt2ywqebaor.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gt2obxeiwvb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gt2hwgxuptp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xziqi.cn/Article/details/gt2lfjexkea.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258888.top/Article/details/gt2xwomwkap.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gt2aahibgze.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2iwqrxltz.html

O. 并发与异步
来源：http://dali.snrcjt.cn/Article/details/gt2obyzhtci.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2piikxkdy.html

[O01] 启动一个线程
来源：http://dali.shangyingyoupin.top/Article/details/gt2cbrjwbdr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.iojbl.cn/Article/details/gt2fqechcsl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangdashe.top/Article/details/gt2eoepegsa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hfpthk.cn/Article/details/gt2hzhefapq.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gt2bjuqikdw.html

Java: new Thread(() -> f()).start()
来源：http://dali.shzxlz.cn/Article/details/gt2btoeqgkc.html

Go:   go f()
来源：http://dali.zhongyouzk.top/Article/details/gt2qnvtxisb.html

Ruby: Thread.new { f }
来源：http://dali.ydzc1.top/Article/details/gt2ihtnzjur.html

C#:   Task.Run(() => F());
来源：http://dali.sweek.top/Article/details/gt2ksevdrkm.html

[O02] 使用线程池
来源：http://dali.meibo888.top/Article/details/gt2kmfbgquq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xziqi.cn/Article/details/gt2dsdlsmnx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgufenzy.top/Article/details/gt2kwdtbmuc.html

JS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gt2lrdxspgt.html

TS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zbtcakmt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yuanzhike.top/Article/details/gt2rruwnxwi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jianghu66.top/Article/details/gt2fvwlbbbm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.iojbl.cn/Article/details/gt2kzjmdtoq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.smart0.xyz/Article/details/gt2bfbumlpp.html

[O03] 加锁保护共享数据
来源：http://dali.ivvv.top/Article/details/gt2pbqnwzrw.html

Py:   with lock: shared += 1
来源：http://dali.chenlongwang.top/Article/details/gt2dwbhbbca.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258888.top/Article/details/gt2ebxuzlxo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnqzz.top/Article/details/gt2xlwmdlut.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gt2horllvrb.html

Java: synchronized (this) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gt2plzppvir.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.kuanghao11.cn/Article/details/gt2jhnmview.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.meibo888.top/Article/details/gt2qqfdxldb.html

C#:   lock (gate) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gt2zopjvlug.html

[O04] 定义异步函数并等待
来源：http://dali.yuxming.cn/Article/details/gt2dhqxbgqd.html

Py:   async def f():⏎    await g()
来源：http://dali.fengsongda.top/Article/details/gt2kfgslnth.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cucudq.cn/Article/details/gt2dmbdoqpp.html

JS:   async function f() { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ljxikspv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.daria6918.cn/Article/details/gt2pofcrkgj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gzhubu.top/Article/details/gt2ypacgtzo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuanzx.com/Article/details/gt2ljejnffy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhoulong.xyz/Article/details/gt2hexnvxzj.html

C#:   async Task F() { await G(); }
来源：http://dali.hywenlv.cn/Article/details/gt2xgjvvttu.html

[O05] 并发执行并等待全部完成
来源：http://dali.mhx1999.top/Article/details/gt2itraakzb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cmdgngjk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hammf.cn/Article/details/gt2lyufjras.html

JS:   await Promise.all(tasks)
来源：http://dali.sweek.top/Article/details/gt2udhknfly.html

TS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gt2xeilakwj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gogol.net.cn/Article/details/gt2tfncdimv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nanxuanxn.top/Article/details/gt2cdkytlwp.html

Ruby: threads.map(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gt2dwxpkyya.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yuanzhike.top/Article/details/gt2osvrrduh.html

[O06] 使用进程池
来源：http://dali.jianghu66.top/Article/details/gt2sulvnhti.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2aljyoovk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.vqdsnc.cn/Article/details/gt2tgdfzzbr.html

JS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gt2hutfntvj.html

TS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gt2qdwdzcfs.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xylfe.cn/Article/details/gt2shvyaqtg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.feifeiyinyue.top/Article/details/gt2lrmebskf.html

Ruby: // fork 块
来源：http://dali.kuanghao11.cn/Article/details/gt2mfqrsnyv.html

C#:   Parallel.For
来源：http://dali.redwolf501.top/Article/details/gt2tusxdlnf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2vfcseioe.html

P. 常用工具函数
来源：http://dali.jqgufenzy.top/Article/details/gt2varwizvk.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2stsaheee.html

[P01] 生成 UUID
来源：http://dali.jqgfzy.top/Article/details/gt2vtrekjfb.html

Py:   str(uuid.uuid4())
来源：http://dali.gzhubu.top/Article/details/gt2nhwbwlyq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gaohongyu789.top/Article/details/gt2ihwnoyij.html

JS:   crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ztpicxka.html

TS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gt2zqfkqvff.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgufenzy.top/Article/details/gt2dpznkaph.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jlsjyb.cn/Article/details/gt2chpfjayc.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mqwwpjkz.html


<!-- 参考信息 -->