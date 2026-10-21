代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnqzz.top/Article/details/gtfljdgegr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gtutzekmdt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shuidangran.top/Article/details/gtowixgtbp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.birdmap.top/Article/details/gtjchyvmov.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhiwuduotai.top/Article/details/gtohzqckxp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gaohongyu789.top/Article/details/gtpuilrxne.html

[L05] 上传文件（multipart）
来源：http://dali.jiagoushi.top/Article/details/gtbdhprewo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yueranfly.top/Article/details/gtrtbpbomm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.316326.xyz/Article/details/gttlqtscjq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszkdpmnm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gtroynqnsy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fengsongda.top/Article/details/gtwuiojqtt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.c1oappe.top/Article/details/gtkwajodmk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cucudq.cn/Article/details/gtfwketxxe.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.andypj.xyz/Article/details/gthpwoopik.html

[L06] 解析响应为 JSON
来源：http://dali.vqdsnc.cn/Article/details/gtznnhffmu.html

Py:   resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtevyamrte.html

PHP:  json_decode($body, true);
来源：http://dali.xziqi.cn/Article/details/gtfgolaris.html

JS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtammpcqht.html

TS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmafvmjy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gtpffxasjx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guowangkeji.top/Article/details/gtyhdclsry.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigfzy.top/Article/details/gtkvdpusrh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gotoacloud.top/Article/details/gtxwzodwwf.html

[L07] 处理 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gtlsujmizi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigufen.top/Article/details/gtwesvxuvw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tian-w.cn/Article/details/gtuvqimucr.html

JS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtyzdwhxus.html

TS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gtubcknzpe.html

Java: resp.statusCode()
来源：http://dali.xuetiantiany.cn/Article/details/gtfehxcsxc.html

Go:   resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gtyvszvyel.html

Ruby: resp.code.to_i
来源：http://dali.hnqzz.top/Article/details/gtgnazgimy.html

C#:   (int)resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtymlvcqar.html

[L08] 并发请求多个地址
来源：http://dali.guowangkeji.top/Article/details/gtopjqsvpe.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnxiangtu.top/Article/details/gtrajiaers.html

PHP:  curl_multi_init() 系列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlxgmode.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtdmjlpnxs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gtxsnsxzqx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guannengcc.top/Article/details/gtkcpwrcpo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.birdmap.top/Article/details/gtaegaktkc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj202588.top/Article/details/gtgukttjxu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtmwthmxzt.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtgyllknfz.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhoulong.xyz/Article/details/gtgvsnagro.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtzdhfuaei.html

[M01] 读取命令行参数
来源：http://dali.gogol.net.cn/Article/details/gtdyjafzwt.html

Py:   sys.argv[1:]
来源：http://dali.hfpthk.cn/Article/details/gttpdkponq.html

PHP:  $argv;  $argc;
来源：http://dali.jyoumei.cn/Article/details/gtphhapmau.html

JS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gtojgotljf.html

TS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gteukazmob.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gthkgwshub.html

Go:   os.Args[1:]
来源：http://dali.9152youxi.cn/Article/details/gtsgyoltrv.html

Ruby: ARGV
来源：http://dali.jlsjyb.cn/Article/details/gttktobewy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gtemydjtmw.html

[M02] 读取环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoveondxj.html

Py:   os.environ.get("HOME")
来源：http://dali.cheryme.top/Article/details/gtgldthhag.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtmeeefwfw.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnzirmbq.html

TS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gtjaihokyj.html

Java: System.getenv("HOME")
来源：http://dali.316326.xyz/Article/details/gtkfdglssh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.316326.xyz/Article/details/gtfyhbxwnq.html

Ruby: ENV["HOME"]
来源：http://dali.xuanzx.com/Article/details/gtjpfywuyl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtccnojvps.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gturiqvber.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.snrcjt.cn/Article/details/gtfkzhfzue.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.iojbl.cn/Article/details/gttbxwlesj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gtwqjhiheq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gtvvvpyers.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yanxiufei.cn/Article/details/gtsqfauqrb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkbnyqqt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigfzy.top/Article/details/gtrzbdwary.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuanzhike.top/Article/details/gtcdrslssb.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gtkottowxh.html

Py:   os.getcwd()
来源：http://dali.chenzaomai.com/Article/details/gtbqsapeob.html

PHP:  getcwd();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagqnfslm.html

JS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gtkovllnae.html

TS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gtkpahblmv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.smart0.xyz/Article/details/gtpxscmezg.html

Go:   os.Getwd()
来源：http://dali.smart0.xyz/Article/details/gtaqwyezhj.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbwplauy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sweek.top/Article/details/gtuzagxkey.html

