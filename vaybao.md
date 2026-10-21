代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guowangkeji.top/Article/details/gtyaojkjqp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj202588.top/Article/details/gthrublkwc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtatghxhhg.html

[L06] 解析响应为 JSON
来源：http://dali.ppjwa.cn/Article/details/gtijrjgnzz.html

Py:   resp.json()
来源：http://dali.cucudq.cn/Article/details/gtoobwowru.html

PHP:  json_decode($body, true);
来源：http://dali.fzhhl.top/Article/details/gtlnxrfbdx.html

JS:   await resp.json()
来源：http://dali.smart0.xyz/Article/details/gtycefdoct.html

TS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gterjmvnxo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtwthxfhtm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ydzc1.top/Article/details/gtbtspatvw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.mhx1999.top/Article/details/gtfcrdboua.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuxming.cn/Article/details/gtytwtuxcu.html

[L07] 处理 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gtjdwqteob.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.iojbl.cn/Article/details/gtlbpkhzoi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jyoumei.cn/Article/details/gtznmqvwed.html

JS:   resp.ok;  resp.status
来源：http://dali.sufxvd.cn/Article/details/gtpbspgruk.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gtmsbaqjuo.html

Java: resp.statusCode()
来源：http://dali.chenjidiqi.icu/Article/details/gtcwbsqtqi.html

Go:   resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtaugeezfn.html

Ruby: resp.code.to_i
来源：http://dali.nwbrower.top/Article/details/gtdyrsfmlz.html

C#:   (int)resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gtszqvetgg.html

[L08] 并发请求多个地址
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovqyuqcy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.0kj1m.cn/Article/details/gtiomeoyla.html

PHP:  curl_multi_init() 系列
来源：http://dali.jiagoushi.top/Article/details/gtjkgybbih.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtpjlerdxq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gtacqgxidn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenzaomai.com/Article/details/gtfgwkfxsw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sweek.top/Article/details/gtakvhpvff.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangshuangyany.cn/Article/details/gtjkcqgjay.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tanke756.top/Article/details/gtjysfvhbo.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtutobqpwn.html

M. 命令行 / 进程 / 环境
来源：http://dali.hfpthk.cn/Article/details/gtglgzjgie.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtgrybrtkt.html

[M01] 读取命令行参数
来源：http://dali.bjfxy.top/Article/details/gtksnvogoz.html

Py:   sys.argv[1:]
来源：http://dali.snrcjt.cn/Article/details/gthbblyudv.html

PHP:  $argv;  $argc;
来源：http://dali.jlsjyb.cn/Article/details/gtzlntvyhd.html

JS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gtnkbctfag.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gtmtxqqych.html

Java: args 数组（main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gtwnmqdrii.html

Go:   os.Args[1:]
来源：http://dali.bjfxy.top/Article/details/gtgqhksgcx.html

Ruby: ARGV
来源：http://dali.smart0.xyz/Article/details/gtjlxoclih.html

C#:   args 数组（Main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtufmxryhu.html

[M02] 读取环境变量
来源：http://dali.hnxiangtu.top/Article/details/gtrsrfctgn.html

