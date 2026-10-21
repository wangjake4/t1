代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aizwys.cn/Article/details/gtgdzulxdt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sysykeji.top/Article/details/gtblsudiwc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shuidangran.top/Article/details/gttxecygzk.html

[L06] 解析响应为 JSON
来源：http://dali.zhengqikj.top/Article/details/gtivtfxigk.html

Py:   resp.json()
来源：http://dali.ivvv.top/Article/details/gtxleihkxg.html

PHP:  json_decode($body, true);
来源：http://dali.ehwqpu.com/Article/details/gthubrizsy.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gtexaqkppb.html

TS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtajmhgqci.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gthhthcrhy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sufxvd.cn/Article/details/gtwtyzggzd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnxiangtu.top/Article/details/gtxsqdduix.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yanxiufei.cn/Article/details/gtwznndxhg.html

[L07] 处理 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gtgbuyyafk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shuidangran.top/Article/details/gtbhauqvdk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daria6918.cn/Article/details/gtnicidboq.html

JS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gtpbjxiiag.html

TS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gttjxlxvdq.html

Java: resp.statusCode()
来源：http://dali.shangyingyoupin.top/Article/details/gtvxofsuft.html

Go:   resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gtwrvgywpw.html

Ruby: resp.code.to_i
来源：http://dali.aibaodan.cn/Article/details/gtdpxjhxfw.html

C#:   (int)resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gtrllakszp.html

[L08] 并发请求多个地址
来源：http://dali.guannengcc.top/Article/details/gtucdxuqum.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.haohaochexian.top/Article/details/gtgewzltvk.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhongyouzk.top/Article/details/gtidasdlaa.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gtalbrobni.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gthxnoolxx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.feifeiyinyue.top/Article/details/gtsawlmolw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhongyouzk.top/Article/details/gtmdkvcoln.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pycfn.com/Article/details/gtyzatjppr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258.top/Article/details/gtldwhbpdm.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtdoqghjyf.html

M. 命令行 / 进程 / 环境
来源：http://dali.daxiang520.top/Article/details/gtbsbxspoq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtapajtcey.html

[M01] 读取命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gthojgshue.html

Py:   sys.argv[1:]
来源：http://dali.jyoumei.cn/Article/details/gtdotsagrw.html

PHP:  $argv;  $argc;
来源：http://dali.9152youxi.cn/Article/details/gtnparhbgf.html

JS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gtyndfzhoi.html

TS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gtdcxuofwf.html

Java: args 数组（main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtbnfuqdko.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gtfycycqho.html

Ruby: ARGV
来源：http://dali.sxryk.cn/Article/details/gtuqrtjsik.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gtufonjwkx.html

[M02] 读取环境变量
来源：http://dali.haohaochexian.top/Article/details/gtssyihzvw.html

Py:   os.environ.get("HOME")
来源：http://dali.andypj.xyz/Article/details/gtbxgckcfw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gtaqunmymq.html

JS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtcppheckp.html

TS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gthuljseyu.html

Java: System.getenv("HOME")
来源：http://dali.c1oappe.top/Article/details/gtysgfkwju.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nwbrower.top/Article/details/gthyhphkro.html

Ruby: ENV["HOME"]
来源：http://dali.yongpay.top/Article/details/gttsuxdhog.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.mhx1999.top/Article/details/gtjggztsgx.html

[M03] 执行外部命令
来源：http://dali.ppjwa.cn/Article/details/gtzkoslrvg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yonumen.top/Article/details/gtlvtsixmn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yanxiufei.cn/Article/details/gtinpnpxwj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gtxjdobbya.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gtecakfzdb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuanzx.com/Article/details/gtcuxxsnzj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gtispgepat.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.quarkkingdee.top/Article/details/gtjmvlhhcw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guannengcc.top/Article/details/gtpzgmhfzj.html

[M04] 获取当前工作目录
来源：http://dali.gogol.net.cn/Article/details/gtrnejnktn.html

Py:   os.getcwd()
来源：http://dali.nanxuanxn.top/Article/details/gtttkzynqr.html

PHP:  getcwd();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyoldpyvp.html

JS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gtvfrsbibt.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtmxvhcizo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pycfn.com/Article/details/gtnbdaaztl.html

Go:   os.Getwd()
来源：http://dali.316326.xyz/Article/details/gtazeocyqe.html

Ruby: Dir.pwd
来源：http://dali.9152youxi.cn/Article/details/gtcreuyapd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ppjwa.cn/Article/details/gttronzjkp.html

[M05] 设置退出码
来源：http://dali.ywan-chungtsiang.top/Article/details/gthuozxajd.html

Py:   sys.exit(1)
来源：http://dali.ybcxt.top/Article/details/gttwrsxzyu.html

PHP:  exit(1);
来源：http://dali.daxiang520.top/Article/details/gtwwqqzfkl.html

