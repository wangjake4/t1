代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.9152youxi.cn/Article/details/gt2hoznzuhu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnxiangtu.top/Article/details/gt2bhwclmqj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2ednjuoca.html

[L06] 解析响应为 JSON
来源：http://dali.gogol.net.cn/Article/details/gt2oaajtdiu.html

Py:   resp.json()
来源：http://dali.shzxlz.cn/Article/details/gt2mtamiwlq.html

PHP:  json_decode($body, true);
来源：http://dali.birdmap.top/Article/details/gt2lapoeylr.html

JS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gt2egmwbgis.html

TS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gt2laytuejg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.mhx1999.top/Article/details/gt2vppdqbor.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxinkj.top/Article/details/gt2tchksqxg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xvxjgknj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tanke756.top/Article/details/gt2erlhkfiw.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qmlyluun.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ybcxt.top/Article/details/gt2frpxvmxu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ppjwa.cn/Article/details/gt2toschepa.html

JS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gt2nohppiar.html

TS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gt2ctvpaahp.html

Java: resp.statusCode()
来源：http://dali.shuidangran.top/Article/details/gt2xckqqyzf.html

Go:   resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gt2xyjluxha.html

Ruby: resp.code.to_i
来源：http://dali.yj20258888.top/Article/details/gt2agozpusj.html

C#:   (int)resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gt2jskjeyhe.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gimpeorn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fengsongda.top/Article/details/gt2yuuornhk.html

PHP:  curl_multi_init() 系列
来源：http://dali.316326.xyz/Article/details/gt2rprybwub.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fikguhqh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gt2tqsuvqmw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tsrvjbfh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xinyue.icu/Article/details/gt2sdpvsmao.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daxiang520.top/Article/details/gt2temyookv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenzaomai.com/Article/details/gt2kmgdfucc.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2nignqcyf.html

M. 命令行 / 进程 / 环境
来源：http://dali.feifeiyinyue.top/Article/details/gt2zuwhyqmy.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2irxcxeem.html

[M01] 读取命令行参数
来源：http://dali.birdmap.top/Article/details/gt2aunvhzas.html

