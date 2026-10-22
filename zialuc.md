代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gtgqsipzta.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gtgfmvzang.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenzaomai.com/Article/details/gtwxumfmup.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj202588.top/Article/details/gthagttqsb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenjidiqi.icu/Article/details/gtmzgwexwf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.9152youxi.cn/Article/details/gtjqslmoty.html

[L05] 上传文件（multipart）
来源：http://dali.cucudq.cn/Article/details/gtgiegkiju.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cucudq.cn/Article/details/gtxogogbnv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cqqwz.cn/Article/details/gthmepowgw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gtxvmzxukn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gtmkoayqrn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.316326.xyz/Article/details/gtftcteoyx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.snrcjt.cn/Article/details/gtwyoodyly.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.smart0.xyz/Article/details/gtyglahenh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtqdzhmmdi.html

[L06] 解析响应为 JSON
来源：http://dali.daxiang520.top/Article/details/gtytddblly.html

Py:   resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtbziyuimq.html

PHP:  json_decode($body, true);
来源：http://dali.hnxiangtu.top/Article/details/gtroouxnqj.html

JS:   await resp.json()
来源：http://dali.zdqjudy.top/Article/details/gtsdelwzmh.html

TS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtyojohrpz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj202588.top/Article/details/gtgrbrfwkh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.c1oappe.top/Article/details/gtbpoiwpdq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.pycfn.com/Article/details/gtfxukvlnt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ehwqpu.com/Article/details/gtargdlmkp.html

[L07] 处理 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gtyucnmxrx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hfpthk.cn/Article/details/gtpnohknkf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhoulong.xyz/Article/details/gtjcjrposz.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gtrxupqyrv.html

TS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gtdcjjsyrc.html

Java: resp.statusCode()
来源：http://dali.yangfankeji.com/Article/details/gtvxmktbvu.html

Go:   resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gtkoofateh.html

Ruby: resp.code.to_i
来源：http://dali.gogol.net.cn/Article/details/gtlxzqcsnq.html

C#:   (int)resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gtbsxbuncg.html

[L08] 并发请求多个地址
来源：http://dali.c1oappe.top/Article/details/gtykibwjqd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tianlin.xyz/Article/details/gtgieanjjj.html

PHP:  curl_multi_init() 系列
来源：http://dali.tanke756.top/Article/details/gtebxhvjqw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gtfnkhehrq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gtyylcxlqp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinghuilouyu.cn/Article/details/gtccymyztb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwxwkcrh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenlongwang.top/Article/details/gthhwjmfrv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.meibo888.top/Article/details/gtljyvdbhj.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtwzbqtbff.html

M. 命令行 / 进程 / 环境
来源：http://dali.nwbrower.top/Article/details/gtoxzbakmf.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtlfyabswn.html

[M01] 读取命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtywtxphyq.html