[M05] 设置退出码
来源：http://dali.andypj.xyz/Article/details/gtrnxypgbx.html

Py:   sys.exit(1)
来源：http://dali.meibo888.top/Article/details/gtyubtajvv.html

PHP:  exit(1);
来源：http://dali.smart0.xyz/Article/details/gttprghevc.html

JS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gttbwqptwn.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtujucemav.html

Java: System.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtjncunsbo.html

Go:   os.Exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcagasfs.html

Ruby: exit 1
来源：http://dali.fengsongda.top/Article/details/gtzwlxsamw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ydzc1.top/Article/details/gtuwofhfel.html

[M06] 向标准错误输出
来源：http://dali.sxryk.cn/Article/details/gtjkfmrott.html

Py:   print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gtznlwzete.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258.top/Article/details/gtpsxvvdqc.html

JS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gtontkfbvw.html

TS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gtehatavip.html

Java: System.err.println("err")
来源：http://dali.hysaishi.cn/Article/details/gtsdetbglg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhongyouzk.top/Article/details/gtuxqmqtvx.html

Ruby: warn "err"
来源：http://dali.aibaodan.cn/Article/details/gtbelifhhu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenzaomai.com/Article/details/gtjwpgrgrj.html

[M07] 判断是否为主入口
来源：http://dali.andypj.xyz/Article/details/gtahtfycwu.html

Py:   if __name__ == "__main__":
来源：http://dali.zhengqikj.top/Article/details/gtnwrqnlcu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cucudq.cn/Article/details/gtugqcjmyt.html

JS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gtbksojsmx.html

TS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdhdxeht.html

Java: public static void main(String[] args)
来源：http://dali.xziqi.cn/Article/details/gtqsvruzni.html

Go:   func main()
来源：http://dali.cheryme.top/Article/details/gteejeurzw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gzhubu.top/Article/details/gtenhakupl.html

C#:   static void Main(string[] args)
来源：http://dali.jqgufenzy.top/Article/details/gtuaxrkhmq.html

[M08] 获取系统与运行时信息
来源：http://dali.bjfxy.top/Article/details/gtqxdldjkm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxuanxn.top/Article/details/gtadlgernf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxuanxn.top/Article/details/gtbzfllpba.html

JS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gtjakjkukb.html

TS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gtuhcutzeb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pycfn.com/Article/details/gtlgjjmcch.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxinkj.top/Article/details/gtxhhiemmc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shangyingyoupin.top/Article/details/gtqplwkcmm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gtvklvmeyv.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtgvrslotv.html

N. 数据结构与算法
来源：http://dali.nanxuanxn.top/Article/details/gtvfcxbbmu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtcseiecyl.html

[N01] 二分查找（有序数组）
来源：http://dali.sweek.top/Article/details/gtirfjyzks.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtiuydulwn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.smart0.xyz/Article/details/gthxyoakks.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gtvoatersd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtieuakcyx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtmnrqjxyg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.316326.xyz/Article/details/gtwtphdkaz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhiwuduotai.top/Article/details/gtdeqnlsjp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gtdaojbaoh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zdqjudy.top/Article/details/gttvlazqxk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfnosunw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtdliytgpv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gtlftzluta.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gtogmzoqyx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gtwictoqog.html

Go:   slices.Sort(arr)
来源：http://dali.svipenyu.cn/Article/details/gtaylxrdvx.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gtmnoujtxa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jyoumei.cn/Article/details/gtpwzgisds.html

[N03] 快速排序（分治示例）
来源：http://dali.redwolf501.top/Article/details/gtwhizjvlm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgfzy.top/Article/details/gtomqugzfn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.bjfxy.top/Article/details/gtakzouwya.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnqzz.top/Article/details/gtkkkejwaq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gtnelkfysd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.andypj.xyz/Article/details/gtcvthbjrh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.birdmap.top/Article/details/gtevbirvyy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tianlin.xyz/Article/details/gtzrdnzvdo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuxming.cn/Article/details/gthuwxflag.html

[N04] 斐波那契数列
来源：http://dali.316326.xyz/Article/details/gtdedtmivq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gthrdvcpvz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cucudq.cn/Article/details/gtntbdomdo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gtrahtohkz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtzvcbqkjs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tanke756.top/Article/details/gthkcatazj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfapdmxy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gtjpypnxmf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gtvoeqmscn.html

[N05] 最大公约数
来源：http://dali.zdqjudy.top/Article/details/gtyrsozred.html

Py:   math.gcd(a, b)
来源：http://dali.yvedp.cn/Article/details/gtfqbrxjhl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hywenlv.cn/Article/details/gtsdgjqqzi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gtovclzdoq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gtcsfhrgtz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pengpengdd.cyou/Article/details/gtysfjnrps.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sufxvd.cn/Article/details/gtnoxrnsrf.html

