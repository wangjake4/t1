代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhiwuduotai.top/Article/details/gtktmvczxl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yonumen.top/Article/details/gttbifdvcv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtxrfwngng.html

[L06] 解析响应为 JSON
来源：http://dali.sufxvd.cn/Article/details/gtnuhkgizj.html

Py:   resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gteglqfogx.html

PHP:  json_decode($body, true);
来源：http://dali.smart0.xyz/Article/details/gtgktvxnwm.html

JS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gtbxthbjqv.html

TS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gtpjedzyzi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuxming.cn/Article/details/gtjanpiemh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jiagoushi.top/Article/details/gtjbnhktnt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sweek.top/Article/details/gtzivbtwom.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ppjwa.cn/Article/details/gtacilqkip.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gtmkmbupnf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuxming.cn/Article/details/gtfgismlow.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ydzc1.top/Article/details/gtttgyqowz.html

JS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gthpikydkq.html

TS:   resp.ok;  resp.status
来源：http://dali.shuidangran.top/Article/details/gtadmetros.html

Java: resp.statusCode()
来源：http://dali.fzhhl.top/Article/details/gtgunlxwiw.html

Go:   resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gtryfedbjw.html

Ruby: resp.code.to_i
来源：http://dali.yueranfly.top/Article/details/gtxxyioebh.html

C#:   (int)resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtlvmsldyp.html

[L08] 并发请求多个地址
来源：http://dali.yueranfly.top/Article/details/gtfayuuccx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daria6918.cn/Article/details/gtzggtumiu.html

PHP:  curl_multi_init() 系列
来源：http://dali.jqgufenzy.top/Article/details/gtneawffnb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gtkgkylfzz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtlibgkcmg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.quarkkingdee.top/Article/details/gtbxrkfftm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zdqjudy.top/Article/details/gtmyknhxkm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guannengcc.top/Article/details/gtdjidmvvf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpycbmsc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtkuvhshbp.html

M. 命令行 / 进程 / 环境
来源：http://dali.sufxvd.cn/Article/details/gtgyiwzvty.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtvghnaqdw.html

[M01] 读取命令行参数
来源：http://dali.316326.xyz/Article/details/gtpuaalwjv.html

Py:   sys.argv[1:]
来源：http://dali.gzhubu.top/Article/details/gtpnodooes.html

PHP:  $argv;  $argc;
来源：http://dali.kuanghao11.cn/Article/details/gtuhyppdmr.html

JS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gtrdprrwst.html

TS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gtlnkrcqzh.html

Java: args 数组（main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gtjpzuwbjt.html

Go:   os.Args[1:]
来源：http://dali.dianchejie.cn/Article/details/gttndiuuyp.html

Ruby: ARGV
来源：http://dali.gotoacloud.top/Article/details/gtzcbukyun.html

C#:   args 数组（Main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gthfmvbljn.html

[M02] 读取环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtukwazeov.html