Py:   sys.argv[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtwigocuwt.html

PHP:  $argv;  $argc;
来源：http://dali.hnxiangtu.top/Article/details/gtfklubtqw.html

JS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtrfogwawk.html

TS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gtftegcxgt.html

Java: args 数组（main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtzzyvzedq.html

Go:   os.Args[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtshxviwfj.html

Ruby: ARGV
来源：http://dali.chenlongwang.top/Article/details/gtfvtdyeqs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gttjdzckrq.html

[M02] 读取环境变量
来源：http://dali.9152youxi.cn/Article/details/gtthaukwvj.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtcfoenbby.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gtrtgfqdfi.html

JS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtnqgmisfl.html

TS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gtlnuxspxi.html

Java: System.getenv("HOME")
来源：http://dali.yj202588.top/Article/details/gtarsdmdhr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuxming.cn/Article/details/gttpehuuws.html

Ruby: ENV["HOME"]
来源：http://dali.sweek.top/Article/details/gtgymrbrka.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtuccbbivr.html

[M03] 执行外部命令
来源：http://dali.hfpthk.cn/Article/details/gtueekajbz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yonumen.top/Article/details/gttbzohexh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258.top/Article/details/gtszspoynq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gtgrdnrxal.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gtulldhdnm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenlongwang.top/Article/details/gtghyktmay.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.quarkkingdee.top/Article/details/gttegkeauj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.iojbl.cn/Article/details/gtrtodfjga.html

C#:   Process.Start("ls", "-l");
来源：http://dali.svipenyu.cn/Article/details/gtlqwcxmtr.html

[M04] 获取当前工作目录
来源：http://dali.yuanzhike.top/Article/details/gtnmersqin.html

Py:   os.getcwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfhyxduz.html

PHP:  getcwd();
来源：http://dali.cdnleiting.top/Article/details/gtpfunhcef.html

JS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtmabqvyls.html

TS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gtubpmeroh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daxiang520.top/Article/details/gtspaykdhg.html

Go:   os.Getwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtajjqjacf.html

Ruby: Dir.pwd
来源：http://dali.dianchejie.cn/Article/details/gtmwqdnmui.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj202588.top/Article/details/gtojcpjwog.html

[M05] 设置退出码
来源：http://dali.yueranfly.top/Article/details/gtafinpguk.html

Py:   sys.exit(1)
来源：http://dali.pycfn.com/Article/details/gtakiahidj.html

PHP:  exit(1);
来源：http://dali.daria6918.cn/Article/details/gttiyoihwx.html

JS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtqoijmrji.html

TS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtxrdibvsb.html

Java: System.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtcqegouvd.html

Go:   os.Exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtohcglkjq.html

Ruby: exit 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgykyoust.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yvedp.cn/Article/details/gtauecvbtw.html

[M06] 向标准错误输出
来源：http://dali.sxryk.cn/Article/details/gtbershcon.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gtprqhirve.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnqzz.top/Article/details/gthprtyhtx.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtnqteioge.html

TS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gtlrhpbjet.html

Java: System.err.println("err")
来源：http://dali.smart0.xyz/Article/details/gtatmrmdah.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigufen.top/Article/details/gtvwphevqg.html

Ruby: warn "err"
来源：http://dali.316326.xyz/Article/details/gtljixuiza.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ydzc1.top/Article/details/gtvfhxghll.html

[M07] 判断是否为主入口
来源：http://dali.chenjidiqi.icu/Article/details/gtublxjwyx.html

Py:   if __name__ == "__main__":
来源：http://dali.tanke756.top/Article/details/gtmgpfbajw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dianchejie.cn/Article/details/gtkuuhyxeb.html

JS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiltrddak.html

TS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gtexzeqbif.html

Java: public static void main(String[] args)
来源：http://dali.quarkkingdee.top/Article/details/gtxcwyzurd.html

Go:   func main()
来源：http://dali.yueranfly.top/Article/details/gtspuwawck.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cheryme.top/Article/details/gtgcsmoxwz.html

C#:   static void Main(string[] args)
来源：http://dali.ivvv.top/Article/details/gtzurkoacv.html

[M08] 获取系统与运行时信息
来源：http://dali.nwbrower.top/Article/details/gtbdiymscu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.snrcjt.cn/Article/details/gtpuqqajqn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.redwolf501.top/Article/details/gthwozkkfq.html

JS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gthmraxqar.html

TS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gthwemipho.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cucudq.cn/Article/details/gtyfjlysox.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigfzy.top/Article/details/gtlfbthqlg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.birdmap.top/Article/details/gtaqhjrizl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.9152youxi.cn/Article/details/gtejwyejib.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnqhcervm.html

N. 数据结构与算法
来源：http://dali.ehwqpu.com/Article/details/gticjzetvh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtvjtmmoxd.html

[N01] 二分查找（有序数组）
来源：http://dali.snrcjt.cn/Article/details/gtidrrfubb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gthozwaywz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.smart0.xyz/Article/details/gtecbomyhy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtcaxoedax.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtsjtkhsxw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtzauoutyc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtawxsxkax.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.meibo888.top/Article/details/gtpvgfziod.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gthhsagfzx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnqzz.top/Article/details/gtutgfuiqf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspuylrzo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258.top/Article/details/gtsglwkvpu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkdyqszf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtszturuit.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenlongwang.top/Article/details/gtvddjxovo.html

Go:   slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gtjiayfaer.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtzarsfgaa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tanke756.top/Article/details/gttmkauuyw.html

[N03] 快速排序（分治示例）
来源：http://dali.zycfv.cn/Article/details/gtieugzefe.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ivvv.top/Article/details/gtlaztumxu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cucudq.cn/Article/details/gthnaeulky.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gtaphjncme.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnqzz.top/Article/details/gtvsptfshp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hammf.cn/Article/details/gtlcwyxbyo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhiwuduotai.top/Article/details/gthnsekbvo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuanzx.com/Article/details/gtgsqsetcx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.haohaochexian.top/Article/details/gtozozvtqc.html

[N04] 斐波那契数列
来源：http://dali.jinqigufen.top/Article/details/gtaawentoj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfuzmcjlc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gteujkrolt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gtbmalaegz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtsllswpdw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtwswxtkdu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.9152youxi.cn/Article/details/gtgqrxrymu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtiozamqtx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtipuklbsf.html

[N05] 最大公约数
来源：http://dali.chenjidiqi.icu/Article/details/gtmhplzogn.html

Py:   math.gcd(a, b)
来源：http://dali.shuidangran.top/Article/details/gtdcgodujo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdrdbugdo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gtsnvzoara.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjcwbjbj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nwbrower.top/Article/details/gtjyodmieh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiupargcj.html

Ruby: a.gcd(b)
来源：http://dali.andypj.xyz/Article/details/gtcktooqet.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.havefunace.top/Article/details/gtiigjovzn.html

[N06] 判断回文字符串
来源：http://dali.zhengqikj.top/Article/details/gtyqxdrfzk.html

Py:   s == s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gtgwkbkrdo.html

PHP:  $s === strrev($s);
来源：http://dali.guannengcc.top/Article/details/gtbtnhhfwe.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtvwymqrhw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtkibudmyz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dashuyun.cn/Article/details/gtyufdjgzm.html

Go:   // 双指针从两端比较
来源：http://dali.jqgufenzy.top/Article/details/gtaxflmvfg.html

Ruby: s == s.reverse
来源：http://dali.hysaishi.cn/Article/details/gtwynrlezv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenjidiqi.icu/Article/details/gtmcerqsbm.html

[N07] 两数之和（返回下标）
来源：http://dali.haohaochexian.top/Article/details/gtilemmbnd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnxiangtu.top/Article/details/gtcaorjmsc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgfzy.top/Article/details/gtmkacljsl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgufenzy.top/Article/details/gtkmqxzmio.html

TS:   // 手写 Map<string, number>
来源：http://dali.daxiang520.top/Article/details/gtjoounkdk.html

Java: // 手写 HashMap
来源：http://dali.cucudq.cn/Article/details/gtxurbvxbl.html

Go:   // 手写 map[int]int
来源：http://dali.cdnleiting.top/Article/details/gtqurutcuq.html

Ruby: // 手写 Hash
来源：http://dali.yonumen.top/Article/details/gtmhhdrhmv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.wangdashe.top/Article/details/gtrsskxnso.html

[N08] 生成全排列
来源：http://dali.vqdsnc.cn/Article/details/gtrfspnnsj.html

Py:   itertools.permutations(arr)
来源：http://dali.ivvv.top/Article/details/gtslmqlhgv.html

PHP:  // 手写递归交换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywvlatqd.html

JS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvbxmdpo.html

TS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtixxrjsjb.html

Java: // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtcrgoyvwu.html

Go:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtqekawdvt.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gtyrhoaapn.html

C#:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtzymdxurh.html

[N09] 栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfrcpaaad.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtjgypwunc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtohdrvgjd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gtkkweavqu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.9152youxi.cn/Article/details/gtpfhemlmq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shuidangran.top/Article/details/gtbtsqwgit.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tian-w.cn/Article/details/gtctcdmnnz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtjuwijfcm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ivvv.top/Article/details/gtmcqvfslz.html

[N10] 链表节点定义
来源：http://dali.ehwqpu.com/Article/details/gtuigualvy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ydzc1.top/Article/details/gtvfpsazdc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cqqwz.cn/Article/details/gttheopysv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtskdtzgfw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cdnleiting.top/Article/details/gtaajvuthe.html

Java: class Node { int v; Node next; }
来源：http://dali.zhiwuduotai.top/Article/details/gtiuexllcf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xinyue.icu/Article/details/gtnjjcqext.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daria6918.cn/Article/details/gtqbqzgdzm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zycfv.cn/Article/details/gtnmzyajme.html

[N11] 二叉树中序遍历
来源：http://dali.smart0.xyz/Article/details/gttlwlqzyd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cdnleiting.top/Article/details/gtfbsajcru.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gtmamhgcat.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cashguo.top/Article/details/gtopxqawvx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gtlrvsdlol.html

Java: // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gtwbamdluo.html

Go:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtgzgfaiba.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.meibo888.top/Article/details/gtbffrpryb.html

C#:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtzvmqripp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yongpay.top/Article/details/gtmfybahnu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hammf.cn/Article/details/gtzuewbozc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pycfn.com/Article/details/gtkiztzctg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gtfadczaoc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sysykeji.top/Article/details/gtwuswqlpu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgufenzy.top/Article/details/gtsejoqanh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.smart0.xyz/Article/details/gtjdyodrwc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daxiang520.top/Article/details/gtejwbkada.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.birdmap.top/Article/details/gtdxngacpd.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhekvyli.html

O. 并发与异步
来源：http://dali.xziqi.cn/Article/details/gtuqexnycm.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvvqsqaiz.html

[O01] 启动一个线程
来源：http://dali.0kj1m.cn/Article/details/gtrxyungiw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shangyingyoupin.top/Article/details/gtyyqnzzrm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jqgfzy.top/Article/details/gtopwhwtdb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zycfv.cn/Article/details/gtkdfjbkxd.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gtqcexbnmi.html

Java: new Thread(() -> f()).start()
来源：http://dali.meibo888.top/Article/details/gthwmhhdqj.html

Go:   go f()
来源：http://dali.ehwqpu.com/Article/details/gtwlrjhmtv.html

Ruby: Thread.new { f }
来源：http://dali.jiagoushi.top/Article/details/gtqcazfzvb.html

C#:   Task.Run(() => F());
来源：http://dali.redwolf501.top/Article/details/gtkywkumax.html

[O02] 使用线程池
来源：http://dali.jiagoushi.top/Article/details/gtpleptayj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yanxiufei.cn/Article/details/gtgffgiqaq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.svipenyu.cn/Article/details/gtqzmhgvsa.html

JS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gtakwezqyz.html

TS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gtbkinfghy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.iojbl.cn/Article/details/gtxpavzzgk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hongshengwenyu.top/Article/details/gtaruektju.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hywenlv.cn/Article/details/gtclpczaek.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cashguo.top/Article/details/gteaanbzvw.html

[O03] 加锁保护共享数据
来源：http://dali.wangshuangyany.cn/Article/details/gthtxsrbxl.html

Py:   with lock: shared += 1
来源：http://dali.cdnleiting.top/Article/details/gtqlxmfdit.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.iojbl.cn/Article/details/gtilfvugbk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hywenlv.cn/Article/details/gtzewpccaz.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gtqdtcochr.html

Java: synchronized (this) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gtyvnxiasl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.mhx1999.top/Article/details/gthzogfnxp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yvedp.cn/Article/details/gtjxwfhvaq.html

C#:   lock (gate) { shared++; }
来源：http://dali.redwolf501.top/Article/details/gtsftxqkkg.html

[O04] 定义异步函数并等待
来源：http://dali.chenlongwang.top/Article/details/gtdocopvpy.html

Py:   async def f():⏎    await g()
来源：http://dali.vqdsnc.cn/Article/details/gtttnkkwgb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hammf.cn/Article/details/gtbcgcntqz.html

JS:   async function f() { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gtangekzbc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.bjfxy.top/Article/details/gtdzbslqme.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hongshengwenyu.top/Article/details/gtiumijcfa.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.havefunace.top/Article/details/gtjhczfpkm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ybcxt.top/Article/details/gtcbdftart.html

C#:   async Task F() { await G(); }
来源：http://dali.hnqzz.top/Article/details/gtomjhjawj.html

[O05] 并发执行并等待全部完成
来源：http://dali.meibo888.top/Article/details/gtnjzwjoic.html

Py:   asyncio.gather(*tasks)
来源：http://dali.svipenyu.cn/Article/details/gtgnexpztj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yanxiufei.cn/Article/details/gtpvojuvtr.html

JS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtoapbuimu.html

TS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtjrvrvilg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.vqdsnc.cn/Article/details/gtgkliqsgn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hongshengwenyu.top/Article/details/gteelqhovh.html

Ruby: threads.map(&:join)
来源：http://dali.hnqzz.top/Article/details/gtpbdhewjh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xinyue.icu/Article/details/gtxmclsibs.html

[O06] 使用进程池
来源：http://dali.pycfn.com/Article/details/gtcnainxyv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nwbrower.top/Article/details/gtmxdcykpx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgufenzy.top/Article/details/gtfjzckdqb.html

JS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gtnhcjikub.html

TS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gtxsuikfyz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorercquw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fzhhl.top/Article/details/gtkubystxg.html

Ruby: // fork 块
来源：http://dali.sufxvd.cn/Article/details/gtlimrvrvy.html

C#:   Parallel.For
来源：http://dali.jianghu66.top/Article/details/gtzjzzotsh.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtepzzxdvx.html

P. 常用工具函数
来源：http://dali.dianchejie.cn/Article/details/gtchldgyyy.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtdiliazqa.html

[P01] 生成 UUID
来源：http://dali.hnqzz.top/Article/details/gtiwrisceu.html

Py:   str(uuid.uuid4())
来源：http://dali.jiagoushi.top/Article/details/gtvvjjjwhg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenjidiqi.icu/Article/details/gtqbdjbmsf.html

JS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtvkzkzizr.html

TS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gtcwfarqjr.html

Java: UUID.randomUUID().toString()
来源：http://dali.dashuyun.cn/Article/details/gtawdtlccu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fengsongda.top/Article/details/gtcynpniiz.html

Ruby: SecureRandom.uuid
来源：http://dali.sysykeji.top/Article/details/gtzfgrbcwl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jiagoushi.top/Article/details/gtfayvzsgc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhixingplan.top/Article/details/gtavofgzwv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sweek.top/Article/details/gtdctjleda.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.snrcjt.cn/Article/details/gtdgtslfhy.html


<!-- 参考信息 -->