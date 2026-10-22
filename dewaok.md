代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.bjfxy.top/Article/details/gtvllwbono.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenjidiqi.icu/Article/details/gtwclhxewu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258888.top/Article/details/gtgdjsxygp.html

[L06] 解析响应为 JSON
来源：http://dali.fzhhl.top/Article/details/gthejdydvc.html

Py:   resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtaibduxvt.html

PHP:  json_decode($body, true);
来源：http://dali.wangdashe.top/Article/details/gtxgufwrxq.html

JS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtchjnckba.html

TS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gtizmzuofe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtqqzfkkdm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.bjfxy.top/Article/details/gtoitcygws.html

Ruby: JSON.parse(resp.body)
来源：http://dali.mhx1999.top/Article/details/gtpsiivrsj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.fengsongda.top/Article/details/gtvjwdusov.html

[L07] 处理 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gtdgoptnai.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xylfe.cn/Article/details/gtshrhtepc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlprwzlbn.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gteimvmygj.html

TS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtlrvgfkrl.html

Java: resp.statusCode()
来源：http://dali.hnxiangtu.top/Article/details/gtxqqaxyor.html

Go:   resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gtaodwtyqk.html

Ruby: resp.code.to_i
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkawwvaqb.html

C#:   (int)resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gtoziucngb.html

[L08] 并发请求多个地址
来源：http://dali.xuetiantiany.cn/Article/details/gtvmvtpoay.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhiwuduotai.top/Article/details/gtoxnzenhr.html

PHP:  curl_multi_init() 系列
来源：http://dali.ydzc1.top/Article/details/gtdxtdtaus.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzgmuiyp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtaktfjowc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258.top/Article/details/gtzuxwzsqn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gotoacloud.top/Article/details/gtzvrswfsl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ivvv.top/Article/details/gtwnrpmsto.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.redwolf501.top/Article/details/gtoctvtwxc.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtpsqtoiip.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuetiantiany.cn/Article/details/gthtmeqbxn.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtrqhotbth.html

[M01] 读取命令行参数
来源：http://dali.ivvv.top/Article/details/gtofodvjkd.html

Py:   sys.argv[1:]
来源：http://dali.9152youxi.cn/Article/details/gtcouzbscf.html

PHP:  $argv;  $argc;
来源：http://dali.cdnleiting.top/Article/details/gtwnkugirw.html

JS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtcxyrjhxk.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gthpcjjhhg.html

Java: args 数组（main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gtrrzkgzac.html

Go:   os.Args[1:]
来源：http://dali.gogol.net.cn/Article/details/gtlyjcvvjg.html

Ruby: ARGV
来源：http://dali.yuxming.cn/Article/details/gtoceaasgq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gtfdliynmx.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsgkzeic.html

Py:   os.environ.get("HOME")
来源：http://dali.sweek.top/Article/details/gtragjydxc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtqzuyuwds.html

JS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gtdonefhyj.html

TS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtvjjzegvn.html

Java: System.getenv("HOME")
来源：http://dali.yvedp.cn/Article/details/gtcshhtagp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zycfv.cn/Article/details/gtghpfpruk.html

Ruby: ENV["HOME"]
来源：http://dali.iojbl.cn/Article/details/gtuywdudvp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtgslhpzvy.html

[M03] 执行外部命令
来源：http://dali.shuidangran.top/Article/details/gthsbjdhtr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yangfankeji.com/Article/details/gthvfnkbic.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetyhtfwb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtftdvymub.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gtlzbaipxe.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pycfn.com/Article/details/gthspjzfgb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jlsjyb.cn/Article/details/gtzrfpmezk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhiwuduotai.top/Article/details/gtmkaqbzin.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xuetiantiany.cn/Article/details/gtexaxksiv.html

[M04] 获取当前工作目录
来源：http://dali.cashguo.top/Article/details/gtatwwntrz.html

Py:   os.getcwd()
来源：http://dali.snrcjt.cn/Article/details/gtxseoikpi.html

PHP:  getcwd();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtertgftwa.html

JS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gtxuvlqfbe.html

TS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gtwonekxpj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.meibo888.top/Article/details/gtuuobvynd.html

Go:   os.Getwd()
来源：http://dali.hysaishi.cn/Article/details/gtwjowimul.html

Ruby: Dir.pwd
来源：http://dali.yanxiufei.cn/Article/details/gtszinqbwd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aibaodan.cn/Article/details/gtucxfpmra.html

[M05] 设置退出码
来源：http://dali.shangyingyoupin.top/Article/details/gtinkwkhup.html

Py:   sys.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtlpkgfmpx.html

PHP:  exit(1);
来源：http://dali.ivvv.top/Article/details/gtwlxnlnis.html