Py:   os.environ.get("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhhfknmd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gtscxtmutb.html

JS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gtxxjqhrtn.html

TS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gtrsfwmlju.html

Java: System.getenv("HOME")
来源：http://dali.yvedp.cn/Article/details/gtrlpizfvc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtvkwvyuwl.html

Ruby: ENV["HOME"]
来源：http://dali.gogol.net.cn/Article/details/gtlmemalki.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtafsphzrs.html

[M03] 执行外部命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqwzgkqn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fzhhl.top/Article/details/gthncfcxkm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gaohongyu789.top/Article/details/gtiwmrkzgr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gttzjveenx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gtbxuqjapm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.feifeiyinyue.top/Article/details/gtbujiouav.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xziqi.cn/Article/details/gtyvtrrlyv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.smart0.xyz/Article/details/gtfkbdtdkh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ydzc1.top/Article/details/gtiofnwibd.html

[M04] 获取当前工作目录
来源：http://dali.tian-w.cn/Article/details/gtzvrfiiyk.html

Py:   os.getcwd()
来源：http://dali.cdnleiting.top/Article/details/gtmkzoccrk.html

PHP:  getcwd();
来源：http://dali.jqgfzy.top/Article/details/gtzosndqof.html

JS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygehklzw.html

TS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtaqsgkgqk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daxiang520.top/Article/details/gtztugqret.html

Go:   os.Getwd()
来源：http://dali.zhongyouzk.top/Article/details/gtnvbcpwlx.html

Ruby: Dir.pwd
来源：http://dali.quarkkingdee.top/Article/details/gtwfjzgdcz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gtreavsajk.html

[M05] 设置退出码
来源：http://dali.cqqwz.cn/Article/details/gtptdvkjvo.html

Py:   sys.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtbfhdtjqn.html

PHP:  exit(1);
来源：http://dali.zdqjudy.top/Article/details/gthkvbndia.html

JS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gteohxncot.html

TS:   process.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtvhjoiflz.html

Java: System.exit(1)
来源：http://dali.yongpay.top/Article/details/gtaeatvvvh.html

Go:   os.Exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtknkmxszi.html

Ruby: exit 1
来源：http://dali.aibaodan.cn/Article/details/gtypswfill.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dianchejie.cn/Article/details/gtfcbedtgx.html

[M06] 向标准错误输出
来源：http://dali.pengpengdd.cyou/Article/details/gtkdnfaxhx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gtrxkuqtmo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenjidiqi.icu/Article/details/gtifzrytbo.html

JS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gtxyylzueh.html

TS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtogxoapac.html

Java: System.err.println("err")
来源：http://dali.9152youxi.cn/Article/details/gtzvuzfhhp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hongshengwenyu.top/Article/details/gtplodmqyh.html

Ruby: warn "err"
来源：http://dali.jyoumei.cn/Article/details/gtzjvhquww.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guowangkeji.top/Article/details/gtcgegvaxi.html

[M07] 判断是否为主入口
来源：http://dali.jianghu66.top/Article/details/gtppwuymgd.html

Py:   if __name__ == "__main__":
来源：http://dali.ybcxt.top/Article/details/gtnrbyzplr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ybcxt.top/Article/details/gtjvlprufz.html

JS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtaaqynriu.html

TS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gtztvddusi.html

Java: public static void main(String[] args)
来源：http://dali.nwbrower.top/Article/details/gtcewjqskd.html

Go:   func main()
来源：http://dali.zdqjudy.top/Article/details/gtyqxxkvwk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangshuangyany.cn/Article/details/gtjgssyept.html

C#:   static void Main(string[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gtxfevkofb.html

[M08] 获取系统与运行时信息
来源：http://dali.sufxvd.cn/Article/details/gtugdynsth.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenlongwang.top/Article/details/gtpyvuctoq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangshuangyany.cn/Article/details/gtwirqqply.html

JS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtygljwpsk.html

TS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gtyfookxkq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jianghu66.top/Article/details/gtpltwgvlp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gthicteofy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.birdmap.top/Article/details/gtvfkevwgf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gzhubu.top/Article/details/gthkvuevgy.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtfdmnqjxh.html

N. 数据结构与算法
来源：http://dali.zdqjudy.top/Article/details/gtsvjwrtyl.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtznzlfqzq.html

[N01] 二分查找（有序数组）
来源：http://dali.iojbl.cn/Article/details/gtlpacejga.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtxdxxliwr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dashuyun.cn/Article/details/gthvdyvtip.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gtijqugtyi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gtspokqool.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtegyljyly.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtfkddgagp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hysaishi.cn/Article/details/gtwuceypow.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtpeqejkcl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yueranfly.top/Article/details/gtvibklhke.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gteyvwtxlf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yangfankeji.com/Article/details/gtwlwtfhjf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gtimnugcsj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gtlvweuiip.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gtypqrlzbq.html

Go:   slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gtawilnpdl.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gtfhvnkmvi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.meibo888.top/Article/details/gtgazarnyh.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxuanxn.top/Article/details/gtajwtnwsg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gtxxusdcvs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gotoacloud.top/Article/details/gtewhwqpfb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gtxqrkwfxb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gtzilgdkmz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cheryme.top/Article/details/gtasdwjfva.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhengqikj.top/Article/details/gtztlrmfvr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.havefunace.top/Article/details/gtxwzyqfgm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tanke756.top/Article/details/gteycrweqc.html

[N04] 斐波那契数列
来源：http://dali.cashguo.top/Article/details/gtbfalqtlf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gthykjcgje.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gtscjwapby.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtzymkcero.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtxtfocqie.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gtaoxxmwns.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxinkj.top/Article/details/gtrzsuwuil.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtuvlzsflu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtveaqcwtc.html

[N05] 最大公约数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumfuozkg.html

Py:   math.gcd(a, b)
来源：http://dali.xinyue.icu/Article/details/gtwapuhqyb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhengqikj.top/Article/details/gtvprmdayf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gtgbfdxjgb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gtvrccihbe.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhoulong.xyz/Article/details/gtfgpslpir.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xziqi.cn/Article/details/gtqtvefisd.html

Ruby: a.gcd(b)
来源：http://dali.meibo888.top/Article/details/gtgfhobekr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.iojbl.cn/Article/details/gtjxkstzcv.html

[N06] 判断回文字符串
来源：http://dali.gaohongyu789.top/Article/details/gthqsescyj.html

Py:   s == s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gttttgljmy.html

PHP:  $s === strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gtyjogwiwk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtvxjtshml.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtqqwjhguh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenjidiqi.icu/Article/details/gtodictzro.html

Go:   // 双指针从两端比较
来源：http://dali.sysykeji.top/Article/details/gtcyghaqcy.html

Ruby: s == s.reverse
来源：http://dali.316326.xyz/Article/details/gtvdnvllgn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gtxafhklfa.html

[N07] 两数之和（返回下标）
来源：http://dali.wangshuangyany.cn/Article/details/gtbncgoksf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhengqikj.top/Article/details/gtfoawhtum.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tian-w.cn/Article/details/gtmlncybbk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangshuangyany.cn/Article/details/gtleaozpxn.html

TS:   // 手写 Map<string, number>
来源：http://dali.cheryme.top/Article/details/gtcuaxerpa.html

Java: // 手写 HashMap
来源：http://dali.ehwqpu.com/Article/details/gtthzespxj.html

Go:   // 手写 map[int]int
来源：http://dali.fzhhl.top/Article/details/gtqtyywbfl.html

Ruby: // 手写 Hash
来源：http://dali.cqqwz.cn/Article/details/gttoifghdn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenjidiqi.icu/Article/details/gtpgukeose.html

[N08] 生成全排列
来源：http://dali.shanyushiyangtech.top/Article/details/gtafwuquyu.html

Py:   itertools.permutations(arr)
来源：http://dali.ppjwa.cn/Article/details/gtzwpfxjoz.html

PHP:  // 手写递归交换
来源：http://dali.meibo888.top/Article/details/gtgwqwdnsk.html

JS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtvvokftde.html

TS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtntbhuacg.html

Java: // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gttwmrnklu.html

Go:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtejtfprss.html

Ruby: arr.permutation.to_a
来源：http://dali.yonumen.top/Article/details/gtqylbofxs.html

C#:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gteukwtzcf.html

[N09] 栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gtzbnfgwtv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqlkeclz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxibqwjr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtmfzmzksl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xziqi.cn/Article/details/gtczgsibeh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yongpay.top/Article/details/gtvrfusjtf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuanzx.com/Article/details/gtkcwdbsfo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtbsexexup.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxinkj.top/Article/details/gtomcrvavc.html

[N10] 链表节点定义
来源：http://dali.ivvv.top/Article/details/gtdolpjqyc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daxiang520.top/Article/details/gtgskkihhr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jianghu66.top/Article/details/gthmbmjlyy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.andypj.xyz/Article/details/gtsqlersec.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenlongwang.top/Article/details/gtxwnapqcy.html

Java: class Node { int v; Node next; }
来源：http://dali.xziqi.cn/Article/details/gtmgeeyguz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daxiang520.top/Article/details/gtrfvoukcv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.iojbl.cn/Article/details/gtngpghocz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yvedp.cn/Article/details/gtdpjtjvln.html

[N11] 二叉树中序遍历
来源：http://dali.tanke756.top/Article/details/gtsvsnxkzn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hysaishi.cn/Article/details/gtclzdvfkg.html

PHP:  // 手写递归函数
来源：http://dali.cashguo.top/Article/details/gtccgcnvsv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.bjfxy.top/Article/details/gtekqphnqz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tanke756.top/Article/details/gtvkcpejva.html

Java: // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtnetnfehx.html

Go:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtefnfjzgl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nanxinkj.top/Article/details/gtsctqgtsb.html

C#:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtznqgcidr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cheryme.top/Article/details/gthxzdfgxl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxinkj.top/Article/details/gttfozlfdu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yuxming.cn/Article/details/gtecuxbuit.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gtwwqvyqhv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtaunysvke.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gtcbmglsag.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cashguo.top/Article/details/gtncbknbdy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlbwscvg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gtttolqzca.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtjdjqzwlt.html

O. 并发与异步
来源：http://dali.ivvv.top/Article/details/gtafrzbcpv.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtgjsmabaw.html

[O01] 启动一个线程
来源：http://dali.sufxvd.cn/Article/details/gtrkmtjtiu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangdashe.top/Article/details/gtfbfpdwpr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hammf.cn/Article/details/gtopjliivd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nwbrower.top/Article/details/gtzjmjznad.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gtnumqmjwg.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangshuangyany.cn/Article/details/gttswqsfzi.html

Go:   go f()
来源：http://dali.vqdsnc.cn/Article/details/gtcpbkixnu.html

Ruby: Thread.new { f }
来源：http://dali.dashuyun.cn/Article/details/gtetskgxnj.html

C#:   Task.Run(() => F());
来源：http://dali.nanxinkj.top/Article/details/gtohsdhhac.html

[O02] 使用线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzfphcoh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.mhx1999.top/Article/details/gtgzuryyqt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhoulong.xyz/Article/details/gtsxcvroww.html

JS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gtaqcgnanv.html

TS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtkobncsup.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258.top/Article/details/gtkebsjelb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xylfe.cn/Article/details/gtqtgosegf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shzxlz.cn/Article/details/gtekbdacvg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.mhx1999.top/Article/details/gtkbdbfynr.html

[O03] 加锁保护共享数据
来源：http://dali.chenjidiqi.icu/Article/details/gtffpcwpqj.html

Py:   with lock: shared += 1
来源：http://dali.yueranfly.top/Article/details/gtslrieesk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinqigufen.top/Article/details/gtkebjousf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cqqwz.cn/Article/details/gtferamqgc.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gtaleyagcc.html

Java: synchronized (this) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtsrydstwb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangshuangyany.cn/Article/details/gtbgoqmoau.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnxiangtu.top/Article/details/gttalgqyej.html

C#:   lock (gate) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gtynqccuwz.html

[O04] 定义异步函数并等待
来源：http://dali.redwolf501.top/Article/details/gthqubqysz.html

Py:   async def f():⏎    await g()
来源：http://dali.jyoumei.cn/Article/details/gtjtrdwhmu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258.top/Article/details/gtgwhnyiiy.html

JS:   async function f() { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtfdkgisob.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gtvxdwsnbz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258.top/Article/details/gtcihhfsap.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigfzy.top/Article/details/gtweudclkm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jiagoushi.top/Article/details/gtzsctiuzg.html

C#:   async Task F() { await G(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtlfsmxtmm.html

[O05] 并发执行并等待全部完成
来源：http://dali.gaohongyu789.top/Article/details/gtiosdzqjy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangdashe.top/Article/details/gtfjalqeeo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yueranfly.top/Article/details/gtoeqcjplo.html

JS:   await Promise.all(tasks)
来源：http://dali.meibo888.top/Article/details/gteznqouaw.html

TS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gtpbytoglp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guannengcc.top/Article/details/gtbxdtgqdv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.mhx1999.top/Article/details/gthqrmagyh.html

Ruby: threads.map(&:join)
来源：http://dali.xinyue.icu/Article/details/gtmexcjmxp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fzhhl.top/Article/details/gtyujndtil.html

[O06] 使用进程池
来源：http://dali.daria6918.cn/Article/details/gtlvyhwcjx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnxiangtu.top/Article/details/gtjpwbvrhc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.0kj1m.cn/Article/details/gtttjrlehp.html

JS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gtxrqrocdh.html

TS:   // child_process / cluster 模块
来源：http://dali.hnxiangtu.top/Article/details/gtxontxcmq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cashguo.top/Article/details/gthorhlytb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258888.top/Article/details/gtnwlktynq.html

Ruby: // fork 块
来源：http://dali.shangyingyoupin.top/Article/details/gtcoqtjoad.html

C#:   Parallel.For
来源：http://dali.zhoulong.xyz/Article/details/gtxucrijkc.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtzjwkwjud.html

P. 常用工具函数
来源：http://dali.haohaochexian.top/Article/details/gthjclxxim.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtgiehnwwe.html

[P01] 生成 UUID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllzzbmtz.html

Py:   str(uuid.uuid4())
来源：http://dali.cdnleiting.top/Article/details/gtpkzpfehe.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aibaodan.cn/Article/details/gtawsaljvy.html

JS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtgoloigsw.html

TS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gtisvwzdiq.html

Java: UUID.randomUUID().toString()
来源：http://dali.andypj.xyz/Article/details/gtkkvkizjh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tanke756.top/Article/details/gtypgqkxuk.html

Ruby: SecureRandom.uuid
来源：http://dali.shuidangran.top/Article/details/gtlghdaiss.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.havefunace.top/Article/details/gtkjmiuuvr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.snrcjt.cn/Article/details/gtsgjltyol.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zdqjudy.top/Article/details/gtiwkqdxec.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ivvv.top/Article/details/gtgwfiggon.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gotoacloud.top/Article/details/gtrsnbtfwf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigfzy.top/Article/details/gtaijhmylk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258888.top/Article/details/gtmxagmaxg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhiwuduotai.top/Article/details/gtxmryhhuh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cheryme.top/Article/details/gtgppjfhno.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zycfv.cn/Article/details/gtyobnqgkh.html

[P03] 生成短随机字符串
来源：http://dali.9152youxi.cn/Article/details/gtfwrubotl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.bjfxy.top/Article/details/gtdetlpyuc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jyoumei.cn/Article/details/gtrupdsupt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gzhubu.top/Article/details/gtqiwbojnr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dianchejie.cn/Article/details/gtliwbdbox.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gtcyabtefg.html


<!-- 参考信息 -->