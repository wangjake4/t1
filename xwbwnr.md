代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shangyingyoupin.top/Article/details/gtrtwrttcd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jianghu66.top/Article/details/gtyejghpto.html

[L05] 上传文件（multipart）
来源：http://dali.sweek.top/Article/details/gtfgmuyomb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuetiantiany.cn/Article/details/gtlmgjhmkw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ehwqpu.com/Article/details/gtnyujzwrf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gtmlxidtwo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gtuylhbeem.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuanzhike.top/Article/details/gtoojtmybp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhoulong.xyz/Article/details/gtaswdzlrp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hywenlv.cn/Article/details/gtkbymelxj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ivvv.top/Article/details/gtezeyiuvl.html

[L06] 解析响应为 JSON
来源：http://dali.zhoulong.xyz/Article/details/gtgxztbldb.html

Py:   resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtksaygmfl.html

PHP:  json_decode($body, true);
来源：http://dali.yongpay.top/Article/details/gtkdqwsrbf.html

JS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtnryuuupw.html

TS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gttxbcrcku.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtbxjdfnvv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hysaishi.cn/Article/details/gtazsivjrk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigufen.top/Article/details/gtkcolxeuy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjrlknjh.html

[L07] 处理 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gtrdnbbnvi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pycfn.com/Article/details/gtszxtqorf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cqqwz.cn/Article/details/gtitrdssxu.html

JS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtgxwvbial.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllgjchih.html

Java: resp.statusCode()
来源：http://dali.gaohongyu789.top/Article/details/gtydfmhoxk.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gtpzjtdxvd.html

Ruby: resp.code.to_i
来源：http://dali.hysaishi.cn/Article/details/gtrccaccki.html

C#:   (int)resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gtjqyxjxmx.html

[L08] 并发请求多个地址
来源：http://dali.cdnleiting.top/Article/details/gtmojtiwfw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxinkj.top/Article/details/gtmeuumdjl.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwkubqkq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtbhkkcwzk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtpfrcdcxa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guowangkeji.top/Article/details/gtnxmqwocl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cdnleiting.top/Article/details/gtnniinfel.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hysaishi.cn/Article/details/gtoccjjaoe.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sufxvd.cn/Article/details/gtfaduylwi.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gthhkxptmu.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj20258.top/Article/details/gtzfhshfur.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtontmiisr.html

[M01] 读取命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtyvtjhfmw.html

Py:   sys.argv[1:]
来源：http://dali.xuanzx.com/Article/details/gtbaolmupd.html

PHP:  $argv;  $argc;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphrdcrkl.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gtrrpgbbbs.html

TS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gtunkvsywi.html

Java: args 数组（main 方法参数）
来源：http://dali.yj202588.top/Article/details/gtepjxhsof.html

