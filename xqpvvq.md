代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hnxiangtu.top/Article/details/gtsfufcvwo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.mhx1999.top/Article/details/gtuitfskgx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtkhqmaitm.html

[L06] 解析响应为 JSON
来源：http://dali.zdqjudy.top/Article/details/gtjhdxuxbi.html

Py:   resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtntqaivkc.html

PHP:  json_decode($body, true);
来源：http://dali.chenlongwang.top/Article/details/gtslheksob.html

JS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gtksfcvfng.html

TS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtdgcmkymt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj202588.top/Article/details/gtzekgoiko.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jlsjyb.cn/Article/details/gtnpwnjwpt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cashguo.top/Article/details/gtcuwbkxib.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ehwqpu.com/Article/details/gtobkqrvet.html

[L07] 处理 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gtjhwnclwh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.snrcjt.cn/Article/details/gthhvavhsi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.mhx1999.top/Article/details/gtctfyzmcs.html

JS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gtvwkyoijb.html

TS:   resp.ok;  resp.status
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpretcnq.html

Java: resp.statusCode()
来源：http://dali.yj20258.top/Article/details/gtbvvnuswu.html

Go:   resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gtkedyqmbh.html

Ruby: resp.code.to_i
来源：http://dali.havefunace.top/Article/details/gtqkdnpxfy.html

C#:   (int)resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gtlrsodeeh.html

[L08] 并发请求多个地址
来源：http://dali.iojbl.cn/Article/details/gtentdrqow.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jyoumei.cn/Article/details/gtweqnmiuz.html

PHP:  curl_multi_init() 系列
来源：http://dali.andypj.xyz/Article/details/gtjgkqgqlk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtcbgnuoke.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtvxjgkisc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sxryk.cn/Article/details/gtcxvdhcdl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxuanxn.top/Article/details/gttragiipv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tianlin.xyz/Article/details/gtrsbmfojh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtmruqezxw.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtmjcfcakv.html

M. 命令行 / 进程 / 环境
来源：http://dali.vqdsnc.cn/Article/details/gtkshpzfci.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gthhjrjdbn.html

[M01] 读取命令行参数
来源：http://dali.snrcjt.cn/Article/details/gtghomussf.html

Py:   sys.argv[1:]
来源：http://dali.c1oappe.top/Article/details/gtubogrjvk.html

PHP:  $argv;  $argc;
来源：http://dali.chenjidiqi.icu/Article/details/gtocdrqlqk.html

JS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gtsjattjrz.html

TS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gtlypqwxcw.html

Java: args 数组（main 方法参数）
来源：http://dali.pycfn.com/Article/details/gtrorydntw.html

Go:   os.Args[1:]
来源：http://dali.tian-w.cn/Article/details/gtntuxxgll.html

Ruby: ARGV
来源：http://dali.hywenlv.cn/Article/details/gtzljknvul.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yongpay.top/Article/details/gthhdyeazn.html

[M02] 读取环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtuzphwyya.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258.top/Article/details/gtechecacb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gthjoyvodd.html

JS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gthpeglyuk.html

TS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtqnogodal.html

