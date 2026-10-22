代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gt2wtsubens.html

[L04] 设置超时
来源：http://dali.shuidangran.top/Article/details/gt2mtkpqfij.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yueranfly.top/Article/details/gt2mveaqeet.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yonumen.top/Article/details/gt2narcecqx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gt2hhiijvhd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gt2gnjiucfj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.mhx1999.top/Article/details/gt2btrkwdrr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hysaishi.cn/Article/details/gt2imtfydgp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.mhx1999.top/Article/details/gt2wbjkbpnm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xziqi.cn/Article/details/gt2kwdduayn.html

[L05] 上传文件（multipart）
来源：http://dali.gotoacloud.top/Article/details/gt2fzztairm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.c1oappe.top/Article/details/gt2cstiphnk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cucudq.cn/Article/details/gt2wzoduprf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gt2arwnfoib.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cqqwz.cn/Article/details/gt2mwrrhwyb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xylfe.cn/Article/details/gt2efjrgtrd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shzxlz.cn/Article/details/gt2epzgqekv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hammf.cn/Article/details/gt2avdtxdkn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2bdbowoog.html

[L06] 解析响应为 JSON
来源：http://dali.jianghu66.top/Article/details/gt2nwrqvnih.html

Py:   resp.json()
来源：http://dali.hnqzz.top/Article/details/gt2djcdnjhr.html

PHP:  json_decode($body, true);
来源：http://dali.jlsjyb.cn/Article/details/gt2yqyvsdzd.html

JS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sfqiospu.html

TS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gt2oedlymzq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gt2exlslqbq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqekkbza.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ydzc1.top/Article/details/gt2sgvnapmn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aibaodan.cn/Article/details/gt2whsxqiun.html

[L07] 处理 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gt2hzgdffeh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.vqdsnc.cn/Article/details/gt2xaclwzru.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gzhubu.top/Article/details/gt2zjwaugwl.html

JS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gt2yrymxbmg.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gt2bleztcyt.html

Java: resp.statusCode()
来源：http://dali.wangdashe.top/Article/details/gt2pervqfos.html

Go:   resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gt2wcbflpqb.html

Ruby: resp.code.to_i
来源：http://dali.nwbrower.top/Article/details/gt2zeiptbyq.html

C#:   (int)resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gt2uaogyyfg.html

[L08] 并发请求多个地址
来源：http://dali.xziqi.cn/Article/details/gt2xigxfqii.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sysykeji.top/Article/details/gt2auiuecvf.html

PHP:  curl_multi_init() 系列
来源：http://dali.hongshengwenyu.top/Article/details/gt2xszyudzz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gt2hwkeegjy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gt2hdzjlivc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zycfv.cn/Article/details/gt2qdqqzsut.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.mhx1999.top/Article/details/gt2zqriswtj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dashuyun.cn/Article/details/gt2qgjxwngt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zycfv.cn/Article/details/gt2fnwxhasc.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2qkxgzefv.html

M. 命令行 / 进程 / 环境
来源：http://dali.fzhhl.top/Article/details/gt2cflihyte.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mhootatk.html

[M01] 读取命令行参数
来源：http://dali.hysaishi.cn/Article/details/gt2wtxkvzpg.html

Py:   sys.argv[1:]
来源：http://dali.daria6918.cn/Article/details/gt2tplukcdj.html

PHP:  $argv;  $argc;
来源：http://dali.guannengcc.top/Article/details/gt2apahiqmk.html

JS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gt2ponwagvl.html

TS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gt2dsckrdmt.html

Java: args 数组（main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mqmmeuog.html

Go:   os.Args[1:]
来源：http://dali.jyoumei.cn/Article/details/gt2uqlexflu.html

Ruby: ARGV
来源：http://dali.shuidangran.top/Article/details/gt2dlkfzhmh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gt2iutspfnh.html

[M02] 读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gt2uxmfzxbh.html

Py:   os.environ.get("HOME")
来源：http://dali.zycfv.cn/Article/details/gt2imyezvvg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.316326.xyz/Article/details/gt2upprvxhe.html

JS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gt2pkgnuluv.html

TS:   process.env.HOME
来源：http://dali.snrcjt.cn/Article/details/gt2jupuouck.html

Java: System.getenv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gt2bzfpnnvx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ncduisek.html

Ruby: ENV["HOME"]
来源：http://dali.tian-w.cn/Article/details/gt2fyiexuya.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2iotzrnux.html

[M03] 执行外部命令
来源：http://dali.redwolf501.top/Article/details/gt2stdlgkfu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangdashe.top/Article/details/gt2qlznsqgl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sufxvd.cn/Article/details/gt2hbhzffxr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gt2htjyodyb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gt2wrakqpwv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tianlin.xyz/Article/details/gt2cljfhzio.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cashguo.top/Article/details/gt2deiwdqtq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sxryk.cn/Article/details/gt2dvcrbsip.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shzxlz.cn/Article/details/gt2tmewybhr.html