JS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtrlbpqadl.html

TS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtpywnjuas.html

Java: System.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtfrxzxdbg.html

Go:   os.Exit(1)
来源：http://dali.yvedp.cn/Article/details/gtepblqbey.html

Ruby: exit 1
来源：http://dali.birdmap.top/Article/details/gtlxvsczsc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zycfv.cn/Article/details/gtxkddrxej.html

[M06] 向标准错误输出
来源：http://dali.iojbl.cn/Article/details/gtckgyfris.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zycfv.cn/Article/details/gtoxmssvds.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guowangkeji.top/Article/details/gtmxwlwnvh.html

JS:   console.error("err")
来源：http://dali.nwbrower.top/Article/details/gtxuckrtsu.html

TS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gtafrjyvkj.html

Java: System.err.println("err")
来源：http://dali.hnqzz.top/Article/details/gtzouvwzap.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigufen.top/Article/details/gtrjtmsoom.html

Ruby: warn "err"
来源：http://dali.quarkkingdee.top/Article/details/gtbgrlrinm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sufxvd.cn/Article/details/gtytafxnqw.html

[M07] 判断是否为主入口
来源：http://dali.jinqigufen.top/Article/details/gtnaqknnef.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gtdpngldii.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.iojbl.cn/Article/details/gtazxkzhlo.html

JS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gtogrrwzch.html

TS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gtzbziipaq.html

Java: public static void main(String[] args)
来源：http://dali.jinqigfzy.top/Article/details/gtvffmqwzh.html

Go:   func main()
来源：http://dali.zhixingplan.top/Article/details/gtvxsoxchx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zycfv.cn/Article/details/gtkmfbrmbg.html

C#:   static void Main(string[] args)
来源：http://dali.dashuyun.cn/Article/details/gtrlyhpuaz.html

[M08] 获取系统与运行时信息
来源：http://dali.yj202588.top/Article/details/gtamzgjltu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgufenzy.top/Article/details/gtwnlajruv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ehwqpu.com/Article/details/gtacqhiecz.html

JS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gttretnkac.html

TS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gtjasqdcae.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hfpthk.cn/Article/details/gtreylbftd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sysykeji.top/Article/details/gtkhjlxkhl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yonumen.top/Article/details/gtxaiqicdz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.316326.xyz/Article/details/gtiztcrylf.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtcvyvipfn.html

N. 数据结构与算法
来源：http://dali.yuxming.cn/Article/details/gterhdxjcc.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gttpgshvgi.html

[N01] 二分查找（有序数组）
来源：http://dali.shuidangran.top/Article/details/gtvjdaqedw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtvmuobjaz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cucudq.cn/Article/details/gthhgbbmxo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtztjzlajs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtucwgirkg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtoefnmwpj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtckmzkqcq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dianchejie.cn/Article/details/gtjaeqikwm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gttieefkhw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.meibo888.top/Article/details/gtdqyavazz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gtcmqnzinw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhsuvckd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gtrkuujvux.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotmkvipp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.havefunace.top/Article/details/gtvrxjgnzg.html

Go:   slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gtbfotuske.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gtvyqciluw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwfmlepr.html

[N03] 快速排序（分治示例）
来源：http://dali.aizwys.cn/Article/details/gtlcskqthz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xylfe.cn/Article/details/gtlfvhtpev.html

PHP:  // 递归实现，或用 usort
来源：http://dali.redwolf501.top/Article/details/gteqfznxfs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gtcbpiimoi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gtkywlbzym.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gaohongyu789.top/Article/details/gtcoskmdrw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.svipenyu.cn/Article/details/gtgtpfkaxj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xinyue.icu/Article/details/gtigbngvqt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258.top/Article/details/gtcdpmrkpy.html

[N04] 斐波那契数列
来源：http://dali.yanxiufei.cn/Article/details/gtnqybugci.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gtkgtffutq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gtwlivrfbc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtklthguge.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtrmitfzzv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gtaiblhsju.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aizwys.cn/Article/details/gtafnemxre.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtpakvhycx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gttabgfbyf.html

[N05] 最大公约数
来源：http://dali.shzxlz.cn/Article/details/gtgfrjmkjm.html