Py:   sys.argv[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hhvqxjmw.html

PHP:  $argv;  $argc;
来源：http://dali.jlsjyb.cn/Article/details/gt2tksrdbiu.html

JS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gt2zvfpdpka.html

TS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gt2tdubytiv.html

Java: args 数组（main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gt2ielxzcbg.html

Go:   os.Args[1:]
来源：http://dali.redwolf501.top/Article/details/gt2boghdozp.html

Ruby: ARGV
来源：http://dali.xinyue.icu/Article/details/gt2beoiatal.html

C#:   args 数组（Main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gt2qqemmuma.html

[M02] 读取环境变量
来源：http://dali.hammf.cn/Article/details/gt2wqzfcgdo.html

Py:   os.environ.get("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2pxvqjcrn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gt2qmzvlxfd.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cplfufif.html

TS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gt2gfhgrvsl.html

Java: System.getenv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gt2onmhwnad.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ofptehhe.html

Ruby: ENV["HOME"]
来源：http://dali.yongpay.top/Article/details/gt2uicfujcr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gt2qygkxgdz.html

[M03] 执行外部命令
来源：http://dali.meibo888.top/Article/details/gt2awvrdrvb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.birdmap.top/Article/details/gt2emqmtwvm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.wangdashe.top/Article/details/gt2bagilqxw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gt2mwawedqu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gt2qphajzis.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ivvv.top/Article/details/gt2cjjkadob.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fzhhl.top/Article/details/gt2rptuetno.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fzhhl.top/Article/details/gt2nesxxhdl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.0kj1m.cn/Article/details/gt2rgcoabhh.html

[M04] 获取当前工作目录
来源：http://dali.jiagoushi.top/Article/details/gt2pojktuat.html

Py:   os.getcwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2moraeiqb.html

PHP:  getcwd();
来源：http://dali.yanxiufei.cn/Article/details/gt2rrzlepxa.html

JS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gt2yjclcvzx.html

TS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gt2zobtjvxw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jlsjyb.cn/Article/details/gt2hzqyfmct.html

Go:   os.Getwd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2vprkpkvj.html

Ruby: Dir.pwd
来源：http://dali.hammf.cn/Article/details/gt2jyjdufmn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ansknidl.html

[M05] 设置退出码
来源：http://dali.svipenyu.cn/Article/details/gt2jyzegndj.html

Py:   sys.exit(1)
来源：http://dali.tanke756.top/Article/details/gt2grztrojl.html

PHP:  exit(1);
来源：http://dali.hywenlv.cn/Article/details/gt2ntcycdjj.html

JS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gt2hqpusxbm.html

TS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2adqqpkbx.html

Java: System.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2bbdndsqb.html

Go:   os.Exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2fvqsqbgd.html

Ruby: exit 1
来源：http://dali.dianchejie.cn/Article/details/gt2cqwakcqo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dianchejie.cn/Article/details/gt2xhmyikmd.html

[M06] 向标准错误输出
来源：http://dali.yangfankeji.com/Article/details/gt2gkzsmzxx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dianchejie.cn/Article/details/gt2okxnovxg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgufenzy.top/Article/details/gt2earhcpfi.html

JS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gt2ecznklqh.html

TS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gt2rsagwqbs.html

Java: System.err.println("err")
来源：http://dali.jqgufenzy.top/Article/details/gt2oavrfqtf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.vqdsnc.cn/Article/details/gt2wxqocmiu.html

Ruby: warn "err"
来源：http://dali.0kj1m.cn/Article/details/gt2sugediry.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.kuanghao11.cn/Article/details/gt2dlrncfhm.html

[M07] 判断是否为主入口
来源：http://dali.xinyue.icu/Article/details/gt2smjlywrm.html

Py:   if __name__ == "__main__":
来源：http://dali.shzxlz.cn/Article/details/gt2fhbooaza.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fzhhl.top/Article/details/gt2fjbzqxqa.html

JS:   require.main === module
来源：http://dali.yvedp.cn/Article/details/gt2dyirkxek.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gt2meqxnbvm.html

Java: public static void main(String[] args)
来源：http://dali.cdnleiting.top/Article/details/gt2nvmkzgqk.html

Go:   func main()
来源：http://dali.gaohongyu789.top/Article/details/gt2ydtnvfia.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xgmtfcce.html

C#:   static void Main(string[] args)
来源：http://dali.fengsongda.top/Article/details/gt2abohnnax.html

[M08] 获取系统与运行时信息
来源：http://dali.wangshuangyany.cn/Article/details/gt2tfujmtck.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zdqjudy.top/Article/details/gt2iowkkdes.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hfpthk.cn/Article/details/gt2zogpfcdn.html

JS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gt2itqnedev.html

TS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gt2ccfkjfsk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgfzy.top/Article/details/gt2cxnlmfjh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zdqjudy.top/Article/details/gt2ytmjwhly.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xziqi.cn/Article/details/gt2neilczys.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yongpay.top/Article/details/gt2ecyocvak.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2cvwqcevc.html

N. 数据结构与算法
来源：http://dali.dashuyun.cn/Article/details/gt2wjsdcdlf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2vazdqjsw.html

[N01] 二分查找（有序数组）
来源：http://dali.ydzc1.top/Article/details/gt2uptjbtfg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2txnhptox.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmvqcrk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gt2neupblex.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gt2tggluwkm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gt2fqdmgomn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xpzoswho.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cucudq.cn/Article/details/gt2vsmlrehm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dgbavauw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guannengcc.top/Article/details/gt2ymdurjqn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gt2iurkvlgj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhoulong.xyz/Article/details/gt2vyhlkrdc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gt2tkzyrpqf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gt2fufawqhl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhixingplan.top/Article/details/gt2btykponn.html

Go:   slices.Sort(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qkazarct.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gt2frdzwzpr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.haohaochexian.top/Article/details/gt2yithiqbz.html

[N03] 快速排序（分治示例）
来源：http://dali.zhengqikj.top/Article/details/gt2hmzaqgqo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhoulong.xyz/Article/details/gt2wnnzilpx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gaohongyu789.top/Article/details/gt2mgpmogwe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gt2brqxcmem.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gt2xfoorttz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgufenzy.top/Article/details/gt2avtdjwkj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guannengcc.top/Article/details/gt2rymvijbv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jiagoushi.top/Article/details/gt2yfsffrpf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vluxqkhd.html

[N04] 斐波那契数列
来源：http://dali.cashguo.top/Article/details/gt2gwprmiuo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gt2phzbtssj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xqkbalty.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gt2cbetvrym.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gt2rtkbqwuy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gt2myrosrsd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ppjwa.cn/Article/details/gt2udhyfxpp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fwhukjyq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gt2bjslydqt.html

[N05] 最大公约数
来源：http://dali.andypj.xyz/Article/details/gt2tmnghzwt.html

Py:   math.gcd(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cjqzklxm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ivvv.top/Article/details/gt2eaweotff.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gt2kqubties.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gt2nfyofdwe.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.redwolf501.top/Article/details/gt2kxubaxdb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.haohaochexian.top/Article/details/gt2tcgoulqo.html

Ruby: a.gcd(b)
来源：http://dali.zhixingplan.top/Article/details/gt2kmqvfskj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shzxlz.cn/Article/details/gt2lrfmeqwn.html

[N06] 判断回文字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2utxuzacw.html

Py:   s == s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gt2hylarfzx.html

PHP:  $s === strrev($s);
来源：http://dali.guannengcc.top/Article/details/gt2ekeeezrn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2lcjalzvb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gt2roohphkq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hywenlv.cn/Article/details/gt2zdkwratq.html

Go:   // 双指针从两端比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2dhivvmbe.html

Ruby: s == s.reverse
来源：http://dali.guannengcc.top/Article/details/gt2xtpllexo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yonumen.top/Article/details/gt2gzxnaotj.html

[N07] 两数之和（返回下标）
来源：http://dali.ydzc1.top/Article/details/gt2vxgkxyov.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.bjfxy.top/Article/details/gt2xlbxmimm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.vqdsnc.cn/Article/details/gt2umnsqzgb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shzxlz.cn/Article/details/gt2qxmalezi.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinqigufen.top/Article/details/gt2bpggthaf.html

Java: // 手写 HashMap
来源：http://dali.dashuyun.cn/Article/details/gt2clpmilpv.html

Go:   // 手写 map[int]int
来源：http://dali.kuanghao11.cn/Article/details/gt2duifqztw.html

Ruby: // 手写 Hash
来源：http://dali.snrcjt.cn/Article/details/gt2iwfgbcwz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shuidangran.top/Article/details/gt2snquigai.html

[N08] 生成全排列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tahtirhq.html

Py:   itertools.permutations(arr)
来源：http://dali.bjfxy.top/Article/details/gt2yzrvfxsq.html

PHP:  // 手写递归交换
来源：http://dali.nanxinkj.top/Article/details/gt2pafxgtah.html

JS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2gbisyujc.html

TS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2duncgdwm.html

Java: // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2nevtsskf.html

Go:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gt2tziiygyo.html

Ruby: arr.permutation.to_a
来源：http://dali.yangfankeji.com/Article/details/gt2igwyxqgf.html

C#:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gt2rfdbpfbx.html

[N09] 栈与队列
来源：http://dali.jinqigufen.top/Article/details/gt2qeepyics.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hywenlv.cn/Article/details/gt2fhyujsrb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gt2ysfjcmaf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gt2qxtlzhji.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jiagoushi.top/Article/details/gt2xzzvugyb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hammf.cn/Article/details/gt2yyaodmwn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhoulong.xyz/Article/details/gt2bibiboob.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gt2ukunqigt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sufxvd.cn/Article/details/gt2bgcvoltb.html

[N10] 链表节点定义
来源：http://dali.zhiwuduotai.top/Article/details/gt2vravgzgc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ebajgywl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ldfdqjzx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.havefunace.top/Article/details/gt2hswfklbm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zgtxwsxf.html

Java: class Node { int v; Node next; }
来源：http://dali.shzxlz.cn/Article/details/gt2hlgzecwz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.meibo888.top/Article/details/gt2ejuyunsx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jlsjyb.cn/Article/details/gt2lakrvubo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgufenzy.top/Article/details/gt2lcmyuhmo.html

[N11] 二叉树中序遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bpiosdlu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daria6918.cn/Article/details/gt2fzumtyxc.html

PHP:  // 手写递归函数
来源：http://dali.sxryk.cn/Article/details/gt2ejhnfcmu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ubpqdmxu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gt2yfwoawfj.html

Java: // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gt2mrjqooak.html

Go:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gt2ajzxmeox.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuetiantiany.cn/Article/details/gt2iywnzdpl.html

C#:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gt2jfmpvjna.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenzaomai.com/Article/details/gt2vzsxcpyn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xuanzx.com/Article/details/gt2klxmfhom.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ydzc1.top/Article/details/gt2zyrtgmil.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zslixdqs.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gt2ogjnqtkt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gt2zudmgboq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hnqzz.top/Article/details/gt2mgmzicms.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.redwolf501.top/Article/details/gt2sofcnwiv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gt2veepjuzd.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2gnzqlhkt.html

O. 并发与异步
来源：http://dali.dianchejie.cn/Article/details/gt2jkwzgwnt.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2nwsuyuvr.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gt2ystyqelt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jianghu66.top/Article/details/gt2xvfjnzug.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.0kj1m.cn/Article/details/gt2wekfwwzw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hywenlv.cn/Article/details/gt2zkykhklz.html

TS:   // 同 JS
来源：http://dali.daria6918.cn/Article/details/gt2bisqtxsu.html

Java: new Thread(() -> f()).start()
来源：http://dali.sweek.top/Article/details/gt2uzyihyvn.html

Go:   go f()
来源：http://dali.sufxvd.cn/Article/details/gt2zayyyexb.html

Ruby: Thread.new { f }
来源：http://dali.yuanzhike.top/Article/details/gt2wgggzxzi.html

C#:   Task.Run(() => F());
来源：http://dali.hfpthk.cn/Article/details/gt2hdovdhxz.html

[O02] 使用线程池
来源：http://dali.jyoumei.cn/Article/details/gt2ezfiutqq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.9152youxi.cn/Article/details/gt2opnxarzc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhoulong.xyz/Article/details/gt2vtqvjptn.html

JS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gt2hwlyzsdw.html

TS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gt2rzcfjxln.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uviclqca.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhoulong.xyz/Article/details/gt2ajspmvzu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pycfn.com/Article/details/gt2niablnza.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenlongwang.top/Article/details/gt2qrgzykzs.html

[O03] 加锁保护共享数据
来源：http://dali.hammf.cn/Article/details/gt2reffzpmx.html

Py:   with lock: shared += 1
来源：http://dali.kuanghao11.cn/Article/details/gt2qdynvsiq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fengsongda.top/Article/details/gt2lwdmcehk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hammf.cn/Article/details/gt2ypiiknbu.html

TS:   // 同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hyxigrbf.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xjlpnqnh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.iojbl.cn/Article/details/gt2lieizjho.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daria6918.cn/Article/details/gt2hifugjdx.html

C#:   lock (gate) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gt2pghwnfcc.html

[O04] 定义异步函数并等待
来源：http://dali.ehwqpu.com/Article/details/gt2vvmlnwbv.html

Py:   async def f():⏎    await g()
来源：http://dali.dashuyun.cn/Article/details/gt2nsckzvzq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuanzhike.top/Article/details/gt2mnawketk.html

JS:   async function f() { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gt2geubeebi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sclagsbv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigfzy.top/Article/details/gt2poqbyepv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.svipenyu.cn/Article/details/gt2dvcuwmku.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj20258.top/Article/details/gt2ylbthazs.html

C#:   async Task F() { await G(); }
来源：http://dali.yangfankeji.com/Article/details/gt2vaonongp.html

[O05] 并发执行并等待全部完成
来源：http://dali.pengpengdd.cyou/Article/details/gt2ffxmjlur.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sweek.top/Article/details/gt2fobhnbiw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbumsrtn.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigfzy.top/Article/details/gt2llqildhm.html

TS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gt2cssukdrv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhengqikj.top/Article/details/gt2qjigpqpq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zdqjudy.top/Article/details/gt2vnksimzm.html

Ruby: threads.map(&:join)
来源：http://dali.tanke756.top/Article/details/gt2ctaxuiuf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tanke756.top/Article/details/gt2cxckkcfi.html

[O06] 使用进程池
来源：http://dali.cheryme.top/Article/details/gt2vkikxvxz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jlsjyb.cn/Article/details/gt2wikbpxef.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhongyouzk.top/Article/details/gt2vgqlobhv.html

JS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gt2wpxwrwlc.html

TS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gt2oillqyxr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.dashuyun.cn/Article/details/gt2vinrklds.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.bjfxy.top/Article/details/gt2lpnpqmdr.html

Ruby: // fork 块
来源：http://dali.chenjidiqi.icu/Article/details/gt2hokvvneg.html

C#:   Parallel.For
来源：http://dali.birdmap.top/Article/details/gt2plukrqqt.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2fgmznnay.html

P. 常用工具函数
来源：http://dali.yvedp.cn/Article/details/gt2ncsvpjnb.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2vtejylwe.html

[P01] 生成 UUID
来源：http://dali.zhongyouzk.top/Article/details/gt2tzxrxnoi.html

Py:   str(uuid.uuid4())
来源：http://dali.pycfn.com/Article/details/gt2ouninsms.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aizwys.cn/Article/details/gt2miesrgre.html

JS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gt2dphixnqu.html

TS:   crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gt2bycxrmdq.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigfzy.top/Article/details/gt2ezehepml.html

Go:   // 用 github.com/google/uuid
来源：http://dali.snrcjt.cn/Article/details/gt2fpbvbclg.html

Ruby: SecureRandom.uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kiiisdrn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.c1oappe.top/Article/details/gt2xmqpnxpq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sweek.top/Article/details/gt2ytmdjhyr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yueranfly.top/Article/details/gt2aateabku.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gzhubu.top/Article/details/gt2rcdnysce.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ydzc1.top/Article/details/gt2onykxxss.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.iojbl.cn/Article/details/gt2jyoimmnh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gt2deomqpid.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fzhhl.top/Article/details/gt2ltpooret.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fzhhl.top/Article/details/gt2yqlnbxuu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sxryk.cn/Article/details/gt2viedznys.html

[P03] 生成短随机字符串
来源：http://dali.yangfankeji.com/Article/details/gt2jwgymzir.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zsdokzly.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daria6918.cn/Article/details/gt2ngqgemlu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gt2qdgwqvny.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2lpzzofjn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuanzhike.top/Article/details/gt2acvrqped.html


<!-- 参考信息 -->