[M04] 获取当前工作目录
来源：http://dali.yongpay.top/Article/details/gt2cyapuiqc.html

Py:   os.getcwd()
来源：http://dali.xziqi.cn/Article/details/gt2taimybhm.html

PHP:  getcwd();
来源：http://dali.chenlongwang.top/Article/details/gt2jhvnyhdx.html

JS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gt2qaktjohz.html

TS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gt2bushtlrq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jjqqamup.html

Go:   os.Getwd()
来源：http://dali.daxiang520.top/Article/details/gt2mlialscg.html

Ruby: Dir.pwd
来源：http://dali.gotoacloud.top/Article/details/gt2thylmelv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cashguo.top/Article/details/gt2svxspsru.html

[M05] 设置退出码
来源：http://dali.jinqigfzy.top/Article/details/gt2vufqfsun.html

Py:   sys.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2zwvqcqjm.html

PHP:  exit(1);
来源：http://dali.jiagoushi.top/Article/details/gt2arglzvsh.html

JS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gt2fjbliykj.html

TS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gt2lvcjskqi.html

Java: System.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gt2zdzrjrgf.html

Go:   os.Exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2dvovuncv.html

Ruby: exit 1
来源：http://dali.yuxming.cn/Article/details/gt2ibtftspq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sufxvd.cn/Article/details/gt2nhqniaie.html

[M06] 向标准错误输出
来源：http://dali.yanxiufei.cn/Article/details/gt2dwbabbnf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gt2lmtylmve.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.haohaochexian.top/Article/details/gt2srcgxkdo.html

JS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gt2mcfizqwr.html

TS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gt2fjwgdnur.html

Java: System.err.println("err")
来源：http://dali.nanxuanxn.top/Article/details/gt2sjyjxwiz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2juxxgmet.html

Ruby: warn "err"
来源：http://dali.tanke756.top/Article/details/gt2pfunwglu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gzhubu.top/Article/details/gt2feogtugi.html

[M07] 判断是否为主入口
来源：http://dali.chenlongwang.top/Article/details/gt2anepphgt.html

Py:   if __name__ == "__main__":
来源：http://dali.haohaochexian.top/Article/details/gt2xughtoil.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj202588.top/Article/details/gt2gbpnigzw.html

JS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gt2zihdjhom.html

TS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gt2xdhnkrtw.html

Java: public static void main(String[] args)
来源：http://dali.aibaodan.cn/Article/details/gt2sdglgzfy.html

Go:   func main()
来源：http://dali.shzxlz.cn/Article/details/gt2mnzbrfcm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.9152youxi.cn/Article/details/gt2ocjdrtka.html

C#:   static void Main(string[] args)
来源：http://dali.meibo888.top/Article/details/gt2reszkxpv.html

[M08] 获取系统与运行时信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hxlzyxka.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hysaishi.cn/Article/details/gt2jzvsdftq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.vqdsnc.cn/Article/details/gt2zcmdokiu.html

JS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gt2tsoeccfo.html

TS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gt2rntbcwzg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.smart0.xyz/Article/details/gt2ecuhyczg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ppjwa.cn/Article/details/gt2iuxvwjyl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.birdmap.top/Article/details/gt2afuldfch.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigfzy.top/Article/details/gt2fcdxsgkz.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2awombufe.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gt2skebvels.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2yhmgknil.html

[N01] 二分查找（有序数组）
来源：http://dali.chenjidiqi.icu/Article/details/gt2eveyicjw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2zudxstbc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2oegkokok.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gt2tvsizmir.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gt2lcqejuxa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2tyxxkwkg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2yvxcubrx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tian-w.cn/Article/details/gt2ujmfneij.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cxfbykit.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.fzhhl.top/Article/details/gt2ytpvxdtd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gt2zqfwmbjg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gt2sulgirll.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gt2fdrwgweu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gt2aadmukac.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.smart0.xyz/Article/details/gt2avbtjyub.html

Go:   slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gt2xhcmgwjr.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gt2tiulawbd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuetiantiany.cn/Article/details/gt2idobcsxb.html

[N03] 快速排序（分治示例）
来源：http://dali.xylfe.cn/Article/details/gt2qlbbooas.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cashguo.top/Article/details/gt2snktwlof.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenlongwang.top/Article/details/gt2jdgivhre.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gt2esytldub.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gt2keqzeblt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daxiang520.top/Article/details/gt2jznbjitm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenjidiqi.icu/Article/details/gt2keyzphyj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hywenlv.cn/Article/details/gt2lnldjxnm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zycfv.cn/Article/details/gt2oladjdxp.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2mjforork.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gt2wspzcxvd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gt2nmkkhsrg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gt2liifnxxd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gt2yzezjbet.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gt2ozbllagd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fzhhl.top/Article/details/gt2fpfhkevw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gt2idjegjpu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gt2moalevki.html