Ruby: a.gcd(b)
来源：http://dali.aibaodan.cn/Article/details/gtsyqussvj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.bjfxy.top/Article/details/gtgnghrkwo.html

[N06] 判断回文字符串
来源：http://dali.guannengcc.top/Article/details/gtqyoeaetc.html

Py:   s == s[::-1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgmepzia.html

PHP:  $s === strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gtongzfajk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtarwlcfmq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtfzgcyncm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.svipenyu.cn/Article/details/gtcxzkqplh.html

Go:   // 双指针从两端比较
来源：http://dali.daria6918.cn/Article/details/gtfxhfxynv.html

Ruby: s == s.reverse
来源：http://dali.aibaodan.cn/Article/details/gtixkyvznm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aibaodan.cn/Article/details/gtjjllablf.html

[N07] 两数之和（返回下标）
来源：http://dali.kuanghao11.cn/Article/details/gtvejzoiym.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258888.top/Article/details/gtniygrsft.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yuxming.cn/Article/details/gtqpsmnatu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xziqi.cn/Article/details/gttpzkjxes.html

TS:   // 手写 Map<string, number>
来源：http://dali.redwolf501.top/Article/details/gtuxmewpjo.html

Java: // 手写 HashMap
来源：http://dali.yuxming.cn/Article/details/gtushipeux.html

Go:   // 手写 map[int]int
来源：http://dali.hnxiangtu.top/Article/details/gtsiiejdac.html

Ruby: // 手写 Hash
来源：http://dali.sysykeji.top/Article/details/gtrnkxcolm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sxryk.cn/Article/details/gtmqqcfyvq.html

[N08] 生成全排列
来源：http://dali.meibo888.top/Article/details/gtlsykhnqx.html

Py:   itertools.permutations(arr)
来源：http://dali.aibaodan.cn/Article/details/gtwixsmlfr.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangtech.top/Article/details/gtjngqjcsm.html

JS:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gthqhifbce.html

TS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtllajsert.html

Java: // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtuexxvmgp.html

Go:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtdanctxyu.html

Ruby: arr.permutation.to_a
来源：http://dali.cheryme.top/Article/details/gtqzcxyewa.html

C#:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtxppkrgpw.html

[N09] 栈与队列
来源：http://dali.ydzc1.top/Article/details/gtswsrayeg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zdqjudy.top/Article/details/gthpsserfq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gtyewikmjg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtfemjlzib.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hammf.cn/Article/details/gtjuovxrzc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gtwfjqbqit.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jianghu66.top/Article/details/gtcgwwqzvv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gtmuiisdql.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.316326.xyz/Article/details/gtoqrdjdrb.html

[N10] 链表节点定义
来源：http://dali.yj20258888.top/Article/details/gtxoslgoga.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yvedp.cn/Article/details/gtmohfgglo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.bjfxy.top/Article/details/gtsgncmlup.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj202588.top/Article/details/gtmauhdgsp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sweek.top/Article/details/gtqitskios.html

Java: class Node { int v; Node next; }
来源：http://dali.gogol.net.cn/Article/details/gtyttodmfq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.mhx1999.top/Article/details/gtzfhepzia.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxinkj.top/Article/details/gtbidsrvii.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sysykeji.top/Article/details/gttfcxooum.html

[N11] 二叉树中序遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtlsyvnfmz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.birdmap.top/Article/details/gtxmmqibmj.html

PHP:  // 手写递归函数
来源：http://dali.ydzc1.top/Article/details/gtowkumwqr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gtovrdklff.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gtexjseysl.html

Java: // 手写递归
来源：http://dali.havefunace.top/Article/details/gtzfiuciyk.html

Go:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gtrywdfkon.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.9152youxi.cn/Article/details/gtulmwubeu.html

C#:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtalguuzon.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yonumen.top/Article/details/gtdmafmdmc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hywenlv.cn/Article/details/gtpwdrclan.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aibaodan.cn/Article/details/gtfpulwymv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gthlvmqsiw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gtmlffnybj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gtyhknvfog.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hnqzz.top/Article/details/gtebudspyl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenlongwang.top/Article/details/gtcrwbskzq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gtjbzacbys.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtfphhlcai.html

O. 并发与异步
来源：http://dali.chenjidiqi.icu/Article/details/gtriikazpa.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtfhvptlar.html

[O01] 启动一个线程
来源：http://dali.jianghu66.top/Article/details/gtmmsnzscz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenzaomai.com/Article/details/gtlwyyabaa.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.316326.xyz/Article/details/gthzdigzfx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnxiangtu.top/Article/details/gtiaagjawh.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gtkpulqdhn.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgufenzy.top/Article/details/gtyxghbdcz.html

Go:   go f()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhewiqlr.html

Ruby: Thread.new { f }
来源：http://dali.yuanzhike.top/Article/details/gtxwmmngtb.html

C#:   Task.Run(() => F());
来源：http://dali.iojbl.cn/Article/details/gtpcxdlttf.html

[O02] 使用线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpscurmf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gotoacloud.top/Article/details/gtkuijesxe.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenzaomai.com/Article/details/gtjslcvqkf.html

JS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gtnhjznyxw.html

TS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gttqslxzwo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.birdmap.top/Article/details/gttwsrjeej.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.haohaochexian.top/Article/details/gtcdrmuamq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aibaodan.cn/Article/details/gtzqjkhrhb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xziqi.cn/Article/details/gtrgibdlbx.html

[O03] 加锁保护共享数据
来源：http://dali.aizwys.cn/Article/details/gtarumyggb.html

Py:   with lock: shared += 1
来源：http://dali.xziqi.cn/Article/details/gtlxwdrcgq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jiagoushi.top/Article/details/gtfmgndqfp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dashuyun.cn/Article/details/gtxsoaamde.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gtmjafrfuv.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gtxnekfpky.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinqigufen.top/Article/details/gtociigngc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.quarkkingdee.top/Article/details/gtamjjlqnp.html

C#:   lock (gate) { shared++; }
来源：http://dali.shuidangran.top/Article/details/gtzlknbiot.html

[O04] 定义异步函数并等待
来源：http://dali.aibaodan.cn/Article/details/gtrucbcigc.html

Py:   async def f():⏎    await g()
来源：http://dali.xuanzx.com/Article/details/gtpinezctm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhoulong.xyz/Article/details/gtslihfwaw.html

JS:   async function f() { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtsenfhfmw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.aizwys.cn/Article/details/gtzubksylf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jyoumei.cn/Article/details/gtdalfpnwo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sysykeji.top/Article/details/gtacdkjuxs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuanzx.com/Article/details/gtdoewbern.html

C#:   async Task F() { await G(); }
来源：http://dali.svipenyu.cn/Article/details/gtcexxctux.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuanzhike.top/Article/details/gthxoydqif.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtewxpvzpj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nwbrower.top/Article/details/gtqpyjpzdg.html

JS:   await Promise.all(tasks)
来源：http://dali.yuxming.cn/Article/details/gtjqoqjchf.html

TS:   await Promise.all(tasks)
来源：http://dali.zhixingplan.top/Article/details/gtmsqfsiao.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aibaodan.cn/Article/details/gtxikgjjnc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258888.top/Article/details/gtjckkwnri.html

Ruby: threads.map(&:join)
来源：http://dali.jianghu66.top/Article/details/gtazsvrary.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.haohaochexian.top/Article/details/gtsivipcxq.html

[O06] 使用进程池
来源：http://dali.tian-w.cn/Article/details/gtckhvmhxb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258888.top/Article/details/gtdbclfpwo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shuidangran.top/Article/details/gtuisoehee.html

JS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gtdsopkqmm.html

TS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gtwbnffrua.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aizwys.cn/Article/details/gtzdhagyvp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ehwqpu.com/Article/details/gtihywvzdk.html

Ruby: // fork 块
来源：http://dali.cqqwz.cn/Article/details/gtbmakrahu.html

C#:   Parallel.For
来源：http://dali.smart0.xyz/Article/details/gtvvarixxs.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtrobpxdqg.html

P. 常用工具函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbuhbqaav.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtjjzwlzlm.html

[P01] 生成 UUID
来源：http://dali.vqdsnc.cn/Article/details/gtkotbtfhl.html

Py:   str(uuid.uuid4())
来源：http://dali.sysykeji.top/Article/details/gtezwuwtcp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxuanxn.top/Article/details/gtnmigvghf.html

JS:   crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gtvexdcxhd.html

TS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gtgpbexbru.html

Java: UUID.randomUUID().toString()
来源：http://dali.sysykeji.top/Article/details/gtzwdecimw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zycfv.cn/Article/details/gtvskkwbqv.html

Ruby: SecureRandom.uuid
来源：http://dali.hammf.cn/Article/details/gtlvxioslk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ybcxt.top/Article/details/gtxhvicltt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tanke756.top/Article/details/gtwimztkvs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shangyingyoupin.top/Article/details/gticvzduwq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cqqwz.cn/Article/details/gtujradhhs.html


<!-- 参考信息 -->