JS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtbtuempur.html

TS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtnicdobxq.html

Java: System.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtycqcmeln.html

Go:   os.Exit(1)
来源：http://dali.sxryk.cn/Article/details/gtyscltruz.html

Ruby: exit 1
来源：http://dali.iojbl.cn/Article/details/gtdwzgylro.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nwbrower.top/Article/details/gtzgstiniz.html

[M06] 向标准错误输出
来源：http://dali.fzhhl.top/Article/details/gtcnfiewyo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ppjwa.cn/Article/details/gtavsevrgy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fengsongda.top/Article/details/gtbifyivoo.html

JS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtoxpcerjn.html

TS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gthzdumbtd.html

Java: System.err.println("err")
来源：http://dali.shuidangran.top/Article/details/gtvcoxqdbr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofvlqons.html

Ruby: warn "err"
来源：http://dali.c1oappe.top/Article/details/gttwnwvmsl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.svipenyu.cn/Article/details/gthccjsxsr.html

[M07] 判断是否为主入口
来源：http://dali.nwbrower.top/Article/details/gtoiutngrd.html

Py:   if __name__ == "__main__":
来源：http://dali.cashguo.top/Article/details/gtmrelkryr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.quarkkingdee.top/Article/details/gtjvjjnahs.html

JS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gtjssouwrb.html

TS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtymnkifut.html

Java: public static void main(String[] args)
来源：http://dali.vqdsnc.cn/Article/details/gtzpsangvi.html

Go:   func main()
来源：http://dali.iojbl.cn/Article/details/gtjhckwnef.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ybcxt.top/Article/details/gtbpzizfqu.html

C#:   static void Main(string[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gtwdrhocje.html

[M08] 获取系统与运行时信息
来源：http://dali.zdqjudy.top/Article/details/gtvfjgnqry.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhixingplan.top/Article/details/gtxtwnefvj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gtqkxmiwiz.html

JS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gthvfsciah.html

TS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtywgqrzvz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxgdvufjq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.iojbl.cn/Article/details/gtresjtcqd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlpaceae.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ybcxt.top/Article/details/gtacoqtqsy.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtafyboydf.html

N. 数据结构与算法
来源：http://dali.guowangkeji.top/Article/details/gtmjqyksca.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcoqjyad.html

[N01] 二分查找（有序数组）
来源：http://dali.tianlin.xyz/Article/details/gtwaonxsqs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj202588.top/Article/details/gtlehkvufi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xziqi.cn/Article/details/gtkdmholna.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtyswoyjwv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnumxjyqa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtzpuuuusg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtxzqdlpwr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tanke756.top/Article/details/gtqhucyfqn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtrqcqqwby.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgfzy.top/Article/details/gthdugfppg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtjavxudjc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258888.top/Article/details/gtysxtrots.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtkwavmgkl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gtxowrjmbn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sxryk.cn/Article/details/gtzfxikyfq.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gtpohadbbh.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gtgwrsvktb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xylfe.cn/Article/details/gtkhrmtnil.html

[N03] 快速排序（分治示例）
来源：http://dali.yuanzhike.top/Article/details/gtxujrnzwq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfyjvqdu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pycfn.com/Article/details/gtqvkjrrzy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gtziueqpne.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gtdanpkvux.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fzhhl.top/Article/details/gtplqpnrdv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.svipenyu.cn/Article/details/gtzlkqdbyq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hywenlv.cn/Article/details/gtqbpyivmu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aibaodan.cn/Article/details/gtjlgdzhcf.html

[N04] 斐波那契数列
来源：http://dali.jqgufenzy.top/Article/details/gtytolyckt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gtctemqhns.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gthliynrfo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gtkhxfcykb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhcjrhuo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gtlzfzcumz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zycfv.cn/Article/details/gtmcbekvkd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gtcybynamc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtpdsxyqfr.html

[N05] 最大公约数
来源：http://dali.dashuyun.cn/Article/details/gtftnhbqym.html

Py:   math.gcd(a, b)
来源：http://dali.zycfv.cn/Article/details/gtlxoswiwo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtiwgcxkec.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtbrbgmsme.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gtyhgpdtob.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dianchejie.cn/Article/details/gtkldvwtqm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sysykeji.top/Article/details/gtjibdmghr.html

Ruby: a.gcd(b)
来源：http://dali.ppjwa.cn/Article/details/gtofbwtudc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.snrcjt.cn/Article/details/gtlmxvxpur.html

[N06] 判断回文字符串
来源：http://dali.wangdashe.top/Article/details/gtkncrnlqo.html

Py:   s == s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gtjxmmpyvh.html