Java: System.getenv("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtrnmwcyvk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gthqnmqzig.html

Ruby: ENV["HOME"]
来源：http://dali.cashguo.top/Article/details/gtytlzbfru.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtnwdpplem.html

[M03] 执行外部命令
来源：http://dali.daxiang520.top/Article/details/gtqfnanblt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gtxzdekqdx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.wangshuangyany.cn/Article/details/gthejrecqq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gtxzsjeijr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gtnhfnsrky.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jiagoushi.top/Article/details/gtecvlkbiz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jiagoushi.top/Article/details/gtmfudebyg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ppjwa.cn/Article/details/gtuidpkxki.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhengqikj.top/Article/details/gtllfhkeso.html

[M04] 获取当前工作目录
来源：http://dali.gzhubu.top/Article/details/gthaysbsku.html

Py:   os.getcwd()
来源：http://dali.zycfv.cn/Article/details/gtewmlgrwl.html

PHP:  getcwd();
来源：http://dali.guannengcc.top/Article/details/gtwdiwojmu.html

JS:   process.cwd()
来源：http://dali.jianghu66.top/Article/details/gtkmwwsoqz.html

TS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gttmlkypyl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbboxussz.html

Go:   os.Getwd()
来源：http://dali.sxryk.cn/Article/details/gtjeguqxqo.html

Ruby: Dir.pwd
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtvndbdf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shuidangran.top/Article/details/gtvzhoosky.html

[M05] 设置退出码
来源：http://dali.zhongyouzk.top/Article/details/gtrxosxbxh.html

Py:   sys.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtwvbqsmuy.html

PHP:  exit(1);
来源：http://dali.nanxuanxn.top/Article/details/gtundnxjvc.html

JS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtydchqvub.html

TS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gtpwlocoth.html

Java: System.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtzulbnknq.html

Go:   os.Exit(1)
来源：http://dali.yuxming.cn/Article/details/gtxfxcsdxf.html

Ruby: exit 1
来源：http://dali.shzxlz.cn/Article/details/gtypgxxubu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxinkj.top/Article/details/gtssihmuzz.html

[M06] 向标准错误输出
来源：http://dali.guowangkeji.top/Article/details/gtledxdulf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gtqxnzdwtu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ppjwa.cn/Article/details/gtbzfplovg.html

JS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gtghqtzcbi.html

TS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gtjhsprvgm.html

Java: System.err.println("err")
来源：http://dali.zhongyouzk.top/Article/details/gtutbitkse.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.birdmap.top/Article/details/gtfbkoziff.html

Ruby: warn "err"
来源：http://dali.cheryme.top/Article/details/gtwgfhyzxi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtvemicjcs.html

[M07] 判断是否为主入口
来源：http://dali.birdmap.top/Article/details/gtowqvuvpz.html

Py:   if __name__ == "__main__":
来源：http://dali.sweek.top/Article/details/gtgavyipce.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yonumen.top/Article/details/gtzmccdvgp.html

JS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gtgbefquue.html

TS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gtmvzanjtu.html

Java: public static void main(String[] args)
来源：http://dali.316326.xyz/Article/details/gtwtkvhzmg.html

Go:   func main()
来源：http://dali.sweek.top/Article/details/gtidnrkcik.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinghuilouyu.cn/Article/details/gtokavejhh.html

C#:   static void Main(string[] args)
来源：http://dali.ppjwa.cn/Article/details/gtlbdicmpm.html

[M08] 获取系统与运行时信息
来源：http://dali.hnqzz.top/Article/details/gtzkwwcpgl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuetiantiany.cn/Article/details/gtdcjnvdru.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gtydbnjmak.html

JS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gtczzwjxlp.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtgtgosyjv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yongpay.top/Article/details/gtnnbpqwzt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sweek.top/Article/details/gtvqqvzdnq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxinkj.top/Article/details/gtwpuckltw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pengpengdd.cyou/Article/details/gtyattbmnh.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtbglztabt.html

N. 数据结构与算法
来源：http://dali.jinqigfzy.top/Article/details/gtqscuyrbl.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtpcxdqtqm.html

[N01] 二分查找（有序数组）
来源：http://dali.shzxlz.cn/Article/details/gtkheagfzo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cheryme.top/Article/details/gtatrumrnp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gthstpbudi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gtxfzbclpz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jiagoushi.top/Article/details/gtaccmbuhx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtsjujghgm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtlzlwroot.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuetiantiany.cn/Article/details/gttjlvxrvw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtjzsmfizn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sysykeji.top/Article/details/gtzhybemio.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gttomzbuzy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aizwys.cn/Article/details/gtdifjvrdu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gtpyuogpxw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtwpmsgdva.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhengqikj.top/Article/details/gtddcqsfpb.html

Go:   slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtzatblivj.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gtnxzrhowx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.andypj.xyz/Article/details/gtqyhskrow.html

[N03] 快速排序（分治示例）
来源：http://dali.yj20258.top/Article/details/gtdmvtskdw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xziqi.cn/Article/details/gtzvobgedq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangtech.top/Article/details/gthsuovsnb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gtmxycoxgi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamdpnwbm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnqzz.top/Article/details/gtshuenexk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nwbrower.top/Article/details/gtmeusnlnh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yongpay.top/Article/details/gtjrcqioac.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuxming.cn/Article/details/gtvjicvgna.html

[N04] 斐波那契数列
来源：http://dali.jyoumei.cn/Article/details/gtuazpnnlx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gtyzwiwgxi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fengsongda.top/Article/details/gtsdbjltab.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtleeceivk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtcnuapfav.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gtewrpcgur.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.andypj.xyz/Article/details/gtnzlkyxij.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtofegydto.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtmitfnshd.html

[N05] 最大公约数
来源：http://dali.aibaodan.cn/Article/details/gtxcccssno.html

Py:   math.gcd(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtzbaqzzfu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aizwys.cn/Article/details/gthvqzqcqi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gotoacloud.top/Article/details/gtuyhtxren.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gtzvlrqhrs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jianghu66.top/Article/details/gtvgiwqmxa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnxiangtu.top/Article/details/gtldybbefo.html

Ruby: a.gcd(b)
来源：http://dali.yj202588.top/Article/details/gtjznpnktr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gtllhvwbkc.html

[N06] 判断回文字符串
来源：http://dali.jinqigfzy.top/Article/details/gtdjxmfama.html

Py:   s == s[::-1]
来源：http://dali.daxiang520.top/Article/details/gttoqqgbxb.html

PHP:  $s === strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gtxbwkbvic.html

JS:   s === [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtcsigeaqw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtaofrirpn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuanzx.com/Article/details/gtxeivdrgv.html

Go:   // 双指针从两端比较
来源：http://dali.jlsjyb.cn/Article/details/gtncycuxph.html

Ruby: s == s.reverse
来源：http://dali.sweek.top/Article/details/gturwoscoe.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gtaukpirvn.html

[N07] 两数之和（返回下标）
来源：http://dali.nwbrower.top/Article/details/gtwsmwamer.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwemiunyv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj202588.top/Article/details/gtktnicbbk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yueranfly.top/Article/details/gtutuztnej.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj202588.top/Article/details/gtivubwuym.html

Java: // 手写 HashMap
来源：http://dali.yongpay.top/Article/details/gtdsvuxmkh.html

Go:   // 手写 map[int]int
来源：http://dali.xuanzx.com/Article/details/gtrprbzfcr.html

Ruby: // 手写 Hash
来源：http://dali.ppjwa.cn/Article/details/gtypcblllo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sufxvd.cn/Article/details/gtignyijbo.html

[N08] 生成全排列
来源：http://dali.pycfn.com/Article/details/gtxyjwenzp.html

Py:   itertools.permutations(arr)
来源：http://dali.yongpay.top/Article/details/gtervefpgq.html

PHP:  // 手写递归交换
来源：http://dali.ehwqpu.com/Article/details/gtqsldrmqd.html

JS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtfcahjcts.html

TS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gteokpkhsy.html

Java: // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtqlnsuyvy.html

Go:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gthgofidcz.html

Ruby: arr.permutation.to_a
来源：http://dali.c1oappe.top/Article/details/gtrrpiylmf.html

C#:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtcvkarspw.html

[N09] 栈与队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbkyfvql.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuanzx.com/Article/details/gtxsmxgwif.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtjiwkgwuz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtpjdsbppq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tianlin.xyz/Article/details/gtkarlkugf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tianlin.xyz/Article/details/gtvjcrddtr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvlgvuqp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gtqqvvibmy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.svipenyu.cn/Article/details/gtctencadk.html

[N10] 链表节点定义
来源：http://dali.yuanzhike.top/Article/details/gtskrapyzd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhongyouzk.top/Article/details/gttubjfnqf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.daria6918.cn/Article/details/gtkywupwfu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.svipenyu.cn/Article/details/gttmwsxyjl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gotoacloud.top/Article/details/gtedeudwur.html

Java: class Node { int v; Node next; }
来源：http://dali.zycfv.cn/Article/details/gtugmnrqob.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hywenlv.cn/Article/details/gttohursyz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.smart0.xyz/Article/details/gttfnfwfmw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dashuyun.cn/Article/details/gtijbpmxju.html

[N11] 二叉树中序遍历
来源：http://dali.aibaodan.cn/Article/details/gtoqxjusmp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gzhubu.top/Article/details/gtzqvqzkfm.html

PHP:  // 手写递归函数
来源：http://dali.wangdashe.top/Article/details/gtxoihlshw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.havefunace.top/Article/details/gtptjyeuwp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gtwojtyses.html

Java: // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyebvuwji.html

Go:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gtbxnygdkm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.9152youxi.cn/Article/details/gtyitoaudv.html

C#:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtwwnsuvry.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sufxvd.cn/Article/details/gtthcxsusf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tanke756.top/Article/details/gtetjmhfvn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tanke756.top/Article/details/gtwkrtiacj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gtyrljfbeb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtvywxovnj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigsrvlek.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.feifeiyinyue.top/Article/details/gthlsubyzw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shuidangran.top/Article/details/gtprchjsws.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgufenzy.top/Article/details/gtmdzgvadb.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtgjukhqld.html

O. 并发与异步
来源：http://dali.ybcxt.top/Article/details/gtvxztiquy.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtxndmkmcg.html

[O01] 启动一个线程
来源：http://dali.jianghu66.top/Article/details/gtmswhvidb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dashuyun.cn/Article/details/gtzsxzwqjs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258888.top/Article/details/gtzjageucz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgfzy.top/Article/details/gtxlibfgqa.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gtmahkclqt.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258888.top/Article/details/gtljiprnsn.html

Go:   go f()
来源：http://dali.fzhhl.top/Article/details/gtysxdonkn.html

Ruby: Thread.new { f }
来源：http://dali.jianghu66.top/Article/details/gtcplglcmk.html

C#:   Task.Run(() => F());
来源：http://dali.xuanzx.com/Article/details/gtheeslskf.html

[O02] 使用线程池
来源：http://dali.tanke756.top/Article/details/gtqobegbxv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yvedp.cn/Article/details/gtoevdmxpp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gaohongyu789.top/Article/details/gttkslyjvm.html

JS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gtovriodhh.html

TS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gtsxtmngnv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yuxming.cn/Article/details/gtbdtbcxhr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuetiantiany.cn/Article/details/gttodiudxf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangdashe.top/Article/details/gtzhtdmnom.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tanke756.top/Article/details/gttlgsyuni.html

[O03] 加锁保护共享数据
来源：http://dali.zdqjudy.top/Article/details/gtnxruageo.html

Py:   with lock: shared += 1
来源：http://dali.sxryk.cn/Article/details/gtfqlxgqly.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinqigufen.top/Article/details/gtuxbaqjdt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.feifeiyinyue.top/Article/details/gtopiyyqwh.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbieqkcwm.html

Java: synchronized (this) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gtglpsbprv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ybcxt.top/Article/details/gtrfvsvuuf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gttrgtheqe.html

C#:   lock (gate) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gtqovhkjvm.html

[O04] 定义异步函数并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnebnqjpj.html

Py:   async def f():⏎    await g()
来源：http://dali.gotoacloud.top/Article/details/gtjxbhlpmp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.bjfxy.top/Article/details/gtbclanjwh.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258.top/Article/details/gtjelecggi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtgeiztlhv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cdnleiting.top/Article/details/gtqaxbxmxx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuanzx.com/Article/details/gtbyjdkklx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nwbrower.top/Article/details/gtqxuvbbon.html

C#:   async Task F() { await G(); }
来源：http://dali.sxryk.cn/Article/details/gtnpziprgc.html

[O05] 并发执行并等待全部完成
来源：http://dali.hongshengwenyu.top/Article/details/gtymagpcyl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sufxvd.cn/Article/details/gtrtzxxrpn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhongyouzk.top/Article/details/gtcmhhsjur.html

JS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gtjwawjtfi.html

TS:   await Promise.all(tasks)
来源：http://dali.redwolf501.top/Article/details/gthopxqjit.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pycfn.com/Article/details/gtpyrhwwia.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hfpthk.cn/Article/details/gthvkriraj.html

Ruby: threads.map(&:join)
来源：http://dali.tanke756.top/Article/details/gtefderafq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sufxvd.cn/Article/details/gtarjnurrx.html

[O06] 使用进程池
来源：http://dali.yongpay.top/Article/details/gtaicneozj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yueranfly.top/Article/details/gtxvcpfmiz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cucudq.cn/Article/details/gtymiatwsk.html

JS:   // child_process / cluster 模块
来源：http://dali.yj202588.top/Article/details/gtkidipvgb.html

TS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gtsvessbms.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.havefunace.top/Article/details/gtccbwlhxf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cqqwz.cn/Article/details/gttxypncng.html

Ruby: // fork 块
来源：http://dali.sysykeji.top/Article/details/gtxsacovqm.html

C#:   Parallel.For
来源：http://dali.svipenyu.cn/Article/details/gtoshykkmh.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gteuqghuih.html

P. 常用工具函数
来源：http://dali.chenjidiqi.icu/Article/details/gtchwsoysy.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtpwcoyhui.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gtfvoximfz.html

Py:   str(uuid.uuid4())
来源：http://dali.shanyushiyangtech.top/Article/details/gtehbreqbi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gogol.net.cn/Article/details/gtkksnxspw.html

JS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gttvceucwu.html

TS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gtvnldhwzg.html

Java: UUID.randomUUID().toString()
来源：http://dali.daria6918.cn/Article/details/gtibubmglq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gtxierjbcm.html

Ruby: SecureRandom.uuid
来源：http://dali.andypj.xyz/Article/details/gtpvoyytfp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.316326.xyz/Article/details/gtmboojtxv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nanxinkj.top/Article/details/gtgyhqemgq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhiwuduotai.top/Article/details/gtqylyakcb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtmnytckxl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkfejwkp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jianghu66.top/Article/details/gttzpxubca.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xinyue.icu/Article/details/gtuwuxejmt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gtzxkonynu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sxryk.cn/Article/details/gtqsjudspy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jiagoushi.top/Article/details/gtleohfmck.html

[P03] 生成短随机字符串
来源：http://dali.nanxuanxn.top/Article/details/gthhcthwnb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ppjwa.cn/Article/details/gtyuceffwt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hongshengwenyu.top/Article/details/gtpicltlkx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtdynnolmk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigfzy.top/Article/details/gtmzueotep.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj202588.top/Article/details/gtlyzxvcyz.html


<!-- 参考信息 -->