代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guowangkeji.top/Article/details/gtcijdnmod.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shuidangran.top/Article/details/gtflsoicwt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtbgnrzlwh.html

[L06] 解析响应为 JSON
来源：http://dali.yj202588.top/Article/details/gtnxblxyuf.html

Py:   resp.json()
来源：http://dali.ybcxt.top/Article/details/gtlqrfbdci.html

PHP:  json_decode($body, true);
来源：http://dali.chenzaomai.com/Article/details/gtqenbfomz.html

JS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtksqxogem.html

TS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gtvdwuwvse.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hammf.cn/Article/details/gtrztiosgh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgufenzy.top/Article/details/gtblnuvvre.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shangyingyoupin.top/Article/details/gtrzhnxsdy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gzhubu.top/Article/details/gtqnwlidoo.html

[L07] 处理 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gtudvidpxr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hongshengwenyu.top/Article/details/gthdaujgoe.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yonumen.top/Article/details/gtvqnhbrpv.html

JS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gtdyzsvyor.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gtmlgiscrp.html

Java: resp.statusCode()
来源：http://dali.xinyue.icu/Article/details/gtrlmkzsid.html

Go:   resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gtdsejpztm.html

Ruby: resp.code.to_i
来源：http://dali.haohaochexian.top/Article/details/gtclursmlp.html

C#:   (int)resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbeexdkz.html

[L08] 并发请求多个地址
来源：http://dali.cashguo.top/Article/details/gtziyqwcas.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yongpay.top/Article/details/gthugjzykm.html

PHP:  curl_multi_init() 系列
来源：http://dali.hongshengwenyu.top/Article/details/gtpjvwfesn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gtrpdbyeio.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gtsrfasevt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xziqi.cn/Article/details/gtgyottltj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuanzhike.top/Article/details/gtppkjmwjw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.haohaochexian.top/Article/details/gthatdozog.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gotoacloud.top/Article/details/gthrimchdt.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtcvjbehzg.html

M. 命令行 / 进程 / 环境
来源：http://dali.hfpthk.cn/Article/details/gtpwmxgsal.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtbvgcjftl.html

[M01] 读取命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gtiebdgnmc.html

Py:   sys.argv[1:]
来源：http://dali.yj20258888.top/Article/details/gtzsxidclg.html

PHP:  $argv;  $argc;
来源：http://dali.xziqi.cn/Article/details/gtgcfrmaxk.html

JS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gtwhdqkuyj.html

TS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gtgkbyvptl.html

Java: args 数组（main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gtnvdilius.html

Go:   os.Args[1:]
来源：http://dali.ehwqpu.com/Article/details/gtzzleladp.html

Ruby: ARGV
来源：http://dali.yuxming.cn/Article/details/gtzdcjyjwb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gtfjkpgvvc.html

[M02] 读取环境变量
来源：http://dali.daria6918.cn/Article/details/gtuvfqjdnx.html