[N05] 最大公约数
来源：http://dali.zhixingplan.top/Article/details/gt2vffmgqqo.html

Py:   math.gcd(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mnctrrze.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jhqkvheo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gt2ssvfhupf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gt2fklxctxh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj202588.top/Article/details/gt2mfhxwvrg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhoulong.xyz/Article/details/gt2rmjhacbq.html

Ruby: a.gcd(b)
来源：http://dali.yanxiufei.cn/Article/details/gt2gdwwijup.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dianchejie.cn/Article/details/gt2tixgnmmy.html

[N06] 判断回文字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2dyhtnvvm.html

Py:   s == s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gt2sxorpicw.html

PHP:  $s === strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gt2nanubevc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gt2zixohysy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gt2nlfzwhad.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nwbrower.top/Article/details/gt2bnyyfocz.html

Go:   // 双指针从两端比较
来源：http://dali.tanke756.top/Article/details/gt2whcxyrhf.html

Ruby: s == s.reverse
来源：http://dali.gzhubu.top/Article/details/gt2ueyavzrq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gt2xwkxjfie.html

[N07] 两数之和（返回下标）
来源：http://dali.jlsjyb.cn/Article/details/gt2fkdwmdln.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tanke756.top/Article/details/gt2pisbedlb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenlongwang.top/Article/details/gt2wptumbiy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pycfn.com/Article/details/gt2kivcpdci.html

TS:   // 手写 Map<string, number>
来源：http://dali.fengsongda.top/Article/details/gt2sxrrdodj.html

Java: // 手写 HashMap
来源：http://dali.andypj.xyz/Article/details/gt2xzxuofjo.html

Go:   // 手写 map[int]int
来源：http://dali.yj202588.top/Article/details/gt2nyolqrog.html

Ruby: // 手写 Hash
来源：http://dali.dianchejie.cn/Article/details/gt2kubocrdx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sufxvd.cn/Article/details/gt2drfuiwqu.html

[N08] 生成全排列
来源：http://dali.vqdsnc.cn/Article/details/gt2llrhxjsw.html

Py:   itertools.permutations(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2igypwtzy.html

PHP:  // 手写递归交换
来源：http://dali.chenzaomai.com/Article/details/gt2kyfkluzu.html

JS:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gt2txmienqy.html

TS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gt2kjqywrjx.html

Java: // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2ilnygotf.html

Go:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2bqhuvzix.html

Ruby: arr.permutation.to_a
来源：http://dali.smart0.xyz/Article/details/gt2hybconoa.html

C#:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2tkqfautm.html

[N09] 栈与队列
来源：http://dali.guannengcc.top/Article/details/gt2ixleuiro.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yueranfly.top/Article/details/gt2jltsyson.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xinyue.icu/Article/details/gt2jrwppkak.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gt2aadiyzvb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yongpay.top/Article/details/gt2djolsqnw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zdqjudy.top/Article/details/gt2igetiale.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxinkj.top/Article/details/gt2xkhedlpg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gt2nikmoaoh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvdxsse.html

[N10] 链表节点定义
来源：http://dali.yueranfly.top/Article/details/gt2nezshxih.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuxming.cn/Article/details/gt2hjgeammo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.snrcjt.cn/Article/details/gt2gixzaodq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gt2qnwnhycu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ehwqpu.com/Article/details/gt2ixcmicbg.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iulqzgku.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cqqwz.cn/Article/details/gt2qyirlydq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gaohongyu789.top/Article/details/gt2atuqcqia.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.andypj.xyz/Article/details/gt2nyaxzsvf.html

[N11] 二叉树中序遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2wepzxcec.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daria6918.cn/Article/details/gt2enfyirgp.html

PHP:  // 手写递归函数
来源：http://dali.yj20258.top/Article/details/gt2yrhpycnz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gt2biqaenab.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2utgrczhd.html

Java: // 手写递归
来源：http://dali.yonumen.top/Article/details/gt2bhwsijym.html

Go:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gt2jirysrmm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hfpthk.cn/Article/details/gt2rdiprmlo.html

C#:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gt2hakleuwy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yonumen.top/Article/details/gt2kehmujhu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uzlzusqb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.meibo888.top/Article/details/gt2robyjlzr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gt2jpfpwdrk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuanzx.com/Article/details/gt2hfgftgvj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gt2pnqrcsbv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daria6918.cn/Article/details/gt2tqpbsvcz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ftxgtigc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gt2ztxccohb.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2meviksss.html

O. 并发与异步
来源：http://dali.cqqwz.cn/Article/details/gt2pzezkwsm.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2ccfszpot.html

[O01] 启动一个线程
来源：http://dali.hywenlv.cn/Article/details/gt2rgyizjzq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhiwuduotai.top/Article/details/gt2gjviiefn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2untxzvqw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhixingplan.top/Article/details/gt2yaxynsjl.html

TS:   // 同 JS
来源：http://dali.316326.xyz/Article/details/gt2qrvydatt.html

Java: new Thread(() -> f()).start()
来源：http://dali.ehwqpu.com/Article/details/gt2pbtamudk.html

Go:   go f()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zsyelfyz.html

Ruby: Thread.new { f }
来源：http://dali.yueranfly.top/Article/details/gt2tskxptqb.html

C#:   Task.Run(() => F());
来源：http://dali.zhiwuduotai.top/Article/details/gt2dfktptfs.html

[O02] 使用线程池
来源：http://dali.ivvv.top/Article/details/gt2joosxtxk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.316326.xyz/Article/details/gt2rjxenneu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shuidangran.top/Article/details/gt2rmtycivu.html

JS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gt2tcvirtec.html

TS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gt2zfmsowlo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hywenlv.cn/Article/details/gt2vonupxth.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yanxiufei.cn/Article/details/gt2vbnpkfwr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuxming.cn/Article/details/gt2hfuuhhkl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cdnleiting.top/Article/details/gt2qfwucjtv.html

[O03] 加锁保护共享数据
来源：http://dali.gaohongyu789.top/Article/details/gt2yrjimxya.html

Py:   with lock: shared += 1
来源：http://dali.c1oappe.top/Article/details/gt2ijnnwcwz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pycfn.com/Article/details/gt2nuetcoqx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xziqi.cn/Article/details/gt2wpypmfvq.html

TS:   // 同 JS
来源：http://dali.jlsjyb.cn/Article/details/gt2znyxhsaw.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gt2kilylhhe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.c1oappe.top/Article/details/gt2hzjyfhrx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cashguo.top/Article/details/gt2qcamybet.html

C#:   lock (gate) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gt2cxngaooh.html

[O04] 定义异步函数并等待
来源：http://dali.mhx1999.top/Article/details/gt2qhvpfstq.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ufthgjln.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.9152youxi.cn/Article/details/gt2xuneunon.html

JS:   async function f() { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2qsfzomzs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gt2jsgyngpe.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yeacniqd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigfzy.top/Article/details/gt2syxnvzvz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hysaishi.cn/Article/details/gt2uunggqrn.html

C#:   async Task F() { await G(); }
来源：http://dali.gogol.net.cn/Article/details/gt2vjldrtta.html

[O05] 并发执行并等待全部完成
来源：http://dali.aibaodan.cn/Article/details/gt2htntrhfw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xinyue.icu/Article/details/gt2hvwztafn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sxryk.cn/Article/details/gt2ocyhsvkw.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gt2svmvqsnl.html

TS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pfwutwrs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2xygoprur.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnqzz.top/Article/details/gt2vzusedmz.html

Ruby: threads.map(&:join)
来源：http://dali.shzxlz.cn/Article/details/gt2exufzobp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yuanzhike.top/Article/details/gt2btakaeio.html

[O06] 使用进程池
来源：http://dali.quarkkingdee.top/Article/details/gt2abuazeri.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dashuyun.cn/Article/details/gt2yqlthrgq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuxming.cn/Article/details/gt2oahcldwo.html

JS:   // child_process / cluster 模块
来源：http://dali.guannengcc.top/Article/details/gt2dryokrbq.html

TS:   // child_process / cluster 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jplaqavv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cheryme.top/Article/details/gt2rismobvq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.iojbl.cn/Article/details/gt2xdkwvkui.html

Ruby: // fork 块
来源：http://dali.yj20258888.top/Article/details/gt2bllonucp.html

C#:   Parallel.For
来源：http://dali.aibaodan.cn/Article/details/gt2myllmitd.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2pjvqxnje.html

P. 常用工具函数
来源：http://dali.redwolf501.top/Article/details/gt2wfgwihas.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvmenybd.html

[P01] 生成 UUID
来源：http://dali.zycfv.cn/Article/details/gt2pzhdjwaq.html

Py:   str(uuid.uuid4())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mlsuoqcx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hoeefbpe.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gt2wfzybmtl.html

TS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gt2beflvpbd.html

Java: UUID.randomUUID().toString()
来源：http://dali.tanke756.top/Article/details/gt2esvogmcj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigufen.top/Article/details/gt2atouxdak.html

Ruby: SecureRandom.uuid
来源：http://dali.sufxvd.cn/Article/details/gt2rrzaapju.html


<!-- 参考信息 -->