PHP:  $s === strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gtsorttmfx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtpafgrnfb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtlifjgekw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tianlin.xyz/Article/details/gtsiljoutl.html

Go:   // 双指针从两端比较
来源：http://dali.cucudq.cn/Article/details/gtmxlroyua.html

Ruby: s == s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtfkmnrjno.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gtaufywlqe.html

[N07] 两数之和（返回下标）
来源：http://dali.guannengcc.top/Article/details/gtiyoxzkbq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aibaodan.cn/Article/details/gtexajavox.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.birdmap.top/Article/details/gttwjklhqg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zycfv.cn/Article/details/gtzqjqzmtf.html

TS:   // 手写 Map<string, number>
来源：http://dali.bjfxy.top/Article/details/gtgnvfyoqo.html

Java: // 手写 HashMap
来源：http://dali.smart0.xyz/Article/details/gtqvavfizc.html

Go:   // 手写 map[int]int
来源：http://dali.aibaodan.cn/Article/details/gtgijheeam.html

Ruby: // 手写 Hash
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykdgkdjx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinghuilouyu.cn/Article/details/gtegvthzvb.html

[N08] 生成全排列
来源：http://dali.yueranfly.top/Article/details/gtkkejdrkq.html

Py:   itertools.permutations(arr)
来源：http://dali.sweek.top/Article/details/gtzuxoyuyh.html

PHP:  // 手写递归交换
来源：http://dali.chenlongwang.top/Article/details/gtibjutsop.html

JS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtiozqhvof.html

TS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtryptvadt.html

Java: // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gteznzhmxs.html

Go:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gthwmmswns.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gtowfpozge.html

C#:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtleczfxkg.html

[N09] 栈与队列
来源：http://dali.ivvv.top/Article/details/gtowmfwnjo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenlongwang.top/Article/details/gttsebmndx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gttjlgylgn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtwdnwhoie.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hongshengwenyu.top/Article/details/gttlxwzmtj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.svipenyu.cn/Article/details/gtoozycbff.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.quarkkingdee.top/Article/details/gttwqetdjl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.meibo888.top/Article/details/gtikkrnuha.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.c1oappe.top/Article/details/gtslazlzkt.html

[N10] 链表节点定义
来源：http://dali.jqgfzy.top/Article/details/gtffbljngy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jlsjyb.cn/Article/details/gteeasnjrb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtawxboeab.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yongpay.top/Article/details/gtwexqzlir.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuanzx.com/Article/details/gtcsxdycrd.html

Java: class Node { int v; Node next; }
来源：http://dali.shzxlz.cn/Article/details/gtmmozfowc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulcwbvoi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pengpengdd.cyou/Article/details/gthvnouvvq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yangfankeji.com/Article/details/gtqlmrfgfm.html

[N11] 二叉树中序遍历
来源：http://dali.birdmap.top/Article/details/gtwotzrxyg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnqzz.top/Article/details/gtxhluijsg.html

PHP:  // 手写递归函数
来源：http://dali.ydzc1.top/Article/details/gtnoyxqiex.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shzxlz.cn/Article/details/gtnmzhvwct.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gtrkubvjir.html

Java: // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gteettezrm.html

Go:   // 手写递归
来源：http://dali.sysykeji.top/Article/details/gtgvmfzkwl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yvedp.cn/Article/details/gtpqcjmpep.html

C#:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gtotunxxmc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtbrhjay.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fzhhl.top/Article/details/gtszthwsbu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gaohongyu789.top/Article/details/gtkynmussf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gtixgtzrhs.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gtzlusbfrd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjbymyfr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pengpengdd.cyou/Article/details/gtivceyfaw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hfpthk.cn/Article/details/gtaodzbcst.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gtxkuowviy.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtfaqwckch.html

O. 并发与异步
来源：http://dali.ybcxt.top/Article/details/gthdzgfkgm.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gthfkoqkif.html

[O01] 启动一个线程
来源：http://dali.hnxiangtu.top/Article/details/gtoaqkfnsw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hfpthk.cn/Article/details/gtgpqdeoet.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuanzhike.top/Article/details/gtsansobjt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbldbbma.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gtitvzfpyk.html

Java: new Thread(() -> f()).start()
来源：http://dali.yanxiufei.cn/Article/details/gtjuerkfeo.html

Go:   go f()
来源：http://dali.jlsjyb.cn/Article/details/gtizqolpun.html

Ruby: Thread.new { f }
来源：http://dali.guannengcc.top/Article/details/gthapxyqlj.html

C#:   Task.Run(() => F());
来源：http://dali.cashguo.top/Article/details/gtftkyrpbx.html

