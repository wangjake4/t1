代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ehwqpu.com/Article/details/gtdprloqsc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhixingplan.top/Article/details/gtaglbllmx.html

[L05] 上传文件（multipart）
来源：http://dali.0kj1m.cn/Article/details/gtiheimebk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhoulong.xyz/Article/details/gtxiajphtq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchazsojy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gthywogtxh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gtyryrbhje.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxuanxn.top/Article/details/gtwwqnrhwm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shzxlz.cn/Article/details/gtnrqoicel.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.wangdashe.top/Article/details/gtmueklhmt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xylfe.cn/Article/details/gtqepwerbb.html

[L06] 解析响应为 JSON
来源：http://dali.quarkkingdee.top/Article/details/gtrlvapdur.html

Py:   resp.json()
来源：http://dali.cucudq.cn/Article/details/gtcqzboeev.html

PHP:  json_decode($body, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtyesikjmm.html

JS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtawbanert.html

TS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gtzzviomib.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtrwrtehku.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhiwuduotai.top/Article/details/gtgwxubfah.html

Ruby: JSON.parse(resp.body)
来源：http://dali.pycfn.com/Article/details/gtntkibfel.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cucudq.cn/Article/details/gtuoamtuqv.html

[L07] 处理 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gtlkejmqeh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuetiantiany.cn/Article/details/gtntgbwplc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sysykeji.top/Article/details/gtlrlrrzmt.html

JS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtfmvaobzs.html

TS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gtnvjogtqp.html

Java: resp.statusCode()
来源：http://dali.yj202588.top/Article/details/gtmogmezxh.html

Go:   resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gtvamhdfrk.html

Ruby: resp.code.to_i
来源：http://dali.shzxlz.cn/Article/details/gterjracct.html

C#:   (int)resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtjgglwqmt.html

[L08] 并发请求多个地址
来源：http://dali.wangdashe.top/Article/details/gtpajnxtfw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xylfe.cn/Article/details/gtddoydihl.html

PHP:  curl_multi_init() 系列
来源：http://dali.cqqwz.cn/Article/details/gtaeqnutur.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gtkoitlloq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gtrdsjqcyr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gthruiyube.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnxiangtu.top/Article/details/gtedkhltna.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.0kj1m.cn/Article/details/gtlmpdpvil.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxinkj.top/Article/details/gtsuaruxln.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gttuqswixq.html

M. 命令行 / 进程 / 环境
来源：http://dali.svipenyu.cn/Article/details/gtunrzbwbv.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gttwtdwvaq.html

[M01] 读取命令行参数
来源：http://dali.yuxming.cn/Article/details/gttwsjrera.html

Py:   sys.argv[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtqwnxuoux.html

PHP:  $argv;  $argc;
来源：http://dali.sxryk.cn/Article/details/gtbikvigpy.html

JS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtorqjtnwm.html

TS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtufodijeq.html

Java: args 数组（main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gtscvkywjv.html

Go:   os.Args[1:]
来源：http://dali.cdnleiting.top/Article/details/gtnqbimxwz.html

Ruby: ARGV
来源：http://dali.haohaochexian.top/Article/details/gtpsjdnoic.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gtyxtncjks.html

[M02] 读取环境变量
来源：http://dali.yonumen.top/Article/details/gtxpgnidtq.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtmcwjoaml.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gtmagzdbah.html

JS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gtxihwitoq.html

TS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtibwturrn.html

Java: System.getenv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtavfsgjtu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtfqrxjkqy.html

Ruby: ENV["HOME"]
来源：http://dali.xuanzx.com/Article/details/gtfqxmvrdk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yueranfly.top/Article/details/gtanjraayz.html

[M03] 执行外部命令
来源：http://dali.zycfv.cn/Article/details/gtpzdcflct.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtotpldyzw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.birdmap.top/Article/details/gtmemvfimf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtapjlmfor.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gtjtsazapf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.0kj1m.cn/Article/details/gtvqrrltsr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhiwuduotai.top/Article/details/gtlshwrhim.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhhfeguy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xuanzx.com/Article/details/gtlkzgcipw.html

[M04] 获取当前工作目录
来源：http://dali.snrcjt.cn/Article/details/gtzqzmupnn.html

Py:   os.getcwd()
来源：http://dali.nanxinkj.top/Article/details/gtcswdjanx.html

PHP:  getcwd();
来源：http://dali.daria6918.cn/Article/details/gtbufgwblh.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gtphhammtc.html

TS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gtoryjsfzd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nwbrower.top/Article/details/gtukznrtmc.html

Go:   os.Getwd()
来源：http://dali.cheryme.top/Article/details/gtqzlktpqg.html

Ruby: Dir.pwd
来源：http://dali.xylfe.cn/Article/details/gtgxafgnqr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenjidiqi.icu/Article/details/gtsjewrzdw.html

[M05] 设置退出码
来源：http://dali.shangyingyoupin.top/Article/details/gtbxjlowwi.html

Py:   sys.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtxzxerfgh.html

PHP:  exit(1);
来源：http://dali.kuanghao11.cn/Article/details/gtltkropon.html

JS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtnivexvwg.html

TS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtawktmelb.html

Java: System.exit(1)
来源：http://dali.pycfn.com/Article/details/gtrfxuceoj.html

Go:   os.Exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtxehiwmgu.html

Ruby: exit 1
来源：http://dali.yuanzhike.top/Article/details/gtbfigsnqj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.0kj1m.cn/Article/details/gtkxbvmndg.html

[M06] 向标准错误输出
来源：http://dali.tianlin.xyz/Article/details/gtjoxepuod.html

Py:   print("err", file=sys.stderr)
来源：http://dali.havefunace.top/Article/details/gtmuuuenwc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guannengcc.top/Article/details/gtzzdydzim.html

JS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gtnnqxqwum.html

TS:   console.error("err")
来源：http://dali.smart0.xyz/Article/details/gtposkddws.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gtxusvkhio.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuanzhike.top/Article/details/gtnjhratwr.html

Ruby: warn "err"
来源：http://dali.0kj1m.cn/Article/details/gtnfnaarzm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sweek.top/Article/details/gthxkjwvyb.html

[M07] 判断是否为主入口
来源：http://dali.sysykeji.top/Article/details/gteetssjos.html

Py:   if __name__ == "__main__":
来源：http://dali.havefunace.top/Article/details/gtwwnagtva.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ehwqpu.com/Article/details/gttdewwxmd.html

JS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtrelzpryh.html

TS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gtuexnnzth.html

Java: public static void main(String[] args)
来源：http://dali.yongpay.top/Article/details/gtwbwmafjn.html

Go:   func main()
来源：http://dali.sysykeji.top/Article/details/gtrryfvcya.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ppjwa.cn/Article/details/gtroefccjn.html

C#:   static void Main(string[] args)
来源：http://dali.shzxlz.cn/Article/details/gtpwricrlb.html

[M08] 获取系统与运行时信息
来源：http://dali.cucudq.cn/Article/details/gtfzdzxzdn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigfzy.top/Article/details/gtzijfjhud.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hywenlv.cn/Article/details/gtuojitwxu.html

JS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gtbpyyknha.html

TS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gtfxiewraa.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhiwuduotai.top/Article/details/gtnukvwvel.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqldirbz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xuetiantiany.cn/Article/details/gtnvrqqfoi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.c1oappe.top/Article/details/gtgkycodjl.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtwywfeais.html

N. 数据结构与算法
来源：http://dali.chenlongwang.top/Article/details/gtfvmgtuhr.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtzrjusaha.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxuanxn.top/Article/details/gtwxeajetk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtaerfwenx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gtmsplwnde.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gtbjjnfcfo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gthizhivnt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtkrrxbpeb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtzggzpsiu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yangfankeji.com/Article/details/gtlekmexqa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtyyimilxx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guowangkeji.top/Article/details/gtvculiipe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gtfvtsmxme.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yvedp.cn/Article/details/gtgthqdtix.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gtejtxtsxo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtmaxptedp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.9152youxi.cn/Article/details/gtbpputibb.html

Go:   slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gtbibkmhad.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gtmrgbfzuu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ydzc1.top/Article/details/gtyigwkiey.html

[N03] 快速排序（分治示例）
来源：http://dali.haohaochexian.top/Article/details/gtrwodiaat.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gzhubu.top/Article/details/gtcswjgazd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfcbqgru.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gtyxcjxvgj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gttwlgtxjo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dianchejie.cn/Article/details/gtrpqjuosb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvwmqifl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ehwqpu.com/Article/details/gtqxxtnlbi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ehwqpu.com/Article/details/gtzqnlshbn.html

[N04] 斐波那契数列
来源：http://dali.ehwqpu.com/Article/details/gtufmkhefq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gtzinttaxl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gtjxamojwc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gtygitdgpg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtrwxoylhq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gtcwpvlcex.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hywenlv.cn/Article/details/gtuhecvsvs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gtfadcuamp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtkzomrtls.html

[N05] 最大公约数
来源：http://dali.chenjidiqi.icu/Article/details/gtbxfnpxke.html

Py:   math.gcd(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtiglujqnc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuanzx.com/Article/details/gtflkuvzcr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmbdcdgm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gtjhodimyj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.redwolf501.top/Article/details/gtcwkmfcgr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.redwolf501.top/Article/details/gtavaeaymq.html

Ruby: a.gcd(b)
来源：http://dali.daria6918.cn/Article/details/gtnjnbzsrc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgfzy.top/Article/details/gtzeiazkki.html

[N06] 判断回文字符串
来源：http://dali.cqqwz.cn/Article/details/gtpaplpdos.html

Py:   s == s[::-1]
来源：http://dali.nwbrower.top/Article/details/gtbjvpxfnn.html

PHP:  $s === strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gtdurpsquh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtpuhupdrp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gteldtcuhn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinghuilouyu.cn/Article/details/gtxyyeweeo.html

Go:   // 双指针从两端比较
来源：http://dali.jqgfzy.top/Article/details/gtnwwdqics.html

Ruby: s == s.reverse
来源：http://dali.yangfankeji.com/Article/details/gtxqbmedio.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gtnhjhbqvd.html

[N07] 两数之和（返回下标）
来源：http://dali.jiagoushi.top/Article/details/gtpeqrwwxo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcuoehema.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.meibo888.top/Article/details/gtcfvpqdak.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangdashe.top/Article/details/gtqtdpkufx.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthlxxjdu.html

Java: // 手写 HashMap
来源：http://dali.hammf.cn/Article/details/gtptqhzrui.html

Go:   // 手写 map[int]int
来源：http://dali.yueranfly.top/Article/details/gtfwuvmlho.html

Ruby: // 手写 Hash
来源：http://dali.cucudq.cn/Article/details/gtkwaocwrs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hongshengwenyu.top/Article/details/gtcbpehfur.html

[N08] 生成全排列
来源：http://dali.jianghu66.top/Article/details/gtunnjkcgu.html

Py:   itertools.permutations(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gterfgulfk.html

PHP:  // 手写递归交换
来源：http://dali.birdmap.top/Article/details/gthjdukvgt.html

JS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtwgldfdty.html

TS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtcjqldttj.html

Java: // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnmtkmcf.html

Go:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtnfszwujm.html

Ruby: arr.permutation.to_a
来源：http://dali.316326.xyz/Article/details/gtibmhpbmz.html

C#:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtxljufrgw.html

[N09] 栈与队列
来源：http://dali.cheryme.top/Article/details/gtkrnflnab.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sufxvd.cn/Article/details/gtijoapqim.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xziqi.cn/Article/details/gtorngfngb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtpanavnir.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tianlin.xyz/Article/details/gtzflnxjpb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cashguo.top/Article/details/gtxaxyffdf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.meibo888.top/Article/details/gtekoiagik.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnwhieuz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenzaomai.com/Article/details/gtctvuasps.html

[N10] 链表节点定义
来源：http://dali.sxryk.cn/Article/details/gtvuwjqrch.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xziqi.cn/Article/details/gtgqomkdzh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jyoumei.cn/Article/details/gtjqbhnawq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dashuyun.cn/Article/details/gtouwejxvr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.bjfxy.top/Article/details/gtrlxnvqsa.html

Java: class Node { int v; Node next; }
来源：http://dali.shzxlz.cn/Article/details/gtqohxlroz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gtdvcwxfyd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258888.top/Article/details/gtfuyshnpm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tian-w.cn/Article/details/gttzbuvenm.html

[N11] 二叉树中序遍历
来源：http://dali.yj20258.top/Article/details/gtfofmwjyk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.9152youxi.cn/Article/details/gtlkirysjc.html

PHP:  // 手写递归函数
来源：http://dali.nanxinkj.top/Article/details/gtbpuenbrk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gtaschmrns.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gtfdstmxta.html

Java: // 手写递归
来源：http://dali.yj20258.top/Article/details/gtztfivmua.html

Go:   // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gtulqpxrbj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aibaodan.cn/Article/details/gtpnmeairi.html

C#:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtxajfdqos.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.quarkkingdee.top/Article/details/gtwubhalgj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xziqi.cn/Article/details/gtdkqijcti.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hammf.cn/Article/details/gtcncnngeu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gtdnhgwveg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.9152youxi.cn/Article/details/gtzphmlnzj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gtrydwzqsz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gtobslqoih.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nwbrower.top/Article/details/gttrgtkmvw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.redwolf501.top/Article/details/gtodcjqxfx.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtcwjoebpg.html

O. 并发与异步
来源：http://dali.ivvv.top/Article/details/gtqdxuopxh.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtrnpqnphz.html

[O01] 启动一个线程
来源：http://dali.haohaochexian.top/Article/details/gthnepejev.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tian-w.cn/Article/details/gtuzyjzjhv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cucudq.cn/Article/details/gtucusxwpc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hammf.cn/Article/details/gtxehioaif.html

TS:   // 同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gtedneywqg.html

Java: new Thread(() -> f()).start()
来源：http://dali.vqdsnc.cn/Article/details/gtdjbtjhsq.html

Go:   go f()
来源：http://dali.cheryme.top/Article/details/gtudxuvvnz.html

Ruby: Thread.new { f }
来源：http://dali.ivvv.top/Article/details/gtihporlvi.html

C#:   Task.Run(() => F());
来源：http://dali.zhiwuduotai.top/Article/details/gtdchajrie.html

[O02] 使用线程池
来源：http://dali.ehwqpu.com/Article/details/gtfsggsjst.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258888.top/Article/details/gtxyshdhnf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cqqwz.cn/Article/details/gtwcbhwxie.html

JS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoitjhcyu.html

TS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gtsvjaxcsv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yuanzhike.top/Article/details/gtjyotnzyg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zdqjudy.top/Article/details/gtwsbjnvqd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ivvv.top/Article/details/gthgpnccih.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigfzy.top/Article/details/gtbaynnlxm.html

[O03] 加锁保护共享数据
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpyqkznq.html

Py:   with lock: shared += 1
来源：http://dali.zycfv.cn/Article/details/gtmlvxynui.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aizwys.cn/Article/details/gtwtunffrl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgfzy.top/Article/details/gtydadzlob.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gtduimomtg.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbvuvgjy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hysaishi.cn/Article/details/gtbzxklgnd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangdashe.top/Article/details/gtxresnflf.html

C#:   lock (gate) { shared++; }
来源：http://dali.hammf.cn/Article/details/gtoxldzjtl.html

[O04] 定义异步函数并等待
来源：http://dali.zhengqikj.top/Article/details/gtsprnvsqo.html

Py:   async def f():⏎    await g()
来源：http://dali.shzxlz.cn/Article/details/gtmbjvzwna.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shuidangran.top/Article/details/gtozttzdyf.html

JS:   async function f() { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gtcynhgqbx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tanke756.top/Article/details/gtjqnptnoa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sxryk.cn/Article/details/gtytvpesre.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuetiantiany.cn/Article/details/gtoklsawnh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.bjfxy.top/Article/details/gtvwjbcyfh.html

C#:   async Task F() { await G(); }
来源：http://dali.haohaochexian.top/Article/details/gtructycju.html

[O05] 并发执行并等待全部完成
来源：http://dali.dashuyun.cn/Article/details/gtffzqtwhq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj20258.top/Article/details/gttslsbulw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.snrcjt.cn/Article/details/gtaettkbiy.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gtwbwejxpy.html

TS:   await Promise.all(tasks)
来源：http://dali.fengsongda.top/Article/details/gtvloexfqg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sxryk.cn/Article/details/gtaycmlaty.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhongyouzk.top/Article/details/gtmcxncyqp.html

Ruby: threads.map(&:join)
来源：http://dali.meibo888.top/Article/details/gtaxdogbfz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.316326.xyz/Article/details/gtfescqriy.html

[O06] 使用进程池
来源：http://dali.quarkkingdee.top/Article/details/gtkuegywoz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgfzy.top/Article/details/gtkpjokafx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yueranfly.top/Article/details/gtdpdxzllo.html

JS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gtjwzxmlhb.html

TS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gtpcdeemgj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.birdmap.top/Article/details/gtpwlbdrxn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tianlin.xyz/Article/details/gtaaymwqxm.html

Ruby: // fork 块
来源：http://dali.jqgfzy.top/Article/details/gtwwtzasbw.html

C#:   Parallel.For
来源：http://dali.feifeiyinyue.top/Article/details/gtniffmjuc.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtkruwrriq.html

P. 常用工具函数
来源：http://dali.fengsongda.top/Article/details/gtjqmmmplg.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtulwzfvpo.html

[P01] 生成 UUID
来源：http://dali.aibaodan.cn/Article/details/gtaqywfhpe.html

Py:   str(uuid.uuid4())
来源：http://dali.meibo888.top/Article/details/gtsexwnjkt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sweek.top/Article/details/gtbumumyau.html

JS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtadatstnt.html

TS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtxxkrfmxt.html

Java: UUID.randomUUID().toString()
来源：http://dali.kuanghao11.cn/Article/details/gtvuhlhont.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yangfankeji.com/Article/details/gtvsdcddjg.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigfzy.top/Article/details/gtbtoxkpgx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dianchejie.cn/Article/details/gtzkhpipxt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sysykeji.top/Article/details/gtjtzrlbrp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinghuilouyu.cn/Article/details/gtyyjabdyw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zdqjudy.top/Article/details/gtbyvpcbna.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnxiangtu.top/Article/details/gtbmadmfgh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuetiantiany.cn/Article/details/gtiiwvssks.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cucudq.cn/Article/details/gtlezxcpxg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hfpthk.cn/Article/details/gtnoaeeboe.html


<!-- 参考信息 -->