Py:   os.environ.get("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtozqlqygn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gtqimxjsup.html

JS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gtbnwlhzkt.html

TS:   process.env.HOME
来源：http://dali.tanke756.top/Article/details/gtucrdgsng.html

Java: System.getenv("HOME")
来源：http://dali.cheryme.top/Article/details/gtadsfiskz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258.top/Article/details/gthazmanuo.html

Ruby: ENV["HOME"]
来源：http://dali.cheryme.top/Article/details/gtmceaevle.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtvgfmprtc.html

[M03] 执行外部命令
来源：http://dali.mhx1999.top/Article/details/gtaceibrhm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtuzbztcot.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cheryme.top/Article/details/gtkzhhdigv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigufen.top/Article/details/gtzeqgqmgn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtfknykbtt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tian-w.cn/Article/details/gtweogyoss.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigfzy.top/Article/details/gthncmiomd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fzhhl.top/Article/details/gtlhvrpbfs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.birdmap.top/Article/details/gtbxkxkene.html

[M04] 获取当前工作目录
来源：http://dali.316326.xyz/Article/details/gtnkkwgtxn.html

Py:   os.getcwd()
来源：http://dali.kuanghao11.cn/Article/details/gtyzasrpfq.html

PHP:  getcwd();
来源：http://dali.yuanzhike.top/Article/details/gtibplcvni.html

JS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gtcegzzuwy.html

TS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gtzfdgajul.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ybcxt.top/Article/details/gtpdetrdzo.html

Go:   os.Getwd()
来源：http://dali.dashuyun.cn/Article/details/gtlrvwronv.html

Ruby: Dir.pwd
来源：http://dali.yueranfly.top/Article/details/gtomrvvgup.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhixingplan.top/Article/details/gtdfpvexyd.html

[M05] 设置退出码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpwlcqhh.html

Py:   sys.exit(1)
来源：http://dali.cheryme.top/Article/details/gtwibalkle.html

PHP:  exit(1);
来源：http://dali.xuetiantiany.cn/Article/details/gtmwfgvodn.html

JS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtoqbpudog.html

TS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtpyqsvcbp.html

Java: System.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtixgeigkg.html

Go:   os.Exit(1)
来源：http://dali.yj20258888.top/Article/details/gtjbngzywn.html

Ruby: exit 1
来源：http://dali.hywenlv.cn/Article/details/gthvsvzswx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.bjfxy.top/Article/details/gtthrfsndg.html

[M06] 向标准错误输出
来源：http://dali.jqgufenzy.top/Article/details/gtqqmyyjrt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gtlzezeiva.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yangfankeji.com/Article/details/gthfvmqony.html

JS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtmlwsornh.html

TS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtcjoofmpw.html

Java: System.err.println("err")
来源：http://dali.jqgfzy.top/Article/details/gtmfuzyeje.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.quarkkingdee.top/Article/details/gtcnbwyfld.html

Ruby: warn "err"
来源：http://dali.xuetiantiany.cn/Article/details/gtmwsxtory.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tianlin.xyz/Article/details/gtqvfwidfw.html

[M07] 判断是否为主入口
来源：http://dali.snrcjt.cn/Article/details/gtlybwoxye.html

Py:   if __name__ == "__main__":
来源：http://dali.nwbrower.top/Article/details/gtjgniugki.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ehwqpu.com/Article/details/gtexukxoji.html

JS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gtcyzwwovv.html

TS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gttkzjnfic.html

Java: public static void main(String[] args)
来源：http://dali.hnqzz.top/Article/details/gtdfybjgqq.html

Go:   func main()
来源：http://dali.sufxvd.cn/Article/details/gtsmiiyoai.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aibaodan.cn/Article/details/gtoocejuzw.html

C#:   static void Main(string[] args)
来源：http://dali.quarkkingdee.top/Article/details/gtbvnsadao.html

[M08] 获取系统与运行时信息
来源：http://dali.andypj.xyz/Article/details/gtqdsajnhu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuanzx.com/Article/details/gtbhczazuk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuanzx.com/Article/details/gtnyasgmpo.html

JS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gttkuoehww.html

TS:   process.platform;  process.version
来源：http://dali.yvedp.cn/Article/details/gtnfzpolsd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daria6918.cn/Article/details/gtyecgtskr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.feifeiyinyue.top/Article/details/gtgjqhbjlq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fzhhl.top/Article/details/gtfijevbjt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ivvv.top/Article/details/gtrsitoinb.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtdobduiby.html

N. 数据结构与算法
来源：http://dali.gzhubu.top/Article/details/gtohhubcbj.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtveykyxmr.html

[N01] 二分查找（有序数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gttytszuso.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtmeyapfcn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtrffnzdyl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqiadrkh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gttuagxpmj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtpkurcjek.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cheryme.top/Article/details/gtwaptswca.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuxming.cn/Article/details/gtveoxzlhx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtaeegrjln.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jyoumei.cn/Article/details/gtqxiuspbf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gtlzwvranh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xziqi.cn/Article/details/gtzedegbxm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gttcxspbmg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtyptrzndt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhixingplan.top/Article/details/gtagupwagd.html

Go:   slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gtnyjgfmrm.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gtkxuvhbfy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ivvv.top/Article/details/gtbxkqmlpm.html

[N03] 快速排序（分治示例）
来源：http://dali.sufxvd.cn/Article/details/gtfsiochye.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuanzhike.top/Article/details/gtfppmwrse.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jianghu66.top/Article/details/gtnpgpzumj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gtqpsggcbl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gtktdpuzvy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.smart0.xyz/Article/details/gtwbztdbhp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daxiang520.top/Article/details/gtbceoipcy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hnqzz.top/Article/details/gtrqenciau.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yongpay.top/Article/details/gtnbbkvheo.html

[N04] 斐波那契数列
来源：http://dali.vqdsnc.cn/Article/details/gtfrwmalll.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gtjqmbtqzz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gtjjihfeqh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtomougqhb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtijuzrnkf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gtffzuyrgk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aizwys.cn/Article/details/gtglpuowcb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gtugebepmm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gtnuhxysrm.html

[N05] 最大公约数
来源：http://dali.aibaodan.cn/Article/details/gtorsyuxwq.html

Py:   math.gcd(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtxbjiztcw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jlsjyb.cn/Article/details/gtmxzzublg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gtwysjbisj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gtbtgvppms.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagiemkao.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.vqdsnc.cn/Article/details/gtpkbywcat.html

Ruby: a.gcd(b)
来源：http://dali.jinqigufen.top/Article/details/gtqojjedvb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xylfe.cn/Article/details/gtvzjqdlcb.html

[N06] 判断回文字符串
来源：http://dali.aibaodan.cn/Article/details/gtyrlhypgn.html

Py:   s == s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gtdpglpxiu.html

PHP:  $s === strrev($s);
来源：http://dali.havefunace.top/Article/details/gtxsvuuaqg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gttnjittlr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtebrvbxls.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnqzz.top/Article/details/gtcfnxszjp.html

Go:   // 双指针从两端比较
来源：http://dali.kuanghao11.cn/Article/details/gtmnwwudpy.html

Ruby: s == s.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtpazshiug.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gtbcqodtkv.html

[N07] 两数之和（返回下标）
来源：http://dali.gaohongyu789.top/Article/details/gtrpyoslpg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hfpthk.cn/Article/details/gtqvspjvbf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.mhx1999.top/Article/details/gtnjffiwqp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jlsjyb.cn/Article/details/gtvdapdqnz.html

TS:   // 手写 Map<string, number>
来源：http://dali.ivvv.top/Article/details/gtedtizzmu.html

Java: // 手写 HashMap
来源：http://dali.aizwys.cn/Article/details/gtikkuccqn.html

Go:   // 手写 map[int]int
来源：http://dali.daria6918.cn/Article/details/gtsnhctyxc.html

Ruby: // 手写 Hash
来源：http://dali.ehwqpu.com/Article/details/gtxyuxzvbi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.andypj.xyz/Article/details/gthlkwjqse.html

[N08] 生成全排列
来源：http://dali.aibaodan.cn/Article/details/gtmdybybye.html

Py:   itertools.permutations(arr)
来源：http://dali.cashguo.top/Article/details/gtqpuupvht.html

PHP:  // 手写递归交换
来源：http://dali.birdmap.top/Article/details/gtucaktfvu.html

JS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtcgzqdzke.html

TS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtdorwkjry.html

Java: // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtqafytupk.html

Go:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtlsfgwzra.html

Ruby: arr.permutation.to_a
来源：http://dali.aibaodan.cn/Article/details/gtwnbdbtrx.html

C#:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtojofrpvy.html

[N09] 栈与队列
来源：http://dali.dianchejie.cn/Article/details/gtdfwuxjxw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunsumoze.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtwexwuefd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtedcccbci.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj202588.top/Article/details/gtjvlkcqfo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xziqi.cn/Article/details/gtytmpiypg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenzaomai.com/Article/details/gtxxaawmdd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gtkbbassoi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.vqdsnc.cn/Article/details/gtpzsdmuhq.html

[N10] 链表节点定义
来源：http://dali.feifeiyinyue.top/Article/details/gtfauokinv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pycfn.com/Article/details/gtjzlhbetl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.0kj1m.cn/Article/details/gtiborrumq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhongyouzk.top/Article/details/gtxxhqphbt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gogol.net.cn/Article/details/gtbmpxhznh.html

Java: class Node { int v; Node next; }
来源：http://dali.c1oappe.top/Article/details/gtdscjtiss.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.redwolf501.top/Article/details/gtgnyoymwm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.316326.xyz/Article/details/gthtnajbgn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tanke756.top/Article/details/gtqtpapldg.html

[N11] 二叉树中序遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtimplvvvz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aibaodan.cn/Article/details/gtvkzbpuuh.html

PHP:  // 手写递归函数
来源：http://dali.hammf.cn/Article/details/gtorkxcrso.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gtfseeputq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gtzeycfgfd.html

Java: // 手写递归
来源：http://dali.ydzc1.top/Article/details/gttcukplaz.html

Go:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtwgtttlst.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guannengcc.top/Article/details/gtlvaimyoh.html

C#:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkibwysrj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.guannengcc.top/Article/details/gtgpbqdqcv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hywenlv.cn/Article/details/gtjbewivwn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxinkj.top/Article/details/gttusjbhdd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gthryvhxhg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gtdddlygqx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gtbiwwzwmk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxpuhant.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnjgnpkr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gtztsllwxc.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gttqdiwrjw.html

O. 并发与异步
来源：http://dali.zhengqikj.top/Article/details/gtcmgaprqt.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gthnvbfadn.html

[O01] 启动一个线程
来源：http://dali.sufxvd.cn/Article/details/gtiypjkdpc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dashuyun.cn/Article/details/gtiqnfzaig.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnxiangtu.top/Article/details/gtmlfqgjhl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hysaishi.cn/Article/details/gtxnogivxy.html

TS:   // 同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gtzozezqyt.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuxming.cn/Article/details/gtpgcnagwa.html

Go:   go f()
来源：http://dali.redwolf501.top/Article/details/gtgfowazfp.html

Ruby: Thread.new { f }
来源：http://dali.zhixingplan.top/Article/details/gtcczusivo.html

C#:   Task.Run(() => F());
来源：http://dali.cashguo.top/Article/details/gtuxhghtyr.html

[O02] 使用线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gteajqiqux.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.bjfxy.top/Article/details/gtndmacavx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangdashe.top/Article/details/gteospicwb.html

JS:   // worker_threads 线程池
来源：http://dali.jianghu66.top/Article/details/gtqbhmqawy.html

TS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gtqxlgkvvx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgfzy.top/Article/details/gtgtzwgwka.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hfpthk.cn/Article/details/gtfylsgcyo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tanke756.top/Article/details/gtdogtplaw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daria6918.cn/Article/details/gtdarlmxqo.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigufen.top/Article/details/gtmkmlwnly.html

Py:   with lock: shared += 1
来源：http://dali.fzhhl.top/Article/details/gtydupgzrz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gzhubu.top/Article/details/gtmyrwfqbu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jianghu66.top/Article/details/gtbegijamw.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gtyzmdlbdt.html

Java: synchronized (this) { shared++; }
来源：http://dali.cashguo.top/Article/details/gtivjqskss.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ehwqpu.com/Article/details/gtfcfxqhqo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ybcxt.top/Article/details/gtcqgybnma.html

C#:   lock (gate) { shared++; }
来源：http://dali.shuidangran.top/Article/details/gtuqgqkxaw.html

[O04] 定义异步函数并等待
来源：http://dali.xziqi.cn/Article/details/gtedzxcvgh.html

Py:   async def f():⏎    await g()
来源：http://dali.kuanghao11.cn/Article/details/gtyddxgvun.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxuanxn.top/Article/details/gtnmvaiuxg.html

JS:   async function f() { await g(); }
来源：http://dali.guannengcc.top/Article/details/gtpjwwwcpo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ybcxt.top/Article/details/gthvlahkgc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aibaodan.cn/Article/details/gtryxyplek.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.9152youxi.cn/Article/details/gtacakbqdc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nanxuanxn.top/Article/details/gtagccnafj.html

C#:   async Task F() { await G(); }
来源：http://dali.yangfankeji.com/Article/details/gtfiiugwld.html

[O05] 并发执行并等待全部完成
来源：http://dali.pycfn.com/Article/details/gtgxebuxic.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnlyffax.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zycfv.cn/Article/details/gtcyrnwjtq.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gtgryexxyq.html

TS:   await Promise.all(tasks)
来源：http://dali.meibo888.top/Article/details/gtwftnreay.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.dianchejie.cn/Article/details/gtzlvpdpnw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ivvv.top/Article/details/gtsgpyxsip.html

Ruby: threads.map(&:join)
来源：http://dali.havefunace.top/Article/details/gtsfizmhbo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.redwolf501.top/Article/details/gtbhrzmgeh.html

[O06] 使用进程池
来源：http://dali.daxiang520.top/Article/details/gtucwfpzht.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hywenlv.cn/Article/details/gtfnoiynct.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuxming.cn/Article/details/gtrlbbawdv.html

JS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gtwjyucvjy.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gtdyupoxov.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yongpay.top/Article/details/gtuzbyfgum.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.iojbl.cn/Article/details/gtrdpysgih.html

Ruby: // fork 块
来源：http://dali.ppjwa.cn/Article/details/gtfsimkkjb.html

C#:   Parallel.For
来源：http://dali.yuanzhike.top/Article/details/gtsbwspuzf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtbogerpos.html

P. 常用工具函数
来源：http://dali.shangyingyoupin.top/Article/details/gtjxmfhqwl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtlggtdqjw.html

[P01] 生成 UUID
来源：http://dali.cashguo.top/Article/details/gtqehmzufl.html

Py:   str(uuid.uuid4())
来源：http://dali.feifeiyinyue.top/Article/details/gtgojmeqgj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangdashe.top/Article/details/gtifyqrvmz.html

JS:   crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcvdleqz.html

TS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtvyagrusf.html

Java: UUID.randomUUID().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlldtseq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.svipenyu.cn/Article/details/gtlbcqqhyp.html

Ruby: SecureRandom.uuid
来源：http://dali.tanke756.top/Article/details/gthcjbjdau.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhengqikj.top/Article/details/gtvysqghrl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sysykeji.top/Article/details/gtkohkzinf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daria6918.cn/Article/details/gtatkiskqf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.haohaochexian.top/Article/details/gtrxcetbmx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenlongwang.top/Article/details/gtoabpkydk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.redwolf501.top/Article/details/gtbdjougzb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangdashe.top/Article/details/gtojjtleyg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dashuyun.cn/Article/details/gtrrvuojli.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.svipenyu.cn/Article/details/gtbtekwhih.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zdqjudy.top/Article/details/gtwefsqxon.html

[P03] 生成短随机字符串
来源：http://dali.cashguo.top/Article/details/gtryttpraz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.birdmap.top/Article/details/gtpgqrhiew.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhoulong.xyz/Article/details/gtnxzlgpew.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnqzz.top/Article/details/gtoiicklie.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gtdiwtpyik.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.havefunace.top/Article/details/gtiuwvljsb.html


<!-- 参考信息 -->