[O02] 使用线程池
来源：http://dali.gogol.net.cn/Article/details/gtubuvgdlx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yanxiufei.cn/Article/details/gthjrgbspn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhoulong.xyz/Article/details/gtywobcbcv.html

JS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gtlpybyyzb.html

TS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gtwhcogkib.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sufxvd.cn/Article/details/gthtiqbyei.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sxryk.cn/Article/details/gtuijloacf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.mhx1999.top/Article/details/gtzpwcfbja.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.haohaochexian.top/Article/details/gtauqsmisw.html

[O03] 加锁保护共享数据
来源：http://dali.hnqzz.top/Article/details/gtidbndkzd.html

Py:   with lock: shared += 1
来源：http://dali.xziqi.cn/Article/details/gtiispylje.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gtqwzavugf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hysaishi.cn/Article/details/gttfbdoafn.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gtjvklydpu.html

Java: synchronized (this) { shared++; }
来源：http://dali.sweek.top/Article/details/gtyzkvqdad.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.bjfxy.top/Article/details/gtbouynynu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxuanxn.top/Article/details/gtaamspmmp.html

C#:   lock (gate) { shared++; }
来源：http://dali.316326.xyz/Article/details/gtyhpfikyv.html

[O04] 定义异步函数并等待
来源：http://dali.yangfankeji.com/Article/details/gtjjutocdx.html

Py:   async def f():⏎    await g()
来源：http://dali.hammf.cn/Article/details/gtsyckayma.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgfzy.top/Article/details/gtxropzapq.html

JS:   async function f() { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gtowtjwmao.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yonumen.top/Article/details/gtwnqriwgy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gtvmsfoqen.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.kuanghao11.cn/Article/details/gtjzmvjkny.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pycfn.com/Article/details/gtmeogkiap.html

C#:   async Task F() { await G(); }
来源：http://dali.aibaodan.cn/Article/details/gtcpzzofsq.html

[O05] 并发执行并等待全部完成
来源：http://dali.hywenlv.cn/Article/details/gtsvpfyesa.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shzxlz.cn/Article/details/gtatxwrncm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tianlin.xyz/Article/details/gtdhlmxqiy.html

JS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gttwgbvrjn.html

TS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gtbvoaxdyl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenjidiqi.icu/Article/details/gtlrnyzcds.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.smart0.xyz/Article/details/gtukxcwddx.html

Ruby: threads.map(&:join)
来源：http://dali.jyoumei.cn/Article/details/gtziedtpbi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jiagoushi.top/Article/details/gtzqhbvkzv.html

[O06] 使用进程池
来源：http://dali.hnqzz.top/Article/details/gtdlcqlgga.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fzhhl.top/Article/details/gtynjbsbye.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yvedp.cn/Article/details/gtfnilkrhq.html

JS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmpnysba.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gtbwhamzfr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhongyouzk.top/Article/details/gtpjuvtklv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zycfv.cn/Article/details/gtthawvfly.html

Ruby: // fork 块
来源：http://dali.sxryk.cn/Article/details/gtxwvxtqfy.html

C#:   Parallel.For
来源：http://dali.zycfv.cn/Article/details/gtjjowbabj.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtoskfnggx.html

P. 常用工具函数
来源：http://dali.yuanzhike.top/Article/details/gtqztzjaoy.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtmytqnuvn.html

[P01] 生成 UUID
来源：http://dali.gogol.net.cn/Article/details/gtbsjbpwlv.html

Py:   str(uuid.uuid4())
来源：http://dali.c1oappe.top/Article/details/gtxhbibbbs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.c1oappe.top/Article/details/gtponugdzy.html

JS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gtuaupoaed.html

TS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtgrkfqwgn.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpxrakhu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tanke756.top/Article/details/gtfizzncaq.html

Ruby: SecureRandom.uuid
来源：http://dali.sysykeji.top/Article/details/gtfrtpfdny.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sxryk.cn/Article/details/gtsgrxplmw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumfzeded.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gogol.net.cn/Article/details/gtumjgfnno.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258888.top/Article/details/gtmzcztqlo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.c1oappe.top/Article/details/gtlthizzgd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigufen.top/Article/details/gtqleqjzob.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cashguo.top/Article/details/gtmfhhrukq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cucudq.cn/Article/details/gtmrnhgjsm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.aizwys.cn/Article/details/gttbdjfpqe.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.birdmap.top/Article/details/gtsijgnwgi.html

[P03] 生成短随机字符串
来源：http://dali.nwbrower.top/Article/details/gtxkztrmsb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinqigfzy.top/Article/details/gtdyaibghf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.c1oappe.top/Article/details/gtzwyfzlsr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtfoztjxqc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gtmcxzbajd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cucudq.cn/Article/details/gtmeopmtzu.html


<!-- 参考信息 -->