Go:   os.Args[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtszsisgdr.html

Ruby: ARGV
来源：http://dali.jyoumei.cn/Article/details/gthbxmlmop.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gtnydzvwuz.html

[M02] 读取环境变量
来源：http://dali.gaohongyu789.top/Article/details/gthvqerezw.html

Py:   os.environ.get("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtpddluojm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gtjeyifxni.html

JS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gtwupgrudl.html

TS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gtkhpaafcn.html

Java: System.getenv("HOME")
来源：http://dali.pycfn.com/Article/details/gtyixggfts.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrwmbuhc.html

Ruby: ENV["HOME"]
来源：http://dali.aibaodan.cn/Article/details/gtyzdewjel.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtqfjchzxe.html

[M03] 执行外部命令
来源：http://dali.shzxlz.cn/Article/details/gtbvfdrcut.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sufxvd.cn/Article/details/gtdpxcewzk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xinyue.icu/Article/details/gtlzbwqque.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gtsovlsjxr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gtmlaihydd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnqzz.top/Article/details/gtodoubtyr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokxlzjci.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchrvzmyl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxuanxn.top/Article/details/gtpykkufnt.html

[M04] 获取当前工作目录
来源：http://dali.yangfankeji.com/Article/details/gtzbrgesda.html

Py:   os.getcwd()
来源：http://dali.ybcxt.top/Article/details/gtzyizrfoe.html

PHP:  getcwd();
来源：http://dali.andypj.xyz/Article/details/gtdzosmjfl.html

JS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gttzxqolzc.html

TS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gtkrsetflj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuetiantiany.cn/Article/details/gtbnrwjzig.html

Go:   os.Getwd()
来源：http://dali.ehwqpu.com/Article/details/gtoscdjykn.html

Ruby: Dir.pwd
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgasbydxr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dashuyun.cn/Article/details/gtxqkxwkiq.html

[M05] 设置退出码
来源：http://dali.shuidangran.top/Article/details/gtdloonzlv.html

Py:   sys.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtwijyrjxp.html

PHP:  exit(1);
来源：http://dali.daria6918.cn/Article/details/gtlggmzpwr.html

JS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtojnurccz.html

TS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtcurcwpuy.html

Java: System.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtqpodvtex.html

Go:   os.Exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtnwypqiqx.html

Ruby: exit 1
来源：http://dali.gotoacloud.top/Article/details/gtjwyajslw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuxming.cn/Article/details/gtsflaagmc.html

[M06] 向标准错误输出
来源：http://dali.shangyingyoupin.top/Article/details/gtbrkznbdj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gthwnozqih.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuanzx.com/Article/details/gtdilvfody.html

JS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtknrvecff.html

TS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gthlyhkskg.html

Java: System.err.println("err")
来源：http://dali.yanxiufei.cn/Article/details/gtctikuqae.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgfzy.top/Article/details/gtolcfeaud.html

Ruby: warn "err"
来源：http://dali.quarkkingdee.top/Article/details/gtbhfksjoe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sufxvd.cn/Article/details/gtqjnwtzzn.html

[M07] 判断是否为主入口
来源：http://dali.havefunace.top/Article/details/gtjtalxbtc.html

Py:   if __name__ == "__main__":
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgillczij.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj202588.top/Article/details/gtjmcbqyzf.html

JS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gtrgqyityb.html

TS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtcqczwlvd.html

Java: public static void main(String[] args)
来源：http://dali.sweek.top/Article/details/gtjdgosuxt.html

Go:   func main()
来源：http://dali.chenzaomai.com/Article/details/gtgeumnkbd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gaohongyu789.top/Article/details/gtdwcycrkl.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvvjyyzd.html

[M08] 获取系统与运行时信息
来源：http://dali.birdmap.top/Article/details/gtyllrbhtx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hysaishi.cn/Article/details/gtwdarptmc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xylfe.cn/Article/details/gtinmgwgny.html

JS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gtocikjhhm.html

TS:   process.platform;  process.version
来源：http://dali.haohaochexian.top/Article/details/gtlzqqilyy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzinsatie.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhengqikj.top/Article/details/gtgccwnpjt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.andypj.xyz/Article/details/gtmofzjrqj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.316326.xyz/Article/details/gthejfxtjc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtsjudpgrp.html

N. 数据结构与算法
来源：http://dali.pengpengdd.cyou/Article/details/gteugxdbfa.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtbasckgha.html

[N01] 二分查找（有序数组）
来源：http://dali.0kj1m.cn/Article/details/gtfcxtvcoh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtbjwerfgy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtvmefhztk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jiagoushi.top/Article/details/gtfepwgvcq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gtesehuaba.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtljsjknlt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtogoonvjq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.haohaochexian.top/Article/details/gtlivupjag.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtfrgxufjg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangshuangyany.cn/Article/details/gtgzuoviwi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gtgxavnrng.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuxming.cn/Article/details/gtzhwxvbnj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gthetfopcx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtgytliwqd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guannengcc.top/Article/details/gtsesmernc.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gtokxetefi.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gtoaqvuuyu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shzxlz.cn/Article/details/gtzcqjbshm.html

[N03] 快速排序（分治示例）
来源：http://dali.yj20258888.top/Article/details/gtxnxqtlub.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gtaydigobo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.andypj.xyz/Article/details/gtasoozutb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjicvspnj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gtortbpcix.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gtwdkydvhs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.vqdsnc.cn/Article/details/gtkerqxyqc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jqgfzy.top/Article/details/gtizbgeeeo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ppjwa.cn/Article/details/gtaneyblta.html

[N04] 斐波那契数列
来源：http://dali.gzhubu.top/Article/details/gterorgaev.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gtriaylfiy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zycfv.cn/Article/details/gtfgsgubmd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gtkljlkytx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gtacnanmky.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.birdmap.top/Article/details/gtgbwblrbq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ppjwa.cn/Article/details/gtjwvegjpm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guannengcc.top/Article/details/gtxalqkonu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiglegriq.html

[N05] 最大公约数
来源：http://dali.mhx1999.top/Article/details/gtucftykbw.html

Py:   math.gcd(a, b)
来源：http://dali.cashguo.top/Article/details/gtzeatswrx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yvedp.cn/Article/details/gtilalzljv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.c1oappe.top/Article/details/gtvtkplubu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvhgoxutv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghetzybk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shuidangran.top/Article/details/gtezfkubvp.html

Ruby: a.gcd(b)
来源：http://dali.zhixingplan.top/Article/details/gtsoftqiss.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigufen.top/Article/details/gtfqynchrl.html

[N06] 判断回文字符串
来源：http://dali.fengsongda.top/Article/details/gtzuqngkct.html

Py:   s == s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtdbnvsjuw.html

PHP:  $s === strrev($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaowogzmw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtwwbsixig.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtxweenjvb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aizwys.cn/Article/details/gtdhogrkcg.html

Go:   // 双指针从两端比较
来源：http://dali.fengsongda.top/Article/details/gtmdxwcuyd.html

Ruby: s == s.reverse
来源：http://dali.316326.xyz/Article/details/gtxncabpzk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gtadrwscah.html

[N07] 两数之和（返回下标）
来源：http://dali.cdnleiting.top/Article/details/gtfqaqnzik.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dianchejie.cn/Article/details/gtwebdzfog.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj202588.top/Article/details/gtczzoxagm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.kuanghao11.cn/Article/details/gtpreeqdlp.html

TS:   // 手写 Map<string, number>
来源：http://dali.shzxlz.cn/Article/details/gtntlpxyjv.html

Java: // 手写 HashMap
来源：http://dali.pycfn.com/Article/details/gtvzvsfikt.html

Go:   // 手写 map[int]int
来源：http://dali.bjfxy.top/Article/details/gtufzpkqpa.html

Ruby: // 手写 Hash
来源：http://dali.yj202588.top/Article/details/gtzopkofef.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gtjxaayygt.html

[N08] 生成全排列
来源：http://dali.vqdsnc.cn/Article/details/gtjfsdllhq.html

Py:   itertools.permutations(arr)
来源：http://dali.hfpthk.cn/Article/details/gtftgyaomo.html

PHP:  // 手写递归交换
来源：http://dali.gotoacloud.top/Article/details/gtmootpjrt.html

JS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtsfpebpua.html

TS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtshuvoirz.html

Java: // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtjhovtkpd.html

Go:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtkjcxstoj.html

Ruby: arr.permutation.to_a
来源：http://dali.yvedp.cn/Article/details/gtbozbubgr.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtditakvsu.html

[N09] 栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtquqqowxj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtsweedigi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtwjgfnbgm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagcgosxd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangshuangyany.cn/Article/details/gtuafcapct.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gtfotqtfvq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gaohongyu789.top/Article/details/gtreqqdvcm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.fzhhl.top/Article/details/gtrmkjcpen.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrtqubqi.html

[N10] 链表节点定义
来源：http://dali.iojbl.cn/Article/details/gtpizxvlfi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hongshengwenyu.top/Article/details/gtydenhilj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gtyfpekhup.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guannengcc.top/Article/details/gtywpcblcy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangdashe.top/Article/details/gtgznbejso.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258888.top/Article/details/gtxabnmwwh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aibaodan.cn/Article/details/gtjbqmfwdo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxuanxn.top/Article/details/gtgkhrbzcp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.haohaochexian.top/Article/details/gtmxftjipq.html

[N11] 二叉树中序遍历
来源：http://dali.gaohongyu789.top/Article/details/gtmphkadmp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sufxvd.cn/Article/details/gtoqyldgti.html

PHP:  // 手写递归函数
来源：http://dali.sxryk.cn/Article/details/gtvklvflet.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pengpengdd.cyou/Article/details/gtlyxvnvrh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gtwnnadhuc.html

Java: // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gtrrkiyafc.html

Go:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtmypbntfh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.snrcjt.cn/Article/details/gtslstyeze.html

C#:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtajibzzlc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj202588.top/Article/details/gtbsxqcnaj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhengqikj.top/Article/details/gtukdoasdy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxpcpzmv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gtqhqyqkty.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gtdjjfitzo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gttdekjfrd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nwbrower.top/Article/details/gtnwdlniij.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sysykeji.top/Article/details/gtiaexcbad.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gtthwzgogb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtdpknlchp.html

O. 并发与异步
来源：http://dali.jianghu66.top/Article/details/gtjjilargv.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtljaukcsw.html

[O01] 启动一个线程
来源：http://dali.yj202588.top/Article/details/gtjqyghprn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangshuangyany.cn/Article/details/gtgoawiiab.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jianghu66.top/Article/details/gteskmfmup.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hammf.cn/Article/details/gtweoacmty.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gtagbdomfe.html

Java: new Thread(() -> f()).start()
来源：http://dali.gotoacloud.top/Article/details/gtyxaidxvf.html

Go:   go f()
来源：http://dali.dianchejie.cn/Article/details/gtpvmparcs.html

Ruby: Thread.new { f }
来源：http://dali.wangdashe.top/Article/details/gtyfjwotus.html

C#:   Task.Run(() => F());
来源：http://dali.cqqwz.cn/Article/details/gttbiepdgv.html

[O02] 使用线程池
来源：http://dali.dianchejie.cn/Article/details/gtqsosojim.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.andypj.xyz/Article/details/gtuwhyqikx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sweek.top/Article/details/gtaikpvqhi.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtkijhdaaz.html

TS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylviylih.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258888.top/Article/details/gtfbjueymj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cqqwz.cn/Article/details/gtmqmmnspw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jyoumei.cn/Article/details/gthgdpmyts.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hongshengwenyu.top/Article/details/gtveznvbbq.html

[O03] 加锁保护共享数据
来源：http://dali.hongshengwenyu.top/Article/details/gtewfglrrl.html

Py:   with lock: shared += 1
来源：http://dali.zdqjudy.top/Article/details/gtxarrzuee.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.svipenyu.cn/Article/details/gtmtkfhjhq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tanke756.top/Article/details/gtnrmvekzv.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gtannnugfm.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gtxwpwjsep.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pycfn.com/Article/details/gtoduzudwf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj202588.top/Article/details/gtbrhtgghv.html

C#:   lock (gate) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gtwekgania.html

[O04] 定义异步函数并等待
来源：http://dali.guannengcc.top/Article/details/gtbpryfjsa.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxinkj.top/Article/details/gtsvbpijon.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ivvv.top/Article/details/gtvzqpjhae.html

JS:   async function f() { await g(); }
来源：http://dali.jianghu66.top/Article/details/gtflujuehl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gteshtghpo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nanxinkj.top/Article/details/gtctudkjmr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hywenlv.cn/Article/details/gtdzdzjqbz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.svipenyu.cn/Article/details/gtrzkpphoz.html

C#:   async Task F() { await G(); }
来源：http://dali.shzxlz.cn/Article/details/gtbbwacjjo.html

[O05] 并发执行并等待全部完成
来源：http://dali.hammf.cn/Article/details/gthiunczdq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shzxlz.cn/Article/details/gthvfihnro.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shuidangran.top/Article/details/gtyngosutt.html

JS:   await Promise.all(tasks)
来源：http://dali.zhongyouzk.top/Article/details/gtdpgjwzcw.html

TS:   await Promise.all(tasks)
来源：http://dali.yanxiufei.cn/Article/details/gtsxfayoce.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigfzy.top/Article/details/gtlowpbenw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nanxinkj.top/Article/details/gtefmyduxs.html

Ruby: threads.map(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtfdynzkns.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cheryme.top/Article/details/gtotjuhiri.html

[O06] 使用进程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtdayyqmqz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zycfv.cn/Article/details/gtaguvkwkx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hammf.cn/Article/details/gtjgmrwhbh.html

JS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gtzczyefru.html

TS:   // child_process / cluster 模块
来源：http://dali.aibaodan.cn/Article/details/gtjviyyiff.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.dianchejie.cn/Article/details/gthfsnfmfg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.vqdsnc.cn/Article/details/gtzjxarnhh.html

Ruby: // fork 块
来源：http://dali.guannengcc.top/Article/details/gtghgbkvmy.html

C#:   Parallel.For
来源：http://dali.yj20258.top/Article/details/gtbpceyfxy.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtsyttgcsr.html

P. 常用工具函数
来源：http://dali.wangdashe.top/Article/details/gtakgsaofa.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtjqukzlzu.html

[P01] 生成 UUID
来源：http://dali.zhongyouzk.top/Article/details/gtpyfubsdn.html

Py:   str(uuid.uuid4())
来源：http://dali.jinqigufen.top/Article/details/gtysetwprq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fzhhl.top/Article/details/gtmjgzckfg.html

JS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gtwqhwsynr.html

TS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gtcldvojig.html

Java: UUID.randomUUID().toString()
来源：http://dali.zdqjudy.top/Article/details/gtaoedzzbh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yonumen.top/Article/details/gthnfbrxpe.html

Ruby: SecureRandom.uuid
来源：http://dali.meibo888.top/Article/details/gttfyyqtvv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tianlin.xyz/Article/details/gttjniqxci.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daria6918.cn/Article/details/gtoklkbwth.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gtcxanvwwe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yangfankeji.com/Article/details/gtjkbqixam.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jianghu66.top/Article/details/gtnntujhqt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.quarkkingdee.top/Article/details/gtmgqumbnn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtsanrjgtg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenlongwang.top/Article/details/gtbsxcsyii.html


<!-- 参考信息 -->