Py:   math.gcd(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtixeqroxu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.redwolf501.top/Article/details/gtlrpsjifl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmukeijt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnqzz.top/Article/details/gtgdvncqqd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fzhhl.top/Article/details/gtsypzrdhn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.9152youxi.cn/Article/details/gtaoxkxtdv.html

Ruby: a.gcd(b)
来源：http://dali.gogol.net.cn/Article/details/gtovxcalbh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmfucjwy.html

[N06] 判断回文字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtinwfsywg.html

Py:   s == s[::-1]
来源：http://dali.daxiang520.top/Article/details/gtiacyknzk.html

PHP:  $s === strrev($s);
来源：http://dali.jinqigufen.top/Article/details/gtrevomugc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtgqvhutkc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtsszdxoql.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenzaomai.com/Article/details/gtbduqjljh.html

Go:   // 双指针从两端比较
来源：http://dali.gotoacloud.top/Article/details/gtnvaxdkik.html

Ruby: s == s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbazkvsr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ppjwa.cn/Article/details/gtbrtyqwll.html

[N07] 两数之和（返回下标）
来源：http://dali.smart0.xyz/Article/details/gtjyjkiwoa.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.mhx1999.top/Article/details/gtxcrzroch.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnqzz.top/Article/details/gthqicnmxj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzmfsesj.html

TS:   // 手写 Map<string, number>
来源：http://dali.yonumen.top/Article/details/gtdsmnwfpm.html

Java: // 手写 HashMap
来源：http://dali.jinqigufen.top/Article/details/gtxoagyxie.html

Go:   // 手写 map[int]int
来源：http://dali.shzxlz.cn/Article/details/gtriyokpwe.html

Ruby: // 手写 Hash
来源：http://dali.sufxvd.cn/Article/details/gtizdklvlv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jlsjyb.cn/Article/details/gtuvzqtalw.html

[N08] 生成全排列
来源：http://dali.pengpengdd.cyou/Article/details/gtfnujbmcr.html

Py:   itertools.permutations(arr)
来源：http://dali.sxryk.cn/Article/details/gtibfquvzt.html

PHP:  // 手写递归交换
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrzhigrp.html

JS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtgfzqqqiw.html

TS:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtiebdwilq.html

Java: // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtnbtymgyv.html

Go:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtxiiujxac.html

Ruby: arr.permutation.to_a
来源：http://dali.fzhhl.top/Article/details/gttgzwvlkp.html

C#:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtcuvkxcpv.html

[N09] 栈与队列
来源：http://dali.ybcxt.top/Article/details/gtvvwfrxob.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daxiang520.top/Article/details/gtwqnxqqmn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtdofgfm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gtbgjghgal.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jlsjyb.cn/Article/details/gtlzmhzdix.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nwbrower.top/Article/details/gtmjxafvlg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyibwdcbr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gtcihyrrqz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.quarkkingdee.top/Article/details/gtmmvixhve.html

[N10] 链表节点定义
来源：http://dali.yvedp.cn/Article/details/gthuwogvru.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pengpengdd.cyou/Article/details/gtcnqcfajk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nwbrower.top/Article/details/gtcihbyhyf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gzhubu.top/Article/details/gtzywexjxu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhengqikj.top/Article/details/gtauoidfqk.html

Java: class Node { int v; Node next; }
来源：http://dali.daxiang520.top/Article/details/gtbqbohrwg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsecjxnfq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.vqdsnc.cn/Article/details/gtpchafrjo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shuidangran.top/Article/details/gtndztxeff.html

[N11] 二叉树中序遍历
来源：http://dali.hywenlv.cn/Article/details/gtjoscmdfz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jiagoushi.top/Article/details/gtayfivtdc.html

PHP:  // 手写递归函数
来源：http://dali.shuidangran.top/Article/details/gtvejvbdgr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gtsnsrujzg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gtyijsupkv.html

Java: // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gtbopexrbl.html

Go:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtyguplcaz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuanzx.com/Article/details/gtmpvaeedb.html

C#:   // 手写递归
来源：http://dali.316326.xyz/Article/details/gtrszwjpbd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhengqikj.top/Article/details/gtdsgzuzsh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.kuanghao11.cn/Article/details/gtkggpxnku.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zycfv.cn/Article/details/gtqdpncpvu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sysykeji.top/Article/details/gtnhceikcm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gtxeahtlqs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gtbpilksny.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hywenlv.cn/Article/details/gttccasdkf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.mhx1999.top/Article/details/gtirfdmfdi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gtaxxrangp.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtkrlhmlrm.html

O. 并发与异步
来源：http://dali.aizwys.cn/Article/details/gtyyckfcnm.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtgfffyfjf.html

[O01] 启动一个线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyhvequvx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.c1oappe.top/Article/details/gtdhlxyims.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nwbrower.top/Article/details/gtwvqxlrhx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cashguo.top/Article/details/gtatxllons.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gtpfbnlwhr.html

Java: new Thread(() -> f()).start()
来源：http://dali.snrcjt.cn/Article/details/gtfndbbmdh.html

Go:   go f()
来源：http://dali.yuxming.cn/Article/details/gtnamexkyf.html

Ruby: Thread.new { f }
来源：http://dali.meibo888.top/Article/details/gtoctqzmej.html

C#:   Task.Run(() => F());
来源：http://dali.316326.xyz/Article/details/gtebsehjgm.html

[O02] 使用线程池
来源：http://dali.zhiwuduotai.top/Article/details/gttvwqxwka.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yangfankeji.com/Article/details/gtlrzmebeh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gtvmyxboht.html

JS:   // worker_threads 线程池
来源：http://dali.cashguo.top/Article/details/gtjnyvinea.html

TS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gtmyvbevzh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ehwqpu.com/Article/details/gtkvsqqnfx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sxryk.cn/Article/details/gtdmnazrie.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj202588.top/Article/details/gtfhtaibsv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ppjwa.cn/Article/details/gtgwzgsyid.html

[O03] 加锁保护共享数据
来源：http://dali.shangyingyoupin.top/Article/details/gtvfydvigr.html

Py:   with lock: shared += 1
来源：http://dali.jinqigfzy.top/Article/details/gthguzdgfp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zycfv.cn/Article/details/gtnskrmlpe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jlsjyb.cn/Article/details/gtliwvsqid.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gtbdpboksj.html

Java: synchronized (this) { shared++; }
来源：http://dali.tanke756.top/Article/details/gtycfeyhdn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258888.top/Article/details/gtjvrmpmvk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jianghu66.top/Article/details/gtvlanzrqx.html

C#:   lock (gate) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtftquvcew.html

[O04] 定义异步函数并等待
来源：http://dali.ivvv.top/Article/details/gtquvgwmjj.html

Py:   async def f():⏎    await g()
来源：http://dali.jiagoushi.top/Article/details/gtktqsdcoz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zycfv.cn/Article/details/gtsviqkvhw.html

JS:   async function f() { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gtojrviggo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gtvdfdfwjm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ppjwa.cn/Article/details/gtoznjaunr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xinyue.icu/Article/details/gtijmzdyfj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.haohaochexian.top/Article/details/gtlnyurkrt.html

C#:   async Task F() { await G(); }
来源：http://dali.dianchejie.cn/Article/details/gtuggrixhm.html

[O05] 并发执行并等待全部完成
来源：http://dali.yueranfly.top/Article/details/gtzbtllfnz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jiagoushi.top/Article/details/gtjbharuif.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shanyushiyangkeji.top/Article/details/gteohdxluh.html

JS:   await Promise.all(tasks)
来源：http://dali.yongpay.top/Article/details/gtllktmnfa.html

TS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gtueqcejtm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.smart0.xyz/Article/details/gtyygsdtza.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj202588.top/Article/details/gtrdntscna.html

Ruby: threads.map(&:join)
来源：http://dali.sufxvd.cn/Article/details/gtgdebafrr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.dianchejie.cn/Article/details/gtkzycbhmm.html

[O06] 使用进程池
来源：http://dali.wangdashe.top/Article/details/gtiwqldmim.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigufen.top/Article/details/gtnyopykwl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shangyingyoupin.top/Article/details/gtvexaicgn.html

JS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gtxlvkobec.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258888.top/Article/details/gtzysqagun.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ivvv.top/Article/details/gtfkgbyvvm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zycfv.cn/Article/details/gtbzchevgd.html

Ruby: // fork 块
来源：http://dali.zdqjudy.top/Article/details/gteacpwlca.html

C#:   Parallel.For
来源：http://dali.sysykeji.top/Article/details/gthpwnkvbo.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtunszyaeb.html

P. 常用工具函数
来源：http://dali.sweek.top/Article/details/gtvshfvqzq.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gttxrqotsl.html

[P01] 生成 UUID
来源：http://dali.kuanghao11.cn/Article/details/gtbdmqfnue.html

Py:   str(uuid.uuid4())
来源：http://dali.shzxlz.cn/Article/details/gtznkyroql.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yvedp.cn/Article/details/gtwmcyufus.html

JS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gttfcxbqof.html

TS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtzmmxdaca.html

Java: UUID.randomUUID().toString()
来源：http://dali.xylfe.cn/Article/details/gthlkpprxt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shangyingyoupin.top/Article/details/gtnlaujtzi.html

Ruby: SecureRandom.uuid
来源：http://dali.ppjwa.cn/Article/details/gtrsfjjnal.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.smart0.xyz/Article/details/gtkggluirs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuanzhike.top/Article/details/gtlqzduwig.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xziqi.cn/Article/details/gttsncmbzh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cucudq.cn/Article/details/gtudjdeknm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.c1oappe.top/Article/details/gtcdtdfpgn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.haohaochexian.top/Article/details/gtslkincio.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtoufpmpgr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.0kj1m.cn/Article/details/gtyqtvebuk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xinyue.icu/Article/details/gtxbqtewsb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuanzhike.top/Article/details/gtpwbousfk.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gtgighexcw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pycfn.com/Article/details/gtzhurhrkl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxdphkya.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmuxnyahj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gtjwyysuud.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nanxinkj.top/Article/details/gtviwymnsf.html


<!-- 参考信息 -->