Py:   os.environ.get("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtlmwovxif.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gtobbnsgwi.html

JS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gtvjwhqgfk.html

TS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtwsynrslq.html

Java: System.getenv("HOME")
来源：http://dali.wangdashe.top/Article/details/gtwkpdevva.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtxnlqzphf.html

Ruby: ENV["HOME"]
来源：http://dali.sufxvd.cn/Article/details/gtdqwzadiu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj202588.top/Article/details/gtgpkyvwii.html

[M03] 执行外部命令
来源：http://dali.jqgfzy.top/Article/details/gtjndzbwqh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yonumen.top/Article/details/gtmrhnuxrz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.9152youxi.cn/Article/details/gtmnnreynm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gteckjvipm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtzvuxisvr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nwbrower.top/Article/details/gtrcwtthwx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cheryme.top/Article/details/gtjywrximu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrknarfey.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cucudq.cn/Article/details/gtgxaqttdk.html

[M04] 获取当前工作目录
来源：http://dali.wangshuangyany.cn/Article/details/gtavswiaws.html

Py:   os.getcwd()
来源：http://dali.hnqzz.top/Article/details/gtnxxjhlie.html

PHP:  getcwd();
来源：http://dali.dianchejie.cn/Article/details/gtrrilydwj.html

JS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gtegsabuuw.html

TS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gtfhyckoec.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aizwys.cn/Article/details/gtsqxosgjg.html

Go:   os.Getwd()
来源：http://dali.tanke756.top/Article/details/gtnxwyjzen.html

Ruby: Dir.pwd
来源：http://dali.jyoumei.cn/Article/details/gtfumyrewm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hammf.cn/Article/details/gtluunxffl.html

[M05] 设置退出码
来源：http://dali.hfpthk.cn/Article/details/gtaxnqyvjg.html

Py:   sys.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtmaqprdev.html

PHP:  exit(1);
来源：http://dali.zhengqikj.top/Article/details/gtxsdpzfwl.html

JS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gtdbhoopqm.html

TS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtjdzqekdt.html

Java: System.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtebywzwhb.html

Go:   os.Exit(1)
来源：http://dali.yvedp.cn/Article/details/gtflrpeckl.html

Ruby: exit 1
来源：http://dali.xziqi.cn/Article/details/gtdhrskvyg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yonumen.top/Article/details/gtfwgpaxos.html

[M06] 向标准错误输出
来源：http://dali.yvedp.cn/Article/details/gtjppolisx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gtwjfdkeba.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenlongwang.top/Article/details/gtjhegelvr.html

JS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gtanpmrnwt.html

TS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtcghbicng.html

Java: System.err.println("err")
来源：http://dali.wangdashe.top/Article/details/gtftmpjwcm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtesrwqsla.html

Ruby: warn "err"
来源：http://dali.shzxlz.cn/Article/details/gtepbgzqap.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aibaodan.cn/Article/details/gtehxyjcit.html

[M07] 判断是否为主入口
来源：http://dali.cucudq.cn/Article/details/gtykwidngc.html

Py:   if __name__ == "__main__":
来源：http://dali.fengsongda.top/Article/details/gtptkchqqg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sufxvd.cn/Article/details/gtwdpooazq.html

JS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gtxlehjifb.html

TS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gtlnzzjlnn.html

Java: public static void main(String[] args)
来源：http://dali.0kj1m.cn/Article/details/gtbkvrghbo.html

Go:   func main()
来源：http://dali.fzhhl.top/Article/details/gteectvaso.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cheryme.top/Article/details/gtcmdmolvn.html

C#:   static void Main(string[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthgnjjic.html

[M08] 获取系统与运行时信息
来源：http://dali.yongpay.top/Article/details/gtkweirawu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hongshengwenyu.top/Article/details/gtvpnonubt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.smart0.xyz/Article/details/gtwdlsgihj.html

JS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gttdrhenlp.html

TS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gtxmzzrweo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.9152youxi.cn/Article/details/gtaknmpmys.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shangyingyoupin.top/Article/details/gtsfjyhqcg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daxiang520.top/Article/details/gtjkhitlil.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cqqwz.cn/Article/details/gtepkztfbt.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtcydzskfe.html

N. 数据结构与算法
来源：http://dali.hnqzz.top/Article/details/gtcixjewlp.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtcmtmflzs.html

[N01] 二分查找（有序数组）
来源：http://dali.wangshuangyany.cn/Article/details/gtsmlkfhuq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtiqjwldru.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnqzz.top/Article/details/gtasawigbw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gtjjrxphbj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fengsongda.top/Article/details/gtyqkjxvkk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gthqytietl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtothgeckm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangshuangyany.cn/Article/details/gtfhiyervs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtxabefdsj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yongpay.top/Article/details/gtfcptrcqa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gtbbzyengx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hysaishi.cn/Article/details/gtpjpakstp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtslysplci.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gtbhhfthez.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigfzy.top/Article/details/gtknxvuwxs.html

Go:   slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gtaebohria.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gthedeisat.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.meibo888.top/Article/details/gtgkqmfvyr.html

[N03] 快速排序（分治示例）
来源：http://dali.smart0.xyz/Article/details/gthyhktnif.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.vqdsnc.cn/Article/details/gtfpyefgeu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.iojbl.cn/Article/details/gtrahvhcmg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gtzapxvsah.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gtvtifpsnz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sxryk.cn/Article/details/gtssgodgkb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aibaodan.cn/Article/details/gtqkfjaihl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hongshengwenyu.top/Article/details/gtnhehicre.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sweek.top/Article/details/gtjottrodr.html

[N04] 斐波那契数列
来源：http://dali.9152youxi.cn/Article/details/gtsvlmjize.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gtlkizzahf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gtpulvvlli.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gtlyfserwc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpksncmqt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gtbxsttuka.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tanke756.top/Article/details/gtutufhnoa.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmihzvgrp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtycpiphxd.html

[N05] 最大公约数
来源：http://dali.tanke756.top/Article/details/gtxmmqebvx.html

Py:   math.gcd(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtkrmetjec.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtibvfqepn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtubeyuigt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gttemysqfm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhengqikj.top/Article/details/gtgsswvgdk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.9152youxi.cn/Article/details/gtmkufzmhl.html

Ruby: a.gcd(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwklecnx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guowangkeji.top/Article/details/gtpgttfskf.html

[N06] 判断回文字符串
来源：http://dali.svipenyu.cn/Article/details/gtngomwwjc.html

Py:   s == s[::-1]
来源：http://dali.yj20258888.top/Article/details/gtuidgrfma.html

PHP:  $s === strrev($s);
来源：http://dali.fengsongda.top/Article/details/gtzaljkfkt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtcrkwjesb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtnwfkynfh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqylekmm.html

Go:   // 双指针从两端比较
来源：http://dali.jiagoushi.top/Article/details/gthschdjvh.html

Ruby: s == s.reverse
来源：http://dali.chenlongwang.top/Article/details/gtfwsxhzfc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gtyzzhkicu.html

[N07] 两数之和（返回下标）
来源：http://dali.jinghuilouyu.cn/Article/details/gtvueplbqa.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hongshengwenyu.top/Article/details/gtuixfjids.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenzaomai.com/Article/details/gtocagzsmz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tanke756.top/Article/details/gtpfqnurxj.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gtiiyemhny.html

Java: // 手写 HashMap
来源：http://dali.sysykeji.top/Article/details/gtdgtqpwtj.html

Go:   // 手写 map[int]int
来源：http://dali.gzhubu.top/Article/details/gtfnybgnyw.html

Ruby: // 手写 Hash
来源：http://dali.sweek.top/Article/details/gtntypeajl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xinyue.icu/Article/details/gtsafoiktx.html

[N08] 生成全排列
来源：http://dali.guannengcc.top/Article/details/gtlxrwnpmb.html

Py:   itertools.permutations(arr)
来源：http://dali.tanke756.top/Article/details/gtzqnhmaid.html

PHP:  // 手写递归交换
来源：http://dali.xuanzx.com/Article/details/gtyeskfqnq.html

JS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtnxpsyzhe.html

TS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtsywhfpol.html

Java: // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtcimubbfy.html

Go:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtxrntbdii.html

Ruby: arr.permutation.to_a
来源：http://dali.shangyingyoupin.top/Article/details/gtjltbvoij.html

C#:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtbzwroyay.html

[N09] 栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gtggoyxflx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtuhuomzdl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtpsqwddhu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gtkahxnxap.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnxiangtu.top/Article/details/gtcqpbllkx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.9152youxi.cn/Article/details/gtzjjrmyvz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sxryk.cn/Article/details/gtbcnkpyae.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtzajmpcqz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sxryk.cn/Article/details/gtppicuccc.html

[N10] 链表节点定义
来源：http://dali.0kj1m.cn/Article/details/gtqfyepkmo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tanke756.top/Article/details/gtxwalxryp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ybcxt.top/Article/details/gtfkxuvced.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guannengcc.top/Article/details/gtummuvqzr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.0kj1m.cn/Article/details/gtbyukqclh.html

Java: class Node { int v; Node next; }
来源：http://dali.cqqwz.cn/Article/details/gtujabzmox.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jiagoushi.top/Article/details/gtryajqphp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.redwolf501.top/Article/details/gtuknojhjj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daria6918.cn/Article/details/gtrstunvdv.html

[N11] 二叉树中序遍历
来源：http://dali.yj20258888.top/Article/details/gtaoqfbcbh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnqzz.top/Article/details/gtdzwpdmea.html

PHP:  // 手写递归函数
来源：http://dali.yanxiufei.cn/Article/details/gttpuutrmv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gtloohbxod.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gtyityxesl.html

Java: // 手写递归
来源：http://dali.daria6918.cn/Article/details/gthxwyctzk.html

Go:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtzbeplqim.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zdqjudy.top/Article/details/gtbzdxunbi.html

C#:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtayrlictd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangshuangyany.cn/Article/details/gtuuytojrt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.mhx1999.top/Article/details/gtfvrvzwtd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jqgufenzy.top/Article/details/gtyjgxqrcf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtsvkehuoz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gtemmlwinj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ppjwa.cn/Article/details/gtqzhyquvq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.redwolf501.top/Article/details/gtqnsjvjxf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gtxoiuwjcf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gtghmjrjul.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmgtxlzz.html

O. 并发与异步
来源：http://dali.yongpay.top/Article/details/gtwuooxrxm.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtyqptxpkv.html

[O01] 启动一个线程
来源：http://dali.ybcxt.top/Article/details/gtpgwryxto.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guannengcc.top/Article/details/gtumqlcvxv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtncqvwiqy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ppjwa.cn/Article/details/gtswqfntkj.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gthibshudp.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gthwkponad.html

Go:   go f()
来源：http://dali.jqgfzy.top/Article/details/gtkuuchbmg.html

Ruby: Thread.new { f }
来源：http://dali.redwolf501.top/Article/details/gtowvqdqnw.html

C#:   Task.Run(() => F());
来源：http://dali.jqgufenzy.top/Article/details/gthwzrrozx.html

[O02] 使用线程池
来源：http://dali.chenlongwang.top/Article/details/gtqrffgivz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sysykeji.top/Article/details/gtkjadclpc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xziqi.cn/Article/details/gtewfepvcn.html

JS:   // worker_threads 线程池
来源：http://dali.chenlongwang.top/Article/details/gtkcmslhlf.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gtctkmpxdv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhixingplan.top/Article/details/gtqpfofyce.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aizwys.cn/Article/details/gtuiihrgen.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuxming.cn/Article/details/gtvzmfxvep.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gaohongyu789.top/Article/details/gtzxewthuy.html

[O03] 加锁保护共享数据
来源：http://dali.havefunace.top/Article/details/gttnvdpskx.html

Py:   with lock: shared += 1
来源：http://dali.tianlin.xyz/Article/details/gtavguhqxd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gtavazlnwf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hongshengwenyu.top/Article/details/gtxyhzmqjs.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gtqbpwwgcy.html

Java: synchronized (this) { shared++; }
来源：http://dali.dianchejie.cn/Article/details/gthrytbdyn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ivvv.top/Article/details/gtouxegudg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sxryk.cn/Article/details/gtlvbivbxq.html

C#:   lock (gate) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtaxbtnrmk.html

[O04] 定义异步函数并等待
来源：http://dali.zhongyouzk.top/Article/details/gtlijmdgsr.html

Py:   async def f():⏎    await g()
来源：http://dali.fzhhl.top/Article/details/gtzijpzczy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsaqxiqjz.html

JS:   async function f() { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gtgnzwbnks.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gthzcuefgl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.andypj.xyz/Article/details/gtvvxcwdya.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ybcxt.top/Article/details/gtxllzuiqo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jiagoushi.top/Article/details/gtbhqgufzf.html

C#:   async Task F() { await G(); }
来源：http://dali.cheryme.top/Article/details/gtncuefbfj.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj20258888.top/Article/details/gtrsxpqwiv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.andypj.xyz/Article/details/gtllutbriy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenjidiqi.icu/Article/details/gtpsmmtose.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gtppbenjgv.html

TS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gtpjcuhcdi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.svipenyu.cn/Article/details/gtigvtdiuk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.meibo888.top/Article/details/gtmmfwwcgc.html

Ruby: threads.map(&:join)
来源：http://dali.jyoumei.cn/Article/details/gtrxtgslcf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hfpthk.cn/Article/details/gttftynzaf.html

[O06] 使用进程池
来源：http://dali.sufxvd.cn/Article/details/gtbbfyfzut.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.redwolf501.top/Article/details/gtvqidzptq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenjidiqi.icu/Article/details/gtgkadmvxu.html

JS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpcgojth.html

TS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gtvzpuhybc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangtech.top/Article/details/gtadbzglnn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hongshengwenyu.top/Article/details/gtpwbcsljw.html

Ruby: // fork 块
来源：http://dali.fengsongda.top/Article/details/gtoeayyrkl.html

C#:   Parallel.For
来源：http://dali.pycfn.com/Article/details/gtsbsgmsth.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtrewcvwyx.html

P. 常用工具函数
来源：http://dali.jinqigfzy.top/Article/details/gtcpgslfwe.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtnprqjfmh.html

[P01] 生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gtwhslfcam.html

Py:   str(uuid.uuid4())
来源：http://dali.xuetiantiany.cn/Article/details/gtrdsguqkf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.pengpengdd.cyou/Article/details/gtnonmvmii.html

JS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gtaqdltaba.html

TS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gtfbwkjpvs.html

Java: UUID.randomUUID().toString()
来源：http://dali.gotoacloud.top/Article/details/gthyimekhh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fzhhl.top/Article/details/gtcuvgjzaq.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxinkj.top/Article/details/gtftdnyxrk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258.top/Article/details/gtddyppqdw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ybcxt.top/Article/details/gtukmpkakc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxfscfcx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxinkj.top/Article/details/gtckclnhrq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj202588.top/Article/details/gtronfpupp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ivvv.top/Article/details/gtsxfrainv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtnhuzorai.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.0kj1m.cn/Article/details/gtrvmixery.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtrnxjpqwx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sweek.top/Article/details/gtnoixbgqp.html

[P03] 生成短随机字符串
来源：http://dali.shuidangran.top/Article/details/gtiaqsfltg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangtech.top/Article/details/gtghpejkwu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.316326.xyz/Article/details/gtquzrspqh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.quarkkingdee.top/Article/details/gtyyhkpxqq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtacrpiyjy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenlongwang.top/Article/details/gtnkctpkkm.html


<!-- 参考信息 -->